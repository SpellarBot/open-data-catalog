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
| Publication Date | 2017-03-31T10:29:44Z |

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
| registration_number | first_name   | middle_name    | last_name | suffix | company_name                                        | street_1                          | street_2 | city          | state | zip   | zip_plus_four | country       | county       | phone_number   | email_address                    | year_admitted | judicial_department_of_admission | law_school                                        | status                                       | next_registration | 
| =================== | ============ | ============== | ========= | ====== | =================================================== | ================================= | ======== | ============= | ===== | ===== | ============= | ============= | ============ | ============== | ================================ | ============= | ================================ | ================================================= | ============================================ | ================= | 
| 5163837             | HELINA       | MICHELLE       | MANESIS   |        | ZAREMBA BROWNELL AND BROWN                          | 40 Wall St FL 27                  |          | New York      | NY    | 10005 | 1304          | United States | New York     | (212) 380-6700 |                                  | 2013          | 1                                | NEW YORK LAW SCHOOL                               | Currently registered                         | Jun 2017          | 
| 5163845             | ALEXANDER    |                | DOLAN     |        | Oscar Insurance                                     | 295 Lafayette St FL 6             |          | New York      | NY    | 10012 | 2722          | United States | New York     |                |                                  | 2013          | 1                                | NYU                                               | Currently registered                         | Apr 2019          | 
| 5163852             | DANIELLE-ANN | ALLISON        | THOMAS    |        | MDRC                                                | 16 E 34th St                      |          | New York      | NY    | 10016 | 4328          | United States | New York     | (212) 340-4502 |                                  | 2013          | 3                                | COLUMBIA LAW                                      | Currently registered                         | Feb 2019          | 
| 5163860             | TERESA       | LAUREN HARROLD | MICHAUD   |        | BAKER & MCKENZIE LLP                                | 2 EMBARCADERO CENTER, 11TH FLOOR  |          | SAN FRANCISCO | CA    | 94111 |               | United States | Out of State | (415) 576-3000 | TERESA.MICHAUD@BAKERMCKENZIE.COM | 2013          | 3                                | SOUTHERN METHODIST UNIVERSITY                     | Due to reregister within 30 days of birthday | May 2017          | 
| 5163878             | REBECCA      | JEAN           | KOWALSKY  |        | NYU LANGONE MEDICAL CENTER                          | 1 Park Ave FL 3                   |          | New York      | NY    | 10016 | 5802          | United States | New York     |                |                                  | 2013          | 1                                | DREXEL UNIVERSITY                                 | Due to reregister within 30 days of birthday | May 2017          | 
| 5163886             | DAVID        | MICHAEL        | GRABLE    |        | QUINN EMANUEL URQUHART & SULLIVAN, LLP              | 865 S Figueroa St FL 10           |          | Los Angeles   | CA    | 90017 | 5003          | United States | Out of State | (213) 443-3669 |                                  | 2013          | 3                                | CORNELL LAW SCHOOL                                | Due to reregister within 30 days of birthday | Apr 2017          | 
| 5163894             | NATHANIEL    | LANE           | STRAND    |        |                                                     | 1790 Broadway Ste 800             |          | New York      | NY    | 10019 | 1412          | United States | New York     | (504) 300-9335 | nate.strand@icloud.com           | 2013          | 3                                | Tulane University Law School                      | Currently registered                         | Nov 2017          | 
| 5163902             | ELIZABETH    | ANN            | CERVENAK  |        | State of New Jersey - Office of the Public Defender | 2150 Headquarters Plz FL 3        |          | Morristown    | NJ    | 07960 | 6856          | United States | Out of State |                |                                  | 2013          | 3                                | RUTGERS SCHOOL OF LAW - NEWARK                    | Currently registered                         | Apr 2019          | 
| 5163910             | KATHARINE    | MICHELLE       | FELLUCA   |        | EVANS & FOX LLP                                     | 100 MERIDIAN CENTRE BLVD, STE 300 |          | ROCHESTER     | NY    | 14618 | 3979          | United States | Monroe       | (585) 787-7000 | kfelluca@evansfox.com            | 2013          | 3                                | BOSTON UNIVERSITY SCHOOL OF LAW                   | Currently registered                         | Oct 2017          | 
| 5163928             | IRINA        |                | MARINESCU |        | KATTEN MUCHIN ROSENMAN LLP                          | 525 W Monroe St                   |          | Chicago       | IL    | 60661 | 3693          | United States | Out of State |                |                                  | 2013          | 1                                | UNIVERSITY OF CALIFORNIA, HASTINGS COLLEGE OF THE | Currently registered                         | Mar 2019          | 
```