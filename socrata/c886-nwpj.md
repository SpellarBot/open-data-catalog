# Home Health Care - Measure Date Range

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-health-care-measure-date-range-b6c22) |
| Metadata | [Link](https://data.medicare.gov/api/views/c886-nwpj) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/c886-nwpj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/c886-nwpj/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | c886-nwpj |
| Name | Home Health Care - Measure Date Range |
| Category | Home Health Compare |
| Tags | hhc, general information |
| Created | 2012-10-17T19:06:56Z |
| Publication Date | 2017-04-11T23:14:50Z |

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | measure_name       | Measure Name       | text      | text        |
| No       |             | measure_date_range | Measure Date Range | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = measure_date_range
```

## Data Commands

```ls
series e:c886-nwpj d:2017-03-27T16:52:18.000Z t:measure_name="HHCAHPS Survey Summary Star Rating" m:row_number.c886-nwpj=1

series e:c886-nwpj d:2017-03-27T16:52:18.000Z t:measure_name="Star Rating for health team gave care in a professional way" m:row_number.c886-nwpj=2

series e:c886-nwpj d:2017-03-27T16:52:18.000Z t:measure_name="Star Rating for health team communicated well with them" m:row_number.c886-nwpj=3
```

## Meta Commands

```ls
metric m:row_number.c886-nwpj p:long l:"Row Number"

entity e:c886-nwpj l:"Home Health Care - Measure Date Range" t:url=https://data.medicare.gov/api/views/c886-nwpj

property e:c886-nwpj t:meta.view v:id=c886-nwpj v:category="Home Health Compare" v:averageRating=0 v:name="Home Health Care - Measure Date Range"

property e:c886-nwpj t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:c886-nwpj t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:c886-nwpj t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HomeHealthQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | measure_name                                                | measure_date_range                   | 
| =========== | =========================================================== | ==================================== | 
| 1490633538  | HHCAHPS Survey Summary Star Rating                          | October 1, 2015 - September 30, 2016 | 
| 1490633538  | Star Rating for health team gave care in a professional way | October 1, 2015 - September 30, 2016 | 
| 1490633538  | Star Rating for health team communicated well with them     | October 1, 2015 - September 30, 2016 | 
| 1490633538  | Star Rating team discussed medicines, pain, and home safety | October 1, 2015 - September 30, 2016 | 
| 1490633538  | Star Rating for how patients rated overall care from agency | October 1, 2015 - September 30, 2016 | 
| 1490633538  | How often patients got better at walking or moving around   | October 1, 2015 - September 30, 2016 | 
| 1490633538  | How often patients got better at getting in and out of bed  | October 1, 2015 - September 30, 2016 | 
| 1490633538  | How often patients got better at bathing                    | October 1, 2015 - September 30, 2016 | 
| 1490633538  | How often the home health team checked patients for pain    | October 1, 2015 - September 30, 2016 | 
| 1490633538  | How often the home health team treated their patients? pain | October 1, 2015 - September 30, 2016 | 
```