# William Mead Homes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/william-mead-homes) |
| Metadata | [Link](https://data.lacity.org/api/views/dpg7-s6dp) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/dpg7-s6dp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/dpg7-s6dp/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | dpg7-s6dp |
| Name | William Mead Homes |
| Attribution | HACLA |
| Category | A Livable and Sustainable City |
| Tags | housing authority for the city of los angeles, hacla, locations, public housing, housing, sites |
| Created | 2014-12-08T20:23:26Z |
| Publication Date | 2014-12-08T20:31:32Z |

## Description

2014 Location Demographics

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | ethnic_profile  | Ethnic Profile  | text      | text        |
| Yes      | numeric metric | count           | Count           | number    | number      |
| Yes      | numeric metric | profile_percent | Profile Percent | percent   | percent     |
| Yes      | series tag     | age_sex         | Age/Sex         | text      | text        |
| Yes      | numeric metric | male            | Male            | number    | number      |
| Yes      | numeric metric | female          | Female          | number    | number      |
| Yes      | numeric metric | total           | Total           | number    | number      |
| Yes      | numeric metric | percent         | Percent         | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dpg7-s6dp d:2014-12-08T12:23:29.000Z t:ethnic_profile=Hispanic t:age_sex=0-5 m:total=94 m:percent=8.2 m:count=940 m:female=46 m:male=48 m:profile_percent=81.6

series e:dpg7-s6dp d:2014-12-08T12:23:29.000Z t:ethnic_profile=Black t:age_sex=6-13 m:total=198 m:percent=17.2 m:count=94 m:female=91 m:male=107 m:profile_percent=8.2

series e:dpg7-s6dp d:2014-12-08T12:23:29.000Z t:ethnic_profile=Asian t:age_sex=14-17 m:total=90 m:percent=7.8 m:count=94 m:female=52 m:male=38 m:profile_percent=8.2
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

metric m:profile_percent p:float l:"Profile Percent" t:dataTypeName=percent

metric m:male p:integer l:Male t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

metric m:percent p:float l:Percent t:dataTypeName=percent

entity e:dpg7-s6dp l:"William Mead Homes" t:attribution=HACLA t:url=https://data.lacity.org/api/views/dpg7-s6dp

property e:dpg7-s6dp t:meta.view d:2017-06-09T13:54:29.591Z v:id=dpg7-s6dp v:category="A Livable and Sustainable City" v:averageRating=0 v:name="William Mead Homes" v:attribution=HACLA

property e:dpg7-s6dp t:meta.view.license d:2017-06-09T13:54:29.591Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:dpg7-s6dp t:meta.view.owner d:2017-06-09T13:54:29.591Z v:id=ihg6-62bp v:screenName="Rodd Talebi" v:displayName="Rodd Talebi"

property e:dpg7-s6dp t:meta.view.tableauthor d:2017-06-09T13:54:29.591Z v:id=ihg6-62bp v:screenName="Rodd Talebi" v:displayName="Rodd Talebi"
```

## Top Records

```ls
| :updated_at | ethnic_profile  | count | profile_percent | age_sex | male | female | total | percent | 
| =========== | =============== | ===== | =============== | ======= | ==== | ====== | ===== | ======= | 
| 1418041409  | Hispanic        | 940   | 81.6            | 0-5     | 48   | 46     | 94    | 8.2     | 
| 1418041409  | Black           | 94    | 8.2             | 6-13    | 107  | 91     | 198   | 17.2    | 
| 1418041409  | Asian           | 94    | 8.2             | 14-17   | 38   | 52     | 90    | 7.8     | 
| 1418041409  | Native American | 0     | 0.0             | 18-21   | 52   | 61     | 113   | 9.8     | 
| 1418041409  | Caucasian       | 24    | 2.1             | 22-40   | 78   | 153    | 231   | 20.1    | 
| 1418041409  | Other           | 0     | 0.0             | 41-60   | 70   | 170    | 240   | 20.8    | 
| 1418041409  | Total           | 1152  | 100.0           | 61+     | 56   | 130    | 186   | 16.1    | 
| 1418041409  |                 |       |                 | Total   | 449  | 703    | 1152  | 100.0   | 
```