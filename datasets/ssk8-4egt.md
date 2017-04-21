# Directory Of Bronx Future Parks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-bronx-future-parks-7ad7a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ssk8-4egt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ssk8-4egt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ssk8-4egt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ssk8-4egt |
| Name | Directory Of Bronx Future Parks |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Recreation |
| Tags | dpr, park, recreation, future, bronx, healthy living |
| Created | 2013-01-29T16:49:59Z |
| Publication Date | 2013-06-21T20:28:20Z |

## Description

List of Bronx Future Parks with their Categories and Nature of Activity

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | park_name           | Park Name           | text      | text        |
| Yes      | series tag  | description_of_work | Description of Work | text      | text        |
| Yes      | series tag  | status              | Status              | text      | text        |
| Yes      | series tag  | category            | Category            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ssk8-4egt d:2013-01-29T08:50:00.000Z t:description_of_work="Reconstruction of the playground and ballfield, install higher perimeter fencing between field and Co-op, new water line and new asphalt pathway." t:category="Neighborhood Parks" t:status=Completed t:park_name="Ambrosini Playground and Ballfield" m:row_number.ssk8-4egt=1

series e:ssk8-4egt d:2013-01-29T08:50:00.000Z t:description_of_work="Entire renovation of both the court and playground areas including repair of the spray shower." t:category="Neighborhood Parks" t:status=Completed t:park_name="Campanaro Playground" m:row_number.ssk8-4egt=2

series e:ssk8-4egt d:2013-01-29T08:50:00.000Z t:description_of_work="Playground Reconstruction to include new play equipment, handball and basketball court renovations with color seal coating, pavement, swings, and fencing." t:category="Neighborhood Parks" t:status=Completed t:park_name="Clark Playground" m:row_number.ssk8-4egt=3
```

## Meta Commands

```ls
metric m:row_number.ssk8-4egt p:long l:"Row Number"

entity e:ssk8-4egt l:"Directory Of Bronx Future Parks" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/ssk8-4egt

property e:ssk8-4egt t:meta.view v:id=ssk8-4egt v:category=Recreation v:attributionLink=http://www.nycgovparks.org/park-features/future-parks/bronx-parks-for-21st-century/project-list v:averageRating=0 v:name="Directory Of Bronx Future Parks" v:attribution="Department of Parks and Recreation (DPR)"

property e:ssk8-4egt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ssk8-4egt t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | park_name                          | description_of_work                                                                                                                                        | status          | category           | 
| =========== | ================================== | ========================================================================================================================================================== | =============== | ================== | 
| 1359449400  | Ambrosini Playground and Ballfield | Reconstruction of the playground and ballfield, install higher perimeter fencing between field and Co-op, new water line and new asphalt pathway.          | Completed       | Neighborhood Parks | 
| 1359449400  | Campanaro Playground               | Entire renovation of both the court and playground areas including repair of the spray shower.                                                             | Completed       | Neighborhood Parks | 
| 1359449400  | Clark Playground                   | Playground Reconstruction to include new play equipment, handball and basketball court renovations with color seal coating, pavement, swings, and fencing. | Completed       | Neighborhood Parks | 
| 1359449400  | Devoe Park                         | Reconstruction of playground to include new play equipment, landscaping and drainage improvements.                                                         | Completed       | Neighborhood Parks | 
| 1359449400  | Drew Playground                    | Renovation of playground.                                                                                                                                  | Completed       | Neighborhood Parks | 
| 1359449400  | Edenwald Playground                | Reconstruction of playground to include new play equipment, spray shower, and landscaping.                                                                 | Completed       | Neighborhood Parks | 
| 1359449400  | Field of Dreams Park               | Development of passive areas of southern section of the park.                                                                                              | In Construction | Neighborhood Parks | 
| 1359449400  | Grant Park                         | Reconstruction of retaining wall for park that will increase available space for future phases.                                                            | Completed       | Neighborhood Parks | 
| 1359449400  | Haffen Park                        | Installation of a synthetic turf field.                                                                                                                    | Completed       | Neighborhood Parks | 
| 1359449400  | Hines Playground                   | Renovation of retaining walls in the park.                                                                                                                 | In Construction | Neighborhood Parks | 
```