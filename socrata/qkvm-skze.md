# OAHU Food Establishments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oahu-food-establishments-8adda) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qkvm-skze) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qkvm-skze/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qkvm-skze/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qkvm-skze |
| Name | OAHU Food Establishments |
| Attribution | Department of Health |
| Category | Health |
| Tags | food, restaurants |
| Created | 2012-10-12T23:54:57Z |
| Publication Date | 2012-10-13T01:55:21Z |

## Description

lists represent all of the permitted Food Establishments.  These include everything from Restaurants, take out, Fast-food, Convenience stores, Mom and Pop Markets, shave ice stands, supermarkets, Mega markets like Costco-Sam?s-Walmart, lunch wagons, food manufacturers, etc

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | establishment                     | Establishment                     | text          | text          |
| Yes      | series tag     | permit_holder                     | Permit Holder                     | text          | text          |
| Yes      | series tag     | telephone                         | Telephone                         | text          | text          |
| Yes      | numeric metric | establishment_permit              | Establishment Permit #            | number        | number        |
| Yes      | series tag     | establishment_address_street_name | Establishment Address Street Name | text          | text          |
| No       |                | establishment_address_unit        | Establishment Address Unit #      | text          | text          |
| No       |                | establishment_address_city        | Establishment Address City        | text          | text          |
| No       |                | establishment_address_state       | Establishment Address State       | text          | text          |
| No       |                | establishment_address_zip_code    | Establishment Address Zip Code    | text          | number        |
| Yes      | series tag     | mailing_address_street_name       | Mailing Address Street Name       | text          | text          |
| No       |                | mailing_address_unit              | Mailing Address Unit #            | text          | text          |
| No       |                | mailing_address_city              | Mailing Address City              | text          | text          |
| No       |                | mailing_address_state             | Mailing Address State             | text          | text          |
| No       |                | mailing_address_zip_code          | Mailing Address Zip Code          | text          | number        |
| Yes      | series tag     | mailing_care_of                   | Mailing Care Of                   | text          | text          |
| Yes      | numeric metric | po_box                            | PO BOX                            | number        | number        |
| Yes      | numeric metric | facility_permit                   | Facility Permit #                 | number        | number        |
| Yes      | series tag     | business_status                   | Business Status                   | text          | text          |
| Yes      | series tag     | facility_type                     | Facility Type                     | text          | text          |
| Yes      | series tag     | risk_category                     | Risk Category                     | text          | text          |
| Yes      | time           | st_inspection                     | 1st Inspection                    | calendar_date | calendar_date |
| Yes      | numeric metric | tmkzone                           | TMKZone                           | number        | number        |
| Yes      | numeric metric | tmksection                        | TMKSection                        | number        | number        |
| Yes      | numeric metric | tmkplat                           | TMKPlat                           | number        | number        |
| Yes      | numeric metric | tmkparcel                         | TMKParcel                         | number        | number        |
| No       |                | permit_expire_date                | Permit Expire Date                | calendar_date | calendar_date |
```

## Time Field

```ls
Value = st_inspection
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = establishment_address_unit,establishment_address_city,establishment_address_state,establishment_address_zip_code,mailing_address_unit,mailing_address_city,mailing_address_state,mailing_address_zip_code,permit_expire_date
```

## Data Commands

```ls
series e:qkvm-skze d:2011-07-25T00:00:00.000Z t:risk_category="Category 1" t:establishment="MATSUMOTO'S OKAZUYA RESTAURANT, LLC" t:mailing_address_street_name="GULICK AVENUE" t:facility_type="137 New and Renewal 1" t:business_status=Open t:permit_holder="TODD MATSUMOTO" t:telephone=(808)721-7464 t:establishment_address_street_name="GULICK AVENUE" m:tmkzone=1 m:facility_permit=8807 m:tmkparcel=24 m:tmkplat=7 m:establishment_permit=8807 m:tmksection=3

series e:qkvm-skze d:2011-11-01T00:00:00.000Z t:risk_category="Category 2" t:establishment="RAINBOW SCHOOL" t:mailing_address_street_name="WAIKALUA ROAD" t:facility_type="137 New and Renewal 2" t:business_status=Open t:permit_holder="RAINBOW SCHOOL" t:telephone=(808)293-9341 t:establishment_address_street_name="WAIKALUA ROAD" m:tmkzone=4 m:facility_permit=2355 m:tmkparcel=12 m:tmkplat=16 m:establishment_permit=2355 m:tmksection=5

series e:qkvm-skze d:2010-08-23T00:00:00.000Z t:mailing_care_of="SUBWAY MANOA (JUB CO., LTD.)" t:risk_category="Category 2" t:establishment="SUBWAY KCC" t:mailing_address_street_name="WOODLAWN DRIVE" t:facility_type="137 New and Renewal 2" t:business_status=Open t:permit_holder="JUB CO., LTD." t:telephone=(808)728-4177 t:establishment_address_street_name="DIAMOND HEAD ROAD" m:tmkzone=3 m:facility_permit=13972 m:tmkparcel=9 m:tmkplat=42 m:establishment_permit=13972 m:tmksection=1
```

## Meta Commands

```ls
metric m:establishment_permit p:integer l:"Establishment Permit #" t:dataTypeName=number

metric m:po_box p:integer l:"PO BOX" t:dataTypeName=number

metric m:facility_permit p:integer l:"Facility Permit #" t:dataTypeName=number

metric m:tmkzone p:integer l:TMKZone t:dataTypeName=number

metric m:tmksection p:integer l:TMKSection t:dataTypeName=number

metric m:tmkplat p:integer l:TMKPlat t:dataTypeName=number

metric m:tmkparcel p:integer l:TMKParcel t:dataTypeName=number

entity e:qkvm-skze l:"OAHU Food Establishments" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/qkvm-skze

property e:qkvm-skze t:meta.view v:id=qkvm-skze v:category=Health v:averageRating=0 v:name="OAHU Food Establishments" v:attribution="Department of Health"

property e:qkvm-skze t:meta.view.license v:name="Creative Commons Attribution | No Derivative Works 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-nd/3.0/legalcode v:logoUrl=images/licenses/cc30bynd.png

property e:qkvm-skze t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:qkvm-skze t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| establishment                       | permit_holder             | telephone     | establishment_permit | establishment_address_street_name | establishment_address_unit | establishment_address_city | establishment_address_state | establishment_address_zip_code | mailing_address_street_name | mailing_address_unit | mailing_address_city | mailing_address_state | mailing_address_zip_code | mailing_care_of              | po_box | facility_permit | business_status | facility_type         | risk_category | st_inspection       | tmkzone | tmksection | tmkplat | tmkparcel | permit_expire_date  | 
| =================================== | ========================= | ============= | ==================== | ================================= | ========================== | ========================== | =========================== | ============================== | =========================== | ==================== | ==================== | ===================== | ======================== | ============================ | ====== | =============== | =============== | ===================== | ============= | =================== | ======= | ========== | ======= | ========= | =================== | 
| MATSUMOTO'S OKAZUYA RESTAURANT, LLC | TODD MATSUMOTO            | (808)721-7464 | 8807                 | GULICK AVENUE                     |                            | HONOLULU                   | HAWAII                      | 96817                          | GULICK AVENUE               |                      | HONOLULU             | HAWAII                | 96817                    |                              |        | 8807            | Open            | 137 New and Renewal 1 | Category 1    | 2011-07-25T00:00:00 | 1       | 3          | 7       | 24        | 2013-08-02T00:00:00 | 
| RAINBOW SCHOOL                      | RAINBOW SCHOOL            | (808)293-9341 | 2355                 | WAIKALUA ROAD                     |                            | KANEOHE                    | HAWAII                      | 96744                          | WAIKALUA ROAD               |                      | KANEOHE              | HAWAII                | 96744                    |                              |        | 2355            | Open            | 137 New and Renewal 2 | Category 2    | 2011-11-01T00:00:00 | 4       | 5          | 16      | 12        | 2013-11-18T00:00:00 | 
| SUBWAY KCC                          | JUB CO., LTD.             | (808)728-4177 | 13972                | DIAMOND HEAD ROAD                 |                            | HONOLULU                   | HAWAII                      | 96816                          | WOODLAWN DRIVE              | 5-106                | HONOLULU             | HAWAII                | 96822                    | SUBWAY MANOA (JUB CO., LTD.) |        | 13972           | Open            | 137 New and Renewal 2 | Category 2    | 2010-08-23T00:00:00 | 3       | 1          | 42      | 9         |                     | 
| 7-ELEVEN STORE #54211               | SEVEN-ELEVEN HAWAII, INC. | (808)526-1711 | 11849                | SOUTH KING STREET                 |                            | HONOLULU                   | HAWAII                      | 96826                          | NUUANU AVENUE               | 2ND FLOOR            | HONOLULU             | HAWAII                | 96817                    | MASAE DOTE                   |        | 11849           | Open            | 137 New and Renewal 2 | Category 2    | 2011-09-29T00:00:00 | 2       | 8          | 24      | 10        | 2013-10-15T00:00:00 | 
| L & L WINDWARD CITY, INC.           | KWOCK YUM KAM             | (808)236-3030 | 3542                 | KANEOHE BAY DRIVE                 |                            | KANEOHE                    | HAWAII                      | 96744                          | KANEOHE BAY DRIVE           |                      | KANEOHE              | HAWAII                | 96744                    |                              |        | 3542            | Open            | 137 New and Renewal 1 | Category 1    | 2010-02-25T00:00:00 | 4       | 5          | 60      | 61        |                     | 
| 99 CAFE VIETNAMESE CUISINE, LLC     | 99 CAFE VIETNAMESE, LLC   | (808)256-8541 | 15168                | NORTH KING STREET                 |                            | HONOLULU                   | HAWAII                      | 96817                          | NORTH KING STREET           |                      | HONOLULU             | HAWAII                | 96817                    |                              |        | 15168           | Open            | 137 New and Renewal 1 | Category 1    | 2012-01-03T00:00:00 | 1       | 7          | 3       | 29        | 2014-01-03T00:00:00 | 
| PACO ALAFANSO (CW853)               | PACO & YOWANINA ALAFANSO  | (808)842-1432 | 13215                | KALAUNU STREET                    |                            | HONOLULU                   | HAWAII                      | 96819                          | KALAUNU STREET              |                      | HONOLULU             | HAWAII                | 96819                    |                              |        | 13215           | Open            | 137 New and Renewal 3 | Category 3    | 2011-10-10T00:00:00 | 1       | 3          | 22      | 1         | 2013-10-01T00:00:00 | 
| ON STAGE DRINKS & GRINDS            | MERLITA SHERMAN           | (808)306-7799 | 7663                 | KAPAHULU AVENUE                   |                            | HONOLULU                   | HAWAII                      | 96816                          | KAPAHULU AVENUE             |                      | HONOLULU             | HAWAII                | 96816                    |                              |        | 7663            | Open            | 137 New and Renewal 3 | Category 3    | 2011-06-02T00:00:00 | 2       | 7          | 32      | 6         | 2013-06-26T00:00:00 | 
| SAIGON NOODLE HOUSE #3              | LOAN UYENO                | (808)387-6556 | 15538                | OLIVE AVENUE                      |                            | WAHIAWA                    | HAWAII                      | 96786                          | OLIVE AVENUE                |                      | WAHIAWA              | HAWAII                | 96786                    |                              |        | 15538           | Open            | 137 New and Renewal 2 | Category 2    | 2012-06-07T00:00:00 | 7       | 4          | 3       | 44        | 2014-06-07T00:00:00 | 
| KAPAHULU STOP & SHOP                | POK CHA NISHI             | (808)737-0443 | 11430                | KAPAHULU AVENUE                   |                            | HONOLULU                   | HAWAII                      | 96815                          | KAPAHULU AVENUE             |                      | HONOLULU             | HAWAII                | 96815                    |                              |        | 11430           | Open            | 137 New and Renewal 2 | Category 2    | 2011-05-24T00:00:00 | 3       | 1          | 22      | 6         | 2013-05-16T00:00:00 | 
```