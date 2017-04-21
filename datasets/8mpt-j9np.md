# HousingDocuments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housingdocuments-ecd81) |
| Metadata | [Link](https://data.oregon.gov/api/views/8mpt-j9np) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/8mpt-j9np/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/8mpt-j9np/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 8mpt-j9np |
| Name | HousingDocuments |
| Attribution | Oregon Housing and Community Services |
| Created | 2014-05-30T01:09:21Z |
| Publication Date | 2014-05-30T01:17:37Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type      | Render Type    |
| ======== | =========== | =========== | ========== | ============== | ============== |
| No       | time        | :updated_at | updated_at | meta_data      | meta_data      |
| Yes      | series tag  | name        | Name       | text           | text           |
| Yes      | series tag  | document    | Document   | document       | document       |
| Yes      | series tag  | category    | Category   | drop_down_list | drop_down_list |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8mpt-j9np d:2014-05-29T18:14:17.000Z t:category=a2bq-u225 t:document.filename=Housing1.xlsx t:document.content_type="application/zip; charset=binary" t:name="Housing test 1" t:document.size=8066 t:document.file_id=wgupcldrBtehVmkdH-dIEU4sER1Ksexm7RSNEE0VS4w m:row_number.8mpt-j9np=1

series e:8mpt-j9np d:2014-05-29T18:17:19.000Z t:category=gzkt-eiz8 t:document.filename=Housing2.xlsx t:document.content_type="application/zip; charset=binary" t:name="Housing test 2" t:document.size=8046 t:document.file_id=o1pIQiP9_oZc2opvkHeHBQM9YTRBRlzS2VwrlN2I-ZM m:row_number.8mpt-j9np=2

series e:8mpt-j9np d:2014-05-29T18:17:23.000Z t:category=gzkt-eiz8 t:document.filename="HousingWord Doc 1.docx" t:document.content_type="application/zip; charset=binary" t:name="Housing test 3" t:document.size=11426 t:document.file_id=1R2KnrV57nK0VQNnJde76JREKwlCSOizU7P_Kc6VY9w m:row_number.8mpt-j9np=3
```

## Meta Commands

```ls
metric m:row_number.8mpt-j9np p:long l:"Row Number"

entity e:8mpt-j9np l:HousingDocuments t:attribution="Oregon Housing and Community Services" t:url=https://data.oregon.gov/api/views/8mpt-j9np

property e:8mpt-j9np t:meta.view v:id=8mpt-j9np v:averageRating=0 v:name=HousingDocuments v:attribution="Oregon Housing and Community Services"

property e:8mpt-j9np t:meta.view.owner v:id=x7ch-rbs5 v:profileImageUrlMedium=/api/users/x7ch-rbs5/profile_images/THUMB v:profileImageUrlLarge=/api/users/x7ch-rbs5/profile_images/LARGE v:screenName="Wally Rogers" v:profileImageUrlSmall=/api/users/x7ch-rbs5/profile_images/TINY v:displayName="Wally Rogers"

property e:8mpt-j9np t:meta.view.tableauthor v:id=x7ch-rbs5 v:profileImageUrlMedium=/api/users/x7ch-rbs5/profile_images/THUMB v:profileImageUrlLarge=/api/users/x7ch-rbs5/profile_images/LARGE v:screenName="Wally Rogers" v:profileImageUrlSmall=/api/users/x7ch-rbs5/profile_images/TINY v:roleName=administrator v:displayName="Wally Rogers"
```

## Top Records

```ls
| :updated_at | name           | document                                                                                                      | category  | 
| =========== | ============== | ============================================================================================================= | ========= | 
| 1401387257  | Housing test 1 | [application/zip; charset=binary, wgupcldrBtehVmkdH-dIEU4sER1Ksexm7RSNEE0VS4w, Housing1.xlsx, 8066]           | a2bq-u225 | 
| 1401387439  | Housing test 2 | [application/zip; charset=binary, o1pIQiP9_oZc2opvkHeHBQM9YTRBRlzS2VwrlN2I-ZM, Housing2.xlsx, 8046]           | gzkt-eiz8 | 
| 1401387443  | Housing test 3 | [application/zip; charset=binary, 1R2KnrV57nK0VQNnJde76JREKwlCSOizU7P_Kc6VY9w, HousingWord Doc 1.docx, 11426] | gzkt-eiz8 | 
| 1401387448  | Housing test 4 | [application/zip; charset=binary, pBAeTw3VHonouWRj9oOl7mFMa-KJbqi5rJxm-x_Y33Q, HousingWord Doc 2.docx, 11444] | rjz9-y2hw | 
```