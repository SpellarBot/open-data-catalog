# CEC - Registered Lobbyists

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cec-registered-lobbyists-14e67) |
| Metadata | [Link](https://data.lacity.org/api/views/j4zm-9kqu) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/j4zm-9kqu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/j4zm-9kqu/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | j4zm-9kqu |
| Name | CEC - Registered Lobbyists |
| Category | A Well Run City |
| Tags | lobbying, lobbyist, lobby, ethics, disclosure |
| Created | 2014-04-24T22:36:34Z |
| Publication Date | 2014-07-16T16:41:46Z |

## Description

An individual who directly communicates with a City official for the purpose of influencing a legislative or administrative matter and is compensated to spend 30 or more hours in any consecutive three-month period engaged in lobbying activities must register with the Ethics Commission as a lobbyist. This also applies to in-house lobbyists (employees who are compensated to lobby only on behalf of their employers).

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag  | lobbyist_prefix            | Lobbyist Prefix            | text          | text          |
| Yes      | series tag  | lobbyist_first_name        | Lobbyist First Name        | text          | text          |
| Yes      | series tag  | lobbyist_middle_name       | Lobbyist Middle Name       | text          | text          |
| Yes      | series tag  | lobbyist_last_name         | Lobbyist Last name         | text          | text          |
| Yes      | series tag  | lobbyist_suffix            | Lobbyist Suffix            | text          | text          |
| Yes      | series tag  | lobbying_firm              | Lobbying Firm              | text          | text          |
| No       |             | registration_year          | Registration Year          | number        | text          |
| Yes      | time        | date_qualified             | Date Qualified             | calendar_date | calendar_date |
| No       |             | date_terminated            | Date Terminated            | calendar_date | calendar_date |
| No       |             | date_registered            | Date Registered            | calendar_date | calendar_date |
| Yes      | series tag  | lobbyist_street_address    | Lobbyist Street Address    | text          | text          |
| Yes      | series tag  | lobbyist_street_address_2  | Lobbyist Street Address 2  | text          | text          |
| Yes      | series tag  | lobbyist_city              | Lobbyist City              | text          | text          |
| Yes      | series tag  | lobbyist_state             | Lobbyist State             | text          | text          |
| Yes      | series tag  | lobbyist_zip               | Lobbyist Zip               | text          | text          |
| Yes      | series tag  | lobbyist_zip_4             | Lobbyist Zip+4             | text          | text          |
| Yes      | series tag  | lobbyist_area_code         | Lobbyist Area Code         | text          | text          |
| Yes      | series tag  | lobbyist_telephone         | Lobbyist Telephone         | text          | text          |
| Yes      | series tag  | lobbyist_telephone_ext     | Lobbyist Telephone Ext     | text          | text          |
| Yes      | series tag  | lobbyist_email             | Lobbyist Email             | text          | text          |
| Yes      | series tag  | lobbyist_alt_area_code     | Lobbyist Alt Area Code     | text          | text          |
| Yes      | series tag  | lobbyist_alt_telephone     | Lobbyist Alt Telephone     | text          | text          |
| Yes      | series tag  | lobbyist_alt_telephone_ext | Lobbyist Alt Telephone Ext | text          | text          |
| Yes      | series tag  | lobbyist_fax_area_code     | Lobbyist Fax Area Code     | text          | text          |
| Yes      | series tag  | lobbyist_fax_number        | Lobbyist Fax Number        | text          | text          |
| Yes      | series tag  | lobbyist_website           | Lobbyist Website           | text          | text          |
| Yes      | series tag  | lobbyist_registration_form | Lobbyist Registration Form | url           | url           |
```

## Time Field

```ls
Value = date_qualified
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_terminated,date_registered,registration_year
```

## Data Commands

```ls
series e:j4zm-9kqu d:2013-01-02T00:00:00.000Z t:lobbyist_telephone=998-3850 t:lobbyist_first_name="Charles H." t:lobbyist_zip=91311 t:lobbyist_street_address="9550 Topanga Canyon Blvd." t:lobbyist_fax_area_code=818 t:lobbyist_fax_number=998-3860 t:lobbyist_registration_form="http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4866" t:lobbyist_state=CA t:lobbyist_city=Chatsworth t:lobbyist_email=chuck@thecriscomcompany.com t:lobbyist_area_code=818 t:lobbying_firm="The CrisCom Company" t:lobbyist_last_name=Jelloian m:row_number.j4zm-9kqu=1

series e:j4zm-9kqu d:2013-01-02T00:00:00.000Z t:lobbyist_street_address="2000 Avenue of the Stars" t:lobbyist_alt_area_code=310 t:lobbyist_state=CA t:lobbyist_registration_form="http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4416" t:lobbyist_website=http://www.aresmgmt.com/ t:lobbyist_area_code=310 t:lobbyist_street_address_2="12th Floor" t:lobbyist_alt_telephone=201-4100 t:lobbyist_telephone=921-7390 t:lobbyist_zip=90067 t:lobbyist_first_name=Merritt t:lobbyist_city="Los Angeles" t:lobbyist_email=hooper@aresmgmt.com t:lobbying_firm="Ares Managment LLC" t:lobbyist_last_name=Hooper m:row_number.j4zm-9kqu=2

series e:j4zm-9kqu d:2013-01-02T00:00:00.000Z t:lobbyist_telephone=7102100 t:lobbyist_first_name=Leonard t:lobbyist_zip=10067 t:lobbyist_street_address="245 Park Avenue" t:lobbyist_registration_form="http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4419" t:lobbyist_state=NY t:lobbyist_city="New York" t:lobbyist_website=http://www.aresmgmt.com/ t:lobbyist_email=loremland@aresmgmt.com t:lobbyist_street_address_2="44th Floor" t:lobbyist_area_code=212 t:lobbying_firm="Ares Managment LLC" t:lobbyist_last_name=Oremland m:row_number.j4zm-9kqu=3
```

## Meta Commands

```ls
metric m:row_number.j4zm-9kqu p:long l:"Row Number"

entity e:j4zm-9kqu l:"CEC - Registered Lobbyists" t:url=https://data.lacity.org/api/views/j4zm-9kqu

property e:j4zm-9kqu t:meta.view v:id=j4zm-9kqu v:category="A Well Run City" v:averageRating=0 v:name="CEC - Registered Lobbyists"

property e:j4zm-9kqu t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:j4zm-9kqu t:meta.view.owner v:id=49an-b36e v:profileImageUrlMedium=/api/users/49an-b36e/profile_images/THUMB v:profileImageUrlLarge=/api/users/49an-b36e/profile_images/LARGE v:screenName="Ethics Commission" v:profileImageUrlSmall=/api/users/49an-b36e/profile_images/TINY v:displayName="Ethics Commission"

property e:j4zm-9kqu t:meta.view.tableauthor v:id=49an-b36e v:profileImageUrlMedium=/api/users/49an-b36e/profile_images/THUMB v:profileImageUrlLarge=/api/users/49an-b36e/profile_images/LARGE v:screenName="Ethics Commission" v:profileImageUrlSmall=/api/users/49an-b36e/profile_images/TINY v:roleName=publisher v:displayName="Ethics Commission"
```

## Top Records

```ls
| lobbyist_prefix | lobbyist_first_name | lobbyist_middle_name | lobbyist_last_name | lobbyist_suffix | lobbying_firm                                  | registration_year | date_qualified      | date_terminated     | date_registered     | lobbyist_street_address      | lobbyist_street_address_2 | lobbyist_city | lobbyist_state | lobbyist_zip | lobbyist_zip_4 | lobbyist_area_code | lobbyist_telephone | lobbyist_telephone_ext | lobbyist_email              | lobbyist_alt_area_code | lobbyist_alt_telephone | lobbyist_alt_telephone_ext | lobbyist_fax_area_code | lobbyist_fax_number | lobbyist_website         | lobbyist_registration_form                                                                  | 
| =============== | =================== | ==================== | ================== | =============== | ============================================== | ================= | =================== | =================== | =================== | ============================ | ========================= | ============= | ============== | ============ | ============== | ================== | ================== | ====================== | =========================== | ====================== | ====================== | ========================== | ====================== | =================== | ======================== | =========================================================================================== | 
|                 | Charles H.          |                      | Jelloian           |                 | The CrisCom Company                            | 2013              | 2013-01-02T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 9550 Topanga Canyon Blvd.    |                           | Chatsworth    | CA             | 91311        |                | 818                | 998-3850           |                        | chuck@thecriscomcompany.com |                        |                        |                            | 818                    | 998-3860            |                          | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4866, null] | 
|                 | Merritt             |                      | Hooper             |                 | Ares Managment LLC                             | 2013              | 2013-01-02T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 2000 Avenue of the Stars     | 12th Floor                | Los Angeles   | CA             | 90067        |                | 310                | 921-7390           |                        | hooper@aresmgmt.com         | 310                    | 201-4100               |                            |                        |                     | http://www.aresmgmt.com/ | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4416, null] | 
|                 | Leonard             |                      | Oremland           |                 | Ares Managment LLC                             | 2013              | 2013-01-02T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 245 Park Avenue              | 44th Floor                | New York      | NY             | 10067        |                | 212                | 7102100            |                        | loremland@aresmgmt.com      |                        |                        |                            |                        |                     | http://www.aresmgmt.com/ | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4419, null] | 
|                 | Kevin K             |                      | McDonnell          |                 | Jeffer Mangels Butler & Mitchell LLP           | 2013              | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 1900 Ave of the Stars 7th Fl |                           | Los Angeles   | CA             | 90067        | 5010           | 310                | 203-8080           |                        | kkm@jmbm.com                |                        |                        |                            | 310                    | 203-0567            |                          | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4941, null] | 
|                 | Benjamin M          |                      | Reznik             |                 | Jeffer Mangels Butler & Mitchell LLP           | 2013              | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 1900 Ave of the Stars 7th Fl |                           | Los Angeles   | CA             | 90067        | 5010           | 310                | 203-8080           |                        | bmr@jmbm.com                |                        |                        |                            | 310                    | 203-0567            |                          | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4944, null] | 
|                 | Sheri               |                      | Bonstelle          |                 | Jeffer Mangels Butler & Mitchell LLP           | 2013              | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 1900 Ave of the Stars 7th Fl |                           | Los Angeles   | CA             | 90067        | 5010           | 310                | 203-8080           |                        | syb@jmbm.com                |                        |                        |                            | 310                    | 203-0567            |                          | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4946, null] | 
|                 | Neill               |                      | Brower             |                 | Jeffer Mangels Butler & Mitchell LLP           | 2013              | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 1900 Ave of the Stars 7th Fl |                           | Los Angeles   | CA             | 90067        | 5010           | 310                | 203-8080           |                        | nb4@jmbm.com                |                        |                        |                            | 310                    | 203-0567            |                          | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=4942, null] | 
|                 | Patrick A           |                      | Perry              |                 | Allen Matkins Leck Gamble Mallory & Natsis LLP | 2013              | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 515 S Figueroa St 9th Fl     |                           | Los Angeles   | CA             | 90071        |                | 213                | 622-5555           |                        | pperry@allenmatkins.com     |                        |                        |                            | 213                    | 620-8816            |                          | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=5056, null] | 
|                 | Susan               |                      | Maunu              |                 | Allen Matkins Leck Gamble Mallory & Natsis LLP | 2013              | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 515 S Figueroa St 9th Fl     |                           | Los Angeles   | CA             | 90071        |                | 213                | 622-5555           |                        | smaunu@allenmatkins.com     |                        |                        |                            | 213                    | 620-8816            |                          | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=5046, null] | 
|                 | Emily               |                      | Murray             |                 | Allen Matkins Leck Gamble Mallory & Natsis LLP | 2013              | 2013-01-01T00:00:00 | 2013-12-31T00:00:00 | 2013-01-02T00:00:00 | 515 S Figueroa St 9th Fl     |                           | Los Angeles   | CA             | 90071        |                | 213                | 622-5555           |                        | emurray@allenmatkins.com    |                        |                        |                            | 213                    | 620-8816            |                          | [http://ethics.lacity.org/disclosure/index.cfm?fuseaction=home.view&DOCUMENT_ID=5051, null] | 
```