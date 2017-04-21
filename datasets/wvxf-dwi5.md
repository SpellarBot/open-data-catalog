# Housing Maintenance Code Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-maintenance-code-violations-a54f4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wvxf-dwi5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wvxf-dwi5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wvxf-dwi5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wvxf-dwi5 |
| Name | Housing Maintenance Code Violations |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | violation, department of housing preservation and development, hpd |
| Created | 2013-11-18T19:49:47Z |
| Publication Date | 2015-04-02T17:36:57Z |

## Description

PLEASE NOTE: For a complete list of open violations, review the ?all open violations? file available on <a href="http://www1.nyc.gov/assets/hpd/downloads/misc/AllOpenViolations20170301.zip">HPD?s website</a>.  Pursuant to New York City?s Housing Maintenance Code, the Department of Housing Preservation and Development (HPD) issues violations against conditions in rental dwelling units that have been verified to violate the New York City using Maintenance Code (HMC) or the New York State Multiple Dwelling Law (MDL). Violations are issued when an inspection verifies that a violation of the HMC or MDL exists. It is closed when the violation is corrected, as observed/verified by HPD or as certified by the landlord.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | violationid           | ViolationID           | text          | number        |
| Yes      | series tag  | buildingid            | BuildingID            | text          | number        |
| Yes      | series tag  | registrationid        | RegistrationID        | text          | number        |
| Yes      | series tag  | boroid                | BoroID                | text          | number        |
| Yes      | series tag  | boro                  | Boro                  | text          | text          |
| Yes      | series tag  | housenumber           | HouseNumber           | text          | text          |
| Yes      | series tag  | lowhousenumber        | LowHouseNumber        | text          | text          |
| Yes      | series tag  | highhousenumber       | HighHouseNumber       | text          | text          |
| Yes      | series tag  | streetname            | StreetName            | text          | text          |
| Yes      | series tag  | streetcode            | StreetCode            | text          | text          |
| Yes      | series tag  | zip                   | Zip                   | text          | text          |
| Yes      | series tag  | apartment             | Apartment             | text          | text          |
| Yes      | series tag  | story                 | Story                 | text          | text          |
| Yes      | series tag  | block                 | Block                 | text          | number        |
| Yes      | series tag  | lot                   | Lot                   | text          | number        |
| Yes      | series tag  | class                 | Class                 | text          | text          |
| Yes      | time        | inspectiondate        | InspectionDate        | calendar_date | calendar_date |
| No       |             | approveddate          | ApprovedDate          | calendar_date | calendar_date |
| No       |             | originalcertifybydate | OriginalCertifyByDate | calendar_date | calendar_date |
| No       |             | originalcorrectbydate | OriginalCorrectByDate | calendar_date | calendar_date |
| No       |             | newcertifybydate      | NewCertifyByDate      | calendar_date | calendar_date |
| No       |             | newcorrectbydate      | NewCorrectByDate      | calendar_date | calendar_date |
| No       |             | certifieddate         | CertifiedDate         | calendar_date | calendar_date |
| Yes      | series tag  | ordernumber           | OrderNumber           | text          | text          |
| Yes      | series tag  | novid                 | NOVID                 | text          | number        |
| Yes      | series tag  | novdescription        | NOVDescription        | text          | text          |
| No       |             | novissueddate         | NOVIssuedDate         | calendar_date | calendar_date |
| Yes      | series tag  | currentstatusid       | CurrentStatusID       | text          | number        |
| Yes      | series tag  | currentstatus         | CurrentStatus         | text          | text          |
| No       |             | currentstatusdate     | CurrentStatusDate     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = inspectiondate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = approveddate,originalcertifybydate,originalcorrectbydate,newcertifybydate,newcorrectbydate,certifieddate,novissueddate,currentstatusdate
```

## Data Commands

```ls
series e:wvxf-dwi5 d:1997-04-11T00:00:00.000Z t:zip=10009 t:buildingid=444 t:boro=MANHATTAN t:streetcode=10010 t:class=A t:ordernumber=772 t:block=429 t:currentstatusid=19 t:housenumber=22 t:currentstatus="VIOLATION CLOSED" t:violationid=2293208 t:novdescription="?? 27-2098 ADM CODE FILE WITH THIS DEPARTMENT A REGISTRATION STATEMENT FOR BUILDING." t:story="All Stories" t:boroid=1 t:lowhousenumber=22 t:lot=7 t:novid=338596 t:registrationid=130476 t:highhousenumber=22 t:streetname="1 AVENUE" m:row_number.wvxf-dwi5=1

series e:wvxf-dwi5 d:1979-06-05T00:00:00.000Z t:zip=10009 t:buildingid=444 t:boro=MANHATTAN t:streetcode=10010 t:class=B t:ordernumber=775 t:block=429 t:currentstatusid=19 t:housenumber=22 t:currentstatus="VIOLATION CLOSED" t:violationid=2293181 t:novdescription="D26-41.05 ADM CODE FILE WITH THIS DEPARTMENT REGISTRATION STATEMENT FOR CHANGE OF OWNERSHIP OF BUILDING." t:boroid=1 t:lowhousenumber=22 t:lot=7 t:novid=338584 t:registrationid=130476 t:highhousenumber=22 t:streetname="1 AVENUE" m:row_number.wvxf-dwi5=2

series e:wvxf-dwi5 d:1996-11-06T00:00:00.000Z t:zip=10029 t:buildingid=448 t:boro=MANHATTAN t:streetcode=10010 t:class=A t:ordernumber=772 t:block=1708 t:currentstatusid=19 t:housenumber=2222 t:currentstatus="VIOLATION CLOSED" t:violationid=2293249 t:novdescription="?? 27-2098 ADM CODE FILE WITH THIS DEPARTMENT A REGISTRATION STATEMENT FOR BUILDING." t:story="All Stories" t:boroid=1 t:lowhousenumber=2222 t:lot=1 t:novid=338619 t:registrationid=135326 t:highhousenumber=2222 t:streetname="1 AVENUE" m:row_number.wvxf-dwi5=3
```

## Meta Commands

```ls
metric m:row_number.wvxf-dwi5 p:long l:"Row Number"

entity e:wvxf-dwi5 l:"Housing Maintenance Code Violations" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/wvxf-dwi5

property e:wvxf-dwi5 t:meta.view v:id=wvxf-dwi5 v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Housing Maintenance Code Violations" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:wvxf-dwi5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wvxf-dwi5 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| violationid | buildingid | registrationid | boroid | boro      | housenumber | lowhousenumber | highhousenumber | streetname      | streetcode | zip   | apartment | story       | block | lot | class | inspectiondate      | approveddate        | originalcertifybydate | originalcorrectbydate | newcertifybydate | newcorrectbydate | certifieddate       | ordernumber | novid   | novdescription                                                                                                                                                                                                                                             | novissueddate       | currentstatusid | currentstatus    | currentstatusdate   | 
| =========== | ========== | ============== | ====== | ========= | =========== | ============== | =============== | =============== | ========== | ===== | ========= | =========== | ===== | === | ===== | =================== | =================== | ===================== | ===================== | ================ | ================ | =================== | =========== | ======= | ========================================================================================================================================================================================================================================================== | =================== | =============== | ================ | =================== | 
| 2293208     | 444        | 130476         | 1      | MANHATTAN | 22          | 22             | 22              | 1 AVENUE        | 10010      | 10009 |           | All Stories | 429   | 7   | A     | 1997-04-11T00:00:00 | 1997-04-11T00:00:00 | 1997-08-15T00:00:00   | 1997-08-08T00:00:00   |                  |                  |                     | 772         | 338596  | ?? 27-2098 ADM CODE FILE WITH THIS DEPARTMENT A REGISTRATION STATEMENT FOR BUILDING.                                                                                                                                                                       | 1997-04-22T00:00:00 | 19              | VIOLATION CLOSED | 2015-03-10T00:00:00 | 
| 2293181     | 444        | 130476         | 1      | MANHATTAN | 22          | 22             | 22              | 1 AVENUE        | 10010      | 10009 |           |             | 429   | 7   | B     | 1979-06-05T00:00:00 | 1974-06-06T00:00:00 | 1974-09-20T00:00:00   | 1974-09-13T00:00:00   |                  |                  | 1974-09-10T00:00:00 | 775         | 338584  | D26-41.05 ADM CODE FILE WITH THIS DEPARTMENT REGISTRATION STATEMENT FOR CHANGE OF OWNERSHIP OF BUILDING.                                                                                                                                                   | 1974-07-16T00:00:00 | 19              | VIOLATION CLOSED | 2015-03-10T00:00:00 | 
| 2293249     | 448        | 135326         | 1      | MANHATTAN | 2222        | 2222           | 2222            | 1 AVENUE        | 10010      | 10029 |           | All Stories | 1708  | 1   | A     | 1996-11-06T00:00:00 | 1996-11-06T00:00:00 | 1997-03-14T00:00:00   | 1997-03-07T00:00:00   |                  |                  |                     | 772         | 338619  | ?? 27-2098 ADM CODE FILE WITH THIS DEPARTMENT A REGISTRATION STATEMENT FOR BUILDING.                                                                                                                                                                       | 1996-11-19T00:00:00 | 19              | VIOLATION CLOSED | 2015-03-10T00:00:00 | 
| 2293486     | 467        | 136913         | 1      | MANHATTAN | 2250        | 2250           | 2250            | 1 AVENUE        | 10010      | 10029 |           | All Stories | 1709  | 47  | A     | 1982-05-07T00:00:00 | 1982-05-07T00:00:00 | 1982-09-02T00:00:00   | 1982-08-26T00:00:00   |                  |                  |                     | 772         | 338733  | D26-41.03 ADM CODE FILE WITH THIS DEPARTMENT A REGISTRATION AND OCCUPANCY STATEMENT OF BUILDING.                                                                                                                                                           | 1982-05-10T00:00:00 | 19              | VIOLATION CLOSED | 2015-03-10T00:00:00 | 
| 2293490     | 467        | 136913         | 1      | MANHATTAN | 2250        | 2250           | 2250            | 1 AVENUE        | 10010      | 10029 |           | All Stories | 1709  | 47  | A     | 1996-11-06T00:00:00 | 1996-11-06T00:00:00 | 1997-03-14T00:00:00   | 1997-03-07T00:00:00   |                  |                  |                     | 772         | 338737  | ?? 27-2098 ADM CODE FILE WITH THIS DEPARTMENT A REGISTRATION STATEMENT FOR BUILDING.                                                                                                                                                                       | 1996-11-19T00:00:00 | 19              | VIOLATION CLOSED | 2015-03-10T00:00:00 | 
| 10690403    | 41095      | 103427         | 1      | MANHATTAN | 622         | 620            | 622             | WEST 137 STREET | 36510      | 10031 | 42        | 4           | 2002  | 61  | B     | 2015-04-24T00:00:00 | 2015-04-30T00:00:00 | 2015-06-19T00:00:00   | 2015-06-05T00:00:00   |                  |                  | 2015-06-01T00:00:00 | 508         | 5109809 | ?? 27-2005 ADM CODE REPAIR THE BROKEN OR DEFECTIVE PLASTERED SURFACES AND PAINT IN A UNIFORM COLOR CEILING IN THE BATHROOM LOCATED AT APT 42, 4th STORY, 1st APARTMENT FROM EAST AT SOUTH                                                                  | 2015-05-01T00:00:00 | 19              | VIOLATION CLOSED | 2015-08-12T00:00:00 | 
| 4037616     | 482        | 0              | 1      | MANHATTAN | 2269        | 2269           | 2275            | 1 AVENUE        | 10010      | 10035 |           |             | 1688  | 30  | A     | 2001-12-05T00:00:00 | 2001-12-10T00:00:00 | 2002-04-04T00:00:00   | 2002-03-21T00:00:00   |                  |                  |                     | 772         | 1756099 | ?? 27-2098 ADM CODE FILE WITH THIS DEPARTMENT A REGISTRATION STATEMENT FOR BUILDING.                                                                                                                                                                       | 2001-12-11T00:00:00 | 19              | VIOLATION CLOSED | 2015-03-10T00:00:00 | 
| 10642313    | 497        | 136600         | 1      | MANHATTAN | 229         | 229            | 229             | 1 AVENUE        | 10010      | 10003 | 3A        | 3           | 455   | 37  | C     | 2015-03-23T00:00:00 | 2015-03-24T00:00:00 | 2015-04-07T00:00:00   | 2015-04-02T00:00:00   |                  |                  |                     | 510         | 5080621 | ?? 27-2005 ADM CODE & 309 M/D LAW ABATE THE NUISANCE CONSISTING OF EXCESSIVE ACCUMULATION OF HOUSEHOLD ITEMS IN THE ENTIRE APARTMENT LOCATED AT APT 3A, 3rd STORY, 2nd APARTMENT FROM WEST AT NORTH                                                        | 2015-03-25T00:00:00 | 2               | NOV SENT OUT     | 2015-03-25T00:00:00 | 
| 10645393    | 544        | 103340         | 1      | MANHATTAN | 26          | 26             | 28              | 1 AVENUE        | 10010      | 10009 |           | 1           | 429   | 9   | A     | 2015-03-25T00:00:00 | 2015-03-29T00:00:00 | 2015-07-17T00:00:00   | 2015-07-03T00:00:00   |                  |                  |                     | 500         | 5084957 | ?? 26-1103 ADMIN. CODE: POST AND MAINTAIN A PROPER NOTICE ON WALL OF THE ENTRANCE STORY IN ENGLISH AND SPANISH ON THE AVAILABILITY OF THE AGENCY???S HOUSING INFORMATION GUIDE. A SAMPLE NOTICE CAN BE FOUND AT WWW.NYC.GOV/HPD. AT PUBLIC HALL, 1st STORY | 2015-03-30T00:00:00 | 2               | NOV SENT OUT     | 2015-03-30T00:00:00 | 
| 10630564    | 545        | 120827         | 1      | MANHATTAN | 261         | 261            | 261             | 1 AVENUE        | 10010      | 10003 |           | All Stories | 922   | 20  | B     | 2015-03-12T00:00:00 | 2015-03-17T00:00:00 | 2015-05-05T00:00:00   | 2015-04-21T00:00:00   |                  |                  |                     | 506         | 5074273 | ?? 27-2005 ADM CODE REPLACE WITH NEW THE MISSING CAPPED DISCONNETED GAS METER SUPPLY LINE AT NORTH SECTION WALL ON 3RD STORY PUBLIC HALL                                                                                                                   | 2015-03-17T00:00:00 | 2               | NOV SENT OUT     | 2015-03-17T00:00:00 | 
```