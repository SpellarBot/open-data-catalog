# Seattle Parks and Recreation Parks Features

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-parks-and-recreation-parks-features) |
| Metadata | [Link](https://data.seattle.gov/api/views/2cer-njie) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/2cer-njie/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/2cer-njie/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 2cer-njie |
| Name | Seattle Parks and Recreation Parks Features |
| Attribution | Seattle Parks & Recreation |
| Category | Parks and Recreation |
| Tags | parks, addresses, features |
| Created | 2016-03-19T17:56:50Z |
| Publication Date | 2016-03-19T18:10:58Z |

## Description

Listing of all park features by park.  EX: if a park has multiple tennis courts each of them is included.

PMAID is our Property Management Area ID. It is used by the City of Seattle to reference a group of adjoined land parcels into a larger area such as a park. This coding works well for Parks because most parks consist of multiple parcels. This number is assigned by the city. Other cities likely use a similar identifier, but not the same method as Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | pmaid        | PMAID        | text      | number      |
| Yes      | series tag     | name         | Name         | text      | text        |
| Yes      | series tag     | alt_name     | Alt_Name     | text      | text        |
| Yes      | numeric metric | xpos         | xPos         | number    | number      |
| Yes      | numeric metric | ypos         | yPos         | number    | number      |
| Yes      | series tag     | feature_id   | Feature_ID   | text      | number      |
| Yes      | series tag     | hours        | hours        | text      | text        |
| Yes      | series tag     | feature_desc | Feature_Desc | text      | text        |
| Yes      | series tag     | child_desc   | CHILD_DESC   | text      | text        |
| Yes      | series tag     | field_type   | FIELD_TYPE   | text      | text        |
| Yes      | series tag     | youth_only   | YOUTH_ONLY   | text      | text        |
| Yes      | series tag     | lighting     | LIGHTING     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2cer-njie d:2016-03-19T10:56:55.000Z t:pmaid=281 t:lighting=FALSE t:feature_desc="Play Area" t:hours="6 a.m. - 10 p.m." t:name="12th and Howe Play Park" t:feature_id=22 t:child_desc="Play Area" t:youth_only=FALSE m:xpos=-122.372985 m:ypos=47.636097

series e:2cer-njie d:2016-03-19T10:56:55.000Z t:pmaid=4159 t:lighting=FALSE t:feature_desc=View t:hours="6 a.m. - 10 p.m." t:name="12th Ave S Viewpoint" t:feature_id=34 t:youth_only=FALSE m:xpos=-122.317765 m:ypos=47.577953

series e:2cer-njie d:2016-03-19T10:56:55.000Z t:pmaid=4010 t:lighting=FALSE t:feature_desc="Boat Launch (Hand Carry)" t:hours="4 a.m. - 11:30 p.m." t:name="14th Ave NW Boat Ramp" t:feature_id=7 t:youth_only=FALSE m:xpos=-122.373536 m:ypos=47.660775
```

## Meta Commands

```ls
metric m:xpos p:double l:xPos t:dataTypeName=number

metric m:ypos p:double l:yPos t:dataTypeName=number

entity e:2cer-njie l:"Seattle Parks and Recreation Parks Features" t:attribution="Seattle Parks & Recreation" t:url=https://data.seattle.gov/api/views/2cer-njie

property e:2cer-njie t:meta.view v:id=2cer-njie v:category="Parks and Recreation" v:attributionLink=http://www.seattle.gov/parks/ v:averageRating=0 v:name="Seattle Parks and Recreation Parks Features" v:attribution="Seattle Parks & Recreation"

property e:2cer-njie t:meta.view.owner v:id=fs78-6jsr v:screenName="Blood, Bruce" v:displayName="Blood, Bruce"

property e:2cer-njie t:meta.view.tableauthor v:id=fs78-6jsr v:screenName="Blood, Bruce" v:displayName="Blood, Bruce"
```

## Top Records

```ls
| :updated_at | pmaid   | name                    | alt_name | xpos        | ypos      | feature_id | hours               | feature_desc              | child_desc | field_type | youth_only | lighting | 
| =========== | ======= | ======================= | ======== | =========== | ========= | ========== | =================== | ========================= | ========== | ========== | ========== | ======== | 
| 1458385015  | 281     | 12th and Howe Play Park |          | -122.372985 | 47.636097 | 22         | 6 a.m. - 10 p.m.    | Play Area                 | Play Area  |            | FALSE      | FALSE    | 
| 1458385015  | 4159    | 12th Ave S Viewpoint    |          | -122.317765 | 47.577953 | 34         | 6 a.m. - 10 p.m.    | View                      |            |            | FALSE      | FALSE    | 
| 1458385015  | 4010    | 14th Ave NW Boat Ramp   |          | -122.373536 | 47.660775 | 7          | 4 a.m. - 11:30 p.m. | Boat Launch (Hand Carry)  |            |            | FALSE      | FALSE    | 
| 1458385015  | 4010    | 14th Ave NW Boat Ramp   |          | -122.373536 | 47.660775 | 6          | 4 a.m. - 11:30 p.m. | Boat Launch (Motorized)   |            |            | FALSE      | FALSE    | 
| 1458385015  | 4010    | 14th Ave NW Boat Ramp   |          | -122.373536 | 47.660775 | 36         | 4 a.m. - 11:30 p.m. | Waterfront                |            |            | FALSE      | FALSE    | 
| 1458385015  | 1000001 | 32nd Ave W Boat Launch  |          |             |           | 7          | 4 a.m. - 11:30 p.m. | Boat Launch (Hand Carry)  |            |            | FALSE      | FALSE    | 
| 1458385015  | 3158    | 6th Ave NW Pocket Park  |          |             |           | 41         | 4 a.m. - 11:30 p.m. | Play Area (ADA Compliant) | Play Area  |            | FALSE      | FALSE    | 
| 1458385015  | 4404    | A. B. Ernst Park        |          | -122.348826 | 47.650087 | 33         | 4 a.m. - 11:30 p.m. | Paths                     |            |            | FALSE      | FALSE    | 
| 1458385015  | 4404    | A. B. Ernst Park        |          | -122.348826 | 47.650087 | 34         | 4 a.m. - 11:30 p.m. | View                      |            |            | FALSE      | FALSE    | 
| 1458385015  | 1000002 | Adams Street Boat Ramp  |          |             |           | 7          | 6 a.m. - 10:00 p.m. | Boat Launch (Hand Carry)  |            |            | FALSE      | FALSE    | 
```