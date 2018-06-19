# Bond Series Sold: Beginning Fiscal Year 1999-2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bond-series-sold-beginning-fiscal-year-1999-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/kvh8-m9d4) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kvh8-m9d4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kvh8-m9d4/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kvh8-m9d4 |
| Name | Bond Series Sold: Beginning Fiscal Year 1999-2000 |
| Attribution | Dormitory Authority State of New York (DASNY) |
| Category | Economic Development |
| Tags | bond series closing date, bond series name, bond series par amount, bond series tax status, bond series rate type, true interest cost (tic) for tax exempt fixed rate bonds, initial interest rate f... |
| Created | 2014-01-08T20:38:40Z |
| Publication Date | 2016-07-22T22:02:18Z |

## Description

Report includes a list of bond series sold beginning FY 1999-2000 through the most recently completed fiscal year.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| No       |                | bond_series_closing_date | Bond Series Closing Date | calendar_date | calendar_date |
| Yes      | numeric metric | bond_series_name         | Bond Series Name         | money         | text          |
| Yes      | numeric metric | bond_series_par_amount   | Bond Series Par Amount   | money         | money         |
| Yes      | series tag     | bond_series_tax_status   | Bond Series Tax Status   | text          | text          |
| Yes      | series tag     | bond_series_rate_type    | Bond Series Rate Type    | text          | text          |
| Yes      | numeric metric | true_interest_cost       | True Interest Cost       | percent       | percent       |
| Yes      | numeric metric | initial_interest_rate    | Initial Interest Rate    | percent       | percent       |
```

## Time Field

```ls
Value = 1999
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = bond_series_closing_date
```

## Data Commands

```ls
series e:kvh8-m9d4 d:1999-01-01T00:00:00.000Z t:bond_series_tax_status=Tax-Exempt t:bond_series_rate_type=Fixed m:bond_series_name=157130000 m:true_interest_cost=5.17 m:initial_interest_rate=0

series e:kvh8-m9d4 d:1999-01-01T00:00:00.000Z t:bond_series_tax_status=Tax-Exempt t:bond_series_rate_type=Fixed m:bond_series_name=15290000 m:true_interest_cost=4.4 m:initial_interest_rate=0

series e:kvh8-m9d4 d:1999-01-01T00:00:00.000Z t:bond_series_tax_status=Tax-Exempt t:bond_series_rate_type=Fixed m:bond_series_name=51700000 m:true_interest_cost=5.18 m:initial_interest_rate=0
```

## Meta Commands

```ls
metric m:bond_series_name p:long l:"Bond Series Name" d:"The name of the bond series" t:dataTypeName=money

metric m:bond_series_par_amount p:double l:"Bond Series Par Amount" d:"Amount of the bonds issued for that particular series of bonds" t:dataTypeName=money

metric m:true_interest_cost p:float l:"True Interest Cost" d:"True interest cost (TIC) is the rate, compounded semi-annually, necessary to discount the amounts payable on the respective principal and interest payment dates to the purchase price received for the new issue of bonds." t:dataTypeName=percent

metric m:initial_interest_rate p:float l:"Initial Interest Rate" d:"The rate assigned to a new bond issue at the time of original issuance which is in effect for a limited period of time. Typically applies to auction rate, variable rate or private placement bonds." t:dataTypeName=percent

entity e:kvh8-m9d4 l:"Bond Series Sold: Beginning Fiscal Year 1999-2000" t:attribution="Dormitory Authority State of New York (DASNY)" t:url=https://data.ny.gov/api/views/kvh8-m9d4

property e:kvh8-m9d4 t:meta.view v:id=kvh8-m9d4 v:category="Economic Development" v:attributionLink=http://www.dasny.org/ v:averageRating=0 v:name="Bond Series Sold: Beginning Fiscal Year 1999-2000" v:attribution="Dormitory Authority State of New York (DASNY)"

property e:kvh8-m9d4 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kvh8-m9d4 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kvh8-m9d4 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bond_series_closing_date | bond_series_name | bond_series_par_amount | bond_series_tax_status | bond_series_rate_type | true_interest_cost | initial_interest_rate | 
| ======================== | ================ | ====================== | ====================== | ===================== | ================== | ===================== | 
|                          | $157,130,000     |                        | Tax-Exempt             | Fixed                 | 5.17               | 0.00                  | 
|                          | $15,290,000      |                        | Tax-Exempt             | Fixed                 | 4.40               | 0.00                  | 
|                          | $51,700,000      |                        | Tax-Exempt             | Fixed                 | 5.18               | 0.00                  | 
|                          | $7,940,000       |                        | Tax-Exempt             | Fixed                 | 4.97               | 0.00                  | 
|                          | $3,075,000       |                        | Tax-Exempt             | Fixed                 | 4.97               | 0.00                  | 
|                          | $11,110,000      |                        | Tax-Exempt             | Fixed                 | 4.97               | 0.00                  | 
|                          | $5,715,000       |                        | Tax-Exempt             | Fixed                 | 4.97               | 0.00                  | 
|                          | $82,075,000      |                        | Tax-Exempt             | Variable              | 4.78               | 0.00                  | 
|                          | $35,560,000      |                        | Tax-Exempt             | Variable              | 5.78               | 0.00                  | 
|                          | $42,500,000      |                        | Tax-Exempt             | Fixed                 | 5.36               | 0.00                  | 
```