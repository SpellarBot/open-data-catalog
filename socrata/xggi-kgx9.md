# Directory of Family Justice Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-family-justice-centers-e0b93) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xggi-kgx9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xggi-kgx9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xggi-kgx9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xggi-kgx9 |
| Name | Directory of Family Justice Centers |
| Attribution | Mayor's Office to Combat Domestic Violence (OCDV) |
| Category | Social Services |
| Tags | ocdv, combat, domestic violence, jobs, economic mobility, family justice, jobs and economic mobility |
| Created | 2013-03-19T18:37:38Z |
| Publication Date | 2013-03-19T21:02:55Z |

## Description

List of Family Justice Centers in New York City

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | borough          | Borough          | text      | text        |
| Yes      | series tag  | facility_name    | Facility Name    | text      | text        |
| Yes      | series tag  | street_address   | Street Address   | text      | text        |
| Yes      | series tag  | city             | City             | text      | text        |
| Yes      | series tag  | state            | State            | text      | text        |
| Yes      | series tag  | zip_code         | Zip Code         | text      | text        |
| Yes      | series tag  | telephone_number | Telephone Number | text      | text        |
| Yes      | series tag  | timings          | Timings          | text      | text        |
| Yes      | series tag  | comments         | Comments         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xggi-kgx9 d:2013-03-19T11:37:45.000Z t:telephone_number=718-250-5111 t:facility_name="Family Justice Center" t:timings="M-F - 9 AM - 5 PM" t:state=NY t:borough=Brooklyn t:street_address="350 Jay Street" t:comments="Walk-in Services are available" t:city=Brooklyn m:row_number.xggi-kgx9=1

series e:xggi-kgx9 d:2013-03-19T11:37:45.000Z t:telephone_number=718-508-1222 t:facility_name="Family Justice Center" t:timings="M-F - 9 AM - 5 PM" t:state=NY t:borough=Bronx t:street_address="198 E. 161st Street" t:comments="Walk-in Services are available" t:city=Bronx m:row_number.xggi-kgx9=2

series e:xggi-kgx9 d:2013-03-19T11:37:45.000Z t:telephone_number=718-575-4500 t:facility_name="Family Justice Center" t:timings="M-F - 9 AM - 5 PM" t:state=NY t:borough=Queens t:street_address="126-02 82nd Avenue" t:comments="Walk-in Services are available" t:city=Queens m:row_number.xggi-kgx9=3
```

## Meta Commands

```ls
metric m:row_number.xggi-kgx9 p:long l:"Row Number"

entity e:xggi-kgx9 l:"Directory of Family Justice Centers" t:attribution="Mayor's Office to Combat Domestic Violence (OCDV)" t:url=https://data.cityofnewyork.us/api/views/xggi-kgx9

property e:xggi-kgx9 t:meta.view v:id=xggi-kgx9 v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/ocdv/html/statistics_resources/providers.shtml v:averageRating=0 v:name="Directory of Family Justice Centers" v:attribution="Mayor's Office to Combat Domestic Violence (OCDV)"

property e:xggi-kgx9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xggi-kgx9 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | borough  | facility_name         | street_address      | city     | state | zip_code | telephone_number | timings           | comments                       | 
| =========== | ======== | ===================== | =================== | ======== | ===== | ======== | ================ | ================= | ============================== | 
| 1363693065  | Brooklyn | Family Justice Center | 350 Jay Street      | Brooklyn | NY    |          | 718-250-5111     | M-F - 9 AM - 5 PM | Walk-in Services are available | 
| 1363693065  | Bronx    | Family Justice Center | 198 E. 161st Street | Bronx    | NY    |          | 718-508-1222     | M-F - 9 AM - 5 PM | Walk-in Services are available | 
| 1363693065  | Queens   | Family Justice Center | 126-02 82nd Avenue  | Queens   | NY    |          | 718-575-4500     | M-F - 9 AM - 5 PM | Walk-in Services are available | 
```