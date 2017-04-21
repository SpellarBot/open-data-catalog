# Residential Impact Tax for Gaithersburg

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residential-impact-tax-for-gaithersburg) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/qfzq-8jxi) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/qfzq-8jxi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/qfzq-8jxi/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | qfzq-8jxi |
| Name | Residential Impact Tax for Gaithersburg |
| Category | Licenses/Permits |
| Tags | residential, impact, taxes, gaithersburg |
| Created | 2015-10-13T21:01:46Z |
| Publication Date | 2015-10-29T19:34:03Z |

## Description

Impact Taxes for residential permits in the City of Gaithersburg. Update Frequency : Daily

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
series e:qfzq-8jxi d:2005-03-08T11:03:00.000Z t:stno=600 t:zip=20877 t:permitno=375874 t:status=Finaled t:tax_status=PAID t:state=MD t:usecode=TOWNHOUSE t:stname="CEDAR SPRING" t:suffix=ST t:city=GAITHERSBURG t:hige_rise=N t:applicationtype="GAITHERSBURG RES. BUILDING" t:description="PI-Bo50163 & 164 &PI-bo50166, 167, PI-B050169-172, PI B050173-177, PI Bo505180-185" t:tax_description="SCHOOLS IMPACT TAX" t:worktype=CONSTRUCT m:no_of_units=0 m:tax_amount=114000

series e:qfzq-8jxi d:2005-04-11T10:04:00.000Z t:stno=559 t:zip=20877 t:permitno=379525 t:status=Finaled t:tax_status=PAID t:state=MD t:usecode=TOWNHOUSE t:stname=PELICAN t:suffix=AVE t:city=GAITHERSBURG t:hige_rise=N t:applicationtype="GAITHERSBURG RES. BUILDING" t:description="NINE (9) TOWNHOMES
559,563,567,571 PELICAN AVENUE
616,620,624,628,632 CEDAR SPRING STREET" t:tax_description="IMPACT TAX >MAR04-GENERAL" t:worktype=CONSTRUCT m:no_of_units=0 m:tax_amount=40500

series e:qfzq-8jxi d:2005-04-12T10:04:00.000Z t:stno=527 t:zip=20877 t:permitno=379698 t:status=Finaled t:tax_status=PAID t:state=MD t:usecode=TOWNHOUSE t:stname=PELICAN t:suffix=AVE t:city=GAITHERSBURG t:hige_rise=N t:applicationtype="GAITHERSBURG RES. BUILDING" t:description="Pelican avenue (527 thru 555) lots 30 thru 37f    Hidden Forrest Street (805 thru 829) lots 12 thru 18 D" t:tax_description="IMPACT TAX >MAR04-GENERAL" t:worktype=CONSTRUCT m:no_of_units=0 m:tax_amount=67500
```

## Meta Commands

```ls
metric m:no_of_units p:integer l:"Number of Dwelling units" d:"Number of dwelling units" t:dataTypeName=number

metric m:tax_amount p:double l:"Tax Amount" d:"Amount of the tax" t:dataTypeName=money

entity e:qfzq-8jxi l:"Residential Impact Tax for Gaithersburg" t:url=https://data.montgomerycountymd.gov/api/views/qfzq-8jxi

property e:qfzq-8jxi t:meta.view v:id=qfzq-8jxi v:category=Licenses/Permits v:averageRating=0 v:name="Residential Impact Tax for Gaithersburg"

property e:qfzq-8jxi t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:qfzq-8jxi t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| permitno | status  | processeddate       | issueddate          | finaleddate         | description                                                                                                           | applicationtype            | worktype  | usecode   | no_of_units | hige_rise | tax_description           | tax_amount | tax_status | tax_paiddate        | stno | predir | stname       | suffix | postdir | city         | state | zip   | 
| ======== | ======= | =================== | =================== | =================== | ===================================================================================================================== | ========================== | ========= | ========= | =========== | ========= | ========================= | ========== | ========== | =================== | ==== | ====== | ============ | ====== | ======= | ============ | ===== | ===== | 
| 375874   | Finaled | 2005-03-08T11:03:00 | 2005-03-08T11:03:00 | 2005-03-08T11:03:00 | PI-Bo50163 & 164 &PI-bo50166, 167, PI-B050169-172, PI B050173-177, PI Bo505180-185                                    | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | SCHOOLS IMPACT TAX        | 114000     | PAID       | 2005-03-08T11:03:19 | 600  |        | CEDAR SPRING | ST     |         | GAITHERSBURG | MD    | 20877 | 
| 379525   | Finaled | 2005-04-11T10:04:00 | 2005-04-11T11:04:00 | 2005-06-22T09:06:00 | NINE (9) TOWNHOMES 559,563,567,571 PELICAN AVENUE 616,620,624,628,632 CEDAR SPRING STREET                             | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | IMPACT TAX >MAR04-GENERAL | 40500      | PAID       | 2005-04-11T10:04:59 | 559  |        | PELICAN      | AVE    |         | GAITHERSBURG | MD    | 20877 | 
| 379698   | Finaled | 2005-04-12T10:04:00 | 2005-04-12T11:04:00 | 2005-04-12T11:04:00 | Pelican avenue (527 thru 555) lots 30 thru 37f Hidden Forrest Street (805 thru 829) lots 12 thru 18 D                 | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | IMPACT TAX >MAR04-GENERAL | 67500      | PAID       | 2005-04-12T11:04:38 | 527  |        | PELICAN      | AVE    |         | GAITHERSBURG | MD    | 20877 | 
| 387354   | Issued  | 2005-06-15T12:06:00 | 2005-06-15T12:06:00 |                     |                                                                                                                       | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | IMPACT TAX >MAR04-GENERAL | 4500       | PAID       | 2005-06-15T12:06:17 | 575  |        | PELICAN      | AVE    |         | GAITHERSBURG | MD    | 20877 | 
| 459671   | Issued  | 2007-07-11T04:07:57 | 2007-07-11T04:07:50 |                     | PI-B070482                                                                                                            | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | IMPACT TAX >JUL07-GENERAL | 5125       | PAID       | 2007-07-11T04:07:07 | 622  |        | HURDLE MILL  | PL     |         | GAITHERSBURG | MD    | 20878 | 
| 387356   | Finaled | 2005-06-15T12:06:00 | 2005-06-15T12:06:00 | 2005-06-16T02:06:00 |                                                                                                                       | GAITHERSBURG RES. BUILDING | CONSTRUCT |           | 0           | N         | IMPACT TAX >MAR04-GENERAL | 4500       | PAID       | 2005-06-15T12:06:01 | 579  |        | PELICAN      | AVE    |         | GAITHERSBURG | MD    | 20877 | 
| 430987   | Issued  | 2006-08-22T12:08:00 | 2006-08-22T12:08:00 |                     | The use of building as a dwelling unit that are townhouses, duplexes and other attached single-family dwelling units. | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | SCHOOLS IMPACT TAX        | 6348       | PAID       | 2006-08-22T12:08:29 | 638  |        | EDEN         | PL     |         | GAITHERSBURG | MD    | 20877 | 
| 387357   | Issued  | 2005-06-15T12:06:00 | 2005-06-15T01:06:00 |                     |                                                                                                                       | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | IMPACT TAX >MAR04-GENERAL | 4500       | PAID       | 2005-06-15T12:06:40 | 583  |        | PELICAN      | AVE    |         | GAITHERSBURG | MD    | 20877 | 
| 430977   | Issued  | 2006-08-22T11:08:00 | 2006-08-22T11:08:00 |                     | The use of building as a dwelling unit that are townhouses, duplexes and other attached single-family dwelling units. | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | SCHOOLS IMPACT TAX        | 6348       | PAID       | 2006-08-22T11:08:58 | 529  |        | CEDAR SPRING | ST     |         | GAITHERSBURG | MD    | 20877 | 
| 387358   | Issued  | 2005-06-15T01:06:00 | 2005-06-15T01:06:00 |                     |                                                                                                                       | GAITHERSBURG RES. BUILDING | CONSTRUCT | TOWNHOUSE | 0           | N         | IMPACT TAX >MAR04-GENERAL | 4500       | PAID       | 2005-06-15T01:06:17 | 587  |        | PELICAN      | AVE    |         | GAITHERSBURG | MD    | 20877 | 
```