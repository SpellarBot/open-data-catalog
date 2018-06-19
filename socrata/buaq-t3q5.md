# 2013 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-foreclosure-avoidance-mediation-beneficiary-exemption-affidavits-pursuant-to-sb-558-33795) |
| Metadata | [Link](https://data.oregon.gov/api/views/buaq-t3q5) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/buaq-t3q5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/buaq-t3q5/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | buaq-t3q5 |
| Name | 2013 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558 |
| Attribution | Oregon Department of Justice |
| Category | Public Safety |
| Tags | foreclosure, mediation, sb 558 |
| Created | 2013-06-25T22:13:24Z |
| Publication Date | 2014-04-16T17:46:25Z |

## Description

Financial institutions that have filed an exemption for participation in foreclosure mediation on or after August 4, 2013, pursuant to SB 558.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | time        | date                       | Date                       | calendar_date | calendar_date |
| Yes      | series tag  | beneficiary                | Beneficiary                | text          | text          |
| Yes      | series tag  | foreclosures_previous_year | Foreclosures Previous Year | text          | text          |
| No       |             | mailing_address            | Mailing Address            | text          | text          |
| Yes      | series tag  | city                       | City                       | text          | text          |
| Yes      | series tag  | state                      | State                      | text          | text          |
| Yes      | series tag  | zip                        | Zip                        | text          | text          |
| Yes      | series tag  | contact                    | Contact                    | text          | text          |
| Yes      | series tag  | title                      | Title                      | text          | text          |
| Yes      | series tag  | phone                      | Phone                      | text          | text          |
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
series e:buaq-t3q5 d:2013-08-05T00:00:00.000Z t:zip=97293 t:phone=503-785-2468 t:title="Vice President" t:state=OR t:foreclosures_previous_year=4 t:contact="Jeff Schwarz" t:beneficiary="Advantis Credit Union" t:city=Portland m:row_number.buaq-t3q5=1

series e:buaq-t3q5 d:2013-11-05T00:00:00.000Z t:zip=90210 t:phone=310-855-0826 t:title="Vice President" t:state=CA t:foreclosures_previous_year=1 t:contact="April Smith" t:beneficiary="Airway III, LLC" t:city="Beverly Hills" m:row_number.buaq-t3q5=2

series e:buaq-t3q5 d:2013-10-21T00:00:00.000Z t:zip=97201 t:phone=503-295-2668 t:title=Individual t:state=OR t:foreclosures_previous_year=1 t:contact="Alan D. Christie" t:beneficiary="Alan D. Christie" t:city=Portland m:row_number.buaq-t3q5=3
```

## Meta Commands

```ls
metric m:row_number.buaq-t3q5 p:long l:"Row Number"

entity e:buaq-t3q5 l:"2013 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" t:attribution="Oregon Department of Justice" t:url=https://data.oregon.gov/api/views/buaq-t3q5

property e:buaq-t3q5 t:meta.view v:id=buaq-t3q5 v:category="Public Safety" v:attributionLink=http://doj.state.or.us v:averageRating=0 v:name="2013 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" v:attribution="Oregon Department of Justice"

property e:buaq-t3q5 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:buaq-t3q5 t:meta.view.owner v:id=fyre-afev v:screenName=MichaelCollins v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins

property e:buaq-t3q5 t:meta.view.tableauthor v:id=fyre-afev v:screenName=MichaelCollins v:roleName=editor v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins
```

## Top Records

```ls
| date                | beneficiary                      | foreclosures_previous_year | mailing_address                                        | city           | state | zip         | contact               | title                       | phone        | 
| =================== | ================================ | ========================== | ====================================================== | ============== | ===== | =========== | ===================== | =========================== | ============ | 
| 2013-08-05T00:00:00 | Advantis Credit Union            | 4                          | PO Box 14220                                           | Portland       | OR    | 97293       | Jeff Schwarz          | Vice President              | 503-785-2468 | 
| 2013-11-05T00:00:00 | Airway III, LLC                  | 1                          | 433 North Camden Drive #400                            | Beverly Hills  | CA    | 90210       | April Smith           | Vice President              | 310-855-0826 | 
| 2013-10-21T00:00:00 | Alan D. Christie                 | 1                          | 1515 SW 5th Avenue, Suite 600                          | Portland       | OR    | 97201       | Alan D. Christie      | Individual                  | 503-295-2668 | 
| 2013-08-08T00:00:00 | Alaska Airlines Horizon Air EFCU | 0                          | 121 SW Morrison Street, Suite 600                      | Portland       | OR    | 97204       | Donna Brehmer         | Loan Manager                | 206-824-9800 | 
| 2013-09-12T00:00:00 | Alerus Financial NA              | 0                          |                                                        |                |       |             | Pam Schulz            | Credit Servicing Specialist | 800-279-3200 | 
| 2013-10-10T00:00:00 | American Internet Mortgage, Inc. | 0                          | 4121 Camino Del Rio South                              | San Diego      | CA    | 92108       | Bella Titiyevskaya    | Vice President              | 619-814-8248 | 
| 2013-10-08T00:00:00 | Amerihome Mortgage Corp.         | 0                          | 3637 Sentara Way                                       | Virginia Beach | WI    | 23452       | Todd Taylor           | CFO                         | 757-452-5071 | 
| 2013-11-14T00:00:00 | Annette Gilbert Waits            | 0                          | 515 E. Main Street                                     | Ashland        | OR    | 97520       | Annette Gilbert Waits | Individual                  | 541-482-3111 | 
| 2013-09-09T00:00:00 | Annie Wong                       | 1                          | PO Box 1026                                            | Baker City     | OR    | 97814       | Martin Leuenberger    | Attorney                    | 541-523-6535 | 
| 2013-08-30T00:00:00 | Anson Financial, Inc.            | 1                          | Suite 2150 Congress Center 1001 Southwest Fifth Avenue | Portland       | OR    | 97204       | J. Michael Ferguson   | President                   | 503-226-0500 | 
```