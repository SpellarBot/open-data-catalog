# Facilities Management - Fire Panel Report, by Location, with Detail - July 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-fire-panel-report-by-location-with-detail-july-2011-95b75) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/czk5-5ryh) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/czk5-5ryh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/czk5-5ryh/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | czk5-5ryh |
| Name | Facilities Management - Fire Panel Report, by Location, with Detail - July 2011 |
| Attribution | Cook County Department of Facilities Management |
| Category | Finance & Administration |
| Created | 2011-10-11T14:04:16Z |
| Publication Date | 2014-10-09T21:58:08Z |

## Description

A recap of the alerts that appeared on Cook County facility fire panels. A building's Fire Panel shows all alarm/alert activity for the building, The report also lists descriptions of each alarm.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| Yes      | series tag  | location    | Location    | text      | text        |
| No       |             | no          | No          | text      | text        |
| Yes      | series tag  | _of         | # of        | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = no
```

## Data Commands

```ls
series e:czk5-5ryh d:2011-01-01T00:00:00.000Z t:_of=Alarms m:row_number.czk5-5ryh=1

series e:czk5-5ryh d:2011-01-01T00:00:00.000Z t:location="Ist District courthouse-DV" m:row_number.czk5-5ryh=2

series e:czk5-5ryh d:2011-01-01T00:00:00.000Z t:location="2nd District courthouse- Sk" m:row_number.czk5-5ryh=3
```

## Meta Commands

```ls
metric m:row_number.czk5-5ryh p:long l:"Row Number"

entity e:czk5-5ryh l:"Facilities Management - Fire Panel Report, by Location, with Detail - July 2011" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/czk5-5ryh

property e:czk5-5ryh t:meta.view v:id=czk5-5ryh v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Fire Panel Report, by Location, with Detail - July 2011" v:attribution="Cook County Department of Facilities Management"

property e:czk5-5ryh t:meta.view.license v:name="Public Domain"

property e:czk5-5ryh t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:czk5-5ryh t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| location                      | no     | _of    | description                                                                                                                                 | 
| ============================= | ====== | ====== | =========================================================================================================================================== | 
|                               | Alarms | Alarms |                                                                                                                                             | 
| Ist District courthouse-DV    | X      |        |                                                                                                                                             | 
| 2nd District courthouse- Sk   | X      |        |                                                                                                                                             | 
| 3rd District courthouse-RM    | X      |        | 3/25 City connection was repaired but no alarms where reported                                                                              | 
| 4th District courthouse-MW    | X      |        |                                                                                                                                             | 
| 5th District courthouse-BV    |        | 2      | 4/3 Troble low battery replaced 4/5, 4/5 Supervisory water flow alarm loading dock sprinkler head hit by truck replaced and back in service | 
| 6th District courthouse-Mark. |        | 1      | 4/6 Supervisory pull station hit by Clerks office repaired and back in service                                                              | 
| Armory                        | X      |        |                                                                                                                                             | 
| Boot camp                     | X      |        |                                                                                                                                             | 
| Central kitchen               | X      |        |                                                                                                                                             | 
```