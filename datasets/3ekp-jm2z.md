# Home Health Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-health-agencies-3a23b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/3ekp-jm2z) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/3ekp-jm2z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/3ekp-jm2z/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 3ekp-jm2z |
| Name | Home Health Agencies |
| Attribution | Department of Health |
| Category | Health |
| Tags | home, health |
| Created | 2012-08-26T20:51:59Z |
| Publication Date | 2012-08-26T20:56:45Z |

## Description

Department of Health Home Health Agencies listing

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
series e:3ekp-jm2z d:2012-08-26T13:52:10.000Z t:phone=244-4700 t:services="Licensed Home Health Agency" t:zip_code=96793 t:name="BAYADA HOME HEALTH CARE" t:house=2200 t:island=Maui m:row_number.3ekp-jm2z=1

series e:3ekp-jm2z d:2012-08-26T13:52:10.000Z t:phone=244-3661 t:services="Certified Licensed Home Health Agency" t:zip_code=96793 t:name="HALE MAKUA HOME HEALTH CARE AGENCY" t:house=1520 t:island=Maui m:row_number.3ekp-jm2z=2

series e:3ekp-jm2z d:2012-08-26T13:52:10.000Z t:phone=591-6050 t:services="Licensed Home Health Agency" t:zip_code=96740 t:name="BAYADA HOME HEALTH CARE" t:house=75-1000 t:island=Hawaii m:row_number.3ekp-jm2z=3
```

## Meta Commands

```ls
metric m:row_number.3ekp-jm2z p:long l:"Row Number"

entity e:3ekp-jm2z l:"Home Health Agencies" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/3ekp-jm2z

property e:3ekp-jm2z t:meta.view v:id=3ekp-jm2z v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Home Health Agencies" v:attribution="Department of Health"

property e:3ekp-jm2z t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:3ekp-jm2z t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:3ekp-jm2z t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                                   | services                              | house   | zip_code | island  | phone    | 
| =========== | ====================================== | ===================================== | ======= | ======== | ======= | ======== | 
| 1345989130  | BAYADA HOME HEALTH CARE                | Licensed Home Health Agency           | 2200    | 96793    | Maui    | 244-4700 | 
| 1345989130  | HALE MAKUA HOME HEALTH CARE AGENCY     | Certified Licensed Home Health Agency | 1520    | 96793    | Maui    | 244-3661 | 
| 1345989130  | BAYADA HOME HEALTH CARE                | Licensed Home Health Agency           | 75-1000 | 96740    | Hawaii  | 591-6050 | 
| 1345989130  | BAYADA HOME HEALTH CARE                | Licensed Home Health Agency           | 615     | 96814    | Oahu    | 591-6050 | 
| 1345989130  | HAUMEA HOME HEALTH AGENCY, LLC         | Licensed Home Health Agency           | 5326    | 96746    | Kauai   | 631-8514 | 
| 1345989130  | ST. FRANCIS HOME CARE SERVICES - KAUAI | Certified Licensed Home Health Agency | 4473    | 96766    | Kauai   | 245-6430 | 
| 1345989130  | CARERESOURCE HAWAII                    | Licensed Home Health Agency           | 10      | 96748    | Molokai | 553-9851 | 
| 1345989130  | CARERESOURCE HAWAII                    | Licensed Home Health Agency           | 355     | 96732    | Maui    | 871-2115 | 
| 1345989130  | WEST HAWAII HOME HEALTH SERVICES, INC. | Certified Licensed Home Health Agency | 82-5899 | 96704    | Hawaii  | 328-9883 | 
| 1345989130  | KOKUA NURSES, INC.                     | Certified Licensed Home Health Agency | 1210    | 96826    | Oahu    | 881-4711 | 
```