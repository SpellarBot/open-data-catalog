# FY12 Day Labor Placements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy12-day-labor-placements) |
| Metadata | [Link](https://data.austintexas.gov/api/views/utnt-hag5) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/utnt-hag5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/utnt-hag5/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | utnt-hag5 |
| Name | FY12 Day Labor Placements |
| Attribution | City of Austin |
| Category | Workforce Development |
| Tags | labor, placement, workers, center |
| Created | 2012-10-05T17:47:36Z |
| Publication Date | 2012-10-05T17:49:21Z |

## Description

This data includes hourly numbers of persons successfully negotiating temporary, daily work with contractors at the First Workers' Day Labor Center for fiscal year 2012. The purpose is to provide the general public with relevant information about the center's daily operations.

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
series e:utnt-hag5 d:2012-09-29T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=0 m:stayed_until_close=9 m:log_out_11_11_59am=22 m:log_out_10_10_59am=3 m:log_out_12_12_59pm=0 m:total_signed_in=51 m:total_signed_out=28 m:log_out_7_7_59am=0 m:log_out_1_1_59pm=0 m:log_out_6_6_59am=2 m:total_contractors=3 m:log_out_8_8_59am=1

series e:utnt-hag5 d:2012-09-28T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=13 m:stayed_until_close=14 m:log_out_11_11_59am=3 m:log_out_10_10_59am=2 m:log_out_12_12_59pm=0 m:total_signed_in=122 m:total_signed_out=50 m:log_out_7_7_59am=8 m:log_out_1_1_59pm=16 m:log_out_6_6_59am=3 m:total_contractors=16 m:log_out_8_8_59am=5

series e:utnt-hag5 d:2012-09-27T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=4 m:stayed_until_close=9 m:log_out_11_11_59am=2 m:log_out_10_10_59am=7 m:log_out_12_12_59pm=3 m:total_signed_in=109 m:total_signed_out=57 m:log_out_7_7_59am=6 m:log_out_1_1_59pm=17 m:log_out_6_6_59am=3 m:total_contractors=13 m:log_out_8_8_59am=15
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

entity e:utnt-hag5 l:"FY12 Day Labor Placements" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/utnt-hag5

property e:utnt-hag5 t:meta.view v:id=utnt-hag5 v:category="Workforce Development" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="FY12 Day Labor Placements" v:attribution="City of Austin"

property e:utnt-hag5 t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:utnt-hag5 t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| date                | day_of_week | log_out_6_6_59am | log_out_7_7_59am | log_out_8_8_59am | log_out_9_9_59am | log_out_10_10_59am | log_out_11_11_59am | log_out_12_12_59pm | log_out_1_1_59pm | total_signed_out | total_contractors | total_signed_in | stayed_until_close | weather_holiday | 
| =================== | =========== | ================ | ================ | ================ | ================ | ================== | ================== | ================== | ================ | ================ | ================= | =============== | ================== | =============== | 
| 2012-09-29T00:00:00 | Saturday    | 2                | 0                | 1                | 0                | 3                  | 22                 | 0                  | 0                | 28               | 3                 | 51              | 9                  | Clear           | 
| 2012-09-28T00:00:00 | Friday      | 3                | 8                | 5                | 13               | 2                  | 3                  | 0                  | 16               | 50               | 16                | 122             | 14                 | Clear           | 
| 2012-09-27T00:00:00 | Thursday    | 3                | 6                | 15               | 4                | 7                  | 2                  | 3                  | 17               | 57               | 13                | 109             | 9                  | Clear           | 
| 2012-09-26T00:00:00 | Wednesday   | 17               | 10               | 5                | 3                | 4                  | 0                  | 9                  | 12               | 60               | 27                | 107             | 11                 | Clear           | 
| 2012-09-25T00:00:00 | Tuesday     | 13               | 11               | 3                | 2                | 3                  | 17                 | 0                  | 0                | 49               | 14                | 111             | 14                 | Clear           | 
| 2012-09-24T00:00:00 | Monday      | 8                | 7                | 5                | 8                | 7                  | 3                  | 0                  | 15               | 53               | 17                | 121             | 8                  | Clear           | 
| 2012-09-22T00:00:00 | Saturday    | 13               | 6                | 9                | 9                | 3                  | 16                 | 0                  | 0                | 56               | 19                | 104             | 17                 | Clear           | 
| 2012-09-21T00:00:00 | Friday      | 16               | 12               | 13               | 5                | 2                  | 12                 | 0                  | 0                | 60               | 23                | 112             | 13                 | Clear           | 
| 2012-09-20T00:00:00 | Thursday    | 17               | 16               | 4                | 15               | 1                  | 4                  | 15                 | 0                | 72               | 24                | 121             | 11                 | Clear           | 
| 2012-09-19T00:00:00 | Wednesday   | 12               | 9                | 1                | 4                | 6                  | 5                  | 18                 | 0                | 55               | 18                | 124             | 12                 | Clear           | 
```