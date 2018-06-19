# Family Day Care Homes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/family-day-care-homes) |
| Metadata | [Link](https://data.ct.gov/api/views/4jc3-c5bs) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/4jc3-c5bs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/4jc3-c5bs/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 4jc3-c5bs |
| Name | Family Day Care Homes |
| Attribution | Office of Early Childhood |
| Category | Health and Human Services |
| Tags | oec, day care |
| Created | 2015-03-26T16:56:01Z |
| Publication Date | 2015-03-26T17:01:37Z |

## Description

Family day care homes are private family homes caring for not more than six children, including the provider?s own children not in school full time, where the children are cared for not less than three nor more than twelve hours during a twenty-four hour period and where care is given on a regularly recurring basis, except that care may be provided in excess of twelve hours but not more than seventy-two consecutive hours to accommodate a need for extended care or intermittent short-term overnight care. During the regular school year, a maximum of three additional children who are in school full time, including the provider?s own children, are permitted, except that if the provider has more than three children who are in school full time, all of the provider?s children are permitted.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | license             | License #           | text          | text          |
| Yes      | series tag     | last_name           | Last Name           | text          | text          |
| Yes      | series tag     | first_name          | First Name          | text          | text          |
| Yes      | series tag     | phone               | Phone               | text          | text          |
| Yes      | numeric metric | regular_capacity    | Regular Capacity    | number        | number        |
| Yes      | numeric metric | school_age_capacity | School Age Capacity | number        | number        |
| Yes      | time           | expiration_date     | Expiration Date     | calendar_date | calendar_date |
| No       |                | address             | Address             | text          | text          |
| Yes      | series tag     | city                | City                | text          | text          |
| Yes      | series tag     | zip_code            | Zip Code            | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:4jc3-c5bs d:2018-06-30T00:00:00.000Z t:first_name=KATHLEEN t:phone="(860) 644-5174" t:zip_code=06074 t:last_name=ZAREK t:license=DCFH.31081 t:city="SOUTH WINDSOR" m:school_age_capacity=3 m:regular_capacity=6

series e:4jc3-c5bs d:2017-07-31T00:00:00.000Z t:first_name=JOSEFINA t:phone="(203) 597-1601" t:zip_code=06704 t:last_name=LUIS t:license=DCFH.51429 t:city=WATERBURY m:school_age_capacity=3 m:regular_capacity=6

series e:4jc3-c5bs d:2016-07-31T00:00:00.000Z t:first_name=SHAWN t:phone="(203) 545-3089" t:zip_code=06607-2403 t:last_name=BYRD t:license=DCFH.56162 t:city=BRIDGEPORT m:school_age_capacity=3 m:regular_capacity=6
```

## Meta Commands

```ls
metric m:regular_capacity p:integer l:"Regular Capacity" t:dataTypeName=number

metric m:school_age_capacity p:integer l:"School Age Capacity" t:dataTypeName=number

entity e:4jc3-c5bs l:"Family Day Care Homes" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/4jc3-c5bs

property e:4jc3-c5bs t:meta.view v:id=4jc3-c5bs v:category="Health and Human Services" v:attributionLink=https://www.elicense.ct.gov/ v:averageRating=0 v:name="Family Day Care Homes" v:attribution="Office of Early Childhood"

property e:4jc3-c5bs t:meta.view.license v:name="Public Domain"

property e:4jc3-c5bs t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:4jc3-c5bs t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| license    | last_name | first_name | phone          | regular_capacity | school_age_capacity | expiration_date     | address              | city          | zip_code   | 
| ========== | ========= | ========== | ============== | ================ | =================== | =================== | ==================== | ============= | ========== | 
| DCFH.31081 | ZAREK     | KATHLEEN   | (860) 644-5174 | 6                | 3                   | 2018-06-30T00:00:00 | 38 STEDMAN CIRCLE    | SOUTH WINDSOR | 06074      | 
| DCFH.51429 | LUIS      | JOSEFINA   | (203) 597-1601 | 6                | 3                   | 2017-07-31T00:00:00 | 18 BLACKMAN ROAD     | WATERBURY     | 06704      | 
| DCFH.56162 | BYRD      | SHAWN      | (203) 545-3089 | 6                | 3                   | 2016-07-31T00:00:00 | 290 ADAMS ST FL 1    | BRIDGEPORT    | 06607-2403 | 
| DCFH.56408 | MCCOTTER  | JANIE      | (203) 772-4165 | 6                | 3                   | 2017-12-31T00:00:00 | 225 CLINTON AVE FL 3 | NEW HAVEN     | 06513-2849 | 
| DCFH.53861 | ALLEN     | STACEY     | (860) 429-0551 | 6                | 3                   | 2017-06-30T00:00:00 | 39 SOUTHWORTH DRIVE  | ASHFORD       | 06278      | 
| DCFH.26104 | ROMEO     | PAMELA     | (860) 490-8302 | 6                | 3                   | 2016-10-31T00:00:00 | 4 WEBSTER RD         | ELLINGTON     | 06029-2719 | 
| DCFH.56354 | SUAREZ    | ALBA       | (203) 527-8374 | 6                | 3                   | 2017-09-30T00:00:00 | 332 E MOUNTAIN RD    | WATERBURY     | 06706-2821 | 
| DCFH.25428 | BALESANO  | VIRGINIA   | (860) 635-2536 | 6                | 3                   | 2018-05-31T00:00:00 | 10 BOTELLE MANOR     | CROMWELL      | 06416      | 
| DCFH.56242 | ACKERMAN  | CHRISTA    | (860) 328-6307 | 6                | 3                   | 2017-01-31T00:00:00 | 6 DARTMOUTH RD       | MANCHESTER    | 06040-6614 | 
| DCFH.21761 | MCCOOE    | BARBARA    | (860) 646-9711 | 6                | 3                   | 2018-09-30T00:00:00 | 13 MUNROE STREET     | MANCHESTER    | 06040      | 
```