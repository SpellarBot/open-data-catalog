# Care 4 Kids Total Families Served FY 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-total-families-served-fy-2010) |
| Metadata | [Link](https://data.ct.gov/api/views/psqf-2jv4) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/psqf-2jv4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/psqf-2jv4/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | psqf-2jv4 |
| Name | Care 4 Kids Total Families Served FY 2010 |
| Attribution | Office of Early Childhood |
| Category | Education |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T14:04:10Z |
| Publication Date | 2014-03-10T14:08:43Z |

## Description

Care 4 Kids unduplicated total families served in State Fiscal Year 2010. Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services (also called DSS

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                       | Data Type | Render Type |
| ======== | ============== | ======================= | ========================== | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                       | text      | text        |
| Yes      | numeric metric | none                    | Total Families Served 2010 | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:psqf-2jv4 d:2010-01-01T00:00:00.000Z t:connecticut_care_4_kids=ABINGTON m:none=0

series e:psqf-2jv4 d:2010-01-01T00:00:00.000Z t:connecticut_care_4_kids=AMSTON m:none=6

series e:psqf-2jv4 d:2010-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANDOVER m:none=5
```

## Meta Commands

```ls
metric m:none p:integer l:"Total Families Served 2010" d:"Unduplicated total families served in State Fiscal year 2010. *A count of less than 5 but, not including zero, has been suppressed because the number is very small and potentially identifiable." t:dataTypeName=number

entity e:psqf-2jv4 l:"Care 4 Kids Total Families Served FY 2010" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/psqf-2jv4

property e:psqf-2jv4 t:meta.view v:id=psqf-2jv4 v:category=Education v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Total Families Served FY 2010" v:attribution="Office of Early Childhood"

property e:psqf-2jv4 t:meta.view.license v:name="Public Domain"

property e:psqf-2jv4 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:psqf-2jv4 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none | 
| ======================= | ==== | 
| ABINGTON                | 0    | 
| AMSTON                  | 6    | 
| ANDOVER                 | 5    | 
| ANSONIA                 | 222  | 
| ASHFORD                 | 15   | 
| AVON                    | 15   | 
| BALLOUVILLE             |      | 
| BALTIC                  | 17   | 
| BANTAM                  |      | 
| BARKHAMSTED             | 6    | 
```