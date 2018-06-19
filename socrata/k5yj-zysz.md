# DCEO Liheap Any Assistance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-liheap-any-assistance-167a7) |
| Metadata | [Link](https://data.illinois.gov/api/views/k5yj-zysz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/k5yj-zysz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/k5yj-zysz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | k5yj-zysz |
| Name | DCEO Liheap Any Assistance |
| Category | Social/Healthcare |
| Created | 2012-01-13T21:31:07Z |
| Publication Date | 2012-01-13T21:31:52Z |

## Description

Liheap Any Assistance received

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | typeofassistance            | TypeOfAssistance            | text      | text        |
| Yes      | numeric metric | numberofassistedhouseholds  | NumberOfAssistedHouseholds  | number    | text        |
| Yes      | numeric metric | householdmember60orolder    | HouseholdMember60OrOlder    | number    | text        |
| Yes      | numeric metric | householdmemberdisabled     | HouseholdMemberDisabled     | number    | text        |
| Yes      | numeric metric | householdmember5oryounger   | HouseholdMember5OrYounger   | number    | text        |
| Yes      | numeric metric | elderlydisabledoryoungchild | ElderlyDisabledOrYoungChild | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k5yj-zysz d:2012-01-13T13:31:13.000Z t:typeofassistance="Any type of LIHEAP Assistance" m:householdmember60orolder=82701 m:numberofassistedhouseholds=316279 m:elderlydisabledoryoungchild=188542 m:householdmemberdisabled=67771 m:householdmember5oryounger=68454
```

## Meta Commands

```ls
metric m:numberofassistedhouseholds p:long l:NumberOfAssistedHouseholds t:dataTypeName=number

metric m:householdmember60orolder p:long l:HouseholdMember60OrOlder t:dataTypeName=number

metric m:householdmemberdisabled p:long l:HouseholdMemberDisabled t:dataTypeName=number

metric m:householdmember5oryounger p:long l:HouseholdMember5OrYounger t:dataTypeName=number

metric m:elderlydisabledoryoungchild p:long l:ElderlyDisabledOrYoungChild t:dataTypeName=number

entity e:k5yj-zysz l:"DCEO Liheap Any Assistance" t:url=https://data.illinois.gov/api/views/k5yj-zysz

property e:k5yj-zysz t:meta.view v:id=k5yj-zysz v:category=Social/Healthcare v:averageRating=0 v:name="DCEO Liheap Any Assistance"

property e:k5yj-zysz t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:k5yj-zysz t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | typeofassistance              | numberofassistedhouseholds | householdmember60orolder | householdmemberdisabled | householdmember5oryounger | elderlydisabledoryoungchild | 
| =========== | ============================= | ========================== | ======================== | ======================= | ========================= | =========================== | 
| 1326461473  | Any type of LIHEAP Assistance | 316,279                    | 82,701                   | 67,771                  | 68,454                    | 188,542                     | 
```