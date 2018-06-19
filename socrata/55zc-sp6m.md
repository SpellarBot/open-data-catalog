# Inmates Under Custody: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inmates-under-custody-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/55zc-sp6m) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/55zc-sp6m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/55zc-sp6m/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 55zc-sp6m |
| Name | Inmates Under Custody: Beginning 2008 |
| Attribution | NYS Department of Corrections and Community Supervision |
| Category | Public Safety |
| Tags | admission type, county, inmates, gender, age, crime, correctional facility |
| Created | 2014-01-10T20:49:18Z |
| Publication Date | 2015-11-30T16:20:08Z |

## Description

Represents inmates under custody in NYS Department of Corrections and Community Supervision as of March 31 of the snapshot year.  Includes data about admission type, county, gender, age, crime, and facility.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | snapshot_year           | Snapshot Year           | number    | number      |
| Yes      | series tag     | latest_admission_type   | Latest Admission Type   | text      | text        |
| Yes      | series tag     | county_of_indictment    | County of Indictment    | text      | text        |
| Yes      | series tag     | gender                  | Gender                  | text      | text        |
| Yes      | series tag     | most_serious_crime      | Most Serious Crime      | text      | text        |
| Yes      | numeric metric | current_age             | Current Age             | number    | number      |
| Yes      | series tag     | housing_facility        | Housing Facility        | text      | text        |
| Yes      | series tag     | facility_security_level | Facility Security Level | text      | text        |
```

## Time Field

```ls
Value = snapshot_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:55zc-sp6m d:2014-01-01T00:00:00.000Z t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="ATT BURGLARY 2ND" t:county_of_indictment=ALBANY t:gender=FEMALE t:facility_security_level="MEDIUM SECURITY" t:housing_facility="TACONIC FEMALE" m:current_age=17

series e:55zc-sp6m d:2014-01-01T00:00:00.000Z t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="ASSAULT 2ND" t:county_of_indictment=ALBANY t:gender=FEMALE t:facility_security_level="MEDIUM SECURITY" t:housing_facility="ALBION FEMALE" m:current_age=18

series e:55zc-sp6m d:2014-01-01T00:00:00.000Z t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="BURGLARY 3RD" t:county_of_indictment=ALBANY t:gender=FEMALE t:facility_security_level="MEDIUM SECURITY" t:housing_facility="ALBION FEMALE" m:current_age=18
```

## Meta Commands

```ls
metric m:current_age p:integer l:"Current Age" d:"Inmate age as of the file date/most recent snapshot year" t:dataTypeName=number

entity e:55zc-sp6m l:"Inmates Under Custody: Beginning 2008" t:attribution="NYS Department of Corrections and Community Supervision" t:url=https://data.ny.gov/api/views/55zc-sp6m

property e:55zc-sp6m t:meta.view v:id=55zc-sp6m v:category="Public Safety" v:attributionLink=http://www.doccs.ny.gov/ v:averageRating=0 v:name="Inmates Under Custody: Beginning 2008" v:attribution="NYS Department of Corrections and Community Supervision"

property e:55zc-sp6m t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:55zc-sp6m t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:55zc-sp6m t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| snapshot_year | latest_admission_type | county_of_indictment | gender | most_serious_crime | current_age | housing_facility | facility_security_level | 
| ============= | ===================== | ==================== | ====== | ================== | =========== | ================ | ======================= | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | ATT BURGLARY 2ND   | 17          | TACONIC FEMALE   | MEDIUM SECURITY         | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | ASSAULT 2ND        | 18          | ALBION FEMALE    | MEDIUM SECURITY         | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | BURGLARY 3RD       | 18          | ALBION FEMALE    | MEDIUM SECURITY         | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | ASSAULT 2ND        | 20          | ALBION FEMALE    | MEDIUM SECURITY         | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | ATT CPCS 3RD       | 20          | ALBION FEMALE    | MEDIUM SECURITY         | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | ATT C POS WEAP 2ND | 20          | ALBION FEMALE    | MEDIUM SECURITY         | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | ATT ROBBERY 2ND    | 20          | ALBION FEMALE    | MEDIUM SECURITY         | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | ATT ROBBERY 2ND    | 20          | TACONIC FEMALE   | MEDIUM SECURITY         | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | BURGLARY 3RD       | 20          | BEDFORD HILLS    | MAXIMUM SECURITY        | 
| 2014          | NEW COURT COMMITMENT  | ALBANY               | FEMALE | YO ATT BURGLARY    | 20          | ALBION FEMALE    | MEDIUM SECURITY         | 
```