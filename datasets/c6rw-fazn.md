# Department of Liquor Control (DLC) Licensee Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-liquor-control-dlc-licensee-data) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/c6rw-fazn) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/c6rw-fazn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/c6rw-fazn/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | c6rw-fazn |
| Name | Department of Liquor Control (DLC) Licensee Data |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | beer, wine, drinking, alcohol, restaurant, dining, liquor, license |
| Created | 2016-03-08T18:56:38Z |
| Publication Date | 2016-11-03T14:22:37Z |

## Description

List of all companies licensed by Montgomery County to sell alcoholic beverages to include name, address, and account number. Update Frequency: Monthly

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | licensee_name   | Licensee Name   | text      | text        |
| Yes      | series tag  | street          | Street          | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | state           | State           | text      | text        |
| Yes      | series tag  | zip             | Zip             | text      | text        |
| Yes      | series tag  | licensee_number | Licensee Number | text      | text        |
| Yes      | series tag  | channel_type    | Channel Type    | text      | text        |
| Yes      | series tag  | account_name    | Account Name    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:c6rw-fazn d:2016-03-09T11:41:43.000Z t:zip=20852 t:licensee_name="DEL FRISCO'S GRILLE" t:street="11800 GRAND PARK AVENUE" t:state=MD t:licensee_number=BBWLHR856 t:channel_type="On Premise" t:account_name="DEL FRISO'S GRILLE OF MARYLAND" t:city=ROCKVILLE m:row_number.c6rw-fazn=1

series e:c6rw-fazn d:2016-03-09T11:41:43.000Z t:zip=20878 t:licensee_name="PALADAR LATIN KITCHEN & RUM BAR - G" t:street="203 CROWNE PARK AVENUE" t:state=MD t:licensee_number=BBWLHR855 t:channel_type="On Premise" t:account_name="PALADAR GAITHERSBURG, LLC" t:city=GAITHERSBURG m:row_number.c6rw-fazn=2

series e:c6rw-fazn d:2016-03-09T11:41:43.000Z t:zip=20901 t:licensee_name="29 CONVENIENCE MART" t:street="10755 COLESVILLE ROAD" t:state=MD t:licensee_number=DBW125 t:channel_type=On/Off-Premise t:account_name="JACOB'S MIRAE, INC." t:city="SILVER SPRING" m:row_number.c6rw-fazn=3
```

## Meta Commands

```ls
metric m:row_number.c6rw-fazn p:long l:"Row Number"

entity e:c6rw-fazn l:"Department of Liquor Control (DLC) Licensee Data" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/c6rw-fazn

property e:c6rw-fazn t:meta.view v:id=c6rw-fazn v:category=Community/Recreation v:averageRating=0 v:name="Department of Liquor Control (DLC) Licensee Data" v:attribution="Montgomery County, MD"

property e:c6rw-fazn t:meta.view.license v:name="Public Domain"

property e:c6rw-fazn t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:c6rw-fazn t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | licensee_name                       | street                  | city           | state | zip   | licensee_number | channel_type   | account_name                   | 
| =========== | =================================== | ======================= | ============== | ===== | ===== | =============== | ============== | ============================== | 
| 1457523703  | DEL FRISCO'S GRILLE                 | 11800 GRAND PARK AVENUE | ROCKVILLE      | MD    | 20852 | BBWLHR856       | On Premise     | DEL FRISO'S GRILLE OF MARYLAND | 
| 1457523703  | PALADAR LATIN KITCHEN & RUM BAR - G | 203 CROWNE PARK AVENUE  | GAITHERSBURG   | MD    | 20878 | BBWLHR855       | On Premise     | PALADAR GAITHERSBURG, LLC      | 
| 1457523703  | 29 CONVENIENCE MART                 | 10755 COLESVILLE ROAD   | SILVER SPRING  | MD    | 20901 | DBW125          | On/Off-Premise | JACOB'S MIRAE, INC.            | 
| 1457523704  | ASIA NINE II                        | 254 CROWN PARK ROAD     | GAITHERSBURG   | MD    | 20878 | BBWLHR861       | On Premise     | THAIDEE, INC                   | 
| 1457523704  | BLO BLOW DRY BAR                    | 317 ELLINGTON BOULEVARD | GAITHERSBURG   | MD    | 20878 | SBSBW0001       | On Premise     | YATA MOCO, LLC                 | 
| 1459486843  | MAKI MAKI SUSHI                     | 8023 WISCONSIN AVE      | BETHESDA       | MD    | 20814 | HBW224          | On Premise     | JTL, LLC                       | 
| 1457523704  | CAMBRIA HOTEL & SUITES              | 1 HELEN HENEGHAN WAY    | ROCKVILLE      | MD    | 20850 | BBWLHM20442     | On Premise     | CRESENT HOTELS & RESORT, LLC   | 
| 1457523704  | CARLUCCIO'S                         | 11826 TRADE STREET      | NORTH BETHESDA | MD    | 20852 | BDBWLHR22663    | On/Off-Premise | CARLUCCIO'S USA GP             | 
| 1457523704  | BRETTON WOODS RECREATION CENTER     | 15700 RIVER ROAD        | GERMANTOWN     | MD    | 20874 | CBWLCC006       | On Premise     | BRETTON WOODS REC. CENTER, INC | 
| 1457523704  | TEDS BULLETIN                       | 220 ELLINGTON BOULEVARD | GAITHERSBURG   | MD    | 20878 | BBWLHR18583     | On Premise     | SWEATER VEST LLC               | 
```