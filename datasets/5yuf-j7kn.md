# SSMMA Combined Sewer Overflow

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-combined-sewer-overflow-3436f) |
| Metadata | [Link](https://data.illinois.gov/api/views/5yuf-j7kn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5yuf-j7kn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5yuf-j7kn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5yuf-j7kn |
| Name | SSMMA Combined Sewer Overflow |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | infrastructure, sanitary, environment, natural resources |
| Created | 2012-11-27T17:45:31Z |
| Publication Date | 2012-11-27T19:12:37Z |

## Description

This dataset details combined sewer overflows in the Chicago Southland area.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | pipe_desc   | PIPE_DESC  | text      | text        |
| Yes      | series tag     | pipe_inact  | PIPE_INACT | text      | text        |
| Yes      | series tag     | pipe_ina_1  | PIPE_INA_1 | text      | text        |
| Yes      | series tag     | county_nam  | COUNTY_NAM | text      | text        |
| Yes      | series tag     | name_1      | NAME_1     | text      | text        |
| No       |                | lat_dec     | LAT_DEC    | number    | number      |
| Yes      | numeric metric | lon_conv    | LON_CONV   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = lat_dec
```

## Data Commands

```ls
series e:5yuf-j7kn d:2012-11-27T09:45:33.000Z t:pipe_desc="CSO-KENILWORTH AVENUE" t:name_1="VILLA PARK WET WEATHER STP" t:pipe_inact=A t:county_nam="DU PAGE" m:lon_conv=-87.961111

series e:5yuf-j7kn d:2012-11-27T09:45:33.000Z t:pipe_desc="CSO-STEPHEN STREET" t:name_1="LEMONT CSOS" t:pipe_inact=A t:county_nam=COOK m:lon_conv=-87.999167

series e:5yuf-j7kn d:2012-11-27T09:45:33.000Z t:pipe_desc="CSO-LAKE ST & MCCORMICK BLVD" t:name_1="SKOKIE CSOS" t:pipe_inact=A t:county_nam=COOK m:lon_conv=-87.708889
```

## Meta Commands

```ls
metric m:lon_conv p:float l:LON_CONV t:dataTypeName=number

entity e:5yuf-j7kn l:"SSMMA Combined Sewer Overflow" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/5yuf-j7kn

property e:5yuf-j7kn t:meta.view v:id=5yuf-j7kn v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Combined Sewer Overflow" v:attribution="South Suburban Mayors and Managers Association"

property e:5yuf-j7kn t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:5yuf-j7kn t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:5yuf-j7kn t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | pipe_desc                    | pipe_inact | pipe_ina_1 | county_nam | name_1                     | lat_dec   | lon_conv   | 
| =========== | ============================ | ========== | ========== | ========== | ========================== | ========= | ========== | 
| 1354009533  | CSO-KENILWORTH AVENUE        | A          |            | DU PAGE    | VILLA PARK WET WEATHER STP | 41.888056 | -87.961111 | 
| 1354009533  | CSO-STEPHEN STREET           | A          |            | COOK       | LEMONT CSOS                | 41.675833 | -87.999167 | 
| 1354009533  | CSO-LAKE ST & MCCORMICK BLVD | A          |            | COOK       | SKOKIE CSOS                | 42.051667 | -87.708889 | 
| 1354009533  | CSO-CLEVELAND STREET         | A          |            | COOK       | EVANSTON CSOS              | 42.03     | -87.71     | 
| 1354009533  | CSO-EMERSON STREET           | A          |            | COOK       | EVANSTON CSOS              | 42.051944 | -87.708056 | 
| 1354009533  | CSO-NORTHWEST TOLLWAY        | A          |            | COOK       | MWRDGC STICKNEY WRP        | 41.985556 | -87.856944 | 
| 1354009533  | CSO-13A PUMP STATION         | A          |            | COOK       | MWRDGC STICKNEY WRP        | 41.7975   | -87.810833 | 
| 1354009533  | CSO-ELLIS AVENUE             | A          |            | COOK       | DOLTON CSOS                | 41.608333 | -87.599722 | 
| 1354009533  | CSO-6872 TOUHY AVENUE        | A          |            | COOK       | NILES CSOS                 | 42.013333 | -87.791667 | 
| 1354009533  | CSO-HOWARD (W)               | A          |            | COOK       | NILES CSOS                 | 42.011667 | -87.788333 | 
```