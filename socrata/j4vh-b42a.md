# Broadway Cycle Track North Of E Union St

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/broadway-cycle-track-north-of-e-union-st-d3751) |
| Metadata | [Link](https://data.seattle.gov/api/views/j4vh-b42a) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/j4vh-b42a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/j4vh-b42a/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | j4vh-b42a |
| Name | Broadway Cycle Track North Of E Union St |
| Attribution | SDOT |
| Category | Transportation |
| Tags | seattle, bike, counts, sdot, monthly data, bicycle, pedestrian |
| Created | 2014-07-24T17:22:33Z |
| Publication Date | 2017-04-03T21:39:12Z |

## Description

The counters consist of two small tube sensors stretching across the street, which are attached to a small metal counting box made by Eco-Counter. The tubes only count people riding bikes. They are very accurate and designed to be used on greenways and cycle tracks.

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                           | Data Type     | Render Type   |
| ======== | ============== | ============================================== | ============================================== | ============= | ============= |
| Yes      | time           | date                                           | Date                                           | calendar_date | calendar_date |
| Yes      | numeric metric | broadway_cycle_track_north_of_e_union_st_total | Broadway Cycle Track North Of E Union St Total | number        | number        |
| No       |                | nb                                             | NB                                             | number        | number        |
| No       |                | sb                                             | SB                                             | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = nb,sb
```

## Data Commands

```ls
series e:j4vh-b42a d:2014-01-01T00:00:00.000Z m:broadway_cycle_track_north_of_e_union_st_total=2

series e:j4vh-b42a d:2014-01-01T01:00:00.000Z m:broadway_cycle_track_north_of_e_union_st_total=13

series e:j4vh-b42a d:2014-01-01T02:00:00.000Z m:broadway_cycle_track_north_of_e_union_st_total=2
```

## Meta Commands

```ls
metric m:broadway_cycle_track_north_of_e_union_st_total p:integer l:"Broadway Cycle Track North Of E Union St Total" t:dataTypeName=number

entity e:j4vh-b42a l:"Broadway Cycle Track North Of E Union St" t:attribution=SDOT t:url=https://data.seattle.gov/api/views/j4vh-b42a

property e:j4vh-b42a t:meta.view v:id=j4vh-b42a v:category=Transportation v:averageRating=0 v:name="Broadway Cycle Track North Of E Union St" v:attribution=SDOT

property e:j4vh-b42a t:meta.view.license v:name="Public Domain"

property e:j4vh-b42a t:meta.view.owner v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:displayName="Zuniga, Rafael"

property e:j4vh-b42a t:meta.view.tableauthor v:id=psms-jbhq v:profileImageUrlMedium=/api/users/psms-jbhq/profile_images/THUMB v:profileImageUrlLarge=/api/users/psms-jbhq/profile_images/LARGE v:screenName="Zuniga, Rafael" v:profileImageUrlSmall=/api/users/psms-jbhq/profile_images/TINY v:roleName=publisher v:displayName="Zuniga, Rafael"
```

## Top Records

```ls
| date                | broadway_cycle_track_north_of_e_union_st_total | nb | sb | 
| =================== | ============================================== | == | == | 
| 2014-01-01T00:00:00 | 2                                              | 0  | 2  | 
| 2014-01-01T01:00:00 | 13                                             | 3  | 10 | 
| 2014-01-01T02:00:00 | 2                                              | 0  | 2  | 
| 2014-01-01T03:00:00 | 0                                              | 0  | 0  | 
| 2014-01-01T04:00:00 | 0                                              | 0  | 0  | 
| 2014-01-01T05:00:00 | 0                                              | 0  | 0  | 
| 2014-01-01T06:00:00 | 2                                              | 0  | 2  | 
| 2014-01-01T07:00:00 | 1                                              | 0  | 1  | 
| 2014-01-01T08:00:00 | 2                                              | 2  | 0  | 
| 2014-01-01T09:00:00 | 0                                              | 0  | 0  | 
```