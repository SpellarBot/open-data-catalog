# Tax credits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-credits-bd067) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5fkx-9rt5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5fkx-9rt5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5fkx-9rt5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5fkx-9rt5 |
| Name | Tax credits |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | hra, human resources administration, jobs and economic mobility, tax credits |
| Created | 2013-03-19T17:02:45Z |
| Publication Date | 2013-03-19T17:02:54Z |

## Description

Earned Income Tax Credit Maximum Income Levels and Credit Amounts Tax Year 2012. *MFJ-Married filing jointly

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | category                | Category                | text      | text        |
| Yes      | numeric metric | maximum_city_credit     | Maximum City Credit     | money     | text        |
| Yes      | numeric metric | maximum_state_credit    | Maximum State Credit    | money     | text        |
| Yes      | numeric metric | maximum_federal_credit  | Maximum Federal Credit  | money     | text        |
| Yes      | numeric metric | maximum_combined_credit | Maximum Combined Credit | money     | text        |
| Yes      | numeric metric | maximum_income          | Maximum Income          | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5fkx-9rt5 d:2013-03-19T10:02:51.000Z t:category="Families with three or more qualifying children" m:maximum_city_credit=295 m:maximum_state_credit=1767 m:maximum_combined_credit=7.95 m:maximum_income=45060 m:maximum_federal_credit=5891

series e:5fkx-9rt5 d:2013-03-19T10:02:51.000Z t:category="Families with two qualifying children" m:maximum_city_credit=262 m:maximum_state_credit=1571 m:maximum_combined_credit=7069 m:maximum_income=41952 m:maximum_federal_credit=5236

series e:5fkx-9rt5 d:2013-03-19T10:02:51.000Z t:category="Families with one qualifying child" m:maximum_city_credit=158 m:maximum_state_credit=951 m:maximum_combined_credit=4278 m:maximum_income=36920 m:maximum_federal_credit=3169
```

## Meta Commands

```ls
metric m:maximum_city_credit p:long l:"Maximum City Credit" t:dataTypeName=money

metric m:maximum_state_credit p:long l:"Maximum State Credit" t:dataTypeName=money

metric m:maximum_federal_credit p:long l:"Maximum Federal Credit" t:dataTypeName=money

metric m:maximum_combined_credit p:long l:"Maximum Combined Credit" t:dataTypeName=money

metric m:maximum_income p:long l:"Maximum Income" t:dataTypeName=money

entity e:5fkx-9rt5 l:"Tax credits" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/5fkx-9rt5

property e:5fkx-9rt5 t:meta.view v:id=5fkx-9rt5 v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/hia/html/other/benefits_tax.shtml v:averageRating=0 v:name="Tax credits" v:attribution="Human Resources Administration (HRA)"

property e:5fkx-9rt5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5fkx-9rt5 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | category                                        | maximum_city_credit | maximum_state_credit | maximum_federal_credit | maximum_combined_credit | maximum_income        | 
| =========== | =============================================== | =================== | ==================== | ====================== | ======================= | ===================== | 
| 1363687371  | Families with three or more qualifying children | $295                | $1,767               | $5,891                 | $7.95                   | $45,060($50,270 MFJ)* | 
| 1363687371  | Families with two qualifying children           | $262                | $1,571               | $5,236                 | $7,069                  | $41,952($47,162MFJ)*  | 
| 1363687371  | Families with one qualifying child              | $158                | $951                 | $3,169                 | $4,278                  | $36,920($42,130 MFJ)* | 
| 1363687371  | Individuals with no qualifying children         | $24                 | $143                 | $475                   | $642                    | $13,980($19,190 MFJ)* | 
```