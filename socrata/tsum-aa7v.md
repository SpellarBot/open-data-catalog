# FY14 Day Labor Placements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy14-day-labor-placements) |
| Metadata | [Link](https://data.austintexas.gov/api/views/tsum-aa7v) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/tsum-aa7v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/tsum-aa7v/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | tsum-aa7v |
| Name | FY14 Day Labor Placements |
| Attribution | City of Austin |
| Category | Workforce Development |
| Tags | labor, placement, workers, center |
| Created | 2014-10-08T15:40:20Z |
| Publication Date | 2014-10-08T18:57:31Z |

## Description

This data includes hourly numbers of persons successfully negotiating temporary, daily work with contractors at the First Worker's  Day Labor Center for fiscal year 2014.  The purpose is to provide the general public with relevant information about the center's daily operations.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | time           | date               | Date               | calendar_date | calendar_date |
| No       |                | day_of_week        | Day of Week        | text          | text          |
| Yes      | numeric metric | log_out_6_6_59am   | Log Out 6-6:59am   | number        | number        |
| Yes      | numeric metric | log_out_7_7_59am   | Log Out 7-7:59am   | number        | number        |
| Yes      | numeric metric | log_out_8_8_59am   | Log Out 8-8:59am   | number        | number        |
| Yes      | numeric metric | log_out_9_9_59am   | Log Out 9-9:59am   | number        | number        |
| Yes      | numeric metric | log_out_10_10_59am | Log Out 10-10:59am | number        | number        |
| Yes      | numeric metric | log_out_11_11_59am | Log Out 11-11:59am | number        | number        |
| Yes      | numeric metric | log_out_12_12_59pm | Log Out 12-12:59pm | number        | number        |
| Yes      | numeric metric | log_out_1_1_59pm   | Log Out 1-1:59pm   | number        | number        |
| Yes      | numeric metric | total_signed_out   | Total Signed Out   | number        | number        |
| Yes      | numeric metric | total_contractors  | Total Contractors  | number        | number        |
| Yes      | numeric metric | total_signed_in    | Total Signed In    | number        | number        |
| Yes      | numeric metric | stayed_until_close | Stayed Until Close | number        | number        |
| Yes      | series tag     | weather_holiday    | Weather / Holiday  | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = day_of_week
```

## Data Commands

```ls
series e:tsum-aa7v d:2014-09-30T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=8 m:stayed_until_close=3 m:log_out_11_11_59am=0 m:log_out_10_10_59am=1 m:log_out_12_12_59pm=0 m:total_signed_in=103 m:total_signed_out=79 m:log_out_7_7_59am=26 m:log_out_1_1_59pm=24 m:log_out_6_6_59am=4 m:total_contractors=23 m:log_out_8_8_59am=16

series e:tsum-aa7v d:2014-09-29T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=6 m:stayed_until_close=9 m:log_out_11_11_59am=1 m:log_out_10_10_59am=11 m:log_out_12_12_59pm=9 m:total_signed_in=104 m:total_signed_out=68 m:log_out_7_7_59am=12 m:log_out_1_1_59pm=15 m:log_out_6_6_59am=2 m:total_contractors=18 m:log_out_8_8_59am=12

series e:tsum-aa7v d:2014-09-27T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=11 m:stayed_until_close=14 m:log_out_11_11_59am=25 m:log_out_10_10_59am=0 m:log_out_12_12_59pm=0 m:total_signed_in=98 m:total_signed_out=68 m:log_out_7_7_59am=19 m:log_out_1_1_59pm=0 m:log_out_6_6_59am=0 m:total_contractors=18 m:log_out_8_8_59am=13
```

## Meta Commands

```ls
metric m:log_out_6_6_59am p:integer l:"Log Out 6-6:59am" t:dataTypeName=number

metric m:log_out_7_7_59am p:integer l:"Log Out 7-7:59am" t:dataTypeName=number

metric m:log_out_8_8_59am p:integer l:"Log Out 8-8:59am" t:dataTypeName=number

metric m:log_out_9_9_59am p:integer l:"Log Out 9-9:59am" t:dataTypeName=number

metric m:log_out_10_10_59am p:integer l:"Log Out 10-10:59am" t:dataTypeName=number

metric m:log_out_11_11_59am p:integer l:"Log Out 11-11:59am" t:dataTypeName=number

metric m:log_out_12_12_59pm p:integer l:"Log Out 12-12:59pm" t:dataTypeName=number

metric m:log_out_1_1_59pm p:integer l:"Log Out 1-1:59pm" t:dataTypeName=number

metric m:total_signed_out p:integer l:"Total Signed Out" t:dataTypeName=number

metric m:total_contractors p:integer l:"Total Contractors" t:dataTypeName=number

metric m:total_signed_in p:integer l:"Total Signed In" t:dataTypeName=number

metric m:stayed_until_close p:integer l:"Stayed Until Close" t:dataTypeName=number

entity e:tsum-aa7v l:"FY14 Day Labor Placements" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/tsum-aa7v

property e:tsum-aa7v t:meta.view v:id=tsum-aa7v v:category="Workforce Development" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="FY14 Day Labor Placements" v:attribution="City of Austin"

property e:tsum-aa7v t:meta.view.license v:name="Public Domain"

property e:tsum-aa7v t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:tsum-aa7v t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| date                | day_of_week | log_out_6_6_59am | log_out_7_7_59am | log_out_8_8_59am | log_out_9_9_59am | log_out_10_10_59am | log_out_11_11_59am | log_out_12_12_59pm | log_out_1_1_59pm | total_signed_out | total_contractors | total_signed_in | stayed_until_close | weather_holiday | 
| =================== | =========== | ================ | ================ | ================ | ================ | ================== | ================== | ================== | ================ | ================ | ================= | =============== | ================== | =============== | 
| 2014-09-30T00:00:00 | Tuesday     | 4                | 26               | 16               | 8                | 1                  | 0                  | 0                  | 24               | 79               | 23                | 103             | 3                  | Clear           | 
| 2014-09-29T00:00:00 | Monday      | 2                | 12               | 12               | 6                | 11                 | 1                  | 9                  | 15               | 68               | 18                | 104             | 9                  | Clear           | 
| 2014-09-27T00:00:00 | Saturday    | 0                | 19               | 13               | 11               | 0                  | 25                 | 0                  | 0                | 68               | 18                | 98              | 14                 | Clear           | 
| 2014-09-26T00:00:00 | Friday      | 5                | 13               | 8                | 4                | 11                 | 1                  | 16                 | 2                | 60               | 19                | 108             | 9                  | Clear           | 
| 2014-09-25T00:00:00 | Thursday    | 5                | 15               | 16               | 11               | 3                  | 2                  | 3                  | 18               | 73               | 21                | 106             | 6                  | Clear           | 
| 2014-09-24T00:00:00 | Wednesday   | 9                | 16               | 12               | 10               | 5                  | 1                  | 0                  | 17               | 70               | 24                | 103             | 9                  | Clear           | 
| 2014-09-23T00:00:00 | Tuesday     | 1                | 26               | 13               | 9                | 5                  | 7                  | 17                 | 0                | 78               | 19                | 100             | 7                  | Clear           | 
| 2014-09-22T00:00:00 | Monday      | 0                | 18               | 5                | 9                | 5                  | 2                  | 3                  | 22               | 64               | 17                | 105             | 13                 | Clear           | 
| 2014-09-20T00:00:00 | Saturday    | 2                | 9                | 1                | 2                | 5                  | 26                 | 0                  | 0                | 45               | 12                | 95              | 12                 | Clear           | 
| 2014-09-19T00:00:00 | Friday      | 1                | 8                | 10               | 1                | 4                  | 16                 | 9                  | 0                | 49               | 13                | 85              | 8                  | Rainy           | 
```