# Cook County Clerk - Tax code Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-clerk-tax-code-rates-f7036) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/8vrk-e2ck) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8vrk-e2ck/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8vrk-e2ck/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 8vrk-e2ck |
| Name | Cook County Clerk - Tax code Rates |
| Attribution | Cook County Clerk |
| Category | Property & Taxation |
| Created | 2014-09-11T16:39:02Z |
| Publication Date | 2014-10-09T22:49:19Z |

## Description

Tax code rates for Tax Years 2006 through 2013. Data is updated yearly. For more information on Tax codes visit the Cook County Clerk's website at: http://www.cookcountyclerk.com/tsd/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | tax_code           | Tax code           | text      | number      |
| Yes      | numeric metric | tax_code_rate_2006 | Tax code Rate 2006 | number    | number      |
| Yes      | numeric metric | tax_code_rate_2007 | Tax code Rate 2007 | number    | number      |
| Yes      | numeric metric | tax_code_rate_2008 | Tax code Rate 2008 | number    | number      |
| Yes      | numeric metric | tax_code_rate_2009 | Tax code Rate 2009 | number    | number      |
| Yes      | numeric metric | tax_code_rate_2010 | Tax code Rate 2010 | number    | number      |
| Yes      | numeric metric | tax_code_rate_2011 | Tax code Rate 2011 | number    | number      |
| Yes      | numeric metric | tax_code_rate_2012 | Tax code Rate 2012 | number    | number      |
| Yes      | numeric metric | tax_code_rate_2013 | Tax code Rate 2013 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8vrk-e2ck d:2014-09-11T09:39:06.000Z t:tax_code=10001 m:tax_code_rate_2011=6.077 m:tax_code_rate_2010=5.362 m:tax_code_rate_2009=4.885 m:tax_code_rate_2006=5.525 m:tax_code_rate_2007=5.023 m:tax_code_rate_2008=4.795 m:tax_code_rate_2012=6.894 m:tax_code_rate_2013=7.682

series e:8vrk-e2ck d:2014-09-11T09:39:06.000Z t:tax_code=10002 m:tax_code_rate_2011=7.305 m:tax_code_rate_2010=6.413 m:tax_code_rate_2009=5.94 m:tax_code_rate_2006=6.704 m:tax_code_rate_2007=6.117 m:tax_code_rate_2008=5.818 m:tax_code_rate_2012=8.38 m:tax_code_rate_2013=9.264

series e:8vrk-e2ck d:2014-09-11T09:39:06.000Z t:tax_code=10003 m:tax_code_rate_2011=5.918 m:tax_code_rate_2010=5.21 m:tax_code_rate_2009=4.796 m:tax_code_rate_2006=5.403 m:tax_code_rate_2007=4.906 m:tax_code_rate_2008=4.651 m:tax_code_rate_2012=6.673 m:tax_code_rate_2013=7.43
```

## Meta Commands

```ls
metric m:tax_code_rate_2006 p:float l:"Tax code Rate 2006" t:dataTypeName=number

metric m:tax_code_rate_2007 p:float l:"Tax code Rate 2007" t:dataTypeName=number

metric m:tax_code_rate_2008 p:float l:"Tax code Rate 2008" t:dataTypeName=number

metric m:tax_code_rate_2009 p:float l:"Tax code Rate 2009" t:dataTypeName=number

metric m:tax_code_rate_2010 p:float l:"Tax code Rate 2010" t:dataTypeName=number

metric m:tax_code_rate_2011 p:float l:"Tax code Rate 2011" t:dataTypeName=number

metric m:tax_code_rate_2012 p:float l:"Tax code Rate 2012" t:dataTypeName=number

metric m:tax_code_rate_2013 p:float l:"Tax code Rate 2013" t:dataTypeName=number

entity e:8vrk-e2ck l:"Cook County Clerk - Tax code Rates" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/8vrk-e2ck

property e:8vrk-e2ck t:meta.view v:id=8vrk-e2ck v:category="Property & Taxation" v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Cook County Clerk - Tax code Rates" v:attribution="Cook County Clerk"

property e:8vrk-e2ck t:meta.view.license v:name="Public Domain"

property e:8vrk-e2ck t:meta.view.owner v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:displayName="Cook County Webmaster"

property e:8vrk-e2ck t:meta.view.tableauthor v:id=d4g2-kc7i v:screenName="Cook County Webmaster" v:roleName=administrator v:displayName="Cook County Webmaster"
```

## Top Records

```ls
| :updated_at | tax_code | tax_code_rate_2006 | tax_code_rate_2007 | tax_code_rate_2008 | tax_code_rate_2009 | tax_code_rate_2010 | tax_code_rate_2011 | tax_code_rate_2012 | tax_code_rate_2013 | 
| =========== | ======== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | ================== | 
| 1410428346  | 10001    | 5.525              | 5.023              | 4.795              | 4.885              | 5.362              | 6.077              | 6.894              | 7.682              | 
| 1410428346  | 10002    | 6.704              | 6.117              | 5.818              | 5.940              | 6.413              | 7.305              | 8.38               | 9.264              | 
| 1410428346  | 10003    | 5.403              | 4.906              | 4.651              | 4.796              | 5.210              | 5.918              | 6.673              | 7.43               | 
| 1410428346  | 10004    | 7.659              | 7.022              | 6.901              | 7.329              | 7.536              | 8.483              | 9.75               | 10.952             | 
| 1410428346  | 10005    | 6.599              | 5.998              | 5.730              | 5.788              | 6.290              | 7.136              | 8.064              | 8.948              | 
| 1410428346  | 10009    | 4.971              | 4.529              | 4.285              | 4.353              | 4.761              | 5.404              | 6.127              | 6.827              | 
| 1410428346  | 10012    | 5.227              | 4.805              | 4.698              | 4.741              | 5.190              | 5.900              | 6.669              | 7.45               | 
| 1410428346  | 10013    | 5.926              | 5.434              | 5.368              | 5.742              | 5.884              | 6.582              | 7.497              | 8.515              | 
| 1410428346  | 10015    | 5.214              | 4.749              | 4.508              | 4.676              | 5.086              | 5.788              | 6.694              | 7.415              | 
| 1410428346  | 10018    | 4.591              | 4.169              | 3.943              | 4.023              | 4.396              | 4.986              | 5.658              | 6.297              | 
```