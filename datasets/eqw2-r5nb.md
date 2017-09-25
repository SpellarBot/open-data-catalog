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
| Publication Date | 2017-09-23T10:22:09Z |

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

property e:eqw2-r5nb t:meta.view d:2017-09-25T07:29:02.996Z v:averageRating=0 v:name="NYS Attorney Registrations" v:attribution="NYS Unified Court System" v:id=eqw2-r5nb v:category=Transparency

property e:eqw2-r5nb t:meta.view.owner d:2017-09-25T07:29:02.996Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:eqw2-r5nb t:meta.view.tableauthor d:2017-09-25T07:29:02.996Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:eqw2-r5nb t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:29:02.996Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| registration_number | first_name | middle_name  | last_name | suffix | company_name                                                      | street_1                    | street_2 | city        | state | zip   | zip_plus_four | country       | county     | phone_number   | email_address              | year_admitted | judicial_department_of_admission | law_school                               | status               | next_registration | 
| =================== | ========== | ============ | ========= | ====== | ================================================================= | =========================== | ======== | =========== | ===== | ===== | ============= | ============= | ========== | ============== | ========================== | ============= | ================================ | ======================================== | ==================== | ================= | 
| 5224910             | JOSHUA     |              | GARCIA    |        | Cooley LLP                                                        | 1114 Avenue of The Americas |          | New York    | NY    | 10036 | 7703          | United States | New York   | (212) 819-8258 |                            | 2014          | 3                                | University of Michigan Law School        | Currently registered | Sep 2018          | 
| 5224928             | ANNA       | SISI         | HAN       |        | Pernod Ricard USA                                                 | 250 Park Ave                |          | New York    | NY    | 10177 | 0001          | United States | New York   | (212) 372-5400 |                            | 2014          | 3                                | UNIVERSITY OF MICHIGAN LAW SCHOOL        | Currently registered | Apr 2018          | 
| 5224936             | MEENA      |              | MENON     |        |                                                                   |                             |          |             |       |       |               |               |            |                |                            | 2014          | 3                                | UCLA SCHOOL OF LAW                       | Delinquent           | Jul 2018          | 
| 5224944             | ANTONIO    | PAULI MARTTI | WIRTA     |        | Shearman & Sterling LLP                                           | 7 rue Jacques Bingen        |          | Paris 75017 |       |       |               | FRANCE        | Out of USA | 0033153897004  | antonio.wirta@shearman.com | 2014          | 3                                | CORNELL LAW SCHOOL                       | Currently registered | Sep 2018          | 
| 5224951             | LAUREN     | CHRISTINE    | THOMAS    |        | WACHTELL, LIPTON, ROSEN & KATZ                                    | 51 W 52nd St                |          | New York    | NY    | 10019 | 6119          | United States | New York   | (212) 403-1000 |                            | 2014          | 2                                | YALE LAW SCHOOL                          | Currently registered | Feb 2018          | 
| 5224969             | PAUL       | MICHAEL      | JINDRA    |        | Fried, Frank, Harris, Shriver & Jacobson LLP                      | 1 New York Plz              |          | New York    | NY    | 10004 | 1901          | United States | New York   | (212) 859-8117 | paul.jindra@friedfrank.com | 2014          | 1                                | COLUMBIA LAW SCHOOL                      | Currently registered | Jun 2018          | 
| 5224977             | YOSEFA     | ARIELA       | HEBER     |        | KASOWITZ BENSON TORRES LLP                                        | 1633 BROADWAY               |          | NEW YORK    | NY    | 10019 | 6708          | United States | New York   | (212) 506-1700 |                            | 2014          | 1                                | ST. JOHN'S UNIVERSITY SCHOOL OF LAW      | Currently registered | Apr 2018          | 
| 5224985             | ADAM       | MICHAEL      | NAMM      |        | DEBEVOISE & PLIMPTON LLP                                          | 919 3rd Ave                 |          | New York    | NY    | 10022 | 3902          | United States | New York   | (212) 909-6418 | amnamm@gmail.com           | 2014          | 1                                | UNIVERSITY OF PENNSYLVANIA               | Currently registered | Oct 2018          | 
| 5224993             | TANSY      |              | WOAN      |        | Skadden, Arps, Slate, Meagher & Flom LLP                          | 4 Times Sq                  |          | New York    | NY    | 10036 | 6518          | United States | New York   | (212) 735-2472 | tansy.woan@skadden.com     | 2014          | 3                                | UNIVERSITY OF PENNSYLVANIA SCHOOL OF LAW | Currently registered | Mar 2018          | 
| 5225008             | JOANNA     | MARIA        | ZDANYS    |        | United States District Court for the Eastern District of New York | 225 Cadman Plz E            |          | Brooklyn    | NY    | 11201 | 1832          | United States | Kings      |                |                            | 2014          | 1                                | FORDHAM UNIVERSITY SCHOOL OF LAW         | Currently registered | Mar 2018          | 
```