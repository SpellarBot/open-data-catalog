# NYS School Tax Relief (STAR) Reimbursement by School District: Beginning Levy Year 1998

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-school-tax-relief-star-reimbursement-by-school-district-beginning-levy-year-1998) |
| Metadata | [Link](https://data.ny.gov/api/views/aa3i-eamx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/aa3i-eamx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/aa3i-eamx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | aa3i-eamx |
| Name | NYS School Tax Relief (STAR) Reimbursement by School District: Beginning Levy Year 1998 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | school tax relief, star, property tax exemption |
| Created | 2015-07-03T21:20:22Z |
| Publication Date | 2016-03-16T20:04:48Z |

## Description

The Department of Taxation and Finance?s Office of Real Property Tax Services maintains data on the New York State STAR program.  This dataset is a compilation of annual data for each school year.  Data are shown for the number and amount of basic and enhanced STAR exemptions and reimbursements by school district for each levy year.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| No       |                | levy_year                        | Levy Year                        | number        | number        |
| Yes      | series tag     | school_district_name             | School District Name             | text          | text          |
| Yes      | series tag     | school_district_code             | School District Code             | text          | text          |
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
series e:aa3i-eamx d:2016-03-15T00:00:00.000Z t:school_district_name=Albany t:school_district_code=010100 m:total_amount_of_reimbursement=9848885 m:amount_of_basic_reimbursement=6049155 m:number_of_enhanced_exemptions=2970 m:amount_of_enhanced_reimbursement=3799730 m:number_of_basic_exemptions=9529

series e:aa3i-eamx d:2016-03-15T00:00:00.000Z t:school_district_name=Cohoes t:school_district_code=010300 m:total_amount_of_reimbursement=2083105 m:amount_of_basic_reimbursement=1210026 m:number_of_enhanced_exemptions=712 m:amount_of_enhanced_reimbursement=873079 m:number_of_basic_exemptions=2073

series e:aa3i-eamx d:2016-03-15T00:00:00.000Z t:school_district_name=Watervliet t:school_district_code=011800 m:total_amount_of_reimbursement=899503 m:amount_of_basic_reimbursement=501811 m:number_of_enhanced_exemptions=452 m:amount_of_enhanced_reimbursement=397692 m:number_of_basic_exemptions=1188
```

## Meta Commands

```ls
metric m:number_of_basic_exemptions p:integer l:"Number of Basic Exemptions" d:"Number of residential units claiming basic STAR exemption (Basic STAR began in levy year 1999)" t:dataTypeName=number

metric m:amount_of_basic_reimbursement p:integer l:"Amount of Basic Reimbursement" d:"Amount (in dollars) reimbursed by New York State to the school district for the reduction in school property tax revenue due to basic STAR exemptions (Basic STAR began in levy year 1999)" t:dataTypeName=number

metric m:number_of_enhanced_exemptions p:integer l:"Number of Enhanced Exemptions" d:"Number of residential units claiming enhanced STAR exemption" t:dataTypeName=number

metric m:amount_of_enhanced_reimbursement p:integer l:"Amount of Enhanced Reimbursement" d:"Amount (in dollars) reimbursed by New York State to the school district for the reduction in school property tax revenue due to enhanced STAR exemptions" t:dataTypeName=number

metric m:total_amount_of_reimbursement p:integer l:"Total Amount of Reimbursement" d:"Total Amount (in dollars) reimbursed by New York State the school district for the total reduction in school property tax revenue due to basic and enhanced STAR exemptions" t:dataTypeName=number

entity e:aa3i-eamx l:"NYS School Tax Relief (STAR) Reimbursement by School District: Beginning Levy Year 1998" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/aa3i-eamx

property e:aa3i-eamx t:meta.view v:id=aa3i-eamx v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/pit/property/star/index.htm v:averageRating=0 v:name="NYS School Tax Relief (STAR) Reimbursement by School District: Beginning Levy Year 1998" v:attribution="New York State Department of Taxation and Finance"

property e:aa3i-eamx t:meta.view.license v:name="Public Domain"

property e:aa3i-eamx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:aa3i-eamx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:aa3i-eamx t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| levy_year | school_district_name    | school_district_code | number_of_basic_exemptions | amount_of_basic_reimbursement | number_of_enhanced_exemptions | amount_of_enhanced_reimbursement | total_amount_of_reimbursement | data_preparation_date | 
| ========= | ======================= | ==================== | ========================== | ============================= | ============================= | ================================ | ============================= | ===================== | 
| 2015      | Albany                  | 010100               | 9529                       | 6049155                       | 2970                          | 3799730                          | 9848885                       | 2016-03-15T00:00:00   | 
| 2015      | Cohoes                  | 010300               | 2073                       | 1210026                       | 712                           | 873079                           | 2083105                       | 2016-03-15T00:00:00   | 
| 2015      | Watervliet              | 011800               | 1188                       | 501811                        | 452                           | 397692                           | 899503                        | 2016-03-15T00:00:00   | 
| 2015      | Berne-Knox-Westerlo     | 012001               | 1598                       | 872776                        | 447                           | 498968                           | 1371744                       | 2016-03-15T00:00:00   | 
| 2015      | Bethlehem               | 012206               | 6733                       | 4129544                       | 1140                          | 1508950                          | 5638494                       | 2016-03-15T00:00:00   | 
| 2015      | Ravena-Coeymans-Selkirk | 012402               | 2787                       | 1629922                       | 799                           | 982509                           | 2612431                       | 2016-03-15T00:00:00   | 
| 2015      | South Colonie           | 012601               | 8931                       | 4694913                       | 2728                          | 3040008                          | 7734921                       | 2016-03-15T00:00:00   | 
| 2015      | North Colonie           | 012605               | 7949                       | 3814517                       | 1723                          | 1768202                          | 5582719                       | 2016-03-15T00:00:00   | 
| 2015      | Menands                 | 012615               | 375                        | 192806                        | 93                            | 102467                           | 295273                        | 2016-03-15T00:00:00   | 
| 2015      | Green Island            | 012801               | 244                        | 146281                        | 120                           | 153919                           | 300200                        | 2016-03-15T00:00:00   | 
```