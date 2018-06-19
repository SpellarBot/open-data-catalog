# Residential Impact Tax for Rockville

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-impact-tax-for-rockville) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/3q4c-igb4) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/3q4c-igb4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/3q4c-igb4/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 3q4c-igb4 |
| Name | Residential Impact Tax for Rockville |
| Category | Licenses/Permits |
| Tags | residential, impact, taxes, rockville |
| Created | 2015-10-13T21:23:01Z |
| Publication Date | 2015-10-29T19:32:22Z |

## Description

Impact Taxes for residential permits in the City of Rockville. Update Frequency : Daily

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
series e:3q4c-igb4 d:2002-07-31T11:07:00.000Z t:stno=903 t:hige_rise=N t:zip=20850 t:applicationtype="ROCKVILLE RES. BUILDING" t:permitno=284125 t:status=Finaled t:tax_description="IMPACT TAX, COUNTY DISTRICT" t:state=MD t:tax_status=UNPAID t:usecode=TOWNHOUSE t:stname=CRESTFIELD t:worktype=CONSTRUCT t:suffix=DR t:city=ROCKVILLE m:no_of_units=0 m:tax_amount=525

series e:3q4c-igb4 d:2002-07-31T11:07:00.000Z t:stno=903 t:hige_rise=N t:zip=20850 t:applicationtype="ROCKVILLE RES. BUILDING" t:permitno=284125 t:status=Finaled t:tax_description="IMPACT TAX, COUNTY DISTRICT" t:state=MD t:tax_status=UNPAID t:usecode=TOWNHOUSE t:stname=CRESTFIELD t:worktype=CONSTRUCT t:suffix=DR t:city=ROCKVILLE m:no_of_units=0 m:tax_amount=0

series e:3q4c-igb4 d:2002-07-31T11:07:00.000Z t:stno=903 t:hige_rise=N t:zip=20850 t:applicationtype="ROCKVILLE RES. BUILDING" t:permitno=284125 t:status=Finaled t:tax_description="IMPACT TAX, COUNTY DISTRICT" t:state=MD t:tax_status=UNPAID t:usecode=TOWNHOUSE t:stname=CRESTFIELD t:worktype=CONSTRUCT t:suffix=DR t:city=ROCKVILLE m:no_of_units=0 m:tax_amount=0
```

## Meta Commands

```ls
metric m:no_of_units p:integer l:"Number of Dwelling units" d:"Number of dwelling units" t:dataTypeName=number

metric m:tax_amount p:double l:"Tax Amount" d:"Amount of the tax" t:dataTypeName=money

entity e:3q4c-igb4 l:"Residential Impact Tax for Rockville" t:url=https://data.montgomerycountymd.gov/api/views/3q4c-igb4

property e:3q4c-igb4 t:meta.view v:id=3q4c-igb4 v:category=Licenses/Permits v:averageRating=0 v:name="Residential Impact Tax for Rockville"

property e:3q4c-igb4 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:3q4c-igb4 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status  | processeddate       | issueddate          | finaleddate         | description | applicationtype         | worktype  | usecode                | no_of_units | hige_rise | tax_description             | tax_amount | tax_status | tax_paiddate        | stno | predir | stname     | suffix | postdir | city      | state | zip   | 
| ======== | ======= | =================== | =================== | =================== | =========== | ======================= | ========= | ====================== | =========== | ========= | =========================== | ========== | ========== | =================== | ==== | ====== | ========== | ====== | ======= | ========= | ===== | ===== | 
| 284125   | Finaled | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 | 2002-08-05T12:08:10 |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 525        | UNPAID     |                     | 903  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
| 284125   | Finaled | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 | 2002-08-05T12:08:10 |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 0          | UNPAID     | 2002-08-15T02:08:56 | 903  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
| 284125   | Finaled | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 | 2002-08-05T12:08:10 |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 0          | UNPAID     | 2002-09-05T01:09:52 | 903  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
| 284125   | Finaled | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 | 2002-08-05T12:08:10 |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 525        | UNPAID     |                     | 903  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
| 284125   | Finaled | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 | 2002-08-05T12:08:10 |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 0          | UNPAID     | 2002-08-15T02:08:12 | 903  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
| 284125   | Finaled | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 | 2002-08-05T12:08:10 |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 0          | UNPAID     | 2002-08-15T02:08:55 | 903  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
| 753565   | Finaled | 2016-04-29T10:04:33 | 2016-04-29T10:04:01 | 2016-04-29T10:04:01 | SFD         | ROCKVILLE RES. BUILDING | CONSTRUCT | SINGLE FAMILY DWELLING | 0           | N         | SCHOOLS IMPACT TAX          | 25944      | PAID       | 2016-04-29T10:04:19 | 102  | S      | VAN BUREN  | ST     |         | ROCKVILLE | MD    | 20851 | 
| 284127   | Finaled | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 | 2002-07-31T12:07:00 |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 525        | PAID       | 2002-07-31T12:07:24 | 905  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
| 284128   | Finaled | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 | 2002-07-31T12:07:00 |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 525        | PAID       | 2002-07-31T12:07:28 | 907  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
| 284129   | Issued  | 2002-07-31T11:07:00 | 2002-07-31T12:07:00 |                     |             | ROCKVILLE RES. BUILDING | CONSTRUCT | TOWNHOUSE              | 0           | N         | IMPACT TAX, COUNTY DISTRICT | 525        | PAID       | 2002-07-31T12:07:14 | 909  |        | CRESTFIELD | DR     |         | ROCKVILLE | MD    | 20850 | 
```