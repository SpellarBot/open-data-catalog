# Location of FY 2014 Curb Ramps Installed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/location-of-fy-2014-curb-ramps-installed) |
| Metadata | [Link](https://data.lacity.org/api/views/cu97-7vhd) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/cu97-7vhd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/cu97-7vhd/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | cu97-7vhd |
| Name | Location of FY 2014 Curb Ramps Installed |
| Attribution | Bureau of Street Services |
| Category | A Livable and Sustainable City |
| Tags | bss, street, services, curb, access, ramps, accessibility, pedestrian, ada |
| Created | 2014-05-19T17:36:49Z |
| Publication Date | 2014-05-28T22:51:35Z |

## Description

Locations of concrete curb ramps installed to date for fiscal year 2014.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                    | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ======================================= | ============= | ============= |
| Yes      | series tag     | street_name                          | Street                                  | text          | text          |
| Yes      | series tag     | cross_street_name                    | Cross Street                            | text          | text          |
| Yes      | series tag     | council_district                     | Council District                        | text          | number        |
| Yes      | numeric metric | ne_quantity_constructed              | NE Quantity Constructed                 | number        | number        |
| No       |                | ne_date_completed                    | NE Date Completed                       | calendar_date | calendar_date |
| Yes      | numeric metric | nw_quantity_constructed              | NW Quantity Constructed                 | number        | number        |
| No       |                | nw_date_completed                    | NW Date Completed                       | calendar_date | calendar_date |
| Yes      | numeric metric | se_quantity_constructed              | SE Quantity Constructed                 | number        | number        |
| No       |                | se_date_completed                    | SE Date Completed                       | calendar_date | calendar_date |
| Yes      | numeric metric | sw_quantity_constructed              | SW Quantity Constructed                 | number        | number        |
| Yes      | time           | sw_date_completed                    | SW Date Completed                       | calendar_date | calendar_date |
| Yes      | numeric metric | mid_block_alley_quantity_constructed | Mid-Block or Alley Quantity Constructed | number        | number        |
| No       |                | mid_block_alley_date_completed       | Mid-Block or Alley Date Completed       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = sw_date_completed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = ne_date_completed,se_date_completed,nw_date_completed,mid_block_alley_date_completed
```

## Data Commands

```ls
series e:cu97-7vhd d:2013-08-26T00:00:00.000Z t:street_name="COUNTRY CLUB DR" t:cross_street_name="LUCERNE BL" t:council_district=10 m:se_quantity_constructed=1 m:mid_block_alley_quantity_constructed=0 m:nw_quantity_constructed=0 m:sw_quantity_constructed=1 m:ne_quantity_constructed=0

series e:cu97-7vhd d:2013-07-01T00:00:00.000Z t:street_name="COLYTON ST" t:cross_street_name="4TH ST" t:council_district=14 m:se_quantity_constructed=1 m:mid_block_alley_quantity_constructed=0 m:nw_quantity_constructed=0 m:sw_quantity_constructed=1 m:ne_quantity_constructed=0

series e:cu97-7vhd d:2013-07-02T00:00:00.000Z t:street_name="PALMETTO ST" t:cross_street_name="MATEO ST" t:council_district=14 m:se_quantity_constructed=0 m:mid_block_alley_quantity_constructed=0 m:nw_quantity_constructed=0 m:sw_quantity_constructed=1 m:ne_quantity_constructed=0
```

## Meta Commands

```ls
metric m:ne_quantity_constructed p:integer l:"NE Quantity Constructed" t:dataTypeName=number

metric m:nw_quantity_constructed p:integer l:"NW Quantity Constructed" t:dataTypeName=number

metric m:se_quantity_constructed p:integer l:"SE Quantity Constructed" t:dataTypeName=number

metric m:sw_quantity_constructed p:integer l:"SW Quantity Constructed" t:dataTypeName=number

metric m:mid_block_alley_quantity_constructed p:integer l:"Mid-Block or Alley Quantity Constructed" t:dataTypeName=number

entity e:cu97-7vhd l:"Location of FY 2014 Curb Ramps Installed" t:attribution="Bureau of Street Services" t:url=https://data.lacity.org/api/views/cu97-7vhd

property e:cu97-7vhd t:meta.view v:id=cu97-7vhd v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Location of FY 2014 Curb Ramps Installed" v:attribution="Bureau of Street Services"

property e:cu97-7vhd t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:cu97-7vhd t:meta.view.owner v:id=awhe-qmys v:screenName=CJ v:displayName=CJ

property e:cu97-7vhd t:meta.view.tableauthor v:id=awhe-qmys v:screenName=CJ v:displayName=CJ
```

## Top Records

```ls
| street_name     | cross_street_name | council_district | ne_quantity_constructed | ne_date_completed   | nw_quantity_constructed | nw_date_completed   | se_quantity_constructed | se_date_completed   | sw_quantity_constructed | sw_date_completed   | mid_block_alley_quantity_constructed | mid_block_alley_date_completed | 
| =============== | ================= | ================ | ======================= | =================== | ======================= | =================== | ======================= | =================== | ======================= | =================== | ==================================== | ============================== | 
| COUNTRY CLUB DR | LUCERNE BL        | 10               | 0                       |                     | 0                       |                     | 1                       | 2013-08-26T00:00:00 | 1                       | 2013-08-26T00:00:00 | 0                                    |                                | 
| COLYTON ST      | 4TH ST            | 14               | 0                       |                     | 0                       |                     | 1                       | 2013-07-01T00:00:00 | 1                       | 2013-07-01T00:00:00 | 0                                    |                                | 
| PALMETTO ST     | MATEO ST          | 14               | 0                       |                     | 0                       |                     | 0                       |                     | 1                       | 2013-07-02T00:00:00 | 0                                    |                                | 
| SEATON ST       | 4TH ST            | 14               | 0                       |                     | 0                       |                     | 1                       | 2013-07-01T00:00:00 | 1                       | 2013-07-01T00:00:00 | 0                                    |                                | 
| GRIFFIN AV      | AVENUE 26         | 1                | 1                       | 2013-07-01T00:00:00 | 0                       |                     | 1                       | 2013-07-01T00:00:00 | 0                       |                     | 0                                    |                                | 
| 37TH PL         | HARVARD BL        | 8                | 1                       | 2013-07-01T00:00:00 | 1                       | 2013-06-27T00:00:00 | 1                       | 2013-07-02T00:00:00 | 1                       | 2013-07-02T00:00:00 | 0                                    |                                | 
| GAFFEY ST       | 26TH ST           | 15               | 1                       | 2013-07-03T00:00:00 | 0                       |                     | 1                       | 2013-07-01T00:00:00 | 1                       | 2013-07-03T00:00:00 | 0                                    |                                | 
| HANCOCK ST      | GEORGE ST         | 1                | 0                       |                     | 0                       |                     | 1                       | 2013-07-03T00:00:00 | 0                       |                     | 0                                    |                                | 
| SIERRA ST       | FLORA AV          | 1                | 0                       |                     | 0                       |                     | 1                       | 2013-07-09T00:00:00 | 1                       | 2013-07-09T00:00:00 | 0                                    |                                | 
| HEWITT ST       | 4TH ST            | 14               | 0                       |                     | 0                       |                     | 1                       | 2013-07-09T00:00:00 | 1                       | 2013-07-09T00:00:00 | 1                                    | 2013-07-09T00:00:00            | 
```