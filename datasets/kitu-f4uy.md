# Stop and Search (Field Interviews)

## Dataset

* [Dataset URL](https://data.nola.gov/api/views/kitu-f4uy/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/stop-and-search-field-interviews)
* Id = kitu-f4uy
* Name = Stop and Search (Field Interviews)
* Category = Public Safety and Preparedness
* Tags = [police, stop, search, field interview]
* Created = 2015-07-10T16:01:09Z
* Publication Date = 2016-04-17T06:24:07Z
* Rows Updated = 2017-03-03T06:40:31Z

## Description

A subset of data collected when individuals are interviewed by NOPD Officers (including individuals stopped for questioning and complainants).Disclaimer: The New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Name                  | Field Name            | Data Type     | Render Type   | Schema Type    | Included | 
| ===================== | ===================== | ============= | ============= | ============== | ======== | 
| FieldInterviewID      | fieldinterviewid      | text          | number        | series tag     | Yes      | 
| NOPD_Item             | nopd_item             | text          | text          | series tag     | Yes      | 
| EventDate             | eventdate             | calendar_date | calendar_date | time           | Yes      | 
| District              | district              | number        | number        | numeric metric | Yes      | 
| Zone                  | zone                  | number        | text          | numeric metric | Yes      | 
| OfficerAssignment     | officerassignment     | text          | text          | series tag     | Yes      | 
| StopDescription       | stopdescription       | text          | text          | series tag     | Yes      | 
| ActionsTaken          | actionstaken          | text          | text          | series tag     | Yes      | 
| VehicleYear           | vehicleyear           | number        | number        |                | No       | 
| VehicleMake           | vehiclemake           | text          | text          | series tag     | Yes      | 
| VehicleModel          | vehiclemodel          | text          | text          | series tag     | Yes      | 
| VehicleStyle          | vehiclestyle          | text          | text          | series tag     | Yes      | 
| VehicleColor          | vehiclecolor          | text          | text          | series tag     | Yes      | 
| SubjectID             | subjectid             | text          | number        | series tag     | Yes      | 
| SubjectRace           | subjectrace           | text          | text          | series tag     | Yes      | 
| SubjectGender         | subjectgender         | text          | text          | series tag     | Yes      | 
| SubjectAge            | subjectage            | number        | number        | numeric metric | Yes      | 
| SubjectHasPhotoID     | subjecthasphotoid     | text          | text          | series tag     | Yes      | 
| SubjectHeight         | subjectheight         | number        | number        | numeric metric | Yes      | 
| SubjectWeight         | subjectweight         | number        | number        | numeric metric | Yes      | 
| SubjectEyeColor       | subjecteyecolor       | text          | text          | series tag     | Yes      | 
| SubjectHairColor      | subjecthaircolor      | text          | text          | series tag     | Yes      | 
| SubjectDriverLicState | subjectdriverlicstate | text          | text          | series tag     | Yes      | 
| CreatedDateTime       | createddatetime       | calendar_date | calendar_date |                | No       | 
| LastModifiedDateTime  | lastmodifieddatetime  | calendar_date | calendar_date |                | No       | 
| Longitude             | longitude             | number        | number        |                | No       | 
| Latitude              | latitude              | number        | number        |                | No       | 
| Zip                   | zip                   | number        | number        | numeric metric | Yes      | 
| BlockAddress          | blockaddress          | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = eventdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = lastmodifieddatetime,createddatetime,longitude,latitude,vehicleyear
Annotation Fields = 
```

## Data Commands

```ls
series e:kitu-f4uy d:2010-01-01T01:11:00.000Z t:vehiclemodel=CARAVAN t:vehiclecolor=BLACK t:subjectgender=FEMALE t:subjecthasphotoid=Yes t:subjectdriverlicstate=LA t:subjecthaircolor=Black t:vehiclemake=DODGE t:vehiclestyle=MINIVAN t:fieldinterviewid=17415 t:subjecteyecolor=Brown t:subjectid=20465 t:stopdescription="TRAFFIC VIOLATION" t:officerassignment="6th  District" t:zone=E t:subjectrace=BLACK m:subjectage=26 m:subjectweight=160 m:subjectheight=69 m:district=6

series e:kitu-f4uy d:2010-01-01T02:06:00.000Z t:subjecthasphotoid=No t:subjecthaircolor=Black t:fieldinterviewid=17416 t:subjecteyecolor=Brown t:subjectgender=MALE t:stopdescription="CALL FOR SERVICE" t:subjectid=20466 t:officerassignment="5th  District" t:zone=D t:subjectrace=BLACK m:subjectage=17 m:subjectweight=140 m:subjectheight=65 m:district=5

series e:kitu-f4uy d:2010-01-01T02:06:00.000Z t:subjecthasphotoid=No t:subjecthaircolor=Black t:fieldinterviewid=17416 t:subjecteyecolor=Brown t:subjectgender=MALE t:stopdescription="CALL FOR SERVICE" t:subjectid=20467 t:officerassignment="5th  District" t:zone=D t:subjectrace=BLACK m:subjectage=18 m:subjectweight=145 m:subjectheight=67 m:district=5
```

## Meta Commands

```ls
metric m:district p:integer l:District t:dataTypeName=number

metric m:subjectage p:integer l:SubjectAge t:dataTypeName=number

metric m:subjectheight p:integer l:SubjectHeight t:dataTypeName=number

metric m:subjectweight l:SubjectWeight t:dataTypeName=number

metric m:zip p:integer l:Zip t:dataTypeName=number

entity e:kitu-f4uy l:"Stop and Search (Field Interviews)" t:url=https://data.nola.gov/api/views/kitu-f4uy

property e:kitu-f4uy t:meta.view d:2017-03-03T13:50:49.853Z v:id=kitu-f4uy v:category="Public Safety and Preparedness" v:averageRating=0 v:name="Stop and Search (Field Interviews)"

property e:kitu-f4uy t:meta.view.license d:2017-03-03T13:50:49.853Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:kitu-f4uy t:meta.view.owner d:2017-03-03T13:50:49.853Z v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:roleName=publisher v:displayName="Enterprise Information Data Team"

property e:kitu-f4uy t:meta.view.tableauthor d:2017-03-03T13:50:49.853Z v:id=uqfu-rapx v:screenName="Enterprise Information Data Team" v:roleName=publisher v:displayName="Enterprise Information Data Team"

property e:kitu-f4uy t:meta.view.metadata.custom_fields.common_core d:2017-03-03T13:50:49.853Z v:Contact_Email=data@nola.gov
```