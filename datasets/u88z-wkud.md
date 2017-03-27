# Commission on Women’s Issues Public Hearing Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commission-on-womens-issues-public-hearing-reports) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/u88z-wkud) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/u88z-wkud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/u88z-wkud/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | u88z-wkud |
| Name | Commission on Women’s Issues Public Hearing Reports |
| Attribution | Cook County Commission on Women’s Issues |
| Created | 2016-06-23T20:35:36Z |
| Publication Date | 2016-06-23T20:49:43Z |

## Description

The Cook County Commission on Women’s Issues hosts an annual public hearing to address issues faced by women and girls in Cook County. The primary purpose of the hearing is educational.  The plan is to use the information gathered to develop a set of recommendations for action by the County Board and other interested parties. The Commission issues a Public Hearing Report based on information presented by speakers and research which offers both insight and recommendations for change, including recommendations for how County government may assist or participate in facilitating necessary change.

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
series e:u88z-wkud d:2015-11-05T00:00:00.000Z t:topic="Graduated Reentry: One Step Closer to Strengthening Communities" t:presentation_report=http://opendocs.cookcountyil.gov/womens-commission/hearing-reports/CCCWI-Public-Hearing-2015_Loyola_Presentation.pdf t:program=http://opendocs.cookcountyil.gov/womens-commission/hearing-reports/CCCWI-Public-Hearing-2015-Program_FINAL.pdf t:description="The Cook County Commission on Women’s Issues held its annual public hearing on the topic of Graduated Reentry. Graduated Reentry is a solution to helping formerly incarcerated women return to their communities. Graduated Reentry uses a blend of supports and sanctions to help women and girls released from incarceration to make good decisions, avoid recidivism, and build healthy lives." m:row_number.u88z-wkud=1

series e:u88z-wkud d:2014-09-23T00:00:00.000Z t:topic="The New Stay-at-Home Mother: Pre-Trial Services and Family Reunification" t:presentation_report=http://opendocs.cookcountyil.gov/womens-commission/hearing-reports/2014-CCCWI-Hearing-Presentation.pdf t:program=http://opendocs.cookcountyil.gov/womens-commission/hearing-reports/2014-CCWI-Hearing-Program-Booklet.pdf t:description="The Cook County Commission on Women’s Issues held its annual public hearing on the topic of the role of pre-trial services in family reunification. The New Stay-At-Home Mother” is a woman who has been charged with a non-violent crime, but is allowed to stay at home with her children, rather than be detained pre-trial. In Cook County, one out of every four women held for a non-violent crime is the head of a single family household. The decision to detain pre-trial defendants in jail carries more significant implications to their families, than their threat to society." t:handout_2=http://opendocs.cookcountyil.gov/womens-commission/hearing-reports/2014-CCWI-Hearing_Gainer-LEAD-Handout.pdf t:handout_1=http://opendocs.cookcountyil.gov/womens-commission/hearing-report/2014-CCWI-Hearing_CLAIM-Handout.pdf m:row_number.u88z-wkud=2

series e:u88z-wkud d:2012-10-18T00:00:00.000Z t:topic="Incarcerated Females: Breaking The Cycle" t:presentation_report=http://opendocs.cookcountyil.gov/womens-commission/hearing-reports/2012-Incarcerated-Females-Final.pdf t:list_of_presenters=http://opendocs.cookcountyil.gov/womens-commission/hearing-reports/2012-List-of-presenters.pdf t:program=http://opendocs.cookcountyil.gov/womens-commission/hearing-reports/2012-Public-Hearing-Program-Incarcerated-Females-Breaking-the-Cycle-FINAL-LAST.pdf t:description="The Cook County Commission on Women’s Issues held its annual public hearing on the topic of Incarcerated Females: Breaking the Cycle. In order to break the cycle, the Commission decided to look closely at repeat offenses and incarcerations among women. The Commission analyzed the cycle by looking at the circumstances that lead women to engage in the behavior for which they were either detained or incarcerated, and how women were treated while they were detained or incarcerated within our criminal justice system. The Commission also analyzed the challenges that women face when they were released from jail and detected the signs of women at risk for recidivism. In addition, the Commission identified support services and programs that assist women in BREAKING THE CYCLE." m:row_number.u88z-wkud=3
```

## Meta Commands

```ls
metric m:row_number.u88z-wkud p:long l:"Row Number"

entity e:u88z-wkud l:"Commission on Women’s Issues Public Hearing Reports" t:attribution="Cook County Commission on Women’s Issues" t:url=https://datacatalog.cookcountyil.gov/api/views/u88z-wkud

property e:u88z-wkud t:meta.view v:id=u88z-wkud v:averageRating=0 v:name="Commission on Women’s Issues Public Hearing Reports" v:attribution="Cook County Commission on Women’s Issues"

property e:u88z-wkud t:meta.view.license v:name="Public Domain"

property e:u88z-wkud t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:displayName="Cook County Open Data"

property e:u88z-wkud t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"
```