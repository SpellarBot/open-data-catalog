# 2015 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-foreclosure-avoidance-mediation-beneficiary-exemption-affidavits-pursuant-to-sb-558-28b7b) |
| Metadata | [Link](https://data.oregon.gov/api/views/rjb8-qkpa) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rjb8-qkpa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rjb8-qkpa/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rjb8-qkpa |
| Name | 2015 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558 |
| Attribution | Oregon Department of Justice |
| Category | Public Safety |
| Tags | foreclosure, mediation, sb 558 |
| Created | 2015-01-13T23:50:32Z |
| Publication Date | 2016-01-30T00:19:05Z |

## Description

Financial institutions that have filed an exemption for participation in foreclosure mediation in 2015, pursuant to SB 558.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | time           | date                       | Date                       | calendar_date | calendar_date |
| Yes      | series tag     | beneficiary                | Beneficiary                | text          | text          |
| Yes      | numeric metric | foreclosures_previous_year | Foreclosures previous year | number        | number        |
| No       |                | mailing_address            | Mailing Address            | text          | text          |
| Yes      | series tag     | city                       | City                       | text          | text          |
| Yes      | series tag     | state                      | State                      | text          | text          |
| Yes      | series tag     | zip                        | Zip                        | text          | text          |
| Yes      | series tag     | contact                    | Contact                    | text          | text          |
| Yes      | series tag     | title                      | Title                      | text          | text          |
| Yes      | series tag     | phone                      | Phone                      | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:rjb8-qkpa d:2015-01-14T00:00:00.000Z t:zip=53209 t:title="Assistant Vice President" t:state=WI t:contact="David M. Roberts" t:beneficiary="Guaranty Bank" t:city=Milwaukie m:foreclosures_previous_year=6

series e:rjb8-qkpa d:2014-12-31T00:00:00.000Z t:zip=97267 t:title="Chief Executive Officer" t:state=OR t:contact="Mark Davis" t:beneficiary="Oregon Pioneer Federal Credit Union" t:city=Milwaukie m:foreclosures_previous_year=0

series e:rjb8-qkpa d:2015-01-05T00:00:00.000Z t:zip=98660 t:phone=360-753-2424 t:title=President/CEO t:state=WA t:contact="Ron Wysaske" t:beneficiary="Riverview Community Bank" t:city=Vancouver m:foreclosures_previous_year=1
```

## Meta Commands

```ls
metric m:foreclosures_previous_year p:integer l:"Foreclosures previous year" t:dataTypeName=number

entity e:rjb8-qkpa l:"2015 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" t:attribution="Oregon Department of Justice" t:url=https://data.oregon.gov/api/views/rjb8-qkpa

property e:rjb8-qkpa t:meta.view v:id=rjb8-qkpa v:category="Public Safety" v:attributionLink=http://doj.state.or.us v:averageRating=0 v:name="2015 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" v:attribution="Oregon Department of Justice"

property e:rjb8-qkpa t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rjb8-qkpa t:meta.view.owner v:id=fyre-afev v:screenName=MichaelCollins v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins

property e:rjb8-qkpa t:meta.view.tableauthor v:id=fyre-afev v:screenName=MichaelCollins v:roleName=editor v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins
```

## Top Records

```ls
| date                | beneficiary                         | foreclosures_previous_year | mailing_address              | city             | state | zip   | contact                                                           | title                                          | phone        | 
| =================== | =================================== | ========================== | ============================ | ================ | ===== | ===== | ================================================================= | ============================================== | ============ | 
| 2015-01-14T00:00:00 | Guaranty Bank                       | 6                          | 4000 W Brown Deer Rd         | Milwaukie        | WI    | 53209 | David M. Roberts                                                  | Assistant Vice President                       |              | 
| 2014-12-31T00:00:00 | Oregon Pioneer Federal Credit Union | 0                          | 17884 SE McLoughlin Blvd     | Milwaukie        | OR    | 97267 | Mark Davis                                                        | Chief Executive Officer                        |              | 
| 2015-01-05T00:00:00 | Riverview Community Bank            | 1                          | 900 Washington St, Suite 900 | Vancouver        | WA    | 98660 | Ron Wysaske                                                       | President/CEO                                  | 360-753-2424 | 
| 2015-01-02T00:00:00 | Red Canoe Credit Union              | 2                          | 1418 15th Ave                | Longview         | WA    | 98632 | Marcos Ramirez                                                    | Collections Manager                            | 360-578-5330 | 
| 2015-01-02T00:00:00 | Zions First National Bank           | 0                          | 2460 South 3270 West         | West Valley City | UT    | 84119 | Wendy Smith                                                       | Vice President                                 | 801-884-4307 | 
| 2015-01-02T00:00:00 | 21 Mortgage Corporation             | 4                          | 620 Market Street            | Knoxville        | TN    | 37902 | Christopher M. Caldwell                                           | Staff Attorney- Head of Foreclosure/Bankruptcy |              | 
| 2015-01-07T00:00:00 | Beal Bank                           | 0                          | 7195 Dallas Parkway          | Plano            | TX    | 75024 | Grant Hamilton, VP, Compliance and Operations, MGC Mortgage, Inc. | Authorized Loan Server                         | 469-229-8715 | 
| 2015-01-07T00:00:00 | MGC Mortgage, Inc.                  | 0                          | 7195 Dallas Parkway          | Plano            | TX    | 75024 | Grant Hamilton, VP, Compliance and Operations, MGC Mortgage, Inc. | Individual                                     | 469-229-8715 | 
| 2015-01-07T00:00:00 | LNV Corporation                     | 6                          | 7195 Dallas Parkway          | Plano            | TX    | 75024 | Grant Hamilton, VP, Compliance and Operations, MGC Mortgage, Inc. | Authorized Loan Server                         | 469-229-8715 | 
| 2015-01-07T00:00:00 | LPP Mortgage LTD.                   | 12                         | 7195 Dallas Parkway          | Plano            | TX    | 75024 | Grant Hamilton, VP, Compliance and Operations, MGC Mortgage, Inc. | Authorized Loan Server                         | 469-229-8715 | 
```