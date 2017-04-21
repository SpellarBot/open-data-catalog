# DHHL Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dhhl-licenses-78d7e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vcvt-yznb) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vcvt-yznb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vcvt-yznb/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vcvt-yznb |
| Name | DHHL Licenses |
| Attribution | DHHL |
| Category | Economic Development |
| Tags | dhhl, licenses, hawaiian home lands |
| Created | 2012-07-11T21:23:11Z |
| Publication Date | 2012-09-05T19:25:45Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | island         | Island         | text          | text          |
| Yes      | series tag     | acreage        | Acreage        | text          | text          |
| No       |                | no             | No.            | text          | text          |
| Yes      | series tag     | use            | Use            | text          | text          |
| Yes      | series tag     | licensee       | Licensee       | text          | text          |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | tmk_number     | TMK Number     | text          | text          |
| Yes      | series tag     | terms_years    | Terms(Years)   | text          | text          |
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
series e:vcvt-yznb d:1985-02-01T00:00:00.000Z t:tmk_number="(2) 3-3-006:053(P)" t:location=Paukukalo t:use=Easement t:licensee="Maui Electric Company, Ltd. & GTE H-TEL" t:comments=Utilities t:island=Maui t:terms_years=Perpetual m:term_rent=1

series e:vcvt-yznb d:1986-06-01T00:00:00.000Z t:tmk_number="(3) 3-8-001:009(P)" t:location=Humuula t:use=Easement t:annual_rent=$0.00 t:licensee="U.S. Department of the Interior USF & WS" t:acreage=1.649 t:comments=Roadway t:island=Hawaii t:terms_years=Perpetual m:term_rent=900

series e:vcvt-yznb d:1986-08-27T00:00:00.000Z t:tmk_number="(2) 5-2-001:004(P), 030(P),  5-2-010:001(P)" t:location=Palaau/Kalamaula t:use=Easement t:licensee="Molokai Ranch, Ltd." t:acreage=7.75 t:comments=Waterline t:island=Molokai t:terms_years=Perpetual m:term_rent=1
```

## Meta Commands

```ls
metric m:term_rent p:double l:"Term Rent" t:dataTypeName=money

entity e:vcvt-yznb l:"DHHL Licenses" t:attribution=DHHL t:url=https://data.hawaii.gov/api/views/vcvt-yznb

property e:vcvt-yznb t:meta.view v:id=vcvt-yznb v:category="Economic Development" v:averageRating=0 v:name="DHHL Licenses" v:attribution=DHHL

property e:vcvt-yznb t:meta.view.license v:name="Creative Commons Attribution | Share Alike 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-sa/3.0/legalcode v:logoUrl=images/licenses/cc30bysa.png

property e:vcvt-yznb t:meta.view.owner v:id=an38-krt2 v:screenName="Linda Inouye" v:displayName="Linda Inouye"

property e:vcvt-yznb t:meta.view.tableauthor v:id=an38-krt2 v:screenName="Linda Inouye" v:roleName=editor v:displayName="Linda Inouye"
```

## Top Records

```ls
| island  | acreage | no  | use            | licensee                                                                 | location         | tmk_number                                 | terms_years | beginning_date      | ending_date         | annual_rent | term_rent | comments                | 
| ======= | ======= | === | ============== | ======================================================================== | ================ | ========================================== | =========== | =================== | =================== | =========== | ========= | ======================= | 
| Molokai | 0.066   | 064 | Easement       | Na Hua Ai Farms                                                          | Hoolehua/Palaau  | (1) 5-2-001:005(P)                         |             | 1977-09-19T00:00:00 | 2026-06-13T00:00:00 | Gratis      |           | Waterline               | 
| Maui    |         | 185 | Easement       | Maui Electric Company, Ltd. & GTE H-TEL                                  | Paukukalo        | (2) 3-3-006:053(P)                         | Perpetual   | 1985-02-01T00:00:00 |                     |             | 1.00      | Utilities               | 
| Hawaii  | 1.649   | 206 | Easement       | U.S. Department of the Interior USF & WS                                 | Humuula          | (3) 3-8-001:009(P)                         | Perpetual   | 1986-06-01T00:00:00 |                     | $0.00       | 900.00    | Roadway                 | 
| Molokai | 7.75    | 207 | Easement       | Molokai Ranch, Ltd.                                                      | Palaau/Kalamaula | (2) 5-2-001:004(P), 030(P), 5-2-010:001(P) | Perpetual   | 1986-08-27T00:00:00 |                     |             | 1.00      | Waterline               | 
| Hawaii  | 1.061   | 208 | Easement       | Trustees of Liliuokalani Trust c/o First Hawaiian Bank                   | Humuula          | (3) 03-8-001:009 (P)                       | Perpetual   | 1986-06-01T00:00:00 |                     | $0.00       | 530.00    | 50-ft. wide road        | 
| Molokai | 1.033   | 261 | Church         | Ierusalema Pomaikai Church                                               | Kalamaula        | (2) 5-2-009:017, 026 & 027                 | 30          | 1990-04-01T00:00:00 | 2020-03-31T00:00:00 | $225.00     |           |                         | 
| Molokai | 0.546   | 269 | Church         | Molokai Congregation of Jehovah's Witnesses c/o Ronald J. Hancock, et al | Kalamaula        | (2) 5-2-009:020                            | 30          | 1990-07-01T00:00:00 | 2020-06-30T00:00:00 | $200.00     |           | Church                  | 
| Hawaii  | 2.121   | 296 | Easement       | Kenneth Kaniho, Sr.                                                      | Humuula          | (3) 3-8-001:007(P)                         |             | 1992-09-25T00:00:00 |                     |             | 1.00      |                         | 
| Hawaii  | 1.12    | 297 | Telecomm       | Hawaii Public Television Foundation                                      | Keaukaha         | (3) 2-1-013:008(P), 149(P)                 | 20          | 1992-07-01T00:00:00 | 2012-06-30T00:00:00 | $10,800.00  |           | Communications Facility | 
| Molokai | 233.68  | 336 | Public Service | State of Hawaii, DLNR                                                    | Palaau           | (2) 5-2-013:006                            | 20          | 1991-12-28T00:00:00 | 2011-12-27T00:00:00 | $979.00     |           | State park facilities   | 
```