# 2013 State Holidays

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-state-holidays-1b7bc) |
| Metadata | [Link](https://data.hawaii.gov/api/views/epj5-jxdm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/epj5-jxdm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/epj5-jxdm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | epj5-jxdm |
| Name | 2013 State Holidays |
| Attribution | Department of Human Resources Development |
| Category | Employment |
| Tags | holiday, days off, closed |
| Created | 2012-05-16T20:50:36Z |
| Publication Date | 2012-05-16T20:52:44Z |

## Description

State Holidays for calendar year 2013

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | series tag  | holiday       | Holiday       | text          | text          |
| Yes      | time        | date          | Date          | calendar_date | calendar_date |
| No       |             | day_of_week   | Day of Week   | text          | text          |
| No       |             | official_date | Official Date | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = day_of_week,official_date
```

## Data Commands

```ls
series e:epj5-jxdm d:2013-01-01T00:00:00.000Z t:holiday="New Year?s Day" m:row_number.epj5-jxdm=1

series e:epj5-jxdm d:2013-01-21T00:00:00.000Z t:holiday="Dr. Martin Luther King, Jr. Day" m:row_number.epj5-jxdm=2

series e:epj5-jxdm d:2013-02-18T00:00:00.000Z t:holiday="Presidents? Day" m:row_number.epj5-jxdm=3
```

## Meta Commands

```ls
metric m:row_number.epj5-jxdm p:long l:"Row Number"

entity e:epj5-jxdm l:"2013 State Holidays" t:attribution="Department of Human Resources Development" t:url=https://data.hawaii.gov/api/views/epj5-jxdm

property e:epj5-jxdm t:meta.view v:id=epj5-jxdm v:category=Employment v:attributionLink=http://hawaii.gov/hrd v:averageRating=0 v:name="2013 State Holidays" v:attribution="Department of Human Resources Development"

property e:epj5-jxdm t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:epj5-jxdm t:meta.view.owner v:id=mz35-s465 v:screenName=david.k.keane@hawaii.gov v:displayName=david.k.keane@hawaii.gov

property e:epj5-jxdm t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| holiday                             | date                | day_of_week | official_date                      | 
| =================================== | =================== | =========== | ================================== | 
| New Year?s Day                      | 2013-01-01T00:00:00 | Tuesday     | The first day in January           | 
| Dr. Martin Luther King, Jr. Day     | 2013-01-21T00:00:00 | Monday      | The third Monday in January        | 
| Presidents? Day                     | 2013-02-18T00:00:00 | Monday      | The third Monday in February       | 
| Prince Jonah Kuhio Kalanianaole Day | 2013-03-26T00:00:00 | Tuesday     | The twenty-sixth day in March      | 
| Good Friday                         | 2013-03-29T00:00:00 | Friday      | The Friday preceding Easter Sunday | 
| Memorial Day                        | 2013-05-27T00:00:00 | Monday      | The last Monday in May             | 
| King Kamehameha I Day               | 2013-06-11T00:00:00 | Tuesday     | The eleventh day in June           | 
| Independence Day                    | 2013-07-04T00:00:00 | Thursday    | The fourth day in July             | 
| Statehood Day                       | 2013-08-16T00:00:00 | Friday      | The third Friday in August         | 
| Labor Day                           | 2013-09-02T00:00:00 | Monday      | The first Monday in September      | 
```