# 2013 Active Business License Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-active-business-license-data) |
| Metadata | [Link](https://data.seattle.gov/api/views/d3ef-e2aq) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/d3ef-e2aq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/d3ef-e2aq/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | d3ef-e2aq |
| Name | 2013 Active Business License Data |
| Attribution | City of Seattle - Department of Finance and Administrative Services |
| Category | Finance |
| Tags | business license |
| Created | 2015-05-14T22:45:16Z |
| Publication Date | 2015-05-15T16:34:26Z |

## Description

Dataset contains active business license data for the City of Seattle for 2013.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | business_legal_name | Business Legal Name | text          | text          |
| Yes      | series tag  | ownership           | Ownership           | text          | text          |
| Yes      | series tag  | trade_name          | Trade Name          | text          | text          |
| Yes      | series tag  | naics_code          | NAICS Code          | text          | number        |
| Yes      | series tag  | description         | Description         | text          | text          |
| Yes      | time        | license_start_date  | License Start Date  | calendar_date | calendar_date |
| Yes      | series tag  | city_state_and_zip  | City, State and ZIP | text          | text          |
```

## Time Field

```ls
Value = license_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:d3ef-e2aq d:1943-07-04T00:00:00.000Z t:business_legal_name="UNION PACIFIC RAILROAD COMPANY" t:ownership=Corporation t:description="Line-Haul Railroads" t:trade_name="UNION PACIFIC RAILROAD COMPANY" t:city_state_and_zip="SEATTLE, WA 98108" t:naics_code=482111 m:row_number.d3ef-e2aq=1

series e:d3ef-e2aq d:1943-07-04T00:00:00.000Z t:business_legal_name="CORE MARK INTL INC" t:ownership=Corporation t:description="Other Grocery and Related Products Merchant Wholesalers" t:trade_name="CORE-MARK INTL INC" t:city_state_and_zip="LAKEWOOD, WA 98499" t:naics_code=424490 m:row_number.d3ef-e2aq=2

series e:d3ef-e2aq d:1943-07-04T00:00:00.000Z t:business_legal_name="NATL ASSN OF CREDIT MANAGEMENT WESTERN WA" t:ownership=Corporation t:description="Collection Agencies" t:trade_name="NACM WESTERN WASHINGTON & ALASKA" t:city_state_and_zip="SEATTLE, WA 98121" t:naics_code=561440 m:row_number.d3ef-e2aq=3
```

## Meta Commands

```ls
metric m:row_number.d3ef-e2aq p:long l:"Row Number"

entity e:d3ef-e2aq l:"2013 Active Business License Data" t:attribution="City of Seattle - Department of Finance and Administrative Services" t:url=https://data.seattle.gov/api/views/d3ef-e2aq

property e:d3ef-e2aq t:meta.view v:id=d3ef-e2aq v:category=Finance v:averageRating=0 v:name="2013 Active Business License Data" v:attribution="City of Seattle - Department of Finance and Administrative Services"

property e:d3ef-e2aq t:meta.view.owner v:id=vjep-zmv4 v:screenName="FAS - Financial Services" v:displayName="FAS - Financial Services"

property e:d3ef-e2aq t:meta.view.tableauthor v:id=vjep-zmv4 v:screenName="FAS - Financial Services" v:roleName=publisher v:displayName="FAS - Financial Services"
```

## Top Records

```ls
| business_legal_name                       | ownership   | trade_name                       | naics_code | description                                                | license_start_date  | city_state_and_zip | 
| ========================================= | =========== | ================================ | ========== | ========================================================== | =================== | ================== | 
| UNION PACIFIC RAILROAD COMPANY            | Corporation | UNION PACIFIC RAILROAD COMPANY   | 482111     | Line-Haul Railroads                                        | 1943-07-04T00:00:00 | SEATTLE, WA 98108  | 
| CORE MARK INTL INC                        | Corporation | CORE-MARK INTL INC               | 424490     | Other Grocery and Related Products Merchant Wholesalers    | 1943-07-04T00:00:00 | LAKEWOOD, WA 98499 | 
| NATL ASSN OF CREDIT MANAGEMENT WESTERN WA | Corporation | NACM WESTERN WASHINGTON & ALASKA | 561440     | Collection Agencies                                        | 1943-07-04T00:00:00 | SEATTLE, WA 98121  | 
| WILBUR ELLIS CO                           | Corporation | WILBUR-ELLIS CO                  | 424910     | Farm Supplies Merchant Wholesalers                         | 2000-01-01T00:00:00 | AUBURN, WA 98001   | 
| SAFEWAY INC                               | Corporation | SAFEWAY INC #1477                | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 2000-09-05T00:00:00 | SEATTLE, WA 98107  | 
| SAFEWAY INC                               | Corporation | SAFEWAY INC STORE 1508           | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 1995-01-01T00:00:00 | SEATTLE, WA 98118  | 
| SAFEWAY INC                               | Corporation | SAFEWAY STORE #1062              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 1987-01-01T00:00:00 | SEATTLE, WA 98116  | 
| SAFEWAY INC                               | Corporation | SAFEWAY STORE #1143              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 1995-01-01T00:00:00 | SEATTLE, WA 98117  | 
| SAFEWAY INC                               | Corporation | SAFEWAY STORE #1550              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 1998-05-20T00:00:00 | SEATTLE, WA 98115  | 
| SAFEWAY INC                               | Corporation | SAFEWAY STORE #1551              | 445110     | Supermarkets and Other Grocery (except Convenience) Stores | 1998-07-29T00:00:00 | SEATTLE, WA 98112  | 
```