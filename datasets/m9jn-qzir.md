# FY11 Day Labor Placements

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/m9jn-qzir/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/fy11-day-labor-placements)
* [Metadata URL](https://data.austintexas.gov/api/views/m9jn-qzir)
* Id = m9jn-qzir
* Name = FY11 Day Labor Placements
* Attribution = City of Austin
* [Attribution Link](https://www.ctkodm.com/austin/)
* Tags = [workforce, workforce development, day labor, labor]
* Created = 2012-07-11T18:34:21Z
* Publication Date = 2012-07-11T18:38:56Z
* Rows Updated = 2012-07-11T18:34:25Z

## Description

This data includes hourly numbers of persons successfully negotiating temporary, daily work with contractors at the First Workers' Day Labor Center for fiscal year 2011.  The purpose is to provide the general public with relevant information about the center's daily operations.

## Columns

```ls
| Name               | Field Name         | Data Type     | Render Type   | Schema Type    | Included | 
| ================== | ================== | ============= | ============= | ============== | ======== | 
| Date               | date               | calendar_date | calendar_date | time           | Yes      | 
| Day of Week        | day_of_week        | text          | text          | series tag     | Yes      | 
| Log Out 6-6:59am   | log_out_6_6_59am   | number        | number        | numeric metric | Yes      | 
| Log Out 7-7:59am   | log_out_7_7_59am   | number        | number        | numeric metric | Yes      | 
| Log Out 8-8:59am   | log_out_8_8_59am   | number        | number        | numeric metric | Yes      | 
| Log Out 9-9:59am   | log_out_9_9_59am   | number        | number        | numeric metric | Yes      | 
| Log Out 10-10:59am | log_out_10_10_59am | number        | number        | numeric metric | Yes      | 
| Log Out 11-11:59am | log_out_11_11_59am | number        | number        | numeric metric | Yes      | 
| Log Out 12-12:59pm | log_out_12_12_59pm | number        | number        | numeric metric | Yes      | 
| Log Out 1-1:59pm   | log_out_1_1_59pm   | number        | number        | numeric metric | Yes      | 
| Total Signed Out   | total_signed_out   | number        | number        | numeric metric | Yes      | 
| Total Contractors  | total_contractors  | number        | number        | numeric metric | Yes      | 
| Total Signed In    | total_signed_in    | number        | number        | numeric metric | Yes      | 
| Stayed Until Close | stayed_until_close | number        | number        | numeric metric | Yes      | 
| Weather / Holiday  | weather_holiday    | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:m9jn-qzir d:2011-09-30T00:00:00.000Z t:day_of_week=Friday t:weather_holiday=Clear m:log_out_9_9_59am=13 m:stayed_until_close=10 m:log_out_11_11_59am=2 m:log_out_10_10_59am=3 m:log_out_12_12_59pm=19 m:total_signed_in=91 m:total_signed_out=52 m:log_out_7_7_59am=9 m:log_out_1_1_59pm=0 m:log_out_6_6_59am=2 m:total_contractors=9 m:log_out_8_8_59am=4

series e:m9jn-qzir d:2011-09-29T00:00:00.000Z t:day_of_week=Thursday t:weather_holiday=Clear m:log_out_9_9_59am=2 m:stayed_until_close=9 m:log_out_11_11_59am=6 m:log_out_10_10_59am=0 m:log_out_12_12_59pm=13 m:total_signed_in=99 m:total_signed_out=50 m:log_out_7_7_59am=7 m:log_out_1_1_59pm=11 m:log_out_6_6_59am=8 m:total_contractors=5 m:log_out_8_8_59am=3

series e:m9jn-qzir d:2011-09-28T00:00:00.000Z t:day_of_week=Wednesday t:weather_holiday=Clear m:log_out_9_9_59am=4 m:stayed_until_close=10 m:log_out_11_11_59am=3 m:log_out_10_10_59am=9 m:log_out_12_12_59pm=5 m:total_signed_in=97 m:total_signed_out=46 m:log_out_7_7_59am=4 m:log_out_1_1_59pm=6 m:log_out_6_6_59am=11 m:total_contractors=11 m:log_out_8_8_59am=4
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

property e:m9jn-qzir t:meta.view d:2017-03-08T00:40:45.848Z v:id=m9jn-qzir v:attributionLink=https://www.ctkodm.com/austin/ v:averageRating=0 v:name="FY11 Day Labor Placements" v:attribution="City of Austin"

property e:m9jn-qzir t:meta.view.owner d:2017-03-08T00:40:45.848Z v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx

property e:m9jn-qzir t:meta.view.tableauthor d:2017-03-08T00:40:45.848Z v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```