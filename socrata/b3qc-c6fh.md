# Directory Of Lead Agencies And Housing Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-lead-agencies-and-housing-programs-1181b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/b3qc-c6fh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/b3qc-c6fh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/b3qc-c6fh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | b3qc-c6fh |
| Name | Directory Of Lead Agencies And Housing Programs |
| Attribution | Department of City Planning (DCP) |
| Category | Public Safety |
| Tags | dcp, city, planning, lead, base, paint, contact, housing, programs |
| Created | 2013-02-13T20:41:38Z |
| Publication Date | 2013-02-13T20:43:59Z |

## Description

Details about the Housing Programs and the corresponding Lead Agency Contact Details

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | housing_programs | HOUSING PROGRAMS | text      | text        |
| Yes      | series tag  | lead_agencies    | LEAD AGENCIES    | text      | text        |
| Yes      | series tag  | contact_person   | CONTACT PERSON   | text      | text        |
| Yes      | series tag  | telephone_number | TELEPHONE NUMBER | text      | text        |
| Yes      | series tag  | fax_number       | FAX NUMBER       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:b3qc-c6fh d:2013-02-13T12:41:40.000Z t:fax_number=347-396-7559 t:housing_programs=HOPWA t:telephone_number=347-396-7428 t:lead_agencies=DOHMH t:contact_person="John Rojas" m:row_number.b3qc-c6fh=1

series e:b3qc-c6fh d:2013-02-13T12:41:40.000Z t:fax_number=212-232-0559 t:housing_programs="HUD CONTINUUM OF CARE HOMELESS ASSISTANCE PROGRAMS, Supportive Housing Program (SHP), Shelter Plus Care (S+C) and Section 8 Moderate Rehabilitation Single, Room Occupancy (SRO)" t:telephone_number=212-361-7957 t:lead_agencies=DHS t:contact_person="Eileen Lynch" m:row_number.b3qc-c6fh=2

series e:b3qc-c6fh d:2013-02-13T12:41:40.000Z t:fax_number=212-442-1206 t:housing_programs="SECTION 202 SUPPORTIVE HOUSING AND ASSISTED LIVING CENTERS" t:telephone_number=212-442-0917 t:lead_agencies=DFTA t:contact_person="Karen Taylor" m:row_number.b3qc-c6fh=3
```

## Meta Commands

```ls
metric m:row_number.b3qc-c6fh p:long l:"Row Number"

entity e:b3qc-c6fh l:"Directory Of Lead Agencies And Housing Programs" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/b3qc-c6fh

property e:b3qc-c6fh t:meta.view v:id=b3qc-c6fh v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/pub/conplan12_amended_vol2.pdf v:averageRating=0 v:name="Directory Of Lead Agencies And Housing Programs" v:attribution="Department of City Planning (DCP)"

property e:b3qc-c6fh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:b3qc-c6fh t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | housing_programs                                                                                                                                                                 | lead_agencies | contact_person     | telephone_number | fax_number   | 
| =========== | ================================================================================================================================================================================ | ============= | ================== | ================ | ============ | 
| 1360759300  | HOPWA                                                                                                                                                                            | DOHMH         | John Rojas         | 347-396-7428     | 347-396-7559 | 
| 1360759300  | HUD CONTINUUM OF CARE HOMELESS ASSISTANCE PROGRAMS, Supportive Housing Program (SHP), Shelter Plus Care (S+C) and Section 8 Moderate Rehabilitation Single, Room Occupancy (SRO) | DHS           | Eileen Lynch       | 212-361-7957     | 212-232-0559 | 
| 1360759300  | SECTION 202 SUPPORTIVE HOUSING AND ASSISTED LIVING CENTERS                                                                                                                       | DFTA          | Karen Taylor       | 212-442-0917     | 212-442-1206 | 
| 1360759300  | SECTION 811 SUPPORTIVE HOUSING                                                                                                                                                   | MOPD          | Jason Mischel      | 212-788-2830     | 212-341-9843 | 
| 1360759300  | FAIR HOUSING INITIATIVE PROGRAM                                                                                                                                                  | DCP           | Charles Sorrentino | 212-720-3337     | 212-720-3495 | 
| 1360759300  | HOUSING COUNSELING PROGRAMS                                                                                                                                                      | DCP           | Charles Sorrentino | 212-720-3337     | 212-720-3495 | 
| 1360759300  | UNIVERSITY AND COLLEGE PROGRAMS                                                                                                                                                  | DCP           | Charles Sorrentino | 212-720-3337     | 212-720-3495 | 
| 1360759300  | YOUTHBUILD(U.S. Dept. of Labor Grant)                                                                                                                                            | DCP           | Charles Sorrentino | 212-720-3337     | 212-720-3495 | 
| 1360759300  | HOPE VI PUBLIC HOUSING REVITALIZATION                                                                                                                                            | DCP           | Charles Sorrentino | 212-720-3337     | 212-720-3495 | 
| 1360759300  | SECTION 213(A) REVIEW                                                                                                                                                            | DCP           | Charles Sorrentino | 212-720-3337     | 212-720-3495 | 
```