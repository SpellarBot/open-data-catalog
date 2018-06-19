# Oregon Prisons

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-prisons-e7cfb) |
| Metadata | [Link](https://data.oregon.gov/api/views/dsje-kuhw) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dsje-kuhw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dsje-kuhw/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dsje-kuhw |
| Name | Oregon Prisons |
| Attribution | Oregon Department of Corrections |
| Category | Public Safety |
| Tags | prison, oregon, address, custody, medium, maximum, minimum |
| Created | 2010-11-17T17:20:52Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Names and addresses of Oregon State Prisons

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | prison_code      | prison_code      | text      | text        |
| Yes      | series tag  | prison_full_name | prison_full_name | text      | text        |
| Yes      | series tag  | prison_type      | prison_type      | text      | text        |
| No       |             | address_line_one | ADDRESS_LINE_ONE | text      | text        |
| No       |             | address_line_two | ADDRESS_LINE_TWO | text      | text        |
| Yes      | series tag  | city             | CITY             | text      | text        |
| Yes      | series tag  | state            | STATE            | text      | text        |
| Yes      | series tag  | zip              | ZIP              | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_line_one,address_line_two
```

## Data Commands

```ls
series e:dsje-kuhw d:2010-11-17T13:58:45.000Z t:prison_full_name="COFFEE CREEK CORRECTIONAL FACILITY" t:zip=97070 t:state=OR t:prison_type=MEDIUM t:city=Wilsonville t:prison_code=CCCF m:row_number.dsje-kuhw=1

series e:dsje-kuhw d:2010-11-17T13:58:46.000Z t:prison_full_name="CCCF Minimum" t:zip=97140 t:state=OR t:prison_type=MINIMUM t:city=SHERWOOD t:prison_code=CCCM m:row_number.dsje-kuhw=2

series e:dsje-kuhw d:2010-11-17T13:58:46.000Z t:prison_full_name="COLUMBIA RIVER CORRECTIONAL INSTITUTION" t:zip=97211 t:state=OR t:prison_type=MINIMUM t:city=PORTLAND t:prison_code=CRCI m:row_number.dsje-kuhw=3
```

## Meta Commands

```ls
metric m:row_number.dsje-kuhw p:long l:"Row Number"

entity e:dsje-kuhw l:"Oregon Prisons" t:attribution="Oregon Department of Corrections" t:url=https://data.oregon.gov/api/views/dsje-kuhw

property e:dsje-kuhw t:meta.view v:id=dsje-kuhw v:category="Public Safety" v:attributionLink=http://www.oregon.gov/doc v:averageRating=0 v:name="Oregon Prisons" v:attribution="Oregon Department of Corrections"

property e:dsje-kuhw t:meta.view.owner v:id=4d25-jqaq v:screenName="Shawn  Miller" v:displayName="Shawn  Miller"

property e:dsje-kuhw t:meta.view.tableauthor v:id=4d25-jqaq v:screenName="Shawn  Miller" v:displayName="Shawn  Miller"
```

## Top Records

```ls
| :updated_at | prison_code | prison_full_name                        | prison_type | address_line_one          | address_line_two | city        | state | zip   | 
| =========== | =========== | ======================================= | =========== | ========================= | ================ | =========== | ===== | ===== | 
| 1290002325  | CCCF        | COFFEE CREEK CORRECTIONAL FACILITY      | MEDIUM      | 24499 SW Grahams Ferry Rd |                  | Wilsonville | OR    | 97070 | 
| 1290002326  | CCCM        | CCCF Minimum                            | MINIMUM     | 11250 SW Clay St.         |                  | SHERWOOD    | OR    | 97140 | 
| 1290002326  | CRCI        | COLUMBIA RIVER CORRECTIONAL INSTITUTION | MINIMUM     | 9111 NE SUNDERLAND AVE    |                  | PORTLAND    | OR    | 97211 | 
| 1290002327  | DRCI        | DEER RIDGE CORRECTIONAL INSTITUTION     | MEDIUM      | 3920 ASHWOOD ROAD         |                  | MADRAS      | OR    | 97741 | 
| 1290002327  | EOCI        | EASTERN OREGON CORRECTIONAL INSTITUTION | MEDIUM      | 2500 WESTGATE             |                  | PENDLETON   | OR    | 97801 | 
| 1290002328  | MCCF        | MILL CREEK CORRECTIONAL FACILITY        | MINIMUM     | 5484 TURNER RD SE         |                  | SALEM       | OR    | 97317 | 
| 1290002328  | OSCI        | OREGON STATE CORRECTIONAL INSTITUTION   | MEDIUM      | 3405 DEER PARK DR SE      |                  | SALEM       | OR    | 97317 | 
| 1290002329  | OSP         | OREGON STATE PENITENTIARY               | MAXIMUM     | 2605 STATE ST.            |                  | SALEM       | OR    | 97310 | 
| 1290002329  | OSPM        | OSP Minimum                             | MINIMUM     | 2605 STATE ST.            |                  | SALEM       | OR    | 97310 | 
| 1290002330  | PRCF        | POWDER RIVER CORRECTIONAL FACILITY      | MINIMUM     | 3600 13TH ST.             |                  | BAKER CITY  | OR    | 97814 | 
```