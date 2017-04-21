# Open Data Initiative Progress Report - Participation Sprint

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-data-initiative-progress-report-participation-sprint) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8qty-vat2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8qty-vat2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8qty-vat2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8qty-vat2 |
| Name | Open Data Initiative Progress Report - Participation Sprint |
| Category | Government |
| Created | 2015-08-17T01:21:03Z |
| Publication Date | 2015-11-02T21:46:46Z |

## Description

The City Manager's Open Data Initiative 2.0 kicked off in May 2015 with a 90-day "sprint-style" project designed to increase the amount of open data published by each City department. Departments were asked to 1) designate an open data liaison, 2) conduct a data inventory, 3) submit an open data participation plan, and 4) publish at least three new datasets to the City's open data portal. Departments continue to work with CTM to meet these goals, and we will update this dataset regularly to reflect their progress until further notice.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | dept        | dept        | text      | text        |
| Yes      | series tag  | liaison     | liaison     | text      | text        |
| Yes      | series tag  | inventory   | inventory   | text      | text        |
| Yes      | series tag  | plans       | plans       | text      | text        |
| Yes      | series tag  | publication | publication | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8qty-vat2 d:2015-08-16T18:21:05.000Z t:plans="not yet" t:liaison=completed t:inventory="in progress" t:dept="Animal Services" t:publication=unknown m:row_number.8qty-vat2=1

series e:8qty-vat2 d:2015-08-16T18:21:05.000Z t:plans=submitted t:liaison=completed t:inventory=submitted t:dept="Austin Code" t:publication=completed m:row_number.8qty-vat2=2

series e:8qty-vat2 d:2015-08-16T18:21:05.000Z t:plans=submitted t:liaison=completed t:inventory=submitted t:dept="Austin Convention Center" t:publication=completed m:row_number.8qty-vat2=3
```

## Meta Commands

```ls
metric m:row_number.8qty-vat2 p:long l:"Row Number"

entity e:8qty-vat2 l:"Open Data Initiative Progress Report - Participation Sprint" t:url=https://data.austintexas.gov/api/views/8qty-vat2

property e:8qty-vat2 t:meta.view v:id=8qty-vat2 v:category=Government v:averageRating=0 v:name="Open Data Initiative Progress Report - Participation Sprint"

property e:8qty-vat2 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8qty-vat2 t:meta.view.owner v:id=pqf2-ayrv v:screenName="Hailey Pate" v:displayName="Hailey Pate"

property e:8qty-vat2 t:meta.view.tableauthor v:id=pqf2-ayrv v:screenName="Hailey Pate" v:roleName=administrator v:displayName="Hailey Pate"
```

## Top Records

```ls
| :updated_at | dept                     | liaison   | inventory   | plans     | publication | 
| =========== | ======================== | ========= | =========== | ========= | =========== | 
| 1439749265  | Animal Services          | completed | in progress | not yet   | unknown     | 
| 1439749265  | Austin Code              | completed | submitted   | submitted | completed   | 
| 1439749265  | Austin Convention Center | completed | submitted   | submitted | completed   | 
| 1439749265  | Austin Energy            | completed | submitted   | submitted | completed   | 
| 1439749265  | Austin Public Library    | completed | submitted   | submitted | completed   | 
| 1439749265  | Austin Resource Recovery | completed | submitted   | submitted | completed   | 
| 1439749265  | Austin Transportation    | completed | submitted   | submitted | completed   | 
| 1439749265  | Aviation                 | completed | submitted   | submitted | completed   | 
| 1439749265  | Building Services        | completed | submitted   | submitted | completed   | 
| 1439749265  | Capital Planning Office  | completed | submitted   | submitted | unknown     | 
```