# What do I do with...? Recycling options in King County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/what-do-i-do-with-recycling-options-in-king-county-1b49d) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/zqwi-c5q3) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/zqwi-c5q3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/zqwi-c5q3/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | zqwi-c5q3 |
| Name | What do I do with...? Recycling options in King County |
| Attribution | King County Solid Waste Division |
| Category | Environment |
| Tags | recycling, recycle, materials, king, county, solid, waste, disposal |
| Created | 2010-10-21T17:25:37Z |
| Publication Date | 2016-07-20T16:54:20Z |

## Description

The "What do I do with...?" site (http://your.kingcounty.gov/solidwaste/wdidw/index.asp) provides King County citizens with recycling and proper disposal options for over 100 products and materials. The site lists over 400 businesses (mostly local) that accept products and materials for recycling or proper disposal. Business details include location (with mapping), contact information, hours of operation, restrictions, fees and more. The goal of "What do I do with...?" is to reduce the volume of reusable or recyclable items being added to the waste-stream, thereby reducing the environmental impact of those items while extending the lifespan of our landfills.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | providerid          | ProviderID          | text      | number      |
| Yes      | series tag  | provider_name       | Provider Name       | text      | text        |
| No       |             | provider_address    | Provider Address    | text      | text        |
| Yes      | series tag  | city                | City                | text      | text        |
| Yes      | series tag  | zip                 | Zip                 | text      | text        |
| Yes      | series tag  | phone               | Phone               | phone     | phone       |
| Yes      | series tag  | phone_ext           | Phone Ext           | text      | text        |
| Yes      | series tag  | hours               | Hours               | text      | text        |
| Yes      | series tag  | material_handled    | Material Handled    | text      | text        |
| Yes      | series tag  | service_description | Service Description | text      | text        |
| Yes      | series tag  | restrictions        | Restrictions        | text      | text        |
| Yes      | series tag  | minimum_volume      | Minimum Volume      | text      | text        |
| Yes      | series tag  | maximum_volume      | Maximum Volume      | text      | text        |
| Yes      | series tag  | property_type       | Property Type       | text      | text        |
| Yes      | series tag  | fee                 | Fee                 | text      | text        |
| Yes      | series tag  | pickup_allowed      | Pickup Allowed      | text      | text        |
| Yes      | series tag  | dropoff_allowed     | Dropoff Allowed     | text      | text        |
| Yes      | series tag  | mail_in_allowed     | Mail In Allowed     | text      | text        |
| Yes      | series tag  | tibn                | TIBN                | text      | text        |
| Yes      | series tag  | ecycle              | eCycle              | text      | text        |
| Yes      | series tag  | location            | Location            | text      | text        |
| Yes      | series tag  | provider_url        | Provider URL        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = provider_address
```

## Data Commands

```ls
series e:zqwi-c5q3 d:2016-07-19T12:18:02.000Z t:zip=98275 t:phone_number="(425) 493-6802" t:providerid=663 t:restrictions="<a href=http://www.acemetalco.com/Services.html>http://www.acemetalco.com/Services.html</a>" t:location="11110 Mukilteo Speedway Ste. 202 WA 98275" t:hours="Mon - Fri: 8am - 6pm  Sat:  8am - 3pm" t:dropoff_allowed=TRUE t:tibn=FALSE t:material_handled="Air Conditioners, Heat Pumps" t:city=Mukilteo t:pickup_allowed=TRUE t:property_type="Business, Residents" t:ecycle=TRUE t:mail_in_allowed=FALSE t:service_description="<a href=http://www.acemetalco.com/Services.html>http://www.acemetalco.com/Services.html</a>" t:provider_url=http://www.acemetalco.com t:provider_name="Ace Metal Company" m:row_number.zqwi-c5q3=1

series e:zqwi-c5q3 d:2016-07-19T12:18:02.000Z t:zip=98275 t:phone_number="(425) 493-6802" t:providerid=663 t:restrictions="<a href=http://www.acemetalco.com/Services.html>http://www.acemetalco.com/Services.html</a>" t:location="11110 Mukilteo Speedway Ste. 202 WA 98275" t:hours="Mon - Fri: 8am - 6pm  Sat:  8am - 3pm" t:dropoff_allowed=TRUE t:tibn=FALSE t:material_handled="Other Major Appliances" t:city=Mukilteo t:pickup_allowed=TRUE t:property_type="Business, Residents" t:ecycle=TRUE t:mail_in_allowed=FALSE t:service_description="<a href=http://www.acemetalco.com/Services.html>http://www.acemetalco.com/Services.html</a>" t:provider_url=http://www.acemetalco.com t:provider_name="Ace Metal Company" m:row_number.zqwi-c5q3=2

series e:zqwi-c5q3 d:2016-07-19T12:18:02.000Z t:zip=98275 t:phone_number="(425) 493-6802" t:providerid=663 t:restrictions="<a href=http://www.acemetalco.com/Services.html>http://www.acemetalco.com/Services.html</a>" t:location="11110 Mukilteo Speedway Ste. 202 WA 98275" t:hours="Mon - Fri: 8am - 6pm  Sat:  8am - 3pm" t:dropoff_allowed=TRUE t:tibn=FALSE t:material_handled="Refrigerators, Freezers" t:city=Mukilteo t:pickup_allowed=TRUE t:property_type="Business, Residents" t:ecycle=TRUE t:mail_in_allowed=FALSE t:service_description="<a href=http://www.acemetalco.com/Services.html>http://www.acemetalco.com/Services.html</a>" t:provider_url=http://www.acemetalco.com t:provider_name="Ace Metal Company" m:row_number.zqwi-c5q3=3
```

## Meta Commands

```ls
metric m:row_number.zqwi-c5q3 p:long l:"Row Number"

entity e:zqwi-c5q3 l:"What do I do with...? Recycling options in King County" t:attribution="King County Solid Waste Division" t:url=https://data.kingcounty.gov/api/views/zqwi-c5q3

property e:zqwi-c5q3 t:meta.view v:id=zqwi-c5q3 v:category=Environment v:attributionLink=http://your.kingcounty.gov/solidwaste/wdidw/index.asp v:averageRating=0 v:name="What do I do with...? Recycling options in King County" v:attribution="King County Solid Waste Division"

property e:zqwi-c5q3 t:meta.view.license v:name="Public Domain"

property e:zqwi-c5q3 t:meta.view.owner v:id=v9bf-ky97 v:profileImageUrlMedium=/api/users/v9bf-ky97/profile_images/THUMB v:profileImageUrlLarge=/api/users/v9bf-ky97/profile_images/LARGE v:screenName="Jay Beach" v:profileImageUrlSmall=/api/users/v9bf-ky97/profile_images/TINY v:displayName="Jay Beach"

property e:zqwi-c5q3 t:meta.view.tableauthor v:id=v9bf-ky97 v:profileImageUrlMedium=/api/users/v9bf-ky97/profile_images/THUMB v:profileImageUrlLarge=/api/users/v9bf-ky97/profile_images/LARGE v:screenName="Jay Beach" v:profileImageUrlSmall=/api/users/v9bf-ky97/profile_images/TINY v:roleName=publisher v:displayName="Jay Beach"
```

## Top Records

```ls
| :updated_at | providerid | provider_name     | provider_address                 | city     | zip   | phone                  | phone_ext | hours                               | material_handled                          | service_description                                                              | restrictions                                                                                             | minimum_volume | maximum_volume | property_type       | fee  | pickup_allowed | dropoff_allowed | mail_in_allowed | tibn  | ecycle | location                                  | provider_url                      | 
| =========== | ========== | ================= | ================================ | ======== | ===== | ====================== | ========= | =================================== | ========================================= | ================================================================================ | ======================================================================================================== | ============== | ============== | =================== | ==== | ============== | =============== | =============== | ===== | ====== | ========================================= | ================================= | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Air Conditioners, Heat Pumps              | http://www.acemetalco.com/Services.html                                          | http://www.acemetalco.com/Services.html                                                                  |                |                | Business, Residents |      | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Other Major Appliances                    | http://www.acemetalco.com/Services.html                                          | http://www.acemetalco.com/Services.html                                                                  |                |                | Business, Residents |      | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Refrigerators, Freezers                   | http://www.acemetalco.com/Services.html                                          | http://www.acemetalco.com/Services.html                                                                  |                |                | Business, Residents |      | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Small Household Appliances                | Recycles any stainless steel appliances and kitchen fixtures, most scrap metals. |                                                                                                          |                |                | Business, Residents |      | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Cell Phones, Smart Phones, Mobile Devices | http://www.acemetalco.com/Services.html                                          | http://www.acemetalco.com/Services.html                                                                  |                |                | Business, Residents |      | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Monitors                                  | http://www.acemetalco.com/Services.html                                          | http://www.acemetalco.com/Services.html                                                                  |                |                | Business, Residents |      | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Computers, Laptops, Tablets               | http://www.acemetalco.com/Services.html                                          | http://www.acemetalco.com/Services.html                                                                  |                |                | Business, Residents |      | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | TVs                                       | http://www.acemetalco.com/Services.html                                          | http://www.acemetalco.com/Services.html                                                                  |                |                | Business, Residents |      | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Aluminum Cans                             | Recycles most scrap metals.                                                      | No Scrap that contains Asbestos material, Excessively greasy or oily scrap, no hazardous or toxic waste. |                |                | Business, Residents | Call | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
| 1468930682  | 663        | Ace Metal Company | 11110 Mukilteo Speedway Ste. 202 | Mukilteo | 98275 | [(425) 493-6802, null] |           | Mon - Fri: 8am - 6pm Sat: 8am - 3pm | Ferrous Metals                            | Recycles most scrap metals.                                                      | No Scrap that contains Asbestos material, Excessively greasy or oily scrap, no hazardous or toxic waste. |                |                | Business, Residents | Call | TRUE           | TRUE            | FALSE           | FALSE | TRUE   | 11110 Mukilteo Speedway Ste. 202 WA 98275 | [http://www.acemetalco.com, null] | 
```