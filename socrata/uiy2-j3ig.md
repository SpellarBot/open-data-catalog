# 2015 HFS Program Enrollment Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-hfs-program-enrollment-data) |
| Metadata | [Link](https://data.illinois.gov/api/views/uiy2-j3ig) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/uiy2-j3ig/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/uiy2-j3ig/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | uiy2-j3ig |
| Name | 2015 HFS Program Enrollment Data |
| Category | Health-Medicaid |
| Tags | hfs, medicaid, health |
| Created | 2016-07-01T18:28:20Z |
| Publication Date | 2016-07-05T13:50:14Z |

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | county                       | County                       | text      | text        |
| Yes      | series tag     | cookzip                      | CookZip                      | text      | text        |
| Yes      | series tag     | category                     | Category                     | text      | text        |
| Yes      | series tag     | newracecd                    | NewRaceCd                    | text      | text        |
| Yes      | numeric metric | gendercd                     | GenderCd                     | number    | number      |
| Yes      | numeric metric | undocind                     | UndocInd                     | number    | number      |
| Yes      | series tag     | enrollmenthighlevelgroupdesc | EnrollmentHighLevelGroupDesc | text      | text        |
| Yes      | series tag     | enrollmentdetailrptgroupdesc | EnrollmentDetailRptGroupDesc | text      | text        |
| Yes      | numeric metric | hipaarecipients              | HIPAARecipients              | number    | number      |
| Yes      | series tag     | ethnicitycd                  | EthnicityCd                  | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:uiy2-j3ig d:2015-01-01T00:00:00.000Z t:category="2 FAdult19t64NoD" t:ethnicitycd=N t:cookzip=60608 t:county=Cook t:newracecd=P t:enrollmenthighlevelgroupdesc="Family Assist (w/o cash) & All Kids" t:enrollmentdetailrptgroupdesc="FamilyCare Assist w/o cash" m:gendercd=2 m:undocind=0 m:hipaarecipients=1.92

series e:uiy2-j3ig d:2015-01-01T00:00:00.000Z t:category="4 FSenior65up" t:ethnicitycd=D t:cookzip=60608 t:county=Cook t:newracecd=W t:enrollmenthighlevelgroupdesc=AABD t:enrollmentdetailrptgroupdesc="AABD - Age 65 years old and older" m:gendercd=2 m:undocind=0 m:hipaarecipients=10

series e:uiy2-j3ig d:2015-01-01T00:00:00.000Z t:category="2 FAdult19t64NoD" t:ethnicitycd=Y t:cookzip=NA t:county=Adams t:newracecd=D t:enrollmenthighlevelgroupdesc="ACA Adult ? 100% Match" t:enrollmentdetailrptgroupdesc="ACA Eligible FPL < 138% not receiving SSI or SSDI" m:gendercd=2 m:undocind=0 m:hipaarecipients=1.92
```

## Meta Commands

```ls
metric m:gendercd p:integer l:GenderCd t:dataTypeName=number

metric m:undocind p:integer l:UndocInd t:dataTypeName=number

metric m:hipaarecipients p:double l:HIPAARecipients t:dataTypeName=number

entity e:uiy2-j3ig l:"2015 HFS Program Enrollment Data" t:url=https://data.illinois.gov/api/views/uiy2-j3ig

property e:uiy2-j3ig t:meta.view v:id=uiy2-j3ig v:category=Health-Medicaid v:averageRating=0 v:name="2015 HFS Program Enrollment Data"

property e:uiy2-j3ig t:meta.view.owner v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:displayName="HFS - Administrator"

property e:uiy2-j3ig t:meta.view.tableauthor v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:roleName=publisher v:displayName="HFS - Administrator"
```

## Top Records

```ls
| county     | cookzip | category         | newracecd | gendercd | undocind | enrollmenthighlevelgroupdesc        | enrollmentdetailrptgroupdesc                      | hipaarecipients | ethnicitycd | 
| ========== | ======= | ================ | ========= | ======== | ======== | =================================== | ================================================= | =============== | =========== | 
| Cook       | 60608   | 2 FAdult19t64NoD | P         | 2        | 0        | Family Assist (w/o cash) & All Kids | FamilyCare Assist w/o cash                        | 1.92            | N           | 
| Cook       | 60608   | 4 FSenior65up    | W         | 2        | 0        | AABD                                | AABD - Age 65 years old and older                 | 10              | D           | 
| Adams      | NA      | 2 FAdult19t64NoD | D         | 2        | 0        | ACA Adult ? 100% Match              | ACA Eligible FPL < 138% not receiving SSI or SSDI | 1.92            | Y           | 
| Cook       | 60164   | 1 FChild0t18     | D         | 1        | 1        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%                           | 1.92            | D           | 
| Cook       | 60606   | 1 FChild0t18     | W         | 1        | 0        | DCFS                                | DCFS - Foster Care                                | 1.92            | N           | 
| Ogle       | NA      | 1 FChild0t18     | D         | 1        | 1        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%                           | 7               | Y           | 
| Cook       | 60634   | 1 FChild0t18     | M         | 1        | 1        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%                           | 1.92            | N           | 
| Washington | NA      | 1 FChild0t18     | D         | 1        | 0        | All Kids Share & Premium            | All Kids - income > 150% <= 200% FPL              | 1.92            | D           | 
| Douglas    | NA      | 2 FAdult19t64NoD | W         | 2        | 0        | Family Assist (w/o cash) & All Kids | FamilyCare Assist w/o cash                        | 1.92            | D           | 
| Cook       | 60633   | 1 FChild0t18     | D         | 1        | 0        | All Kids Share & Premium            | All Kids - income > 200% <= 300% FPL              | 13              | Y           | 
```