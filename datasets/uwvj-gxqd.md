# Commercial Impact Tax for Gaithersburg

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commercial-impact-tax-for-gaithersburg) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/uwvj-gxqd) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/uwvj-gxqd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/uwvj-gxqd/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | uwvj-gxqd |
| Name | Commercial Impact Tax for Gaithersburg |
| Category | Licenses/Permits |
| Tags | commercial, impact, taxes, gaithersburg |
| Created | 2015-10-13T20:44:11Z |
| Publication Date | 2015-10-29T19:17:05Z |

## Description

Impact Taxes for Commercial permits in the City of Gaithersburg. Update Frequency : Daily

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                         | Data Type     | Render Type   |
| ======== | ============== | =============== | ============================ | ============= | ============= |
| Yes      | series tag     | permitno        | Permit Number                | text          | text          |
| Yes      | series tag     | status          | Status                       | text          | text          |
| Yes      | time           | processeddate   | Processed Date               | calendar_date | calendar_date |
| No       |                | issueddate      | Issued Date                  | calendar_date | calendar_date |
| No       |                | finaleddate     | Finaled Date                 | calendar_date | calendar_date |
| Yes      | series tag     | description     | Description                  | text          | text          |
| Yes      | series tag     | applicationtype | Application Type             | text          | text          |
| Yes      | series tag     | worktype        | Work Type                    | text          | text          |
| Yes      | series tag     | usecode         | Use code                     | text          | text          |
| Yes      | numeric metric | no_of_units     | Number of Dwelling units     | number        | number        |
| Yes      | series tag     | hige_rise       | High Rise                    | text          | text          |
| Yes      | series tag     | tax_description | Tax Description              | text          | text          |
| Yes      | numeric metric | tax_amount      | Tax Amount                   | money         | money         |
| Yes      | series tag     | tax_status      | Tax Status                   | text          | text          |
| No       |                | tax_paiddate    | Tax Paid Date                | calendar_date | calendar_date |
| Yes      | series tag     | stno            | Street Number                | text          | text          |
| Yes      | series tag     | predir          | Pre-direction                | text          | text          |
| Yes      | series tag     | stname          | Street name of work location | text          | text          |
| Yes      | series tag     | suffix          | Street Suffix                | text          | text          |
| Yes      | series tag     | postdir         | Post-direction               | text          | text          |
| Yes      | series tag     | city            | City                         | text          | text          |
| Yes      | series tag     | state           | State                        | text          | text          |
| Yes      | series tag     | zip             | ZIP code                     | text          | text          |
```

## Time Field

```ls
Value = processeddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issueddate,finaleddate,tax_paiddate
```

## Data Commands

```ls
series e:uwvj-gxqd d:2002-12-27T11:12:00.000Z t:stno=662 t:hige_rise=N t:zip=20878 t:applicationtype="GAITHERSBURG COM. BUILDING" t:permitno=295211 t:status=Issued t:tax_description="IMPACT TAX, COUNTY DISTRICT" t:state=MD t:tax_status=PAID t:usecode="MERCANTILE BUILDING" t:stname="QUINCE ORCHARD" t:worktype=CONSTRUCT t:suffix=RD t:city=GAITHERSBURG m:no_of_units=0 m:tax_amount=2958.38

series e:uwvj-gxqd d:2003-01-17T02:01:00.000Z t:stno=4 t:hige_rise=N t:zip=20878 t:applicationtype="GAITHERSBURG COM. BUILDING" t:permitno=296285 t:status=Issued t:tax_description="IMPACT TAX, COUNTY DISTRICT" t:state=MD t:tax_status=PAID t:usecode="MERCANTILE BUILDING" t:stname=BUREAU t:worktype=CONSTRUCT t:suffix=DR t:city=GAITHERSBURG m:no_of_units=0 m:tax_amount=1128.38

series e:uwvj-gxqd d:2003-01-29T11:01:00.000Z t:stno=750 t:hige_rise=N t:zip=20878 t:applicationtype="GAITHERSBURG COM. BUILDING" t:permitno=297077 t:status=Finaled t:tax_description="IMPACT TAX, COUNTY DISTRICT" t:state=MD t:tax_status=PAID t:usecode="ASSEMBLY BUILDING" t:stname=CLOPPER t:worktype=CONSTRUCT t:suffix=RD t:city=GAITHERSBURG m:no_of_units=0 m:tax_amount=1980
```

## Meta Commands

```ls
metric m:no_of_units p:integer l:"Number of Dwelling units" d:"Number of dwelling units" t:dataTypeName=number

metric m:tax_amount p:double l:"Tax Amount" d:"Amount of the tax" t:dataTypeName=money

entity e:uwvj-gxqd l:"Commercial Impact Tax for Gaithersburg" t:url=https://data.montgomerycountymd.gov/api/views/uwvj-gxqd

property e:uwvj-gxqd t:meta.view v:id=uwvj-gxqd v:category=Licenses/Permits v:averageRating=0 v:name="Commercial Impact Tax for Gaithersburg"

property e:uwvj-gxqd t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:uwvj-gxqd t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status  | processeddate       | issueddate          | finaleddate         | description                     | applicationtype            | worktype  | usecode               | no_of_units | hige_rise | tax_description             | tax_amount | tax_status | tax_paiddate        | stno | predir | stname         | suffix | postdir | city         | state | zip   | 
| ======== | ======= | =================== | =================== | =================== | =============================== | ========================== | ========= | ===================== | =========== | ========= | =========================== | ========== | ========== | =================== | ==== | ====== | ============== | ====== | ======= | ============ | ===== | ===== | 
| 295211   | Issued  | 2002-12-27T11:12:00 | 2002-12-27T11:12:00 |                     |                                 | GAITHERSBURG COM. BUILDING | CONSTRUCT | MERCANTILE BUILDING   | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 2958.38    | PAID       | 2002-12-27T11:12:14 | 662  |        | QUINCE ORCHARD | RD     |         | GAITHERSBURG | MD    | 20878 | 
| 296285   | Issued  | 2003-01-17T02:01:00 | 2003-01-17T02:01:00 |                     |                                 | GAITHERSBURG COM. BUILDING | CONSTRUCT | MERCANTILE BUILDING   | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 1128.38    | PAID       | 2003-01-17T02:01:49 | 4    |        | BUREAU         | DR     |         | GAITHERSBURG | MD    | 20878 | 
| 297077   | Finaled | 2003-01-29T11:01:00 | 2003-01-29T11:01:00 | 2003-01-29T11:01:00 |                                 | GAITHERSBURG COM. BUILDING | CONSTRUCT | ASSEMBLY BUILDING     | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 1980       | PAID       | 2003-01-29T11:01:38 | 750  |        | CLOPPER        | RD     |         | GAITHERSBURG | MD    | 20878 | 
| 307028   | Issued  | 2003-05-27T12:05:00 | 2007-02-09T08:02:00 |                     |                                 | GAITHERSBURG COM. BUILDING | CONSTRUCT |                       | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 0          | UNPAID     |                     |      |        |                |        |         |              |       |       | 
| 314812   | Issued  | 2003-08-06T11:08:00 | 2003-08-06T12:08:00 |                     |                                 | GAITHERSBURG COM. BUILDING | CONSTRUCT |                       | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 33928.5    | PAID       | 2003-08-06T12:08:21 |      |        |                |        |         |              |       |       | 
| 770599   | Open    | 2016-09-01T01:09:14 |                     |                     |                                 | GAITHERSBURG COM. BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING | 1           | N         | SCHOOLS IMPACT TAX          | 12765      | PAID       | 2016-09-01T02:09:41 |      |        |                |        |         |              |       |       | 
| 770601   | Open    | 2016-09-01T01:09:10 |                     |                     |                                 | GAITHERSBURG COM. BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING | 1           | N         | SCHOOLS IMPACT TAX          | 12765      | PAID       | 2016-09-01T02:09:13 |      |        |                |        |         |              |       |       | 
| 381146   | Finaled | 2005-04-26T11:04:00 | 2005-04-26T11:04:00 | 2005-04-26T11:04:00 | City of Gaithersburg Impax Tax. | GAITHERSBURG COM. BUILDING | CONSTRUCT | MERCANTILE BUILDING   | 0           | N         | IMPACT TAX >MAR04-GENERAL   | 17991      | PAID       | 2005-04-26T11:04:37 | 84   |        | BUREAU         | DR     |         | GAITHERSBURG | MD    | 20878 | 
| 391994   | Finaled | 2005-07-27T11:07:00 | 2005-07-27T11:07:00 | 2005-07-27T11:07:00 |                                 | GAITHERSBURG COM. BUILDING | CONSTRUCT | PLACE OF WORSHIP      | 0           | N         | IMPACT TAX >JUL05-GENERAL   | 4943.1     | PAID       | 2005-07-27T11:07:01 | 1409 |        | MAIN           | ST     |         | GAITHERSBURG | MD    | 20878 | 
| 387412   | Finaled | 2005-06-15T03:06:00 | 2005-06-15T03:06:00 | 2005-06-15T03:06:00 | PI-B050110                      | GAITHERSBURG COM. BUILDING | CONSTRUCT | BUSINESS BUILDING     | 0           | N         | IMPACT TAX >MAR04-GENERAL   | 98700      | PAID       | 2005-06-15T03:06:05 | 17   |        | FIRSTFIELD     | RD     |         | GAITHERSBURG | MD    | 20878 | 
```