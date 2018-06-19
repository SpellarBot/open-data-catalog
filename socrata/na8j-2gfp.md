# SSMMA Enterprise Zone

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-enterprise-zone-14a43) |
| Metadata | [Link](https://data.illinois.gov/api/views/na8j-2gfp) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/na8j-2gfp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/na8j-2gfp/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | na8j-2gfp |
| Name | SSMMA Enterprise Zone |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | economic development, planning |
| Created | 2012-11-27T20:51:14Z |
| Publication Date | 2012-11-27T20:52:17Z |

## Description

This dataset details Enterprise Zones in the Chicago Southland region. This was created by South Suburban Atlas staff

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | ent_zone_n  | Ent_Zone_N | text      | text        |
| Yes      | series tag     | muni        | Muni       | text      | text        |
| Yes      | series tag     | county      | County     | text      | text        |
| Yes      | numeric metric | shape_leng  | SHAPE_Leng | number    | number      |
| Yes      | numeric metric | shape_area  | SHAPE_Area | number    | number      |
| Yes      | numeric metric | zone_numbe  | Zone_Numbe | number    | number      |
| Yes      | series tag     | organizati  | Organizati | text      | text        |
| Yes      | series tag     | organiza_1  | Organiza_1 | text      | text        |
| Yes      | series tag     | organiza_2  | Organiza_2 | text      | text        |
| Yes      | series tag     | organiza_3  | Organiza_3 | text      | text        |
| Yes      | series tag     | website     | Website    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:na8j-2gfp d:2012-11-27T12:51:16.000Z t:organiza_1="1601 Chicago Rd, Chicago Heights, Illinois" t:organiza_3=(708)-755-3102 t:organizati="City of Chicago Heights" t:organiza_2="Mr. Joe Kudra" t:muni="Chicago Heights" t:county=Cook t:website="http://www.ieza.org/index.php?option=com_mtree&task=viewlink&link_id=32&Itemid=26" t:ent_zone_n="Chicago Heights" t:objectid=5 m:shape_area=281616928.908 m:zone_numbe=79 m:shape_leng=159719.440335

series e:na8j-2gfp d:2012-11-27T12:51:16.000Z t:muni="Ford Heights" t:county=Cook t:ent_zone_n="Ford Heights/Sauk Village" t:objectid=6 m:shape_area=66950877.9077 m:shape_leng=82932.9522729

series e:na8j-2gfp d:2012-11-27T12:51:16.000Z t:organiza_1="15320 S. Broadway, Harvey, Illinois" t:organiza_3=(708)-210-5300 t:organizati="City of Harvey" t:organiza_2="Ms. LaTonya Rufus" t:muni=Harvey t:county=Cook t:website="http://www.cityofharvey.org/site2/index.php?option=com_content&task=view&id=96&Itemid=108" t:ent_zone_n="Harvey/Phoenix/Hazel Crest" t:objectid=7 m:shape_area=204552105.076 m:shape_leng=121510.59737
```

## Meta Commands

```ls
metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

metric m:zone_numbe p:integer l:Zone_Numbe t:dataTypeName=number

entity e:na8j-2gfp l:"SSMMA Enterprise Zone" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/na8j-2gfp

property e:na8j-2gfp t:meta.view v:id=na8j-2gfp v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Enterprise Zone" v:attribution="South Suburban Mayors and Managers Association"

property e:na8j-2gfp t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:na8j-2gfp t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:na8j-2gfp t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | ent_zone_n                      | muni            | county | shape_leng    | shape_area    | zone_numbe | organizati                                       | organiza_1                                 | organiza_2                                         | organiza_3     | website                                                                                   | 
| =========== | ======== | =============================== | =============== | ====== | ============= | ============= | ========== | ================================================ | ========================================== | ================================================== | ============== | ========================================================================================= | 
| 1354020676  | 5        | Chicago Heights                 | Chicago Heights | Cook   | 159719.440335 | 281616928.908 | 79         | City of Chicago Heights                          | 1601 Chicago Rd, Chicago Heights, Illinois | Mr. Joe Kudra                                      | (708)-755-3102 | http://www.ieza.org/index.php?option=com_mtree&task=viewlink&link_id=32&Itemid=26         | 
| 1354020676  | 6        | Ford Heights/Sauk Village       | Ford Heights    | Cook   | 82932.9522729 | 66950877.9077 |            |                                                  |                                            |                                                    |                |                                                                                           | 
| 1354020676  | 7        | Harvey/Phoenix/Hazel Crest      | Harvey          | Cook   | 121510.59737  | 204552105.076 |            | City of Harvey                                   | 15320 S. Broadway, Harvey, Illinois        | Ms. LaTonya Rufus                                  | (708)-210-5300 | http://www.cityofharvey.org/site2/index.php?option=com_content&task=view&id=96&Itemid=108 | 
| 1354020676  | 8        | Cal-Sag Enterprise Zone         | Blue Island     | Cook   | 187653.091678 | 260395435.677 | 80         | Alsip Economic Development Group                 | 12159 S. Pulaski Rd, Alsip, Illinois       | Ms. Mary Schmidt                                   | (708)-653-3122 | http://www.calsagezone.org/                                                               | 
| 1354020676  | 9        | Calumet Region                  | Calumet City    | Cook   | 405114.516934 | 168872557.629 | 78         | City of Calumet City                             | 204 Pulaski Rd, Calumet City, Illinois     | Mr. Jim Gigliotti-Director of Economic Development | (708)-891-8141 | http://www.ieza.org/index.php?option=com_mtree&task=viewlink&link_id=14&Itemid=26         | 
| 1354020676  | 10       | Enterprise Zone: Three          | Burnham         | Cook   | 341331.093665 | 459108205.915 | 71         | City of Chicago: Bureau of Community Development | 121 N. LaSalle Street                      | Tracy Sanchez                                      | (312)-744-0892 | http://www.ieza.org/index.php?option=com_mtree&task=viewlink&link_id=10&Itemid=26         | 
| 1354020676  | 11       | Summit, Village of/Bedford Park | Bedford Park    | Cook   | 91884.8063198 | 173840180.67  | 75         | Village of Summit                                | 7321 W. 59th Street, Summit, Illinois      | Ms. Marvel Parker                                  | (708)-563-4806 | http://www.ieza.org/index.php?option=com_mtree&task=viewlink&link_id=97&Itemid=26         | 
| 1354020676  | 12       | Summit, Village of/Bedford Park |                 | Cook   | 37717.6149394 | 60891772.9265 | 75         | Village of Summit                                | 7321 W. 59th Street, Summit, Illinois      | Ms. Marvel Parker                                  | (708)-563-4806 | http://www.ieza.org/index.php?option=com_mtree&task=viewlink&link_id=97&Itemid=26         | 
| 1354020676  | 13       | Hodgkins                        |                 | Cook   | 96684.7723829 | 146632887.913 |            |                                                  |                                            |                                                    |                |                                                                                           | 
| 1354020676  | 97       | Harvey/Phoenix/Hazel Crest      | Hazel Crest     | Cook   | 7581.78127945 | 3236733.58252 |            | City of Harvey                                   | 15320 S. Broadway, Harvey, Illinois        | Ms. LaTonya Rufus                                  |                | http://www.cityofharvey.org/site2/index.php?option=com_content&task=view&id=96&Itemid=108 | 
```