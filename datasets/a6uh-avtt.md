# FY2015 Annual Report EMS Safety Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-ems-safety-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/a6uh-avtt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/a6uh-avtt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/a6uh-avtt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | a6uh-avtt |
| Name | FY2015 Annual Report EMS Safety Data |
| Category | Public Safety |
| Tags | safety office, fy2015, atcems, annual report |
| Created | 2016-12-29T21:41:27Z |
| Publication Date | 2016-12-29T21:43:29Z |

## Description

** Static Data Set ** This table shows activities done by the ATCEMS Safety Office for FY2015. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | injury     | Injury  | text      | text        |
| Yes      | numeric metric | fy_2015    | FY 2015 | number    | number      |
| Yes      | numeric metric | fy_2016    | FY 2016 | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a6uh-avtt d:2015-01-01T00:00:00.000Z t:injury="Back Injuries" m:fy_2016=17 m:fy_2015=18

series e:a6uh-avtt d:2015-01-01T00:00:00.000Z t:injury=Exposures m:fy_2016=26 m:fy_2015=53
```

## Meta Commands

```ls
metric m:fy_2015 p:integer l:"FY 2015" t:dataTypeName=number

metric m:fy_2016 p:integer l:"FY 2016" t:dataTypeName=number

entity e:a6uh-avtt l:"FY2015 Annual Report EMS Safety Data" t:url=https://data.austintexas.gov/api/views/a6uh-avtt

property e:a6uh-avtt t:meta.view v:id=a6uh-avtt v:category="Public Safety" v:averageRating=0 v:name="FY2015 Annual Report EMS Safety Data"

property e:a6uh-avtt t:meta.view.owner v:id=pr76-z559 v:screenName=hfunk v:displayName=hfunk

property e:a6uh-avtt t:meta.view.tableauthor v:id=pr76-z559 v:screenName=hfunk v:roleName=publisher_stories v:displayName=hfunk
```

## Top Records

```ls
| injury        | fy_2015 | fy_2016 | 
| ============= | ======= | ======= | 
| Back Injuries | 18      | 17      | 
| Exposures     | 53      | 26      | 
```