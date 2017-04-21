# Commercial Fast Track Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commercial-fast-track-permits) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/drdm-p89i) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/drdm-p89i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/drdm-p89i/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | drdm-p89i |
| Name | Commercial Fast Track Permits |
| Category | Licenses/Permits |
| Tags | permit, fast_track, process, commercial, alteration, permits issued |
| Created | 2015-03-25T00:11:07Z |
| Publication Date | 2015-03-25T13:35:16Z |

## Description

Commercial alteration permits issued through DPS' Fast Track process. Update Frequency : Daily.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                         | Data Type     | Render Type   |
| ======== | ============== | ================= | ============================ | ============= | ============= |
| Yes      | series tag     | permitno          | Permit Number                | text          | text          |
| Yes      | time           | processdate       | Processed Date               | calendar_date | calendar_date |
| No       |                | issueddate        | Issued Date                  | calendar_date | calendar_date |
| No       |                | finaleddate       | Finaled Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | buildingarea      | Building Area                | number        | number        |
| Yes      | numeric metric | declaredvaluation | Declared Valuation           | number        | number        |
| Yes      | series tag     | description       | Description                  | text          | text          |
| Yes      | series tag     | worktype          | Work Type                    | text          | text          |
| Yes      | series tag     | usecode           | Use Code                     | text          | text          |
| Yes      | series tag     | stno              | Street Number                | text          | text          |
| Yes      | series tag     | predir            | Pre-direction                | text          | text          |
| Yes      | series tag     | stname            | Street name of work location | text          | text          |
| Yes      | series tag     | suffix            | Street Suffix                | text          | text          |
| Yes      | series tag     | postdir           | Post-direction               | text          | text          |
| Yes      | series tag     | city              | City                         | text          | text          |
| Yes      | series tag     | state             | State                        | text          | text          |
| Yes      | series tag     | zip               | ZIP code                     | text          | text          |
```

## Time Field

```ls
Value = processdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issueddate,finaleddate
```

## Data Commands

```ls
series e:drdm-p89i d:2013-10-02T00:00:00.000Z t:stno=8455 t:zip=20910 t:permitno=650428 t:description="INTERIOR ALTERATIONS (SUITE 8000)" t:state=MD t:usecode="BUSINESS BUILDING" t:stname=COLESVILLE t:worktype=ALTER t:suffix=RD t:city="SILVER SPRING" m:buildingarea=14699 m:declaredvaluation=220000

series e:drdm-p89i d:2008-03-11T00:00:00.000Z t:stno=7735 t:zip=20814 t:permitno=479790 t:description="interior alteration adding furniture" t:state=MD t:usecode="BUSINESS BUILDING" t:stname="OLD GEORGETOWN" t:worktype=ALTER t:suffix=RD t:city=BETHESDA m:buildingarea=3000 m:declaredvaluation=15000

series e:drdm-p89i d:2001-11-27T00:00:00.000Z t:stno=9601 t:zip=20850 t:permitno=264170 t:state=MD t:usecode="BUSINESS BUILDING" t:stname=BLACKWELL t:worktype=ALTER t:suffix=RD t:city=ROCKVILLE m:buildingarea=2820 m:declaredvaluation=20000
```

## Meta Commands

```ls
metric m:buildingarea p:double l:"Building Area" d:"The number of square feet for the proposed construction alterations, it represents only the area of the affected space, not the entire structure." t:dataTypeName=number

metric m:declaredvaluation p:integer l:"Declared Valuation" d:"The value or cost of the proposed construction or work as declared by the applicant" t:dataTypeName=number

entity e:drdm-p89i l:"Commercial Fast Track Permits" t:url=https://data.montgomerycountymd.gov/api/views/drdm-p89i

property e:drdm-p89i t:meta.view v:id=drdm-p89i v:category=Licenses/Permits v:averageRating=0 v:name="Commercial Fast Track Permits"

property e:drdm-p89i t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:drdm-p89i t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | processdate         | issueddate          | finaleddate         | buildingarea | declaredvaluation | description                                 | worktype | usecode                        | stno | predir | stname         | suffix | postdir | city          | state | zip   | 
| ======== | =================== | =================== | =================== | ============ | ================= | =========================================== | ======== | ============================== | ==== | ====== | ============== | ====== | ======= | ============= | ===== | ===== | 
| 650428   | 2013-10-02T00:00:00 | 2013-10-18T00:00:00 | 2013-12-19T00:00:00 | 14699        | 220000            | INTERIOR ALTERATIONS (SUITE 8000)           | ALTER    | BUSINESS BUILDING              | 8455 |        | COLESVILLE     | RD     |         | SILVER SPRING | MD    | 20910 | 
| 479790   | 2008-03-11T00:00:00 | 2008-03-12T00:00:00 | 2008-06-05T00:00:00 | 3000         | 15000             | interior alteration adding furniture        | ALTER    | BUSINESS BUILDING              | 7735 |        | OLD GEORGETOWN | RD     |         | BETHESDA      | MD    | 20814 | 
| 264170   | 2001-11-27T00:00:00 | 2001-12-04T00:00:00 |                     | 2820         | 20000             |                                             | ALTER    | BUSINESS BUILDING              | 9601 |        | BLACKWELL      | RD     |         | ROCKVILLE     | MD    | 20850 | 
| 392831   | 2005-08-03T00:00:00 | 2005-08-05T00:00:00 | 2005-09-19T00:00:00 | 168          | 15000             | Interior Alterations.                       | ALTER    | BUSINESS                       | 6410 |        | ROCKLEDGE      | DR     |         | BETHESDA      | MD    | 20817 | 
| 591439   | 2012-02-16T00:00:00 | 2012-02-16T00:00:00 |                     | 80           | 36000             | interior alteration 5th floor               | ALTER    | BUSINESS BUILDING              | 3    |        | BETHESDA METRO | CIR    |         | BETHESDA      | MD    | 20814 | 
| 582608   | 2011-10-20T00:00:00 | 2011-10-20T00:00:00 | 2011-10-28T00:00:00 | 200          | 8000              | Interior Alterations                        | ALTER    | BUSINESS BUILDING              | 4550 |        | MONTGOMERY     | AVE    |         | BETHESDA      | MD    | 20814 | 
| 419736   | 2006-05-03T00:00:00 | 2006-06-05T00:00:00 | 2006-08-31T00:00:00 | 2380         | 105000            | suite g-02                                  | ALTER    | BUSINESS BUILDING              | 4701 |        | RANDOLPH       | RD     |         | ROCKVILLE     | MD    | 20852 | 
| 386075   | 2005-06-06T00:00:00 | 2005-07-07T00:00:00 | 2005-11-17T00:00:00 | 3567         | 110000            |                                             | ALTER    | BUSINESS BUILDING              | 5454 |        | WISCONSIN      | AVE    |         | CHEVY CHASE   | MD    | 20815 | 
| 476614   | 2008-01-25T00:00:00 | 2008-01-31T00:00:00 | 2008-05-09T00:00:00 | 300          | 110000            | interior alteration                         | ALTER    | MULTI-FAMILY SENIOR CITIZEN BL | 5600 |        | WISCONSIN      | AVE    |         | CHEVY CHASE   | MD    | 20815 | 
| 627352   | 2013-02-28T00:00:00 | 2013-04-25T00:00:00 |                     | 1140         | 55000             | INTERIOR ALTERATIONS TO COMMERCIAL PROPERTY | ALTER    | BUSINESS BUILDING              | 7818 |        | OLD GEORGETOWN | RD     |         | BETHESDA      | MD    | 20814 | 
```