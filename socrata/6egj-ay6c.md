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
| Category | Utilities and City Services |
| Tags | solar for schools, solar, solar energy, solar power, energy conservation |
| Created | 2016-09-20T20:07:28Z |
| Publication Date | 2016-10-14T18:30:13Z |

## Description

Austin Energy launched its Solar for Schools Program in 2006 to promote the use of solar energy and to educate students on the benefits of solar power. The program was funded by the utility, the State Energy Conservation Office, and the U.S. Department of Energy. The Solar for Schools program ended in FY2012. Go to austinenergy.com/go/solar to learn more about solar solutions from Austin Energy.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag     | school_name                     | School Name                       | text      | text        |
| Yes      | series tag     | school_district                 | School District                   | text      | text        |
| Yes      | time           | date_completed                  | Date Completed                    | number    | number      |
| Yes      | series tag     | source_of_grant                 | Source of Grant                   | text      | text        |
| Yes      | numeric metric | estimated_ae_cost               | Estimated AE Cost ($)             | money     | money       |
| Yes      | numeric metric | estimated_grant_funds           | Estimated Grant Funds ($)         | money     | money       |
| Yes      | numeric metric | estimated_total_cost            | Estimated Total Cost ($)          | money     | money       |
| Yes      | numeric metric | system_size_dc_kw               | System Size (DC kW)               | number    | number      |
| Yes      | numeric metric | estimated_annual_production_kwh | Estimated Annual Production (kWh) | number    | number      |
```

## Time Field

```ls
Value = date_completed
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6egj-ay6c d:2006-01-01T00:00:00.000Z t:school_district=Austin t:school_name="Cunningham Elementary" t:source_of_grant=SECO m:estimated_total_cost=44205.56 m:estimated_ae_cost=35114.65 m:estimated_grant_funds=9090.91 m:estimated_annual_production_kwh=5450 m:system_size_dc_kw=3.4

series e:6egj-ay6c d:2006-01-01T00:00:00.000Z t:school_district=Austin t:school_name="Bedichek Middle School" t:source_of_grant=SECO m:estimated_total_cost=44205.56 m:estimated_ae_cost=35114.65 m:estimated_grant_funds=9090.91 m:estimated_annual_production_kwh=5450 m:system_size_dc_kw=3.4

series e:6egj-ay6c d:2006-01-01T00:00:00.000Z t:school_district=Austin t:school_name="Blanton Elementary School" t:source_of_grant=SECO m:estimated_total_cost=44205.56 m:estimated_ae_cost=35114.65 m:estimated_grant_funds=9090.91 m:estimated_annual_production_kwh=5450 m:system_size_dc_kw=3.4
```

## Meta Commands

```ls
metric m:estimated_ae_cost p:double l:"Estimated AE Cost ($)" d:"includes $35,304.25 change order note: Modules and Inverters were donated for Maplewood, Brykerwoods, and Kealing" t:dataTypeName=money

metric m:estimated_grant_funds p:double l:"Estimated Grant Funds ($)" d:"includes $35,304.25 change order. Modules and Inverters were donated for Maplewood, Brykerwoods, and Kealing" t:dataTypeName=money

metric m:estimated_total_cost p:double l:"Estimated Total Cost ($)" d:"includes $35,304.25 change order. Modules and Inverters were donated for Maplewood, Brykerwoods, and Kealing" t:dataTypeName=money

metric m:system_size_dc_kw p:float l:"System Size (DC kW)" t:dataTypeName=number

metric m:estimated_annual_production_kwh p:integer l:"Estimated Annual Production (kWh)" t:dataTypeName=number

entity e:6egj-ay6c l:"Solar For Schools" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/6egj-ay6c

property e:6egj-ay6c t:meta.view d:2017-09-25T07:28:15.825Z v:averageRating=0 v:name="Solar For Schools" v:attribution="Austin Energy" v:id=6egj-ay6c v:category="Utilities and City Services"

property e:6egj-ay6c t:meta.view.license d:2017-09-25T07:28:15.825Z v:name="Public Domain"

property e:6egj-ay6c t:meta.view.owner d:2017-09-25T07:28:15.825Z v:displayName="Sarah Lambert" v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:id=c433-zrb5 v:screenName="Sarah Lambert" v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB

property e:6egj-ay6c t:meta.view.tableauthor d:2017-09-25T07:28:15.825Z v:displayName="Sarah Lambert" v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:id=c433-zrb5 v:screenName="Sarah Lambert" v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB
```

## Top Records

```ls
| school_name                    | school_district | date_completed | source_of_grant | estimated_ae_cost | estimated_grant_funds | estimated_total_cost | system_size_dc_kw | estimated_annual_production_kwh | 
| ============================== | =============== | ============== | =============== | ================= | ===================== | ==================== | ================= | =============================== | 
| Cunningham Elementary          | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| Bedichek Middle School         | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| Blanton Elementary School      | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| Garza Independence High School | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| Martin Middle School           | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| Murchison Middle School        | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| O. Henry Middle School         | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| Davis Elementary               | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| Zilker Elementary              | Austin          | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
| Pond Springs Elementary        | Round Rock      | 2006           | SECO            | 35114.65          | 9090.91               | 44205.56             | 3.4               | 5450                            | 
```