# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.Rental Housing Support Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-applications-rental-housing-support-a7bf4) |
| Metadata | [Link](https://data.illinois.gov/api/views/c72f-kjd5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/c72f-kjd5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/c72f-kjd5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | c72f-kjd5 |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.Rental Housing Support Program |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T16:59:03Z |
| Publication Date | 2012-01-25T22:00:19Z |

## Description

FY2010 Governor's Report - Applications.Rental Housing Support Program

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type     | Render Type   |
| ======== | ============== | ============================================ | ============================================ | ============= | ============= |
| No       |                | fiscal_year                                  | FISCAL YEAR                                  | number        | text          |
| Yes      | series tag     | agency_name                                  | AGENCY NAME                                  | text          | text          |
| No       |                | unit_address                                 | UNIT ADDRESS                                 | text          | text          |
| Yes      | series tag     | service_area                                 | SERVICE AREA                                 | text          | text          |
| Yes      | series tag     | grant                                        | GRANT                                        | text          | text          |
| Yes      | time           | application_date                             | APPLICATION DATE                             | calendar_date | calendar_date |
| Yes      | numeric metric | total_rental_housing_support_program_request | TOTAL RENTAL HOUSING SUPPORT PROGRAM REQUEST | money         | money         |
| Yes      | numeric metric | of_units                                     | # OF UNITS                                   | number        | number        |
```

## Time Field

```ls
Value = application_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = unit_address,fiscal_year
```

## Data Commands

```ls
series e:c72f-kjd5 d:2009-12-09T00:00:00.000Z t:grant=Grant t:service_area="Lake County" t:agency_name="Affordable Housing Corporation of Lake County" m:total_rental_housing_support_program_request=1495375 m:of_units=31

series e:c72f-kjd5 d:2009-12-09T00:00:00.000Z t:grant=Grant t:service_area="Cook County" t:agency_name=CEDA m:total_rental_housing_support_program_request=3140000 m:of_units=79

series e:c72f-kjd5 d:2009-12-09T00:00:00.000Z t:grant=Grant t:service_area="DuPage County" t:agency_name="DuPage Housing Authority" m:total_rental_housing_support_program_request=7016340 m:of_units=200
```

## Meta Commands

```ls
metric m:total_rental_housing_support_program_request p:integer l:"TOTAL RENTAL HOUSING SUPPORT PROGRAM REQUEST" t:dataTypeName=money

metric m:of_units p:integer l:"# OF UNITS" t:dataTypeName=number

entity e:c72f-kjd5 l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.Rental Housing Support Program" t:url=https://data.illinois.gov/api/views/c72f-kjd5

property e:c72f-kjd5 t:meta.view v:id=c72f-kjd5 v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.Rental Housing Support Program"

property e:c72f-kjd5 t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:c72f-kjd5 t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | agency_name                                       | unit_address | service_area                 | grant | application_date    | total_rental_housing_support_program_request | of_units | 
| =========== | ================================================= | ============ | ============================ | ===== | =================== | ============================================ | ======== | 
| 2010        | Affordable Housing Corporation of Lake County     | Various      | Lake County                  | Grant | 2009-12-09T00:00:00 | 1495375                                      | 31       | 
| 2010        | CEDA                                              | Various      | Cook County                  | Grant | 2009-12-09T00:00:00 | 3140000                                      | 79       | 
| 2010        | DuPage Housing Authority                          | Various      | DuPage County                | Grant | 2009-12-09T00:00:00 | 7016340                                      | 200      | 
| 2010        | Housing Choice Partners                           | Various      | Cook County                  | Grant | 2009-12-09T00:00:00 | 1648944                                      | 41       | 
| 2010        | Lazarus House                                     | Various      | Kane County                  | Grant | 2009-12-09T00:00:00 | 478606                                       | 12       | 
| 2010        | City of Rockford, Human Services Department       | Various      | Winnebago and Boone Counties | Grant | 2009-12-09T00:00:00 | 1020780                                      | 35       | 
| 2010        | Illinois Association of Community Action Agencies | Various      | 32 rural counties            | Grant | 2009-12-09T00:00:00 | 1498284                                      | 80       | 
| 2010        | Kankakee County Housing Authority                 | Various      | Kankakee County              | Grant | 2009-12-09T00:00:00 | 361350                                       | 10       | 
| 2010        | Kendall Housing Authority                         | Various      | Kendall and Grundy Counties  | Grant | 2009-12-09T00:00:00 | 4008816                                      | 100      | 
| 2010        | Winnebago County Housing Authority                | Various      | 9 rural counties             | Grant | 2009-12-09T00:00:00 | 933412                                       | 55       | 
```