# ICN E-Rate Details for School & Libraries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/icn-e-rate-details-for-school-libraries) |
| Metadata | [Link](https://data.iowa.gov/api/views/4dfz-ax32) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/4dfz-ax32/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/4dfz-ax32/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 4dfz-ax32 |
| Name | ICN E-Rate Details for School & Libraries |
| Attribution | Iowa Communications Network |
| Category | Education |
| Tags | telecommunications, usac, e-rate, internet, data, icn |
| Created | 2015-07-29T15:14:45Z |
| Publication Date | 2016-07-15T13:40:44Z |

## Description

Federal Universal Service Fund (USF) Tax Dollars Approved for Qualified Services by Applicant by Fiscal Year.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | series tag     | service_ordered         | Service Ordered         | text      | text        |
| Yes      | series tag     | applicant               | Applicant               | text      | text        |
| Yes      | numeric metric | tax_dollars_approved    | Tax Dollars Approved    | money     | money       |
| Yes      | numeric metric | tax_percentage_approved | Tax Percentage Approved | percent   | percent     |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4dfz-ax32 d:2015-01-01T00:00:00.000Z t:service_ordered="Internet Access" t:applicant="ACKLEY-GENEVA WELLSBURG STEAMBOAT ROCK SCHOOL DIST" m:tax_dollars_approved=7492.8 m:tax_percentage_approved=70

series e:4dfz-ax32 d:2015-01-01T00:00:00.000Z t:service_ordered="Telecommunications Service" t:applicant="ACKLEY-GENEVA WELLSBURG STEAMBOAT ROCK SCHOOL DIST" m:tax_dollars_approved=8892.8 m:tax_percentage_approved=70

series e:4dfz-ax32 d:2015-01-01T00:00:00.000Z t:service_ordered="Internet Access" t:applicant="ADAIR-CASEY COMM SCHOOL DIST" m:tax_dollars_approved=4316.05 m:tax_percentage_approved=65
```

## Meta Commands

```ls
metric m:tax_dollars_approved p:double l:"Tax Dollars Approved" d:"The total amount of E-rate funds available for the applicant for the fiscal year." t:dataTypeName=money

metric m:tax_percentage_approved p:integer l:"Tax Percentage Approved" d:"Percentage of service discount applicant is qualified to receive." t:dataTypeName=percent

entity e:4dfz-ax32 l:"ICN E-Rate Details for School & Libraries" t:attribution="Iowa Communications Network" t:url=https://data.iowa.gov/api/views/4dfz-ax32

property e:4dfz-ax32 t:meta.view v:id=4dfz-ax32 v:category=Education v:averageRating=0 v:name="ICN E-Rate Details for School & Libraries" v:attribution="Iowa Communications Network"

property e:4dfz-ax32 t:meta.view.license v:name="Public Domain"

property e:4dfz-ax32 t:meta.view.owner v:id=ghj5-n87n v:profileImageUrlMedium=/api/users/ghj5-n87n/profile_images/THUMB v:profileImageUrlLarge=/api/users/ghj5-n87n/profile_images/LARGE v:screenName="Iowa Communications Network" v:profileImageUrlSmall=/api/users/ghj5-n87n/profile_images/TINY v:displayName="Iowa Communications Network"

property e:4dfz-ax32 t:meta.view.tableauthor v:id=ghj5-n87n v:profileImageUrlMedium=/api/users/ghj5-n87n/profile_images/THUMB v:profileImageUrlLarge=/api/users/ghj5-n87n/profile_images/LARGE v:screenName="Iowa Communications Network" v:profileImageUrlSmall=/api/users/ghj5-n87n/profile_images/TINY v:roleName=editor v:displayName="Iowa Communications Network"
```

## Top Records

```ls
| fiscal_year | service_ordered            | applicant                                          | tax_dollars_approved | tax_percentage_approved | 
| =========== | ========================== | ================================================== | ==================== | ======================= | 
| 2015        | Internet Access            | ACKLEY-GENEVA WELLSBURG STEAMBOAT ROCK SCHOOL DIST | 7492.80              | 70                      | 
| 2015        | Telecommunications Service | ACKLEY-GENEVA WELLSBURG STEAMBOAT ROCK SCHOOL DIST | 8892.80              | 70                      | 
| 2015        | Internet Access            | ADAIR-CASEY COMM SCHOOL DIST                       | 4316.05              | 65                      | 
| 2015        | Telecommunications Service | ADAIR-CASEY COMM SCHOOL DIST                       | 390.00               | 65                      | 
| 2015        | Internet Access            | ADEL-DESOTO-MINBURN COMM SCHS                      | 4032.54              | 50                      | 
| 2015        | Internet Access            | ALBERT CITY-TRUESDALE CSD                          | 4287.26              | 80                      | 
| 2015        | Telecommunications Service | ALBERT CITY-TRUESDALE CSD                          | 413.66               | 80                      | 
| 2015        | Internet Access            | ALBIA COMMUNITY SCHOOL DIST                        | 7668.87              | 67                      | 
| 2015        | Telecommunications Service | ALBIA COMMUNITY SCHOOL DIST                        | 949.44               | 67                      | 
| 2015        | Internet Access            | ALBURNETT COMM SCHOOL DISTRICT                     | 5265.20              | 46                      | 
```