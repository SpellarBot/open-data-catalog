# Main Tier Facilities for Renewable Portfolio Standard: 2007 - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/main-tier-facilities-for-renewable-portfolio-standard-beginning-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/r5ck-yed6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/r5ck-yed6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/r5ck-yed6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | r5ck-yed6 |
| Name | Main Tier Facilities for Renewable Portfolio Standard: 2007 - 2013 |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | wind, hydro, biomass, biogas |
| Created | 2013-02-21T20:23:35Z |
| Publication Date | 2014-11-03T14:20:34Z |

## Description

The goal of the Renewable Portfolio Standard (RPS) is to increase the proportion of renewable energy used by New York Consumers from the 2003 19.3% (baseline resources) to at least 30% by the end of 2015. The Main Tier Facilities for Renewable Portfolio Standard data set contains the facility name, contractor and county for each active Main Tier biogas, biomass, hydro, and wind project, as required by the New York State Public Service Commission and reported in the annual New York State Renewable Portfolio Standard Performance Reports 2005 to 2011.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| Yes      | time        | year_reported | Year Reported | number    | number      |
| Yes      | series tag  | resource_type | Resource Type | text      | text        |
| Yes      | series tag  | facility      | Facility      | text      | text        |
| Yes      | series tag  | contractor    | Contractor    | text      | text        |
| Yes      | series tag  | county        | County        | text      | text        |
| Yes      | series tag  | state         | State         | text      | text        |
| Yes      | series tag  | country       | Country       | text      | text        |
```

## Time Field

```ls
Value = year_reported
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:r5ck-yed6 l:"Main Tier Facilities for Renewable Portfolio Standard: 2007 - 2013" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/r5ck-yed6

property e:r5ck-yed6 t:meta.view v:id=r5ck-yed6 v:category="Energy & Environment" v:attributionLink=http://www.nyserda.ny.gov/Publications/Program-Planning-Status-and-Evaluation-Reports/Renewable-Portfolio-Standard-Reports.aspx v:averageRating=0 v:name="Main Tier Facilities for Renewable Portfolio Standard: 2007 - 2013" v:attribution="New York State Energy Research and Development Authority"

property e:r5ck-yed6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:r5ck-yed6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:r5ck-yed6 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year_reported | resource_type | facility                    | contractor                      | county       | state    | country | 
| ============= | ============= | =========================== | =============================== | ============ | ======== | ======= | 
| 2007          | Biomass       | AES Greenidge Station       | AES Greenidge LLC               | Yates        | New York | USA     | 
| 2007          | Biomass       | Niagara Generating Facility | USRG Niagara Biomass LLC        | Niagara      | New York | USA     | 
| 2007          | Hydro         | Allens Falls                | Brookfield Power New York       | St. Lawrence | New York | USA     | 
| 2007          | Hydro         | Browns Falls                | Brookfield Power New York       | St. Lawrence | New York | USA     | 
| 2007          | Hydro         | Colton                      | Brookfield Power New York       | St. Lawrence | New York | USA     | 
| 2007          | Hydro         | Eagle                       | Brookfield Power New York       | Lewis        | New York | USA     | 
| 2007          | Hydro         | East Norfolk                | Brookfield Power New York       | St. Lawrence | New York | USA     | 
| 2007          | Hydro         | Effley Hydro                | Brookfield Power New York       | Lewis        | New York | USA     | 
| 2007          | Hydro         | High Falls                  | Brookfield Energy Marketing Inc | N/A          | Quebec   | Canada  | 
| 2007          | Hydro         | Higley                      | Brookfield Power New York       | St. Lawrence | New York | USA     | 
```