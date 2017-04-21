# I Love NY - Places to Stay

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/i-love-ny-places-to-stay) |
| Metadata | [Link](https://data.ny.gov/api/views/nvxm-nnvd) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nvxm-nnvd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nvxm-nnvd/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nvxm-nnvd |
| Name | I Love NY - Places to Stay |
| Attribution | I Love NY |
| Created | 2013-07-12T14:04:38Z |
| Publication Date | 2013-07-15T21:07:29Z |

## Description

This data set includes Places to Stay in New York State. These places are currently part of the ILoveNY.com website. Currently, they are grouped by region.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | regions          | Regions          | text      | text        |
| Yes      | series tag  | county           | County           | text      | text        |
| Yes      | series tag  | ip_name          | IP Name          | text      | text        |
| Yes      | series tag  | website_url      | Website URL      | url       | url         |
| Yes      | series tag  | site_city        | Site City        | text      | text        |
| Yes      | series tag  | description      | Description      | text      | text        |
| No       |             | latitude         | Latitude         | number    | number      |
| No       |             | longitude        | Longitude        | number    | number      |
| Yes      | series tag  | subcategories    | Subcategories    | text      | text        |
| Yes      | series tag  | minor_categories | Minor Categories | text      | text        |
| Yes      | series tag  | image_url        | Image URL        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:nvxm-nnvd d:2013-07-15T14:06:57.000Z t:site_city="NEW HARTFORD" t:ip_name="Hampton Inn & Suites" t:county="Oneida County" t:description="Discover true hospitality from our incredible staff to the remarkable orchard setting, we have focused on every detail to insure you?ll enjoy your stay and look forward to your next visit.  Retire to one of our luxurious smoke-free guest rooms and find everything you need for a comfortable and relaxing stay. Stay connected everywhere in the hotel with free internet access and enjoy a restful sleep in the clean fresh Hampton bed. Our stylish suites offer extra space and a generous work area, ideal for business travelers or families." t:minor_categories="Hotels & Motels" t:website_url=http://www.hampton.com t:subcategories="Hotels & Motels" t:regions="Central New York" m:row_number.nvxm-nnvd=1

series e:nvxm-nnvd d:2013-07-15T14:06:57.000Z t:site_city=GROTON t:ip_name="The Little House" t:county="Tompkins County" t:description="Light-filled 2-story Victorian cottage with gleaming hardwood floors, patio, balcony. Linens included. Fully-appointed kitchen w/dishwasher." t:minor_categories="Cabins & Cottages" t:subcategories="Cabins & Cottages" t:regions="Finger Lakes" m:row_number.nvxm-nnvd=2

series e:nvxm-nnvd d:2013-07-15T14:06:57.000Z t:site_city=ITHACA t:ip_name="Fieldstone Suites" t:county="Tompkins County" t:description="This is a unique earth sheltered (underground) home that is rural and private yet close to Ithaca, Cornell and Ithaca College. Perfect for visiting professionals, couples or family." t:minor_categories="Vacation Rentals" t:website_url=http://www.fieldstonesuites.com/ t:subcategories="Vacation Rentals" t:regions="Finger Lakes" m:row_number.nvxm-nnvd=3
```

## Meta Commands

```ls
metric m:row_number.nvxm-nnvd p:long l:"Row Number"

entity e:nvxm-nnvd l:"I Love NY - Places to Stay" t:attribution="I Love NY" t:url=https://data.ny.gov/api/views/nvxm-nnvd

property e:nvxm-nnvd t:meta.view v:id=nvxm-nnvd v:attributionLink=http://iloveny.com/where-to-stay v:averageRating=0 v:name="I Love NY - Places to Stay" v:attribution="I Love NY"

property e:nvxm-nnvd t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nvxm-nnvd t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:nvxm-nnvd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | regions             | county          | ip_name                                | website_url                                                   | site_city        | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | latitude   | longitude   | subcategories                   | minor_categories                    | image_url    | 
| =========== | =================== | =============== | ====================================== | ============================================================= | ================ | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========== | =========== | =============================== | =================================== | ============ | 
| 1373897217  | Central New York    | Oneida County   | Hampton Inn & Suites                   | [http://www.hampton.com, null]                                | NEW HARTFORD     | Discover true hospitality from our incredible staff to the remarkable orchard setting, we have focused on every detail to insure you?ll enjoy your stay and look forward to your next visit. Retire to one of our luxurious smoke-free guest rooms and find everything you need for a comfortable and relaxing stay. Stay connected everywhere in the hotel with free internet access and enjoy a restful sleep in the clean fresh Hampton bed. Our stylish suites offer extra space and a generous work area, ideal for business travelers or families. | 43.0905093 | -75.3301312 | Hotels & Motels                 | Hotels & Motels                     | [null, null] | 
| 1373897217  | Finger Lakes        | Tompkins County | The Little House                       | [null, null]                                                  | GROTON           | Light-filled 2-story Victorian cottage with gleaming hardwood floors, patio, balcony. Linens included. Fully-appointed kitchen w/dishwasher.                                                                                                                                                                                                                                                                                                                                                                                                             | 42.587976  | -76.373372  | Cabins & Cottages               | Cabins & Cottages                   | [null, null] | 
| 1373897217  | Finger Lakes        | Tompkins County | Fieldstone Suites                      | [http://www.fieldstonesuites.com/, null]                      | ITHACA           | This is a unique earth sheltered (underground) home that is rural and private yet close to Ithaca, Cornell and Ithaca College. Perfect for visiting professionals, couples or family.                                                                                                                                                                                                                                                                                                                                                                    | 42.4114136 | -76.4021975 | Vacation Rentals                | Vacation Rentals                    | [null, null] | 
| 1373897217  | Catskills           | Greene County   | Earlton Hill Campground & RV Park, LLC | [http://www.earltonhillcampground.com, null]                  | EARLTON          | Over 300 sites, 1/3 with full hook-ups, tent sites, pavilion rentals, recreation room, convenience store, clean restrooms with showers, lake for swimming, fishing and boating. Daily, weekly, monthly and seasonal rates.                                                                                                                                                                                                                                                                                                                               | 42.3745586 | -73.909884  | Camping                         | Privately-owned Campgrounds         | [null, null] | 
| 1373897217  | Hudson Valley       | Dutchess County | Wing's Castle                          | [http://www.wingscastle.com, null]                            | MILLBROOK        | Escape to the country for a night or a weekend and relax in a true stone castle 70 miles north of New York City, in the quaint, happening town of Millbrook, New York.                                                                                                                                                                                                                                                                                                                                                                                   | 41.840401  | -73.6794309 | B&Bs & Country Inns             | B&Bs & Country Inns                 | [null, null] | 
| 1373897217  | Central New York    | Otsego County   | Grand Slam Campgrounds & Cabins        | [http://www.grandslamcampground.com, null]                    | SOUTH NEW BERLIN | Enjoy family style camping along the banks of the Unadilla River in Central New York with almost 2000' of river frontage with grassy campsites under the shade of stately maple trees. Canoe rentals by the hour and by the day. Close to Cooperstown, Oneonta and Norwich. Game room, fireplace, pool table, horseshoes, soccer and more.                                                                                                                                                                                                               | 42.602833  | -75.323931  | Camping                         | Privately-owned Campgrounds         | [null, null] | 
| 1373897217  | 1000 Islands-Seaway | Oswego County   | Salmon Hills LLC                       | [http://www.salmonhills.com, null]                            | REDFIELD         | Salmon Hills, under new ownership, offers a lovely remodeled lodge conveniently located between Syracuse and Watertown just off of I-81. Nestled near the beautiful Salmon River and Salmon River Reservoir, it is surrounded by thousands of acres of forest land. With easy access to world-class salmon and trout fishing, miles of snowmobile trails, cross-country skiing and easy access to a public boat launch, Salmon Hill?s offers so much to those wanting to escape to nature.                                                               | 43.551384  | -75.878918  | B&Bs & Country Inns             | B&Bs & Country Inns                 | [null, null] | 
| 1373897217  | Central New York    | Madison County  | The Horned Dorset Inn                  | [http://www.horneddorsetinn.com, null]                        | LEONARDSVILLE    | The Horned Dorset Inn is the quintessential destination for memorable fine dining and lodging in Central NY. It has lovingly been managed by the same owners for 35 years. Classic French cuisine, gracious Victorian accommodations and sensitive service are the hallmarks of this countryside hostelry. The owners recently inaugurated the Horned Dorset Colony, an artists? residency program offering writers, composers and visual artists a one-month stay during which they can work free of worldly distractions.                              | 42.841989  | -75.256348  | B&Bs & Country Inns|Restaurants | American|B&Bs & Country Inns|French | [null, null] | 
| 1373897217  | Central New York    | Madison County  | Shiloh Christian Family Campground     | [http://www.shilohonhatch.com, null]                          | EATON            | Shiloh Christian Family Campground provides great YR opportunities for spiritual refreshment, fun and relaxation. Whether your visit is just for a day, a weekend or a full week. Included in the facilities are lakeside cottages, RV sites, campsites, boat launching and docking, swimming, canoes, paddle boats, row boats, fishing, hiking, volleyball, basketball and horseshoes. we have a Chapel that seats 200 that can be rented for special occasions.                                                                                        | 42.8544909 | -75.6582748 | Camping                         | Privately-owned Campgrounds         | [null, null] | 
| 1373897217  | 1000 Islands-Seaway | Oswego County   | Quality Inn & Suites Riverfront        | [http://www.qualityinn.com/hotel-oswego-new_york-NY613, null] | OSWEGO           | This hotel is ideally located with several rooms overlooking the historic Oswego Harbor. It is within walking distance of several shops, fishing areas, theatres and a marina. Enjoy a scenic walk along the river and visit the many businesses located in the downtown district.                                                                                                                                                                                                                                                                       | 43.4594895 | -76.5087969 | Hotels & Motels                 | Hotels & Motels                     | [null, null] | 
```