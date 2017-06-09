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
series e:krqq-6qhc d:2017-05-17T16:26:54.000Z t:ntee_cd=A80 t:zip_code=06024-0383 t:status=1 t:name="FRIENDS OF BECKLEY FURNACE INC" t:street="PO BOX 383" t:state=CT t:ico="% ROBERT ANDERSON" t:city="EAST CANAAN" m:subsection=3 m:ein=10703391 m:ruling=200306 m:acct_pd=12 m:filing_req_cd=2 m:tax_period=201512 m:organization=1 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=2000 m:foundation=15 m:affiliation=3 m:income_cd=0 m:group=0 m:revenue_amt=0 m:deductibility=1 m:income_amt=0 m:activity=0 m:asset_amt=0

series e:krqq-6qhc d:2017-05-17T16:26:55.000Z t:ntee_cd=X21 t:zip_code=06062-0551 t:status=1 t:name="DIVINE TRUTH APOSTOLIC CHURCH" t:street="PO BOX 551" t:state=CT t:sort_name="PASTOR GEORGE L KNIGHT" t:city=PLAINVILLE m:subsection=3 m:ein=10957621 m:ruling=201109 m:acct_pd=12 m:filing_req_cd=6 m:organization=1 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=7000 m:foundation=10 m:affiliation=3 m:income_cd=0 m:group=0 m:deductibility=1 m:activity=0

series e:krqq-6qhc d:2017-05-17T16:26:57.000Z t:ntee_cd=G84 t:zip_code=06790-8026 t:status=1 t:name="LITCHFIELD COUNTY AUTISM SPECTRUM ASSOCIATION INC" t:street="PO BOX 2026" t:state=CT t:ico="% JOHN E HUDSON" t:city=TORRINGTON m:subsection=3 m:ein=20544955 m:ruling=200211 m:acct_pd=12 m:filing_req_cd=2 m:tax_period=201512 m:organization=1 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=2000 m:foundation=15 m:affiliation=3 m:income_cd=0 m:group=0 m:revenue_amt=0 m:deductibility=1 m:income_amt=0 m:activity=0 m:asset_amt=0
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

property e:krqq-6qhc t:meta.view d:2017-06-09T13:54:32.715Z v:id=krqq-6qhc v:category=Business v:attributionLink=https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf v:averageRating=0 v:name="Tax Exempt Organizations (Extracted from the Internal Revenue Service)" v:attribution="Internal Revenue Service"

property e:krqq-6qhc t:meta.view.license d:2017-06-09T13:54:32.715Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:krqq-6qhc t:meta.view.owner d:2017-06-09T13:54:32.715Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1496849452 v:displayName="Tyler Kleykamp"

property e:krqq-6qhc t:meta.view.tableauthor d:2017-06-09T13:54:32.715Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1496849452 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | ein       | name                                                           | ico                  | street                             | city        | state | zip_code   | group | subsection | affiliation | classification | ruling | deductibility | foundation | activity  | organization | status | tax_period | asset_cd | income_cd | filing_req_cd | pf_filing_req_cd | acct_pd | asset_amt | income_amt | revenue_amt | ntee_cd | sort_name              | 
| =========== | ========= | ============================================================== | ==================== | ================================== | =========== | ===== | ========== | ===== | ========== | =========== | ============== | ====== | ============= | ========== | ========= | ============ | ====== | ========== | ======== | ========= | ============= | ================ | ======= | ========= | ========== | =========== | ======= | ====================== | 
| 1495038414  | 10703391  | FRIENDS OF BECKLEY FURNACE INC                                 | % ROBERT ANDERSON    | PO BOX 383                         | EAST CANAAN | CT    | 06024-0383 | 0     | 3          | 3           | 2000           | 200306 | 1             | 15         | 0         | 1            | 1      | 201512     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | A80     |                        | 
| 1495038415  | 10957621  | DIVINE TRUTH APOSTOLIC CHURCH                                  |                      | PO BOX 551                         | PLAINVILLE  | CT    | 06062-0551 | 0     | 3          | 3           | 7000           | 201109 | 1             | 10         | 0         | 1            | 1      |            | 0        | 0         | 6             | 0                | 12      |           |            |             | X21     | PASTOR GEORGE L KNIGHT | 
| 1495038417  | 20544955  | LITCHFIELD COUNTY AUTISM SPECTRUM ASSOCIATION INC              | % JOHN E HUDSON      | PO BOX 2026                        | TORRINGTON  | CT    | 06790-8026 | 0     | 3          | 3           | 2000           | 200211 | 1             | 15         | 0         | 1            | 1      | 201512     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | G84     |                        | 
| 1495038417  | 20609285  | LITTLE LEAGUE BASEBALL INC                                     | % WILFRED PETIT      | PO BOX 301                         | BERLIN      | CT    | 06037-0301 | 3158  | 3          | 9           | 1000           | 196701 | 1             | 15         | 321059000 | 1            | 1      | 201509     | 4        | 4         | 1             | 0                | 9       | 250458    | 115897     | 97228       |         | 2070501 BERLIN LL      | 
| 1495038418  | 237144312 | ACADIA LODGE NO 85 ANCIENT FREE & ACCEPTED MASONS OF GREENWICH |                      | PO BOX 4663                        | GREENWICH   | CT    |            | 0     | 10         | 3           | 1000           | 201612 | 1             | 0          | 59036602  | 5            | 1      | 201511     | 5        | 3         | 2             | 0                | 11      | 541593    | 40000      | 40000       | Y40     |                        | 
| 1495038419  | 237532367 | INTERNATIONAL MASONS                                           | % CORA MERCER        | 24 MAPLEWOOD LN                    | NORTHFORD   | CT    | 06472-1326 | 1385  | 8          | 9           | 1000           | 197209 | 1             | 0          | 279265000 | 5            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           |         | ELECTA GRAND CHAPTER   | 
| 1495038419  | 270505166 | BAILEY FARMINGTON VILLAGE GREEN AND LIBRARY TRUST              | % WILLIAM WOLLENBERG | 314 MAIN ST                        | FARMINGTON  | CT    | 06032-2961 | 0     | 3          | 3           | 1000           | 201002 | 1             | 4          | 0         | 2            | 1      | 201606     | 4        | 6         | 0             | 1                | 6       | 402514    | 1189680    |             | T20     |                        | 
| 1495038419  | 271497607 | COEEA FUND INC                                                 | % ALBERTO MIMO       | 55 TALMADGE HILL RD                | PROSPECT    | CT    | 06281-2822 | 0     | 3          | 3           | 2000           | 201103 | 1             | 15         | 0         | 1            | 1      | 201412     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | C30     |                        | 
| 1481824668  | 43201493  | EPSILON BUILDING ASSOCIATION OF THETA CHI FRATERNITY           | % JOE GUGLIEMINO     | C/O WILL SKENE-157 STONE BRIDGE RD | WOODSTOCK   | CT    | 06281-0000 | 241   | 7          | 9           | 1000           | 0      | 0             | 0          | 0         | 0            | 1      | 201606     | 5        | 4         | 1             | 0                | 6       | 886878    | 139969     | 139969      |         |                        | 
| 1495038420  | 274254934 | EAST ROCK SANGHA INC                                           | % ROY MONEY          | 41 ELD ST                          | NEW HAVEN   | CT    | 06511-3815 | 0     | 3          | 3           | 1000           | 201209 | 1             | 16         | 0         | 1            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | X50     |                        | 
```