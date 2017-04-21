# Lead Training Course Provider List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lead-training-course-provider-list) |
| Metadata | [Link](https://data.illinois.gov/api/views/wwdj-394b) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wwdj-394b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wwdj-394b/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wwdj-394b |
| Name | Lead Training Course Provider List |
| Attribution | IDPH - Division of Environmental Health |
| Category | Public Health |
| Tags | lead, training |
| Created | 2015-02-26T19:30:41Z |
| Publication Date | 2017-04-13T15:27:52Z |

## Description

Lead Training Course Providers Last updated April 2017

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                     | Data Type     | Render Type   |
| ======== | =========== | ============================ | ======================== | ============= | ============= |
| Yes      | series tag  | id_number                    | ID Number                | text          | number        |
| Yes      | series tag  | name                         | Training Course Provider | text          | text          |
| No       |             | address                      | Address                  | text          | text          |
| Yes      | series tag  | city                         | City                     | text          | text          |
| Yes      | series tag  | state                        | State                    | text          | text          |
| Yes      | series tag  | zip                          | Zip                      | text          | text          |
| Yes      | series tag  | county                       | County                   | text          | text          |
| Yes      | series tag  | phone_no                     | Phone No.                | phone         | phone         |
| Yes      | series tag  | fax_no                       | Fax No.                  | phone         | phone         |
| Yes      | series tag  | contact_first_name           | Contact                  | text          | text          |
| No       |             | inspector_initial_exp        | Inspector Initial        | calendar_date | calendar_date |
| No       |             | risk_assessor_initial_exp    | Risk Assessor Initial    | calendar_date | calendar_date |
| No       |             | supervisor_initial_exp       | Supervisor Initial       | calendar_date | calendar_date |
| No       |             | worker_initial_exp           | Worker Initial           | calendar_date | calendar_date |
| No       |             | woker_initial_polish_exp     | Worker Initial Polish    | calendar_date | calendar_date |
| No       |             | worker_initial_spanish_exp   | Worker Initial Spanish   | calendar_date | calendar_date |
| No       |             | inspector_refresher_exp      | Inspector Refresher      | calendar_date | calendar_date |
| No       |             | risk_assessor_exp            | Risk Assessor            | calendar_date | calendar_date |
| No       |             | supervisor_refresher_exp     | Supervisor Refresher     | calendar_date | calendar_date |
| No       |             | worker_refresher_exp         | Worker Refresher         | calendar_date | calendar_date |
| No       |             | worker_refresher_spanish_exp | Worker Refresher Spanish | calendar_date | calendar_date |
| No       |             | worker_refresher_polish_exp  | Worker Refresher Polish  | calendar_date | calendar_date |
| Yes      | time        | rrp_initial_exp              | RRP Initial              | calendar_date | calendar_date |
| No       |             | rrp_initial_polish_exp       | RRP Initial Polish       | calendar_date | calendar_date |
| No       |             | rrp_initial_spanish_exp      | RRP Initial Spanish      | calendar_date | calendar_date |
| Yes      | series tag  | rrp_refresher_exp            | RRP Refresher            | text          | text          |
| No       |             | rrp_refresher_polish_exp     | RRP Refresher Polish     | calendar_date | calendar_date |
| No       |             | rrp_refresher_spanish_exp    | RRP Refresher Spanish    | calendar_date | calendar_date |
| Yes      | series tag  | alternate_type               | Alternate Type           | text          | text          |
| No       |             | alternate_exp                | Alternate Exp            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = rrp_initial_exp
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,risk_assessor_initial_exp,inspector_initial_exp,worker_initial_exp,woker_initial_polish_exp,worker_initial_spanish_exp,inspector_refresher_exp,risk_assessor_exp,supervisor_initial_exp,worker_refresher_exp,worker_refresher_spanish_exp,worker_refresher_polish_exp,supervisor_refresher_exp,rrp_initial_polish_exp,rrp_initial_spanish_exp,rrp_refresher_polish_exp,rrp_refresher_spanish_exp,alternate_exp
```

## Data Commands

```ls
series e:wwdj-394b d:2017-10-15T00:00:00.000Z t:zip=62353 t:phone_number="(217) 773-2835" t:county=Brown t:contact_first_name="Ron Litherland" t:id_number=19 t:name="IL Laborers' & Contractors Joint Apprenticeship & Training Program" t:state=IL t:city="Mount Sterling" m:row_number.wwdj-394b=1

series e:wwdj-394b d:2017-10-15T00:00:00.000Z t:zip=49005 t:phone_number="(269) 382-4161" t:county="OUT OF STATE" t:contact_first_name="Susan Pinto" t:id_number=117 t:name="Wonder Makers Environmental, Inc." t:state=MI t:city=Kalamazoo m:row_number.wwdj-394b=2

series e:wwdj-394b d:2017-10-15T00:00:00.000Z t:zip=60101 t:phone_number="(630) 953-2106" t:county=DuPage t:contact_first_name="David Laninga" t:id_number=143 t:name="District Council Training Center Fund" t:state=IL t:city=Addison m:row_number.wwdj-394b=3
```

## Meta Commands

```ls
metric m:row_number.wwdj-394b p:long l:"Row Number"

entity e:wwdj-394b l:"Lead Training Course Provider List" t:attribution="IDPH - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/wwdj-394b

property e:wwdj-394b t:meta.view v:id=wwdj-394b v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/lead-poisoning-prevention v:averageRating=0 v:name="Lead Training Course Provider List" v:attribution="IDPH - Division of Environmental Health"

property e:wwdj-394b t:meta.view.license v:name="Public Domain"

property e:wwdj-394b t:meta.view.owner v:id=6dyi-26tm v:screenName="ken mccann" v:displayName="ken mccann"

property e:wwdj-394b t:meta.view.tableauthor v:id=6dyi-26tm v:screenName="ken mccann" v:roleName=publisher v:displayName="ken mccann"
```

## Top Records

```ls
| id_number | name                                                               | address                   | city            | state | zip   | county       | phone_no               | fax_no                 | contact_first_name | inspector_initial_exp | risk_assessor_initial_exp | supervisor_initial_exp | worker_initial_exp  | woker_initial_polish_exp | worker_initial_spanish_exp | inspector_refresher_exp | risk_assessor_exp   | supervisor_refresher_exp | worker_refresher_exp | worker_refresher_spanish_exp | worker_refresher_polish_exp | rrp_initial_exp     | rrp_initial_polish_exp | rrp_initial_spanish_exp | rrp_refresher_exp | rrp_refresher_polish_exp | rrp_refresher_spanish_exp | alternate_type            | alternate_exp       | 
| ========= | ================================================================== | ========================= | =============== | ===== | ===== | ============ | ====================== | ====================== | ================== | ===================== | ========================= | ====================== | =================== | ======================== | ========================== | ======================= | =================== | ======================== | ==================== | ============================ | =========================== | =================== | ====================== | ======================= | ================= | ======================== | ========================= | ========================= | =================== | 
| 19        | IL Laborers' & Contractors Joint Apprenticeship & Training Program | 1730 750N Ave             | Mount Sterling  | IL    | 62353 | Brown        | [(217) 773-2741, null] | [(217) 773-2835, null] | Ron Litherland     |                       |                           | 2017-10-15T00:00:00    | 2017-10-15T00:00:00 |                          |                            |                         |                     | 2017-10-15T00:00:00      | 2017-10-15T00:00:00  |                              |                             | 2017-10-15T00:00:00 | 2017-10-15T00:00:00    |                         |                   |                          |                           |                           |                     | 
| 117       | Wonder Makers Environmental, Inc.                                  | P.O. Box 50209            | Kalamazoo       | MI    | 49005 | OUT OF STATE | [(269) 382-4154, null] | [(269) 382-4161, null] | Susan Pinto        |                       |                           |                        |                     |                          |                            |                         |                     |                          |                      |                              |                             | 2017-10-15T00:00:00 |                        |                         |                   |                          |                           |                           |                     | 
| 143       | District Council Training Center Fund                              | 2140 Corporate Dr         | Addison         | IL    | 60101 | DuPage       | [(630) 396-7143, null] | [(630) 953-2106, null] | David Laninga      |                       |                           |                        |                     |                          |                            |                         |                     |                          |                      |                              |                             | 2017-10-15T00:00:00 | 2017-10-15T00:00:00    |                         |                   |                          |                           |                           |                     | 
| 8         | Public Health and Safety, Inc.                                     | 37 South Ashland Ave      | Chicago         | IL    | 60607 | Cook         | [(312) 421-7397, null] | [(312) 421-2901, null] | Kathryn Newson     | 2017-10-15T00:00:00   | 2017-10-15T00:00:00       | 2017-10-15T00:00:00    | 2017-10-15T00:00:00 | 2017-10-15T00:00:00      | 2011-10-15T00:00:00        | 2017-10-15T00:00:00     | 2017-10-15T00:00:00 | 2017-10-15T00:00:00      | 2017-10-15T00:00:00  | 2017-10-15T00:00:00          | 2012-10-15T00:00:00         | 2017-10-15T00:00:00 | 2017-10-15T00:00:00    |                         |                   |                          |                           |                           |                     | 
| 107       | SSPC Society For Protective Coatings                               | 800 Trumbull Dr           | Pittsburgh      | PA    | 15205 | OUT OF STATE | [(412) 281-2331, null] | [(412) 281-9993, null] | Jennifer Merck     |                       |                           |                        |                     |                          |                            |                         |                     | 2017-10-15T00:00:00      |                      |                              |                             |                     |                        |                         |                   |                          |                           | SUPERVISOR 5 DAY 40 HOURS | 2017-10-15T00:00:00 | 
| 73        | OAI, INC.                                                          | 180 N Wabash Ave, Ste 750 | Chicago         | IL    | 60601 | Cook         | [(312) 528-3508, null] | [(312) 528-3501, null] | Sanobeia Brima     |                       |                           |                        | 2017-10-15T00:00:00 |                          |                            |                         |                     |                          |                      |                              |                             | 2017-10-15T00:00:00 | 2017-10-15T00:00:00    |                         |                   |                          |                           |                           |                     | 
| 115       | Ideal Environmental Engineering, Inc.                              | 2904 Tractor Ln           | Bloomington     | IL    | 61704 | McLean       | [(309) 828-4259, null] | [(309) 828-5735, null] | Ann Skeate         |                       |                           |                        |                     |                          |                            |                         |                     |                          |                      |                              |                             | 2017-10-15T00:00:00 | 2017-10-15T00:00:00    |                         |                   |                          |                           |                           |                     | 
| 149       | Iowa Lead Safety, Inc.                                             | 4725 Merle Hay Rd #212    | Des Moines      | IA    | 50322 | OUT OF STATE | [(515) 331-1690, null] | [(515) 727-1440, null] | Marci Papian       |                       |                           |                        |                     |                          |                            |                         |                     | 2017-10-15T00:00:00      | 2017-10-15T00:00:00  |                              |                             |                     |                        |                         |                   |                          |                           |                           |                     | 
| 127       | Reliable Environmental Solutions, Inc                              | 4211 Westgate Dr          | Springfield     | IL    | 62711 | Sangamon     | [(217) 787-9800, null] | [(217) 787-9801, null] | William S Williams |                       |                           |                        |                     |                          |                            |                         |                     |                          |                      |                              |                             | 2017-10-15T00:00:00 | 2017-10-15T00:00:00    |                         |                   |                          |                           |                           |                     | 
| 148       | 1st All Around Company                                             | 370 55th St               | Clarendon Hills | IL    | 60514 | DuPage       | [(773) 986-8725, null] | [(773) 943-6342, null] | Marcin Swierzowski |                       |                           |                        | 2017-10-15T00:00:00 |                          |                            |                         |                     |                          | 2017-10-15T00:00:00  |                              | 2017-10-15T00:00:00         |                     |                        |                         |                   |                          |                           |                           |                     | 
```