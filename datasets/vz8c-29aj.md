# Borough Enrollment Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/borough-enrollment-offices-2c1fd) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vz8c-29aj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vz8c-29aj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vz8c-29aj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vz8c-29aj |
| Name | Borough Enrollment Offices |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | jobs and economic mobility, doe, education, enrollment, schools, borough, lifelong learning |
| Created | 2011-10-11T04:30:05Z |
| Publication Date | 2017-08-15T14:59:40Z |

## Description

Department of Education borough enrollment offices

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | borough          | Borough          | text      | text        |
| Yes      | series tag     | zip_code         | Postcode         | text      | number      |
| Yes      | series tag     | phone            | Phone            | text      | text        |
| Yes      | series tag     | districts_served | Districts Served | text      | text        |
| Yes      | series tag     | hours            | Hours            | text      | text        |
| No       |                | address          | Address          | text      | text        |
| No       |                | latitude         | Latitude         | number    | number      |
| No       |                | longitude        | Longitude        | number    | number      |
| Yes      | numeric metric | community_board  | Community Board  | number    | number      |
| Yes      | series tag     | council_district | Council District | text      | number      |
| Yes      | numeric metric | census_tract     | Census Tract     | number    | number      |
| Yes      | numeric metric | bin              | BIN              | number    | number      |
| Yes      | numeric metric | bbl              | BBL              | number    | number      |
| Yes      | series tag     | nta              | NTA              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:vz8c-29aj d:2017-08-15T14:56:19.000Z t:hours="Monday-Friday, 8:00am-3:00pm" t:phone=718-935-2178 t:districts_served="7, 9, 10" t:nta=Belmont t:borough=Bronx t:council_district=15 t:zip_code=10458 m:community_board=6 m:census_tract=387

series e:vz8c-29aj d:2017-08-15T14:56:19.000Z t:hours="Monday-Friday, 8:00am-3:00pm" t:phone=718-935-2313 t:districts_served="17, 18, 22" t:nta=Midwood t:borough=Brooklyn t:council_district=48 t:zip_code=11230 m:bin=3180747 m:community_board=14 m:bbl=3067390077 m:census_tract=538

series e:vz8c-29aj d:2017-08-15T14:56:19.000Z t:hours="Monday-Friday, 8:00am-3:00pm" t:phone=718-935-2371 t:districts_served="13, 14, 15, 16" t:nta="Fort Greene" t:borough="Brooklyn (Note: General Education Only)" t:council_district=35 t:zip_code=11217 m:bin=3058752 m:community_board=2 m:bbl=3020980013 m:census_tract=33
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:bin p:integer l:BIN t:dataTypeName=number

metric m:bbl p:long l:BBL t:dataTypeName=number

entity e:vz8c-29aj l:"Borough Enrollment Offices" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vz8c-29aj

property e:vz8c-29aj t:meta.view d:2017-09-25T07:26:30.799Z v:averageRating=0 v:name="Borough Enrollment Offices" v:attribution="Department of Education (DOE)" v:id=vz8c-29aj v:category=Education

property e:vz8c-29aj t:meta.view.owner d:2017-09-25T07:26:30.799Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:vz8c-29aj t:meta.view.tableauthor d:2017-09-25T07:26:30.799Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough                                 | zip_code | phone        | districts_served | hours                        | address                                              | latitude  | longitude  | community_board | council_district | census_tract | bin     | bbl        | nta                                                      | 
| =========== | ======================================= | ======== | ============ | ================ | ============================ | ==================================================== | ========= | ========== | =============== | ================ | ============ | ======= | ========== | ======================================================== | 
| 1502808979  | Bronx                                   | 10458    | 718-935-2178 | 7, 9, 10         | Monday-Friday, 8:00am-3:00pm | 1 Fordham Plaza                                      | 40.860994 | -73.890073 | 6               | 15               | 387          |         |            | Belmont                                                  | 
| 1502808979  | Brooklyn                                | 11230    | 718-935-2313 | 17, 18, 22       | Monday-Friday, 8:00am-3:00pm | 1780 Ocean Avenue                                    | 40.618915 | -73.955115 | 14              | 48               | 538          | 3180747 | 3067390077 | Midwood                                                  | 
| 1502808979  | Brooklyn (Note: General Education Only) | 11217    | 718-935-2371 | 13, 14, 15, 16   | Monday-Friday, 8:00am-3:00pm | 29 Fort Greene Place (Note: General Education Only)  | 40.688834 | -73.976905 | 2               | 35               | 33           | 3058752 | 3020980013 | Fort Greene                                              | 
| 1502808979  | Brooklyn (Note: Special Education Only) | 11201    | 718-935-4908 | 13, 14, 15, 16   | Monday-Friday, 8:00am-3:00pm | 131 Livingston Street (Note: Special Education Only) | 40.690743 | -73.988605 | 2               | 33               | 37           | 3000420 | 3001540001 | DUMBO-Vinegar Hill-Downtown Brooklyn-Boerum Hill         | 
| 1502808979  | Brooklyn                                | 11209    | 718-935-2331 | 20, 21           | Monday-Friday, 8:00am-3:00pm | 415 89th Street                                      | 40.619931 | -74.028086 | 10              | 43               | 160          | 3154215 | 3060650043 | Bay Ridge                                                | 
| 1502808979  | Brooklyn                                | 11233    | 718-935-2340 | 19, 23, 32       | Monday-Friday, 8:00am-3:00pm | 1665 St Mark's Avenue                                | 40.673138 | -73.912024 | 16              | 41               | 36501        | 3039123 | 3014540054 | Ocean Hill                                               | 
| 1502808979  | Bronx                                   | 10462    | 718-935-2278 | 8, 11, 12        | Monday-Friday, 8:00am-3:00pm | 1230 Zerega Avenue                                   | 40.833586 | -73.845099 | 9               | 13               | 96           | 2027195 | 2038420002 | Westchester-Unionport                                    | 
| 1502808979  | Manhattan                               | 10001    | 718-935-2383 | 1, 2, 4          | Monday-Friday, 8:00am-3:00pm | 333 Seventh Avenue                                   | 40.747629 | -73.99306  | 5               | 3                | 95           | 1015097 | 1008040001 | Midtown-Midtown South                                    | 
| 1502808979  | Staten Island                           | 10301    | 718-935-2402 | 31               | Monday-Friday, 8:00am-3:00pm | 718 Ocean Terrace                                    | 40.608405 | -74.101919 | 2               | 50               | 177          | 1015097 | 1008040001 | Todt Hill-Emerson Hill-Heartland Village-Lighthouse Hill | 
| 1502808979  | Queens                                  | 11354    | 718-935-2391 | 25, 26           | Monday-Friday, 8:00am-3:00pm | 30 48 Linden Place                                   | 40.770185 | -73.832925 | 7               | 20               | 869          | 4100749 | 4043700050 | Flushing                                                 | 
```