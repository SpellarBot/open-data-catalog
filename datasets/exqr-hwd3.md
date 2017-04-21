# Public Health Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-directory) |
| Metadata | [Link](https://data.oregon.gov/api/views/exqr-hwd3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/exqr-hwd3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/exqr-hwd3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | exqr-hwd3 |
| Name | Public Health Directory |
| Category | Health & Human Services |
| Created | 2016-12-22T21:37:11Z |
| Publication Date | 2016-12-23T01:00:33Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name               | Data Type | Render Type |
| ======== | =========== | =================== | ================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | title               | Title              | text      | text        |
| Yes      | series tag  | e_mail              | Email              | email     | email       |
| Yes      | series tag  | phone               | Phone              | text      | text        |
| Yes      | series tag  | fax                 | FAX                | text      | text        |
| Yes      | series tag  | tty_tdd             | TTY-TDD            | text      | text        |
| Yes      | series tag  | additionalcontact   | More Information   | text      | text        |
| No       |             | additionaladdress   | Additional Address | text      | text        |
| Yes      | series tag  | hoursofoperation    | Hours              | text      | text        |
| Yes      | series tag  | additionalhourstext | Notes              | text      | text        |
| Yes      | series tag  | staff               | Staff              | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = additionaladdress
```

## Data Commands

```ls
series e:exqr-hwd3 d:2016-12-22T21:37:13.000Z t:additionalcontact="Toll-free: 800-422-6012" t:hoursofoperation="9:00 AM - 4:00 PM" t:phone=971-673-0300 t:title="Oregon Immunization Program" t:fax=971-673-0278 t:e_mail=anne.m.vancuren@state.or.us m:row_number.exqr-hwd3=1

series e:exqr-hwd3 d:2016-12-22T21:37:13.000Z t:additionalcontact="Help Desk Contact" t:hoursofoperation="8:00 AM - 5:00 PM" t:phone=971-673-0741 t:title="Oregon Prescription Drug Monitoring Program (PDMP)" t:fax=971-673-0990 t:tty_tdd=971-673-0372 t:e_mail=pdmp.health@state.or.us m:row_number.exqr-hwd3=2

series e:exqr-hwd3 d:2016-12-22T21:37:13.000Z t:hoursofoperation="8:00 AM - 4:30 PM, Mon-Fri" t:phone=503-378-8667 t:title="Health Licensing Office (HLO)" t:fax=503-370-9004 t:e_mail=hlo.info@state.or.us m:row_number.exqr-hwd3=3
```

## Meta Commands

```ls
metric m:row_number.exqr-hwd3 p:long l:"Row Number"

entity e:exqr-hwd3 l:"Public Health Directory" t:url=https://data.oregon.gov/api/views/exqr-hwd3

property e:exqr-hwd3 t:meta.view v:id=exqr-hwd3 v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Directory"

property e:exqr-hwd3 t:meta.view.owner v:id=xv7a-3d5f v:profileImageUrlMedium=/api/users/xv7a-3d5f/profile_images/THUMB v:profileImageUrlLarge=/api/users/xv7a-3d5f/profile_images/LARGE v:screenName="Britt Parrott" v:profileImageUrlSmall=/api/users/xv7a-3d5f/profile_images/TINY v:displayName="Britt Parrott"

property e:exqr-hwd3 t:meta.view.tableauthor v:id=xv7a-3d5f v:profileImageUrlMedium=/api/users/xv7a-3d5f/profile_images/THUMB v:profileImageUrlLarge=/api/users/xv7a-3d5f/profile_images/LARGE v:screenName="Britt Parrott" v:profileImageUrlSmall=/api/users/xv7a-3d5f/profile_images/TINY v:roleName=editor v:displayName="Britt Parrott"
```

## Top Records

```ls
| :updated_at | title                                              | e_mail                               | phone        | fax          | tty_tdd      | additionalcontact                                   | additionaladdress  | hoursofoperation           | additionalhourstext | staff                    | 
| =========== | ================================================== | ==================================== | ============ | ============ | ============ | =================================================== | ================== | ========================== | =================== | ======================== | 
| 1482442633  | Oregon Immunization Program                        | anne.m.vancuren@state.or.us          | 971-673-0300 | 971-673-0278 |              | Toll-free: 800-422-6012                             |                    | 9:00 AM - 4:00 PM          |                     | [null, null, null, null] | 
| 1482442633  | Oregon Prescription Drug Monitoring Program (PDMP) | pdmp.health@state.or.us              | 971-673-0741 | 971-673-0990 | 971-673-0372 | Help Desk Contact                                   |                    | 8:00 AM - 5:00 PM          |                     | [null, null, null, null] | 
| 1482442633  | Health Licensing Office (HLO)                      | hlo.info@state.or.us                 | 503-378-8667 | 503-370-9004 |              |                                                     |                    | 8:00 AM - 4:30 PM, Mon-Fri |                     | [null, null, null, null] | 
| 1482442657  | Tuberculosis Program                               | heidi.behm@state.or.us               | 971-673-0169 | 971-673-0178 | 971-673-0372 |                                                     |                    | 8:00 AM - 5:00 PM          |                     | [null, null, null, null] | 
| 1482442657  | Healthy Child Care Oregon                          | heather.r.morrow-almeida@state.or.us | 971-673-1883 | 971-673-0250 | 971-673-0372 |                                                     |                    | 8:00 AM - 5:00 PM          |                     | [null, null, null, null] | 
| 1482442657  | Center for Health Protection                       | health.webmaster@state.or.us         | 971-673-0400 | 971-673-0456 | 971-673-0372 | Toll-free: 800-422-6012                             |                    | 8:00 AM - 5:00 PM          |                     | [null, null, null, null] | 
| 1482442657  | Health Impact Assessment (HIA) Program             | hia.info@state.or.us                 | 971-673-0977 | 971-673-0979 |              |                                                     |                    | 8:00 AM - 5:00 PM          |                     | [null, null, null, null] | 
| 1482442657  | EMS Professional Standards and Licensing           | veronica.seymour@state.or.us         | 971-673-0520 | 971-673-0555 | 971-673-0372 | General EMS & Trauma E-mail: ems.trauma@state.or.us | Driving Directions | 8:00 AM - 4:00 PM          |                     | [null, null, null, null] | 
| 1482442657  | Oral Health Unit                                   | oral.health@state.or.us              | 971-673-0348 | 971-673-0240 | 971-673-0372 |                                                     |                    | 8:00 AM - 5:00 PM          |                     | [null, null, null, null] | 
| 1482442657  | School-Based Health Center Program                 | SBHC.program@state.or.us             | 971-673-0871 |              |              |                                                     |                    | 8:00 A.M. - 5:00 P.M.      |                     | [null, null, null, null] | 
```