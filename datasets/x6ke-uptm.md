# 2016 Active Business License Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-active-business-license-data) |
| Metadata | [Link](https://data.seattle.gov/api/views/x6ke-uptm) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/x6ke-uptm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/x6ke-uptm/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | x6ke-uptm |
| Name | 2016 Active Business License Data |
| Attribution | Finance and Administrative Services |
| Category | Finance |
| Tags | license, business license |
| Created | 2016-07-01T22:59:49Z |
| Publication Date | 2016-07-01T23:05:20Z |

## Description

Dataset contains active business license data for the City of Seattle for 2016, as of June 30, 2016.

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
| Yes      | series tag  | city_state_zip      | City, State, ZIP    | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x6ke-uptm d:2016-01-01T00:00:00.000Z t:license_start_date=04-Jul-43 t:city_state_zip="SEATTLE, WA 98108" t:ownership_type=Corporation t:business_legal_name="UNION PACIFIC RAILROAD COMPANY" t:naics_description="Line-Haul Railroads" t:trade_name="UNION PACIFIC RAILROAD COMPANY" t:naics_code=482111 m:row_number.x6ke-uptm=1

series e:x6ke-uptm d:2016-01-01T00:00:00.000Z t:license_start_date=04-Jul-43 t:city_state_zip="LAKEWOOD, WA 98499" t:ownership_type=Corporation t:business_legal_name="CORE MARK INTL INC" t:naics_description="Other Grocery and Related Products Merchant Wholesalers" t:trade_name="CORE-MARK INTL INC" t:naics_code=424490 m:row_number.x6ke-uptm=2

series e:x6ke-uptm d:2016-01-01T00:00:00.000Z t:license_start_date=04-Jul-43 t:city_state_zip="SEATTLE, WA 98134" t:ownership_type=Corporation t:business_legal_name="NATL ASSN OF CREDIT MANAGEMENT WESTERN WA" t:naics_description="Collection Agencies" t:trade_name="NACM WESTERN WASHINGTON & ALASKA" t:naics_code=561440 m:row_number.x6ke-uptm=3
```

## Meta Commands

```ls
metric m:row_number.x6ke-uptm p:long l:"Row Number"

entity e:x6ke-uptm l:"2016 Active Business License Data" t:attribution="Finance and Administrative Services" t:url=https://data.seattle.gov/api/views/x6ke-uptm

property e:x6ke-uptm t:meta.view v:id=x6ke-uptm v:category=Finance v:attributionLink=http://www.seattle.gov/fas/ v:averageRating=0 v:name="2016 Active Business License Data" v:attribution="Finance and Administrative Services"

property e:x6ke-uptm t:meta.view.license v:name="Public Domain"

property e:x6ke-uptm t:meta.view.owner v:id=vjep-zmv4 v:screenName="FAS - Financial Services" v:displayName="FAS - Financial Services"

property e:x6ke-uptm t:meta.view.tableauthor v:id=vjep-zmv4 v:screenName="FAS - Financial Services" v:roleName=publisher v:displayName="FAS - Financial Services"
```

## Top Records

```ls
| business_legal_name                       | ownership_type | trade_name                       | naics_code | naics_description                                          | license_start_date | city_state_zip     | 
| ========================================= | ============== | ================================ | ========== | ========================================================== | ================== | ================== | 
| UNION PACIFIC RAILROAD COMPANY            | Corporation    | UNION PACIFIC RAILROAD COMPANY   | 482111     | Line-Haul Railroads                                        | 04-Jul-43          | SEATTLE, WA 98108  | 
| CORE MARK INTL INC                        | Corporation    | CORE-MARK INTL INC               | 424490     | Other Grocery and Related Products Merchant Wholesalers    | 04-Jul-43          | LAKEWOOD, WA 98499 | 
| NATL ASSN OF CREDIT MANAGEMENT WESTERN WA | Corporation    | NACM WESTERN WASHINGTON & ALASKA | 561440     | Collection Agencies                                        | 04-Jul-43          | SEATTLE, WA 98134  | 
| WILBUR ELLIS CO                           | Corporation    | WILBUR-ELLIS CO                  | 424910     | Farm Supplies Merchant Wholesalers                         | 01-Jan-00          | AUBURN, WA 98001   | 
| WILBUR ELLIS CO                           | Corporation    | WILBUR-ELLIS CO                  | 424910     | Farm Supplies Merchant Wholesalers                         | 01-Jan-87          | AUBURN, WA 98001   | 
| SAFEWAY INC                               | Corporation    | SAFEWAY STORE #1965              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 29-Jan-03          | SEATTLE, WA 98118  | 
| SAFEWAY INC                               | Corporation    | SAFEWAY INC STORE 1508           | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 01-Jan-95          | SEATTLE, WA 98118  | 
| SAFEWAY INC                               | Corporation    | SAFEWAY STORE #1143              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 01-Jan-95          | SEATTLE, WA 98117  | 
| SAFEWAY INC                               | Corporation    | SAFEWAY STORE #3091              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 01-Jan-87          | SEATTLE, WA 98105  | 
| SAFEWAY INC                               | Corporation    | SAFEWAY STORE #1586              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 01-Jan-87          | SEATTLE, WA 98125  | 
```