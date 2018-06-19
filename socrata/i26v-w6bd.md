# Commercial Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commercial-permits-6d3e5) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/i26v-w6bd) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/i26v-w6bd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/i26v-w6bd/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | i26v-w6bd |
| Name | Commercial Permits |
| Category | Licenses/Permits |
| Tags | permits, commercial, permitting |
| Created | 2012-08-01T12:19:55Z |
| Publication Date | 2013-11-06T06:06:42Z |

## Description

Data for all Commercial Building Permits issued since 2000, including status and work performed. Update Frequency: Daily

## Columns

```ls
| Included | Schema Type    | Field Name        | Name               | Data Type     | Render Type   |
| ======== | ============== | ================= | ================== | ============= | ============= |
| Yes      | series tag     | permitno          | Permit Number      | text          | text          |
| Yes      | series tag     | status            | Status             | text          | text          |
| Yes      | series tag     | stno              | Street Number      | text          | text          |
| Yes      | series tag     | predir            | Pre-direction      | text          | text          |
| Yes      | series tag     | stname            | Street Name        | text          | text          |
| Yes      | series tag     | suffix            | Street Suffix      | text          | text          |
| Yes      | series tag     | postdir           | Post-direction     | text          | text          |
| Yes      | series tag     | city              | City               | text          | text          |
| Yes      | series tag     | state             | State              | text          | text          |
| Yes      | series tag     | zip               | ZIP code           | text          | number        |
| Yes      | time           | addeddate         | Added Date         | calendar_date | calendar_date |
| No       |                | issueddate        | Issue Date         | calendar_date | calendar_date |
| No       |                | finaleddate       | Final Date         | calendar_date | calendar_date |
| Yes      | numeric metric | buildingarea      | Building Area      | number        | number        |
| Yes      | numeric metric | declaredvaluation | Declared Valuation | money         | money         |
| Yes      | series tag     | description       | Description        | text          | text          |
| Yes      | series tag     | applicationtype   | Application Type   | text          | text          |
| Yes      | series tag     | worktype          | Work Type          | text          | text          |
| Yes      | series tag     | usecode           | Use Code           | text          | text          |
```

## Time Field

```ls
Value = addeddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issueddate,finaleddate
```

## Data Commands

```ls
series e:i26v-w6bd d:2000-01-03T09:01:25.000Z t:stno=19850 t:zip=20874 t:applicationtype="COMMERCIAL BUILDING" t:permitno=208677 t:status=Finaled t:state=MD t:usecode="MULTI-FAMILY DWELLING" t:stname=CENTURY t:worktype=CONSTRUCT t:suffix=BLVD t:city=GERMANTOWN m:buildingarea=42600 m:declaredvaluation=1000000

series e:i26v-w6bd d:2000-01-03T09:01:55.000Z t:stno=12903 t:zip=20874 t:applicationtype="COMMERCIAL BUILDING" t:permitno=208679 t:status=Finaled t:state=MD t:usecode="MULTI-FAMILY DWELLING" t:stname=PINNACLE t:worktype=CONSTRUCT t:suffix=DR t:city=GERMANTOWN m:buildingarea=42600 m:declaredvaluation=1000000

series e:i26v-w6bd d:2000-01-03T10:01:56.000Z t:stno=12907 t:zip=20874 t:applicationtype="COMMERCIAL BUILDING" t:permitno=208689 t:status=Finaled t:state=MD t:usecode="MULTI-FAMILY DWELLING" t:stname=PINNACLE t:worktype=CONSTRUCT t:suffix=DR t:city=GERMANTOWN m:buildingarea=63300 m:declaredvaluation=1500000
```

## Meta Commands

```ls
metric m:buildingarea p:integer l:"Building Area" d:"The number of square feet for the proposed construction. For a new home, it is the entire building area. For an addition or alteration, it represents only the area of the affected space, not the entire structure" t:dataTypeName=number

metric m:declaredvaluation p:integer l:"Declared Valuation" d:"The value or cost of the proposed construction or work as declared by the applicant" t:dataTypeName=money

entity e:i26v-w6bd l:"Commercial Permits" t:url=https://data.montgomerycountymd.gov/api/views/i26v-w6bd

property e:i26v-w6bd t:meta.view v:id=i26v-w6bd v:category=Licenses/Permits v:averageRating=0 v:name="Commercial Permits"

property e:i26v-w6bd t:meta.view.license v:name="Public Domain"

property e:i26v-w6bd t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:i26v-w6bd t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status  | stno  | predir | stname        | suffix | postdir | city       | state | zip   | addeddate           | issueddate          | finaleddate         | buildingarea | declaredvaluation | description                                                                                                                                                                                                                                                                                                                                                                                         | applicationtype     | worktype  | usecode                        | 
| ======== | ======= | ===== | ====== | ============= | ====== | ======= | ========== | ===== | ===== | =================== | =================== | =================== | ============ | ================= | =================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | ========= | ============================== | 
| 208677   | Finaled | 19850 |        | CENTURY       | BLVD   |         | GERMANTOWN | MD    | 20874 | 2000-01-03T09:01:25 | 2000-12-14T02:12:00 | 2001-10-10T03:10:00 | 42600        | 1000000           |                                                                                                                                                                                                                                                                                                                                                                                                     | COMMERCIAL BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING          | 
| 208679   | Finaled | 12903 |        | PINNACLE      | DR     |         | GERMANTOWN | MD    | 20874 | 2000-01-03T09:01:55 | 2000-12-14T02:12:00 | 2001-10-12T03:10:00 | 42600        | 1000000           |                                                                                                                                                                                                                                                                                                                                                                                                     | COMMERCIAL BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING          | 
| 208689   | Finaled | 12907 |        | PINNACLE      | DR     |         | GERMANTOWN | MD    | 20874 | 2000-01-03T10:01:56 | 2000-12-14T02:12:00 | 2002-01-31T12:01:00 | 63300        | 1500000           |                                                                                                                                                                                                                                                                                                                                                                                                     | COMMERCIAL BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING          | 
| 208691   | Finaled | 12925 |        | PINNACLE      | DR     |         | GERMANTOWN | MD    | 20874 | 2000-01-03T10:01:55 | 2000-12-14T02:12:00 | 2002-01-25T02:01:00 | 63300        | 1500000           |                                                                                                                                                                                                                                                                                                                                                                                                     | COMMERCIAL BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING          | 
| 208782   | Finaled | 20001 |        | CRYSTAL ROCK  | DR     |         | GERMANTOWN | MD    | 20874 | 2000-01-04T12:01:16 | 2000-12-14T02:12:00 | 2001-12-14T02:12:00 | 36400        | 750000            |                                                                                                                                                                                                                                                                                                                                                                                                     | COMMERCIAL BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING          | 
| 208783   | Finaled | 20001 |        | CRYSTAL ROCK  | DR     |         | GERMANTOWN | MD    | 20874 | 2000-01-04T12:01:36 | 2000-12-14T02:12:00 | 2001-12-14T02:12:00 | 36400        | 750000            |                                                                                                                                                                                                                                                                                                                                                                                                     | COMMERCIAL BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING          | 
| 448500   | Issued  | 20302 |        | CIDER BARREL  | DR     |         | GERMANTOWN | MD    | 20876 | 2007-03-27T08:03:10 | 2008-05-07T03:05:00 |                     | 2000         | 100000            | (Code 2003) Lot 240 **Reinstatement of permit granted==Permit valid until 1/1/11** PERMIT EXTENDED until 09/23/2012****REVISION submitted 09/06/11 - Electrical, Mechanical, & Structural, Architectural...rev sq ft = 100; cost $1000 (emc)***REVISION issued 2/22/12 (emc)                                                                                                                        | COMMERCIAL BUILDING | CONSTRUCT | TOWNHOUSE                      | 
| 448648   | Finaled | 11924 |        | WEYBRIDGE     | LN     |         | GERMANTOWN | MD    | 20876 | 2007-03-28T08:03:07 | 2008-04-04T03:04:00 | 2013-03-11T06:03:57 | 2000         | 100000            | (Code 2003) Lot 254 **Reinstatement of permit granted==Permit valid until 1/1/11** PERMIT EXTENDED until 09/23/2012****REVISION submitted 09/06/11 - Electrical, Mechanical, & Structural, Architectural...rev sq ft = 100; cost $1000 (emc)***REVISION issued 2/22/12 (emc);11-01-2013-EXPIRATION DATE CHANGED TO 03-23-2013- DUE TO PASSED INSPECTION ON:10-03-2012(JR) PER MS.LUCAS' S APPROVAL. | COMMERCIAL BUILDING | CONSTRUCT | TOWNHOUSE                      | 
| 456566   | Issued  | 8111  |        | RIVER         | RD     |         | BETHESDA   | MD    | 20817 | 2007-06-14T08:06:00 | 2014-03-07T11:03:05 |                     | 280005       | 5500000           | Building 1 &  4 Parking garage underneath.  REVISION - 4/17/14 - STRUCTURAL, ELECTRICAL, MECHANICAL, ARCHITECTURAL CHANGES. $250,000 COST PER APPLICATION, 280,005 SQUARE FEET. - MS                                                                                                                                                                                                                | COMMERCIAL BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING          | 
| 547681   | Issued  | 21000 |        | FATHER HURLEY | BLVD   |         | GERMANTOWN | MD    | 20874 | 2010-08-30T11:08:27 | 2014-10-30T09:10:13 |                     | 156769       | 14500000          | Churchill Senior Phase II - 133 units - U&O# 266735 **REVISION** 11/27/15  Accross all disclipines (LW) REVISION 11/27/15 IS AN ATERATION NOT NEW CONSTRUCTION.  USE THE $50,000.00 ESTIMATED PROJECT COST SUBMITTED FOR REVISION 11/27/15 AS A FACTOR TO COMPUTE THIS PERMIT FEE. Revision issued and picked up on 4/12/16 (emc)                                                                   | COMMERCIAL BUILDING | CONSTRUCT | MULTI-FAMILY SENIOR CITIZEN BL | 
```