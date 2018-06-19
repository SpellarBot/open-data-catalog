# Assisted Living Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assisted-living-facilities-0a4ec) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/q2vm-e9dp) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/q2vm-e9dp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/q2vm-e9dp/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | q2vm-e9dp |
| Name | Assisted Living Facilities |
| Attribution | Baltimore City Commission on Aging and Retirement |
| Category | Health |
| Tags | assisted living |
| Created | 2011-12-14T15:29:42Z |
| Publication Date | 2014-04-03T23:28:29Z |

## Description

This data set provides the location of assisted living facilities within the City of Baltimore. The list of facilities is from the Maryland Office of Health Care and Quality (OHCQ). EGIS gets the data indirectly from the Baltimore City Commission on Aging and Retirement Education (CARE).

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
series e:q2vm-e9dp d:2011-12-14T07:30:36.000Z t:councildistrict=7 t:zipcode=21217 t:name="A Home With A Heart" t:neighborhood=Mondawmin t:policedistrict=WESTERN m:row_number.q2vm-e9dp=1

series e:q2vm-e9dp d:2011-12-14T07:30:36.000Z t:councildistrict=4 t:zipcode=21212 t:name="About Your Care, Inc." t:neighborhood=Winston-Govans t:policedistrict=NORTHERN m:row_number.q2vm-e9dp=2

series e:q2vm-e9dp d:2011-12-14T07:30:36.000Z t:councildistrict=13 t:zipcode=21213 t:name="Absolute Care Assisted Living" t:neighborhood=Belair-Edison t:policedistrict=NORTHEASTERN m:row_number.q2vm-e9dp=3
```

## Meta Commands

```ls
metric m:row_number.q2vm-e9dp p:long l:"Row Number"

entity e:q2vm-e9dp l:"Assisted Living Facilities" t:attribution="Baltimore City Commission on Aging and Retirement" t:url=https://data.baltimorecity.gov/api/views/q2vm-e9dp

property e:q2vm-e9dp t:meta.view v:id=q2vm-e9dp v:category=Health v:attributionLink=http://baltimorehealth.org/care.html v:averageRating=0 v:name="Assisted Living Facilities" v:attribution="Baltimore City Commission on Aging and Retirement"

property e:q2vm-e9dp t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:q2vm-e9dp t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:q2vm-e9dp t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                          | zipcode | neighborhood    | councildistrict | policedistrict | 
| =========== | ============================= | ======= | =============== | =============== | ============== | 
| 1323847836  | A Home With A Heart           | 21217   | Mondawmin       | 7               | WESTERN        | 
| 1323847836  | About Your Care, Inc.         | 21212   | Winston-Govans  | 4               | NORTHERN       | 
| 1323847836  | Absolute Care Assisted Living | 21213   | Belair-Edison   | 13              | NORTHEASTERN   | 
| 1323847836  | Absolute Quality Care         | 21212   | Wilson Park     | 4               | NORTHERN       | 
| 1323847836  | Acts Assisted Living          | 21211   | Hampden         | 14              | NORTHERN       | 
| 1323847836  | Acts of Love I                | 21216   | Winchester      | 9               | SOUTHWESTERN   | 
| 1323847836  | Adassa Assisted Living        | 21206   | Waltherson      | 2               | NORTHEASTERN   | 
| 1323847836  | Agape Assisted Living Home I  | 21206   | Frankford       | 2               | NORTHEASTERN   | 
| 1323847836  | Agape Assisted Living Home II | 21206   | Moravia-Walther | 3               | NORTHEASTERN   | 
| 1323847836  | All About Caring              | 21213   | Biddle Street   | 13              | EASTERN        | 
```