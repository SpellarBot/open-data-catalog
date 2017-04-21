# Care 4 Kids Unique Children By Age Group FY10

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/care-4-kids-unique-children-by-age-group-fy10) |
| Metadata | [Link](https://data.ct.gov/api/views/axur-9t7e) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/axur-9t7e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/axur-9t7e/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | axur-9t7e |
| Name | Care 4 Kids Unique Children By Age Group FY10 |
| Attribution | Office of Early Childhood |
| Category | Education |
| Tags | ct, care 4 kids, education |
| Created | 2014-03-10T14:40:04Z |
| Publication Date | 2014-03-10T14:44:59Z |

## Description

Care 4 Kids unique children served by age group by Town in Fiscal Year 2010. Care 4 Kids helps low to moderate income families in Connecticut pay for child care costs. This program is sponsored by the State of Connecticut?s Department of Social Services (also called DSS

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | town           | Town           | text      | text        |
| Yes      | numeric metric | infant_toddler | Infant/Toddler | number    | number      |
| Yes      | numeric metric | preschool_age  | Preschool Age  | number    | number      |
| Yes      | numeric metric | school_age     | School Age     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:axur-9t7e d:2014-03-10T07:40:07.000Z t:town=ABINGTON m:preschool_age=0 m:infant_toddler=0 m:school_age=0

series e:axur-9t7e d:2014-03-10T07:40:07.000Z t:town=AMSTON m:preschool_age=6

series e:axur-9t7e d:2014-03-10T07:40:07.000Z t:town=ANDOVER m:infant_toddler=5
```

## Meta Commands

```ls
metric m:infant_toddler p:integer l:Infant/Toddler d:"6 weeks through 2 years in age. *A count of less than 5 but, not including zero, has been suppressed because the number is very small and potentially identifiable.?" t:dataTypeName=number

metric m:preschool_age p:integer l:"Preschool Age" d:"3 through 5 years in age. *A count of less than 5 but, not including zero, has been suppressed because the number is very small and potentially identifiable.?" t:dataTypeName=number

metric m:school_age p:integer l:"School Age" d:"6 through 12 years and if special needs, 13-19 years in age. *A count of less than 5 but, not including zero, has been suppressed because the number is very small and potentially identifiable.?" t:dataTypeName=number

entity e:axur-9t7e l:"Care 4 Kids Unique Children By Age Group FY10" t:attribution="Office of Early Childhood" t:url=https://data.ct.gov/api/views/axur-9t7e

property e:axur-9t7e t:meta.view v:id=axur-9t7e v:category=Education v:attributionLink=http://www.ctcare4kids.com/ v:averageRating=0 v:name="Care 4 Kids Unique Children By Age Group FY10" v:attribution="Office of Early Childhood"

property e:axur-9t7e t:meta.view.license v:name="Public Domain"

property e:axur-9t7e t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:axur-9t7e t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | town        | infant_toddler | preschool_age | school_age | 
| =========== | =========== | ============== | ============= | ========== | 
| 1394437207  | ABINGTON    | 0              | 0             | 0          | 
| 1394437207  | AMSTON      |                | 6             |            | 
| 1394437207  | ANDOVER     | 5              |               |            | 
| 1394437207  | ANSONIA     | 141            | 138           | 119        | 
| 1394437207  | ASHFORD     | 11             | 13            | 8          | 
| 1394437207  | AVON        | 5              | 12            | 9          | 
| 1394437207  | BALLOUVILLE | 0              |               |            | 
| 1394437207  | BALTIC      | 14             | 18            |            | 
| 1394437207  | BANTAM      |                |               |            | 
| 1394437207  | BARKHAMSTED |                |               | 5          | 
```