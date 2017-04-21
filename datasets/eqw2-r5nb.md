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
| Publication Date | 2017-04-20T10:30:41Z |

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
| registration_number | first_name | middle_name | last_name | suffix | company_name                        | street_1                                      | street_2                     | city           | state | zip   | zip_plus_four | country       | county       | phone_number    | email_address              | year_admitted | judicial_department_of_admission | law_school                      | status               | next_registration | 
| =================== | ========== | =========== | ========= | ====== | =================================== | ============================================= | ============================ | ============== | ===== | ===== | ============= | ============= | ============ | =============== | ========================== | ============= | ================================ | =============================== | ==================== | ================= | 
| 5434188             | SHAKERA    | MONIQUE     | THOMPSON  |        | CRAVATH SWAINE & MOORE LLP          | 825 8TH AVENUE                                |                              | NEW YORK       | NY    | 10019 | 7416          | United States | New York     | (212) 474-1061  |                            | 2016          | 1                                | HOWARD UNIVERSITY SCHOOL OF LAW | Currently registered | Aug 2018          | 
| 5434204             | SHANE      | GEORGE      | WEBER     |        | BARCLAYS CAPITAL                    | 745 7TH AVENUE, 13TH FLOOR                    |                              | NEW YORK       | NY    | 10019 | 6801          | United States | New York     | (646) 476-0557  |                            | 2016          | 1                                | NEW YORK LAW SCHOOL             | Currently registered | Jun 2018          | 
| 5434212             | JACOB      | SAMUEL      | WEINER    |        | DAVIS, POLK AND WARDWELL LLP        | 450 LEXINGTON AVENUE                          |                              | NEW YORK       | NY    | 10017 | 3904          | United States | New York     | (212) 450-4906  | JACOB.WEINER@DAVISPOLK.COM | 2016          | 1                                | UNIVERSITY OF PENNSYLVANIA      | Currently registered | Nov 2018          | 
| 5434238             | ALISON     | MARIE       | PRINGLE   |        |                                     |                                               |                              |                |       |       |               |               |              |                 |                            | 2016          | 3                                | UNIVERSITY OF SAN DIEGO         | Currently registered | Jan 2018          | 
| 5434246             | ANDREW     | NEEL        | MAHARAJH  |        | LATHAM & WATKINS LLP                | 885 3RD AVENUE                                |                              | NEW YORK       | NY    | 10022 | 4834          | United States | New York     | (212) 906-1200  |                            | 2016          | 3                                | CORNELL LAW SCHOOL              | Currently registered | Sep 2018          | 
| 5434253             | AARON      | LOUIS       | WEBMAN    |        | KRAMER LEVIN NAFTALIS & FRANKEL LLP | 1177 AVENUE OF THE AMERICAS                   |                              | NEW YORK       | NY    | 10036 | 2714          | United States | New York     | (212) 715-9470  |                            | 2016          | 1                                | HARVARD LAW SCHOOL              | Currently registered | Sep 2018          | 
| 5434261             | OSAMU      |             | HAMADA    |        | DT LEGAL JAPAN                      | SHIN-KOKSAI BUILDING                          | 3-4-1 MARUNOUCHI, CHIYODA-KU | TOKYO 100-0005 |       |       |               | JAPAN         | Out of USA   | +81-3-6870-3300 |                            | 2016          | 3                                | THE UNIVERSITY OF CHICAGO       | Currently registered | May 2018          | 
| 5434279             | MEGUMI     |             | WADA      |        | THE LAW OFFICE OF TAKANO TAKASHI    | #901 DAIROKU-AZMA BLDG, 2-7 KANDA-SAKUMA-CHO, | CHIYODA-KU                   | TOKYO 101 0025 |       |       |               | JAPAN         | Out of USA   | +81-3-5825-6033 |                            | 2016          | 3                                | UC HASTINGS COLLEGE OF THE LAW  | Currently registered | May 2018          | 
| 5434287             | KEVIN      | MICHAEL     | CASEY     |        | MORRISON & FOERSTER, LLP            | 425 MARKET ST                                 |                              | SAN FRANCISCO  | CA    | 94105 |               | United States | Out of State | (415) 268-7000  |                            | 2016          | 1                                | COLUMBIA LAW SCHOOL             | Currently registered | Apr 2018          | 
| 5434295             | DUNCAN     | BREWSTER    | DELANO    |        | SCHULTE ROTH & ZABEL LLP            | 919 3RD AVENUE                                |                              | NEW YORK       | NY    | 10022 | 3902          | United States | New York     | (212) 756-2772  |                            | 2016          | 1                                | LEWIS & CLARK LAW SCHOOL        | Currently registered | Jul 2018          | 
```