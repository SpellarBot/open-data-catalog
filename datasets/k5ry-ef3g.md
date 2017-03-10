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
| Rows Updated | 2014-04-03T23:39:41Z |

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
```

## Meta Commands

```ls
entity e:k5ry-ef3g l:Restaurants t:attribution="City of Baltimore" t:url=https://data.baltimorecity.gov/api/views/k5ry-ef3g

property e:k5ry-ef3g t:meta.view d:2017-03-10T16:05:24.118Z v:id=k5ry-ef3g v:category="Culture & Arts" v:attributionLink=http://www.baltimorecity.gov v:averageRating=0 v:name=Restaurants v:attribution="City of Baltimore"

property e:k5ry-ef3g t:meta.view.license d:2017-03-10T16:05:24.118Z v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:k5ry-ef3g t:meta.view.owner d:2017-03-10T16:05:24.118Z v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"

property e:k5ry-ef3g t:meta.view.tableauthor d:2017-03-10T16:05:24.118Z v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```