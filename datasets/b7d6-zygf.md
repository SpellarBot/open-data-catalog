# Long-term Industry Projections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/long-term-industry-projections) |
| Metadata | [Link](https://data.ny.gov/api/views/b7d6-zygf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/b7d6-zygf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/b7d6-zygf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | b7d6-zygf |
| Name | Long-term Industry Projections |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | industry, industry forecast, industry outlook, employment, employment projections |
| Created | 2014-09-03T15:42:13Z |
| Publication Date | 2015-11-05T16:17:17Z |

## Description

Long-term Industry Projections for a 10 year time horizon are provided for the state and 10 labor market regions to provide individuals and organizations with an industry outlook.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                               | Data Type | Render Type |
| ======== | ============== | ================== | ================================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | area               | Area                               | text      | text        |
| Yes      | series tag     | period             | Period                             | text      | text        |
| Yes      | series tag     | industry_code      | Industry Code                      | text      | text        |
| Yes      | series tag     | industry_title     | Industry Title                     | text      | text        |
| Yes      | numeric metric | base_year          | Base Year Employment Estimate      | number    | number      |
| Yes      | numeric metric | projected_year     | Projected Year Employment Estimate | number    | number      |
| Yes      | numeric metric | net_change         | Net Change                         | number    | number      |
| Yes      | numeric metric | annual_growth_rate | Growth Rate                        | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:b7d6-zygf d:2015-11-04T15:05:35.000Z t:area="New York State" t:industry_title=Total t:industry_code=0000000 t:period="2012 - 2022" m:base_year=9448100 m:net_change=1048210 m:annual_growth_rate=11.1 m:projected_year=10496310

series e:b7d6-zygf d:2015-11-04T15:05:35.000Z t:area="New York State" t:industry_title="Self Employed and Unpaid Family Workers" t:industry_code=000671 t:period="2012 - 2022" m:base_year=565060 m:net_change=19510 m:annual_growth_rate=3.5 m:projected_year=584570

series e:b7d6-zygf d:2015-11-04T15:05:35.000Z t:area="New York State" t:industry_title="Financial Activities" t:industry_code='102300 t:period="2012 - 2022" m:base_year=683490 m:net_change=4870 m:annual_growth_rate=0.7 m:projected_year=688360
```

## Meta Commands

```ls
metric m:base_year p:integer l:"Base Year Employment Estimate" d:"A numerical value representing a base year employment estimate for an industry." t:dataTypeName=number

metric m:projected_year p:integer l:"Projected Year Employment Estimate" d:"A numerical value representing the projected year employment estimate for an industry." t:dataTypeName=number

metric m:net_change p:integer l:"Net Change" d:"Numeric change in employment between the projected estimate and the base estimate." t:dataTypeName=number

metric m:annual_growth_rate p:float l:"Growth Rate" d:"A value representing the percentage growth. This value is calculated by dividing the projected year by the base year." t:dataTypeName=percent

entity e:b7d6-zygf l:"Long-term Industry Projections" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/b7d6-zygf

property e:b7d6-zygf t:meta.view v:id=b7d6-zygf v:category="Economic Development" v:attributionLink=http://labor.ny.gov/stats/lsproj.shtm v:averageRating=0 v:name="Long-term Industry Projections" v:attribution="New York State Department of Labor"

property e:b7d6-zygf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:b7d6-zygf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:b7d6-zygf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | area           | period      | industry_code | industry_title                                  | base_year | projected_year | net_change | annual_growth_rate | 
| =========== | ============== | =========== | ============= | =============================================== | ========= | ============== | ========== | ================== | 
| 1446649535  | New York State | 2012 - 2022 | 0000000       | Total                                           | 9448100   | 10496310       | 1048210    | 11.10              | 
| 1446649535  | New York State | 2012 - 2022 | 000671        | Self Employed and Unpaid Family Workers         | 565060    | 584570         | 19510      | 3.50               | 
| 1446649535  | New York State | 2012 - 2022 | '102300       | Financial Activities                            | 683490    | 688360         | 4870       | 0.70               | 
| 1446649535  | New York State | 2012 - 2022 | '102400       | Professional and Business Services              | 1050460   | 1291890        | 241430     | 23.00              | 
| 1446649535  | New York State | 2012 - 2022 | '110000       | Agriculture, Forestry, Fishing and Hunting      | 32030     | 34260          | 2230       | 7.00               | 
| 1446649535  | New York State | 2012 - 2022 | '111000       | Crop Production                                 | 15090     | 14930          | -160       | -1.10              | 
| 1446649535  | New York State | 2012 - 2022 | '112000       | Animal Production                               | 12580     | 15250          | 2670       | 21.20              | 
| 1446649535  | New York State | 2012 - 2022 | '113000       | Forestry and Logging                            | 1570      | 1390           | -180       | -11.50             | 
| 1446649535  | New York State | 2012 - 2022 | '114000       | Fishing, Hunting and Trapping                   | 520       | 520            | 0          | 0.00               | 
| 1446649535  | New York State | 2012 - 2022 | '115000       | Support Activities for Agriculture and Forestry | 2270      | 2170           | -100       | -4.40              | 
```