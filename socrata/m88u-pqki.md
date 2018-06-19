# Residential Permit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-permit-8f8f0) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/m88u-pqki) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/m88u-pqki/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/m88u-pqki/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | m88u-pqki |
| Name | Residential Permit |
| Category | Licenses/Permits |
| Tags | licenses, permits, residential |
| Created | 2012-08-01T12:17:51Z |
| Publication Date | 2013-11-12T05:45:50Z |

## Description

Data for all Residential Building Permits issued since 2000, including status and work performed. Update Frequency: Daily

## Columns

```ls
| Included | Schema Type    | Field Name        | Name               | Data Type     | Render Type   |
| ======== | ============== | ================= | ================== | ============= | ============= |
| Yes      | series tag     | permitno          | Permit Number      | text          | text          |
| Yes      | series tag     | status            | Status             | text          | text          |
| Yes      | series tag     | stno              | Street Number      | text          | text          |
| Yes      | series tag     | stname            | Street Name        | text          | text          |
| Yes      | series tag     | suffix            | Street Suffix      | text          | text          |
| Yes      | series tag     | postdir           | Post-direction     | text          | text          |
| Yes      | series tag     | city              | City               | text          | text          |
| Yes      | series tag     | state             | State              | text          | text          |
| Yes      | series tag     | zip               | ZIP code           | text          | text          |
| Yes      | time           | addeddate         | Added Date         | calendar_date | calendar_date |
| No       |                | issueddate        | Issue Date         | calendar_date | calendar_date |
| No       |                | finaleddate       | Final Date         | calendar_date | calendar_date |
| Yes      | numeric metric | buildingarea      | Building Area      | number        | number        |
| Yes      | numeric metric | declaredvaluation | Declared Valuation | money         | money         |
| Yes      | series tag     | description       | Description        | text          | text          |
| Yes      | series tag     | applicationtype   | Application Type   | text          | text          |
| Yes      | series tag     | worktype          | Work Type          | text          | text          |
| Yes      | series tag     | usecode           | Use Code           | text          | text          |
| Yes      | series tag     | predir            | Pre-direction      | text          | text          |
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
series e:m88u-pqki d:2016-06-10T12:06:39.000Z t:stno=11805 t:zip=20902 t:applicationtype="BUILDING RESIDENTIAL PERMIT" t:permitno=759175 t:status=Finaled t:description="1 story addition" t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=AUTH t:worktype=ADD t:suffix=LN t:city="SILVER SPRING" m:buildingarea=266 m:declaredvaluation=110000

series e:m88u-pqki d:2000-01-03T07:01:38.000Z t:stno=6209 t:zip=20817 t:applicationtype="BUILDING RESIDENTIAL PERMIT" t:permitno=208669 t:status=Issued t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=STONEHAM t:worktype=ADD t:suffix=RD t:city=BETHESDA m:buildingarea=288 m:declaredvaluation=25000

series e:m88u-pqki d:2016-06-07T02:06:50.000Z t:stno=1108 t:zip=20906 t:applicationtype="BUILDING RESIDENTIAL PERMIT" t:permitno=758718 t:status=Finaled t:description="Customer Wants To Use ePlans,lot 25U Poplar Run Sedona" t:state=MD t:usecode="SINGLE FAMILY DWELLING" t:stname=SWEETBAY t:worktype=CONSTRUCT t:suffix=PL t:city="SILVER SPRING" m:buildingarea=6073 m:declaredvaluation=300000
```

## Meta Commands

```ls
metric m:buildingarea p:integer l:"Building Area" d:"The number of square feet for the proposed construction. For a new home, it is the entire building area. For an addition or alteration, it represents only the area of the affected space, not the entire structure" t:dataTypeName=number

metric m:declaredvaluation p:integer l:"Declared Valuation" d:"The value or cost of the proposed construction or work as declared by the applicant" t:dataTypeName=money

entity e:m88u-pqki l:"Residential Permit" t:url=https://data.montgomerycountymd.gov/api/views/m88u-pqki

property e:m88u-pqki t:meta.view v:id=m88u-pqki v:category=Licenses/Permits v:averageRating=0 v:name="Residential Permit"

property e:m88u-pqki t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:m88u-pqki t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status  | stno  | stname         | suffix | postdir | city          | state | zip   | addeddate           | issueddate          | finaleddate         | buildingarea | declaredvaluation | description                                            | applicationtype             | worktype         | usecode                | predir | 
| ======== | ======= | ===== | ============== | ====== | ======= | ============= | ===== | ===== | =================== | =================== | =================== | ============ | ================= | ====================================================== | =========================== | ================ | ====================== | ====== | 
| 759175   | Finaled | 11805 | AUTH           | LN     |         | SILVER SPRING | MD    | 20902 | 2016-06-10T12:06:39 | 2016-06-17T11:06:49 | 2017-01-17T03:01:00 | 266          | 110000            | 1 story addition                                       | BUILDING RESIDENTIAL PERMIT | ADD              | SINGLE FAMILY DWELLING |        | 
| 208669   | Issued  | 6209  | STONEHAM       | RD     |         | BETHESDA      | MD    | 20817 | 2000-01-03T07:01:38 | 2000-01-03T08:01:00 |                     | 288          | 25000             |                                                        | BUILDING RESIDENTIAL PERMIT | ADD              | SINGLE FAMILY DWELLING |        | 
| 758718   | Finaled | 1108  | SWEETBAY       | PL     |         | SILVER SPRING | MD    | 20906 | 2016-06-07T02:06:50 | 2016-07-11T09:07:44 | 2016-11-21T10:11:11 | 6073         | 300000            | Customer Wants To Use ePlans,lot 25U Poplar Run Sedona | BUILDING RESIDENTIAL PERMIT | CONSTRUCT        | SINGLE FAMILY DWELLING |        | 
| 208671   | Finaled | 6221  | TILDEN         | LN     |         | ROCKVILLE     | MD    | 20852 | 2000-01-03T07:01:15 | 2000-01-03T09:01:48 | 2001-10-30T01:10:00 | 400          | 56000             | REVISION TO PERMIT #998060250                          | BUILDING RESIDENTIAL PERMIT | BUILD FOUNDATION | SINGLE FAMILY DWELLING |        | 
| 208687   | Issued  | 4001  | CHARLEY FOREST | ST     |         | OLNEY         | MD    | 20832 | 2000-01-03T10:01:03 | 2000-01-04T03:01:00 |                     | 664          | 20000             | TWO-CAR ATTACHED GARAGE                                | BUILDING RESIDENTIAL PERMIT | ADD              | SINGLE FAMILY DWELLING |        | 
| 761067   | Finaled | 11711 | ROBERTS GLEN   | CT     |         | POTOMAC       | MD    | 20854 | 2016-06-23T09:06:06 | 2016-06-24T08:06:56 | 2016-11-21T03:11:50 | 180          | 8000              | deck                                                   | BUILDING RESIDENTIAL PERMIT | CONSTRUCT        | DECK                   |        | 
| 752510   | Finaled | 9101  | CLEWERWALL     | DR     |         | BETHESDA      | MD    | 20817 | 2016-04-21T11:04:06 | 2016-04-21T12:04:42 | 2016-11-07T08:11:56 | 500          | 45000             | INTERIOR ALTERATION                                    | BUILDING RESIDENTIAL PERMIT | ALTER            | SINGLE FAMILY DWELLING |        | 
| 208701   | Issued  | 2952  | GRACEFIELD     | RD     |         | SILVER SPRING | MD    | 20904 | 2000-01-03T11:01:55 | 2000-01-03T12:01:03 |                     | 276          | 5000              | CARPORT CONVERSION TO GARAGE                           | BUILDING RESIDENTIAL PERMIT | ALTER            | SINGLE FAMILY DWELLING |        | 
| 759594   | Finaled | 700   | DARTMOUTH      | AVE    |         | SILVER SPRING | MD    | 20910 | 2016-06-14T10:06:42 | 2016-06-15T11:06:19 | 2016-12-19T06:12:49 | 450          | 50000             | Alter basement                                         | BUILDING RESIDENTIAL PERMIT | ALTER            | SINGLE FAMILY DWELLING |        | 
| 208748   | Finaled | 13320 | TRAVILAH       | RD     |         | GAITHERSBURG  | MD    | 20878 | 2000-01-04T09:01:16 | 2000-05-04T03:05:00 | 2000-07-25T03:07:00 | 399          | 20000             |                                                        | BUILDING RESIDENTIAL PERMIT | ADD              | SINGLE FAMILY DWELLING |        | 
```