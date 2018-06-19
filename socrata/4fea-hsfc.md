# Connecticut Open Data Tutorials

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connecticut-open-data-tutorials) |
| Metadata | [Link](https://data.ct.gov/api/views/4fea-hsfc) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/4fea-hsfc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/4fea-hsfc/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 4fea-hsfc |
| Name | Connecticut Open Data Tutorials |
| Tags | help, tutorial, vidoes |
| Created | 2014-03-19T19:11:24Z |
| Publication Date | 2017-02-21T19:33:03Z |

## Description

Links to videos to help users get started using the Connecticut Open Data portal and the Socrata platform.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | name        | Name        | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
| Yes      | series tag  | link        | Link        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4fea-hsfc d:2014-03-19T12:14:49.000Z t:description="The dataset catalog is typically the first thing you see on a Socrata site, so what does everything mean on the catalog page?" t:link=http://support.socrata.com/entries/23258642-Navigating-the-Dataset-Catalog t:name="Navigating the Data Catalog" m:row_number.4fea-hsfc=1

series e:4fea-hsfc d:2014-03-19T12:15:26.000Z t:description="Once you have found an interesting dataset, chart, or map to look at, what can you do on the page?" t:link=http://support.socrata.com/entries/23288822-Navigating-the-Dataset-Page t:name="Navigating the Dataset Page" m:row_number.4fea-hsfc=2

series e:4fea-hsfc d:2016-06-27T08:33:34.000Z t:description="A guidance document and tutorial for data publishers" t:link=https://data.ct.gov/dataset/CT-Open-Data-Portal-Publisher-Guide/bktc-8u9h t:name="Open Data Publishers Guide" m:row_number.4fea-hsfc=3
```

## Meta Commands

```ls
metric m:row_number.4fea-hsfc p:long l:"Row Number"

entity e:4fea-hsfc l:"Connecticut Open Data Tutorials" t:url=https://data.ct.gov/api/views/4fea-hsfc

property e:4fea-hsfc t:meta.view v:id=4fea-hsfc v:averageRating=0 v:name="Connecticut Open Data Tutorials"

property e:4fea-hsfc t:meta.view.license v:name="Public Domain"

property e:4fea-hsfc t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:4fea-hsfc t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | name                              | description                                                                                                                   | link                                                                               | 
| =========== | ================================= | ============================================================================================================================= | ================================================================================== | 
| 1395231289  | Navigating the Data Catalog       | The dataset catalog is typically the first thing you see on a Socrata site, so what does everything mean on the catalog page? | [http://support.socrata.com/entries/23258642-Navigating-the-Dataset-Catalog, null] | 
| 1395231326  | Navigating the Dataset Page       | Once you have found an interesting dataset, chart, or map to look at, what can you do on the page?                            | [http://support.socrata.com/entries/23288822-Navigating-the-Dataset-Page, null]    | 
| 1467016414  | Open Data Publishers Guide        | A guidance document and tutorial for data publishers                                                                          | [https://data.ct.gov/dataset/CT-Open-Data-Portal-Publisher-Guide/bktc-8u9h, null]  | 
| 1467016537  | Importing a Dataset               | A quick video tutorial for importing data into the Open Data Portal                                                           | [https://opendata.socrata.com/videos#import-dataset, null]                         | 
| 1467016596  | Publishing a dataset              | A quick video tutorial for publishing open data                                                                               | [https://opendata.socrata.com/videos#dataset-publication, null]                    | 
| 1487705566  | Now start working with a data set | These video tutorial will help you serach, sort, chart, and map the data set you are interested in                            | [https://data.ct.gov/videos, null]                                                 | 
```