# FY2015 Annual Report EMS Public Information Office Activities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy2015-annual-report-ems-public-information-office-activities) |
| Metadata | [Link](https://data.austintexas.gov/api/views/hghw-zjns) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/hghw-zjns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/hghw-zjns/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | hghw-zjns |
| Name | FY2015 Annual Report EMS Public Information Office Activities |
| Category | Public Safety |
| Tags | public information office, fy2015, atcems, annual report |
| Created | 2016-12-14T17:59:11Z |
| Publication Date | 2016-12-15T20:59:33Z |

## Description

** Static Data Set ** This table shows activities done by the ATCEMS Public Information Office for FY2015. It has been uploaded to support the ATCEMS FY2015 annual report. THE DATA IN THIS TABLE WILL NOT BE UPDATED.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | activity   | Activity | text      | text        |
| Yes      | numeric metric | count      | FY 2015  | number    | number      |
| Yes      | numeric metric | 2016_count | FY 2016  | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hghw-zjns d:2015-01-01T00:00:00.000Z t:activity="Media Interviews" m:count=48 m:2016_count=196

series e:hghw-zjns d:2015-01-01T00:00:00.000Z t:activity="Media Inquiries" m:count=68 m:2016_count=53

series e:hghw-zjns d:2015-01-01T00:00:00.000Z t:activity="Audio Requests" m:count=114 m:2016_count=125
```

## Meta Commands

```ls
metric m:count p:integer l:"FY 2015" t:dataTypeName=number

metric m:2016_count p:integer l:"FY 2016" t:dataTypeName=number

entity e:hghw-zjns l:"FY2015 Annual Report EMS Public Information Office Activities" t:url=https://data.austintexas.gov/api/views/hghw-zjns

property e:hghw-zjns t:meta.view v:id=hghw-zjns v:category="Public Safety" v:averageRating=0 v:name="FY2015 Annual Report EMS Public Information Office Activities"

property e:hghw-zjns t:meta.view.owner v:id=pr76-z559 v:screenName=hfunk v:displayName=hfunk

property e:hghw-zjns t:meta.view.tableauthor v:id=pr76-z559 v:screenName=hfunk v:roleName=publisher_stories v:displayName=hfunk
```

## Top Records

```ls
| activity                    | count | 2016_count | 
| =========================== | ===== | ========== | 
| Media Interviews            | 48    | 196        | 
| Media Inquiries             | 68    | 53         | 
| Audio Requests              | 114   | 125        | 
| Public Information Requests | 153   | 243        | 
| Non-Media Inquiries         | 158   | 170        | 
| Subpoenas                   | 215   | 289        | 
```