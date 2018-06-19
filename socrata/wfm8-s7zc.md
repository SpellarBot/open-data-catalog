# Austin Water - Gallons of Water Pumped per Capita

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-gallons-of-water-pumped-per-capita) |
| Metadata | [Link](https://data.austintexas.gov/api/views/wfm8-s7zc) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/wfm8-s7zc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/wfm8-s7zc/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | wfm8-s7zc |
| Name | Austin Water - Gallons of Water Pumped per Capita |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, pumpage, capita |
| Created | 2015-08-24T19:43:27Z |
| Publication Date | 2017-01-11T17:58:41Z |

## Description

Average total gallons of water pumped per capita.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | fiscalyear                 | FiscalYear                 | number    | number      |
| Yes      | numeric metric | pumpage                    | Pumpage                    | number    | number      |
| Yes      | numeric metric | water_service_population   | Water Service Population   | number    | number      |
| Yes      | numeric metric | pumpage_per_capita_per_day | Pumpage per capita per day | number    | number      |
```

## Time Field

```ls
Value = fiscalyear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wfm8-s7zc d:1995-01-01T00:00:00.000Z m:water_service_population=630997 m:pumpage_per_capita_per_day=171 m:pumpage=39485284857

series e:wfm8-s7zc d:1996-01-01T00:00:00.000Z m:water_service_population=649660 m:pumpage_per_capita_per_day=193 m:pumpage=45818995265

series e:wfm8-s7zc d:1997-01-01T00:00:00.000Z m:water_service_population=668876 m:pumpage_per_capita_per_day=175 m:pumpage=42802218906
```

## Meta Commands

```ls
metric m:pumpage p:long l:Pumpage t:dataTypeName=number

metric m:water_service_population p:integer l:"Water Service Population" t:dataTypeName=number

metric m:pumpage_per_capita_per_day p:integer l:"Pumpage per capita per day" t:dataTypeName=number

entity e:wfm8-s7zc l:"Austin Water - Gallons of Water Pumped per Capita" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/wfm8-s7zc

property e:wfm8-s7zc t:meta.view v:id=wfm8-s7zc v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Gallons of Water Pumped per Capita" v:attribution="Austin Water"

property e:wfm8-s7zc t:meta.view.license v:name="Public Domain"

property e:wfm8-s7zc t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:wfm8-s7zc t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| fiscalyear | pumpage     | water_service_population | pumpage_per_capita_per_day | 
| ========== | =========== | ======================== | ========================== | 
| 1995       | 39485284857 | 630997                   | 171                        | 
| 1996       | 45818995265 | 649660                   | 193                        | 
| 1997       | 42802218906 | 668876                   | 175                        | 
| 1998       | 46668518691 | 688660                   | 185                        | 
| 1999       | 46604542023 | 709029                   | 180                        | 
| 2000       | 52326072111 | 738229                   | 194                        | 
| 2001       | 50184846040 | 754470                   | 182                        | 
| 2002       | 50883135913 | 767296                   | 181                        | 
| 2003       | 51110853373 | 774969                   | 180                        | 
| 2004       | 48468969212 | 786594                   | 168                        | 
```