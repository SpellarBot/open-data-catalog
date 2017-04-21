# Candidate and Committee Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/draft-candidate-and-committee-registrations) |
| Metadata | [Link](https://data.wa.gov/api/views/d27u-zvri) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/d27u-zvri/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/d27u-zvri/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | d27u-zvri |
| Name | Candidate and Committee Registrations |
| Attribution | Public Disclosure Commission |
| Tags | political finance, elections, campaign, political committee |
| Created | 2017-01-17T20:52:34Z |
| Publication Date | 2017-04-17T03:07:49Z |

## Description

This dataset contains candidate and committee registrations for the last 10 years.

For candidates, the number of years is determined by the year of the election, not necessarily the year the expenditure was reported. For political committees, the number of years is determined by the calendar year of the reporting period.

This dataset is a best-effort by the PDC to provide a complete set of records as described herewith and may contain incomplete or incorrect information. The PDC provides access to the original reports for the purpose of record verification.

Descriptions attached to this dataset do not constitute legal definitions; please consult RCW 42.17A and WAC Title 390 for legal definitions and additional information regarding political finance disclosure requirements.

CONDITION OF RELEASE: This publication and or referenced documents constitutes a list of individuals prepared by the Washington State Public Disclosure Commission and may not be used for commercial purposes. This list is provided on the condition and with the understanding that the persons receiving it agree to this statutorily imposed limitation on its use. See RCW 42.56.070(9) and AGO 1975 No. 15.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| No       |                | id                         | id                         | text          | text          |
| Yes      | series tag     | report_number              | report_number              | text          | text          |
| Yes      | series tag     | origin                     | origin                     | text          | text          |
| Yes      | series tag     | filer_id                   | filer_id                   | text          | text          |
| Yes      | series tag     | filer_type                 | filer_type                 | text          | text          |
| Yes      | time           | receipt_date               | receipt_date               | calendar_date | calendar_date |
| No       |                | election_year              | election_year              | number        | number        |
| Yes      | series tag     | candidate_committee_status | candidate_committee_status | text          | text          |
| Yes      | series tag     | filer_name                 | filer_name                 | text          | text          |
| Yes      | series tag     | first_name                 | first_name                 | text          | text          |
| Yes      | series tag     | middle_initial             | middle_initial             | text          | text          |
| Yes      | series tag     | last_name                  | last_name                  | text          | text          |
| Yes      | series tag     | committee_acronym          | committee_acronym          | text          | text          |
| No       |                | committee_address          | committee_address          | text          | text          |
| Yes      | series tag     | committee_city             | committee_city             | text          | text          |
| Yes      | series tag     | committee_county           | committee_county           | text          | text          |
| Yes      | series tag     | committee_state            | committee_state            | text          | text          |
| Yes      | series tag     | committee_zip              | committee_zip              | text          | text          |
| Yes      | series tag     | committee_email            | committee_email            | email         | email         |
| Yes      | series tag     | candidate_email            | candidate_email            | email         | email         |
| Yes      | numeric metric | candidate_committee_phone  | candidate_committee_phone  | number        | text          |
| Yes      | numeric metric | committee_fax              | committee_fax              | number        | text          |
| Yes      | series tag     | office                     | office                     | text          | text          |
| Yes      | series tag     | jurisdiction               | jurisdiction               | text          | text          |
| Yes      | series tag     | jurisdiction_county        | jurisdiction_county        | text          | text          |
| Yes      | series tag     | jurisdiction_type          | jurisdiction_type          | text          | text          |
| Yes      | series tag     | position                   | position                   | text          | text          |
| Yes      | series tag     | party                      | party                      | text          | text          |
| No       |                | election_date              | election_date              | calendar_date | calendar_date |
| Yes      | series tag     | reporting_option           | reporting_option           | text          | text          |
| Yes      | series tag     | primary_election_status    | primary_election_status    | text          | text          |
| Yes      | series tag     | general_election_status    | general_election_status    | text          | text          |
| Yes      | series tag     | election_status            | election_status            | text          | text          |
| Yes      | series tag     | political_committee_type   | political_committee_type   | text          | text          |
| Yes      | series tag     | party_committee            | party_committee            | text          | text          |
| Yes      | series tag     | bonafide_type              | bonafide_type              | text          | text          |
| Yes      | series tag     | party_account_type         | party_account_type         | text          | text          |
| Yes      | series tag     | initiative_type            | initiative_type            | text          | text          |
| Yes      | series tag     | ballot_number              | ballot_number              | text          | text          |
| Yes      | series tag     | for_or_against             | for_or_against             | text          | text          |
| Yes      | series tag     | pac_type                   | PAC_type                   | text          | text          |
| Yes      | series tag     | treasurer_first_name       | treasurer_first_name       | text          | text          |
| Yes      | series tag     | treasurer_last_name        | treasurer_last_name        | text          | text          |
| No       |                | treasurer_address          | treasurer_address          | text          | text          |
| Yes      | series tag     | treasurer_city             | treasurer_city             | text          | text          |
| Yes      | series tag     | treasurer_county           | treasurer_county           | text          | text          |
| Yes      | series tag     | treasurer_state            | treasurer_state            | text          | text          |
| Yes      | series tag     | treasurer_zip              | treasurer_zip              | text          | text          |
| Yes      | numeric metric | treasurer_phone            | treasurer_phone            | number        | text          |
| Yes      | series tag     | url                        | url                        | url           | url           |
```

## Time Field

```ls
Value = receipt_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,committee_address,election_date,treasurer_address,election_year
```

## Data Commands

```ls
series e:d27u-zvri d:2008-09-05T00:00:00.000Z t:committee_county=KING t:report_number=1001268312 t:filer_name="NOW YOU KNOW PAC" t:reporting_option=FULL t:treasurer_last_name=GOMMENGINGER t:treasurer_state=WA t:origin=C1PC t:filer_type="Political Committee" t:treasurer_city=SEATTLE t:treasurer_zip=98104 t:url="http://web.pdc.wa.gov/rptimg/default.aspx?docid=1216569" t:pac_type="Continuing Political Committee" t:committee_zip=98104 t:committee_city=SEATTLE t:committee_email=INFO@PROCHOICEWASHINGTON.ORG t:filer_id="NOW YK 104" t:treasurer_county=KING t:committee_state=WA t:last_name="NOW YOU KNOW PAC" t:political_committee_type=OTHER t:treasurer_first_name=CORRIGAN m:treasurer_phone=2066241990 m:candidate_committee_phone=2066241990 m:committee_fax=2066244505

series e:d27u-zvri d:2008-09-05T00:00:00.000Z t:committee_county=KING t:report_number=1001269418 t:filer_name="NOW YOU KNOW PAC" t:reporting_option=FULL t:treasurer_last_name=GOMMENGINGER t:treasurer_state=WA t:origin=C1PC t:filer_type="Political Committee" t:treasurer_city=SEATTLE t:treasurer_zip=98104 t:pac_type="Continuing Political Committee" t:committee_zip=98104 t:committee_city=SEATTLE t:committee_email=INFO@PROCHOICEWASHINGTON.ORG t:filer_id="NOW YK 104" t:committee_state=WA t:treasurer_county=KING t:last_name="NOW YOU KNOW PAC" t:political_committee_type=OTHER t:treasurer_first_name=CORRIGAN m:treasurer_phone=2066241990 m:candidate_committee_phone=2066241990 m:committee_fax=2066244505

series e:d27u-zvri d:2010-04-09T00:00:00.000Z t:committee_county=KING t:report_number=1001273979 t:filer_name="NOW YOU KNOW PAC" t:reporting_option=FULL t:treasurer_last_name=EVANS-SATORAN t:treasurer_state=WA t:origin=C1PC t:filer_type="Political Committee" t:treasurer_city=SEATTLE t:treasurer_zip=98104 t:url="http://web.pdc.wa.gov/rptimg/default.aspx?docid=1820813" t:pac_type="Continuing Political Committee" t:committee_zip=98104 t:committee_city=SEATTLE t:committee_email=INFO@PROCHOICEWASHINGTON.ORG t:filer_id="NOW YK 104" t:treasurer_county=KING t:committee_state=WA t:last_name="NOW YOU KNOW PAC" t:political_committee_type=OTHER t:treasurer_first_name=SERENA m:treasurer_phone=2066241990 m:candidate_committee_phone=2066241990 m:committee_fax=2066244505
```

## Meta Commands

```ls
metric m:candidate_committee_phone p:long l:candidate_committee_phone d:"The committee phone number. In the case of a candidate, this is the phone number of the candidate, not the candidate's committee." t:dataTypeName=number

metric m:committee_fax p:long l:committee_fax d:"The committee fax number." t:dataTypeName=number

metric m:treasurer_phone p:long l:treasurer_phone d:"The treasurer?s phone number." t:dataTypeName=number

entity e:d27u-zvri l:"Candidate and Committee Registrations" t:attribution="Public Disclosure Commission" t:url=https://data.wa.gov/api/views/d27u-zvri

property e:d27u-zvri t:meta.view v:id=d27u-zvri v:attributionLink=http://www.pdc.wa.gov v:averageRating=0 v:name="Candidate and Committee Registrations" v:attribution="Public Disclosure Commission"

property e:d27u-zvri t:meta.view.license v:name="Public Domain"

property e:d27u-zvri t:meta.view.owner v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:displayName="Washington Public Disclosure Commission"

property e:d27u-zvri t:meta.view.tableauthor v:id=6hhm-htpq v:profileImageUrlMedium=/api/users/6hhm-htpq/profile_images/THUMB v:profileImageUrlLarge=/api/users/6hhm-htpq/profile_images/LARGE v:screenName="Washington Public Disclosure Commission" v:profileImageUrlSmall=/api/users/6hhm-htpq/profile_images/TINY v:roleName=publisher v:displayName="Washington Public Disclosure Commission"
```

## Top Records

```ls
| id        | report_number | origin | filer_id   | filer_type          | receipt_date        | election_year | candidate_committee_status | filer_name                                | first_name | middle_initial | last_name                                 | committee_acronym | committee_address     | committee_city | committee_county | committee_state | committee_zip | committee_email              | candidate_email                | candidate_committee_phone | committee_fax | office                      | jurisdiction          | jurisdiction_county | jurisdiction_type | position | party        | election_date       | reporting_option | primary_election_status | general_election_status | election_status | political_committee_type | party_committee           | bonafide_type | party_account_type | initiative_type | ballot_number | for_or_against | pac_type                       | treasurer_first_name | treasurer_last_name | treasurer_address     | treasurer_city | treasurer_county | treasurer_state | treasurer_zip | treasurer_phone | url                                                                          | 
| ========= | ============= | ====== | ========== | =================== | =================== | ============= | ========================== | ========================================= | ========== | ============== | ========================================= | ================= | ===================== | ============== | ================ | =============== | ============= | ============================ | ============================== | ========================= | ============= | =========================== | ===================== | =================== | ================= | ======== | ============ | =================== | ================ | ======================= | ======================= | =============== | ======================== | ========================= | ============= | ================== | =============== | ============= | ============== | ============================== | ==================== | =================== | ===================== | ============== | ================ | =============== | ============= | =============== | ============================================================================ | 
| 145884.c1 | 1001295081    | C1     | BEUHW 382  | Candidate           |                     | 2016          | Candidate withdrew         | BUEHLER WERNER                            | WERNER     |                | BUEHLER                                   |                   | 31 OWLS NEST RD       | SEQUIM         | CLALLAM          | WA              | 98382         |                              |                                |                           |               | PUBLIC UTILITY COMMISSIONER | CLALLAM COUNTY PUD #1 | CLALLAM             | Local             | 01       |              | 2016-11-08T00:00:00 |                  |                         |                         |                 |                          |                           |               |                    |                 |               |                |                                |                      |                     |                       |                | CLALLAM          |                 |               |                 | [null, null]                                                                 | 
| 122673.c1 | 1001268312    | C1PC   | NOW YK 104 | Political Committee | 2008-09-05T00:00:00 | 2008          |                            | NOW YOU KNOW PAC                          |            |                | NOW YOU KNOW PAC                          |                   | 811 1ST AVE STE 456   | SEATTLE        | KING             | WA              | 98104         | INFO@PROCHOICEWASHINGTON.ORG |                                | 2066241990                | 2066244505    |                             |                       |                     |                   |          |              |                     | FULL             |                         |                         |                 | OTHER                    |                           |               |                    |                 |               |                | Continuing Political Committee | CORRIGAN             | GOMMENGINGER        | 811 1ST AVE STE 456   | SEATTLE        | KING             | WA              | 98104         | 2066241990      | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=1216569, View Registration] | 
| 123110.c1 | 1001269418    | C1PC   | NOW YK 104 | Political Committee | 2008-09-05T00:00:00 | 2009          |                            | NOW YOU KNOW PAC                          |            |                | NOW YOU KNOW PAC                          |                   | 811 1ST AVE STE 456   | SEATTLE        | KING             | WA              | 98104         | INFO@PROCHOICEWASHINGTON.ORG |                                | 2066241990                | 2066244505    |                             |                       |                     |                   |          |              |                     | FULL             |                         |                         |                 | OTHER                    |                           |               |                    |                 |               |                | Continuing Political Committee | CORRIGAN             | GOMMENGINGER        | 811 1ST AVE STE 456   | SEATTLE        | KING             | WA              | 98104         | 2066241990      | [null, null]                                                                 | 
| 127285.c1 | 1001273979    | C1PC   | NOW YK 104 | Political Committee | 2010-04-09T00:00:00 | 2010          |                            | NOW YOU KNOW PAC                          |            |                | NOW YOU KNOW PAC                          |                   | 811 1ST AVE STE 456   | SEATTLE        | KING             | WA              | 98104         | INFO@PROCHOICEWASHINGTON.ORG |                                | 2066241990                | 2066244505    |                             |                       |                     |                   |          |              |                     | FULL             |                         |                         |                 | OTHER                    |                           |               |                    |                 |               |                | Continuing Political Committee | SERENA               | EVANS-SATORAN       | 811 1ST AVE STE 456   | SEATTLE        | KING             | WA              | 98104         | 2066241990      | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=1820813, View Registration] | 
| 146764.c1 | 1001296293    | C1PC   | PENDOD 156 | Political Committee | 2017-01-31T00:00:00 | 2017          |                            | PEND OREILLE CO DEMO CENT COMM NON EXEMPT |            |                | PEND OREILLE CO DEMO CENT COMM NON EXEMPT | POCDC             | PO BOX 1838           | NEWPORT        | PEND OREILLE     | WA              | 99156         |                              | PENDOREILLEDEMOCRATS@GMAIL.COM | 5094474547                |               |                             |                       |                     |                   |          |              |                     | MINI             |                         |                         |                 | DEMOCRATIC BONA FIDE     | Political party committee | County Party  | Non-Exempt account |                 |               |                |                                | ROBERT               | EUGENE              | 121 WOODARD RD        | NEWPORT        | PEND OREILLE     | WA              | 99156         | 5095507609      | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=4625810, View Registration] | 
| 128349.c1 | 100360224     | C1     | EGGAM 402  | Candidate           | 2010-06-21T00:00:00 | 2010          | Candidate declared         | EGGART MARIE J                            | MARIE      | J              | EGGART                                    |                   | PO BOX 246            | ASOTIN         | ASOTIN           | WA              | 99402         | MARIEEGGART@GMAIL.COM        | MARIEEGGART@GMAIL.COM          | 5097583676                |               | COUNTY CLERK                | ASOTIN CO             | ASOTIN              | Local             |          | DEMOCRAT     | 2010-11-02T00:00:00 | MINI             | Won in primary          | Won in general          |                 |                          |                           |               |                    |                 |               |                |                                | TAMMY                | LEAVITT             | 2633 BLUE MT COURT    | CLARKSTON      | ASOTIN           | WA              | 99403         | 5097587016      | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=1926566, View Registration] | 
| 144843.c1 | 100696167     | C1PC   | SKAMRC 648 | Political Committee | 2016-05-22T00:00:00 | 2016          |                            | SKAMANIA CO REPUB CENT COMM NON EXEMPT    |            |                | SKAMANIA CO REPUB CENT COMM NON EXEMPT    | SCRCC             | PO BOX 227            | STEVENSON      | SKAMANIA         | WA              | 98648         | DMMCKENZIE@EARTHLINK.NET     |                                | 5094278558                |               |                             |                       |                     |                   |          |              |                     | MINI             |                         |                         |                 | REPUBLICAN BONA FIDE     | Political party committee | County Party  | Non-Exempt account |                 |               |                |                                | DAVE                 | MCKENZIE            | 540 MAJOR ST          | STEVENSON      | SKAMANIA         | WA              | 98648         | 5094278558      | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=4573218, View Registration] | 
| 118643.c1 | 1001248166    | C1PC   | SKAMRC 648 | Political Committee | 2007-06-04T00:00:00 | 2007          |                            | SKAMANIA CO REPUB CENT COMM               |            |                | SKAMANIA CO REPUB CENT COMM NON EXEMPT    | SCRP              | PO BOX 227            | STEVENSON      | SKAMANIA         | WA              | 98648         | JUDITHLANZ@EARTHLINK.NET     |                                | 5094275517                | 5094277770    |                             |                       |                     |                   |          |              |                     | MINI             |                         |                         |                 | REPUBLICAN BONA FIDE     | Political party committee | County Party  | Non-Exempt account |                 |               |                |                                | JUDITH               | LANTZ               | PO BOX 848            | STEVENSON      | SKAMANIA         | WA              | 98648         | 5094275517      | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=1041578, View Registration] | 
| 143682.c1 | 1001292501    | C1     | LOY K 284  | Candidate           | 2015-06-23T00:00:00 | 2015          | Candidate declared         | LOY KEVIN M                               | KEVIN      | M              | LOY                                       |                   | 128 GARDEN OF EDEN RD | SEDRO-WOOLLEY  | SKAGIT           | WA              | 98284         | LOY4MAYOR@GMAIL.COM          | KEVINMLOY@GMAIL.COM            | 3604218396                |               | MAYOR                       | CITY OF SEDRO WOOLLEY | SKAGIT              | Local             |          | NON PARTISAN | 2015-11-03T00:00:00 | MINI             | Not in primary          | Lost in general         |                 |                          |                           |               |                    |                 |               |                |                                | KEVIN                | LOY                 | 128 GARDEN OF EDEN RD | SEDRO-WOOLLEY  | SKAGIT           | WA              | 98284         | 3604218396      | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=4470286, View Registration] | 
| 131455.c1 | 100414564     | C1     | CLARJ 042  | Candidate           | 2011-07-05T00:00:00 | 2011          | Candidate declared         | CLARK JEFF T                              | JEFFREY    | T              | CLARK                                     |                   | 25923 184TH PL SE     | COVINGTION     | KING             | WA              | 98042         | NEVERDOUBTCLARK@COMCAST.NET  | NEVERDOUBTCLARK@COMCAST.NET    | 2067788843                |               | WATER COMMISSIONER          | COVINGTON WATER DIST  | KING                | Local             | 04       | NON PARTISAN | 2011-11-08T00:00:00 | MINI             | Not in primary          | Unopposed in general    |                 |                          |                           |               |                    |                 |               |                |                                | JEFF                 | CLARK               | 25923 184TH PL SE     | COVINGTION     | KING             | WA              | 98042         | 2067788843      | [http://web.pdc.wa.gov/rptimg/default.aspx?docid=2406026, View Registration] | 
```