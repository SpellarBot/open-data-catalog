# Unemployment Insurance Replacement Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unemployment-insurance-replacement-rates) |
| Metadata | [Link](https://data.iowa.gov/api/views/4hiw-uacc) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/4hiw-uacc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/4hiw-uacc/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 4hiw-uacc |
| Name | Unemployment Insurance Replacement Rates |
| Attribution | Iowa Workforce Development, Labor Market Information Division |
| Category | Economy |
| Tags | unemployment insurance, ui, replacement rate |
| Created | 2016-12-05T20:01:13Z |
| Publication Date | 2017-04-13T16:40:58Z |

## Description

The Replacement Rate is the ratio of the claimants' weekly benefit amount to the claimants' average weekly wage.  This represents an estimate of the portion of normal wages replaced by Unemployment Insurance benefit payments.  The calculations are based on sample data used for the Benefit Accuracy Measurement program.

## Columns

```ls
| Included | Schema Type    | Field Name | Name                   | Data Type | Render Type |
| ======== | ============== | ========== | ====================== | ========= | =========== |
| Yes      | time           | year       | Year                   | number    | number      |
| Yes      | numeric metric | aww        | Average Weekly Wage    | money     | money       |
| Yes      | numeric metric | awb        | Weekly Benefit Amount  | money     | money       |
| Yes      | numeric metric | ratio2     | Replacement Ratio      | percent   | percent     |
| Yes      | numeric metric | ratio1     | Replacement Ratio (WA) | percent   | percent     |
| Yes      | numeric metric | sample     | Sample Size            | number    | number      |
| Yes      | numeric metric | valid      | Valid Cases            | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4hiw-uacc d:1997-01-01T00:00:00.000Z m:ratio2=46.3 m:aww=424.9 m:awb=196.53 m:ratio1=51.1 m:valid=474 m:sample=483

series e:4hiw-uacc d:1998-01-01T00:00:00.000Z m:ratio2=49.1 m:aww=419.08 m:awb=205.66 m:ratio1=52.5 m:valid=467 m:sample=480

series e:4hiw-uacc d:1999-01-01T00:00:00.000Z m:ratio2=44.7 m:aww=484.76 m:awb=216.56 m:ratio1=50.5 m:valid=461 m:sample=480
```

## Meta Commands

```ls
metric m:aww p:double l:"Average Weekly Wage" d:"The average weekly wage is based on hourly wage of usual job of claimant, normalized to a 40-hour work week and may not equal the claimant's actual average weekly wage. [AWW]" t:dataTypeName=money

metric m:awb p:double l:"Weekly Benefit Amount" d:"Average of the weekly benefit amounts for claimants in sample. [WBA]" t:dataTypeName=money

metric m:ratio2 p:float l:"Replacement Ratio" d:"Ratio of: Weighted Average WBA / Weighted Average (Normal Hourly Wage x 40 Hrs.)" t:dataTypeName=percent

metric m:ratio1 p:float l:"Replacement Ratio (WA)" d:"Weighted Average of: [WBA / (Normal Hourly Wage x 40 Hrs.)] (Ratios greater than or equal to 2 have been excluded as outliers.)" t:dataTypeName=percent

metric m:sample p:integer l:"Sample Size" t:dataTypeName=number

metric m:valid p:integer l:"Valid Cases" t:dataTypeName=number

entity e:4hiw-uacc l:"Unemployment Insurance Replacement Rates" t:attribution="Iowa Workforce Development, Labor Market Information Division" t:url=https://data.iowa.gov/api/views/4hiw-uacc

property e:4hiw-uacc t:meta.view v:id=4hiw-uacc v:category=Economy v:attributionLink=https://www.oui.doleta.gov/unemploy/ui_replacement_rates.asp v:averageRating=0 v:name="Unemployment Insurance Replacement Rates" v:attribution="Iowa Workforce Development, Labor Market Information Division"

property e:4hiw-uacc t:meta.view.license v:name="Public Domain"

property e:4hiw-uacc t:meta.view.owner v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"

property e:4hiw-uacc t:meta.view.tableauthor v:id=fipn-jtty v:profileImageUrlMedium=/api/users/fipn-jtty/profile_images/THUMB v:profileImageUrlLarge=/api/users/fipn-jtty/profile_images/LARGE v:screenName="Unemployment Insurance Statistics" v:profileImageUrlSmall=/api/users/fipn-jtty/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491494200 v:displayName="Unemployment Insurance Statistics"
```

## Top Records

```ls
| year | aww    | awb    | ratio2 | ratio1 | sample | valid | 
| ==== | ====== | ====== | ====== | ====== | ====== | ===== | 
| 1997 | 424.90 | 196.53 | 46.3   | 51.1   | 483    | 474   | 
| 1998 | 419.08 | 205.66 | 49.1   | 52.5   | 480    | 467   | 
| 1999 | 484.76 | 216.56 | 44.7   | 50.5   | 480    | 461   | 
| 2000 | 487.38 | 229.30 | 47.0   | 51.8   | 480    | 470   | 
| 2001 | 497.20 | 240.98 | 48.5   | 52.2   | 480    | 468   | 
| 2002 | 525.89 | 245.63 | 46.7   | 50.8   | 480    | 464   | 
| 2003 | 518.65 | 251.46 | 48.5   | 52.8   | 480    | 473   | 
| 2004 | 505.44 | 250.96 | 49.7   | 53.3   | 480    | 473   | 
| 2005 | 542.98 | 257.16 | 47.4   | 51.8   | 480    | 463   | 
| 2006 | 546.03 | 268.40 | 49.2   | 53.5   | 480    | 470   | 
```