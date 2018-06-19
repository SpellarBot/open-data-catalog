# Exemption test data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/exemption-test-data) |
| Metadata | [Link](https://data.oregon.gov/api/views/r99i-rada) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/r99i-rada/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/r99i-rada/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | r99i-rada |
| Name | Exemption test data |
| Created | 2016-02-24T18:15:15Z |
| Publication Date | 2016-02-24T18:19:12Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                     | Data Type | Render Type |
| ======== | ============== | ===================== | ======================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | county                | County                   | text      | text        |
| Yes      | series tag     | sitename              | SiteName                 | text      | text        |
| Yes      | series tag     | grade                 | Grade                    | text      | text        |
| Yes      | numeric metric | vaccinated_dtap       | % Vaccinated:DTaP        | percent   | percent     |
| Yes      | numeric metric | exemption_dtap        | % Exemption:DTaP         | percent   | percent     |
| Yes      | numeric metric | vaccinated_polio      | % Vaccinated:Polio       | percent   | percent     |
| Yes      | numeric metric | exemption_polio       | % Exemption:Polio        | percent   | percent     |
| Yes      | numeric metric | vaccinated_varicella  | % Vaccinated:Varicella   | percent   | percent     |
| Yes      | numeric metric | exemption_varicella   | % Exemption:Varicella    | percent   | percent     |
| Yes      | numeric metric | vaccinated_measles    | % Vaccinated:Measles     | percent   | percent     |
| Yes      | numeric metric | exemption_measles     | % Exemption:Measles      | percent   | percent     |
| Yes      | numeric metric | vaccinated_mumps      | % Vaccinated:Mumps       | percent   | percent     |
| Yes      | numeric metric | exemption_mumps       | % Exemption:Mumps        | percent   | percent     |
| Yes      | numeric metric | vaccinated_rubella    | % Vaccinated:Rubella     | percent   | percent     |
| Yes      | numeric metric | exemption_rubella     | % Exemption:Rubella      | percent   | percent     |
| Yes      | numeric metric | vaccinated_hepb       | % Vaccinated:HepB        | percent   | percent     |
| Yes      | numeric metric | exemption_hepb        | % Exemption:HepB         | percent   | percent     |
| Yes      | numeric metric | vaccinated_hepa       | % Vaccinated:HepA        | percent   | percent     |
| Yes      | numeric metric | exemption_hepa        | % Exemption:HepA         | percent   | percent     |
| Yes      | numeric metric | vaccinated_hib        | % Vaccinated:Hib         | percent   | percent     |
| Yes      | numeric metric | exemption_hib         | % Exemption:Hib          | percent   | percent     |
| Yes      | numeric metric | no_record             | % No Record              | percent   | percent     |
| Yes      | numeric metric | incomplete1_vaccines  | % Incomplete1+ Vaccines  | percent   | percent     |
| Yes      | numeric metric | w_1_medical_exemption | % w/ 1+Medical Exemption | percent   | percent     |
| Yes      | numeric metric | documentationrequired | # DocumentationRequired  | number    | number      |
| Yes      | numeric metric | notcounted            | NotCounted               | number    | number      |
| Yes      | numeric metric | children_18_months    | Children<18 Months       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:r99i-rada d:2016-02-24T10:15:32.000Z t:sitename="BAKER EARLY COLLEGE" t:county="Baker CHD" t:grade="FULL SCHOOL GRADES K-12" m:notcounted=0 m:documentationrequired=0 m:children_18_months=0

series e:r99i-rada d:2016-02-24T10:15:32.000Z t:sitename="BAKER WEB ACADEMY" t:county="Baker CHD" t:grade="FULL SCHOOL GRADES K-12" m:notcounted=0 m:documentationrequired=0 m:children_18_months=0

series e:r99i-rada d:2016-02-24T10:15:32.000Z t:sitename="BROOKLYN ELEMENTARY SCHOOL" t:county="Baker CHD" t:grade="FULL SCHOOL GRADES K-12" m:notcounted=0 m:documentationrequired=0 m:children_18_months=0
```

## Meta Commands

```ls
metric m:vaccinated_dtap p:integer l:"% Vaccinated:DTaP" t:dataTypeName=percent

metric m:exemption_dtap p:integer l:"% Exemption:DTaP" t:dataTypeName=percent

metric m:vaccinated_polio p:integer l:"% Vaccinated:Polio" t:dataTypeName=percent

metric m:exemption_polio p:integer l:"% Exemption:Polio" t:dataTypeName=percent

metric m:vaccinated_varicella p:integer l:"% Vaccinated:Varicella" t:dataTypeName=percent

metric m:exemption_varicella p:integer l:"% Exemption:Varicella" t:dataTypeName=percent

metric m:vaccinated_measles p:integer l:"% Vaccinated:Measles" t:dataTypeName=percent

metric m:exemption_measles p:integer l:"% Exemption:Measles" t:dataTypeName=percent

metric m:vaccinated_mumps p:integer l:"% Vaccinated:Mumps" t:dataTypeName=percent

metric m:exemption_mumps p:integer l:"% Exemption:Mumps" t:dataTypeName=percent

metric m:vaccinated_rubella p:integer l:"% Vaccinated:Rubella" t:dataTypeName=percent

metric m:exemption_rubella p:integer l:"% Exemption:Rubella" t:dataTypeName=percent

metric m:vaccinated_hepb p:integer l:"% Vaccinated:HepB" t:dataTypeName=percent

metric m:exemption_hepb p:integer l:"% Exemption:HepB" t:dataTypeName=percent

metric m:vaccinated_hepa p:integer l:"% Vaccinated:HepA" t:dataTypeName=percent

metric m:exemption_hepa p:integer l:"% Exemption:HepA" t:dataTypeName=percent

metric m:vaccinated_hib p:integer l:"% Vaccinated:Hib" t:dataTypeName=percent

metric m:exemption_hib p:integer l:"% Exemption:Hib" t:dataTypeName=percent

metric m:no_record p:integer l:"% No Record" t:dataTypeName=percent

metric m:incomplete1_vaccines p:integer l:"% Incomplete1+ Vaccines" t:dataTypeName=percent

metric m:w_1_medical_exemption p:integer l:"% w/ 1+Medical Exemption" t:dataTypeName=percent

metric m:documentationrequired p:integer l:"# DocumentationRequired" t:dataTypeName=number

metric m:notcounted p:integer l:NotCounted t:dataTypeName=number

metric m:children_18_months p:integer l:"Children<18 Months" t:dataTypeName=number

entity e:r99i-rada l:"Exemption test data" t:url=https://data.oregon.gov/api/views/r99i-rada

property e:r99i-rada t:meta.view v:id=r99i-rada v:averageRating=0 v:name="Exemption test data"

property e:r99i-rada t:meta.view.owner v:id=zk7t-qvwu v:screenName="Scott Jeffries" v:displayName="Scott Jeffries"

property e:r99i-rada t:meta.view.tableauthor v:id=zk7t-qvwu v:screenName="Scott Jeffries" v:roleName=editor v:displayName="Scott Jeffries"
```

## Top Records

```ls
| :updated_at | county    | sitename                                   | grade                               | vaccinated_dtap | exemption_dtap | vaccinated_polio | exemption_polio | vaccinated_varicella | exemption_varicella | vaccinated_measles | exemption_measles | vaccinated_mumps | exemption_mumps | vaccinated_rubella | exemption_rubella | vaccinated_hepb | exemption_hepb | vaccinated_hepa | exemption_hepa | vaccinated_hib | exemption_hib | no_record | incomplete1_vaccines | w_1_medical_exemption | documentationrequired | notcounted | children_18_months | 
| =========== | ========= | ========================================== | =================================== | =============== | ============== | ================ | =============== | ==================== | =================== | ================== | ================= | ================ | =============== | ================== | ================= | =============== | ============== | =============== | ============== | ============== | ============= | ========= | ==================== | ===================== | ===================== | ========== | ================== | 
| 1456308932  | Baker CHD | BAKER EARLY COLLEGE                        | FULL SCHOOL GRADES K-12             |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 0                     | 0          | 0                  | 
| 1456308932  | Baker CHD | BAKER WEB ACADEMY                          | FULL SCHOOL GRADES K-12             |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 0                     | 0          | 0                  | 
| 1456308932  | Baker CHD | BROOKLYN ELEMENTARY SCHOOL                 | FULL SCHOOL GRADES K-12             |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 0                     | 0          | 0                  | 
| 1456308932  | Baker CHD | BURNT RIVER SCHOOL DISTRICT                | FULL SCHOOL GRADES K-12             | 93              | 7              | 97               | 3               | 97                   | 7                   | 97                 | 3                 | 97               | 3               | 97                 | 3                 | 97              | 3              | 100             | 0              | 0              | 0             | 0         | 7                    | 0                     | 30                    | 4          | 0                  | 
| 1456308932  | Baker CHD | ELKHORN ADOLESCENT TREATMENT CENTER SCHOOL | FULL SCHOOL GRADES K-12             |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 0                     | 0          | 0                  | 
| 1456308932  | Baker CHD | HAINES ELEMENTARY SCHOOL                   | FULL SCHOOL GRADES K-12             |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 0                     | 0          | 0                  | 
| 1456308932  | Baker CHD | HARVEST CHRISTIAN ACADEMY                  | FULL SCHOOL GRADES K-12             |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 0                     | 0          | 0                  | 
| 1456308932  | Baker CHD | HUNTINGTON SCHOOL DISTRICT 16J             | FULL SCHOOL GRADES K-12             |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 0                     | 0          | 0                  | 
| 1456308932  | Baker CHD | INTERMOUNTAIN ESD EARLY CHILDHOOD          | PRESCHOOL / CHILD CARE / HEAD START |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 7                     | 20         | 0                  | 
| 1456308932  | Baker CHD | KEATING ELEMENTARY SCHOOL                  | PRESCHOOL / CHILD CARE / HEAD START |                 |                |                  |                 |                      |                     |                    |                   |                  |                 |                    |                   |                 |                |                 |                |                |               |           |                      |                       | 2                     | 0          | 0                  | 
```