# Museums

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/museums-8ab53) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/8hgq-9pi6) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/8hgq-9pi6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/8hgq-9pi6/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 8hgq-9pi6 |
| Name | Museums |
| Attribution | City of Baltimore |
| Category | Culture & Arts |
| Tags | museum, culture, art |
| Created | 2011-12-14T18:31:10Z |
| Publication Date | 2014-04-03T23:57:10Z |

## Description

This data set shows the location of museums within the City of Baltimore. However, this is not a complete list.

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
series e:8hgq-9pi6 d:2011-12-14T10:31:41.000Z t:councildistrict=12 t:zipcode=21201 t:name="American Dime Museum" t:neighborhood="Charles North" t:policedistrict=CENTRAL m:row_number.8hgq-9pi6=1

series e:8hgq-9pi6 d:2011-12-14T10:31:41.000Z t:councildistrict=1 t:zipcode=21231 t:name="American Indian Museum" t:neighborhood="Washington Hill" t:policedistrict=SOUTHEASTERN m:row_number.8hgq-9pi6=2

series e:8hgq-9pi6 d:2011-12-14T10:31:41.000Z t:councildistrict=11 t:zipcode=21230 t:name="American Visionary Art Museum" t:neighborhood="Federal Hill" t:policedistrict=SOUTHERN m:row_number.8hgq-9pi6=3
```

## Meta Commands

```ls
metric m:row_number.8hgq-9pi6 p:long l:"Row Number"

entity e:8hgq-9pi6 l:Museums t:attribution="City of Baltimore" t:url=https://data.baltimorecity.gov/api/views/8hgq-9pi6

property e:8hgq-9pi6 t:meta.view v:id=8hgq-9pi6 v:category="Culture & Arts" v:attributionLink=http://www.baltimorecity.gov v:averageRating=0 v:name=Museums v:attribution="City of Baltimore"

property e:8hgq-9pi6 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:8hgq-9pi6 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:8hgq-9pi6 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                             | zipcode | neighborhood           | councildistrict | policedistrict | 
| =========== | ================================ | ======= | ====================== | =============== | ============== | 
| 1323858701  | American Dime Museum             | 21201   | Charles North          | 12              | CENTRAL        | 
| 1323858701  | American Indian Museum           | 21231   | Washington Hill        | 1               | SOUTHEASTERN   | 
| 1323858701  | American Visionary Art Museum    | 21230   | Federal Hill           | 11              | SOUTHERN       | 
| 1323858701  | B. Olive Cole Pharmacy Museum    | 21201   | University Of Maryland | 11              | CENTRAL        | 
| 1323858701  | Babe Ruth Birthplace and Museum  | 21230   | Ridgely's Delight      | 11              | SOUTHERN       | 
| 1323858701  | Baltimore American Indian Center | 21231   | Upper Fells Point      | 1               | SOUTHEASTERN   | 
| 1323858701  | Baltimore City Fire Museum       | 21202   | Oldtown                | 12              | EASTERN        | 
| 1323858701  | Baltimore Civil War Museum       | 21202   | Inner Harbor           | 1               | SOUTHEASTERN   | 
| 1323858701  | Baltimore Clayworks              | 21209   | Mount Washington       | 5               | NORTHERN       | 
| 1323858701  | Baltimore Maritime Museum        | 21202   | Inner Harbor           | 11              | CENTRAL        | 
```