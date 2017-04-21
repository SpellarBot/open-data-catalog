# Steelhead Estimates 2012 Final

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/steelhead-estimates-2012-final-96faf) |
| Metadata | [Link](https://data.wa.gov/api/views/72vk-wi6f) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/72vk-wi6f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/72vk-wi6f/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 72vk-wi6f |
| Name | Steelhead Estimates 2012 Final |
| Attribution | WDFW |
| Category | Natural Resources & Environment |
| Tags | steelhead sport harvest 2012 |
| Created | 2014-12-16T18:21:05Z |
| Publication Date | 2014-12-16T18:27:07Z |

## Description

Sport harvest of steelhead from Washington waters, by water, month, and mark type.

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | region     | Region   | text      | text        |
| Yes      | series tag     | system     | System   | text      | text        |
| Yes      | series tag     | water      | Water    | text      | text        |
| Yes      | series tag     | race       | Race     | text      | text        |
| Yes      | series tag     | mark       | Mark     | text      | text        |
| Yes      | numeric metric | apr_2012   | Apr 2012 | number    | number      |
| Yes      | numeric metric | may_2012   | May 2012 | number    | number      |
| Yes      | numeric metric | jun_2012   | Jun 2012 | number    | number      |
| Yes      | numeric metric | jul_2012   | Jul 2012 | number    | number      |
| Yes      | numeric metric | aug_2012   | Aug 2012 | number    | number      |
| Yes      | numeric metric | sep_2012   | Sep 2012 | number    | number      |
| Yes      | numeric metric | oct_2012   | Oct 2012 | number    | number      |
| Yes      | numeric metric | nov_2012   | Nov 2012 | number    | number      |
| Yes      | numeric metric | dec_2012   | Dec 2012 | number    | number      |
| Yes      | numeric metric | jan_2013   | Jan 2013 | number    | number      |
| Yes      | numeric metric | feb_2013   | Feb 2013 | number    | number      |
| Yes      | numeric metric | mar_2013   | Mar 2013 | number    | number      |
| Yes      | numeric metric | total      | Total    | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:72vk-wi6f d:2012-01-01T00:00:00.000Z t:region=CST t:water="Chehalis R. above Black R." t:system="Chehalis R. System *" t:mark=Marked t:race=S m:total=6 m:jul_2012=3 m:jun_2012=3

series e:72vk-wi6f d:2012-01-01T00:00:00.000Z t:mark=Marked t:race=W m:total=251 m:dec_2012=8 m:jan_2013=105 m:feb_2013=119 m:mar_2013=19

series e:72vk-wi6f d:2012-01-01T00:00:00.000Z t:water="Chehalis R. below Black R." t:mark=Marked t:race=S m:total=58 m:aug_2012=30 m:jul_2012=3 m:oct_2012=11 m:sep_2012=14
```

## Meta Commands

```ls
metric m:apr_2012 p:integer l:"Apr 2012" t:dataTypeName=number

metric m:may_2012 p:integer l:"May 2012" t:dataTypeName=number

metric m:jun_2012 p:integer l:"Jun 2012" t:dataTypeName=number

metric m:jul_2012 p:integer l:"Jul 2012" t:dataTypeName=number

metric m:aug_2012 p:integer l:"Aug 2012" t:dataTypeName=number

metric m:sep_2012 p:integer l:"Sep 2012" t:dataTypeName=number

metric m:oct_2012 p:integer l:"Oct 2012" t:dataTypeName=number

metric m:nov_2012 p:integer l:"Nov 2012" t:dataTypeName=number

metric m:dec_2012 p:integer l:"Dec 2012" t:dataTypeName=number

metric m:jan_2013 p:integer l:"Jan 2013" t:dataTypeName=number

metric m:feb_2013 p:integer l:"Feb 2013" t:dataTypeName=number

metric m:mar_2013 p:integer l:"Mar 2013" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:72vk-wi6f l:"Steelhead Estimates 2012 Final" t:attribution=WDFW t:url=https://data.wa.gov/api/views/72vk-wi6f

property e:72vk-wi6f t:meta.view v:id=72vk-wi6f v:category="Natural Resources & Environment" v:averageRating=0 v:name="Steelhead Estimates 2012 Final" v:attribution=WDFW

property e:72vk-wi6f t:meta.view.owner v:id=vbq7-qew5 v:screenName="Eric Kraig" v:displayName="Eric Kraig"

property e:72vk-wi6f t:meta.view.tableauthor v:id=vbq7-qew5 v:screenName="Eric Kraig" v:roleName=publisher v:displayName="Eric Kraig"
```

## Top Records

```ls
| region | system               | water                      | race | mark   | apr_2012 | may_2012 | jun_2012 | jul_2012 | aug_2012 | sep_2012 | oct_2012 | nov_2012 | dec_2012 | jan_2013 | feb_2013 | mar_2013 | total | 
| ====== | ==================== | ========================== | ==== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ===== | 
|        |                      |                            |      |        |          |          |          |          |          |          |          |          |          |          |          |          |       | 
| CST    | Chehalis R. System * | Chehalis R. above Black R. | S    | Marked |          |          | 3        | 3        |          |          |          |          |          |          |          |          | 6     | 
|        |                      |                            | W    | Marked |          |          |          |          |          |          |          |          | 8        | 105      | 119      | 19       | 251   | 
|        |                      | Chehalis R. below Black R. | S    | Marked |          |          |          | 3        | 30       | 14       | 11       |          |          |          |          |          | 58    | 
|        |                      |                            | W    | Marked | 6        |          |          |          |          |          |          | 8        | 39       | 161      | 97       | 17       | 328   | 
|        |                      | Cloquallam Creek           | W    | Marked |          |          |          |          |          |          |          |          | 3        |          |          |          | 3     | 
|        |                      | Newaukum River             | S    | Marked |          |          |          |          |          |          | 3        |          |          |          |          |          | 3     | 
|        |                      |                            | W    | Marked |          |          |          |          |          |          |          |          |          | 3        | 3        |          | 6     | 
|        |                      | Satsop River               | S    | Marked |          |          | 3        | 8        | 3        | 5        | 3        |          |          |          |          |          | 22    | 
|        |                      |                            | W    | Marked |          |          |          |          |          |          |          | 3        | 103      | 249      | 216      | 83       | 654   | 
```