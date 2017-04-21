# Public Health Services- Chicago Primary Care Community Health Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-services-chicago-primary-care-community-health-centers-573f3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cjg8-dbka) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cjg8-dbka/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cjg8-dbka/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cjg8-dbka |
| Name | Public Health Services- Chicago Primary Care Community Health Centers |
| Category | Health & Human Services |
| Tags | health, services, clinics, care, primary, fqhc, community |
| Created | 2014-04-14T15:09:08Z |
| Publication Date | 2014-07-08T02:33:38Z |

## Description

Locations and contact information for Chicago primary care community health clinics (including all federally qualified health centers and similar community health centers that provide primary care and are open to the general community).  Additional information can be found at: http://j.mp/QfZ7SP

CDPH anticipates that this list will be used in the following ways: 1) by residents who are in need of 
assistance in finding a primary care physician and clinic near their homes; 2) by social service and 
public sector service providers that want to link their consumers to primary care near their homes; 3) 
by health system and public health researchers who are interested in Chicago?s primary care and 
safety net provider landscape. 
 
Clinics were excluded from this list if a) it is not specifically in their mission to care for underserved 
populations or b) if clinic services are only available to a narrowly defined population. 
 
Disclaimers: This list is intended to be a working document of primary care clinics for underserved 
populations in Chicago. If you believe an entry on this list to be outdated, misrepresented, or 
otherwise in error, please contact healthychicago@cityofchicago.org.

## Columns

```ls
| Included | Schema Type | Field Name                               | Name                                        | Data Type | Render Type |
| ======== | =========== | ======================================== | =========================================== | ========= | =========== |
| No       | time        | :updated_at                              | updated_at                                  | meta_data | meta_data   |
| Yes      | series tag  | facility                                 | Facility                                    | text      | text        |
| Yes      | series tag  | community_area                           | Community Area (#)                          | text      | text        |
| Yes      | series tag  | phone                                    | Phone                                       | text      | text        |
| Yes      | series tag  | fqhc_look_alike_or_neither_special_notes | FQHC, Look-alike, or Neither; Special Notes | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cjg8-dbka d:2014-04-22T13:30:12.000Z t:phone="(773) 268-7600" t:facility="Near North - Komed Holman Health Center" t:fqhc_look_alike_or_neither_special_notes=FQHC t:community_area="OAKLAND (36)" m:row_number.cjg8-dbka=1

series e:cjg8-dbka d:2014-04-22T13:30:12.000Z t:phone="(866) 882-2237" t:facility="ACCESS at the Illinois Eye Institute" t:fqhc_look_alike_or_neither_special_notes=FQHC t:community_area="DOUGLAS (35)" m:row_number.cjg8-dbka=2

series e:cjg8-dbka d:2014-04-22T13:30:12.000Z t:phone="(866) 882-2237" t:facility="ACCESS Doctors Medical Center" t:fqhc_look_alike_or_neither_special_notes=FQHC t:community_area="GARFIELD RIDGE (56)" m:row_number.cjg8-dbka=3
```

## Meta Commands

```ls
metric m:row_number.cjg8-dbka p:long l:"Row Number"

entity e:cjg8-dbka l:"Public Health Services- Chicago Primary Care Community Health Centers" t:url=https://data.cityofchicago.org/api/views/cjg8-dbka

property e:cjg8-dbka t:meta.view v:id=cjg8-dbka v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Services- Chicago Primary Care Community Health Centers"

property e:cjg8-dbka t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:cjg8-dbka t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| :updated_at | facility                                         | community_area          | phone          | fqhc_look_alike_or_neither_special_notes             | 
| =========== | ================================================ | ======================= | ============== | ==================================================== | 
| 1398173412  | Near North - Komed Holman Health Center          | OAKLAND (36)            | (773) 268-7600 | FQHC                                                 | 
| 1398173412  | ACCESS at the Illinois Eye Institute             | DOUGLAS (35)            | (866) 882-2237 | FQHC                                                 | 
| 1398173412  | ACCESS Doctors Medical Center                    | GARFIELD RIDGE (56)     | (866) 882-2237 | FQHC                                                 | 
| 1398173412  | Esperanza Health Center - Marquette              | CHICAGO LAWN (66)       | (773) 584-6200 | FQHC; School-based health center (open to community) | 
| 1398173412  | Lawndale Christian Health Center - Archer        | ARCHER HEIGHTS (57)     | (773) 843-3000 | FQHC                                                 | 
| 1398173412  | PrimeCare Portage Park                           | PORTAGE PARK (15)       | (773) 736-1830 | FQHC                                                 | 
| 1398173412  | Erie Family Health Center - - Johnson School     | NORTH LAWNDALE (29)     | (312) 666-3494 | FQHC; School-based health center (open to community) | 
| 1398173412  | ACCESS Madison Family Health Center              | WEST GARFIELD PARK (26) | (866) 882-2237 | FQHC                                                 | 
| 1398173412  | PrimeCare Ames                                   | LOGAN SQUARE (22)       | (773) 772-7202 | FQHC; School-based health center (open to community) | 
| 1398173413  | ACCESS Evanston-Rogers Park Family Health Center | ROGERS PARK (1)         | (866) 882-2237 | FQHC                                                 | 
```