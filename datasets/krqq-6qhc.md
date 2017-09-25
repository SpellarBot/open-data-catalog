# Tax Exempt Organizations (Extracted from the Internal Revenue Service)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-exempt-organizations-extracted-from-the-internal-revenue-service) |
| Metadata | [Link](https://data.ct.gov/api/views/krqq-6qhc) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/krqq-6qhc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/krqq-6qhc/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | krqq-6qhc |
| Name | Tax Exempt Organizations (Extracted from the Internal Revenue Service) |
| Attribution | Internal Revenue Service |
| Category | Business |
| Tags | tax, exempt, non-profit, tax exempt, charity, charities |
| Created | 2016-12-15T17:57:44Z |
| Publication Date | 2016-12-15T19:44:31Z |

## Description

Exempt organization information is extracted monthly from the Internal Revenue Service’s Business Master File. This is a cumulative file, and the data are the most recent information the IRS has for these organizations.

If you have any questions about the tax-exempt organizations or the content of the files, please contact TE/GE Customer Account Services toll-free line at 1-877-829-5500

State is determined from the filing address and generally represent the location of an organization’s headquarters, which may or may not represent the state(s) in which an organization has operations.

Records are sorted by Employer Identification Number (EIN). 

This dataset is for Connecticut only.

The IRS exempt organization data have been accumulated since the inception of the tax-exempt statutes. A determination letter is issued to an organization upon the granting of an exemption and is considered valid throughout the life of the organization, as long as the organization complies with the provisions of its exemption.
If an organization's exemption is revoked, an announcement to inform potential donors of the revocation is published in the Internal Revenue Bulletin. In addition, the organization’s name is removed from publicly accessible venues, including this file. NOTE: Split-interest trusts are not included in this database.

FIELDS AVAILABLE
All exempt organization records on this file will contain the following data fields:
Column Name Contents
EIN Employer Identification Number (EIN)
NAME Primary Name of Organization
ICO In Care of Name
STREET Street Address
CITY City
STATE State
ZIP Zip Code 
GROUP Group Exemption Number
SUBSECTION Subsection Code
AFFILIATION Affiliation Code
CLASSIFICATION Classification Code(s)
RULING Ruling Date
DEDUCTIBILITY Deductibility Code
FOUNDATION Foundation Code
ACTIVITY Activity Codes
ORGANIZATION Organization Code
STATUS Exempt Organization Status Code
TAX_PERIOD Tax Period
ASSET_CD Asset Code
INCOME_CD Income Code
FILING_REQ_CD Filing Requirement Code
PF_FILING_REQ_CD PF Filing Requirement Code
ACCT_PD Accounting Period
ASSET_AMT Asset Amount
INCOME_AMT Income Amount (includes negative sign if amount is negative)
REVENUE_AMT Form 990 Revenue Amount (includes negative sign if amount is negative)
NTEE_CD National Taxonomy of Exempt Entities (NTEE) Code
SORT_NAME Sort Name (Secondary Name Line)

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | numeric metric | ein              | EIN              | number    | number      |
| Yes      | series tag     | name             | NAME             | text      | text        |
| Yes      | series tag     | ico              | ICO              | text      | text        |
| Yes      | series tag     | street           | STREET           | text      | text        |
| Yes      | series tag     | city             | CITY             | text      | text        |
| Yes      | series tag     | state            | STATE            | text      | text        |
| Yes      | series tag     | zip_code         | ZIP CODE         | text      | text        |
| Yes      | numeric metric | group            | GROUP            | number    | number      |
| Yes      | numeric metric | subsection       | SUBSECTION       | number    | number      |
| Yes      | numeric metric | affiliation      | AFFILIATION      | number    | number      |
| Yes      | numeric metric | classification   | CLASSIFICATION   | number    | number      |
| Yes      | numeric metric | ruling           | RULING           | number    | number      |
| Yes      | numeric metric | deductibility    | DEDUCTIBILITY    | number    | number      |
| Yes      | numeric metric | foundation       | FOUNDATION       | number    | number      |
| Yes      | numeric metric | activity         | ACTIVITY         | number    | number      |
| Yes      | numeric metric | organization     | ORGANIZATION     | number    | number      |
| Yes      | series tag     | status           | STATUS           | text      | number      |
| Yes      | numeric metric | tax_period       | TAX_PERIOD       | number    | number      |
| Yes      | numeric metric | asset_cd         | ASSET_CD         | number    | number      |
| Yes      | numeric metric | income_cd        | INCOME_CD        | number    | number      |
| Yes      | numeric metric | filing_req_cd    | FILING_REQ_CD    | number    | number      |
| Yes      | numeric metric | pf_filing_req_cd | PF_FILING_REQ_CD | number    | number      |
| Yes      | numeric metric | acct_pd          | ACCT_PD          | number    | number      |
| Yes      | numeric metric | asset_amt        | ASSET_AMT        | number    | number      |
| Yes      | numeric metric | income_amt       | INCOME_AMT       | number    | number      |
| Yes      | numeric metric | revenue_amt      | REVENUE_AMT      | number    | number      |
| Yes      | series tag     | ntee_cd          | NTEE_CD          | text      | text        |
| Yes      | series tag     | sort_name        | SORT_NAME        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:krqq-6qhc d:2017-07-20T13:31:41.000Z t:ntee_cd=B82 t:city="NEW BRITAIN" t:street="55 NEANDA ST" t:name="ITALIAN HERITAGE FOUNDATION INC" t:state=CT t:zip_code=06050-0446 t:status=1 m:tax_period=201606 m:deductibility=1 m:filing_req_cd=0 m:subsection=3 m:income_cd=3 m:activity=0 m:ein=10692828 m:foundation=4 m:pf_filing_req_cd=1 m:classification=1000 m:asset_cd=3 m:ruling=200209 m:asset_amt=61462 m:affiliation=3 m:acct_pd=6 m:organization=1 m:income_amt=55131 m:group=0

series e:krqq-6qhc d:2017-07-20T13:31:41.000Z t:ntee_cd=T30 t:ico="% A POLLACK" t:city=WESTPORT t:street=5044 t:name="VOICE OF THE FAITHFUL IN THE DIOCESE OF BRODGEPORT INC" t:state=CT t:status=1 m:tax_period=201612 m:deductibility=1 m:filing_req_cd=2 m:subsection=3 m:income_cd=0 m:activity=0 m:revenue_amt=0 m:ein=10742684 m:foundation=16 m:pf_filing_req_cd=0 m:classification=1000 m:asset_cd=0 m:ruling=201703 m:asset_amt=0 m:affiliation=3 m:acct_pd=12 m:organization=1 m:income_amt=0 m:group=0

series e:krqq-6qhc d:2017-07-20T13:31:41.000Z t:ntee_cd=C34 t:ico="% MICHAEL SZYMASZEK" t:city=MERIDEN t:street="146 BROAD ST" t:name="WILD LAKE ASSOCIATION INC" t:sort_name=WLA t:state=CT t:zip_code=06450-7330 t:status=1 m:tax_period=201612 m:deductibility=1 m:filing_req_cd=2 m:subsection=3 m:income_cd=0 m:activity=0 m:revenue_amt=0 m:ein=113807405 m:foundation=15 m:pf_filing_req_cd=0 m:classification=1000 m:asset_cd=0 m:ruling=200712 m:asset_amt=0 m:affiliation=3 m:acct_pd=12 m:organization=1 m:income_amt=0 m:group=0
```

## Meta Commands

```ls
metric m:ein p:integer l:EIN t:dataTypeName=number

metric m:group p:integer l:GROUP t:dataTypeName=number

metric m:subsection p:integer l:SUBSECTION t:dataTypeName=number

metric m:affiliation p:integer l:AFFILIATION t:dataTypeName=number

metric m:classification p:integer l:CLASSIFICATION t:dataTypeName=number

metric m:ruling p:integer l:RULING t:dataTypeName=number

metric m:deductibility p:integer l:DEDUCTIBILITY t:dataTypeName=number

metric m:foundation p:integer l:FOUNDATION t:dataTypeName=number

metric m:activity p:integer l:ACTIVITY t:dataTypeName=number

metric m:organization p:integer l:ORGANIZATION t:dataTypeName=number

metric m:tax_period p:integer l:TAX_PERIOD t:dataTypeName=number

metric m:asset_cd p:integer l:ASSET_CD t:dataTypeName=number

metric m:income_cd p:integer l:INCOME_CD t:dataTypeName=number

metric m:filing_req_cd p:integer l:FILING_REQ_CD t:dataTypeName=number

metric m:pf_filing_req_cd p:integer l:PF_FILING_REQ_CD t:dataTypeName=number

metric m:acct_pd p:integer l:ACCT_PD t:dataTypeName=number

metric m:asset_amt p:long l:ASSET_AMT t:dataTypeName=number

metric m:income_amt p:long l:INCOME_AMT t:dataTypeName=number

metric m:revenue_amt p:long l:REVENUE_AMT t:dataTypeName=number

entity e:krqq-6qhc l:"Tax Exempt Organizations (Extracted from the Internal Revenue Service)" t:attribution="Internal Revenue Service" t:url=https://data.ct.gov/api/views/krqq-6qhc

property e:krqq-6qhc t:meta.view d:2017-09-25T07:25:56.786Z v:averageRating=0 v:name="Tax Exempt Organizations (Extracted from the Internal Revenue Service)" v:attribution="Internal Revenue Service" v:attributionLink=https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf v:id=krqq-6qhc v:category=Business

property e:krqq-6qhc t:meta.view.license d:2017-09-25T07:25:56.786Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:krqq-6qhc t:meta.view.owner d:2017-09-25T07:25:56.786Z v:displayName="Tyler Kleykamp" v:lastNotificationSeenAt=1505139295 v:id=cvy9-n6sb v:screenName="Tyler Kleykamp"

property e:krqq-6qhc t:meta.view.tableauthor d:2017-09-25T07:25:56.786Z v:displayName="Tyler Kleykamp" v:lastNotificationSeenAt=1505139295 v:roleName=administrator v:id=cvy9-n6sb v:screenName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | ein       | name                                                        | ico                            | street                      | city          | state | zip_code   | group | subsection | affiliation | classification | ruling | deductibility | foundation | activity  | organization | status | tax_period | asset_cd | income_cd | filing_req_cd | pf_filing_req_cd | acct_pd | asset_amt | income_amt | revenue_amt | ntee_cd | sort_name                           | 
| =========== | ========= | =========================================================== | ============================== | =========================== | ============= | ===== | ========== | ===== | ========== | =========== | ============== | ====== | ============= | ========== | ========= | ============ | ====== | ========== | ======== | ========= | ============= | ================ | ======= | ========= | ========== | =========== | ======= | =================================== | 
| 1500557501  | 10692828  | ITALIAN HERITAGE FOUNDATION INC                             |                                | 55 NEANDA ST                | NEW BRITAIN   | CT    | 06050-0446 | 0     | 3          | 3           | 1000           | 200209 | 1             | 4          | 0         | 1            | 1      | 201606     | 3        | 3         | 0             | 1                | 6       | 61462     | 55131      |             | B82     |                                     | 
| 1500557501  | 10742684  | VOICE OF THE FAITHFUL IN THE DIOCESE OF BRODGEPORT INC      | % A POLLACK                    | 5044                        | WESTPORT      | CT    |            | 0     | 3          | 3           | 1000           | 201703 | 1             | 16         | 0         | 1            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | T30     |                                     | 
| 1500557501  | 113807405 | WILD LAKE ASSOCIATION INC                                   | % MICHAEL SZYMASZEK            | 146 BROAD ST                | MERIDEN       | CT    | 06450-7330 | 0     | 3          | 3           | 1000           | 200712 | 1             | 15         | 0         | 1            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | C34     | WLA                                 | 
| 1500557501  | 113836667 | AMERICAN FEDERATION OF STATE COUNTY AND MUNICIPAL EMPLOYEES | % SUSAN MCVEIGH                | 20 MORGAN ST                | PAWCATUCK     | CT    | 06379-1811 | 1381  | 5          | 9           | 3000           | 195708 | 2             | 0          | 263264279 | 5            | 1      | 201612     | 0        | 0         | 1             | 0                | 12      | 0         | 0          | 0           | S40     | L1996CT STONINGTON CT BD OF ED EMPL | 
| 1500557501  | 113843688 | BUILDING FOUNDATIONS INC                                    | % ROBERT J SUSALKA             | 67 GREAT OAK LN             | REDDING       | CT    | 06896-1921 | 0     | 3          | 3           | 1000           | 201102 | 1             | 15         | 0         | 1            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | L20     |                                     | 
| 1500557501  | 133394935 | GLOBAL VILLAGE MEDIA INC                                    |                                | 60 FURNACE BROOK RD         | CORNWALL BRG  | CT    | 06754-1125 | 0     | 3          | 3           | 1200           | 198705 | 1             | 15         | 91000000  | 1            | 1      | 201606     | 1        | 1         | 2             | 0                | 6       | 476       | 378        | 378         |         |                                     | 
| 1500557502  | 133415691 | REAL ESTATE RESEARCH INSTITUTE                              | % INDIANA U SCHOOL OF BUSINESS | 100 PEARL STREET 13TH FLOOR | HARTFORD      | CT    | 06103-4511 | 0     | 3          | 3           | 1200           | 198808 | 1             | 15         | 124000000 | 1            | 1      | 201612     | 4        | 4         | 1             | 0                | 12      | 363932    | 194087     | 194087      | S47E    | BUSINESS                            | 
| 1500557502  | 133527578 | WHITTEMORE FOUNDATION                                       | % FB WHITTEMORE                | 53 WESTWOOD RD              | WEST HARTFORD | CT    | 06117-2253 | 0     | 3          | 3           | 1000           | 198910 | 1             | 4          | 602000000 | 1            | 1      | 201612     | 6        | 4         | 0             | 1                | 12      | 1064272   | 423822     |             |         |                                     | 
| 1500557502  | 133681992 | ABBOTT GUGGENHEIM FOUNDATION INC                            | % GUGGENHEIM                   | 27 COUNTRY CLUB RD          | RIDGEFIELD    | CT    | 06877-5305 | 0     | 3          | 3           | 1000           | 199310 | 1             | 4          | 119124000 | 1            | 1      | 201612     | 4        | 0         | 0             | 1                | 12      | 279431    | 0          |             |         |                                     | 
| 1500557502  | 133692236 | AUERBACH SCHIRO FOUNDATION                                  | % ELIZABETH A SCHIRO TTEE      | 25 BROOKSIDE BLVD           | W HARTFORD    | CT    | 06107-1108 | 0     | 3          | 3           | 1000           | 199303 | 1             | 4          | 602319000 | 2            | 1      | 201612     | 6        | 4         | 0             | 1                | 12      | 1958024   | 322555     |             |         |                                     | 
```