# Real Property Transactions of Industrial Development Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-transactions-of-industrial-development-agencies) |
| Metadata | [Link](https://data.ny.gov/api/views/dixy-n3q7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dixy-n3q7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dixy-n3q7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dixy-n3q7 |
| Name | Real Property Transactions of Industrial Development Agencies |
| Attribution | Individual Industrial Development Agencies submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | public authority, industrial development agency, real property, lease, purchase |
| Created | 2015-03-10T17:50:55Z |
| Publication Date | 2016-10-20T15:30:27Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include real property transactions data.  The dataset consists real property transactions reported by Industrial Development Agencies beginning with fiscal years ending in 2011. Authorities are required to report real property transactions having an estimated fair market of more than $15,000.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| Yes      | series tag     | authority_name                      | Authority Name                      | text          | text          |
| Yes      | time           | fiscal_year_end_date                | Fiscal Year End Date                | calendar_date | calendar_date |
| Yes      | series tag     | property_transactions               | Property Transactions               | text          | text          |
| No       |                | property_address1                   | Property Address 1                  | text          | text          |
| No       |                | property_address2                   | Property Address 2                  | text          | text          |
| Yes      | series tag     | property_city                       | Property City                       | text          | text          |
| Yes      | series tag     | property_state                      | Property State                      | text          | text          |
| Yes      | series tag     | property_postal_code                | Property Postal Code                | text          | text          |
| Yes      | series tag     | property_description                | Property Description                | text          | text          |
| Yes      | numeric metric | estimated_fair_market_value         | Estimated Fair Market Value         | money         | money         |
| Yes      | series tag     | fair_market_description             | Fair Market Description             | text          | text          |
| Yes      | series tag     | transaction_type                    | Transaction Type                    | text          | text          |
| Yes      | series tag     | transaction_type_other              | Transaction Type Other              | text          | text          |
| No       |                | transaction_date                    | Transaction Date                    | calendar_date | calendar_date |
| Yes      | numeric metric | purchase_sale_price                 | Purchase Sale Price                 | money         | money         |
| Yes      | numeric metric | market_rate                         | Market Rate                         | money         | money         |
| Yes      | numeric metric | lease_rate                          | Lease Rate                          | money         | money         |
| Yes      | numeric metric | lease_period                        | Lease Period                        | number        | number        |
| Yes      | series tag     | seller_purchaser_tenant             | Seller/Purchaser/Tenant             | text          | text          |
| Yes      | series tag     | relation_with_authority             | Relation With Authority             | text          | text          |
| Yes      | series tag     | seller_purchaser_tenant_city        | Seller/Purchaser/Tenant City        | text          | text          |
| Yes      | series tag     | seller_purchaser_tenant_state       | Seller/Purchaser/Tenant State       | text          | text          |
| Yes      | series tag     | seller_purchaser_tenant_postal_code | Seller/Purchaser/Tenant Postal Code | text          | text          |
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = property_address1,property_address2,transaction_date
```

## Data Commands

```ls
series e:dixy-n3q7 d:2015-12-31T00:00:00.000Z t:authority_name="Allegany Industrial Development Agency" t:property_description="Vacant Lot/Undeveloped Land" t:seller_purchaser_tenant_postal_code=14813 t:property_postal_code=14813 t:fair_market_description=Other t:property_state=NY t:transaction_type=ACQUISITION t:relation_with_authority=No t:property_city=BELMONT t:seller_purchaser_tenant="Gerald W. and Paula M. Van Dyke, Jr." t:seller_purchaser_tenant_state=NY t:seller_purchaser_tenant_city=BELMONT m:purchase_sale_price=286000 m:estimated_fair_market_value=286000

series e:dixy-n3q7 d:2015-12-31T00:00:00.000Z t:authority_name="Allegany Industrial Development Agency" t:property_description="Vacant Lot/Undeveloped Land" t:transaction_type="DISPOSITION OTHER" t:property_state=NY t:property_city=BELMONT t:seller_purchaser_tenant_city=BELMONT t:property_postal_code=14813 t:seller_purchaser_tenant_postal_code=14813 t:fair_market_description=Other t:relation_with_authority=No t:transaction_type_other="New Build Office Bldg on adjacent vacant land owned by ACIDA" t:seller_purchaser_tenant="Allegany County Industrial Development Agency" t:seller_purchaser_tenant_state=NY m:purchase_sale_price=762000 m:estimated_fair_market_value=800000

series e:dixy-n3q7 d:2015-12-31T00:00:00.000Z t:authority_name="Allegany Industrial Development Agency" t:property_description="Office Building" t:seller_purchaser_tenant_postal_code=14744 t:property_postal_code=14813 t:fair_market_description=Appraisal t:property_state=NY t:transaction_type=ACQUISITION t:relation_with_authority=No t:property_city=BELMONT t:seller_purchaser_tenant="Willard J. Houghton Foundation" t:seller_purchaser_tenant_state=NY t:seller_purchaser_tenant_city=HOUGHTON m:purchase_sale_price=400000 m:estimated_fair_market_value=700000
```

## Meta Commands

```ls
metric m:estimated_fair_market_value p:double l:"Estimated Fair Market Value" d:"Estimated fair market value of the transacted property." t:dataTypeName=money

metric m:purchase_sale_price p:double l:"Purchase Sale Price" d:"Price for which the property was transacted (purchased or sold). This field is blank if it doesn't apply or if the authority didn't enter any information." t:dataTypeName=money

metric m:market_rate p:double l:"Market Rate" d:"Market rate ($ per square foot) of the transacted property. This field is blank if it doesn't apply or if the authority didn?t enter any information." t:dataTypeName=money

metric m:lease_rate p:double l:"Lease Rate" d:"Lease rate ($ per square foot) of the transacted property. This field is blank if it doesn't apply or if the authority didn?t enter any information." t:dataTypeName=money

metric m:lease_period p:integer l:"Lease Period" d:"Duration (months) of the lease of the transacted property. This field is blank if it doesn't apply or if the authority didn't enter any information." t:dataTypeName=number

entity e:dixy-n3q7 l:"Real Property Transactions of Industrial Development Agencies" t:attribution="Individual Industrial Development Agencies submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/dixy-n3q7

property e:dixy-n3q7 t:meta.view v:id=dixy-n3q7 v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Real Property Transactions of Industrial Development Agencies" v:attribution="Individual Industrial Development Agencies submitted to Authorities Budget Office"

property e:dixy-n3q7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dixy-n3q7 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dixy-n3q7 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                         | fiscal_year_end_date | property_transactions | property_address1    | property_address2 | property_city | property_state | property_postal_code | property_description        | estimated_fair_market_value | fair_market_description | transaction_type  | transaction_type_other                                       | transaction_date    | purchase_sale_price | market_rate | lease_rate | lease_period | seller_purchaser_tenant                       | relation_with_authority | seller_purchaser_tenant_city | seller_purchaser_tenant_state | seller_purchaser_tenant_postal_code | 
| ====================================== | ==================== | ===================== | ==================== | ================= | ============= | ============== | ==================== | =========================== | =========================== | ======================= | ================= | ============================================================ | =================== | =================== | =========== | ========== | ============ | ============================================= | ======================= | ============================ | ============================= | =================================== | 
| Allegany Industrial Development Agency | 2014-12-31T00:00:00  | No                    |                      |                   |               |                |                      |                             |                             |                         |                   |                                                              |                     |                     |             |            |              |                                               |                         |                              |                               |                                     | 
| Allegany Industrial Development Agency | 2015-12-31T00:00:00  |                       | 5884 County Road 20  |                   | BELMONT       | NY             | 14813                | Vacant Lot/Undeveloped Land | 286000.00                   | Other                   | ACQUISITION       |                                                              | 2012-03-09T00:00:00 | 286000.00           |             |            |              | Gerald W. and Paula M. Van Dyke, Jr.          | No                      | BELMONT                      | NY                            | 14813                               | 
| Allegany Industrial Development Agency | 2015-12-31T00:00:00  |                       | 6085 State Route 19N |                   | BELMONT       | NY             | 14813                | Vacant Lot/Undeveloped Land | 800000.00                   | Other                   | DISPOSITION OTHER | New Build Office Bldg on adjacent vacant land owned by ACIDA | 2010-12-21T00:00:00 | 762000.00           |             |            |              | Allegany County Industrial Development Agency | No                      | BELMONT                      | NY                            | 14813                               | 
| Allegany Industrial Development Agency | 2015-12-31T00:00:00  |                       | 6087 State Route 19N |                   | BELMONT       | NY             | 14813                | Office Building             | 700000.00                   | Appraisal               | ACQUISITION       |                                                              | 2008-08-14T00:00:00 | 400000.00           |             |            |              | Willard J. Houghton Foundation                | No                      | HOUGHTON                     | NY                            | 14744                               | 
| Allegany Industrial Development Agency | 2015-12-31T00:00:00  |                       | 5744 Friendship Road |                   | BELMONT       | NY             | 14813                | Mixed Use                   | 400000.00                   | Other                   | ACQUISITION       |                                                              | 2015-08-13T00:00:00 | 399000.00           |             |            |              | Thunder Road, LLC                             | No                      | OLEAN                        | NY                            | 14760                               | 
| Allegany Industrial Development Agency | 2011-12-31T00:00:00  | No                    |                      |                   |               |                |                      |                             |                             |                         |                   |                                                              |                     |                     |             |            |              |                                               |                         |                              |                               |                                     | 
| Allegany Industrial Development Agency | 2012-12-31T00:00:00  |                       | 5884 County Road 20  |                   | BELMONT       | NY             | 14813                | Vacant Lot/Undeveloped Land | 286000.00                   | Other                   | ACQUISITION       |                                                              | 2012-03-09T00:00:00 | 286000.00           |             |            |              | Gerald W and Paula M Van Dyke                 | No                      | BELMONT                      | NY                            | 14813                               | 
| Allegany Industrial Development Agency | 2013-12-31T00:00:00  | No                    |                      |                   |               |                |                      |                             |                             |                         |                   |                                                              |                     |                     |             |            |              |                                               |                         |                              |                               |                                     | 
| Amherst Industrial Development Agency  | 2014-12-31T00:00:00  | No                    |                      |                   |               |                |                      |                             |                             |                         |                   |                                                              |                     |                     |             |            |              |                                               |                         |                              |                               |                                     | 
| Amherst Industrial Development Agency  | 2015-12-31T00:00:00  | No                    |                      |                   |               |                |                      |                             |                             |                         |                   |                                                              |                     |                     |             |            |              |                                               |                         |                              |                               |                                     | 
```