# Contributions to Candidates and Political Committees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contributions-to-candidates-and-political-committees) |
| Metadata | [Link](https://data.wa.gov/api/views/kv7h-kjye) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/kv7h-kjye/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/kv7h-kjye/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | kv7h-kjye |
| Name | Contributions to Candidates and Political Committees |
| Attribution | Public Disclosure Commission |
| Tags | political finance, elections, contributions, campaign, political committee |
| Created | 2016-12-16T15:12:58Z |
| Publication Date | 2017-04-18T06:06:45Z |

## Description

This dataset contains cash and in-kind contributions made to Washington State Candidates and Political Committees for the last 10 years as reported to the PDC on forms C3, C4, Schedule C and their electronic filing equivalents. It does not include loans, pledges or any expenditures.

For candidates, the number of years is determined by the year of the election, not necessarily the year the contribution was reported. For political committees, the number of years is determined by the calendar year of the reporting period.

Candidates and political committees choosing to file under "mini reporting" are not included in this dataset. See WAC 390-16-105 for information regarding eligibility.

This dataset is a best-effort by the PDC to provide a complete set of records as described herewith and may contain incomplete or incorrect information. The PDC provides access to the original reports for the purpose of record verification.

Descriptions attached to this dataset do not constitute legal definitions; please consult RCW 42.17A and WAC Title 390 for legal definitions and additional information political finance disclosure requirements.

CONDITION OF RELEASE: This publication constitutes a list of individuals prepared by the Washington State Public Disclosure Commission and may not be used for commercial purposes. This list is provided on the condition and with the understanding that the persons receiving it agree to this statutorily imposed limitation on its use. See
RCW 42.56.070(9) and AGO 1975 No. 15.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| No       |                | id                         | ID                         | text          | text          |
| Yes      | series tag     | report_number              | report_number              | text          | text          |
| Yes      | series tag     | origin                     | origin                     | text          | text          |
| Yes      | series tag     | filer_id                   | filer_id                   | text          | text          |
| Yes      | series tag     | type                       | type                       | text          | text          |
| Yes      | series tag     | filer_name                 | filer_name                 | text          | text          |
| Yes      | series tag     | first_name                 | first_name                 | text          | text          |
| Yes      | series tag     | middle_initial             | middle_initial             | text          | text          |
| Yes      | series tag     | last_name                  | last_name                  | text          | text          |
| Yes      | series tag     | office                     | office                     | text          | text          |
| Yes      | series tag     | legislative_district       | legislative_district       | text          | text          |
| Yes      | series tag     | position                   | position                   | text          | text          |
| Yes      | series tag     | party                      | party                      | text          | text          |
| Yes      | series tag     | ballot_number              | ballot_number              | text          | text          |
| Yes      | series tag     | for_or_against             | for_or_against             | text          | text          |
| Yes      | series tag     | jurisdiction               | jurisdiction               | text          | text          |
| Yes      | series tag     | jurisdiction_county        | jurisdiction_county        | text          | text          |
| Yes      | series tag     | jurisdiction_type          | jurisdiction_type          | text          | text          |
| No       |                | election_year              | election_year              | number        | number        |
| Yes      | numeric metric | amount                     | amount                     | money         | money         |
| Yes      | series tag     | cash_or_in_kind            | cash_or_in_kind            | text          | text          |
| Yes      | time           | receipt_date               | receipt_date               | calendar_date | calendar_date |
| Yes      | series tag     | description                | description                | text          | text          |
| Yes      | series tag     | memo                       | memo                       | text          | text          |
| Yes      | series tag     | primary_general            | primary_general            | text          | text          |
| Yes      | series tag     | code                       | code                       | text          | text          |
| Yes      | series tag     | contributor_name           | contributor_name           | text          | text          |
| No       |                | contributor_address        | contributor_address        | text          | text          |
| Yes      | series tag     | contributor_city           | contributor_city           | text          | text          |
| Yes      | series tag     | contributor_state          | contributor_state          | text          | text          |
| Yes      | series tag     | contributor_zip            | contributor_zip            | text          | text          |
| Yes      | series tag     | contributor_occupation     | contributor_occupation     | text          | text          |
| Yes      | series tag     | contributor_employer_name  | contributor_employer_name  | text          | text          |
| Yes      | series tag     | contributor_employer_city  | contributor_employer_city  | text          | text          |
| Yes      | series tag     | contributor_employer_state | contributor_employer_state | text          | text          |
| Yes      | series tag     | url                        | url                        | url           | url           |
```

## Time Field

```ls
Value = receipt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,contributor_address,election_year
```

## Data Commands

```ls
series e:kv7h-kjye d:2007-07-11T00:00:00.000Z t:report_number=100218448 t:filer_name="NW HOUSING ASSN PAC" t:cash_or_in_kind=Cash t:primary_general="Full election cycle" t:contributor_city=MILLERSBURG t:origin=C3 t:contributor_zip=97321 t:code=Other t:contributor_name="PALM HARBOR HOMES" t:type="Political Committee" t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218448" t:contributor_state=OR t:filer_id="WASHMH 006" t:last_name="NORTHWEST HOUSING ASSN PAC" m:amount=21

series e:kv7h-kjye d:2007-07-17T00:00:00.000Z t:position=07 t:office="CITY COUNCIL MEMBER" t:cash_or_in_kind=Cash t:report_number=100218449 t:filer_name="NOBLE PHILLIP D" t:jurisdiction_county=KING t:primary_general="Full election cycle" t:middle_initial=D t:origin=C3 t:contributor_city=SEATTLE t:contributor_zip=98199 t:contributor_name="RHA PAC" t:code=Other t:jurisdiction="CITY OF BELLEVUE" t:party="NON PARTISAN" t:type=Candidate t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449" t:jurisdiction_type=Local t:first_name=PHILLIP t:contributor_state=WA t:filer_id="NOBLP  005" t:last_name=NOBLE m:amount=700

series e:kv7h-kjye d:2007-07-17T00:00:00.000Z t:position=07 t:office="CITY COUNCIL MEMBER" t:cash_or_in_kind=Cash t:report_number=100218449 t:filer_name="NOBLE PHILLIP D" t:jurisdiction_county=KING t:primary_general="Full election cycle" t:middle_initial=D t:origin=C3 t:contributor_city=SEATTLE t:contributor_zip=98111 t:contributor_name="HELSELL FETTERMAN LLP" t:code=Other t:jurisdiction="CITY OF BELLEVUE" t:party="NON PARTISAN" t:type=Candidate t:url="http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449" t:jurisdiction_type=Local t:first_name=PHILLIP t:contributor_state=WA t:filer_id="NOBLP  005" t:last_name=NOBLE m:amount=5000
```

## Meta Commands

```ls
metric m:amount p:double l:amount d:"The amount of the cash or in-kind contribution. On corrections records, this field is the amount of the adjustment." t:dataTypeName=money

entity e:kv7h-kjye l:"Contributions to Candidates and Political Committees" t:attribution="Public Disclosure Commission" t:url=https://data.wa.gov/api/views/kv7h-kjye

property e:kv7h-kjye t:meta.view v:id=kv7h-kjye v:attributionLink=http://pdc.wa.gov v:averageRating=0 v:name="Contributions to Candidates and Political Committees" v:attribution="Public Disclosure Commission"

property e:kv7h-kjye t:meta.view.license v:name="Public Domain"

property e:kv7h-kjye t:meta.view.owner v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:displayName="Washington Public Disclosure Commission"

property e:kv7h-kjye t:meta.view.tableauthor v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:roleName=publisher v:displayName="Washington Public Disclosure Commission"
```

## Top Records

```ls
| id           | report_number | origin | filer_id   | type                | filer_name                          | first_name | middle_initial | last_name                           | office              | legislative_district | position | party        | ballot_number | for_or_against | jurisdiction     | jurisdiction_county | jurisdiction_type | election_year | amount  | cash_or_in_kind | receipt_date        | description | memo | primary_general     | code       | contributor_name      | contributor_address            | contributor_city | contributor_state | contributor_zip | contributor_occupation | contributor_employer_name | contributor_employer_city | contributor_employer_state | url                                                                            | 
| ============ | ============= | ====== | ========== | =================== | =================================== | ========== | ============== | =================================== | =================== | ==================== | ======== | ============ | ============= | ============== | ================ | =================== | ================= | ============= | ======= | =============== | =================== | =========== | ==== | =================== | ========== | ===================== | ============================== | ================ | ================= | =============== | ====================== | ========================= | ========================= | ========================== | ============================================================================== | 
| 1807811.rcpt | 100218448     | C3     | WASHMH 006 | Political Committee | NW HOUSING ASSN PAC                 |            |                | NORTHWEST HOUSING ASSN PAC          |                     |                      |          |              |               |                |                  |                     |                   | 2007          | 21.00   | Cash            | 2007-07-11T00:00:00 |             |      | Full election cycle | Other      | PALM HARBOR HOMES     | 3737 PALM HARBOR DRIVE         | MILLERSBURG      | OR                | 97321           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218448, View report] | 
| 1807812.rcpt | 100218449     | C3     | NOBLP 005  | Candidate           | NOBLE PHILLIP D                     | PHILLIP    | D              | NOBLE                               | CITY COUNCIL MEMBER |                      | 07       | NON PARTISAN |               |                | CITY OF BELLEVUE | KING                | Local             | 2007          | 700.00  | Cash            | 2007-07-17T00:00:00 |             |      | Full election cycle | Other      | RHA PAC               | PO BOX 99447                   | SEATTLE          | WA                | 98199           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449, View report] | 
| 1807813.rcpt | 100218449     | C3     | NOBLP 005  | Candidate           | NOBLE PHILLIP D                     | PHILLIP    | D              | NOBLE                               | CITY COUNCIL MEMBER |                      | 07       | NON PARTISAN |               |                | CITY OF BELLEVUE | KING                | Local             | 2007          | 5000.00 | Cash            | 2007-07-17T00:00:00 |             |      | Full election cycle | Other      | HELSELL FETTERMAN LLP | 1001 FOURTH AVENUE, SUITE 4200 | SEATTLE          | WA                | 98111           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449, View report] | 
| 1807814.rcpt | 100218449     | C3     | NOBLP 005  | Candidate           | NOBLE PHILLIP D                     | PHILLIP    | D              | NOBLE                               | CITY COUNCIL MEMBER |                      | 07       | NON PARTISAN |               |                | CITY OF BELLEVUE | KING                | Local             | 2007          | 250.00  | Cash            | 2007-07-17T00:00:00 |             |      | Full election cycle | Individual | KING DALE             | 13412 - 174TH AVENUE NE        | REDMOND          | WA                | 98052           | PRINICPAL              | GLY CONSTRUCTION, INC.    | BELLEVUE                  | WA                         | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449, View report] | 
| 1807815.rcpt | 100218449     | C3     | NOBLP 005  | Candidate           | NOBLE PHILLIP D                     | PHILLIP    | D              | NOBLE                               | CITY COUNCIL MEMBER |                      | 07       | NON PARTISAN |               |                | CITY OF BELLEVUE | KING                | Local             | 2007          | 50.00   | Cash            | 2007-07-17T00:00:00 |             |      | Full election cycle | Individual | BLACKER MARGOT        | 2011 - 100TH AVENUE NE         | BELLEVUE         | WA                | 98004           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449, View report] | 
| 1807816.rcpt | 100218449     | C3     | NOBLP 005  | Candidate           | NOBLE PHILLIP D                     | PHILLIP    | D              | NOBLE                               | CITY COUNCIL MEMBER |                      | 07       | NON PARTISAN |               |                | CITY OF BELLEVUE | KING                | Local             | 2007          | 100.00  | Cash            | 2007-07-17T00:00:00 |             |      | Full election cycle | Individual | HOOPLE DOUGLAS D.     | 10637 SE 22ND STREET           | BELLEVUE         | WA                | 98004           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449, View report] | 
| 1807817.rcpt | 100218449     | C3     | NOBLP 005  | Candidate           | NOBLE PHILLIP D                     | PHILLIP    | D              | NOBLE                               | CITY COUNCIL MEMBER |                      | 07       | NON PARTISAN |               |                | CITY OF BELLEVUE | KING                | Local             | 2007          | 50.00   | Cash            | 2007-07-17T00:00:00 |             |      | Full election cycle | Individual | COLLETTE RICHARD J.   | 13901 NE 1ST PLACE             | BELLEVUE         | WA                | 98005           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449, View report] | 
| 1807818.rcpt | 100218449     | C3     | NOBLP 005  | Candidate           | NOBLE PHILLIP D                     | PHILLIP    | D              | NOBLE                               | CITY COUNCIL MEMBER |                      | 07       | NON PARTISAN |               |                | CITY OF BELLEVUE | KING                | Local             | 2007          | 50.00   | Cash            | 2007-07-17T00:00:00 |             |      | Full election cycle | Individual | COLLETTE BONNIE L.    | 13901 NE 1ST PLACE             | BELLEVUE         | WA                | 98005           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218449, View report] | 
| 1807819.rcpt | 100218451     | C3     | CITIIE 926 | Political Committee | CIT FOR IMPROVED EMERGENCY SERVICES |            |                | CIT FOR IMPROVED EMERGENCY SERVICES |                     |                      |          |              |               | For            |                  |                     |                   | 2007          | 100.00  | Cash            | 2007-06-28T00:00:00 |             |      | Full election cycle | Individual | MABBUTT CHRIS         | 1506 STONEBRIDGE ST            | ELLENSBURG       | WA                | 98926           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218451, View report] | 
| 1807820.rcpt | 100218451     | C3     | CITIIE 926 | Political Committee | CIT FOR IMPROVED EMERGENCY SERVICES |            |                | CIT FOR IMPROVED EMERGENCY SERVICES |                     |                      |          |              |               | For            |                  |                     |                   | 2007          | 100.00  | Cash            | 2007-07-06T00:00:00 |             |      | Full election cycle | Individual | SINCLAIR JOHN         | 102 N PEARL ST                 | ELLENSBURG       | WA                | 98926           |                        |                           |                           |                            | [http://web.pdc.wa.gov/rptimg/default.aspx?batchnumber=100218451, View report] | 
```