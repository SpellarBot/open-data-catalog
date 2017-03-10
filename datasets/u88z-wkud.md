# Commission on Women?s Issues Public Hearing Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commission-on-womens-issues-public-hearing-reports) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/u88z-wkud) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/u88z-wkud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/u88z-wkud/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | u88z-wkud |
| Name | Commission on Women?s Issues Public Hearing Reports |
| Attribution | Cook County Commission on Women?s Issues |
| Created | 2016-06-23T20:35:36Z |
| Publication Date | 2016-06-23T20:49:43Z |
| Rows Updated | 2016-06-23T20:49:12Z |

## Description

The Cook County Commission on Women?s Issues hosts an annual public hearing to address issues faced by women and girls in Cook County. The primary purpose of the hearing is educational.  The plan is to use the information gathered to develop a set of recommendations for action by the County Board and other interested parties. The Commission issues a Public Hearing Report based on information presented by speakers and research which offers both insight and recommendations for change, including recommendations for how County government may assist or participate in facilitating necessary change.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | topic               | Topic               | text          | text          |
| Yes      | series tag  | description         | Description         | text          | text          |
| Yes      | time        | hearing_date        | Hearing Date        | calendar_date | calendar_date |
| Yes      | series tag  | program             | Program             | url           | url           |
| Yes      | series tag  | presentation_report | Presentation/Report | url           | url           |
| Yes      | series tag  | handout_1           | Handout 1           | url           | url           |
| Yes      | series tag  | handout_2           | Handout 2           | url           | url           |
| Yes      | series tag  | list_of_presenters  | List of Presenters  | url           | url           |
```

## Time Field

```ls
Value = hearing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:u88z-wkud l:"Commission on Women?s Issues Public Hearing Reports" t:attribution="Cook County Commission on Women?s Issues" t:url=https://datacatalog.cookcountyil.gov/api/views/u88z-wkud

property e:u88z-wkud t:meta.view d:2017-03-10T14:35:14.945Z v:id=u88z-wkud v:averageRating=0 v:name="Commission on Women?s Issues Public Hearing Reports" v:attribution="Cook County Commission on Women?s Issues"

property e:u88z-wkud t:meta.view.license d:2017-03-10T14:35:14.945Z v:name="Public Domain"

property e:u88z-wkud t:meta.view.owner d:2017-03-10T14:35:14.945Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"

property e:u88z-wkud t:meta.view.tableauthor d:2017-03-10T14:35:14.945Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"
```