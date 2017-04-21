# Fixed Speed Cameras

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fixed-speed-cameras-f24ca) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/aqgr-xx9h) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/aqgr-xx9h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/aqgr-xx9h/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | aqgr-xx9h |
| Name | Fixed Speed Cameras |
| Attribution | Department of Transportation |
| Category | Transportation |
| Tags | speed, transportation, citation |
| Created | 2012-03-09T13:14:45Z |
| Publication Date | 2014-04-03T23:24:46Z |

## Description

Motorists who drive aggressively and exceed the posted speed limit by at least 12 miles per hour will receive $40 citations in the mail. These citations are not reported to insurance companies and no license points are assigned. Notification signs will be placed at all speed enforcement locations so that motorists will be aware that they are approaching a speed check zone. The goal of the program is to make the streets of Baltimore safer for everyone by changing aggressive driving behavior. In addition to the eight portable speed enforcement units, the city has retrofitted 50 red light camera locations with the automated speed enforcement technology.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| No       |             | address      | address      | text      | text        |
| Yes      | series tag  | direction    | direction    | text      | text        |
| Yes      | series tag  | street       | street       | text      | text        |
| Yes      | series tag  | crossstreet  | crossStreet  | text      | text        |
| Yes      | series tag  | intersection | intersection | text      | text        |
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
series e:aqgr-xx9h d:2012-03-09T05:14:46.000Z t:intersection="Caton Ave & Benson Ave" t:crossstreet="Benson Ave" t:direction=N/B t:street="Caton Ave" m:row_number.aqgr-xx9h=1

series e:aqgr-xx9h d:2012-03-09T05:14:46.000Z t:intersection="Caton Ave & Benson Ave" t:crossstreet="Benson Ave" t:direction=S/B t:street="Caton Ave" m:row_number.aqgr-xx9h=2

series e:aqgr-xx9h d:2012-03-09T05:14:46.000Z t:intersection="Wilkens Ave & Pine Heights" t:crossstreet="Pine Heights" t:direction=E/B t:street="Wilkens Ave" m:row_number.aqgr-xx9h=3
```

## Meta Commands

```ls
metric m:row_number.aqgr-xx9h p:long l:"Row Number"

entity e:aqgr-xx9h l:"Fixed Speed Cameras" t:attribution="Department of Transportation" t:url=https://data.baltimorecity.gov/api/views/aqgr-xx9h

property e:aqgr-xx9h t:meta.view v:id=aqgr-xx9h v:category=Transportation v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Transportation/SpeedMonitoringLocations.aspx v:averageRating=0 v:name="Fixed Speed Cameras" v:attribution="Department of Transportation"

property e:aqgr-xx9h t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:aqgr-xx9h t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:aqgr-xx9h t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | address                        | direction | street      | crossstreet  | intersection               | 
| =========== | ============================== | ========= | =========== | ============ | ========================== | 
| 1331270086  | S CATON AVE & BENSON AVE       | N/B       | Caton Ave   | Benson Ave   | Caton Ave & Benson Ave     | 
| 1331270086  | S CATON AVE & BENSON AVE       | S/B       | Caton Ave   | Benson Ave   | Caton Ave & Benson Ave     | 
| 1331270086  | WILKENS AVE & PINE HEIGHTS AVE | E/B       | Wilkens Ave | Pine Heights | Wilkens Ave & Pine Heights | 
| 1331270086  | THE ALAMEDA & E 33RD ST        | S/B       | The Alameda | 33rd St      | The Alameda & 33rd St      | 
| 1331270086  | E 33RD ST & THE ALAMEDA        | E/B       | E 33rd      | The Alameda  | E 33rd & The Alameda       | 
| 1331270086  | ERDMAN AVE & N MACON ST        | E/B       | Erdman      | Macon St     | Erdman & Macon St          | 
| 1331270086  | ERDMAN AVE & N MACON ST        | W/B       | Erdman      | Macon St     | Erdman & Macon St          | 
| 1331270086  | N CHARLES ST & E LAKE AVE      | S/B       | Charles     | Lake Ave     | Charles & Lake Ave         | 
| 1331270086  | E MADISON ST & N CAROLINE ST   | W/B       | Madison     | Caroline St  | Madison & Caroline St      | 
| 1331270086  | ORLEANS ST & N LINWOOD AVE     | E/B       | Orleans     | Linwood Ave  | Orleans & Linwood Ave      | 
```