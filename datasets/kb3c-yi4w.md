# Mill Rates for 2017 Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mill-rates-for-2017-fiscal-year) |
| Metadata | [Link](https://data.ct.gov/api/views/kb3c-yi4w) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/kb3c-yi4w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/kb3c-yi4w/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | kb3c-yi4w |
| Name | Mill Rates for 2017 Fiscal Year |
| Attribution | Office of Policy and Managment |
| Category | Government |
| Tags | mill rates, mill, tax, towns, municipal |
| Created | 2017-01-30T20:30:47Z |
| Publication Date | 2017-01-30T20:33:09Z |
| Rows Updated | 2017-01-30T20:30:51Z |

## Description

A mill is equal to $1.00 of tax for each $1,000 of assessment. To calculate the property tax, multiply the assessment of the property by the mill rate and divide by 1,000. For example, a property with an assessed value of $50,000 located in a municipality with a mill rate of 20 mills would have a property tax bill of $1,000 per year.

Local property tax mill rates have been set for individual Connecticut municipalities for fiscal year 2016-2017. These rates are based upon the 2015 grand list and are available below. These are the most current mill rates and are reflected in each municipality's July 2016 tax bills

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                                | Data Type | Render Type |
| ======== | ============== | ============================================================= | =================================================================== | ========= | =========== |
| Yes      | series tag     | code                                                          | Code                                                                | text      | number      |
| Yes      | series tag     | service_district_code                                         | Service District Code                                               | text      | number      |
| Yes      | series tag     | municipality                                                  | Municipality                                                        | text      | text        |
| Yes      | numeric metric | fy_2017_mill_rate                                             | FY 2017 Mill Rate                                                   | number    | number      |
| Yes      | numeric metric | fy_2017_mill_rate_real_personal_property_pa_16_3_s_189_may_ss | FY 2017 Mill Rate - Real & Personal Property (PA 16-3 S.189 May SS) | number    | number      |
| Yes      | numeric metric | fy_2017_mill_rate_motor_vehicle_pa_16_3_s_189_may_ss          | FY 2017 Mill Rate - Motor Vehicle (PA 16-3 S.189 May SS)            | number    | number      |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kb3c-yi4w d:2017-01-01T00:00:00.000Z t:municipality=Andover t:service_district_code=0 t:code=1 m:fy_2017_mill_rate=30.72

series e:kb3c-yi4w d:2017-01-01T00:00:00.000Z t:municipality=Ansonia t:service_district_code=0 t:code=2 m:fy_2017_mill_rate_motor_vehicle_pa_16_3_s_189_may_ss=37 m:fy_2017_mill_rate_real_personal_property_pa_16_3_s_189_may_ss=37.32

series e:kb3c-yi4w d:2017-01-01T00:00:00.000Z t:municipality=Ashford t:service_district_code=0 t:code=3 m:fy_2017_mill_rate_motor_vehicle_pa_16_3_s_189_may_ss=32 m:fy_2017_mill_rate_real_personal_property_pa_16_3_s_189_may_ss=32.368
```

## Meta Commands

```ls
metric m:fy_2017_mill_rate p:float l:"FY 2017 Mill Rate" t:dataTypeName=number

metric m:fy_2017_mill_rate_real_personal_property_pa_16_3_s_189_may_ss p:float l:"FY 2017 Mill Rate - Real & Personal Property (PA 16-3 S.189 May SS)" t:dataTypeName=number

metric m:fy_2017_mill_rate_motor_vehicle_pa_16_3_s_189_may_ss p:float l:"FY 2017 Mill Rate - Motor Vehicle (PA 16-3 S.189 May SS)" t:dataTypeName=number

entity e:kb3c-yi4w l:"Mill Rates for 2017 Fiscal Year" t:attribution="Office of Policy and Managment" t:url=https://data.ct.gov/api/views/kb3c-yi4w

property e:kb3c-yi4w t:meta.view v:id=kb3c-yi4w v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?A=2987&Q=385976" v:averageRating=0 v:name="Mill Rates for 2017 Fiscal Year" v:attribution="Office of Policy and Managment"

property e:kb3c-yi4w t:meta.view.license v:name="Public Domain"

property e:kb3c-yi4w t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"

property e:kb3c-yi4w t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"
```