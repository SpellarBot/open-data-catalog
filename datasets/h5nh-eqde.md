# Columbus Avenue BID Businesses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/columbus-avenue-bid-businesses-4c7fd) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h5nh-eqde) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h5nh-eqde/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h5nh-eqde/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h5nh-eqde |
| Name | Columbus Avenue BID Businesses |
| Attribution | Columbus Avenue BID |
| Category | Business |
| Tags | columbus avenue, business improvement district, bid, merchant, merchandise, shop, shopping, business, sales, food, coffee, tea, shoes, services, hotels, entertainment, children?s store, clothing, ... |
| Created | 2011-09-09T20:29:29Z |
| Publication Date | 2013-06-21T19:29:27Z |
| Rows Updated | 2013-06-21T19:29:23Z |

## Description

A listing of all the shops in the Columbus Avenue Business Improvement District (BID) which runs along Columbus Avenue from  W 82nd St to W 67th (only to 68th on the west side of the street).
Update Frequency: As needed

## Columns

```ls
| Included | Schema Type | Field Name            | Name                    | Data Type | Render Type |
| ======== | =========== | ===================== | ======================= | ========= | =========== |
| No       | time        | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | shop_name             | Shop Name               | text      | text        |
| Yes      | series tag  | telephone             | Telephone               | text      | text        |
| Yes      | series tag  | store_type_category_1 | Store Type (category 1) | text      | text        |
| Yes      | series tag  | store_type_category_2 | Store Type (category 2) | text      | text        |
| Yes      | series tag  | store_type_category_3 | Store Type (category 3) | text      | text        |
| Yes      | series tag  | website               | website                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:h5nh-eqde l:"Columbus Avenue BID Businesses" t:attribution="Columbus Avenue BID" t:url=https://data.cityofnewyork.us/api/views/h5nh-eqde

property e:h5nh-eqde t:meta.view v:id=h5nh-eqde v:category=Business v:averageRating=0 v:name="Columbus Avenue BID Businesses" v:attribution="Columbus Avenue BID"

property e:h5nh-eqde t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:h5nh-eqde t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```