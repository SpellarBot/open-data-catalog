# 2016 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-foreclosure-avoidance-mediation-beneficiary-exemption-affidavits-pursuant-to-sb-558) |
| Metadata | [Link](https://data.oregon.gov/api/views/ach8-dmse) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ach8-dmse/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ach8-dmse/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ach8-dmse |
| Name | 2016 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558 |
| Attribution | Oregon Department of Justice |
| Category | Public Safety |
| Tags | foreclosure, mediation, sb 558 |
| Created | 2016-01-12T23:59:05Z |
| Publication Date | 2017-01-24T19:13:21Z |

## Description

Financial institutions that have filed an exemption for participation in foreclosure mediation in 2016, pursuant to SB 558.

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
series e:ach8-dmse d:2016-01-07T00:00:00.000Z t:title=Manager t:contact="Manuel Mata" t:beneficiary="PennyMac Loan Services, LLC" m:foreclosures_previous_year=100

series e:ach8-dmse d:2016-01-06T00:00:00.000Z t:zip=85255 t:title=Manager t:state=AZ t:contact="Jeffrey S. Bleaman" t:beneficiary="MBOM Investments, LLC" t:city=Scottsdale m:foreclosures_previous_year=0

series e:ach8-dmse d:2016-01-06T00:00:00.000Z t:zip=77042 t:title="Senior Vice President" t:state=TX t:contact="Gina Gray" t:beneficiary="Selene Finance LP" t:city=Houston m:foreclosures_previous_year=72
```

## Meta Commands

```ls
metric m:foreclosures_previous_year p:integer l:"Foreclosures previous year" t:dataTypeName=number

entity e:ach8-dmse l:"2016 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" t:attribution="Oregon Department of Justice" t:url=https://data.oregon.gov/api/views/ach8-dmse

property e:ach8-dmse t:meta.view v:id=ach8-dmse v:category="Public Safety" v:attributionLink=http://doj.state.or.us v:averageRating=0 v:name="2016 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" v:attribution="Oregon Department of Justice"

property e:ach8-dmse t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ach8-dmse t:meta.view.owner v:id=fyre-afev v:screenName=MichaelCollins v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins

property e:ach8-dmse t:meta.view.tableauthor v:id=fyre-afev v:screenName=MichaelCollins v:roleName=editor v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins
```

## Top Records

```ls
| date                | beneficiary                           | foreclosures_previous_year | mailing_address                | city       | state | zip   | contact            | title                     | phone | 
| =================== | ===================================== | ========================== | ============================== | ========== | ===== | ===== | ================== | ========================= | ===== | 
| 2016-01-07T00:00:00 | PennyMac Loan Services, LLC           | 100                        |                                |            |       |       | Manuel Mata        | Manager                   |       | 
| 2016-01-06T00:00:00 | MBOM Investments, LLC                 | 0                          | 9934 E. Buteo Dr.              | Scottsdale | AZ    | 85255 | Jeffrey S. Bleaman | Manager                   |       | 
| 2016-01-06T00:00:00 | Selene Finance LP                     | 72                         | 9990 Richmond Ave. Suite 400 S | Houston    | TX    | 77042 | Gina Gray          | Senior Vice President     |       | 
| 2016-01-08T00:00:00 | Columbia Credit Union                 | 0                          | PO Box 324                     | Vancouver  | WA    | 98666 | Michael Van Winkle | A.V.P. Lending Solutions  |       | 
| 2016-01-04T00:00:00 | Branch Banking and Trust Company      | 5                          |                                |            |       |       | Patrick Carper     | Vice President            |       | 
| 2016-01-05T00:00:00 | Vanderbilt Mortgage and Finance, Inc. | 8                          | Po Box 9800                    | Maryville  | TN    | 97802 | Antonetta Miller   | Default Servicing Manager |       | 
| 2015-01-05T00:00:00 | Willamette Valley Bank                | 1                          | PO Box 2747                    | Salem      | OR    | 97301 | Craig Hummel       | EVP, Chief Credit Officer |       | 
| 2016-01-05T00:00:00 | OR Resoulutios LLC                    | 0                          | PO Box 2747                    | Salem      | OR    | 97301 | Craig Hummel       | EVP, Chief Credit Officer |       | 
| 2016-01-05T00:00:00 | First Tech Federal Credit Union       | 8                          | PO Box 2100                    | Beaverton  | OR    | 97075 | Mark Bacu          | Foreclosure Specialist II |       | 
| 2016-01-05T00:00:00 | Marion and Polk Schools Credit Union  | 5                          |                                |            |       |       | Alan Hanson        | General Counsel           |       | 
```