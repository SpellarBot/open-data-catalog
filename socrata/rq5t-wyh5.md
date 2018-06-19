# Current Licensed Hospitals-2017 11072016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-licensed-hospitals-2017-11072016) |
| Metadata | [Link](https://data.maryland.gov/api/views/rq5t-wyh5) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/rq5t-wyh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/rq5t-wyh5/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | rq5t-wyh5 |
| Name | Current Licensed Hospitals-2017 11072016 |
| Category | Agriculture |
| Tags | veterinary hospitals |
| Created | 2016-11-07T21:21:30Z |
| Publication Date | 2016-11-21T18:10:42Z |

## Description

Veterinary Hospitals registered for FY 2017 (July1, 2016 to June 30, 2016) - updated 11/07/2016

## Columns

```ls
| Included | Schema Type | Field Name          | Name            | Data Type | Render Type |
| ======== | =========== | =================== | =============== | ========= | =========== |
| Yes      | series tag  | countydesc          | HOSPITAL COUNTY | text      | text        |
| Yes      | series tag  | hosp_name           | HOSPITAL NAME   | text      | text        |
| Yes      | series tag  | hosp_owner          | HOSPITAL OWNER  | text      | text        |
| Yes      | series tag  | hosp_addr           | STREET ADDRESS  | text      | text        |
| Yes      | series tag  | bus_licno           | LICENSE NUMBER  | text      | text        |
| Yes      | series tag  | hosp_city_hosp_st_h | CITY, STATE,ZIP | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rq5t-wyh5 d:2017-01-01T00:00:00.000Z t:bus_licno=02-080 t:hosp_owner="ERIC ALEXANDER, DVM" t:countydesc="ANNE ARUNDEL" t:hosp_city_hosp_st_h="SEVERNA PARK, MD 21146" t:hosp_addr="160 RITCHIE HIGHWAY, SUITE A9" t:hosp_name="ALEXANDER ANIMAL HOSPITAL" m:row_number.rq5t-wyh5=1

series e:rq5t-wyh5 d:2017-01-01T00:00:00.000Z t:bus_licno=02-064 t:hosp_owner="REGGIE COX, D.V.M." t:countydesc="ANNE ARUNDEL" t:hosp_city_hosp_st_h="GLEN BURNIE, MD 21061" t:hosp_addr="7387 BALTIMORE ANNAPOLIS BLVD., SUITE D" t:hosp_name="ALPHA VETERINARY CENTER, INC." m:row_number.rq5t-wyh5=2

series e:rq5t-wyh5 d:2017-01-01T00:00:00.000Z t:bus_licno=02-045 t:hosp_owner="GAIL CAMPBELL, D.V.M." t:countydesc="ANNE ARUNDEL" t:hosp_city_hosp_st_h="WEST RIVER, MD 20778" t:hosp_addr="595 OWENSVILLE ROAD" t:hosp_name="AMERIPACA ALPACA BREEDING CO., INC." m:row_number.rq5t-wyh5=3
```

## Meta Commands

```ls
metric m:row_number.rq5t-wyh5 p:long l:"Row Number"

entity e:rq5t-wyh5 l:"Current Licensed Hospitals-2017 11072016" t:url=https://data.maryland.gov/api/views/rq5t-wyh5

property e:rq5t-wyh5 t:meta.view v:id=rq5t-wyh5 v:category=Agriculture v:averageRating=0 v:name="Current Licensed Hospitals-2017 11072016"

property e:rq5t-wyh5 t:meta.view.owner v:id=5i5x-vf5f v:screenName=teachoaa v:displayName=teachoaa

property e:rq5t-wyh5 t:meta.view.tableauthor v:id=5i5x-vf5f v:screenName=teachoaa v:roleName=editor v:displayName=teachoaa
```

## Top Records

```ls
| countydesc   | hosp_name                                     | hosp_owner                                | hosp_addr                               | bus_licno | hosp_city_hosp_st_h    | 
| ============ | ============================================= | ========================================= | ======================================= | ========= | ====================== | 
| ANNE ARUNDEL | ALEXANDER ANIMAL HOSPITAL                     | ERIC ALEXANDER, DVM                       | 160 RITCHIE HIGHWAY, SUITE A9           | 02-080    | SEVERNA PARK, MD 21146 | 
| ANNE ARUNDEL | ALPHA VETERINARY CENTER, INC.                 | REGGIE COX, D.V.M.                        | 7387 BALTIMORE ANNAPOLIS BLVD., SUITE D | 02-064    | GLEN BURNIE, MD 21061  | 
| ANNE ARUNDEL | AMERIPACA ALPACA BREEDING CO., INC.           | GAIL CAMPBELL, D.V.M.                     | 595 OWENSVILLE ROAD                     | 02-045    | WEST RIVER, MD 20778   | 
| ANNE ARUNDEL | ANIMAL BIRTH CONTROL, LLC                     | SUSAN MCDONOUGH, VMD                      | 8424 VETERANS HIGHWAY**                 | 02-071    | MILLERSVILLE, MD 21108 | 
| ANNE ARUNDEL | ANIMAL CLINIC OF WAYSON'S CORNER              | ANITA L. MOORE, D.V.M. & WEBSTER B. ESSEX | 5443 SOUTHERN MARYLAND BLVD.            | 02-060    | LOTHIAN, MD 20711      | 
| ANNE ARUNDEL | ANIMAL DENTAL CENTER, INC.                    | IRA R. LUSKIN, D.V.M.                     | 197 DEFENSE HIGHWAY, SUITE 101          | 02-066    | ANNAPOLIS, MD 21401    | 
| ANNE ARUNDEL | ANIMAL HOSPITAL AT SOUTHGATE                  | AJ VETERINARY PROVIDERS, LLC              | 338 HOSPITAL DRIVE                      | 02-019    | GLEN BURNIE, MD 21061  | 
| ANNE ARUNDEL | ANIMAL WORLD LLC (DBA - GAMBRILLS VET CENTER) | DR. JASON I. ORENSTEIN                    | 1078 MD ROUTE 3 , SOUTH                 | 02-057    | GAMBRILLS, MD 21054    | 
| ANNE ARUNDEL | ANNAPOLIS ANIMAL HOSPITAL                     | JAMES REED                                | 712 MELROSE STREET                      | 02-002    | ANNAPOLIS, MD 21401    | 
| ANNE ARUNDEL | ANNAPOLIS CAT HOSPITAL                        | SUSAN L. LONGO, D.V.M.                    | 2248 BAY RIDGE AVENUE                   | 02-017    | ANNAPOLIS, MD 21403    | 
```