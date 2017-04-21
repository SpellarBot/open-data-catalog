# All Systems Permit (No Restrictions - Street Level)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/all-systems-permit-unrestricted-routes) |
| Metadata | [Link](https://data.iowa.gov/api/views/rb2c-eid3) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/rb2c-eid3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/rb2c-eid3/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | rb2c-eid3 |
| Name | All Systems Permit (No Restrictions - Street Level) |
| Attribution | Iowa Department of Transportation - Office of Motor Carrier Services, Office of Research and Analytics |
| Category | Transportation & Utilities |
| Tags | asset, classification, routes, restrictions, unrestricted, permit, systems permit, iowa dot, iowa department of transportation |
| Created | 2016-06-09T02:42:14Z |
| Publication Date | 2016-06-09T02:43:46Z |

## Description

Displays all non-restricted local road segments in the state of Iowa. Specific route information is only available once zoomed into the county level. County restriction map can be found here: http://www.iowadot.gov/mvd/motorcarriers/systemmap.htm#county   Check with local officials when traveling on county roads or city streets for bridge embargo, detour, road embargo and vertical clearance information. State and interstate highways are valid routes except for restrictions listed on the bridge embargo, detour and road embargo, and vertical clearance maps located at http://www.iowadot.gov/mvd/motorcarriers/omcsMaps.htm.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type  | Render Type |
| ======== | ============== | ======================= | ======================= | ========== | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data  | meta_data   |
| Yes      | series tag     | contact_name            | CONTACT_NAME            | text       | text        |
| Yes      | series tag     | contact_number          | CONTACT_NUMBER          | text       | text        |
| Yes      | series tag     | contact_email           | CONTACT_EMAIL           | text       | text        |
| Yes      | series tag     | restriction_description | RESTRICTION_DESCRIPTION | text       | text        |
| Yes      | series tag     | weight_restriction      | WEIGHT_RESTRICTION      | text       | text        |
| Yes      | series tag     | height_restriction      | HEIGHT_RESTRICTION      | text       | text        |
| Yes      | series tag     | county_no               | COUNTY_NO               | text       | number      |
| Yes      | series tag     | geographic_extent_name  | GEOGRAPHIC_EXTENT_NAME  | text       | text        |
| Yes      | series tag     | full_name               | FULL_NAME               | text       | text        |
| Yes      | series tag     | route_system_id         | ROUTE_SYSTEM_ID         | text       | number      |
| Yes      | numeric metric | shape_len               | SHAPE.LEN               | number     | number      |
| Yes      | series tag     | objectid                | OBJECTID                | text       | number      |
| No       |                | shape                   | SHAPE                   | geospatial | geospatial  |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:shape_len p:long l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:rb2c-eid3 l:"All Systems Permit (No Restrictions - Street Level)" t:attribution="Iowa Department of Transportation - Office of Motor Carrier Services, Office of Research and Analytics" t:url=https://data.iowa.gov/api/views/rb2c-eid3

property e:rb2c-eid3 t:meta.view v:id=rb2c-eid3 v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Pavement_Management/All_Systems_Permit/MapServer/1 v:averageRating=0 v:name="All Systems Permit (No Restrictions - Street Level)" v:attribution="Iowa Department of Transportation - Office of Motor Carrier Services, Office of Research and Analytics"

property e:rb2c-eid3 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:rb2c-eid3 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | contact_name           | contact_number       | contact_email                  | restriction_description | weight_restriction | height_restriction | county_no | geographic_extent_name | full_name            | route_system_id | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| =========== | ====================== | ==================== | ============================== | ======================= | ================== | ================== | ========= | ====================== | ==================== | =============== | ========= | ======== | =============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 0           | DENNIS MICHAEL         | 563-263-6351 EXT.102 | dmichael@co.muscatine.ia.us    | NO RESTRICTIONS         | N                  | N                  | 70        | COUNTY OF MUSCATINE    | 4TH ST, N            | 4               |           | 1        | [null, 41.578292573000056, -91.07960640599998, null, false, {paths=[[[-91.07960640599998, 41.578292573000056], [-91.07960021599996, 41.57436434700003], [-91.07947846299999, 41.574182955000026], [-91.07920488799994, 41.574017602000026]]]}]                                                                                                                                                                                                                                                                                                                                                                                  | 
| 0           | JASON ETNYRE           | 515-295-2411         | jetnure@ci.algona.ia.us        | NO RESTRICTIONS         | N                  | N                  | 55        | CITY OF ALGONA         | N VALLEY ST, N       | 4               |           | 2        | [null, 43.075822506000065, -94.23302867299998, null, false, {paths=[[[-94.23302867299998, 43.075822506000065], [-94.23301671699994, 43.076542181000036]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 0           | DYLAN FEIK             | 641-828-0550         | acm@knoxvilleia.gov            | NO RESTRICTIONS         | N                  | N                  | 63        | CITY OF KNOXVILLE      | ASH ST, E            | 4               |           | 3        | [null, 41.32336133900003, -93.10646902199994, null, false, {paths=[[[-93.10646902199994, 41.32336133900003], [-93.10756669199998, 41.32343285700006], [-93.10950820599999, 41.32343353400006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                               | 
| 0           | MIKKI STEGEN           | 563-568-4574         | mstegen@co.allamakee.ia.us     | NO RESTRICTIONS         | N                  | N                  | 3         | COUNTY OF ALLAMAKEE    | DOTUR CHURCH 3 RD, N | 4               |           | 4        | [null, 43.47042097800005, -91.45238354099996, null, false, {paths=[[[-91.45238354099996, 43.47042097800005], [-91.45106732099998, 43.47179341700007], [-91.45091550199999, 43.47669607000006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                               | 
| 0           | MIKKI STEGEN           | 563-568-4574         | mstegen@co.allamakee.ia.us     | NO RESTRICTIONS         | N                  | N                  | 3         | COUNTY OF ALLAMAKEE    | SUMMERSET RD, S      | 4               |           | 5        | [null, 43.18886182400007, -91.37486853299998, null, false, {paths=[[[-91.37486853299998, 43.18886182400007], [-91.37474321699995, 43.18952902700005]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 0           | PAUL GEILENFELDT, P.E. | 641-754-6343         | pgeilenfeldt@co.marshall.ia.us | NOT RESTRICTED          | N                  | N                  | 64        | COUNTY OF MARSHALL     | LORAY RD, E          | 4               |           | 6        | [null, 41.999964918000046, -92.96062570099997, null, false, {paths=[[[-92.96062570099997, 41.999964918000046], [-92.96307293799998, 41.99988066600008], [-92.96902247399998, 41.999942660000045], [-92.97945974099997, 41.99992483300008], [-92.97957710599997, 41.99983782900006], [-92.97959825499998, 41.99967653300007], [-92.97939543799998, 41.99304688900003], [-92.97948399999996, 41.99289497500007], [-92.97967955799999, 41.99281649100004], [-92.99984896599994, 41.99296629400004]]]}]                                                                                                                             | 
| 0           | SCOTT RINEHART         | 712-262-2825         | srinehart@co.clay.ia.us        | NO RESTRICTIONS         | N                  | N                  | 71        | COUNTY OF CLAY         | 450TH ST, E          | 4               |           | 7        | [null, 42.99616464400003, -95.38876383099995, null, false, {paths=[[[-95.38876383099995, 42.99616464400003], [-95.36867916299997, 42.99613111900004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 0           | JOHN WADDINGHAM        | 641-456-4671         | jwaddingham@co.franklin.ia.us  | NO RESTRICTIONS         | N                  | N                  | 99        | COUNTY OF FRANKLIN     | 140TH ST, E          | 4               |           | 8        | [null, 42.73132802200007, -93.49884308699995, null, false, {paths=[[[-93.49884308699995, 42.73132802200007], [-93.47820681799999, 42.73137110000005]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 0           | MIKKI STEGEN           | 563-568-4574         | mstegen@co.allamakee.ia.us     |                         | N                  | N                  | 3         | CITY OF NEW ALBIN      | CHERRY ST, S         | 4               |           | 9        | [null, 43.497267763000025, -91.28392054099999, null, false, {paths=[[[-91.28392054099999, 43.497267763000025], [-91.28395054199996, 43.49739040000003], [-91.28541733999998, 43.49862774800005]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| 0           | MIKKI STEGEN           | 563-568-4574         | mstegen@co.allamakee.ia.us     | NO RESTRICTIONS         | N                  | N                  | 3         | COUNTY OF ALLAMAKEE    | FOLEY DR, E          | 4               |           | 10       | [null, 43.19597487200008, -91.19163850499996, null, false, {paths=[[[-91.19163850499996, 43.19597487200008], [-91.18798068699994, 43.196034747000056], [-91.18727017799995, 43.19595994100007], [-91.18639461199996, 43.19572459600005], [-91.18553422899998, 43.19534299800006], [-91.18469852399994, 43.19508698300007], [-91.18172725299996, 43.194849427000065], [-91.18088827499997, 43.19455042700008], [-91.17921894999995, 43.19372025000007], [-91.17891496299995, 43.19374996300007], [-91.17708357499998, 43.194392734000076], [-91.17557869899997, 43.195056263000026], [-91.17526319199999, 43.19526445400004]]]}] | 
```