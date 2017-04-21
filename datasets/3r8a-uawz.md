# Parks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parks-40ca3) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/3r8a-uawz) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/3r8a-uawz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/3r8a-uawz/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 3r8a-uawz |
| Name | Parks |
| Attribution | Baltimore City Department of Recreation and Parks |
| Category | Culture & Arts |
| Tags | parks, recreation |
| Created | 2011-12-14T18:41:50Z |
| Publication Date | 2014-04-03T23:38:26Z |

## Description

This inventory was set up to fulfill the request of the City auditors for a description of all city property. It has been modified to include information useful to the Department of Recreation and Parks.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | name        | name       | text      | text        |
| Yes      | series tag     | district    | district   | text      | text        |
| Yes      | numeric metric | acres       | acres      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3r8a-uawz d:2011-12-14T10:42:03.000Z t:name="32nd Street Park" t:district=Clifton m:acres=0.1342

series e:3r8a-uawz d:2011-12-14T10:42:03.000Z t:name="Adams Park" t:district=Clifton m:acres=0.51

series e:3r8a-uawz d:2011-12-14T10:42:03.000Z t:name="Alexander Odum Park" t:district="Gwynns Falls" m:acres=1.155
```

## Meta Commands

```ls
metric m:acres p:float l:acres t:dataTypeName=number

entity e:3r8a-uawz l:Parks t:attribution="Baltimore City Department of Recreation and Parks" t:url=https://data.baltimorecity.gov/api/views/3r8a-uawz

property e:3r8a-uawz t:meta.view v:id=3r8a-uawz v:category="Culture & Arts" v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/RecreationandParks.aspx v:averageRating=0 v:name=Parks v:attribution="Baltimore City Department of Recreation and Parks"

property e:3r8a-uawz t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:3r8a-uawz t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:3r8a-uawz t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                      | district     | acres               | 
| =========== | ========================= | ============ | =================== | 
| 1323859323  | 32nd Street Park          | Clifton      | 0.13420000000000001 | 
| 1323859323  | Adams Park                | Clifton      | 0.51                | 
| 1323859323  | Alexander Odum Park       | Gwynns Falls | 1.155               | 
| 1323859323  | Alhambra Park             | Clifton      | 0.89049999999999996 | 
| 1323859323  | Ambrose Kennedy Park      | Patterson    | 1.7305999999999999  | 
| 1323859323  | Anchorage Promenade Park  | Patterson    | 0.26                | 
| 1323859323  | Andover & North Hill Park | Clifton      | 0.59                | 
| 1323859323  | Arnold Sumpter Park       | Druid Hill   | 2.7610000000000001  | 
| 1323859323  | Asbury Park               | Druid Hill   | 1.2190000000000001  | 
| 1323859323  | Atlantic Ave Park         | Carroll      | 1.4810000000000001  | 
```