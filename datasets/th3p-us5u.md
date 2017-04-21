# Board of Ethics - Notices of Determination

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-ethics-notices-of-determination) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/th3p-us5u) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/th3p-us5u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/th3p-us5u/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | th3p-us5u |
| Name | Board of Ethics - Notices of Determination |
| Attribution | Cook County Board of Ethics |
| Category | Finance & Administration |
| Created | 2016-06-22T18:01:19Z |
| Publication Date | 2016-06-22T18:05:22Z |

## Description

By ordinance, the investigations and considerations by the Board of Ethics of potential violations of the Ethics Ordinance are confidential. County Code, ? 2-592. As a matter of policy, the Board also maintains as confidential the identity of the requestors of advisory opinions. Board of Ethics Rules & Regulations, ? 4.10. The Board, however, is undertaking to make its final determinations available to the public with such deletions as may be necessary to prevent disclosure of any information the Board determines to be confidential.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | link        | Link        | url       | url         |
| Yes      | series tag  | case_number | Case Number | text      | text        |
| Yes      | series tag  | type        | Type        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:th3p-us5u d:2016-06-22T11:01:22.000Z t:case_number="14 I 0001" t:link=http://opendocs.cookcountyil.gov/ethics/notices-determination/14-I-0001-Notice-of-Determination.pdf t:type="Notice of Determination" m:row_number.th3p-us5u=1

series e:th3p-us5u d:2016-06-22T11:01:22.000Z t:case_number="13 I 0001" t:link=http://opendocs.cookcountyil.gov/ethics/notices-determination/13-I-0001-Notice-of-Determination.pdf t:type="Notice of Determination" m:row_number.th3p-us5u=2

series e:th3p-us5u d:2016-06-22T11:01:22.000Z t:case_number="12 I 0006" t:link=http://opendocs.cookcountyil.gov/ethics/notices-determination/12-I-0006-Notice-of-Determination.pdf t:type="Notice of Determination" m:row_number.th3p-us5u=3
```

## Meta Commands

```ls
metric m:row_number.th3p-us5u p:long l:"Row Number"

entity e:th3p-us5u l:"Board of Ethics - Notices of Determination" t:attribution="Cook County Board of Ethics" t:url=https://datacatalog.cookcountyil.gov/api/views/th3p-us5u

property e:th3p-us5u t:meta.view v:id=th3p-us5u v:category="Finance & Administration" v:averageRating=0 v:name="Board of Ethics - Notices of Determination" v:attribution="Cook County Board of Ethics"

property e:th3p-us5u t:meta.view.license v:name="Public Domain"

property e:th3p-us5u t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:th3p-us5u t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| :updated_at | link                                                                                                                                                                            | case_number | type                                       | 
| =========== | =============================================================================================================================================================================== | =========== | ========================================== | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/14-I-0001-Notice-of-Determination.pdf, 14 I 0001 Notice of Determination]                                        | 14 I 0001   | Notice of Determination                    | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/13-I-0001-Notice-of-Determination.pdf, 13 I 0001 Notice of Determination]                                        | 13 I 0001   | Notice of Determination                    | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/12-I-0006-Notice-of-Determination.pdf, 12 I 0006 Notice of Determination]                                        | 12 I 0006   | Notice of Determination                    | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/12-I-0005-Notice-of-Determination.pdf, 12 I 0005 Notice of Determination]                                        | 12 I 0005   | Notice of Determination                    | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/12-I-0002-Notice-of-Determination.pdf, 12 I 0002 Notice of Determination]                                        | 12 I 0002   | Notice of Determination                    | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/12-I-0001-Notice-of-Determination-on-Reconsideration1.pdf, 12 I 0001 Notice of Determination on Reconsideration] | 12 I 0001   | Notice of Determination on Reconsideration | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/12-I-0001-Notice-of-Determination.pdf, 12 I 0001 Notice of Determination]                                        | 12 I 0001   | Notice of Determination                    | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/11-I-0006-Notice-of-Determination.pdf, 11 I 0006 Notice of Determination]                                        | 11 I 0006   | Notice of Determination                    | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/11-I-0005-Notice-of-Determination.pdf, 11 I 0005 Notice of Determination]                                        | 11 I 0005   | Notice of Determination                    | 
| 1466593282  | [http://opendocs.cookcountyil.gov/ethics/notices-determination/11-I-0001-Notice-of-Determination-on-Reconsideration.pdf, 11 I 0001 Notice of Determination on Reconsideration]  | 11 I 0001   | Notice of Determination on Reconsideration | 
```