# Real Property Transactions of State Authorities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-transactions-of-state-authorities) |
| Metadata | [Link](https://data.ny.gov/api/views/t7uh-5ac8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/t7uh-5ac8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/t7uh-5ac8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | t7uh-5ac8 |
| Name | Real Property Transactions of State Authorities |
| Attribution | Individual State Authorities submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | public authority, state authority, real property, lease, purchase |
| Created | 2015-03-09T17:47:45Z |
| Publication Date | 2016-10-20T15:30:30Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include real property transactions data.  The dataset consists of real property transactions reported by State Authorities beginning with fiscal years ending in 2011. Authorities are required to report real property transactions having an estimated fair market of more than $15,000.

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
series e:t7uh-5ac8 d:2014-10-31T00:00:00.000Z t:authority_name="Battery Park City Authority" t:property_description="Commercial Building" t:seller_purchaser_tenant_postal_code=10012 t:property_postal_code=10004 t:fair_market_description=Other t:property_state=NY t:transaction_type="DISPOSITION LEASE" t:relation_with_authority=No t:property_city="NEW YORK" t:seller_purchaser_tenant="Gigino at Wagner Park LLC c/o Giraldi Suarez Productions" t:seller_purchaser_tenant_state=NY t:seller_purchaser_tenant_city="NEW YORK" m:lease_period=24 m:lease_rate=27 m:estimated_fair_market_value=123669 m:market_rate=39

series e:t7uh-5ac8 d:2015-10-31T00:00:00.000Z t:authority_name="Battery Park City Authority" t:property_description="Commercial Building" t:transaction_type=ACQUISITION t:property_state=NY t:property_city="NEW YORK" t:seller_purchaser_tenant_city="NEW YORK" t:property_postal_code=10280 t:seller_purchaser_tenant_postal_code=10280 t:fair_market_description=Other t:relation_with_authority=No t:transaction_type_other="Market comparissons" t:seller_purchaser_tenant="Regatta Property LLC" t:seller_purchaser_tenant_state=NY m:purchase_sale_price=519400 m:lease_period=12 m:lease_rate=0.01 m:estimated_fair_market_value=519400

series e:t7uh-5ac8 d:2015-10-31T00:00:00.000Z t:authority_name="Battery Park City Authority" t:property_description="Commercial Building" t:seller_purchaser_tenant_postal_code=10281 t:property_postal_code=10281 t:fair_market_description=Appraisal t:property_state=NY t:transaction_type="DISPOSITION LEASE PURCHASE" t:relation_with_authority=No t:property_city="NEW YORK" t:seller_purchaser_tenant="BOP North Cove Marina LLC" t:seller_purchaser_tenant_state=NY t:seller_purchaser_tenant_city="NEW YORK" m:estimated_fair_market_value=450000
```

## Meta Commands

```ls
metric m:estimated_fair_market_value p:double l:"Estimated Fair Market Value" d:"Estimated fair market value of the transacted property." t:dataTypeName=money

metric m:purchase_sale_price p:double l:"Purchase Sale Price" d:"Price for which the property was transacted (purchased or sold). This field is blank if it doesn't apply or if the authority didn't enter any information." t:dataTypeName=money

metric m:market_rate p:double l:"Market Rate" d:"Market rate ($ per square foot) of the transacted property. This field is blank if it doesn't apply or if the authority didn?t enter any information." t:dataTypeName=money

metric m:lease_rate p:double l:"Lease Rate" d:"Lease rate ($ per square foot) of the transacted property. This field is blank if it doesn't apply or if the authority didn?t enter any information." t:dataTypeName=money

metric m:lease_period p:integer l:"Lease Period" d:"Duration (months) of the lease of the transacted property. This field is blank if it doesn't apply or if the authority didn?t enter any information." t:dataTypeName=number

entity e:t7uh-5ac8 l:"Real Property Transactions of State Authorities" t:attribution="Individual State Authorities submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/t7uh-5ac8

property e:t7uh-5ac8 t:meta.view v:id=t7uh-5ac8 v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Real Property Transactions of State Authorities" v:attribution="Individual State Authorities submitted to Authorities Budget Office"

property e:t7uh-5ac8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:t7uh-5ac8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:t7uh-5ac8 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                                 | fiscal_year_end_date | property_transactions | property_address1   | property_address2 | property_city | property_state | property_postal_code | property_description | estimated_fair_market_value | fair_market_description | transaction_type           | transaction_type_other | transaction_date    | purchase_sale_price | market_rate | lease_rate | lease_period | seller_purchaser_tenant                                  | relation_with_authority | seller_purchaser_tenant_city | seller_purchaser_tenant_state | seller_purchaser_tenant_postal_code | 
| ============================================================== | ==================== | ===================== | =================== | ================= | ============= | ============== | ==================== | ==================== | =========================== | ======================= | ========================== | ====================== | =================== | =================== | =========== | ========== | ============ | ======================================================== | ======================= | ============================ | ============================= | =================================== | 
| Agriculture and New York State Horse Breeding Development Fund | 2014-12-31T00:00:00  | No                    |                     |                   |               |                |                      |                      |                             |                         |                            |                        |                     |                     |             |            |              |                                                          |                         |                              |                               |                                     | 
| Agriculture and New York State Horse Breeding Development Fund | 2011-12-31T00:00:00  | No                    |                     |                   |               |                |                      |                      |                             |                         |                            |                        |                     |                     |             |            |              |                                                          |                         |                              |                               |                                     | 
| Agriculture and New York State Horse Breeding Development Fund | 2015-12-31T00:00:00  | No                    |                     |                   |               |                |                      |                      |                             |                         |                            |                        |                     |                     |             |            |              |                                                          |                         |                              |                               |                                     | 
| Agriculture and New York State Horse Breeding Development Fund | 2012-12-31T00:00:00  | No                    |                     |                   |               |                |                      |                      |                             |                         |                            |                        |                     |                     |             |            |              |                                                          |                         |                              |                               |                                     | 
| Agriculture and New York State Horse Breeding Development Fund | 2013-12-31T00:00:00  | No                    |                     |                   |               |                |                      |                      |                             |                         |                            |                        |                     |                     |             |            |              |                                                          |                         |                              |                               |                                     | 
| Battery Park City Authority                                    | 2014-10-31T00:00:00  |                       | 20 Battery Place    |                   | NEW YORK      | NY             | 10004                | Commercial Building  | 123669.00                   | Other                   | DISPOSITION LEASE          |                        | 2014-01-01T00:00:00 |                     | 39.00       | 27.00      | 24           | Gigino at Wagner Park LLC c/o Giraldi Suarez Productions | No                      | NEW YORK                     | NY                            | 10012                               | 
| Battery Park City Authority                                    | 2011-10-31T00:00:00  | No                    |                     |                   |               |                |                      |                      |                             |                         |                            |                        |                     |                     |             |            |              |                                                          |                         |                              |                               |                                     | 
| Battery Park City Authority                                    | 2015-10-31T00:00:00  |                       | 21 South End Avenue |                   | NEW YORK      | NY             | 10280                | Commercial Building  | 519400.00                   | Other                   | ACQUISITION                | Market comparissons    | 2015-01-01T00:00:00 | 519400.00           |             | 0.01       | 12           | Regatta Property LLC                                     | No                      | NEW YORK                     | NY                            | 10280                               | 
| Battery Park City Authority                                    | 2015-10-31T00:00:00  |                       | North Cove Marina   |                   | NEW YORK      | NY             | 10281                | Commercial Building  | 450000.00                   | Appraisal               | DISPOSITION LEASE PURCHASE |                        | 2016-05-06T00:00:00 |                     |             |            |              | BOP North Cove Marina LLC                                | No                      | NEW YORK                     | NY                            | 10281                               | 
| Battery Park City Authority                                    | 2012-10-31T00:00:00  | No                    |                     |                   |               |                |                      |                      |                             |                         |                            |                        |                     |                     |             |            |              |                                                          |                         |                              |                               |                                     | 
```