# 2012 Business License Data (Updated June 2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-business-license-data-updated-june-2013-d35fa) |
| Metadata | [Link](https://data.seattle.gov/api/views/qmtq-5rpt) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/qmtq-5rpt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/qmtq-5rpt/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | qmtq-5rpt |
| Name | 2012 Business License Data (Updated June 2013) |
| Attribution | City of Seattle Department of Finance and Administrative Services |
| Category | Finance |
| Tags | business, business license |
| Created | 2013-06-11T22:31:04Z |
| Publication Date | 2013-06-11T22:36:29Z |

## Description

Dataset contains active business license data for the City of Seattle for 2012 updated in June 2013.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | business_id         | business_id         | text          | number        |
| Yes      | series tag  | business_legal_name | business_legal_name | text          | text          |
| Yes      | series tag  | ownership           | Ownership           | text          | text          |
| Yes      | series tag  | trade_name          | trade_name          | text          | text          |
| Yes      | series tag  | naics_code          | naics_code          | text          | number        |
| Yes      | series tag  | nacisdesc           | NACISDesc           | text          | text          |
| Yes      | series tag  | sic_code_id         | sic_code_id         | text          | number        |
| Yes      | series tag  | sic_description     | SIC Description     | text          | text          |
| Yes      | time        | lic_start_date      | lic_start_date      | calendar_date | calendar_date |
| Yes      | series tag  | city_state_zip      | city_state_zip      | text          | text          |
```

## Time Field

```ls
Value = lic_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qmtq-5rpt d:2043-07-04T00:00:00.000Z t:city_state_zip="SEATTLE, WA   98108" t:nacisdesc="Line-Haul Railroads" t:business_legal_name="UNION PACIFIC RAILROAD COMPANY" t:ownership=Corporation t:sic_description="Railroads, Line-Haul Operating" t:business_id=5 t:trade_name="UNION PACIFIC RAILROAD COMPANY" t:sic_code_id=575 t:naics_code=482111 m:row_number.qmtq-5rpt=1

series e:qmtq-5rpt d:2043-07-04T00:00:00.000Z t:city_state_zip="LAKEWOOD, WA   98499" t:nacisdesc="Other Grocery and Related Products Merchant Wholesalers" t:business_legal_name="CORE MARK INTL INC" t:ownership=Corporation t:sic_description="Groceries and Related Products, Not Elsewhere Classified" t:business_id=13 t:trade_name="CORE-MARK INTL INC" t:sic_code_id=693 t:naics_code=424490 m:row_number.qmtq-5rpt=2

series e:qmtq-5rpt d:2043-07-04T00:00:00.000Z t:city_state_zip="SEATTLE, WA   98121" t:nacisdesc="Collection Agencies" t:business_legal_name="NATL ASSN OF CREDIT MANAGEMENT WESTERN WA" t:ownership=Corporation t:sic_description="Adjustment and Collection Services" t:business_id=14 t:trade_name="NACM WESTERN WASHINGTON & ALASKA" t:sic_code_id=850 t:naics_code=561440 m:row_number.qmtq-5rpt=3
```

## Meta Commands

```ls
metric m:row_number.qmtq-5rpt p:long l:"Row Number"

entity e:qmtq-5rpt l:"2012 Business License Data (Updated June 2013)" t:attribution="City of Seattle Department of Finance and Administrative Services" t:url=https://data.seattle.gov/api/views/qmtq-5rpt

property e:qmtq-5rpt t:meta.view v:id=qmtq-5rpt v:category=Finance v:averageRating=0 v:name="2012 Business License Data (Updated June 2013)" v:attribution="City of Seattle Department of Finance and Administrative Services"

property e:qmtq-5rpt t:meta.view.license v:name="Public Domain"

property e:qmtq-5rpt t:meta.view.owner v:id=n3fs-imjt v:screenName=JLCarnell v:displayName=JLCarnell

property e:qmtq-5rpt t:meta.view.tableauthor v:id=n3fs-imjt v:screenName=JLCarnell v:roleName=publisher v:displayName=JLCarnell
```

## Top Records

```ls
| business_id | business_legal_name                       | ownership   | trade_name                       | naics_code | nacisdesc                                                  | sic_code_id | sic_description                                          | lic_start_date      | city_state_zip     | 
| =========== | ========================================= | =========== | ================================ | ========== | ========================================================== | =========== | ======================================================== | =================== | ================== | 
| 5           | UNION PACIFIC RAILROAD COMPANY            | Corporation | UNION PACIFIC RAILROAD COMPANY   | 482111     | Line-Haul Railroads                                        | 575         | Railroads, Line-Haul Operating                           | 2043-07-04T00:00:00 | SEATTLE, WA 98108  | 
| 13          | CORE MARK INTL INC                        | Corporation | CORE-MARK INTL INC               | 424490     | Other Grocery and Related Products Merchant Wholesalers    | 693         | Groceries and Related Products, Not Elsewhere Classified | 2043-07-04T00:00:00 | LAKEWOOD, WA 98499 | 
| 14          | NATL ASSN OF CREDIT MANAGEMENT WESTERN WA | Corporation | NACM WESTERN WASHINGTON & ALASKA | 561440     | Collection Agencies                                        | 850         | Adjustment and Collection Services                       | 2043-07-04T00:00:00 | SEATTLE, WA 98121  | 
| 19          | WILBUR ELLIS CO                           | Corporation | WILBUR-ELLIS CO                  | 424910     | Farm Supplies Merchant Wholesalers                         | 703         | Farm Supplies                                            | 2000-01-01T00:00:00 | AUBURN, WA 98001   | 
| 21          | SAFEWAY INC                               | Corporation | SAFEWAY INC                      | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717         | Grocery Stores                                           | 2043-07-04T00:00:00 | BELLEVUE, WA 98005 | 
| 21          | SAFEWAY INC                               | Corporation | SAFEWAY INC #1477                | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717         | Grocery Stores                                           | 2000-09-05T00:00:00 | SEATTLE, WA 98107  | 
| 21          | SAFEWAY INC                               | Corporation | SAFEWAY STORE #1062              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717         | Grocery Stores                                           | 1987-01-01T00:00:00 | SEATTLE, WA 98116  | 
| 21          | SAFEWAY INC                               | Corporation | SAFEWAY STORE #1143              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717         | Grocery Stores                                           | 1995-01-01T00:00:00 | SEATTLE, WA 98117  | 
| 21          | SAFEWAY INC                               | Corporation | SAFEWAY STORE #1508              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717         | Grocery Stores                                           | 1995-01-01T00:00:00 | SEATTLE, WA 98118  | 
| 21          | SAFEWAY INC                               | Corporation | SAFEWAY STORE #1550              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 717         | Grocery Stores                                           | 1998-05-20T00:00:00 | SEATTLE, WA 98115  | 
```