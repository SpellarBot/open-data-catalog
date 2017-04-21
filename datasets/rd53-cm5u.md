# Trials and Hearings De Novo Held ( RSN 39975)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trials-and-hearings-de-novo-held-rsn-39975-8f903) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rd53-cm5u) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rd53-cm5u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rd53-cm5u/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rd53-cm5u |
| Name | Trials and Hearings De Novo Held ( RSN 39975) |
| Attribution | Labor and Industrial Relations Appeals Board |
| Category | Employment |
| Tags | trial, hearing |
| Created | 2012-08-23T18:09:09Z |
| Publication Date | 2013-07-30T18:10:15Z |

## Description

Labor and Industrial Relations Appeals Board - Trials and Hearings De Novo Held

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year             | Fiscal Year             | text      | text        |
| Yes      | numeric metric | number_of_hearings_held | Number of Hearings Held | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rd53-cm5u d:2012-08-23T11:09:10.000Z t:fiscal_year="1975 - 1976" m:number_of_hearings_held=49

series e:rd53-cm5u d:2012-08-23T11:09:10.000Z t:fiscal_year="1976 - 1977" m:number_of_hearings_held=53

series e:rd53-cm5u d:2012-08-23T11:09:10.000Z t:fiscal_year="1977 - 1978" m:number_of_hearings_held=97
```

## Meta Commands

```ls
metric m:number_of_hearings_held p:integer l:"Number of Hearings Held" t:dataTypeName=number

entity e:rd53-cm5u l:"Trials and Hearings De Novo Held ( RSN 39975)" t:attribution="Labor and Industrial Relations Appeals Board" t:url=https://data.hawaii.gov/api/views/rd53-cm5u

property e:rd53-cm5u t:meta.view v:id=rd53-cm5u v:category=Employment v:averageRating=0 v:name="Trials and Hearings De Novo Held ( RSN 39975)" v:attribution="Labor and Industrial Relations Appeals Board"

property e:rd53-cm5u t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:rd53-cm5u t:meta.view.owner v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:displayName="Labor and Industrial Relations Appeals Board"

property e:rd53-cm5u t:meta.view.tableauthor v:id=r3in-7sfs v:profileImageUrlMedium=/api/users/r3in-7sfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/r3in-7sfs/profile_images/LARGE v:screenName="Labor and Industrial Relations Appeals Board" v:profileImageUrlSmall=/api/users/r3in-7sfs/profile_images/TINY v:roleName=publisher v:displayName="Labor and Industrial Relations Appeals Board"
```

## Top Records

```ls
| :updated_at | fiscal_year | number_of_hearings_held | 
| =========== | =========== | ======================= | 
| 1345720150  | 1975 - 1976 | 49                      | 
| 1345720150  | 1976 - 1977 | 53                      | 
| 1345720150  | 1977 - 1978 | 97                      | 
| 1345720150  | 1978 - 1979 | 59                      | 
| 1345720150  | 1979 - 1980 | 158                     | 
| 1345720150  | 1980 - 1981 | 232                     | 
| 1345720150  | 1981 - 1982 | 197                     | 
| 1345720150  | 1982 - 1983 | 124                     | 
| 1345720150  | 1983 - 1984 | 125                     | 
| 1345720150  | 1984 - 1985 | 101                     | 
```