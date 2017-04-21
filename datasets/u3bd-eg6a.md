# IDPH Community Water Fluoridation 2010 Compliance Award List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-community-water-fluoridation-2010-compliance-award-list-4c64f) |
| Metadata | [Link](https://data.illinois.gov/api/views/u3bd-eg6a) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/u3bd-eg6a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/u3bd-eg6a/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | u3bd-eg6a |
| Name | IDPH Community Water Fluoridation 2010 Compliance Award List |
| Attribution | Illinois Department of Public Health |
| Category | Public Health |
| Tags | fluoridation, compliance, awards |
| Created | 2011-09-28T17:33:09Z |
| Publication Date | 2011-09-28T17:43:33Z |

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                 | Data Type | Render Type |
| ======== | ============== | =================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | county                              | County                               | text      | text        |
| Yes      | numeric metric | length_of_consecutive_compliancy    | Number of Years Compliant            | number    | number      |
| Yes      | series tag     | perfect_compliance_12_of_12_months_ | Perfect Compliance (12 of 12 months) | text      | text        |
| Yes      | series tag     | years_of_consecutive_compliancy     | Years of Consecutive Compliancy      | text      | text        |
| Yes      | series tag     | honorable_mention_11_of_12_months_  | Honorable Mention (11 of 12 months)  | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:u3bd-eg6a d:2010-01-01T00:00:00.000Z t:perfect_compliance_12_of_12_months_="Mill Creek Public Water District ***" t:county=Adams t:honorable_mention_11_of_12_months_="Clayton Camp Point" t:years_of_consecutive_compliancy=1993-2010 m:length_of_consecutive_compliancy=18

series e:u3bd-eg6a d:2010-01-01T00:00:00.000Z t:perfect_compliance_12_of_12_months_="Quincy Water Department *****" t:county=Adams t:honorable_mention_11_of_12_months_="Plainville Water Department" t:years_of_consecutive_compliancy=1984-2010 m:length_of_consecutive_compliancy=27

series e:u3bd-eg6a d:2010-01-01T00:00:00.000Z t:perfect_compliance_12_of_12_months_="IL American Water Co. - Cairo *" t:county=Alexander t:years_of_consecutive_compliancy=2005-2010 m:length_of_consecutive_compliancy=6
```

## Meta Commands

```ls
metric m:length_of_consecutive_compliancy p:integer l:"Number of Years Compliant" t:dataTypeName=number

entity e:u3bd-eg6a l:"IDPH Community Water Fluoridation 2010 Compliance Award List" t:attribution="Illinois Department of Public Health" t:url=https://data.illinois.gov/api/views/u3bd-eg6a

property e:u3bd-eg6a t:meta.view v:id=u3bd-eg6a v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/ v:averageRating=0 v:name="IDPH Community Water Fluoridation 2010 Compliance Award List" v:attribution="Illinois Department of Public Health"

property e:u3bd-eg6a t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:u3bd-eg6a t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| county    | length_of_consecutive_compliancy | perfect_compliance_12_of_12_months_   | years_of_consecutive_compliancy | honorable_mention_11_of_12_months_ | 
| ========= | ================================ | ===================================== | =============================== | ================================== | 
| Adams     | 18                               | Mill Creek Public Water District ***  | 1993-2010                       | Clayton Camp Point                 | 
| Adams     | 27                               | Quincy Water Department *****         | 1984-2010                       | Plainville Water Department        | 
| Alexander | 6                                | IL American Water Co. - Cairo *       | 2005-2010                       |                                    | 
| Alexander | 12                               | South Water Inc. **                   | 1999-2010                       |                                    | 
| Alexander | 9                                | Tamms Water Department *              | 2002-2010                       |                                    | 
| Bond      |                                  |                                       |                                 |                                    | 
| Boone     | 10                               | Aqua IL - Candlewick **               | 2001-2010                       | Capron Water Department            | 
| Boone     | 21                               | Belvidere Water Department ****       | 1990-2010                       | Poplar Grove Water Department      | 
| Boone     | 6                                | Poplar Grove South Water Department * | 2005-2010                       |                                    | 
| Brown     |                                  |                                       |                                 |                                    | 
```