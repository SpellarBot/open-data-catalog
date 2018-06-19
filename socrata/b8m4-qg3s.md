# Care 4 Kids Average Families Served per Month 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-average-families-served-per-month-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/b8m4-qg3s) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/b8m4-qg3s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/b8m4-qg3s/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | b8m4-qg3s |
| Name | Care 4 Kids Average Families Served per Month 2012 |
| Attribution | Office of Early Childhood |
| Category | Education |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T13:26:04Z |
| Publication Date | 2014-03-10T13:30:32Z |

## Description

Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services (also called DSS

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                         | Data Type | Render Type |
| ======== | ============== | ======================= | ============================ | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                         | text      | text        |
| Yes      | numeric metric | none                    | Average Families Served 2012 | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b8m4-qg3s d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=AMSTON m:none=7

series e:b8m4-qg3s d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANDOVER m:none=6

series e:b8m4-qg3s d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANSONIA m:none=158
```

## Meta Commands

```ls
metric m:none p:integer l:"Average Families Served 2012" d:"Average number of families served per month in 2012. A value of ""*"" indicates that the values has been suppressed. Values less than 5 and greater than 0 have been suppressed." t:dataTypeName=number

entity e:b8m4-qg3s l:"Care 4 Kids Average Families Served per Month 2012" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/b8m4-qg3s

property e:b8m4-qg3s t:meta.view v:id=b8m4-qg3s v:category=Education v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Average Families Served per Month 2012" v:attribution="Office of Early Childhood"

property e:b8m4-qg3s t:meta.view.license v:name="Public Domain"

property e:b8m4-qg3s t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:b8m4-qg3s t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none | 
| ======================= | ==== | 
| ABINGTON                |      | 
| AMSTON                  | 7    | 
| ANDOVER                 | 6    | 
| ANSONIA                 | 158  | 
| ASHFORD                 | 8    | 
| AVON                    | 8    | 
| BALLOUVILLE             |      | 
| BALTIC                  | 15   | 
| BANTAM                  |      | 
| BARKHAMSTED             | 5    | 
```