# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.State Tax Credits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-closings-state-tax-credits-d5b75) |
| Metadata | [Link](https://data.illinois.gov/api/views/thdm-e6xz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/thdm-e6xz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/thdm-e6xz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | thdm-e6xz |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.State Tax Credits |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T15:17:52Z |
| Publication Date | 2012-01-25T22:00:50Z |

## Description

FY2010 Governor's Report - Closings.State Tax Credits

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| No       |                | fiscal_year            | FISCAL YEAR            | number        | text          |
| Yes      | series tag     | project_name           | PROJECT NAME           | text          | text          |
| No       |                | project_address        | PROJECT ADDRESS        | text          | text          |
| Yes      | series tag     | project_city           | PROJECT CITY           | text          | text          |
| Yes      | series tag     | owner                  | OWNER                  | text          | text          |
| Yes      | series tag     | credit_type            | CREDIT TYPE            | text          | text          |
| Yes      | time           | reservation_date       | RESERVATION DATE       | calendar_date | calendar_date |
| Yes      | numeric metric | amount                 | AMOUNT                 | money         | money         |
| Yes      | numeric metric | units                  | UNITS                  | number        | number        |
| Yes      | numeric metric | state_tax_credit_units | STATE TAX CREDIT UNITS | number        | number        |
```

## Time Field

```ls
Value = reservation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address,fiscal_year
```

## Data Commands

```ls
series e:thdm-e6xz d:2009-12-07T00:00:00.000Z t:project_name="Branch of Hope Apartments" t:owner="56th Street Limited Partnership" t:project_city=Chicago t:credit_type="State Tax Credits" m:amount=358493 m:state_tax_credit_units=100 m:units=100

series e:thdm-e6xz d:2009-12-29T00:00:00.000Z t:project_name="DuPage Habitat 2009 Scattered Site Homes" t:owner="DuPage Habitat for Humanity" t:project_city="Addison, Villa Park, Glendale Heights, W. Chicago" t:credit_type="State Tax Credits" m:amount=104976 m:state_tax_credit_units=4 m:units=4

series e:thdm-e6xz d:2009-12-29T00:00:00.000Z t:project_name="DuPage Habitat Pioneer Prairie Phase II" t:owner="Pioneer Prairie, LLC" t:project_city="West Chicago" t:credit_type="State Tax Credits" m:amount=43257 m:state_tax_credit_units=2 m:units=2
```

## Meta Commands

```ls
metric m:amount p:integer l:AMOUNT t:dataTypeName=money

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:state_tax_credit_units p:integer l:"STATE TAX CREDIT UNITS" t:dataTypeName=number

entity e:thdm-e6xz l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.State Tax Credits" t:url=https://data.illinois.gov/api/views/thdm-e6xz

property e:thdm-e6xz t:meta.view v:id=thdm-e6xz v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Closings.State Tax Credits"

property e:thdm-e6xz t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:thdm-e6xz t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                                  | project_address                                                   | project_city                                      | owner                                       | credit_type                                       | reservation_date    | amount  | units | state_tax_credit_units | 
| =========== | ============================================= | ================================================================= | ================================================= | =========================================== | ================================================= | =================== | ======= | ===== | ====================== | 
| 2010        | Branch of Hope Apartments                     | 5600-5658 South Halsted                                           | Chicago                                           | 56th Street Limited Partnership             | State Tax Credits                                 | 2009-12-07T00:00:00 | 358493  | 100   | 100                    | 
| 2010        | DuPage Habitat 2009 Scattered Site Homes      | Scattered Sites                                                   | Addison, Villa Park, Glendale Heights, W. Chicago | DuPage Habitat for Humanity                 | State Tax Credits                                 | 2009-12-29T00:00:00 | 104976  | 4     | 4                      | 
| 2010        | DuPage Habitat Pioneer Prairie Phase II       | 308 W. Pomeroy & 316 W. Pomeroy                                   | West Chicago                                      | Pioneer Prairie, LLC                        | State Tax Credits                                 | 2009-12-29T00:00:00 | 43257   | 2     | 2                      | 
| 2010        | Hairpin Lofts                                 | 2800-12 N. Milwaukee and 3416 W. Diversey                         | Chicago                                           | Hairpin Lofts, LLC                          | State Tax Credits                                 | 2010-03-15T00:00:00 | 1500000 | 28    | 25                     | 
| 2010        | Hancock House                                 | 12045 S. Emerald                                                  | Chicago                                           | Hancock House LP                            | State Tax Credits                                 | 2010-04-14T00:00:00 | 45000   | 89    | 80                     | 
| 2010        | Liberty Meadows Estates Phase II              | Southwest Corner of Briggs and Rosalind                           | Joliet                                            | Liberty Meadow Estates Phase II             | State Tax Credits                                 | 2010-06-29T00:00:00 | 299901  | 42    | 35                     | 
| 2010        | Live Work Rock Island Phase VI                | 120 16 1/2 Street                                                 | Rock Island                                       | Rock Island Economic Growth Corp.           | Employer Assisted Housing (EAH) State Tax Credits | 2010-05-10T00:00:00 | 283735  | 73    | 73                     | 
| 2010        | McKenzie Falls                                | Intersection of Briarcliff & Malibu Roads                         | Bolingbrook                                       | McKenzie Falls LLC                          | State Tax Credits                                 | 2010-05-12T00:00:00 | 466578  | 106   | 105                    | 
| 2010        | Northeastwood Shores                          | 850 W. Eastwood Avenue                                            | Chicago                                           | HWA-850 Eastwood Limited Partnership        | State Tax Credits                                 | 2010-05-21T00:00:00 | 4087500 | 231   | 215                    | 
| 2010        | Northern Fox Valley Habitat for Humanity 2009 | 611 Margaret Place, 467 Division St, & 475 Dixon, 140 Lord Avenue | Elgin & Carpentersville                           | Habitat for Humanity of Northern Fox Valley | State Tax Credits                                 | 2009-12-29T00:00:00 | 266089  | 4     | 4                      | 
```