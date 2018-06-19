# Correctional Institutions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/correctional-institutions-b2417) |
| Metadata | [Link](https://data.oregon.gov/api/views/fqhs-84r4) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/fqhs-84r4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/fqhs-84r4/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | fqhs-84r4 |
| Name | Correctional Institutions |
| Attribution | TechniGraphics, Inc. |
| Category | Government |
| Tags | oregon, corrections, prisons, infrastructure, jails, jail, prison, facilities, detention, federal, state, local, justice, doj |
| Created | 2010-11-12T22:57:32Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

The Jails and Prisons sub-layer is part of the Emergency Law Enforcement Sector and the Critical Infrastructure Category. A Jail or Prison consists of any facility or location where individuals are regularly and lawfully detained against their will. This includes Federal and State prisons, local jails, and juvenile detention facilities, as well as law enforcement temporary holding facilities. Work camps, including camps operated seasonally, are included if they otherwise meet the definition. A Federal Prison is a facility operated by the Federal Bureau of Prisons for the incarceration of individuals. A State Prison is a facility operated by a state, commonwealth, or territory of the US for the incarceration of individuals for a term usually longer than 1 year. A Juvenile Detention Facility is a facility for the incarceration of those who have not yet reached the age of majority (usually 18 years). A Local Jail is a locally administered facility that holds inmates beyond arraignment (usually 72 hours) and is staffed by municipal or county employees. A temporary holding facility, sometimes referred to as a "police lock up" or "drunk tank", is a facility used to detain people prior to arraignment. Locations that are administrative offices only are excluded from the dataset. This definition of Jails is consistent with that used by the Department of Justice (DOJ) in their "National Jail Census", with the exception of "temporary holding facilities", which the DOJ excludes.

Locations which function primarily as law enforcement offices are included in this dataset if they have holding cells.

If the facility is enclosed with a fence, wall, or structure with a gate around the buildings only, the locations were depicted as "on entity" at the center of the facility. If the facility's buildings are not enclosed, the locations were depicted as "on entity" on the main building or "block face" on the correct street segment.

For full metadata record, please refer to the Oregon Geospatial Library: http://gis.oregon.gov/DAS/EISPD/GEO/sdlibrary.shtml

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | NAME       | text      | text        |
| Yes      | series tag  | telephone   | TELEPHONE  | text      | text        |
| No       |             | address     | ADDRESS    | text      | text        |
| No       |             | address2    | ADDRESS2   | text      | text        |
| Yes      | series tag  | city        | CITY       | text      | text        |
| Yes      | series tag  | state       | STATE      | text      | text        |
| Yes      | series tag  | zip         | ZIP        | text      | number      |
| Yes      | series tag  | zipp4       | ZIPP4      | text      | number      |
| Yes      | series tag  | county      | COUNTY     | text      | text        |
| Yes      | series tag  | fips        | FIPS       | text      | number      |
| Yes      | series tag  | directions  | DIRECTIONS | text      | text        |
| Yes      | series tag  | naicsdescr  | NAICSDESCR | text      | text        |
| No       |             | x           | X          | number    | number      |
| No       |             | y           | Y          | number    | number      |
| Yes      | series tag  | factype     | FACTYPE    | text      | text        |
| Yes      | series tag  | agency      | AGENCY     | text      | text        |
| Yes      | series tag  | inmate_men  | INMATE_MEN | checkbox  | checkbox    |
| Yes      | series tag  | inmate_wom  | INMATE_WOM | checkbox  | checkbox    |
| Yes      | series tag  | inmate_juv  | INMATE_JUV | checkbox  | checkbox    |
| Yes      | series tag  | inmate_coe  | INMATE_COE | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address2,x,y
```

## Data Commands

```ls
series e:fqhs-84r4 d:2010-11-12T14:57:34.000Z t:directions="ON THE NORTH SIDE OF MAIN STREET BETWEEN 19TH AVENUE AND 22ND AVENUE" t:zip=97386 t:naicsdescr="POLICE DEPARTMENTS (EXCEPT AMERICAN INDIAN OR ALASKA NATIVE)" t:county=LINN t:name="SWEET HOME POLICE DEPARTMENT" t:state=OR t:zipp4=1711 t:telephone=541-367-5181 t:fips=41043 t:city="SWEET HOME" m:row_number.fqhs-84r4=1

series e:fqhs-84r4 d:2010-11-12T14:57:34.000Z t:zip=97463 t:inmate_wom=true t:naicsdescr="POLICE DEPARTMENTS (EXCEPT AMERICAN INDIAN OR ALASKA NATIVE)" t:inmate_juv=false t:state=OR t:inmate_coe=true t:factype=LOCAL t:city=OAKRIDGE t:directions="E SIDE OF ASH ST BETWEEN E COMMERCIAL ST AND E 1ST ST" t:county=LANE t:name="OAKRIDGE POLICE DEPARTMENT" t:inmate_men=true t:zipp4=9606 t:telephone=541-782-4232 t:fips=41039 m:row_number.fqhs-84r4=2

series e:fqhs-84r4 d:2010-11-12T14:57:34.000Z t:directions="ON THE WEST SIDE OF NW BROADWAY ST BETWEEN NW GLISAN ST AND NW HOYT ST." t:zip=97209 t:naicsdescr="FEDERAL POLICE SERVICES" t:county=MULTNOMAH t:name="UNITED STATES CUSTOMS AND BORDER PROTECTION - PORTLAND DEFERRED INSPECTION SITE" t:state=OR t:zipp4=3411 t:agency=USCBP t:telephone=503-326-3409 t:fips=41051 t:factype="DEFERRED INSPECTION SITES" t:city=PORTLAND m:row_number.fqhs-84r4=3
```

## Meta Commands

```ls
metric m:row_number.fqhs-84r4 p:long l:"Row Number"

entity e:fqhs-84r4 l:"Correctional Institutions" t:attribution="TechniGraphics, Inc." t:url=https://data.oregon.gov/api/views/fqhs-84r4

property e:fqhs-84r4 t:meta.view v:id=fqhs-84r4 v:category=Government v:attributionLink=http://gis.oregon.gov/DAS/EISPD/GEO/sdlibrary.shtml v:averageRating=0 v:name="Correctional Institutions" v:attribution="TechniGraphics, Inc."

property e:fqhs-84r4 t:meta.view.owner v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"

property e:fqhs-84r4 t:meta.view.tableauthor v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"
```

## Top Records

```ls
| :updated_at | name                                                                            | telephone    | address                   | address2                                              | city       | state | zip   | zipp4 | county    | fips  | directions                                                                                 | naicsdescr                                                   | x            | y          | factype                   | agency | inmate_men | inmate_wom | inmate_juv | inmate_coe | 
| =========== | =============================================================================== | ============ | ========================= | ===================================================== | ========== | ===== | ===== | ===== | ========= | ===== | ========================================================================================== | ============================================================ | ============ | ========== | ========================= | ====== | ========== | ========== | ========== | ========== | 
| 1289573854  | SWEET HOME POLICE DEPARTMENT                                                    | 541-367-5181 | 1950 MAIN STREET          |                                                       | SWEET HOME | OR    | 97386 | 1711  | LINN      | 41043 | ON THE NORTH SIDE OF MAIN STREET BETWEEN 19TH AVENUE AND 22ND AVENUE                       | POLICE DEPARTMENTS (EXCEPT AMERICAN INDIAN OR ALASKA NATIVE) | -122.7210418 | 44.40001   |                           |        |            |            |            |            | 
| 1289573854  | OAKRIDGE POLICE DEPARTMENT                                                      | 541-782-4232 | 76435 ASH STREET          |                                                       | OAKRIDGE   | OR    | 97463 | 9606  | LANE      | 41039 | E SIDE OF ASH ST BETWEEN E COMMERCIAL ST AND E 1ST ST                                      | POLICE DEPARTMENTS (EXCEPT AMERICAN INDIAN OR ALASKA NATIVE) | -122.4569066 | 43.7472225 | LOCAL                     |        | true       | true       | false      | true       | 
| 1289573854  | UNITED STATES CUSTOMS AND BORDER PROTECTION - PORTLAND DEFERRED INSPECTION SITE | 503-326-3409 | 511 NORTHWEST BROADWAY    | ROOM 117                                              | PORTLAND   | OR    | 97209 | 3411  | MULTNOMAH | 41051 | ON THE WEST SIDE OF NW BROADWAY ST BETWEEN NW GLISAN ST AND NW HOYT ST.                    | FEDERAL POLICE SERVICES                                      | -122.6779878 | 45.5269982 | DEFERRED INSPECTION SITES | USCBP  |            |            |            |            | 
| 1289573854  | CROOK COUNTY CORRECTIONAL FACILITY                                              | 541-416-3620 | 400 NORTHEAST 3RD STREET  |                                                       | PRINEVILLE | OR    | 97754 | 1921  | CROOK     | 41013 | LOCATED ON SOUTH SIDE OF EAST 3RD STREET BETWEEN NE DUNHAM STREET AND N ELM STREET.        | CORRECTIONAL INSTITUTIONS                                    | -120.8428523 | 44.3026352 |                           |        |            |            |            |            | 
| 1289573854  | NORTHERN OREGON REGIONAL CORRECTIONAL FACILITY ADULT                            | 541-298-1576 | 201 WEBBER STREET         |                                                       | THE DALLES | OR    | 97058 | 3507  | WASCO     | 41065 | LOC ON THE NORTHWEST SIDE OF WEBER ST, BETWEEN W 2ND ST AND W 1ST ST.                      | CORRECTIONAL INSTITUTIONS                                    | -121.2013205 | 45.6119336 |                           |        |            |            |            |            | 
| 1289573854  | LANE COUNTY SHERIFFS OFFICE                                                     | 541-682-6790 | 125 EAST 8TH AVENUE       |                                                       | EUGENE     | OR    | 97401 | 2922  | LANE      | 41039 | LOC ON THE NORTH SIDE OF E 8TH AVE, BETWEEN OAK ST AND PEARL ST ACROSS FROM E PARK STREET. | SHERIFFS' OFFICES (EXCEPT COURT FUNCTIONS ONLY)              | -123.0904601 | 44.0512897 |                           |        |            |            |            |            | 
| 1289573854  | TROUTDALE POLICE DEPARTMENT                                                     | 503-665-6129 | 141 SOUTHEAST DORA STREET |                                                       | TROUTDALE  | OR    | 97060 | 2058  | MULTNOMAH | 41051 | W SIDE OF SE DORA ST BETWEEN SE 2ND ST AND E COLUMBIA RIVER HWY                            | POLICE DEPARTMENTS (EXCEPT AMERICAN INDIAN OR ALASKA NATIVE) | -122.3877252 | 45.5403154 | LOCAL                     |        | true       | true       | false      | true       | 
| 1289573854  | SEASIDE POLICE DEPARTMENT                                                       | 503-738-6311 | 1091 SOUTH HOLLIDAY DRIVE |                                                       | SEASIDE    | OR    | 97138 | 6612  | CLATSOP   | 41007 | LOCATED ON S HOLLIDAY DR E SIDE BETWEEN AVE J AND AVE K.                                   | POLICE DEPARTMENTS (EXCEPT AMERICAN INDIAN OR ALASKA NATIVE) | -123.9232823 | 45.987217  | LOCAL                     |        | true       | true       | false      | true       | 
| 1289573854  | CONDON POLICE DEPARTMENT                                                        | 541-384-6111 | 128 SOUTH MAIN STREET     |                                                       | CONDON     | OR    | 97823 |       | GILLIAM   | 41021 | EAST SIDE OF S MAIN ST, BETWEEN OR-19 AND E GILLIAM ST.                                    | POLICE DEPARTMENTS (EXCEPT AMERICAN INDIAN OR ALASKA NATIVE) | -120.1844214 | 45.2366583 |                           |        |            |            |            |            | 
| 1289573854  | UNITED STATES MARSHALS SERVICE - EUGENE                                         | 541-465-6701 | 405 EAST 8TH AVENUE       | WAYNE LYMAN MORSE UNITED STATES COURTHOUSE SUITE 1200 | EUGENE     | OR    | 97401 | 3301  | LANE      | 41039 | LOC ON THE NORTH SIDE OF E 8TH AVE, BETWEEN FERRY ST AND MILL ST.                          | MARSHALS' OFFICES                                            | -123.0862458 | 44.0512897 |                           |        |            |            |            |            | 
```