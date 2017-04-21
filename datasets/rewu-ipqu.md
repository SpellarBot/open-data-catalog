# 2016 Active Businesses License Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-active-businesses-license-data) |
| Metadata | [Link](https://data.seattle.gov/api/views/rewu-ipqu) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/rewu-ipqu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/rewu-ipqu/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | rewu-ipqu |
| Name | 2016 Active Businesses License Data |
| Attribution | City of Seattle, Department of Finance & Administrative Services |
| Category | Finance |
| Tags | finance, business, licence, tax |
| Created | 2017-01-20T20:55:04Z |
| Publication Date | 2017-01-20T21:37:27Z |

## Description

City of Seattle Business License data current as of January 9, 2017

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | series tag  | business_legal_name | Business Legal Name | text      | text        |
| Yes      | series tag  | ownership_type      | Ownership Type      | text      | text        |
| Yes      | series tag  | trade_name          | Trade Name          | text      | text        |
| Yes      | series tag  | naics_code          | NAICS Code          | text      | number      |
| Yes      | series tag  | naics_description   | NAICS Description   | text      | text        |
| Yes      | series tag  | license_start_date  | License Start Date  | text      | text        |
| Yes      | series tag  | city_state_zip      | City, State, Zip    | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rewu-ipqu d:2016-01-01T00:00:00.000Z t:license_start_date=01-Apr-18 t:city_state_zip="SEATTLE, WA 98115-3306" t:ownership_type="Sole Proprietor" t:business_legal_name="POOL REBECCA E" t:naics_description="Other Specialized Design Services" t:trade_name="REBECCA POOL" t:naics_code=541490 m:row_number.rewu-ipqu=1

series e:rewu-ipqu d:2016-01-01T00:00:00.000Z t:license_start_date=02-Jan-18 t:city_state_zip="SEATTLE, WA 98105" t:ownership_type="LLC*Limited Liability Co" t:business_legal_name="JOYFULZI LLC" t:naics_description="Meat Markets" t:trade_name="MY FAVORITE DELI" t:naics_code=445210 m:row_number.rewu-ipqu=2

series e:rewu-ipqu d:2016-01-01T00:00:00.000Z t:license_start_date=01-Jan-18 t:city_state_zip="SEATTLE, WA 98106" t:ownership_type="Sole Proprietor" t:business_legal_name="JUUL WANDA S" t:naics_description="All Other Transit and Ground Passenger Transportation" t:trade_name="WANDA S JUUL" t:naics_code=485999 m:row_number.rewu-ipqu=3
```

## Meta Commands

```ls
metric m:row_number.rewu-ipqu p:long l:"Row Number"

entity e:rewu-ipqu l:"2016 Active Businesses License Data" t:attribution="City of Seattle, Department of Finance & Administrative Services" t:url=https://data.seattle.gov/api/views/rewu-ipqu

property e:rewu-ipqu t:meta.view v:id=rewu-ipqu v:category=Finance v:attributionLink=http://www.seattle.gov/licenses/get-a-business-license/who-needs-a-business-license v:averageRating=0 v:name="2016 Active Businesses License Data" v:attribution="City of Seattle, Department of Finance & Administrative Services"

property e:rewu-ipqu t:meta.view.license v:name="Public Domain"

property e:rewu-ipqu t:meta.view.owner v:id=vjep-zmv4 v:screenName="FAS - Financial Services" v:displayName="FAS - Financial Services"

property e:rewu-ipqu t:meta.view.tableauthor v:id=vjep-zmv4 v:screenName="FAS - Financial Services" v:roleName=publisher v:displayName="FAS - Financial Services"
```

## Top Records

```ls
| business_legal_name                        | ownership_type           | trade_name                                 | naics_code | naics_description                                     | license_start_date | city_state_zip         | 
| ========================================== | ======================== | ========================================== | ========== | ===================================================== | ================== | ====================== | 
| POOL REBECCA E                             | Sole Proprietor          | REBECCA POOL                               | 541490     | Other Specialized Design Services                     | 01-Apr-18          | SEATTLE, WA 98115-3306 | 
| JOYFULZI LLC                               | LLC*Limited Liability Co | MY FAVORITE DELI                           | 445210     | Meat Markets                                          | 02-Jan-18          | SEATTLE, WA 98105      | 
| JUUL WANDA S                               | Sole Proprietor          | WANDA S JUUL                               | 485999     | All Other Transit and Ground Passenger Transportation | 01-Jan-18          | SEATTLE, WA 98106      | 
| LENOVA GLOBAL TECHNOLOGY UNITED STATES INC | Corporation              | LENOVA GLOBAL TECHNOLOGY UNITED STATES INC | 334111     | Electronic Computer Manufacturing                     | 01-Jan-18          | MORRISVILLE, NC 27560  | 
| WELDY VICTORIA L                           | Sole Proprietor          | ADVANCED BEGINNING CHILDCARE               | 624410     | Child Day Care Services                               | 01-Jan-18          | SEATTLE, WA 98106-2305 | 
| LUSHER JULIA L                             | Sole Proprietor          | JULIA L LUSHER                             | 485999     | All Other Transit and Ground Passenger Transportation | 01-Jan-18          | PORT ORCHARD, WA 98366 | 
| WARRANTY LOGISTICS LLC                     | LLC*Limited Liability Co | WARRANTY LOGISTICS LLC                     | 811211     | Consumer Electronics Repair and Maintenance           | 01-Jan-18          | SEATTLE, WA 98101      | 
| TELICA PETROS S                            | Sole Proprietor          | PETROS S TELICA                            | 485999     | All Other Transit and Ground Passenger Transportation | 01-Jan-18          | SEATTLE, WA 98125      | 
| ZENG JIA MING                              | Sole Proprietor          | JIA MING ZENG                              | 485999     | All Other Transit and Ground Passenger Transportation | 01-Jan-18          | RENTON, WA 98056       | 
| IONA PRIVATE PROTECTION LLC                | LLC*Limited Liability Co | IONA PRIVATE PROTECTION                    | 561612     | Security Guards and Patrol Services                   | 01-Jan-18          | EVERETT, WA 98204      | 
```