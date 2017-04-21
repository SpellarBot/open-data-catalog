# Outpatient Physical therapy locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/outpatient-physical-therapy-locations-b8446) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3gh2-6seg) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3gh2-6seg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3gh2-6seg/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3gh2-6seg |
| Name | Outpatient Physical therapy locations |
| Attribution | Department of Health |
| Category | Health |
| Tags | outpatient, physical, therapy |
| Created | 2012-08-26T21:54:00Z |
| Publication Date | 2012-08-26T21:58:26Z |

## Description

Department of Health Outpatient Physical Therapy locations

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | services    | Services   | text      | text        |
| Yes      | series tag  | house       | House      | text      | text        |
| Yes      | series tag  | zip_code    | Zip code   | text      | number      |
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
series e:3gh2-6seg d:2012-08-26T14:54:08.000Z t:phone=889-6211 t:services="Outpatient Physical Therapy" t:zip_code=96755 t:name="HAWAIIAN REHABILITATION SERVICES, INC.
(Kohala Hospital-Extension Unit)" t:house=54-383 t:island=Hawaii m:row_number.3gh2-6seg=1

series e:3gh2-6seg d:2012-08-26T14:54:08.000Z t:phone=883-3400 t:services="Outpatient Physical Therapy" t:zip_code=96738 t:name="HAWAIIAN REHABILITATION SERVICES, INC.(Waikoloa Road-Extension Unit)" t:house=68-1845 t:island=Hawaii m:row_number.3gh2-6seg=2

series e:3gh2-6seg d:2012-08-26T14:54:08.000Z t:phone=961-5776 t:services="Outpatient Physical Therapy" t:zip_code=96720 t:name="REHAB AT HILO" t:house=76 t:island=Hawaii m:row_number.3gh2-6seg=3
```

## Meta Commands

```ls
metric m:row_number.3gh2-6seg p:long l:"Row Number"

entity e:3gh2-6seg l:"Outpatient Physical therapy locations" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/3gh2-6seg

property e:3gh2-6seg t:meta.view v:id=3gh2-6seg v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Outpatient Physical therapy locations" v:attribution="Department of Health"

property e:3gh2-6seg t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:3gh2-6seg t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:3gh2-6seg t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                                                                      | services                                     | house   | zip_code | island | phone    | 
| =========== | ========================================================================= | ============================================ | ======= | ======== | ====== | ======== | 
| 1345992848  | HAWAIIAN REHABILITATION SERVICES, INC. (Kohala Hospital-Extension Unit)   | Outpatient Physical Therapy                  | 54-383  | 96755    | Hawaii | 889-6211 | 
| 1345992848  | HAWAIIAN REHABILITATION SERVICES, INC.(Waikoloa Road-Extension Unit)      | Outpatient Physical Therapy                  | 68-1845 | 96738    | Hawaii | 883-3400 | 
| 1345992848  | REHAB AT HILO                                                             | Outpatient Physical Therapy                  | 76      | 96720    | Hawaii | 961-5776 | 
| 1345992848  | REHAB AT KAILUA-KONA                                                      | Outpatient Physical Therapy                  | 75-1029 | 96740    | Hawaii | 334-0806 | 
| 1345992848  | HAWAIIAN REHABILITATION SERVICES, INC. (Hualalai Road)                    | Outpatient Physical Therapy                  | 75-165  | 96740    | Hawaii | 329-0591 | 
| 1345992848  | REHAB AT MAUI - KIHEI                                                     | Outpatient Physical Therapy                  | 221     | 96753    | Maui   | 879-5211 | 
| 1345992848  | REHAB AT KONA (Extension Unit)                                            | Outpatient Physical Therapy                  | 79-7430 | 96750    | Hawaii | 322-6766 | 
| 1345992848  | HAWAIIAN REHABILITATION SERVICES, INC. (Mamalahoa Highway-Extension Unit) | Outpatient Physical Therapy                  | 65-1230 | 96743    | Hawaii | 885-7131 | 
| 1345992848  | HAWAII PHYSICAL THERAPY AND CHIROPRACTIC CLINIC, INC.                     | Outpatient Physical Therapy and Chiropractic | 261     | 96720    | Hawaii | 961-5663 | 
```