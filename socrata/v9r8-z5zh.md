# 2013 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-foreclosure-avoidance-mediation-beneficiary-exemption-affidavits-82d97) |
| Metadata | [Link](https://data.oregon.gov/api/views/v9r8-z5zh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/v9r8-z5zh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/v9r8-z5zh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | v9r8-z5zh |
| Name | 2013 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits |
| Attribution | Oregon Department of Justice |
| Category | Public Safety |
| Tags | foreclosure, mediation |
| Created | 2013-01-18T22:22:02Z |
| Publication Date | 2014-02-19T20:13:55Z |

## Description

Financial institutions that have filed an exemption for participation in foreclosure avoidance mediation (2013)

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | time        | date            | Date            | calendar_date | calendar_date |
| Yes      | series tag  | beneficiary     | Beneficiary     | text          | text          |
| No       |             | mailing_address | Mailing Address | text          | text          |
| Yes      | series tag  | city            | City            | text          | text          |
| Yes      | series tag  | state           | State           | text          | text          |
| Yes      | series tag  | zip             | Zip             | text          | text          |
| Yes      | series tag  | contact         | Contact         | text          | text          |
| Yes      | series tag  | title           | Title           | text          | text          |
| Yes      | series tag  | phone           | Phone           | text          | text          |
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
series e:v9r8-z5zh d:2013-01-14T00:00:00.000Z t:zip=37902 t:phone=800-955-0021 t:title="Legal Department Manager" t:state=TN t:contact="Christopher M. Caldwell" t:beneficiary="21st Mortgage Corporation" t:city=Knoxville m:row_number.v9r8-z5zh=1

series e:v9r8-z5zh d:2013-01-04T00:00:00.000Z t:zip=97293 t:phone=503-785-2468 t:title=President t:state=OR t:contact="Robert Corwin" t:beneficiary="Advantis Credit Union" t:city=Portland m:row_number.v9r8-z5zh=2

series e:v9r8-z5zh d:2013-01-10T00:00:00.000Z t:zip=98188 t:title="Loan Department Manager" t:state=WA t:contact="Donna Brehmer" t:beneficiary="Alaska Airlines Horizon Air" t:city=SeaTac m:row_number.v9r8-z5zh=3
```

## Meta Commands

```ls
metric m:row_number.v9r8-z5zh p:long l:"Row Number"

entity e:v9r8-z5zh l:"2013 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits" t:attribution="Oregon Department of Justice" t:url=https://data.oregon.gov/api/views/v9r8-z5zh

property e:v9r8-z5zh t:meta.view v:id=v9r8-z5zh v:category="Public Safety" v:attributionLink=http://doj.state.or.us v:averageRating=0 v:name="2013 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits" v:attribution="Oregon Department of Justice"

property e:v9r8-z5zh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:v9r8-z5zh t:meta.view.owner v:id=fyre-afev v:screenName=MichaelCollins v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins

property e:v9r8-z5zh t:meta.view.tableauthor v:id=fyre-afev v:screenName=MichaelCollins v:roleName=editor v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins
```

## Top Records

```ls
| date                | beneficiary                       | mailing_address                       | city        | state | zip   | contact                 | title                           | phone        | 
| =================== | ================================= | ===================================== | =========== | ===== | ===== | ======================= | =============================== | ============ | 
| 2013-01-14T00:00:00 | 21st Mortgage Corporation         | 620 Market Street                     | Knoxville   | TN    | 37902 | Christopher M. Caldwell | Legal Department Manager        | 800-955-0021 | 
| 2013-01-04T00:00:00 | Advantis Credit Union             | PO Box 14220                          | Portland    | OR    | 97293 | Robert Corwin           | President                       | 503-785-2468 | 
| 2013-01-10T00:00:00 | Alaska Airlines Horizon Air       | 19530 International Blvd. S Suite 108 | SeaTac      | WA    | 98188 | Donna Brehmer           | Loan Department Manager         |              | 
| 2013-01-10T00:00:00 | Albina Community Bank             | 8625 SW Cascade Ave, Suite 450        | Beaverton   | OR    | 97008 | Kent Walton             | Vice President                  | 503-288-7286 | 
| 2013-01-31T00:00:00 | Alvin Schaefer Testamentary Trust | 5300Meadows Road, Suite 200           | Lake Oswego | OR    | 97035 | Alice Sichley           | Trustee                         | 503-620-8900 | 
| 2013-02-05T00:00:00 | Alvin Schaefer Testamentary Trust | 5300 Meadows Road, Suite 200          | Lake Oswego | OR    | 97035 | Alice Sichley           | Individual                      |              | 
| 2013-01-29T00:00:00 | Amelia Williams                   | 1800 Blankenship Rd, Suite 200        | West Linn   | OR    | 97068 | Amelia Williams         | Individual                      | 503-655-7659 | 
| 2013-05-25T00:00:00 | Arnold Zidell                     | 1000 SW Broadway, Suite 1400          | Portland    | OR    | 97205 | Arnold Zidell           | Individual                      |              | 
| 2013-01-09T00:00:00 | Bank of Oswego                    | 5300 Meadows Road, Suite 200          | Lake Oswego | OR    | 97035 | Kelly Francis           | Senior VP, Chief Credit Officer | 503-620-8900 | 
| 2013-01-09T00:00:00 | Bank of the Cascades              | 150 NW Pacific Park Lane, Ste 101     | Bend        | OR    | 97701 | Ed Stonefelt            | Senior Vice President           | 541-617-3131 | 
```