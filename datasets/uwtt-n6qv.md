# IDOR SIC Report Q3 2010

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/uwtt-n6qv/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/idor-sic-report-q3-2010-95c27)
* [Metadata URL](https://data.illinois.gov/api/views/uwtt-n6qv)
* Id = uwtt-n6qv
* Name = IDOR SIC Report Q3 2010
* Attribution = Illinois Department of Revenue
* Category = Economics
* Tags = [revenue, tax]
* Created = 2011-06-15T17:26:04Z
* Publication Date = 2011-06-15T17:26:04Z
* Rows Updated = 2011-08-21T02:56:54Z

## Description

The SIC report is compiled to provide detail information regarding the types of business collecting the various taxes connected to the retailing of tangible personal property. This report shows the amount of each tax type, by a category grouping and totals for each incorporated municipality and the unincorporated areas of each county.   Information is for liability periods July 2010 thru September 2010 which were collected in August 2010 thru October 2010.

## Columns

```ls
| Name                                   | Field Name                           | Data Type | Render Type | Schema Type    | Included | 
| ====================================== | ==================================== | ========= | =========== | ============== | ======== | 
| updated_at                             | :updated_at                          | meta_data | meta_data   | time           | No       | 
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
series e:uwtt-n6qv d:2011-06-15T10:26:07.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=ST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=14975.03 m:general_merchandise_category=0 m:lumber_building_hardware_category=123815.82 m:agriculture_all_others_category=272044.75 m:automative_filling_stations_category=86328.92 m:food_category=479.43 m:ending_liability_period=201009 m:manufacturers_category=56585.7 m:number_of_taxpayers=219 m:drugs_misc_retail_category=96213.62 m:funiture_h_h_radio_category=4539.46 m:total_tax_receipts=655709.93

series e:uwtt-n6qv d:2011-06-15T10:26:07.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CT m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=3020.45 m:general_merchandise_category=0 m:lumber_building_hardware_category=24729.01 m:agriculture_all_others_category=55606 m:automative_filling_stations_category=17506.71 m:food_category=117.49 m:ending_liability_period=201009 m:manufacturers_category=11691.69 m:number_of_taxpayers=0 m:drugs_misc_retail_category=19908.49 m:funiture_h_h_radio_category=907.89 m:total_tax_receipts=133633.17

series e:uwtt-n6qv d:2011-06-15T10:26:07.000Z t:local_government_name="ADAMS COUNTY GOVERNMENT" t:multi_county_indicator=N t:tax_type_indicator=CST m:apparel_category=0 m:run_type_indicator=2 m:drinking_eating_places_category=748.79 m:general_merchandise_category=0 m:lumber_building_hardware_category=6182.29 m:agriculture_all_others_category=13597.67 m:automative_filling_stations_category=4313.56 m:food_category=23.98 m:ending_liability_period=201009 m:manufacturers_category=2829.1 m:number_of_taxpayers=0 m:drugs_misc_retail_category=4805.22 m:funiture_h_h_radio_category=226.97 m:total_tax_receipts=32763.94
```

## Meta Commands

```ls
metric m:ending_liability_period p:integer l:"Ending Liability Period" t:dataTypeName=number

metric m:run_type_indicator p:integer l:"Run Type Indicator" t:dataTypeName=number

metric m:number_of_taxpayers p:integer l:"Number of Taxpayers" t:dataTypeName=number

entity e:uwtt-n6qv l:"IDOR SIC Report Q3 2010" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/uwtt-n6qv

property e:uwtt-n6qv t:meta.view d:2017-03-07T23:00:48.584Z v:id=uwtt-n6qv v:category=Economics v:averageRating=0 v:name="IDOR SIC Report Q3 2010" v:attribution="Illinois Department of Revenue"

property e:uwtt-n6qv t:meta.view.owner d:2017-03-07T23:00:48.584Z v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd

property e:uwtt-n6qv t:meta.view.tableauthor d:2017-03-07T23:00:48.584Z v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```