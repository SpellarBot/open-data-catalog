# Expenditures- FTEs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-ftes-8e71f) |
| Metadata | [Link](https://data.seattle.gov/api/views/nr4r-xu4y) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/nr4r-xu4y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/nr4r-xu4y/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | nr4r-xu4y |
| Name | Expenditures- FTEs |
| Category | Finance |
| Created | 2013-09-17T16:32:42Z |
| Publication Date | 2013-10-03T14:35:52Z |

## Description

Expenditures - FTEs

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | deptcode      | DeptCode      | text      | text        |
| Yes      | series tag     | bclname       | BCLName       | text      | text        |
| Yes      | numeric metric | 2012_actual   | 2012 Actual   | number    | number      |
| Yes      | numeric metric | 2013_adopted  | 2013 Adopted  | number    | number      |
| Yes      | numeric metric | 2014_endorsed | 2014 Endorsed | number    | number      |
| Yes      | numeric metric | 2014_proposed | 2014 Proposed | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nr4r-xu4y d:2013-10-03T07:35:24.000Z t:deptcode=ARTS t:bclname="Arts Account" m:2013_adopted=17.34 m:2014_proposed=20.09 m:2012_actual=9.75 m:2014_endorsed=17.34

series e:nr4r-xu4y d:2013-10-03T07:35:24.000Z t:deptcode=ARTS t:bclname="Municipal Arts Fund" m:2013_adopted=10.75 m:2014_proposed=10.75 m:2012_actual=10.1 m:2014_endorsed=10.75

series e:nr4r-xu4y d:2013-10-03T07:35:24.000Z t:deptcode=AUD t:bclname="Office of City Auditor" m:2013_adopted=9.5 m:2014_proposed=9.5 m:2012_actual=9 m:2014_endorsed=9.5
```

## Meta Commands

```ls
metric m:2012_actual p:float l:"2012 Actual" t:dataTypeName=number

metric m:2013_adopted p:float l:"2013 Adopted" t:dataTypeName=number

metric m:2014_endorsed p:float l:"2014 Endorsed" t:dataTypeName=number

metric m:2014_proposed p:float l:"2014 Proposed" t:dataTypeName=number

entity e:nr4r-xu4y l:"Expenditures- FTEs" t:url=https://data.seattle.gov/api/views/nr4r-xu4y

property e:nr4r-xu4y t:meta.view v:id=nr4r-xu4y v:category=Finance v:averageRating=0 v:name="Expenditures- FTEs"

property e:nr4r-xu4y t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:nr4r-xu4y t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | deptcode | bclname                | 2012_actual | 2013_adopted | 2014_endorsed | 2014_proposed | 
| =========== | ======== | ====================== | =========== | ============ | ============= | ============= | 
| 1380785724  | ARTS     | Arts Account           | 9.75        | 17.34        | 17.34         | 20.09         | 
| 1380785724  | ARTS     | Municipal Arts Fund    | 10.10       | 10.75        | 10.75         | 10.75         | 
| 1380785724  | AUD      | Office of City Auditor | 9.00        | 9.50         | 9.50          | 9.50          | 
| 1380785724  | CBO      | City Budget Office     | 27.50       | 28.50        | 28.50         | 29.50         | 
| 1380785724  | CEN      | Access                 | 11.23       | 11.23        | 11.23         | 10.27         | 
| 1380785724  | CEN      | Administration-SC      | 22.61       | 20.11        | 20.11         | 20.11         | 
| 1380785724  | CEN      | Campus Grounds         | 78.97       | 77.97        | 77.97         | 77.97         | 
| 1380785724  | CEN      | Commercial Events      | 7.48        | 7.48         | 7.48          | 7.48          | 
| 1380785724  | CEN      | Community Programs     | 11.88       | 11.88        | 11.88         | 11.88         | 
| 1380785724  | CEN      | Cultural Facilities    | 3.26        | 3.26         | 3.26          | 3.26          | 
```