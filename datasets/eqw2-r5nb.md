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
| Publication Date | 2017-03-29T10:29:13Z |

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
| registration_number | first_name | middle_name | last_name | suffix | company_name                       | street_1                | street_2 | city             | state | zip   | zip_plus_four | country       | county   | phone_number   | email_address   | year_admitted | judicial_department_of_admission | law_school                       | status                                  | next_registration | 
| =================== | ========== | =========== | ========= | ====== | ================================== | ======================= | ======== | ================ | ===== | ===== | ============= | ============= | ======== | ============== | =============== | ============= | ================================ | ================================ | ======================================= | ================= | 
| 1002294             | JACOB      | D.          | DIAMOND   |        |                                    |                         |          |                  |       |       |               |               |          |                |                 | 1967          | 2                                | FORDHAM UNIV                     | Currently registered                    | May 2018          | 
| 1002302             | DANIEL     | ARTHUR      | PINKUS    |        |                                    |                         |          |                  |       |       |               |               |          |                |                 | 1958          | 2                                | CORNELL                          | Currently registered                    | Jan 2018          | 
| 1002310             | MELVIN     | E.          | LAZAR     |        | LAW OFFICE MELVIN E. LAZAR         | 233 LAKE AVE, APT. 106  |          | SARATOGA SPRINGS | NY    | 12866 | 2737          | United States | Saratoga | (917) 324-2127 | MALL@NYU.EDU    | 1957          | 2                                | NEW YORK UNIVERSITY              | Currently registered                    | Sep 2018          | 
| 1002328             | ALAN       | JOEL        | PANZER    |        |                                    |                         |          |                  |       |       |               |               |          |                |                 | 1970          | 1                                | NY LAW SCHOOL                    | Deceased                                |                   | 
| 1002336             | KAREN      | PHYLLIS     | BINDER    |        | U.S. CUSTOMS AND BORDER PROTECTION | 26 FEDERAL PLZ          |          | NEW YORK         | NY    | 10278 | 0004          | United States | New York | (212) 264-9271 |                 | 1978          | 2                                | WASHINGTON UNIVERSITY            | Currently registered                    | Feb 2018          | 
| 1002344             | EDWIN      | CHARLES     | BULLOCK   |        |                                    |                         |          |                  |       |       |               |               |          |                |                 | 1979          | 1                                | RUTGERS SCHOOL OF LAW            | Currently registered                    | Jun 2018          | 
| 1002351             | WALTER     | J.          | KORPACZ   |        |                                    |                         |          |                  |       |       |               |               |          |                |                 | 1944          | 1                                | ST JOHNS LAW SCHOOL              | Deceased                                |                   | 
| 1002369             | HOWARD     |             | RAAB      |        |                                    |                         |          |                  |       |       |               |               |          |                |                 | 1973          | 1                                | ST JOHNS UNIVERSITY              | Resigned from bar - disciplinary reason |                   | 
| 1002377             | EDWARD     | G.          | LUKOSKI   |        |                                    |                         |          |                  |       |       |               |               |          |                | swrluke@aol.com | 1977          | 2                                | Seattle University School of Law | Currently registered                    | Dec 2018          | 
| 1002385             | ANDREA     | C.          | LEVINE    |        | NATIONAL ADVERTISING DIVISION      | 112 MADISON AVE, 3RD FL |          | NEW YORK         | NY    | 10016 | 7416          | United States | New York | (212) 705-0118 |                 | 1979          | 2                                | BROOKLYN LAW SCHOOL              | Currently registered                    | Feb 2018          | 
```