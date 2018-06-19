# Distribution of Force Allegations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/distribution-of-force-allegations-10773) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7ujc-hpzg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7ujc-hpzg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7ujc-hpzg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7ujc-hpzg |
| Name | Distribution of Force Allegations |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, allegations, distribution |
| Created | 2013-02-26T18:26:51Z |
| Publication Date | 2013-06-21T20:06:49Z |

## Description

This table represents the distribution of force allegations

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                  | Data Type | Render Type |
| ======== | ============== | ================================= | ===================================== | ========= | =========== |
| Yes      | time           | year                              | Year                                  | number    | text        |
| Yes      | numeric metric | animal                            | Animal                                | number    | text        |
| Yes      | numeric metric | chokehold                         | Chokehold                             | number    | text        |
| Yes      | numeric metric | flashlight_as_club                | Flashlight as club                    | number    | text        |
| Yes      | numeric metric | gun_as_club                       | Gun as club                           | number    | text        |
| Yes      | numeric metric | gun_fired                         | Gun fired                             | number    | text        |
| Yes      | numeric metric | gun_pointed                       | Gun pointed                           | number    | text        |
| Yes      | numeric metric | handcuffs_too_tight               | Handcuffs too tight                   | number    | text        |
| Yes      | numeric metric | hit_against_inanimate_object      | Hit against inanimate object          | number    | text        |
| Yes      | numeric metric | nightstick_as_club_incl_asp_baton | Nightstick as club (incl asp & baton) | number    | text        |
| Yes      | numeric metric | nonlethal_restraining_device      | Nonlethal restraining device          | number    | text        |
| Yes      | numeric metric | other_blunt_instrument_as_club    | Other blunt instrument as club        | number    | text        |
| Yes      | numeric metric | pepper_spray                      | Pepper spray                          | number    | text        |
| Yes      | numeric metric | physical_force                    | Physical force                        | number    | text        |
| Yes      | numeric metric | police_shield                     | Police shield                         | number    | text        |
| Yes      | numeric metric | radio_as_club                     | Radio as Club                         | number    | text        |
| Yes      | numeric metric | vehicle                           | Vehicle                               | number    | text        |
| Yes      | numeric metric | other_form_of_force               | Other form of Force                   | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7ujc-hpzg d:2009-01-01T00:00:00.000Z m:nightstick_as_club_incl_asp_baton=364 m:other_form_of_force=36 m:pepper_spray=342 m:vehicle=26 m:gun_pointed=313 m:gun_fired=24 m:chokehold=244 m:handcuffs_too_tight=71 m:nonlethal_restraining_device=30 m:physical_force=4612 m:hit_against_inanimate_object=183 m:gun_as_club=33 m:flashlight_as_club=11 m:radio_as_club=46 m:other_blunt_instrument_as_club=54 m:police_shield=15 m:animal=0

series e:7ujc-hpzg d:2010-01-01T00:00:00.000Z m:nightstick_as_club_incl_asp_baton=306 m:other_form_of_force=29 m:pepper_spray=287 m:vehicle=28 m:gun_pointed=302 m:gun_fired=17 m:chokehold=215 m:handcuffs_too_tight=44 m:nonlethal_restraining_device=31 m:physical_force=3787 m:hit_against_inanimate_object=137 m:gun_as_club=25 m:flashlight_as_club=11 m:radio_as_club=26 m:other_blunt_instrument_as_club=45 m:police_shield=8 m:animal=0

series e:7ujc-hpzg d:2011-01-01T00:00:00.000Z m:nightstick_as_club_incl_asp_baton=300 m:other_form_of_force=19 m:pepper_spray=319 m:vehicle=35 m:gun_pointed=318 m:gun_fired=17 m:chokehold=186 m:handcuffs_too_tight=56 m:nonlethal_restraining_device=25 m:physical_force=3660 m:hit_against_inanimate_object=182 m:gun_as_club=36 m:flashlight_as_club=20 m:radio_as_club=31 m:other_blunt_instrument_as_club=66 m:police_shield=8 m:animal=5
```

## Meta Commands

```ls
metric m:animal p:integer l:Animal t:dataTypeName=number

metric m:chokehold p:integer l:Chokehold t:dataTypeName=number

metric m:flashlight_as_club p:integer l:"Flashlight as club" t:dataTypeName=number

metric m:gun_as_club p:integer l:"Gun as club" t:dataTypeName=number

metric m:gun_fired p:integer l:"Gun fired" t:dataTypeName=number

metric m:gun_pointed p:integer l:"Gun pointed" t:dataTypeName=number

metric m:handcuffs_too_tight p:integer l:"Handcuffs too tight" t:dataTypeName=number

metric m:hit_against_inanimate_object p:integer l:"Hit against inanimate object" t:dataTypeName=number

metric m:nightstick_as_club_incl_asp_baton p:integer l:"Nightstick as club (incl asp & baton)" t:dataTypeName=number

metric m:nonlethal_restraining_device p:integer l:"Nonlethal restraining device" t:dataTypeName=number

metric m:other_blunt_instrument_as_club p:integer l:"Other blunt instrument as club" t:dataTypeName=number

metric m:pepper_spray p:integer l:"Pepper spray" t:dataTypeName=number

metric m:physical_force p:integer l:"Physical force" t:dataTypeName=number

metric m:police_shield p:integer l:"Police shield" t:dataTypeName=number

metric m:radio_as_club p:integer l:"Radio as Club" t:dataTypeName=number

metric m:vehicle p:integer l:Vehicle t:dataTypeName=number

metric m:other_form_of_force p:integer l:"Other form of Force" t:dataTypeName=number

entity e:7ujc-hpzg l:"Distribution of Force Allegations" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/7ujc-hpzg

property e:7ujc-hpzg t:meta.view v:id=7ujc-hpzg v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Distribution of Force Allegations" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:7ujc-hpzg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7ujc-hpzg t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | animal | chokehold | flashlight_as_club | gun_as_club | gun_fired | gun_pointed | handcuffs_too_tight | hit_against_inanimate_object | nightstick_as_club_incl_asp_baton | nonlethal_restraining_device | other_blunt_instrument_as_club | pepper_spray | physical_force | police_shield | radio_as_club | vehicle | other_form_of_force | 
| ==== | ====== | ========= | ================== | =========== | ========= | =========== | =================== | ============================ | ================================= | ============================ | ============================== | ============ | ============== | ============= | ============= | ======= | =================== | 
| 2009 | 0      | 244       | 11                 | 33          | 24        | 313         | 71                  | 183                          | 364                               | 30                           | 54                             | 342          | 4612           | 15            | 46            | 26      | 36                  | 
| 2010 | 0      | 215       | 11                 | 25          | 17        | 302         | 44                  | 137                          | 306                               | 31                           | 45                             | 287          | 3787           | 8             | 26            | 28      | 29                  | 
| 2011 | 5      | 186       | 20                 | 36          | 17        | 318         | 56                  | 182                          | 300                               | 25                           | 66                             | 319          | 3660           | 8             | 31            | 35      | 19                  | 
```