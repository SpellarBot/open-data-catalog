# L&I Public Notes For Affidavit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-public-notes-for-affidavit) |
| Metadata | [Link](https://data.wa.gov/api/views/gs3k-hp7i) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/gs3k-hp7i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/gs3k-hp7i/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | gs3k-hp7i |
| Name | L&I Public Notes For Affidavit |
| Attribution | L & I |
| Category | Labor |
| Tags | contractor, affidavit, notes |
| Created | 2015-10-30T20:39:23Z |
| Publication Date | 2015-12-07T20:08:05Z |

## Description

Public Notes For Affidavit

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| No       |             | id             | ID             | text          | number        |
| Yes      | series tag  | notes          | Notes          | text          | text          |
| Yes      | time        | notesenteredon | NotesEnteredOn | calendar_date | calendar_date |
```

## Time Field

```ls
Value = notesenteredon
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:gs3k-hp7i d:2015-12-09T00:00:00.000Z t:notes="Nordic Project # 15869 WO #01 Harbor Island Safety Fencing" m:row_number.gs3k-hp7i=1

series e:gs3k-hp7i d:2017-05-01T00:00:00.000Z t:notes="-- On 5/18/2016:--
Other Trucks: Lowbed - mobilization of equipment (Teamsters Union)
General Laborer: Laborer Foreman/Supervisor (Laborers Union)
Dump Truck: Broom/Pickup Sweeper (Teamsters Union)" m:row_number.gs3k-hp7i=2

series e:gs3k-hp7i d:2016-08-17T00:00:00.000Z t:notes="Filed by Sarah Wright" m:row_number.gs3k-hp7i=3
```

## Meta Commands

```ls
metric m:row_number.gs3k-hp7i p:long l:"Row Number"

entity e:gs3k-hp7i l:"L&I Public Notes For Affidavit" t:attribution="L & I" t:url=https://data.wa.gov/api/views/gs3k-hp7i

property e:gs3k-hp7i t:meta.view d:2017-09-25T07:28:58.978Z v:averageRating=0 v:name="L&I Public Notes For Affidavit" v:attribution="L & I" v:id=gs3k-hp7i v:category=Labor

property e:gs3k-hp7i t:meta.view.owner d:2017-09-25T07:28:58.978Z v:displayName=Nithya v:lastNotificationSeenAt=1492794743 v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:id=sbxf-tc9c v:screenName=Nithya v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB

property e:gs3k-hp7i t:meta.view.tableauthor d:2017-09-25T07:28:58.978Z v:displayName=Nithya v:lastNotificationSeenAt=1492794743 v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:id=sbxf-tc9c v:screenName=Nithya v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB
```

## Top Records

```ls
| id     | notes                                                                                                                                                                                                 | notesenteredon      | 
| ====== | ===================================================================================================================================================================================================== | =================== | 
| 617191 | Nordic Project # 15869 WO #01 Harbor Island Safety Fencing                                                                                                                                            | 2015-12-09T00:00:00 | 
| 711411 | -- On 5/18/2016:-- Other Trucks: Lowbed - mobilization of equipment (Teamsters Union) General Laborer: Laborer Foreman/Supervisor (Laborers Union) Dump Truck: Broom/Pickup Sweeper (Teamsters Union) | 2017-05-01T00:00:00 | 
| 659834 | Filed by Sarah Wright                                                                                                                                                                                 | 2016-08-17T00:00:00 | 
| 44130  | Filed by Rob Whitmore                                                                                                                                                                                 | 2013-04-19T00:00:00 | 
| 615075 | Station 6 9520 Evergreen Way Everett, WA 98204 Door was stuck shut. Emergency chain was engaged.                                                                                                      | 2015-12-03T00:00:00 | 
| 62492  | This Affidavit should actually be tied to Intent 53047.                                                                                                                                               | 2012-06-26T00:00:00 | 
| 84444  | This Affidavit should actually be tied to Intent 57910.                                                                                                                                               | 2012-06-26T00:00:00 | 
| 90933  | This Affidavit should actually be tied to Intent 44193.                                                                                                                                               | 2012-06-26T00:00:00 | 
| 98505  | This Affidavit is tied to Intent 48002                                                                                                                                                                | 2012-10-03T00:00:00 | 
| 105876 | This Affidavit is tied to Intent 84456                                                                                                                                                                | 2012-08-31T00:00:00 | 
```