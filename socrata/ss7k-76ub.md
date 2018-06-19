# Governor?s Office of Storm Recovery (GOSR) Quarterly Contract Reporting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/governors-office-of-storm-recovery-gosr-quarterly-contract-reporting) |
| Metadata | [Link](https://data.ny.gov/api/views/ss7k-76ub) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ss7k-76ub/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ss7k-76ub/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ss7k-76ub |
| Name | Governor?s Office of Storm Recovery (GOSR) Quarterly Contract Reporting |
| Attribution | Governor?s Office of Storm Recovery (GOSR) |
| Category | Economic Development |
| Tags | storm recovery, sandy, irene, lee, hurricane, superstorm, tropical storm, build it back, nyrising, resiliency, resilient, housing |
| Created | 2016-04-15T18:33:01Z |
| Publication Date | 2016-07-25T21:39:46Z |

## Description

A listing of contracts between the Governor?s Office of Storm Recovery ? organized under the NYS Housing Trust Fund Corporation (HTFC) and operating within NYS Homes and Community Renewal ? and various service providers and storm recovery organizations across New York State.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================= | ============= | ============= |
| Yes      | series tag     | contractor_name               | Contractor Name               | text          | text          |
| Yes      | series tag     | duns_number                   | DUNS Number                   | text          | text          |
| Yes      | series tag     | procured_by                   | Procured By                   | text          | text          |
| Yes      | time           | contract_execution_date       | Contract Execution Date       | calendar_date | calendar_date |
| No       |                | contract_end_date             | Contract End Date             | calendar_date | calendar_date |
| Yes      | numeric metric | total_contract_amount         | Total Contract Amount         | money         | money         |
| Yes      | numeric metric | amount_of_cdbg_dr_funds       | Amount of CDBG-DR Funds       | money         | money         |
| Yes      | series tag     | brief_description_of_contract | Brief Description of Contract | text          | text          |
| Yes      | series tag     | comment                       | Comment                       | text          | text          |
```

## Time Field

```ls
Value = contract_execution_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contract_end_date
```

## Data Commands

```ls
series e:ss7k-76ub d:2014-11-18T00:00:00.000Z t:procured_by=HTFC/GOSR t:duns_number=82-638-8886 t:contractor_name="A Russo Wrecking Inc" t:brief_description_of_contract=Demolition m:total_contract_amount=967545 m:amount_of_cdbg_dr_funds=967545

series e:ss7k-76ub d:2011-03-15T00:00:00.000Z t:procured_by=HTFC/GOSR t:duns_number=80-201-6709 t:contractor_name="Agate Software Inc" t:brief_description_of_contract="Grant Administration Software Program" m:total_contract_amount=998250 m:amount_of_cdbg_dr_funds=998250

series e:ss7k-76ub d:2015-09-18T00:00:00.000Z t:procured_by=HTFC/GOSR t:duns_number=80-201-6709 t:contractor_name="Agate Software Inc" t:brief_description_of_contract="Development and Configuration of IntelliGrants Grant Administration Software" m:total_contract_amount=897562.75 m:amount_of_cdbg_dr_funds=897562.75
```

## Meta Commands

```ls
metric m:total_contract_amount p:double l:"Total Contract Amount" d:"The total value of the contract including funds not provided by the Governor?s Office of Storm Recovery or in other words the ?gross amount? of the contract. If marked ?open,? these contracts are for professional services like temporary staffing or legal services, which do not specify a total dollar amount, but do have specific contract end dates. Some DASNY (Dormitory Authority of the State of New York) term consultant contracts do not have a dollar value assigned, rather, the ?Not To Exceed? values are decided at the work order level, not the contract level. When there is a specific scope of work that GOSR needs DASNY to perform, GOSR signs a work order with DASNY specifying the scope and budget, and then DASNY issues a work authorization to a contractor to perform the work. (A ?work authorization? is the specific contract mechanism used by DASNY to engage a consultant under an existing term contract that details the specific scope of services to be performed. Conversely, a ?work order? is the mechanism used under a different HTFC/DASNY subrecipient agreement pursuant to which HTFC engages DASNY to perform a particular scope of work for a specific budget.)" t:dataTypeName=money

metric m:amount_of_cdbg_dr_funds p:double l:"Amount of CDBG-DR Funds" d:"The dollar value of the grant provided by the Governor?s Office of Storm Recovery or the ?net amount? of CDBG-DR funds in the contract." t:dataTypeName=money

entity e:ss7k-76ub l:"Governor?s Office of Storm Recovery (GOSR) Quarterly Contract Reporting" t:attribution="Governor?s Office of Storm Recovery (GOSR)" t:url=https://data.ny.gov/api/views/ss7k-76ub

property e:ss7k-76ub t:meta.view v:id=ss7k-76ub v:category="Economic Development" v:attributionLink=http://stormrecovery.ny.gov/contracts v:averageRating=0 v:name="Governor?s Office of Storm Recovery (GOSR) Quarterly Contract Reporting" v:attribution="Governor?s Office of Storm Recovery (GOSR)"

property e:ss7k-76ub t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ss7k-76ub t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| contractor_name                 | duns_number | procured_by       | contract_execution_date | contract_end_date   | total_contract_amount | amount_of_cdbg_dr_funds | brief_description_of_contract                                                | comment                                                              | 
| =============================== | =========== | ================= | ======================= | =================== | ===================== | ======================= | ============================================================================ | ==================================================================== | 
| 22nd Century Technologies, Inc. | 02-861-9588 | HTFC/GOSR         | 2015-05-15T00:00:00     | 2016-08-08T00:00:00 |                       |                         | Temporary Staffing Services                                                  | Both "Total Contract Amount" and "Amount of CDBG-DR Funds" are open. | 
| A Russo Wrecking Inc            | 82-638-8886 | HTFC/GOSR         | 2014-11-18T00:00:00     | 2015-03-15T00:00:00 | 967545.00             | 967545.00               | Demolition                                                                   |                                                                      | 
| Agate Software Inc              | 80-201-6709 | HTFC/GOSR         | 2011-03-15T00:00:00     | 2014-04-04T00:00:00 | 998250.00             | 998250.00               | Grant Administration Software Program                                        |                                                                      | 
| Agate Software Inc              | 80-201-6709 | HTFC/GOSR         | 2015-09-18T00:00:00     | 2016-09-13T00:00:00 | 897562.75             | 897562.75               | Development and Configuration of IntelliGrants Grant Administration Software |                                                                      | 
| AKRF Inc                        | 01-305-2295 | HTFC/GOSR         | 2013-10-25T00:00:00     | 2015-06-19T00:00:00 | 3013951.11            | 3013951.00              | Planning, Technical and Professional Services                                |                                                                      | 
| AKRF Inc                        | 01-305-2295 | HTFC/GOSR         | 2014-10-02T00:00:00     | 2016-11-03T00:00:00 | 3000000.00            | 3000000.00              | Environmental Services                                                       |                                                                      | 
| Alt Consulting Inc              | 00-213-9048 | HTFC/GOSR         | 2014-08-05T00:00:00     | 2015-06-15T00:00:00 | 100000.00             | 100000.00               | Financial Programmer                                                         |                                                                      | 
| Anderson Kill & Olick P.C       | 07-770-3353 | HTFC/GOSR         | 2013-11-07T00:00:00     | 2014-11-06T00:00:00 | 70000.00              | 70000.00                | Legal Services                                                               |                                                                      | 
| Armand Corporation              | 55-676-1823 | HTFC/GOSR         | 2015-01-09T00:00:00     | 2016-09-29T00:00:00 | 36964996.00           | 36964996.00             | Construction Management Services                                             |                                                                      | 
| Barton & Loguidice, D.P.C.      | 05-372-6253 | City of Amsterdam | 2015-09-22T00:00:00     |                     | 131574.00             | 131574.00               | A/E Services                                                                 |                                                                      | 
```