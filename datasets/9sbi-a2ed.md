# Jobs and Job Growth (2004-Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jobs-and-job-growth-2004-present) |
| Metadata | [Link](https://data.nola.gov/api/views/9sbi-a2ed) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/9sbi-a2ed/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/9sbi-a2ed/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 9sbi-a2ed |
| Name | Jobs and Job Growth (2004-Present) |
| Attribution | Bureau of Labor Statistics |
| Category | Economy and Workforce |
| Tags | resultsnola |
| Created | 2015-10-13T18:34:21Z |
| Publication Date | 2015-10-13T18:44:07Z |

## Description

This data on farm, nonfarm, and total jobs comes from the U.S. Department of Labor, Bureau of Labor Statistics (BLS) and is published on an annual basis. It includes data for the following counties: Orleans Parish, LA (New Orleans); Oklahoma County, OK (Oklahoma City); Hillsborough County, FL (Tampa); Wake County, NC (Raleigh); Fulton County, GA (Atlanta); Miami-Dade County, FL (Miami); Davidson County, TN (Nashville); Shelby County, TN (Memphis); and Jefferson County, KY (Louisville).

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | indicatorname  | IndicatorName  | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
| Yes      | series tag     | indicatorid    | IndicatorID    | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:9sbi-a2ed d:2013-01-01T00:00:00.000Z t:location="Shelby County, TN" t:indicatorid=511 t:rowid="Shelby County, TN_511_2013" t:indicatorname="Farm jobs" m:indicatorvalue=206

series e:9sbi-a2ed d:2013-01-01T00:00:00.000Z t:location="Wake County, NC" t:indicatorid=511 t:rowid="Wake County, NC_511_2013" t:indicatorname="Farm jobs" m:indicatorvalue=877

series e:9sbi-a2ed d:2013-01-01T00:00:00.000Z t:location="Hillsborough County, FL" t:indicatorid=511 t:rowid="Hillsborough County, FL_511_2013" t:indicatorname="Farm jobs" m:indicatorvalue=10145
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:9sbi-a2ed l:"Jobs and Job Growth (2004-Present)" t:attribution="Bureau of Labor Statistics" t:url=https://data.nola.gov/api/views/9sbi-a2ed

property e:9sbi-a2ed t:meta.view v:id=9sbi-a2ed v:category="Economy and Workforce" v:attributionLink=http://www.bls.gov/home.htm v:averageRating=0 v:name="Jobs and Job Growth (2004-Present)" v:attribution="Bureau of Labor Statistics"

property e:9sbi-a2ed t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:9sbi-a2ed t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:9sbi-a2ed t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov v:Public_Access_Level=public
```

## Top Records

```ls
| rowid                                                 | date                | year | location                    | indicatorname | indicatorvalue | indicatorid          | 
| ===================================================== | =================== | ==== | =========================== | ============= | ============== | ==================== | 
| Shelby County, TN_511_2013                            | 2013-01-01T00:00:00 | 2013 | Shelby County, TN           | Farm jobs     | 206            | 511                  | 
| Wake County, NC_511_2013                              | 2013-01-01T00:00:00 | 2013 | Wake County, NC             | Farm jobs     | 877            | 511                  | 
| Hillsborough County, FL_511_2013                      | 2013-01-01T00:00:00 | 2013 | Hillsborough County, FL     | Farm jobs     | 10145          | 511                  | 
| Fulton County, GA_511_2013                            | 2013-01-01T00:00:00 | 2013 | Fulton County, GA           | Farm jobs     | 205            | 511                  | 
| Oklahoma County, OK_511_2013                          | 2013-01-01T00:00:00 | 2013 | Oklahoma County, OK         | Farm jobs     | 158            | 511                  | 
| Davidson County, TN_511_2013                          | 2013-01-01T00:00:00 | 2013 | Davidson County, TN         | Farm jobs     | 300            | 511                  | 
| Orleans Parish, LA_511_2013                           | 2013-01-01T00:00:00 | 2013 | Orleans Parish, LA          | Farm jobs     | 66             | 511                  | 
| Miami-Dade County, FL_511_2013                        | 2013-01-01T00:00:00 | 2013 | Miami-Dade County, FL       | Farm jobs     | 7929           | 511                  | 
| Jefferson County, KY_511_2013                         | 2013-01-01T00:00:00 | 2013 | Jefferson County, KY        | Farm jobs     | 145            | 511                  | 
| East Baton Rouge Parish, LA_Calculation: 010-511_2013 | 2013-01-01T00:00:00 | 2013 | East Baton Rouge Parish, LA | Nonfarm jobs  | 263131.75      | Calculation: 010-511 | 
```