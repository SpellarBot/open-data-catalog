# Citywide Cash Assistance Cases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/citywide-cash-assistance-cases) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9jbx-hna8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9jbx-hna8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9jbx-hna8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9jbx-hna8 |
| Name | Citywide Cash Assistance Cases |
| Attribution | Human Resource Administration (HRA) |
| Category | Social Services |
| Created | 2016-01-14T17:37:20Z |
| Publication Date | 2016-11-04T14:06:33Z |

## Description

Total number of cases on Cash Assistance, including breakdown by major categories.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                   | Data Type | Render Type |
| ======== | ============== | ==================================== | ====================================== | ========= | =========== |
| Yes      | time           | month                                | Month                                  | text      | text        |
| Yes      | numeric metric | family_assistance_cases              | Family Assistance Cases                | number    | number      |
| Yes      | numeric metric | safety_net_assistance_cases          | Safety Net Assistance Cases            | number    | number      |
| Yes      | numeric metric | 60_mo_converted_to_sn_cases          | 60 Mo. Converted to SN Cases           | number    | number      |
| Yes      | numeric metric | total_cash_assistance_cases_citywide | Total Cash Assistance Cases (Citywide) | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:9jbx-hna8 d:2007-01-01T00:00:00.000Z m:family_assistance_cases=75451 m:60_mo_converted_to_sn_cases=27918 m:total_cash_assistance_cases_citywide=193748 m:safety_net_assistance_cases=90379

series e:9jbx-hna8 d:2007-02-01T00:00:00.000Z m:family_assistance_cases=73613 m:60_mo_converted_to_sn_cases=27493 m:total_cash_assistance_cases_citywide=190000 m:safety_net_assistance_cases=88894

series e:9jbx-hna8 d:2007-03-01T00:00:00.000Z m:family_assistance_cases=73219 m:60_mo_converted_to_sn_cases=27162 m:total_cash_assistance_cases_citywide=190417 m:safety_net_assistance_cases=90036
```

## Meta Commands

```ls
metric m:family_assistance_cases p:integer l:"Family Assistance Cases" t:dataTypeName=number

metric m:safety_net_assistance_cases p:integer l:"Safety Net Assistance Cases" t:dataTypeName=number

metric m:60_mo_converted_to_sn_cases p:integer l:"60 Mo. Converted to SN Cases" t:dataTypeName=number

metric m:total_cash_assistance_cases_citywide p:integer l:"Total Cash Assistance Cases (Citywide)" t:dataTypeName=number

entity e:9jbx-hna8 l:"Citywide Cash Assistance Cases" t:attribution="Human Resource Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/9jbx-hna8

property e:9jbx-hna8 t:meta.view v:id=9jbx-hna8 v:category="Social Services" v:averageRating=0 v:name="Citywide Cash Assistance Cases" v:attribution="Human Resource Administration (HRA)"

property e:9jbx-hna8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9jbx-hna8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| month  | family_assistance_cases | safety_net_assistance_cases | 60_mo_converted_to_sn_cases | total_cash_assistance_cases_citywide | 
| ====== | ======================= | =========================== | =========================== | ==================================== | 
| Jan-07 | 75451                   | 90379                       | 27918                       | 193748                               | 
| Feb-07 | 73613                   | 88894                       | 27493                       | 190000                               | 
| Mar-07 | 73219                   | 90036                       | 27162                       | 190417                               | 
| Apr-07 | 72191                   | 88984                       | 26855                       | 188030                               | 
| May-07 | 72106                   | 89739                       | 26799                       | 188644                               | 
| Jun-07 | 71527                   | 88285                       | 27259                       | 187071                               | 
| Jul-07 | 73462                   | 82175                       | 30740                       | 186377                               | 
| Aug-07 | 73263                   | 81970                       | 30439                       | 185672                               | 
| Sep-07 | 72390                   | 79926                       | 29800                       | 182116                               | 
| Oct-07 | 73202                   | 81950                       | 29928                       | 185080                               | 
```