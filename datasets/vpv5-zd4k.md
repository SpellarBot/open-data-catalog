# Annual Enplanements in NYS Airports: Beginning 1997

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-enplanements-in-nys-airports-beginning-1997) |
| Metadata | [Link](https://data.ny.gov/api/views/vpv5-zd4k) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vpv5-zd4k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vpv5-zd4k/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vpv5-zd4k |
| Name | Annual Enplanements in NYS Airports: Beginning 1997 |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | airports, enplanements, air passengers |
| Created | 2013-05-14T19:37:17Z |
| Publication Date | 2016-03-04T23:00:46Z |

## Description

The dataset lists the number of passengers boarding an aircraft at the NYS Airports.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | airport_group | Airport Group | text      | text        |
| Yes      | series tag     | airport_name  | Airport Name  | text      | text        |
| Yes      | time           | year          | Year          | number    | number      |
| Yes      | numeric metric | enplanements  | Enplanements  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vpv5-zd4k d:2011-01-01T00:00:00.000Z t:airport_name="ADIRONDACK REGIONAL" t:airport_group="UPSTATE NON-PRIMARY" m:enplanements=5770

series e:vpv5-zd4k d:2011-01-01T00:00:00.000Z t:airport_name="ALBANY INTERNATIONAL" t:airport_group="UPSTATE HUB" m:enplanements=1216626

series e:vpv5-zd4k d:2011-01-01T00:00:00.000Z t:airport_name="BINGHAMTON REGIONAL AIRPORT" t:airport_group="OTHER UPSTATE PRIMARY" m:enplanements=108172
```

## Meta Commands

```ls
metric m:enplanements p:integer l:Enplanements d:"Number of enplanements" t:dataTypeName=number

entity e:vpv5-zd4k l:"Annual Enplanements in NYS Airports: Beginning 1997" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/vpv5-zd4k

property e:vpv5-zd4k t:meta.view v:id=vpv5-zd4k v:category=Transportation v:attributionLink=http://www.faa.gov/airports/planning_capacity/passenger_allcargo_stats/passenger/ v:averageRating=0 v:name="Annual Enplanements in NYS Airports: Beginning 1997" v:attribution="New York State Department of Transportation"

property e:vpv5-zd4k t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vpv5-zd4k t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vpv5-zd4k t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| airport_group         | airport_name                    | year | enplanements | 
| ===================== | =============================== | ==== | ============ | 
| UPSTATE NON-PRIMARY   | ADIRONDACK REGIONAL             | 2011 | 5770         | 
| UPSTATE HUB           | ALBANY INTERNATIONAL            | 2011 | 1216626      | 
| OTHER UPSTATE PRIMARY | BINGHAMTON REGIONAL AIRPORT     | 2011 | 108172       | 
| UPSTATE HUB           | BUFFALO-NIAGARA INTERNATIONAL   | 2011 | 2582597      | 
| UPSTATE NON-PRIMARY   | CHAUTAUQUA CO.-JAMESTOWN MUNI.  | 2011 | 3483         | 
| UPSTATE NON-PRIMARY   | CLINTON COUNTY/PLATTSBURGH INTL | 2011 | 139698       | 
| OTHER UPSTATE PRIMARY | ELMIRA-CORNING REGIONAL         | 2011 | 152582       | 
| UPSTATE HUB           | GREATER ROCHESTER INTERNATIONAL | 2011 | 1190967      | 
| OTHER UPSTATE PRIMARY | ITHACA/TOMPKINS REGIONAL        | 2011 | 121733       | 
| PORT AUTHORITY/NY     | JOHN F. KENNEDY INTERNATIONAL   | 2011 | 23664832     | 
```