# Tax Exempt Organizations (Extracted from the Internal Revenue Service)

## Dataset

* [Dataset URL](https://data.ct.gov/api/views/krqq-6qhc/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/tax-exempt-organizations-extracted-from-the-internal-revenue-service)
* [Metadata URL](https://data.ct.gov/api/views/krqq-6qhc)
* Id = krqq-6qhc
* Name = Tax Exempt Organizations (Extracted from the Internal Revenue Service)
* Attribution = Internal Revenue Service
* [Attribution Link](https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf)
* Category = Business
* Tags = [tax, exempt, non-profit, tax exempt, charity, charities]
* Created = 2016-12-15T17:57:44Z
* Publication Date = 2016-12-15T19:44:31Z
* Rows Updated = 2017-02-15T15:48:19Z

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
| Name             | Field Name       | Data Type | Render Type | Schema Type    | Included | 
| ================ | ================ | ========= | =========== | ============== | ======== | 
| updated_at       | :updated_at      | meta_data | meta_data   | time           | No       | 
| EIN              | ein              | number    | number      | numeric metric | Yes      | 
| NAME             | name             | text      | text        | series tag     | Yes      | 
| ICO              | ico              | text      | text        | series tag     | Yes      | 
| STREET           | street           | text      | text        | series tag     | Yes      | 
| CITY             | city             | text      | text        | series tag     | Yes      | 
| STATE            | state            | text      | text        | series tag     | Yes      | 
| ZIP CODE         | zip_code         | text      | text        | series tag     | Yes      | 
| GROUP            | group            | number    | number      | numeric metric | Yes      | 
| SUBSECTION       | subsection       | number    | number      | numeric metric | Yes      | 
| AFFILIATION      | affiliation      | number    | number      | numeric metric | Yes      | 
| CLASSIFICATION   | classification   | number    | number      | numeric metric | Yes      | 
| RULING           | ruling           | number    | number      | numeric metric | Yes      | 
| DEDUCTIBILITY    | deductibility    | number    | number      | numeric metric | Yes      | 
| FOUNDATION       | foundation       | number    | number      | numeric metric | Yes      | 
| ACTIVITY         | activity         | number    | number      | numeric metric | Yes      | 
| ORGANIZATION     | organization     | number    | number      | numeric metric | Yes      | 
| STATUS           | status           | number    | number      | numeric metric | Yes      | 
| TAX_PERIOD       | tax_period       | number    | number      | numeric metric | Yes      | 
| ASSET_CD         | asset_cd         | number    | number      | numeric metric | Yes      | 
| INCOME_CD        | income_cd        | number    | number      | numeric metric | Yes      | 
| FILING_REQ_CD    | filing_req_cd    | number    | number      | numeric metric | Yes      | 
| PF_FILING_REQ_CD | pf_filing_req_cd | number    | number      | numeric metric | Yes      | 
| ACCT_PD          | acct_pd          | number    | number      | numeric metric | Yes      | 
| ASSET_AMT        | asset_amt        | number    | number      | numeric metric | Yes      | 
| INCOME_AMT       | income_amt       | number    | number      | numeric metric | Yes      | 
| REVENUE_AMT      | revenue_amt      | number    | number      | numeric metric | Yes      | 
| NTEE_CD          | ntee_cd          | text      | text        | series tag     | Yes      | 
| SORT_NAME        | sort_name        | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:krqq-6qhc d:2017-02-15T15:48:06.000Z t:ntee_cd=X20 t:zip_code=06514-0416 t:name="WEST HAVEN CHURCH OF CHRIST INC" t:street="PO BOX 4416" t:state=CT t:ico="% WILLIAM BOWLING SR" t:city=HAMDEN m:status=1 m:subsection=3 m:ein=10563865 m:ruling=0 m:acct_pd=12 m:filing_req_cd=6 m:organization=1 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=7000 m:foundation=10 m:affiliation=3 m:income_cd=0 m:group=0 m:activity=0 m:deductibility=1

series e:krqq-6qhc d:2017-02-15T15:48:06.000Z t:ntee_cd=X21 t:zip_code=06134-1249 t:name="PRIMERA IGLESIA BAUTISTA INC" t:street="PO BOX 341249" t:state=CT t:ico="% JUSTO J CARRERA" t:city=HARTFORD m:status=1 m:subsection=3 m:ein=10607204 m:ruling=0 m:acct_pd=12 m:filing_req_cd=6 m:organization=1 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=7000 m:foundation=10 m:affiliation=3 m:income_cd=0 m:group=0 m:activity=0 m:deductibility=1

series e:krqq-6qhc d:2017-02-15T15:48:06.000Z t:ntee_cd=X21 t:zip_code=06615-0024 t:name="BETHEL MINISTRY" t:street="PO BOX 24" t:state=CT t:ico="% REV JUDSON G OLIVEIRA" t:city=STRATFORD m:status=1 m:subsection=3 m:ein=10657417 m:ruling=0 m:acct_pd=12 m:filing_req_cd=6 m:organization=1 m:pf_filing_req_cd=0 m:asset_cd=0 m:classification=1700 m:foundation=10 m:affiliation=3 m:income_cd=0 m:group=0 m:activity=0 m:deductibility=1
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

metric m:status p:integer l:STATUS t:dataTypeName=number

metric m:tax_period p:integer l:TAX_PERIOD t:dataTypeName=number

metric m:asset_cd p:integer l:ASSET_CD t:dataTypeName=number

metric m:income_cd p:integer l:INCOME_CD t:dataTypeName=number

metric m:filing_req_cd p:integer l:FILING_REQ_CD t:dataTypeName=number

metric m:pf_filing_req_cd p:integer l:PF_FILING_REQ_CD t:dataTypeName=number

metric m:acct_pd p:integer l:ACCT_PD t:dataTypeName=number

metric m:asset_amt p:long l:ASSET_AMT t:dataTypeName=number

metric m:income_amt l:INCOME_AMT t:dataTypeName=number

metric m:revenue_amt l:REVENUE_AMT t:dataTypeName=number

entity e:krqq-6qhc l:"Tax Exempt Organizations (Extracted from the Internal Revenue Service)" t:attribution="Internal Revenue Service" t:url=https://data.ct.gov/api/views/krqq-6qhc

property e:krqq-6qhc t:meta.view d:2017-03-07T22:59:04.099Z v:id=krqq-6qhc v:category=Business v:attributionLink=https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf v:averageRating=0 v:name="Tax Exempt Organizations (Extracted from the Internal Revenue Service)" v:attribution="Internal Revenue Service"

property e:krqq-6qhc t:meta.view.license d:2017-03-07T22:59:04.099Z v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:krqq-6qhc t:meta.view.owner d:2017-03-07T22:59:04.099Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"

property e:krqq-6qhc t:meta.view.tableauthor d:2017-03-07T22:59:04.099Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"
```