# State Liquor Authority (SLA) Brand Label and Wholesaler Information for Alcoholic Beverage Products Registered in New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-liquor-authority-sla-brand-label-and-wholesaler-information-for-alcoholic-beverage-p) |
| Metadata | [Link](https://data.ny.gov/api/views/n2dz-pwuk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/n2dz-pwuk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/n2dz-pwuk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | n2dz-pwuk |
| Name | State Liquor Authority (SLA) Brand Label and Wholesaler Information for Alcoholic Beverage Products Registered in New York State |
| Attribution | NYSLA Wholesale Bureau / NYSITS |
| Category | Economic Development |
| Tags | alcohol, labeling, wholesalers, registered brands, whiskey, beer, liquor, cordials, rum |
| Created | 2014-01-27T21:29:39Z |
| Publication Date | 2017-04-19T22:17:12Z |

## Description

Brand Label and Wholesale Information for Alcohol Products Registered in NYS.The New York State Alcohol Beverage Control Law specifies that no manufacturer or wholesaler shall sell to any retailer nor shall any retailer purchase any alcoholic beverages unless these beverages are labeled in accordance with the Authority's Rules and Federal Regulations and unless such label shall be registered with and approved by the State Liquor Authority. Effective January 1, 1994, wine does not need to be brand label registered if the wine has received label approval from the Bureau of Alcohol, Tobacco and Firearms (BATF).

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | =========== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag  | brand_label_serial_number        | Brand Label Serial Number        | text          | text          |
| Yes      | series tag  | brand_label_name                 | Brand Label Name                 | text          | text          |
| Yes      | series tag  | license_class_code               | License Type Code                | text          | text          |
| Yes      | series tag  | license_type_code                | License Class Code               | text          | text          |
| Yes      | series tag  | license_class_description        | License Class Description        | text          | text          |
| Yes      | series tag  | product_description              | Product Description              | text          | text          |
| Yes      | series tag  | wholesaler_license_serial_number | Wholesaler License Serial Number | text          | text          |
| Yes      | series tag  | wholesaler_name                  | Wholesaler Name                  | text          | text          |
| Yes      | series tag  | domestic_d_or_imported_i         | Domestic (D) or Imported (I)     | text          | text          |
| Yes      | time        | brand_label_expiration_date      | Brand Label Expiration Date      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = brand_label_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:n2dz-pwuk d:2017-06-30T00:00:00.000Z t:brand_label_serial_number=5002370 t:wholesaler_name="MATT BREWING CO INC" t:wholesaler_license_serial_number=2503534 t:license_class_code=650 t:brand_label_name="SARANAC PALE ALE" t:license_type_code=1 t:domestic_d_or_imported_i=D t:product_description=ALE t:license_class_description=ALE m:row_number.n2dz-pwuk=1

series e:n2dz-pwuk d:2017-06-30T00:00:00.000Z t:brand_label_serial_number=5002383 t:wholesaler_name="MATT BREWING CO INC" t:wholesaler_license_serial_number=2503534 t:license_class_code=650 t:brand_label_name="UTICA CLUB LIGHT" t:license_type_code=2 t:domestic_d_or_imported_i=D t:product_description=BEER t:license_class_description="BEER & LAGER" m:row_number.n2dz-pwuk=2

series e:n2dz-pwuk d:2017-06-30T00:00:00.000Z t:brand_label_serial_number=5002384 t:wholesaler_name="MATT BREWING CO INC" t:wholesaler_license_serial_number=2503534 t:license_class_code=650 t:brand_label_name="UTICA CLUB" t:license_type_code=2 t:domestic_d_or_imported_i=D t:product_description=BEER t:license_class_description="BEER & LAGER" m:row_number.n2dz-pwuk=3
```

## Meta Commands

```ls
metric m:row_number.n2dz-pwuk p:long l:"Row Number"

entity e:n2dz-pwuk l:"State Liquor Authority (SLA) Brand Label and Wholesaler Information for Alcoholic Beverage Products Registered in New York State" t:attribution="NYSLA Wholesale Bureau / NYSITS" t:url=https://data.ny.gov/api/views/n2dz-pwuk

property e:n2dz-pwuk t:meta.view v:id=n2dz-pwuk v:category="Economic Development" v:attributionLink=http://www.sla.ny.gov/wholesale v:averageRating=0 v:name="State Liquor Authority (SLA) Brand Label and Wholesaler Information for Alcoholic Beverage Products Registered in New York State" v:attribution="NYSLA Wholesale Bureau / NYSITS"

property e:n2dz-pwuk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:n2dz-pwuk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:n2dz-pwuk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| brand_label_serial_number | brand_label_name                      | license_class_code | license_type_code | license_class_description | product_description | wholesaler_license_serial_number | wholesaler_name              | domestic_d_or_imported_i | brand_label_expiration_date | 
| ========================= | ===================================== | ================== | ================= | ========================= | =================== | ================================ | ============================ | ======================== | =========================== | 
| 5002370                   | SARANAC PALE ALE                      | 650                | 1                 | ALE                       | ALE                 | 2503534                          | MATT BREWING CO INC          | D                        | 2017-06-30T00:00:00         | 
| 5002383                   | UTICA CLUB LIGHT                      | 650                | 2                 | BEER & LAGER              | BEER                | 2503534                          | MATT BREWING CO INC          | D                        | 2017-06-30T00:00:00         | 
| 5002384                   | UTICA CLUB                            | 650                | 2                 | BEER & LAGER              | BEER                | 2503534                          | MATT BREWING CO INC          | D                        | 2017-06-30T00:00:00         | 
| 5002388                   | SARANAC BLACK FOREST                  | 650                | G                 | NO FEE BEER               | LAGER               | 2503534                          | MATT BREWING CO INC          | D                        | 2017-06-30T00:00:00         | 
| 5002390                   | SARANAC ADIRONDACK LAGER              | 650                | 2                 | BEER & LAGER              | BEER                | 2503534                          | MATT BREWING CO INC          | D                        | 2017-06-30T00:00:00         | 
| 5002410                   | OLDE ENGLISH 800                      | 650                | M                 | MALT LIQUOR               | MALT LIQUOR         | 2195946                          | MILLERCOORS LLC              | D                        | 2017-06-30T00:00:00         | 
| 5002411                   | MICKEYS MALT LIQUOR                   | 650                | G                 | NO FEE BEER               | MALT LIQUOR         | 2195946                          | MILLERCOORS LLC              | D                        | 2017-06-30T00:00:00         | 
| 5002414                   | WURZBURGER HOFBRAU JULIUS ECHTER HEFE | 650                | G                 | NO FEE BEER               | WEISSBIER ALE       | 2504784                          | T J SHEEHAN DISTRIBUTING INC | I                        | 2017-06-30T00:00:00         | 
| 5002415                   | BRICKHOUSE BREW BROWN ALE             | 650                | G                 | NO FEE BEER               | BROWN ALE           | 2505143                          | A J SUDS INC                 | D                        | 2017-06-30T00:00:00         | 
| 5002418                   | BRICKHOUSE HONEY LIGHT ALE            | 650                | G                 | NO FEE BEER               | ALE                 | 2505143                          | A J SUDS INC                 | D                        | 2017-06-30T00:00:00         | 
```