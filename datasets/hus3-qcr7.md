# Statewide CMT 8th Grade Reading and Math: 2007-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-cmt-8th-grade-reading-and-math-2007-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/hus3-qcr7) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/hus3-qcr7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/hus3-qcr7/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | hus3-qcr7 |
| Name | Statewide CMT 8th Grade Reading and Math: 2007-2013 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | cmt, reading, math, ctkids |
| Created | 2014-09-03T15:38:54Z |
| Publication Date | 2014-09-03T15:41:17Z |

## Description

This dataset contains the percentage of students achieving goal in reading and mathematics on the 8th grade Connecticut Mastery Test (CMT) for the years 2007-2013. Data are disaggregated by various subgroups including race/ethnicity, special education, free and reduced price lunch eligibility, and English language learner (ELL) status.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| Yes      | series tag     | group                        | Group                          | text      | text        |
| Yes      | time           | year                         | Year                           | number    | text        |
| Yes      | numeric metric | total_mathematics_goal_range | Total Mathematics % Goal Range | percent   | percent     |
| Yes      | numeric metric | total_reading_goal_range     | Total Reading % Goal Range     | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hus3-qcr7 d:2007-01-01T00:00:00.000Z t:group=State m:total_reading_goal_range=66.6 m:total_mathematics_goal_range=60.8

series e:hus3-qcr7 d:2007-01-01T00:00:00.000Z t:group=Male m:total_reading_goal_range=63.9 m:total_mathematics_goal_range=61.2

series e:hus3-qcr7 d:2007-01-01T00:00:00.000Z t:group=Female m:total_reading_goal_range=69.4 m:total_mathematics_goal_range=60.4
```

## Meta Commands

```ls
metric m:total_mathematics_goal_range p:float l:"Total Mathematics % Goal Range" t:dataTypeName=percent

metric m:total_reading_goal_range p:float l:"Total Reading % Goal Range" t:dataTypeName=percent

entity e:hus3-qcr7 l:"Statewide CMT 8th Grade Reading and Math: 2007-2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/hus3-qcr7

property e:hus3-qcr7 t:meta.view v:id=hus3-qcr7 v:category=Education v:averageRating=0 v:name="Statewide CMT 8th Grade Reading and Math: 2007-2013" v:attribution="State Department of Education"

property e:hus3-qcr7 t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:hus3-qcr7 t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| group          | year | total_mathematics_goal_range | total_reading_goal_range | 
| ============== | ==== | ============================ | ======================== | 
| State          | 2007 | 60.8                         | 66.6                     | 
| Male           | 2007 | 61.2                         | 63.9                     | 
| Female         | 2007 | 60.4                         | 69.4                     | 
| Black          | 2007 | 27.7                         | 38.3                     | 
| Hispanic       | 2007 | 29.7                         | 37.3                     | 
| White          | 2007 | 73.4                         | 78.2                     | 
| Asian American | 2007 | 81.2                         | 79                       | 
| Am. Indian     | 2007 | 45.7                         | 51.9                     | 
| F/R Meals      | 2007 | 30.3                         | 38.2                     | 
| Full Price     | 2007 | 72.3                         | 77.3                     | 
```