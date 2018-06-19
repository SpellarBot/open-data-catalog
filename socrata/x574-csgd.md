# L&I Public Notes For Intent

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/li-public-notes-for-intent) |
| Metadata | [Link](https://data.wa.gov/api/views/x574-csgd) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/x574-csgd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/x574-csgd/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | x574-csgd |
| Name | L&I Public Notes For Intent |
| Attribution | L&I |
| Category | Labor |
| Tags | contractor, intent, notes |
| Created | 2015-12-03T19:22:02Z |
| Publication Date | 2015-12-04T22:36:40Z |

## Description

Public Notes For Approved Intent

## Columns

```ls
| Included | Schema Type | Field Name   | Name                  | Data Type     | Render Type   |
| ======== | =========== | ============ | ===================== | ============= | ============= |
| Yes      | series tag  | intent_id    | Intent ID Number      | text          | number        |
| Yes      | series tag  | text_data    | Intent Notes Section  | text          | text          |
| Yes      | time        | comment_date | Date Note Was Entered | calendar_date | calendar_date |
```

## Time Field

```ls
Value = comment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:x574-csgd d:2011-03-02T00:00:00.000Z t:text_data="6444 Dana Apts. 10902 Freiday #1-8 Lakewood, WA 98499
6438 Stegman 11813 28th Ave. E Tacoma, WA 98445
6476 Adamiec 13906 215th Ave. E Bonney Lake, WA 98391" t:intent_id=334642 m:row_number.x574-csgd=1

series e:x574-csgd d:2011-03-02T00:00:00.000Z t:text_data="Project scope to include installation of sprinkler system and plantings.  Equipment to be used:  backhoe under 90 hp and loader under 50 hp." t:intent_id=445542 m:row_number.x574-csgd=2

series e:x574-csgd d:2016-01-12T00:00:00.000Z t:text_data="1-Install bath fan and two light fixtures; repair wiring
2-yes
3-1
4-a)no, b)no, c)yes, d-k)no
5-yes
6-yes
7-no
8-no" t:intent_id=741255 m:row_number.x574-csgd=3
```

## Meta Commands

```ls
metric m:row_number.x574-csgd p:long l:"Row Number"

entity e:x574-csgd l:"L&I Public Notes For Intent" t:attribution=L&I t:url=https://data.wa.gov/api/views/x574-csgd

property e:x574-csgd t:meta.view v:id=x574-csgd v:category=Labor v:averageRating=0 v:name="L&I Public Notes For Intent" v:attribution=L&I

property e:x574-csgd t:meta.view.owner v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:displayName=Nithya

property e:x574-csgd t:meta.view.tableauthor v:id=sbxf-tc9c v:profileImageUrlMedium=/api/users/sbxf-tc9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/sbxf-tc9c/profile_images/LARGE v:screenName=Nithya v:profileImageUrlSmall=/api/users/sbxf-tc9c/profile_images/TINY v:roleName=publisher v:displayName=Nithya
```

## Top Records

```ls
| intent_id | text_data                                                                                                                                                                                                                                     | comment_date        | 
| ========= | ============================================================================================================================================================================================================================================= | =================== | 
| 334642    | 6444 Dana Apts. 10902 Freiday #1-8 Lakewood, WA 98499 6438 Stegman 11813 28th Ave. E Tacoma, WA 98445 6476 Adamiec 13906 215th Ave. E Bonney Lake, WA 98391                                                                                   | 2011-03-02T00:00:00 | 
| 445542    | Project scope to include installation of sprinkler system and plantings. Equipment to be used: backhoe under 90 hp and loader under 50 hp.                                                                                                    | 2011-03-02T00:00:00 | 
| 741255    | 1-Install bath fan and two light fixtures; repair wiring 2-yes 3-1 4-a)no, b)no, c)yes, d-k)no 5-yes 6-yes 7-no 8-no                                                                                                                          | 2016-01-12T00:00:00 | 
| 445846    | Rockwell Apts: 14502 E Rockwell, Spokane Valley 99216; 14503 E Rockwell Ave Spokane Valley, 99216; 14517 E Rockwell Ave, Spokane Valley 99216; 14526 E Rockwell Ave, Spokane Valley 99216                                                     | 2011-03-04T00:00:00 | 
| 445827    | I am working with Beatriz Hart,Industrial Relations Agent, in the Bellevue office. This Intent covers 1 year and is for multiple sites including fire stations, city offices, bus barn, library, performing arts center, police station, etc. | 2011-03-04T00:00:00 | 
| 334441    | All info has been given to Bob Kushman                                                                                                                                                                                                        | 2011-03-04T00:00:00 | 
| 445895    | Allene Mills 4311 Jenkins Place Montesano WA 98563                                                                                                                                                                                            | 2011-03-04T00:00:00 | 
| 445978    | NA                                                                                                                                                                                                                                            | 2011-03-07T00:00:00 | 
| 316090    | HYDROSEEDING STRIPS OF LAWN ON PRIVATE HOMES                                                                                                                                                                                                  | 2011-03-08T00:00:00 | 
| 456374    | Operating a walk behind pavement striper.                                                                                                                                                                                                     | 2011-05-18T00:00:00 | 
```