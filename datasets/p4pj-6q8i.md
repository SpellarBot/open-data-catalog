# NET Deficiencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/net-deficiencies) |
| Metadata | [Link](https://data.austintexas.gov/api/views/p4pj-6q8i) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/p4pj-6q8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/p4pj-6q8i/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | p4pj-6q8i |
| Name | NET Deficiencies |
| Category | Government |
| Created | 2015-08-04T16:22:28Z |
| Publication Date | 2017-01-11T13:10:31Z |

## Description

This dataset lists deficiencies related to NET cases, which are used for the NET dashboard.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | numeric metric | folderrsn                  | FOLDERRSN                  | number        | number        |
| Yes      | series tag     | casenumber                 | CASENUMBER                 | text          | text          |
| Yes      | time           | date_opened                | DATE_OPENED                | calendar_date | calendar_date |
| Yes      | series tag     | case_type                  | CASE_TYPE                  | text          | text          |
| Yes      | series tag     | status                     | STATUS                     | text          | text          |
| Yes      | series tag     | primary_reported_violation | PRIMARY_REPORTED_VIOLATION | text          | text          |
| Yes      | numeric metric | propx                      | PROPX                      | number        | number        |
| Yes      | numeric metric | propy                      | PROPY                      | number        | number        |
| Yes      | series tag     | categorydesc               | CATEGORYDESC               | text          | text          |
| No       |                | address                    | ADDRESS                    | text          | text          |
| No       |                | longitude                  | LONGITUDE                  | number        | number        |
| No       |                | latitude                   | LATITUDE                   | number        | number        |
```

## Time Field

```ls
Value = date_opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,longitude,latitude
```

## Data Commands

```ls
series e:p4pj-6q8i d:2015-12-11T00:00:00.000Z t:categorydesc="Exterior Property Areas" t:casenumber="2015-148552 CC" t:status=Active t:primary_reported_violation="Land Use Violation(s)" t:case_type=Neighborhood m:folderrsn=11459290 m:propy=10101701 m:propx=3127328.25

series e:p4pj-6q8i d:2015-12-11T00:00:00.000Z t:categorydesc="Exterior Structure" t:casenumber="2015-148552 CC" t:status=Active t:primary_reported_violation="Land Use Violation(s)" t:case_type=Neighborhood m:folderrsn=11459290 m:propy=10101701 m:propx=3127328.25

series e:p4pj-6q8i d:2015-12-11T00:00:00.000Z t:categorydesc="Exterior Structure" t:casenumber="2015-148552 CC" t:status=Active t:primary_reported_violation="Land Use Violation(s)" t:case_type=Neighborhood m:folderrsn=11459290 m:propy=10101701 m:propx=3127328.25
```

## Meta Commands

```ls
metric m:folderrsn p:integer l:FOLDERRSN t:dataTypeName=number

metric m:propx p:double l:PROPX t:dataTypeName=number

metric m:propy p:double l:PROPY t:dataTypeName=number

entity e:p4pj-6q8i l:"NET Deficiencies" t:url=https://data.austintexas.gov/api/views/p4pj-6q8i

property e:p4pj-6q8i t:meta.view v:id=p4pj-6q8i v:category=Government v:averageRating=0 v:name="NET Deficiencies"

property e:p4pj-6q8i t:meta.view.owner v:id=bci6-zyu7 v:screenName=Shawn v:displayName=Shawn

property e:p4pj-6q8i t:meta.view.tableauthor v:id=bci6-zyu7 v:screenName=Shawn v:roleName=editor v:displayName=Shawn
```

## Top Records

```ls
| folderrsn | casenumber     | date_opened         | case_type    | status | primary_reported_violation | propx      | propy    | categorydesc                                 | address        | longitude    | latitude    | 
| ========= | ============== | =================== | ============ | ====== | ========================== | ========== | ======== | ============================================ | ============== | ============ | =========== | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Exterior Property Areas                      | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Exterior Structure                           | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Exterior Structure                           | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Exterior Structure                           | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Interior Structure                           | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Interior Structure                           | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Plumbing Facilities and Fixture Requirements | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Plumbing Facilities and Fixture Requirements | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Exterior Structure                           | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
| 11459290  | 2015-148552 CC | 2015-12-11T00:00:00 | Neighborhood | Active | Land Use Violation(s)      | 3127328.25 | 10101701 | Mechanical and Electrical Requirements       | 8608 DUNGAN ST | -97.69926920 | 30.35229542 | 
```