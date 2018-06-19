# Hospice Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospice-facilities-dc1e3) |
| Metadata | [Link](https://data.hawaii.gov/api/views/c6z7-qg9b) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/c6z7-qg9b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/c6z7-qg9b/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | c6z7-qg9b |
| Name | Hospice Facilities |
| Attribution | Department of Health |
| Category | Health |
| Tags | hospice |
| Created | 2012-08-26T20:59:32Z |
| Publication Date | 2012-08-26T21:03:18Z |

## Description

Department of Health Hospice listing

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | services    | Services   | text      | text        |
| Yes      | series tag  | house       | House      | text      | text        |
| Yes      | series tag  | zip_code    | Zip code   | text      | text        |
| Yes      | series tag  | island      | Island     | text      | text        |
| Yes      | series tag  | phone       | PHONE      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:c6z7-qg9b d:2012-08-26T13:59:41.000Z t:phone=969-1733 t:services="HOSPICE Medicare" t:zip_code=96720 t:name="HOSPICE OF HILO" t:house=1011 t:island=Hawaii m:row_number.c6z7-qg9b=1

series e:c6z7-qg9b d:2012-08-26T13:59:41.000Z t:phone=245-7277 t:services="HOSPICE Medicare" t:zip_code=96766 t:name="KAUAI HOSPICE" t:house=4457 t:island=Kauai m:row_number.c6z7-qg9b=2

series e:c6z7-qg9b d:2012-08-26T13:59:41.000Z t:phone=885-7547 t:services="HOSPICE Medicare" t:zip_code=96743 t:name="NORTH HAWAII HOSPICE, INC." t:house=65-1328 t:island=Hawaii m:row_number.c6z7-qg9b=3
```

## Meta Commands

```ls
metric m:row_number.c6z7-qg9b p:long l:"Row Number"

entity e:c6z7-qg9b l:"Hospice Facilities" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/c6z7-qg9b

property e:c6z7-qg9b t:meta.view v:id=c6z7-qg9b v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Hospice Facilities" v:attribution="Department of Health"

property e:c6z7-qg9b t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:c6z7-qg9b t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:c6z7-qg9b t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                                        | services                    | house   | zip_code | island  | phone    | 
| =========== | =========================================== | =========================== | ======= | ======== | ======= | ======== | 
| 1345989581  | HOSPICE OF HILO                             | HOSPICE Medicare            | 1011    | 96720    | Hawaii  | 969-1733 | 
| 1345989581  | KAUAI HOSPICE                               | HOSPICE Medicare            | 4457    | 96766    | Kauai   | 245-7277 | 
| 1345989581  | NORTH HAWAII HOSPICE, INC.                  | HOSPICE Medicare            | 65-1328 | 96743    | Hawaii  | 885-7547 | 
| 1345989581  | BRISTOL HOSPICE ? HAWAII, LLC               | HOSPICE Medicare            | 500     | 96813    | Oahu    | 536-8012 | 
| 1345989581  | HOSPICE OF KONA                             | HOSPICE Medicare            | 75-5925 | 96740    | Hawaii  | 324-7700 | 
| 1345989581  | HOSPICE HAWAII - MOLOKA?I (EXTENSION UNIT)  | HOSPICE Medicare            | 280     | 96748    | Molokai | 553-4310 | 
| 1345989581  | HOSPICE MAUI                                | HOSPICE Medicare            | 400     | 96793    | Maui    | 244-5555 | 
| 1345989581  | ST. FRANCIS HOSPICE                         | HOSPICE Medicare, Inpatient | 24      | 96817    | Oahu    | 595-7566 | 
| 1345989581  | ST. FRANCIS HOSPICE - WEST (EXTENSION UNIT) | HOSPICE Medicare, Inpatient | 91-2127 | 96706    | Oahu    | 678-7549 | 
| 1345989581  | ISLANDS HOSPICE                             | HOSPICE Medicare            | 560     | 96817    | Oahu    | 550-2552 | 
```