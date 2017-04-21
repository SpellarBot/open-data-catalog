# Union Square Partnership (USP) Business List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/union-square-partnership-usp-business-list-b7713) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/p6bh-gqsg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/p6bh-gqsg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/p6bh-gqsg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | p6bh-gqsg |
| Name | Union Square Partnership (USP) Business List |
| Attribution | Union Square Partnership (USP) |
| Category | Business |
| Tags | union square partnership, usp, business, directory, 14th street |
| Created | 2011-10-11T04:22:35Z |
| Publication Date | 2013-06-21T19:27:52Z |

## Description

Directory of businesses in the Union Square area

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | category         | Category         | text      | text        |
| Yes      | series tag  | type_of_business | Type of Business | text      | text        |
| Yes      | series tag  | business         | Business         | text      | text        |
| No       |             | parsed_address   | Parsed Address   | number    | number      |
| Yes      | series tag  | city_state       | City/State       | text      | text        |
| Yes      | series tag  | zip_code         | Zip Code         | text      | number      |
| Yes      | series tag  | phone_number     | Phone Number     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = parsed_address
```

## Data Commands

```ls
series e:p6bh-gqsg d:2011-10-10T21:22:43.000Z t:category="Points of Interest" t:phone_number=212-788-7476 t:zip_code=10003 t:city_state="New York, NY" t:type_of_business=Landmarks t:business=Greenmarket m:row_number.p6bh-gqsg=1

series e:p6bh-gqsg d:2011-10-10T21:22:45.000Z t:category=Services t:zip_code=10003 t:city_state="New York, NY" t:type_of_business="Cleaners and Shoe Repair" t:business="Alpine Cleaners and Tailors" m:row_number.p6bh-gqsg=2

series e:p6bh-gqsg d:2011-10-10T21:22:55.000Z t:category="Food and Drink" t:phone_number=212-777-6663 t:zip_code=10003 t:city_state="New York, NY" t:type_of_business="Bars and Lounges" t:business="Bar None" m:row_number.p6bh-gqsg=3
```

## Meta Commands

```ls
metric m:row_number.p6bh-gqsg p:long l:"Row Number"

entity e:p6bh-gqsg l:"Union Square Partnership (USP) Business List" t:attribution="Union Square Partnership (USP)" t:url=https://data.cityofnewyork.us/api/views/p6bh-gqsg

property e:p6bh-gqsg t:meta.view v:id=p6bh-gqsg v:category=Business v:averageRating=0 v:name="Union Square Partnership (USP) Business List" v:attribution="Union Square Partnership (USP)"

property e:p6bh-gqsg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:p6bh-gqsg t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | category           | type_of_business         | business                    | parsed_address | city_state   | zip_code | phone_number | 
| =========== | ================== | ======================== | =========================== | ============== | ============ | ======== | ============ | 
| 1318281763  | Points of Interest | Landmarks                | Greenmarket                 |                | New York, NY | 10003    | 212-788-7476 | 
| 1318281765  | Services           | Cleaners and Shoe Repair | Alpine Cleaners and Tailors |                | New York, NY | 10003    |              | 
| 1318281775  | Food and Drink     | Bars and Lounges         | Bar None                    | 98             | New York, NY | 10003    | 212-777-6663 | 
| 1318281775  | Food and Drink     | Bars and Lounges         | Belmont Lounge              | 117            | New York, NY | 10003    | 212-533-0009 | 
| 1318281775  | Food and Drink     | Bars and Lounges         | Cibar Lounge                | 56             | New York, NY | 10003    | 212-460-5656 | 
| 1318281775  | Food and Drink     | Bars and Lounges         | Bar 13                      | 35             | New York, NY | 10003    | 212-979-6677 | 
| 1318281775  | Food and Drink     | Bars and Lounges         | Blatt Billiards             | 809            | New York, NY | 10003    | 212-674-8855 | 
| 1318281775  | Food and Drink     | Bars and Lounges         | Finnerty's                  | 221            | New York, NY | 10003    | 212-677-2655 | 
| 1318281775  | Food and Drink     | Bars and Lounges         | Flute Bar                   | 40             | New York, NY | 10003    | 212-529-7870 | 
| 1318281775  | Food and Drink     | Bars and Lounges         | Karaoke One 7               | 29             | New York, NY | 10011    | 212-675-3527 | 
```