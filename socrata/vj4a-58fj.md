# Hunt Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hunt-statistics-8b50e) |
| Metadata | [Link](https://data.wa.gov/api/views/vj4a-58fj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/vj4a-58fj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/vj4a-58fj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | vj4a-58fj |
| Name | Hunt Statistics |
| Attribution | WDFW |
| Category | Natural Resources & Environment |
| Tags | hunting, hunt |
| Created | 2012-08-08T23:56:49Z |
| Publication Date | 2012-08-09T00:07:25Z |

## Description

Decprecated: Hunting statistics from Department of Fish and Wildlife (DFW) for historical period 2011.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | stattype    | stattype   | text      | text        |
| Yes      | series tag     | uname       | uname      | text      | text        |
| Yes      | series tag     | nspecies    | nspecies   | text      | text        |
| Yes      | series tag     | unit        | unit       | text      | text        |
| Yes      | series tag     | reporttype  | reporttype | text      | text        |
| Yes      | series tag     | unittype    | unittype   | text      | text        |
| Yes      | series tag     | nmethod     | nmethod    | text      | text        |
| Yes      | numeric metric | licyr       | licyr      | number    | number      |
| Yes      | numeric metric | statvalue   | statvalue  | number    | number      |
| Yes      | numeric metric | sortorder   | SORTORDER  | number    | number      |
| Yes      | series tag     | tagtype     | tagtype    | text      | text        |
| Yes      | series tag     | weapon      | WEAPON     | text      | text        |
| Yes      | series tag     | src         | src        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vj4a-58fj d:2012-08-08T16:56:51.000Z t:unit=101 t:nspecies=COUGAR t:stattype="MALES HARVESTED" t:nmethod="ALL METHODS" t:uname=SHERMAN t:reporttype=HARVEST t:unittype=GMU m:sortorder=2 m:statvalue=1 m:licyr=2011

series e:vj4a-58fj d:2012-08-08T16:56:51.000Z t:unit=101 t:nspecies=COUGAR t:stattype="FEMALES HARVESTED" t:nmethod="ALL METHODS" t:uname=SHERMAN t:reporttype=HARVEST t:unittype=GMU m:sortorder=1 m:statvalue=2 m:licyr=2011

series e:vj4a-58fj d:2012-08-08T16:56:51.000Z t:unit=101 t:nspecies=COUGAR t:stattype="TOTAL HARVEST" t:nmethod="ALL METHODS" t:uname=SHERMAN t:reporttype=HARVEST t:unittype=GMU m:sortorder=4 m:statvalue=3 m:licyr=2011
```

## Meta Commands

```ls
metric m:licyr p:integer l:licyr t:dataTypeName=number

metric m:statvalue p:double l:statvalue t:dataTypeName=number

metric m:sortorder p:integer l:SORTORDER t:dataTypeName=number

entity e:vj4a-58fj l:"Hunt Statistics" t:attribution=WDFW t:url=https://data.wa.gov/api/views/vj4a-58fj

property e:vj4a-58fj t:meta.view v:id=vj4a-58fj v:category="Natural Resources & Environment" v:averageRating=40 v:name="Hunt Statistics" v:attribution=WDFW

property e:vj4a-58fj t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:vj4a-58fj t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | stattype          | uname      | nspecies | unit | reporttype | unittype | nmethod       | licyr | statvalue | sortorder | tagtype | weapon | src | 
| =========== | ================= | ========== | ======== | ==== | ========== | ======== | ============= | ===== | ========= | ========= | ======= | ====== | === | 
| 1344445011  | MALES HARVESTED   | SHERMAN    | COUGAR   | 101  | HARVEST    | GMU      | ALL METHODS   | 2011  | 1         | 2         |         |        |     | 
| 1344445011  | FEMALES HARVESTED | SHERMAN    | COUGAR   | 101  | HARVEST    | GMU      | ALL METHODS   | 2011  | 2         | 1         |         |        |     | 
| 1344445011  | TOTAL HARVEST     | SHERMAN    | COUGAR   | 101  | HARVEST    | GMU      | ALL METHODS   | 2011  | 3         | 4         |         |        |     | 
| 1344445011  | FEMALES HARVESTED | SHERMAN    | COUGAR   | 101  | HARVEST    | GMU      | RECREATION    | 2011  | 2         | 1         |         |        |     | 
| 1344445011  | TOTAL HARVEST     | SHERMAN    | COUGAR   | 101  | HARVEST    | GMU      | RECREATION    | 2011  | 2         | 4         |         |        |     | 
| 1344445011  | MALES HARVESTED   | SHERMAN    | COUGAR   | 101  | HARVEST    | GMU      | PUBLIC SAFETY | 2011  | 1         | 2         |         |        |     | 
| 1344445011  | TOTAL HARVEST     | SHERMAN    | COUGAR   | 101  | HARVEST    | GMU      | PUBLIC SAFETY | 2011  | 1         | 4         |         |        |     | 
| 1344445011  | MALES HARVESTED   | KELLY HILL | COUGAR   | 105  | HARVEST    | GMU      | ALL METHODS   | 2011  | 1         | 2         |         |        |     | 
| 1344445011  | FEMALES HARVESTED | KELLY HILL | COUGAR   | 105  | HARVEST    | GMU      | ALL METHODS   | 2011  | 1         | 1         |         |        |     | 
| 1344445011  | TOTAL HARVEST     | KELLY HILL | COUGAR   | 105  | HARVEST    | GMU      | ALL METHODS   | 2011  | 2         | 4         |         |        |     | 
```