# BSS - Pavement Condition Index PCI

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bss-pavement-condition-index-pci-8563a) |
| Metadata | [Link](https://data.lacity.org/api/views/3n9z-qdhi) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/3n9z-qdhi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/3n9z-qdhi/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 3n9z-qdhi |
| Name | BSS - Pavement Condition Index PCI |
| Created | 2014-05-30T21:21:36Z |
| Publication Date | 2014-05-30T21:23:45Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | numeric metric | pci                 | PCI                 | number        | number        |
| Yes      | numeric metric | last_year           | last year           | number        | number        |
| Yes      | numeric metric | absolute_change_yoy | absolute change YOY | number        | number        |
| No       |                | year                | Year                | number        | text          |
| Yes      | time           | date                | Date                | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:3n9z-qdhi d:2005-06-30T00:00:00.000Z m:pci=62

series e:3n9z-qdhi d:2008-06-30T00:00:00.000Z m:pci=62 m:absolute_change_yoy=0.2 m:last_year=62

series e:3n9z-qdhi d:2011-06-30T00:00:00.000Z m:pci=62 m:absolute_change_yoy=-0.6 m:last_year=62.17
```

## Meta Commands

```ls
metric m:pci p:integer l:PCI t:dataTypeName=number

metric m:last_year p:float l:"last year" t:dataTypeName=number

metric m:absolute_change_yoy p:float l:"absolute change YOY" t:dataTypeName=number

entity e:3n9z-qdhi l:"BSS - Pavement Condition Index  PCI" t:url=https://data.lacity.org/api/views/3n9z-qdhi

property e:3n9z-qdhi t:meta.view v:id=3n9z-qdhi v:averageRating=0 v:name="BSS - Pavement Condition Index  PCI"

property e:3n9z-qdhi t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:3n9z-qdhi t:meta.view.owner v:id=df4s-jhab v:profileImageUrlMedium=/api/users/df4s-jhab/profile_images/THUMB v:profileImageUrlLarge=/api/users/df4s-jhab/profile_images/LARGE v:screenName="Public Works: Street Services OpenData" v:profileImageUrlSmall=/api/users/df4s-jhab/profile_images/TINY v:displayName="Public Works: Street Services OpenData"

property e:3n9z-qdhi t:meta.view.tableauthor v:id=df4s-jhab v:profileImageUrlMedium=/api/users/df4s-jhab/profile_images/THUMB v:profileImageUrlLarge=/api/users/df4s-jhab/profile_images/LARGE v:screenName="Public Works: Street Services OpenData" v:profileImageUrlSmall=/api/users/df4s-jhab/profile_images/TINY v:roleName=publisher v:displayName="Public Works: Street Services OpenData"
```

## Top Records

```ls
| pci | last_year | absolute_change_yoy | year | date                | 
| === | ========= | =================== | ==== | =================== | 
| 62  |           |                     | 2005 | 2005-06-30T00:00:00 | 
| 62  | 62        | 0.2                 | 2008 | 2008-06-30T00:00:00 | 
| 62  | 62.17     | -0.6                | 2011 | 2011-06-30T00:00:00 | 
```