# Care 4 Kids Total Families Served FY 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-total-families-served-fy-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/ru4i-m74j) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ru4i-m74j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ru4i-m74j/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ru4i-m74j |
| Name | Care 4 Kids Total Families Served FY 2013 |
| Attribution | Office of Early Childhood |
| Category | Education |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T14:32:33Z |
| Publication Date | 2014-03-10T14:35:13Z |

## Description

Care 4 Kids unduplicated total families served in State Fiscal Year 2013. Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                       | Data Type | Render Type |
| ======== | ============== | ======================= | ========================== | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                       | text      | text        |
| Yes      | numeric metric | none                    | Total Families Served 2013 | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ru4i-m74j d:2013-01-01T00:00:00.000Z t:connecticut_care_4_kids=AMSTON m:none=11

series e:ru4i-m74j d:2013-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANDOVER m:none=8

series e:ru4i-m74j d:2013-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANSONIA m:none=247
```

## Meta Commands

```ls
metric m:none p:integer l:"Total Families Served 2013" d:"Unduplicated total families served in State Fiscal year 2013. *A count of less than 5 but, not including zero, has been suppressed because the number is very small and potentially identifiable." t:dataTypeName=number

entity e:ru4i-m74j l:"Care 4 Kids Total Families Served FY 2013" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/ru4i-m74j

property e:ru4i-m74j t:meta.view v:id=ru4i-m74j v:category=Education v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Total Families Served FY 2013" v:attribution="Office of Early Childhood"

property e:ru4i-m74j t:meta.view.license v:name="Public Domain"

property e:ru4i-m74j t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:ru4i-m74j t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none | 
| ======================= | ==== | 
| ABINGTON                |      | 
| AMSTON                  | 11   | 
| ANDOVER                 | 8    | 
| ANSONIA                 | 247  | 
| ASHFORD                 | 15   | 
| AVON                    | 12   | 
| BALLOUVILLE             |      | 
| BALTIC                  | 17   | 
| BANTAM                  |      | 
| BARKHAMSTED             | 6    | 
```