# Previous Standard Product Lists

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/previous-standard-product-lists) |
| Metadata | [Link](https://data.austintexas.gov/api/views/askc-vuqf) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/askc-vuqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/askc-vuqf/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | askc-vuqf |
| Name | Previous Standard Product Lists |
| Attribution | Austin Water |
| Category | Government |
| Tags | water, standard product lists, austin water, construction, wastewater |
| Created | 2015-10-20T20:33:24Z |
| Publication Date | 2016-10-06T22:20:13Z |

## Description

Austin Water?s Standard Products List specifies acceptable manufacturer products for use in the construction of water and wastewater facilities. These products have undergone stringent testing to ensure the safety, reliability and consistency within the Austin Water system

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | standard_product_number | Standard Product Number | text          | text          |
| Yes      | series tag  | standard_product_url    | Standard Product URL    | url           | url           |
| Yes      | series tag  | product_description     | Product Description     | text          | text          |
| Yes      | time        | revision_date           | Revision Date           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = revision_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:askc-vuqf d:2012-10-01T00:00:00.000Z t:standard_product_url=http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-123_10-01-12.pdf t:standard_product_number=WW-123 t:product_description="Swing Check Valves, AWWA C508" m:row_number.askc-vuqf=1

series e:askc-vuqf d:2012-10-01T00:00:00.000Z t:standard_product_url=http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-123A_10-01-12.pdf t:standard_product_number=WW-123A t:product_description="Swing Check Valves, Air Cushioned" m:row_number.askc-vuqf=2

series e:askc-vuqf d:2012-07-01T00:00:00.000Z t:standard_product_url=http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-145A_07-01-12.pdf t:standard_product_number=WW-145A t:product_description="HDPE Meter Boxes" m:row_number.askc-vuqf=3
```

## Meta Commands

```ls
metric m:row_number.askc-vuqf p:long l:"Row Number"

entity e:askc-vuqf l:"Previous Standard Product Lists" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/askc-vuqf

property e:askc-vuqf t:meta.view v:id=askc-vuqf v:category=Government v:attributionLink=http://AustinWater.org v:averageRating=0 v:name="Previous Standard Product Lists" v:attribution="Austin Water"

property e:askc-vuqf t:meta.view.owner v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:displayName="Austin Water"

property e:askc-vuqf t:meta.view.tableauthor v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:roleName=editor v:displayName="Austin Water"
```

## Top Records

```ls
| standard_product_number | standard_product_url                                                                                      | product_description                      | revision_date       | 
| ======================= | ========================================================================================================= | ======================================== | =================== | 
| WW-123                  | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-123_10-01-12.pdf, null]  | Swing Check Valves, AWWA C508            | 2012-10-01T00:00:00 | 
| WW-123A                 | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-123A_10-01-12.pdf, null] | Swing Check Valves, Air Cushioned        | 2012-10-01T00:00:00 | 
| WW-145A                 | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-145A_07-01-12.pdf, null] | HDPE Meter Boxes                         | 2012-07-01T00:00:00 | 
| WW-146                  | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-146_07-01-12.pdf, null]  | Concrete Manhole Sections                | 2012-07-01T00:00:00 | 
| WW-146                  | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-146_01-01-15.pdf, null]  | Concrete Manhole Sections                | 2015-01-01T00:00:00 | 
| WW-146                  | [http://austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-146_04-01-16.pdf, null]      | Concrete Manhole Sections                | 2016-04-01T00:00:00 | 
| WW-146A                 | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-146A_07-01-14.pdf, null] | Manhole Seals                            | 2014-07-01T00:00:00 | 
| WW-146B                 | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-146b_07-01-11.pdf, null] | Large Diameter Cleanouts (Sampling Port) | 2011-07-01T00:00:00 | 
| WW-146B                 | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-146B_01-01-15.pdf, null] | Large Diameter Cleanouts (Sampling Port) | 2015-01-01T00:00:00 | 
| WW-146C                 | [http://www.austintexas.gov/sites/default/files/files/Water/Standard_Products/ww-146c_07-01-11.pdf, null] | Manhole Gaskets                          | 2011-07-01T00:00:00 | 
```