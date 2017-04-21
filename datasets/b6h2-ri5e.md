# Class Specification And Minimum Qualification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/class-specification-and-minimum-qualification-74c49) |
| Metadata | [Link](https://data.hawaii.gov/api/views/b6h2-ri5e) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/b6h2-ri5e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/b6h2-ri5e/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | b6h2-ri5e |
| Name | Class Specification And Minimum Qualification |
| Attribution | Department of Human Resources |
| Category | Employment |
| Tags | class, jobs, emplyment |
| Created | 2012-06-01T01:07:52Z |
| Publication Date | 2012-06-01T01:13:30Z |

## Description

Department of Human Resources information regarding class specs and minimum qualifications for State positions

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | class_title            | Class Title            | text      | text        |
| Yes      | series tag  | code                   | Code                   | text      | number      |
| Yes      | series tag  | class_specifications   | Class Specifications   | text      | text        |
| Yes      | series tag  | minimum_qualifications | Minimum Qualifications | text      | text        |
| Yes      | series tag  | other                  | Other                  | text      | text        |
| No       |             | bu                     | BU                     | number    | number      |
| Yes      | series tag  | bu_salary_schedule     | BU Salary Schedule     | text      | text        |
| Yes      | series tag  | grade                  | Grade                  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = bu
```

## Data Commands

```ls
series e:b6h2-ri5e d:2012-05-31T18:07:54.000Z t:bu_salary_schedule="<a href=""http://hawaii.gov/hrd/information/HRDInfoCentral/DocCentral/SalarySchedules/BU03_04/BU03,04_2008_07_01.pdf"">BU03</a>" t:minimum_qualifications="<a href=""http://www.hawaii.gov/hrd/main/eccd/Class Specifications and Minimum Qualifications/Group_I/1004mq.pdf"">1665mq.pdf</a>" t:class_title="ABSTRACTING ASSISTANT III" t:grade=SR09 t:code=1.665 t:class_specifications="<a href=""http://www.hawaii.gov/hrd/main/eccd/Class Specifications and Minimum Qualification Requirements/Group_I/1665.pdf"">1665.pdf</a>" m:row_number.b6h2-ri5e=1

series e:b6h2-ri5e d:2012-05-31T18:07:54.000Z t:bu_salary_schedule="<a href=""http://hawaii.gov/hrd/information/HRDInfoCentral/DocCentral/SalarySchedules/BU03_04/BU03,04_2008_07_01.pdf"">BU03</a>" t:minimum_qualifications="<a href=""http://www.hawaii.gov/hrd/main/eccd/Class Specifications and Minimum Qualifications/Group_I/1004mq.pdf"">1665mq.pdf</a>" t:class_title="ABSTRACTING ASSISTANT IV" t:grade=SR11 t:code=1.667 t:class_specifications="<a href=""http://www.hawaii.gov/hrd/main/eccd/Class Specifications and Minimum Qualifications/Group_I/1665.pdf"">1665.pdf</a>" m:row_number.b6h2-ri5e=2

series e:b6h2-ri5e d:2012-05-31T18:07:54.000Z t:bu_salary_schedule="<a href=""http://hawaii.gov/hrd/information/HRDInfoCentral/DocCentral/SalarySchedules/BU03_04/BU03,04_2008_07_01.pdf"">BU03</a>" t:minimum_qualifications="<a href=""http://www.hawaii.gov/hrd/main/eccd/Class Specifications and Minimum Qualifications/Group_I/1004mq.pdf"">1665mq.pdf</a>" t:class_title="ABSTRACTING ASSISTANT V" t:grade=SR13 t:code=1.669 t:class_specifications="<a href=""http://www.hawaii.gov/hrd/main/eccd/Class Specifications and Minimum Qualifications/Group_I/1665.pdf"">1665.pdf</a>" m:row_number.b6h2-ri5e=3
```

## Meta Commands

```ls
metric m:row_number.b6h2-ri5e p:long l:"Row Number"

entity e:b6h2-ri5e l:"Class Specification And Minimum Qualification" t:attribution="Department of Human Resources" t:url=https://data.hawaii.gov/api/views/b6h2-ri5e

property e:b6h2-ri5e t:meta.view v:id=b6h2-ri5e v:category=Employment v:attributionLink=http://hawaii.gov/hrd/main/eccd/ v:averageRating=0 v:name="Class Specification And Minimum Qualification" v:attribution="Department of Human Resources"

property e:b6h2-ri5e t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:b6h2-ri5e t:meta.view.owner v:id=mz35-s465 v:screenName=david.k.keane@hawaii.gov v:displayName=david.k.keane@hawaii.gov

property e:b6h2-ri5e t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | class_title               | code  | class_specifications | minimum_qualifications | other | bu | bu_salary_schedule | grade | 
| =========== | ========================= | ===== | ==================== | ====================== | ===== | == | ================== | ===== | 
| 1338487674  | ABSTRACTING ASSISTANT III | 1.665 | 1665.pdf             | 1665mq.pdf             |       | 3  | BU03               | SR09  | 
| 1338487674  | ABSTRACTING ASSISTANT IV  | 1.667 | 1665.pdf             | 1665mq.pdf             |       | 3  | BU03               | SR11  | 
| 1338487674  | ABSTRACTING ASSISTANT V   | 1.669 | 1665.pdf             | 1665mq.pdf             |       | 3  | BU03               | SR13  | 
| 1338487674  | ABSTRACTOR IX             | 1.676 | 1665.pdf             | 1665mq.pdf             |       | 4  | BU03               | SR21  | 
| 1338487674  | ABSTRACTOR VI             | 1.670 | 1665.pdf             | 1665mq.pdf             |       | 3  | BU03               | SR15  | 
| 1338487674  | ABSTRACTOR VII            | 1.672 | 1665.pdf             | 1665mq.pdf             |       | 4  | BU03               | SR17  | 
| 1338487674  | ABSTRACTOR VIII           | 1.674 | 1665.pdf             | 1665mq.pdf             |       | 4  | BU03               | SR19  | 
| 1338487674  | ABSTRACTOR X              | 1.678 | 1665.pdf             | 1665mq.pdf             |       | 4  | BU03               | SR23  | 
| 1338487674  | ACCOUNT CLERK I           | 1.336 | 1336.pdf             | 1336mq.pdf             |       | 3  | BU03               | SR06  | 
| 1338487674  | ACCOUNT CLERK II          | 1.337 | 1336.pdf             | 1336mq.pdf             |       | 3  | BU03               | SR08  | 
```