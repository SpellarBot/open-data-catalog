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
series e:tjzn-e5cs d:2008-01-01T00:00:00.000Z t:month=Dec m:output_workloads=20 m:outcomes=20 m:inputs=240 m:effectiveness=6 m:efficiencies=6 m:output_demands=40

series e:tjzn-e5cs d:2008-01-01T00:00:00.000Z t:month=Jan m:output_workloads=23 m:outcomes=23 m:inputs=184 m:effectiveness=8 m:efficiencies=8 m:output_demands=46

series e:tjzn-e5cs d:2008-01-01T00:00:00.000Z t:month=Feb m:output_workloads=35 m:outcomes=35 m:inputs=280 m:effectiveness=4 m:efficiencies=4 m:output_demands=70
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

property e:tjzn-e5cs t:meta.view v:id=tjzn-e5cs v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Home Investigation Data - 2008" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:tjzn-e5cs t:meta.view.license v:name="Public Domain"

property e:tjzn-e5cs t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:tjzn-e5cs t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```