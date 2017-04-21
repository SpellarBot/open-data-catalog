# Municipal Building Electricity Usage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-building-electricity-usage) |
| Metadata | [Link](https://data.lacity.org/api/views/w7j2-5kjf) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/w7j2-5kjf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/w7j2-5kjf/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | w7j2-5kjf |
| Name | Municipal Building Electricity Usage |
| Category | A Livable and Sustainable City |
| Created | 2015-11-02T22:34:50Z |
| Publication Date | 2015-11-02T22:35:32Z |

## Description

2014 and 2015 Municipal Building Electricity Usage

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | month       | Month      | text      | text        |
| Yes      | numeric metric | 2014        | 2014       | number    | number      |
| Yes      | numeric metric | 2015        | 2015       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w7j2-5kjf d:2015-11-02T14:34:51.000Z t:month=January m:2015=17187919

series e:w7j2-5kjf d:2015-11-02T14:34:51.000Z t:month=February m:2015=17130787

series e:w7j2-5kjf d:2015-11-02T14:34:51.000Z t:month=March m:2015=17094200
```

## Meta Commands

```ls
metric m:2014 p:integer l:2014 t:dataTypeName=number

metric m:2015 p:integer l:2015 t:dataTypeName=number

entity e:w7j2-5kjf l:"Municipal Building Electricity Usage" t:url=https://data.lacity.org/api/views/w7j2-5kjf

property e:w7j2-5kjf t:meta.view v:id=w7j2-5kjf v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Municipal Building Electricity Usage"

property e:w7j2-5kjf t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:w7j2-5kjf t:meta.view.owner v:id=cyxz-kxfb v:profileImageUrlMedium=/api/users/cyxz-kxfb/profile_images/THUMB v:profileImageUrlLarge=/api/users/cyxz-kxfb/profile_images/LARGE v:screenName="Lilian Coral" v:profileImageUrlSmall=/api/users/cyxz-kxfb/profile_images/TINY v:displayName="Lilian Coral"

property e:w7j2-5kjf t:meta.view.tableauthor v:id=cyxz-kxfb v:profileImageUrlMedium=/api/users/cyxz-kxfb/profile_images/THUMB v:profileImageUrlLarge=/api/users/cyxz-kxfb/profile_images/LARGE v:screenName="Lilian Coral" v:profileImageUrlSmall=/api/users/cyxz-kxfb/profile_images/TINY v:roleName=administrator v:displayName="Lilian Coral"
```

## Top Records

```ls
| :updated_at | month     | 2014     | 2015     | 
| =========== | ========= | ======== | ======== | 
| 1446474891  | January   |          | 17187919 | 
| 1446474891  | February  |          | 17130787 | 
| 1446474891  | March     |          | 17094200 | 
| 1446474891  | April     |          | 17003326 | 
| 1446474891  | May       |          | 16817051 | 
| 1446474891  | June      |          | 16654249 | 
| 1446474891  | July      | 17294024 | 16156034 | 
| 1446474891  | August    | 17328806 |          | 
| 1446474891  | September | 17362385 |          | 
| 1446474891  | October   | 17397425 |          | 
```