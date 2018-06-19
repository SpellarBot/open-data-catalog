# Economic Development - Affordable Homes in Cook County - January 7, 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/economic-development-affordable-homes-in-cook-county-january-7-2013-dd93e) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/e9sx-ehrn) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/e9sx-ehrn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/e9sx-ehrn/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | e9sx-ehrn |
| Name | Economic Development - Affordable Homes in Cook County - January 7, 2013 |
| Attribution | Cook County Bureau of Economic Development |
| Category | Economic Development |
| Created | 2013-01-07T21:41:18Z |
| Publication Date | 2014-10-09T22:07:48Z |

## Description

From the Bureau of Economic Development, a dataset of affordable homes for sale in Cook County on January 7, 2013

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       |                | listing_address | Listing Address | text      | text        |
| Yes      | series tag     | listing_city    | Listing City    | text      | text        |
| Yes      | numeric metric | price           | Price           | money     | money       |
| Yes      | series tag     | listing_agent   | Listing Agent   | text      | text        |
| Yes      | series tag     | phone           | Phone           | text      | text        |
| Yes      | series tag     | email           | Email           | email     | email       |
| Yes      | series tag     | notes           | Notes           | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = listing_address
```

## Data Commands

```ls
series e:e9sx-ehrn d:2013-01-01T00:00:00.000Z t:phone=708-367-4325 t:email=Barb@barbbaileyHomes.com t:listing_agent="Barbara Bailey" t:listing_city="Richton Park" m:price=60000

series e:e9sx-ehrn d:2013-01-01T00:00:00.000Z t:phone=708-527-9104 t:email=Staceyrsmith@yahoo.com t:listing_agent="Stacey R Smith" t:listing_city=Dolton m:price=95000

series e:e9sx-ehrn d:2013-01-01T00:00:00.000Z t:phone=708-743-3395 t:email=huerta.david@sbcglobal.net t:listing_agent="David Huerta" t:listing_city="Chicago Heights" m:price=90000
```

## Meta Commands

```ls
metric m:price p:integer l:Price t:dataTypeName=money

entity e:e9sx-ehrn l:"Economic Development - Affordable Homes in Cook County - January 7, 2013" t:attribution="Cook County Bureau of Economic Development" t:url=https://datacatalog.cookcountyil.gov/api/views/e9sx-ehrn

property e:e9sx-ehrn t:meta.view v:id=e9sx-ehrn v:category="Economic Development" v:attributionLink=http://blog.cookcountyil.gov/economicdevelopment/ v:averageRating=0 v:name="Economic Development - Affordable Homes in Cook County - January 7, 2013" v:attribution="Cook County Bureau of Economic Development"

property e:e9sx-ehrn t:meta.view.license v:name="Public Domain"

property e:e9sx-ehrn t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:e9sx-ehrn t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| listing_address          | listing_city    | price | listing_agent   | phone        | email                      | notes                      | 
| ======================== | =============== | ===== | =============== | ============ | ========================== | ========================== | 
| 2802 Knollwood Place     | Hazlecrest      |       |                 |              |                            |                            | 
| 1214 S. 51st Avenue      | Cicero          |       | Ralph Vargas    | 708-717-7170 | Ralph@RalphVargas.com      | Pricing starts at $168,000 | 
| 2626 Spencer Avenue      | Sauk Village    |       | Tom Tomaszewski | 708-960-0356 |                            |                            | 
| 1337-1339 S 49th Avenue  | Cicero          |       | Ralph Vargas    | 708-717-7170 | Ralph@RalphVargas.com      | Pricing starts at $168,000 | 
| 152 E 16th St            | Chicago Heights |       | David Huerta    | 708-743-3395 | huerta.david@sbcglobal.net | Call for price             | 
| 3084 St Ives Lane        | Richton Park    | 60000 | Barbara Bailey  | 708-367-4325 | Barb@barbbaileyHomes.com   |                            | 
| 13825 Forest             | Dolton          | 95000 | Stacey R Smith  | 708-527-9104 | Staceyrsmith@yahoo.com     |                            | 
| 1426-1428 S. 49th Avenue | Cicero          |       | Ralph Vargas    | 708-717-7170 | Ralph@RalphVargas.com      | Pricing starts at $168,000 | 
| 202 E 16th Street        | Chicago Heights | 90000 | David Huerta    | 708-743-3395 | huerta.david@sbcglobal.net |                            | 
| 229 Indianwood           | Park Forest     | 57000 | Lisa Thompson   | 773-317-6265 | Lisa@LisaAThompson.com     |                            | 
```