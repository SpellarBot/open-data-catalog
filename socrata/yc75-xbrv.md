# Adult Day Care Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adult-day-care-facilities-a2dd6) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/yc75-xbrv) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/yc75-xbrv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/yc75-xbrv/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | yc75-xbrv |
| Name | Adult Day Care Facilities |
| Attribution | Baltimore City Commission on Aging and Retirement |
| Category | Health |
| Tags | adult day care, day care |
| Created | 2011-12-14T15:16:50Z |
| Publication Date | 2014-04-03T23:41:35Z |

## Description

This data set provides the location of adult day care facilities within the City of Baltimore. The list of facilities is from the Maryland Office of Health Care and Quality (OHCQ). EGIS gets the data indirectly from the Baltimore City Commission on Aging and Retirement Education (CARE).

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | neighborhood    | neighborhood    | text      | text        |
| Yes      | series tag  | zipcode         | zipCode         | text      | text        |
| Yes      | series tag  | councildistrict | councilDistrict | text      | number      |
| Yes      | series tag  | policedistrict  | policeDistrict  | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yc75-xbrv d:2011-12-14T07:17:35.000Z t:councildistrict=9 t:zipcode=21223 t:name="ACTIVE DAY OF MOUNT CLARE" t:neighborhood="Washington Village" t:policedistrict=9 m:row_number.yc75-xbrv=1

series e:yc75-xbrv d:2011-12-14T07:17:35.000Z t:councildistrict=2 t:zipcode=21206 t:name="ADULT MEDICAL DAY CARE OF OVERLEA" t:neighborhood=Glenham-Belford t:policedistrict=4 m:row_number.yc75-xbrv=2

series e:yc75-xbrv d:2011-12-14T07:17:35.000Z t:councildistrict=11 t:zipcode=21201 t:name="ELEANOR EVANS HOOPER ADULT DAY CARE" t:neighborhood="Mid-Town Belvedere" t:policedistrict=1 m:row_number.yc75-xbrv=3
```

## Meta Commands

```ls
metric m:row_number.yc75-xbrv p:long l:"Row Number"

entity e:yc75-xbrv l:"Adult Day Care Facilities" t:attribution="Baltimore City Commission on Aging and Retirement" t:url=https://data.baltimorecity.gov/api/views/yc75-xbrv

property e:yc75-xbrv t:meta.view v:id=yc75-xbrv v:category=Health v:attributionLink=http://baltimorehealth.org/care.html v:averageRating=0 v:name="Adult Day Care Facilities" v:attribution="Baltimore City Commission on Aging and Retirement"

property e:yc75-xbrv t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:yc75-xbrv t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:yc75-xbrv t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                                 | neighborhood         | zipcode | councildistrict | policedistrict | 
| =========== | ==================================== | ==================== | ======= | =============== | ============== | 
| 1323847055  | ACTIVE DAY OF MOUNT CLARE            | Washington Village   | 21223   | 9               | 9              | 
| 1323847055  | ADULT MEDICAL DAY CARE OF OVERLEA    | Glenham-Belford      | 21206   | 2               | 4              | 
| 1323847055  | ELEANOR EVANS HOOPER ADULT DAY CARE  | Mid-Town Belvedere   | 21201   | 11              | 1              | 
| 1323847055  | EXTENDED FAMILT ADULT DAY CARE, INC. | Rognel Heights       | 21229   | 8               | 8              | 
| 1323847055  | FEHSENFELD MEDICAL DAY CARE          | New Northwood        | 21239   | 3               | 4              | 
| 1323847055  | GOLDEN POND ADULT DAY PROGRAM, INC.  | Frankford            | 21206   | 2               | 4              | 
| 1323847055  | GRACE OUTREACH ADULTDAY CARE         | Cylburn              | 21215   | 6               | 5              | 
| 1323847055  | HAPPY DAYS ADULT DAY CARE            | Central Park Heights | 21215   | 6               | 6              | 
| 1323847055  | INTERVALS, INC.                      | Seton Business Park  | 21215   | 5               | 6              | 
| 1323847055  | JUEL'S MEDICAL ADULT DAY CARE CENTER | Ashburton            | 21215   | 6               | 6              | 
```