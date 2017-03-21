# PED_PlanReviewMeasures_Building

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ped-planreviewmeasures-building) |
| Metadata | [Link](https://data.srcity.org/api/views/ebe6-dvsr) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/ebe6-dvsr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/ebe6-dvsr/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | ebe6-dvsr |
| Name | PED_PlanReviewMeasures_Building |
| Created | 2017-01-20T21:57:23Z |
| Publication Date | 2017-01-21T02:46:43Z |
| Rows Updated | 2017-03-09T23:04:54Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | series tag     | goaltype    | GoalType    | text          | text          |
| Yes      | series tag     | measure     | Measure     | text          | text          |
| No       |                | year        | Year        | number        | number        |
| Yes      | series tag     | type        | Type        | text          | text          |
| Yes      | time           | date        | Date        | calendar_date | calendar_date |
| Yes      | numeric metric | avgnumdays  | AvgNumDays  | number        | number        |
| Yes      | numeric metric | noofpermits | NoOfPermits | number        | number        |
| Yes      | series tag     | rescomm     | ResComm     | text          | text          |
| Yes      | series tag     | recsubtype  | RecSubType  | text          | text          |
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
series e:ebe6-dvsr d:2015-08-01T00:00:00.000Z t:recsubtype=Demolition t:measure=AvgNumDaysFirstPlanReviewNONRESIDENTIAL t:rescomm=Non-Residential t:type=monthly t:goaltype=NonResidentialOnlyFirstPlanReview m:avgnumdays=14 m:noofpermits=1

series e:ebe6-dvsr d:2015-07-01T00:00:00.000Z t:recsubtype=Demolition t:measure=AvgNumDaysFirstPlanReviewRESIDENTIAL t:rescomm=Residential t:type=monthly t:goaltype=ResidentialOnlyFirstPlanReview m:avgnumdays=6 m:noofpermits=1

series e:ebe6-dvsr d:2015-07-01T00:00:00.000Z t:recsubtype="Site Grading" t:measure=AvgNumDaysFirstPlanReviewNONRESIDENTIAL t:rescomm=Non-Residential t:type=monthly t:goaltype=NonResidentialOnlyFirstPlanReview m:avgnumdays=18 m:noofpermits=1
```

## Meta Commands

```ls
metric m:avgnumdays p:double l:AvgNumDays t:dataTypeName=number

metric m:noofpermits p:integer l:NoOfPermits t:dataTypeName=number

entity e:ebe6-dvsr l:PED_PlanReviewMeasures_Building t:url=https://data.srcity.org/api/views/ebe6-dvsr

property e:ebe6-dvsr t:meta.view v:id=ebe6-dvsr v:averageRating=0 v:name=PED_PlanReviewMeasures_Building

property e:ebe6-dvsr t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:ebe6-dvsr t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```