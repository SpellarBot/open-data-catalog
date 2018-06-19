# Empire State Development (ESD) Directors' Approval Funding Summary: Beginning Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/empire-state-development-esd-directors-approval-funding-summary-beginning-fiscal-year-2012) |
| Metadata | [Link](https://data.ny.gov/api/views/ukw4-nsjd) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ukw4-nsjd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ukw4-nsjd/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ukw4-nsjd |
| Name | Empire State Development (ESD) Directors' Approval Funding Summary: Beginning Fiscal Year 2012 |
| Attribution | Empire State Development |
| Category | Economic Development |
| Tags | loans, grants, economic development, empire state development, region, program |
| Created | 2014-02-24T15:45:39Z |
| Publication Date | 2016-02-10T14:25:02Z |

## Description

This dataset presents a list of funding approved by the ESD Directors. Data categories are project name, region, program, funding amount and fiscal year.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | region           | ESD Region       | text      | text        |
| Yes      | series tag     | project_name     | Project Name     | text      | text        |
| Yes      | series tag     | program          | Program          | text      | text        |
| Yes      | numeric metric | approved_funding | Approved Funding | money     | money       |
| Yes      | time           | fiscal_year      | Fiscal Year      | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ukw4-nsjd d:2013-01-01T00:00:00.000Z t:region=Capital t:project_name="Albany Medical College Capital & Working Capital - NYCAP Research Alliance" t:program=EDPF m:approved_funding=950000

series e:ukw4-nsjd d:2013-01-01T00:00:00.000Z t:region=Capital t:project_name="Capital Chamber Foundation - EAP Center 2012-2013" t:program=EAP m:approved_funding=99593

series e:ukw4-nsjd d:2013-01-01T00:00:00.000Z t:region=Capital t:project_name="Community Loan Fund of the Capital Region CDFI 14" t:program=CDFI m:approved_funding=75000
```

## Meta Commands

```ls
metric m:approved_funding p:integer l:"Approved Funding" d:"Dollars approved for business assistance" t:dataTypeName=money

entity e:ukw4-nsjd l:"Empire State Development (ESD) Directors' Approval Funding Summary: Beginning Fiscal Year 2012" t:attribution="Empire State Development" t:url=https://data.ny.gov/api/views/ukw4-nsjd

property e:ukw4-nsjd t:meta.view v:id=ukw4-nsjd v:category="Economic Development" v:attributionLink=http://www.esd.ny.gov/ v:averageRating=0 v:name="Empire State Development (ESD) Directors' Approval Funding Summary: Beginning Fiscal Year 2012" v:attribution="Empire State Development"

property e:ukw4-nsjd t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ukw4-nsjd t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ukw4-nsjd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| region  | project_name                                                               | program   | approved_funding | fiscal_year | 
| ======= | ========================================================================== | ========= | ================ | =========== | 
| Capital | Albany Medical College Capital & Working Capital - NYCAP Research Alliance | EDPF      | 950000           | 2013        | 
| Capital | Capital Chamber Foundation - EAP Center 2012-2013                          | EAP       | 99593            | 2013        | 
| Capital | Community Loan Fund of the Capital Region CDFI 14                          | CDFI      | 75000            | 2013        | 
| Capital | Fountains Spatial Online Mapping Application UCDP Working Capital          | UCDP      | 100000           | 2013        | 
| Capital | Hudson Falls-RESTORE III-First National Bank Building Redevelopment        | RestoreNY | 500000           | 2013        | 
| Capital | NYBDC Small Business Loan Program                                          | SBRLF     | 996684           | 2013        | 
| Capital | SEED - SUNY Albany Working Capital                                         | UCDP      | 99924            | 2013        | 
| Capital | The Case Group JDA M&E                                                     | JDA       | 816000           | 2013        | 
| Capital | The Case Group JDA RE                                                      | JDA       | 1200000          | 2013        | 
| Capital | University at Albany - Biotechnology Training Center                       | RCCF      | 1000000          | 2013        | 
```