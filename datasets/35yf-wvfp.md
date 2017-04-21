# Statewide CMT 3rd Grade Reading And Math: 2007-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statewide-cmt-3rd-grade-reading-and-math-2007-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/35yf-wvfp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/35yf-wvfp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/35yf-wvfp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 35yf-wvfp |
| Name | Statewide CMT 3rd Grade Reading And Math: 2007-2013 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | cmt, reading, math, ctkids |
| Created | 2014-09-03T15:31:06Z |
| Publication Date | 2014-09-03T15:36:42Z |

## Description

This dataset contains the percentage of students achieving goal in reading and mathematics on the 3rd grade Connecticut Mastery Test (CMT) for the years 2007-2013. Data are disaggregated by various subgroups including race/ethnicity, special education, free and reduced price lunch eligibility, and English language learner (ELL) status.

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
series e:35yf-wvfp d:2007-01-01T00:00:00.000Z t:group=State m:total_reading_goal_range=52.3 m:total_mathematics_goal_range=59.4

series e:35yf-wvfp d:2007-01-01T00:00:00.000Z t:group=Male m:total_reading_goal_range=50.2 m:total_mathematics_goal_range=60

series e:35yf-wvfp d:2007-01-01T00:00:00.000Z t:group=Female m:total_reading_goal_range=54.5 m:total_mathematics_goal_range=58.8
```

## Meta Commands

```ls
metric m:total_mathematics_goal_range p:float l:"Total Mathematics % Goal Range" t:dataTypeName=percent

metric m:total_reading_goal_range p:float l:"Total Reading % Goal Range" t:dataTypeName=percent

entity e:35yf-wvfp l:"Statewide CMT 3rd Grade Reading And Math: 2007-2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/35yf-wvfp

property e:35yf-wvfp t:meta.view v:id=35yf-wvfp v:category=Education v:averageRating=0 v:name="Statewide CMT 3rd Grade Reading And Math: 2007-2013" v:attribution="State Department of Education"

property e:35yf-wvfp t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:35yf-wvfp t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| group          | year | total_mathematics_goal_range | total_reading_goal_range | 
| ============== | ==== | ============================ | ======================== | 
| State          | 2007 | 59.4                         | 52.3                     | 
| Male           | 2007 | 60                           | 50.2                     | 
| Female         | 2007 | 58.8                         | 54.5                     | 
| Black          | 2007 | 31.4                         | 23.6                     | 
| Hispanic       | 2007 | 34                           | 22.9                     | 
| White          | 2007 | 70.9                         | 65.1                     | 
| Asian American | 2007 | 77.3                         | 66.2                     | 
| Am. Indian     | 2007 | 55.2                         | 48.1                     | 
| F/R Meals      | 2007 | 34.4                         | 23.4                     | 
| Full Price     | 2007 | 70.6                         | 65.1                     | 
```