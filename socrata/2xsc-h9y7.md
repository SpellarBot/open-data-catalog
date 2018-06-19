# Risk Management - Employee Healthcare Enrollment, by Month - 2007 through August 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/risk-management-employee-healthcare-enrollment-by-month-2007-through-august-2012-588e0) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/2xsc-h9y7) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/2xsc-h9y7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/2xsc-h9y7/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 2xsc-h9y7 |
| Name | Risk Management - Employee Healthcare Enrollment, by Month - 2007 through August 2012 |
| Attribution | Cook County Department of Risk Management |
| Category | Finance & Administration |
| Created | 2012-09-24T17:41:42Z |
| Publication Date | 2014-10-09T22:35:03Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | month                    | MONTH                    | text      | text        |
| Yes      | numeric metric | employee_enrollment_2007 | EMPLOYEE ENROLLMENT 2007 | number    | text        |
| Yes      | numeric metric | employee_enrollment_2008 | EMPLOYEE ENROLLMENT 2008 | number    | text        |
| Yes      | numeric metric | employee_enrollment_2009 | EMPLOYEE ENROLLMENT 2009 | number    | text        |
| Yes      | numeric metric | employee_enrollment_2010 | EMPLOYEE ENROLLMENT 2010 | number    | text        |
| Yes      | numeric metric | employee_enrollment_2011 | EMPLOYEE ENROLLMENT 2011 | number    | text        |
| Yes      | numeric metric | employee_enrollment_2012 | EMPLOYEE ENROLLMENT 2012 | number    | text        |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2xsc-h9y7 d:2007-01-01T00:00:00.000Z t:month=January m:employee_enrollment_2012=22051 m:employee_enrollment_2011=22973 m:employee_enrollment_2007=25140 m:employee_enrollment_2008=23343 m:employee_enrollment_2009=23251 m:employee_enrollment_2010=23361

series e:2xsc-h9y7 d:2007-01-01T00:00:00.000Z t:month=February m:employee_enrollment_2012=22046 m:employee_enrollment_2011=22945 m:employee_enrollment_2007=25062 m:employee_enrollment_2008=23294 m:employee_enrollment_2009=23231 m:employee_enrollment_2010=23350

series e:2xsc-h9y7 d:2007-01-01T00:00:00.000Z t:month=March m:employee_enrollment_2012=21981 m:employee_enrollment_2011=22863 m:employee_enrollment_2007=24394 m:employee_enrollment_2008=23267 m:employee_enrollment_2009=23225 m:employee_enrollment_2010=23357
```

## Meta Commands

```ls
metric m:employee_enrollment_2007 p:long l:"EMPLOYEE ENROLLMENT 2007" t:dataTypeName=number

metric m:employee_enrollment_2008 p:long l:"EMPLOYEE ENROLLMENT 2008" t:dataTypeName=number

metric m:employee_enrollment_2009 p:long l:"EMPLOYEE ENROLLMENT 2009" t:dataTypeName=number

metric m:employee_enrollment_2010 p:long l:"EMPLOYEE ENROLLMENT 2010" t:dataTypeName=number

metric m:employee_enrollment_2011 p:long l:"EMPLOYEE ENROLLMENT 2011" t:dataTypeName=number

metric m:employee_enrollment_2012 p:long l:"EMPLOYEE ENROLLMENT 2012" t:dataTypeName=number

entity e:2xsc-h9y7 l:"Risk Management - Employee Healthcare Enrollment, by Month - 2007 through August 2012" t:attribution="Cook County Department of Risk Management" t:url=https://datacatalog.cookcountyil.gov/api/views/2xsc-h9y7

property e:2xsc-h9y7 t:meta.view v:id=2xsc-h9y7 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyrisk.com/ v:averageRating=0 v:name="Risk Management - Employee Healthcare Enrollment, by Month - 2007 through August 2012" v:attribution="Cook County Department of Risk Management"

property e:2xsc-h9y7 t:meta.view.license v:name="Public Domain"

property e:2xsc-h9y7 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:2xsc-h9y7 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month     | employee_enrollment_2007 | employee_enrollment_2008 | employee_enrollment_2009 | employee_enrollment_2010 | employee_enrollment_2011 | employee_enrollment_2012 | 
| ========= | ======================== | ======================== | ======================== | ======================== | ======================== | ======================== | 
| January   | 25,140                   | 23,343                   | 23,251                   | 23,361                   | 22,973                   | 22,051                   | 
| February  | 25,062                   | 23,294                   | 23,231                   | 23,350                   | 22,945                   | 22,046                   | 
| March     | 24,394                   | 23,267                   | 23,225                   | 23,357                   | 22,863                   | 21,981                   | 
| April     | 24,442                   | 23,203                   | 23,275                   | 23,314                   | 22,766                   | 21,822                   | 
| May       | 24,339                   | 23,197                   | 23,318                   | 23,238                   | 22,695                   | 21,753                   | 
| June      | 24,302                   | 23,123                   | 23,307                   | 23,300                   | 22,637                   | 21,727                   | 
| July      | 24,120                   | 23,125                   | 23,291                   | 23,251                   | 22,590                   | 21,683                   | 
| August    | 23,980                   | 23,159                   | 23,328                   | 23,252                   | 22,550                   | 21,703                   | 
| September | 23,908                   | 23,164                   | 23,438                   | 23,241                   | 22,473                   |                          | 
| October   | 23,746                   | 23,210                   | 23,478                   | 23,198                   | 22,441                   |                          | 
```