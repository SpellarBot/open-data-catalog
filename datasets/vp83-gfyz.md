# Local Development Corporations Loans

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-development-corporations-loans) |
| Metadata | [Link](https://data.ny.gov/api/views/vp83-gfyz) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vp83-gfyz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vp83-gfyz/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vp83-gfyz |
| Name | Local Development Corporations Loans |
| Attribution | Individual Local Development Corporations submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | ldc loans |
| Created | 2015-03-16T13:50:10Z |
| Publication Date | 2016-10-06T16:40:02Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include loans data. Local development corporations are required to report information on the projects they support and how those approved projects are financed (either through grants, loans, or bonds).  The dataset consists of loans data reported by Local Development Corporations beginning with fiscal years ending in 2011.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | authority_name        | Authority Name        | text          | text          |
| Yes      | time           | fiscal_year_end_date  | Fiscal Year End Date  | calendar_date | calendar_date |
| Yes      | series tag     | loans                 | Loans                 | text          | text          |
| Yes      | series tag     | loan_fund_sources     | Loan Fund Sources     | text          | text          |
| Yes      | series tag     | recipient_name        | Recipient Name        | text          | text          |
| Yes      | series tag     | recipient_city        | Recipient City        | text          | text          |
| Yes      | series tag     | recipient_state       | Recipient State       | text          | text          |
| Yes      | series tag     | recipient_postal_code | Recipient Postal Code | text          | text          |
| No       |                | date_loan_awarded     | Date Loan Awarded     | calendar_date | calendar_date |
| Yes      | numeric metric | original_loan_amount  | Original Loan Amount  | money         | money         |
| Yes      | numeric metric | interest_rate         | Interest Rate         | number        | number        |
| Yes      | numeric metric | loan_length           | Loan Length           | number        | number        |
| Yes      | numeric metric | amount_repaid         | Amount Repaid         | money         | money         |
| Yes      | series tag     | loan_purpose          | Loan Purpose          | text          | text          |
| Yes      | series tag     | new_jobs              | New Jobs              | text          | text          |
| Yes      | numeric metric | jobs_planned          | Jobs Planned          | number        | number        |
| Yes      | numeric metric | jobs_created          | Jobs Created          | number        | number        |
| Yes      | series tag     | loan_terms_completed  | Loan Terms Completed  | text          | text          |
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_loan_awarded
```

## Data Commands

```ls
series e:vp83-gfyz d:2011-06-30T00:00:00.000Z t:authority_name="Watertown Industrial Center Local Development Corporation" t:loan_fund_sources=Federal t:recipient_city=WATERTOWN t:loan_purpose="Commercial Property Construction/Acquisition/Revitalization/Improvement" t:new_jobs=No t:recipient_postal_code=13601 t:recipient_state=NY t:recipient_name="Jefferson County Job Development Corporation" t:loan_terms_completed=Yes m:original_loan_amount=81000 m:loan_length=5 m:amount_repaid=81000 m:interest_rate=3

series e:vp83-gfyz d:2011-06-30T00:00:00.000Z t:authority_name="Watertown Industrial Center Local Development Corporation" t:loan_fund_sources=Federal t:recipient_city=WATERTOWN t:loan_purpose="Commercial Property Construction/Acquisition/Revitalization/Improvement" t:new_jobs=No t:recipient_postal_code=13601 t:recipient_state=NY t:recipient_name="Ferguson Waterworks" t:loan_terms_completed=No m:original_loan_amount=100000 m:loan_length=5 m:amount_repaid=61741.85 m:interest_rate=3

series e:vp83-gfyz d:2011-06-30T00:00:00.000Z t:authority_name="Watertown Industrial Center Local Development Corporation" t:loan_fund_sources=Federal t:recipient_city=WATERTOWN t:loan_purpose="Commercial Property Construction/Acquisition/Revitalization/Improvement" t:new_jobs=No t:recipient_postal_code=13601 t:recipient_state=NY t:recipient_name="ServPro of Jefferson County" t:loan_terms_completed=No m:original_loan_amount=58457 m:loan_length=10 m:amount_repaid=15840.62 m:interest_rate=3
```

## Meta Commands

```ls
metric m:original_loan_amount p:double l:"Original Loan Amount" d:"Original amount of the loan" t:dataTypeName=money

metric m:interest_rate p:float l:"Interest Rate" d:"Interest rate of the loan as a percentage." t:dataTypeName=number

metric m:loan_length p:integer l:"Loan Length" d:"Number of years to repay loan" t:dataTypeName=number

metric m:amount_repaid p:double l:"Amount Repaid" d:"Amount of the loan that was repaid as of the end of the fiscal year" t:dataTypeName=money

metric m:jobs_planned p:integer l:"Jobs Planned" d:"Number of jobs planned to be created as a result of the loan. This field is blank if the authority indicated that the loan was not expected to result in new jobs being created or if there were no loans." t:dataTypeName=number

metric m:jobs_created p:integer l:"Jobs Created" d:"Number of jobs created as a result of the loan. This field is blank if the authority indicated that the loan was not expected to result in new jobs being created or if there were no loans" t:dataTypeName=number

entity e:vp83-gfyz l:"Local Development Corporations Loans" t:attribution="Individual Local Development Corporations submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/vp83-gfyz

property e:vp83-gfyz t:meta.view v:id=vp83-gfyz v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Local Development Corporations Loans" v:attribution="Individual Local Development Corporations submitted to Authorities Budget Office"

property e:vp83-gfyz t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vp83-gfyz t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vp83-gfyz t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                            | fiscal_year_end_date | loans | loan_fund_sources | recipient_name                                 | recipient_city | recipient_state | recipient_postal_code | date_loan_awarded   | original_loan_amount | interest_rate | loan_length | amount_repaid | loan_purpose                                                            | new_jobs | jobs_planned | jobs_created | loan_terms_completed | 
| ========================================================= | ==================== | ===== | ================= | ============================================== | ============== | =============== | ===================== | =================== | ==================== | ============= | =========== | ============= | ======================================================================= | ======== | ============ | ============ | ==================== | 
| Watertown Industrial Center Local Development Corporation | 2011-06-30T00:00:00  |       | Federal           | Jefferson County Job Development Corporation   | WATERTOWN      | NY              | 13601                 | 2004-09-21T00:00:00 | 81000.00             | 3             | 5           | 81000.00      | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | Yes                  | 
| Watertown Industrial Center Local Development Corporation | 2011-06-30T00:00:00  |       | Federal           | Ferguson Waterworks                            | WATERTOWN      | NY              | 13601                 | 2007-04-17T00:00:00 | 100000.00            | 3             | 5           | 61741.85      | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | No                   | 
| Watertown Industrial Center Local Development Corporation | 2011-06-30T00:00:00  |       | Federal           | ServPro of Jefferson County                    | WATERTOWN      | NY              | 13601                 | 2008-06-24T00:00:00 | 58457.00             | 3             | 10          | 15840.62      | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | No                   | 
| Watertown Industrial Center Local Development Corporation | 2011-06-30T00:00:00  |       | Federal           | Ferguson Waterworks                            | WATERTOWN      | NY              | 13601                 | 2009-02-17T00:00:00 | 25179.75             | 3             | 5           | 25179.75      | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | Yes                  | 
| New York City Economic Development Corporation            | 2011-06-30T00:00:00  |       | Federal           | M. Slavin & Sons, Ltd.                         | NEW YORK       | NY              | 10038                 | 2005-05-17T00:00:00 | 221850.00            | 3             | 20          | 0.00          | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | Yes                  | 
| New York City Economic Development Corporation            | 2011-06-30T00:00:00  |       | Federal           | South Street Seafood Corp.                     | NEW YORK       | NY              | 10038                 | 2005-05-17T00:00:00 | 101400.00            | 3             | 20          | 0.00          | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | No                   | 
| New York City Economic Development Corporation            | 2011-06-30T00:00:00  |       | Municipal         | East Harlem Abyssinian Triangle Limited Partn. | NEW YORK       | NY              | 10027                 | 1997-08-21T00:00:00 | 1412000.00           | 1             | 25          | 375253.41     | Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)  | No       |              |              | No                   | 
| New York City Economic Development Corporation            | 2011-06-30T00:00:00  |       | Municipal         | Mermaid Plaza Associates, Inc.                 | NEW YORK       | NY              | 10001                 | 1995-06-06T00:00:00 | 577596.00            | 1             | 22          | 0.00          | Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)  | No       |              |              | No                   | 
| New York City Economic Development Corporation            | 2011-06-30T00:00:00  |       | Municipal         | Plaza Del Castillo Development Corp.           | NEW YORK       | NY              | 10016                 | 1996-07-02T00:00:00 | 515746.00            | 1             | 14          | 0.00          | Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)  | No       |              |              | No                   | 
| New York City Economic Development Corporation            | 2011-06-30T00:00:00  |       | Municipal         | Poly Seal Packaging Corp.                      | BRONX          | NY              | 10460                 | 1990-10-29T00:00:00 | 175000.00            | 7             | 20          | 128122.17     | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | No                   | 
```