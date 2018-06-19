# SFO Museum Exhibitions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfo-museum-exhibitions) |
| Metadata | [Link](https://data.sfgov.org/api/views/bjtz-s8v8) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/bjtz-s8v8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/bjtz-s8v8/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | bjtz-s8v8 |
| Name | SFO Museum Exhibitions |
| Attribution | SFO Museum |
| Category | Culture and Recreation |
| Tags | museum, exhibition, art, exhibit, aviation, history, gallery |
| Created | 2016-02-01T23:44:53Z |
| Publication Date | 2016-02-03T17:53:21Z |

## Description

This dataset represents a history of all exhibitions held at San Francisco International Airport by SFO Museum.  The data includes the exhibition name, gallery/location, start date, end date, and exhibition type (general or aviation).

## Columns

```ls
| Included | Schema Type    | Field Name       | Name               | Data Type     | Render Type   |
| ======== | ============== | ================ | ================== | ============= | ============= |
| Yes      | series tag     | id_no            | ID No.             | text          | number        |
| Yes      | time           | start_date       | Start Date         | calendar_date | calendar_date |
| Yes      | numeric metric | start_date_month | Start Date - Month | number        | number        |
| Yes      | numeric metric | start_date_day   | Start Date - Day   | number        | number        |
| No       |                | start_date_year  | Start Date - Year  | text          | number        |
| No       |                | end_date         | End Date           | calendar_date | calendar_date |
| Yes      | numeric metric | end_date_month   | End Date - Month   | number        | number        |
| Yes      | numeric metric | end_date_day     | End Date - Day     | number        | number        |
| No       |                | end_date_year    | End Date - Year    | text          | number        |
| Yes      | series tag     | exhibition_type  | Exhibition Type    | text          | text          |
| Yes      | series tag     | title            | Title              | text          | text          |
| Yes      | series tag     | gallery_site     | Gallery Site       | text          | text          |
| Yes      | series tag     | gallery_terminal | Gallery Terminal   | text          | text          |
| Yes      | series tag     | gallery_area     | Gallery Area       | text          | text          |
| Yes      | series tag     | gallery_level    | Gallery Level      | text          | text          |
| Yes      | series tag     | gallery_name     | Gallery Name       | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_date_year,end_date,end_date_year
```

## Data Commands

```ls
series e:bjtz-s8v8 d:1981-01-01T00:00:00.000Z t:exhibition_type=General t:title="From the Table Top" t:gallery_area=F t:gallery_terminal=T3 t:gallery_name="F-02 North Connector" t:gallery_level=D t:gallery_site=F02 t:id_no=704 m:end_date_month=3 m:end_date_day=25 m:start_date_month=1 m:start_date_day=1

series e:bjtz-s8v8 d:1981-03-28T00:00:00.000Z t:exhibition_type=General t:title="New Glass" t:gallery_area=F t:gallery_terminal=T3 t:gallery_name="F-02 North Connector" t:gallery_level=D t:gallery_site=F02 t:id_no=682 m:end_date_month=6 m:end_date_day=1 m:start_date_month=3 m:start_date_day=28

series e:bjtz-s8v8 d:1981-09-15T00:00:00.000Z t:exhibition_type=General t:title="Folk Art from the Mexican Museum" t:gallery_area=F t:gallery_terminal=T3 t:gallery_name="F-02 North Connector" t:gallery_level=D t:gallery_site=F02 t:id_no=707 m:end_date_month=1 m:end_date_day=30 m:start_date_month=9 m:start_date_day=15
```

## Meta Commands

```ls
metric m:start_date_month p:integer l:"Start Date - Month" t:dataTypeName=number

metric m:start_date_day p:integer l:"Start Date - Day" t:dataTypeName=number

metric m:end_date_month p:integer l:"End Date - Month" t:dataTypeName=number

metric m:end_date_day p:integer l:"End Date - Day" t:dataTypeName=number

entity e:bjtz-s8v8 l:"SFO Museum Exhibitions" t:attribution="SFO Museum" t:url=https://data.sfgov.org/api/views/bjtz-s8v8

property e:bjtz-s8v8 t:meta.view v:id=bjtz-s8v8 v:category="Culture and Recreation" v:attributionLink=http://www.sfomuseum.org v:averageRating=0 v:name="SFO Museum Exhibitions" v:attribution="SFO Museum"

property e:bjtz-s8v8 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:bjtz-s8v8 t:meta.view.owner v:id=7ctb-7due v:screenName=Megan v:displayName=Megan

property e:bjtz-s8v8 t:meta.view.tableauthor v:id=7ctb-7due v:screenName=Megan v:roleName=editor v:displayName=Megan
```

## Top Records

```ls
| id_no | start_date          | start_date_month | start_date_day | start_date_year | end_date            | end_date_month | end_date_day | end_date_year | exhibition_type | title                                                       | gallery_site | gallery_terminal | gallery_area | gallery_level | gallery_name                 | 
| ===== | =================== | ================ | ============== | =============== | =================== | ============== | ============ | ============= | =============== | =========================================================== | ============ | ================ | ============ | ============= | ============================ | 
| 704   | 1981-01-01T00:00:00 | 1                | 1              | 1981            | 1981-03-25T00:00:00 | 3              | 25           | 1981          | General         | From the Table Top                                          | F02          | T3               | F            | D             | F-02 North Connector         | 
| 682   | 1981-03-28T00:00:00 | 3                | 28             | 1981            | 1981-06-01T00:00:00 | 6              | 1            | 1981          | General         | New Glass                                                   | F02          | T3               | F            | D             | F-02 North Connector         | 
| 707   | 1981-09-15T00:00:00 | 9                | 15             | 1981            | 1982-01-30T00:00:00 | 1              | 30           | 1982          | General         | Folk Art from the Mexican Museum                            | F02          | T3               | F            | D             | F-02 North Connector         | 
| 677   | 1982-02-14T00:00:00 | 2                | 14             | 1982            | 1982-05-15T00:00:00 | 5              | 15           | 1982          | General         | Carousel Animals from Golden Gate Park Carousel             | F02          | T3               | F            | D             | F-02 North Connector         | 
| 464   | 1982-06-21T00:00:00 | 6                | 21             | 1982            | 1982-08-05T00:00:00 | 8              | 5            | 1982          | General         | Artist's Furniture: New Dimensions and Statements in Design | F02          | T3               | F            | D             | F-02 North Connector         | 
| 679   | 1982-08-06T00:00:00 | 8                | 6              | 1982            | 1982-09-17T00:00:00 | 9              | 17           | 1982          | General         | Forgotten Dimension                                         | F02          | T3               | F            | D             | F-02 North Connector         | 
| 425   | 1982-10-09T00:00:00 | 10               | 9              | 1982            | 1983-12-08T00:00:00 | 12             | 8            | 1983          | General         | American Porcelain                                          | F02          | T3               | F            | D             | F-02 North Connector         | 
| 465   | 1983-07-13T00:00:00 | 7                | 13             | 1983            | 1984-01-01T00:00:00 | 1              | 1            | 1984          | General         | Navajo Weavings                                             | D01          | T2               | D            | D             | D-01 Central North Connector | 
| 426   | 1983-12-12T00:00:00 | 12               | 12             | 1983            | 1984-03-31T00:00:00 | 3              | 31           | 1984          | General         | A is for Animal                                             | F02          | T3               | F            | D             | F-02 North Connector         | 
| 718   | 1983-12-15T00:00:00 | 12               | 15             | 1983            | 1984-03-15T00:00:00 | 3              | 15           | 1984          | General         | Mexican Dance Masks                                         | D04          | T2               | D            | D             | D-04 Central Gallery         | 
```