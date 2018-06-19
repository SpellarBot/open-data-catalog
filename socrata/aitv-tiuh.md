# Adoption & Child Custody Advocacy - Adoptive Parent Fingerprinting Data - 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adoption-child-custody-advocacy-adoptive-parent-fingerprinting-data-2008-55040) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/aitv-tiuh) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/aitv-tiuh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/aitv-tiuh/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | aitv-tiuh |
| Name | Adoption & Child Custody Advocacy - Adoptive Parent Fingerprinting Data - 2008 |
| Attribution | Cook County Department of Adoption & Child Custody Advocacy |
| Category | Finance & Administration |
| Created | 2011-08-11T13:44:19Z |
| Publication Date | 2014-10-09T22:14:51Z |

## Description

When an individual or family wish to adopt, they must obtain fingerprint clearance. This Office is the pass through agency from the FBI, Illinois State Police and the courts.  The data represents the number of people fingerprinted by this office for the purposes of adoption in 2008.

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
series e:aitv-tiuh d:2008-01-01T00:00:00.000Z t:month=Dec m:output_workloads=17 m:outcomes=34 m:inputs=21 m:effectiveness=2 m:efficiencies=2 m:output_demands=17

series e:aitv-tiuh d:2008-01-01T00:00:00.000Z t:month=Jan m:output_workloads=27 m:outcomes=54 m:inputs=81 m:effectiveness=2 m:efficiencies=2 m:output_demands=27

series e:aitv-tiuh d:2008-01-01T00:00:00.000Z t:month=Feb m:output_workloads=26 m:outcomes=52 m:inputs=78 m:effectiveness=2 m:efficiencies=2 m:output_demands=26
```

## Meta Commands

```ls
metric m:output_demands p:integer l:"Output Demands" t:dataTypeName=number

metric m:inputs p:integer l:Inputs t:dataTypeName=number

metric m:output_workloads p:integer l:"Output Workloads" t:dataTypeName=number

metric m:efficiencies p:integer l:Efficiencies t:dataTypeName=number

metric m:effectiveness p:integer l:Effectiveness t:dataTypeName=number

metric m:outcomes p:integer l:Outcomes t:dataTypeName=number

entity e:aitv-tiuh l:"Adoption & Child Custody Advocacy - Adoptive Parent Fingerprinting Data - 2008" t:attribution="Cook County Department of Adoption & Child Custody Advocacy" t:url=https://datacatalog.cookcountyil.gov/api/views/aitv-tiuh

property e:aitv-tiuh t:meta.view v:id=aitv-tiuh v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/adoption___child_custody_advocacy/245 v:averageRating=0 v:name="Adoption & Child Custody Advocacy - Adoptive Parent Fingerprinting Data - 2008" v:attribution="Cook County Department of Adoption & Child Custody Advocacy"

property e:aitv-tiuh t:meta.view.license v:name="Public Domain"

property e:aitv-tiuh t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:aitv-tiuh t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month | output_demands | inputs | output_workloads | efficiencies | effectiveness | outcomes | 
| ===== | ============== | ====== | ================ | ============ | ============= | ======== | 
| Dec   | 17             | 21     | 17               | 2            | 2             | 34       | 
| Jan   | 27             | 81     | 27               | 2            | 2             | 54       | 
| Feb   | 26             | 78     | 26               | 2            | 2             | 52       | 
| Mar   | 34             | 102    | 34               | 2            | 2             | 68       | 
| Apr   | 42             | 126    | 42               | 2            | 2             | 84       | 
| May   | 21             | 63     | 21               | 2            | 2             | 42       | 
| Jun   | 35             | 105    | 35               | 2            | 2             | 70       | 
| Jul   | 38             | 72     | 38               | 2            | 2             | 76       | 
| Aug   | 24             | 72     | 24               | 2            | 2             | 48       | 
| Sep   | 17             | 21     | 17               | 2            | 2             | 34       | 
```