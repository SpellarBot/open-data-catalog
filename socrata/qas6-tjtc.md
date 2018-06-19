# NYSTAR Center for Advanced Technology Economic Impacts: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nystar-center-for-advanced-technology-economic-impacts-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/qas6-tjtc) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qas6-tjtc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qas6-tjtc/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qas6-tjtc |
| Name | NYSTAR Center for Advanced Technology Economic Impacts: Beginning 2008 |
| Attribution | Empire State Development Division of Science, Technology and Innovation (NYSTAR) |
| Category | Economic Development |
| Tags | cat, economic impact, job growth, technology, high tech, investments, public private partnerships |
| Created | 2014-02-24T18:21:16Z |
| Publication Date | 2016-03-02T15:11:45Z |

## Description

Economic impacts of the 15 Division of Science, Technology and Innovation (NYSTAR) Centers for Advanced Technology (CATs).

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | cat_name                      | CAT Name                      | text      | text        |
| Yes      | time           | year                          | Year                          | number    | number      |
| Yes      | numeric metric | state_funding                 | State Funding                 | money     | money       |
| Yes      | numeric metric | increased_revenues            | Increased Revenues            | money     | money       |
| Yes      | numeric metric | cost_savings                  | Cost Savings                  | money     | money       |
| Yes      | numeric metric | government_funds_acquired     | Government Funds Acquired     | money     | money       |
| Yes      | numeric metric | non_government_funds_acquired | Non-Government Funds Acquired | money     | money       |
| Yes      | numeric metric | capital_improvements          | Capital Improvements          | money     | money       |
| Yes      | numeric metric | new_jobs                      | New Jobs                      | number    | number      |
| Yes      | numeric metric | retained_jobs                 | Retained Jobs                 | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qas6-tjtc d:2008-01-01T00:00:00.000Z t:cat_name="Alfred University Center for Advanced Ceramic Technology (CACT)" m:non_government_funds_acquired=21590000 m:retained_jobs=12 m:capital_improvements=100000 m:new_jobs=27 m:government_funds_acquired=0 m:increased_revenues=18320000 m:cost_savings=2466000 m:state_funding=921200

series e:qas6-tjtc d:2008-01-01T00:00:00.000Z t:cat_name="Binghamton University Integrated Electronics Engineering Center" m:non_government_funds_acquired=0 m:retained_jobs=63 m:capital_improvements=167506 m:new_jobs=73 m:government_funds_acquired=0 m:increased_revenues=4559629 m:cost_savings=7602320 m:state_funding=921200

series e:qas6-tjtc d:2008-01-01T00:00:00.000Z t:cat_name="Clarkson University Center for Advanced Materials Processing" m:non_government_funds_acquired=0 m:retained_jobs=12 m:capital_improvements=0 m:new_jobs=7 m:government_funds_acquired=1600000 m:increased_revenues=8200000 m:cost_savings=21173500 m:state_funding=921200
```

## Meta Commands

```ls
metric m:state_funding p:integer l:"State Funding" d:"Level of New York State funding allocated (not reimbursed) to the CAT during designated year." t:dataTypeName=money

metric m:increased_revenues p:double l:"Increased Revenues" d:"CATs frequently collaborate in new product development or existing product improvement that directly increases client revenues. Retained sales ? In extraordinary cases, NYSTAR may credit impact for retained sales. In these cases, company documentation must clearly state that due to the CAT?s work, the Company was able to retain a specific customer that it would have otherwise lost (e.g., due to quality control problems). These cases are expected to be the exception rather than the norm." t:dataTypeName=money

metric m:cost_savings p:double l:"Cost Savings" d:"Cost savings that typically accrue from CAT collaboration are production process improvements, the value of accessing specialized equipment, expertise or analytical testing, and other research savings. Valuing Research Savings ? When savings are reported because the CAT is providing services such as access to specialized equipment, analytical testing, or research expertise that otherwise would have to be done by the company in-house, the appropriate level of credit is not the total amount the research would have cost the company in-house, but the difference between this cost and the amount contributed by the company. Most often, company letters already report savings as this net amount." t:dataTypeName=money

metric m:government_funds_acquired p:double l:"Government Funds Acquired" d:"Grants and funds acquired that are not considered NYS Funds, these can be federal grants or funds acquired from the locality" t:dataTypeName=money

metric m:non_government_funds_acquired p:double l:"Non-Government Funds Acquired" d:"NYSTAR recognizes venture capital, other business investments, and non-NYS grants such as Small Business Innovation Research(SBIR)/Small Business Technology Transfer (STTR), etc. Key Factors ? Funds must represent nonNYS government funds (i.e., additional funds being infused into New York?s economy) and a demonstration that the CAT played a substantive role in helping the company obtain the funds." t:dataTypeName=money

metric m:capital_improvements p:double l:"Capital Improvements" d:"Building and capital projects created as a direct result of the work of the CAT." t:dataTypeName=money

metric m:new_jobs p:integer l:"New Jobs" d:"Credited jobs must be permanent, full-time positions. Job creation is not equivalent to a company hiring a number of students out of the University population. Credited job creation is the result of business expansion resulting from the CAT?s efforts." t:dataTypeName=number

metric m:retained_jobs p:integer l:"Retained Jobs" d:"Jobs may be at risk when companies consider relocation because of high operating costs, incentives offered by another location, or production contractions. A company?s relationship with the CAT may be a major factor in its decision to continue operations in NYS or maintain production capacity. The company letter and other substantiation must present a credible case that the jobs were at risk and that the collaboration with the CAT was a significant reason for their retention. In the case of company relocation, supporting documentation must include the following: (1) comparisons of higher operating costs in NYS vs. other considered specific location(s); or (2) specific offers or incentives for relocation." t:dataTypeName=number

entity e:qas6-tjtc l:"NYSTAR Center for Advanced Technology Economic Impacts: Beginning 2008" t:attribution="Empire State Development Division of Science, Technology and Innovation (NYSTAR)" t:url=https://data.ny.gov/api/views/qas6-tjtc

property e:qas6-tjtc t:meta.view v:id=qas6-tjtc v:category="Economic Development" v:attributionLink=http://esd.ny.gov/nystar/ v:averageRating=0 v:name="NYSTAR Center for Advanced Technology Economic Impacts: Beginning 2008" v:attribution="Empire State Development Division of Science, Technology and Innovation (NYSTAR)"

property e:qas6-tjtc t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qas6-tjtc t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:qas6-tjtc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| cat_name                                                                    | year | state_funding | increased_revenues | cost_savings | government_funds_acquired | non_government_funds_acquired | capital_improvements | new_jobs | retained_jobs | 
| =========================================================================== | ==== | ============= | ================== | ============ | ========================= | ============================= | ==================== | ======== | ============= | 
| Alfred University Center for Advanced Ceramic Technology (CACT)             | 2008 | 921200        | 18320000.00        | 2466000.00   | 0.00                      | 21590000.00                   | 100000.00            | 27       | 12            | 
| Binghamton University Integrated Electronics Engineering Center             | 2008 | 921200        | 4559629.00         | 7602320.00   | 0.00                      | 0.00                          | 167506.00            | 73       | 63            | 
| Clarkson University Center for Advanced Materials Processing                | 2008 | 921200        | 8200000.00         | 21173500.00  | 1600000.00                | 0.00                          | 0.00                 | 7        | 12            | 
| Columbia University Center for Advanced Information Management              | 2008 | 921200        | 0.00               | 31910000.00  | 1300000.00                | 0.00                          | 0.00                 | 10       | 0             | 
| Cornell University Center for Life Science Enterprise                       | 2008 | 921200        | 0.00               | 526000.00    | 2624200.00                | 7110000.00                    | 546000.00            | 12       | 32            | 
| CUNY Center for Ultrafast Photonic Materials and Applications               | 2008 | 522369        | 0.00               | 3026850.00   | 2099000.00                | 0.00                          | 516000.00            | 1        | 0             | 
| Polytechnic University Center for Advanced Technology in Telecommunications | 2008 | 921200        | 668000.00          | 41710000.00  | 0.00                      | 0.00                          | 0.00                 | 18       | 36            | 
| RPI Center for Automation Technologies and Systems                          | 2008 | 921200        | 19510162.00        | 1490422.00   | 7590825.00                | 2076969.00                    | 11698499.00          | 143      | 35            | 
| RPI Center for Future Energy Systems                                        | 2008 | 921200        | 0.00               | 0.00         | 0.00                      | 10300000.00                   | 0.00                 | 6        | 0             | 
| Stony Brook University Center for Advanced Sensor Technology                | 2008 | 921200        | 1536000.00         | 10690000.00  | 2286000.00                | 850000.00                     | 1115000.00           | 9        | 5             | 
```