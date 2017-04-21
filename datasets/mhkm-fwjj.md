# All Public Facilities Available for Community Use

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/all-public-facilities-available-for-community-use) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/mhkm-fwjj) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/mhkm-fwjj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/mhkm-fwjj/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | mhkm-fwjj |
| Name | All Public Facilities Available for Community Use |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | public facility, rent, reserve, schools, regional service center, library, athletic field |
| Created | 2016-06-14T23:54:43Z |
| Publication Date | 2017-01-13T16:15:45Z |

## Description

Community Use of Public Facilities All Facilities.  To reserve a public facility follow this link: http://www.montgomerycountymd.gov/cupf/  and select "Reserve Facility" from the  menu on the left side.

This data is updated annually

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | facility_owner | Facility Owner | text      | text        |
| Yes      | series tag  | site           | Site           | text      | text        |
| No       |             | address        | Address        | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip            | Zip            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:mhkm-fwjj d:2016-06-15T08:27:55.000Z t:site="McNair, Ronald ES" t:zip=20874 t:state=MD t:facility_owner="Montgomery County Public Schools" t:city=Germantown m:row_number.mhkm-fwjj=1

series e:mhkm-fwjj d:2016-06-15T08:27:55.000Z t:site="Newport Mill LP/MS" t:zip=20895 t:state=MD t:facility_owner=MNCPPC t:city=Kensington m:row_number.mhkm-fwjj=2

series e:mhkm-fwjj d:2016-06-15T08:27:55.000Z t:site="Damascus Community Recreation Center" t:zip=20872 t:state=MD t:facility_owner=Recreation t:city=Damascus m:row_number.mhkm-fwjj=3
```

## Meta Commands

```ls
metric m:row_number.mhkm-fwjj p:long l:"Row Number"

entity e:mhkm-fwjj l:"All Public Facilities Available for Community Use" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/mhkm-fwjj

property e:mhkm-fwjj t:meta.view v:id=mhkm-fwjj v:category=Community/Recreation v:averageRating=0 v:name="All Public Facilities Available for Community Use" v:attribution="Montgomery County, MD"

property e:mhkm-fwjj t:meta.view.license v:name="Public Domain"

property e:mhkm-fwjj t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:mhkm-fwjj t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | facility_owner                   | site                                 | address                 | city               | state | zip   | 
| =========== | ================================ | ==================================== | ======================= | ================== | ===== | ===== | 
| 1465979275  | Montgomery County Public Schools | McNair, Ronald ES                    | 13881 Hopkins Road      | Germantown         | MD    | 20874 | 
| 1465979275  | MNCPPC                           | Newport Mill LP/MS                   | 11201 Newport Mill RD   | Kensington         | MD    | 20895 | 
| 1465979275  | Recreation                       | Damascus Community Recreation Center | 25520 Oak Drive         | Damascus           | MD    | 20872 | 
| 1465979275  | Libraries                        | Kensington Park Community Library    | 4201 Knowles AVE        | Kensington         | MD    | 20895 | 
| 1465979275  | MNCPPC                           | Manor Oak Local Park                 | 18820 Quarrymen TER     | Olney              | MD    | 20832 | 
| 1465979275  | MNCPPC                           | Concord Local Park                   | 7216 Hidden Creek RD    | Bethesda           | MD    | 20817 | 
| 1465979275  | Montgomery County Public Schools | Montgomery Village MS                | 19300 Watkins Mill Road | Montgomery Village | MD    | 20886 | 
| 1465979275  | Montgomery County Public Schools | Baker, John T. MS                    | 25400 Oak Drive         | Damascus           | MD    | 20872 | 
| 1465979275  | MNCPPC                           | Parkland LP/MS                       | 4701 Renn ST            | Rockville          | MD    | 20853 | 
| 1465979275  | MNCPPC                           | Jesup-Blair Local Park               | 900 Jesup Blair DR      | Silver Spring      | MD    | 20912 | 
```