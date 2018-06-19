# Commercial Impact Tax for Rockville

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commercial-impact-tax-for-rockville) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/r5vz-knwn) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/r5vz-knwn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/r5vz-knwn/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | r5vz-knwn |
| Name | Commercial Impact Tax for Rockville |
| Category | Licenses/Permits |
| Tags | commercial, impact, taxes, rockville |
| Created | 2015-10-13T20:55:15Z |
| Publication Date | 2015-10-29T19:35:27Z |

## Description

Impact Taxes for Commercial permits in the City of Rockville. Update Frequency : Daily

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
series e:r5vz-knwn d:2002-09-09T03:09:00.000Z t:stno=14949 t:hige_rise=N t:zip=20850 t:applicationtype="ROCKVILLE COM. BUILDING" t:permitno=287143 t:status=Issued t:tax_description="IMPACT TAX, COUNTY DISTRICT" t:state=MD t:tax_status=UNPAID t:usecode="BUSINESS BUILDING" t:stname="SHADY GROVE" t:worktype=CONSTRUCT t:suffix=RD t:city=ROCKVILLE m:no_of_units=0 m:tax_amount=1093.5

series e:r5vz-knwn d:2002-10-10T11:10:00.000Z t:stno=1799 t:zip=20852 t:permitno=289814 t:predir=E t:status=Issued t:tax_status=PAID t:state=MD t:usecode="MULTI-FAMILY DWELLING" t:stname=JEFFERSON t:suffix=ST t:city=ROCKVILLE t:hige_rise=N t:applicationtype="ROCKVILLE COM. BUILDING" t:tax_description="IMPACT TAX, METRO STATION POLICY AREA" t:worktype=CONSTRUCT m:no_of_units=0 m:tax_amount=2437.5

series e:r5vz-knwn d:2005-05-04T02:05:28.000Z t:stno=255 t:zip=20850 t:permitno=382253 t:predir=N t:status=Finaled t:tax_status=PAID t:state=MD t:usecode="MULTI-FAMILY DWELLING" t:stname=WASHINGTON t:suffix=ST t:city=ROCKVILLE t:hige_rise=Y t:applicationtype="ROCKVILLE COM. BUILDING" t:description=BLD2005-10952 t:tax_description="IMPACT TAX >MAR04-ROCKVILLE TOWN CENTER" t:worktype=CONSTRUCT m:no_of_units=204 m:tax_amount=255000
```

## Meta Commands

```ls
metric m:no_of_units p:integer l:"Number of Dwelling units" d:"Number of dwelling units" t:dataTypeName=number

metric m:tax_amount p:double l:"Tax Amount" d:"Amount of the tax" t:dataTypeName=money

entity e:r5vz-knwn l:"Commercial Impact Tax for Rockville" t:url=https://data.montgomerycountymd.gov/api/views/r5vz-knwn

property e:r5vz-knwn t:meta.view v:id=r5vz-knwn v:category=Licenses/Permits v:averageRating=0 v:name="Commercial Impact Tax for Rockville"

property e:r5vz-knwn t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:r5vz-knwn t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status  | processeddate       | issueddate          | finaleddate         | description                                        | applicationtype         | worktype  | usecode               | no_of_units | hige_rise | tax_description                         | tax_amount | tax_status | tax_paiddate        | stno  | predir | stname       | suffix | postdir | city         | state | zip   | 
| ======== | ======= | =================== | =================== | =================== | ================================================== | ======================= | ========= | ===================== | =========== | ========= | ======================================= | ========== | ========== | =================== | ===== | ====== | ============ | ====== | ======= | ============ | ===== | ===== | 
| 287143   | Issued  | 2002-09-09T03:09:00 | 2002-09-17T08:09:00 |                     |                                                    | ROCKVILLE COM. BUILDING | CONSTRUCT | BUSINESS BUILDING     | 0           | N         | IMPACT TAX, COUNTY DISTRICT             | 1093.5     | UNPAID     |                     | 14949 |        | SHADY GROVE  | RD     |         | ROCKVILLE    | MD    | 20850 | 
| 289814   | Issued  | 2002-10-10T11:10:00 | 2002-10-10T11:10:00 |                     |                                                    | ROCKVILLE COM. BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING | 0           | N         | IMPACT TAX, METRO STATION POLICY AREA   | 2437.5     | PAID       | 2002-10-10T11:10:51 | 1799  | E      | JEFFERSON    | ST     |         | ROCKVILLE    | MD    | 20852 | 
| 382253   | Finaled | 2005-05-04T02:05:28 | 2005-05-04T02:05:26 | 2005-05-04T02:05:28 | BLD2005-10952                                      | ROCKVILLE COM. BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING | 204         | Y         | IMPACT TAX >MAR04-ROCKVILLE TOWN CENTER | 255000     | PAID       | 2005-05-04T12:05:00 | 255   | N      | WASHINGTON   | ST     |         | ROCKVILLE    | MD    | 20850 | 
| 315281   | Issued  | 2003-08-11T02:08:00 | 2003-08-11T03:08:00 |                     |                                                    | ROCKVILLE COM. BUILDING | CONSTRUCT | BUSINESS BUILDING     | 0           | N         | IMPACT TAX, COUNTY DISTRICT             | 144099.75  | UNPAID     |                     | 1     |        | CHOKE CHERRY | RD     |         | ROCKVILLE    | MD    | 20850 | 
| 317317   | Finaled | 2003-09-02T08:09:00 | 2003-09-02T08:09:00 | 2003-10-24T02:10:43 |                                                    | ROCKVILLE COM. BUILDING | CONSTRUCT | BUSINESS BUILDING     | 0           | N         | IMPACT TAX, METRO STATION POLICY AREA   | 1692.56    | PAID       | 2003-09-02T08:09:18 | 387   |        | HUNGERFORD   | DR     |         | ROCKVILLE    | MD    | 20850 | 
| 385858   | Finaled | 2005-06-02T02:06:00 | 2007-02-08T01:02:00 | 2007-02-08T01:02:48 | Bld 2005-11109, 92 highrise units and retail below | ROCKVILLE COM. BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING | 92          | Y         | SCHOOLS IMPACT TAX                      | 147200     | PAID       | 2005-06-02T02:06:19 | 360   |        | HUNGERFORD   | DR     |         | ROCKVILLE    | MD    | 20850 | 
| 342502   | Finaled | 2004-04-28T12:04:00 | 2004-04-28T12:04:00 | 2004-04-28T12:04:00 |                                                    | ROCKVILLE COM. BUILDING | CONSTRUCT | ASSEMBLY, CHURCHES    | 0           | N         | IMPACT TAX >MAR04-ROCKVILLE TOWN CENTER | 942.3      | PAID       | 2004-04-28T12:04:55 | 24518 |        | WELSH        | RD     |         | GAITHERSBURG | MD    | 20882 | 
| 342502   | Finaled | 2004-04-28T12:04:00 | 2004-04-28T12:04:00 | 2004-04-28T12:04:00 |                                                    | ROCKVILLE COM. BUILDING | CONSTRUCT | ASSEMBLY, CHURCHES    | 0           | N         | IMPACT TAX >MAR04-ROCKVILLE TOWN CENTER | 0          | UNPAID     |                     | 24518 |        | WELSH        | RD     |         | GAITHERSBURG | MD    | 20882 | 
| 349220   | Finaled | 2004-06-23T03:06:10 | 2004-06-23T03:06:25 | 2004-06-23T03:06:47 | BLD2004-09668                                      | ROCKVILLE COM. BUILDING | CONSTRUCT |                       | 0           | N         | IMPACT TAX, COUNTY DISTRICT             | 59566      | PAID       | 2004-06-23T12:06:00 | 701   |        | DOVER        | RD     |         | ROCKVILLE    | MD    | 20850 | 
| 433573   | Finaled | 2006-09-19T11:09:00 | 2006-09-19T11:09:00 | 2006-10-23T12:10:05 | SFD2006-02692-Demolition/rebuild                   | ROCKVILLE COM. BUILDING | CONSTRUCT | MULTI-FAMILY DWELLING | 0           | N         | SCHOOLS IMPACT TAX                      | 8464       | UNPAID     |                     | 155   |        | MOORE        | DR     |         | ROCKVILLE    | MD    | 20850 | 
```