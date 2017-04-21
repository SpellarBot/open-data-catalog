# Restricted Use Pesticide Dealers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/restricted-use-pesticide-dealers) |
| Metadata | [Link](https://data.hawaii.gov/api/views/cai8-hwet) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/cai8-hwet/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/cai8-hwet/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | cai8-hwet |
| Name | Restricted Use Pesticide Dealers |
| Attribution | Hawaii Department of Agriculture, Pesticides Branch |
| Category | Environmental Protection |
| Tags | agriculture, hdoa, pesticides, rups |
| Created | 2016-01-07T04:19:03Z |
| Publication Date | 2017-04-02T01:49:45Z |

## Description

Dealers licensed to sell Restricted Use Pesticides in the state of Hawaii.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | license_no      | LICENSE NO.     | text          | text          |
| Yes      | series tag  | company         | COMPANY         | text          | text          |
| Yes      | series tag  | first_name      | FIRST NAME      | text          | text          |
| Yes      | series tag  | middle          | MIDDLE          | text          | text          |
| Yes      | series tag  | last_name       | LAST NAME       | text          | text          |
| Yes      | series tag  | rep_cert        | REP CERT #      | text          | text          |
| Yes      | series tag  | phone           | Phone           | text          | text          |
| Yes      | series tag  | e_mail          | E-mail          | text          | text          |
| Yes      | time        | expiration_date | EXPIRATION DATE | calendar_date | calendar_date |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cai8-hwet d:2017-12-31T00:00:00.000Z t:first_name=William t:phone=831-637-0195 t:license_no=PD-461 t:rep_cert=US-001 t:company="Trical, Inc." t:last_name=Fukuda t:e_mail=bfukuda@trical.com m:row_number.cai8-hwet=1

series e:cai8-hwet d:2017-12-31T00:00:00.000Z t:first_name=Joseph t:phone=808-245-3472 t:license_no=PD-368 t:rep_cert=KA-005 t:company="Crop Production Services, Inc." t:last_name=Silva t:e_mail=joey.silva@cpsagu.com m:row_number.cai8-hwet=2

series e:cai8-hwet d:2017-12-31T00:00:00.000Z t:first_name=Kurt t:phone=808-216-5932 t:license_no=PD-384 t:rep_cert=OA-014 t:company="Univar USA" t:last_name=Nosal t:e_mail=hawaiikurt@yahoo.com t:middle=T. m:row_number.cai8-hwet=3
```

## Meta Commands

```ls
metric m:row_number.cai8-hwet p:long l:"Row Number"

entity e:cai8-hwet l:"Restricted Use Pesticide Dealers" t:attribution="Hawaii Department of Agriculture, Pesticides Branch" t:url=https://data.hawaii.gov/api/views/cai8-hwet

property e:cai8-hwet t:meta.view v:id=cai8-hwet v:category="Environmental Protection" v:averageRating=0 v:name="Restricted Use Pesticide Dealers" v:attribution="Hawaii Department of Agriculture, Pesticides Branch"

property e:cai8-hwet t:meta.view.owner v:id=dnu6-bvze v:profileImageUrlMedium=/api/users/dnu6-bvze/profile_images/THUMB v:profileImageUrlLarge=/api/users/dnu6-bvze/profile_images/LARGE v:screenName="HDOA Pesticides Branch" v:profileImageUrlSmall=/api/users/dnu6-bvze/profile_images/TINY v:displayName="HDOA Pesticides Branch"

property e:cai8-hwet t:meta.view.tableauthor v:id=dnu6-bvze v:profileImageUrlMedium=/api/users/dnu6-bvze/profile_images/THUMB v:profileImageUrlLarge=/api/users/dnu6-bvze/profile_images/LARGE v:screenName="HDOA Pesticides Branch" v:profileImageUrlSmall=/api/users/dnu6-bvze/profile_images/TINY v:roleName=editor v:displayName="HDOA Pesticides Branch"
```

## Top Records

```ls
| license_no | company                                      | first_name | middle | last_name | rep_cert | phone        | e_mail                         | expiration_date     | 
| ========== | ============================================ | ========== | ====== | ========= | ======== | ============ | ============================== | =================== | 
| PD-461     | Trical, Inc.                                 | William    |        | Fukuda    | US-001   | 831-637-0195 | bfukuda@trical.com             | 2017-12-31T00:00:00 | 
| PD-368     | Crop Production Services, Inc.               | Joseph     |        | Silva     | KA-005   | 808-245-3472 | joey.silva@cpsagu.com          | 2017-12-31T00:00:00 | 
| PD-384     | Univar USA                                   | Kurt       | T.     | Nosal     | OA-014   | 808-216-5932 | hawaiikurt@yahoo.com           | 2017-12-31T00:00:00 | 
| PD-34133   | J.R. Simplot Company                         | Peter      |        | Ballerini | D50008   | 808-326-7555 | Peter.ballerini@simplot.com    | 2017-12-31T00:00:00 | 
| PD-493     | Hawaii Grower Products, Inc.                 | Kevin      |        | Boteilho  | MM-022   | 808-877-6636 | kevin@hawaiigrowerproducts.com | 2017-02-08T00:00:00 | 
| PD-359     | Phoenix V LLC dba BEI Hawaii - Barbers Point | Iris       |        | Iwami     | OA-031   | 808-532-7414 | iiwami@beihawaii.com           | 2017-12-31T00:00:00 | 
| PD-337     | Hawaii Agro Solutions                        | John       |        | Sigurdson | HA-036   | 206-948-9501 | jsigurdson@comcast.net         | 2017-12-31T00:00:00 | 
| PD-34134   | J.R. Simplot Company                         | Kevin      |        | Boteilho  | D50009   | 808-877-6636 | kevin.boteilho@simplot.com     | 2017-12-31T00:00:00 | 
| PD-422     | USDA, APHIS, Wildlife Services               | Steven     | M.     | Tanaka    | OA-040   | 808-838-2843 | steven.m.tanaka@aphis.usda.gov | 2017-12-31T00:00:00 | 
| PD-33529   | Univar USA, Inc. (Maui)                      | Kurt       |        | Nosal     | OA-014   | 808-216-5932 | hawaiikurt@yahoo.com           | 2017-12-31T00:00:00 | 
```