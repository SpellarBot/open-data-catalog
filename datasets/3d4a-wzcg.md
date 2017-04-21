# Energy Efficiency Peak Demand Reduction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-efficiency-peak-demand-reduction) |
| Metadata | [Link](https://data.austintexas.gov/api/views/3d4a-wzcg) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/3d4a-wzcg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/3d4a-wzcg/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 3d4a-wzcg |
| Name | Energy Efficiency Peak Demand Reduction |
| Attribution | Austin Energy |
| Category | Utility |
| Tags | energy efficiency, demand, energy usage |
| Created | 2016-12-01T20:38:06Z |
| Publication Date | 2016-12-05T15:49:26Z |

## Description

Austin Energy's energy efficiency programs are designed to lower energy usage and reduce the amount of load on the electric system. Peak demand is the highest point of energy usage on any given day and typically occurs between the hours of 3 and 7 p.m.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | program        | Program        | text      | text        |
| Yes      | series tag     | customer_class | Customer Class | text      | text        |
| Yes      | numeric metric | 2007           | 2007           | number    | number      |
| Yes      | numeric metric | 2008           | 2008           | number    | number      |
| Yes      | numeric metric | 2009           | 2009           | number    | number      |
| Yes      | numeric metric | 2010           | 2010           | number    | number      |
| Yes      | numeric metric | 2011           | 2011           | number    | number      |
| Yes      | numeric metric | 2012           | 2012           | number    | number      |
| Yes      | numeric metric | 2013           | 2013           | number    | number      |
| Yes      | numeric metric | 2014           | 2014           | number    | number      |
| Yes      | numeric metric | 2015           | 2015           | number    | number      |
| Yes      | numeric metric | total          | Total          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3d4a-wzcg d:2016-12-05T15:47:32.000Z t:customer_class=Residential t:program="EES- Appliance Efficiency Program" m:2008=3.4 m:total=27.4 m:2009=3.4 m:2007=2.3 m:2013=2.5 m:2014=2.4 m:2015=2.1 m:2012=2.7 m:2011=4.7 m:2010=4.2

series e:3d4a-wzcg d:2016-12-05T15:47:32.000Z t:customer_class=Residential t:program="EES- Home Performance ES - Rebate" m:2008=4 m:total=34 m:2009=4.4 m:2007=3.1 m:2013=3.3 m:2014=2.9 m:2015=1.7 m:2012=4 m:2011=5.3 m:2010=5.3

series e:3d4a-wzcg d:2016-12-05T15:47:32.000Z t:customer_class=Residential t:program="EES- Home Performance ES - Loan" m:2008=0.4 m:total=3.2 m:2009=0.3 m:2007=0.5 m:2013=0.7 m:2014=0.8 m:2015=0.1 m:2012=0.1 m:2011=0.1 m:2010=0.2
```

## Meta Commands

```ls
metric m:2007 p:float l:2007 t:dataTypeName=number

metric m:2008 p:float l:2008 t:dataTypeName=number

metric m:2009 p:float l:2009 t:dataTypeName=number

metric m:2010 p:float l:2010 t:dataTypeName=number

metric m:2011 p:float l:2011 t:dataTypeName=number

metric m:2012 p:float l:2012 t:dataTypeName=number

metric m:2013 p:float l:2013 t:dataTypeName=number

metric m:2014 p:float l:2014 t:dataTypeName=number

metric m:2015 p:float l:2015 t:dataTypeName=number

metric m:total p:float l:Total t:dataTypeName=number

entity e:3d4a-wzcg l:"Energy Efficiency Peak Demand Reduction" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/3d4a-wzcg

property e:3d4a-wzcg t:meta.view v:id=3d4a-wzcg v:category=Utility v:averageRating=0 v:name="Energy Efficiency Peak Demand Reduction" v:attribution="Austin Energy"

property e:3d4a-wzcg t:meta.view.license v:name="Public Domain"

property e:3d4a-wzcg t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:3d4a-wzcg t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| :updated_at | program                           | customer_class | 2007 | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 2014 | 2015 | total | 
| =========== | ================================= | ============== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ===== | 
| 1480952852  | EES- Appliance Efficiency Program | Residential    | 2.3  | 3.4  | 3.4  | 4.2  | 4.7  | 2.7  | 2.5  | 2.4  | 2.1  | 27.4  | 
| 1480952852  | EES- Home Performance ES - Rebate | Residential    | 3.1  | 4.0  | 4.4  | 5.3  | 5.3  | 4.0  | 3.3  | 2.9  | 1.7  | 34.0  | 
| 1480952852  | EES- Home Performance ES - Loan   | Residential    | 0.5  | 0.4  | 0.3  | 0.2  | 0.1  | 0.1  | 0.7  | 0.8  | 0.1  | 3.2   | 
| 1480952852  | EES- Free Weatherization          | Residential    | 0.6  | 0.5  | 0.5  | 0.4  | 1.0  | 0.9  | 0.2  | 0.4  | 0.5  | 5.0   | 
| 1480952852  | EES- Clothes Washer Rebate        | Residential    | 0.1  | 0.0  | 0.0  | 0.1  | 0.0  | 0.0  | 0.0  | 0.0  | 0.0  | 0.3   | 
| 1480952852  | EES- Refrigerator Recycling       | Residential    | 0.7  | 0.8  | 0.7  | 0.7  | 0.5  | 0.4  | 0.4  | 0.4  | 0.3  | 4.9   | 
| 1480952852  | EES- Compact Fluorescent Lighting | Residential    | 0.9  | 1.0  | 2.2  | 0.0  | 0.0  | 0.0  | 0.0  | 0.0  | 0.1  | 4.3   | 
| 1480952852  | GB- Residential Ratings           | Residential    | 0.8  | 0.9  | 0.6  | 0.6  | 0.3  | 0.2  | 0.4  | 0.5  | 0.5  | 4.8   | 
| 1480952852  | GB- Residential Energy Code       | Residential    | 6.9  | 4.9  | 2.9  | 3.2  | 3.0  | 3.9  | 4.5  | 8.2  | 8.6  | 46.0  | 
| 1480952852  | EES- Discontinued Programs        | Residential    | 0.2  | 0.0  | 0.0  | 0.0  | 0.0  | 0.0  | 0.0  | 0.0  | 0.0  | 0.2   | 
```