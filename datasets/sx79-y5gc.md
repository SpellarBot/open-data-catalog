# Socrata Help

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/socrata-help) |
| Metadata | [Link](https://data.hartford.gov/api/views/sx79-y5gc) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/sx79-y5gc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/sx79-y5gc/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | sx79-y5gc |
| Name | Socrata Help |
| Attribution | Socrata |
| Tags | help |
| Created | 2014-04-14T19:57:58Z |
| Publication Date | 2014-04-14T19:59:52Z |

## Description

Help with visualizing and using data on data.hartford.gov

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
series e:sx79-y5gc d:2014-04-14T12:58:01.000Z t:description="The dataset catalog is the first thing you see on the socrata site" t:link=http://support.socrata.com/entries/23258642-Navigating-the-Dataset-Catalog t:name="Navigating the Data Catalog" m:row_number.sx79-y5gc=1

series e:sx79-y5gc d:2014-04-14T12:58:01.000Z t:description="What can you do with a data set" t:link=http://support.socrata.com/entries/23288822-Navigating-the-Dataset-Page t:name="Navigating the Data Set Page" m:row_number.sx79-y5gc=2

series e:sx79-y5gc d:2014-04-14T12:58:01.000Z t:description="These video tutorials will show you how to work with a data set" t:link=https://opendata.socrata.com/videos t:name="Start working with the data" m:row_number.sx79-y5gc=3
```

## Meta Commands

```ls
metric m:row_number.sx79-y5gc p:long l:"Row Number"

entity e:sx79-y5gc l:"Socrata Help" t:attribution=Socrata t:url=https://data.hartford.gov/api/views/sx79-y5gc

property e:sx79-y5gc t:meta.view v:id=sx79-y5gc v:attributionLink=http://support.socrata.com/home v:averageRating=0 v:name="Socrata Help" v:attribution=Socrata

property e:sx79-y5gc t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:sx79-y5gc t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| :updated_at | name                         | description                                                        | link                                                                               | 
| =========== | ============================ | ================================================================== | ================================================================================== | 
| 1397480281  | Navigating the Data Catalog  | The dataset catalog is the first thing you see on the socrata site | [http://support.socrata.com/entries/23258642-Navigating-the-Dataset-Catalog, null] | 
| 1397480281  | Navigating the Data Set Page | What can you do with a data set                                    | [http://support.socrata.com/entries/23288822-Navigating-the-Dataset-Page, null]    | 
| 1397480281  | Start working with the data  | These video tutorials will show you how to work with a data set    | [https://opendata.socrata.com/videos, null]                                        | 
```