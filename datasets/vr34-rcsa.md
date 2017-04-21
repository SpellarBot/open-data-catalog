# Family Guidance Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/family-guidance-centers-bc3ae) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vr34-rcsa) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vr34-rcsa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vr34-rcsa/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vr34-rcsa |
| Name | Family Guidance Centers |
| Attribution | Department of Health |
| Category | Health |
| Tags | family |
| Created | 2012-08-25T01:52:15Z |
| Publication Date | 2012-08-25T01:54:39Z |

## Description

Family Guidance Centers

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
series e:vr34-rcsa d:2012-08-24T18:52:21.000Z t:phone=733-9393 t:services="Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services" t:zip_code=96816 t:name="Honolulu Family Guidance Center" t:house=3627 t:island=Oahu m:row_number.vr34-rcsa=1

series e:vr34-rcsa d:2012-08-24T18:52:21.000Z t:phone=692-7700 t:services="Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services" t:zip_code=96707 t:name="Leeward Oahu Family Guidance Center" t:house=601 t:island=Oahu m:row_number.vr34-rcsa=2

series e:vr34-rcsa d:2012-08-24T18:52:21.000Z t:phone=565-7915 t:services="Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services" t:zip_code=96763 t:name="Maui Family Guidance Center" t:house=555 t:island=Lanai m:row_number.vr34-rcsa=3
```

## Meta Commands

```ls
metric m:row_number.vr34-rcsa p:long l:"Row Number"

entity e:vr34-rcsa l:"Family Guidance Centers" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/vr34-rcsa

property e:vr34-rcsa t:meta.view v:id=vr34-rcsa v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Family Guidance Centers" v:attribution="Department of Health"

property e:vr34-rcsa t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:vr34-rcsa t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:vr34-rcsa t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                                | services                                                                                                                                                              | house   | zip_code | island | phone    | 
| =========== | =================================== | ===================================================================================================================================================================== | ======= | ======== | ====== | ======== | 
| 1345834341  | Honolulu Family Guidance Center     | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 3627    | 96816    | Oahu   | 733-9393 | 
| 1345834341  | Leeward Oahu Family Guidance Center | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 601     | 96707    | Oahu   | 692-7700 | 
| 1345834341  | Maui Family Guidance Center         | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 555     | 96763    | Lanai  | 565-7915 | 
| 1345834341  | Big Island Family Guidance Center   | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 81-980  | 96750    | Hawaii | 322-1541 | 
| 1345834341  | Maui Family Guidance Center         | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 270     | 96793    | Maui   | 243-1252 | 
| 1345834341  | Family Court Liaison Branch         | Psychiatric Evaluations, Suicide Risk Assessments, Medication Management, Psychotherapy, Family Therapy, Crisis Intervention, Care Coordination                       | 42-477  | 96734    | Oahu   | 266-9922 | 
| 1345834341  | Big Island Family Guidance Center   | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 88      | 96720    | Hawaii | 933-0558 | 
| 1345834341  | Central Oahu Family Guidance Center | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 45-6911 | 96744    | Oahu   | 233-3770 | 
| 1345834341  | Maui Family Guidance Center         | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 1830    | 96761    | Maui   | 662-4045 | 
| 1345834341  | Central Oahu Family Guidance Center | Care Coordination, Liaison with DOE, Receipt of Referrals, Registration, Intensive Clinical Case Management Services, Procurement of Intensive Mental Health Services | 54-010  | 96717    | Oahu   | 293-8993 | 
```