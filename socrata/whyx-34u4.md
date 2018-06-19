# Traffic Circles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-circles-f6d49) |
| Metadata | [Link](https://data.sfgov.org/api/views/whyx-34u4) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/whyx-34u4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/whyx-34u4/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | whyx-34u4 |
| Name | Traffic Circles |
| Attribution | City and County of San Francisco |
| Category | Transportation |
| Tags | traffic circles |
| Created | 2016-08-18T20:54:01Z |
| Publication Date | 2016-10-12T00:50:33Z |

## Description

This dataset was created to show the locations of traffic circles.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | object_id                    | Object ID                    | text      | number      |
| Yes      | series tag     | description                  | Description                  | text      | text        |
| Yes      | series tag     | install_fiscal_year          | Install Fiscal Year          | text      | text        |
| Yes      | series tag     | funding_source               | Funding Source               | text      | text        |
| Yes      | series tag     | type_of_landscaping_elements | Type of Landscaping Elements | text      | text        |
| Yes      | numeric metric | number_of_circles            | Number of Circles            | number    | number      |
| Yes      | series tag     | project_name                 | Project Name                 | text      | text        |
| Yes      | series tag     | cnn_id                       | CNN ID                       | text      | text        |
| Yes      | series tag     | street_name                  | Street Name                  | text      | text        |
| Yes      | series tag     | cross_street                 | Cross Street                 | text      | text        |
| Yes      | numeric metric | install_month                | Install Month                | number    | text        |
| Yes      | numeric metric | install_year                 | Install Year                 | number    | number      |
| Yes      | time           | last_edited_date             | Last Edited Date             | date      | date        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:whyx-34u4 d:2016-12-23T00:00:00.000Z t:install_fiscal_year="FY 04/05" t:description="Traffic Circle" t:cross_street=Kirkwood t:object_id=2 t:street_name="Earl St" t:cnn_id=33128000 m:install_year=2005 m:install_month=10

series e:whyx-34u4 d:2016-12-23T00:00:00.000Z t:install_fiscal_year="FY 85/86" t:description="Traffic Circle" t:cross_street="8th St" t:object_id=3 t:street_name="Division St" t:cnn_id=23871000 m:install_year=1986 m:install_month=2

series e:whyx-34u4 d:2016-12-23T00:00:00.000Z t:project_name="Mission Bay" t:install_fiscal_year="FY 14/15" t:description="Traffic Circle" t:cross_street="Owens St" t:object_id=4 t:street_name="Mission Bay Dr" t:cnn_id=35050000 m:install_year=2014 m:install_month=9
```

## Meta Commands

```ls
metric m:number_of_circles p:long l:"Number of Circles" t:dataTypeName=number

metric m:install_month p:long l:"Install Month" t:dataTypeName=number

metric m:install_year p:integer l:"Install Year" t:dataTypeName=number

entity e:whyx-34u4 l:"Traffic Circles" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/whyx-34u4

property e:whyx-34u4 t:meta.view v:id=whyx-34u4 v:category=Transportation v:attributionLink=http://sfgov.org/ v:averageRating=0 v:name="Traffic Circles" v:attribution="City and County of San Francisco"

property e:whyx-34u4 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:whyx-34u4 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:whyx-34u4 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | description    | install_fiscal_year | funding_source | type_of_landscaping_elements | number_of_circles | project_name | cnn_id   | street_name    | cross_street | install_month | install_year | last_edited_date | 
| ========= | ============== | =================== | ============== | ============================ | ================= | ============ | ======== | ============== | ============ | ============= | ============ | ================ | 
| 1         | Traffic Circle |                     |                |                              |                   |              | 33489000 | Gonzales Dr    | Crespi Dr    |               |              | 1482451200       | 
| 2         | Traffic Circle | FY 04/05            |                |                              |                   |              | 33128000 | Earl St        | Kirkwood     | 10            | 2005         | 1482451200       | 
| 3         | Traffic Circle | FY 85/86            |                |                              |                   |              | 23871000 | Division St    | 8th St       | 2             | 1986         | 1482451200       | 
| 4         | Traffic Circle | FY 14/15            |                |                              |                   | Mission Bay  | 35050000 | Mission Bay Dr | Owens St     | 9             | 2014         | 1482451200       | 
| 5         | Traffic Circle | FY 04/05            |                |                              |                   |              | 20196000 | La Salle Ave   | Newcomb      | 5             | 2006         | 1482451200       | 
| 6         | Traffic Circle |                     |                |                              |                   |              | 23095000 | Font Blvd      | Serrano Dr   |               |              | 1482451200       | 
| 7         | Traffic Circle | FY 16/17            |                |                              |                   |              | 22132000 | Hearst Ave     | Baden St     | 7             | 2016         | 1482451200       | 
| 8         | Traffic Circle |                     |                |                              |                   |              | 23049000 | Gonzalez Dr    | Bucareli Dr  |               |              | 1482451200       | 
| 9         | Traffic Circle | FY 12/13            |                |                              |                   | Mid-Richmond | 27535000 | 23rd Ave       | Anza         | 3             | 2013         | 1482451200       | 
| 10        | Traffic Circle | FY 13/14            |                |                              |                   |              | 23281000 | RIVERA ST      | 28TH AVE     | 6             | 2014         | 1482451200       | 
```