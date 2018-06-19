# NYSTAR Regional Technology Development Centers Economic Impacts: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nystar-regional-technology-development-centers-economic-impacts-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/eza2-df93) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/eza2-df93/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/eza2-df93/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | eza2-df93 |
| Name | NYSTAR Regional Technology Development Centers Economic Impacts: Beginning 2009 |
| Attribution | Empire State Development Division of Science, Technology and Innovation (NYSTAR) |
| Category | Economic Development |
| Tags | high tech, economic development, manufacturing, nist, mep, rtdc |
| Created | 2014-02-24T18:52:10Z |
| Publication Date | 2016-03-02T15:12:25Z |

## Description

Economic Impacts of the 10 Division of Science, Technology and Innovation (NYSTAR) National Institute of Standards and Technology (NIST) Manufacturing Extension Partnership (MEP) Regional Technology Development Centers (RTDC).

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                       | Data Type | Render Type |
| ======== | ============== | ======================== | ========================== | ========= | =========== |
| Yes      | series tag     | abbreviation             | Abbreviation               | text      | text        |
| Yes      | series tag     | name                     | Center Name                | text      | text        |
| Yes      | series tag     | region                   | ESD Region                 | text      | text        |
| Yes      | time           | year                     | Year                       | number    | number      |
| Yes      | numeric metric | federal_funding          | Federal Funding            | money     | money       |
| Yes      | numeric metric | nys_funding              | NYS Funding                | money     | money       |
| Yes      | numeric metric | increased_sales          | Increased Sales            | money     | money       |
| Yes      | numeric metric | retained_sales           | Retained Sales             | money     | money       |
| Yes      | numeric metric | cost_savings             | Cost Savings               | money     | money       |
| Yes      | numeric metric | jobs_created             | Jobs Created               | number    | number      |
| Yes      | numeric metric | jobs_retained            | Jobs Retained              | number    | number      |
| Yes      | numeric metric | plant_equipment          | Plant Equipment            | money     | money       |
| Yes      | numeric metric | information_systems      | Information Systems        | money     | money       |
| Yes      | numeric metric | workforce_practices      | Workforce Practices        | money     | money       |
| Yes      | numeric metric | other_non_specific_areas | Other (Non-Specific) Areas | money     | money       |
| Yes      | numeric metric | investment_savings       | Investment Savings         | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:eza2-df93 d:2009-01-01T00:00:00.000Z t:region="Southern Tier" t:name="Alliance for Manufacturing and Technology" t:abbreviation=AM&T m:workforce_practices=678980 m:retained_sales=123690368 m:nys_funding=268000 m:plant_equipment=2606000 m:increased_sales=38501000 m:federal_funding=416000 m:other_non_specific_areas=155000 m:jobs_created=146 m:information_systems=909000 m:cost_savings=2860145 m:jobs_retained=587 m:investment_savings=1585000

series e:eza2-df93 d:2009-01-01T00:00:00.000Z t:region="Capital Region" t:name="Center for Economic Growth" t:abbreviation=CEG m:workforce_practices=560790 m:retained_sales=8625000 m:nys_funding=268000 m:plant_equipment=13027000 m:increased_sales=12325000 m:federal_funding=413000 m:other_non_specific_areas=262000 m:jobs_created=153 m:information_systems=625000 m:cost_savings=5543387 m:jobs_retained=321 m:investment_savings=12335925

series e:eza2-df93 d:2009-01-01T00:00:00.000Z t:region="Central New York" t:name="Central New York Technology Development Organization" t:abbreviation=CNYTDO m:workforce_practices=489000 m:retained_sales=18343000 m:nys_funding=227000 m:plant_equipment=11531000 m:increased_sales=5750000 m:federal_funding=352000 m:other_non_specific_areas=0 m:jobs_created=70 m:information_systems=97500 m:cost_savings=2505000 m:jobs_retained=157 m:investment_savings=338600
```

## Meta Commands

```ls
metric m:federal_funding p:double l:"Federal Funding" d:"National Iinstiture of Standards and Technology Manufacturing Extension Partnership (NIST MEP) provides $5,468,093 to NYS for the RTDC (NYMEP) program. This funding is allocated to the 10 centers through a formula taking into account number of small & medium sized manufacturers in the region, number of employees at these companies and economic impacts ? on a three year rolling average." t:dataTypeName=money

metric m:nys_funding p:double l:"NYS Funding" d:"NYS provides $3,773,000 in funding for the RTDC program. This funding is allocated in the same manner as the federal funding ? through a formula taking into account number of small & medium sized manufacturers in the region, number of employees at these companies and economic impacts ? on a three year rolling average." t:dataTypeName=money

metric m:increased_sales p:double l:"Increased Sales" d:"Increased sales are the result of introduction of new products, improved products, new markets, etc. realized through services provided." t:dataTypeName=money

metric m:retained_sales p:double l:"Retained Sales" d:"Retained sales realized by services provided. that would are the result of introduction of new products, improved products, new markets, etc." t:dataTypeName=money

metric m:cost_savings p:double l:"Cost Savings" d:"Cost savings that typically realized after services are provided include: labor, materials, energy, overhead, etc." t:dataTypeName=money

metric m:jobs_created p:integer l:"Jobs Created" d:"Credited jobs are permanent, full-time positions. Credited job creation is the result of services provided that create new markets, new product line(s), business expansion, etc." t:dataTypeName=number

metric m:jobs_retained p:integer l:"Jobs Retained" d:"Jobs may be at risk because of high operating costs, incentives offered by another location, production contractions, etc." t:dataTypeName=number

metric m:plant_equipment p:double l:"Plant Equipment" d:"Companies report on investments made in Plant Equipment as a result of the services provided." t:dataTypeName=money

metric m:information_systems p:double l:"Information Systems" d:"Companies report on investments made in Information Systems as a result of the services provided." t:dataTypeName=money

metric m:workforce_practices p:double l:"Workforce Practices" d:"Companies report on investments made in Workforce Practices as a result of the services provided" t:dataTypeName=money

metric m:other_non_specific_areas p:double l:"Other (Non-Specific) Areas" d:"Companies report on investments made in other areas as a result of the services provided" t:dataTypeName=money

metric m:investment_savings p:double l:"Investment Savings" d:"Companies report on investments savings or cost avoidance as a result of the services provided" t:dataTypeName=money

entity e:eza2-df93 l:"NYSTAR Regional Technology Development Centers Economic Impacts: Beginning 2009" t:attribution="Empire State Development Division of Science, Technology and Innovation (NYSTAR)" t:url=https://data.ny.gov/api/views/eza2-df93

property e:eza2-df93 t:meta.view v:id=eza2-df93 v:category="Economic Development" v:attributionLink=http://esd.ny.gov/nystar/ v:averageRating=0 v:name="NYSTAR Regional Technology Development Centers Economic Impacts: Beginning 2009" v:attribution="Empire State Development Division of Science, Technology and Innovation (NYSTAR)"

property e:eza2-df93 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:eza2-df93 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:eza2-df93 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| abbreviation | name                                                                     | region           | year | federal_funding | nys_funding | increased_sales | retained_sales | cost_savings | jobs_created | jobs_retained | plant_equipment | information_systems | workforce_practices | other_non_specific_areas | investment_savings | 
| ============ | ======================================================================== | ================ | ==== | =============== | =========== | =============== | ============== | ============ | ============ | ============= | =============== | =================== | =================== | ======================== | ================== | 
| AM&T         | Alliance for Manufacturing and Technology                                | Southern Tier    | 2009 | 416000.00       | 268000.00   | 38501000.00     | 123690368.00   | 2860145.00   | 146          | 587           | 2606000.00      | 909000.00           | 678980.00           | 155000.00                | 1585000.00         | 
| CEG          | Center for Economic Growth                                               | Capital Region   | 2009 | 413000.00       | 268000.00   | 12325000.00     | 8625000.00     | 5543387.00   | 153          | 321           | 13027000.00     | 625000.00           | 560790.00           | 262000.00                | 12335925.00        | 
| CNYTDO       | Central New York Technology Development Organization                     | Central New York | 2009 | 352000.00       | 227000.00   | 5750000.00      | 18343000.00    | 2505000.00   | 70           | 157           | 11531000.00     | 97500.00            | 489000.00           | 0.00                     | 338600.00          | 
| CITEC        | Council for International Trade, Technology, Education and Communication | North Country    | 2009 | 264000.00       | 170000.00   | 5914628.00      | 2810000.00     | 2370360.00   | 38           | 91            | 12796000.00     | 305000.00           | 184000.00           | 11565500.00              | 223000.00          | 
| HTR          | High Tech Rochester, Inc.                                                | Finger Lakes     | 2009 | 554000.00       | 357000.00   | 7485000.00      | 11342000.00    | 8110000.00   | 115          | 316           | 6912924.00      | 882000.00           | 683600.00           | 1139000.00               | 1501000.00         | 
| HVTDC        | Hudson Valley Technology Development Center                              | Mid-Hudson       | 2009 | 465000.00       | 301000.00   | 10150000.00     | 6825001.00     | 3642001.00   | 85           | 274           | 4917000.00      | 770500.00           | 429000.00           | 1083500.00               | 205000.00          | 
| ITAC         | Industrial and Technology Assistance Corporation                         | New York City    | 2009 | 1324000.00      | 854000.00   | 45264600.00     | 64425000.00    | 27299916.00  | 398          | 557           | 25409850.00     | 2784286.00          | 2490091.00          | 4913940.00               | 15368807.00        | 
| Insyte       | Insyte Consulting                                                        | Western New York | 2009 | 579000.00       | 374000.00   | 19016524.00     | 14133152.00    | 6105900.00   | 92           | 358           | 12941000.00     | 1307500.00          | 976452.00           | 1740000.00               | 2307750.00         | 
| LIFT         | Long Island Forum for Technology                                         | Long Island      | 2009 | 816000.00       | 526000.00   | 5381000.00      | 2316000.00     | 8978000.00   | 29           | 220           | 3855000.00      | 313300.00           | 278501.00           | 165000.00                | 524000.00          | 
| MVATC        | Mohawk Valley Applied Technology Corporation                             | Mohawk Valley    | 2009 | 285093.00       | 182000.00   | 442000.00       | 385000.00      | 619000.00    | 2            | 6             | 520000.00       | 234000.00           | 70000.00            | 30000.00                 | 56500.00           | 
```