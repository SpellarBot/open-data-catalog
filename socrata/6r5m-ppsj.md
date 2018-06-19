# Hawaii Public Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-public-schools-d7fae) |
| Metadata | [Link](https://data.hawaii.gov/api/views/6r5m-ppsj) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/6r5m-ppsj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/6r5m-ppsj/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 6r5m-ppsj |
| Name | Hawaii Public Schools |
| Attribution | State of Hawaii Department of Education |
| Tags | schools |
| Created | 2012-06-05T10:03:40Z |
| Publication Date | 2012-08-04T01:15:17Z |

## Description

Data about all public schools in Hawaii

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                  | Data Type | Render Type |
| ======== | ============== | =================================== | ===================================== | ========= | =========== |
| No       | time           | :updated_at                         | updated_at                            | meta_data | meta_data   |
| Yes      | series tag     | districtname                        | districtname                          | text      | text        |
| Yes      | series tag     | complexareaname                     | complexareaname                       | text      | text        |
| Yes      | series tag     | complexname                         | complexname                           | text      | text        |
| Yes      | series tag     | schoolcode                          | schoolcode                            | text      | number      |
| Yes      | series tag     | schoolname                          | schoolname                            | text      | text        |
| Yes      | series tag     | schoolnameshort                     | schoolnameshort                       | text      | text        |
| Yes      | series tag     | island                              | island                                | text      | text        |
| Yes      | series tag     | phone                               | phone                                 | text      | text        |
| Yes      | series tag     | fax                                 | fax                                   | text      | text        |
| Yes      | series tag     | principal                           | principal                             | text      | text        |
| Yes      | series tag     | gradefrom                           | gradefrom                             | text      | text        |
| Yes      | numeric metric | gradeto                             | gradeto                               | number    | number      |
| Yes      | numeric metric | enrollment_2011_2012_not_incl_pre_k | enrollment (2011-2012) Not_incl_pre_K | number    | number      |
| Yes      | series tag     | type                                | type                                  | text      | text        |
| Yes      | series tag     | url_home                            | url_home                              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6r5m-ppsj d:2012-06-05T03:03:50.000Z t:complexname=Kahuku t:phone=293-8950 t:schoolname="Kahuku High & Intermediate" t:fax=293-8960 t:principal="Donna Lindsey" t:districtname=Windward t:complexareaname=Castle-Kahuku t:gradefrom=7 t:schoolcode=307 t:schoolnameshort="Kahuku High & Int" t:url_home=http://www.k12.hi.us/~kahukuhs t:island=Oahu m:enrollment_2011_2012_not_incl_pre_k=1491 m:gradeto=12

series e:6r5m-ppsj d:2012-06-05T03:03:50.000Z t:complexname=Farrington t:phone=832-3600 t:schoolname="Governor Wallace Rider Farrington High" t:fax=832-3587 t:principal="Alfredo Carganilla" t:districtname=Honolulu t:complexareaname=Farrington-Kaiser-Kalani t:gradefrom=9 t:schoolcode=106 t:schoolnameshort="Farrington High" t:url_home=http://farringtonhighschool.org t:island=Oahu m:enrollment_2011_2012_not_incl_pre_k=2483 m:gradeto=12

series e:6r5m-ppsj d:2012-06-05T03:03:50.000Z t:complexname=Kalani t:phone=733-4740 t:schoolname="Mayor John H. Wilson Elementary" t:fax=733-4746 t:principal="Richard Kiyonaga" t:districtname=Honolulu t:complexareaname=Farrington-Kaiser-Kalani t:gradefrom=K t:schoolcode=153 t:schoolnameshort="Wilson El" t:url_home=http://wilsonschoolhawaii.org t:island=Oahu m:enrollment_2011_2012_not_incl_pre_k=604 m:gradeto=5
```

## Meta Commands

```ls
metric m:gradeto p:integer l:gradeto t:dataTypeName=number

metric m:enrollment_2011_2012_not_incl_pre_k p:integer l:"enrollment (2011-2012) Not_incl_pre_K" t:dataTypeName=number

entity e:6r5m-ppsj l:"Hawaii Public Schools" t:attribution="State of Hawaii Department of Education" t:url=https://data.hawaii.gov/api/views/6r5m-ppsj

property e:6r5m-ppsj t:meta.view v:id=6r5m-ppsj v:attributionLink=http://doe.k12.hi.us v:averageRating=0 v:name="Hawaii Public Schools" v:attribution="State of Hawaii Department of Education"

property e:6r5m-ppsj t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:6r5m-ppsj t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:6r5m-ppsj t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | districtname | complexareaname                    | complexname | schoolcode | schoolname                             | schoolnameshort   | island | phone    | fax      | principal          | gradefrom | gradeto | enrollment_2011_2012_not_incl_pre_k | type | url_home                                       | 
| =========== | ============ | ================================== | =========== | ========== | ====================================== | ================= | ====== | ======== | ======== | ================== | ========= | ======= | =================================== | ==== | ============================================== | 
| 1338865430  | Windward     | Castle-Kahuku                      | Kahuku      | 307        | Kahuku High & Intermediate             | Kahuku High & Int | Oahu   | 293-8950 | 293-8960 | Donna Lindsey      | 7         | 12      | 1491                                |      | http://www.k12.hi.us/~kahukuhs                 | 
| 1338865430  | Honolulu     | Farrington-Kaiser-Kalani           | Farrington  | 106        | Governor Wallace Rider Farrington High | Farrington High   | Oahu   | 832-3600 | 832-3587 | Alfredo Carganilla | 9         | 12      | 2483                                |      | http://farringtonhighschool.org                | 
| 1338865430  | Honolulu     | Farrington-Kaiser-Kalani           | Kalani      | 153        | Mayor John H. Wilson Elementary        | Wilson El         | Oahu   | 733-4740 | 733-4746 | Richard Kiyonaga   | K         | 5       | 604                                 |      | http://wilsonschoolhawaii.org                  | 
| 1338865430  | Windward     | Kailua-Kalaheo                     | Kailua      | 321        | Maunawili Elementary                   | Maunawili El      | Oahu   | 266-7822 | 266-7834 | Ryan Amine         | K         | 6       | 376                                 |      | http://mes.k12.hi.us                           | 
| 1338865430  | Honolulu     | Farrington-Kaiser-Kalani           | Farrington  | 133        | Linapuni Elementary                    | Linapuni El       | Oahu   | 832-3303 | 832-3305 | Cindy Sunahara     | K         | 1       | 171                                 |      | http://www.linapuniel.k12.hi.us                | 
| 1338865430  | Kauai        | Kapaa-Kauai-Waimea                 | Kapaa       | 447        | Kapa'a Middle                          | Kapaa Middle      | Kauai  | 821-4460 | 821-6967 | Nathan Aiwohi      | 6         | 8       | 633                                 |      | http://www.kapaams.k12.hi.us                   | 
| 1338865430  | Windward     | Castle-Kahuku                      | Kahuku      | 319        | La'ie Elementary                       | Laie El           | Oahu   | 293-8965 | 293-8968 | Matthew Ho         | K         | 6       | 658                                 |      | http://www.k12.hi.us/~laie                     | 
| 1338865430  | Hawaii       | Hilo-Laupahoehoe-Waiakea           | Hilo        | 355        | Hilo High                              | Hilo High         | Hawaii | 974-4021 | 974-4036 | Robert Dircks      | 9         | 12      | 1207                                |      | http://www.hilohs.k12.hi.us                    | 
| 1338865430  | Honolulu     | Kaimuki-McKinley-Roosevelt         | McKinley    | 117        | Princess Victoria Ka'iulani Elementary | Kaiulani El       | Oahu   | 832-3160 | 832-3164 | Rodney Moriwake    | K         | 5       | 420                                 |      | http://www.kaiulani.k12.hi.us/web/Welcome.html | 
| 1338865430  | Hawaii       | Honokaa-Kealakehe-Kohala-Konawaena | Honokaa     | 361        | Honoka'a Elementary                    | Honokaa El        | Hawaii | 775-8820 | 775-8828 | Rachelle Matsumura | K         | 6       | 376                                 |      | http://www.honokaael.k12.hi.us                 | 
```