# New York Power Authority Net Generation (MWh) Produced by Facility: Beginning 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-power-authority-net-generation-mwh-produced-by-facility-beginning-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/isux-jnrn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/isux-jnrn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/isux-jnrn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | isux-jnrn |
| Name | New York Power Authority Net Generation (MWh) Produced by Facility: Beginning 2013 |
| Attribution | New York Power Authority |
| Category | Energy & Environment |
| Tags | energy, power, generation |
| Created | 2013-03-05T19:24:36Z |
| Publication Date | 2016-09-19T18:29:31Z |

## Description

The New York Power Authority is America's largest state power organization, with 16 generating facilities and more than 1,400 circuit-miles of transmission lines.The data provided includes megawatt-hours produced net of station service by each NYPA facility.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type | Render Type |
| ======== | ============== | ================== | ==================== | ========= | =========== |
| Yes      | time           | year               | Year                 | number    | number      |
| Yes      | series tag     | nypa_facility_name | NYPA Facility Name   | text      | text        |
| Yes      | numeric metric | net_generation_mwh | Net Generation (MWh) | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:isux-jnrn d:2013-01-01T00:00:00.000Z t:nypa_facility_name="ST. LAWRENCE" m:net_generation_mwh=6700000

series e:isux-jnrn d:2013-01-01T00:00:00.000Z t:nypa_facility_name=NIAGARA m:net_generation_mwh=13000000

series e:isux-jnrn d:2013-01-01T00:00:00.000Z t:nypa_facility_name=BLENHEIM-GILBOA m:net_generation_mwh=260000
```

## Meta Commands

```ls
metric m:net_generation_mwh p:integer l:"Net Generation (MWh)" d:"Net generation in megawatt-hours ** Pump storage facility is reported as Gross Generation in megawatt-hours" t:dataTypeName=number

entity e:isux-jnrn l:"New York Power Authority Net Generation (MWh) Produced by Facility: Beginning 2013" t:attribution="New York Power Authority" t:url=https://data.ny.gov/api/views/isux-jnrn

property e:isux-jnrn t:meta.view v:id=isux-jnrn v:category="Energy & Environment" v:averageRating=0 v:name="New York Power Authority Net Generation (MWh) Produced by Facility: Beginning 2013" v:attribution="New York Power Authority"

property e:isux-jnrn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:isux-jnrn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:isux-jnrn t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | nypa_facility_name       | net_generation_mwh | 
| ==== | ======================== | ================== | 
| 2013 | ST. LAWRENCE             | 6700000            | 
| 2013 | NIAGARA                  | 13000000           | 
| 2013 | BLENHEIM-GILBOA          | 260000             | 
| 2013 | RICHARD M. FLYNN         | 1200000            | 
| 2013 | SMALL HYDRO FACILITIES   | 140000             | 
| 2013 | SMALL CLEAN POWER PLANTS | 590000             | 
| 2013 | 500 MW                   | 3400000            | 
| 2014 | ST. LAWRENCE             | 7050000            | 
| 2014 | NIAGARA                  | 13680000           | 
| 2014 | BLENHEIM-GILBOA          | 380000             | 
```