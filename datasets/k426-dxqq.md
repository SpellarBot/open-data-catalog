# Film Tax Credit Productions and Stage Locations: Beginning 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/film-tax-credit-productions-and-stage-locations-beginning-2004) |
| Metadata | [Link](https://data.ny.gov/api/views/k426-dxqq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/k426-dxqq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/k426-dxqq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | k426-dxqq |
| Name | Film Tax Credit Productions and Stage Locations: Beginning 2004 |
| Attribution | Empire State Development |
| Category | Economic Development |
| Tags | film, tax credit, stage |
| Created | 2014-02-24T17:45:40Z |
| Publication Date | 2016-02-16T14:36:29Z |

## Description

Empire State Development manages and tracks data for the NYS Film Tax Credit Program. This dataset was provided as a companion file to the Film Credits database. The dataset displays a list of film credit productions and the location of the primary stage facility for each production.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | project        | Project        | text      | text        |
| Yes      | time        | effective_year | Effective Year | number    | number      |
| Yes      | series tag  | county         | County         | text      | text        |
| Yes      | series tag  | esd_region     | ESD Region     | text      | text        |
```

## Time Field

```ls
Value = effective_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:k426-dxqq l:"Film Tax Credit Productions and Stage Locations: Beginning 2004" t:attribution="Empire State Development" t:url=https://data.ny.gov/api/views/k426-dxqq

property e:k426-dxqq t:meta.view v:id=k426-dxqq v:category="Economic Development" v:attributionLink=http://esd.ny.gov/Resources.html v:averageRating=0 v:name="Film Tax Credit Productions and Stage Locations: Beginning 2004" v:attribution="Empire State Development"

property e:k426-dxqq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:k426-dxqq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:k426-dxqq t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project                                 | effective_year | county      | esd_region | 
| ======================================= | ============== | =========== | ========== | 
| Life of an Actress                      | 2014           | Kings       | NYC        | 
| Ten Thousand Saints                     | 2014           | Kings       | NYC        | 
| Friends of the People Pilot (fka TruTV) | 2014           | New York    | NYC        | 
| ALONE                                   | 2014           | Kings       | NYC        | 
| Leftovers Season 1                      | 2014           | Westchester | Mid-Hudson | 
| GET HAPPY                               | 2014           | Kings       | NYC        | 
| I Dream Too Much                        | 2014           | Ulster      | Mid-Hudson | 
| Bad Hurt                                | 2014           | Kings       | NYC        | 
| Burning Bride                           | 2014           | Kings       | NYC        | 
| One Bad Choice Season 1                 | 2014           | New York    | NYC        | 
```