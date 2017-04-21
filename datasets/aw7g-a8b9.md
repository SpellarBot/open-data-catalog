# IEPA - BOA - Minor Construction Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iepa-boa-minor-construction-permits-f5343) |
| Metadata | [Link](https://data.illinois.gov/api/views/aw7g-a8b9) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/aw7g-a8b9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/aw7g-a8b9/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | aw7g-a8b9 |
| Name | IEPA - BOA - Minor Construction Permits |
| Attribution | Hal Waggoner |
| Category | Environment |
| Tags | permits, air, construction, epa, environment |
| Created | 2011-09-29T20:18:09Z |
| Publication Date | 2011-09-29T20:36:51Z |

## Description

Bureau of Air Permit Streamlining Project for Minor Construction Permits. This class of permit would be for a new or expanded air emission source that is not subject to nonattainment new source review (NSR) or federal Prevention of Significant Deterioration (PSD) regulations.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | series tag  | program       | Program       | text          | text          |
| Yes      | series tag  | boa_id_number | BOA ID Number | text          | text          |
| Yes      | series tag  | facility_name | Facility Name | text          | text          |
| Yes      | series tag  | permit_number | Permit Number | text          | text          |
| Yes      | series tag  | operation     | Operation     | text          | text          |
| Yes      | time        | date_received | Date Received | calendar_date | calendar_date |
| Yes      | series tag  | analyst       | Analyst       | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:aw7g-a8b9 d:2008-01-02T00:00:00.000Z t:analyst=NULL t:operation="Biogas Scrubber" t:permit_number=8010061 t:facility_name="Tyson Fresh Meats Inc" t:program="TITLE V" t:boa_id_number=161817AAA m:row_number.aw7g-a8b9=1

series e:aw7g-a8b9 d:2008-12-12T00:00:00.000Z t:analyst="ROMAINE, CHRIS" t:operation="Product Storage" t:permit_number=8120016 t:facility_name="Marathon Petroleum Co LP" t:program="TITLE V" t:boa_id_number=031804AAS m:row_number.aw7g-a8b9=2

series e:aw7g-a8b9 d:2008-12-12T00:00:00.000Z t:analyst="SMITH, KEVIN" t:operation="Glycol Plt" t:permit_number=6060071 t:facility_name="Archer Daniels Midland Co" t:program="TITLE V" t:boa_id_number=115015AAE m:row_number.aw7g-a8b9=3
```

## Meta Commands

```ls
metric m:row_number.aw7g-a8b9 p:long l:"Row Number"

entity e:aw7g-a8b9 l:"IEPA - BOA - Minor Construction Permits" t:attribution="Hal Waggoner" t:url=https://data.illinois.gov/api/views/aw7g-a8b9

property e:aw7g-a8b9 t:meta.view v:id=aw7g-a8b9 v:category=Environment v:attributionLink=http://www.epa.state.il.us/air/permits/streamlining/index.html v:averageRating=0 v:name="IEPA - BOA - Minor Construction Permits" v:attribution="Hal Waggoner"

property e:aw7g-a8b9 t:meta.view.owner v:id=9gpg-gpch v:screenName=IEPA v:displayName=IEPA

property e:aw7g-a8b9 t:meta.view.tableauthor v:id=9gpg-gpch v:screenName=IEPA v:roleName=publisher v:displayName=IEPA
```

## Top Records

```ls
| program | boa_id_number | facility_name                         | permit_number | operation                   | date_received       | analyst        | 
| ======= | ============= | ===================================== | ============= | =========================== | =================== | ============== | 
| TITLE V | 161817AAA     | Tyson Fresh Meats Inc                 | 8010061       | Biogas Scrubber             | 2008-01-02T00:00:00 | NULL           | 
| TITLE V | 031804AAS     | Marathon Petroleum Co LP              | 8120016       | Product Storage             | 2008-12-12T00:00:00 | ROMAINE, CHRIS | 
| TITLE V | 115015AAE     | Archer Daniels Midland Co             | 6060071       | Glycol Plt                  | 2008-12-12T00:00:00 | SMITH, KEVIN   | 
| TITLE V | 097025AAR     | Countryside Genco LLC                 | 98050077      | LANDFILL GAS COGEN FACILITY | 2009-06-04T00:00:00 | PATEL, KUNJ    | 
| TITLE V | 057801AAA     | Ameren Energy Resources Generating Co | 9080011       | Sorbent Injection           | 2009-08-07T00:00:00 | PATEL, KUNJ    | 
| TITLE V | 141015AAB     | Rochelle Municipal Landfill #2        | 9100017       | Landfill Expansion          | 2009-10-13T00:00:00 | PATEL, KUNJ    | 
| TITLE V | 143808AAA     | Keystone Steel & Wire Co              | 9100039       | PSD                         | 2009-10-28T00:00:00 | SMITH, KEVIN   | 
| TITLE V | 001815AAF     | ADM Quincy                            | 10020013      | East Plt Expansion          | 2010-02-05T00:00:00 | SMITH, KEVIN   | 
| TITLE V | 119040AAC     | Amsted Rail Co Inc                    | 10070026      | No. 6 Floor Mod.            | 2010-07-14T00:00:00 | HECHT, KEVIN   | 
| TITLE V | 119040AAC     | Amsted Rail Co Inc                    | 10080008      | No 7 Shot Blast Machine     | 2010-08-06T00:00:00 | HECHT, KEVIN   | 
```