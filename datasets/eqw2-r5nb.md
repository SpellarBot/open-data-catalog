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
| Publication Date | 2017-06-09T10:39:10Z |

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

property e:eqw2-r5nb t:meta.view d:2017-06-09T13:57:38.569Z v:id=eqw2-r5nb v:category=Transparency v:averageRating=0 v:name="NYS Attorney Registrations" v:attribution="NYS Unified Court System"

property e:eqw2-r5nb t:meta.view.owner d:2017-06-09T13:57:38.569Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:eqw2-r5nb t:meta.view.tableauthor d:2017-06-09T13:57:38.569Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:eqw2-r5nb t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:57:38.569Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| registration_number | first_name | middle_name | last_name       | suffix | company_name                           | street_1                           | street_2                   | city           | state | zip   | zip_plus_four | country       | county       | phone_number   | email_address         | year_admitted | judicial_department_of_admission | law_school                                      | status                                       | next_registration | 
| =================== | ========== | =========== | =============== | ====== | ====================================== | ================================== | ========================== | ============== | ===== | ===== | ============= | ============= | ============ | ============== | ===================== | ============= | ================================ | =============================================== | ============================================ | ================= | 
| 5368337             | YILEI      |             | WU              |        | TONGFANG GLOBAL INC.                   | 1550 VALLEY VISTA DR., SUITE 210   |                            | DIAMOND BAR    | CA    | 91765 |               | United States | Out of State | (909) 860-6900 |                       | 2015          | 3                                | UNI. OF SOUTHERN CALIFORNIA GOULD SCHOOL OF LAW | Due to reregister within 30 days of birthday | Jul 2017          | 
| 5368345             | KOTARO     |             | OKADA           |        | NISHIMURA & ASAHI                      | ARK MORI BUILDING, 1-12-32 AKASAKA | MINATO-KU                  | TOKYO 107-6029 |       |       |               | JAPAN         | Out of USA   | 81 3 5562 8500 |                       | 2015          | 3                                | DUKE LAW                                        | Due to reregister within 30 days of birthday | Jun 2017          | 
| 5368352             | HANMO      |             | WANG            |        |                                        |                                    |                            |                |       |       |               |               |              |                |                       | 2015          | 3                                | NORTHWESTERN UNIVERSITY                         | Due to reregister within 30 days of birthday | Jun 2017          | 
| 5368360             | KARL       | G.          | CHEUNG          |        | MENTAL HYGIENE LEGAL SERVICE           | CREEDMOOR PSYCHIATRIC CENTER       | 80-45 WINCHESTER BOULEVARD | QUEENS VILLAGE | NY    | 11427 |               | United States | Queens       | (718) 264-3340 | KGCHEUNG@NYCOURTS.GOV | 2015          | 2                                | ST. JOHN'S SCHOOL OF LAW                        | Currently registered                         | Jan 2019          | 
| 5368378             | ARAM       | GABRIEL     | HANESSIAN       |        | MILBANK, TWEED, HADLEY & MCCLOY LLP    | 28 LIBERTY ST.                     |                            | NEW YORK       | NY    | 10005 | 1400          | United States | New York     | (212) 530-5000 |                       | 2015          | 2                                | NORTHWESTERN UNIVERSITY SCHOOL OF LAW           | Due to reregister within 30 days of birthday | Apr 2017          | 
| 5368386             | JOHNATHAN  | N.          | VEGA            |        | ADMINISTRATION FOR CHILDREN'S SERVICES | 900 SHERIDAN AVE., 6TH FLR.        |                            | BRONX          | NY    | 10451 | 3317          | United States | Bronx        | (718) 590-5598 |                       | 2015          | 1                                | DICKINSON SCHOOL OF LAW                         | Currently registered                         | Sep 2017          | 
| 5368394             | JONATHAN   |             | FRUTKIN         |        | RADIX LAW, PLC                         | 15205 N Kierland Blvd Ste 200      |                            | Scottsdale     | AZ    | 85254 | 8170          | United States | Out of State | (602) 606-9300 | JFRUTKIN@RADIXLAW.COM | 2015          | 3                                | UNIVERSITY OF VIRGINIA                          | Currently registered                         | Mar 2019          | 
| 5368402             | PHIONAH    | N.          | BROWN           |        | Cabanillas & Associates, P.C           | 120 Bloomingdale Rd Ste 400        |                            | White Plains   | NY    | 10605 | 1500          | United States | Westchester  | (914) 418-2022 |                       | 2015          | 2                                | WESTERN MICHIGAN THOMAS M. COOLEY               | Currently registered                         | Feb 2019          | 
| 5368410             | ALI        |             | AGHAZADEH NAINI |        | MFY Legal Services, Inc.               | 299 Broadway                       |                            | New York       | NY    | 10007 | 1901          | United States | New York     | (212) 417-3700 |                       | 2015          | 3                                | GEORGE WASHINGTON UNIV. LAW SCHOOL              | Due to reregister within 30 days of birthday | Apr 2017          | 
| 5368428             | LAURAN     | ALISABETH   | SMITH           |        | Clifford Chance US LLP                 | 2001 K St NW FL 9                  |                            | Washington     | DC    | 20006 | 1037          | United States | Out of State | (202) 912-5000 |                       | 2015          | 3                                | THE UNIVERSITY OF TEXAS AT AUSTIN               | Currently registered                         | Apr 2019          | 
```