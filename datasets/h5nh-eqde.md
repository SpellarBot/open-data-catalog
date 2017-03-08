# Columbus Avenue BID Businesses

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/h5nh-eqde/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/columbus-avenue-bid-businesses-4c7fd)
* [Metadata URL](https://data.cityofnewyork.us/api/views/h5nh-eqde)
* Id = h5nh-eqde
* Name = Columbus Avenue BID Businesses
* Attribution = Columbus Avenue BID
* Category = Business
* Tags = [columbus avenue, business improvement district, bid, merchant, merchandise, shop, shopping, business, sales, food, coffee, tea, shoes, services, hotels, entertainment, children?s store, clothing, ...
* Created = 2011-09-09T20:29:29Z
* Publication Date = 2013-06-21T19:29:27Z
* Rows Updated = 2013-06-21T19:29:23Z

## Description

A listing of all the shops in the Columbus Avenue Business Improvement District (BID) which runs along Columbus Avenue from  W 82nd St to W 67th (only to 68th on the west side of the street).
Update Frequency: As needed

## Columns

```ls
| Name                    | Field Name            | Data Type | Render Type | Schema Type | Included | 
| ======================= | ===================== | ========= | =========== | =========== | ======== | 
| updated_at              | :updated_at           | meta_data | meta_data   | time        | No       | 
| Shop Name               | shop_name             | text      | text        | series tag  | Yes      | 
| Telephone               | telephone             | text      | text        | series tag  | Yes      | 
| Store Type (category 1) | store_type_category_1 | text      | text        | series tag  | Yes      | 
| Store Type (category 2) | store_type_category_2 | text      | text        | series tag  | Yes      | 
| Store Type (category 3) | store_type_category_3 | text      | text        | series tag  | Yes      | 
| website                 | website               | text      | text        | series tag  | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:h5nh-eqde l:"Columbus Avenue BID Businesses" t:attribution="Columbus Avenue BID" t:url=https://data.cityofnewyork.us/api/views/h5nh-eqde

property e:h5nh-eqde t:meta.view d:2017-03-08T01:28:15.691Z v:id=h5nh-eqde v:category=Business v:averageRating=0 v:name="Columbus Avenue BID Businesses" v:attribution="Columbus Avenue BID"

property e:h5nh-eqde t:meta.view.owner d:2017-03-08T01:28:15.691Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:h5nh-eqde t:meta.view.tableauthor d:2017-03-08T01:28:15.691Z v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```