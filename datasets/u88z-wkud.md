# Commission on Women?s Issues Public Hearing Reports

## Dataset

* [Dataset URL](https://datacatalog.cookcountyil.gov/api/views/u88z-wkud/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/commission-on-womens-issues-public-hearing-reports)
* Id = u88z-wkud
* Name = Commission on Women?s Issues Public Hearing Reports
* Attribution = Cook County Commission on Women?s Issues
* Created = 2016-06-23T20:35:36Z
* Publication Date = 2016-06-23T20:49:43Z
* Rows Updated = 2016-06-23T20:49:12Z

## Description

The Cook County Commission on Women?s Issues hosts an annual public hearing to address issues faced by women and girls in Cook County. The primary purpose of the hearing is educational.  The plan is to use the information gathered to develop a set of recommendations for action by the County Board and other interested parties. The Commission issues a Public Hearing Report based on information presented by speakers and research which offers both insight and recommendations for change, including recommendations for how County government may assist or participate in facilitating necessary change.

## Columns

```ls
| Name                | Field Name          | Data Type     | Render Type   | Schema Type | Included | 
| =================== | =================== | ============= | ============= | =========== | ======== | 
| Topic               | topic               | text          | text          | series tag  | Yes      | 
| Description         | description         | text          | text          | series tag  | Yes      | 
| Hearing Date        | hearing_date        | calendar_date | calendar_date | time        | Yes      | 
| Program             | program             | url           | url           | series tag  | Yes      | 
| Presentation/Report | presentation_report | url           | url           | series tag  | Yes      | 
| Handout 1           | handout_1           | url           | url           | series tag  | Yes      | 
| Handout 2           | handout_2           | url           | url           | series tag  | Yes      | 
| List of Presenters  | list_of_presenters  | url           | url           | series tag  | Yes      | 
```

## Time Field

```ls
Value = hearing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:u88z-wkud l:"Commission on Women?s Issues Public Hearing Reports" t:attribution="Cook County Commission on Women?s Issues" t:url=https://datacatalog.cookcountyil.gov/api/views/u88z-wkud

property e:u88z-wkud t:meta.view d:2017-03-03T13:48:50.522Z v:id=u88z-wkud v:averageRating=0 v:name="Commission on Women?s Issues Public Hearing Reports" v:attribution="Cook County Commission on Women?s Issues"

property e:u88z-wkud t:meta.view.license d:2017-03-03T13:48:50.522Z v:name="Public Domain"

property e:u88z-wkud t:meta.view.owner d:2017-03-03T13:48:50.522Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"

property e:u88z-wkud t:meta.view.tableauthor d:2017-03-03T13:48:50.522Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"
```