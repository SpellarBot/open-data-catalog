# Cook County Clerk - Tax Agency Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-clerk-tax-agency-rates-9e966) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/9sgn-ibhu) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9sgn-ibhu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/9sgn-ibhu/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 9sgn-ibhu |
| Name | Cook County Clerk - Tax Agency Rates |
| Attribution | Cook County Clerk |
| Category | Property & Taxation |
| Tags | tax agencies, property |
| Created | 2014-09-11T15:59:30Z |
| Publication Date | 2014-09-11T16:31:34Z |

## Description

Tax Agency rates for Tax Years 2006 through 2013. Data is updated yearly. For more information on Tax agencies visit the Cook County Clerk's website at: http://www.cookcountyclerk.com/tsd/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | agency           | Agency           | text      | text        |
| Yes      | series tag     | agency_name      | Agency Name      | text      | text        |
| Yes      | numeric metric | agency_rate_2006 | Agency Rate 2006 | number    | number      |
| Yes      | numeric metric | agency_rate_2007 | Agency Rate 2007 | number    | number      |
| Yes      | numeric metric | agency_rate_2008 | Agency Rate 2008 | number    | number      |
| Yes      | numeric metric | agency_rate_2009 | Agency Rate 2009 | number    | number      |
| Yes      | numeric metric | agency_rate_2010 | Agency Rate 2010 | number    | number      |
| Yes      | numeric metric | agency_rate_2011 | Agency Rate 2011 | number    | number      |
| Yes      | numeric metric | agency_rate_2012 | Agency Rate 2012 | number    | number      |
| Yes      | numeric metric | agency_rate_2013 | Agency Rate 2013 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9sgn-ibhu d:2014-09-11T08:59:34.000Z t:agency=010010000 t:agency_name="COUNTY OF COOK" m:agency_rate_2011=0.462 m:agency_rate_2010=0.423 m:agency_rate_2013=0.56 m:agency_rate_2012=0.531 m:agency_rate_2006=0.5 m:agency_rate_2008=0.415 m:agency_rate_2007=0.446 m:agency_rate_2009=0.394

series e:9sgn-ibhu d:2014-09-11T08:59:34.000Z t:agency=010010001 t:agency_name="CONSOLIDATED ELECTIONS" m:agency_rate_2011=0.025 m:agency_rate_2010=0 m:agency_rate_2013=0.031 m:agency_rate_2012=0 m:agency_rate_2006=0 m:agency_rate_2008=0 m:agency_rate_2007=0.012 m:agency_rate_2009=0.021

series e:9sgn-ibhu d:2014-09-11T08:59:34.000Z t:agency=010020000 t:agency_name="FOREST PRESERVE DISTRICT OF COOK COUNTY" m:agency_rate_2011=0.058 m:agency_rate_2010=0.051 m:agency_rate_2013=0.069 m:agency_rate_2012=0.063 m:agency_rate_2006=0.057 m:agency_rate_2008=0.051 m:agency_rate_2007=0.053 m:agency_rate_2009=0.049
```

## Meta Commands

```ls
metric m:agency_rate_2006 p:float l:"Agency Rate 2006" t:dataTypeName=number

metric m:agency_rate_2007 p:float l:"Agency Rate 2007" t:dataTypeName=number

metric m:agency_rate_2008 p:float l:"Agency Rate 2008" t:dataTypeName=number

metric m:agency_rate_2009 p:float l:"Agency Rate 2009" t:dataTypeName=number

metric m:agency_rate_2010 p:float l:"Agency Rate 2010" t:dataTypeName=number

metric m:agency_rate_2011 p:float l:"Agency Rate 2011" t:dataTypeName=number

metric m:agency_rate_2012 p:float l:"Agency Rate 2012" t:dataTypeName=number

metric m:agency_rate_2013 p:float l:"Agency Rate 2013" t:dataTypeName=number

entity e:9sgn-ibhu l:"Cook County Clerk - Tax Agency Rates" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/9sgn-ibhu

property e:9sgn-ibhu t:meta.view v:id=9sgn-ibhu v:category="Property & Taxation" v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Cook County Clerk - Tax Agency Rates" v:attribution="Cook County Clerk"

property e:9sgn-ibhu t:meta.view.license v:name="Public Domain"

property e:9sgn-ibhu t:meta.view.owner v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:displayName="Cook County Webmaster"

property e:9sgn-ibhu t:meta.view.tableauthor v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:roleName=administrator v:displayName="Cook County Webmaster"
```

## Top Records

```ls
| :updated_at | agency    | agency_name                             | agency_rate_2006 | agency_rate_2007 | agency_rate_2008 | agency_rate_2009 | agency_rate_2010 | agency_rate_2011 | agency_rate_2012 | agency_rate_2013 | 
| =========== | ========= | ======================================= | ================ | ================ | ================ | ================ | ================ | ================ | ================ | ================ | 
| 1410425974  | 010010000 | COUNTY OF COOK                          | 0.500            | 0.446            | 0.415            | 0.394            | 0.423            | 0.462            | 0.531            | 0.56             | 
| 1410425974  | 010010001 | CONSOLIDATED ELECTIONS                  | 0.000            | 0.012            | 0.000            | 0.021            | 0.000            | 0.025            | 0.000            | 0.031            | 
| 1410425974  | 010020000 | FOREST PRESERVE DISTRICT OF COOK COUNTY | 0.057            | 0.053            | 0.051            | 0.049            | 0.051            | 0.058            | 0.063            | 0.069            | 
| 1410425974  | 020010000 | TOWN BARRINGTON                         | 0.025            | 0.021            | 0.020            | 0.020            | 0.022            | 0.026            | 0.028            | 0.032            | 
| 1410425974  | 020010002 | GENERAL ASSISTANCE BARRINGTON           | 0.002            | 0.002            | 0.002            | 0.002            | 0.001            | 0.000            | 0.001            | 0.001            | 
| 1410425974  | 020010003 | ROAD AND BRIDGE BARRINGTON              | 0.000            | 0.000            | 0.000            | 0.000            | 0.000            | 0.000            | 0.000            | 0.0              | 
| 1410425974  | 020020000 | TOWN BERWYN                             | 0.031            | 0.032            | 0.031            | 0.032            | 0.032            | 0.042            | 0.048            | 0.053            | 
| 1410425974  | 020020002 | GENERAL ASSISTANCE BERWYN               | 0.025            | 0.026            | 0.025            | 0.026            | 0.028            | 0.037            | 0.042            | 0.046            | 
| 1410425974  | 020020004 | BERWYN TOWNSHIP COMM MENTAL HEALTH DIST | 0.051            | 0.048            | 0.046            | 0.046            | 0.048            | 0.063            | 0.070            | 0.076            | 
| 1410425974  | 020020005 | PUBLIC HEALTH BERWYN                    | 0.060            | 0.061            | 0.059            | 0.061            | 0.060            | 0.078            | 0.089            | 0.095            | 
```