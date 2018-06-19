# PSD Facility Addresses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/psd-facility-addresses-6bc54) |
| Metadata | [Link](https://data.hawaii.gov/api/views/i6md-8nrq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/i6md-8nrq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/i6md-8nrq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | i6md-8nrq |
| Name | PSD Facility Addresses |
| Created | 2013-11-21T00:27:55Z |
| Publication Date | 2013-11-21T07:48:46Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| No       | time           | :updated_at                               | updated_at                                | meta_data | meta_data   |
| Yes      | series tag     | department_of_public_safety_facility_name | Department of Public Safety Facility Name | text      | text        |
| Yes      | series tag     | facility_abbreviation                     | Facility Abbreviation                     | text      | text        |
| Yes      | numeric metric | design_bed_capacity                       | Design Bed Capacity                       | number    | number      |
| Yes      | numeric metric | operational_bed_capacity                  | Operational Bed Capacity                  | number    | number      |
| Yes      | series tag     | type_of_inmate_beds                       | Type of Inmate Beds                       | text      | text        |
| Yes      | series tag     | street                                    | Street                                    | text      | text        |
| Yes      | series tag     | city                                      | City                                      | text      | text        |
| Yes      | series tag     | state                                     | State                                     | text      | text        |
| Yes      | series tag     | zip                                       | Zip                                       | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i6md-8nrq d:2013-11-20T23:46:40.000Z t:zip=96720 t:facility_abbreviation=HCCC t:department_of_public_safety_facility_name="Hawaii Community Correctional Center" t:type_of_inmate_beds=State t:street="60 Punahele Street" t:state=Hawaii t:city=Hilo m:operational_bed_capacity=226 m:design_bed_capacity=206

series e:i6md-8nrq d:2013-11-20T23:46:54.000Z t:zip=96766 t:facility_abbreviation=KCCC t:department_of_public_safety_facility_name="Kauai Community Correctional Center" t:type_of_inmate_beds=State t:street="3-5351 Kuhio Highway" t:state=Hawaii t:city=Lihue m:operational_bed_capacity=128 m:design_bed_capacity=110

series e:i6md-8nrq d:2013-11-20T23:47:12.000Z t:zip=96793 t:facility_abbreviation=MCCC t:department_of_public_safety_facility_name="Maui Community Correctional Center" t:type_of_inmate_beds=State t:street="600 Waiale Drive" t:state=Hawaii t:city=Wailuku m:operational_bed_capacity=301 m:design_bed_capacity=209
```

## Meta Commands

```ls
metric m:design_bed_capacity p:integer l:"Design Bed Capacity" t:dataTypeName=number

metric m:operational_bed_capacity p:integer l:"Operational Bed Capacity" t:dataTypeName=number

entity e:i6md-8nrq l:"PSD Facility Addresses" t:url=https://data.hawaii.gov/api/views/i6md-8nrq

property e:i6md-8nrq t:meta.view v:id=i6md-8nrq v:averageRating=0 v:name="PSD Facility Addresses"

property e:i6md-8nrq t:meta.view.owner v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:lastNotificationSeenAt=1492637852 v:displayName="Meredith Slota"

property e:i6md-8nrq t:meta.view.tableauthor v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:lastNotificationSeenAt=1492637852 v:displayName="Meredith Slota"
```

## Top Records

```ls
| :updated_at | department_of_public_safety_facility_name | facility_abbreviation | design_bed_capacity | operational_bed_capacity | type_of_inmate_beds | street                      | city     | state   | zip   | 
| =========== | ========================================= | ===================== | =================== | ======================== | =================== | =========================== | ======== | ======= | ===== | 
| 1384978045  | Red Rock Correctional Center              | Red Rock CC, AZ       |                     |                          | Contracted          | 1750 E. Arica Road          | Eloy     | Arizona | 85131 | 
| 1384978045  | Saguaro Correctional Center               | Saguaro CC, AC        |                     |                          | Contracted          | 1252 E. Arica Road          | Eloy     | Arizona | 85131 | 
| 1384978045  | Honolulu Federal Detention Center         | FDC                   |                     |                          | Contracted          | 351 Elliott Street          | Honolulu | Hawaii  | 96819 | 
| 1384991200  | Hawaii Community Correctional Center      | HCCC                  | 206                 | 226                      | State               | 60 Punahele Street          | Hilo     | Hawaii  | 96720 | 
| 1384991214  | Kauai Community Correctional Center       | KCCC                  | 110                 | 128                      | State               | 3-5351 Kuhio Highway        | Lihue    | Hawaii  | 96766 | 
| 1384991232  | Maui Community Correctional Center        | MCCC                  | 209                 | 301                      | State               | 600 Waiale Drive            | Wailuku  | Hawaii  | 96793 | 
| 1384991250  | Oahu Community Correctional Center        | OCCC                  | 628                 | 954                      | State               | 2199 Kamehameha Highway     | Honolulu | Hawaii  | 96819 | 
| 1384991279  | Halawa Correctional Facility              | HMSF                  | 496                 | 992                      | State               | 99-902 Moanalua Road        | Aiea     | Hawaii  | 96701 | 
| 1384991289  | Halawa Correctional Facility              | SNF                   | 496                 | 992                      | State               | 99-902 Moanalua Road        | Aiea     | Hawaii  | 96701 | 
| 1384991304  | Women's Community Correctional Center     | WCCC                  | 258                 | 260                      | State               | 42-477 Kalanianaole Highway | Kailua   | Hawaii  | 96734 | 
```