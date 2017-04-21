# Care 4 Kids Total Families Served FY 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-total-families-served-fy-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/3dd4-v7yv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/3dd4-v7yv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/3dd4-v7yv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 3dd4-v7yv |
| Name | Care 4 Kids Total Families Served FY 2012 |
| Attribution | Office of Early Childhood |
| Category | Education |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T14:16:17Z |
| Publication Date | 2014-03-10T14:19:33Z |

## Description

Care 4 Kids unduplicated total families served in State Fiscal Year 2012. Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type | Render Type |
| ======== | ============== | ======================= | ========================= | ========= | =========== |
| Yes      | series tag     | connecticut_care_4_kids | Town                      | text      | text        |
| Yes      | numeric metric | none                    | Total Familes Served 2012 | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3dd4-v7yv d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=AMSTON m:none=10

series e:3dd4-v7yv d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANDOVER m:none=9

series e:3dd4-v7yv d:2012-01-01T00:00:00.000Z t:connecticut_care_4_kids=ANSONIA m:none=247
```

## Meta Commands

```ls
metric m:none p:integer l:"Total Familes Served 2012" d:"Unduplicated total families served in State Fiscal year 2010. *A count of less than 5 but, not including zero, has been suppressed because the number is very small and potentially identifiable." t:dataTypeName=number

entity e:3dd4-v7yv l:"Care 4 Kids Total Families Served FY 2012" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/3dd4-v7yv

property e:3dd4-v7yv t:meta.view v:id=3dd4-v7yv v:category=Education v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Total Families Served FY 2012" v:attribution="Office of Early Childhood"

property e:3dd4-v7yv t:meta.view.license v:name="Public Domain"

property e:3dd4-v7yv t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:3dd4-v7yv t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| connecticut_care_4_kids | none | 
| ======================= | ==== | 
| ABINGTON                |      | 
| AMSTON                  | 10   | 
| ANDOVER                 | 9    | 
| ANSONIA                 | 247  | 
| ASHFORD                 | 16   | 
| AVON                    | 14   | 
| BALLOUVILLE             |      | 
| BALTIC                  | 21   | 
| BANTAM                  |      | 
| BARKHAMSTED             | 7    | 
```