# Main Tier Project Status for Renewable Portfolio Standard: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/main-tier-project-status-for-renewable-portfolio-standard-beginning-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/ykd6-2pvd) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ykd6-2pvd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ykd6-2pvd/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ykd6-2pvd |
| Name | Main Tier Project Status for Renewable Portfolio Standard: Beginning 2007 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | mw, wind, hydro, biomass, biogas |
| Created | 2013-02-21T21:45:55Z |
| Publication Date | 2016-04-27T22:00:57Z |

## Description

The goal of the Renewable Portfolio Standard (RPS) is to increase the proportion of renewable energy used by New York Consumers from the 2003 19.3% (baseline resources) to at least 30% by the end of 2015.The Main Tier Project Status for Renewable Portfolio Standard data set contains annual summary information, as required by the New York State Public Service Commission and reported in the annual New York State Renewable Portfolio Standard Performance Reports 2005 to 2011, on the number of MW operating, the number of MW in development/construction, number of facilities operating and number of facilities in development/construction for active RPS Main Tier wind, hydroelectric, biomass, and biogas projects.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | time           | year_reported                      | Year Reported                      | number    | number      |
| Yes      | series tag     | resource_type                      | Resource Type                      | text      | text        |
| Yes      | numeric metric | mw_operating                       | MW Operating                       | number    | number      |
| Yes      | numeric metric | mw_in_development_construction     | MW In Development/Construction     | number    | number      |
| Yes      | numeric metric | total_mw                           | Total MW                           | number    | number      |
| Yes      | numeric metric | number_operating                   | Number Operating                   | number    | number      |
| Yes      | numeric metric | number_in_development_construction | Number In Development/Construction | number    | number      |
| Yes      | series tag     | total_number                       | Total Number                       | text      | number      |
```

## Time Field

```ls
Value = year_reported
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ykd6-2pvd d:2015-01-01T00:00:00.000Z t:resource_type=Wind t:total_number=24 m:mw_operating=1672.9 m:mw_in_development_construction=278 m:number_in_development_construction=5 m:total_mw=1950.9 m:number_operating=19

series e:ykd6-2pvd d:2015-01-01T00:00:00.000Z t:resource_type=Hydroelectric t:total_number=26 m:mw_operating=51.6 m:mw_in_development_construction=0.56 m:number_in_development_construction=1 m:total_mw=52.1 m:number_operating=25

series e:ykd6-2pvd d:2015-01-01T00:00:00.000Z t:resource_type=Biomass t:total_number=2 m:mw_operating=69.3 m:mw_in_development_construction=0 m:number_in_development_construction=0 m:total_mw=69.3 m:number_operating=2
```

## Meta Commands

```ls
metric m:mw_operating p:float l:"MW Operating" d:"Megawatts of renewable capacity from projects in operation. Wind, Hydroelectric, Biomass, and Biogas." t:dataTypeName=number

metric m:mw_in_development_construction p:float l:"MW In Development/Construction" d:"Megawatts of renewable capacity from projects currently under development and/or construction. Wind, Hydroelectric, Biomass, and Biogas." t:dataTypeName=number

metric m:total_mw p:float l:"Total MW" d:"Total megawatts of renewable capacity from projects in operation and currently under development and/or construction." t:dataTypeName=number

metric m:number_operating p:integer l:"Number Operating" d:"Number of renewable capacity projects in operation. Wind, Hydroelectric, Biomass, and Biogas." t:dataTypeName=number

metric m:number_in_development_construction p:integer l:"Number In Development/Construction" d:"Number of renewable capacity projects currently under development and/or construction. Wind, Hydroelectric, Biomass, and Biogas." t:dataTypeName=number

entity e:ykd6-2pvd l:"Main Tier Project Status for Renewable Portfolio Standard:  Beginning 2007" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/ykd6-2pvd

property e:ykd6-2pvd t:meta.view v:id=ykd6-2pvd v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Publications/Program-Planning-Status-and-Evaluation-Reports/Renewable-Portfolio-Standard-Reports.aspx v:averageRating=0 v:name="Main Tier Project Status for Renewable Portfolio Standard:  Beginning 2007" v:attribution="New York State Energy Research and Development Authority"

property e:ykd6-2pvd t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ykd6-2pvd t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ykd6-2pvd t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year_reported | resource_type | mw_operating | mw_in_development_construction | total_mw | number_operating | number_in_development_construction | total_number | 
| ============= | ============= | ============ | ============================== | ======== | ================ | ================================== | ============ | 
| 2015          | Wind          | 1672.9       | 278                            | 1950.9   | 19               | 5                                  | 24           | 
| 2015          | Hydroelectric | 51.6         | 0.56                           | 52.1     | 25               | 1                                  | 26           | 
| 2015          | Biomass       | 69.3         | 0                              | 69.3     | 2                | 0                                  | 2            | 
| 2015          | Biogas        | 60.1         | 2.2                            | 62.3     | 10               | 2                                  | 12           | 
| 2015          | Fuel Cell     | 1.3          | 0.8                            | 2.1      | 3                | 1                                  | 4            | 
| 2014          | Wind          | 1672.9       | 178                            | 1850.9   | 19               | 4                                  | 23           | 
| 2014          | Hydroelectric | 51.66        | 0                              | 51.66    | 25               | 0                                  | 25           | 
| 2014          | Biomass       | 69.26        | 0                              | 69.26    | 2                | 0                                  | 2            | 
| 2014          | Biogas        | 60.1         | 2.15                           | 62.25    | 10               | 2                                  | 12           | 
| 2014          | Fuel Cell     | 0            | 1.26                           | 1.26     | 0                | 3                                  | 3            | 
```