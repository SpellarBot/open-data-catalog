# 2013 NBPD Bike Counts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-nbpd-bike-counts-52f79) |
| Metadata | [Link](https://data.seattle.gov/api/views/ewwk-ty4e) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ewwk-ty4e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ewwk-ty4e/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ewwk-ty4e |
| Name | 2013 NBPD Bike Counts |
| Attribution | SDOT |
| Category | Transportation |
| Tags | 2013, nbpd, bike, counts, bike counts |
| Created | 2014-09-29T20:46:14Z |
| Publication Date | 2014-09-29T20:50:43Z |

## Description

Detailed Bike quarterly count on the fifty National Bike and Pedestrian Count locations in Seattle. This data set does not show pedestrian counts.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | location   | Location | text      | text        |
| Yes      | numeric metric | jan        | Jan      | number    | number      |
| Yes      | numeric metric | may        | May      | number    | number      |
| Yes      | numeric metric | july       | July     | number    | number      |
| Yes      | numeric metric | sept       | Sept     | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ewwk-ty4e d:2013-01-01T00:00:00.000Z t:location="Linden Ave N and N 130th St" m:may=255 m:sept=186 m:jan=61 m:july=244

series e:ewwk-ty4e d:2013-01-01T00:00:00.000Z t:location="Greenwood Ave N and N 85th St" m:may=103 m:sept=79 m:jan=39 m:july=82

series e:ewwk-ty4e d:2013-01-01T00:00:00.000Z t:location="NE Ravenna Blvd, E Green Lake Way N/NE 71st St" m:may=408 m:sept=492 m:jan=176 m:july=420
```

## Meta Commands

```ls
metric m:jan p:integer l:Jan t:dataTypeName=number

metric m:may p:integer l:May t:dataTypeName=number

metric m:july p:integer l:July t:dataTypeName=number

metric m:sept p:integer l:Sept t:dataTypeName=number

entity e:ewwk-ty4e l:"2013 NBPD Bike Counts" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/ewwk-ty4e

property e:ewwk-ty4e t:meta.view v:id=ewwk-ty4e v:category=Transportation v:averageRating=0 v:name="2013 NBPD Bike Counts" v:attribution=SDOT

property e:ewwk-ty4e t:meta.view.license v:name="Public Domain"

property e:ewwk-ty4e t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:ewwk-ty4e t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| location                                       | jan | may | july | sept | 
| ============================================== | === | === | ==== | ==== | 
| Linden Ave N and N 130th St                    | 61  | 255 | 244  | 186  | 
| Greenwood Ave N and N 85th St                  | 39  | 103 | 82   | 79   | 
| NE Ravenna Blvd, E Green Lake Way N/NE 71st St | 176 | 408 | 420  | 492  | 
| 32nd Ave NW and NW 54th St                     | 81  | 298 | 212  | 258  | 
| NW Market St and 24th Ave NW/Shilshole Ave NW  | 135 | 415 | 481  | 424  | 
| 15th Ave NW and NW Market St                   | 82  | 92  | 73   | 85   | 
| N 45th St and Stone Way N                      | 126 | 328 | 320  | 382  | 
| Lake City Way and NE 125th St                  | 52  | 73  | 109  | 116  | 
| NE Northgate Way and 5th Ave NE                | 36  | 28  | 56   | 51   | 
| 12th Ave NE and NE 65th St                     | 102 | 68  | 151  | 88   | 
```