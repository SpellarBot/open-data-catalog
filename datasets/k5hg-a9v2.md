# IDOR SIC Report Q4 2010

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/k5hg-a9v2/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/idor-sic-report-q4-2010-12600)
* Id = k5hg-a9v2
* Name = IDOR SIC Report Q4 2010
* Attribution = Illinois Department of Revenue
* Category = Economics
* Tags = [revenue, tax]
* Created = 2011-06-15T18:47:04Z
* Publication Date = 2011-06-15T18:47:04Z
* Rows Updated = 2011-08-21T02:56:54Z

## Description

The SIC report is compiled to provide detail information regarding the types of business collecting the various taxes connected to the retailing of tangible personal property. This report shows the amount of each tax type, by a category grouping and totals for each incorporated municipality and the unincorporated areas of each county.   Information is for liability periods October 2010 thru December 2010 which were collected in November 2010 thru January 2011.

## Columns

```ls
| Name                                   | Field Name                           | Data Type | Render Type | Schema Type    | Included | 
| ====================================== | ==================================== | ========= | =========== | ============== | ======== | 
| updated_at                             | :updated_at                          | meta_data | meta_data   | time           | Yes      | 
| Ending Liability Period                | ending_liability_period              | number    | text        | numeric metric | Yes      | 
| Run Type Indicator                     | run_type_indicator                   | number    | text        | numeric metric | Yes      | 
| Local Government Name                  | local_government_name                | text      | text        | series tag     | Yes      | 
| Multi-County Indicator                 | multi_county_indicator               | number    | text        | numeric metric | Yes      | 
| Tax Type Indicator                     | tax_type_indicator                   | text      | text        | series tag     | Yes      | 
| Number of Taxpayers                    | number_of_taxpayers                  | number    | number      | numeric metric | Yes      | 
| Total Tax Receipts                     | total_tax_receipts                   | money     | money       | numeric metric | Yes      | 
| General Merchandise Category           | general_merchandise_category         | money     | money       | numeric metric | Yes      | 
| Food Category                          | food_category                        | money     | money       | numeric metric | Yes      | 
| Drinking & Eating Places Category      | drinking_eating_places_category      | money     | money       | numeric metric | Yes      | 
| Apparel Category                       | apparel_category                     | money     | money       | numeric metric | Yes      | 
| Funiture, H.H. & Radio Category        | funiture_h_h_radio_category          | money     | money       | numeric metric | Yes      | 
| Lumber, Building & Hardware Category   | lumber_building_hardware_category    | money     | money       | numeric metric | Yes      | 
| Automative & Filling Stations Category | automative_filling_stations_category | money     | money       | numeric metric | Yes      | 
| Drugs & Misc. Retail Category          | drugs_misc_retail_category           | money     | money       | numeric metric | Yes      | 
| Agriculture & All Others Category      | agriculture_all_others_category      | money     | money       | numeric metric | Yes      | 
| Manufacturers Category                 | manufacturers_category               | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:k5hg-a9v2 d:2011-06-15T11:47:06.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=ST m:general_merchandise_category=0 m:agriculture_all_others_category=274944.28 m:food_category=334.31 m:ending_liability_period=201012 m:manufacturers_category=46355.93 m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=11537.56 m:lumber_building_hardware_category=94737.19 m:automative_filling_stations_category=786327.57 m:number_of_taxpayers=278 m:drugs_misc_retail_category=96790.6 m:funiture_h_h_radio_category=4247.23 m:total_tax_receipts=1316274.65

series e:k5hg-a9v2 d:2011-06-15T11:47:06.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CT m:general_merchandise_category=0 m:agriculture_all_others_category=57554.3 m:food_category=726.9 m:ending_liability_period=201012 m:manufacturers_category=9623.71 m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=2320.26 m:lumber_building_hardware_category=18942 m:automative_filling_stations_category=157441.22 m:number_of_taxpayers=0 m:drugs_misc_retail_category=20782.87 m:funiture_h_h_radio_category=911.67 m:total_tax_receipts=268502.93

series e:k5hg-a9v2 d:2011-06-15T11:47:06.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CST m:general_merchandise_category=0 m:agriculture_all_others_category=13715.92 m:food_category=16.72 m:ending_liability_period=201012 m:manufacturers_category=2317.76 m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=576.87 m:lumber_building_hardware_category=4735.48 m:automative_filling_stations_category=39307.96 m:number_of_taxpayers=0 m:drugs_misc_retail_category=4809.89 m:funiture_h_h_radio_category=212.22 m:total_tax_receipts=65742.82
```

## Meta Commands

```ls
metric m:ending_liability_period p:integer l:"Ending Liability Period" t:dataTypeName=number

metric m:run_type_indicator p:integer l:"Run Type Indicator" t:dataTypeName=number

metric m:number_of_taxpayers p:integer l:"Number of Taxpayers" t:dataTypeName=number

entity e:k5hg-a9v2 l:"IDOR SIC Report Q4 2010" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/k5hg-a9v2

property e:k5hg-a9v2 t:meta.view d:2017-03-03T14:08:57.883Z v:id=k5hg-a9v2 v:category=Economics v:averageRating=0 v:name="IDOR SIC Report Q4 2010" v:attribution="Illinois Department of Revenue"

property e:k5hg-a9v2 t:meta.view.owner d:2017-03-03T14:08:57.883Z v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd

property e:k5hg-a9v2 t:meta.view.tableauthor d:2017-03-03T14:08:57.883Z v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```