# 2014 HFS Program Enrollment Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-hfs-program-enrollment-data) |
| Metadata | [Link](https://data.illinois.gov/api/views/9vqk-fygn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/9vqk-fygn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/9vqk-fygn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 9vqk-fygn |
| Name | 2014 HFS Program Enrollment Data |
| Category | Health-Medicaid |
| Tags | hfs, medicaid, health |
| Created | 2015-06-02T19:08:56Z |
| Publication Date | 2015-06-09T16:16:43Z |

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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9vqk-fygn d:2014-01-01T00:00:00.000Z t:category="2 FAdult19t64NoD" t:ethnicitycd=N t:cookzip=60608 t:county=Cook t:newracecd=P t:enrollmenthighlevelgroupdesc="Family Assist (w/o cash) & All Kids" t:enrollmentdetailrptgroupdesc="FamilyCare Assist w/o cash" m:gendercd=2 m:undocind=0 m:hipaarecipients=1.92

series e:9vqk-fygn d:2014-01-01T00:00:00.000Z t:category="1 FChild0t18" t:ethnicitycd=N t:cookzip=NA t:county=Menard t:newracecd=A t:enrollmenthighlevelgroupdesc="Family Assist (w/o cash) & All Kids" t:enrollmentdetailrptgroupdesc=TMA m:gendercd=1 m:undocind=0 m:hipaarecipients=1.92

series e:9vqk-fygn d:2014-01-01T00:00:00.000Z t:category="1 FChild0t18" t:ethnicitycd=D t:cookzip=NA t:county=Stephenson t:newracecd=W t:enrollmenthighlevelgroupdesc=DCFS t:enrollmentdetailrptgroupdesc="DCFS - Adoption Assistance" m:gendercd=2 m:undocind=0 m:hipaarecipients=1.92
```

## Meta Commands

```ls
metric m:gendercd p:integer l:GenderCd t:dataTypeName=number

metric m:undocind p:integer l:UndocInd t:dataTypeName=number

metric m:hipaarecipients p:double l:HIPAARecipients t:dataTypeName=number

entity e:9vqk-fygn l:"2014 HFS Program Enrollment Data" t:url=https://data.illinois.gov/api/views/9vqk-fygn

property e:9vqk-fygn t:meta.view v:id=9vqk-fygn v:category=Health-Medicaid v:averageRating=0 v:name="2014 HFS Program Enrollment Data"

property e:9vqk-fygn t:meta.view.owner v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:displayName="HFS - Administrator"

property e:9vqk-fygn t:meta.view.tableauthor v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:roleName=publisher v:displayName="HFS - Administrator"
```

## Top Records

```ls
| county     | cookzip | category         | newracecd | ethnicitycd | gendercd | undocind | enrollmenthighlevelgroupdesc        | enrollmentdetailrptgroupdesc                      | hipaarecipients | 
| ========== | ======= | ================ | ========= | =========== | ======== | ======== | =================================== | ================================================= | =============== | 
| Cook       | 60608   | 2 FAdult19t64NoD | P         | N           | 2        | 0        | Family Assist (w/o cash) & All Kids | FamilyCare Assist w/o cash                        | 1.92            | 
| Menard     | NA      | 1 FChild0t18     | A         | N           | 1        | 0        | Family Assist (w/o cash) & All Kids | TMA                                               | 1.92            | 
| Stephenson | NA      | 1 FChild0t18     | W         | D           | 2        | 0        | DCFS                                | DCFS - Adoption Assistance                        | 1.92            | 
| Cook       | 60164   | 1 FChild0t18     | D         | D           | 1        | 1        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%                           | 1.92            | 
| Cook       | 60629   | 2 FAdult19t64NoD | D         | Y           | 2        | 0        | Family Care                         | FamilyCare - income > 133% <= 150% FPL            | 1.92            | 
| Ogle       | NA      | 1 FChild0t18     | D         | Y           | 1        | 1        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%                           | 12              | 
| Cook       | 60053   | 2 FAdult19t64NoD | A         | N           | 2        | 0        | ACA Adult ? 100% Match              | ACA Eligible FPL < 138% not receiving SSI or SSDI | 79              | 
| Washington | NA      | 1 FChild0t18     | D         | D           | 1        | 0        | All Kids Share & Premium            | All Kids - income > 150% <= 200% FPL              | 1.92            | 
| Schuyler   | NA      | 1 FChild0t18     | D         | D           | 2        | 0        | All Kids Share & Premium            | All Kids - income > 133% <= 150% FPL              | 1.92            | 
| Cook       | 60633   | 1 FChild0t18     | D         | Y           | 1        | 0        | All Kids Share & Premium            | All Kids - income > 200% <= 300% FPL              | 7               | 
```