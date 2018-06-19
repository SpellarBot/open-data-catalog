# Active Sporting License Issuing Agents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-sporting-license-issuing-agents) |
| Metadata | [Link](https://data.ny.gov/api/views/66qd-rvmy) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/66qd-rvmy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/66qd-rvmy/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 66qd-rvmy |
| Name | Active Sporting License Issuing Agents |
| Attribution | Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | sporting licenses, deer management permits |
| Created | 2014-10-31T20:51:54Z |
| Publication Date | 2016-02-10T16:33:08Z |

## Description

The name, mailing address and telephone number for the retail establishments and municipalities that sell hunting, fishing, and trapping licenses and associated privileges and permits.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | agent_id      | Agent ID      | text      | number      |
| Yes      | series tag  | business_name | Business Name | text      | text        |
| No       |             | address_1     | Address 1     | text      | text        |
| No       |             | address_2     | Address 2     | text      | text        |
| Yes      | series tag  | county        | County        | text      | text        |
| Yes      | series tag  | city          | City          | text      | text        |
| Yes      | series tag  | state         | State         | text      | text        |
| Yes      | series tag  | zip           | Zip           | text      | text        |
| Yes      | series tag  | phone_number  | Phone Number  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:66qd-rvmy d:2015-12-23T15:06:11.000Z t:business_name="DICK'S SPORTING GOODS INC.#20" t:zip=12110 t:phone_number=518-783-0701 t:county=Latham t:state=NY t:agent_id=1002 t:city=Albany m:row_number.66qd-rvmy=1

series e:66qd-rvmy d:2015-12-23T15:06:11.000Z t:business_name="TOWN OF GUILDERLAND" t:zip=12084 t:phone_number=518-356-1980 t:county=Guilderland t:state=NY t:agent_id=1007 t:city=Albany m:row_number.66qd-rvmy=2

series e:66qd-rvmy d:2015-12-23T15:06:11.000Z t:business_name="TOWN OF BRANT" t:zip=14027 t:phone_number=716-549-0282 t:county=Brant t:state=NY t:agent_id=1018 t:city=Erie m:row_number.66qd-rvmy=3
```

## Meta Commands

```ls
metric m:row_number.66qd-rvmy p:long l:"Row Number"

entity e:66qd-rvmy l:"Active Sporting License Issuing Agents" t:attribution="Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/66qd-rvmy

property e:66qd-rvmy t:meta.view v:id=66qd-rvmy v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/permits/95448.html v:averageRating=0 v:name="Active Sporting License Issuing Agents" v:attribution="Department of Environmental Conservation"

property e:66qd-rvmy t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:66qd-rvmy t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:66qd-rvmy t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | agent_id | business_name                 | address_1                     | address_2   | county       | city       | state | zip   | phone_number | 
| =========== | ======== | ============================= | ============================= | =========== | ============ | ========== | ===== | ===== | ============ | 
| 1450883171  | 1002     | DICK'S SPORTING GOODS INC.#20 | 579 Troy-Schdy Rd, Suite 124  |             | Latham       | Albany     | NY    | 12110 | 518-783-0701 | 
| 1450883171  | 1007     | TOWN OF GUILDERLAND           | P.O. Box 339                  |             | Guilderland  | Albany     | NY    | 12084 | 518-356-1980 | 
| 1450883171  | 1018     | TOWN OF BRANT                 | 1272 Brant-North Collins Road | Po Box 228  | Brant        | Erie       | NY    | 14027 | 716-549-0282 | 
| 1450883171  | 1027     | TOWN OF HAMBURG               | S6100 South Park Ave          |             | Hamburg      | Erie       | NY    | 14075 | 716-649-6111 | 
| 1450883172  | 2065     | TOWN OF CAMDEN                | Po Box 265                    |             | Camden       | Oneida     | NY    | 13316 | 315-245-2180 | 
| 1450883171  | 1034     | TOWN OF SARDINIA              | 12320 Savage Road             | Po Box 219  | Sardinia     | Erie       | NY    | 14134 | 716-496-8900 | 
| 1450883171  | 1036     | TOWN OF WALES                 | 12345 Big Tree Road           | Po Box 264  | Wales Center | Erie       | NY    | 14169 | 716-652-0589 | 
| 1450883171  | 1067     | TOWN OF LIVINGSTON            | 119 County Route 19           |             | Livingston   | Columbia   | NY    | 12541 | 518-851-9441 | 
| 1450883171  | 1074     | TOWN OF YORK                  | 2668 Main Street              | P O Box 187 | York         | Livingston | NY    | 14592 | 585-243-3128 | 
| 1450883171  | 1081     | TOWN OF MIDDLESEX             | 1216 Route 245 - Main Street  | P O Box 147 | Middlesex    | Yates      | NY    | 14507 | 585-554-3607 | 
```