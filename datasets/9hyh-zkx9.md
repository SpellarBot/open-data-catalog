# ACS Community Partners

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/acs-community-partners-0dd3c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9hyh-zkx9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9hyh-zkx9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9hyh-zkx9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9hyh-zkx9 |
| Name | ACS Community Partners |
| Attribution | Administration for Children's Services (ACS) |
| Category | Social Services |
| Tags | acs community partners, administration for children's services (acs), preventitive, children, service, partner |
| Created | 2013-01-11T16:55:39Z |
| Publication Date | 2013-06-21T19:32:43Z |

## Description

Directory of preventitive agency location centers

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | program_lst_id          | PROGRAM_LST_ID          | text      | number      |
| Yes      | series tag     | program_code            | PROGRAM_CODE            | text      | text        |
| Yes      | series tag     | program_name            | PROGRAM_NAME            | text      | text        |
| Yes      | series tag     | active_flag             | ACTIVE_FLAG             | text      | text        |
| Yes      | series tag     | agency_name             | AGENCY_NAME             | text      | text        |
| Yes      | series tag     | description             | DESCRIPTION             | text      | text        |
| Yes      | series tag     | borough                 | BOROUGH                 | text      | text        |
| Yes      | series tag     | prog_contact_last_name  | PROG_CONTACT_LAST_NAME  | text      | text        |
| Yes      | series tag     | prog_contact_first_name | PROG_CONTACT_FIRST_NAME | text      | text        |
| Yes      | series tag     | prog_contact_phone_no   | PROG_CONTACT_PHONE_NO   | text      | number      |
| Yes      | series tag     | prog_contact_fax_no     | PROG_CONTACT_FAX_NO     | text      | number      |
| Yes      | numeric metric | prog_contact_extension  | PROG_CONTACT_EXTENSION  | number    | number      |
| Yes      | series tag     | prog_contact_email      | PROG_CONTACT_EMAIL      | text      | text        |
| No       |                | program_address_1       | PROGRAM_ADDRESS_1       | text      | text        |
| No       |                | program_address_2       | PROGRAM_ADDRESS_2       | text      | text        |
| Yes      | series tag     | program_city            | PROGRAM_CITY            | text      | text        |
| Yes      | series tag     | program_zip             | PROGRAM_ZIP             | text      | number      |
| No       |                | office_mon_from_time    | OFFICE_MON_FROM_TIME    | text      | text        |
| No       |                | office_mon_to_time      | OFFICE_MON_TO_TIME      | text      | text        |
| No       |                | office_tues_from_time   | OFFICE_TUES_FROM_TIME   | text      | text        |
| No       |                | office_tues_to_time     | OFFICE_TUES_TO_TIME     | text      | text        |
| No       |                | office_wed_from_time    | OFFICE_WED_FROM_TIME    | text      | text        |
| No       |                | office_wed_to_time      | OFFICE_WED_TO_TIME      | text      | text        |
| No       |                | office_thurs_from_time  | OFFICE_THURS_FROM_TIME  | text      | text        |
| No       |                | office_thurs_to_time    | OFFICE_THURS_TO_TIME    | text      | text        |
| No       |                | office_fri_from_time    | OFFICE_FRI_FROM_TIME    | text      | text        |
| No       |                | office_fri_to_time      | OFFICE_FRI_TO_TIME      | text      | text        |
| No       |                | office_sat_from_time    | OFFICE_SAT_FROM_TIME    | text      | text        |
| No       |                | office_sat_to_time      | OFFICE_SAT_TO_TIME      | text      | text        |
| No       |                | office_sun_from_time    | OFFICE_SUN_FROM_TIME    | text      | text        |
| No       |                | office_sun_to_time      | OFFICE_SUN_TO_TIME      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = program_address_1,program_address_2,office_mon_from_time,office_mon_to_time,office_tues_from_time,office_tues_to_time,office_wed_from_time,office_wed_to_time,office_thurs_from_time,office_thurs_to_time,office_fri_from_time,office_fri_to_time,office_sat_from_time,office_sat_to_time,office_sun_from_time,office_sun_to_time
```

## Data Commands

```ls
series e:9hyh-zkx9 d:2013-01-11T08:55:42.000Z t:program_code=00A556PR t:prog_contact_last_name=McAndrew t:program_name="Intensive Preventive and AfterCare Services-SI" t:borough="Staten Island" t:agency_name="Childrens Aid Society" t:program_lst_id=496 t:program_zip=10302 t:prog_contact_first_name=Linda t:prog_contact_phone_no=7182735305 t:description="Intensive Preventive" t:program_city="Staten Island" t:prog_contact_email=lindam@childrensaidsociety.org t:active_flag=Y t:prog_contact_fax_no=7182736895 m:prog_contact_extension=17

series e:9hyh-zkx9 d:2013-01-11T08:55:42.000Z t:prog_contact_first_name=Denise t:prog_contact_last_name=Bent t:program_code=00A639PR t:prog_contact_phone_no=7184976090 t:description="Family Treatment and Rehabilitation" t:program_name="Family Treatment Rehabilitation Program" t:borough=Brooklyn t:program_city=Kings t:agency_name="Coalition for Hispanic Family Services" t:program_lst_id=604 t:active_flag=Y t:program_zip=11237 m:prog_contact_extension=450

series e:9hyh-zkx9 d:2013-01-11T08:55:42.000Z t:program_code=000A350PR t:prog_contact_last_name=Cherry t:program_name="First Step II (FTR)" t:borough=Brooklyn t:agency_name="Community Counseling and Mediation" t:program_lst_id=558 t:program_zip=11226 t:prog_contact_first_name=Lana t:prog_contact_phone_no=7186937700 t:description="Family Treatment and Rehabilitation" t:program_city=Brooklyn t:prog_contact_email=lcherry@ccmnyc.org t:active_flag=Y t:prog_contact_fax_no=7186930120 m:prog_contact_extension=26
```

## Meta Commands

```ls
metric m:prog_contact_extension p:integer l:PROG_CONTACT_EXTENSION t:dataTypeName=number

entity e:9hyh-zkx9 l:"ACS Community Partners" t:attribution="Administration for Children's Services (ACS)" t:url=https://data.cityofnewyork.us/api/views/9hyh-zkx9

property e:9hyh-zkx9 t:meta.view v:id=9hyh-zkx9 v:category="Social Services" v:averageRating=0 v:name="ACS Community Partners" v:attribution="Administration for Children's Services (ACS)"

property e:9hyh-zkx9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9hyh-zkx9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | program_lst_id | program_code | program_name                                       | active_flag | agency_name                         | description                         | borough   | prog_contact_last_name | prog_contact_first_name | prog_contact_phone_no | prog_contact_fax_no | prog_contact_extension | prog_contact_email               | program_address_1    | program_address_2 | program_city     | program_zip | office_mon_from_time | office_mon_to_time | office_tues_from_time | office_tues_to_time | office_wed_from_time | office_wed_to_time | office_thurs_from_time | office_thurs_to_time | office_fri_from_time | office_fri_to_time | office_sat_from_time | office_sat_to_time | office_sun_from_time | office_sun_to_time | 
| =========== | ============== | ============ | ================================================== | =========== | =================================== | =================================== | ========= | ====================== | ======================= | ===================== | =================== | ====================== | ================================ | ==================== | ================= | ================ | =========== | ==================== | ================== | ===================== | =================== | ==================== | ================== | ====================== | ==================== | ==================== | ================== | ==================== | ================== | ==================== | ================== | 
| 1357894542  | 163            | 00A385PR     | Family Support Center Inc. - G.P. - Brooklyn       | Y           | Arab-American Family Support Center | General Preventive                  | Brooklyn  | Alhusseini             | Lena                    | 7186438000            | 7186438167          |                        | lena@aafscny.org                 | 150 Court Street     |                   | Brooklyn         | 11201       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
| 1357894542  | 643            | 00A680PR     | Family Support Center-Astoria                      | Y           | Arab-American Family Support Center | General Preventive                  | Queens    | Alhusseini             | Lena                    | 7186438000            |                     |                        |                                  | 37-10 30th Street    |                   | Long Island City | 11101       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
| 1357894542  | 644            | 00A681PR     | Family Support Center-Jackson Heights              | Y           | Arab-American Family Support Center | General Preventive                  | Queens    | Alhusseini             | Lena                    | 7186438000            |                     |                        |                                  | 37-10 30th Street    |                   | Long Island City | 11101       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
| 1357894542  | 169            | 00A415PR     | All Childrens House Preventive Svcs. - G.P. - Man. | Y           | Association to Benefit Children     | General Preventive                  | Manhattan | Horchak-Andino         | Kathy                   | 6464596099            | 6464596087          |                        | Khorchak-andino@a-b-c.org        | 1841 Park Avenue     | 3rd Floor         | New York         | 10035       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
| 1357894542  | 167            | 00A017PR     | Astor Family Services - General Preventive - Bronx | Y           | Astor Home for Children             | General Preventive                  | Bronx     | Weber                  | Ronna                   | 7182313400            | 7186553503          |                        |                                  | 750 Tilden Street    |                   | Bronx            | 10467       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
| 1357894542  | 510            | 00A661PR     | Astor Family Support Services-FT/R                 | Y           | Astor Home for Children             | Family Treatment and Rehabilitation | Bronx     | Weber                  | Ronna                   | 7182313400            | 7186553503          |                        |                                  | 750 Tilden Street    |                   | New York         | 10467       |                      |                    |                       |                     |                      |                    |                        |                      |                      |                    |                      |                    |                      |                    | 
| 1357894542  | 640            | 00A673PR     | General Preventive                                 | Y           | BoysTown                            | General Preventive                  | Brooklyn  | Madlangbayan           | Elaine                  | 3473818181            | 3473818185          |                        | elaine.madlangbayan@boystown.org | 1360 Fulton Street   | Bldg B,Siute #511 | Kings            | 11216       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
| 1357894542  | 318            | 00A409PR     | Family Enrichment Program - G.P. - Bronx           | Y           | Bronx Works                         | General Preventive                  | Bronx     | Morgenstern            | Jonathan                | 7185083160            | 7182931946          |                        | jmorgenstern@bronxworks.org      | 1130 Grand Concourse |                   | Bronx            | 10456       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
| 1357894542  | 513            | 00A649PR     | Bedford Stuyvesant Family Center -FT/R             | Y           | Brooklyn Community Services         | Family Treatment and Rehabilitation | Brooklyn  | Querbach               | Jodi                    | 7186229400            |                     |                        |                                  | 20 New York Avenue   | 2nd Floor         | Kings County     | 11216       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
| 1357894542  | 171            | 00A037PR     | Bedford Stuyvesant Family Ctr.- Gen. Prev. - Bklyn | Y           | Brooklyn Community Services         | General Preventive                  | Brooklyn  | Querbach               | Jodi                    | 7186229400            |                     |                        |                                  | 20 New York Avenue   | 2nd Floor         | Brooklyn         | 11216       | 9:00 AM              | 5:00 PM            | 9:00 AM               | 5:00 PM             | 9:00 AM              | 5:00 PM            | 9:00 AM                | 5:00 PM              | 9:00 AM              | 5:00 PM            |                      |                    |                      |                    | 
```