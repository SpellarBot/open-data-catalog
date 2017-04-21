# City Employee Engagement/Satisfaction (2012 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-employee-engagement-satisfaction-2012-present) |
| Metadata | [Link](https://data.nola.gov/api/views/i9nd-c9bb) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/i9nd-c9bb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/i9nd-c9bb/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | i9nd-c9bb |
| Name | City Employee Engagement/Satisfaction (2012 - Present) |
| Attribution | City of New Orleans |
| Category | City Administration |
| Tags | resultsnola |
| Created | 2016-02-12T15:33:58Z |
| Publication Date | 2016-02-12T15:47:08Z |

## Description

This dataset includes the results of the City employee engagemet/satisfaction survey conducted by the City.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | numeric metric | surveyquestion | SurveyQuestion | number        | number        |
| Yes      | series tag     | indicatorname  | IndicatorName  | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:i9nd-c9bb d:2012-01-01T00:00:00.000Z t:rowid="Percent of respondents that agree or strongly agree with the following statement: I think it is safe to challenge the way things are done in the City organization.2012" t:indicatorname="Percent of respondents that agree or strongly agree with the following statement: I think it is safe to challenge the way things are done in the City organization." m:surveyquestion=1 m:indicatorvalue=37.07246161401081

series e:i9nd-c9bb d:2012-01-01T00:00:00.000Z t:rowid="Percent of respondents that agree or strongly agree with the following statement: I know what work is expected of me.
2012" t:indicatorname="Percent of respondents that agree or strongly agree with the following statement: I know what work is expected of me." m:surveyquestion=2 m:indicatorvalue=84.09342763659957

series e:i9nd-c9bb d:2012-01-01T00:00:00.000Z t:rowid="Percent of respondents that agree or strongly agree with the following statement: I have the equipment and materials I need to do my work well and efficiently.
2012" t:indicatorname="Percent of respondents that agree or strongly agree with the following statement: I have the equipment and materials I need to do my work well and efficiently." m:surveyquestion=3 m:indicatorvalue=28.843819418172878
```

## Meta Commands

```ls
metric m:surveyquestion p:integer l:SurveyQuestion t:dataTypeName=number

metric m:indicatorvalue p:decimal l:IndicatorValue t:dataTypeName=number

entity e:i9nd-c9bb l:"City Employee Engagement/Satisfaction (2012 - Present)" t:attribution="City of New Orleans" t:url=https://data.nola.gov/api/views/i9nd-c9bb

property e:i9nd-c9bb t:meta.view v:id=i9nd-c9bb v:category="City Administration" v:attributionLink=http://www.nola.gov/performance-and-accountability/ v:averageRating=0 v:name="City Employee Engagement/Satisfaction (2012 - Present)" v:attribution="City of New Orleans"

property e:i9nd-c9bb t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:i9nd-c9bb t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:i9nd-c9bb t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                                                                                                                                           | date                | year | surveyquestion | indicatorname                                                                                                                                                                              | indicatorvalue     | 
| =============================================================================================================================================================================================== | =================== | ==== | ============== | ========================================================================================================================================================================================== | ================== | 
| Percent of respondents that agree or strongly agree with the following statement: I think it is safe to challenge the way things are done in the City organization.2012                         | 2012-01-01T00:00:00 | 2012 | 1              | Percent of respondents that agree or strongly agree with the following statement: I think it is safe to challenge the way things are done in the City organization.                        | 37.072461614010813 | 
| Percent of respondents that agree or strongly agree with the following statement: I know what work is expected of me. 2012                                                                      | 2012-01-01T00:00:00 | 2012 | 2              | Percent of respondents that agree or strongly agree with the following statement: I know what work is expected of me.                                                                      | 84.093427636599571 | 
| Percent of respondents that agree or strongly agree with the following statement: I have the equipment and materials I need to do my work well and efficiently. 2012                            | 2012-01-01T00:00:00 | 2012 | 3              | Percent of respondents that agree or strongly agree with the following statement: I have the equipment and materials I need to do my work well and efficiently.                            | 28.843819418172878 | 
| Percent of respondents that agree or strongly agree with the following statement: The people on my team are encouraged to come up with new and better ways of doing things. 2012                | 2012-01-01T00:00:00 | 2012 | 4              | Percent of respondents that agree or strongly agree with the following statement: The people on my team are encouraged to come up with new and better ways of doing things.                | 41.749941158254074 | 
| Percent of respondents that agree or strongly agree with the following statement: My immediate supervisor helps me to understand how I contribute to the department's/office's objectives. 2012 | 2012-01-01T00:00:00 | 2012 | 5              | Percent of respondents that agree or strongly agree with the following statement: My immediate supervisor helps me to understand how I contribute to the department's/office's objectives. | 60.528121115788295 | 
| Percent of respondents that agree or strongly agree with the following statement: I receive regular feedback on my performance. 2012                                                            | 2012-01-01T00:00:00 | 2012 | 6              | Percent of respondents that agree or strongly agree with the following statement: I receive regular feedback on my performance.                                                            | 49.601302481117536 | 
| Percent of respondents that agree or strongly agree with the following statement: The feedback I receive helps me to improve my performance. 2012                                               | 2012-01-01T00:00:00 | 2012 | 7              | Percent of respondents that agree or strongly agree with the following statement: The feedback I receive helps me to improve my performance.                                               | 52.257269539274873 | 
| Percent of respondents that agree or strongly agree with the following statement: I think that my performance is evaluated fairly. 2012                                                         | 2012-01-01T00:00:00 | 2012 | 8              | Percent of respondents that agree or strongly agree with the following statement: I think that my performance is evaluated fairly.                                                         | 52.008856854327256 | 
| Percent of respondents that agree or strongly agree with the following statement: Pay here is tied to performance2012                                                                           | 2012-01-01T00:00:00 | 2012 | 9              | Percent of respondents that agree or strongly agree with the following statement: Pay here is tied to performance                                                                          | 5.738292442856368  | 
| Percent of respondents that agree or strongly agree with the following statement: Poor performance is dealt with effectively on my team2012                                                     | 2012-01-01T00:00:00 | 2012 | 10             | Percent of respondents that agree or strongly agree with the following statement: Poor performance is dealt with effectively on my team                                                    | 27.974478323334335 | 
```