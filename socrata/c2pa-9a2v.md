# SSMMA Social Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-social-services-9e513) |
| Metadata | [Link](https://data.illinois.gov/api/views/c2pa-9a2v) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/c2pa-9a2v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/c2pa-9a2v/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | c2pa-9a2v |
| Name | SSMMA Social Services |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | social service, housing, community development |
| Created | 2012-11-27T19:08:22Z |
| Publication Date | 2012-11-27T19:09:31Z |

## Description

This dataset is a listing of social service agencies in the Chicago Southland region.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | objectid    | OBJECTID   | text      | number      |
| No       |             | x           | X          | number    | number      |
| No       |             | y           | Y          | number    | number      |
| Yes      | series tag  | match_addr  | Match_addr | text      | text        |
| Yes      | series tag  | agency_nam  | Agency_Nam | text      | text        |
| Yes      | series tag  | category    | Category   | text      | text        |
| Yes      | series tag  | website     | Website    | text      | text        |
| Yes      | series tag  | phone_numb  | Phone_Numb | text      | text        |
| Yes      | series tag  | add_num     | Add_Num    | text      | number      |
| Yes      | series tag  | municipali  | Municipali | text      | text        |
| Yes      | series tag  | editor      | Editor     | text      | text        |
| Yes      | series tag  | propreitar  | Propreitar | text      | text        |
| Yes      | series tag  | universal   | Universal_ | text      | text        |
| Yes      | series tag  | location_1  | Location 1 | text      | text        |
| Yes      | series tag  | location_2  | Location 2 | text      | text        |
| Yes      | series tag  | location_3  | Location 3 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x,y
```

## Data Commands

```ls
series e:c2pa-9a2v d:2012-11-27T11:08:24.000Z t:agency_nam="Adolescent Clinic" t:location_3="3900 95th Street" t:category="Medical Services" t:editor=MJR t:location_2="3900 W. 95th Street, Suite 11, Evergreen Park, Illinois, 60805" t:phone_numb=(708)-499-1643 t:add_num=3900 t:match_addr="3900 W 95TH ST" t:location_1="3900 95th Street" t:objectid=1 t:municipali="Evergreen Park" m:row_number.c2pa-9a2v=1

series e:c2pa-9a2v d:2012-11-27T11:08:24.000Z t:agency_nam="Advocate Christ Medical Center" t:location_3="4400 95th Street" t:category="Disabled/Mentally Ill Services" t:editor=MJR t:location_2="4440 W. 95th Street, Oak Lawn, Illinois, 60453" t:phone_numb=(708)-425-8000 t:add_num=4400 t:match_addr="4400 W 95TH ST" t:location_1="4400 95th Street" t:objectid=2 t:municipali="Oak Lawn" m:row_number.c2pa-9a2v=2

series e:c2pa-9a2v d:2012-11-27T11:08:24.000Z t:agency_nam="Angels Touch" t:location_3="2851 Everett" t:category="Education Services" t:editor=MJR t:location_2="2851 W. Everett, Blue Island, Illinois, 60406" t:phone_numb=(708)-489-5434 t:add_num=2851 t:match_addr="2851 EVERETT ST" t:location_1="2851 Everett" t:objectid=3 t:municipali="Blue Island" m:row_number.c2pa-9a2v=3
```

## Meta Commands

```ls
metric m:row_number.c2pa-9a2v p:long l:"Row Number"

entity e:c2pa-9a2v l:"SSMMA Social Services" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/c2pa-9a2v

property e:c2pa-9a2v t:meta.view v:id=c2pa-9a2v v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Social Services" v:attribution="South Suburban Mayors and Managers Association"

property e:c2pa-9a2v t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c2pa-9a2v t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:c2pa-9a2v t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| :updated_at | objectid | x              | y             | match_addr        | agency_nam                             | category                          | website | phone_numb     | add_num | municipali      | editor | propreitar | universal | location_1           | location_2                                                     | location_3           | 
| =========== | ======== | ============== | ============= | ================= | ====================================== | ================================= | ======= | ============== | ======= | =============== | ====== | ========== | ========= | ==================== | ============================================================== | ==================== | 
| 1354014504  | 1        | -87.718995151  | 41.7206844846 | 3900 W 95TH ST    | Adolescent Clinic                      | Medical Services                  |         | (708)-499-1643 | 3900    | Evergreen Park  | MJR    |            |           | 3900 95th Street     | 3900 W. 95th Street, Suite 11, Evergreen Park, Illinois, 60805 | 3900 95th Street     | 
| 1354014504  | 2        | -87.7310751176 | 41.7202904215 | 4400 W 95TH ST    | Advocate Christ Medical Center         | Disabled/Mentally Ill Services    |         | (708)-425-8000 | 4400    | Oak Lawn        | MJR    |            |           | 4400 95th Street     | 4440 W. 95th Street, Oak Lawn, Illinois, 60453                 | 4400 95th Street     | 
| 1354014504  | 3        | -87.6920555761 | 41.6574634158 | 2851 EVERETT ST   | Angels Touch                           | Education Services                |         | (708)-489-5434 | 2851    | Blue Island     | MJR    |            |           | 2851 Everett         | 2851 W. Everett, Blue Island, Illinois, 60406                  | 2851 Everett         | 
| 1354014504  | 4        | -87.6975977575 | 41.5334888338 | 3400 196TH ST     | Anita M. Stone Jewish Community Center | Job Information/Career Counseling |         | (708)-799-7650 | 3400    | Flossmoor       | MJR    |            |           | 3400 196th Street    | 3400 W. 196th Street, Flossmoor, Illinois, 60422               | 3400 196th Street    | 
| 1354014504  | 5        | -87.8059593681 | 42.0484941419 | 9229 HARLEM AVE   | Ammunciation Episcopal Church          | Emergency Services                |         | (708)-599-2405 | 9229    | Bridgeview      | MJR    |            |           | 9229 Harlem Avenue   | 9229 W. Harlem Avenue, Bridgeview, Illinois, 60455             | 9229 Harlem Avenue   | 
| 1354014504  | 6        | -87.7077132001 | 41.643987821  | 3520 W 137TH ST   | Apostolic Deliverance Temple           | Emergency Services                |         | (708)-239-0497 | 3520    | Robbins         | MJR    |            |           | 3520 137th Street    | 3520 W. 137th Street, Robbins, Illinois, 60472                 | 3520 137th Street    | 
| 1354014504  | 7        | -87.6597125392 | 41.6153121767 | 15100 PAGE AVE    | Bethel Gospel Tabernacle               | Emergency Services                |         | (708)-388-8944 | 15100   | Harvey          | MJR    |            |           | 15100 Page           | 15100 S. Page, Harvey, Illinois, 60426                         | 15100 Page           | 
| 1354014504  | 8        | -87.6234650759 | 41.5085697329 | 1250 PORTLAND AVE | Bethel Community Facility              | Emergency Services                |         | (708)-758-5585 | 1250    | Chicago Heights | MJR    |            |           | 1250 Portland Avenue | 1250 Portland Avenue, Chicago Heights, Illinois, 60411         | 1250 Portland Avenue | 
| 1354014504  | 9        | -87.6473929774 | 41.8896691258 | 425 N HALSTED ST  | Bloom Township                         | Emergency Services                |         | (708)-754-9400 | 425     | Chicago Heights | MJR    |            |           | 425 Halsted Street   | 425 Halsted, Chicago Heights, Illinois, 60411                  | 425 Halsted Street   | 
| 1354014504  | 10       | -87.6473929774 | 41.8896691258 | 425 N HALSTED ST  | Bloom Township Committee on Youth      | Job Information/Career Counseling |         | (708)-754-9400 | 425     | Chicago Heights | MJR    |            |           | 425 Halsted Street   | 425 Halsted, Chicago Heights, Illinois, 60411                  | 425 Halsted Street   | 
```