# Parking Signs / Street Space Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-signs-street-space-permits-aka-dpt-tow-verification-list) |
| Metadata | [Link](https://data.sfgov.org/api/views/sftu-nd43) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/sftu-nd43/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/sftu-nd43/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | sftu-nd43 |
| Name | Parking Signs / Street Space Permits |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | permits, construction, buildings, sidewalk, sfmta, tow, verification, street, space, parking, signs |
| Created | 2016-12-30T17:54:45Z |
| Publication Date | 2017-04-18T03:21:44Z |

## Description

Parking Signs / Street Space permits are generally issued for construction related work such as building construction activities or sidewalk repair work.  Related photos of posted signs are here:  https://data.sfgov.org/d/pigs-fac7

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | time           | datetimeentered    | DateTimeEntered    | calendar_date | calendar_date |
| No       |                | datetimeposted     | DateTimePosted     | calendar_date | calendar_date |
| No       |                | updatedon          | UpdatedOn          | calendar_date | calendar_date |
| Yes      | series tag     | category           | Category           | text          | text          |
| Yes      | series tag     | source             | Source             | text          | text          |
| Yes      | series tag     | signtype           | SignType           | text          | text          |
| Yes      | series tag     | companyname        | CompanyName        | text          | text          |
| Yes      | series tag     | companyphone       | CompanyPhone       | text          | text          |
| Yes      | series tag     | permitnumber       | PermitNumber       | text          | text          |
| Yes      | numeric metric | numberofsigns      | NumberOfSigns      | number        | number        |
| No       |                | startdate          | StartDate          | text          | text          |
| No       |                | enddate            | EndDate            | text          | text          |
| Yes      | series tag     | starttime          | StartTime          | text          | text          |
| Yes      | series tag     | endtime            | EndTime            | text          | text          |
| Yes      | series tag     | notes              | Notes              | text          | text          |
| Yes      | series tag     | 24hourenforcement  | 24HourEnforcement  | text          | text          |
| Yes      | series tag     | signid             | SignID             | text          | number        |
| Yes      | series tag     | sideofstreet       | SideOfStreet       | text          | text          |
| Yes      | series tag     | location_1         | location_desc      | text          | text          |
| No       |                | address            | address            | text          | text          |
| Yes      | numeric metric | cnn                | cnn                | number        | number        |
| Yes      | series tag     | streetfrontagefeet | StreetFrontageFeet | text          | number        |
| Yes      | series tag     | block              | Block              | text          | text          |
| Yes      | series tag     | lot                | Lot                | text          | text          |
| No       |                | latitude           | Latitude           | number        | number        |
| No       |                | longitude          | Longitude          | number        | number        |
| Yes      | series tag     | signlink           | SignLink           | url           | url           |
| Yes      | series tag     | alldatalink        | AllDataLink        | url           | url           |
| Yes      | series tag     | streetfrontagename | StreetFrontageName | text          | text          |
| Yes      | series tag     | streetfrontagefrom | StreetFrontageFrom | text          | text          |
| Yes      | series tag     | streetfrontageto   | StreetFrontageTo   | text          | text          |
```

## Time Field

```ls
Value = datetimeentered
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = datetimeposted,updatedon,enddate,address,latitude,longitude,startdate
```

## Data Commands

```ls
series e:sftu-nd43 d:2017-04-06T14:22:33.000Z t:endtime=23:00 t:starttime=0:00 t:companyphone=415-238-7744 t:block=0976 t:streetfrontagefrom="BRODERICK ST" t:streetfrontageto="BAKER ST" t:signid=89973 t:streetfrontagefeet=20 t:alldatalink="http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=2017040053236" t:companyname="DESIGN & DEVELOP CONSTRUCTION" t:signlink="http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3&params=signid=89973&ExportPDF=1&filename=89973" t:category="Construction - Private" t:source=StreetSpaceRequest t:streetfrontagename="PACIFIC AVE" t:permitnumber=2017040053236 t:24hourenforcement=N t:lot=035 t:sideofstreet=N t:notes="12AM - 11:59PM - Mon - Sun" t:location_1="PACIFIC AVE: BRODERICK ST to BAKER ST (2900 - 2999)" t:signtype=DBI m:numberofsigns=2 m:cnn=10161000

series e:sftu-nd43 d:2016-11-28T08:25:11.000Z t:endtime=18:00 t:starttime=7:00 t:companyphone=415-916-2856 t:block=1157 t:streetfrontagefrom="BRODERICK ST" t:streetfrontageto="BAKER ST" t:signid=77254 t:streetfrontagefeet=100 t:alldatalink="http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=M740487" t:companyname="Fineline Construction" t:signlink="http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3&params=signid=77254&ExportPDF=1&filename=77254" t:category="Construction - Private" t:source=StreetSpaceRequest t:streetfrontagename="MCALLISTER ST" t:permitnumber=M740487 t:24hourenforcement=N t:lot=007 t:sideofstreet=N t:notes="7AM - 6PM - Mon - Fri" t:location_1="MCALLISTER ST: BRODERICK ST to BAKER ST (1700 - 1799)" t:signtype=DBI m:numberofsigns=6 m:cnn=8905000

series e:sftu-nd43 d:2016-10-31T15:38:02.000Z t:endtime=18:00 t:starttime=7:00 t:companyphone=510-885-1110 t:block=0984 t:streetfrontagefrom="PRESIDIO AVE" t:streetfrontageto="WALNUT ST" t:signid=74661 t:streetfrontagefeet=32 t:alldatalink="http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=M734887" t:companyname="Welch Construction" t:signlink="http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3&params=signid=74661&ExportPDF=1&filename=74661" t:category="Construction - Private" t:source=StreetSpaceRequest t:streetfrontagename="WASHINGTON ST" t:permitnumber=M734887 t:24hourenforcement=N t:lot=010 t:sideofstreet=N t:notes="7AM - 6PM - Mon - Fri" t:location_1="WASHINGTON ST: PRESIDIO AVE to WALNUT ST (3300 - 3399)" t:signtype=DBI m:numberofsigns=3 m:cnn=13446000
```

## Meta Commands

```ls
metric m:numberofsigns p:integer l:NumberOfSigns t:dataTypeName=number

metric m:cnn p:integer l:cnn t:dataTypeName=number

entity e:sftu-nd43 l:"Parking Signs / Street Space Permits" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/sftu-nd43

property e:sftu-nd43 t:meta.view v:id=sftu-nd43 v:category="City Infrastructure" v:attributionLink=http://www.sfpublicworks.org v:averageRating=0 v:name="Parking Signs / Street Space Permits" v:attribution="San Francisco Department of Public Works"

property e:sftu-nd43 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sftu-nd43 t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:sftu-nd43 t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| datetimeentered     | datetimeposted      | updatedon           | category               | source             | signtype | companyname                          | companyphone | permitnumber  | numberofsigns | startdate  | enddate    | starttime | endtime | notes                       | 24hourenforcement | signid | sideofstreet | location_1                                                      | address            | cnn      | streetfrontagefeet | block | lot  | latitude         | longitude         | signlink                                                                                                                           | alldatalink                                                               | streetfrontagename | streetfrontagefrom | streetfrontageto | 
| =================== | =================== | =================== | ====================== | ================== | ======== | ==================================== | ============ | ============= | ============= | ========== | ========== | ========= | ======= | =========================== | ================= | ====== | ============ | =============================================================== | ================== | ======== | ================== | ===== | ==== | ================ | ================= | ================================================================================================================================== | ========================================================================= | ================== | ================== | ================ | 
| 2017-04-06T14:22:33 | 1900-01-01T00:00:00 | 2017-04-06T14:22:33 | Construction - Private | StreetSpaceRequest | DBI      | DESIGN & DEVELOP CONSTRUCTION        | 415-238-7744 | 2017040053236 | 2             | 04/13/2017 | 05/13/2017 | 0:00      | 23:00   | 12AM - 11:59PM - Mon - Sun  | N                 | 89973  | N            | PACIFIC AVE: BRODERICK ST to BAKER ST (2900 - 2999)             | 2945 PACIFIC AVE   | 10161000 | 20                 | 0976  | 035  | 37.7919324064038 | -122.443726051883 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=89973&ExportPDF=1&filename=89973, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=2017040053236, null] | PACIFIC AVE        | BRODERICK ST       | BAKER ST         | 
| 2016-11-28T08:25:11 | 2016-11-28T08:25:14 | 2016-11-28T08:25:11 | Construction - Private | StreetSpaceRequest | DBI      | Fineline Construction                | 415-916-2856 | M740487       | 6             | 12/01/2016 | 06/01/2017 | 7:00      | 18:00   | 7AM - 6PM - Mon - Fri       | N                 | 77254  | N            | MCALLISTER ST: BRODERICK ST to BAKER ST (1700 - 1799)           | 1750 MCALLISTER ST | 8905000  | 100                | 1157  | 007  | 37.7777702416758 | -122.44053811009  | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=77254&ExportPDF=1&filename=77254, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=M740487, null]       | MCALLISTER ST      | BRODERICK ST       | BAKER ST         | 
| 2016-10-31T15:38:02 | 2016-10-31T15:38:15 | 2016-10-31T15:38:02 | Construction - Private | StreetSpaceRequest | DBI      | Welch Construction                   | 510-885-1110 | M734887       | 3             | 11/03/2016 | 05/03/2017 | 7:00      | 18:00   | 7AM - 6PM - Mon - Fri       | N                 | 74661  | N            | WASHINGTON ST: PRESIDIO AVE to WALNUT ST (3300 - 3399)          | 3340 WASHINGTON ST | 13446000 | 32                 | 0984  | 010  | 37.7901068196733 | -122.448172279309 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=74661&ExportPDF=1&filename=74661, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=M734887, null]       | WASHINGTON ST      | PRESIDIO AVE       | WALNUT ST        | 
| 2017-02-17T08:51:14 | 2017-02-18T15:48:33 | 2017-02-17T08:51:14 | Construction - Private | StreetSpaceRequest | DBI      | Sure Inc                             | 415-706-6170 | M759347       | 2             | 02/22/2017 | 05/22/2017 | 7:30      | 5:30    | 7:30AM - 5:30AM - Mon - Sat | N                 | 84760  | N            | UNION ST: LARKIN ST to POLK ST (1300 - 1399)                    | 1330 UNION ST      | 12862000 | 20                 | 0525  | 009  | 37.7991272348573 | -122.421280060435 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=84760&ExportPDF=1&filename=84760, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=M759347, null]       | UNION ST           | LARKIN ST          | POLK ST          | 
| 2017-04-03T15:22:43 | 2017-04-06T09:45:27 | 2017-04-03T15:22:43 | Construction - Private | StreetSpaceRequest | DBI      | Matt Sanford Homes                   | 415-706-4168 | 201702038579  | 2             | 04/10/2017 | 08/10/2017 | 7:00      | 18:00   | 7AM - 6PM - Mon - Sat       | N                 | 89370  | N            | 30TH AVE: GEARY BLVD to ANZA ST (500 - 599)                     | 590 30TH AVE       | 1642000  | 20                 | 1515  | 020A | 37.778149052175  | -122.489687469789 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=89370&ExportPDF=1&filename=89370, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=201702038579, null]  | 30TH AVE           | GEARY BLVD         | ANZA ST          | 
| 2017-03-16T13:33:02 | 2017-03-22T17:07:55 | 2017-03-16T13:33:02 | Construction - Private | StreetSpaceRequest | DBI      | hunts construction partnership       | 408-858-7007 | M768907       | 2             | 03/23/2017 | 05/23/2017 | 8:00      | 17:00   | 8AM - 5PM - Mon - Fri       | N                 | 87521  | N            | CALIFORNIA ST: 26TH AVE to 27TH AVE (6400 - 6499)               | 6423 CALIFORNIA ST | 3603000  | 20                 | 1407  | 046  | 37.7835675795187 | -122.486511246171 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=87521&ExportPDF=1&filename=87521, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=M768907, null]       | CALIFORNIA ST      | 26TH AVE           | 27TH AVE         | 
| 2017-03-08T11:48:14 | 2017-03-15T08:16:12 | 2017-03-08T11:48:14 | Construction - Private | StreetSpaceRequest | DBI      | Houseworks                           | 415-394-9300 | 201612134867  | 2             | 03/07/2017 | 05/07/2017 | 7:00      | 18:00   | 7AM - 6PM - Mon - Fri       | N                 | 86683  | N            | MISSOURI ST: 19TH ST to 20TH ST (400 - 499)                     | 430 MISSOURI ST    | 9211000  | 20                 | 4067  | 005  | 37.7608150730542 | -122.396670792546 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=86683&ExportPDF=1&filename=86683, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=201612134867, null]  | MISSOURI ST        | 19TH ST            | 20TH ST          | 
| 2017-02-15T08:46:05 | 1900-01-01T00:00:00 | 2017-02-15T08:46:05 | Construction - Private | StreetSpaceRequest | DBI      | CHL CONSTRUCTION                     | 415-297-8897 | 20161152686   | 2             | 02/21/2017 | 04/21/2017 | 7:00      | 18:00   | 7AM - 6PM - Mon - Sat       | N                 | 84415  | N            | 04TH ST: CHANNEL to LONG BRIDGE ST (1100 - 1175)                | 1170 04TH ST       | 19981000 | 20                 | 8711  | 014  | 37.7735407994211 | -122.392027896039 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=84415&ExportPDF=1&filename=84415, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=20161152686, null]   | 04TH ST            | CHANNEL            | LONG BRIDGE ST   | 
| 2016-12-07T10:19:46 | 2016-12-07T10:19:51 | 2016-12-07T10:19:46 | Construction - Private | StreetSpaceRequest | DBI      | swinerton builders                   | 415-421-2980 | M737467       | 3             | 12/10/2016 | 05/10/2017 | 6:00      | 15:00   | 6AM - 3PM - Mon - Sun       | N                 | 78339  | N            | MISSION ST: FREMONT ST to 01ST ST (400 - 499)                   | 50 FREMONT ST      | 9087000  | 40                 | 3709  | 006A | 37.790304371639  | -122.397365063531 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=78339&ExportPDF=1&filename=78339, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=M737467, null]       | MISSION ST         | FREMONT ST         | 01ST ST          | 
| 2016-12-20T09:00:58 | 2017-01-07T23:01:45 | 2016-12-20T09:00:58 | Construction - Private | StreetSpaceRequest | DBI      | Envision Construction & Design, Inc. | 925-560-9906 | 201511243561  | 2             | 01/03/2017 | 07/03/2017 | 5:30      | 17:00   | 5:30AM - 5PM - Mon - Sat    | N                 | 79446  | N            | DIVISADERO ST: ELLIS ST to OFARRELL ST (1301 - 1399) -- WEST -- | 2107 OFARRELL ST   | 4810101  | 20                 | 1101  | 001  | 37.782232534961  | -122.439580287088 | [http://bsm.sfdpw.org/permitstracker/reports/report.aspx?report=rptParkingSignV3?ms=signid=79446&ExportPDF=1&filename=79446, null] | [http://bsm.sfdpw.org/permit/StreetSpaceInfo.aspx?id=201511243561, null]  | DIVISADERO ST      | ELLIS ST           | OFARRELL ST      | 
```