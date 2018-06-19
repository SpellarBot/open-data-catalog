# DHHL Right Of Entry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dhhl-right-of-entry-9d71c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jpyg-5jmy) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jpyg-5jmy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jpyg-5jmy/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jpyg-5jmy |
| Name | DHHL Right Of Entry |
| Attribution | DHHL |
| Category | Economic Development |
| Tags | dhhl, right of entry, hawaiian home lands |
| Created | 2012-07-11T21:54:30Z |
| Publication Date | 2012-09-05T19:20:44Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | island         | Island         | text          | text          |
| Yes      | series tag     | acreage        | Acreage        | text          | text          |
| No       |                | no             | No             | text          | text          |
| Yes      | series tag     | use            | Use            | text          | text          |
| Yes      | series tag     | licensee       | Licensee       | text          | text          |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | tmk_number     | TMK Number     | text          | text          |
| Yes      | series tag     | terms_years    | Terms (Years)  | text          | text          |
| Yes      | time           | beginning_date | Beginning Date | calendar_date | calendar_date |
| No       |                | ending_date    | Ending Date    | calendar_date | calendar_date |
| Yes      | series tag     | annual_rent    | Annual Rent    | text          | text          |
| Yes      | numeric metric | term_rent      | Term Rent      | money         | money         |
| Yes      | series tag     | comments       | Comments       | text          | text          |
```

## Time Field

```ls
Value = beginning_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = no,ending_date
```

## Data Commands

```ls
series e:jpyg-5jmy d:2012-08-31T14:48:17.000Z t:tmk_number="(3) 2-2-063:025" t:location=Pana'ewa t:use=Construction t:annual_rent=Gratis t:licensee="University of Hawaii for Hawaii Community College (HCC), c/o Office of Procurement & Risk Management" t:acreage=.48 t:comments="HCC to build bedroom, bath house for its model home program from '06 - '07 (9 months)" t:island=Hawaii m:term_rent=1

series e:jpyg-5jmy d:2012-08-31T14:48:17.000Z t:tmk_number="(3) 2-5-050:150" t:location=Kaumana t:use=Research t:licensee="Hawaii Community College (pe BK)" t:island=Hawaii t:terms_years="9 months" m:term_rent=1

series e:jpyg-5jmy d:2012-08-31T14:48:29.000Z t:tmk_number="(2) 5-4-003:014 (P)" t:location=Kapa'akea t:use=Construction t:licensee="County of Maui, Department of Fire and Public Safety" t:acreage=.07 t:island=Molokai t:terms_years="18 months" m:term_rent=1
```

## Meta Commands

```ls
metric m:term_rent p:double l:"Term Rent" t:dataTypeName=money

entity e:jpyg-5jmy l:"DHHL Right Of Entry" t:attribution=DHHL t:url=https://data.hawaii.gov/api/views/jpyg-5jmy

property e:jpyg-5jmy t:meta.view v:id=jpyg-5jmy v:category="Economic Development" v:averageRating=0 v:name="DHHL Right Of Entry" v:attribution=DHHL

property e:jpyg-5jmy t:meta.view.license v:name="Creative Commons Attribution | Share Alike 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-sa/3.0/legalcode v:logoUrl=images/licenses/cc30bysa.png

property e:jpyg-5jmy t:meta.view.owner v:id=an38-krt2 v:screenName="Linda Inouye" v:displayName="Linda Inouye"

property e:jpyg-5jmy t:meta.view.tableauthor v:id=an38-krt2 v:screenName="Linda Inouye" v:roleName=editor v:displayName="Linda Inouye"
```

## Top Records

```ls
| island  | acreage | no    | use            | licensee                                                    | location  | tmk_number                               | terms_years | beginning_date      | ending_date         | annual_rent | term_rent | comments                                               | 
| ======= | ======= | ===== | ============== | =========================================================== | ========= | ======================================== | =========== | =================== | =================== | =========== | ========= | ====================================================== | 
| Hawaii  |         | 371   | Construction   | Department of Transportation, State of Hawaii               | Hilo      | (3) 3-8-001:003-011                      |             | 2005-11-15T00:00:00 | 2009-04-30T00:00:00 | Gratis      |           | Preliminary and construction work on Saddle Road.      | 
| Molokai | 1.354   | 032   | Cemetery       | County of Maui                                              | Kapa'akea | (2) 5-4-003:012 (P)                      |             |                     |                     | $200.00     |           | Additional land for Kapaakea Cemetery.                 | 
| Oahu    | 1.40    | 378   | Public Service | United States of America, Naval Facilities Command, Pacific | Halawa    | (1) 9-9-011:004 (P)                      |             | 2006-06-01T00:00:00 | 2007-05-31T00:00:00 | Gratis      |           | Recovery of human remains.                             | 
| Oahu    | 1.4     | 376   | Public Service | TEC, Inc.                                                   | Halawa    | (1) 4-6-015:014 (P), (1) 9-9-011:004 (P) |             | 2006-06-01T00:00:00 | 2007-12-31T00:00:00 | Gratis      |           | Restoration work.                                      | 
| Hawaii  | 0.56    | 379   | Construction   | RHB Contracting, Inc.                                       | Keaukaha  | (3) 2-1-024:014                          |             | 2006-05-15T00:00:00 | 2007-02-15T00:00:00 | Gratis      |           | Construction on dwelling on Lot 413-A.                 | 
| Hawaii  | 136.00  | 380   | Survey         | Hui Kakoo Aina Hoopulapula                                  | Pi'ihonua | (3) 2-6-018:002 (P)                      | 1           | 2006-07-01T00:00:00 | 2007-06-30T00:00:00 | Gratis      |           | To conduct feasibility study for recreational use.     | 
| Hawaii  | 20.00   | 381   | Survey         | Hawaii Energy Corporation                                   | Kawaihae  | (3) 6-1-001:002 (P)                      |             | 2006-07-14T00:00:00 | 2008-07-14T00:00:00 | Gratis      |           | Feasibility study for hydro-electric plant.            | 
| Hawaii  |         | 381-A | Survey         | RHB Contracting, Inc.                                       | Keaukaha  | (3) 2-1-020:009                          |             | 2006-07-20T00:00:00 | 2007-04-20T00:00:00 | Gratis      |           | Hawaii scattered lots program.                         | 
| Hawaii  | 232.00  | 382   | Survey         | KIP Environment, Inc.                                       | Lalamilo  | (3) 6-6-001:077                          |             | 2006-07-26T00:00:00 | 2007-07-25T00:00:00 | Gratis      |           | Studies mapping and detection of unexploded ordinance. | 
| Hawaii  | 2.32    | 383   | Survey         | Strategic Solutions, Inc.                                   | Lalamilo  | (3) 6-6-001:077                          |             | 2006-07-26T00:00:00 | 2007-07-25T00:00:00 | Gratis      |           | Studies mapping and detection of unexploded ordinance. | 
```