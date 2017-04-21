# Maker Spaces, Business Incubators & Accelerators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maker-spaces-business-incubators-accelerators) |
| Metadata | [Link](https://data.oregon.gov/api/views/wpin-z8u6) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wpin-z8u6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wpin-z8u6/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wpin-z8u6 |
| Name | Maker Spaces, Business Incubators & Accelerators |
| Attribution | Ruth Miles, Small Business Advocate |
| Category | Business |
| Tags | maker, artisan, craft, entrepreneur, incubator, business, accelerator, investor, investors, angel, small business advocate, secretary of state, office of small business assistance, oregon, busines... |
| Created | 2015-07-06T20:11:55Z |
| Publication Date | 2017-04-20T17:53:03Z |

## Description

Regularly updated list of maker spaces, business incubators and accelerators located in the State of Oregon.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | name         | Name         | text      | text        |
| Yes      | series tag  | description  | Description  | text      | text        |
| Yes      | series tag  | phone        | Phone        | text      | text        |
| Yes      | series tag  | email        | Email        | email     | email       |
| Yes      | series tag  | website      | Website      | url       | url         |
| Yes      | series tag  | service_area | Service area | text      | text        |
| Yes      | series tag  | type         | Type         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wpin-z8u6 d:2015-07-06T13:13:08.000Z t:website=http://www.starveups.com/ t:email=contactus@starveups.com t:service_area="Portland Metro" t:description="Starve Ups' mission is to share insights, resources and networks amongst membership companies to support and sustain successful businesses." t:name="Starve Ups" t:type=Accelerator m:row_number.wpin-z8u6=1

series e:wpin-z8u6 d:2015-07-06T13:13:08.000Z t:phone=541-345-9584 t:website=http://nedcocdc.org/hatch/ t:service_area="Lane County" t:description="Hatch?s business development program equips entrepreneurs with the financial resources and skills necessary to achieve long-term economic stability." t:name="Hatch Business Incubator" t:type=Incubator m:row_number.wpin-z8u6=2

series e:wpin-z8u6 d:2015-07-06T13:13:08.000Z t:phone=503-326-5211 t:website=https://portlandor.score.org/ t:service_area="Clackamas, Multnomah and Washington counties" t:description="SCORE provides support to business owners by offering 24/7 online mentoring advice, in-person meetings, low- cost workshops, ""how-to"" articles, business templates, online workshops and online training." t:name="SCORE?Portland Chapter" t:type="Technical Assistance" m:row_number.wpin-z8u6=3
```

## Meta Commands

```ls
metric m:row_number.wpin-z8u6 p:long l:"Row Number"

entity e:wpin-z8u6 l:"Maker Spaces, Business Incubators & Accelerators" t:attribution="Ruth Miles, Small Business Advocate" t:url=https://data.oregon.gov/api/views/wpin-z8u6

property e:wpin-z8u6 t:meta.view v:id=wpin-z8u6 v:category=Business v:averageRating=0 v:name="Maker Spaces, Business Incubators & Accelerators" v:attribution="Ruth Miles, Small Business Advocate"

property e:wpin-z8u6 t:meta.view.license v:name="Public Domain"

property e:wpin-z8u6 t:meta.view.owner v:id=qt3g-huzp v:profileImageUrlMedium=/api/users/qt3g-huzp/profile_images/THUMB v:profileImageUrlLarge=/api/users/qt3g-huzp/profile_images/LARGE v:screenName="Ruth Miles" v:profileImageUrlSmall=/api/users/qt3g-huzp/profile_images/TINY v:displayName="Ruth Miles"

property e:wpin-z8u6 t:meta.view.tableauthor v:id=qt3g-huzp v:profileImageUrlMedium=/api/users/qt3g-huzp/profile_images/THUMB v:profileImageUrlLarge=/api/users/qt3g-huzp/profile_images/LARGE v:screenName="Ruth Miles" v:profileImageUrlSmall=/api/users/qt3g-huzp/profile_images/TINY v:roleName=editor v:displayName="Ruth Miles"
```

## Top Records

```ls
| :updated_at | name                                              | description                                                                                                                                                                                                                                                                                                                               | phone        | email                        | website                                   | service_area                                 | type                 | 
| =========== | ================================================= | ========================================================================================================================================================================================================================================================================================================================================= | ============ | ============================ | ========================================= | ============================================ | ==================== | 
| 1436188388  | Starve Ups                                        | Starve Ups' mission is to share insights, resources and networks amongst membership companies to support and sustain successful businesses.                                                                                                                                                                                               |              | contactus@starveups.com      | [http://www.starveups.com/, null]         | Portland Metro                               | Accelerator          | 
| 1436188388  | Hatch Business Incubator                          | Hatch?s business development program equips entrepreneurs with the financial resources and skills necessary to achieve long-term economic stability.                                                                                                                                                                                      | 541-345-9584 |                              | [http://nedcocdc.org/hatch/, null]        | Lane County                                  | Incubator            | 
| 1436188388  | SCORE?Portland Chapter                            | SCORE provides support to business owners by offering 24/7 online mentoring advice, in-person meetings, low- cost workshops, "how-to" articles, business templates, online workshops and online training.                                                                                                                                 | 503-326-5211 |                              | [https://portlandor.score.org/, null]     | Clackamas, Multnomah and Washington counties | Technical Assistance | 
| 1436188388  | Fertilab Thinkubator-Springfield                  | Fertilab is a non-profit community and resource network that supports Lane County entrepreners.                                                                                                                                                                                                                                           | 541.632.4159 | info@fertilabthinkubator.com | [http://fertilabthinkubator.com/, null]   | Lane County                                  | Incubator            | 
| 1436188388  | Gorge Innoventure                                 | Gorge Innoventure helps grow businesses by providing collaboration and meeting space, education and networking activities, and access to expertise and capital.                                                                                                                                                                           | 541-436-0797 | info@gorgeinnoventure.com    | [https://www.gorgeinnoventure.com/, null] | Hood River County                            | Accelerator          | 
| 1436188388  | Eugene Mindworks Coworking and Business Incubator | Eugene Mindworks is an opportunity, a place for entrepreneurs, startups and the self employed to collaborate, innovate and grow.                                                                                                                                                                                                          | 541-515-9330 |                              | [http://eugenemindworks.com/, null]       | Eugene/Springfield                           | Incubator            | 
| 1436188388  | OTRADI Bioscience Incubator (OBI)                 | The OBI provides scientists and young companies with the resources and expertise needed to take their research from the lab to the market. Lab, office space and advanced scientific equipment.                                                                                                                                           | 503-227-1814 | info@otradi.org              | [http://www.otradi.org/incubator/, null]  | Statewide                                    | Incubator, Science   | 
| 1436188388  | OSU Advantage Accelerator                         | Oregon RAIN serves entrepreneurs in Oregon's South Willamette Valley by connecting them to resources and partners that can help them turn ideas into thriving, local traded-sector companies. RAIN has presence in Corvallis (OSU Advantage Accelerator) and Eugene (RAIN Eugene).                                                        | 541-368-5206 | anna.walsh@oregonstate.edu   | [http://oregonrain.org/, null]            | South Willamette Valley                      | Accelerator          | 
| 1436188388  | E1ectr0n                                          | E1ectr0n accelerates hardware development. At e1ectr0n there is a concentration of forces that are focused on hardware and those unique requirements for success. Axiom Electronics powers the incubator, bringing engineering and manufacturing capability, and many supporting companies and individuals bring expertise and knowledge. | 503-643-6600 | e1ectr0n@axiomsmt.com        | [http://www.e1ectr0n.com/, null]          | Washington County                            | Incubator            | 
| 1436188388  | Oregon BEST                                       | Oregon BEST nurtures clean technology innovation by transforming new ideas, research, and products into green collar jobs, greater sustainability, and economic prosperity for Oregon.                                                                                                                                                    | 503-725-9849 | info@oregonbest.org          | [http://oregonbest.org/, null]            | Statewide                                    | Accelerator          | 
```