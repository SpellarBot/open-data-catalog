# Restaurants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/restaurants-15baa) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/k5ry-ef3g) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/k5ry-ef3g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/k5ry-ef3g/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | k5ry-ef3g |
| Name | Restaurants |
| Attribution | City of Baltimore |
| Category | Culture & Arts |
| Tags | food, restaurant |
| Created | 2011-12-14T19:20:41Z |
| Publication Date | 2014-04-03T23:39:45Z |

## Description

This dataset contains a list of restaurants within Baltimore City. The accuracy and completeness of this list is unknown.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | zipcode         | zipCode         | text      | text        |
| Yes      | series tag  | neighborhood    | neighborhood    | text      | text        |
| Yes      | series tag  | councildistrict | councilDistrict | text      | number      |
| Yes      | series tag  | policedistrict  | policeDistrict  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k5ry-ef3g d:2011-12-14T11:21:02.000Z t:zipcode=21206 t:name=410 t:policedistrict=NORTHEASTERN t:neighborhood=Frankford t:councildistrict=2 m:row_number.k5ry-ef3g=1

series e:k5ry-ef3g d:2011-12-14T11:21:02.000Z t:zipcode=21231 t:name=1919 t:policedistrict=SOUTHEASTERN t:neighborhood="Fells Point" t:councildistrict=1 m:row_number.k5ry-ef3g=2

series e:k5ry-ef3g d:2011-12-14T11:21:02.000Z t:zipcode=21224 t:name=SAUTE t:policedistrict=SOUTHEASTERN t:neighborhood=Canton t:councildistrict=1 m:row_number.k5ry-ef3g=3
```

## Meta Commands

```ls
metric m:row_number.k5ry-ef3g p:long l:"Row Number"

entity e:k5ry-ef3g l:Restaurants t:attribution="City of Baltimore" t:url=https://data.baltimorecity.gov/api/views/k5ry-ef3g

property e:k5ry-ef3g t:meta.view d:2017-09-25T07:23:17.692Z v:averageRating=0 v:name=Restaurants v:attribution="City of Baltimore" v:attributionLink=http://www.baltimorecity.gov v:id=k5ry-ef3g v:category="Culture & Arts"

property e:k5ry-ef3g t:meta.view.license d:2017-09-25T07:23:17.692Z v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:k5ry-ef3g t:meta.view.owner d:2017-09-25T07:23:17.692Z v:displayName="Open Baltimore" v:id=6r9a-dfdj v:screenName="Open Baltimore"

property e:k5ry-ef3g t:meta.view.tableauthor d:2017-09-25T07:23:17.692Z v:displayName="Open Baltimore" v:roleName=administrator v:id=6r9a-dfdj v:screenName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                  | zipcode | neighborhood      | councildistrict | policedistrict | 
| =========== | ===================== | ======= | ================= | =============== | ============== | 
| 1323861662  | 410                   | 21206   | Frankford         | 2               | NORTHEASTERN   | 
| 1323861662  | 1919                  | 21231   | Fells Point       | 1               | SOUTHEASTERN   | 
| 1323861662  | SAUTE                 | 21224   | Canton            | 1               | SOUTHEASTERN   | 
| 1323861662  | #1 CHINESE KITCHEN    | 21211   | Hampden           | 14              | NORTHERN       | 
| 1323861662  | #1 chinese restaurant | 21223   | Millhill          | 9               | SOUTHWESTERN   | 
| 1323861662  | 19TH HOLE             | 21218   | Clifton Park      | 14              | NORTHEASTERN   | 
| 1323861662  | 3 KINGS               | 21205   | McElderry Park    | 13              | SOUTHEASTERN   | 
| 1323861662  | 3 MILES HOUSE, INC.   | 21211   | Remington         | 7               | NORTHERN       | 
| 1323861662  | 3 W'S TAVERN          | 21205   | McElderry Park    | 13              | SOUTHEASTERN   | 
| 1323861662  | 300 SOUTH ANN STREET  | 21231   | Upper Fells Point | 1               | SOUTHEASTERN   | 
```