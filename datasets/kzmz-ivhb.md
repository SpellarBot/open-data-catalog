# DSNY's Refuse and Recycling Disposal Networks

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/kzmz-ivhb/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/dsnys-refuse-and-recycling-disposal-networks-d0e72)
* Id = kzmz-ivhb
* Name = DSNY's Refuse and Recycling Disposal Networks
* Attribution = Department of Sanitation (DSNY)
* Category = City Government
* Tags = [sanitation, services, community, district, refuse, paper, metal, glass, plastic, recycle, recycling, clean web]
* Created = 2011-10-10T22:48:24Z
* Publication Date = 2016-02-19T19:24:42Z
* Rows Updated = 2016-02-19T19:24:11Z

## Description

For each Community District, the name and address of the location where Refuse, Paper, and Metal/Glass/Plastic collected in that district are disposed of under normal operating circumstances.
Update Schedule: As required

## Columns

```ls
| Name                      | Field Name                | Data Type | Render Type | Schema Type | Included | 
| ========================= | ========================= | ========= | =========== | =========== | ======== | 
| updated_at                | :updated_at               | meta_data | meta_data   | time        | Yes      | 
| District                  | district                  | text      | text        | series tag  | Yes      | 
| Material                  | material                  | text      | text        | series tag  | Yes      | 
| Primary Disposal Facility | primary_disposal_facility | text      | text        | series tag  | Yes      | 
| Location                  | location                  | text      | text        | series tag  | Yes      | 
| Latitude                  | latitude                  | number    | number      |             | No       | 
| Longitude                 | longitude                 | number    | number      |             | No       | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = longitude,latitude
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:kzmz-ivhb l:"DSNY's Refuse and Recycling Disposal Networks" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/kzmz-ivhb

property e:kzmz-ivhb t:meta.view d:2017-03-03T14:22:19.036Z v:id=kzmz-ivhb v:category="City Government" v:averageRating=0 v:name="DSNY's Refuse and Recycling Disposal Networks" v:attribution="Department of Sanitation (DSNY)"

property e:kzmz-ivhb t:meta.view.owner d:2017-03-03T14:22:19.036Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:kzmz-ivhb t:meta.view.tableauthor d:2017-03-03T14:22:19.036Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```