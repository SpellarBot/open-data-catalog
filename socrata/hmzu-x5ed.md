# Meals Programs in Seattle

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/meals-programs-in-seattle-de35a) |
| Metadata | [Link](https://data.seattle.gov/api/views/hmzu-x5ed) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/hmzu-x5ed/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/hmzu-x5ed/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | hmzu-x5ed |
| Name | Meals Programs in Seattle |
| Attribution | Department of Human Services |
| Category | Community |
| Tags | meal providers, human services, meals, breakfast, lunch, dinner |
| Created | 2010-04-28T22:05:58Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

This data set provides the names, locations, and service days of meal programs that serve free meals to low-income and homeless people in Seattle. It also provides the kinds of meals served.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| No       |             | day_time        | Day_Time        | text      | text        |
| Yes      | series tag  | meal_served     | Meal_Served     | text      | text        |
| Yes      | series tag  | people_served   | People_Served   | text      | text        |
| Yes      | series tag  | location        | Location        | text      | text        |
| Yes      | series tag  | name_of_program | Name_of_Program | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = day_time
```

## Data Commands

```ls
series e:hmzu-x5ed d:2010-04-29T09:11:32.000Z t:people_served="OPEN TO ALL" t:meal_served=Breakfast t:name_of_program="Millionair Club Charity" t:location="2515 Western Ave.,  Seattle" m:row_number.hmzu-x5ed=1

series e:hmzu-x5ed d:2010-04-29T09:11:32.000Z t:people_served="OPEN TO ALL" t:meal_served=Breakfast t:name_of_program="South Park Breakfast Bunch" t:location="8201 10th Ave S., Seattle" m:row_number.hmzu-x5ed=2

series e:hmzu-x5ed d:2010-04-29T09:11:32.000Z t:people_served="AMERICAN INDIANS ONLY" t:name_of_program="Chief Seattle Club" t:location="410 2nd Ave. Extension So., Seattle" m:row_number.hmzu-x5ed=3
```

## Meta Commands

```ls
metric m:row_number.hmzu-x5ed p:long l:"Row Number"

entity e:hmzu-x5ed l:"Meals Programs in Seattle" t:attribution="Department of Human Services" t:url=https://data.seattle.gov/api/views/hmzu-x5ed

property e:hmzu-x5ed t:meta.view v:id=hmzu-x5ed v:category=Community v:attributionLink=http://www.seattle.gov/humanservices/ v:averageRating=0 v:name="Meals Programs in Seattle" v:attribution="Department of Human Services"

property e:hmzu-x5ed t:meta.view.license v:name="Public Domain"

property e:hmzu-x5ed t:meta.view.owner v:id=zxcy-ghm5 v:screenName="Department of Human Services" v:displayName="Department of Human Services"

property e:hmzu-x5ed t:meta.view.tableauthor v:id=zxcy-ghm5 v:screenName="Department of Human Services" v:displayName="Department of Human Services"
```

## Top Records

```ls
| :updated_at | day_time                                                                                                                                                                | meal_served | people_served                 | location                                       | name_of_program                         | 
| =========== | ======================================================================================================================================================================= | =========== | ============================= | ============================================== | ======================================= | 
| 1272532292  | Monday - Friday: 6:15 - 7:00 A.M.                                                                                                                                       | Breakfast   | OPEN TO ALL                   | 2515 Western Ave., Seattle                     | Millionair Club Charity                 | 
| 1272532292  | Sunday - Thursday 5:30 - 8:30 A.M.                                                                                                                                      | Breakfast   | OPEN TO ALL                   | 8201 10th Ave S., Seattle                      | South Park Breakfast Bunch              | 
| 1272532292  | Monday - Friday 7:00 - 9:30 A.M.                                                                                                                                        |             | AMERICAN INDIANS ONLY         | 410 2nd Ave. Extension So., Seattle            | Chief Seattle Club                      | 
| 1272532292  | Chapel required prior to meal service. There are 3 daily Chapel services to choose from: 7-7:30 A.M., 7:45-8:15 A.M., 8:30-9 A.M. (Meal served following each service.) | Breakfast   | OPEN TO ALL                   | 318 2nd Ave. S. Extension, Seattle             | Union Gospel Mission                    | 
| 1272532292  | Monday - Friday: 8:30 - 11:00 A.M. (Sack lunch for the day)                                                                                                             | Breakfast   | OPEN TO ALL                   | 232 Warren Ave. North, Suite B, Seattle        | Sacred Heart Church/SVDP Society        | 
| 1272532292  | Daily: 1st seating is 7:20 - 7:50 A.M. (overnight guests only) 2nd seating is 8:10 - 8:40 A.M. (day program clients)                                                    | Breakfast   | WOMEN 18 AND OLDER            | 2030 3rd Ave, Seattle                          | YWCA Angeline's Meals Program           | 
| 1272532292  | 3 Breakfasts per week on variable days: 8:00 A.M.                                                                                                                       | Breakfast   | OPEN TO 55+                   | 85 Pike St. #200, Seattle                      | Pike Market Senior Center               | 
| 1272532292  | Daily: 8:00 A.M.                                                                                                                                                        | Breakfast   | OPEN TO MEN 50+               | 1561 Alaskan Way S., Seattle                   | Saint Martin's de Porres Shelter        | 
| 1272532292  | Monday - Friday: Breakfast 8:00 - 9:00 A.M.                                                                                                                             | Breakfast   | OPEN TO ALL                   | Outdoor Meal Site at 6th and Columbia, Seattle | Operation Sack Lunch                    | 
| 1272532292  | Monday - Friday: 8:30 - 9:30 A.M.; Saturdays: 10:00 A.M.                                                                                                                | Breakfast   | OPEN TO WOMEN & CHILDREN ONLY | 210 Dexter Avenue, Seattle                     | Mary's Place / Church of Mary Magdalene | 
```