# 26th Ave SW Greenway at SW Oregon St

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/26th-ave-sw-greenway-at-sw-oregon-st-2bbd7) |
| Metadata | [Link](https://data.seattle.gov/api/views/mefu-7eau) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/mefu-7eau/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/mefu-7eau/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | mefu-7eau |
| Name | 26th Ave SW Greenway at SW Oregon St |
| Attribution | SDOT |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, monthly data, bicycle, pedestrian |
| Created | 2014-02-04T16:31:41Z |
| Publication Date | 2017-04-03T21:51:18Z |

## Description

The counters consist of two small tube sensors stretching across the street, which are attached to a small metal counting box made by Eco-Counter. The tubes only count people riding bikes. They are very accurate and designed to be used on greenways.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================== | ========================================== | ============= | ============= |
| Yes      | time           | date                                       | Date                                       | calendar_date | calendar_date |
| Yes      | numeric metric | 26th_ave_sw_greenway_at_sw_oregon_st_total | 26th Ave SW Greenway at SW Oregon St Total | number        | number        |
| Yes      | numeric metric | north                                      | North                                      | number        | number        |
| Yes      | numeric metric | south                                      | South                                      | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mefu-7eau d:2014-01-01T00:00:00.000Z m:south=0 m:north=2 m:26th_ave_sw_greenway_at_sw_oregon_st_total=2

series e:mefu-7eau d:2014-01-01T01:00:00.000Z m:south=6 m:north=0 m:26th_ave_sw_greenway_at_sw_oregon_st_total=6

series e:mefu-7eau d:2014-01-01T02:00:00.000Z m:south=4 m:north=1 m:26th_ave_sw_greenway_at_sw_oregon_st_total=5
```

## Meta Commands

```ls
metric m:26th_ave_sw_greenway_at_sw_oregon_st_total p:integer l:"26th Ave SW Greenway at SW Oregon St Total" t:dataTypeName=number

metric m:north p:integer l:North t:dataTypeName=number

metric m:south p:integer l:South t:dataTypeName=number

entity e:mefu-7eau l:"26th Ave SW Greenway at SW Oregon St" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/mefu-7eau

property e:mefu-7eau t:meta.view v:id=mefu-7eau v:category=Transportation v:averageRating=0 v:name="26th Ave SW Greenway at SW Oregon St" v:attribution=SDOT

property e:mefu-7eau t:meta.view.license v:name="Public Domain"

property e:mefu-7eau t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:mefu-7eau t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | 26th_ave_sw_greenway_at_sw_oregon_st_total | north | south | 
| =================== | ========================================== | ===== | ===== | 
| 2014-01-01T00:00:00 | 2                                          | 2     | 0     | 
| 2014-01-01T01:00:00 | 6                                          | 0     | 6     | 
| 2014-01-01T02:00:00 | 5                                          | 1     | 4     | 
| 2014-01-01T03:00:00 | 1                                          | 1     | 0     | 
| 2014-01-01T04:00:00 | 3                                          | 1     | 2     | 
| 2014-01-01T05:00:00 | 0                                          | 0     | 0     | 
| 2014-01-01T06:00:00 | 0                                          | 0     | 0     | 
| 2014-01-01T07:00:00 | 0                                          | 0     | 0     | 
| 2014-01-01T08:00:00 | 0                                          | 0     | 0     | 
| 2014-01-01T09:00:00 | 4                                          | 2     | 2     | 
```