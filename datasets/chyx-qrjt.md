# Care 4 Kids Average Families Served per Month 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-average-families-served-per-month-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/chyx-qrjt) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/chyx-qrjt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/chyx-qrjt/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | chyx-qrjt |
| Name | Care 4 Kids Average Families Served per Month 2013 |
| Attribution | Office of Early Childhood |
| Category | Education |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T13:38:07Z |
| Publication Date | 2014-03-10T13:42:07Z |

## Description

Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                         | Data Type | Render Type |
| ======== | ============== | ======================= | ============================ | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                         | text      | text        |
| Yes      | numeric metric | none                    | Average Families Served 2013 | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:chyx-qrjt d:2013-01-01T00:00:00.000Z t:connecticut_care_4_kids=AMSTON m:none=7

series e:chyx-qrjt d:2013-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANDOVER m:none=6

series e:chyx-qrjt d:2013-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANSONIA m:none=159
```

## Meta Commands

```ls
metric m:none p:integer l:"Average Families Served 2013" d:"Average number of Families served in 2013. Values of ""*"" have been suppressed. Values less than 5 and greater than 0 have been suppressed" t:dataTypeName=number

entity e:chyx-qrjt l:"Care 4 Kids Average Families Served per Month 2013" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/chyx-qrjt

property e:chyx-qrjt t:meta.view v:id=chyx-qrjt v:category=Education v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Average Families Served per Month 2013" v:attribution="Office of Early Childhood"

property e:chyx-qrjt t:meta.view.license v:name="Public Domain"

property e:chyx-qrjt t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:chyx-qrjt t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none | 
| ======================= | ==== | 
| ABINGTON                |      | 
| AMSTON                  | 7    | 
| ANDOVER                 | 6    | 
| ANSONIA                 | 159  | 
| ASHFORD                 | 9    | 
| AVON                    | 7    | 
| BALLOUVILLE             |      | 
| BALTIC                  | 12   | 
| BANTAM                  |      | 
| BARKHAMSTED             |      | 
```