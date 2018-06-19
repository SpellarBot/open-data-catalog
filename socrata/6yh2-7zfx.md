# DCEO Tourism - Illinois Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-tourism-illinois-events-ea95f) |
| Metadata | [Link](https://data.illinois.gov/api/views/6yh2-7zfx) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6yh2-7zfx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6yh2-7zfx/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6yh2-7zfx |
| Name | DCEO Tourism - Illinois Events |
| Category | Social/Healthcare |
| Tags | tourism |
| Created | 2012-01-13T21:18:26Z |
| Publication Date | 2012-01-13T21:30:32Z |

## Description

Illinois Tourism Events

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | cc_name        | cc_name        | text      | text        |
| Yes      | series tag  | cc_description | cc_description | text      | text        |
| Yes      | series tag  | cc_website     | cc_website     | text      | text        |
| Yes      | series tag  | cat_name       | cat_name       | text      | text        |
| No       |             | cc_start_date  | cc_start_date  | text      | text        |
| No       |             | cc_end_date    | cc_end_date    | text      | text        |
| Yes      | series tag  | ad_postal_code | ad_postal_code | text      | number      |
| Yes      | series tag  | ad_email       | ad_email       | text      | text        |
| Yes      | series tag  | ad_phone_no    | ad_phone_no    | text      | text        |
| Yes      | series tag  | ad_phone_no2   | ad_phone_no2   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = cc_start_date,cc_end_date
```

## Data Commands

```ls
series e:6yh2-7zfx d:2012-01-13T13:18:31.000Z t:ad_phone_no2=NULL t:cc_name="Splash City Family Waterpark" t:ad_postal_code=62234 t:cc_description="Surfing in Illinois?  Yes!  The FlowRider creates a perfect wave for surfing and body boarding.  Water slides, a lap pool, the lazy river, a sandy play area and Monsoon Mountain make for a family adventure." t:cc_website=www.splashcity.org t:ad_phone_no=6183467529 t:cat_name=Attractions m:row_number.6yh2-7zfx=1

series e:6yh2-7zfx d:2012-01-13T13:18:31.000Z t:ad_phone_no2=NULL t:cc_name="Arthur-The Great Pumpkin Patch" t:ad_postal_code=61911 t:cc_description="Over 400 varieties of pumpkins, squash and gourds on your working farm. Over 6000 harvest mums and feature mazes, farm animals, sweet shop, 1912 one-room schoolhouse, and gift shop. Numerous displays to enjoy." t:cc_website=www.thegreatpumpkinpatch.biz t:ad_phone_no=2175432394 t:cat_name=Attractions m:row_number.6yh2-7zfx=2

series e:6yh2-7zfx d:2012-01-13T13:18:31.000Z t:ad_phone_no2=NULL t:cc_name="Oak Park Visitors Center Walking Tour" t:ad_postal_code=60301 t:cc_description="This state of the art PDA guided tour will show you the evolution or architecture - from the Victorian period, Prairie School through the Art Deco period of the 1930's. Hear the reflections of the famous people who walked these streets, nurtured their creativity and brought international recognition to the place they called home - Oak Park, Illinois. The Audio Tour begins and ends at the Oak Park Visitors Center.  Last audio tour available at 3:30 pm (2:30 January and February). Last combo tour available at 1pm. PDA equipment must be turned in at Visitors Center on the same day as your tour rental." t:cc_website=www.visitoakpark.com t:ad_phone_no=7088481500 t:cat_name=Attractions m:row_number.6yh2-7zfx=3
```

## Meta Commands

```ls
metric m:row_number.6yh2-7zfx p:long l:"Row Number"

entity e:6yh2-7zfx l:"DCEO Tourism - Illinois Events" t:url=https://data.illinois.gov/api/views/6yh2-7zfx

property e:6yh2-7zfx t:meta.view v:id=6yh2-7zfx v:category=Social/Healthcare v:averageRating=0 v:name="DCEO Tourism - Illinois Events"

property e:6yh2-7zfx t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:6yh2-7zfx t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | cc_name                                                                                          | cc_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | cc_website                                              | cat_name    | cc_start_date | cc_end_date | ad_postal_code | ad_email          | ad_phone_no | ad_phone_no2 | 
| =========== | ================================================================================================ | =================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ======================================================= | =========== | ============= | =========== | ============== | ================= | =========== | ============ | 
| 1326460711  | Splash City Family Waterpark                                                                     | Surfing in Illinois? Yes! The FlowRider creates a perfect wave for surfing and body boarding. Water slides, a lap pool, the lazy river, a sandy play area and Monsoon Mountain make for a family adventure.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | www.splashcity.org                                      | Attractions | 5/1/2002      | 9/1/2011    | 62234          |                   | 6183467529  | NULL         | 
| 1326460711  | Arthur-The Great Pumpkin Patch                                                                   | Over 400 varieties of pumpkins, squash and gourds on your working farm. Over 6000 harvest mums and feature mazes, farm animals, sweet shop, 1912 one-room schoolhouse, and gift shop. Numerous displays to enjoy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | www.thegreatpumpkinpatch.biz                            | Attractions | 9/15/2006     | 10/31/2011  | 61911          |                   | 2175432394  | NULL         | 
| 1326460711  | Oak Park Visitors Center Walking Tour                                                            | This state of the art PDA guided tour will show you the evolution or architecture - from the Victorian period, Prairie School through the Art Deco period of the 1930's. Hear the reflections of the famous people who walked these streets, nurtured their creativity and brought international recognition to the place they called home - Oak Park, Illinois. The Audio Tour begins and ends at the Oak Park Visitors Center. Last audio tour available at 3:30 pm (2:30 January and February). Last combo tour available at 1pm. PDA equipment must be turned in at Visitors Center on the same day as your tour rental.                                                                                                                                                                                        | www.visitoakpark.com                                    | Attractions | 12/1/2009     | 12/31/2015  | 60301          |                   | 7088481500  | NULL         | 
| 1326460711  | Twin Groves Wind Farm                                                                            | Located on the wind-swept Bloomington Moraine in eastern McLean County, Twin Groves Wind Farm offers 396 megawatts of affordable, pollution-free wind energy, enough to meet the annual energy needs of about 118,000 homes. Learn more about this exciting new facility with a farm tour.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | www.horizonwind.com                                     | Attractions | 4/12/2010     | 4/12/2015   | 61737          |                   | 3097248278  | NULL         | 
| 1326460711  | Team of Rivals                                                                                   | A Civil War 150th Year Exhibition commemorates the beginning of the Civil War with a visit to the Abraham Lincoln Presidential Museum for its one-of-a-kind temporary exhibition. Through a series of audio-visual presentations and compelling artifacts, Doris Kearns Goodwin, author of the best-selling book Team of Rivals will bring to life those fateful days when our divided nation teetered on the brink, then toppled into the dark abyss of civil war.                                                                                                                                                                                                                                                                                                                                                 | www.presidentlincoln.org                                | Art/Culture | 10/14/2010    | 8/15/2011   | 62701          |                   | 2175588934  | NULL         | 
| 1326460711  | Team of Rivals                                                                                   | Commemorate the beginning of the Civil War Sesquicentennial with a visit to the Museum for its one-of-a-kind temporary exhibition. This exhibition takes you inside the highest levels of the United States government as Abraham Lincoln and his cabinet struggle with the momentous issue of war. Restricted to the information they possessed at the time, you will confront the perplexities and options they faced during the first weeks of Lincoln's presidency - and decide for yourself if they made the right choices.                                                                                                                                                                                                                                                                                    | www.abelincolnmuseum.org                                | Art/Culture | 10/14/2010    | 1/16/2012   | 62701          |                   | 2175588934  | NULL         | 
| 1326460711  | Design Detectives Family Tour at the Frank Lloyd Wright Home & Studio                            | Every Saturday! Bring your family of sleuths together and explore Wright's home to uncover the secrets of his designs. Join Preservation Trust Junior Interpreters, specially trained 5th-10th grade students, to discover how America's most famous architect broke with traditional design, and hear stories of his family's life in their Oak Park house.                                                                                                                                                                                                                                                                                                                                                                                                                                                        | www.gowright.org                                        | Art/Culture | 12/4/2010     | 8/25/2011   | 60302          | info@gowright.org | 7088481606  | NULL         | 
| 1326460711  | Afternoon Tour and Tea at Historic Pleasant Home                                                 | Thursday afternoons from 1:30-4:30pm. $25 includes tour and tea (reservations required at least one week in advance). Thursday afternoon Tour & Tea at Pleasant Home is a great way to catch up with friends and tour Pleasant Home, too! Come for the 1:30pm tour and stay for tea and light sandwiches. For more information call 708-383-2654.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | www.pleasanthome.org                                    | Art/Culture | 12/16/2010    | 11/27/2011  | 60302          |                   | 7083832654  | NULL         | 
| 1326460711  | Walking Tour of the Frank Lloyd Wright Prairie School of Architecture National Historic District | Discover the development of Wright's style between 1889 and 1909, and trace the evolution of American residential architecture as trained interpreters guide you through the Historic District surrounding the Home and Studio. Self-Guided Audio Tours: Saturday and Sunday, 10 am to 3:30 pm. Holiday hours: Sunday, 12/26 and 1/2, noon - 4 pm (last tour at 2:30 pm). Guided Tours: Saturday and Sunday, 11 am - 4 pm March - October. 12 pm - 2 pm November - February. Call or visit the website for tickets.                                                                                                                                                                                                                                                                                                 | www.gowright.org                                        | Art/Culture | 12/18/2010    | 10/27/2011  | 60302          | info@gowright.org | 7088481606  | NULL         | 
| 1326460711  | Illinois Bed and Breakfast Murder Mystery - Fun For All!                                         | Come out for a night of great food, fun and find out Whodunit. Join in on a set date or call us to plan a special date for your party of 8 or more! A week before your reservation you will be emailed the information about what character you will be playing, a little about your past life, to help you decide what costume you will want to be wearing. Arrive in the parlor at 7:00pm for Wine & Cheese and meeting the other suspects. At 7:30pm we will move into the formal dining room for a catered in dinner and the investigation will continue. The mystery will be solved after dinner with coffee and desert in the parlor. Prizes given for the Best Costume, Best Actor and Best Ham. Price is $30 plus price of your room for overnight guests and $49 per person for the Dinner & Mystery only. | http://www.oldvictorianfarmhouse.com/murder_mystery.php | Art/Culture | 1/19/2011     | 12/31/2011  | 60084          |                   | 8475269271  | NULL         | 
```