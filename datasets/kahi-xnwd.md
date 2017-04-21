# Adult Day Health Center facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adult-day-health-center-facilities-ad4d6) |
| Metadata | [Link](https://data.hawaii.gov/api/views/kahi-xnwd) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/kahi-xnwd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/kahi-xnwd/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | kahi-xnwd |
| Name | Adult Day Health Center facilities |
| Attribution | Department of Health |
| Category | Health |
| Tags | adhc |
| Created | 2012-08-24T23:36:12Z |
| Publication Date | 2012-08-25T00:06:37Z |

## Description

Adult Day Health Center

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | service     | Service    | text      | text        |
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
series e:kahi-xnwd d:2012-08-24T17:06:01.000Z t:phone=440-3020 t:zip_code=96826 t:name="CENTRAL UNION CHURCH ADULT DAY CARE &
ADULT DAY HEALTH CENTER" t:service="Adult Day Health Center Free Standing" t:house=1660 t:island=Oahu m:row_number.kahi-xnwd=1

series e:kahi-xnwd d:2012-08-24T17:06:01.000Z t:phone=246-6919 t:zip_code=96766 t:name="KAUAI ADULT DAY HEALTH CENTER" t:service="Adult Day Health Center Free Standing" t:house=2943 t:island=Kauai m:row_number.kahi-xnwd=2

series e:kahi-xnwd d:2012-08-24T17:06:01.000Z t:phone=928-2050 t:zip_code=96777 t:name="KAU HOSPITAL" t:service="Adult Day Health Center Provider Base" t:house=1 t:island=Hawaii m:row_number.kahi-xnwd=3
```

## Meta Commands

```ls
metric m:row_number.kahi-xnwd p:long l:"Row Number"

entity e:kahi-xnwd l:"Adult Day Health Center facilities" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/kahi-xnwd

property e:kahi-xnwd t:meta.view v:id=kahi-xnwd v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Adult Day Health Center facilities" v:attribution="Department of Health"

property e:kahi-xnwd t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:kahi-xnwd t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:kahi-xnwd t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                                                          | service                               | house  | zip_code | island | phone    | 
| =========== | ============================================================= | ===================================== | ====== | ======== | ====== | ======== | 
| 1345827961  | CENTRAL UNION CHURCH ADULT DAY CARE & ADULT DAY HEALTH CENTER | Adult Day Health Center Free Standing | 1660   | 96826    | Oahu   | 440-3020 | 
| 1345827961  | KAUAI ADULT DAY HEALTH CENTER                                 | Adult Day Health Center Free Standing | 2943   | 96766    | Kauai  | 246-6919 | 
| 1345827961  | KAU HOSPITAL                                                  | Adult Day Health Center Provider Base | 1      | 96777    | Hawaii | 928-2050 | 
| 1345827961  | SALVATION ARMY ADULT DAY HEALTH SERVICES                      | Adult Day Health Center Free Standing | 296    | 96817    | Oahu   |          | 
| 1345827961  | HALE MAKUA (KAHULUI)                                          | Adult Day Health Center Provider Base | 472    | 96732    | Maui   | 877-2761 | 
| 1345827961  | MALUHIA                                                       | Adult Day Health Center Provider Base | 1027   | 96817    | Oahu   | 832-3000 | 
| 1345827961  | KILOHANA SENIOR ENRICHMENT CENTER                             | Adult Day Health Center Free Standing | 5289   | 96821    | Oahu   | 373-2700 | 
| 1345827961  | LEAHI HOSPITAL                                                | Adult Day Health Center Provider Base | 3675   | 96816    | Oahu   | 733-8000 | 
| 1345827961  | ANN PEARL NURSING FACILITY                                    | Adult Day Health Center Provider Base | 45-181 | 96744    | Oahu   | 247-8558 | 
```