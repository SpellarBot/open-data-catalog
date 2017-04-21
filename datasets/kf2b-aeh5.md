# Workforce1 Recruitment Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/workforce1-recruitment-events) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kf2b-aeh5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kf2b-aeh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kf2b-aeh5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kf2b-aeh5 |
| Name | Workforce1 Recruitment Events |
| Attribution | Department of Small Business Services (SBS) |
| Category | Business |
| Tags | small business, recruitment, events, opportunities, job |
| Created | 2015-06-29T21:49:34Z |
| Publication Date | 2015-08-25T19:28:01Z |

## Description

Schedule of recruitment events offered by Workforce1 Center. This data is up to date as of the date reflected in the "About" tab of this dataset.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | location                  | location                  | text      | text        |
| No       |             | event_date                | event_date                | text      | text        |
| Yes      | series tag  | check_in_from             | check_in_from             | text      | text        |
| Yes      | series tag  | check_in_to               | check_in_to               | text      | text        |
| Yes      | series tag  | event_title               | event_title               | text      | text        |
| Yes      | series tag  | job_family                | job_family                | text      | text        |
| Yes      | series tag  | company_name_or_type      | company_name_or_type      | text      | text        |
| Yes      | series tag  | qualifications            | qualifications            | text      | text        |
| Yes      | series tag  | borough                   | borough                   | text      | text        |
| No       |             | location_name_and_address | location_name_and_address | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = event_date,location_name_and_address
```

## Data Commands

```ls
series e:kf2b-aeh5 d:2017-01-23T21:12:19.000Z t:qualifications="Must have HSD/GED. Some college preferred. Must have between 1-2 years of experience working in the field of human services. Driver?s license is required. Ability to handle crisis situations with minimum supervision. Must have experience working with children. Must have excellent verbal and written communication skills." t:company_name_or_type="Sheltering Arms" t:location="Queens Workforce1 Career Center" t:job_family="Social Work, Child Care, Counseling" t:borough=Queens t:event_title="Direct Care Workers" t:check_in_to="11:00 AM" t:check_in_from="10:45 AM" m:row_number.kf2b-aeh5=1

series e:kf2b-aeh5 d:2017-01-23T21:12:19.000Z m:row_number.kf2b-aeh5=2

series e:kf2b-aeh5 d:2017-01-23T21:12:19.000Z m:row_number.kf2b-aeh5=3
```

## Meta Commands

```ls
metric m:row_number.kf2b-aeh5 p:long l:"Row Number"

entity e:kf2b-aeh5 l:"Workforce1 Recruitment Events" t:attribution="Department of Small Business Services (SBS)" t:url=https://data.cityofnewyork.us/api/views/kf2b-aeh5

property e:kf2b-aeh5 t:meta.view v:id=kf2b-aeh5 v:category=Business v:averageRating=0 v:name="Workforce1 Recruitment Events" v:attribution="Department of Small Business Services (SBS)"

property e:kf2b-aeh5 t:meta.view.license v:name="Public Domain"

property e:kf2b-aeh5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kf2b-aeh5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | location                        | event_date            | check_in_from | check_in_to | event_title         | job_family                          | company_name_or_type | qualifications                                                                                                                                                                                                                                                                                                                    | borough | location_name_and_address                                                            | 
| =========== | =============================== | ===================== | ============= | =========== | =================== | =================================== | ==================== | ================================================================================================================================================================================================================================================================================================================================= | ======= | ==================================================================================== | 
| 1485205939  | Queens Workforce1 Career Center | Wednesday, January 25 | 10:45 AM      | 11:00 AM    | Direct Care Workers | Social Work, Child Care, Counseling | Sheltering Arms      | Must have HSD/GED. Some college preferred. Must have between 1-2 years of experience working in the field of human services. Driver?s license is required. Ability to handle crisis situations with minimum supervision. Must have experience working with children. Must have excellent verbal and written communication skills. | Queens  | Queens Workforce1 Career Center, 168-25 Jamaica Avenue, 2nd Floor, Jamaica, NY 11342 | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
| 1485205939  |                                 |                       |               |             |                     |                                     |                      |                                                                                                                                                                                                                                                                                                                                   |         |                                                                                      | 
```