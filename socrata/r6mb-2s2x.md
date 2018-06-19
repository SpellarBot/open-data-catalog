# Main Tier Contracts by Solicitation for Renewable Portfolio Standard: 2005-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/main-tier-contracts-by-solicitation-for-renewable-portfolio-standard-2005-2011) |
| Metadata | [Link](https://data.ny.gov/api/views/r6mb-2s2x) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/r6mb-2s2x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/r6mb-2s2x/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | r6mb-2s2x |
| Name | Main Tier Contracts by Solicitation for Renewable Portfolio Standard: 2005-2015 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | mw, mwh, wind, hydro, biomass, biogas, solicitation |
| Created | 2013-02-21T21:13:13Z |
| Publication Date | 2016-04-28T14:55:26Z |

## Description

The goal of the Renewable Portfolio Standard (RPS) is to increase the proportion of renewable energy used by New York Consumers from the 2003 19.3% (baseline resources) to at least 30% by the end of 2015. The Main Tier Contracts by Solicitation for Renewable Portfolio Standard data set contains the solicitation round (1-7), facility name, resource type, location, county, MW capacity, MW bid capacity, contract annual maximum MWh quantity, duration of contract and project status, as required by the New York State Public Service Commission and reported in the annual New York State Renewable Portfolio Standard Performance Reports 2005 to 2011.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| Yes      | time           | year_reported                | Year Reported                  | number    | number      |
| Yes      | series tag     | solicitation                 | Solicitation                   | text      | text        |
| Yes      | series tag     | facility                     | Facility                       | text      | text        |
| Yes      | series tag     | resource_type                | Resource Type                  | text      | text        |
| Yes      | series tag     | state                        | State                          | text      | text        |
| Yes      | series tag     | county                       | County                         | text      | text        |
| Yes      | numeric metric | new_renewable_capacity_mw    | New Renewable Capacity (MW)    | number    | text        |
| Yes      | numeric metric | bid_capacity_mw              | Bid Capacity (MW)              | number    | text        |
| Yes      | numeric metric | annual_contract_quantity_mwh | Annual Contract Quantity (MWh) | number    | text        |
| Yes      | numeric metric | contract_duration_years      | Contract Duration (years)      | number    | number      |
| Yes      | series tag     | project_status               | Project Status                 | text      | text        |
```

## Time Field

```ls
Value = year_reported
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r6mb-2s2x d:2005-01-01T00:00:00.000Z t:project_status="not available" t:facility="Spier Falls" t:county="not available" t:resource_type=Hydro t:state="New York" t:solicitation="1st Main Tier Solicitation" m:annual_contract_quantity_mwh=3115 m:new_renewable_capacity_mw=0.8 m:contract_duration_years=10

series e:r6mb-2s2x d:2005-01-01T00:00:00.000Z t:project_status="not available" t:facility="Higley Falls" t:county="not available" t:resource_type=Hydro t:state="New York" t:solicitation="1st Main Tier Solicitation" m:annual_contract_quantity_mwh=8917 m:new_renewable_capacity_mw=2.2 m:contract_duration_years=1

series e:r6mb-2s2x d:2005-01-01T00:00:00.000Z t:project_status="not available" t:facility="Browns Falls" t:county="not available" t:resource_type=Hydro t:state="New York" t:solicitation="1st Main Tier Solicitation" m:annual_contract_quantity_mwh=978 m:new_renewable_capacity_mw=0.2 m:contract_duration_years=1
```

## Meta Commands

```ls
metric m:new_renewable_capacity_mw p:integer l:"New Renewable Capacity (MW)" d:"The renewable capacity resulting from the repowering or upgrade of a Facility." t:dataTypeName=number

metric m:bid_capacity_mw p:float l:"Bid Capacity (MW)" d:"Megawatt capacity a facility agreed to provide in their response to a Main Tier RFP" t:dataTypeName=number

metric m:annual_contract_quantity_mwh p:integer l:"Annual Contract Quantity (MWh)" d:"The maximum annual quantity of RPS attributes NYSERDA is obligated to purchase from the contracted Main Tier project." t:dataTypeName=number

metric m:contract_duration_years p:double l:"Contract Duration (years)" d:"RPS Main Tier contract duration in whole years." t:dataTypeName=number

entity e:r6mb-2s2x l:"Main Tier Contracts by Solicitation for Renewable Portfolio Standard: 2005-2015" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/r6mb-2s2x

property e:r6mb-2s2x t:meta.view v:id=r6mb-2s2x v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Publications/Program-Planning-Status-and-Evaluation-Reports/Renewable-Portfolio-Standard-Reports.aspx v:averageRating=0 v:name="Main Tier Contracts by Solicitation for Renewable Portfolio Standard: 2005-2015" v:attribution="New York State Energy Research and Development Authority"

property e:r6mb-2s2x t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:r6mb-2s2x t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:r6mb-2s2x t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year_reported | solicitation               | facility        | resource_type | state        | county        | new_renewable_capacity_mw | bid_capacity_mw | annual_contract_quantity_mwh | contract_duration_years | project_status | 
| ============= | ========================== | =============== | ============= | ============ | ============= | ========================= | =============== | ============================ | ======================= | ============== | 
| 2005          | 1st Main Tier Solicitation | Spier Falls     | Hydro         | New York     | not available | 0.8                       |                 | 3,115.00                     | 10                      | not available  | 
| 2005          | 1st Main Tier Solicitation | Higley Falls    | Hydro         | New York     | not available | 2.2                       |                 | 8,917.00                     | 1                       | not available  | 
| 2005          | 1st Main Tier Solicitation | Browns Falls    | Hydro         | New York     | not available | 0.2                       |                 | 978                          | 1                       | not available  | 
| 2005          | 1st Main Tier Solicitation | Maple Ridge     | Wind          | New York     | not available | 231                       |                 | 679,927.00                   | 10                      | not available  | 
| 2005          | 1st Main Tier Solicitation | Jersey-Atlantic | Wind          | New Jersey   | not available | 7.5                       |                 | 4,895.00                     | 10                      | not available  | 
| 2005          | 1st Main Tier Solicitation | Criterion       | Wind          | Maryland     | not available | 50                        |                 | 64,036.00                    | 4                       | not available  | 
| 2005          | 1st Main Tier Solicitation | Bear Creek      | Wind          | Pennsylvania | not available | 22                        |                 | 59,743.00                    | 4                       | not available  | 
| 2006          | 1st Main Tier Solicitation | Spier Falls     | Hydro         | New York     | not available | 0.8                       | 0.8             | 3,582.30                     | 10                      | not available  | 
| 2006          | 1st Main Tier Solicitation | Higley Falls    | Hydro         | New York     | not available |                           |                 | 10,254.60                    | 1                       | not available  | 
| 2006          | 1st Main Tier Solicitation | Browns Falls    | Hydro         | New York     | not available |                           |                 | 1,124.70                     | 1                       | not available  | 
```