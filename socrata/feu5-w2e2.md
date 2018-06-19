# Registration Contacts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/registration-contacts-a9986) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/feu5-w2e2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/feu5-w2e2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/feu5-w2e2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | feu5-w2e2 |
| Name | Registration Contacts |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | registration, department of housing preservation and development, hpd |
| Created | 2013-11-18T21:16:19Z |
| Publication Date | 2017-04-01T19:48:27Z |

## Description

Contains information about organizations or individuals listed on a Multiple Dwelling Registration form.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | registrationcontactid | RegistrationContactID | text      | number      |
| Yes      | series tag  | registrationid        | RegistrationID        | text      | number      |
| Yes      | series tag  | type                  | Type                  | text      | text        |
| Yes      | series tag  | contactdescription    | ContactDescription    | text      | text        |
| Yes      | series tag  | corporationname       | CorporationName       | text      | text        |
| Yes      | series tag  | title                 | Title                 | text      | text        |
| Yes      | series tag  | firstname             | FirstName             | text      | text        |
| Yes      | series tag  | middleinitial         | MiddleInitial         | text      | text        |
| Yes      | series tag  | lastname              | LastName              | text      | text        |
| Yes      | series tag  | businesshousenumber   | BusinessHouseNumber   | text      | text        |
| Yes      | series tag  | businessstreetname    | BusinessStreetName    | text      | text        |
| Yes      | series tag  | businessapartment     | BusinessApartment     | text      | text        |
| Yes      | series tag  | businesscity          | BusinessCity          | text      | text        |
| Yes      | series tag  | businessstate         | BusinessState         | text      | text        |
| Yes      | series tag  | businesszip           | BusinessZip           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:feu5-w2e2 d:2017-04-01T19:43:38.000Z t:registrationcontactid=34681513 t:contactdescription=INDIV t:lastname=GAYLE t:firstname=ELEANOR t:type=SiteManager t:registrationid=346815 m:row_number.feu5-w2e2=1

series e:feu5-w2e2 d:2017-04-01T19:43:38.000Z t:businesszip=11207 t:registrationcontactid=32275503 t:corporationname="FIVE A ASSOCIATES INC." t:businesshousenumber=669 t:businessstreetname=MILLER t:businessstate=NY t:contactdescription=CORP t:type=CorporateOwner t:registrationid=322755 t:businesscity=BROOKLYN m:row_number.feu5-w2e2=2

series e:feu5-w2e2 d:2017-04-01T19:43:38.000Z t:businesszip=11207 t:registrationcontactid=32275504 t:businesshousenumber=669 t:businessstreetname=MILLER t:businessstate=NY t:contactdescription=CORP t:lastname=DELLIMORE t:firstname=ANNE t:type=Agent t:registrationid=322755 t:businesscity=BROOKLYN m:row_number.feu5-w2e2=3
```

## Meta Commands

```ls
metric m:row_number.feu5-w2e2 p:long l:"Row Number"

entity e:feu5-w2e2 l:"Registration Contacts" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/feu5-w2e2

property e:feu5-w2e2 t:meta.view v:id=feu5-w2e2 v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Registration Contacts" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:feu5-w2e2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:feu5-w2e2 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | registrationcontactid | registrationid | type            | contactdescription | corporationname        | title          | firstname | middleinitial | lastname   | businesshousenumber | businessstreetname | businessapartment | businesscity | businessstate | businesszip | 
| =========== | ===================== | ============== | =============== | ================== | ====================== | ============== | ========= | ============= | ========== | =================== | ================== | ================= | ============ | ============= | =========== | 
| 1491075818  | 34681513              | 346815         | SiteManager     | INDIV              |                        |                | ELEANOR   |               | GAYLE      |                     |                    |                   |              |               |             | 
| 1491075818  | 32275503              | 322755         | CorporateOwner  | CORP               | FIVE A ASSOCIATES INC. |                |           |               |            | 669                 | MILLER             |                   | BROOKLYN     | NY            | 11207       | 
| 1491075818  | 32275504              | 322755         | Agent           | CORP               |                        |                | ANNE      |               | DELLIMORE  | 669                 | MILLER             |                   | BROOKLYN     | NY            | 11207       | 
| 1491075818  | 32275505              | 322755         | HeadOfficer     | CORP               |                        | VICE PRESIDENT | ANNE      |               | DELLIMORE  | 669                 | MILLER             |                   | BROOKLYN     | NY            | 11207       | 
| 1491075818  | 32275506              | 322755         | Officer         | CORP               |                        | PRESIDENT      | ANDREW    |               | DELLIMORE  | 669                 | MILLER             |                   | BROOKLYN     | NY            | 11207       | 
| 1491075818  | 32275510              | 322755         | Shareholder     | CORP               |                        |                | ANNE      |               | DELLIMORE  | 669                 | MILLER             |                   | BROOKLYN     | NY            | 11207       | 
| 1491075818  | 32275513              | 322755         | SiteManager     | CORP               |                        |                | ANDREW    |               | DELLIMORE  |                     |                    |                   |              |               |             | 
| 1491075818  | 34808402              | 348084         | IndividualOwner | INDIV              |                        |                | KAY       |               | ALER-MAIDA | 863                 | EAST 23 STREET     |                   | BROOKLYN     | NY            | 11210       | 
| 1491075818  | 34808413              | 348084         | SiteManager     | INDIV              |                        |                | KAY       |               | ALER-MALDA |                     |                    |                   |              |               |             | 
| 1491075818  | 35567502              | 355675         | IndividualOwner | INDIV              |                        |                | WHITT     |               | MACK       | 37                  | ELDERT STREET      |                   | BROOKLYN     | NY            | 11227       | 
```