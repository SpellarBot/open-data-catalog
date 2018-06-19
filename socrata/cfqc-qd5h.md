# IDPH Licensed Swimming Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-licensed-swimming-facilities-c2cd9) |
| Metadata | [Link](https://data.illinois.gov/api/views/cfqc-qd5h) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cfqc-qd5h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cfqc-qd5h/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cfqc-qd5h |
| Name | IDPH Licensed Swimming Facilities |
| Attribution | Illinois Department of Public Health, Division of Environmental Health |
| Category | Public Health |
| Tags | swim, idph, license |
| Created | 2013-11-04T15:12:47Z |
| Publication Date | 2013-11-04T15:18:48Z |

## Description

Swimming facilities, including beaches, licensed by the Illinois Department of Public Health. Swimming facilities are comprised of aquatic features which have individual an license and operational status.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | license_id         | LICENSE ID#        | text      | text        |
| Yes      | series tag     | fac_license_status | FAC LICENSE STATUS | text      | text        |
| Yes      | series tag     | facility_name      | FACILITY NAME      | text      | text        |
| Yes      | series tag     | county             | COUNTY             | text      | text        |
| Yes      | series tag     | idph_region        | IDPH REGION        | text      | text        |
| Yes      | series tag     | feature_name       | FEATURE NAME       | text      | text        |
| Yes      | series tag     | feature_location   | FEATURE LOCATION   | text      | text        |
| Yes      | series tag     | feature_type       | FEATURE TYPE       | text      | text        |
| Yes      | series tag     | feature_status     | FEATURE STATUS     | text      | text        |
| Yes      | numeric metric | batherload         | BATHERLOAD         | number    | number      |
| Yes      | numeric metric | volume             | VOLUME             | number    | number      |
| Yes      | numeric metric | surface_area       | SURFACE AREA       | number    | number      |
| Yes      | series tag     | s_e_compliance     | S/E COMPLIANCE     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cfqc-qd5h d:2013-11-04T07:12:50.000Z t:feature_type="Swimming Pool" t:feature_name="OUTDOOR SWIM 1" t:facility_name="SHERWOOD GARDEN CONDOMINIUM ASSOC" t:county=Cook t:feature_location=Outdoor t:license_id=133-04864 t:idph_region="West Chicago" t:feature_status=Open t:s_e_compliance=Yes m:surface_area=1000 m:volume=30000 m:batherload=56

series e:cfqc-qd5h d:2013-11-04T07:12:52.000Z t:feature_type="Swimming Pool" t:feature_name="INDOOR SWIM 1" t:facility_name="GURNEE FAIRFIELD INN" t:county=Lake t:feature_location=Indoor t:license_id=133-07601 t:idph_region="West Chicago" t:feature_status=Open t:s_e_compliance=Yes m:batherload=36

series e:cfqc-qd5h d:2013-11-04T07:12:52.000Z t:feature_type=Spa t:feature_name="SPA 1" t:facility_name="GURNEE FAIRFIELD INN" t:county=Lake t:feature_location=Indoor t:license_id=133-07601 t:idph_region="West Chicago" t:feature_status="Closed Permanently" t:s_e_compliance=Yes m:batherload=5
```

## Meta Commands

```ls
metric m:batherload p:integer l:BATHERLOAD t:dataTypeName=number

metric m:volume p:integer l:VOLUME t:dataTypeName=number

metric m:surface_area p:integer l:"SURFACE AREA" t:dataTypeName=number

entity e:cfqc-qd5h l:"IDPH Licensed Swimming Facilities" t:attribution="Illinois Department of Public Health, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/cfqc-qd5h

property e:cfqc-qd5h t:meta.view v:id=cfqc-qd5h v:category="Public Health" v:attributionLink=http://ehlicv5pub.illinois.gov/Clients/ILDOHENV/PUBLIC/Swimming_Verifications.aspx v:averageRating=0 v:name="IDPH Licensed Swimming Facilities" v:attribution="Illinois Department of Public Health, Division of Environmental Health"

property e:cfqc-qd5h t:meta.view.license v:name="Public Domain"

property e:cfqc-qd5h t:meta.view.owner v:id=6dyi-26tm v:screenName="ken mccann" v:displayName="ken mccann"

property e:cfqc-qd5h t:meta.view.tableauthor v:id=6dyi-26tm v:screenName="ken mccann" v:roleName=publisher v:displayName="ken mccann"
```

## Top Records

```ls
| :updated_at | license_id | fac_license_status | facility_name                     | county | idph_region  | feature_name   | feature_location | feature_type  | feature_status     | batherload | volume | surface_area | s_e_compliance | 
| =========== | ========== | ================== | ================================= | ====== | ============ | ============== | ================ | ============= | ================== | ========== | ====== | ============ | ============== | 
| 1383549170  | 133-04864  | Active             | SHERWOOD GARDEN CONDOMINIUM ASSOC | Cook   | West Chicago |                |                  |               |                    |            |        |              |                | 
| 1383549170  | 133-04864  |                    | SHERWOOD GARDEN CONDOMINIUM ASSOC | Cook   | West Chicago | OUTDOOR SWIM 1 | Outdoor          | Swimming Pool | Open               | 56         | 30000  | 1000         | Yes            | 
| 1383549171  | 133-07056  | Inactive           | KELLY'S CAMP                      | Lake   | West Chicago |                |                  |               |                    |            |        |              |                | 
| 1383549171  | 133-07056  |                    | KELLY'S CAMP                      | Lake   | West Chicago | INDOOR SWIM 1  | Indoor           | Swimming Pool | Closed             |            |        |              | No             | 
| 1383549171  | 133-07056  |                    | KELLY'S CAMP                      | Lake   | West Chicago | OUTDOOR SWIM 2 | Outdoor          | Swimming Pool | Closed             |            |        |              | No             | 
| 1383549172  | 133-07601  | Ordinance Agency   | GURNEE FAIRFIELD INN              | Lake   | West Chicago |                |                  |               |                    |            |        |              |                | 
| 1383549172  | 133-07601  |                    | GURNEE FAIRFIELD INN              | Lake   | West Chicago | INDOOR SWIM 1  | Indoor           | Swimming Pool | Open               | 36         |        |              | Yes            | 
| 1383549172  | 133-07601  |                    | GURNEE FAIRFIELD INN              | Lake   | West Chicago | SPA 1          | Indoor           | Spa           | Closed Permanently | 5          |        |              | Yes            | 
| 1383549173  | 133-08733  | Pending            | Residence Inn                     | DuPage | West Chicago |                |                  |               |                    |            |        |              |                | 
| 1383549173  | 133-08733  |                    | Residence Inn                     | DuPage | West Chicago |                |                  | NULL          |                    |            |        |              | No             | 
```