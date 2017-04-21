# ODFW License Agents in OR

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/odfw-license-agents-in-or-dfae3) |
| Metadata | [Link](https://data.oregon.gov/api/views/wis2-2pdd) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wis2-2pdd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wis2-2pdd/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wis2-2pdd |
| Name | ODFW License Agents in OR |
| Attribution | Oregon Department of Fish and Wildlife and Oregon State Marine Board |
| Category | Natural Resources |
| Tags | fish and wildlife, boating, fishing, hunting, angling, permits, licenses, regulations, odfw, marine board, boat launches, aquatic invasive species, tyvek tags, non-motorized, paddling permits |
| Created | 2012-06-12T16:59:16Z |
| Publication Date | 2015-06-23T17:15:24Z |

## Description

Where outdoor enthusiasts can purchase Hunting and Fishing Licenses, Angling Tags, Controlled Hunt Applications, Game Bird Validations and Permits, Hunting Tags, Raffles, Sauvie Island Parking Permits and Aquatic Invasive Species Prevention Permits.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                | Data Type | Render Type |
| ======== | =========== | ===================== | =================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | agent_name            | Agent Name          | text      | text        |
| No       |             | agent_mailing_address | Agent Address       | text      | text        |
| Yes      | series tag  | city                  | City                | text      | text        |
| Yes      | series tag  | zip_code              | Zip Code            | text      | text        |
| Yes      | series tag  | odfw_license_agents   | ODFW License Agents | photo     | photo       |
| Yes      | series tag  | type_of_permit_sold   | Type of Permit Sold | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = agent_mailing_address
```

## Data Commands

```ls
series e:wis2-2pdd d:2015-06-22T16:37:59.000Z t:zip_code=97701 t:type_of_permit_sold="Annual permit & out-of-state permit" t:agent_name="DICK'S SPORTING GOODS #676" m:row_number.wis2-2pdd=1

series e:wis2-2pdd d:2015-06-22T16:37:59.000Z t:zip_code=97355 t:type_of_permit_sold="Annual permit & out-of-state permit" t:agent_name="M2 OUTDOOR SPORTS" m:row_number.wis2-2pdd=2

series e:wis2-2pdd d:2015-06-22T16:37:59.000Z t:zip_code=97467 t:type_of_permit_sold="Annual permit & out-of-state permit" t:agent_name="RECREATION STATION" m:row_number.wis2-2pdd=3
```

## Meta Commands

```ls
metric m:row_number.wis2-2pdd p:long l:"Row Number"

entity e:wis2-2pdd l:"ODFW License Agents in OR" t:attribution="Oregon Department of Fish and Wildlife and Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/wis2-2pdd

property e:wis2-2pdd t:meta.view v:id=wis2-2pdd v:category="Natural Resources" v:attributionLink=http://www.dfw.state.or.us/online_license_sales/index.asp v:averageRating=0 v:name="ODFW License Agents in OR" v:attribution="Oregon Department of Fish and Wildlife and Oregon State Marine Board"

property e:wis2-2pdd t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:wis2-2pdd t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| :updated_at | agent_name                 | agent_mailing_address | city | zip_code | odfw_license_agents | type_of_permit_sold                 | 
| =========== | ========================== | ===================== | ==== | ======== | =================== | =================================== | 
| 1434991079  | DICK'S SPORTING GOODS #676 | 63455 N HWY 97        |      | 97701    |                     | Annual permit & out-of-state permit | 
| 1434991079  | M2 OUTDOOR SPORTS          | 155 W GRANT STREET    |      | 97355    |                     | Annual permit & out-of-state permit | 
| 1434991079  | RECREATION STATION         | 1575 HWY 101 S        |      | 97467    |                     | Annual permit & out-of-state permit | 
| 1434991079  | FRED MEYER-WOOD VILLAGE    | 22855 NE PARKLANE     |      | 97060    |                     | Annual permit & out-of-state permit | 
| 1434991079  | UNION CREEK RESORT         | 56484 HWY 62          |      | 97536    |                     | Annual permit & out-of-state permit | 
| 1434991079  | GORGE FLY SHOP INC         | 201 OAK ST            |      | 97031    |                     | Annual permit & out-of-state permit | 
| 1434991079  | T & E'S GENERAL STORE      | 110 S MAPLE           |      | 97148    |                     | Annual permit & out-of-state permit | 
| 1434991079  | LAKESIDE MARKET            | 2448 ALSEA HWY        |      | 97394    |                     | Annual permit & out-of-state permit | 
| 1434991079  | MC ISAAC'S STORE           | 4966 BASELINE DR      |      | 97041    |                     | Annual permit & out-of-state permit | 
| 1434991079  | WAL-MART SUPERCENTER #1925 | 160 NW 25TH STREET    |      | 97365    |                     | Annual permit & out-of-state permit | 
```