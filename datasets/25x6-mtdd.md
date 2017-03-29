# Interstate Closure Gates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/interstate-closure-gates) |
| Metadata | [Link](https://data.iowa.gov/api/views/25x6-mtdd) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/25x6-mtdd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/25x6-mtdd/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 25x6-mtdd |
| Name | Interstate Closure Gates |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, operations, gates, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-08T19:09:21Z |
| Publication Date | 2016-06-08T19:11:20Z |

## Description

This is a representation of all gates and barricades that prevent access to the interstates. It consists of mainline barricades (left and right) that are physically located in the median and shoulder of the interstate that can be automatically lowered to prevent travel in the event of a road closure. It also includes ramp barricades that prevent travel onto the interstate by means of the entrance ramps, denoted with a "Road Closed" sign posted on a gate.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | gate_id             | GATE_ID             | text      | text        |
| Yes      | series tag  | district            | DISTRICT            | text      | number      |
| Yes      | series tag  | cost_center         | COST_CENTER         | text      | text        |
| Yes      | series tag  | route               | ROUTE               | text      | number      |
| Yes      | series tag  | dirtravel           | DIRTRAVEL           | text      | text        |
| Yes      | series tag  | sideofroad          | SIDEOFROAD          | text      | text        |
| Yes      | series tag  | milepost            | MILEPOST            | text      | text        |
| No       |             | milepost_offset     | MILEPOST_OFFSET     | number    | number      |
| No       |             | latitude            | LATITUDE            | number    | number      |
| No       |             | longitude           | LONGITUDE           | number    | number      |
| Yes      | series tag  | sign_face_direction | SIGN_FACE_DIRECTION | text      | text        |
| Yes      | series tag  | signtype            | SIGNTYPE            | text      | text        |
| Yes      | series tag  | subcategory         | SUBCATEGORY         | text      | text        |
| Yes      | series tag  | description         | DESCRIPTION         | text      | text        |
| Yes      | series tag  | remarks             | REMARKS             | text      | text        |
| Yes      | series tag  | activation_type     | ACTIVATION_TYPE     | text      | text        |
| Yes      | series tag  | objectid            | OBJECTID            | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = milepost_offset,latitude,longitude
```

## Data Commands

```ls
series e:25x6-mtdd d:2016-06-08T19:09:21.000Z t:cost_center=551609 t:gate_id=A91341ADAF9244C890920563507EC3F4 t:activation_type=Manual t:milepost=159 t:description="Ramp Barricade" t:route=35 t:dirtravel=Ramp t:sideofroad=Left t:objectid=1 t:district=1 t:sign_face_direction=N t:signtype=Regulatory m:row_number.25x6-mtdd=1

series e:25x6-mtdd d:2016-06-08T19:09:21.000Z t:cost_center=554810 t:gate_id=0FA20C59470E43D88F65A88F67A49F2E t:activation_type=Remote t:milepost=75 t:description="Right Mainline Barricade" t:subcategory="No Subcategory" t:route=29 t:dirtravel="With Milepost (increasing in number)" t:sideofroad=Right t:objectid=2 t:district=4 t:sign_face_direction=S t:signtype=Guide m:row_number.25x6-mtdd=2

series e:25x6-mtdd d:2016-06-08T19:09:21.000Z t:cost_center=554810 t:gate_id=7EF1FEF2035948EEB2C197E3593193A1 t:activation_type=Manual t:milepost=75 t:description="Ramp Barricade" t:route=29 t:dirtravel=Ramp t:remarks="Sign face SE when gate is CLOSED" t:sideofroad=Right t:objectid=3 t:district=4 t:sign_face_direction=SE t:signtype=Regulatory m:row_number.25x6-mtdd=3
```

## Meta Commands

```ls
metric m:row_number.25x6-mtdd p:long l:"Row Number"

entity e:25x6-mtdd l:"Interstate Closure Gates" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/25x6-mtdd

property e:25x6-mtdd t:meta.view v:id=25x6-mtdd v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Closure_Gates/MapServer/0 v:averageRating=0 v:name="Interstate Closure Gates" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:25x6-mtdd t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:25x6-mtdd t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | gate_id                          | district | cost_center | route | dirtravel                            | sideofroad | milepost | milepost_offset                                       | latitude                                           | longitude                                          | sign_face_direction | signtype   | subcategory    | description              | remarks                           | activation_type | objectid | 
| =========== | ================================ | ======== | =========== | ===== | ==================================== | ========== | ======== | ===================================================== | ================================================== | ================================================== | =================== | ========== | ============== | ======================== | ================================= | =============== | ======== | 
| 0           | A91341ADAF9244C890920563507EC3F4 | 1        | 551609      | 35    | Ramp                                 | Left       | 159      | 0                                                     | 42.67302928000000150632331497035920619964599609375 | -93.458228439999999181964085437357425689697265625  | N                   | Regulatory |                | Ramp Barricade           |                                   | Manual          | 1        | 
| 0           | 0FA20C59470E43D88F65A88F67A49F2E | 4        | 554810      | 29    | With Milepost (increasing in number) | Right      | 75       | 0.556999980000000061153286878834478557109832763671875 | 41.547366670000002386586857028305530548095703125   | -95.917274439999999913197825662791728973388671875  | S                   | Guide      | No Subcategory | Right Mainline Barricade |                                   | Remote          | 2        | 
| 0           | 7EF1FEF2035948EEB2C197E3593193A1 | 4        | 554810      | 29    | Ramp                                 | Right      | 75       | 0                                                     | 41.55034672000000028901922632940113544464111328125 | -95.915291440000004286048351787030696868896484375  | SE                  | Regulatory |                | Ramp Barricade           | Sign face SE when gate is CLOSED  | Manual          | 3        | 
| 0           | 4145D287E43D4636ADA840E52115C535 | 4        | 554810      | 29    | Ramp                                 | Left       | 75       | 0                                                     | 41.55028166999999683639543945901095867156982421875 | -95.9158699999999981855580699630081653594970703125 | SW                  | Regulatory |                | Ramp Barricade           | Sign faces SW when gate is CLOSED | Manual          | 4        | 
| 0           | DC2C4EA0BCF843A48E39FAFB41A4C9E9 | 4        | 554810      | 29    | Ramp                                 | Right      | 75       | 0                                                     | 41.54974028000000174642991623841226100921630859375 | -95.918799500000005764377419836819171905517578125  | NW                  | Regulatory |                | Ramp Barricade           | Sign faces SW when gate is CLOSED | Manual          | 5        | 
| 0           | 99CA3ED3A19C48728CF8DD5DE6CB2F9B | 4        | 554810      | 29    | Ramp                                 | Right      | 82       | 0                                                     | 41.619990999999998848579707555472850799560546875   | -95.9850190599999990581636666320264339447021484375 | SE                  | Regulatory |                | Ramp Barricade           |                                   | Manual          | 6        | 
| 0           | A80C1D71578E4B77B5B47C6891478851 | 4        | 554810      | 29    | Ramp                                 | Left       | 82       | 0                                                     | 41.620055890000003273598849773406982421875         | -95.9857652799999954140730551443994045257568359375 | SW                  | Regulatory |                | Ramp Barricade           | Sign faces SW when gate is CLOSED | Manual          | 7        | 
| 0           | A2FBFFFBD4C2440194533446F37FE8BD | 4        | 554810      | 29    | Ramp                                 | Left       | 82       | 0                                                     | 41.6197058300000009012364898808300495147705078125  | -95.9901464400000037358040572144091129302978515625 | N                   | Regulatory |                | Ramp Barricade           | Sign faces N when gate is CLOSED  | Manual          | 8        | 
| 0           | C8A65EDDF7DF44EC8C835717825FB7AA | 4        | 554810      | 29    | Ramp                                 | Right      | 89       | 0                                                     | 41.71161316999999968402335071004927158355712890625 | -96.0424657800000005636320565827190876007080078125 | SE                  | Regulatory |                | Ramp Barricade           | Sign faces SE when gate is CLOSED | Manual          | 9        | 
| 0           | 12333EC00C504913996679EA1FE16EE  | 4        | 554810      | 29    | Ramp                                 | Left       | 89       | 0                                                     | 41.71102110999999723617293057031929492950439453125 | -96.046771780000000262589310295879840850830078125  | N                   | Regulatory |                | Ramp Barricade           |                                   | Manual          | 10       | 
```