# Adoption & Child Custody Advocacy - Home Investigation Data - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-home-investigation-data-2008-cfe88) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/tjzn-e5cs) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/tjzn-e5cs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/tjzn-e5cs/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | tjzn-e5cs |
| Name | Adoption & Child Custody Advocacy - Home Investigation Data - 2008 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Finance & Administration |
| Created | 2011-08-11T14:20:59Z |
| Publication Date | 2014-10-09T22:00:35Z |

## Description

The department is court ordered to complete a home investigation to determine if potential adoptive family whom is seeking permanency is suitable for placement. This data represents the number of home investigations undertaken by this office in 2008.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | month            | Month            | text      | text        |
| Yes      | numeric metric | output_demands   | Output Demands   | number    | number      |
| Yes      | numeric metric | inputs           | Inputs           | number    | number      |
| Yes      | numeric metric | output_workloads | Output Workloads | number    | number      |
| Yes      | numeric metric | efficiencies     | Efficiencies     | number    | number      |
| Yes      | numeric metric | effectiveness    | Effectiveness    | number    | number      |
| Yes      | numeric metric | outcomes         | Outcomes         | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tjzn-e5cs d:2008-01-01T00:00:00.000Z t:month=Dec m:output_workloads=20 m:outcomes=20 m:effectiveness=6 m:inputs=240 m:efficiencies=6 m:output_demands=40

series e:tjzn-e5cs d:2008-01-01T00:00:00.000Z t:month=Jan m:output_workloads=23 m:outcomes=23 m:effectiveness=8 m:inputs=184 m:efficiencies=8 m:output_demands=46

series e:tjzn-e5cs d:2008-01-01T00:00:00.000Z t:month=Feb m:output_workloads=35 m:outcomes=35 m:effectiveness=4 m:inputs=280 m:efficiencies=4 m:output_demands=70
```

## Meta Commands

```ls
metric m:output_demands p:integer l:"Output Demands" t:dataTypeName=number

metric m:inputs p:integer l:Inputs t:dataTypeName=number

metric m:output_workloads p:integer l:"Output Workloads" t:dataTypeName=number

metric m:efficiencies p:integer l:Efficiencies t:dataTypeName=number

metric m:effectiveness p:integer l:Effectiveness t:dataTypeName=number

metric m:outcomes p:integer l:Outcomes t:dataTypeName=number

entity e:tjzn-e5cs l:"Adoption & Child Custody Advocacy - Home Investigation Data - 2008" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/tjzn-e5cs

property e:tjzn-e5cs t:meta.view d:2017-06-09T13:55:16.226Z v:id=tjzn-e5cs v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Home Investigation Data - 2008" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:tjzn-e5cs t:meta.view.license d:2017-06-09T13:55:16.226Z v:name="Public Domain"

property e:tjzn-e5cs t:meta.view.owner d:2017-06-09T13:55:16.226Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:tjzn-e5cs t:meta.view.tableauthor d:2017-06-09T13:55:16.226Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month | output_demands | inputs | output_workloads | efficiencies | effectiveness | outcomes | 
| ===== | ============== | ====== | ================ | ============ | ============= | ======== | 
| Dec   | 40             | 240    | 20               | 6            | 6             | 20       | 
| Jan   | 46             | 184    | 23               | 8            | 8             | 23       | 
| Feb   | 70             | 280    | 35               | 4            | 4             | 35       | 
| Mar   | 56             | 224    | 32               | 8            | 8             | 28       | 
| Apr   | 62             | 252    | 31               | 8            | 8             | 38       | 
| May   | 50             | 200    | 25               | 8            | 8             | 20       | 
| Jun   | 30             | 120    | 22               | 5            | 5             | 22       | 
| Jul   | 46             | 184    | 25               | 8            | 8             | 23       | 
| Aug   | 46             | 184    | 20               | 8            | 8             | 23       | 
| Sep   | 52             | 208    | 27               | 4            | 4             | 26       | 
```