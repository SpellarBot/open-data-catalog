# LADWP Power Poles Replaced

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-power-poles-installation-12799) |
| Metadata | [Link](https://data.lacity.org/api/views/t24g-hqix) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/t24g-hqix/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/t24g-hqix/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | t24g-hqix |
| Name | LADWP Power Poles Replaced |
| Attribution | LADWP |
| Category | A Well Run City |
| Tags | power polls, reliability |
| Created | 2014-05-23T23:02:44Z |
| Publication Date | 2017-03-03T23:08:33Z |

## Description

Cumulative number of poles replaced annually (fiscal year) under the LADWP Power System Reliability Program

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                       | Data Type | Render Type |
| ======== | ============== | ======================== | ========================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | years                    | Years                      | text      | text        |
| Yes      | numeric metric | of_power_poles_installed | # of Power Poles Installed | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:t24g-hqix d:2017-03-03T23:05:18.000Z t:years="July 2016" m:of_power_poles_installed=148

series e:t24g-hqix d:2017-03-03T23:05:33.000Z t:years="August 2016" m:of_power_poles_installed=271

series e:t24g-hqix d:2017-03-03T23:05:40.000Z t:years="September 2016" m:of_power_poles_installed=549
```

## Meta Commands

```ls
metric m:of_power_poles_installed p:integer l:"# of Power Poles Installed" t:dataTypeName=number

entity e:t24g-hqix l:"LADWP Power Poles Replaced" t:attribution=LADWP t:url=https://data.lacity.org/api/views/t24g-hqix

property e:t24g-hqix t:meta.view v:id=t24g-hqix v:category="A Well Run City" v:averageRating=0 v:name="LADWP Power Poles Replaced" v:attribution=LADWP

property e:t24g-hqix t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:t24g-hqix t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:t24g-hqix t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| :updated_at | years          | of_power_poles_installed | 
| =========== | ============== | ======================== | 
| 1488582318  | July 2016      | 148                      | 
| 1488582333  | August 2016    | 271                      | 
| 1488582340  | September 2016 | 549                      | 
| 1488582351  | October 2016   | 788                      | 
| 1488582361  | November 2016  | 944                      | 
| 1488582379  | December 2016  | 1184                     | 
| 1488582391  | January 2016   | 1408                     | 
| 1488582472  | February 2016  | 1543                     | 
```