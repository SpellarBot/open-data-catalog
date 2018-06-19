# Metered motorcycle spaces

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/metered-motorcycle-spaces-0174b) |
| Metadata | [Link](https://data.sfgov.org/api/views/uf55-k7py) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/uf55-k7py/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/uf55-k7py/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | uf55-k7py |
| Name | Metered motorcycle spaces |
| Attribution | SFMTA, SFpark |
| Category | Transportation |
| Tags | sfmta, sfpark, motorcycles, meters, parking |
| Created | 2012-06-04T04:47:51Z |
| Publication Date | 2013-05-07T18:06:27Z |

## Description

This dataset includes metered motorcycle parking spaces in San Francisco as of April 2013. Find attached a data dictionary, a version of the map as a PDF, and a shapefile of the data. This data provides locations of motorcycle meters; meter characteristics, such as single-space or multi-space meter, smart meter status, sensor status, owner, on- or off-street location; rate area.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| No       |                | id          | ID         | text      | number      |
| Yes      | series tag     | post_id     | POST_ID    | text      | text        |
| Yes      | series tag     | ms_id       | MS_ID      | text      | text        |
| Yes      | series tag     | ms_spaceid  | MS_SPACEID | text      | number      |
| Yes      | series tag     | cap_color   | CAP_COLOR  | text      | text        |
| Yes      | series tag     | meter_type  | METER_TYPE | text      | text        |
| Yes      | series tag     | smart_mete  | SMART_METE | text      | text        |
| Yes      | series tag     | activesens  | ACTIVESENS | text      | text        |
| Yes      | series tag     | jurisdicti  | JURISDICTI | text      | text        |
| Yes      | series tag     | on_off_str  | ON_OFF_STR | text      | text        |
| Yes      | series tag     | osp_id      | OSP_ID     | text      | number      |
| Yes      | series tag     | ratearea    | RATEAREA   | text      | text        |
| Yes      | series tag     | sfparkarea  | SFPARKAREA | text      | text        |
| Yes      | series tag     | street_num  | STREET_NUM | text      | number      |
| Yes      | series tag     | streetname  | STREETNAME | text      | text        |
| Yes      | numeric metric | street_seg  | STREET_SEG | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:uf55-k7py d:2013-05-07T11:06:09.000Z t:on_off_str=ON t:activesens=N t:ratearea=MC3 t:street_num=1104 t:cap_color=Black t:ms_id=324-11040 t:post_id=324-11041 t:smart_mete=N t:meter_type=MS t:jurisdicti=SFMTA t:osp_id=0 t:streetname="BATTERY ST" t:ms_spaceid=1 m:street_seg=2767000

series e:uf55-k7py d:2013-05-07T11:06:09.000Z t:on_off_str=ON t:activesens=N t:ratearea=MC3 t:street_num=225 t:cap_color=Black t:ms_id=- t:post_id=700-02250 t:smart_mete=N t:meter_type=SS t:jurisdicti=SFMTA t:osp_id=0 t:streetname="VALENCIA ST" t:ms_spaceid=0 m:street_seg=13055000

series e:uf55-k7py d:2013-05-07T11:06:09.000Z t:on_off_str=ON t:activesens=N t:ratearea=PortMC1 t:street_num=556 t:cap_color=Black t:ms_id=- t:post_id=830-05560 t:smart_mete=Y t:meter_type=SS t:jurisdicti=PORT t:osp_id=0 t:streetname="EMBARCADERO NORTH" t:ms_spaceid=0 m:street_seg=12556102
```

## Meta Commands

```ls
metric m:street_seg p:integer l:STREET_SEG t:dataTypeName=number

entity e:uf55-k7py l:"Metered motorcycle spaces" t:attribution="SFMTA, SFpark" t:url=https://data.sfgov.org/api/views/uf55-k7py

property e:uf55-k7py t:meta.view v:id=uf55-k7py v:category=Transportation v:attributionLink=http://sfpark.org/resources/motorcycle-parking-census-gis-data/ v:averageRating=0 v:name="Metered motorcycle spaces" v:attribution="SFMTA, SFpark"

property e:uf55-k7py t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:uf55-k7py t:meta.view.owner v:id=zn8n-8wyr v:screenName="Leslie Bienenfeld" v:displayName="Leslie Bienenfeld"

property e:uf55-k7py t:meta.view.tableauthor v:id=zn8n-8wyr v:screenName="Leslie Bienenfeld" v:roleName=editor v:displayName="Leslie Bienenfeld"
```

## Top Records

```ls
| :updated_at | id | post_id   | ms_id     | ms_spaceid | cap_color | meter_type | smart_mete | activesens | jurisdicti | on_off_str | osp_id | ratearea | sfparkarea        | street_num | streetname        | street_seg | 
| =========== | == | ========= | ========= | ========== | ========= | ========== | ========== | ========== | ========== | ========== | ====== | ======== | ================= | ========== | ================= | ========== | 
| 1367924769  | 1  | 324-11041 | 324-11040 | 1          | Black     | MS         | N          | N          | SFMTA      | ON         | 0      | MC3      |                   | 1104       | BATTERY ST        | 2767000    | 
| 1367924769  | 2  | 700-02250 | -         | 0          | Black     | SS         | N          | N          | SFMTA      | ON         | 0      | MC3      |                   | 225        | VALENCIA ST       | 13055000   | 
| 1367924769  | 3  | 830-05560 | -         | 0          | Black     | SS         | Y          | N          | PORT       | ON         | 0      | PortMC1  |                   | 556        | EMBARCADERO NORTH | 12556102   | 
| 1367924769  | 4  | 330-03300 | -         | 0          | Black     | SS         | Y          | N          | SFMTA      | ON         | 0      | MC5      | South Embarcadero | 330        | BRANNAN ST        | 3075000    | 
| 1367924769  | 5  | 593-00031 | 593-00030 | 1          | Black     | MS         | N          | N          | SFMTA      | ON         | 0      | MC5      | Downtown          | 3          | OFARRELL ST       | 9720000    | 
| 1367924769  | 6  | 464-03241 | 464-03240 | 1          | Black     | MS         | N          | N          | SFMTA      | ON         | 0      | MC5      | Civic Center      | 324        | HAYES ST          | 6815000    | 
| 1367924769  | 7  | 462-18050 | -         | 0          | Black     | SS         | N          | N          | SFMTA      | ON         | 0      | MC3      |                   | 1805       | HAIGHT ST         | 6624000    | 
| 1367924769  | 8  | 440-08401 | 440-08400 | 1          | Black     | MS         | N          | N          | SFMTA      | ON         | 0      | MC3      |                   | 840        | GEARY ST          | 6116000    | 
| 1367924769  | 9  | 209-04620 | -         | 0          | Black     | SS         | N          | N          | SFMTA      | ON         | 0      | MC3      |                   | 462        | 09TH ST           | 458000     | 
| 1367924769  | 10 | 440-38180 | -         | 0          | Black     | SS         | N          | N          | SFMTA      | ON         | 0      | MC3      |                   | 3818       | GEARY BLVD        | 6058201    | 
```