# Vacant Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vacant-buildings-f6b67) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/qqcv-ihn5) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/qqcv-ihn5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/qqcv-ihn5/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | qqcv-ihn5 |
| Name | Vacant Buildings |
| Attribution | Housing Authority of Baltimore City |
| Category | Housing & Development |
| Tags | vacant buildings, vacant |
| Created | 2011-12-12T17:54:56Z |
| Publication Date | 2016-03-10T14:47:31Z |

## Description

Vacant Buildings located throughout the City of Baltimore. To be updated twice a month, or as needed.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | referenceid     | ReferenceID     | text          | text          |
| Yes      | series tag  | block           | Block           | text          | text          |
| Yes      | series tag  | lot             | Lot             | text          | text          |
| No       |             | buildingaddress | BuildingAddress | text          | text          |
| Yes      | time        | noticedate      | NoticeDate      | calendar_date | calendar_date |
| Yes      | series tag  | neighborhood    | Neighborhood    | text          | text          |
| Yes      | series tag  | policedistrict  | PoliceDistrict  | text          | text          |
| Yes      | series tag  | councildistrict | CouncilDistrict | text          | number        |
```

## Time Field

```ls
Value = noticedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = buildingaddress
```

## Data Commands

```ls
series e:qqcv-ihn5 d:2016-03-10T00:00:00.000Z t:referenceid="0002 019 031016" t:councildistrict=7 t:neighborhood=EASTERWOOD t:lot=019 t:block=0002 t:policedistrict=WESTERN m:row_number.qqcv-ihn5=1

series e:qqcv-ihn5 d:2016-03-11T00:00:00.000Z t:referenceid="0007 057 031116" t:councildistrict=7 t:neighborhood=EASTERWOOD t:lot=057 t:block=0007 t:policedistrict=WESTERN m:row_number.qqcv-ihn5=2

series e:qqcv-ihn5 d:2016-03-08T00:00:00.000Z t:referenceid="0125 012 030816" t:councildistrict=9 t:neighborhood="HARLEM PARK" t:lot=012 t:block=0125 t:policedistrict=WESTERN m:row_number.qqcv-ihn5=3
```

## Meta Commands

```ls
metric m:row_number.qqcv-ihn5 p:long l:"Row Number"

entity e:qqcv-ihn5 l:"Vacant Buildings" t:attribution="Housing Authority of Baltimore City" t:url=https://data.baltimorecity.gov/api/views/qqcv-ihn5

property e:qqcv-ihn5 t:meta.view v:id=qqcv-ihn5 v:category="Housing & Development" v:attributionLink=http://www.baltimorehousing.org/default.aspx v:averageRating=0 v:name="Vacant Buildings" v:attribution="Housing Authority of Baltimore City"

property e:qqcv-ihn5 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:qqcv-ihn5 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:qqcv-ihn5 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| referenceid     | block | lot | buildingaddress      | noticedate          | neighborhood               | policedistrict | councildistrict | 
| =============== | ===== | === | ==================== | =================== | ========================== | ============== | =============== | 
| 0002 019 031016 | 0002  | 019 | 1909 W NORTH AVE     | 2016-03-10T00:00:00 | EASTERWOOD                 | WESTERN        | 7               | 
| 0007 057 031116 | 0007  | 057 | 1734 APPLETON ST     | 2016-03-11T00:00:00 | EASTERWOOD                 | WESTERN        | 7               | 
| 0125 012 030816 | 0125  | 012 | 522 N CAREY ST       | 2016-03-08T00:00:00 | HARLEM PARK                | WESTERN        | 9               | 
| 0151 009 030716 | 0151  | 009 | 317 N GILMOR ST      | 2016-03-07T00:00:00 | FRANKLIN SQUARE            | WESTERN        | 9               | 
| 0232 032 031116 | 0232  | 032 | 1324 W LOMBARD ST    | 2016-03-11T00:00:00 | UNION SQUARE               | SOUTHERN       | 9               | 
| 0275 060 030716 | 0275  | 060 | 319 S MONROE ST      | 2016-03-07T00:00:00 | CARROLLTON RIDGE           | SOUTHERN       | 9               | 
| 0599 008 031116 | 0599  | 008 | 235 PARK AVE         | 2016-03-11T00:00:00 | DOWNTOWN                   | CENTRAL        | 11              | 
| 0767 117 030816 | 0767  | 117 | 1329 SARGEANT ST     | 2016-03-08T00:00:00 | WASHINGTON VILLAGE/PIGTOWN | SOUTHERN       | 10              | 
| 0779 002 030716 | 0779  | 002 | 1203 WASHINGTON BLVD | 2016-03-07T00:00:00 | WASHINGTON VILLAGE/PIGTOWN | SOUTHERN       | 10              | 
| 0801 066 031016 | 0801  | 066 | 1121 NANTICOKE ST    | 2016-03-10T00:00:00 | WASHINGTON VILLAGE/PIGTOWN | SOUTHERN       | 10              | 
```