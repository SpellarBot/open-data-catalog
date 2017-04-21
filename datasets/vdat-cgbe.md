# NYS School Tax Relief (STAR) Reimbursement by County: Beginning Levy Year 1998

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-school-tax-relief-star-reimbursement-by-county-beginning-levy-year-1998) |
| Metadata | [Link](https://data.ny.gov/api/views/vdat-cgbe) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vdat-cgbe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vdat-cgbe/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vdat-cgbe |
| Name | NYS School Tax Relief (STAR) Reimbursement by County: Beginning Levy Year 1998 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | school tax relief, star, property tax exemption |
| Created | 2015-07-03T20:58:21Z |
| Publication Date | 2016-04-04T21:37:27Z |

## Description

The Department of Taxation and Finance?s Office of Real Property Tax Services maintains data on the New York State STAR program.  This dataset is a compilation of annual data for each school year.  Data are shown for the number and amount of basic and enhanced STAR exemptions and reimbursements by county for each levy year.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| No       |                | levy_year                        | Levy Year                        | number        | number        |
| Yes      | series tag     | county                           | County                           | text          | text          |
| Yes      | series tag     | county_code                      | County Code                      | text          | text          |
| Yes      | numeric metric | number_of_basic_exemptions       | Number of Basic Exemptions       | number        | number        |
| Yes      | numeric metric | amount_of_basic_reimbursement    | Amount of Basic Reimbursement    | number        | number        |
| Yes      | numeric metric | number_of_enhanced_exemptions    | Number of Enhanced Exemptions    | number        | number        |
| Yes      | numeric metric | amount_of_enhanced_reimbursement | Amount of Enhanced Reimbursement | number        | number        |
| Yes      | numeric metric | total_amount_of_reimbursement    | Total Amount of Reimbursement    | number        | number        |
| Yes      | time           | data_preparation_date            | Data Preparation Date            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = data_preparation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = levy_year
```

## Data Commands

```ls
series e:vdat-cgbe d:2016-03-15T00:00:00.000Z t:county=Albany t:county_code=01 m:total_amount_of_reimbursement=44175180 m:amount_of_basic_reimbursement=28476762 m:number_of_enhanced_exemptions=13417 m:amount_of_enhanced_reimbursement=15698418 m:number_of_basic_exemptions=51159

series e:vdat-cgbe d:2016-03-15T00:00:00.000Z t:county=Allegany t:county_code=02 m:total_amount_of_reimbursement=8563525 m:amount_of_basic_reimbursement=4755005 m:number_of_enhanced_exemptions=3743 m:amount_of_enhanced_reimbursement=3808520 m:number_of_basic_exemptions=8418

series e:vdat-cgbe d:2016-03-15T00:00:00.000Z t:county=Broome t:county_code=03 m:total_amount_of_reimbursement=39374871 m:amount_of_basic_reimbursement=21803374 m:number_of_enhanced_exemptions=12865 m:amount_of_enhanced_reimbursement=17571497 m:number_of_basic_exemptions=32963
```

## Meta Commands

```ls
metric m:number_of_basic_exemptions p:integer l:"Number of Basic Exemptions" d:"Number of residential units claiming basic STAR exemption (Basic STAR began in levy year 1999)." t:dataTypeName=number

metric m:amount_of_basic_reimbursement p:integer l:"Amount of Basic Reimbursement" d:"Amount (in dollars) reimbursed by the New York State to school districts within the County for the reduction in school property tax revenue due to basic STAR exemptions. (Basic STAR began in levy year 1999.)" t:dataTypeName=number

metric m:number_of_enhanced_exemptions p:integer l:"Number of Enhanced Exemptions" d:"Number of residential units claiming enhanced STAR exemption" t:dataTypeName=number

metric m:amount_of_enhanced_reimbursement p:integer l:"Amount of Enhanced Reimbursement" d:"Amount (in dollars) reimbursed by the New York State to school districts within the County for the reduction in school property tax revenue due to enhanced STAR exemptions." t:dataTypeName=number

metric m:total_amount_of_reimbursement p:integer l:"Total Amount of Reimbursement" d:"Total Amount (in dollars) reimbursed by the New York State to school districts within the County for the total reduction in school property tax revenue due to basic and enhanced STAR exemptions." t:dataTypeName=number

entity e:vdat-cgbe l:"NYS School Tax Relief (STAR) Reimbursement by County: Beginning Levy Year 1998" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/vdat-cgbe

property e:vdat-cgbe t:meta.view v:id=vdat-cgbe v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/pit/property/star/index.htm v:averageRating=0 v:name="NYS School Tax Relief (STAR) Reimbursement by County: Beginning Levy Year 1998" v:attribution="New York State Department of Taxation and Finance"

property e:vdat-cgbe t:meta.view.license v:name="Public Domain"

property e:vdat-cgbe t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vdat-cgbe t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vdat-cgbe t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| levy_year | county      | county_code | number_of_basic_exemptions | amount_of_basic_reimbursement | number_of_enhanced_exemptions | amount_of_enhanced_reimbursement | total_amount_of_reimbursement | data_preparation_date | 
| ========= | =========== | =========== | ========================== | ============================= | ============================= | ================================ | ============================= | ===================== | 
| 2015      | Albany      | 01          | 51159                      | 28476762                      | 13417                         | 15698418                         | 44175180                      | 2016-03-15T00:00:00   | 
| 2015      | Allegany    | 02          | 8418                       | 4755005                       | 3743                          | 3808520                          | 8563525                       | 2016-03-15T00:00:00   | 
| 2015      | Broome      | 03          | 32963                      | 21803374                      | 12865                         | 17571497                         | 39374871                      | 2016-03-15T00:00:00   | 
| 2015      | Cattaraugus | 04          | 14123                      | 7024602                       | 5841                          | 5287586                          | 12312188                      | 2016-03-15T00:00:00   | 
| 2015      | Cayuga      | 05          | 14148                      | 7432194                       | 5056                          | 5371474                          | 12803668                      | 2016-03-15T00:00:00   | 
| 2015      | Chautauqua  | 06          | 22933                      | 12911790                      | 10105                         | 10886933                         | 23798723                      | 2016-03-15T00:00:00   | 
| 2015      | Chemung     | 07          | 15434                      | 8818643                       | 5950                          | 6959026                          | 15777669                      | 2016-03-15T00:00:00   | 
| 2015      | Chenango    | 08          | 9004                       | 4505041                       | 3789                          | 3772073                          | 8277114                       | 2016-03-15T00:00:00   | 
| 2015      | Clinton     | 09          | 14127                      | 7730068                       | 4888                          | 5291154                          | 13021222                      | 2016-03-15T00:00:00   | 
| 2015      | Columbia    | 10          | 10352                      | 4692420                       | 3819                          | 3569190                          | 8261610                       | 2016-03-15T00:00:00   | 
```