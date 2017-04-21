# Public Information of Open Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-information-of-open-sites-959cf) |
| Metadata | [Link](https://data.seattle.gov/api/views/23t6-xzcc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/23t6-xzcc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/23t6-xzcc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 23t6-xzcc |
| Name | Public Information of Open Sites |
| Attribution | Department of Human Services |
| Category | Community |
| Tags | meal providers, human services, meals, breakfast, lunch, dinner |
| Created | 2010-04-29T21:17:27Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Public meal programs in Seattle

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | geographic_area  | Geographic Area  | text      | text        |
| Yes      | series tag  | program_name     | Program Name     | text      | text        |
| Yes      | series tag  | location         | Location         | text      | text        |
| Yes      | series tag  | phone_number     | Phone Number     | text      | text        |
| Yes      | series tag  | website          | Website          | text      | text        |
| Yes      | series tag  | meal_information | Meal Information | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:23t6-xzcc d:2010-04-29T14:17:34.000Z t:meal_information="Open to all: Friday 10:30 AM" t:phone_number=206-695-7522 t:website=www.acrs.org t:location="3639 MLK Jr. Way S. Seattle, WA 98144" t:program_name="Asian Counseling and Referral Services" t:geographic_area="South Seattle" m:row_number.23t6-xzcc=1

series e:23t6-xzcc d:2010-04-29T14:17:34.000Z t:meal_information="Open to all: See website for schedule of shared meals" t:phone_number="Not Available" t:website=www.communitykitchensnw.org t:location="4437 41st Ave S. Seattle, WA 98188" t:program_name="Community Kitchen Coalition" t:geographic_area="South Seattle" m:row_number.23t6-xzcc=2

series e:23t6-xzcc d:2010-04-29T14:17:34.000Z t:meal_information="Open to all: Serves at various outdoor meal sites on the 2nd and last Saturday each month" t:phone_number=425-985-7852 t:website=www.heroesforthehomeless.org t:location="Various Locations" t:program_name="Heroes for the Homeless" t:geographic_area="South Seattle" m:row_number.23t6-xzcc=3
```

## Meta Commands

```ls
metric m:row_number.23t6-xzcc p:long l:"Row Number"

entity e:23t6-xzcc l:"Public Information of Open Sites" t:attribution="Department of Human Services" t:url=https://data.seattle.gov/api/views/23t6-xzcc

property e:23t6-xzcc t:meta.view v:id=23t6-xzcc v:category=Community v:attributionLink=http://www.seattle.gov/humanservices/ v:averageRating=0 v:name="Public Information of Open Sites" v:attribution="Department of Human Services"

property e:23t6-xzcc t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:23t6-xzcc t:meta.view.owner v:id=zxcy-ghm5 v:screenName="Department of Human Services" v:displayName="Department of Human Services"

property e:23t6-xzcc t:meta.view.tableauthor v:id=zxcy-ghm5 v:screenName="Department of Human Services" v:displayName="Department of Human Services"
```

## Top Records

```ls
| :updated_at | geographic_area | program_name                           | location                                                       | phone_number  | website                      | meal_information                                                                                | 
| =========== | =============== | ====================================== | ============================================================== | ============= | ============================ | =============================================================================================== | 
| 1272550654  | South Seattle   | Asian Counseling and Referral Services | 3639 MLK Jr. Way S. Seattle, WA 98144                          | 206-695-7522  | www.acrs.org                 | Open to all: Friday 10:30 AM                                                                    | 
| 1272550654  | South Seattle   | Community Kitchen Coalition            | 4437 41st Ave S. Seattle, WA 98188                             | Not Available | www.communitykitchensnw.org  | Open to all: See website for schedule of shared meals                                           | 
| 1272550654  | South Seattle   | Heroes for the Homeless                | Various Locations                                              | 425-985-7852  | www.heroesforthehomeless.org | Open to all: Serves at various outdoor meal sites on the 2nd and last Saturday each month       | 
| 1272550654  | South Seattle   | Latino Hot Meal                        | 2524 16th Ave S.W. Seattle, WA 98144                           | 206-329-7960  | www.elcentrodelaraza.org     | Open to all: Monday through Friday 12:00 pm (noon) to 1:00 pm , closed some holidays            | 
| 1272550654  | South Seattle   | St. Vincent de Paul Food Bank          | 5950 4th Ave S. Seattle, WA 98108                              | 206-283-2104  | www.svdpseattle.org          | Open to all: Monday through Friday sandwiches and soup are given out 8:30 am 11:00 am           | 
| 1272550654  | South Seattle   | South Park Breakfast Bunch             | 8201 10th Ave S. Seattle, WA 98108                             | 206-767-3650  | www.allaboutsouthpark.com    | Open to all: Breakfast, Sunday through Friday 5:30 am to 8:30 am                                | 
| 1272550654  | South Seattle   | South Park Senior Meals                | 8201 10th Ave S. Seattle, WA 98108                             | 206-767-3650  | www.allaboutsouthpark.com    | Open to all: Dinner; Monday & Friday 5:30 pm                                                    | 
| 1272550654  | South Seattle   | Latino Lunch                           | 8201 10th Ave S. Seattle, WA 98108                             | 206-764-0494  | www.allaboutsouthpark.com    | Open to all: Lunch; Tuesdays 11:30 am                                                           | 
| 1272550654  | South Seattle   | Samoan American Pacific lunch          | 8201 10th Ave S. Seattle, WA 98108                             | 253-230-7959  | www.allaboutsouthpark.com    | Open to all: Lunch; Wednesdays & Fridays 11:30 am                                               | 
| 1272550654  | Central Seattle | AOK Friends                            | Outdoor Meal Site located under I-5 at 6th & Columbia, Seattle | Not Available | No Website                   | Open to all: Every Sunday, Lunch 1:00 pm to 2:00 pm (3rd Sunday meal served at Noon to 1:00 pm) | 
```