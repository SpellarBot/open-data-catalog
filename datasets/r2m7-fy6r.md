# Hartford Glossary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hartford-glossary) |
| Metadata | [Link](https://data.hartford.gov/api/views/r2m7-fy6r) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/r2m7-fy6r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/r2m7-fy6r/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | r2m7-fy6r |
| Name | Hartford Glossary |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | hartford, financial, checkbook |
| Created | 2015-08-25T20:28:11Z |
| Publication Date | 2015-08-25T20:28:24Z |

## Description

The glossary is being used for our checkbook Hartford website

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | term_type   | Term Type   | text      | text        |
| Yes      | series tag  | term        | Term        | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:r2m7-fy6r d:2015-08-25T13:28:14.000Z t:term="Culture & Recreation" t:description="Events to enhance the quality of life in Hartford.  Promotes artists, the arts and cultural organizations." t:term_type=Org1 m:row_number.r2m7-fy6r=1

series e:r2m7-fy6r d:2015-08-25T13:28:14.000Z t:term="Debt Service" t:description="Management of the City's long term debt." t:term_type=Org1 m:row_number.r2m7-fy6r=2

series e:r2m7-fy6r d:2015-08-25T13:28:14.000Z t:term="Development & Comm Affairs" t:description="Parking garage operations, Hartford Parking Authority, Hartford Public Library, Planning for growth and improvement" t:term_type=Org1 m:row_number.r2m7-fy6r=3
```

## Meta Commands

```ls
metric m:row_number.r2m7-fy6r p:long l:"Row Number"

entity e:r2m7-fy6r l:"Hartford Glossary" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/r2m7-fy6r

property e:r2m7-fy6r t:meta.view v:id=r2m7-fy6r v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Hartford Glossary" v:attribution="City of Hartford"

property e:r2m7-fy6r t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:r2m7-fy6r t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:r2m7-fy6r t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| :updated_at | term_type | term                           | description                                                                                                                       | 
| =========== | ========= | ============================== | ================================================================================================================================= | 
| 1440509294  | Org1      | Culture & Recreation           | Events to enhance the quality of life in Hartford. Promotes artists, the arts and cultural organizations.                         | 
| 1440509294  | Org1      | Debt Service                   | Management of the City's long term debt.                                                                                          | 
| 1440509294  | Org1      | Development & Comm Affairs     | Parking garage operations, Hartford Parking Authority, Hartford Public Library, Planning for growth and improvement               | 
| 1440509294  | Org1      | Development Services           | Controls the development of Hartford's neighborhoods. Provides for job creation, community services and safe affordable hosing.   | 
| 1440509294  | Org1      | Economic Development           | Small business development, licensing & inspections, marketing events, housing lending                                            | 
| 1440509294  | Org1      | EDUCATION                      | Hartford Public School System                                                                                                     | 
| 1440509294  | Org1      | Finance                        | Vehicle leasing, tax deeds                                                                                                        | 
| 1440509294  | Org1      | General Government             | Treasurer, Information Services, Town Clerk, Registrar of Voters,Internal Audit, Corporation Council, Mayors Office, City Council | 
| 1440509294  | Org1      | Human Services                 | Health, Department of Families, Children, Youth and Recreation                                                                    | 
| 1440509294  | Org1      | INTERGOVERNMENTAL EXPENDITURES | Employee pension expenses                                                                                                         | 
```