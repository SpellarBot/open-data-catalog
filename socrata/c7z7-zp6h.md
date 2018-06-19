# 2015-08-15 Austin Sustainability Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-08-15-austin-sustainability-indicators) |
| Metadata | [Link](https://data.austintexas.gov/api/views/c7z7-zp6h) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/c7z7-zp6h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/c7z7-zp6h/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | c7z7-zp6h |
| Name | 2015-08-15 Austin Sustainability Indicators |
| Attribution | Office of Sustainability |
| Category | Environmental |
| Tags | sustainability, indicators, climate, mobility, transportation, ecosystems, zero waste |
| Created | 2015-08-17T15:19:37Z |
| Publication Date | 2017-04-20T14:44:34Z |

## Description

A full list of the ~50 indicators the Office of Sustainability tracks to measure progress on how we are doing as an organization (the City of Austin) and the broader community.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | time           | date                      | Date                      | calendar_date | calendar_date |
| No       |                | chart_date                | Chart date                | text          | text          |
| Yes      | series tag     | topic_area                | Topic Area                | text          | text          |
| Yes      | series tag     | key_performance_indicator | Key Performance Indicator | text          | text          |
| Yes      | numeric metric | value                     | Value                     | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = chart_date
```

## Data Commands

```ls
series e:c7z7-zp6h d:2012-12-31T00:00:00.000Z t:topic_area=Mobility t:key_performance_indicator="# of traffic signals retimed" m:value=286

series e:c7z7-zp6h d:2014-12-31T00:00:00.000Z t:topic_area=Mobility t:key_performance_indicator="Miles of new and improved bike facilities" m:value=34.6

series e:c7z7-zp6h d:2012-12-31T00:00:00.000Z t:topic_area="Built Environment" t:key_performance_indicator="# Multifamily units rated through AE Green Building program" m:value=709
```

## Meta Commands

```ls
metric m:value p:long l:Value t:dataTypeName=number

entity e:c7z7-zp6h l:"2015-08-15 Austin Sustainability Indicators" t:attribution="Office of Sustainability" t:url=https://data.austintexas.gov/api/views/c7z7-zp6h

property e:c7z7-zp6h t:meta.view v:id=c7z7-zp6h v:category=Environmental v:averageRating=0 v:name="2015-08-15 Austin Sustainability Indicators" v:attribution="Office of Sustainability"

property e:c7z7-zp6h t:meta.view.license v:name="Public Domain"

property e:c7z7-zp6h t:meta.view.owner v:id=4zwe-qybu v:screenName="Lewis Leff" v:lastNotificationSeenAt=1491503531 v:displayName="Lewis Leff"

property e:c7z7-zp6h t:meta.view.tableauthor v:id=4zwe-qybu v:screenName="Lewis Leff" v:roleName=publisher_stories v:lastNotificationSeenAt=1491503531 v:displayName="Lewis Leff"
```

## Top Records

```ls
| date                | chart_date | topic_area        | key_performance_indicator                                           | value | 
| =================== | ========== | ================= | =================================================================== | ===== | 
| 2012-12-31T00:00:00 | 2012       | Mobility          | # of traffic signals retimed                                        | 286   | 
| 2014-12-31T00:00:00 | 2014       | Mobility          | Miles of new and improved bike facilities                           | 34.6  | 
| 2012-12-31T00:00:00 | 2012       | Built Environment | # Multifamily units rated through AE Green Building program         | 709   | 
| 2013-12-31T00:00:00 | 2013       | Built Environment | # Multifamily units rated through AE Green Building program         | 1548  | 
| 2014-12-31T00:00:00 | 2014       | Built Environment | # Multifamily units rated through AE Green Building program         | 2067  | 
| 2012-12-31T00:00:00 | 2012       | Built Environment | # Residential properties rated through AE Green Building program    | 352   | 
| 2013-12-31T00:00:00 | 2013       | Built Environment | # Residential properties rated through AE Green Building program    | 616   | 
| 2014-12-31T00:00:00 | 2014       | Built Environment | # Residential properties rated through AE Green Building program    | 729   | 
| 2011-12-31T00:00:00 | 2011       | Built Environment | % new City Capital Improvement Projects meeting minimum Silver LEED | 75    | 
| 2012-12-31T00:00:00 | 2012       | Built Environment | % new City Capital Improvement Projects meeting minimum Silver LEED | 100   | 
```