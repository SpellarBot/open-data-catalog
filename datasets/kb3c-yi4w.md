# Mill Rates for 2017 Fiscal Year

## Dataset

* [Dataset URL](https://data.ct.gov/api/views/kb3c-yi4w/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/mill-rates-for-2017-fiscal-year)
* Id = kb3c-yi4w
* Name = Mill Rates for 2017 Fiscal Year
* Attribution = Office of Policy and Managment
* Attribution Link = http://www.ct.gov/opm/cwp/view.asp?A=2987&Q=385976
* Category = Government
* Tags = [mill rates, mill, tax, towns, municipal]
* Created = 2017-01-30T20:30:47Z
* Publication Date = 2017-01-30T20:33:09Z
* Rows Updated = 2017-01-30T20:30:51Z

## Description

A mill is equal to $1.00 of tax for each $1,000 of assessment. To calculate the property tax, multiply the assessment of the property by the mill rate and divide by 1,000. For example, a property with an assessed value of $50,000 located in a municipality with a mill rate of 20 mills would have a property tax bill of $1,000 per year.

Local property tax mill rates have been set for individual Connecticut municipalities for fiscal year 2016-2017. These rates are based upon the 2015 grand list and are available below. These are the most current mill rates and are reflected in each municipality's July 2016 tax bills

## Columns

```ls
| Name                                                                | Field Name                                                    | Data Type | Render Type | Schema Type    | Included | 
| =================================================================== | ============================================================= | ========= | =========== | ============== | ======== | 
| updated_at                                                          | :updated_at                                                   | meta_data | meta_data   | time           | Yes      | 
| Code                                                                | code                                                          | number    | number      | numeric metric | Yes      | 
| Service District Code                                               | service_district_code                                         | text      | number      | series tag     | Yes      | 
| Municipality                                                        | municipality                                                  | text      | text        | series tag     | Yes      | 
| FY 2017 Mill Rate                                                   | fy_2017_mill_rate                                             | number    | number      | numeric metric | Yes      | 
| FY 2017 Mill Rate - Real & Personal Property (PA 16-3 S.189 May SS) | fy_2017_mill_rate_real_personal_property_pa_16_3_s_189_may_ss | number    | number      | numeric metric | Yes      | 
| FY 2017 Mill Rate - Motor Vehicle (PA 16-3 S.189 May SS)            | fy_2017_mill_rate_motor_vehicle_pa_16_3_s_189_may_ss          | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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
series e:kb3c-yi4w d:2017-01-30T20:30:48.000Z t:municipality=Andover t:service_district_code=0 m:fy_2017_mill_rate=30.72 m:code=1

series e:kb3c-yi4w d:2017-01-30T20:30:48.000Z t:municipality=Ansonia t:service_district_code=0 m:fy_2017_mill_rate_motor_vehicle_pa_16_3_s_189_may_ss=37 m:code=2 m:fy_2017_mill_rate_real_personal_property_pa_16_3_s_189_may_ss=37.32

series e:kb3c-yi4w d:2017-01-30T20:30:48.000Z t:municipality=Ashford t:service_district_code=0 m:fy_2017_mill_rate_motor_vehicle_pa_16_3_s_189_may_ss=32 m:code=3 m:fy_2017_mill_rate_real_personal_property_pa_16_3_s_189_may_ss=32.368
```

## Meta Commands

```ls
metric m:code p:integer l:Code t:dataTypeName=number

metric m:fy_2017_mill_rate l:"FY 2017 Mill Rate" t:dataTypeName=number

metric m:fy_2017_mill_rate_real_personal_property_pa_16_3_s_189_may_ss l:"FY 2017 Mill Rate - Real & Personal Property (PA 16-3 S.189 May SS)" t:dataTypeName=number

metric m:fy_2017_mill_rate_motor_vehicle_pa_16_3_s_189_may_ss l:"FY 2017 Mill Rate - Motor Vehicle (PA 16-3 S.189 May SS)" t:dataTypeName=number

entity e:kb3c-yi4w l:"Mill Rates for 2017 Fiscal Year" t:attribution="Office of Policy and Managment" t:url=https://data.ct.gov/api/views/kb3c-yi4w

property e:kb3c-yi4w t:meta.view d:2017-03-03T14:17:26.286Z v:id=kb3c-yi4w v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?A=2987&Q=385976" v:averageRating=0 v:name="Mill Rates for 2017 Fiscal Year" v:attribution="Office of Policy and Managment"

property e:kb3c-yi4w t:meta.view.license d:2017-03-03T14:17:26.286Z v:name="Public Domain"

property e:kb3c-yi4w t:meta.view.owner d:2017-03-03T14:17:26.286Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"

property e:kb3c-yi4w t:meta.view.tableauthor d:2017-03-03T14:17:26.286Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"
```