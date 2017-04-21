# SY2015-2016 6th Grade Socrata

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sy2015-2016-6th-grade-socrata) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ffnn-5e2s) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ffnn-5e2s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ffnn-5e2s/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ffnn-5e2s |
| Name | SY2015-2016 6th Grade Socrata |
| Attribution | Washington State Dept of Health |
| Category | Health |
| Created | 2016-04-08T19:38:03Z |
| Publication Date | 2016-04-08T20:02:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | school_name                    | School Name                    | text      | text        |
| Yes      | series tag     | school_type                    | School Type                    | text      | text        |
| Yes      | series tag     | school_year                    | School Year                    | text      | text        |
| Yes      | series tag     | reported                       | Reported                       | text      | text        |
| Yes      | series tag     | within_district_boundary       | Within District Boundary       | text      | text        |
| Yes      | series tag     | grade_level                    | Grade Level                    | text      | text        |
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
series e:ffnn-5e2s d:2015-01-01T00:00:00.000Z t:school_type="PRIVATE SCHOOL" t:reported=Y t:school_name="ACADEMY FOR PRECISION LEARNING" t:within_district_boundary="SEATTLE PUBLIC SCHOOLS" t:school_year=2015-16 t:grade_level=K-9 m:exempt=14.3 m:complete_hep_b=100 m:medical_exemption=14.3 m:number_enrolled=7 m:religious_exemption=0 m:complete_pertussis=100 m:complete_mmr=85.7 m:out_of_compliance=0 m:complete_dt=100 m:religious_membership_exemption=0 m:complete=85.7 m:complete_polio=100 m:complete_varicella=85.7 m:conditional=0 m:personal_exemption=0

series e:ffnn-5e2s d:2015-01-01T00:00:00.000Z t:school_type="PRIVATE SCHOOL" t:reported=Y t:school_name="ACADEMY SCHOOLS / CHILDREN?S ACADEMY" t:within_district_boundary="TUKWILA SCHOOL DISTRICT" t:school_year=2015-16 t:grade_level=P-12 m:exempt=0 m:complete_hep_b=100 m:medical_exemption=0 m:number_enrolled=4 m:religious_exemption=0 m:complete_pertussis=100 m:complete_mmr=100 m:out_of_compliance=0 m:complete_dt=100 m:religious_membership_exemption=0 m:complete=100 m:complete_polio=100 m:complete_varicella=100 m:conditional=0 m:personal_exemption=0

series e:ffnn-5e2s d:2015-01-01T00:00:00.000Z t:school_type="PUBLIC SCHOOL" t:reported=Y t:school_name="AKI KUROSE MIDDLE SCHOOL" t:within_district_boundary="SEATTLE PUBLIC SCHOOLS" t:school_year=2015-16 t:grade_level=6-8 m:exempt=4.2 m:complete_hep_b=97 m:medical_exemption=4.6 m:number_enrolled=263 m:religious_exemption=0 m:complete_pertussis=73 m:complete_mmr=97.7 m:out_of_compliance=28.1 m:complete_dt=73 m:religious_membership_exemption=0.4 m:complete=67.7 m:complete_polio=96.6 m:complete_varicella=92.8 m:conditional=0 m:personal_exemption=0.8
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

entity e:ffnn-5e2s l:"SY2015-2016 6th Grade Socrata" t:attribution="Washington State Dept of Health" t:url=https://data.kingcounty.gov/api/views/ffnn-5e2s

property e:ffnn-5e2s t:meta.view v:id=ffnn-5e2s v:category=Health v:averageRating=0 v:name="SY2015-2016 6th Grade Socrata" v:attribution="Washington State Dept of Health"

property e:ffnn-5e2s t:meta.view.owner v:id=8hu9-dtbz v:screenName="Libby Page" v:displayName="Libby Page"

property e:ffnn-5e2s t:meta.view.tableauthor v:id=8hu9-dtbz v:screenName="Libby Page" v:roleName=publisher v:displayName="Libby Page"
```

## Top Records

```ls
| school_name                            | school_type    | school_year | reported | within_district_boundary   | grade_level | number_enrolled | complete | conditional | out_of_compliance | exempt | medical_exemption | personal_exemption | religious_exemption | religious_membership_exemption | complete_dt | complete_pertussis | complete_mmr | complete_polio | complete_hep_b | complete_varicella | 
| ====================================== | ============== | =========== | ======== | ========================== | =========== | =============== | ======== | =========== | ================= | ====== | ================= | ================== | =================== | ============================== | =========== | ================== | ============ | ============== | ============== | ================== | 
| ACADEMY FOR PRECISION LEARNING         | PRIVATE SCHOOL | 2015-16     | Y        | SEATTLE PUBLIC SCHOOLS     | K-9         | 7               | 85.7     | 0.0         | 0.0               | 14.3   | 14.3              | 0.0                | 0.0                 | 0.0                            | 100.0       | 100.0              | 85.7         | 100.0          | 100.0          | 85.7               | 
| ACADEMY SCHOOLS / CHILDREN?S ACADEMY   | PRIVATE SCHOOL | 2015-16     | Y        | TUKWILA SCHOOL DISTRICT    | P-12        | 4               | 100.0    | 0.0         | 0.0               | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 100.0       | 100.0              | 100.0        | 100.0          | 100.0          | 100.0              | 
| AKI KUROSE MIDDLE SCHOOL               | PUBLIC SCHOOL  | 2015-16     | Y        | SEATTLE PUBLIC SCHOOLS     | 6-8         | 263             | 67.7     | 0.0         | 28.1              | 4.2    | 4.6               | 0.8                | 0.0                 | 0.4                            | 73.0        | 73.0               | 97.7         | 96.6           | 97.0           | 92.8               | 
| AMAZING GRACE CHRISTIAN SCHOOL         | PRIVATE SCHOOL | 2015-16     | Y        | SEATTLE PUBLIC SCHOOLS     | K-8         | 0               | 0.0      | 0.0         | 0.0               | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 0.0         | 0.0                | 0.0          | 0.0            | 0.0            | 0.0                | 
| APP AT LINCOLN                         | PUBLIC SCHOOL  | 2015-16     | Y        | SEATTLE PUBLIC SCHOOLS     | 1-5         | 0               | 0.0      | 0.0         | 0.0               | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 0.0         | 0.0                | 0.0          | 0.0            | 0.0            | 0.0                | 
| APPLIED SCHOLASTICS ACADEMY OF SEATTLE | PRIVATE SCHOOL | 2015-16     | Y        | SEATTLE PUBLIC SCHOOLS     | K-6         | 1               | 100.0    | 0.0         | 0.0               | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 100.0       | 100.0              | 100.0        | 100.0          | 100.0          | 100.0              | 
| ARBOR SCHOOLS                          | PRIVATE SCHOOL | 2015-16     | Y        | ISSAQUAH SCHOOL DISTRICT   | P-9         | 2               | 50.0     | 0.0         | 0.0               | 50.0   | 0.0               | 50.0               | 0.0                 | 0.0                            | 50.0        | 50.0               | 50.0         | 50.0           | 50.0           | 50.0               | 
| ARROWHEAD ELEMENTARY                   | PUBLIC SCHOOL  | 2015-16     | Y        | NORTHSHORE SCHOOL DISTRICT | K -6        | 60              | 86.7     | 0.0         | 6.7               | 6.7    | 0.0               | 6.7                | 0.0                 | 0.0                            | 91.7        | 91.7               | 93.3         | 93.3           | 95.0           | 91.7               | 
| ASSUMPTION ST. BRIDGET                 | PRIVATE SCHOOL | 2015-16     | Y        | SEATTLE PUBLIC SCHOOLS     | K-8         | 57              | 96.5     | 0.0         | 3.5               | 0.0    | 0.0               | 0.0                | 0.0                 | 0.0                            | 96.5        | 96.5               | 98.2         | 98.2           | 98.2           | 98.2               | 
| BEAR CREEK ELEMENTARY                  | PUBLIC SCHOOL  | 2015-16     | Y        | NORTHSHORE SCHOOL DISTRICT | K -6        | 74              | 91.9     | 0.0         | 0.0               | 8.1    | 1.4               | 6.8                | 0.0                 | 0.0                            | 95.9        | 95.9               | 98.6         | 95.9           | 95.9           | 94.6               | 
```