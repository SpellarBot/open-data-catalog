# SY2015-2016 Kindergarten Socrata

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sy2015-2016-kindergarten-socrata) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/4jxc-yk8f) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/4jxc-yk8f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/4jxc-yk8f/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 4jxc-yk8f |
| Name | SY2015-2016 Kindergarten Socrata |
| Created | 2016-04-08T20:27:23Z |
| Publication Date | 2016-04-08T21:10:37Z |

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | school_name                    | School Name                    | text      | text        |
| Yes      | series tag     | school_type                    | School Type                    | text      | text        |
| Yes      | series tag     | county                         | County                         | text      | text        |
| Yes      | series tag     | location                       | Location                       | text      | text        |
| Yes      | series tag     | within_district_boundary       | Within District Boundary       | text      | text        |
| Yes      | series tag     | school_year                    | School Year                    | text      | text        |
| Yes      | series tag     | reported                       | Reported                       | text      | text        |
| Yes      | series tag     | grade_levels                   | Grade Levels                   | text      | text        |
| Yes      | numeric metric | number_enrolled                | Number Enrolled                | number    | number      |
| Yes      | numeric metric | complete                       | COMPLETE                       | percent   | percent     |
| Yes      | numeric metric | conditional                    | CONDITIONAL                    | percent   | percent     |
| Yes      | numeric metric | out_of_compliance              | OUT-OF-COMPLIANCE              | percent   | percent     |
| Yes      | numeric metric | exempt                         | EXEMPT                         | percent   | percent     |
| Yes      | numeric metric | medical_exemption              | Medical Exemption              | percent   | percent     |
| Yes      | numeric metric | personal_exemption             | Personal Exemption             | percent   | percent     |
| Yes      | numeric metric | religious_exemption            | Religious Exemption            | percent   | percent     |
| Yes      | numeric metric | religious_membership_exemption | Religious Membership Exemption | percent   | percent     |
| Yes      | numeric metric | complete_dt                    | Complete DT                    | percent   | percent     |
| Yes      | numeric metric | complete_pertussis             | Complete Pertussis             | percent   | percent     |
| Yes      | numeric metric | complete_mmr                   | Complete MMR                   | percent   | percent     |
| Yes      | numeric metric | complete_polio                 | Complete Polio                 | percent   | percent     |
| Yes      | numeric metric | complete_hep_b                 | Complete Hep B                 | percent   | percent     |
| Yes      | numeric metric | complete_varicella             | Complete Varicella             | percent   | percent     |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4jxc-yk8f d:2015-01-01T00:00:00.000Z t:school_type="PRIVATE SCHOOL" t:reported=Y t:school_name="ACADEMY FOR PRECISION LEARNING" t:county=KING t:location="5031 UNIVERSITY WAY NE, SEATTLE, WA, 98105" t:grade_levels=K-9 t:within_district_boundary="SEATTLE PUBLIC SCHOOLS" t:school_year=2015-16 m:exempt=16.7 m:complete_hep_b=83.3 m:number_enrolled=6 m:medical_exemption=0 m:religious_exemption=0 m:complete_pertussis=83.3 m:complete_mmr=83.3 m:out_of_compliance=0 m:complete_dt=83.3 m:religious_membership_exemption=0 m:complete=83.3 m:complete_polio=83.3 m:complete_varicella=83.3 m:conditional=0 m:personal_exemption=16.7

series e:4jxc-yk8f d:2015-01-01T00:00:00.000Z t:school_type="PRIVATE SCHOOL" t:reported=Y t:school_name="ACADEMY SCHOOLS / CHILDREN?S ACADEMY" t:county=KING t:location="14601 INTERURBAN AVE S, TUKWILA, WA, 98168" t:grade_levels=P-12 t:within_district_boundary="TUKWILA SCHOOL DISTRICT" t:school_year=2015-16 m:exempt=0 m:complete_hep_b=100 m:number_enrolled=6 m:medical_exemption=0 m:religious_exemption=0 m:complete_pertussis=100 m:complete_mmr=100 m:out_of_compliance=0 m:complete_dt=100 m:religious_membership_exemption=0 m:complete=100 m:complete_polio=100 m:complete_varicella=100 m:conditional=0 m:personal_exemption=0

series e:4jxc-yk8f d:2015-01-01T00:00:00.000Z t:school_type="PUBLIC SCHOOL" t:reported=Y t:school_name="ADAMS ELEMENTARY SCHOOL" t:county=KING t:location="6110 28 AVE NW, SEATTLE, WA, 98107" t:grade_levels="K -5" t:within_district_boundary="SEATTLE PUBLIC SCHOOLS" t:school_year=2015-16 m:exempt=1.9 m:complete_hep_b=91.6 m:number_enrolled=107 m:medical_exemption=0.9 m:religious_exemption=0 m:complete_pertussis=89.7 m:complete_mmr=90.7 m:out_of_compliance=19.6 m:complete_dt=89.7 m:religious_membership_exemption=0 m:complete=78.5 m:complete_polio=86.9 m:complete_varicella=89.7 m:conditional=0 m:personal_exemption=1.9
```

## Meta Commands

```ls
metric m:number_enrolled p:integer l:"Number Enrolled" t:dataTypeName=number

metric m:complete p:float l:COMPLETE t:dataTypeName=percent

metric m:conditional p:float l:CONDITIONAL t:dataTypeName=percent

metric m:out_of_compliance p:float l:OUT-OF-COMPLIANCE t:dataTypeName=percent

metric m:exempt p:float l:EXEMPT t:dataTypeName=percent

metric m:medical_exemption p:float l:"Medical Exemption" t:dataTypeName=percent

metric m:personal_exemption p:float l:"Personal Exemption" t:dataTypeName=percent

metric m:religious_exemption p:float l:"Religious Exemption" t:dataTypeName=percent

metric m:religious_membership_exemption p:float l:"Religious Membership Exemption" t:dataTypeName=percent

metric m:complete_dt p:float l:"Complete DT" t:dataTypeName=percent

metric m:complete_pertussis p:float l:"Complete Pertussis" t:dataTypeName=percent

metric m:complete_mmr p:float l:"Complete MMR" t:dataTypeName=percent

metric m:complete_polio p:float l:"Complete Polio" t:dataTypeName=percent

metric m:complete_hep_b p:float l:"Complete Hep B" t:dataTypeName=percent

metric m:complete_varicella p:float l:"Complete Varicella" t:dataTypeName=percent

entity e:4jxc-yk8f l:"SY2015-2016 Kindergarten Socrata" t:url=https://data.kingcounty.gov/api/views/4jxc-yk8f

property e:4jxc-yk8f t:meta.view v:id=4jxc-yk8f v:averageRating=0 v:name="SY2015-2016 Kindergarten Socrata"

property e:4jxc-yk8f t:meta.view.owner v:id=8hu9-dtbz v:screenName="Libby Page" v:displayName="Libby Page"

property e:4jxc-yk8f t:meta.view.tableauthor v:id=8hu9-dtbz v:screenName="Libby Page" v:roleName=publisher v:displayName="Libby Page"
```

## Top Records

```ls
| school_name                          | school_type    | county | location                                   | within_district_boundary        | school_year | reported | grade_levels | number_enrolled | complete | conditional | out_of_compliance | exempt | medical_exemption | personal_exemption | religious_exemption | religious_membership_exemption | complete_dt | complete_pertussis | complete_mmr | complete_polio | complete_hep_b | complete_varicella | 
| ==================================== | ============== | ====== | ========================================== | =============================== | =========== | ======== | ============ | =============== | ======== | =========== | ================= | ====== | ================= | ================== | =================== | ============================== | =========== | ================== | ============ | ============== | ============== | ================== | 
| ACADEMY FOR PRECISION LEARNING       | PRIVATE SCHOOL | KING   | 5031 UNIVERSITY WAY NE, SEATTLE, WA, 98105 | SEATTLE PUBLIC SCHOOLS          | 2015-16     | Y        | K-9          | 6               | 83.3     | 0.0         | 0.0               | 16.7   | 0.0               | 16.7               | 0.0                 | 0.0                            | 83.3        | 83.3               | 83.3         | 83.3           | 83.3           | 83.3               | 
| ACADEMY SCHOOLS / CHILDREN?S ACADEMY | PRIVATE SCHOOL | KING   | 14601 INTERURBAN AVE S, TUKWILA, WA, 98168 | TUKWILA SCHOOL DISTRICT         | 2015-16     | Y        | P-12         | 6               | 100.0    | 0.0         | 0.0               | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 100.0       | 100.0              | 100.0        | 100.0          | 100.0          | 100.0              | 
| ADAMS ELEMENTARY SCHOOL              | PUBLIC SCHOOL  | KING   | 6110 28 AVE NW, SEATTLE, WA, 98107         | SEATTLE PUBLIC SCHOOLS          | 2015-16     | Y        | K -5         | 107             | 78.5     | 0.0         | 19.6              | 1.9    | 0.9               | 1.9                | 0.0                 | 0.0                            | 89.7        | 89.7               | 90.7         | 86.9           | 91.6           | 89.7               | 
| ADELAIDE ELEMENTARY SCHOOL           | PUBLIC SCHOOL  | KING   | 1635 SW 304TH ST, FEDERAL WAY, WA, 98023   | FEDERAL WAY SCHOOL DISTRICT     | 2015-16     | Y        | PK-5         | 59              | 81.4     | 1.7         | 11.9              | 5.1    | 0.0               | 5.1                | 0.0                 | 0.0                            | 88.1        | 88.1               | 89.8         | 89.8           | 93.2           | 84.7               | 
| ALCOTT ELEMENTARY                    | PUBLIC SCHOOL  | KING   | 4213 228TH AVENUE NE, REDMOND, WA, 98053   | LAKE WASHINGTON SCHOOL DISTRICT | 2015-16     | Y        | K -5         | 87              | 89.7     | 2.3         | 5.7               | 2.3    | 0.0               | 2.3                | 0.0                 | 0.0                            | 96.6        | 96.6               | 96.6         | 96.6           | 90.8           | 97.7               | 
| ALCUIN SCHOOL                        | PRIVATE SCHOOL | KING   | 216 W BOSTON, SEATTLE, WA, 98119           | SEATTLE PUBLIC SCHOOLS          | 2015-16     | Y        | P-1          | 1               | 100.0    | 0.0         | 0.0               | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 100.0       | 100.0              | 100.0        | 100.0          | 100.0          | 100.0              | 
| ALKI ELEMENTARY SCHOOL               | PUBLIC SCHOOL  | KING   | 3010 59 AVE SW, SEATTLE, WA, 98116         | SEATTLE PUBLIC SCHOOLS          | 2015-16     | Y        | PK-5         | 50              | 84.0     | 2.0         | 0.0               | 14.0   | 2.0               | 12.0               | 0.0                 | 0.0                            | 98.0        | 98.0               | 96.0         | 96.0           | 88.0           | 92.0               | 
| AMAZING GRACE CHRISTIAN SCHOOL       | PRIVATE SCHOOL | KING   | 10056 RENTON AVE S, SEATTLE, WA, 98178     | SEATTLE PUBLIC SCHOOLS          | 2015-16     | Y        | K-8          | 58              | 87.9     | 0.0         | 12.1              | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 94.8        | 94.8               | 94.8         | 93.1           | 100.0          | 91.4               | 
| AMERICA'S CHILD MONTESSORI           | PRIVATE SCHOOL | KING   | 14340 NE 21ST, BELLEVUE, WA, 98007         | BELLEVUE SCHOOL DISTRICT        | 2015-16     | Y        | P-2          | 12              | 100.0    | 0.0         | 0.0               | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 100.0       | 100.0              | 100.0        | 100.0          | 100.0          | 100.0              | 
| APOLLO ELEMENTARY                    | PUBLIC SCHOOL  | KING   | 15025 SE 117TH ST, RENTON, WA, 98059       | ISSAQUAH SCHOOL DISTRICT        | 2015-16     | Y        | PK-5         | 100             | 86.0     | 0.0         | 3.0               | 11.0   | 2.0               | 9.0                | 0.0                 | 0.0                            | 92.0        | 92.0               | 91.0         | 92.0           | 92.0           | 90.0               | 
```