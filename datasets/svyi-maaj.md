# Minority and Women-Owned Business Enterprise Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/minority-and-women-owned-business-enterprise-statistics-cbe63) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/svyi-maaj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/svyi-maaj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/svyi-maaj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | svyi-maaj |
| Name | Minority and Women-Owned Business Enterprise Statistics |
| Attribution | Law Department (LAW) |
| Category | City Government |
| Tags | law, justice, legislation, lawyer |
| Created | 2013-02-05T22:29:36Z |
| Publication Date | 2013-06-21T19:55:39Z |

## Description

New York City's "MWBE" program, enacted by the City Council and signed by the Mayor as Local Law 129 of 2005, is designed to promote government contracting opportunities for businesses owned by minorities and women. Our "Emerging Business Enterprise" program, enacted by the City Council and signed by the Mayor as Local Law 12 of 2006, is designed to promote such opportunities for businesses owned by persons who are "socially and economically disadvantaged." Together, the programs establish the following Citywide goals for contracts and subcontracts in amounts under $1 million.

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                    | Data Type | Render Type |
| ======== | =========== | ===================================== | ======================================= | ========= | =========== |
| No       | time        | :updated_at                           | updated_at                              | meta_data | meta_data   |
| Yes      | series tag  | mwbe_type                             | MWBE Type                               | text      | text        |
| Yes      | series tag  | prime_contracts_professional_services | Prime Contracts - Professional Services | text      | text        |
| Yes      | series tag  | prime_contracts_standard_services     | Prime Contracts - Standard Services     | text      | text        |
| Yes      | series tag  | prime_contracts_goods                 | Prime Contracts - Goods                 | text      | text        |
| Yes      | series tag  | prime_contracts_construction          | Prime Contracts - Construction          | text      | text        |
| Yes      | series tag  | subcontracts_professional_services    | Subcontracts - Professional Services    | text      | text        |
| Yes      | series tag  | subcontracts_construction             | Subcontracts - Construction             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:svyi-maaj d:2013-02-05T14:29:37.000Z t:subcontracts_construction=9% t:mwbe_type="Black American" t:prime_contracts_professional_services=9% t:subcontracts_professional_services=9% t:prime_contracts_construction=12.63% t:prime_contracts_standard_services=9.23% t:prime_contracts_goods=7.47% m:row_number.svyi-maaj=1

series e:svyi-maaj d:2013-02-05T14:29:37.000Z t:subcontracts_construction=9.47% t:mwbe_type="Asian American" t:prime_contracts_professional_services="No goal" t:subcontracts_professional_services="No goal" t:prime_contracts_construction="No goal" t:prime_contracts_standard_services="No goal" t:prime_contracts_goods=5.29% m:row_number.svyi-maaj=2

series e:svyi-maaj d:2013-02-05T14:29:37.000Z t:subcontracts_construction=9.06% t:mwbe_type="Hispanic American" t:prime_contracts_professional_services=5% t:subcontracts_professional_services=5% t:prime_contracts_construction=9.06% t:prime_contracts_standard_services=5.14% t:prime_contracts_goods=4.99% m:row_number.svyi-maaj=3
```

## Meta Commands

```ls
metric m:row_number.svyi-maaj p:long l:"Row Number"

entity e:svyi-maaj l:"Minority and Women-Owned  Business Enterprise Statistics" t:attribution="Law Department (LAW)" t:url=https://data.cityofnewyork.us/api/views/svyi-maaj

property e:svyi-maaj t:meta.view v:id=svyi-maaj v:category="City Government" v:attributionLink=http://www.nyc.gov/html/law/html/opportunities/opportunities.shtml v:averageRating=0 v:name="Minority and Women-Owned  Business Enterprise Statistics" v:attribution="Law Department (LAW)"

property e:svyi-maaj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:svyi-maaj t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | mwbe_type         | prime_contracts_professional_services | prime_contracts_standard_services | prime_contracts_goods | prime_contracts_construction | subcontracts_professional_services | subcontracts_construction | 
| =========== | ================= | ===================================== | ================================= | ===================== | ============================ | ================================== | ========================= | 
| 1360074577  | Black American    | 9%                                    | 9.23%                             | 7.47%                 | 12.63%                       | 9%                                 | 9%                        | 
| 1360074577  | Asian American    | No goal                               | No goal                           | 5.29%                 | No goal                      | No goal                            | 9.47%                     | 
| 1360074577  | Hispanic American | 5%                                    | 5.14%                             | 4.99%                 | 9.06%                        | 5%                                 | 9.06%                     | 
| 1360074577  | Caucasian Female  | 16.50%                                | 10.45%                            | 17.87%                | No goal                      | 16.50%                             | No goal                   | 
| 1360074577  | Emerging Business | 6%                                    | 6%                                | 6%                    | 6%                           | 6%                                 | 6%                        | 
```