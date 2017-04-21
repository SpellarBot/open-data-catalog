# Directory of Food Stamp Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-food-stamp-centers-2b8f5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tc6u-8rnp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tc6u-8rnp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tc6u-8rnp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tc6u-8rnp |
| Name | Directory of Food Stamp Centers |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | hra, human resources, food stamps, jobs, economic mobility, jobs and economic mobility |
| Created | 2013-03-19T18:36:44Z |
| Publication Date | 2013-03-19T20:39:49Z |

## Description

List of Food Stamp Centers in New York City by Borough

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | borough         | Borough         | text      | text        |
| Yes      | series tag  | facility_name   | Facility Name   | text      | text        |
| Yes      | series tag  | street_address  | Street Address  | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | zip_code        | Zip Code        | text      | text        |
| Yes      | series tag  | state           | State           | text      | text        |
| Yes      | series tag  | phone_number_s_ | Phone Number(s) | text      | text        |
| Yes      | series tag  | comments        | Comments        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tc6u-8rnp d:2013-03-19T11:37:06.000Z t:phone_number_s_=718-333-3275/718-333-3033 t:zip_code=11224 t:facility_name="Coney Island" t:state=NY t:borough=Brooklyn t:street_address="30-50 West 21 Street, 1st flr" t:city=Brooklyn m:row_number.tc6u-8rnp=1

series e:tc6u-8rnp d:2013-03-19T11:37:06.000Z t:phone_number_s_=718-827-3961/718-827-3444 t:zip_code=11208 t:facility_name="East New York" t:state=NY t:borough=Brooklyn t:street_address="404 Pine Street, 1st Floor" t:city=Brooklyn m:row_number.tc6u-8rnp=2

series e:tc6u-8rnp d:2013-03-19T11:37:06.000Z t:phone_number_s_=718-473-8510/718-694-8196 t:zip_code=11217 t:facility_name="Ft. Greene" t:state=NY t:borough=Brooklyn t:street_address="275 Bergen Street, 1st Floor" t:comments="Extended Hours - Mon. - Fri. 8:30 - 6 pm, Sat 9:00 am to 5:00 pm" t:city=Brooklyn m:row_number.tc6u-8rnp=3
```

## Meta Commands

```ls
metric m:row_number.tc6u-8rnp p:long l:"Row Number"

entity e:tc6u-8rnp l:"Directory of Food Stamp Centers" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/tc6u-8rnp

property e:tc6u-8rnp t:meta.view v:id=tc6u-8rnp v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/hra/html/directory/food_stamp_centers.shtml v:averageRating=0 v:name="Directory of Food Stamp Centers" v:attribution="Human Resources Administration (HRA)"

property e:tc6u-8rnp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tc6u-8rnp t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | borough   | facility_name  | street_address                  | city     | zip_code | state | phone_number_s_            | comments                                                         | 
| =========== | ========= | ============== | =============================== | ======== | ======== | ===== | ========================== | ================================================================ | 
| 1363693026  | Brooklyn  | Coney Island   | 30-50 West 21 Street, 1st flr   | Brooklyn | 11224    | NY    | 718-333-3275/718-333-3033  |                                                                  | 
| 1363693026  | Brooklyn  | East New York  | 404 Pine Street, 1st Floor      | Brooklyn | 11208    | NY    | 718-827-3961/718-827-3444  |                                                                  | 
| 1363693026  | Brooklyn  | Ft. Greene     | 275 Bergen Street, 1st Floor    | Brooklyn | 11217    | NY    | 718-473-8510/718-694-8196  | Extended Hours - Mon. - Fri. 8:30 - 6 pm, Sat 9:00 am to 5:00 pm | 
| 1363693026  | Brooklyn  | North Brooklyn | 500 Dekalb Avenue, 4rd Floor    | Brooklyn | 11205    | NY    | 718-398-5057/718-636-7046  |                                                                  | 
| 1363693026  | Brooklyn  | Williamsburg   | 30 Thornton Street, 4th Floor   | Brooklyn | 11206    | NY    | 718-963-5115/718-963-5140  |                                                                  | 
| 1363693026  | Bronx     | Concourse      | 1375 Jerome Avenue, 2nd Floor   | Bronx    | 10452    | NY    | 718-637-2401/718-590-7235  | Extended Hours - Mon. - Fri. 8:30 - 6 pm, Sat 9:00 am to 5:00 pm | 
| 1363693026  | Bronx     | Crotona        | 1910 Monterey Avenue, 5th Floor | Bronx    | 10457    | NY    | 718-901-0287/ 718-901-5459 |                                                                  | 
| 1363693026  | Bronx     | Melrose        | 260 East 161 Street             | Bronx    | 10451    | NY    | 718-838-6353               | 8:30am-9am only                                                  | 
| 1363693026  | Bronx     | Melrose        | 260 East 161 Street             | Bronx    | 10451    | NY    | 718-838-6320               | work requirements                                                | 
| 1363693026  | Manhattan | East End       | 2322 Third Avenue, 3rd Floor    | New York | 10035    | NY    | 212-860-5159, 212-860-5147 |                                                                  | 
```