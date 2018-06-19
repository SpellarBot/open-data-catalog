# Maryland Title X Family Planning Clinics (As of October 2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-title-x-family-planning-clinics-1f3c2) |
| Metadata | [Link](https://data.maryland.gov/api/views/bpm6-i7k9) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/bpm6-i7k9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/bpm6-i7k9/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | bpm6-i7k9 |
| Name | Maryland Title X Family Planning Clinics (As of October 2012) |
| Attribution | Title X Delegates, Maternal and Child Health Bureau, Prevention and Health Promotion Administration. |
| Category | Health and Human Services |
| Tags | family planning, title x, birth control, women's health, pregnancy prevention, maternal and child health |
| Created | 2012-11-20T16:33:30Z |
| Publication Date | 2012-11-20T16:36:25Z |

## Description

Maryland Title X Family Planning Clinics as of 10/31/12. Title X is the only Federal grant program dedicated solely to providing individuals with comprehensive family planning and related preventive health services. The Title X program is designed to provide access to contraceptive services, supplies and information to all who want and need them. Services are provided on a sliding fee scale based on the individual's ability to pay. Individuals at or below 100% of the federal poverty level are not charged a fee.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| Yes      | series tag  | clinic_name | Clinic Name | text      | text        |
| Yes      | series tag  | phone       | Phone       | text      | text        |
| Yes      | series tag  | fax         | Fax         | text      | text        |
| Yes      | series tag  | county      | County      | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bpm6-i7k9 d:2012-01-01T00:00:00.000Z t:phone=301-723-3940 t:fax=301-723-3941 t:county=Allegany t:clinic_name="Tri-State Women's Health Center" m:row_number.bpm6-i7k9=1

series e:bpm6-i7k9 d:2012-01-01T00:00:00.000Z t:phone=410-222-7381 t:fax=410-222-4467 t:county="Anne Arundel" t:clinic_name="Annapolis Health Center, Health Services Building" m:row_number.bpm6-i7k9=2

series e:bpm6-i7k9 d:2012-01-01T00:00:00.000Z t:phone=410-222-7247 t:fax=410-222-4323 t:county="Anne Arundel" t:clinic_name="Parole Health Center" m:row_number.bpm6-i7k9=3
```

## Meta Commands

```ls
metric m:row_number.bpm6-i7k9 p:long l:"Row Number"

entity e:bpm6-i7k9 l:"Maryland Title X Family Planning Clinics (As of October 2012)" t:attribution="Title X Delegates, Maternal and Child Health Bureau, Prevention and Health Promotion Administration." t:url=https://data.maryland.gov/api/views/bpm6-i7k9

property e:bpm6-i7k9 t:meta.view v:id=bpm6-i7k9 v:category="Health and Human Services" v:averageRating=0 v:name="Maryland Title X Family Planning Clinics (As of October 2012)" v:attribution="Title X Delegates, Maternal and Child Health Bureau, Prevention and Health Promotion Administration."

property e:bpm6-i7k9 t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:bpm6-i7k9 t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| clinic_name                                       | phone        | fax          | county           | 
| ================================================= | ============ | ============ | ================ | 
| Tri-State Women's Health Center                   | 301-723-3940 | 301-723-3941 | Allegany         | 
| Annapolis Health Center, Health Services Building | 410-222-7381 | 410-222-4467 | Anne Arundel     | 
| Parole Health Center                              | 410-222-7247 | 410-222-4323 | Anne Arundel     | 
| North County Health Services                      | 410-222-6625 | 410-222-6679 | Anne Arundel     | 
| Dundalk Health Center                             | 410-887-7182 | 410-887-7184 | Baltimore County | 
| Eastern Family Resource Center                    | 410-887-0213 | 410-887-0418 | Baltimore County | 
| Essex Health Center                               | 410-887-0246 | 410-887-0265 | Baltimore County | 
| Liberty Family Resource Center                    | 410-887-0607 | 410-887-0713 | Baltimore County | 
| Hannah More Academy Center                        | 410-887-1152 | 410-887-1153 | Baltimore County | 
| Woodlawn Health Center                            | 410-887-6803 | 410-887-1386 | Baltimore County | 
```