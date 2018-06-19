# Tax Liability By AGI Range

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-liability-by-agi-range-5e9bd) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3vvi-fwjs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3vvi-fwjs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3vvi-fwjs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3vvi-fwjs |
| Name | Tax Liability By AGI Range |
| Attribution | NYC Independent Budget Office (IBO) |
| Tags | tax liability by agi range |
| Created | 2014-03-06T05:46:34Z |
| Publication Date | 2014-03-06T05:47:08Z |

## Description

Number of tax filers/payers and total city tax liability by income ranges

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | income_group            | Income Group            | text      | text        |
| Yes      | numeric metric | total_nyc_pit_liability | Total NYC PIT Liability | number    | number      |
| Yes      | numeric metric | avg_pit_liability       | Avg PIT Liability       | number    | number      |
| Yes      | numeric metric | number_of_tax_payers    | Number of tax Payers    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3vvi-fwjs d:2014-03-05T21:46:36.000Z t:income_group="1st Decile" m:number_of_tax_payers=9 m:total_nyc_pit_liability=-27 m:avg_pit_liability=-78

series e:3vvi-fwjs d:2014-03-05T21:46:36.000Z t:income_group="2nd Decile" m:number_of_tax_payers=214 m:total_nyc_pit_liability=-37 m:avg_pit_liability=-107

series e:3vvi-fwjs d:2014-03-05T21:46:36.000Z t:income_group="3rd Decile" m:number_of_tax_payers=104979 m:total_nyc_pit_liability=-39.6 m:avg_pit_liability=-114
```

## Meta Commands

```ls
metric m:total_nyc_pit_liability p:float l:"Total NYC PIT Liability" t:dataTypeName=number

metric m:avg_pit_liability p:integer l:"Avg PIT Liability" t:dataTypeName=number

metric m:number_of_tax_payers p:integer l:"Number of tax Payers" t:dataTypeName=number

entity e:3vvi-fwjs l:"Tax Liability By AGI Range" t:attribution="NYC Independent Budget Office (IBO)" t:url=https://data.cityofnewyork.us/api/views/3vvi-fwjs

property e:3vvi-fwjs t:meta.view v:id=3vvi-fwjs v:averageRating=0 v:name="Tax Liability By AGI Range" v:attribution="NYC Independent Budget Office (IBO)"

property e:3vvi-fwjs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3vvi-fwjs t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | income_group | total_nyc_pit_liability | avg_pit_liability | number_of_tax_payers | 
| =========== | ============ | ======================= | ================= | ==================== | 
| 1394055996  | 1st Decile   | -27                     | -78               | 9                    | 
| 1394055996  | 2nd Decile   | -37                     | -107              | 214                  | 
| 1394055996  | 3rd Decile   | -39.6                   | -114              | 104979               | 
| 1394055996  | 4th Decile   | -2.1                    | -6                | 175647               | 
| 1394055996  | 5th Decile   | 78.400000000000006      | 226               | 286107               | 
| 1394055996  | 6th Decile   | 192.6                   | 557               | 338188               | 
| 1394055996  | 7th Decile   | 320.39999999999998      | 925               | 342856               | 
| 1394055996  | 8th Decile   | 481.7                   | 1392              | 344058               | 
| 1394055996  | 9th Decile   | 770.7                   | 2227              | 344774               | 
| 1394055996  | 10th Decile  | 4306                    | 12441             | 345169               | 
```