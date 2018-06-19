# 2017 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2017-foreclosure-avoidance-mediation-beneficiary-exemption-affidavits-pursuant-to-sb-558) |
| Metadata | [Link](https://data.oregon.gov/api/views/mjgc-qsfr) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mjgc-qsfr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mjgc-qsfr/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mjgc-qsfr |
| Name | 2017 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558 |
| Attribution | Oregon Department of Justice |
| Category | Public Safety |
| Tags | foreclosure, mediation, sb 558 |
| Created | 2017-01-24T20:00:12Z |
| Publication Date | 2017-04-13T23:31:41Z |

## Description

Financial institutions that have filed an exemption for participation in foreclosure mediation in 2017, pursuant to SB 558.

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
series e:mjgc-qsfr d:2017-01-03T00:00:00.000Z t:zip=27409 t:title="Vice President" t:state=NC t:contact="Patrick Carper" t:beneficiary="Branch Banking and Trust Co." t:city=Greensboro m:foreclosures_previous_year=4

series e:mjgc-qsfr d:2017-01-03T00:00:00.000Z t:zip=97075 t:title="Senior Foreclosure Specialist" t:state=OR t:contact="Mark Bacu" t:beneficiary="First Technology Federal Credit Union" t:city=Beaverton m:foreclosures_previous_year=18

series e:mjgc-qsfr d:2017-01-05T00:00:00.000Z t:zip=44702 t:title="Senior Foreclosure Specialist" t:state=OH t:contact="Joan D. Ickes" t:beneficiary="Dollar Bank, Federal Savings Bank" t:city=Canton m:foreclosures_previous_year=0
```

## Meta Commands

```ls
metric m:foreclosures_previous_year p:integer l:"Foreclosures previous year" t:dataTypeName=number

entity e:mjgc-qsfr l:"2017 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" t:attribution="Oregon Department of Justice" t:url=https://data.oregon.gov/api/views/mjgc-qsfr

property e:mjgc-qsfr t:meta.view v:id=mjgc-qsfr v:category="Public Safety" v:attributionLink=http://doj.state.or.us v:averageRating=0 v:name="2017 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" v:attribution="Oregon Department of Justice"

property e:mjgc-qsfr t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:mjgc-qsfr t:meta.view.owner v:id=fyre-afev v:screenName=MichaelCollins v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins

property e:mjgc-qsfr t:meta.view.tableauthor v:id=fyre-afev v:screenName=MichaelCollins v:roleName=editor v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins
```

## Top Records

```ls
| date                | beneficiary                           | foreclosures_previous_year | mailing_address                   | city          | state | zip   | contact              | title                         | phone | 
| =================== | ===================================== | ========================== | ================================= | ============= | ===== | ===== | ==================== | ============================= | ===== | 
| 2017-01-03T00:00:00 | Branch Banking and Trust Co.          | 4                          | 7701 Airport Center Dr. 4th floor | Greensboro    | NC    | 27409 | Patrick Carper       | Vice President                |       | 
| 2017-01-03T00:00:00 | First Technology Federal Credit Union | 18                         | PO Box 2100                       | Beaverton     | OR    | 97075 | Mark Bacu            | Senior Foreclosure Specialist |       | 
| 2017-01-05T00:00:00 | Dollar Bank, Federal Savings Bank     | 0                          | 300 W Tuscarawas St               | Canton        | OH    | 44702 | Joan D. Ickes        | Senior Foreclosure Specialist |       | 
| 2017-01-05T00:00:00 | Oregon Pacific Banking Company        | 2                          | PO Box 1475                       | Eugene        | OR    | 97440 | Brook Burkhart       | Vice President                |       | 
| 2017-01-05T00:00:00 | Mild Oregon Federal Credit Union      | 1                          | PO Box 6749                       | Bend          | OR    | 97708 | Cynthia Krickhahn    | Vice President of Lending     |       | 
| 2017-01-12T00:00:00 | Franklin American Mortgage Company    | 29                         | 6100 Tower Circle, Suite 600      | Franklin      | TN    | 37067 | Michael J. Sweklo    | Senior Vice President         |       | 
| 2017-01-10T00:00:00 | Clackamas County Bank                 | 0                          | Po Box 38                         | Sandy         | OR    | 97055 | Lisa Hanson          | Chief Credit Officer          |       | 
| 2017-01-04T00:00:00 | Blue Mountain Credit Union            | 0                          | 520 S College Avenue              | College Place | WA    | 99324 | Jim Drake            | President, CEO                |       | 
| 2017-01-04T00:00:00 | Provident Funding Associates, L.P.    | 13                         |                                   |               |       |       | Jessica L Praniewicz | Assistant Vice President      |       | 
| 2017-01-09T00:00:00 | Pacific Cascade Federal Credit Union  | 0                          | PO Box 10886                      | Eugene        | OR    | 97440 | Lori Bryan           | VP of Operations              |       | 
```