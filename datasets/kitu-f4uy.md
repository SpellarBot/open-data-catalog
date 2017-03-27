# Stop and Search (Field Interviews)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stop-and-search-field-interviews) |
| Metadata | [Link](https://data.nola.gov/api/views/kitu-f4uy) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/kitu-f4uy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/kitu-f4uy/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | kitu-f4uy |
| Name | Stop and Search (Field Interviews) |
| Category | Public Safety and Preparedness |
| Tags | police, stop, search, field interview |
| Created | 2015-07-10T16:01:09Z |
| Publication Date | 2016-04-17T06:24:07Z |

## Description

A subset of data collected when individuals are interviewed by NOPD Officers (including individuals stopped for questioning and complainants).Disclaimer: The New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | fieldinterviewid      | FieldInterviewID      | text          | number        |
| Yes      | series tag     | nopd_item             | NOPD_Item             | text          | text          |
| Yes      | time           | eventdate             | EventDate             | calendar_date | calendar_date |
| Yes      | series tag     | district              | District              | text          | number        |
| Yes      | series tag     | zone                  | Zone                  | text          | text          |
| Yes      | series tag     | officerassignment     | OfficerAssignment     | text          | text          |
| Yes      | series tag     | stopdescription       | StopDescription       | text          | text          |
| Yes      | series tag     | actionstaken          | ActionsTaken          | text          | text          |
| Yes      | series tag     | vehicleyear           | VehicleYear           | text          | number        |
| Yes      | series tag     | vehiclemake           | VehicleMake           | text          | text          |
| Yes      | series tag     | vehiclemodel          | VehicleModel          | text          | text          |
| Yes      | series tag     | vehiclestyle          | VehicleStyle          | text          | text          |
| Yes      | series tag     | vehiclecolor          | VehicleColor          | text          | text          |
| Yes      | series tag     | subjectid             | SubjectID             | text          | number        |
| Yes      | series tag     | subjectrace           | SubjectRace           | text          | text          |
| Yes      | series tag     | subjectgender         | SubjectGender         | text          | text          |
| Yes      | numeric metric | subjectage            | SubjectAge            | number        | number        |
| Yes      | series tag     | subjecthasphotoid     | SubjectHasPhotoID     | text          | text          |
| Yes      | numeric metric | subjectheight         | SubjectHeight         | number        | number        |
| Yes      | numeric metric | subjectweight         | SubjectWeight         | number        | number        |
| Yes      | series tag     | subjecteyecolor       | SubjectEyeColor       | text          | text          |
| Yes      | series tag     | subjecthaircolor      | SubjectHairColor      | text          | text          |
| Yes      | series tag     | subjectdriverlicstate | SubjectDriverLicState | text          | text          |
| No       |                | createddatetime       | CreatedDateTime       | calendar_date | calendar_date |
| No       |                | lastmodifieddatetime  | LastModifiedDateTime  | calendar_date | calendar_date |
| No       |                | longitude             | Longitude             | number        | number        |
| No       |                | latitude              | Latitude              | number        | number        |
| Yes      | series tag     | zip                   | Zip                   | text          | number        |
| No       |                | blockaddress          | BlockAddress          | text          | text          |
```

## Time Field

```ls
Value = eventdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = createddatetime,lastmodifieddatetime,longitude,latitude,blockaddress
```

## Data Commands

```ls
series e:kitu-f4uy d:2010-01-01T01:11:00.000Z t:vehiclemodel=CARAVAN t:vehiclecolor=BLACK t:subjectgender=FEMALE t:vehicleyear=2005 t:subjecthasphotoid=Yes t:subjectdriverlicstate=LA t:subjecthaircolor=Black t:vehiclemake=DODGE t:vehiclestyle=MINIVAN t:fieldinterviewid=17415 t:subjecteyecolor=Brown t:district=6 t:subjectid=20465 t:stopdescription="TRAFFIC VIOLATION" t:officerassignment="6th  District" t:zone=E t:subjectrace=BLACK m:subjectage=26 m:subjectweight=160 m:subjectheight=69

series e:kitu-f4uy d:2010-01-01T02:06:00.000Z t:subjecthasphotoid=No t:subjecthaircolor=Black t:fieldinterviewid=17416 t:subjecteyecolor=Brown t:subjectgender=MALE t:district=5 t:stopdescription="CALL FOR SERVICE" t:subjectid=20466 t:officerassignment="5th  District" t:zone=D t:subjectrace=BLACK m:subjectage=17 m:subjectweight=140 m:subjectheight=65

series e:kitu-f4uy d:2010-01-01T02:06:00.000Z t:subjecthasphotoid=No t:subjecthaircolor=Black t:fieldinterviewid=17416 t:subjecteyecolor=Brown t:subjectgender=MALE t:district=5 t:stopdescription="CALL FOR SERVICE" t:subjectid=20467 t:officerassignment="5th  District" t:zone=D t:subjectrace=BLACK m:subjectage=18 m:subjectweight=145 m:subjectheight=67
```

## Meta Commands

```ls
metric m:subjectage p:integer l:SubjectAge t:dataTypeName=number

metric m:subjectheight p:integer l:SubjectHeight t:dataTypeName=number

metric m:subjectweight p:integer l:SubjectWeight t:dataTypeName=number

entity e:kitu-f4uy l:"Stop and Search (Field Interviews)" t:url=https://data.nola.gov/api/views/kitu-f4uy

property e:kitu-f4uy t:meta.view v:id=kitu-f4uy v:category="Public Safety and Preparedness" v:averageRating=0 v:name="Stop and Search (Field Interviews)"

property e:kitu-f4uy t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:kitu-f4uy t:meta.view.owner v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:displayName="Enterprise Information Data Team"

property e:kitu-f4uy t:meta.view.tableauthor v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:roleName=publisher v:displayName="Enterprise Information Data Team"

property e:kitu-f4uy t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```