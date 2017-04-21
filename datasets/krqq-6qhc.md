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

Exempt organization information is extracted monthly from the Internal Revenue Service?s Business Master File. This is a cumulative file, and the data are the most recent information the IRS has for these organizations.

If you have any questions about the tax-exempt organizations or the content of the files, please contact TE/GE Customer Account Services toll-free line at 1-877-829-5500

State is determined from the filing address and generally represent the location of an organization?s headquarters, which may or may not represent the state(s) in which an organization has operations.

Records are sorted by Employer Identification Number (EIN). 

This dataset is for Connecticut only.

The IRS exempt organization data have been accumulated since the inception of the tax-exempt statutes. A determination letter is issued to an organization upon the granting of an exemption and is considered valid throughout the life of the organization, as long as the organization complies with the provisions of its exemption.
If an organization's exemption is revoked, an announcement to inform potential donors of the revocation is published in the Internal Revenue Bulletin. In addition, the organization?s name is removed from publicly accessible venues, including this file. NOTE: Split-interest trusts are not included in this database.

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
series e:krqq-6qhc d:2017-03-22T15:20:38.000Z t:ntee_cd=U50 t:zip_code=06378-2403 t:status=1 t:name="LIFE EDU ORG INC" t:street="PO BOX 368" t:state=CT t:ico="% ALBERT KAUSCH" t:sort_name="KAUSCH ALBERT P PHD PRESIDENT" t:city=MYSTIC m:subsection=3 m:ein=10596826 m:ruling=0 m:acct_pd=12 m:filing_req_cd=2 m:tax_period=201612 m:organization=1 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=1238 m:foundation=15 m:affiliation=3 m:income_cd=0 m:group=0 m:asset_amt=0 m:activity=0 m:income_amt=0 m:deductibility=1 m:revenue_amt=0

series e:krqq-6qhc d:2017-03-22T15:20:38.000Z t:ntee_cd=P20 t:zip_code=06790-2188 t:status=1 t:name="CHRISTIAN EVANGELISTIC ASSOCIATION" t:street="455 MARSHALL LAKE RD" t:state=CT t:ico="% JOB AYANTOLA" t:city=TORRINGTON m:subsection=3 m:ein=10623416 m:ruling=0 m:acct_pd=12 m:filing_req_cd=2 m:tax_period=201612 m:organization=1 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=1000 m:foundation=16 m:affiliation=3 m:income_cd=0 m:group=0 m:asset_amt=0 m:activity=0 m:income_amt=0 m:deductibility=1 m:revenue_amt=0

series e:krqq-6qhc d:2017-03-22T15:20:38.000Z t:ntee_cd=J40 t:zip_code=06708-1814 t:status=1 t:name="WATERBURY RETIRED EDUCATORS ASSOCIATION" t:street="37 STODDARD RD" t:state=CT t:ico="% LOUIS PONZILLO" t:city=WATERBURY m:subsection=5 m:ein=10723886 m:ruling=0 m:acct_pd=12 m:filing_req_cd=2 m:tax_period=201612 m:organization=5 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=3000 m:foundation=0 m:affiliation=3 m:income_cd=0 m:group=0 m:asset_amt=0 m:activity=0 m:income_amt=0 m:deductibility=2 m:revenue_amt=0
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

property e:krqq-6qhc t:meta.view v:id=krqq-6qhc v:category=Business v:attributionLink=https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf v:averageRating=0 v:name="Tax Exempt Organizations (Extracted from the Internal Revenue Service)" v:attribution="Internal Revenue Service"

property e:krqq-6qhc t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:krqq-6qhc t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:krqq-6qhc t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | ein       | name                                                              | ico                         | street                           | city        | state | zip_code   | group | subsection | affiliation | classification | ruling | deductibility | foundation | activity  | organization | status | tax_period | asset_cd | income_cd | filing_req_cd | pf_filing_req_cd | acct_pd | asset_amt | income_amt | revenue_amt | ntee_cd | sort_name                     | 
| =========== | ========= | ================================================================= | =========================== | ================================ | =========== | ===== | ========== | ===== | ========== | =========== | ============== | ====== | ============= | ========== | ========= | ============ | ====== | ========== | ======== | ========= | ============= | ================ | ======= | ========= | ========== | =========== | ======= | ============================= | 
| 1490196038  | 10596826  | LIFE EDU ORG INC                                                  | % ALBERT KAUSCH             | PO BOX 368                       | MYSTIC      | CT    | 06378-2403 | 0     | 3          | 3           | 1238           | 0      | 1             | 15         | 0         | 1            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | U50     | KAUSCH ALBERT P PHD PRESIDENT | 
| 1490196038  | 10623416  | CHRISTIAN EVANGELISTIC ASSOCIATION                                | % JOB AYANTOLA              | 455 MARSHALL LAKE RD             | TORRINGTON  | CT    | 06790-2188 | 0     | 3          | 3           | 1000           | 0      | 1             | 16         | 0         | 1            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | P20     |                               | 
| 1490196038  | 10723886  | WATERBURY RETIRED EDUCATORS ASSOCIATION                           | % LOUIS PONZILLO            | 37 STODDARD RD                   | WATERBURY   | CT    | 06708-1814 | 0     | 5          | 3           | 3000           | 0      | 2             | 0          | 0         | 5            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | J40     |                               | 
| 1490196038  | 10870395  | MUSIC HAVEN INC                                                   | % TINA LEE                  | 117 WHALLEY AVE                  | NEW HAVEN   | CT    | 06511-3220 | 0     | 3          | 3           | 1000           | 0      | 1             | 15         | 0         | 1            | 1      | 201606     | 4        | 5         | 1             | 0                | 6       | 420335    | 592450     | 592450      | A68     |                               | 
| 1490196038  | 113492739 | ASSOCIATION OF COURT SECURITY OFFICERS-CONNECTICUT                | % GEORGE TRAPP              | 141 CHURCH STREET                | NEW HAVEN   | CT    | 06510-2030 | 0     | 5          | 3           | 3000           | 0      | 2             | 0          | 0         | 5            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | J40     |                               | 
| 1490196038  | 113723325 | STONEFIELD HOLLOW HOMEOWNERS ASSOCIATION INC                      | % BLITHE DOTSON-SECRETARY   | 34 STONEFIELD RD                 | WOODBURY    | CT    | 06798-2639 | 0     | 4          | 3           | 3000           | 0      | 2             | 0          | 0         | 1            | 1      | 201612     | 0        | 0         | 2             | 0                | 12      | 0         | 0          | 0           | L50     |                               | 
| 1490196038  | 113810755 | SGT JOHN L LEVITOW AUXILIARY 45 JEWISH WAR VETERANS OF THE UNITED | % ELISSA DONN               | 241 KINGS LNDG                   | WINDSOR     | CT    | 06095-3572 | 0     | 4          | 3           | 3000           | 0      | 2             | 0          | 908907000 | 5            | 1      | 201608     | 0        | 0         | 2             | 0                | 8       | 0         | 0          | 0           |         | 45 AUX HARTFORD-LAUREL POST   | 
| 1490196038  | 130598110 | BPA WORLDWIDE INC                                                 |                             | 100 BEARD SAWMILL ROAD 6TH FLOOR | SHELTON     | CT    | 06484-6150 | 0     | 6          | 3           | 2000           | 0      | 2             | 0          | 59205279  | 1            | 1      | 201606     | 7        | 8         | 1             | 0                | 6       | 8749060   | 15000627   | 10963231    |         |                               | 
| 1490196038  | 133015572 | EASTCHESTER TEACHERS TRUST FUND                                   | % INSURANCE PROGRAMMERS INC | 10 TECHNOLOGY DR                 | WALLINGFORD | CT    | 06492-1955 | 0     | 9          | 3           | 1000           | 0      | 1             | 0          | 200000000 | 1            | 1      | 201606     | 4        | 5         | 1             | 0                | 6       | 346443    | 531206     | 531206      |         |                               | 
| 1490196038  | 133083976 | TUCKAHOE TEACHERS ASSOCIATION TRUST FUND                          | % INSURANCE PROGRAMMERS INC | 10 TECHNOLOGY DR                 | WALLINGFORD | CT    | 06492-1955 | 0     | 9          | 3           | 1000           | 0      | 2             | 0          | 264265262 | 2            | 1      | 201606     | 4        | 4         | 1             | 0                | 6       | 118796    | 281858     | 281858      |         |                               | 
```