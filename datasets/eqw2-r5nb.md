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
| Publication Date | 2017-04-02T10:27:49Z |

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
| registration_number | first_name    | middle_name | last_name | suffix | company_name                                               | street_1                                     | street_2                  | city            | state | zip   | zip_plus_four | country        | county       | phone_number    | email_address                     | year_admitted | judicial_department_of_admission | law_school                                | status               | next_registration | 
| =================== | ============= | =========== | ========= | ====== | ========================================================== | ============================================ | ========================= | =============== | ===== | ===== | ============= | ============== | ============ | =============== | ================================= | ============= | ================================ | ========================================= | ==================== | ================= | 
| 4797783             | KATHERINE     | ELIZABETH   | SUELL     |        | BRESSLER AMERY & ROSS                                      | 325 COLUMBIA TURNPIKE                        |                           | FLORHAM PARK    | NJ    | 07932 | 1213          | United States  | Out of State | (973) 514-1200  | KSUELL@BRESSLER.COM               | 2010          | 3                                | SETON HALL UNIVERSITY                     | Currently registered | May 2018          | 
| 4797809             | JANESSE       |             | DAWSON    |        | KINGS COUNTY DISTRICT ATTORNEY'S OFFICE                    | 350 JAY ST                                   |                           | BROOKLYN        | NY    | 11201 | 2904          | United States  | Kings        |                 |                                   | 2010          | 1                                | CITY UNIVERSITY OF NEW YORK SCHOOL OF LAW | Currently registered | Apr 2018          | 
| 4797817             | LOUISE DIANNE | AMBE        | BEJER     |        | Bejer Law Office, P.C.                                     | 469 7th Avenue, 12th Floor                   | Suite 1233                | New York        | NY    | 10018 |               | United States  | New York     | (646) 436-4534  |                                   | 2010          | 2                                | ATENEO DE MANILA LAW SCHOOL               | Currently registered | Sep 2018          | 
| 4797825             | WILLIAM       | LANE        | VERLENDEN | IV     | Zynga Inc.                                                 | 699 8th St                                   |                           | San Francisco   | CA    | 94103 | 4901          | United States  | Out of State |                 | LVerlenden@gmail.com              | 2010          | 3                                | BOSTON UNIVERSITY                         | Currently registered | Jul 2018          | 
| 4797833             | MICHAEL       | SCOTT       | DECESARE  |        |                                                            |                                              |                           |                 |       |       |               |                |              |                 |                                   | 2010          | 2                                | PACE UNIVERSITY SCHOOL OF LAW             | Currently registered | Mar 2018          | 
| 4797841             | HOWARD        | LAURENCE    | FELDBERG  |        | New York State Attorney General Organized Crime Task Force | 44 S Broadway                                |                           | White Plains    | NY    | 10601 | 4425          | United States  | Westchester  | (914) 422-8700  |                                   | 2010          | 2                                | BROOKLYN LAW SCHOOL                       | Currently registered | Jul 2018          | 
| 4797858             | JINHEE        | JENNIFER    | CHUNG     |        | SULLIVAN & CROMWELL HONG KONG                              | 28TH FLOOR                                   | NINE QUEEN'S ROAD CENTRAL | HONG KONG       |       |       |               | HONG KONG      | Out of USA   | +852 2826-8688  |                                   | 2010          | 1                                | CORNELL LAW SCHOOL                        | Currently registered | May 2018          | 
| 4797866             | JEFFREY       | PAUL        | NEWMAN    |        | TD AMERITRADE                                              | 1 HARBORSIDE FINANCIAL CENTER PLAZA SUITE 4A |                           | JERSEY CITY     | NJ    | 07311 | 4000          | United States  | Out of State | (201) 369-8397  |                                   | 2010          | 1                                | FORDHAM                                   | Currently registered | Jan 2018          | 
| 4797874             | EVGENIYA      |             | RUBININA  |        | FRESHFIELDS BRUCKHAUS DERINGER                             | 65 Fleet Street                              |                           | London EC4Y 1HS |       |       |               | UNITED KINGDOM | Out of USA   | 44 7834 889 903 | evgeniya.rubinina@freshfields.com | 2010          | 3                                | HARVARD LAW SCHOOL                        | Currently registered | Aug 2018          | 
| 4797882             | TED           | BYUNG       | KWON      |        |                                                            |                                              |                           |                 |       |       |               |                |              |                 |                                   | 2010          | 2                                | ST. JOHN'S LAW SCHOOL                     | Delinquent           | Jan 2018          | 
```