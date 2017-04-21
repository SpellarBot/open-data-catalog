# Statewide Food Est List11-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-food-est-list11-2011-ad3d7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/9ekn-r3cm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/9ekn-r3cm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/9ekn-r3cm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 9ekn-r3cm |
| Name | Statewide Food Est List11-2011 |
| Attribution | Department of Health |
| Category | Health |
| Tags | restaurant, food |
| Created | 2012-10-13T02:21:18Z |
| Publication Date | 2012-10-17T23:17:58Z |

## Description

Statewide dbase as of the end of 2011.
all of the permitted Food Establishments.  These include everything from Restaurants, take out, Fast-food, Convenience stores, Mom and Pop Markets, shave ice stands, supermarkets, Mega markets like Costco-Sam?s-Walmart, lunch wagons, food manufacturers, etc

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| Yes      | series tag  | estname     | EstName     | text      | text        |
| Yes      | series tag  | phonenoest  | PhoneNoEst  | text      | text        |
| Yes      | series tag  | email       | EMail       | text      | text        |
| Yes      | series tag  | owner       | OWNER       | text      | text        |
| Yes      | series tag  | mailaddr1   | MailAddr1   | text      | text        |
| Yes      | series tag  | mailaddr2   | MailAddr2   | text      | text        |
| Yes      | series tag  | mailcity    | MailCity    | text      | text        |
| Yes      | series tag  | mailzip     | MailZip     | text      | number      |
| Yes      | series tag  | esttype1    | EstType1    | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9ekn-r3cm d:2011-01-01T00:00:00.000Z t:mailaddr2="DENA & SERGIO RAMIREZ" t:phonenoest="45-3626-A MAMANE STREET" t:esttype1="SIT DOWN (RESTAURANT)" t:mailcity="P.O. BOX 1557" t:estname="CAFE IL MONDO, LLC" t:email=HONOKAA t:mailzip=96727 t:owner=(808)775-7711 m:row_number.9ekn-r3cm=1

series e:9ekn-r3cm d:2011-01-01T00:00:00.000Z t:mailaddr2="VSE HILO, LLC" t:phonenoest="111 E. PUAINAKO STREET, SPACE 790" t:esttype1="SIT DOWN (RESTAURANT)" t:mailcity="1850 ALA MOANA BOULEVARD" t:estname=IHOP t:email=HILO t:mailzip=96815 t:owner=(808)947-8555 m:row_number.9ekn-r3cm=2

series e:9ekn-r3cm d:2011-01-01T00:00:00.000Z t:mailaddr2="KAWAIHAE PIZZA, INC." t:phonenoest="308 KAMEHAMEHA AVENUE" t:esttype1="SIT DOWN (RESTAURANT)" t:mailcity="308 KAMEHAMEHA AVENUE" t:estname="CAFE PESTO" t:email=HILO t:mailzip=96720 t:owner=(808)969-6640 m:row_number.9ekn-r3cm=3
```

## Meta Commands

```ls
metric m:row_number.9ekn-r3cm p:long l:"Row Number"

entity e:9ekn-r3cm l:"Statewide Food Est List11-2011" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/9ekn-r3cm

property e:9ekn-r3cm t:meta.view v:id=9ekn-r3cm v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Statewide Food Est List11-2011" v:attribution="Department of Health"

property e:9ekn-r3cm t:meta.view.license v:name="Creative Commons Attribution | No Derivative Works 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-nd/3.0/legalcode v:logoUrl=images/licenses/cc30bynd.png

property e:9ekn-r3cm t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:9ekn-r3cm t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| estname                    | phonenoest                        | email   | owner         | mailaddr1                    | mailaddr2                        | mailcity                   | mailzip | esttype1              | description | 
| ========================== | ================================= | ======= | ============= | ============================ | ================================ | ========================== | ======= | ===================== | =========== | 
| CAFE IL MONDO, LLC         | 45-3626-A MAMANE STREET           | HONOKAA | (808)775-7711 |                              | DENA & SERGIO RAMIREZ            | P.O. BOX 1557              | 96727   | SIT DOWN (RESTAURANT) |             | 
| IHOP                       | 111 E. PUAINAKO STREET, SPACE 790 | HILO    | (808)947-8555 |                              | VSE HILO, LLC                    | 1850 ALA MOANA BOULEVARD   | 96815   | SIT DOWN (RESTAURANT) |             | 
| CAFE PESTO                 | 308 KAMEHAMEHA AVENUE             | HILO    | (808)969-6640 |                              | KAWAIHAE PIZZA, INC.             | 308 KAMEHAMEHA AVENUE      | 96720   | SIT DOWN (RESTAURANT) |             | 
| HOKULANI'S STEAK HOUSE     | 16-586 OLD VOLCANO ROAD, #106     | KEAAU   | (808)966-5560 |                              | HOKULANI'S STEAK HOUSE, LLC      | 1333 OPUA STREET           | 96818   | SIT DOWN (RESTAURANT) |             | 
| HAMAKUA SPORTS BAR & GRILL | 45-3490 G MAMANE STREET, UNIT G   | HONOKAA | (808)775-1444 | bigislandbrewery@hotmail.com | BIG ISLAND BREWERY, LLC          | 45-3490 G MAMANE STREET    | 92727   | SIT DOWN (RESTAURANT) |             | 
| COCONUT GRILL              | 136 BANYAN WAY                    | HILO    | (808)961-3330 |                              | PARADISE HOSPITALITY GROUP, INC. | 411 HUALI PLACE            | 96720   | SIT DOWN (RESTAURANT) |             | 
| HILO BAY CAF?              | 315 MAKAALA STREET, #109          | HILO    | (808)935-4939 |                              | HILO BAY CAF?, INC.              | 315 MAKAALA STREET, #109   | 96720   | SIT DOWN (RESTAURANT) |             | 
| HAWAIIAN VANILLA CO.       | 43-2007 PAAUILO MAUKA ROAD        | PAAUILO | (808)776-1771 |                              | JIM REDDEKOPP                    | 43-2007 PAAUILO MAUKA ROAD | 96776   | SIT DOWN (RESTAURANT) |             | 
| HILO TOWN TAVERN & PIZZA   | 168 KEAWE STREET                  | HILO    | (808)989-5385 |                              | RHONDA NICHOLS                   | 168 KEAWE STREET           | 96720   | SIT DOWN (RESTAURANT) |             | 
| CLUB RAINBOW-HILO          | 688 KINOOLE STREET, UNIT 128      | HILO    | (808)935-2000 |                              | CHONG TSUKAYAMA                  | 556 POHAKULANI STREET      | 96720   | SIT DOWN (RESTAURANT) |             | 
```