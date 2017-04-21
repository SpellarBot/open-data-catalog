# City University of New York (CUNY) University Campus Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-university-of-new-york-cuny-university-campus-locations) |
| Metadata | [Link](https://data.ny.gov/api/views/irqs-74ez) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/irqs-74ez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/irqs-74ez/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | irqs-74ez |
| Name | City University of New York (CUNY) University Campus Locations |
| Attribution | City University of New York |
| Category | Education |
| Tags | higher education, university, new york city |
| Created | 2014-01-17T16:21:38Z |
| Publication Date | 2014-01-17T16:27:26Z |

## Description

Geographic locations of all CUNY institutions with contact information

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | college_or_institution_type | College or Institution Type | text      | text        |
| Yes      | series tag  | campus                      | Campus                      | text      | text        |
| Yes      | series tag  | campus_website              | Campus Website              | url       | url         |
| No       |             | address                     | Address                     | text      | text        |
| Yes      | series tag  | city                        | City                        | text      | text        |
| Yes      | series tag  | state                       | State                       | text      | text        |
| Yes      | series tag  | zip                         | Zip                         | text      | text        |
| No       |             | lat                         | Latitude                    | number    | number      |
| No       |             | long                        | Longitude                   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,lat,long
```

## Data Commands

```ls
series e:irqs-74ez d:2014-01-17T08:26:12.000Z t:zip=10010-2313 t:state=NY t:campus_website=http://baruch.cuny.edu t:college_or_institution_type="Senior Colleges" t:city="New York" t:campus="Baruch College" m:row_number.irqs-74ez=1

series e:irqs-74ez d:2014-01-17T08:26:12.000Z t:zip=11210-2850 t:state=NY t:campus_website=http://brooklyn.edu t:college_or_institution_type="Senior Colleges" t:city=Brooklyn t:campus="Brooklyn College" m:row_number.irqs-74ez=2

series e:irqs-74ez d:2014-01-17T08:26:12.000Z t:zip=10007-1044 t:state=NY t:campus_website=http://bmcc.cuny.edu t:college_or_institution_type="Community Colleges" t:city="New York" t:campus="Borough of Manhattan Community College" m:row_number.irqs-74ez=3
```

## Meta Commands

```ls
metric m:row_number.irqs-74ez p:long l:"Row Number"

entity e:irqs-74ez l:"City University of New York (CUNY) University Campus Locations" t:attribution="City University of New York" t:url=https://data.ny.gov/api/views/irqs-74ez

property e:irqs-74ez t:meta.view v:id=irqs-74ez v:category=Education v:averageRating=0 v:name="City University of New York (CUNY) University Campus Locations" v:attribution="City University of New York"

property e:irqs-74ez t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:irqs-74ez t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:irqs-74ez t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | college_or_institution_type | campus                                    | campus_website                 | address                | city             | state | zip        | lat       | long       | 
| =========== | =========================== | ========================================= | ============================== | ====================== | ================ | ===== | ========== | ========= | ========== | 
| 1389947172  | Senior Colleges             | Baruch College                            | [http://baruch.cuny.edu, null] | 151 East 25th Street   | New York         | NY    | 10010-2313 | 40.740977 | -73.984252 | 
| 1389947172  | Senior Colleges             | Brooklyn College                          | [http://brooklyn.edu, null]    | 2900 Bedford Avenue    | Brooklyn         | NY    | 11210-2850 | 40.630276 | -73.955545 | 
| 1389947172  | Community Colleges          | Borough of Manhattan Community College    | [http://bmcc.cuny.edu, null]   | 199 Chambers Street    | New York         | NY    | 10007-1044 | 40.717367 | -74.012178 | 
| 1389947172  | Community Colleges          | Bronx Community College                   | [http://bcc.cuny.edu, null]    | 2155 University Avenue | Bronx            | NY    | 10453      | 40.856673 | -73.910127 | 
| 1389947172  | Senior Colleges             | The City College of New York              | [http://ccny.cuny.edu, null]   | 160 Convent Avenue     | New York         | NY    | 10031-9101 | 40.819548 | -73.949518 | 
| 1389947172  | Graduate Colleges           | CUNY School of Law                        | [http://law.cuny.edu, null]    | 2 Court Square         | Long Island City | NY    | 11101-4356 | 40.747639 | -73.943676 | 
| 1389947172  | Graduate Colleges           | The Graduate School and University Center | [http://gc.cuny.edu, null]     | 365 5th Avenue         | New York         | NY    | 10016-4309 | 40.748724 | -73.984205 | 
| 1389947172  | Senior Colleges             | Hunter College                            | [http://hunter.cuny.edu, null] | 695 Park Avenue        | New York         | NY    | 10065-5024 | 40.768731 | -73.964915 | 
| 1389947172  | Community Colleges          | Hostos Community College                  | [http://hostos.cuny.edu, null] | 500 Grand Concourse    | Bronx            | NY    | 10451-5323 | 40.817828 | -73.926862 | 
| 1389947172  | Senior Colleges             | John Jay College of Criminal Justice      | [http://jjay.cuny.edu, null]   | 445 West 59th Street   | New York         | NY    | 10019-1104 | 40.769939 | -73.986469 | 
```