# Location of FY 2014 Bus Pads Installed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/location-of-fy-2014-bus-pads-installed) |
| Metadata | [Link](https://data.lacity.org/api/views/msv5-mj8x) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/msv5-mj8x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/msv5-mj8x/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | msv5-mj8x |
| Name | Location of FY 2014 Bus Pads Installed |
| Category | A Livable and Sustainable City |
| Tags | bus, pad, pads, landing, landings, street, services, bss, concrete |
| Created | 2014-05-22T18:49:31Z |
| Publication Date | 2014-05-28T20:25:10Z |

## Description

Locations for concrete bus pads and bus landings installed to date for fiscal year 2014.

## Columns

```ls
| Included | Schema Type | Field Name     | Name                   | Data Type     | Render Type   |
| ======== | =========== | ============== | ====================== | ============= | ============= |
| Yes      | series tag  | cornerp        | Corner Pad             | text          | text          |
| No       |             | datecompletedp | Pad Date Completed     | calendar_date | calendar_date |
| Yes      | series tag  | cornerl        | Corner Landing         | text          | text          |
| Yes      | time        | datecompletedl | Landing Date Completed | calendar_date | calendar_date |
```

## Time Field

```ls
Value = datecompletedl
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = datecompletedp
```

## Data Commands

```ls
series e:msv5-mj8x d:2014-04-11T00:00:00.000Z t:cornerl="NE CORNER" t:cornerp="SW CORNER" m:row_number.msv5-mj8x=1

series e:msv5-mj8x d:2014-05-22T11:49:51.000Z t:cornerp="SE CORNER" m:row_number.msv5-mj8x=2

series e:msv5-mj8x d:2014-05-22T11:49:51.000Z t:cornerp="SE CORNER" m:row_number.msv5-mj8x=3
```

## Meta Commands

```ls
metric m:row_number.msv5-mj8x p:long l:"Row Number"

entity e:msv5-mj8x l:"Location of FY 2014 Bus Pads Installed" t:url=https://data.lacity.org/api/views/msv5-mj8x

property e:msv5-mj8x t:meta.view v:id=msv5-mj8x v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Location of FY 2014 Bus Pads Installed"

property e:msv5-mj8x t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:msv5-mj8x t:meta.view.owner v:id=awhe-qmys v:screenName=CJ v:displayName=CJ

property e:msv5-mj8x t:meta.view.tableauthor v:id=awhe-qmys v:screenName=CJ v:displayName=CJ
```

## Top Records

```ls
| cornerp   | datecompletedp      | cornerl   | datecompletedl      | 
| ========= | =================== | ========= | =================== | 
| SW CORNER | 2014-04-16T00:00:00 | NE CORNER | 2014-04-11T00:00:00 | 
| SE CORNER | 2014-03-29T00:00:00 |           |                     | 
| SE CORNER | 2013-10-05T00:00:00 |           |                     | 
|           |                     | NE CORNER | 2013-07-12T00:00:00 | 
|           |                     | NE CORNER | 2013-12-03T00:00:00 | 
|           |                     | SW CORNER | 2013-12-06T00:00:00 | 
| SE CORNER | 2013-09-21T00:00:00 |           |                     | 
|           |                     | NE CORNER | 2014-04-29T00:00:00 | 
| SE CORNER | 2014-03-22T00:00:00 |           |                     | 
|           |                     | SE CORNER | 2013-07-30T00:00:00 | 
```