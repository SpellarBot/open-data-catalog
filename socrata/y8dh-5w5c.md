# Medical Examiner - Unidentified Persons

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-unidentified-persons) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/y8dh-5w5c) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/y8dh-5w5c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/y8dh-5w5c/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | y8dh-5w5c |
| Name | Medical Examiner - Unidentified Persons |
| Attribution | Cook County Medical Examiner |
| Category | Healthcare |
| Created | 2016-06-23T00:57:30Z |
| Publication Date | 2017-03-22T18:10:22Z |

## Description

This dataset contains descriptions of unidentified remains whose cases have been processed by the Medical Examiner?s Office.

Call 312-666-0500 to speak to Chief Investigator, Christopher Kalka, about matching one of these unidentified bodies to the identity of a missing person. Descriptions of cases can also be found at NAMUS.gov

Please note that images posted in this section may be graphic in nature and may not be appropriate for all users.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | case_number      | Case Number      | text          | text          |
| Yes      | time        | date_found       | Date Found       | calendar_date | calendar_date |
| Yes      | series tag  | location_found   | Location Found   | text          | text          |
| Yes      | series tag  | location_details | Location Details | text          | text          |
| Yes      | series tag  | description      | Description      | text          | text          |
| Yes      | series tag  | image_1          | Image 1          | url           | url           |
| Yes      | series tag  | image_2          | Image 2          | url           | url           |
```

## Time Field

```ls
Value = date_found
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:y8dh-5w5c d:2014-05-10T00:00:00.000Z t:case_number="163 MAY 14" t:description="Male
Clothing: brown striped shirt, white t-shirt, brown/black pants with a brown belt, white briefs, white boxer underwear, black stocking. A burlap bag is also received." t:location_found="4816 W. Ferdinand Ave. Chicago, IL 60644" m:row_number.y8dh-5w5c=1

series e:y8dh-5w5c d:2014-04-21T00:00:00.000Z t:case_number="311 APR 14" t:description="Black Male, appearing at least 40 years of age
5?9?, 129lbs.
Straight black hair with gray streaks, black beard
Clothing: white t-shirt, blue jeans, gray pants, blue socks" t:image_1=http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/sketches/311-Apr-14-sketch-with-words_sm.jpg t:location_details="Found in an abandoned residence" t:location_found="6222 S. Paulina
Chicago, IL 60636" m:row_number.y8dh-5w5c=2

series e:y8dh-5w5c d:2014-04-11T00:00:00.000Z t:case_number="162 APR 14" t:description="Male
5?7"", 150 lbs.
clothing: fragments of gray hooded sweatshirt and black t-shirt" t:location_found="Chicago River
near 700 S Wells Street" m:row_number.y8dh-5w5c=3
```

## Meta Commands

```ls
metric m:row_number.y8dh-5w5c p:long l:"Row Number"

entity e:y8dh-5w5c l:"Medical Examiner - Unidentified Persons" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/y8dh-5w5c

property e:y8dh-5w5c t:meta.view v:id=y8dh-5w5c v:category=Healthcare v:averageRating=0 v:name="Medical Examiner - Unidentified Persons" v:attribution="Cook County Medical Examiner"

property e:y8dh-5w5c t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:y8dh-5w5c t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| case_number | date_found          | location_found                           | location_details                | description                                                                                                                                                                                                                                                                                                                               | image_1                                                                                                                       | image_2                                                                                                           | 
| =========== | =================== | ======================================== | =============================== | ========================================================================================================================================================================================================================================================================================================================================= | ============================================================================================================================= | ================================================================================================================= | 
| 163 MAY 14  | 2014-05-10T00:00:00 | 4816 W. Ferdinand Ave. Chicago, IL 60644 |                                 | Male Clothing: brown striped shirt, white t-shirt, brown/black pants with a brown belt, white briefs, white boxer underwear, black stocking. A burlap bag is also received.                                                                                                                                                               | [null, null]                                                                                                                  | [null, null]                                                                                                      | 
| 311 APR 14  | 2014-04-21T00:00:00 | 6222 S. Paulina Chicago, IL 60636        | Found in an abandoned residence | Black Male, appearing at least 40 years of age 5?9?, 129lbs. Straight black hair with gray streaks, black beard Clothing: white t-shirt, blue jeans, gray pants, blue socks                                                                                                                                                               | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/sketches/311-Apr-14-sketch-with-words_sm.jpg, Sketch] | [null, null]                                                                                                      | 
| 162 APR 14  | 2014-04-11T00:00:00 | Chicago River near 700 S Wells Street    |                                 | Male 5?7", 150 lbs. clothing: fragments of gray hooded sweatshirt and black t-shirt                                                                                                                                                                                                                                                       | [null, null]                                                                                                                  | [null, null]                                                                                                      | 
| 342 Jan 14  | 2014-01-21T00:00:00 | 3272 W. Fullerton, Chicago, IL 60647     |                                 | White Male, 178 lbs., 5?9? Straight gray hair up to 1-1/2? long with a receded hairline and balding on the frontoparietal scalp, gray mustache and beard Brown eyes Clothes:  blue hooded jacket (Blue Ink Apparel, 2XL), brown leather belt (38 inches), brown corduroy pants (Nautica Rigger 36W x 34 L), black leather boots (size 11) | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/warning_342JAN14.html, Photo]                         | [null, null]                                                                                                      | 
| 199 Nov 13  | 2013-11-12T00:00:00 | 7147 S. University, Chicago, IL 60619    | Found in abandoned building     | Black Male 5?9? to 6?4? height range Approximately 35 to 50 years of age Black, curly hair and black beard Known to be called ?Pops? Clothes:  green scrub top-Medline Encore size extra large.  A gray blanket accompanies the body.                                                                                                     | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/sketches/199-NOV-13.jpg, Sketch]                      | [null, null]                                                                                                      | 
| 511 JUL 13  | 2013-07-29T00:00:00 | 1059 N. Clark Chicago, IL                |                                 | Black female, 50?s, 160 lbs., 5?6" Black hair with gray, Brown eyes Earlobes are pierced: faint scars on buttocks. Clothes: white Hanes XXL t-shirt, black Crocs, white nylon socks, white Jerzees medium t-shirt, black and brown Hanes premium size medium sweatpants                                                                   | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/warning_511JUL13.html, Photo]                         | [null, null]                                                                                                      | 
| 031 MAY 13  | 2013-05-02T00:00:00 | 4053 W. School Chicago, IL               |                                 | White male, 50?s, 149 lbs., 5?11? Brown with gray hair, slightly gray beard Clothes: blue jacket, brown leather jacket, blue sweater, 2 blue t-shirts, blue denim jeans, blue boxer briefs, yellow sock, white and blue shoes                                                                                                             | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/sketches/031-MAY-13-final.jpg, Sketch]                | [null, null]                                                                                                      | 
| 092 DEC 12  | 2012-12-05T00:00:00 | 1623 W. 21 St. Chicago, IL               |                                 | White Hispanic male, 30?s, 234 lbs., 5?5" Black hair, black mustache and beard, brown eyes Clothes: brown fleece jacket, blue jacket, black jeans, white socks, and black and white shoes. Found in alley                                                                                                                                 | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/warning_092DEC12.html, Photo]                         | [null, null]                                                                                                      | 
| 081 NOV 12  | 2012-11-05T00:00:00 | 626 E. 111th St., Chicago, IL            |                                 | White female, approximately 20 yrs. old, 134 lbs., 5?8" Medium length brown hair, brown eyes Clothes: Black sweatshirt, white undershirt, blue jeans, and blue boxer shorts Found in parking lot of recycling center                                                                                                                      | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/sketches/081-Nov-12_retouch.jpg, Sketch]              | [null, null]                                                                                                      | 
| 377 AUG 12  | 2012-08-21T00:00:00 | 3203 W. Cermak Rd. Chicago, IL           | Found in abandoned building     | Decomposed individual, 38 lbs, 4?9" Short black hair. Red/black facial hair on chin and philtrum Tattoo of wings and a parachute on posterior aspect of right forearm. Scorpion on the posterior aspect of left forearm Clothes: Blue jeans, brown sneakers                                                                               | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/sketches/377-AUG-12.jpg, Sketch 1]                    | [http://opendocs.cookcountyil.gov/medical-examiner/unidentified-persons/sketches/377-Aug-12-tattoo.jpg, Sketch 2] | 
```