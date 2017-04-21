# Ten Year Capital Strategy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ten-year-capital-strategy-6f2b7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9i2s-e6hd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9i2s-e6hd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9i2s-e6hd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9i2s-e6hd |
| Name | Ten Year Capital Strategy |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | capital, strategy, expenses, uniformed forces, health and welfare |
| Created | 2013-02-14T13:43:38Z |
| Publication Date | 2013-06-21T20:06:04Z |

## Description

The table repersents the Capital Spendings allorted for the next ten years on different areas.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type | Render Type |
| ======== | ============== | ============================== | ================================ | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | capital_highlights_in_millions | Capital Highlights $ In Millions | text      | text        |
| Yes      | numeric metric | in_millions                    | $ In Millions                    | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9i2s-e6hd d:2013-02-14T05:43:39.000Z t:capital_highlights_in_millions="Construction of New Schools" m:in_millions=7884

series e:9i2s-e6hd d:2013-02-14T05:43:39.000Z t:capital_highlights_in_millions="Resurfacing of 6,228 Lane Miles of Streets, Citywide" m:in_millions=1343

series e:9i2s-e6hd d:2013-02-14T05:43:39.000Z t:capital_highlights_in_millions="Rondout West Branch Tunnel Bypass and Related Infrastructure" m:in_millions=1048
```

## Meta Commands

```ls
metric m:in_millions p:integer l:"$ In Millions" t:dataTypeName=money

entity e:9i2s-e6hd l:"Ten Year Capital Strategy" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/9i2s-e6hd

property e:9i2s-e6hd t:meta.view v:id=9i2s-e6hd v:category="City Government" v:attributionLink=http://www.nyc.gov/html/omb/downloads/pdf/sum1_13.pdf v:averageRating=0 v:name="Ten Year Capital Strategy" v:attribution="Office of the Mayor (OTM)"

property e:9i2s-e6hd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9i2s-e6hd t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | capital_highlights_in_millions                                               | in_millions | 
| =========== | ============================================================================ | =========== | 
| 1360820619  | Construction of New Schools                                                  | 7884        | 
| 1360820619  | Resurfacing of 6,228 Lane Miles of Streets, Citywide                         | 1343        | 
| 1360820619  | Rondout West Branch Tunnel Bypass and Related Infrastructure                 | 1048        | 
| 1360820619  | Sanitation Vehicle Replacement                                               | 1040        | 
| 1360820619  | Combined Sewer Overflow Reduction Projects via NYC Green Infrastructure Plan | 1026        | 
| 1360820619  | Sewer and Water Main Emergency Contracts                                     | 731         | 
| 1360820619  | Energy Efficiency Measures & Building Retrofits, Citywide                    | 650         | 
| 1360820619  | New 1,500 Bed Facility on Rikers Island                                      | 547         | 
| 1360820619  | Fire Emergency Front-Line & Support Vehicle Replacement                      | 463         | 
| 1360820619  | Continued Rehabilitation of East River Bridges                               | 253         | 
```