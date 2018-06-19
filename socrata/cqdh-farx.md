# Traffic Count Study Area

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-count-study-area) |
| Metadata | [Link](https://data.austintexas.gov/api/views/cqdh-farx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/cqdh-farx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/cqdh-farx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | cqdh-farx |
| Name | Traffic Count Study Area |
| Attribution | City of Austin |
| Category | Government |
| Tags | traffic, count, transportation |
| Created | 2015-08-07T18:11:25Z |
| Publication Date | 2015-08-07T18:15:24Z |

## Description

The City of Austin (COA) collects vehicle volume counts on an ?as needed basis.? When a particular location needs a traffic study, COA adds these counts to the City of Austin Traffic Counts spreadsheet. COA does studies to install all-way stop and traffic signal controls, set speed limits, determine the need for school zones, and analyze traffic calming requests. The city does not collect any data on major highways within Austin. COA generally uses rubber tubes laid across roads that are attached to electronic traffic counters.  Note: Traffic counts taken in June, July and August can be lower than average due to local school and University closures.   C.O.A. contact:  Jerry Carden @ (512) 974-5625 (Data Collection)

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | 24_hour_volume_count_locations | 24 HOUR VOLUME COUNT LOCATIONS | text          | text          |
| Yes      | numeric metric | nb_total                       | NB TOTAL                       | number        | number        |
| Yes      | numeric metric | sb_total                       | SB TOTAL                       | number        | number        |
| Yes      | numeric metric | eb_total                       | EB TOTAL                       | number        | number        |
| Yes      | numeric metric | wb_totoal                      | WB TOTOAL                      | number        | number        |
| Yes      | numeric metric | total_volume                   | TOTAL VOLUME                   | number        | number        |
| Yes      | time           | date                           | DATE                           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cqdh-farx d:2005-09-27T00:00:00.000Z t:24_hour_volume_count_locations="10th St East, 1000 blk - West of Waller St" m:eb_total=101 m:wb_totoal=115 m:total_volume=216

series e:cqdh-farx d:2005-09-27T00:00:00.000Z t:24_hour_volume_count_locations="10th St East, 1200 blk - West of Navasota St" m:eb_total=103 m:wb_totoal=55 m:total_volume=158

series e:cqdh-farx d:2009-02-26T00:00:00.000Z t:24_hour_volume_count_locations="10th St East, 600 blk - East of Red River St" m:wb_totoal=2240 m:total_volume=2240
```

## Meta Commands

```ls
metric m:nb_total p:integer l:"NB TOTAL" t:dataTypeName=number

metric m:sb_total p:integer l:"SB TOTAL" t:dataTypeName=number

metric m:eb_total p:integer l:"EB TOTAL" t:dataTypeName=number

metric m:wb_totoal p:integer l:"WB TOTOAL" t:dataTypeName=number

metric m:total_volume p:integer l:"TOTAL VOLUME" t:dataTypeName=number

entity e:cqdh-farx l:"Traffic Count Study Area" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/cqdh-farx

property e:cqdh-farx t:meta.view v:id=cqdh-farx v:category=Government v:averageRating=0 v:name="Traffic Count Study Area" v:attribution="City of Austin"

property e:cqdh-farx t:meta.view.license v:name="Public Domain"

property e:cqdh-farx t:meta.view.owner v:id=jsyn-mk6f v:screenName=jhrncir v:displayName=jhrncir

property e:cqdh-farx t:meta.view.tableauthor v:id=jsyn-mk6f v:screenName=jhrncir v:roleName=editor v:displayName=jhrncir
```

## Top Records

```ls
| 24_hour_volume_count_locations                    | nb_total | sb_total | eb_total | wb_totoal | total_volume | date                | 
| ================================================= | ======== | ======== | ======== | ========= | ============ | =================== | 
| 10th St East, 1000 blk - West of Waller St        |          |          | 101      | 115       | 216          | 2005-09-27T00:00:00 | 
| 10th St East, 1200 blk - West of Navasota St      |          |          | 103      | 55        | 158          | 2005-09-27T00:00:00 | 
| 10th St East, 600 blk - East of Red River St      |          |          |          | 2240      | 2240         | 2009-02-26T00:00:00 | 
| 10th St East, 700 blk - West of IH35 WSR 1-way WB |          |          |          | 1599      | 1599         | 2005-07-06T00:00:00 | 
| 10th St West, 1000 blk - West of N. Lamar Blvd    |          |          | 373      | 288       | 661          | 2001-01-24T00:00:00 | 
| 10th St West, 1300 blk - West of Lorrain St       |          |          | 383      | 314       | 697          | 2007-06-05T00:00:00 | 
| 10th St West, 600 blk - West of Nueces St         |          |          | 1591     | 431       | 2022         | 2001-01-11T00:00:00 | 
| 10th St West, 800 blk - West of West Ave          |          |          | 2163     | 925       | 3088         | 2003-01-30T00:00:00 | 
| 10th St West, 900 blk - East of N. Lamar Blvd     |          |          | 2254     | 940       | 3194         | 2003-01-30T00:00:00 | 
| 11th St East, 1100 blk - East of Waller St        |          |          | 4185     | 3788      | 7973         | 2006-06-26T00:00:00 | 
```