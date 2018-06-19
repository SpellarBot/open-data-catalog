# VSRR - Quarterly provisional estimates for infant mortality, 2014?Quarter 1, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vsrr-quarterly-provisional-estimates-for-infant-mortality-2014aquarter-4-2015) |
| Metadata | [Link](https://data.cdc.gov/api/views/jqwm-z2g9) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/jqwm-z2g9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/jqwm-z2g9/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | jqwm-z2g9 |
| Name | VSRR - Quarterly provisional estimates for infant mortality, 2014?Quarter 1, 2016 |
| Attribution | NCHS |
| Category | NCHS |
| Tags | vital statistics rapid release, vsrr, national vital statistics system, nvss, infant mortality, causes of death |
| Created | 2016-11-21T18:32:15Z |
| Publication Date | 2017-02-27T13:31:12Z |

## Description

Provisional estimates of infant mortality (deaths of infants under 1 year per 1,000 live births), neonatal mortality (deaths of infants aged 0-27 days per 1,000 live births), postneonatal mortality (deaths of infants aged 28 days through 11 months per 1,000 live births), and death rates for the five leading causes of infant death for 2014 through the first quarter of 2016.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | year_and_quarter | Year and Quarter | text      | text        |
| Yes      | series tag     | topic            | Topic            | text      | text        |
| Yes      | series tag     | indicator        | Indicator        | text      | text        |
| No       |                | time_period      | Time Period      | text      | text        |
| Yes      | numeric metric | rate             | Rate             | number    | number      |
| Yes      | series tag     | unit             | Unit             | text      | text        |
| Yes      | series tag     | significant      | Significant      | text      | text        |
| Yes      | numeric metric | standard_error   | Standard Error   | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = time_period
```

## Data Commands

```ls
series e:jqwm-z2g9 d:2014-01-01T00:00:00.000Z t:topic="Rates by Age" t:unit="per 1,000 births" t:indicator="Infant mortality" t:year_and_quarter="2014 Q1" m:standard_error=0.04 m:rate=5.91

series e:jqwm-z2g9 d:2014-01-01T00:00:00.000Z t:topic="Rates by Age" t:unit="per 1,000 births" t:indicator="Infant mortality" t:year_and_quarter="2014 Q2" m:standard_error=0.04 m:rate=5.89

series e:jqwm-z2g9 d:2014-01-01T00:00:00.000Z t:topic="Rates by Age" t:unit="per 1,000 births" t:indicator="Infant mortality" t:year_and_quarter="2014 Q3" m:standard_error=0.04 m:rate=5.84
```

## Meta Commands

```ls
metric m:rate p:float l:Rate t:dataTypeName=number

metric m:standard_error p:float l:"Standard Error" t:dataTypeName=number

entity e:jqwm-z2g9 l:"VSRR - Quarterly provisional estimates for infant mortality, 2014?Quarter 1, 2016" t:attribution=NCHS t:url=https://data.cdc.gov/api/views/jqwm-z2g9

property e:jqwm-z2g9 t:meta.view v:id=jqwm-z2g9 v:category=NCHS v:attributionLink=https://www.cdc.gov/nchs/products/vsrr/infant-mortality-dashboard.htm v:averageRating=0 v:name="VSRR - Quarterly provisional estimates for infant mortality, 2014?Quarter 1, 2016" v:attribution=NCHS

property e:jqwm-z2g9 t:meta.view.license v:name="Public Domain"

property e:jqwm-z2g9 t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:jqwm-z2g9 t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:jqwm-z2g9 t:meta.view.metadata.custom_fields.common_core v:Publisher=NCHS v:Contact_Email=hku4@cdc.gov v:Contact_Name=NCHS v:Bureau_Code=009:000 v:Program_Code=009:020
```

## Top Records

```ls
| year_and_quarter | topic        | indicator          | time_period     | rate | unit             | significant | standard_error | 
| ================ | ============ | ================== | =============== | ==== | ================ | =========== | ============== | 
| 2014 Q1          | Rates by Age | Infant mortality   | 12 Month-ending | 5.91 | per 1,000 births |             | 0.04           | 
| 2014 Q2          | Rates by Age | Infant mortality   | 12 Month-ending | 5.89 | per 1,000 births |             | 0.04           | 
| 2014 Q3          | Rates by Age | Infant mortality   | 12 Month-ending | 5.84 | per 1,000 births |             | 0.04           | 
| 2014 Q4          | Rates by Age | Infant mortality   | 12 Month-ending | 5.82 | per 1,000 births |             | 0.04           | 
| 2015 Q1          | Rates by Age | Infant mortality   | 12 Month-ending | 5.87 | per 1,000 births |             | 0.04           | 
| 2015 Q2          | Rates by Age | Infant mortality   | 12 Month-ending | 5.88 | per 1,000 births |             | 0.04           | 
| 2015 Q3          | Rates by Age | Infant mortality   | 12 Month-ending | 5.91 | per 1,000 births |             | 0.04           | 
| 2015 Q4          | Rates by Age | Infant mortality   | 12 Month-ending | 5.9  | per 1,000 births |             | 0.04           | 
| 2016 Q1          | Rates by Age | Infant mortality   | 12 Month-ending | 5.86 | per 1,000 births |             | 0.04           | 
| 2014 Q1          | Rates by Age | Neonatal mortality | 12 Month-ending | 4.02 | per 1,000 births |             | 0.03           | 
```