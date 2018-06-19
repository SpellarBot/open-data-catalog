# Microsite-belleville

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/microsite-belleville-0f4bf) |
| Metadata | [Link](https://data.illinois.gov/api/views/5ggh-m2ea) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5ggh-m2ea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5ggh-m2ea/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5ggh-m2ea |
| Name | Microsite-belleville |
| Created | 2013-01-28T17:36:19Z |
| Publication Date | 2013-02-04T20:52:19Z |

## Description

Control file for the Belleville Microsite

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | featured_stat        | featured stat        | text      | text        |
| Yes      | series tag  | featured_description | featured description | text      | text        |
| Yes      | series tag  | featured_title       | featured title       | text      | text        |
| Yes      | series tag  | featured_agency      | featured agency      | text      | text        |
| Yes      | series tag  | agency_icon          | agency icon          | photo     | photo       |
| Yes      | series tag  | featured_text        | featured text        | text      | text        |
| Yes      | series tag  | featured_thumbnail   | featured thumbnail   | photo     | photo       |
| Yes      | series tag  | featured_link        | featured link        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5ggh-m2ea d:2013-02-01T13:33:00.000Z t:featured_description=Citizens t:featured_agency="Economic Development" t:featured_text="Knowing the age makeup of its citizen's helps the City of Belleville allocate resources for the greatest benefit." t:featured_stat="44,000 +" t:featured_title="Explore the Belleville population's age demographic." t:featured_link=knxq-gy8e t:featured_thumbnail=L_BPeCwwgH1bNj8zrZ7q3enHSvazDT_oQh35OxZzqBk t:agency_icon=DKnRnrgqjZ7ivOEAZT3PAngsbqxW727p-WiE8PpFVB0 m:row_number.5ggh-m2ea=1

series e:5ggh-m2ea d:2013-02-01T14:48:41.000Z t:featured_description="Public Parks" t:featured_agency="Parks and Recreation" t:featured_text="Belleville Parks and Recreation is committed to wholesome, family oriented recreation in a fiscally responsible manner that interprets the culture and history of the community while expanding recreation opportunities in a healthy and safe environment for all generations of city residents." t:featured_stat=26 t:featured_title="View a map of Belleville's Parks and Facilities" t:featured_link=hh6k-kvzj t:featured_thumbnail=7WlewjRjrzizHHf9rrvptDJMcmGIcedEhqnQqqJrGx0 t:agency_icon=nLj5G5cjx0kEH2Beqru1WiFgX4r8cyIywo-uVnqrvbk m:row_number.5ggh-m2ea=2

series e:5ggh-m2ea d:2013-02-04T11:58:09.000Z t:featured_description="Ambulatory Surgical Treatment Centers" t:featured_agency="Division of Health Care Facilities and Programs" t:featured_text="Assuring the quality of our food, setting the standards for hospital and nursing home care, checking the safety of recreation areas, overseeing the inspection of milk producing farms and processing plants, maintaining the state's vital records and screening newborns for genetic diseases are just some of the duties of Illinois Department of Public Health." t:featured_stat=4 t:featured_title="A map of Ambulatory Surgical Treatment Centers in Belleville." t:featured_link=x3ut-za6t t:featured_thumbnail=ta3_MAWZ7JpiMBVjG15Jl1OqubVGQjitZhEnTLuB_nk t:agency_icon=ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek m:row_number.5ggh-m2ea=3
```

## Meta Commands

```ls
metric m:row_number.5ggh-m2ea p:long l:"Row Number"

entity e:5ggh-m2ea l:Microsite-belleville t:url=https://data.illinois.gov/api/views/5ggh-m2ea

property e:5ggh-m2ea t:meta.view v:id=5ggh-m2ea v:averageRating=0 v:name=Microsite-belleville

property e:5ggh-m2ea t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:5ggh-m2ea t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | featured_stat | featured_description                  | featured_title                                                | featured_agency                                 | agency_icon                                 | featured_text                                                                                                                                                                                                                                                                                                                                                        | featured_thumbnail                          | featured_link | 
| =========== | ============= | ===================================== | ============================================================= | =============================================== | =========================================== | ==================================================================================================================================================================================================================================================================================================================================================================== | =========================================== | ============= | 
| 1359725580  | 44,000 +      | Citizens                              | Explore the Belleville population's age demographic.          | Economic Development                            | DKnRnrgqjZ7ivOEAZT3PAngsbqxW727p-WiE8PpFVB0 | Knowing the age makeup of its citizen's helps the City of Belleville allocate resources for the greatest benefit.                                                                                                                                                                                                                                                    | L_BPeCwwgH1bNj8zrZ7q3enHSvazDT_oQh35OxZzqBk | knxq-gy8e     | 
| 1359730121  | 26            | Public Parks                          | View a map of Belleville's Parks and Facilities               | Parks and Recreation                            | nLj5G5cjx0kEH2Beqru1WiFgX4r8cyIywo-uVnqrvbk | Belleville Parks and Recreation is committed to wholesome, family oriented recreation in a fiscally responsible manner that interprets the culture and history of the community while expanding recreation opportunities in a healthy and safe environment for all generations of city residents.                                                                    | 7WlewjRjrzizHHf9rrvptDJMcmGIcedEhqnQqqJrGx0 | hh6k-kvzj     | 
| 1359979089  | 4             | Ambulatory Surgical Treatment Centers | A map of Ambulatory Surgical Treatment Centers in Belleville. | Division of Health Care Facilities and Programs | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | Assuring the quality of our food, setting the standards for hospital and nursing home care, checking the safety of recreation areas, overseeing the inspection of milk producing farms and processing plants, maintaining the state's vital records and screening newborns for genetic diseases are just some of the duties of Illinois Department of Public Health. | ta3_MAWZ7JpiMBVjG15Jl1OqubVGQjitZhEnTLuB_nk | x3ut-za6t     | 
| 1359982324  | 1,164         | Business Establishments               | See a pie chart showing the makeup of Belleville's businesses | US Census                                       | DKnRnrgqjZ7ivOEAZT3PAngsbqxW727p-WiE8PpFVB0 | In an effort to attract new business development and growth to Belleville as well as assist existing firms to expand thereby increasing the local tax base and further providing job opportunities, the Belleville, Illinois City Council has established several programs to provide various financial incentives and inducements.                                  | RDJwOtCTLAmDZLZFRUBwQdQzBZE4JRe5L-eyyzoVm5Q | jdjn-7j39     | 
```