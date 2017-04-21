# Museum Visitors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/museum-visitors) |
| Metadata | [Link](https://data.lacity.org/api/views/trxm-jn3c) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/trxm-jn3c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/trxm-jn3c/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | trxm-jn3c |
| Name | Museum Visitors |
| Attribution | El Pueblo Historical Monument |
| Category | A Livable and Sustainable City |
| Tags | museums |
| Created | 2014-05-29T22:51:45Z |
| Publication Date | 2017-03-20T22:48:22Z |

## Description

Individual visits to El Pueblo museums, per month.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| Yes      | time           | month                                | Month                                | calendar_date | calendar_date |
| Yes      | numeric metric | america_tropical_interpretive_center | America Tropical Interpretive Center | number        | number        |
| Yes      | numeric metric | avila_adobe                          | Avila Adobe                          | number        | number        |
| Yes      | numeric metric | chinese_american_museum              | Chinese American Museum              | number        | number        |
| Yes      | numeric metric | firehouse_museum                     | Firehouse Museum                     | number        | number        |
| Yes      | numeric metric | hellman_quon                         | Hellman Quon                         | number        | number        |
| Yes      | numeric metric | pico_house                           | Pico House                           | number        | number        |
| Yes      | numeric metric | visitor_center_avila_adobe           | Visitor Center (Avila Adobe)         | number        | number        |
| Yes      | numeric metric | iamla                                | IAMLA                                | number        | number        |
| Yes      | numeric metric | biscailuz_gallery                    | Biscailuz Gallery                    | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:trxm-jn3c d:2014-01-01T00:00:00.000Z m:pico_house=2204 m:hellman_quon=0 m:firehouse_museum=4486 m:visitor_center_avila_adobe=2961 m:chinese_american_museum=1581 m:america_tropical_interpretive_center=6602 m:avila_adobe=24778

series e:trxm-jn3c d:2014-02-01T00:00:00.000Z m:pico_house=1330 m:hellman_quon=0 m:firehouse_museum=4172 m:visitor_center_avila_adobe=2276 m:chinese_american_museum=1785 m:america_tropical_interpretive_center=5029 m:avila_adobe=18976

series e:trxm-jn3c d:2014-03-01T00:00:00.000Z m:pico_house=4320 m:hellman_quon=70 m:firehouse_museum=7082 m:visitor_center_avila_adobe=3116 m:chinese_american_museum=3229 m:america_tropical_interpretive_center=8129 m:avila_adobe=25231
```

## Meta Commands

```ls
metric m:america_tropical_interpretive_center p:integer l:"America Tropical Interpretive Center" t:dataTypeName=number

metric m:avila_adobe p:integer l:"Avila Adobe" t:dataTypeName=number

metric m:chinese_american_museum p:integer l:"Chinese American Museum" t:dataTypeName=number

metric m:firehouse_museum p:integer l:"Firehouse Museum" t:dataTypeName=number

metric m:hellman_quon p:integer l:"Hellman Quon" t:dataTypeName=number

metric m:pico_house p:integer l:"Pico House" t:dataTypeName=number

metric m:visitor_center_avila_adobe p:integer l:"Visitor Center (Avila Adobe)" t:dataTypeName=number

metric m:iamla p:integer l:IAMLA d:"Italian American Museum" t:dataTypeName=number

metric m:biscailuz_gallery p:integer l:"Biscailuz Gallery" t:dataTypeName=number

entity e:trxm-jn3c l:"Museum Visitors" t:attribution="El Pueblo Historical Monument" t:url=https://data.lacity.org/api/views/trxm-jn3c

property e:trxm-jn3c t:meta.view v:id=trxm-jn3c v:category="A Livable and Sustainable City" v:attributionLink=http://elpueblo.lacity.org/index.htm v:averageRating=0 v:name="Museum Visitors" v:attribution="El Pueblo Historical Monument"

property e:trxm-jn3c t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:trxm-jn3c t:meta.view.owner v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:displayName="El Pueblo OpenData"

property e:trxm-jn3c t:meta.view.tableauthor v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:roleName=publisher v:displayName="El Pueblo OpenData"
```

## Top Records

```ls
| month               | america_tropical_interpretive_center | avila_adobe | chinese_american_museum | firehouse_museum | hellman_quon | pico_house | visitor_center_avila_adobe | iamla | biscailuz_gallery | 
| =================== | ==================================== | =========== | ======================= | ================ | ============ | ========== | ========================== | ===== | ================= | 
| 2014-01-01T00:00:00 | 6602                                 | 24778       | 1581                    | 4486             | 0            | 2204       | 2961                       |       |                   | 
| 2014-02-01T00:00:00 | 5029                                 | 18976       | 1785                    | 4172             | 0            | 1330       | 2276                       |       |                   | 
| 2014-03-01T00:00:00 | 8129                                 | 25231       | 3229                    | 7082             | 70           | 4320       | 3116                       |       |                   | 
| 2014-04-01T00:00:00 | 2824                                 | 26989       | 2129                    | 6756             | 250          | 3277       | 2808                       |       |                   | 
| 2014-05-01T00:00:00 | 10694                                | 36883       | 3676                    | 10858            | 135          | 4122       | 3987                       |       |                   | 
| 2014-06-01T00:00:00 | 11036                                | 29487       | 2121                    | 5751             | 255          | 355        | 3133                       |       |                   | 
| 2014-07-01T00:00:00 | 13490                                | 32378       | 2239                    | 5406             | 120          | 3375       | 3527                       |       |                   | 
| 2014-08-01T00:00:00 | 9139                                 | 37680       | 1769                    | 8619             | 250          | 1550       | 0                          |       |                   | 
| 2014-09-01T00:00:00 | 5661                                 | 28473       | 1073                    | 61192            | 1145         | 1335       | 0                          |       |                   | 
| 2014-10-01T00:00:00 | 7356                                 | 27995       | 1979                    | 6488             | 550          | 1518       | 0                          |       |                   | 
```