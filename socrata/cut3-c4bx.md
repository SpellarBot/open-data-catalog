# Baltimore City Government Entities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-government-entities-5973e) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/cut3-c4bx) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/cut3-c4bx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/cut3-c4bx/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | cut3-c4bx |
| Name | Baltimore City Government Entities |
| Attribution | Baltimore City |
| Category | City Government |
| Tags | government, agency, agencies, mayoral offices, offices, departments, boards, commissions, elected officials |
| Created | 2011-01-23T02:45:05Z |
| Publication Date | 2014-04-03T23:22:47Z |

## Description

A comprehensive listing of all government entities (Agencies, Mayoral Offices, Departments, Boards, Commissions, Elected Officials)

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | tags               | tags               | text      | text        |
| Yes      | series tag  | formal_agency_name | Formal Agency Name | text      | text        |
| Yes      | series tag  | agency_short_name  | Agency Short Name  | text      | text        |
| Yes      | series tag  | acronym            | Acronym            | text      | text        |
| Yes      | series tag  | agency_url         | Agency URL         | url       | url         |
| Yes      | series tag  | agency_contact_url | Agency Contact Url | url       | url         |
| Yes      | series tag  | agency_head        | Agency Head        | text      | text        |
| Yes      | series tag  | agency_head_title  | Agency Head Title  | text      | text        |
| Yes      | series tag  | agency_head_image  | Agency Head Image  | photo     | photo       |
| Yes      | series tag  | agency_logo        | Agency Logo        | photo     | photo       |
| Yes      | series tag  | agency_type        | Agency Type        | text      | text        |
| Yes      | series tag  | agency_email       | Agency Email       | email     | email       |
| Yes      | series tag  | agency_phone       | Agency Phone       | phone     | phone       |
| Yes      | series tag  | other_phone        | Other Phone        | phone     | phone       |
| Yes      | series tag  | agency_fax         | Agency Fax         | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cut3-c4bx d:2011-08-20T19:54:18.000Z t:agency_head_title=Sheriff t:agency_type="Elected Office" t:tags=ge_sheriff t:phone_number="(410) 396-1155" t:phone_type=Work t:formal_agency_name="Baltimore City Sheriff's Office" t:agency_head="John W. Anderson" t:agency_url=http://www.baltimorecity.gov/Government/StateAgencies/SheriffsOffice.aspx t:agency_short_name="Sheriff's Office" m:row_number.cut3-c4bx=1

series e:cut3-c4bx d:2011-08-20T19:54:18.000Z t:agency_head_title=Director t:agency_type="Mayoral Office" t:tags=ge_mo_employment_development t:phone_number="(410) 396-3009" t:acronym=MOED t:phone_type=Work t:formal_agency_name="Mayor?s Office of Employment Development" t:agency_head="Karen Sitnick" t:agency_url=http://www.oedworks.com t:agency_short_name="Employment Development" m:row_number.cut3-c4bx=2

series e:cut3-c4bx d:2011-08-29T11:21:53.000Z t:agency_head_title=Director t:agency_type="Mayoral Office" t:tags=ge_mo_emergency_management t:phone_number="(410) 396-6188" t:acronym=MOEM t:phone_type=Work t:formal_agency_name="Mayor's Office of Emergency Management" t:agency_head="Robert Maloney" t:agency_url=http://www.baltimorecity.gov/OfficeoftheMayor/MayoralOffices/EmergencyManagement.aspx t:agency_short_name="Emergency Management" t:agency_email=eoc@baltimorecity.gov m:row_number.cut3-c4bx=3
```

## Meta Commands

```ls
metric m:row_number.cut3-c4bx p:long l:"Row Number"

entity e:cut3-c4bx l:"Baltimore City Government Entities" t:attribution="Baltimore City" t:url=https://data.baltimorecity.gov/api/views/cut3-c4bx

property e:cut3-c4bx t:meta.view v:id=cut3-c4bx v:category="City Government" v:attributionLink=http://www.baltimorecity.gov/Government.aspx v:averageRating=0 v:name="Baltimore City Government Entities" v:attribution="Baltimore City"

property e:cut3-c4bx t:meta.view.license v:name="Public Domain"

property e:cut3-c4bx t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:cut3-c4bx t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | tags                         | formal_agency_name                        | agency_short_name       | acronym | agency_url                                                                                          | agency_contact_url | agency_head               | agency_head_title  | agency_head_image | agency_logo | agency_type    | agency_email          | agency_phone           | other_phone  | agency_fax   | 
| =========== | ============================ | ========================================= | ======================= | ======= | =================================================================================================== | ================== | ========================= | ================== | ================= | =========== | ============== | ===================== | ====================== | ============ | ============ | 
| 1313870058  | ge_sheriff                   | Baltimore City Sheriff's Office           | Sheriff's Office        |         | [http://www.baltimorecity.gov/Government/StateAgencies/SheriffsOffice.aspx, null]                   | [null, null]       | John W. Anderson          | Sheriff            |                   |             | Elected Office |                       | [(410) 396-1155, Work] | [null, null] | [null, null] | 
| 1313870058  | ge_mo_employment_development | Mayor?s Office of Employment Development  | Employment Development  | MOED    | [http://www.oedworks.com, null]                                                                     | [null, null]       | Karen Sitnick             | Director           |                   |             | Mayoral Office |                       | [(410) 396-3009, Work] | [null, null] | [null, null] | 
| 1314616913  | ge_mo_emergency_management   | Mayor's Office of Emergency Management    | Emergency Management    | MOEM    | [http://www.baltimorecity.gov/OfficeoftheMayor/MayoralOffices/EmergencyManagement.aspx, null]       | [null, null]       | Robert Maloney            | Director           |                   |             | Mayoral Office | eoc@baltimorecity.gov | [(410) 396-6188, Work] | [null, null] | [null, null] | 
| 1313870058  | ge_mo_criminal_justice       | Mayor's Office on Criminal Justice        | Criminal Justice        | MOCJ    | [http://www.baltimorecity.gov/OfficeoftheMayor/MayoralOffices/CriminalJustice.aspx, null]           | [null, null]       | Sheryl Goldstein          | Director           |                   |             | Mayoral Office |                       | [(410) 396-9521, Work] | [null, null] | [null, null] | 
| 1313870058  | ge_environmental_control     | Environmental Control Board               | Environmental Control   | ECB     | [http://www.baltimorecity.gov/Government/BoardsandCommissions/EnvironmentalControlBoard.aspx, null] | [null, null]       | Sandra E. Baker, Esq.     | Executive Director |                   |             | Board          |                       | [(410) 396-6909, Work] | [null, null] | [null, null] | 
| 1313870058  | ge_women_commission          | Commission For Women                      | Women's Commission      |         | [http://www.baltimorecity.gov/Government/BoardsandCommissions/WomensCommission.aspx, null]          | [null, null]       | Anne O. Emery             | Commission Chair   |                   |             | Commission     |                       | [(410) 396-7370, Work] | [null, null] | [null, null] | 
| 1313870058  | ge_mo_neighborhoods          | Mayor's Office of Neighborhoods           | Neighborhoods           | MON     | [http://www.baltimorecity.gov/OfficeoftheMayor/MayoralOffices/Neighborhoods.aspx, null]             | [null, null]       | Gussener T. Augustus, Jr. | Director           |                   |             | Mayoral Office |                       | [(410) 396-4735, Work] | [null, null] | [null, null] | 
| 1313870058  | ge_mo_communications         | Mayor's Office of Communications & Policy | Communications & Policy | MOCP    | [http://www.baltimorecity.gov/OfficeoftheMayor/MayoralOffices/CommunicationsandPolicy.aspx, null]   | [null, null]       | Ryan O'Doherty            | Director           |                   |             | Mayoral Office |                       | [(410) 818-4269, Work] | [null, null] | [null, null] | 
| 1313870058  | ge_youth                     | Youth Commission                          | Youth Commission        |         | [http://www.baltimorecity.gov/Government/BoardsandCommissions/YouthCommission.aspx, null]           | [null, null]       | Donald Wright Jr.         | Commission Chair   |                   |             | Commission     |                       | [(443) 984-3587, Work] | [null, null] | [null, null] | 
| 1313870058  | ge_ethics                    | Ethics Board                              | Ethics Board            |         | [http://www.baltimorecity.gov/Government/BoardsandCommissions/EthicsBoard.aspx, null]               | [null, null]       | Avery Aisenstark          | Director           |                   |             | Board          |                       | [(410) 396-4730, Work] | [null, null] | [null, null] | 
```