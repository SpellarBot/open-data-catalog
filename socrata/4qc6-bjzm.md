# Table 14.04 CONSUMER PRICE INDEX, FOR ALL URBAN CONSUMERS ( CPI- U), ALL ITEMS, FOR HONOLULU AND UNITED STATES 1940 TO 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-14-04-consumer-price-index-for-all-urban-consumers-cpi-u-all-items-for-honolulu-and-) |
| Metadata | [Link](https://data.hawaii.gov/api/views/4qc6-bjzm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/4qc6-bjzm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/4qc6-bjzm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 4qc6-bjzm |
| Name | Table 14.04 CONSUMER PRICE INDEX, FOR ALL URBAN CONSUMERS ( CPI- U), ALL ITEMS, FOR HONOLULU AND UNITED STATES 1940 TO 2014 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | price, index, cpi |
| Created | 2012-08-27T23:43:08Z |
| Publication Date | 2015-10-13T02:38:48Z |

## Description

* 1982-1984 average = 100.  Excludes rent before 1963							
     Source:  For Honolulu: 1940-1963 from surveys by Eugene Danaher and Hawaii State Department of Labor and Industrial Relations, cited in Hawaii State Department of Planning and Economic Development,							
U.S. Bureau of Labor Statistics, Consumer Price Index-All Urban Consumers [CPI-U] Honolulu and the United States							
Please go to the DBEDT Databook site, http://hawaii.gov/dbedt/info/economic/databook,  for the complete data source.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                      | Data Type | Render Type |
| ======== | ============== | ====================== | ========================= | ========= | =========== |
| Yes      | time           | year                   | Year                      | number    | number      |
| Yes      | numeric metric | honolulu_annualaverage | Honolulu (Annual average) | number    | number      |
| Yes      | numeric metric | honolulu_change        | Honolulu(% change)        | number    | number      |
| Yes      | numeric metric | us_annualaverage       | US (Annual average)       | number    | number      |
| Yes      | numeric metric | us_change              | US(% change)              | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4qc6-bjzm d:1940-01-01T00:00:00.000Z m:us_change=0.7 m:us_annualaverage=14 m:honolulu_annualaverage=14.7

series e:4qc6-bjzm d:1941-01-01T00:00:00.000Z m:us_change=5 m:us_annualaverage=14.7 m:honolulu_change=5.4 m:honolulu_annualaverage=15.5

series e:4qc6-bjzm d:1942-01-01T00:00:00.000Z m:us_change=10.9 m:us_annualaverage=16.3 m:honolulu_change=13.5 m:honolulu_annualaverage=17.6
```

## Meta Commands

```ls
metric m:honolulu_annualaverage p:float l:"Honolulu (Annual average)" t:dataTypeName=number

metric m:honolulu_change p:float l:"Honolulu(% change)" t:dataTypeName=number

metric m:us_annualaverage p:float l:"US (Annual average)" t:dataTypeName=number

metric m:us_change p:float l:"US(% change)" t:dataTypeName=number

entity e:4qc6-bjzm l:"Table 14.04 CONSUMER PRICE INDEX, FOR ALL URBAN CONSUMERS ( CPI- U), ALL ITEMS, FOR HONOLULU AND UNITED STATES  1940 TO 2014" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/4qc6-bjzm

property e:4qc6-bjzm t:meta.view v:id=4qc6-bjzm v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/info/economic/databook v:averageRating=0 v:name="Table 14.04 CONSUMER PRICE INDEX, FOR ALL URBAN CONSUMERS ( CPI- U), ALL ITEMS, FOR HONOLULU AND UNITED STATES  1940 TO 2014" v:attribution="Department of Economic Development and Tourism"

property e:4qc6-bjzm t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:4qc6-bjzm t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:4qc6-bjzm t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | honolulu_annualaverage | honolulu_change | us_annualaverage | us_change | 
| ==== | ====================== | =============== | ================ | ========= | 
| 1940 | 14.7                   |                 | 14.0             | 0.7       | 
| 1941 | 15.5                   | 5.4             | 14.7             | 5.0       | 
| 1942 | 17.6                   | 13.5            | 16.3             | 10.9      | 
| 1943 | 18.9                   | 7.4             | 17.3             | 6.1       | 
| 1944 | 19.2                   | 1.6             | 17.6             | 1.7       | 
| 1945 | 19.7                   | 2.6             | 18.0             | 2.3       | 
| 1946 | 21.0                   | 6.6             | 19.5             | 8.3       | 
| 1947 | 24.4                   | 16.2            | 22.3             | 14.4      | 
| 1948 | 25.7                   | 5.3             | 24.1             | 8.1       | 
| 1949 | 25.2                   | -1.9            | 23.8             | -1.2      | 
```