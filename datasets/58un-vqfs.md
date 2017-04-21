# Job Titles by Classification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/job-titles-by-classification-1edbe) |
| Metadata | [Link](https://data.sfgov.org/api/views/58un-vqfs) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/58un-vqfs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/58un-vqfs/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 58un-vqfs |
| Name | Job Titles by Classification |
| Attribution | San Francisco Department of Human Resources |
| Category | City Management and Ethics |
| Created | 2011-11-12T23:53:18Z |
| Publication Date | 2011-11-12T23:56:55Z |

## Description

Shows the job titles associated with job classifications. Used with the Salary Ranges by Classification and Employees by Classification

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | job_code    | Job Code   | text      | text        |
| Yes      | series tag  | job_title   | Job Title  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:58un-vqfs d:2011-11-12T15:53:20.000Z t:job_code=0111 t:job_title="BdComm Mbr, Grp2,M=$25/Mtg" m:row_number.58un-vqfs=1

series e:58un-vqfs d:2011-11-12T15:53:20.000Z t:job_code=0112 t:job_title="BdComm Mbr, Grp3,M=$50/Mtg" m:row_number.58un-vqfs=2

series e:58un-vqfs d:2011-11-12T15:53:20.000Z t:job_code=0114 t:job_title="BdComm Mbr, Grp5,M$100/Mo" m:row_number.58un-vqfs=3
```

## Meta Commands

```ls
metric m:row_number.58un-vqfs p:long l:"Row Number"

entity e:58un-vqfs l:"Job Titles by Classification" t:attribution="San Francisco Department of Human Resources" t:url=https://data.sfgov.org/api/views/58un-vqfs

property e:58un-vqfs t:meta.view v:id=58un-vqfs v:category="City Management and Ethics" v:attributionLink=http://www.sfdhr.org v:averageRating=0 v:name="Job Titles by Classification" v:attribution="San Francisco Department of Human Resources"

property e:58un-vqfs t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:58un-vqfs t:meta.view.owner v:id=ivaz-tugd v:screenName="Department of Human Resources" v:displayName="Department of Human Resources"

property e:58un-vqfs t:meta.view.tableauthor v:id=ivaz-tugd v:screenName="Department of Human Resources" v:roleName=editor v:displayName="Department of Human Resources"
```

## Top Records

```ls
| :updated_at | job_code | job_title                      | 
| =========== | ======== | ============================== | 
| 1321113200  | 0111     | BdComm Mbr, Grp2,M=$25/Mtg     | 
| 1321113200  | 0112     | BdComm Mbr, Grp3,M=$50/Mtg     | 
| 1321113200  | 0114     | BdComm Mbr, Grp5,M$100/Mo      | 
| 1321113200  | 0115     | BdComm MbrGrp6,D=@$100/Halfday | 
| 1321113200  | 0116     | Brd Comm Mbr, M=$200/Mtg       | 
| 1321113200  | 0118     | BdComm Mbr, Grp7,M=$500/Month  | 
| 1321113200  | 0130     | Superintendent of Schools      | 
| 1321113200  | 0140     | Chief, Fire Department         | 
| 1321113200  | 0150     | Dep Chf of Dept (Fire Dept)    | 
| 1321113200  | 0170     | Assistant Law Librarian        | 
```