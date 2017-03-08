# LADWP Solar Incentive Program

## Dataset

* [Dataset URL](https://data.lacity.org/api/views/2yrw-q8tw/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/ladwp-solar-incentive-program-b0ebd)
* [Metadata URL](https://data.lacity.org/api/views/2yrw-q8tw)
* Id = 2yrw-q8tw
* Name = LADWP Solar Incentive Program
* Attribution = LADWP
* [Attribution Link](https://www.ladwp.com/ladwp/faces/ladwp/commercial/c-gogreen/c-gg-installsolar?_afrLoop=487268705452986&_afrWindowMode=0&_afrWindowId=16vdo6czx2_1#%40%3F_afrWindowId%3D16vdo6czx2_1%26_afrLoop%3D487...)
* Category = A Livable and Sustainable City
* Tags = [local solar, sip]
* Created = 2014-05-14T00:01:26Z
* Publication Date = 2017-02-21T22:04:12Z
* Rows Updated = 2017-02-21T22:03:24Z

## Description

Installed Capacity from Solar Incentive Program (Kilowatts).  The program offers customers an incentive to offset the cost of installing a solar rooftop system on their home or business.  LADWP has been helping customers to go solar since 1999.

## Columns

```ls
| Name                                                      | Field Name                                                    | Data Type | Render Type | Schema Type    | Included | 
| ========================================================= | ============================================================= | ========= | =========== | ============== | ======== | 
| updated_at                                                | :updated_at                                                   | meta_data | meta_data   | time           | No       | 
| Quarter-Fiscal Year                                       | quarter_fiscalyear                                            | text      | text        | series tag     | Yes      | 
| Solar Incentive Program Cumulative Installed Capacity(kW) | installed_capacity_from_solar_incentive_program_in_quarter_kw | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:2yrw-q8tw d:2017-02-21T22:03:21.000Z t:quarter_fiscalyear="Q1 FY08" m:installed_capacity_from_solar_incentive_program_in_quarter_kw=10901.66

series e:2yrw-q8tw d:2017-02-21T22:03:21.000Z t:quarter_fiscalyear="Q2 FY08" m:installed_capacity_from_solar_incentive_program_in_quarter_kw=11316.87

series e:2yrw-q8tw d:2017-02-21T22:03:21.000Z t:quarter_fiscalyear="Q3 FY08" m:installed_capacity_from_solar_incentive_program_in_quarter_kw=11938.39
```

## Meta Commands

```ls
metric m:installed_capacity_from_solar_incentive_program_in_quarter_kw l:"Solar Incentive Program Cumulative Installed Capacity(kW)" d:"Cumulative Installed Capacity for Solar Incentive Program" t:dataTypeName=number

entity e:2yrw-q8tw l:"LADWP Solar Incentive Program" t:attribution=LADWP t:url=https://data.lacity.org/api/views/2yrw-q8tw

property e:2yrw-q8tw t:meta.view d:2017-03-07T20:26:44.785Z v:id=2yrw-q8tw v:category="A Livable and Sustainable City" v:attributionLink="https://www.ladwp.com/ladwp/faces/ladwp/commercial/c-gogreen/c-gg-installsolar?_afrLoop=487268705452986&_afrWindowMode=0&_afrWindowId=16vdo6czx2_1#%40%3F_afrWindowId%3D16vdo6czx2_1%26_afrLoop%3D487268705452986%26_afrWindowMode%3D0%26_adf.ctrl-state%3D16vdo6czx2_49" v:averageRating=0 v:name="LADWP Solar Incentive Program" v:attribution=LADWP

property e:2yrw-q8tw t:meta.view.license d:2017-03-07T20:26:44.785Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:2yrw-q8tw t:meta.view.owner d:2017-03-07T20:26:44.785Z v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"

property e:2yrw-q8tw t:meta.view.tableauthor d:2017-03-07T20:26:44.785Z v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```