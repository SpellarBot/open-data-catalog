# ARR Household Hazardous Waste Facility- Weight And Costs of Items Collected for Fiscal Year 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arr-household-hazardous-waste-facility-weight-and-costs-of-items-collected-for-fiscal-year) |
| Metadata | [Link](https://data.austintexas.gov/api/views/jnev-h7d5) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/jnev-h7d5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/jnev-h7d5/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | jnev-h7d5 |
| Name | ARR Household Hazardous Waste Facility- Weight And Costs of Items Collected for Fiscal Year 2015 |
| Tags | household, hazardous, waste, hhw, resource, recovery, weight, recycle |
| Created | 2015-09-14T18:26:27Z |
| Publication Date | 2016-02-04T20:14:09Z |

## Description

The total weight of materials processed at the HHW facility and the associated cost to dispose of or recycle them.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | description | Description | text      | text        |
| Yes      | numeric metric | oct_14      | Oct-14      | money     | text        |
| Yes      | numeric metric | nov_14      | Nov-14      | money     | text        |
| Yes      | numeric metric | dec_14      | Dec-14      | money     | text        |
| Yes      | numeric metric | jan_15      | Jan-15      | money     | text        |
| Yes      | numeric metric | feb_15      | Feb-15      | money     | text        |
| Yes      | numeric metric | mar_15      | Mar-15      | money     | text        |
| Yes      | numeric metric | apr_15      | Apr-15      | money     | text        |
| Yes      | numeric metric | may_15      | May-15      | money     | text        |
| Yes      | numeric metric | jun_15      | Jun-15      | money     | text        |
| Yes      | numeric metric | jul_15      | Jul-15      | money     | text        |
| Yes      | numeric metric | aug_15      | Aug-15      | money     | text        |
| Yes      | numeric metric | sep_15      | Sep-15      | money     | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jnev-h7d5 d:2015-01-01T00:00:00.000Z t:description="Number of Hazardous Household Items Collected" m:nov_14=1000 m:oct_14=1260 m:jul_15=2334 m:mar_15=1575 m:may_15=1638 m:jan_15=1379 m:jun_15=1964 m:dec_14=1232 m:feb_15=1287 m:apr_15=1984

series e:jnev-h7d5 d:2015-01-01T00:00:00.000Z t:description="Total Weight (lbs) of Items Collected" m:nov_14=48024.4 m:sep_15=0 m:oct_14=140600.5 m:jul_15=163157.18 m:mar_15=140303.1 m:may_15=120679.4 m:aug_15=0 m:jan_15=108584.7 m:jun_15=122240.36 m:dec_14=91371.4 m:feb_15=98128.9 m:apr_15=164786.76

series e:jnev-h7d5 d:2015-01-01T00:00:00.000Z t:description="Material Recycled /Diverted (lbs)" m:nov_14=21968 m:sep_15=0 m:oct_14=61429.6 m:jul_15=63527.28 m:mar_15=75215.3 m:may_15=58190 m:aug_15=0 m:jan_15=28346.7 m:jun_15=53703.76 m:dec_14=41557.7 m:feb_15=35247.8 m:apr_15=68887.86
```

## Meta Commands

```ls
metric m:oct_14 p:double l:Oct-14 t:dataTypeName=money

metric m:nov_14 p:double l:Nov-14 t:dataTypeName=money

metric m:dec_14 p:double l:Dec-14 t:dataTypeName=money

metric m:jan_15 p:double l:Jan-15 t:dataTypeName=money

metric m:feb_15 p:double l:Feb-15 t:dataTypeName=money

metric m:mar_15 p:double l:Mar-15 t:dataTypeName=money

metric m:apr_15 p:double l:Apr-15 t:dataTypeName=money

metric m:may_15 p:double l:May-15 t:dataTypeName=money

metric m:jun_15 p:double l:Jun-15 t:dataTypeName=money

metric m:jul_15 p:double l:Jul-15 t:dataTypeName=money

metric m:aug_15 p:double l:Aug-15 t:dataTypeName=money

metric m:sep_15 p:double l:Sep-15 t:dataTypeName=money

entity e:jnev-h7d5 l:"ARR Household Hazardous Waste Facility- Weight And Costs of Items Collected for Fiscal Year 2015" t:url=https://data.austintexas.gov/api/views/jnev-h7d5

property e:jnev-h7d5 t:meta.view v:id=jnev-h7d5 v:averageRating=0 v:name="ARR Household Hazardous Waste Facility- Weight And Costs of Items Collected for Fiscal Year 2015"

property e:jnev-h7d5 t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:jnev-h7d5 t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| description                                   | oct_14         | nov_14        | dec_14        | jan_15        | feb_15        | mar_15       | apr_15        | may_15        | jun_15        | jul_15        | aug_15        | sep_15        | 
| ============================================= | ============== | ============= | ============= | ============= | ============= | ============ | ============= | ============= | ============= | ============= | ============= | ============= | 
| Number of Hazardous Household Items Collected | 1260           | 1000          | 1232          | 1379          | 1287          | 1575         | 1984          | 1638          | 1964          | 2334          |               |               | 
| Total Weight (lbs) of Items Collected         | 140600.50      | 48024.40      | 91371.40      | 108584.70     | 98128.90      | 140303.10    | 164786.76     | 120679.40     | 122240.36     | 163157.18     | 0.00          | 0.00          | 
| Material Recycled /Diverted (lbs)             | 61429.60       | 21968.00      | 41557.70      | 28346.70      | 35247.80      | 75215.30     | 68887.86      | 58190.00      | 53703.76      | 63527.28      | 0.00          | 0.00          | 
| Weight of Hazardous Waste Disposed (lbs)      | 79170.90       | 26056.40      | 49813.70      | 80279.00      | 62881.10      | 65087.80     | 95898.90      | 62489.40      | 68536.60      | 99629.90      | 0.00          | 0.00          | 
| Estimated Disposal / Recycling Cost           | $32,577.50     | $13,197.00    | $21,551.25    | $32,131.60    | $29,199.25    | $29,141.50   | $34,421.25    | $27,680.25    | $30,816.25    | $41,907.75    | $0.00         | $0.00         | 
| Average Weight (lbs) of Hazardous Waste       | 111.5876984127 | 83.4623451327 | 80.1822164948 | 79.7743789776 | 79.0370087691 | 81.082762188 | 81.4860306679 | 80.3592391017 | 77.6874780389 | 76.5269724653 | 76.5269724653 | 76.5269724653 | 
| Cost Per Pound of Hazardous Waste             | $0.23170259    | $0.24267475   | $0.24045228   | $0.25595011   | $0.26433939   | $0.25166639  | $0.24276258   | $0.24099137   | $0.24230320   | $0.24428524   | $0.24428524   | $0.24428524   | 
| Total Estimated Cost per Hazardous Material   | $25.85515873   | $20.25420354  | $19.27999714  | $20.41826114  | $20.89259500  | $20.40580628 | $19.78175877  | $19.36588287  | $18.82392447  | $18.69441002  | $18.69441002  | $18.69441002  | 
```