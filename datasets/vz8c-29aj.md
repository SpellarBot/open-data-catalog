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
| Rows Updated | 2011-10-11T04:30:09Z |

## Description

Department of Education borough enrollment offices

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | borough          | Borough          | text      | text        |
| Yes      | numeric metric | zip_code         | Zip Code         | number    | number      |
| Yes      | series tag     | phone            | Phone            | text      | text        |
| Yes      | series tag     | districts_served | Districts Served | text      | text        |
| Yes      | series tag     | hours            | Hours            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vz8c-29aj d:2011-10-10T21:30:08.000Z t:phone=718-935-2178 t:hours="Monday-Friday, 8:00am-3:00pm" t:districts_served="7, 9, 10" t:borough=Bronx m:zip_code=10458

series e:vz8c-29aj d:2011-10-10T21:30:08.000Z t:phone=718-935-2313 t:hours="Monday-Friday, 8:00am-3:00pm" t:districts_served="17, 18, 22" t:borough=Brooklyn m:zip_code=11230

series e:vz8c-29aj d:2011-10-10T21:30:08.000Z t:phone=718-935-2371 t:hours="Monday-Friday, 8:00am-3:00pm" t:districts_served="13, 14, 15, 16" t:borough="Brooklyn (Note: General Education Only)" m:zip_code=11217
```

## Meta Commands

```ls
metric m:zip_code l:"Zip Code" t:dataTypeName=number

entity e:vz8c-29aj l:"Borough Enrollment Offices" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/vz8c-29aj

property e:vz8c-29aj t:meta.view d:2017-03-10T14:35:23.591Z v:id=vz8c-29aj v:category=Education v:averageRating=0 v:name="Borough Enrollment Offices" v:attribution="Department of Education (DOE)"

property e:vz8c-29aj t:meta.view.owner d:2017-03-10T14:35:23.591Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:vz8c-29aj t:meta.view.tableauthor d:2017-03-10T14:35:23.591Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```