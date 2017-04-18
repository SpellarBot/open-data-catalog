# NYS Attorney Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-attorney-registrations) |
| Metadata | [Link](https://data.ny.gov/api/views/eqw2-r5nb) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/eqw2-r5nb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/eqw2-r5nb/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | eqw2-r5nb |
| Name | NYS Attorney Registrations |
| Attribution | NYS Unified Court System |
| Category | Transparency |
| Tags | attorney, registrations, integrity |
| Created | 2013-04-12T18:29:05Z |
| Publication Date | 2017-04-18T10:31:54Z |

## Description

The data included here is the information in the NYS Attorney Registration Database that is deemed public information pursuant to 22 NYCRR 118.

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type | Render Type |
| ======== | =========== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag  | registration_number              | Registration Number              | text      | number      |
| Yes      | series tag  | first_name                       | First Name                       | text      | text        |
| Yes      | series tag  | middle_name                      | Middle Name                      | text      | text        |
| Yes      | series tag  | last_name                        | Last Name                        | text      | text        |
| Yes      | series tag  | suffix                           | Suffix                           | text      | text        |
| Yes      | series tag  | company_name                     | Company Name                     | text      | text        |
| Yes      | series tag  | street_1                         | Street 1                         | text      | text        |
| Yes      | series tag  | street_2                         | Street 2                         | text      | text        |
| Yes      | series tag  | city                             | City                             | text      | text        |
| Yes      | series tag  | state                            | State                            | text      | text        |
| Yes      | series tag  | zip                              | Zip                              | text      | text        |
| Yes      | series tag  | zip_plus_four                    | Zip Plus Four                    | text      | text        |
| Yes      | series tag  | country                          | Country                          | text      | text        |
| Yes      | series tag  | county                           | County                           | text      | text        |
| Yes      | series tag  | phone_number                     | Phone Number                     | text      | text        |
| Yes      | series tag  | email_address                    | Email Address                    | text      | text        |
| Yes      | time        | year_admitted                    | Year Admitted                    | number    | number      |
| Yes      | series tag  | judicial_department_of_admission | Judicial Department of Admission | text      | number      |
| Yes      | series tag  | law_school                       | Law School                       | text      | text        |
| Yes      | series tag  | status                           | Status                           | text      | text        |
| Yes      | series tag  | next_registration                | Next Registration                | text      | text        |
```

## Time Field

```ls
Value = year_admitted
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:eqw2-r5nb l:"NYS Attorney Registrations" t:attribution="NYS Unified Court System" t:url=https://data.ny.gov/api/views/eqw2-r5nb

property e:eqw2-r5nb t:meta.view v:id=eqw2-r5nb v:category=Transparency v:averageRating=0 v:name="NYS Attorney Registrations" v:attribution="NYS Unified Court System"

property e:eqw2-r5nb t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:eqw2-r5nb t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:eqw2-r5nb t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| registration_number | first_name | middle_name | last_name   | suffix | company_name                                  | street_1               | street_2                   | city         | state | zip   | zip_plus_four | country       | county   | phone_number   | email_address          | year_admitted | judicial_department_of_admission | law_school                         | status               | next_registration | 
| =================== | ========== | =========== | =========== | ====== | ============================================= | ====================== | ========================== | ============ | ===== | ===== | ============= | ============= | ======== | ============== | ====================== | ============= | ================================ | ================================== | ==================== | ================= | 
| 1001585             | WILLIAM    | CARL        | KRATENSTEIN |        |                                               |                        |                            |              |       |       |               |               |          |                |                        | 1969          | 2                                | NEW YORK UNIVERSITY                | Currently registered | Sep 2018          | 
| 1001601             | ROWAN      | PETER       | KIRCHHEIMER |        | FEDERAL DEFENDER OF NEW YORK                  | 1 PIERREPONT PLZ FL 16 |                            | BROOKLYN     | NY    | 11201 | 2790          | United States | Kings    | (718) 330-1206 |                        | 1975          | 1                                | COLUMBIA                           | Currently registered | Jan 2018          | 
| 1001619             | DAVID      | BENJAMIN    | MANOWITZ    |        | DAVID B MANOWITZ ESQ C/O STAHL REAL ESTATE CO | 277 PARK AVE           |                            | NEW YORK     | NY    | 10172 | 0003          | United States | New York | (212) 826-7060 |                        | 1963          | 3                                | COLUMBIA UNIV SCHL OF LAW          | Currently registered | Jan 2018          | 
| 1001627             | THOMAS     | V.          | INCANTALUPO |        | THE LAW FIRM MITCHELL & INCANTALUPO           | 9820 METROPOLITAN AVE  |                            | FOREST HILLS | NY    | 11375 | 6628          | United States | Queens   | (718) 997-1000 |                        | 1978          | 2                                | BROOKLYN LAW SCHOOL                | Currently registered | Nov 2018          | 
| 1001635             | JOHN       | ANTHONY     | MITCHELL    |        | MITCHELL & INCANTALUPO                        | 9820 METROPOLITAN AVE  |                            | FOREST HILLS | NY    | 11375 | 6628          | United States | Queens   | (718) 997-1000 |                        | 1969          | 2                                | SUFFOLK UNIVERSITY, BOSTON, MASS   | Currently registered | Sep 2018          | 
| 1001643             | EVELYN     | LAURIE      | BRAUN       |        | JUSTICE OF THE SUPREME COURT                  | 12501 Queens Blvd      |                            | Kew Gardens  | NY    | 11415 | 1520          | United States | Queens   | (718) 298-1442 |                        | 1979          | 2                                | St. Johns University School of Law | Currently registered | Apr 2018          | 
| 1001650             | STEPHEN    | M.          | OBREMSKI    |        |                                               |                        |                            |              |       |       |               |               |          |                |                        | 1947          | 4                                |                                    | Deceased             |                   | 
| 1001668             | JACK       |             | WOOLAMS     |        | JACK V WOOLAMS ESQ                            | 135 W 81ST ST          | Street Level Gate Entrance | NEW YORK     | NY    | 10024 | 7201          | United States | New York | (212) 496-8530 | woolams@mindspring.com | 1978          | 1                                | RUTGERS UNIVERSITY                 | Currently registered | Mar 2018          | 
| 1001676             | PAUL       | S.          | FEINBERG    |        |                                               |                        |                            |              |       |       |               |               |          |                |                        | 1969          | 1                                | COLUMBIA                           | Currently registered | Dec 2018          | 
| 1001684             | CHESTER    | PAUL        | LUSTGARTEN  |        |                                               | 81 CHESTER AVE         |                            | BROOKLYN     | NY    | 11218 | 2001          | United States | Kings    | (917) 512-1915 |                        | 1977          | 2                                | NEW YORK UNIVERSITY                | Currently registered | Oct 2018          | 
```