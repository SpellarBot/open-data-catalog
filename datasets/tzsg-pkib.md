# 2014 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-foreclosure-avoidance-mediation-beneficiary-exemption-affidavits-pursuant-to-sb-558-32a65) |
| Metadata | [Link](https://data.oregon.gov/api/views/tzsg-pkib) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tzsg-pkib/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tzsg-pkib/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tzsg-pkib |
| Name | 2014 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558 |
| Attribution | Oregon Department of Justice |
| Category | Public Safety |
| Tags | foreclosure, mediation, sb 558 |
| Created | 2014-01-16T19:11:17Z |
| Publication Date | 2015-01-31T00:22:07Z |

## Description

Financial institutions that have filed an exemption for participation in foreclosure mediation in 2014, pursuant to SB 558.

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
series e:tzsg-pkib d:2014-01-17T00:00:00.000Z t:zip=37902 t:phone=800-955-0021 t:title="Staff Attorney" t:state=TN t:contact="Christopher M. Caldwell" t:beneficiary="21st Mortgage Corporation" t:city=Knoxville m:foreclosures_previous_year=2

series e:tzsg-pkib d:2014-01-13T00:00:00.000Z t:zip=97526 t:title=Individual t:state=OR t:contact="Aaron Yerzy" t:beneficiary="Aaron S. Yerzy & Jacqueline S. Yerzy Trustee" t:city="Grants Pass" m:foreclosures_previous_year=0

series e:tzsg-pkib d:2014-01-15T00:00:00.000Z t:zip=98293 t:phone=503-785-2468 t:title="Loss Prevention Supervisor" t:state=OR t:contact="Jason Holmes" t:beneficiary="Advantis Credit Union" t:city=Portland m:foreclosures_previous_year=1
```

## Meta Commands

```ls
metric m:foreclosures_previous_year p:integer l:"Foreclosures previous year" t:dataTypeName=number

entity e:tzsg-pkib l:"2014 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" t:attribution="Oregon Department of Justice" t:url=https://data.oregon.gov/api/views/tzsg-pkib

property e:tzsg-pkib t:meta.view v:id=tzsg-pkib v:category="Public Safety" v:attributionLink=http://doj.state.or.us v:averageRating=0 v:name="2014 Foreclosure Avoidance Mediation Beneficiary Exemption Affidavits Pursuant To SB 558" v:attribution="Oregon Department of Justice"

property e:tzsg-pkib t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:tzsg-pkib t:meta.view.owner v:id=fyre-afev v:screenName=MichaelCollins v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins

property e:tzsg-pkib t:meta.view.tableauthor v:id=fyre-afev v:screenName=MichaelCollins v:roleName=editor v:lastNotificationSeenAt=1492126320 v:displayName=MichaelCollins
```

## Top Records

```ls
| date                | beneficiary                                                                                   | foreclosures_previous_year | mailing_address                     | city           | state | zip   | contact                        | title                       | phone        | 
| =================== | ============================================================================================= | ========================== | =================================== | ============== | ===== | ===== | ============================== | =========================== | ============ | 
| 2014-01-17T00:00:00 | 21st Mortgage Corporation                                                                     | 2                          | 620 Market Street                   | Knoxville      | TN    | 37902 | Christopher M. Caldwell        | Staff Attorney              | 800-955-0021 | 
| 2014-01-13T00:00:00 | Aaron S. Yerzy & Jacqueline S. Yerzy Trustee                                                  | 0                          | 242 NW 'E' Street                   | Grants Pass    | OR    | 97526 | Aaron Yerzy                    | Individual                  |              | 
| 2014-01-15T00:00:00 | Advantis Credit Union                                                                         | 1                          | PO Box 14220                        | Portland       | OR    | 98293 | Jason Holmes                   | Loss Prevention Supervisor  | 503-785-2468 | 
| 2014-04-14T00:00:00 | AKT America Capital, Inc                                                                      | 0                          | 2121 Rosecrans Ave 6th Floor        | El Segundo     | CA    | 90245 | Karen Lieb                     | Vice President              | 503-288-7283 | 
| 2014-01-22T00:00:00 | Albina Community Bank                                                                         | 0                          | 2002 NE Martin Luther King Jr. Blvd | Portland       | OR    | 97212 | Kirk Amick                     | Vice President              | 701-795-3258 | 
| 2014-01-09T00:00:00 | Alerus Financial N.A.                                                                         | 0                          | PO Box 6001                         | Grand Folks    | ND    | 58201 | Shari Breiland                 | Loan Operation Manager      | 541-328-3011 | 
| 2014-01-16T00:00:00 | Allen Bigelow & Nancy Muktoyuk Co-Trustees of the Bigelow Revocable Trust U/T/A Dated 1/31/13 | 0                          | 1201 NW Wall Street Ste. 200        | Bend           | OR    | 97701 | Allen Bigelow & Nancy Muktoyuk | Indivdual                   |              | 
| 2014-05-02T00:00:00 | AllQuest Home Mortgage Coroporation                                                           | 0                          | 6110 Pinemont Dr Suite 220          | Houston        | TX    | 77092 | Paul Weber                     | President                   | 757-955-8747 | 
| 2014-04-28T00:00:00 | AmericanWest Bank                                                                             | 17                         | 110 S Ferrall St                    | Spokane        | WA    | 99202 | Kim Becker                     | SVP/Loan Operations Manager | 503-228-1455 | 
| 2014-01-07T00:00:00 | Amerihome Mortgage Corp.                                                                      | 0                          | 3637 Sentara Way                    | Virginia Beach | VA    | 23452 | Richard Johnson                | Senior Vice President       | 509-495-2236 | 
```