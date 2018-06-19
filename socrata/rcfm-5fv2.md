# 2014 State Holidays

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-state-holidays-06b60) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rcfm-5fv2) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rcfm-5fv2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rcfm-5fv2/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rcfm-5fv2 |
| Name | 2014 State Holidays |
| Attribution | Department of Human Resources Development |
| Category | Employment |
| Tags | holiday, days off |
| Created | 2012-05-16T20:30:13Z |
| Publication Date | 2012-05-16T20:36:29Z |

## Description

Stte of Hawaii Holidays for calendar year 2014

## Columns

```ls
| Included | Schema Type | Field Name               | Name          | Data Type     | Render Type   |
| ======== | =========== | ======================== | ============= | ============= | ============= |
| Yes      | series tag  | new_year_s_day           | Holiday       | text          | text          |
| No       |             | jan_14                   | Date          | calendar_date | calendar_date |
| Yes      | series tag  | wednesday                | Day of Week   | text          | text          |
| Yes      | series tag  | the_first_day_in_january | Official Data | text          | text          |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = jan_14
```

## Data Commands

```ls
series e:rcfm-5fv2 d:2014-01-01T00:00:00.000Z t:wednesday=Wednesday t:new_year_s_day="New Year?s Day" t:the_first_day_in_january="The first day in January" m:row_number.rcfm-5fv2=1

series e:rcfm-5fv2 d:2014-01-01T00:00:00.000Z t:wednesday=Monday t:new_year_s_day="Dr. Martin Luther King, Jr. Day" t:the_first_day_in_january="The third Monday in January" m:row_number.rcfm-5fv2=2

series e:rcfm-5fv2 d:2014-01-01T00:00:00.000Z t:wednesday=Monday t:new_year_s_day="Presidents? Day" t:the_first_day_in_january="The third Monday in February" m:row_number.rcfm-5fv2=3
```

## Meta Commands

```ls
metric m:row_number.rcfm-5fv2 p:long l:"Row Number"

entity e:rcfm-5fv2 l:"2014 State Holidays" t:attribution="Department of Human Resources Development" t:url=https://data.hawaii.gov/api/views/rcfm-5fv2

property e:rcfm-5fv2 t:meta.view v:id=rcfm-5fv2 v:category=Employment v:attributionLink=http://hawaii.gov/hrd v:averageRating=0 v:name="2014 State Holidays" v:attribution="Department of Human Resources Development"

property e:rcfm-5fv2 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:rcfm-5fv2 t:meta.view.owner v:id=mz35-s465 v:screenName=david.k.keane@hawaii.gov v:displayName=david.k.keane@hawaii.gov

property e:rcfm-5fv2 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| new_year_s_day                      | jan_14 | wednesday | the_first_day_in_january           | 
| =================================== | ====== | ========= | ================================== | 
| New Year?s Day                      |        | Wednesday | The first day in January           | 
| Dr. Martin Luther King, Jr. Day     |        | Monday    | The third Monday in January        | 
| Presidents? Day                     |        | Monday    | The third Monday in February       | 
| Prince Jonah Kuhio Kalanianaole Day |        | Wednesday | The twenty-sixth day in March      | 
| Good Friday                         |        | Friday    | The Friday preceding Easter Sunday | 
| Memorial Day                        |        | Monday    | The last Monday in May             | 
| King Kamehameha I Day               |        | Wednesday | The eleventh day in June           | 
| Independence Day                    |        | Friday    | The fourth day in July             | 
| Statehood Day                       |        | Friday    | The third Friday in August         | 
| Labor Day                           |        | Monday    | The first Monday in September      | 
```