# Solar Photovoltaic (PV) Incentive Program Completed Projects by City and Contractor: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solar-photovoltaic-pv-incentive-program-completed-projects-by-city-and-contractor-beginnin) |
| Metadata | [Link](https://data.ny.gov/api/views/3pzs-2zsk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/3pzs-2zsk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/3pzs-2zsk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 3pzs-2zsk |
| Name | Solar Photovoltaic (PV) Incentive Program Completed Projects by City and Contractor: Beginning 2010 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | kwh, kw, solar photovoltaic, pv |
| Created | 2014-11-17T16:17:08Z |
| Publication Date | 2015-07-29T22:02:22Z |

## Description

The Solar Photovoltaic (PV) Incentive Program Completed Projects by City and Contractor Dataset provides market insight into the volume of work and photovoltaic (PV) capacity installed in New York State annually, by city and contractor, beginning August 2010 under the New York State Energy Research and Development Authority (NYSERDA)?s NY-Sun Solar Electric Incentive Program Opportunity Notice (PON) 2112.The dataset includes the following data points: Project Install Year, Contractor, County, City, Project Count by City, Project Cost, NYSERDA Incentives, Kilowatt Capacity, Expected Annual Kilowatt Hour Production, and NYSERDA Solicitation.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | time           | project_install_year           | Project Install Year           | number    | number      |
| Yes      | series tag     | contractor                     | Contractor                     | text      | text        |
| Yes      | series tag     | county                         | County                         | text      | text        |
| Yes      | series tag     | city                           | City                           | text      | text        |
| Yes      | numeric metric | project_count_by_city          | Project Count by City          | number    | number      |
| Yes      | numeric metric | project_cost                   | Project Cost                   | number    | number      |
| Yes      | numeric metric | incentive_dollars              | Incentive, Dollars             | number    | number      |
| Yes      | numeric metric | total_nameplate_kw             | Total Nameplate KW             | number    | number      |
| Yes      | numeric metric | expected_kwh_annual_production | Expected KWh Annual Production | number    | number      |
| Yes      | series tag     | solicitation                   | Solicitation                   | text      | text        |
```

## Time Field

```ls
Value = project_install_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3pzs-2zsk d:2010-01-01T00:00:00.000Z t:county=Allegany t:contractor=Other t:solicitation="PON 2112" t:city=Other m:project_count_by_city=1 m:project_cost=34440 m:total_nameplate_kw=4.6 m:expected_kwh_annual_production=5399.66 m:incentive_dollars=8050

series e:3pzs-2zsk d:2010-01-01T00:00:00.000Z t:county=Cayuga t:contractor=Other t:solicitation="PON 2112" t:city=Other m:project_count_by_city=1 m:project_cost=39000 m:total_nameplate_kw=5.04 m:expected_kwh_annual_production=5916.15 m:incentive_dollars=8820

series e:3pzs-2zsk d:2010-01-01T00:00:00.000Z t:county=Columbia t:contractor=Other t:solicitation="PON 2112" t:city=Other m:project_count_by_city=1 m:project_cost=20198 m:total_nameplate_kw=2.53 m:expected_kwh_annual_production=2969.82 m:incentive_dollars=4427.5
```

## Meta Commands

```ls
metric m:project_count_by_city p:integer l:"Project Count by City" d:"Sum of projects installed in a year by a contractor in a given New York State city" t:dataTypeName=number

metric m:project_cost p:double l:"Project Cost" d:"The sum of the project cost in US dollars (USD)" t:dataTypeName=number

metric m:incentive_dollars p:float l:"Incentive, Dollars" d:"The sum of the NYSERDA project incentives in US dollars (USD)" t:dataTypeName=number

metric m:total_nameplate_kw p:float l:"Total Nameplate KW" d:"The sum of kilowatt (KW) capacity ratings of the installed photovoltaic equipment" t:dataTypeName=number

metric m:expected_kwh_annual_production p:double l:"Expected KWh Annual Production" d:"The sum of the expected annual electricity production as a result of the projects" t:dataTypeName=number

entity e:3pzs-2zsk l:"Solar Photovoltaic (PV) Incentive Program Completed Projects by City and Contractor: Beginning 2010" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/3pzs-2zsk

property e:3pzs-2zsk t:meta.view v:id=3pzs-2zsk v:category="Energy & Environment" v:averageRating=0 v:name="Solar Photovoltaic (PV) Incentive Program Completed Projects by City and Contractor: Beginning 2010" v:attribution="New York State Energy Research and Development Authority"

property e:3pzs-2zsk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:3pzs-2zsk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:3pzs-2zsk t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project_install_year | contractor | county   | city  | project_count_by_city | project_cost | incentive_dollars | total_nameplate_kw | expected_kwh_annual_production | solicitation | 
| ==================== | ========== | ======== | ===== | ===================== | ============ | ================= | ================== | ============================== | ============ | 
| 2010                 | Other      | Allegany | Other | 1                     | 34440        | 8050              | 4.6                | 5399.66                        | PON 2112     | 
| 2010                 | Other      | Cayuga   | Other | 1                     | 39000        | 8820              | 5.04               | 5916.15                        | PON 2112     | 
| 2010                 | Other      | Columbia | Other | 1                     | 20198        | 4427.5            | 2.53               | 2969.82                        | PON 2112     | 
| 2010                 | Other      | Dutchess | Other | 4                     | 163678       | 45080             | 25.76              | 30238.11                       | PON 2112     | 
| 2010                 | Other      | Erie     | Other | 2                     | 70272        | 21070             | 12.24              | 14367.8                        | PON 2112     | 
| 2010                 | Other      | Essex    | Other | 2                     | 154240.4     | 42665             | 24.38              | 28618.22                       | PON 2112     | 
| 2010                 | Other      | Franklin | Other | 1                     | 54325        | 12250             | 8.05               | 9449.41                        | PON 2112     | 
| 2010                 | Other      | Genesee  | Other | 1                     | 39888        | 10867.5           | 6.21               | 7289.55                        | PON 2112     | 
| 2010                 | Other      | Herkimer | Other | 1                     | 34199.86     | 11970             | 6.84               | 8029.07                        | PON 2112     | 
| 2010                 | Other      | Monroe   | Other | 2                     | 58386        | 15487.5           | 8.85               | 10388.49                       | PON 2112     | 
```