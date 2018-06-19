# State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-new-york-mortgage-agency-sonyma-loans-purchased-beginning-2004) |
| Metadata | [Link](https://data.ny.gov/api/views/22ew-dxez) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/22ew-dxez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/22ew-dxez/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 22ew-dxez |
| Name | State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004 |
| Attribution | New York State Homes & Community Renewal |
| Category | Economic Development |
| Tags | sonyma, loans, mortgage, assistance, lmi, first-time, homebuyer, buying, home, homeowner, homeownership, rent, rental assistance |
| Created | 2013-12-23T14:58:47Z |
| Publication Date | 2016-07-21T20:16:31Z |

## Description

Financial and Geographic Information on SONYMA Loans purchased since 2004.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | bond_series             | Bond Series             | text          | text          |
| Yes      | numeric metric | original_loan_amount    | Original Loan Amount    | money         | money         |
| Yes      | time           | loan_purchase_date      | Loan Purchase Date      | calendar_date | calendar_date |
| No       |                | purchase_year           | Purchase Year           | number        | text          |
| Yes      | numeric metric | original_ltv            | Original Loan To Value  | percent       | percent       |
| Yes      | series tag     | loan_type               | Loan Type               | text          | text          |
| Yes      | numeric metric | sonyma_dpal_ccal_amount | SONYMA DPAL/CCAL Amount | money         | money         |
| Yes      | numeric metric | original_term           | Original Term           | number        | number        |
| Yes      | series tag     | county                  | County                  | text          | text          |
| Yes      | series tag     | fips_code               | FIPS Code               | text          | text          |
| Yes      | series tag     | of_units                | Number of Units         | text          | text          |
| Yes      | series tag     | property_type           | Property Type           | text          | text          |
| Yes      | series tag     | housing_type            | Housing Type            | text          | text          |
| Yes      | numeric metric | household_size          | Household Size          | number        | number        |
```

## Time Field

```ls
Value = loan_purchase_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = purchase_year
```

## Data Commands

```ls
series e:22ew-dxez d:2004-01-02T00:00:00.000Z t:loan_type=Conventional t:property_type=Detached t:bond_series="Series 109/110" t:county=Monroe t:fips_code=36055 t:of_units="1 Family" t:housing_type=Existing m:sonyma_dpal_ccal_amount=2933 m:original_loan_amount=32470 m:household_size=1 m:original_term=360 m:original_ltv=97

series e:22ew-dxez d:2004-01-02T00:00:00.000Z t:loan_type=Conventional t:property_type=Detached t:bond_series="Series 109/110" t:county=Genesee t:fips_code=36037 t:of_units="1 Family" t:housing_type=Existing m:sonyma_dpal_ccal_amount=3435 m:original_loan_amount=48500 m:household_size=4 m:original_term=360 m:original_ltv=97

series e:22ew-dxez d:2004-01-02T00:00:00.000Z t:loan_type=Conventional t:property_type=Detached t:bond_series="Series 109/110" t:county=Monroe t:fips_code=36055 t:of_units="1 Family" t:housing_type=Existing m:sonyma_dpal_ccal_amount=4996 m:original_loan_amount=49470 m:household_size=3 m:original_term=360 m:original_ltv=97
```

## Meta Commands

```ls
metric m:original_loan_amount p:integer l:"Original Loan Amount" d:"The original amount of mortgage provided to the homebuyer." t:dataTypeName=money

metric m:original_ltv p:double l:"Original Loan To Value" d:"The original loan amount divided by the lower of the original home sales price or the original appraised value." t:dataTypeName=percent

metric m:sonyma_dpal_ccal_amount p:integer l:"SONYMA DPAL/CCAL Amount" d:"The amount of down payment assistance (DPAL) or closing cost assistance (CCAL) provided to the homebuyer." t:dataTypeName=money

metric m:original_term p:integer l:"Original Term" d:"The loan term in months." t:dataTypeName=number

metric m:household_size p:integer l:"Household Size" d:"The number of persons living in the household at origination." t:dataTypeName=number

entity e:22ew-dxez l:"State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004" t:attribution="New York State Homes & Community Renewal" t:url=https://data.ny.gov/api/views/22ew-dxez

property e:22ew-dxez t:meta.view v:id=22ew-dxez v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/HomeOwnership-HomeBuyers.htm v:averageRating=0 v:name="State of New York Mortgage Agency (SONYMA) Loans Purchased: Beginning 2004" v:attribution="New York State Homes & Community Renewal"

property e:22ew-dxez t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:22ew-dxez t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:22ew-dxez t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bond_series    | original_loan_amount | loan_purchase_date  | purchase_year | original_ltv | loan_type    | sonyma_dpal_ccal_amount | original_term | county      | fips_code | of_units | property_type | housing_type | household_size | 
| ============== | ==================== | =================== | ============= | ============ | ============ | ======================= | ============= | =========== | ========= | ======== | ============= | ============ | ============== | 
| Series 109/110 | 32470                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 2933                    | 360           | Monroe      | 36055     | 1 Family | Detached      | Existing     | 1              | 
| Series 109/110 | 48500                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 3435                    | 360           | Genesee     | 36037     | 1 Family | Detached      | Existing     | 4              | 
| Series 109/110 | 49470                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 4996                    | 360           | Monroe      | 36055     | 1 Family | Detached      | Existing     | 3              | 
| Series 109/110 | 58200                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 4170                    | 360           | Erie        | 36029     | 1 Family | Detached      | Existing     | 2              | 
| Series 109/110 | 64990                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 4940                    | 360           | Erie        | 36029     | 1 Family | Detached      | Existing     | 3              | 
| Series 109/110 | 64990                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 4772                    | 360           | Schenectady | 36093     | 1 Family | Detached      | Existing     | 1              | 
| Series 109/110 | 67900                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 5000                    | 360           | Orleans     | 36073     | 1 Family | Detached      | Existing     | 3              | 
| Series 109/110 | 67900                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 4845                    | 360           | Wayne       | 36117     | 1 Family | Detached      | Existing     | 2              | 
| Series 109/110 | 72775                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 5000                    | 360           | Monroe      | 36055     | 1 Family | Detached      | Existing     | 2              | 
| Series 109/110 | 77115                | 2004-01-02T00:00:00 | 2004          | 97           | Conventional | 5000                    | 360           | Broome      | 36007     | 1 Family | Detached      | Existing     | 2              | 
```