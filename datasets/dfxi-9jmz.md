# 2013 Program Enrollment Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-program-enrollment-data-1e16a) |
| Metadata | [Link](https://data.illinois.gov/api/views/dfxi-9jmz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/dfxi-9jmz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/dfxi-9jmz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | dfxi-9jmz |
| Name | 2013 Program Enrollment Data |
| Category | Health-Medicaid |
| Tags | hfs, medicaid, health |
| Created | 2014-04-23T16:36:36Z |
| Publication Date | 2014-04-23T16:39:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | county                       | County                       | text      | text        |
| Yes      | series tag     | cookzip                      | CookZip                      | text      | text        |
| Yes      | series tag     | category                     | Category                     | text      | text        |
| Yes      | series tag     | newracecd                    | NewRaceCd                    | text      | text        |
| Yes      | series tag     | ethnicitycd                  | EthnicityCd                  | text      | text        |
| Yes      | numeric metric | gendercd                     | GenderCd                     | number    | number      |
| Yes      | numeric metric | undocind                     | UndocInd                     | number    | number      |
| Yes      | series tag     | enrollmenthighlevelgroupdesc | EnrollmentHighLevelGroupDesc | text      | text        |
| Yes      | series tag     | enrollmentdetailrptgroupdesc | EnrollmentDetailRptGroupDesc | text      | text        |
| Yes      | numeric metric | hipaarecipients              | HIPAARecipients              | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dfxi-9jmz d:2013-01-01T00:00:00.000Z t:category="2 FAdult19t64NoD" t:ethnicitycd=N t:cookzip=60608 t:county=Cook t:newracecd=P t:enrollmenthighlevelgroupdesc="Family Assist (w/o cash) & All Kids" t:enrollmentdetailrptgroupdesc="FamilyCare Assist w/o cash" m:gendercd=2 m:undocind=0 m:hipaarecipients=6

series e:dfxi-9jmz d:2013-01-01T00:00:00.000Z t:category="4 FSenior65up" t:ethnicitycd=D t:cookzip=60608 t:county=Cook t:newracecd=W t:enrollmenthighlevelgroupdesc=AABD t:enrollmentdetailrptgroupdesc="AABD - Age 65 years old and older" m:gendercd=2 m:undocind=0 m:hipaarecipients=9

series e:dfxi-9jmz d:2013-01-01T00:00:00.000Z t:category="1 FChild0t18" t:ethnicitycd=D t:cookzip=60439 t:county=Cook t:newracecd=D t:enrollmenthighlevelgroupdesc="Family Assist (w/o cash) & All Kids" t:enrollmentdetailrptgroupdesc="All Kids Income <= 133%" m:gendercd=1 m:undocind=0 m:hipaarecipients=27
```

## Meta Commands

```ls
metric m:gendercd p:integer l:GenderCd t:dataTypeName=number

metric m:undocind p:integer l:UndocInd t:dataTypeName=number

metric m:hipaarecipients p:double l:HIPAARecipients t:dataTypeName=number

entity e:dfxi-9jmz l:"2013 Program Enrollment Data" t:url=https://data.illinois.gov/api/views/dfxi-9jmz

property e:dfxi-9jmz t:meta.view v:id=dfxi-9jmz v:category=Health-Medicaid v:averageRating=0 v:name="2013 Program Enrollment Data"

property e:dfxi-9jmz t:meta.view.owner v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:displayName="HFS - Administrator"

property e:dfxi-9jmz t:meta.view.tableauthor v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:roleName=publisher v:displayName="HFS - Administrator"
```

## Top Records

```ls
| county     | cookzip | category         | newracecd | ethnicitycd | gendercd | undocind | enrollmenthighlevelgroupdesc        | enrollmentdetailrptgroupdesc         | hipaarecipients | 
| ========== | ======= | ================ | ========= | =========== | ======== | ======== | =================================== | ==================================== | =============== | 
| Cook       | 60608   | 2 FAdult19t64NoD | P         | N           | 2        | 0        | Family Assist (w/o cash) & All Kids | FamilyCare Assist w/o cash           | 6               | 
| Cook       | 60608   | 4 FSenior65up    | W         | D           | 2        | 0        | AABD                                | AABD - Age 65 years old and older    | 9               | 
| Cook       | 60439   | 1 FChild0t18     | D         | D           | 1        | 0        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%              | 27              | 
| Cook       | 60164   | 1 FChild0t18     | D         | D           | 1        | 1        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%              | 6               | 
| Cook       | 60656   | 1 FChild0t18     | B         | N           | 2        | 0        | All Kids Share & Premium            | All Kids - income > 150% <= 200% FPL | 1.92            | 
| Ogle       | NA      | 1 FChild0t18     | D         | Y           | 1        | 1        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%              | 17              | 
| Cook       | 60634   | 1 FChild0t18     | M         | N           | 1        | 1        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%              | 1.92            | 
| Washington | NA      | 1 FChild0t18     | D         | D           | 1        | 0        | All Kids Share & Premium            | All Kids - income > 150% <= 200% FPL | 1.92            | 
| Douglas    | NA      | 2 FAdult19t64NoD | W         | D           | 2        | 0        | Family Assist (w/o cash) & All Kids | FamilyCare Assist w/o cash           | 1.92            | 
| Cook       | 60546   | 1 FChild0t18     | B         | N           | 2        | 0        | Family Assist (w/o cash) & All Kids | Moms & Babies                        | 1.92            | 
```