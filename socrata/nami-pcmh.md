# Connector Market Place Assisters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/connector-market-place-assisters-c93e1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/nami-pcmh) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/nami-pcmh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/nami-pcmh/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | nami-pcmh |
| Name | Connector Market Place Assisters |
| Attribution | DHS |
| Created | 2013-09-10T23:31:33Z |
| Publication Date | 2013-09-16T18:53:24Z |

## Description

Updated: 9.9.13

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | organization              | Organization              | text      | text        |
| Yes      | series tag  | contact_person_first_name | Contact Person First Name | text      | text        |
| Yes      | series tag  | last_name                 | Last Name                 | text      | text        |
| Yes      | series tag  | email                     | email                     | text      | text        |
| Yes      | series tag  | phone                     | phone                     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nami-pcmh d:2013-09-16T11:49:03.000Z t:phone=808-781-9413 t:organization="K?kua Kalihi Valley Comprehensive Family Services" t:email=dsalas@kkv.net t:last_name=Salas t:contact_person_first_name=Dallys m:row_number.nami-pcmh=1

series e:nami-pcmh d:2013-09-16T11:49:03.000Z t:phone=808-380-6436 t:organization="Ke Ola Mamo, Inc." t:email=dpalakiko@keolamamo.org t:last_name=Palakiko t:contact_person_first_name=Donna-Marie m:row_number.nami-pcmh=2

series e:nami-pcmh d:2013-09-16T11:49:03.000Z t:phone=808-969-9220 t:organization="Hui M?lama Ola N? ??iwi" t:email=kelsey@huimalamahawaii.com t:last_name=Hiraishi t:contact_person_first_name=Kelsey m:row_number.nami-pcmh=3
```

## Meta Commands

```ls
metric m:row_number.nami-pcmh p:long l:"Row Number"

entity e:nami-pcmh l:"Connector Market Place Assisters" t:attribution=DHS t:url=https://data.hawaii.gov/api/views/nami-pcmh

property e:nami-pcmh t:meta.view v:id=nami-pcmh v:averageRating=0 v:name="Connector Market Place Assisters" v:attribution=DHS

property e:nami-pcmh t:meta.view.owner v:id=r6wt-w4yc v:screenName=Kayla v:displayName=Kayla

property e:nami-pcmh t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | organization                                                 | contact_person_first_name | last_name | email                                | phone             | 
| =========== | ============================================================ | ========================= | ========= | ==================================== | ================= | 
| 1379332143  | K?kua Kalihi Valley Comprehensive Family Services            | Dallys                    | Salas     | dsalas@kkv.net                       | 808-781-9413      | 
| 1379332143  | Ke Ola Mamo, Inc.                                            | Donna-Marie               | Palakiko  | dpalakiko@keolamamo.org              | 808-380-6436      | 
| 1379332143  | Hui M?lama Ola N? ??iwi                                      | Kelsey                    | Hiraishi  | kelsey@huimalamahawaii.com           | 808-969-9220      | 
| 1379332143  | Kaua?i Economic Opportunity                                  | Lynn                      | Kua       | keo@keoinc.org                       | 808-245-4077      | 
| 1379332143  | Ka?u Rural Health Community Association, Inc.                | Jessanie                  | Marques   | krhcai@yahoo.com                     | (808)928-0101     | 
| 1379332143  | Molokai Community Health Center                              | Desiree                   | Puhi      | dpuhi@molokaichc.org                 | 808-660-2600      | 
| 1379332143  | Rolf Advertising                                             | David                     | Rolf      | drolf@rolfadvertising.com            | 808-593-1533      | 
| 1379332143  | Hawai?i Island Workforce & Economic Development ?Ohana, Inc. | Gaye                      | Ishimaru  | gishimaru@earthlink.net              | (808) 959-6200    | 
| 1379332143  | The Bay Clinic, Inc.                                         | Youlsau                   | Bells     | ybells@bayclinic.org                 | (808) 961-4078    | 
| 1379332143  | L?na?i Community Health Center                               | Diana                     | Shaw      | dshaw@lanaicommunityhealthcenter.org | 808-565-6919 x114 | 
```