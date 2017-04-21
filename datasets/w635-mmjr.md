# EOC Activations - City Open Data HSEM

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/eoc-activations-city-open-data-hsem) |
| Metadata | [Link](https://data.austintexas.gov/api/views/w635-mmjr) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/w635-mmjr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/w635-mmjr/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | w635-mmjr |
| Name | EOC Activations - City Open Data HSEM |
| Attribution | City of Austin Office of Homeland Security and Emergency Management |
| Category | Public Safety |
| Tags | eoc, hsem, disaster, flood |
| Created | 2015-08-06T18:48:01Z |
| Publication Date | 2015-08-06T21:24:34Z |

## Description

A list of activations of the Austin/Travis County Emergency Operation Center (EOC) in 2014 and YTD 2015.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | time        | eoc_activation_start_date | EOC Activation Start Date | calendar_date | calendar_date |
| No       |             | eoc_activation_end_date   | EOC Activation End Date   | calendar_date | calendar_date |
| Yes      | series tag  | hazard                    | Hazard                    | text          | text          |
| Yes      | series tag  | harzard_details           | Harzard Details           | text          | text          |
```

## Time Field

```ls
Value = eoc_activation_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = eoc_activation_end_date
```

## Data Commands

```ls
series e:w635-mmjr d:2015-03-04T00:00:00.000Z t:harzard_details=N/A t:hazard="Winter Weather" m:row_number.w635-mmjr=1

series e:w635-mmjr d:2015-05-27T00:00:00.000Z t:harzard_details="Memorial Day Flooding, with multiple F1 tornados. Presidential IA and PA" t:hazard=Flooding m:row_number.w635-mmjr=2

series e:w635-mmjr d:2015-06-16T00:00:00.000Z t:harzard_details="Tropical Storm Bill. Presidential IA and PA from Memorial Day storms extended to this event." t:hazard=Flooding m:row_number.w635-mmjr=3
```

## Meta Commands

```ls
metric m:row_number.w635-mmjr p:long l:"Row Number"

entity e:w635-mmjr l:"EOC Activations - City Open Data   HSEM" t:attribution="City of Austin Office of Homeland Security and Emergency Management" t:url=https://data.austintexas.gov/api/views/w635-mmjr

property e:w635-mmjr t:meta.view v:id=w635-mmjr v:category="Public Safety" v:attributionLink=https://austintexas.gov/department/about-hsem v:averageRating=0 v:name="EOC Activations - City Open Data   HSEM" v:attribution="City of Austin Office of Homeland Security and Emergency Management"

property e:w635-mmjr t:meta.view.license v:name="Public Domain"

property e:w635-mmjr t:meta.view.owner v:id=wnhb-trsd v:profileImageUrlMedium=/api/users/wnhb-trsd/profile_images/THUMB v:profileImageUrlLarge=/api/users/wnhb-trsd/profile_images/LARGE v:screenName="Jake Dirr" v:profileImageUrlSmall=/api/users/wnhb-trsd/profile_images/TINY v:displayName="Jake Dirr"

property e:w635-mmjr t:meta.view.tableauthor v:id=wnhb-trsd v:profileImageUrlMedium=/api/users/wnhb-trsd/profile_images/THUMB v:profileImageUrlLarge=/api/users/wnhb-trsd/profile_images/LARGE v:screenName="Jake Dirr" v:profileImageUrlSmall=/api/users/wnhb-trsd/profile_images/TINY v:roleName=editor v:displayName="Jake Dirr"
```

## Top Records

```ls
| eoc_activation_start_date | eoc_activation_end_date | hazard                       | harzard_details                                                                              | 
| ========================= | ======================= | ============================ | ============================================================================================ | 
| 2015-03-04T00:00:00       | 2015-03-04T00:00:00     | Winter Weather               | N/A                                                                                          | 
| 2015-05-27T00:00:00       | 2015-05-29T00:00:00     | Flooding                     | Memorial Day Flooding, with multiple F1 tornados. Presidential IA and PA                     | 
| 2015-06-16T00:00:00       | 2015-06-16T00:00:00     | Flooding                     | Tropical Storm Bill. Presidential IA and PA from Memorial Day storms extended to this event. | 
| 2014-01-24T00:00:00       | 2014-01-24T00:00:00     | Winter Weather               | N/A                                                                                          | 
| 2014-01-28T00:00:00       | 2014-01-28T00:00:00     | Winter Weather               | N/A                                                                                          | 
| 2014-02-07T00:00:00       | 2014-02-07T00:00:00     | Winter Weather               | N/A                                                                                          | 
| 2014-02-11T00:00:00       | 2014-02-11T00:00:00     | Winter Weather               | N/A                                                                                          | 
| 2014-03-04T00:00:00       | 2014-03-04T00:00:00     | Winter Weather               | Limited acitivation                                                                          | 
| 2014-05-27T00:00:00       | 2014-05-27T00:00:00     | Flooding                     | Senior Deputy Jessica Hollis line of duty death                                              | 
| 2014-06-09T00:00:00       | 2014-06-10T00:00:00     | Motorcade Traffic Management | N/A                                                                                          | 
```