# IDPH Rural Health Center Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-rural-health-center-directory-cbd2d) |
| Metadata | [Link](https://data.illinois.gov/api/views/hpcx-tvp5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/hpcx-tvp5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/hpcx-tvp5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | hpcx-tvp5 |
| Name | IDPH Rural Health Center Directory |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | rural, health, rhc |
| Created | 2012-01-31T19:04:04Z |
| Publication Date | 2017-01-06T18:56:25Z |

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | rural_health_center | Rural Health Center | text      | text        |
| No       |             | dba                 | Address             | text      | text        |
| No       |             | address             | City                | text      | text        |
| Yes      | series tag  | county              | County              | text      | text        |
| Yes      | series tag  | zip                 | Zip                 | text      | number      |
| Yes      | series tag  | phone               | Phone               | phone     | phone       |
| Yes      | series tag  | medicare_           | Medicare #          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = dba,address
```

## Data Commands

```ls
series e:hpcx-tvp5 d:2017-01-06T18:55:45.000Z t:zip=61443 t:phone_number="(309) 853-2442" t:county=Henry t:medicare_=14-8985 t:rural_health_center="Ahearn & Associates Medical Center, Inc." m:row_number.hpcx-tvp5=1

series e:hpcx-tvp5 d:2017-01-06T18:55:45.000Z t:zip=61913 t:phone_number="(217) 578-3814" t:county=Douglas t:medicare_=14-3438 t:rural_health_center="Atwood Rural Health Clinic" m:row_number.hpcx-tvp5=2

series e:hpcx-tvp5 d:2017-01-06T18:55:45.000Z t:zip=61832 t:phone_number="(217) 446-3259" t:county=Vermilion t:medicare_=14-3878 t:rural_health_center="Bayview Family ClinicLtd - DBA Danville Pediatric Center" m:row_number.hpcx-tvp5=3
```

## Meta Commands

```ls
metric m:row_number.hpcx-tvp5 p:long l:"Row Number"

entity e:hpcx-tvp5 l:"IDPH Rural Health Center Directory" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/hpcx-tvp5

property e:hpcx-tvp5 t:meta.view v:id=hpcx-tvp5 v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Rural Health Center Directory" v:attribution="Division of Health Care Facilities and Programs"

property e:hpcx-tvp5 t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:hpcx-tvp5 t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| :updated_at | rural_health_center                                                   | dba                       | address     | county    | zip   | phone                  | medicare_ | 
| =========== | ===================================================================== | ========================= | =========== | ========= | ===== | ====================== | ========= | 
| 1483728945  | Ahearn & Associates Medical Center, Inc.                              | 513 Elliott Street, Ste.1 | Kewanee     | Henry     | 61443 | [(309) 853-2442, null] | 14-8985   | 
| 1483728945  | Atwood Rural Health Clinic                                            | 108 South Main            | Atwood      | Douglas   | 61913 | [(217) 578-3814, null] | 14-3438   | 
| 1483728945  | Bayview Family ClinicLtd - DBA Danville Pediatric Center              | 405 Sheridan              | Danville    | Vermilion | 61832 | [(217) 446-3259, null] | 14-3878   | 
| 1483728945  | Benton Community Healthcare                                           | 203 Bailey Lane, Suite 1  | Benton      | Franklin  | 62812 | [(618) 438-5670, null] | 78-3821   | 
| 1483728945  | Bowen Family Clinic                                                   | 209 E. 5th Street         | Bowen       | Hancock   | 62316 | [(217) 842-5211, null] | 14-3456   | 
| 1483728945  | Boyd-Fillager Clinic                                                  | 712 College Street        | Greenfield  | Greene    | 62044 | [(217) 368-3051, null] | 14-3474   | 
| 1483728945  | Brian W. Dossett, M.D., LTD.                                          | 1029 N. Eighth St.        | Vandalia    | Fayette   | 62471 | [(618) 283-4469, null] | 14-3917   | 
| 1483728945  | C.C. Medical Clinic                                                   | 1141 N Cheney Street      | Taylorville | Christian | 62568 | [(217) 287-7477, null] | 14-8921   | 
| 1483728945  | Carlinville Area Hospital Association - DBA Girard Family Health Care | 205 South Third Street    | Girard      | Macoupin  | 62640 | [(217) 627-2222, null] | 14-8532   | 
| 1483728945  | Carlinville Family Health Care                                        | 20613 North Broad Street  | Carlinville | Macoupin  | 62626 | [(217) 854-3881, null] | 14-8530   | 
```