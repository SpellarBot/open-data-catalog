# Department of Public Safety Bed Capacity 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-public-safety-bed-capacity-2013-9df72) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qv4n-m8rb) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qv4n-m8rb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qv4n-m8rb/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qv4n-m8rb |
| Name | Department of Public Safety Bed Capacity 2013 |
| Category | Public Safety |
| Created | 2013-06-08T00:01:15Z |
| Publication Date | 2013-06-27T16:21:04Z |

## Description

Q1 2013. Capacity is compared with the Weekly Population Report.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | facility                 | Facility                 | text      | text        |
| Yes      | numeric metric | design_bed_capacity      | Design Bed Capacity      | number    | number      |
| Yes      | numeric metric | operational_bed_capacity | Operational Bed Capacity | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qv4n-m8rb d:2013-01-01T00:00:00.000Z t:facility=HCCC m:operational_bed_capacity=226 m:design_bed_capacity=206

series e:qv4n-m8rb d:2013-01-01T00:00:00.000Z t:facility=SMSF m:operational_bed_capacity=992 m:design_bed_capacity=496

series e:qv4n-m8rb d:2013-01-01T00:00:00.000Z t:facility=KCCC m:operational_bed_capacity=128 m:design_bed_capacity=110
```

## Meta Commands

```ls
metric m:design_bed_capacity p:integer l:"Design Bed Capacity" t:dataTypeName=number

metric m:operational_bed_capacity p:integer l:"Operational Bed Capacity" t:dataTypeName=number

entity e:qv4n-m8rb l:"Department of Public Safety Bed Capacity 2013" t:url=https://data.hawaii.gov/api/views/qv4n-m8rb

property e:qv4n-m8rb t:meta.view v:id=qv4n-m8rb v:category="Public Safety" v:averageRating=0 v:name="Department of Public Safety Bed Capacity 2013"

property e:qv4n-m8rb t:meta.view.license v:name="Public Domain"

property e:qv4n-m8rb t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:qv4n-m8rb t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| facility | design_bed_capacity | operational_bed_capacity | 
| ======== | =================== | ======================== | 
| HCCC     | 206                 | 226                      | 
| SMSF     | 496                 | 992                      | 
| KCCC     | 110                 | 128                      | 
| MCCC     | 209                 | 301                      | 
| OCCC     | 628                 | 954                      | 
| WCCC     | 258                 | 260                      | 
| WCF      | 294                 | 334                      | 
| SNF      | 90                  | 132                      | 
```