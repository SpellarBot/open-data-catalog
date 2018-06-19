# LADWP Power Supply Since 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-power-supply-since-2003-3d1fc) |
| Metadata | [Link](https://data.lacity.org/api/views/hmiy-sxh5) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/hmiy-sxh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/hmiy-sxh5/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | hmiy-sxh5 |
| Name | LADWP Power Supply Since 2003 |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | power supply, power content label |
| Created | 2014-05-23T22:29:30Z |
| Publication Date | 2017-02-24T22:35:19Z |

## Description

LADWP's Power Content Label certified by the California Energy Commission

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | energy_resources | ENERGY RESOURCES | text      | text        |
| Yes      | numeric metric | 2012             | 2015             | number    | text        |
| Yes      | numeric metric | 2011             | 2014             | number    | text        |
| Yes      | numeric metric | 2010             | 2013             | number    | text        |
| Yes      | numeric metric | 2009             | 2012             | number    | text        |
| Yes      | numeric metric | 2008             | 2011             | number    | text        |
| Yes      | numeric metric | 2007             | 2010             | number    | text        |
| Yes      | series tag     | 2006             | 2009             | text      | text        |
| Yes      | series tag     | 2005             | 2008             | text      | text        |
| Yes      | series tag     | 2004             | 2007             | text      | text        |
| Yes      | series tag     | 2003             | 2006             | text      | text        |
| Yes      | series tag     | 2005_2           | 2005             | text      | text        |
| Yes      | series tag     | 2004_2           | 2004             | text      | text        |
| Yes      | series tag     | 2003_2           | 2003             | text      | text        |
```

## Time Field

```ls
Value = 2003
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hmiy-sxh5 d:2003-01-01T00:00:00.000Z t:2005_2=0.06 t:2006=0.14 t:2004=0.06 t:2003_2=0.03 t:2005=0.08 t:2003=0.06 t:energy_resources="Eligible Renewable (sub-catagories below)" t:2004_2=0.03 m:2008=0.19 m:2009=0.2 m:2007=0.2 m:2012=0.21 m:2011=0.2 m:2010=0.23

series e:hmiy-sxh5 d:2003-01-01T00:00:00.000Z t:2005_2=0.01 t:2006=0.02 t:2004=0.01 t:2003_2=0.01 t:2005=0.01 t:2003=0.01 t:energy_resources="-- Biomass & waste" t:2004_2=0.01 m:2008=0.03 m:2009=0.05 m:2007=0.04 m:2012=0.04 m:2011=0.05 m:2010=0.06

series e:hmiy-sxh5 d:2003-01-01T00:00:00.000Z t:2005_2=<1% t:2006=0.01 t:2004=<1% t:2003_2=0.01 t:2005=<1% t:2003=<1% t:energy_resources="-- Geothermal" t:2004_2=0.01 m:2008=0 m:2009=0 m:2007=0.01 m:2012=0.02 m:2011=0.01 m:2010=0.01
```

## Meta Commands

```ls
metric m:2012 p:float l:2015 t:dataTypeName=number

metric m:2011 p:float l:2014 t:dataTypeName=number

metric m:2010 p:float l:2013 t:dataTypeName=number

metric m:2009 p:float l:2012 t:dataTypeName=number

metric m:2008 p:float l:2011 t:dataTypeName=number

metric m:2007 p:float l:2010 t:dataTypeName=number

entity e:hmiy-sxh5 l:"LADWP Power Supply Since 2003" t:attribution=LADWP t:url=https://data.lacity.org/api/views/hmiy-sxh5

property e:hmiy-sxh5 t:meta.view v:id=hmiy-sxh5 v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LADWP Power Supply Since 2003" v:attribution=LADWP

property e:hmiy-sxh5 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:hmiy-sxh5 t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:hmiy-sxh5 t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| energy_resources                          | 2012 | 2011 | 2010 | 2009 | 2008 | 2007 | 2006 | 2005 | 2004 | 2003 | 2005_2              | 2004_2 | 2003_2 | 
| ========================================= | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | =================== | ====== | ====== | 
| Eligible Renewable (sub-catagories below) | 0.21 | 0.2  | 0.23 | 0.2  | 0.19 | 0.2  | 0.14 | 0.08 | 0.06 | 0.06 | 0.06                | 0.03   | 0.03   | 
| -- Biomass & waste                        | 0.04 | 0.05 | 0.06 | 0.05 | 0.03 | 0.04 | 0.02 | 0.01 | 0.01 | 0.01 | 0.01                | 0.01   | 0.01   | 
| -- Geothermal                             | 0.02 | 0.01 | 0.01 | 0    | 0    | 0.01 | 0.01 | <1%  | <1%  | <1%  | <1%                 | 0.01   | 0.01   | 
| -- Solar                                  | 0.03 | 0.01 | 0.01 | 0    | 0    | 0    | <1%  | <1%  | <1%  | <1%  | <1%                 | <1%    | <1%    | 
| Coal                                      | 0.37 | 0.4  | 0.42 | 0.33 | 0.41 | 0.39 | 0.41 | 0.44 | 0.45 | 0.48 | 0.51                | 0.51   | 0.51   | 
| Large Hydroelectric                       | 0.03 | 0.02 | 0.04 | 0.04 | 0.03 | 0.03 | 0.04 | 0.07 | 0.07 | 0.06 | 0.05                | 0.08   | 0.08   | 
| Natural Gas                               | 0.25 | 0.22 | 0.17 | 0.21 | 0.17 | 0.22 | 0.3  | 0.32 | 0.33 | 0.3  | 0.28999999999999998 | 0.26   | 0.26   | 
| Nuclear                                   | 0.1  | 0.09 | 0.1  | 0.1  | 0.11 | 0.11 | 0.11 | 0.09 | 0.09 | 0.1  | 0.09                | 0.12   | 0.12   | 
| Other                                     | 0    | 0    | 0    | 0    | 0    | 0    | <1%  | 0    | 0    | <1%  | <1%                 | 0      | 0      | 
| -- Small hydroelectric                    | 0.01 | 0.01 | 0.01 | 0.02 | 0.06 | .07  | 0.06 | 0.05 | 0.06 | 0.04 | 0.05                | 0.01   | 0.01   | 
```