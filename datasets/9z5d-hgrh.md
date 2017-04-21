# CEC - Clients of Registered Lobbying Firms

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cec-clients-of-registered-lobbying-firms-4fc30) |
| Metadata | [Link](https://data.lacity.org/api/views/9z5d-hgrh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/9z5d-hgrh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/9z5d-hgrh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 9z5d-hgrh |
| Name | CEC - Clients of Registered Lobbying Firms |
| Category | A Well Run City |
| Tags | lobbying, lobbyist, lobby, ethics, disclosure |
| Created | 2014-04-25T00:27:46Z |
| Publication Date | 2014-07-16T16:34:07Z |

## Description

Entities who wish to influence City matters often hire lobbyists to represent them. A lobbying firm must register these entities as clients.

## Columns

```ls
| Included | Schema Type | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | =========== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag  | client_prefix                   | Client Prefix                   | text          | text          |
| Yes      | series tag  | client_first_name               | Client First Name               | text          | text          |
| Yes      | series tag  | client_middle_name              | Client Middle Name              | text          | text          |
| Yes      | series tag  | client_last_name                | Client Last Name                | text          | text          |
| Yes      | series tag  | client_suffix                   | Client Suffix                   | text          | text          |
| Yes      | series tag  | lobbying_firm                   | Lobbying Firm                   | text          | text          |
| No       |             | registration_year               | Registration Year               | number        | text          |
| Yes      | time        | date_representation_began       | Date Representation Began       | calendar_date | calendar_date |
| No       |             | date_terminated                 | Date Terminated                 | calendar_date | calendar_date |
| No       |             | date_registered                 | Date Registered                 | calendar_date | calendar_date |
| Yes      | series tag  | client_street_address           | Client Street Address           | text          | text          |
| Yes      | series tag  | client_street_address_2         | Client Street Address 2         | text          | text          |
| Yes      | series tag  | client_city                     | Client City                     | text          | text          |
| Yes      | series tag  | client_state                    | Client State                    | text          | text          |
| Yes      | series tag  | client_zip                      | Client Zip                      | text          | text          |
| Yes      | series tag  | client_zip_4                    | Client Zip+4                    | text          | text          |
| Yes      | series tag  | client_area_code                | Client Area Code                | text          | text          |
| Yes      | series tag  | client_telephone                | Client Telephone                | text          | text          |
| Yes      | series tag  | client_telephone_ext            | Client Telephone Ext            | text          | text          |
| Yes      | series tag  | client_email                    | Client Email                    | text          | text          |
| Yes      | series tag  | client_alt_area_code            | Client Alt Area Code            | text          | text          |
| Yes      | series tag  | client_alt_telephone            | Client Alt Telephone            | text          | text          |
| Yes      | series tag  | client_alt_telephone_ext        | Client Alt Telephone Ext        | text          | text          |
| Yes      | series tag  | client_fax_area_code            | Client Fax Area Code            | text          | text          |
| Yes      | series tag  | client_fax_number               | Client Fax Number               | text          | text          |
| Yes      | series tag  | client_website                  | Client Website                  | text          | text          |
| Yes      | series tag  | city_agencies                   | City Agencies                   | text          | text          |
| Yes      | series tag  | lobbying_firm_registration_form | Lobbying Firm Registration Form | url           | url           |
```

## Time Field

```ls
Value = date_representation_began
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_terminated,date_registered,registration_year
```

## Data Commands

```ls
series e:9z5d-hgrh d:2013-01-02T00:00:00.000Z t:client_telephone=577-3632 t:client_last_name="Duncan Solutions" t:client_area_code=877 t:city_agencies="ANY CITY AGENCY | Mayor, Office of | City Council" t:client_street_address="633 W. Wisconsin Avenue" t:lobbying_firm_registration_form="http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=3810" t:client_alt_area_code=414 t:client_zip=53203 t:client_street_address_2="Suite 1600" t:client_alt_telephone=847-3773 t:client_fax_number=847-6773 t:client_fax_area_code=414 t:lobbying_firm="The CrisCom Company" t:client_state=WI t:client_city=Milwaukee m:row_number.9z5d-hgrh=1

series e:9z5d-hgrh d:2013-01-02T00:00:00.000Z t:client_zip=91352 t:client_last_name="Crown Disposal Company, Inc." t:client_telephone=767-0675 t:client_area_code=818 t:lobbying_firm="The CrisCom Company" t:city_agencies="ANY CITY AGENCY" t:client_state=CA t:client_street_address="9189 De Garmo Street" t:client_city="Sun Valley" t:lobbying_firm_registration_form="http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=3810" m:row_number.9z5d-hgrh=2

series e:9z5d-hgrh d:2013-01-01T00:00:00.000Z t:client_telephone=744-5489 t:client_last_name="Raytheon Company" t:client_area_code=626 t:city_agencies="City Council | Chief Legislative Analyst (CLA) | City Administrative Officer (CAO) | Fire (LAFD) | Information Technology Agency (ITA) | Police (LAPD)" t:client_street_address="299 N. Euclid Ave." t:lobbying_firm_registration_form="http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4480" t:client_alt_area_code=415 t:client_zip=91101 t:client_alt_telephone=389-6800 t:client_email=sscally@nmgovlaw.com t:client_fax_number=388-6874 t:client_fax_area_code=415 t:lobbying_firm="Roger Ham Consulting" t:client_state=CA t:client_city=Pasadena m:row_number.9z5d-hgrh=3
```

## Meta Commands

```ls
metric m:row_number.9z5d-hgrh p:long l:"Row Number"

entity e:9z5d-hgrh l:"CEC - Clients of Registered Lobbying Firms" t:url=https://data.lacity.org/api/views/9z5d-hgrh

property e:9z5d-hgrh t:meta.view v:id=9z5d-hgrh v:category="A Well Run City" v:averageRating=0 v:name="CEC - Clients of Registered Lobbying Firms"

property e:9z5d-hgrh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:9z5d-hgrh t:meta.view.owner v:id=49an-b36e v:profileImageUrlMedium=/api/users/49an-b36e/profile_images/THUMB v:profileImageUrlLarge=/api/users/49an-b36e/profile_images/LARGE v:screenName="Ethics Commission" v:profileImageUrlSmall=/api/users/49an-b36e/profile_images/TINY v:displayName="Ethics Commission"

property e:9z5d-hgrh t:meta.view.tableauthor v:id=49an-b36e v:profileImageUrlMedium=/api/users/49an-b36e/profile_images/THUMB v:profileImageUrlLarge=/api/users/49an-b36e/profile_images/LARGE v:screenName="Ethics Commission" v:profileImageUrlSmall=/api/users/49an-b36e/profile_images/TINY v:roleName=publisher v:displayName="Ethics Commission"
```

## Top Records

```ls
| client_prefix | client_first_name | client_middle_name | client_last_name                         | client_suffix | lobbying_firm                     | registration_year | date_representation_began | date_terminated     | date_registered     | client_street_address               | client_street_address_2 | client_city | client_state | client_zip | client_zip_4 | client_area_code | client_telephone | client_telephone_ext | client_email         | client_alt_area_code | client_alt_telephone | client_alt_telephone_ext | client_fax_area_code | client_fax_number | client_website | city_agencies                                                                                                                                          | lobbying_firm_registration_form                                                             | 
| ============= | ================= | ================== | ======================================== | ============= | ================================= | ================= | ========================= | =================== | =================== | =================================== | ======================= | =========== | ============ | ========== | ============ | ================ | ================ | ==================== | ==================== | ==================== | ==================== | ======================== | ==================== | ================= | ============== | ====================================================================================================================================================== | =========================================================================================== | 
|               |                   |                    | Duncan Solutions                         |               | The CrisCom Company               | 2013              | 2013-01-02T00:00:00       | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 633 W. Wisconsin Avenue             | Suite 1600              | Milwaukee   | WI           | 53203      |              | 877              | 577-3632         |                      |                      | 414                  | 847-3773             |                          | 414                  | 847-6773          |                | ANY CITY AGENCY | Mayor, Office of | City Council                                                                                                      | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=3810, null] | 
|               |                   |                    | Crown Disposal Company, Inc.             |               | The CrisCom Company               | 2013              | 2013-01-02T00:00:00       | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 9189 De Garmo Street                |                         | Sun Valley  | CA           | 91352      |              | 818              | 767-0675         |                      |                      |                      |                      |                          |                      |                   |                | ANY CITY AGENCY                                                                                                                                        | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=3810, null] | 
|               |                   |                    | Raytheon Company                         |               | Roger Ham Consulting              | 2013              | 2013-01-01T00:00:00       | 2013-12-31T00:00:00 | 2013-01-15T00:00:00 | 299 N. Euclid Ave.                  |                         | Pasadena    | CA           | 91101      |              | 626              | 744-5489         |                      | sscally@nmgovlaw.com | 415                  | 389-6800             |                          | 415                  | 388-6874          |                | City Council | Chief Legislative Analyst (CLA) | City Administrative Officer (CAO) | Fire (LAFD) | Information Technology Agency (ITA) | Police (LAPD) | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4480, null] | 
|               |                   |                    | Westfield, LLC                           |               | Dakota Communications             | 2013              | 2013-01-01T00:00:00       | 2013-12-31T00:00:00 | 2013-01-22T00:00:00 | 11601 Wilshire Blvd 12th Fl.        |                         | Los Angeles | CA           | 90025      | 1748         | 310              | 478-4456         |                      |                      |                      |                      |                          |                      |                   |                | ANY CITY AGENCY                                                                                                                                        | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4825, null] | 
|               |                   |                    | Paramount Construction                   |               | Rick Taylor and Associates        | 2013              | 2013-01-01T00:00:00       | 2013-12-31T00:00:00 | 2013-01-27T00:00:00 | 6464 sunset Blvd                    |                         | Los Angeles | CA           | 90028      |              | 323              | 464-7050         |                      |                      |                      |                      |                          |                      |                   |                | ANY CITY AGENCY                                                                                                                                        | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4720, null] | 
|               |                   |                    | 7-11                                     |               | Andrew Casana and Associates, LLC | 2013              | 2013-01-27T00:00:00       | 2013-12-31T00:00:00 | 2013-01-28T00:00:00 | P.O. Box 711                        |                         | Dallas      | TX           | 75221      |              | 972              | 828-7804         |                      | Keith.Jones@7-11.com |                      |                      |                          |                      |                   |                | ANY CITY AGENCY                                                                                                                                        | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4031, null] | 
|               |                   |                    | Wilshire Gayley, LLC                     |               | Montgomery Clark Advisors         | 2013              | 2013-01-01T00:00:00       | 2013-12-31T00:00:00 | 2013-01-28T00:00:00 | 10877 Wilshire Boulevard, Suite 300 |                         | Los Angeles | CA           | 90024      |              | 310              | 824-3000         |                      |                      |                      |                      |                          | 310                  | 824-2424          |                | ANY CITY AGENCY                                                                                                                                        | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=3813, null] | 
|               |                   |                    | SA/Recycling                             |               | B Szabo Inc                       | 2013              | 2013-01-22T00:00:00       | 2013-12-31T00:00:00 | 2013-01-30T00:00:00 | 3200 East Frontera Street           |                         | Anaheim     | CA           | 92806      |              | 714              | 632-2000         |                      |                      |                      |                      |                          |                      |                   |                | Harbor (Port of LA, POLA)                                                                                                                              | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=5364, null] | 
|               |                   |                    | Cabrillo Beach Yacht Club                |               | Butterfield Communications        | 2013              | 2013-01-20T00:00:00       | 2013-12-31T00:00:00 | 2013-01-30T00:00:00 | 211 West 22nd Street                |                         | San Pedro   | CA           | 90731      |              | 310              | 533-8562         |                      |                      |                      |                      |                          |                      |                   |                | ANY CITY AGENCY                                                                                                                                        | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=3884, null] | 
|               |                   |                    | Burlington Northern and Santa Fe Railway |               | Butterfield Communications        | 2013              | 2013-01-20T00:00:00       | 2013-12-31T00:00:00 | 2013-01-30T00:00:00 | 3770 E. 26th Street                 |                         | Los Angeles | CA           | 90023      |              | 323              | 267-4041         |                      |                      |                      |                      |                          |                      |                   |                | Mayor, Office of | City Council | Harbor (Port of LA, POLA)                                                                                            | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=3884, null] | 
```