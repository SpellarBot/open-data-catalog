# Table 10: Cumulative Sanitary Surveys of Drinking Water Systems

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-10-cumulative-sanitary-surveys-of-drinking-water-systems-21d7f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/x38n-w8un) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/x38n-w8un/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/x38n-w8un/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | x38n-w8un |
| Name | Table 10: Cumulative Sanitary Surveys of Drinking Water Systems |
| Attribution | DOH |
| Category | Health |
| Tags | water, sanitary |
| Created | 2012-07-31T23:53:17Z |
| Publication Date | 2012-07-31T23:54:42Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| No       |                | _                                            | #                                            | number    | number      |
| Yes      | time           | calendar_year                                | Calendar Year                                | number    | text        |
| Yes      | numeric metric | target_sumulative_number_of_systems_surveyed | Target Sumulative Number of Systems Surveyed | number    | number      |
| Yes      | numeric metric | surveys_actually_completed_annually          | Surveys Actually Completed Annually          | number    | number      |
| Yes      | numeric metric | percentage_of_systems_actually_surveyed      | Percentage of Systems Actually Surveyed      | percent   | percent     |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:x38n-w8un d:2007-01-01T00:00:00.000Z m:percentage_of_systems_actually_surveyed=88 m:target_sumulative_number_of_systems_surveyed=26 m:surveys_actually_completed_annually=23

series e:x38n-w8un d:2008-01-01T00:00:00.000Z m:percentage_of_systems_actually_surveyed=60 m:target_sumulative_number_of_systems_surveyed=52 m:surveys_actually_completed_annually=31

series e:x38n-w8un d:2009-01-01T00:00:00.000Z m:percentage_of_systems_actually_surveyed=36 m:target_sumulative_number_of_systems_surveyed=78 m:surveys_actually_completed_annually=28
```

## Meta Commands

```ls
metric m:target_sumulative_number_of_systems_surveyed p:integer l:"Target Sumulative Number of Systems Surveyed" t:dataTypeName=number

metric m:surveys_actually_completed_annually p:integer l:"Surveys Actually Completed Annually" t:dataTypeName=number

metric m:percentage_of_systems_actually_surveyed p:integer l:"Percentage of Systems Actually Surveyed" t:dataTypeName=percent

entity e:x38n-w8un l:"Table 10: Cumulative Sanitary Surveys of Drinking Water Systems" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/x38n-w8un

property e:x38n-w8un t:meta.view v:id=x38n-w8un v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 10: Cumulative Sanitary Surveys of Drinking Water Systems" v:attribution=DOH

property e:x38n-w8un t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:x38n-w8un t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:x38n-w8un t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | target_sumulative_number_of_systems_surveyed | surveys_actually_completed_annually | percentage_of_systems_actually_surveyed | 
| = | ============= | ============================================ | =================================== | ======================================= | 
| 1 | 2007          | 26                                           | 23                                  | 88                                      | 
| 2 | 2008          | 52                                           | 31                                  | 60                                      | 
| 3 | 2009          | 78                                           | 28                                  | 36                                      | 
| 4 | 2010          | 104                                          | 27                                  | 26                                      | 
| 5 | 2011          | 130                                          |                                     |                                         | 
```