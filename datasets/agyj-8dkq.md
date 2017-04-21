# Agency Payroll Contacts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agency-payroll-contacts-343fb) |
| Metadata | [Link](https://data.oregon.gov/api/views/agyj-8dkq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/agyj-8dkq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/agyj-8dkq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | agyj-8dkq |
| Name | Agency Payroll Contacts |
| Attribution | Kari Kampert, OSPS |
| Category | Administrative |
| Tags | payroll, osps, agency, contact |
| Created | 2014-09-17T17:28:02Z |
| Publication Date | 2014-09-17T18:13:36Z |

## Description

Need to contact someone in your agency's payroll department. Well look no further!

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| No       | time        | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | agency                       | Agency                       | text      | html        |
| Yes      | series tag  | agency_number                | Agency Number                | text      | text        |
| Yes      | series tag  | agency_payroll_phone_number  | Agency Payroll Phone Number  | phone     | phone       |
| Yes      | series tag  | agency_payroll_email_contact | Agency Payroll Email Contact | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:agyj-8dkq d:2014-09-17T10:59:44.000Z t:phone_number=503-378-3708 t:agency_payroll_email_contact=OSPS.Payroll@oregon.gov t:agency="Administrative Services (DAS)" t:agency_number=10700 m:row_number.agyj-8dkq=1

series e:agyj-8dkq d:2014-09-17T10:59:44.000Z t:phone_number=503-945-6286 t:agency_payroll_email_contact=OFS-Payroll@state.or.us t:agency="Human Services (DHS)" t:agency_number=10000 m:row_number.agyj-8dkq=2

series e:agyj-8dkq d:2014-09-17T10:59:44.000Z t:phone_number=503-945-6286 t:agency_payroll_email_contact=OFS-Payroll@state.or.us t:agency="Oregon Health Authority" t:agency_number=44300 m:row_number.agyj-8dkq=3
```

## Meta Commands

```ls
metric m:row_number.agyj-8dkq p:long l:"Row Number"

entity e:agyj-8dkq l:"Agency Payroll Contacts" t:attribution="Kari Kampert, OSPS" t:url=https://data.oregon.gov/api/views/agyj-8dkq

property e:agyj-8dkq t:meta.view v:id=agyj-8dkq v:category=Administrative v:attributionLink=http://www.oregon.gov/DAS/EGS/FBS/OSPS/pages/index.aspx v:averageRating=0 v:name="Agency Payroll Contacts" v:attribution="Kari Kampert, OSPS"

property e:agyj-8dkq t:meta.view.owner v:id=dfu9-nz7s v:screenName="Kari Kampert" v:displayName="Kari Kampert"

property e:agyj-8dkq t:meta.view.tableauthor v:id=dfu9-nz7s v:screenName="Kari Kampert" v:displayName="Kari Kampert"
```

## Top Records

```ls
| :updated_at | agency                                          | agency_number | agency_payroll_phone_number | agency_payroll_email_contact | 
| =========== | =============================================== | ============= | =========================== | ============================ | 
| 1410951584  | Administrative Services (DAS)                   | 10700         | [503-378-3708, null]        | OSPS.Payroll@oregon.gov      | 
| 1410951584  | Human Services (DHS)                            | 10000         | [503-945-6286, null]        | OFS-Payroll@state.or.us      | 
| 1410951584  | Oregon Health Authority                         | 44300         | [503-945-6286, null]        | OFS-Payroll@state.or.us      | 
| 1410951584  | Licensed Professional Counselors and Therapists | 10800         | [503-378-3708, null]        | osps.payroll@oregon.gov      | 
| 1410951584  | Aviation                                        | 10900         | [503-986-3900, null]        | mary.rooper@odot.state.or.us | 
| 1410951584  | Long Term Care Ombudsman                        | 11400         | [503-378-3708, null]        | osps.payroll@oregon.gov      | 
| 1410951584  | Employment Relations Board                      | 11500         | [503-378-3708, null]        | osps.payroll@oregon.gov      | 
| 1410951584  | Tax Practitioners Board                         | 11900         | [503-378-3708, null]        | osps.payroll@oregon.gov      | 
| 1410951584  | Accountancy Board                               | 12000         | [503-378-3708, null]        | osps.payroll@oregon.gov      | 
| 1410951584  | Governor's Office                               | 12100         | [503-378-3708, null]        | osps.payroll@oregon.gov      | 
```