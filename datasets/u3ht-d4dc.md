# DCEO Liheap/Weatherization Assisted Households

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-liheap-weatherization-assisted-households-9f785) |
| Metadata | [Link](https://data.illinois.gov/api/views/u3ht-d4dc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/u3ht-d4dc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/u3ht-d4dc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | u3ht-d4dc |
| Name | DCEO Liheap/Weatherization Assisted Households |
| Category | Social/Healthcare |
| Tags | liheap, weather |
| Created | 2012-01-13T21:33:36Z |
| Publication Date | 2012-01-13T21:38:23Z |

## Description

Liheap Assisted Households

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag     | typeofassistance              | TypeOfAssistance              | text      | text        |
| Yes      | numeric metric | numberofassistedhouseholds    | NumberOfAssistedHouseholds    | number    | number      |
| Yes      | numeric metric | under75pcthhspoverty          | Under75PctHHSPoverty          | number    | number      |
| Yes      | numeric metric | pctto100pcthhspoverty         | 75PctTo100PctHHSPoverty       | number    | number      |
| Yes      | numeric metric | pctto125pcthhspoverty         | 101PctTo125PctHHSPoverty      | number    | number      |
| Yes      | numeric metric | pctto150pcthhspoverty         | 126PctTo150PctHHSPoverty      | number    | number      |
| Yes      | numeric metric | over150pcthhspoverty          | Over150PctHHSPoverty          | number    | number      |
| Yes      | numeric metric | householdmember60orolder      | HouseholdMember60OrOlder      | number    | number      |
| Yes      | numeric metric | householdmemberdisabled       | HouseholdMemberDisabled       | number    | number      |
| Yes      | numeric metric | householdmember5oryounger     | HouseholdMember5OrYounger     | number    | number      |
| Yes      | numeric metric | elderlydisabledoryoungchild   | ElderlyDisabledOrYoungChild   | number    | number      |
| Yes      | numeric metric | householdmember2oryounger     | HouseholdMember2OrYounger     | number    | number      |
| Yes      | numeric metric | householdmember3thru5yearsold | HouseholdMember3Thru5YearsOld | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u3ht-d4dc d:2012-01-13T13:33:41.000Z t:typeofassistance=Heating m:householdmember60orolder=78720 m:pctto150pcthhspoverty=40403 m:pctto100pcthhspoverty=69715 m:pctto125pcthhspoverty=52008 m:under75pcthhspoverty=134486 m:householdmember3thru5yearsold=45735 m:numberofassistedhouseholds=296612 m:elderlydisabledoryoungchild=176338 m:over150pcthhspoverty=0 m:householdmemberdisabled=62383 m:householdmember2oryounger=28458 m:householdmember5oryounger=63765

series e:u3ht-d4dc d:2012-01-13T13:33:41.000Z t:typeofassistance=Cooling m:householdmember60orolder=0 m:pctto150pcthhspoverty=0 m:pctto100pcthhspoverty=0 m:pctto125pcthhspoverty=0 m:under75pcthhspoverty=0 m:householdmember3thru5yearsold=0 m:numberofassistedhouseholds=0 m:elderlydisabledoryoungchild=0 m:over150pcthhspoverty=0 m:householdmemberdisabled=0 m:householdmember2oryounger=0 m:householdmember5oryounger=0

series e:u3ht-d4dc d:2012-01-13T13:33:41.000Z t:typeofassistance="Winter/year round  crisis" m:householdmember60orolder=6964 m:pctto150pcthhspoverty=5953 m:pctto100pcthhspoverty=10527 m:pctto125pcthhspoverty=7710 m:under75pcthhspoverty=26827 m:householdmember3thru5yearsold=9462 m:numberofassistedhouseholds=51017 m:elderlydisabledoryoungchild=26807 m:over150pcthhspoverty=0 m:householdmemberdisabled=10818 m:householdmember2oryounger=5841 m:householdmember5oryounger=13029
```

## Meta Commands

```ls
metric m:numberofassistedhouseholds p:integer l:NumberOfAssistedHouseholds t:dataTypeName=number

metric m:under75pcthhspoverty p:integer l:Under75PctHHSPoverty t:dataTypeName=number

metric m:pctto100pcthhspoverty p:integer l:75PctTo100PctHHSPoverty t:dataTypeName=number

metric m:pctto125pcthhspoverty p:integer l:101PctTo125PctHHSPoverty t:dataTypeName=number

metric m:pctto150pcthhspoverty p:integer l:126PctTo150PctHHSPoverty t:dataTypeName=number

metric m:over150pcthhspoverty p:integer l:Over150PctHHSPoverty t:dataTypeName=number

metric m:householdmember60orolder p:integer l:HouseholdMember60OrOlder t:dataTypeName=number

metric m:householdmemberdisabled p:integer l:HouseholdMemberDisabled t:dataTypeName=number

metric m:householdmember5oryounger p:integer l:HouseholdMember5OrYounger t:dataTypeName=number

metric m:elderlydisabledoryoungchild p:integer l:ElderlyDisabledOrYoungChild t:dataTypeName=number

metric m:householdmember2oryounger p:integer l:HouseholdMember2OrYounger t:dataTypeName=number

metric m:householdmember3thru5yearsold p:integer l:HouseholdMember3Thru5YearsOld t:dataTypeName=number

entity e:u3ht-d4dc l:"DCEO Liheap/Weatherization Assisted Households" t:url=https://data.illinois.gov/api/views/u3ht-d4dc

property e:u3ht-d4dc t:meta.view v:id=u3ht-d4dc v:category=Social/Healthcare v:averageRating=0 v:name="DCEO Liheap/Weatherization Assisted Households"

property e:u3ht-d4dc t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:u3ht-d4dc t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| :updated_at | typeofassistance         | numberofassistedhouseholds | under75pcthhspoverty | pctto100pcthhspoverty | pctto125pcthhspoverty | pctto150pcthhspoverty | over150pcthhspoverty | householdmember60orolder | householdmemberdisabled | householdmember5oryounger | elderlydisabledoryoungchild | householdmember2oryounger | householdmember3thru5yearsold | 
| =========== | ======================== | ========================== | ==================== | ===================== | ===================== | ===================== | ==================== | ======================== | ======================= | ========================= | =========================== | ========================= | ============================= | 
| 1326461621  | Heating                  | 296612                     | 134486               | 69715                 | 52008                 | 40403                 | 0                    | 78720                    | 62383                   | 63765                     | 176338                      | 28458                     | 45735                         | 
| 1326461621  | Cooling                  | 0                          | 0                    | 0                     | 0                     | 0                     | 0                    | 0                        | 0                       | 0                         | 0                           | 0                         | 0                             | 
| 1326461621  | Winter/year round crisis | 51017                      | 26827                | 10527                 | 7710                  | 5953                  | 0                    | 6964                     | 10818                   | 13029                     | 26807                       | 5841                      | 9462                          | 
| 1326461621  | Summer crisis            | 0                          | 0                    | 0                     | 0                     | 0                     | 0                    | 0                        | 0                       | 0                         | 0                           | 0                         | 0                             | 
| 1326461621  | Other crisis             | 0                          | 0                    | 0                     | 0                     | 0                     | 0                    | 0                        | 0                       | 0                         | 0                           | 0                         | 0                             | 
| 1326461621  | Weatherization           | 1978                       | 801                  | 500                   | 360                   | 195                   | 122                  | 658                      | 278                     | 320                       | 1085                        | 0                         | 0                             | 
```