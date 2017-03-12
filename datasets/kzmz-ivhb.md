# DSNY's Refuse and Recycling Disposal Networks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dsnys-refuse-and-recycling-disposal-networks-d0e72) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kzmz-ivhb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kzmz-ivhb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kzmz-ivhb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kzmz-ivhb |
| Name | DSNY's Refuse and Recycling Disposal Networks |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Tags | sanitation, services, community, district, refuse, paper, metal, glass, plastic, recycle, recycling, clean web |
| Created | 2011-10-10T22:48:24Z |
| Publication Date | 2016-02-19T19:24:42Z |
| Rows Updated | 2016-02-19T19:24:11Z |

## Description

For each Community District, the name and address of the location where Refuse, Paper, and Metal/Glass/Plastic collected in that district are disposed of under normal operating circumstances.
Update Schedule: As required

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | district                  | District                  | text      | text        |
| Yes      | series tag  | material                  | Material                  | text      | text        |
| Yes      | series tag  | primary_disposal_facility | Primary Disposal Facility | text      | text        |
| Yes      | series tag  | location                  | Location                  | text      | text        |
| No       |             | latitude                  | Latitude                  | number    | number      |
| No       |             | longitude                 | Longitude                 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:kzmz-ivhb l:"DSNY's Refuse and Recycling Disposal Networks" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/kzmz-ivhb

property e:kzmz-ivhb t:meta.view v:id=kzmz-ivhb v:category="City Government" v:averageRating=0 v:name="DSNY's Refuse and Recycling Disposal Networks" v:attribution="Department of Sanitation (DSNY)"

property e:kzmz-ivhb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:kzmz-ivhb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```