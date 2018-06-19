# Real Property Transactions of Local Authorities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-transactions-of-local-authorities) |
| Metadata | [Link](https://data.ny.gov/api/views/kmkz-x3aa) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kmkz-x3aa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kmkz-x3aa/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kmkz-x3aa |
| Name | Real Property Transactions of Local Authorities |
| Attribution | Individual Local Authorities submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | public authority, local authority, real property, lease, purchase |
| Created | 2015-03-09T18:36:22Z |
| Publication Date | 2016-10-20T15:30:31Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include real property transactions data.  The dataset consists of real property transactions reported by local authorities beginning with fiscal years ending in 2011. Authorities are required to report real property transactions having an estimated fair market of more than $15,000.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| Yes      | series tag     | authority_name                      | Authority Name                      | text          | text          |
| Yes      | time           | fiscal_year_end_date                | Fiscal Year End Date                | calendar_date | calendar_date |
| Yes      | series tag     | property_transactions               | Property Transactions               | text          | text          |
| No       |                | property_address1                   | Property Address1                   | text          | text          |
| No       |                | property_address2                   | Property Address2                   | text          | text          |
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
series e:kmkz-x3aa d:2014-12-31T00:00:00.000Z t:authority_name="Albany Port District Commission" t:property_description="Vacant Lot/Undeveloped Land" t:seller_purchaser_tenant_postal_code=12144 t:property_postal_code=12144 t:fair_market_description=Appraisal t:property_state=NY t:transaction_type="DISPOSITION SALE" t:relation_with_authority=Yes t:property_city=RENSSELAER t:seller_purchaser_tenant="City of Rensselaer" t:seller_purchaser_tenant_state=NY t:seller_purchaser_tenant_city=RENSSELAER m:purchase_sale_price=45000 m:estimated_fair_market_value=45000

series e:kmkz-x3aa d:2014-12-31T00:00:00.000Z t:authority_name="Albany Port District Commission" t:property_description="Vacant Lot/Undeveloped Land" t:seller_purchaser_tenant_postal_code=12205 t:property_postal_code=12202 t:fair_market_description=Appraisal t:property_state=NY t:transaction_type="DISPOSITION SALE" t:relation_with_authority=No t:property_city=ALBANY t:seller_purchaser_tenant="Joseph Martin" t:seller_purchaser_tenant_state=NY t:seller_purchaser_tenant_city=ALBANY m:purchase_sale_price=170000 m:estimated_fair_market_value=170000

series e:kmkz-x3aa d:2011-12-31T00:00:00.000Z t:authority_name="Albany Port District Commission" t:property_description="Commercial Building" t:seller_purchaser_tenant_postal_code=60555 t:property_postal_code=12202 t:fair_market_description=Appraisal t:property_state=NY t:transaction_type="DISPOSITION LEASE" t:relation_with_authority=No t:property_city=ALBANY t:seller_purchaser_tenant="Durham School Services, LP" t:seller_purchaser_tenant_state=IL t:seller_purchaser_tenant_city=WARRENVILLE m:purchase_sale_price=184424.52 m:lease_period=60 m:lease_rate=0.7 m:estimated_fair_market_value=184424.52 m:market_rate=0.7
```

## Meta Commands

```ls
metric m:estimated_fair_market_value p:double l:"Estimated Fair Market Value" d:"Estimated fair market value of the transacted property." t:dataTypeName=money

metric m:purchase_sale_price p:double l:"Purchase Sale Price" d:"Price for which the property was transacted (purchased or sold). This field is blank if it doesn't apply or if the authority didn't enter any information." t:dataTypeName=money

metric m:market_rate p:double l:"Market Rate" d:"Market rate ($ per square foot) of the transacted property. This field is blank if it doesn't apply or if the authority didn?t enter any information." t:dataTypeName=money

metric m:lease_rate p:double l:"Lease Rate" d:"Lease rate ($ per square foot) of the transacted property. This field is blank if it doesn't apply or if the authority didn?t enter any information." t:dataTypeName=money

metric m:lease_period p:integer l:"Lease Period" d:"Duration (months) of the lease of the transacted property. This field is blank if it doesn't apply or if the authority didn?t enter any information." t:dataTypeName=number

entity e:kmkz-x3aa l:"Real Property Transactions of Local Authorities" t:attribution="Individual Local Authorities submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/kmkz-x3aa

property e:kmkz-x3aa t:meta.view v:id=kmkz-x3aa v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Real Property Transactions of Local Authorities" v:attribution="Individual Local Authorities submitted to Authorities Budget Office"

property e:kmkz-x3aa t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kmkz-x3aa t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kmkz-x3aa t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                           | fiscal_year_end_date | property_transactions | property_address1 | property_address2 | property_city | property_state | property_postal_code | property_description | estimated_fair_market_value | fair_market_description | transaction_type | transaction_type_other | transaction_date | purchase_sale_price | market_rate | lease_rate | lease_period | seller_purchaser_tenant | relation_with_authority | seller_purchaser_tenant_city | seller_purchaser_tenant_state | seller_purchaser_tenant_postal_code | 
| ======================================================== | ==================== | ===================== | ================= | ================= | ============= | ============== | ==================== | ==================== | =========================== | ======================= | ================ | ====================== | ================ | =================== | =========== | ========== | ============ | ======================= | ======================= | ============================ | ============================= | =================================== | 
| Albany Parking Authority                                 | 2014-12-31T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| Albany Parking Authority                                 | 2015-12-31T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| Albany Parking Authority                                 | 2011-12-31T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| Albany Parking Authority                                 | 2012-12-31T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| Albany Parking Authority                                 | 2013-12-31T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| American Museum of Natural History Planetarium Authority | 2013-06-30T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| American Museum of Natural History Planetarium Authority | 2014-06-30T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| American Museum of Natural History Planetarium Authority | 2015-06-30T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| American Museum of Natural History Planetarium Authority | 2011-06-30T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
| American Museum of Natural History Planetarium Authority | 2012-06-30T00:00:00  | No                    |                   |                   |               |                |                      |                      |                             |                         |                  |                        |                  |                     |             |            |              |                         |                         |                              |                               |                                     | 
```