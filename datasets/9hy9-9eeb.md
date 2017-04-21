# SAT District Participation and Performance: 2012-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sat-district-participation-and-performance-2012-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/9hy9-9eeb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/9hy9-9eeb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/9hy9-9eeb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 9hy9-9eeb |
| Name | SAT District Participation and Performance: 2012-2013 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, district, sat |
| Created | 2014-06-26T19:53:12Z |
| Publication Date | 2014-06-26T19:56:11Z |

## Description

This dataset contains data by district on student SAT scores relative to the SAT College and Career Readiness (CCR) Benchmark score of 1550 (critical reading, mathematics and writing sections combined) for the graduating classes of 2012 and 2013.  According to research conducted by the College Board*, a score of 1550 indicates that a student will have a 65 percent or greater likelihood of achieving a B- average or higher during the first year of college.

This dataset also provides an estimated SAT Participation Rate, which equals the number of SAT test-taking seniors in the district divided by the number of seniors enrolled in the district, as a percentage.  These participation rates are considered an estimate because the grade level of the SAT test-taker is self-reported by the student at the time of registration for the SAT while the total number of seniors enrolled in the district is reported to the Connecticut State Department of Education (CSDE) by the district. These are the best available estimates of SAT participation rates.

The Benchmark Performance reflect the results of only those who participate in the SAT.  Because participation rates vary from district to district, the CSDE provides both the estimated Participation rates together with the Benchmark Performance in order to promote fair and valid comparisons across districts. 

Note: The data are suppressed when there are too few test-takers to sufficiently protect privacy.

*The research report can be found at:
http://research.collegeboard.org/sites/default/files/publications/2012/7/researchreport-2011-5-sat-college-readiness-benchmark-secondary-performance.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                  | Data Type | Render Type |
| ======== | ============== | ================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | district_number                    | District Number                       | text      | number      |
| Yes      | series tag     | district                           | District                              | text      | text        |
| Yes      | numeric metric | test_takers_2012                   | Test-takers: 2012                     | number    | number      |
| Yes      | numeric metric | test_takers_2013                   | Test-takers: 2013                     | number    | number      |
| Yes      | numeric metric | test_takers_change                 | Test-takers: Change%                  | percent   | percent     |
| Yes      | numeric metric | participation_rate_estimate_2012   | Participation Rate(estimate): 2012    | percent   | percent     |
| Yes      | numeric metric | participation_rate_estimate_2013   | Participation Rate(estimate): 2013    | percent   | percent     |
| Yes      | numeric metric | participation_rate_estimate_change | Participation Rate(estimate): Change% | percent   | percent     |
| Yes      | numeric metric | percent_meeting_benchmark_2012     | Percent Meeting Benchmark: 2012       | percent   | percent     |
| Yes      | numeric metric | percent_meeting_benchmark_2013     | Percent Meeting Benchmark: 2013       | percent   | percent     |
| Yes      | numeric metric | percent_meeting_benchmark_change   | Percent Meeting Benchmark: Change%    | percent   | percent     |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9hy9-9eeb d:2012-01-01T00:00:00.000Z t:district=Ansonia t:district_number=2 m:percent_meeting_benchmark_2012=18 m:test_takers_change=-12 m:participation_rate_estimate_2013=60 m:percent_meeting_benchmark_change=0 m:participation_rate_estimate_change=-6 m:participation_rate_estimate_2012=66 m:percent_meeting_benchmark_2013=18 m:test_takers_2013=104 m:test_takers_2012=118

series e:9hy9-9eeb d:2012-01-01T00:00:00.000Z t:district=Avon t:district_number=4 m:percent_meeting_benchmark_2012=73 m:test_takers_change=-4 m:participation_rate_estimate_2013=89 m:percent_meeting_benchmark_change=2 m:participation_rate_estimate_change=-1 m:participation_rate_estimate_2012=90 m:percent_meeting_benchmark_2013=75 m:test_takers_2013=243 m:test_takers_2012=254

series e:9hy9-9eeb d:2012-01-01T00:00:00.000Z t:district=Berlin t:district_number=7 m:percent_meeting_benchmark_2012=42 m:test_takers_change=2 m:participation_rate_estimate_2013=82 m:percent_meeting_benchmark_change=7 m:participation_rate_estimate_change=1 m:participation_rate_estimate_2012=81 m:percent_meeting_benchmark_2013=49 m:test_takers_2013=220 m:test_takers_2012=216
```

## Meta Commands

```ls
metric m:test_takers_2012 p:integer l:"Test-takers: 2012" t:dataTypeName=number

metric m:test_takers_2013 p:integer l:"Test-takers: 2013" t:dataTypeName=number

metric m:test_takers_change p:integer l:"Test-takers: Change%" t:dataTypeName=percent

metric m:participation_rate_estimate_2012 p:integer l:"Participation Rate(estimate): 2012" t:dataTypeName=percent

metric m:participation_rate_estimate_2013 p:integer l:"Participation Rate(estimate): 2013" t:dataTypeName=percent

metric m:participation_rate_estimate_change p:integer l:"Participation Rate(estimate): Change%" t:dataTypeName=percent

metric m:percent_meeting_benchmark_2012 p:integer l:"Percent Meeting Benchmark: 2012" t:dataTypeName=percent

metric m:percent_meeting_benchmark_2013 p:integer l:"Percent Meeting Benchmark: 2013" t:dataTypeName=percent

metric m:percent_meeting_benchmark_change p:integer l:"Percent Meeting Benchmark: Change%" t:dataTypeName=percent

entity e:9hy9-9eeb l:"SAT District Participation and Performance: 2012-2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/9hy9-9eeb

property e:9hy9-9eeb t:meta.view v:id=9hy9-9eeb v:category=Education v:averageRating=0 v:name="SAT District Participation and Performance: 2012-2013" v:attribution="State Department of Education"

property e:9hy9-9eeb t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:9hy9-9eeb t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| district_number | district   | test_takers_2012 | test_takers_2013 | test_takers_change | participation_rate_estimate_2012 | participation_rate_estimate_2013 | participation_rate_estimate_change | percent_meeting_benchmark_2012 | percent_meeting_benchmark_2013 | percent_meeting_benchmark_change | 
| =============== | ========== | ================ | ================ | ================== | ================================ | ================================ | ================================== | ============================== | ============================== | ================================ | 
| 2               | Ansonia    | 118              | 104              | -12                | 66                               | 60                               | -6                                 | 18                             | 18                             | 0                                | 
| 4               | Avon       | 254              | 243              | -4                 | 90                               | 89                               | -1                                 | 73                             | 75                             | 2                                | 
| 7               | Berlin     | 216              | 220              | 2                  | 81                               | 82                               | 1                                  | 42                             | 49                             | 7                                | 
| 9               | Bethel     | 200              | 190              | -5                 | 86                               | 82                               | -4                                 | 51                             | 49                             | -2                               | 
| 11              | Bloomfield | 130              | 160              | 23                 | 81                               | 99                               | 18                                 | 11                             | 8                              | -3                               | 
| 12              | Bolton     | 62               | 70               | 13                 | 85                               | 83                               | -2                                 | 55                             | 57                             | 2                                | 
| 14              | Branford   | 196              | 213              | 9                  | 77                               | 77                               | 0                                  | 47                             | 44                             | -3                               | 
| 15              | Bridgeport | 606              | 540              | -11                | 58                               | 62                               | 4                                  | 10                             | 10                             | 0                                | 
| 17              | Bristol    | 422              | 390              | -8                 | 67                               | 66                               | -1                                 | 45                             | 38                             | -7                               | 
| 18              | Brookfield | 227              | 219              | -4                 | 89                               | 89                               | 0                                  | 57                             | 59                             | 2                                | 
```