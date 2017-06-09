# FY11 Day Labor Placements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy11-day-labor-placements) |
| Metadata | [Link](https://data.austintexas.gov/api/views/m9jn-qzir) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/m9jn-qzir/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/m9jn-qzir/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | m9jn-qzir |
| Name | FY11 Day Labor Placements |
| Attribution | City of Austin |
| Tags | workforce, workforce development, day labor, labor |
| Created | 2012-07-11T18:34:21Z |
| Publication Date | 2012-07-11T18:38:56Z |

## Description

This data includes hourly numbers of persons successfully negotiating temporary, daily work with contractors at the First Workers' Day Labor Center for fiscal year 2011.  The purpose is to provide the general public with relevant information about the center's daily operations.

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
series e:m9jn-qzir d:2011-09-30T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=13 m:stayed_until_close=10 m:log_out_10_10_59am=3 m:log_out_11_11_59am=2 m:log_out_12_12_59pm=19 m:total_signed_in=91 m:log_out_7_7_59am=9 m:total_signed_out=52 m:log_out_1_1_59pm=0 m:log_out_6_6_59am=2 m:total_contractors=9 m:log_out_8_8_59am=4

series e:m9jn-qzir d:2011-09-29T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=2 m:stayed_until_close=9 m:log_out_10_10_59am=0 m:log_out_11_11_59am=6 m:log_out_12_12_59pm=13 m:total_signed_in=99 m:log_out_7_7_59am=7 m:total_signed_out=50 m:log_out_1_1_59pm=11 m:log_out_6_6_59am=8 m:total_contractors=5 m:log_out_8_8_59am=3

series e:m9jn-qzir d:2011-09-28T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=4 m:stayed_until_close=10 m:log_out_10_10_59am=9 m:log_out_11_11_59am=3 m:log_out_12_12_59pm=5 m:total_signed_in=97 m:log_out_7_7_59am=4 m:total_signed_out=46 m:log_out_1_1_59pm=6 m:log_out_6_6_59am=11 m:total_contractors=11 m:log_out_8_8_59am=4
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

entity e:m9jn-qzir l:"FY11 Day Labor Placements" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/m9jn-qzir

property e:m9jn-qzir t:meta.view d:2017-06-09T13:55:27.689Z v:id=m9jn-qzir v:attributionLink=https://www.ctkodm.com/austin/ v:averageRating=0 v:name="FY11 Day Labor Placements" v:attribution="City of Austin"

property e:m9jn-qzir t:meta.view.owner d:2017-06-09T13:55:27.689Z v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:m9jn-qzir t:meta.view.tableauthor d:2017-06-09T13:55:27.689Z v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| date                | day_of_week | log_out_6_6_59am | log_out_7_7_59am | log_out_8_8_59am | log_out_9_9_59am | log_out_10_10_59am | log_out_11_11_59am | log_out_12_12_59pm | log_out_1_1_59pm | total_signed_out | total_contractors | total_signed_in | stayed_until_close | weather_holiday | 
| =================== | =========== | ================ | ================ | ================ | ================ | ================== | ================== | ================== | ================ | ================ | ================= | =============== | ================== | =============== | 
| 2011-09-30T00:00:00 | Friday      | 2                | 9                | 4                | 13               | 3                  | 2                  | 19                 | 0                | 52               | 9                 | 91              | 10                 | Clear           | 
| 2011-09-29T00:00:00 | Thursday    | 8                | 7                | 3                | 2                | 0                  | 6                  | 13                 | 11               | 50               | 5                 | 99              | 9                  | Clear           | 
| 2011-09-28T00:00:00 | Wednesday   | 11               | 4                | 4                | 4                | 9                  | 3                  | 5                  | 6                | 46               | 11                | 97              | 10                 | Clear           | 
| 2011-09-27T00:00:00 | Tuesday     | 11               | 11               | 6                | 8                | 7                  | 4                  | 9                  | 0                | 56               | 17                | 108             | 8                  | Clear           | 
| 2011-09-26T00:00:00 | Monday      | 5                | 5                | 4                | 10               | 1                  | 0                  | 2                  | 10               | 37               | 11                | 106             | 15                 | Clear           | 
| 2011-09-24T00:00:00 | Saturday    | 0                | 10               | 8                | 4                | 2                  | 21                 | 0                  | 0                | 45               | 15                | 98              | 14                 | Clear           | 
| 2011-09-23T00:00:00 | Friday      | 1                | 9                | 2                | 20               | 4                  | 2                  | 0                  | 11               | 49               | 13                | 108             | 12                 | Clear           | 
| 2011-09-22T00:00:00 | Thursday    | 9                | 1                | 11               | 4                | 3                  | 10                 | 0                  | 13               | 51               | 17                | 106             | 13                 | Clear           | 
| 2011-09-21T00:00:00 | Wednesday   | 6                | 9                | 8                | 4                | 3                  | 1                  | 0                  | 16               | 47               | 10                | 109             | 12                 | Clear           | 
| 2011-09-20T00:00:00 | Tuesday     | 7                | 8                | 5                | 4                | 2                  | 0                  | 0                  | 20               | 46               | 13                | 106             | 14                 | Clear           | 
```