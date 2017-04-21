# Care 4 Kids Total Families Served FY 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-total-families-served-fy-2011) |
| Metadata | [Link](https://data.ct.gov/api/views/3mqv-d66s) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/3mqv-d66s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/3mqv-d66s/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 3mqv-d66s |
| Name | Care 4 Kids Total Families Served FY 2011 |
| Attribution | Office of Early Childhood |
| Category | Education |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T14:11:44Z |
| Publication Date | 2014-03-10T14:21:13Z |

## Description

Care 4 Kids unduplicated total families served in State Fiscal Year 2011. Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                       | Data Type | Render Type |
| ======== | ============== | ======================= | ========================== | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                       | text      | text        |
| Yes      | numeric metric | none                    | Total Families Served 2011 | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3mqv-d66s d:2011-01-01T00:00:00.000Z t:connecticut_care_4_kids=ABINGTON m:none=0

series e:3mqv-d66s d:2011-01-01T00:00:00.000Z t:connecticut_care_4_kids=AMSTON m:none=10

series e:3mqv-d66s d:2011-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANDOVER m:none=9
```

## Meta Commands

```ls
metric m:none p:integer l:"Total Families Served 2011" d:"Unduplicated total families served in State Fiscal year 2011. *A count of less than 5 but, not including zero, has been suppressed because the number is very small and potentially identifiable" t:dataTypeName=number

entity e:3mqv-d66s l:"Care 4 Kids Total Families Served FY 2011" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/3mqv-d66s

property e:3mqv-d66s t:meta.view v:id=3mqv-d66s v:category=Education v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Total Families Served FY 2011" v:attribution="Office of Early Childhood"

property e:3mqv-d66s t:meta.view.license v:name="Public Domain"

property e:3mqv-d66s t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:3mqv-d66s t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none | 
| ======================= | ==== | 
| ABINGTON                | 0    | 
| AMSTON                  | 10   | 
| ANDOVER                 | 9    | 
| ANSONIA                 | 237  | 
| ASHFORD                 | 14   | 
| AVON                    | 16   | 
| BALLOUVILLE             |      | 
| BALTIC                  | 19   | 
| BANTAM                  | 5    | 
| BARKHAMSTED             | 9    | 
```