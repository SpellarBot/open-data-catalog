# Community Health Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-health-centers-48f3e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/b2sp-asbg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/b2sp-asbg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/b2sp-asbg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | b2sp-asbg |
| Name | Community Health Centers |
| Attribution | Human Resources Administration (HRA) |
| Category | City Government |
| Tags | jobs and economic mobility, human resources administration, hra, community, health |
| Created | 2013-03-19T18:20:29Z |
| Publication Date | 2013-06-21T20:05:55Z |

## Description

This table represents the details of the Community Health Centers distributed by Borough along with their address, Zip and phone number detail.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | name_of_borough  | Name of Borough  | text      | text        |
| Yes      | series tag  | name_of_center   | Name of Center   | text      | text        |
| No       |             | center_address   | Center Address   | text      | text        |
| Yes      | series tag  | zip              | Zip              | text      | text        |
| Yes      | series tag  | telephone_number | Telephone Number | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = center_address
```

## Data Commands

```ls
series e:b2sp-asbg d:2013-03-19T11:20:35.000Z t:zip=10456 t:telephone_number="(718) 466-6072" t:name_of_center="Bronx-Lebanon Hospital Center" t:name_of_borough=Bronx m:row_number.b2sp-asbg=1

series e:b2sp-asbg d:2013-03-19T11:20:35.000Z t:zip=10456 t:telephone_number="(718) 579-2500" t:name_of_center="Comprehensive Family Care Center" t:name_of_borough=Bronx m:row_number.b2sp-asbg=2

series e:b2sp-asbg d:2013-03-19T11:20:35.000Z t:zip=10461 t:telephone_number="(718) 503-7714" t:name_of_center="Dr. Martin Luther King Jr. Health Center" t:name_of_borough=Bronx m:row_number.b2sp-asbg=3
```

## Meta Commands

```ls
metric m:row_number.b2sp-asbg p:long l:"Row Number"

entity e:b2sp-asbg l:"Community Health Centers" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/b2sp-asbg

property e:b2sp-asbg t:meta.view v:id=b2sp-asbg v:category="City Government" v:attributionLink=http://www.nyc.gov/html/hia/html/resources/community.shtml v:averageRating=0 v:name="Community Health Centers" v:attribution="Human Resources Administration (HRA)"

property e:b2sp-asbg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:b2sp-asbg t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | name_of_borough | name_of_center                             | center_address                     | zip   | telephone_number | 
| =========== | =============== | ========================================== | ================================== | ===== | ================ | 
| 1363692035  | Bronx           | Bronx-Lebanon Hospital Center              | 1276 Fulton Avenue, Suite 401-402  | 10456 | (718) 466-6072   | 
| 1363692035  | Bronx           | Comprehensive Family Care Center           | 1265 Franklin Avenue               | 10456 | (718) 579-2500   | 
| 1363692035  | Bronx           | Dr. Martin Luther King Jr. Health Center   | (Montefiore) 1621 Eastchester Road | 10461 | (718) 503-7714   | 
| 1363692035  | Bronx           | Montefiore Family Health Center            | 360 East 193rd Street              | 10458 | (718) 933-2400   | 
| 1363692035  | Bronx           | Montefiore Medical Group Comprehensive HCC | 305 East 161st Street              | 10451 | (718) 579-2597   | 
| 1363692035  | Bronx           | Morris Heights Health Center               | Morris Heights Health Center       | 10453 | (718) 716-4400   | 
| 1363692035  | Bronx           | Soundview Health Center                    | 731 White Plains Road              | 10473 | (718) 589-2232   | 
| 1363692035  | Bronx           | Urban Health Plan                          | 1065 Southern Boulevard            | 10459 | (718) 991-4833   | 
| 1363692035  | Brooklyn        | Bedford/Stuyvesant Family Health Center    | 1413 Fulton Street                 | 11216 | (718) 636-4500   | 
| 1363692035  | Brooklyn        | Brooklyn Plaza Medical Center              | 650 Fulton Street                  | 11217 | (718) 596-9896   | 
```