# 2010 Active Business License Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-active-business-license-data-0e328) |
| Metadata | [Link](https://data.seattle.gov/api/views/evxh-x3jp) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/evxh-x3jp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/evxh-x3jp/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | evxh-x3jp |
| Name | 2010 Active Business License Data |
| Attribution | City of Seattle Department of Finance and Administrative Services |
| Category | Finance |
| Tags | business license, zzznb |
| Created | 2011-10-26T17:29:22Z |
| Publication Date | 2011-10-26T17:45:49Z |

## Description

Dataset contains active business license data for the City of Seattle for 2010

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | series tag  | business_legal_name | Business Legal Name | text      | text        |
| Yes      | series tag  | ownership_type      | Ownership Type      | text      | text        |
| Yes      | series tag  | trade_name          | Trade Name          | text      | text        |
| Yes      | series tag  | naics_code          | NAICS Code          | text      | number      |
| Yes      | series tag  | naics_description   | NAICS Description   | text      | text        |
| Yes      | series tag  | sic_code            | SIC Code            | text      | number      |
| Yes      | series tag  | sic_description     | SIC Description     | text      | text        |
| Yes      | time        | license_start_date  | License Start Date  | date      | date        |
| Yes      | series tag  | city_state_zip      | City, State, Zip    | text      | text        |
```

## Time Field

```ls
Value = license_start_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:evxh-x3jp d:1943-07-04T07:00:00.000Z t:city_state_zip="SEATTLE, WA   98108" t:ownership_type=Corporation t:business_legal_name="UNION PACIFIC RAILROAD COMPANY" t:sic_description="Railroads, Line-Haul Operating" t:sic_code=575 t:naics_description="Line-Haul Railroads" t:trade_name="UNION PACIFIC RAILROAD COMPANY" t:naics_code=482111 m:row_number.evxh-x3jp=1

series e:evxh-x3jp d:1943-07-04T07:00:00.000Z t:city_state_zip="KENT, WA   98032" t:ownership_type=Corporation t:business_legal_name="SEA PAC SALES COMPANY" t:sic_description="Home furnishings" t:sic_code=645 t:naics_description="Home Furnishing Merchant Wholesalers" t:trade_name="SEA-PAC SALES COMPANY" t:naics_code=423220 m:row_number.evxh-x3jp=2

series e:evxh-x3jp d:1943-07-04T07:00:00.000Z t:city_state_zip="SEATTLE, WA   98109" t:ownership_type=Corporation t:business_legal_name="WILDERMAN REFRIGERATION CO" t:sic_description="Refrigeration Equipment and Supplies" t:sic_code=665 t:naics_description="Refrigeration Equipment and Supplies Merchant Wholesalers" t:trade_name="WILDERMAN REFRIGERATION CO" t:naics_code=423740 m:row_number.evxh-x3jp=3
```

## Meta Commands

```ls
metric m:row_number.evxh-x3jp p:long l:"Row Number"

entity e:evxh-x3jp l:"2010 Active Business License Data" t:attribution="City of Seattle Department of Finance and Administrative Services" t:url=https://data.seattle.gov/api/views/evxh-x3jp

property e:evxh-x3jp t:meta.view v:id=evxh-x3jp v:category=Finance v:averageRating=0 v:name="2010 Active Business License Data" v:attribution="City of Seattle Department of Finance and Administrative Services"

property e:evxh-x3jp t:meta.view.license v:name="Public Domain"

property e:evxh-x3jp t:meta.view.owner v:id=n3fs-imjt v:screenName=JLCarnell v:displayName=JLCarnell

property e:evxh-x3jp t:meta.view.tableauthor v:id=n3fs-imjt v:screenName=JLCarnell v:roleName=publisher v:displayName=JLCarnell
```

## Top Records

```ls
| business_legal_name                       | ownership_type | trade_name                       | naics_code | naics_description                                          | sic_code | sic_description                                          | license_start_date | city_state_zip     | 
| ========================================= | ============== | ================================ | ========== | ========================================================== | ======== | ======================================================== | ================== | ================== | 
| UNION PACIFIC RAILROAD COMPANY            | Corporation    | UNION PACIFIC RAILROAD COMPANY   | 482111     | Line-Haul Railroads                                        | 575      | Railroads, Line-Haul Operating                           | -836154000         | SEATTLE, WA 98108  | 
| SEA PAC SALES COMPANY                     | Corporation    | SEA-PAC SALES COMPANY            | 423220     | Home Furnishing Merchant Wholesalers                       | 645      | Home furnishings                                         | -836154000         | KENT, WA 98032     | 
| WILDERMAN REFRIGERATION CO                | Corporation    | WILDERMAN REFRIGERATION CO       | 423740     | Refrigeration Equipment and Supplies Merchant Wholesalers  | 665      | Refrigeration Equipment and Supplies                     | -836154000         | SEATTLE, WA 98109  | 
| ASSOCIATED GROCERS INC                    | Corporation    | ASSOCIATED GROCERS INC           | 424410     | General Line Grocery Merchant Wholesalers                  | 685      | Groceries, General Line                                  | -1136044800        | SEATTLE, WA 98118  | 
| CORE MARK INTL INC                        | Corporation    | CORE-MARK INTL INC               | 424490     | Other Grocery and Related Products Merchant Wholesalers    | 693      | Groceries and Related Products, Not Elsewhere Classified | -836154000         | LAKEWOOD, WA 98499 | 
| NATL ASSN OF CREDIT MANAGEMENT WESTERN WA | Corporation    | NACM WESTERN WASHINGTON & ALASKA | 561440     | Collection Agencies                                        | 850      | Adjustment and Collection Services                       | -836154000         | SEATTLE, WA 98121  | 
| WILBUR ELLIS CO                           | Corporation    | WILBUR-ELLIS CO                  | 424910     | Farm Supplies Merchant Wholesalers                         | 703      | Farm Supplies                                            | 946713600          | AUBURN, WA 98001   | 
| SAFEWAY INC                               | Corporation    | SAFEWAY INC                      | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717      | Grocery Stores                                           | -836154000         | BELLEVUE, WA 98005 | 
| SAFEWAY INC                               | Corporation    | SAFEWAY INC #1477                | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717      | Grocery Stores                                           | 968137200          | SEATTLE, WA 98107  | 
| SAFEWAY INC                               | Corporation    | SAFEWAY STORE #1062              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717      | Grocery Stores                                           | 536486400          | SEATTLE, WA 98116  | 
```