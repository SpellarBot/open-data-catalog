# 2012 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-foreclosure-avoidance-mediation-beneficiary-exemption-affidavits-890df) |
| Metadata | [Link](https://data.oregon.gov/api/views/k2r3-pczu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/k2r3-pczu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/k2r3-pczu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | k2r3-pczu |
| Name | 2012 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits |
| Attribution | Oregon Department of Justice |
| Category | Public Safety |
| Tags | foreclosure, mediation |
| Created | 2012-07-25T16:40:22Z |
| Publication Date | 2012-10-30T18:33:20Z |

## Description

Financial institutions which have filed an exemption for participation in foreclosure avoidance mediation (2012)

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| Yes      | time        | date            | Date            | text      | text        |
| Yes      | series tag  | beneficiary     | Beneficiary     | text      | text        |
| No       |             | mailing_address | Mailing Address | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | state           | State           | text      | text        |
| Yes      | series tag  | zip             | Zip             | text      | number      |
| Yes      | series tag  | contact         | Contact         | text      | text        |
| Yes      | series tag  | title           | Title           | text      | text        |
| Yes      | series tag  | email           | Email           | email     | email       |
| Yes      | series tag  | phone           | Phone           | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:k2r3-pczu d:2012-07-11T00:00:00.000Z t:zip=37902 t:phone="800-955-0021 ext. 1022" t:title="Legal Department Manager" t:email=chriscaldwell@21stmortgage.com t:state=TN t:contact="Chris Caldwell" t:beneficiary="21st Mortgage Corporation" t:city=Knoxville m:row_number.k2r3-pczu=1

series e:k2r3-pczu d:2012-07-12T00:00:00.000Z t:zip=97293 t:phone=503-785-2468 t:title=President/CEO t:email=Rbarrick@advantiscu.org t:state=OR t:contact="Ronald A. Barrick" t:beneficiary="Advantis Credit Union" t:city=Portland m:row_number.k2r3-pczu=2

series e:k2r3-pczu d:2012-07-30T00:00:00.000Z t:zip=97212 t:phone=503.288.7283 t:title="AVP - Loan Servicing Manager" t:email=ddesemple@albinabank.com t:state=OR t:contact="Dave DeSemple" t:beneficiary="Albina Community Bank" t:city=Portland m:row_number.k2r3-pczu=3
```

## Meta Commands

```ls
metric m:row_number.k2r3-pczu p:long l:"Row Number"

entity e:k2r3-pczu l:"2012 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits" t:attribution="Oregon Department of Justice" t:url=https://data.oregon.gov/api/views/k2r3-pczu

property e:k2r3-pczu t:meta.view v:id=k2r3-pczu v:category="Public Safety" v:attributionLink=http://doj.state.or.us v:averageRating=0 v:name="2012 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits" v:attribution="Oregon Department of Justice"

property e:k2r3-pczu t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:k2r3-pczu t:meta.view.owner v:id=94n4-ymzw v:screenName=jj v:displayName=jj

property e:k2r3-pczu t:meta.view.tableauthor v:id=94n4-ymzw v:screenName=jj v:displayName=jj
```

## Top Records

```ls
| date    | beneficiary                     | mailing_address                   | city        | state | zip   | contact           | title                                           | email                          | phone                  | 
| ======= | =============================== | ================================= | =========== | ===== | ===== | ================= | =============================================== | ============================== | ====================== | 
| 7/11/12 | 21st Mortgage Corporation       | 620 Market Street                 | Knoxville   | TN    | 37902 | Chris Caldwell    | Legal Department Manager                        | chriscaldwell@21stmortgage.com | 800-955-0021 ext. 1022 | 
| 7/12/12 | Advantis Credit Union           | P.O. Box 14220                    | Portland    | OR    | 97293 | Ronald A. Barrick | President/CEO                                   | Rbarrick@advantiscu.org        | 503-785-2468           | 
| 7/30/12 | Albina Community Bank           | 2002 NE Martin Luther King Blvd   | Portland    | OR    | 97212 | Dave DeSemple     | AVP - Loan Servicing Manager                    | ddesemple@albinabank.com       | 503.288.7283           | 
| 8/28/12 | AMVESCO, Inc.                   | 800 Willamette Street, Suite 800  | Eugene      | OR    | 97401 | JoEllen Sanderson | President                                       | bdavis@agsprp.com              | 541-484-0188           | 
| 7/30/12 | Bank of Eastern Oregon          | PO Box 39                         | Heppner     | OR    | 97836 | Edward C. Rollins | Senior Vice President                           |                                | 541-676-9125           | 
| 8/8/12  | Bank of Oswego                  | 5300 Meadows Road, Suite 200      | Lake Oswego | OR    | 97035 | Kelly Francis     | Senior Vice President/ Chief Credit Officer     | wrc@buckley-law.com            | 503-620-8900           | 
| 8/7/12  | Bank of the Cascades            |                                   |             |       |       | Daniel Lee        | Executive Vice President & Chief Credit Officer | KeithB@botc.com                | 541-617-3570           | 
| 7/11/12 | Bank United, NA                 | 7815 NW 148th Street              | Miami Lakes | FL    | 33016 | Chris Zimmerman   | Vice President-Foreclosure/Bankruptcy           | CZimmerman@BankUnited.Com      | 305-818-8651           | 
| 7/25/12 | Banner Bank                     | 121 SW Morrison Street, Suite 450 | Portland    | OR    | 97204 | Ken Larson        | SVP Mortgage Banking director                   | edubay@tsbnwlaw.com            | 503-894-9900           | 
| 7/18/12 | Beltway Capital Management, LLC | 4380 SW Macadam Avenue            | Portland    | OR    | 97239 | John A. Pinzelik  | Oregon attorney                                 | JohnP@owens-law.com            | 503-224-3100           | 
```