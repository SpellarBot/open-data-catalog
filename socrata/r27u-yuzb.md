# Adoption & Child Custody Advocacy - Adoptive Adoption Investigation Data - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-adoptive-adoption-investigation-data-2008-9a4f5) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/r27u-yuzb) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/r27u-yuzb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/r27u-yuzb/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | r27u-yuzb |
| Name | Adoption & Child Custody Advocacy - Adoptive Adoption Investigation Data - 2008 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Finance & Administration |
| Created | 2011-08-11T14:12:25Z |
| Publication Date | 2014-10-09T22:10:34Z |

## Description

The department is court ordered to complete a home investigation to determine if potential adoptive family whom is seeking permanency is suitable for placement.  This data represents the number of investigations undertaken by this office in 2008

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
series e:r27u-yuzb d:2008-01-01T00:00:00.000Z t:month=Dec m:output_workloads=8 m:outcomes=5 m:inputs=96 m:effectiveness=6 m:efficiencies=6 m:output_demands=16

series e:r27u-yuzb d:2008-01-01T00:00:00.000Z t:month=Jan m:output_workloads=2 m:outcomes=4 m:inputs=32 m:effectiveness=4 m:efficiencies=4 m:output_demands=4

series e:r27u-yuzb d:2008-01-01T00:00:00.000Z t:month=Feb m:output_workloads=3 m:outcomes=3 m:inputs=34 m:effectiveness=5 m:efficiencies=5 m:output_demands=6
```

## Meta Commands

```ls
metric m:output_demands p:integer l:"Output Demands" t:dataTypeName=number

metric m:inputs p:integer l:Inputs t:dataTypeName=number

metric m:output_workloads p:integer l:"Output Workloads" t:dataTypeName=number

metric m:efficiencies p:integer l:Efficiencies t:dataTypeName=number

metric m:effectiveness p:integer l:Effectiveness t:dataTypeName=number

metric m:outcomes p:integer l:Outcomes t:dataTypeName=number

entity e:r27u-yuzb l:"Adoption & Child Custody Advocacy - Adoptive Adoption Investigation Data - 2008" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/r27u-yuzb

property e:r27u-yuzb t:meta.view v:id=r27u-yuzb v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Adoptive Adoption Investigation Data - 2008" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:r27u-yuzb t:meta.view.license v:name="Public Domain"

property e:r27u-yuzb t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:r27u-yuzb t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month | output_demands | inputs | output_workloads | efficiencies | effectiveness | outcomes | 
| ===== | ============== | ====== | ================ | ============ | ============= | ======== | 
| Dec   | 16             | 96     | 8                | 6            | 6             | 5        | 
| Jan   | 4              | 32     | 2                | 4            | 4             | 4        | 
| Feb   | 6              | 34     | 3                | 5            | 5             | 3        | 
| Mar   | 12             | 48     | 2                | 4            | 4             | 6        | 
| Apr   | 10             | 80     | 5                | 16           | 16            | 5        | 
| May   | 4              | 24     | 2                | 12           | 12            | 6        | 
| Jun   | 12             | 48     | 6                | 8            | 8             | 6        | 
| Jul   | 6              | 34     | 10               | 6            | 6             | 3        | 
| Aug   | 17             | 32     | 5                | 8            | 8             | 2        | 
| Sep   | 4              | 16     | 4                | 4            | 4             | 2        | 
```