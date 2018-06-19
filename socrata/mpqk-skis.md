# Emergency Food Assistance Program (Quarterly Report)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/emergency-food-assistance-program-quarterly-report-e5adf) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mpqk-skis) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mpqk-skis/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mpqk-skis/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mpqk-skis |
| Name | Emergency Food Assistance Program (Quarterly Report) |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | emergency food assistance program (quarterly report), hra, human resources, reporting, food, services |
| Created | 2013-05-17T17:13:31Z |
| Publication Date | 2013-05-17T17:17:40Z |

## Description

Quarterly report showing the number of individuals served meals in food pantries and soup kitchens.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | facility         | Facility         | text      | text        |
| Yes      | numeric metric | oct_dec_2012     | Oct-Dec 2012     | number    | text        |
| Yes      | numeric metric | jul_sep_2012     | Jul-Sep 2012     | number    | text        |
| Yes      | series tag     | quarterly_change | Quarterly Change | text      | text        |
| Yes      | numeric metric | oct_dec_2011     | Oct-Dec 2011     | number    | text        |
| Yes      | series tag     | yearly_change    | Yearly Change    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mpqk-skis d:2013-05-17T10:13:48.000Z t:quarterly_change=22% t:facility="Food Pantries (Individuals Served)" t:yearly_change=6% m:oct_dec_2012=2734453 m:oct_dec_2011=2587785 m:jul_sep_2012=2235270

series e:mpqk-skis d:2013-05-17T10:13:48.000Z t:quarterly_change=5% t:facility="Soup Kitchens ( meals served)" t:yearly_change=3% m:oct_dec_2012=838315 m:oct_dec_2011=811222 m:jul_sep_2012=799640
```

## Meta Commands

```ls
metric m:oct_dec_2012 p:long l:"Oct-Dec 2012" t:dataTypeName=number

metric m:jul_sep_2012 p:long l:"Jul-Sep 2012" t:dataTypeName=number

metric m:oct_dec_2011 p:long l:"Oct-Dec 2011" t:dataTypeName=number

entity e:mpqk-skis l:"Emergency Food Assistance Program (Quarterly Report)" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/mpqk-skis

property e:mpqk-skis t:meta.view v:id=mpqk-skis v:category="Social Services" v:averageRating=0 v:name="Emergency Food Assistance Program (Quarterly Report)" v:attribution="Human Resources Administration (HRA)"

property e:mpqk-skis t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mpqk-skis t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | facility                           | oct_dec_2012 | jul_sep_2012 | quarterly_change | oct_dec_2011 | yearly_change | 
| =========== | ================================== | ============ | ============ | ================ | ============ | ============= | 
| 1368785628  | Food Pantries (Individuals Served) | 2,734,453    | 2,235,270    | 22%              | 2,587,785    | 6%            | 
| 1368785628  | Soup Kitchens ( meals served)      | 838,315      | 799,640      | 5%               | 811,222      | 3%            | 
```