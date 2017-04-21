# Local Development Corporations Bonds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-development-corporations-bonds) |
| Metadata | [Link](https://data.ny.gov/api/views/9kfh-uzu3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9kfh-uzu3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9kfh-uzu3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9kfh-uzu3 |
| Name | Local Development Corporations Bonds |
| Attribution | Individual Local Development Corporations submitted to Authorities Budget Office |
| Category | Transparency |
| Tags | ldc bonds |
| Created | 2015-03-16T13:13:41Z |
| Publication Date | 2016-10-06T16:40:03Z |

## Description

Public authorities are required by Section 2800 of Public Authorities Law to submit annual reports to the Authorities Budget Office that include bonds data. Local development corporations are required to report information on the projects they support and how those approved projects are financed (either through grants, loans, or bonds). The dataset consists bonds data reported by Local Development Corporations beginning with fiscal years ending in 2011.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ========================================= | ============= | ============= |
| Yes      | series tag     | authority_name                            | Authority Name                            | text          | text          |
| Yes      | time           | fiscal_year_end_date                      | Fiscal Year End Date                      | calendar_date | calendar_date |
| Yes      | series tag     | bonds                                     | Bonds                                     | text          | text          |
| Yes      | series tag     | recipient_name                            | Recipient Name                            | text          | text          |
| Yes      | series tag     | recipient_city                            | Recipient City                            | text          | text          |
| Yes      | series tag     | recipient_state                           | Recipient State                           | text          | text          |
| Yes      | series tag     | recipient_postal_code                     | Recipient Postal Code                     | text          | text          |
| Yes      | numeric metric | amount_issued                             | Amount Issued                             | money         | money         |
| No       |                | date_issued                               | Date Issued                               | calendar_date | calendar_date |
| Yes      | numeric metric | interest_rate                             | Interest Rate                             | number        | number        |
| Yes      | numeric metric | expected_year_retired                     | Expected Year Retired                     | number        | number        |
| Yes      | numeric metric | principal_retired_during_year             | Principal Retired During Year             | money         | money         |
| Yes      | numeric metric | principal_retired_at_start_of_fiscal_year | Principal Retired at Start of Fiscal Year | money         | money         |
| Yes      | numeric metric | amount_outstanding                        | Amount Outstanding                        | money         | money         |
| Yes      | series tag     | bond_purpose                              | Bond Purpose                              | text          | text          |
| Yes      | series tag     | new_jobs                                  | New Jobs                                  | text          | text          |
| Yes      | numeric metric | jobs_planned                              | Jobs Planned                              | number        | number        |
| Yes      | numeric metric | jobs_created                              | Jobs Created                              | number        | number        |
| Yes      | series tag     | fully_retired                             | Fully Retired                             | text          | text          |
```

## Time Field

```ls
Value = fiscal_year_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_issued
```

## Data Commands

```ls
series e:9kfh-uzu3 d:2011-06-30T00:00:00.000Z t:authority_name="STAR (Sales Tax Asset Receivable) Corporation" t:recipient_city="NEW YORK" t:new_jobs=No t:bond_purpose="Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)" t:recipient_postal_code=10007 t:recipient_state=NY t:fully_retired=No t:recipient_name="Sales Tax Asset Receivable Corporation" m:amount_issued=2551435000 m:principal_retired_at_start_of_fiscal_year=373535000 m:amount_outstanding=2116455000 m:expected_year_retired=2033 m:interest_rate=4.64 m:principal_retired_during_year=61445000

series e:9kfh-uzu3 d:2011-06-30T00:00:00.000Z t:authority_name="Fiscal Year 2005 Securitization Corporation" t:recipient_city="NEW YORK" t:new_jobs=No t:bond_purpose="Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)" t:recipient_postal_code=10007 t:recipient_state=NY t:fully_retired=No t:recipient_name="Fiscal Year 2005 Securitization Corporation" m:amount_issued=498845000 m:principal_retired_at_start_of_fiscal_year=204600000 m:amount_outstanding=282385000 m:expected_year_retired=2020 m:interest_rate=4.8 m:principal_retired_during_year=11860000

series e:9kfh-uzu3 d:2011-06-30T00:00:00.000Z t:authority_name="Hudson Yards Infrastructure Corporation" t:recipient_city="NEW YORK" t:new_jobs=No t:bond_purpose="Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)" t:recipient_postal_code=10007 t:recipient_state=NY t:fully_retired=No t:recipient_name="Hudson Yards Infrastructure Corporation" m:amount_issued=2000000000 m:principal_retired_at_start_of_fiscal_year=0 m:amount_outstanding=2000000000 m:expected_year_retired=2047 m:interest_rate=4.6 m:principal_retired_during_year=0
```

## Meta Commands

```ls
metric m:amount_issued p:double l:"Amount Issued" d:"Total dollar amount of the bond issued" t:dataTypeName=money

metric m:interest_rate p:double l:"Interest Rate" d:"Interest rate of the bond" t:dataTypeName=number

metric m:expected_year_retired p:integer l:"Expected Year Retired" d:"Year bonds are expected to be retired (paid off)" t:dataTypeName=number

metric m:principal_retired_during_year p:double l:"Principal Retired During Year" d:"Amount of bonds principal retired (paid off) during the reporting year" t:dataTypeName=money

metric m:principal_retired_at_start_of_fiscal_year p:double l:"Principal Retired at Start of Fiscal Year" d:"Amount of bonds principal retired (paid off) prior to the reporting year. This field is blank if the authority did not enter any data in this field." t:dataTypeName=money

metric m:amount_outstanding p:double l:"Amount Outstanding" d:"Current amount of bonds remaining to be paid off (outstanding)" t:dataTypeName=money

metric m:jobs_planned p:integer l:"Jobs Planned" d:"Number of jobs planned to be created as a result of the bonds. This field is blank if the authority indicated that the bonds were not expected to result in new jobs being created or if there were no bonds reported." t:dataTypeName=number

metric m:jobs_created p:integer l:"Jobs Created" d:"Number of jobs created as a result of the bonds. This field is blank if the authority indicated that the bonds were not expected to result in new jobs being created or if there were no bonds reported." t:dataTypeName=number

entity e:9kfh-uzu3 l:"Local Development Corporations Bonds" t:attribution="Individual Local Development Corporations submitted to Authorities Budget Office" t:url=https://data.ny.gov/api/views/9kfh-uzu3

property e:9kfh-uzu3 t:meta.view v:id=9kfh-uzu3 v:category=Transparency v:attributionLink=http://www.abo.ny.gov/ v:averageRating=0 v:name="Local Development Corporations Bonds" v:attribution="Individual Local Development Corporations submitted to Authorities Budget Office"

property e:9kfh-uzu3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9kfh-uzu3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:9kfh-uzu3 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| authority_name                                                | fiscal_year_end_date | bonds | recipient_name                              | recipient_city | recipient_state | recipient_postal_code | amount_issued | date_issued         | interest_rate | expected_year_retired | principal_retired_during_year | principal_retired_at_start_of_fiscal_year | amount_outstanding | bond_purpose                                                            | new_jobs | jobs_planned | jobs_created | fully_retired | 
| ============================================================= | ==================== | ===== | =========================================== | ============== | =============== | ===================== | ============= | =================== | ============= | ===================== | ============================= | ========================================= | ================== | ======================================================================= | ======== | ============ | ============ | ============= | 
| STAR (Sales Tax Asset Receivable) Corporation                 | 2011-06-30T00:00:00  |       | Sales Tax Asset Receivable Corporation      | NEW YORK       | NY              | 10007                 | 2551435000.00 | 2004-11-04T00:00:00 | 4.64          | 2033                  | 61445000.00                   | 373535000.00                              | 2116455000.00      | Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)  | No       |              |              | No            | 
| Fiscal Year 2005 Securitization Corporation                   | 2011-06-30T00:00:00  |       | Fiscal Year 2005 Securitization Corporation | NEW YORK       | NY              | 10007                 | 498845000.00  | 2004-12-02T00:00:00 | 4.8           | 2020                  | 11860000.00                   | 204600000.00                              | 282385000.00       | Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)  | No       |              |              | No            | 
| Hudson Yards Infrastructure Corporation                       | 2011-06-30T00:00:00  |       | Hudson Yards Infrastructure Corporation     | NEW YORK       | NY              | 10007                 | 2000000000.00 | 2006-12-21T00:00:00 | 4.6           | 2047                  | 0.00                          | 0.00                                      | 2000000000.00      | Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)  | No       |              |              | No            | 
| TSASC, Inc.                                                   | 2011-06-30T00:00:00  |       | TSASC, Inc.                                 | NEW YORK       | NY              | 10007                 | 1353510000.00 | 2006-02-08T00:00:00 | 5.43          | 2042                  | 4875000.00                    | 88345000.00                               | 1260290000.00      | Land Acquisition/Development /Infrastructure Costs (i.e., Water/Sewer)  | No       |              |              | No            | 
| New York City Capital Resource Corporation                    | 2011-06-30T00:00:00  |       | Cobble Hill Health Center, Inc.             | BROOKLYN       | NY              | 11201                 | 48190000.00   | 2008-01-30T00:00:00 | 0.6           | 2037                  | 1165000.00                    | 0.00                                      | 47025000.00        | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | No            | 
| New York City Capital Resource Corporation                    | 2011-06-30T00:00:00  |       | Maimonides Medical Center                   | BROOKLYN       | NY              | 11219                 | 31200000.00   | 2006-05-01T00:00:00 | 0.6           | 2026                  | 1085000.00                    | 3770000.00                                | 26345000.00        | Commercial Property Construction/Acquisition/Revitalization/Improvement | Yes      | 127          | 924          | No            | 
| New York City Capital Resource Corporation                    | 2011-06-30T00:00:00  |       | Natural Resources Defense Council           | NEW YORK       | NY              | 10011                 | 12730000.00   | 2008-01-24T00:00:00 | 0.6           | 2038                  | 235000.00                     | 440000.00                                 | 12055000.00        | Commercial Property Construction/Acquisition/Revitalization/Improvement | Yes      | 15           | 0            | No            | 
| New York City Capital Resource Corporation                    | 2011-06-30T00:00:00  |       | Polytechnic Prepatory Country Day School    | BROOKLYN       | NY              | 11215                 | 7245000.00    | 2006-12-01T00:00:00 | 0.29          | 2037                  | 0.00                          | 0.00                                      | 7245000.00         | Commercial Property Construction/Acquisition/Revitalization/Improvement | Yes      | 2            | 1            | No            | 
| New York City Capital Resource Corporation                    | 2011-06-30T00:00:00  |       | Village Center for Care                     | NEW YORK       | NY              | 10014                 | 37620000.00   | 2007-12-20T00:00:00 | 0.6           | 2037                  | 23275000.00                   | 0.00                                      | 14345000.00        | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | No            | 
| Monroe Security & Safety System Local Development Corporation | 2011-12-31T00:00:00  |       | Monroe Security and Safety Systems LDC      | ROCHESTER      | NY              | 14614                 | 59335000.00   | 2010-05-14T00:00:00 | 4.08          | 2029                  | 0.00                          | 0.00                                      | 59335000.00        | Commercial Property Construction/Acquisition/Revitalization/Improvement | No       |              |              | No            | 
```