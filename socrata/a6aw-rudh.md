# Plumbing Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plumbing-permits) |
| Metadata | [Link](https://data.sfgov.org/api/views/a6aw-rudh) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/a6aw-rudh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/a6aw-rudh/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | a6aw-rudh |
| Name | Plumbing Permits |
| Category | Housing and Buildings |
| Created | 2016-04-06T22:47:31Z |
| Publication Date | 2016-08-04T16:00:26Z |

## Description

This data set pertains to all types of plumbing and mechanical permits. Data includes details on application/permit numbers, job addresses, supervisorial districts, and the current status of the applications. Data is uploaded weekly by DBI. Users can access permit information online through DBI?s Permit Tracking System which is 24/7 at www.sfdbi.org/dbipts.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type | Render Type |
| ======== | ============== | ================================= | =================================== | ========= | =========== |
| Yes      | series tag     | permit_number                     | Permit Number                       | text      | text        |
| Yes      | time           | application_date                  | Application Date                    | date      | date        |
| Yes      | series tag     | block                             | Block                               | text      | text        |
| Yes      | series tag     | lot                               | Lot                                 | text      | text        |
| Yes      | series tag     | street_number                     | Street Number                       | text      | text        |
| Yes      | series tag     | street_number_suffix              | Street Number Suffix                | text      | text        |
| Yes      | series tag     | street_name                       | Street Name                         | text      | text        |
| Yes      | series tag     | street_suffix                     | Street Suffix                       | text      | text        |
| Yes      | numeric metric | unit                              | Unit                                | number    | text        |
| Yes      | series tag     | unit_suffix                       | Unit Suffix                         | text      | text        |
| Yes      | series tag     | description                       | Description                         | text      | text        |
| Yes      | series tag     | status                            | Status                              | text      | text        |
| Yes      | series tag     | neighborhoods_analysis_boundaries | Neighborhoods - Analysis Boundaries | text      | text        |
| Yes      | series tag     | supervisor_district               | Supervisor District                 | text      | text        |
| Yes      | series tag     | zipcode                           | Zipcode                             | text      | text        |
```

## Time Field

```ls
Value = application_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:a6aw-rudh d:2016-08-04T00:00:00.000Z t:permit_number=PM20160804784 t:neighborhoods_analysis_boundaries=Chinatown t:status=issued t:description="retailofficeremodeling installonefurnace" t:zipcode=94108 t:street_name=Washington t:street_suffix=St t:lot=044 t:block=0210 t:street_number=813 t:supervisor_district=3 m:unit=0

series e:a6aw-rudh d:2016-08-02T00:00:00.000Z t:permit_number=PMW20160802453 t:neighborhoods_analysis_boundaries="Pacific Heights" t:status=issued t:description=workcategory:1m;installtwo(2)directventgasfireplacespermanualspecs;gaslinesprovisionedbyothers t:zipcode=94115 t:street_name=Washington t:street_suffix=St t:lot=060 t:block=0999 t:street_number=3191 t:supervisor_district=2 m:unit=5

series e:a6aw-rudh d:2016-08-01T00:00:00.000Z t:permit_number=PP20160801632 t:neighborhoods_analysis_boundaries="Hayes Valley" t:status=issued t:description="2/f:remodel(e)bathroom&(e)kitchen.convert(e)kitchentobedroom addwasher&dryer." t:zipcode=94102 t:street_name=Buchanan t:street_suffix=St t:lot=013 t:block=0851 t:street_number=300 t:supervisor_district=5 m:unit=0
```

## Meta Commands

```ls
metric m:unit p:integer l:Unit t:dataTypeName=number

entity e:a6aw-rudh l:"Plumbing Permits" t:url=https://data.sfgov.org/api/views/a6aw-rudh

property e:a6aw-rudh t:meta.view v:id=a6aw-rudh v:category="Housing and Buildings" v:averageRating=0 v:name="Plumbing Permits"

property e:a6aw-rudh t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:a6aw-rudh t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:a6aw-rudh t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| permit_number | application_date | block | lot | street_number | street_number_suffix | street_name | street_suffix | unit | unit_suffix | description                                                                                           | status   | neighborhoods_analysis_boundaries | supervisor_district | zipcode | 
| ============= | ================ | ===== | === | ============= | ==================== | =========== | ============= | ==== | =========== | ===================================================================================================== | ======== | ================================= | =================== | ======= | 
| PM20160801626 | 1470009600       | 1654  | 015 | 771           |                      | 11th        | Ave           |      |             | replacetheoldfurnace.newfluepvc2"newcondensatedrain.                                                  | issued   | Inner Richmond                    | 1                   | 94118   | 
| PM20160801631 | 1470009600       | 3119  | 034 | 283           |                      | Hearst      | Ave           |      |             | renewalofpermitpm20150126507.                                                                         | issued   | West of Twin Peaks                | 7                   | 94131   | 
| PM20160801634 | 1470009600       | 1826  | 035 | 1438          |                      | 28th        | Ave           |      |             | replacefuranceand(2)ventpipes.                                                                        | issued   | Sunset/Parkside                   | 4                   | 94122   | 
| PM20160802658 | 1470096000       | 5323  | 012 | 1574          |                      | Palou       | Ave           |      |             | replacefurnace                                                                                        | issued   | Bayview Hunters Point             | 10                  | 94124   | 
| PM20160802662 | 1470096000       | 2473  | 023 | 2690          |                      | 24th        | Ave           |      |             | relocate(e)furnace(n)ductsforgroundflooraddtition fullbathfan&ventilationductsforlaundry              | issued   | Sunset/Parkside                   | 4                   | 94116   | 
| PM20160802666 | 1470096000       | 4088  | 027 | 823           |                      | York        | St            |      |             | move(e)forcedairunit;installnewsystemmovegaslineasnecessary.                                          | issued   | Mission                           | 9                   | 94110   | 
| PM20160802670 | 1470096000       | 3725  | 078 | 981           |                      | Mission     | St            |      |             | modifyexisitingductowrktoaccommodatenewfloorplan add(2)transferfansand(1)exhaustfan.                  | canceled | South of Market                   | 6                   | 94103   | 
| PM20160802684 | 1470096000       | 0871  | 014 | 1800          |                      | Market      | St            |      |             | groundand2ndfloor;hvacrenovation add6newvavboxeswithrelatedhotwaterpiping ducts registersandcontrols. | pos sent | Hayes Valley                      | 8                   | 94102   | 
| PM20160802685 | 1470096000       | 0871  | 014 | 1800          |                      | Market      | St            |      |             | 3rdfloor;hvacrenovation add6newvavboxeswithrelatedhotwaterpiping ducts registersandcontrols.          | pos sent | Hayes Valley                      | 8                   | 94102   | 
| PM20160802686 | 1470096000       | 0871  | 014 | 1800          |                      | Market      | St            |      |             | 4thfloor;hvacrenovation add6newvavboxeswithrelatedhotwaterpiping ducts registersandcontrols.          | pos sent | Hayes Valley                      | 8                   | 94102   | 
```