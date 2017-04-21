# 2011 Program Enrollment Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-program-enrollment-data-b542e) |
| Metadata | [Link](https://data.illinois.gov/api/views/4py4-2jin) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/4py4-2jin/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/4py4-2jin/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 4py4-2jin |
| Name | 2011 Program Enrollment Data |
| Category | Health-Medicaid |
| Tags | hfs, medicaid |
| Created | 2014-04-23T16:25:29Z |
| Publication Date | 2014-04-23T16:30:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | county                       | County                       | text      | text        |
| Yes      | series tag     | cookzip                      | CookZip                      | text      | text        |
| Yes      | series tag     | category                     | Category                     | text      | text        |
| Yes      | series tag     | racecd                       | RaceCd                       | text      | text        |
| Yes      | series tag     | ethnicitycd                  | EthnicityCd                  | text      | text        |
| Yes      | numeric metric | gendercd                     | GenderCd                     | number    | number      |
| Yes      | numeric metric | undocind                     | UndocInd                     | number    | number      |
| Yes      | series tag     | enrollmenthighlevelgroupdesc | EnrollmentHighLevelGroupDesc | text      | text        |
| Yes      | series tag     | enrollmentdetailrptgroupdesc | EnrollmentDetailRptGroupDesc | text      | text        |
| Yes      | numeric metric | hipaarecipients              | HIPAARecipients              | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4py4-2jin d:2011-01-01T00:00:00.000Z t:category="1 FChild0t18" t:ethnicitycd=N t:racecd=D t:cookzip=NA t:county=Adams t:enrollmenthighlevelgroupdesc="All Kids Share & Premium" t:enrollmentdetailrptgroupdesc="All Kids - income > 300% <= 400% FPL" m:gendercd=1 m:undocind=0 m:hipaarecipients=1.92

series e:4py4-2jin d:2011-01-01T00:00:00.000Z t:category="2 FAdult19t64NoD" t:ethnicitycd=N t:racecd=B t:cookzip=NA t:county=Adams t:enrollmenthighlevelgroupdesc="Family Assist (w/o cash) & All Kids" t:enrollmentdetailrptgroupdesc="Breast and Cervical Cancer (BCC)" m:gendercd=2 m:undocind=0 m:hipaarecipients=1.92

series e:4py4-2jin d:2011-01-01T00:00:00.000Z t:category="3 FAdult19t64Dis" t:ethnicitycd=D t:racecd=B t:cookzip=NA t:county=Adams t:enrollmenthighlevelgroupdesc=AABD t:enrollmentdetailrptgroupdesc="AABD - Blind/Disabled under Age 65 years" m:gendercd=1 m:undocind=0 m:hipaarecipients=1.92
```

## Meta Commands

```ls
metric m:gendercd p:integer l:GenderCd t:dataTypeName=number

metric m:undocind p:integer l:UndocInd t:dataTypeName=number

metric m:hipaarecipients p:double l:HIPAARecipients t:dataTypeName=number

entity e:4py4-2jin l:"2011 Program Enrollment Data" t:url=https://data.illinois.gov/api/views/4py4-2jin

property e:4py4-2jin t:meta.view v:id=4py4-2jin v:category=Health-Medicaid v:averageRating=0 v:name="2011 Program Enrollment Data"

property e:4py4-2jin t:meta.view.owner v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:displayName="HFS - Administrator"

property e:4py4-2jin t:meta.view.tableauthor v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:roleName=publisher v:displayName="HFS - Administrator"
```

## Top Records

```ls
| county | cookzip | category         | racecd | ethnicitycd | gendercd | undocind | enrollmenthighlevelgroupdesc        | enrollmentdetailrptgroupdesc             | hipaarecipients | 
| ====== | ======= | ================ | ====== | =========== | ======== | ======== | =================================== | ======================================== | =============== | 
| Adams  | NA      | 1 FChild0t18     | D      | N           | 1        | 0        | All Kids Share & Premium            | All Kids - income > 300% <= 400% FPL     | 1.92            | 
| Adams  | NA      | 2 FAdult19t64NoD | B      | N           | 2        | 0        | Family Assist (w/o cash) & All Kids | Breast and Cervical Cancer (BCC)         | 1.92            | 
| Adams  | NA      | 3 FAdult19t64Dis | B      | D           | 1        | 0        | AABD                                | AABD - Blind/Disabled under Age 65 years | 1.92            | 
| Adams  | NA      | 5 Partial        | W      | N           | 1        | 0        | QI-1 Only                           | QI-1 Only                                | 9               | 
| Adams  | NA      | 5 Partial        | W      | N           | 2        | 0        | Illinois Healthy Women              | Illinois Healthy Women (IHW)             | 614             | 
| Adams  | NA      | 1 FChild0t18     | D      | Y           | 2        | 0        | Family Assist (w/o cash) & All Kids | All Kids Income <= 133%                  | 9               | 
| Adams  | NA      | 1 FChild0t18     | B      | N           | 1        | 0        | Family Assist (w/o cash) & All Kids | TMA                                      | 55              | 
| Adams  | NA      | 1 FChild0t18     | B      | N           | 2        | 0        | All Kids Share & Premium            | All Kids - income > 150% <= 200% FPL     | 1.92            | 
| Adams  | NA      | 1 FChild0t18     | D      | D           | 1        | 0        | Family Assist (w/o cash) & All Kids | Moms & Babies                            | 1.92            | 
| Adams  | NA      | 1 FChild0t18     | D      | N           | 1        | 0        | All Kids Share & Premium            | All Kids - income > 133% <= 150% FPL     | 1.92            | 
```