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
| Publication Date | 2011-10-11T04:31:19Z |

## Description

Department of Education borough enrollment offices

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | borough          | Borough          | text      | text        |
| Yes      | series tag  | zip_code         | Zip Code         | text      | number      |
| Yes      | series tag  | phone            | Phone            | text      | text        |
| Yes      | series tag  | districts_served | Districts Served | text      | text        |
| Yes      | series tag  | hours            | Hours            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vz8c-29aj d:2011-10-10T21:30:08.000Z t:phone=718-935-2178 t:zip_code=10458 t:hours="Monday-Friday, 8:00am-3:00pm" t:districts_served="7, 9, 10" t:borough=Bronx m:row_number.vz8c-29aj=1

series e:vz8c-29aj d:2011-10-10T21:30:08.000Z t:phone=718-935-2313 t:zip_code=11230 t:hours="Monday-Friday, 8:00am-3:00pm" t:districts_served="17, 18, 22" t:borough=Brooklyn m:row_number.vz8c-29aj=2

series e:vz8c-29aj d:2011-10-10T21:30:08.000Z t:phone=718-935-2371 t:zip_code=11217 t:hours="Monday-Friday, 8:00am-3:00pm" t:districts_served="13, 14, 15, 16" t:borough="Brooklyn (Note: General Education Only)" m:row_number.vz8c-29aj=3
```

## Meta Commands

```ls
metric m:row_number.vz8c-29aj p:long l:"Row Number"

entity e:vz8c-29aj l:"Borough Enrollment Offices" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vz8c-29aj

property e:vz8c-29aj t:meta.view d:2017-06-09T13:55:08.624Z v:id=vz8c-29aj v:category=Education v:averageRating=0 v:name="Borough Enrollment Offices" v:attribution="Department of Education (DOE)"

property e:vz8c-29aj t:meta.view.owner d:2017-06-09T13:55:08.624Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:vz8c-29aj t:meta.view.tableauthor d:2017-06-09T13:55:08.624Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough                                 | zip_code | phone        | districts_served | hours                        | 
| =========== | ======================================= | ======== | ============ | ================ | ============================ | 
| 1318282208  | Bronx                                   | 10458    | 718-935-2178 | 7, 9, 10         | Monday-Friday, 8:00am-3:00pm | 
| 1318282208  | Brooklyn                                | 11230    | 718-935-2313 | 17, 18, 22       | Monday-Friday, 8:00am-3:00pm | 
| 1318282208  | Brooklyn (Note: General Education Only) | 11217    | 718-935-2371 | 13, 14, 15, 16   | Monday-Friday, 8:00am-3:00pm | 
| 1318282208  | Brooklyn (Note: Special Education Only) | 11201    | 718-935-4908 | 13, 14, 15, 16   | Monday-Friday, 8:00am-3:00pm | 
| 1318282208  | Brooklyn                                | 11209    | 718-935-2331 | 20, 21           | Monday-Friday, 8:00am-3:00pm | 
| 1318282208  | Brooklyn                                | 11233    | 718-935-2340 | 19, 23, 32       | Monday-Friday, 8:00am-3:00pm | 
| 1318282208  | Manhattan                               | 10027    | 718-935-2385 | 3, 5, 6          | Monday-Friday, 8:00am-3:00pm | 
| 1318282208  | Bronx                                   | 10462    | 718-935-2278 | 8, 11, 12        | Monday-Friday, 8:00am-3:00pm | 
| 1318282208  | Manhattan                               | 10001    | 718-935-2383 | 1, 2, 4          | Monday-Friday, 8:00am-3:00pm | 
| 1318282209  | Staten Island                           | 10301    | 718-935-2402 | 31               | Monday-Friday, 8:00am-3:00pm | 
```