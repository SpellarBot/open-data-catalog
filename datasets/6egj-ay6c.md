# Solar For Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solar-for-schools) |
| Metadata | [Link](https://data.austintexas.gov/api/views/6egj-ay6c) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/6egj-ay6c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/6egj-ay6c/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 6egj-ay6c |
| Name | Solar For Schools |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | solar for schools, solar, solar energy, solar power, energy conservation |
| Created | 2016-09-20T20:07:28Z |
| Publication Date | 2016-10-14T18:30:13Z |
| Rows Updated | 2016-10-14T18:30:10Z |

## Description

Austin Energy's Solar for Schools Program was officially launched in 2006 to promote the use of solar energy and to educate students on the benefits of solar power. The program was funded by the utility, the State Energy Conservation Office, and the U.S. Department of Energy. Since the program?s inception, Austin Energy has contributed $1.1 million to help build 47 solar installations at schools in districts served by Austin Energy. The estimated energy savings for those 47 schools is 209,579 kWh annually -- electricity sufficient to power 16 average-sized homes in Austin. These arrays are located in school districts within the Austin Energy service territory.  The Solar for Schools program ended in FY2012.

Modules and Inverters were donated for Maplewood, Brykerwoods, and Kealing

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                        | meta_data | meta_data   |
| Yes      | series tag     | school_name                     | School Name                       | text      | text        |
| Yes      | series tag     | school_district                 | School District                   | text      | text        |
| Yes      | numeric metric | date_completed                  | Date Completed                    | number    | number      |
| Yes      | series tag     | source_of_grant                 | Source of Grant                   | text      | text        |
| Yes      | numeric metric | estimated_ae_cost               | Estimated AE Cost ($)             | money     | money       |
| Yes      | numeric metric | estimated_grant_funds           | Estimated Grant Funds ($)         | money     | money       |
| Yes      | numeric metric | estimated_total_cost            | Estimated Total Cost ($)          | money     | money       |
| Yes      | numeric metric | system_size_dc_kw               | System Size (DC kW)               | number    | number      |
| Yes      | numeric metric | estimated_annual_production_kwh | Estimated Annual Production (kWh) | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6egj-ay6c d:2016-09-20T20:07:30.000Z t:school_name="Cunningham Elementary" t:source_of_grant=SECO t:school_district=Austin m:date_completed=2006 m:estimated_total_cost=44205.56 m:system_size_dc_kw=3.4 m:estimated_ae_cost=35114.65 m:estimated_annual_production_kwh=5450 m:estimated_grant_funds=9090.91

series e:6egj-ay6c d:2016-09-20T20:07:30.000Z t:school_name="Bedichek Middle School" t:source_of_grant=SECO t:school_district=Austin m:date_completed=2006 m:estimated_total_cost=44205.56 m:system_size_dc_kw=3.4 m:estimated_ae_cost=35114.65 m:estimated_annual_production_kwh=5450 m:estimated_grant_funds=9090.91

series e:6egj-ay6c d:2016-09-20T20:07:30.000Z t:school_name="Blanton Elementary School" t:source_of_grant=SECO t:school_district=Austin m:date_completed=2006 m:estimated_total_cost=44205.56 m:system_size_dc_kw=3.4 m:estimated_ae_cost=35114.65 m:estimated_annual_production_kwh=5450 m:estimated_grant_funds=9090.91
```

## Meta Commands

```ls
metric m:date_completed p:integer l:"Date Completed" t:dataTypeName=number

metric m:system_size_dc_kw l:"System Size (DC kW)" t:dataTypeName=number

metric m:estimated_annual_production_kwh p:integer l:"Estimated Annual Production (kWh)" t:dataTypeName=number

entity e:6egj-ay6c l:"Solar For Schools" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/6egj-ay6c

property e:6egj-ay6c t:meta.view v:id=6egj-ay6c v:category=Utility v:averageRating=0 v:name="Solar For Schools" v:attribution="Austin Energy"

property e:6egj-ay6c t:meta.view.license v:name="Public Domain"

property e:6egj-ay6c t:meta.view.owner v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"

property e:6egj-ay6c t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```