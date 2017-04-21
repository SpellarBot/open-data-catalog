# Proposed Coal Export Terminal Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/proposed-coal-export-terminal-locations-dec94) |
| Metadata | [Link](https://data.wa.gov/api/views/tmay-2i9v) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/tmay-2i9v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/tmay-2i9v/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | tmay-2i9v |
| Name | Proposed Coal Export Terminal Locations |
| Created | 2013-07-16T19:06:17Z |
| Publication Date | 2013-07-16T21:50:48Z |

## Description

Locations based on lat and long

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | website     | Website    | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tmay-2i9v d:2013-07-16T12:09:25.000Z t:website=http://www.ecy.wa.gov/geographic/millennium/index.html t:name="Millennium Bulk Terminals - Longview Proposed Coal Export Terminal" m:row_number.tmay-2i9v=1

series e:tmay-2i9v d:2013-07-16T12:15:48.000Z t:website=http://www.ecy.wa.gov/geographic/gatewaypacific/ t:name="Gateway Pacific Terminal at Cherry Point Proposal" m:row_number.tmay-2i9v=2
```

## Meta Commands

```ls
metric m:row_number.tmay-2i9v p:long l:"Row Number"

entity e:tmay-2i9v l:"Proposed Coal Export Terminal Locations" t:url=https://data.wa.gov/api/views/tmay-2i9v

property e:tmay-2i9v t:meta.view v:id=tmay-2i9v v:averageRating=0 v:name="Proposed Coal Export Terminal Locations"

property e:tmay-2i9v t:meta.view.owner v:id=fdwy-m844 v:screenName="Linda Kent" v:displayName="Linda Kent"

property e:tmay-2i9v t:meta.view.tableauthor v:id=fdwy-m844 v:screenName="Linda Kent" v:roleName=publisher v:displayName="Linda Kent"
```

## Top Records

```ls
| :updated_at | name                                                               | website                                                        | 
| =========== | ================================================================== | ============================================================== | 
| 1373976565  | Millennium Bulk Terminals - Longview Proposed Coal Export Terminal | [http://www.ecy.wa.gov/geographic/millennium/index.html, null] | 
| 1373976948  | Gateway Pacific Terminal at Cherry Point Proposal                  | [http://www.ecy.wa.gov/geographic/gatewaypacific/, null]       | 
```