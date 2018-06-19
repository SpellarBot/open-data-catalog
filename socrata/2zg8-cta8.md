# Missouri Farmers' Markets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-farmers-markets-6019f) |
| Metadata | [Link](https://data.mo.gov/api/views/2zg8-cta8) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/2zg8-cta8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/2zg8-cta8/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 2zg8-cta8 |
| Name | Missouri Farmers' Markets |
| Category | Agriculture |
| Tags | farmers' markets, missouri, agrimissouri |
| Created | 2013-11-19T14:15:09Z |
| Publication Date | 2017-04-21T01:30:35Z |

## Description

This dataset is updated MON-FRI at 8:30PM

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | business_name        | business name        | text      | text        |
| No       |             | address1             | address1             | text      | text        |
| No       |             | address2             | address2             | text      | text        |
| Yes      | series tag  | city                 | city                 | text      | text        |
| Yes      | series tag  | state                | state                | text      | text        |
| Yes      | series tag  | zipcode              | zipcode              | text      | text        |
| Yes      | series tag  | county               | county               | text      | text        |
| Yes      | series tag  | contact_name         | contact name         | text      | text        |
| Yes      | series tag  | website              | website              | url       | url         |
| Yes      | series tag  | email                | email                | text      | text        |
| Yes      | series tag  | company_profile      | company profile      | text      | text        |
| Yes      | series tag  | company_description  | company description  | text      | text        |
| Yes      | series tag  | location_description | location description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address1,address2
```

## Data Commands

```ls
series e:2zg8-cta8 d:2017-04-21T01:30:09.000Z t:company_description="Vendors sell locally grown fruits, vegetables, beef, pork, lamb and eggs.  Also available are plants, baked goods, jams, jellies, scented soaps, handmade wooden items, various crafts and kettle corn." t:business_name="Boone County Farmers Market" t:company_profile="The Boone County Farmers' Market was formed in 2003 in Columbia, Missouri." t:county=Boone t:email=boonecou@boonecountyfarmers.com t:website=http://www.boonecountyfarmers.com t:zipcode=65203 t:contact_name="Shelly Blevins" t:state=MO t:location_description="Located in the Columbia Mall parking lot in Columbia Missouri.  

Hours are Saturdays 8 am - noon mid-April through the end of October." t:city=Columbia m:row_number.2zg8-cta8=1

series e:2zg8-cta8 d:2017-04-21T01:30:09.000Z t:company_description="The Market opens in early April with mostly bedding plants, potted plants and hanging baskets.  May brings fresh salad greens and hydroponics tomatoes.  In June, we add new potatoes and peas and our first taste of green beans.  The summer months provide sweet corn, peaches, melons, eggplants, apples, peppers, etc.  The Fall brings a large variety of produce, with hardy mums and all your fall decorating needs." t:business_name="Cole County Farmers' Market" t:company_profile="The Cole County Farmers' Market began in 1992 and has become a valuable tradition. All vendors must be from Cole or any adjoining county, and produce all products they sell, no resale of purchased products will be allowed.  Producers arrive 30-60 minutes before market opening to set up displays, but ""no early sales"" is strictly enforced." t:county=Cole t:email=hohman2@hotmail.com t:zipcode=65109 t:contact_name="James Hohman" t:state=MO t:location_description="Take Highway 50 to Jefferson City, exit Highway 179. Go south one block to Missouri Boulevard. Go east on Missouri Boulevard to the K-Mart parking lot. 

The market gathers Tuesdays and Fridays from 4:00 p.m. until 6:00 p.m. and Saturdays from 2:00 p.m. until 4:00 pm, April 13th through October." t:city="Jefferson City" m:row_number.2zg8-cta8=2

series e:2zg8-cta8 d:2017-04-21T01:30:09.000Z t:company_description="Fair Grove Farmers' Market:  Produce, fruits, berries, vegetables and bedding plants, perinnals, herbs, honey, baked goods and breads,  jams, jellies, organic produce, prepared food (dinner), crafts and special events." t:business_name="Fair Grove Farmers Market" t:company_profile="The Fair Grove Farmers' Market began in 2000. It is held on the grounds of the historic Wommack Mill.

EBT and Debit Cards accepted at the market.

Open:  April through October

Hours:  Wednesday - 3:00pm to 6:30pm" t:county=Greene t:email=debi7653@gmail.com t:website=http://www.fairgrovefarmersmarket.com/ t:zipcode=65648 t:contact_name="Debie Phillips" t:state=MO t:location_description="Eighteen miles north of Springfield on Highway 65, to Fair Grove. Take Highway 125 East 2 blocks to corner of Main Street and Highway 125. Held on Wommack Mill grounds. 

Every Wednesday 3:00 p.m. through 6:30 p.m., rain or shine, starting the 3rd Wednesday in April till the 1st Wednesday in October.

www.fairgrovefarmersmarket.com

1st place winner of the 2010 Farmers' Market of the Year Award
2nd place winner of the 2009 Farmers' Market of the Year Award" t:city="Fair Grove" m:row_number.2zg8-cta8=3
```

## Meta Commands

```ls
metric m:row_number.2zg8-cta8 p:long l:"Row Number"

entity e:2zg8-cta8 l:"Missouri Farmers' Markets" t:url=https://data.mo.gov/api/views/2zg8-cta8

property e:2zg8-cta8 t:meta.view v:id=2zg8-cta8 v:category=Agriculture v:averageRating=0 v:name="Missouri Farmers' Markets"

property e:2zg8-cta8 t:meta.view.owner v:id=nye7-5sqq v:screenName=John v:displayName=John

property e:2zg8-cta8 t:meta.view.tableauthor v:id=nye7-5sqq v:screenName=John v:displayName=John
```

## Top Records

```ls
| :updated_at | business_name                     | address1                                | address2               | city           | state | zipcode | county     | contact_name       | website                                              | email                           | company_profile                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | company_description                                                                                                                                                                                                                                                                                                                                                                                                                                                            | location_description                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| =========== | ================================= | ======================================= | ====================== | ============== | ===== | ======= | ========== | ================== | ==================================================== | =============================== | ==================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1492738209  | Boone County Farmers Market       | Columbia Mall (NE Parking Lot by Sears) | 2300 Bernadette Drive  | Columbia       | MO    | 65203   | Boone      | Shelly Blevins     | [http://www.boonecountyfarmers.com, null]            | boonecou@boonecountyfarmers.com | The Boone County Farmers' Market was formed in 2003 in Columbia, Missouri.                                                                                                                                                                                                                                                                                                                                                                                                                           | Vendors sell locally grown fruits, vegetables, beef, pork, lamb and eggs. Also available are plants, baked goods, jams, jellies, scented soaps, handmade wooden items, various crafts and kettle corn.                                                                                                                                                                                                                                                                         | Located in the Columbia Mall parking lot in Columbia Missouri. Hours are Saturdays 8 am - noon mid-April through the end of October.                                                                                                                                                                                                                                                                                                                                     | 
| 1492738209  | Cole County Farmers' Market       | K-Mart parking lot on Missouri Blvd.    |                        | Jefferson City | MO    | 65109   | Cole       | James Hohman       | [null, null]                                         | hohman2@hotmail.com             | The Cole County Farmers' Market began in 1992 and has become a valuable tradition. All vendors must be from Cole or any adjoining county, and produce all products they sell, no resale of purchased products will be allowed. Producers arrive 30-60 minutes before market opening to set up displays, but "no early sales" is strictly enforced.                                                                                                                                                   | The Market opens in early April with mostly bedding plants, potted plants and hanging baskets. May brings fresh salad greens and hydroponics tomatoes. In June, we add new potatoes and peas and our first taste of green beans. The summer months provide sweet corn, peaches, melons, eggplants, apples, peppers, etc. The Fall brings a large variety of produce, with hardy mums and all your fall decorating needs.                                                       | Take Highway 50 to Jefferson City, exit Highway 179. Go south one block to Missouri Boulevard. Go east on Missouri Boulevard to the K-Mart parking lot. The market gathers Tuesdays and Fridays from 4:00 p.m. until 6:00 p.m. and Saturdays from 2:00 p.m. until 4:00 pm, April 13th through October.                                                                                                                                                                   | 
| 1492738209  | Fair Grove Farmers Market         | Wommack Mill Pavilion                   | Hwy 125 & Main ST      | Fair Grove     | MO    | 65648   | Greene     | Debie Phillips     | [http://www.fairgrovefarmersmarket.com/, null]       | debi7653@gmail.com              | The Fair Grove Farmers' Market began in 2000. It is held on the grounds of the historic Wommack Mill. EBT and Debit Cards accepted at the market. Open: April through October Hours: Wednesday - 3:00pm to 6:30pm                                                                                                                                                                                                                                                                                    | Fair Grove Farmers' Market: Produce, fruits, berries, vegetables and bedding plants, perinnals, herbs, honey, baked goods and breads, jams, jellies, organic produce, prepared food (dinner), crafts and special events.                                                                                                                                                                                                                                                       | Eighteen miles north of Springfield on Highway 65, to Fair Grove. Take Highway 125 East 2 blocks to corner of Main Street and Highway 125. Held on Wommack Mill grounds. Every Wednesday 3:00 p.m. through 6:30 p.m., rain or shine, starting the 3rd Wednesday in April till the 1st Wednesday in October. www.fairgrovefarmersmarket.com 1st place winner of the 2010 Farmers' Market of the Year Award 2nd place winner of the 2009 Farmers' Market of the Year Award | 
| 1492738209  | Holden Farmers' Market            | 101 South Market Street                 |                        | Holden         | MO    | 64040   | Johnson    | Paula Sechrest     | [http://www.facebook.com/holdenfarmersmarket/, null] | p_sechrest@yahoo.com            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | The market is located in the community parking lot behind the old F&C Building and across the street from the Community Center. Look for the Farmers' Market banner. Vendors gather on Saturdays from 8 am to noon, June through September.                                                                                                                                                                                                                              | 
| 1492738209  | The Webb City Farmers' Market     | 555 South Main                          |                        | Webb City      | MO    | 64870   | Jasper     | Eileen Nichols     | [http://webbcityfarmersmarket.com, null]             | eileennichols@sbcglobal.net     | The Webb City Farmers Market is a producer-only market focused on local foods. We're open year-round on Saturdays from 9 to noon and beginning April 15 are also open on Tuesdays from 4 to 6 pm and on Fridays from 11 to 2. During the regular season, there is live music and a meal at every market. On Saturdays, the market hosts Cooking for a Cause, a benefit breakfast featuring biscuits and gravy, sausage and eggs to order. All profits benefit a different local nonprofit each week. | Most products sold at the market come from within 50 miles of Webb City. All vendors are inspected prior to setting up at the market to ensure that the customer is buying directly from the producer. Market produce is truly "food with a face" where customers buy directly from the baker, the beekeeper, the gardener and the grower. All producers of edible food must take a Food Safety: from field to market course prior to selling at the Webb City Farmers Market. | The market is located just east of 555 South Main Street in Webb City (64870) just southeast of the Main Street entrance to King Jack Park. During the winter the pavilion is enclosed with temporary sidings and heated.                                                                                                                                                                                                                                                | 
| 1492738209  | Willow Springs Farmers' Market    | 800 block of E Main Street              | Booster Field Pavilion | Willow Springs | MO    | 65793   | Howell     | Elizabeth M. Boyle | [null, null]                                         |                                 | Willow Springs Farmers' Market, established in 1987, is the oldest market in Howell County, Missouri. Specializing in locally grown, fresh produce, bedding plants, baked goods, jams and jellies, and handmade crafts. Open seasonally from June through October from 7:30 a.m. - 11:00 a.m. Wednesdays and Saturdays, at Booster Field, 800 W Main Street, Willow Springs, MO                                                                                                                      | Locally grown and produced fresh produce, bedding plants, baked goods, jams and jellies, and handmade crafts.                                                                                                                                                                                                                                                                                                                                                                  | Located within Booster Field, under the Pavilion in the 800 Block of W. Main Street, Willow Springs, Missouri. Business Hwy 60-63 The Market is open Wednesdays and Saturdays from 7:30 am-11:00 am, June to September                                                                                                                                                                                                                                                   | 
| 1492738209  | Kirkwood Farmers' Market          | 150 East Argonne Dr.                    |                        | Kirkwood       | MO    | 63122   | St. Louis  | Kori Thompson      | [http://www.downtownkirkwood.com, null]              | info@downtownkirkwood.com       | Kirkwood Farmers' Market is located in the heart of Downtown Kirkwood and is open daily. The season runs from April - September with a Harvest Market and Pumpkin Patch in October and a Christmas Market late-November through December. Please visit our web site www.downtownkirkwood.com for a list of participating vendors and operating hours.                                                                                                                                                | Kirkwood Farmers' Market is the site of numerous special events.                                                                                                                                                                                                                                                                                                                                                                                                               | Conveniently located between Highway 40 and I-44 in St. Louis County at the intersection of E. Argonne Drive and Taylor Avenue at 150 East Argonne Drive. Located in the heart of Kirkwood Junction. Mon-Fri 9 am-6 pm & Sat 8 am-5 pm, Apr-Sept 25 Harvest Market in October - Saturdays Pumpkin Patch - 7 days a week in October, 9:00 a.m. - 8:00 p.m. Christmas Market - 7 days a week, November to December 9:00 a.m. - 9:00 p.m.                                   | 
| 1492738209  | Washington County Farmers' Market | 520 Purcell Dr.                         | County Health Dept.    | Potosi         | MO    | 63664   | Washington | Lisa Eisenbeis     | [null, null]                                         | bequettek@missouri.edu          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Saturdays- Washington County Courthouse 102 N Missouri Potosi, MO 63664 Wednesdays- Washington County Health Dept 520 Purcell Drive Potosi, MO 63664 Hours are 7:30 am- 2 pm On Saturdays or until sold out 7:30 am-2 pm on Wednesdays or until sold out                                                                                                                                                                                                                 | 
| 1492738209  | Wildwood Farmers' Market          | 220 Plaza Drive                         |                        | Wildwood       | MO    | 63040   | St. Louis  | Rene Sackett       | [http://www.wildwoodfarmersmarket.org/, null]        | g3.rene.sackett@gmail.com       | The Farmers' Market of Wildwood is a private entity that has been contracted by the City of Wildwood, to provide a service to the community. Thus, we will bring together local grower to sell their produce to the public. Baked goods will also be in abundance.                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 1492738209  | Clinton Farmers' Market           | Historic Downtown Clinton Square        |                        | Clinton        | MO    | 64735   | Henry      | Jennifer Shadwick  | [null, null]                                         | fizzicians@hotmail.com          | The community of Clinton is proud to support their Farmers' Market and hope you will enjoy visiting the Market on the Historic Square - the largest square in the state of Missouri and second largest in the United States.                                                                                                                                                                                                                                                                         | The Clinton Farmers' Market has everything from apples to zucchini. There is a wide variety of vendors who sell a large selection of produce throughout the growing season. Numerous crafters and bakers join the market vendors to sell their crafts and baked goods also.                                                                                                                                                                                                    | Historic Downtown Clinton Square (North side of the Square) Come to the Clinton Farmers' Market on the Square from April through October, every Tuesday starting at 2:00 pm to sellout and every Saturday from 7:00 am to sellout.                                                                                                                                                                                                                                       | 
```