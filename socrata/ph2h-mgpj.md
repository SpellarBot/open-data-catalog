# State Liquor Authority (SLA) Alcoholic Beverage Wet and Dry Local Options: Beginning 1948

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-liquor-authority-sla-alcoholic-beverage-wet-and-dry-local-options-beginning-1948) |
| Metadata | [Link](https://data.ny.gov/api/views/ph2h-mgpj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ph2h-mgpj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ph2h-mgpj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ph2h-mgpj |
| Name | State Liquor Authority (SLA) Alcoholic Beverage Wet and Dry Local Options: Beginning 1948 |
| Attribution | NYSLA Secretary?s Office / NYSITS |
| Category | Economic Development |
| Tags | local options; dry towns; partially dry towns |
| Created | 2014-02-06T19:56:01Z |
| Publication Date | 2014-12-18T18:59:58Z |

## Description

Dataset of in-force Local Options regarding sales of alcoholic beverages for municipalities across New York state beginning in 1948

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag  | county                 | County                 | text      | text        |
| Yes      | series tag  | town                   | Town                   | text      | text        |
| Yes      | time        | year_voted_on_ballot   | Year Voted on Ballot   | number    | number      |
| Yes      | series tag  | type                   | Type                   | text      | text        |
| Yes      | series tag  | description_parameters | Description/Parameters | text      | text        |
```

## Time Field

```ls
Value = year_voted_on_ballot
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:ph2h-mgpj l:"State Liquor Authority (SLA) Alcoholic Beverage Wet and Dry Local Options: Beginning 1948" t:attribution="NYSLA Secretary?s Office / NYSITS" t:url=https://data.ny.gov/api/views/ph2h-mgpj

property e:ph2h-mgpj t:meta.view v:id=ph2h-mgpj v:category="Economic Development" v:attributionLink=https://www.sla.ny.gov v:averageRating=0 v:name="State Liquor Authority (SLA) Alcoholic Beverage Wet and Dry Local Options: Beginning 1948" v:attribution="NYSLA Secretary?s Office / NYSITS"

property e:ph2h-mgpj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ph2h-mgpj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ph2h-mgpj t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county      | town          | year_voted_on_ballot | type          | description_parameters                                                                                                                                                                                                                                | 
| =========== | ============= | ==================== | ============= | ===================================================================================================================================================================================================================================================== | 
| Allegany    | Caneadea      | 1986                 | DRY           | No Alcohol Sold                                                                                                                                                                                                                                       | 
| Allegany    | West Almond   | 1973                 | PARTIALLY DRY | Wet for On-Premises Consumption; Dry for Off-Premises Consumption                                                                                                                                                                                     | 
| Allegany    | Rushford      | 1984                 | PARTIALLY DRY | Wet for On-Premises Consumption & Off-Premises Consumption; Dry for Special On-Premises Consumption                                                                                                                                                   | 
| Cattaraugus | Freedom       | 2011                 | PARTIALLY DRY | Wet for Off-Premises Consumption; Wet for Special On-Premises Consumption (tavern); Wet for On-Premises Consumption of beer at race tracks and outdoor athletic fields and stadiums where admission fees are charged; Dry for On-Premises Consumption | 
| Cayuga      | Sterling      | 1973                 | PARTIALLY DRY | Wet for On-Premises Consumption & Off-Premises Consumption; Dry for Special On-Premises Consumption                                                                                                                                                   | 
| Cayuga      | Throop        | 1972                 | PARTIALLY DRY | Wet for On-Premises Consumption & Off-Premises Consumption; Dry for Special On-Premises Consumption                                                                                                                                                   | 
| Chautauqua  | Clymer        | 1974                 | DRY           | No Alcohol Sold                                                                                                                                                                                                                                       | 
| Chautauqua  | North Harmony | 1977                 | PARTIALLY DRY | Wet for On-Premises Consumption & Off-Premises Consumption; Dry for Special On-Premises Consumption                                                                                                                                                   | 
| Chautauqua  | Harmony       | 2006                 | PARTIALLY DRY | Wet for Off-Premises Consumption (beer only - ?54); Wet for On-Premises Consumption (beer & wine products only ??55 & 79-b); Dry in all other areas                                                                                                   | 
| Cortland    | Lapeer        | 1948                 | DRY           | No Alcohol Sold                                                                                                                                                                                                                                       | 
```