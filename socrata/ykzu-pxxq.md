# FY13 Day Labor Placements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy13-day-labor-placements) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ykzu-pxxq) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ykzu-pxxq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ykzu-pxxq/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ykzu-pxxq |
| Name | FY13 Day Labor Placements |
| Attribution | City of Austin |
| Category | Workforce Development |
| Tags | labor, placement, workers, center |
| Created | 2013-10-10T20:08:46Z |
| Publication Date | 2013-10-10T20:42:56Z |

## Description

This data includes hourly numbers of persons successfully negotiating temporary, daily work with contractors at the First Workers' Day Labor Center for fiscal year 2013. The purpose is to provide the general public with relevant information about the center's daily operations.

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
series e:ykzu-pxxq d:2013-09-30T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=5 m:stayed_until_close=10 m:log_out_11_11_59am=22 m:log_out_10_10_59am=5 m:log_out_12_12_59pm=7 m:total_signed_in=109 m:total_signed_out=67 m:log_out_7_7_59am=20 m:log_out_1_1_59pm=0 m:log_out_6_6_59am=0 m:total_contractors=19 m:log_out_8_8_59am=8

series e:ykzu-pxxq d:2013-09-28T00:00:00.000Z t:weather_holiday=Rainy m:log_out_9_9_59am=8 m:stayed_until_close=8 m:log_out_11_11_59am=21 m:log_out_10_10_59am=6 m:log_out_12_12_59pm=0 m:total_signed_in=81 m:total_signed_out=47 m:log_out_7_7_59am=9 m:log_out_1_1_59pm=0 m:log_out_6_6_59am=1 m:total_contractors=11 m:log_out_8_8_59am=2

series e:ykzu-pxxq d:2013-09-27T00:00:00.000Z t:weather_holiday=Clear m:log_out_9_9_59am=10 m:stayed_until_close=9 m:log_out_11_11_59am=0 m:log_out_10_10_59am=0 m:log_out_12_12_59pm=8 m:total_signed_in=95 m:total_signed_out=58 m:log_out_7_7_59am=13 m:log_out_1_1_59pm=15 m:log_out_6_6_59am=6 m:total_contractors=21 m:log_out_8_8_59am=6
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

entity e:ykzu-pxxq l:"FY13 Day Labor Placements" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/ykzu-pxxq

property e:ykzu-pxxq t:meta.view v:id=ykzu-pxxq v:category="Workforce Development" v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="FY13 Day Labor Placements" v:attribution="City of Austin"

property e:ykzu-pxxq t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:ykzu-pxxq t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| date                | day_of_week | log_out_6_6_59am | log_out_7_7_59am | log_out_8_8_59am | log_out_9_9_59am | log_out_10_10_59am | log_out_11_11_59am | log_out_12_12_59pm | log_out_1_1_59pm | total_signed_out | total_contractors | total_signed_in | stayed_until_close | weather_holiday | 
| =================== | =========== | ================ | ================ | ================ | ================ | ================== | ================== | ================== | ================ | ================ | ================= | =============== | ================== | =============== | 
| 2013-09-30T00:00:00 | Monday      | 0                | 20               | 8                | 5                | 5                  | 22                 | 7                  | 0                | 67               | 19                | 109             | 10                 | Clear           | 
| 2013-09-28T00:00:00 | Saturday    | 1                | 9                | 2                | 8                | 6                  | 21                 | 0                  | 0                | 47               | 11                | 81              | 8                  | Rainy           | 
| 2013-09-27T00:00:00 | Friday      | 6                | 13               | 6                | 10               | 0                  | 0                  | 8                  | 15               | 58               | 21                | 95              | 9                  | Clear           | 
| 2013-09-26T00:00:00 | Thursday    | 1                | 15               | 6                | 9                | 3                  | 6                  | 19                 | 0                | 59               | 14                | 91              | 13                 | Clear           | 
| 2013-09-25T00:00:00 | Wednesday   | 5                | 8                | 7                | 13               | 3                  | 0                  | 1                  | 23               | 60               | 18                | 116             | 10                 | Clear           | 
| 2013-09-24T00:00:00 | Tuesday     | 2                | 12               | 5                | 5                | 0                  | 1                  | 0                  | 21               | 46               | 15                | 104             | 19                 | Clear           | 
| 2013-09-23T00:00:00 | Monday      | 2                | 18               | 3                | 2                | 4                  | 7                  | 1                  | 22               | 59               | 16                | 108             | 10                 | Clear           | 
| 2013-09-21T00:00:00 | Saturday    | 1                | 6                | 10               | 1                | 2                  | 20                 | 0                  | 0                | 40               | 10                | 80              | 16                 | Clear           | 
| 2013-09-20T00:00:00 | Friday      | 5                | 4                | 0                | 2                | 1                  | 1                  | 17                 | 0                | 30               | 6                 | 93              | 7                  | Rainy           | 
| 2013-09-19T00:00:00 | Thursday    | 3                | 17               | 11               | 12               | 1                  | 16                 | 0                  | 0                | 60               | 22                | 107             | 9                  | Clear           | 
```