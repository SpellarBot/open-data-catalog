# State Owned Lands

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-owned-lands-b508f) |
| Metadata | [Link](https://data.ct.gov/api/views/meyk-xprb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/meyk-xprb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/meyk-xprb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | meyk-xprb |
| Name | State Owned Lands |
| Attribution | Officec of Policy and Management |
| Category | Government |
| Tags | pilot, property, usodcensus |
| Created | 2015-12-17T17:50:42Z |
| Publication Date | 2015-12-17T18:00:54Z |

## Description

A listing of individual properties owned by the State of Connecticut which is collected and updated annualy (in March) by the Office of Policy and Management. this inventory is maintained primarily for the purposes of payments in lieu of property taxes (PILOT) to the host municipaltiy. The column REF NO# refers to the local atx id for the parcel (if available) and and ADDRESS contains the physical address when assigned by the municipality, otherwise the street name is provided.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | ref_no      | REF NO#    | text      | text        |
| Yes      | series tag     | code        | CODE       | text      | text        |
| Yes      | series tag     | facility    | FACILITY   | text      | text        |
| Yes      | series tag     | town        | Town       | text      | text        |
| No       |                | address     | ADDRESS    | text      | text        |
| Yes      | numeric metric | acres       | ACRES      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:meyk-xprb d:2015-12-17T09:50:52.000Z t:facility="EX COM LN" t:ref_no="39 027 010-4A" t:town=Andover t:code=Transportation m:acres=2.65

series e:meyk-xprb d:2015-12-17T09:50:52.000Z t:facility="VACANT LAND" t:ref_no="39 036 0010-3" t:town=Andover t:code=Transportation m:acres=2.53

series e:meyk-xprb d:2015-12-17T09:50:52.000Z t:facility="EX COM LN" t:ref_no="39 036 0010-2" t:town=Andover t:code=Transportation m:acres=2.36
```

## Meta Commands

```ls
metric m:acres p:float l:ACRES t:dataTypeName=number

entity e:meyk-xprb l:"State Owned Lands" t:attribution="Officec of Policy and Management" t:url=https://data.ct.gov/api/views/meyk-xprb

property e:meyk-xprb t:meta.view v:id=meyk-xprb v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?a=2993&q=383338" v:averageRating=0 v:name="State Owned Lands" v:attribution="Officec of Policy and Management"

property e:meyk-xprb t:meta.view.license v:name="Public Domain"

property e:meyk-xprb t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:meyk-xprb t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | ref_no        | code           | facility           | town    | address          | acres | 
| =========== | ============= | ============== | ================== | ======= | ================ | ===== | 
| 1450345852  | 39 027 010-4A | Transportation | EX COM LN          | Andover | BUNKER HILL ROAD | 2.65  | 
| 1450345852  | 39 036 0010-3 | Transportation | VACANT LAND        | Andover | BUNKER HILL ROAD | 2.53  | 
| 1450345852  | 39 036 0010-2 | Transportation | EX COM LN          | Andover | BUNKER HILL ROAD | 2.36  | 
| 1450345852  | 39 036 0010-1 | Transportation | EX COM LN          | Andover | BUNKER HILL ROAD | 2.02  | 
| 1450345852  | 39 036 010A-1 | Transportation | EX COM LN          | Andover | BUNKER HILL ROAD | 0.55  | 
| 1450345852  | 39 027 0010-9 | Transportation | EX COM LN          | Andover | BUNKER HILL ROAD | 4.27  | 
| 1450345852  | 39 027 0010-8 | Transportation | EX COM LN          | Andover | BUNKER HILL ROAD | 4.73  | 
| 1450345852  | 39 027 010-3A | Transportation | EX COM LN          | Andover | BUNKER HILL ROAD | 2.30  | 
| 1450345852  | 39 027 010-2A | Transportation | VACANT LAND        | Andover | BUNKER HILL ROAD | 2.10  | 
| 1450345852  | 39 027 00013B | Recreation     | NATHAN HALE FOREST | Andover | BUNKER HILL ROAD | 0.50  | 
```