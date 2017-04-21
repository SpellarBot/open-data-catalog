# Lincoln Square BID Business List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lincoln-square-bid-business-list-14404) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ne9f-g6k4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ne9f-g6k4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ne9f-g6k4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ne9f-g6k4 |
| Name | Lincoln Square BID Business List |
| Attribution | Lincoln Square BID |
| Category | Business |
| Tags | lincoln square bid, lincoln square, bid, businesses, business |
| Created | 2011-07-26T19:59:04Z |
| Publication Date | 2013-06-21T19:30:38Z |

## Description

List of all of the businesses in the Lincoln Square area

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| No       | time        | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | company                      | Company                      | text      | text        |
| Yes      | series tag  | business_address_street      | Business Address Street      | text      | text        |
| No       |             | business_address_city        | Business Address City        | text      | text        |
| No       |             | business_address_state       | Business Address State       | text      | text        |
| No       |             | business_address_postal_code | Business Address Postal Code | text      | text        |
| Yes      | series tag  | phone_business               | Phone Business               | text      | text        |
| Yes      | series tag  | categories                   | Categories                   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = business_address_city,business_address_state,business_address_postal_code
```

## Data Commands

```ls
series e:ne9f-g6k4 d:2011-07-26T12:59:05.000Z t:phone_business="(212) 265-3386" t:business_address_street="1841 Broadway" t:company="American Apparel" t:categories="Business Retail" m:row_number.ne9f-g6k4=1

series e:ne9f-g6k4 d:2011-07-26T12:59:05.000Z t:phone_business="(212) 408-1385" t:business_address_street="1865 Broadway" t:company="American Bible Society Bookstore" t:categories="Business Retail" m:row_number.ne9f-g6k4=2

series e:ne9f-g6k4 d:2011-07-26T12:59:05.000Z t:phone_business="(212) 595 9533 X121" t:business_address_street="125 Columbus Avenue" t:company="American Folk Art Museum Book & Gift Shop" t:categories="Business Retail" m:row_number.ne9f-g6k4=3
```

## Meta Commands

```ls
metric m:row_number.ne9f-g6k4 p:long l:"Row Number"

entity e:ne9f-g6k4 l:"Lincoln Square BID Business List" t:attribution="Lincoln Square BID" t:url=https://data.cityofnewyork.us/api/views/ne9f-g6k4

property e:ne9f-g6k4 t:meta.view v:id=ne9f-g6k4 v:category=Business v:averageRating=0 v:name="Lincoln Square BID Business List" v:attribution="Lincoln Square BID"

property e:ne9f-g6k4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ne9f-g6k4 t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | company                                   | business_address_street | business_address_city | business_address_state | business_address_postal_code | phone_business      | categories      | 
| =========== | ========================================= | ======================= | ===================== | ====================== | ============================ | =================== | =============== | 
| 1311685145  | American Apparel                          | 1841 Broadway           | New York              | NY                     | 10023-                       | (212) 265-3386      | Business Retail | 
| 1311685145  | American Bible Society Bookstore          | 1865 Broadway           | New York              | NY                     | 10023-                       | (212) 408-1385      | Business Retail | 
| 1311685145  | American Folk Art Museum Book & Gift Shop | 125 Columbus Avenue     | New York              | NY                     | 10023-                       | (212) 595 9533 X121 | Business Retail | 
| 1311685145  | Apple Store, Upper West Side              | 1981 Broadway           | New York              | NY                     | 10023                        | (212) 209-3400      | Business Retail | 
| 1311685145  | Banana Republic                           | 1976 Broadway           | New York              | NY                     | 10023-                       | (212) 362-7320      | Business Retail | 
| 1311685145  | Barnes & Noble                            | 1972 Broadway           | New York              | NY                     | 10023                        | (212) 595-6859      | Business Retail | 
| 1311685145  | BCBG Max Azria                            | 2005 Broadway           | New York              | NY                     | 10023-                       | (212) 496-1853      | Business Retail | 
| 1311685145  | Bebe                                      | 10 Columbus Circle      | New York              | NY                     | 10019                        | (212) 262-2690      | Business Retail | 
| 1311685145  | Bolton's                                  | 181 Amsterdam Avenue    | New York              | NY                     | 10023-                       | (212) 362-7396      | Business Retail | 
| 1311685145  | Brooks Brothers                           | 1934 Broadway           | New York              | NY                     | 10023                        | (212) 362-2374      | Business Retail | 
```