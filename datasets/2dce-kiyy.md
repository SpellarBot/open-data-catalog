# DEPRECATED : King County Ballot Drop Boxes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deprecated-king-county-ballot-drop-boxes-ea2c9) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/2dce-kiyy) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/2dce-kiyy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/2dce-kiyy/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 2dce-kiyy |
| Name | DEPRECATED : King County Ballot Drop Boxes |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections, king county, voting |
| Created | 2012-06-19T20:38:58Z |
| Publication Date | 2013-10-25T20:37:50Z |
| Rows Updated | 2013-10-25T20:37:40Z |

## Description

GO HERE (08/2013): https://electionsdata.kingcounty.gov/dataset/Master-KC-Ballot-Drop-Box-Dataset/k59d-q4u8

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | ballot_drop_box        | Ballot drop box        | text      | text        |
| Yes      | series tag  | in_use                 | In use                 | checkbox  | checkbox    |
| Yes      | series tag  | box_city               | Box city               | text      | text        |
| No       |             | bdb_address            | Address                | text      | text        |
| Yes      | series tag  | box_zip_code           | Box Zip Code           | text      | text        |
| Yes      | series tag  | description            | Description            | text      | text        |
| Yes      | series tag  | photo2                 | Photo                  | photo     | photo       |
| Yes      | series tag  | dates_open             | Dates Open             | text      | text        |
| Yes      | series tag  | hours                  | Hours                  | text      | text        |
| Yes      | series tag  | election_day_hours     | Election Day Hours     | text      | text        |
| Yes      | series tag  | chinese                | Chinese                | text      | text        |
| Yes      | series tag  | chinese_description    | Chinese description    | text      | text        |
| Yes      | series tag  | vietnamese             | Vietnamese             | text      | text        |
| Yes      | series tag  | vietnamese_description | Vietnamese description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = bdb_address
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:2dce-kiyy l:"DEPRECATED : King County Ballot Drop Boxes" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/2dce-kiyy

property e:2dce-kiyy t:meta.view d:2017-03-10T16:12:06.144Z v:id=2dce-kiyy v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="DEPRECATED : King County Ballot Drop Boxes" v:attribution="King County Elections"

property e:2dce-kiyy t:meta.view.license d:2017-03-10T16:12:06.144Z v:name="Public Domain"

property e:2dce-kiyy t:meta.view.owner d:2017-03-10T16:12:06.144Z v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"

property e:2dce-kiyy t:meta.view.tableauthor d:2017-03-10T16:12:06.144Z v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```