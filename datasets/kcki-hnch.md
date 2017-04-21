# Chicago Department of Public Health Clinic Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chicago-department-of-public-health-clinic-locations-0cc3b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kcki-hnch) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kcki-hnch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kcki-hnch/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kcki-hnch |
| Name | Chicago Department of Public Health Clinic Locations |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | facilities, public health, clinics, sti, std, wic, mental health, case management, healthy start, healthy families |
| Created | 2016-05-24T20:50:53Z |
| Publication Date | 2016-06-07T20:24:34Z |

## Description

City of Chicago Mental Health, Sexually Transmitted Infection (STI) Specialty, and Women Infant Children (WIC) clinic locations, hours of operation and contact information.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | site_name                | Site Name                | text      | text        |
| Yes      | series tag  | clinic_type              | Clinic Type              | text      | text        |
| Yes      | series tag  | site_number              | Site Number              | text      | number      |
| Yes      | series tag  | hours_of_operation       | Hours of Operation       | text      | text        |
| Yes      | series tag  | street_address           | Street Address           | text      | text        |
| Yes      | series tag  | city                     | City                     | text      | text        |
| Yes      | series tag  | state                    | State                    | text      | text        |
| Yes      | series tag  | zip                      | ZIP                      | text      | text        |
| Yes      | series tag  | phone_1                  | Phone 1                  | text      | text        |
| Yes      | series tag  | phone_2                  | Phone 2                  | text      | text        |
| Yes      | series tag  | phone_3                  | Phone 3                  | text      | text        |
| Yes      | series tag  | phone_4                  | Phone 4                  | text      | text        |
| Yes      | series tag  | phone_5                  | Phone 5                  | text      | text        |
| Yes      | series tag  | fax                      | Fax                      | text      | text        |
| Yes      | series tag  | public_health_nursing    | Public Health Nursing    | text      | text        |
| Yes      | series tag  | family_case_management   | Family Case Management   | text      | text        |
| Yes      | series tag  | healthy_start_program    | Healthy Start Program    | text      | text        |
| Yes      | series tag  | healthy_families_program | Healthy Families Program | text      | text        |
| Yes      | series tag  | wic                      | WIC                      | text      | text        |
| No       |             | latitude                 | Latitude                 | number    | number      |
| No       |             | longitude                | Longitude                | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:kcki-hnch d:2016-05-24T13:50:58.000Z t:zip=60621 t:phone_1=312-747-7496 t:hours_of_operation="Mon - Fri: 8:30 a.m. ? 4:30 p.m." t:state=IL t:street_address="641 W. 63rd St" t:site_name="Englewood MHC" t:clinic_type="Mental Health Clinic" t:city=Chicago m:row_number.kcki-hnch=1

series e:kcki-hnch d:2016-05-24T13:50:58.000Z t:zip=60653 t:phone_1=312-747-0036 t:hours_of_operation="Mon - Fri: 8:30 a.m. ? 4:30 p.m." t:state=IL t:street_address="4314 S. Cottage Grove" t:site_name="Greater Grand/MID-South MHC" t:clinic_type="Mental Health Clinic" t:city=Chicago m:row_number.kcki-hnch=2

series e:kcki-hnch d:2016-05-24T13:50:58.000Z t:zip=60632 t:phone_1=312-747-1020 t:hours_of_operation="Mon - Fri: 8:30 a.m. ? 4:30 p.m." t:state=IL t:street_address="4150 W. 55th Street" t:site_name="Greater Lawn MHC" t:clinic_type="Mental Health Clinic" t:city=Chicago m:row_number.kcki-hnch=3
```

## Meta Commands

```ls
metric m:row_number.kcki-hnch p:long l:"Row Number"

entity e:kcki-hnch l:"Chicago Department of Public Health Clinic Locations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/kcki-hnch

property e:kcki-hnch t:meta.view v:id=kcki-hnch v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Chicago Department of Public Health Clinic Locations" v:attribution="City of Chicago"

property e:kcki-hnch t:meta.view.owner v:id=awtb-su8t v:screenName="Aaron Feldman" v:displayName="Aaron Feldman"

property e:kcki-hnch t:meta.view.tableauthor v:id=awtb-su8t v:screenName="Aaron Feldman" v:displayName="Aaron Feldman"
```

## Top Records

```ls
| :updated_at | site_name                      | clinic_type          | site_number | hours_of_operation                                                         | street_address               | city    | state | zip   | phone_1      | phone_2 | phone_3 | phone_4 | phone_5 | fax          | public_health_nursing | family_case_management | healthy_start_program | healthy_families_program | wic | latitude           | longitude           | 
| =========== | ============================== | ==================== | =========== | ========================================================================== | ============================ | ======= | ===== | ===== | ============ | ======= | ======= | ======= | ======= | ============ | ===================== | ====================== | ===================== | ======================== | === | ================== | =================== | 
| 1464097858  | Englewood MHC                  | Mental Health Clinic |             | Mon - Fri: 8:30 a.m. ? 4:30 p.m.                                           | 641 W. 63rd St               | Chicago | IL    | 60621 | 312-747-7496 |         |         |         |         |              |                       |                        |                       |                          |     | 41.7796923798942   | -87.641427912993393 | 
| 1464097858  | Greater Grand/MID-South MHC    | Mental Health Clinic |             | Mon - Fri: 8:30 a.m. ? 4:30 p.m.                                           | 4314 S. Cottage Grove        | Chicago | IL    | 60653 | 312-747-0036 |         |         |         |         |              |                       |                        |                       |                          |     | 41.816325970337402 | -87.606846737921302 | 
| 1464097858  | Greater Lawn MHC               | Mental Health Clinic |             | Mon - Fri: 8:30 a.m. ? 4:30 p.m.                                           | 4150 W. 55th Street          | Chicago | IL    | 60632 | 312-747-1020 |         |         |         |         |              |                       |                        |                       |                          |     | 41.793274556210299 | -87.727664085301697 | 
| 1464097858  | Lawndale MHC                   | Mental Health Clinic |             | Mon - Fri: 8:30 a.m. ? 4:30 p.m.                                           | 1201 S. Campbell St          | Chicago | IL    | 60608 | 312-746-5905 |         |         |         |         |              |                       |                        |                       |                          |     | 41.866455972281599 | -87.689013605616097 | 
| 1464097858  | North River MHC                | Mental Health Clinic |             | Mon - Fri: 8:30 a.m. ? 4:30 p.m.                                           | 5801 N. Pulaski Road         | Chicago | IL    | 60646 | 312-744-1906 |         |         |         |         |              |                       |                        |                       |                          |     | 41.985931514182703 | -87.728369210034103 | 
| 1464097858  | Roseland MHC                   | Mental Health Clinic |             | Mon - Fri: 8:30 a.m. ? 4:30 p.m.                                           | 200 E. 115th Street          | Chicago | IL    | 60628 | 312-747-7320 |         |         |         |         |              |                       |                        |                       |                          |     | 41.685485762796503 | -87.6179898743747   | 
| 1464097858  | Englewood STI Specialty Clinic | STI Specialty Clinic |             | Mon, Wed & Fri: 8:00 a.m. - 4:00 p.m.; Tues & Thurs: 9:00 a.m. - 5:00 p.m. | 641 W. 63rd St., Lower Level | Chicago | IL    | 60621 | 312-747-8900 |         |         |         |         | 312-747-0292 |                       |                        |                       |                          |     | 41.7796923798942   | -87.641427912993393 | 
| 1464097858  | Lakeview STI Specialty Clinic  | STI Specialty Clinic |             | Mon, Wed & Fri: 8:00 a.m. - 4:00 p.m.; Tues &Thurs: 10:00 a.m. - 6:00 p.m. | 2861 N. Clark, 2nd Floor     | Chicago | IL    | 60657 | 312-744-5507 |         |         |         |         | 312-744-2573 |                       |                        |                       |                          |     | 41.934366841663902 | -87.645982126596493 | 
| 1464097858  | Roseland STI Specialty Clinic  | STI Specialty Clinic |             | Mon: 8:00 a.m. - 4:00 p.m.; Thurs: 9:00 a.m. - 5:00 p.m.                   | 200 E. 115th St.             | Chicago | IL    | 60628 | 312-747-2831 |         |         |         |         | 312-747-2841 |                       |                        |                       |                          |     | 41.685485762796503 | -87.6179898743747   | 
| 1464097858  | West Town STI Specialty Clinic | STI Specialty Clinic |             | Thurs: 9:00 a.m. - 5:00 p.m.; Fri: 8:00 a.m. - 4:00 p.m.                   | 2418 W. Division St.         | Chicago | IL    | 60622 | 312-744-5464 |         |         |         |         | 312-744-5516 |                       |                        |                       |                          |     | 41.903118044270599 | -87.6877798637138   | 
```