# Historical Permit Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-permit-data) |
| Metadata | [Link](https://data.nola.gov/api/views/f7tt-z5vu) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/f7tt-z5vu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/f7tt-z5vu/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | f7tt-z5vu |
| Name | Historical Permit Data |
| Attribution | City of New Orleans ? Office of Information Technology & Innovation, Enterprise Information Team |
| Category | Housing, Land Use, and Blight |
| Tags | permits, building, electrical, sign |
| Created | 2015-04-23T20:29:56Z |
| Publication Date | 2015-04-24T21:02:50Z |

## Description

This dataset includes Building, Electrical, and Sign permits filed from December 1995 to January 2005.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | permitnumber    | PermitNumber    | text          | text          |
| Yes      | time           | applicationdate | ApplicationDate | calendar_date | calendar_date |
| No       |                | issuedate       | IssueDate       | calendar_date | calendar_date |
| Yes      | numeric metric | housenum        | HouseNum        | number        | text          |
| Yes      | series tag     | streetdir       | StreetDir       | text          | text          |
| Yes      | series tag     | streetname      | StreetName      | text          | text          |
| Yes      | series tag     | streetsuffix    | StreetSuffix    | text          | text          |
| Yes      | series tag     | unitnumber      | UnitNumber      | text          | text          |
| No       |                | matchaddress    | MatchAddress    | text          | text          |
| Yes      | series tag     | applicantname   | ApplicantName   | text          | text          |
| Yes      | series tag     | parcelowner     | ParcelOwner     | text          | text          |
| Yes      | numeric metric | planningdist    | PlanningDist    | number        | text          |
| Yes      | series tag     | zoning          | Zoning          | text          | text          |
| Yes      | series tag     | description     | Description     | text          | text          |
| Yes      | series tag     | propertykey     | PropertyKey     | text          | text          |
| No       |                | x               | X               | number        | number        |
| No       |                | y               | Y               | number        | number        |
```

## Time Field

```ls
Value = applicationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issuedate,matchaddress,x,y
```

## Data Commands

```ls
series e:f7tt-z5vu d:2000-01-04T00:00:00.000Z t:propertykey=39W10560400001 t:parcelowner="REUTHER SEAFOOD, O INC" t:description="BUILDING DEMOLITION AND DEBRIS REMOVAL VACANT LOT DEMOLISH VACANT COMMERCIAL BUILDING TO GRADE AS PER HDLC C/A #10564. ANY FURTHER USE SHALL REQUIRE A SEPARATE PERMIT." t:permitnumber=B00000007 t:streetsuffix=ST t:applicantname="MICHAEL GANGI" t:zoning=LI t:streetname=MAZANT m:planningdist=3 m:housenum=600

series e:f7tt-z5vu d:2000-01-04T00:00:00.000Z t:propertykey=20720580300004 t:parcelowner="MC QUITTY, MARTHA A" t:description="CHANGE OF USE DOUBLE RESIDENCE CONVERT VACANT MFD TO DOF ON MAIN FLOOR AS PER PLANS. WORK TO INCL SHORING, PNT, ELEC, PLMB, HVAC     ATTIC WILL BECOME LIVABLE AREA, BASEMENT WILL BE STORAGE" t:permitnumber=B00000013 t:streetsuffix=ST t:applicantname="P.E. ODENDAHL" t:zoning=RD3 t:streetname=DUMAINE m:planningdist=2 m:housenum=4016

series e:f7tt-z5vu d:2000-01-05T00:00:00.000Z t:propertykey=39W41070200003 t:parcelowner="COLLINS, DIANNE" t:description="HOME BASED BUSINESS HOME BASED BUSINESS CERTIFICATE OF OCCUPANCY FOR HOME BASED BUSINESS ""STINGRAY SERVICES""CASE #D9934. HOME USED FOR OFFICE SPACE ONLY. MAIL ADD:PO BOX 3552 NO,LA 70177." t:permitnumber=B00000034 t:streetsuffix=ST t:applicantname="DIANNE COLLINS & DAVID LEE" t:zoning=RD3 t:streetname=BENTON m:planningdist=3 m:housenum=1735
```

## Meta Commands

```ls
metric m:housenum p:integer l:HouseNum t:dataTypeName=number

metric m:planningdist p:integer l:PlanningDist t:dataTypeName=number

entity e:f7tt-z5vu l:"Historical Permit Data" t:attribution="City of New Orleans ? Office of Information Technology & Innovation, Enterprise Information Team" t:url=https://data.nola.gov/api/views/f7tt-z5vu

property e:f7tt-z5vu t:meta.view v:id=f7tt-z5vu v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="Historical Permit Data" v:attribution="City of New Orleans ? Office of Information Technology & Innovation, Enterprise Information Team"

property e:f7tt-z5vu t:meta.view.owner v:id=7kk9-bewq v:screenName="J.B. Raasch" v:displayName="J.B. Raasch"

property e:f7tt-z5vu t:meta.view.tableauthor v:id=7kk9-bewq v:screenName="J.B. Raasch" v:roleName=administrator v:displayName="J.B. Raasch"

property e:f7tt-z5vu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| permitnumber | applicationdate     | issuedate           | housenum | streetdir | streetname  | streetsuffix | unitnumber | matchaddress                                    | applicantname              | parcelowner            | planningdist | zoning | description                                                                                                                                                                                         | propertykey    | x             | y             | 
| ============ | =================== | =================== | ======== | ========= | =========== | ============ | ========== | =============================================== | ========================== | ====================== | ============ | ====== | =================================================================================================================================================================================================== | ============== | ============= | ============= | 
| B00000007    | 2000-01-04T00:00:00 | 2000-01-04T00:00:00 | 600      |           | MAZANT      | ST           |            | 600 MAZANT ST, NEW ORLEANS, LA 70150            | MICHAEL GANGI              | REUTHER SEAFOOD, O INC | 3            | LI     | BUILDING DEMOLITION AND DEBRIS REMOVAL VACANT LOT DEMOLISH VACANT COMMERCIAL BUILDING TO GRADE AS PER HDLC C/A #10564. ANY FURTHER USE SHALL REQUIRE A SEPARATE PERMIT.                             | 39W10560400001 | 3691627.45562 | 533396.775842 | 
| B00000013    | 2000-01-04T00:00:00 | 2000-02-04T00:00:00 | 4016     |           | DUMAINE     | ST           |            | 4016 DUMAINE ST, NEW ORLEANS, LA 70122          | P.E. ODENDAHL              | MC QUITTY, MARTHA A    | 2            | RD3    | CHANGE OF USE DOUBLE RESIDENCE CONVERT VACANT MFD TO DOF ON MAIN FLOOR AS PER PLANS. WORK TO INCL SHORING, PNT, ELEC, PLMB, HVAC ATTIC WILL BECOME LIVABLE AREA, BASEMENT WILL BE STORAGE           | 20720580300004 | 3673272.00677 | 540368.93447  | 
| B00000034    | 2000-01-05T00:00:00 |                     | 1735     |           | BENTON      | ST           |            | 1735 BENTON ST, NEW ORLEANS, LA 70117           | DIANNE COLLINS & DAVID LEE | COLLINS, DIANNE        | 3            | RD3    | HOME BASED BUSINESS HOME BASED BUSINESS CERTIFICATE OF OCCUPANCY FOR HOME BASED BUSINESS "STINGRAY SERVICES"CASE #D9934. HOME USED FOR OFFICE SPACE ONLY. MAIL ADD:PO BOX 3552 NO,LA 70177.         | 39W41070200003 | 3699869.32431 | 535969.909803 | 
| B00000035    | 2000-01-05T00:00:00 |                     | 2420     |           | CHARTRES    | ST           |            | 2420 CHARTRES ST, NEW ORLEANS, LA 70183         | CRAIG DUNN                 | PRUDHOMME, PAUL E      | 3            | HMR3   | GENERAL REPAIRS MULTI-FAMILY DWELLING REPAIRS TO EXISTING MULTI FAMILY DWELL- ING TO CONSIST OF: NEW ROOF SHINGLES, REPLACING ROTTON WOOD.                                                          | 38W10032200006 | 3686123.77699 | 534502.832357 | 
| B00000052    | 2000-01-06T00:00:00 | 2000-01-06T00:00:00 | 7732     |           | HAMPSON     | ST           |            | 7732 HAMPSON ST, NEW ORLEANS, LA 70118          | GREGORY THOMAS GUIRINTANO  | GUIRINTANO, GREGORY T  | 7            | RD2    | CHANGE OF USE SINGLE-FAMILY DWELLING CONVERTING EXISTING 2-STY DOUBLE FAMILY DWELLING INTO SINGLE FAMILY DWELLING AS PER PLANS.                                                                     | 71610490200002 | 3661689.02501 | 526230.560188 | 
| B00000063    | 2000-01-06T00:00:00 |                     | 4420     |           | TOURO       | ST           |            | 4420 TOURO ST, NEW ORLEANS, LA 70122            | NIKKI I. BROWN             | COLLY, JAMES W         | 3            | RM2    | HOME BASED BUSINESS HOME BASED BUSINESS                                                                                                                                                             | 37W50241500002 | 3683104.65278 | 548943.311022 | 
| B00000067    | 2000-01-07T00:00:00 | 2000-02-18T00:00:00 | 601      |           | POYDRAS     | ST           | 11FL       | 601 POYDRAS ST UNIT 11FL, NEW ORLEANS, LA 70130 | MICHAEL O'DONNELL          | PAN AM LIFE INS, CO    | 1            | CBD1   | BUILDING RENOVATIONS OFFICE BUILDING INTERIOR RENOVATIONS TO THE 11TH FLOOR OF AN EXISTING OFFICE BUILDING AS PER PLANS.                                                                            | 10410121500019 | 3680938.01801 | 529396.80648  | 
| B00000082    | 2000-01-07T00:00:00 |                     | 1600     |           | KENTUCKY    | ST           |            | 1600 KENTUCKY ST, NEW ORLEANS, LA 70119         | ALVIN J. EDMOND            | RUIZ S, JOHN E         | 3            | HI     | CHANGE OF USE CAR WASH CHANGE OF USE FROM VACANT COMMERCIAL BUILDING (IRON WORKS SHOP) INTO A CAR WASH AS PER PLANS. ELECTRICAL, PLUMB- ING                                                         | 39W40570500001 | 3693720.52689 | 536859.944112 | 
| B00000094    | 2000-01-10T00:00:00 |                     | 1105     |           | TERPSICHORE | ST           |            | 1105 TERPSICHORE ST, NEW ORLEANS, LA 70130      | EUGENE TIMOTHY SCHMID      | UNKNOWN, UNKNOWN       |              | RM2    | CERT. OF OCCUPANCY-NO WORK TO BE DONE HOME BASED BUSINESS CERTIFICATE OF OCCUPANCY FOR HOME BASED BUSINESS: PHI DESIGN AS PER CASE # D9863                                                          | GENERATED10723 | 3680310.8398  | 524569.111083 | 
| B00000100    | 2000-01-10T00:00:00 |                     | 100      |           | EUTERPE     | ST           |            | 100 EUTERPE ST, NEW ORLEANS, LA 70130           | SEAN SULLIVAN              | ORLEANS, PORT OF NEW   |              | HI     | BUILDING RENOVATIONS MEETING HALL RENOVATIONS TO VACANT COMMERCIAL BUILD- ING TO CONSIST OF MODIFICATIONS TO MECH SYSTEM, AUTOMATIC SPRINKLER & FIRE ALARM (TO BE USE FOR TERMINAL/HALL)AS PER PLAN | GENERATED10821 |               |               | 
```