# Time Series Socrata Datasets

## Overview

The list contains [U.S. Government open data](http://www.data.gov/) datasets with a **time-series** dimension.

The total number of entries is **7,190** out of **280,000** available in the [catalog](https://catalog.data.gov) and includes only datasets published in the [Socrata](https://dev.socrata.com/docs/formats) format.

The listing is grouped by reporting agency (host), category, and catalog tag:

* [Reporting Agencies](./data-hosts/README.md)
* [Categories](./data-categories/README.md)
* [Catalog tags](./data-tags/README.md)

## Analyzing Data

To analyze a dataset with SQL queries you can automatically load it into Axibase Time Series Database (ATSD), a non-relational database optimized for storing and analyzing time-series data.

Install [Docker](https://docs.docker.com/engine/installation/).

Download the [`docker-compose.yml`](./resources/docker-compose.yml) file.

```bash
curl -o docker-compose.yml \
  https://raw.githubusercontent.com/axibase/open-data-catalog/master/resources/docker-compose.yml
```

Launch ATSD and Axibase Collector containers and specify the URL to the dataset in the `DATASET_URL` variable.

For this walk-through, the dataset is [Seattle City Budget](./datasets/socrata/55z8-f4gi.md) and the URL is provided in the **Data: JSON** field.

```elm
https://data.seattle.gov/api/views/55z8-f4gi/rows.json
```

Remove the `?max_rows=100` parameter from the URL to load the entire dataset.

```bash
export DATASET_URL=https://data.seattle.gov/api/views/55z8-f4gi/rows.json; \
docker-compose up -d
```

Watch for **ATSD start completed** message in the start log.

```bash
docker logs -f atsd
```

```txt
[ATSD] ATSD user interface:
[ATSD] http://172.18.0.2:8088
[ATSD] https://172.18.0.2:8443
[ATSD] ATSD start completed. Time: 2018-06-25 11-03-12.
[ATSD] Collector account 'myuser' created. Type: 'api-rw'.
```

Login into ATSD web interface on port `8443` (https).

Open **Entities** tab in the main menu, locate the `55z8-f4gi` entity which refers to dataset identifier in the `DATASET_URL` variable and click **Metrics** to view a list of metrics collected in this dataset.

![](./resources/dataset-entity.png)

Choose one of the available metrics and click **Series** icon to open a list of all series collected for this entity and metric.

![](./resources/dataset-metrics.png)

![](./resources/dataset-series.png)

Select a series and open the **Series Statistics** page. The page contains summary information about the series including metadata published by the reporting agency.

![](./resources/dataset-series-statistics.png)

Click **SQL** to open the **SQL Console** with a sample pre-generated query that selects last 100 values for the given series.

![](./resources/dataset-series-query.png)

Customize the query to produce an analytical report, for example:

```sql
SELECT tags."department", SUM(value)/1000000 AS "Total, $M"
  FROM "proposed_2011_expenditure_allowance"
 WHERE entity = '55z8-f4gi'
GROUP BY tags."department"
  ORDER BY SUM(value) DESC
```

Review the results which can be also exported in CSV and Excel formats.

```ls
| tags.department                       | Total, $M |
|---------------------------------------|-----------|
| Seattle City Light                    | 1087.5    |
| Seattle Public Utilities              | 823.9     |
| Finance General                       | 358.9     |
| Seattle Department of Transportation  | 322.0     |
| Seattle Police Department             | 248.5     |
```

![](./resources/sql-console.png)

Review [SQL syntax](https://axibase.com/docs/atsd/) and [SQL examples](https://axibase.com/docs/atsd/sql/examples/) in ATSD documentation for insights and ideas on how to analyze the data.