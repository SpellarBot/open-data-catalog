# Care 4 Kids Average Families Served Per Month 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-average-families-served-per-month-2010) |
| Metadata | [Link](https://data.ct.gov/api/views/m3xd-9xcw) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/m3xd-9xcw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/m3xd-9xcw/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | m3xd-9xcw |
| Name | Care 4 Kids Average Families Served Per Month 2010 |
| Attribution | Office of Early Childhood |
| Created | 2014-03-10T13:10:40Z |
| Publication Date | 2014-03-10T13:37:01Z |

## Description

Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                       | Data Type | Render Type |
| ======== | ============== | ======================= | ========================== | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                       | text      | text        |
| Yes      | numeric metric | none                    | Avg Families Served (2010) | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m3xd-9xcw d:2010-01-01T00:00:00.000Z t:connecticut_care_4_kids=ABINGTON m:none=0

series e:m3xd-9xcw d:2010-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANSONIA m:none=145

series e:m3xd-9xcw d:2010-01-01T00:00:00.000Z t:connecticut_care_4_kids=ASHFORD m:none=10
```

## Meta Commands

```ls
metric m:none p:integer l:"Avg Families Served (2010)" d:"Average number of families served in 2010. An ""*"" indicates the value has been suppressed. Values less than 5 and greater than 0 have been suppressed" t:dataTypeName=number

entity e:m3xd-9xcw l:"Care 4 Kids Average Families Served Per Month 2010" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/m3xd-9xcw

property e:m3xd-9xcw t:meta.view v:id=m3xd-9xcw v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Average Families Served Per Month 2010" v:attribution="Office of Early Childhood"

property e:m3xd-9xcw t:meta.view.license v:name="Public Domain"

property e:m3xd-9xcw t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:m3xd-9xcw t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none | 
| ======================= | ==== | 
| ABINGTON                | 0    | 
| AMSTON                  |      | 
| ANDOVER                 |      | 
| ANSONIA                 | 145  | 
| ASHFORD                 | 10   | 
| AVON                    | 10   | 
| BALLOUVILLE             |      | 
| BALTIC                  | 11   | 
| BANTAM                  |      | 
| BARKHAMSTED             | 5    | 
```