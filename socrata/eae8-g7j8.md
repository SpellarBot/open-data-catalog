# State Art Collection At Colleges And Universities 2014-10-02

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-art-collection-at-colleges-and-universities-2014-10-02-42152) |
| Metadata | [Link](https://data.wa.gov/api/views/eae8-g7j8) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/eae8-g7j8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/eae8-g7j8/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | eae8-g7j8 |
| Name | State Art Collection At Colleges And Universities 2014-10-02 |
| Attribution | Washington State Arts Commission (ArtsWA) |
| Category | Education |
| Tags | public art, culture, art, visual art, architecture, sculpture, paintings, state art collection, washington state arts commission, artswa, colleges, universities, artwork, work of art, heritage, ar... |
| Created | 2014-10-02T21:43:53Z |
| Publication Date | 2014-10-02T21:49:47Z |

## Description

Artworks included in this dataset are part of the State Art Collection, a collection that is publicly owned, publicly sited, and publicly selected.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| Yes      | series tag  | id_number         | ID NUMBER         | text      | text        |
| Yes      | series tag  | artist            | ARTIST            | text      | text        |
| Yes      | series tag  | title             | TITLE             | text      | text        |
| No       |             | date              | DATE              | text      | text        |
| Yes      | series tag  | materials         | MATERIALS         | text      | text        |
| Yes      | series tag  | measurements      | MEASUREMENTS      | text      | text        |
| Yes      | series tag  | credit_line       | CREDIT LINE       | text      | text        |
| Yes      | series tag  | artwork_site      | ARTWORK SITE      | text      | text        |
| Yes      | series tag  | specific_location | SPECIFIC LOCATION | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:eae8-g7j8 d:2014-01-01T00:00:00.000Z t:measurements="10 ft x 21 in x 27 in" t:title=Olduwan t:artwork_site="South Seattle College - Georgetown Campus" t:materials="Painted steel, fired ceramic, and glass" t:id_number=WSAC2006.009.000 t:specific_location="Exterior courtyard" t:artist="Bigger, Charles" t:credit_line="This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with South Seattle Community College" m:row_number.eae8-g7j8=1

series e:eae8-g7j8 d:2014-01-01T00:00:00.000Z t:measurements="8 ft x 25 in x 10 in" t:title="Duwamish Working Hands" t:artwork_site="South Seattle College - Georgetown Campus" t:materials="Cast cement and ceramic tile" t:id_number=WSAC2003.073.002 t:specific_location="Near main entrance door to Building A" t:artist="Buckner, Paul" t:credit_line="This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with South Seattle Community College" m:row_number.eae8-g7j8=2

series e:eae8-g7j8 d:2014-01-01T00:00:00.000Z t:measurements="30 in x 37 in x 8 in" t:title="Sculpin Wind Vane" t:artwork_site="South Seattle College - Georgetown Campus" t:materials="Gold and metal leaf on formed copper sheet" t:id_number=WSAC2003.073.001 t:specific_location="SE corner of the roof of Building A" t:artist="Buckner, Paul" t:credit_line="This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with South Seattle Community College" m:row_number.eae8-g7j8=3
```

## Meta Commands

```ls
metric m:row_number.eae8-g7j8 p:long l:"Row Number"

entity e:eae8-g7j8 l:"State Art Collection At Colleges And Universities 2014-10-02" t:attribution="Washington State Arts Commission (ArtsWA)" t:url=https://data.wa.gov/api/views/eae8-g7j8

property e:eae8-g7j8 t:meta.view v:id=eae8-g7j8 v:category=Education v:attributionLink=http://www.arts.wa.gov v:averageRating=0 v:name="State Art Collection At Colleges And Universities 2014-10-02" v:attribution="Washington State Arts Commission (ArtsWA)"

property e:eae8-g7j8 t:meta.view.owner v:id=wjx2-y8md v:profileImageUrlMedium=/api/users/wjx2-y8md/profile_images/THUMB v:profileImageUrlLarge=/api/users/wjx2-y8md/profile_images/LARGE v:screenName="Janae Huber" v:profileImageUrlSmall=/api/users/wjx2-y8md/profile_images/TINY v:displayName="Janae Huber"

property e:eae8-g7j8 t:meta.view.tableauthor v:id=wjx2-y8md v:profileImageUrlMedium=/api/users/wjx2-y8md/profile_images/THUMB v:profileImageUrlLarge=/api/users/wjx2-y8md/profile_images/LARGE v:screenName="Janae Huber" v:profileImageUrlSmall=/api/users/wjx2-y8md/profile_images/TINY v:roleName=publisher v:displayName="Janae Huber"
```

## Top Records

```ls
| id_number            | artist          | title                                          | date | materials                                                                               | measurements             | credit_line                                                                                                                                                       | artwork_site                              | specific_location                                                                                                                                                                                                                                     | 
| ==================== | =============== | ============================================== | ==== | ======================================================================================= | ======================== | ================================================================================================================================================================= | ========================================= | ===================================================================================================================================================================================================================================================== | 
| WSAC2006.009.000     | Bigger, Charles | Olduwan                                        | 2007 | Painted steel, fired ceramic, and glass                                                 | 10 ft x 21 in x 27 in    | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with South Seattle Community College   | South Seattle College - Georgetown Campus | Exterior courtyard                                                                                                                                                                                                                                    | 
| WSAC2003.073.002     | Buckner, Paul   | Duwamish Working Hands                         | 2005 | Cast cement and ceramic tile                                                            | 8 ft x 25 in x 10 in     | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with South Seattle Community College   | South Seattle College - Georgetown Campus | Near main entrance door to Building A                                                                                                                                                                                                                 | 
| WSAC2003.073.001     | Buckner, Paul   | Sculpin Wind Vane                              | 2005 | Gold and metal leaf on formed copper sheet                                              | 30 in x 37 in x 8 in     | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with South Seattle Community College   | South Seattle College - Georgetown Campus | SE corner of the roof of Building A                                                                                                                                                                                                                   | 
| WSAC2004.052.001-006 | Hall, Kim David | Biomechanical Future 1-6                       | 2007 | Hand-formed polymer                                                                     |                          | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Bellingham Technical College      | Bellingham Technical College              | Morse Center/Auto Collision/Welding Lobby - 3 lightwells, east and west staircases                                                                                                                                                                    | 
| WSAC1979.006.000     | Lindsey, Thomas | Landed Bridge Series                           | 1979 | Weathering steel plate                                                                  | 240 in x 204 in x 108 in | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Spokane Community College         | Spokane Community College                 | Lawn directly west of building 7                                                                                                                                                                                                                      | 
| WSAC1990.005.000     | Bates, Gary     | Cascade Cradle                                 | 1991 | Steel                                                                                   | 234 in x 106 in          | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Central Washington University     | Central Washington University             | In front of Science Bldg East Entrance                                                                                                                                                                                                                | 
| WSAC2003.080.001A-B  | Sollod, Ellen   | Breathing Lessons                              | 2004 | Neon                                                                                    | 11 in x 120 in x 4 in    | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with South Seattle Community College   | South Seattle College                     | Building: Olympic Hall (OLY) - North and South                                                                                                                                                                                                        | 
| WSAC2010.014.000     | Stone, Katy     | Life Sign                                      | 2011 | Acrylic on aluminum                                                                     | 14 ft x 13 ft x 3 in     | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Lake Washington Technical College | Lake Washington Institute of Technoloy    | South Atrium Curved Wall                                                                                                                                                                                                                              | 
| WSAC1993.162.00A-E   | Simpson, Buster | Parapet Relay                                  | 1995 | Galvanized steel louvered signs with cast iron and bronze plaques embedded in sidewalks | dimensions vary          | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with University of Washington          | University of Washington - Tacoma         | Parapet: GWP Building on Pacific Ave & 19th facades (parts A & B); Sidewalk viewing markers: (1) 19th & Pacific, in front of WSHM (part C), (2) On central campus pedestrian section of 19th (part D), (3) 1 block west of The Swiss on 19th (part E) | 
| WSAC1985.044.000     | Hoge, John      | Changing Workplace: Yesterday, Today, Tomorrow | 1985 | Granite                                                                                 | 84 in x 144 in x 84 in   | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Lake Washington Technical College | Lake Washington Institute of Technoloy    | East building mall exterior                                                                                                                                                                                                                           | 
```