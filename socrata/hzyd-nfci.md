# 2015 Active Business License Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-active-business-license-data) |
| Metadata | [Link](https://data.seattle.gov/api/views/hzyd-nfci) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/hzyd-nfci/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/hzyd-nfci/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | hzyd-nfci |
| Name | 2015 Active Business License Data |
| Attribution | Finance and Administrative Services |
| Category | Finance |
| Tags | license, business license |
| Created | 2016-07-01T22:49:25Z |
| Publication Date | 2016-07-01T22:57:56Z |

## Description

Dataset contains active business license data for the City of Seattle for 2015

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
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hzyd-nfci d:2015-01-01T00:00:00.000Z t:license_start_date=04-Jul-43 t:city_state_zip="SEATTLE, WA 98108" t:ownership_type=Corporation t:business_legal_name="UNION PACIFIC RAILROAD COMPANY" t:naics_description="Line-Haul Railroads" t:trade_name="UNION PACIFIC RAILROAD COMPANY" t:naics_code=482111 m:row_number.hzyd-nfci=1

series e:hzyd-nfci d:2015-01-01T00:00:00.000Z t:license_start_date=04-Jul-43 t:city_state_zip="LAKEWOOD, WA 98499" t:ownership_type=Corporation t:business_legal_name="CORE MARK INTL INC" t:naics_description="Other Grocery and Related Products Merchant Wholesalers" t:trade_name="CORE-MARK INTL INC" t:naics_code=424490 m:row_number.hzyd-nfci=2

series e:hzyd-nfci d:2015-01-01T00:00:00.000Z t:license_start_date=04-Jul-43 t:city_state_zip="SEATTLE, WA 98134" t:ownership_type=Corporation t:business_legal_name="NATL ASSN OF CREDIT MANAGEMENT WESTERN WA" t:naics_description="Collection Agencies" t:trade_name="NACM WESTERN WASHINGTON & ALASKA" t:naics_code=561440 m:row_number.hzyd-nfci=3
```

## Meta Commands

```ls
metric m:row_number.hzyd-nfci p:long l:"Row Number"

entity e:hzyd-nfci l:"2015 Active Business License Data" t:attribution="Finance and Administrative Services" t:url=https://data.seattle.gov/api/views/hzyd-nfci

property e:hzyd-nfci t:meta.view v:id=hzyd-nfci v:category=Finance v:attributionLink=http://www.seattle.gov/fas/ v:averageRating=0 v:name="2015 Active Business License Data" v:attribution="Finance and Administrative Services"

property e:hzyd-nfci t:meta.view.owner v:id=vjep-zmv4 v:screenName="FAS - Financial Services" v:displayName="FAS - Financial Services"

property e:hzyd-nfci t:meta.view.tableauthor v:id=vjep-zmv4 v:screenName="FAS - Financial Services" v:roleName=publisher v:displayName="FAS - Financial Services"
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
| SAFEWAY INC                               | Corporation    | SAFEWAY STORE #1993              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 27-Oct-04          | SEATTLE, WA 98112  | 
| SAFEWAY INC                               | Corporation    | SAFEWAY STORE #1550              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 20-May-98          | SEATTLE, WA 98115  | 
| SAFEWAY INC                               | Corporation    | SAFEWAY INC #1477                | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 05-Sep-00          | SEATTLE, WA 98107  | 
| SAFEWAY INC                               | Corporation    | SAFEWAY STORE #219               | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 01-Jan-87          | SEATTLE, WA 98118  | 
```