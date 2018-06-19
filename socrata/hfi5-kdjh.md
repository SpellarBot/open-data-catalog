# CMT District Performance: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cmt-district-performance-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/hfi5-kdjh) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/hfi5-kdjh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/hfi5-kdjh/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | hfi5-kdjh |
| Name | CMT District Performance: 2013 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, school district, cmt, school performance |
| Created | 2014-03-21T16:57:50Z |
| Publication Date | 2014-03-21T16:59:29Z |

## Description

This dataset contains the Connecticut Mastery Test (CMT) district performance indices (DPIs) and DPI target attainment status for 2012-13. These data were published in the District Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)

Note: Target attainment status will say ?n/a? if there is no 2012-13 DPI target or if there is no 2012-13 DPI, which happens when there are small N sizes for a particular subgroup or subject.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | district                      | District                      | text      | number      |
| Yes      | series tag     | district_name                 | District Name                 | text      | text        |
| Yes      | numeric metric | dpi_overall_2013              | DPI OVERALL 2013              | number    | number      |
| Yes      | series tag     | dpi_overall_status            | DPI OVERALL Status            | text      | text        |
| Yes      | numeric metric | black_dpi_overall_2013        | Black DPI OVERALL 2013        | number    | number      |
| Yes      | series tag     | black_dpi_overall_status      | Black DPI OVERALL Status      | text      | text        |
| Yes      | numeric metric | hispanic_dpi_overall_2013     | Hispanic DPI OVERALL 2013     | number    | number      |
| Yes      | series tag     | hispanic_dpi_overall_status   | Hispanic DPI OVERALL Status   | text      | text        |
| Yes      | numeric metric | ell_dpi_overall_2013          | ELL DPI OVERALL 2013          | number    | number      |
| Yes      | series tag     | ell_dpi_overall_status        | ELL DPI OVERALL Status        | text      | text        |
| Yes      | numeric metric | frl_dpi_overall_2013          | FRL DPI OVERALL 2013          | number    | number      |
| Yes      | series tag     | frl_dpi_overall_status        | FRL DPI OVERALL Status        | text      | text        |
| Yes      | numeric metric | swd_dpi_overall_2013          | SWD DPI OVERALL 2013          | number    | number      |
| Yes      | series tag     | swd_dpi_overall_status        | SWD DPI OVERALL Status        | text      | text        |
| Yes      | numeric metric | high_needs_dpi_overall_2013   | High Needs DPI OVERALL 2013   | number    | number      |
| Yes      | series tag     | high_needs_dpi_overall_status | High Needs DPI OVERALL Status | text      | text        |
| Yes      | numeric metric | dpi_math_2013                 | DPI MATH 2013                 | number    | number      |
| Yes      | series tag     | dpi_math_target_status        | DPI MATH Target Status        | text      | text        |
| Yes      | numeric metric | dpi_read_2013                 | DPI READ 2013                 | number    | number      |
| Yes      | series tag     | dpi_read_status               | DPI READ Status               | text      | text        |
| Yes      | numeric metric | dpi_write_2013                | DPI WRITE 2013                | number    | number      |
| Yes      | series tag     | dpi_write_status              | DPI Write Status              | text      | text        |
| Yes      | numeric metric | dpi_science_2013              | DPI SCIENCE 2013              | number    | number      |
| Yes      | series tag     | dpi_science_status            | DPI SCIENCE Status            | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hfi5-kdjh d:2013-01-01T00:00:00.000Z t:dpi_read_status=No t:dpi_science_status=Yes t:high_needs_dpi_overall_status=No t:district_name="Andover School District" t:dpi_overall_status=Yes t:dpi_write_status=Yes t:dpi_math_target_status=Yes t:district=1 t:frl_dpi_overall_status=No m:dpi_write_2013=91.3 m:dpi_read_2013=86.9 m:frl_dpi_overall_2013=77.4 m:dpi_science_2013=90.3 m:dpi_overall_2013=88.9 m:high_needs_dpi_overall_2013=69.6 m:dpi_math_2013=90.1

series e:hfi5-kdjh d:2013-01-01T00:00:00.000Z t:dpi_read_status=No t:ell_dpi_overall_status=No t:dpi_science_status=No t:black_dpi_overall_status=No t:high_needs_dpi_overall_status=No t:district_name="Ansonia School District" t:swd_dpi_overall_status=No t:dpi_overall_status=No t:dpi_write_status=No t:hispanic_dpi_overall_status=No t:dpi_math_target_status=No t:district=2 t:frl_dpi_overall_status=No m:dpi_write_2013=77.1 m:hispanic_dpi_overall_2013=64.3 m:swd_dpi_overall_2013=34.4 m:dpi_read_2013=65.1 m:frl_dpi_overall_2013=64.7 m:dpi_science_2013=58.4 m:black_dpi_overall_2013=60.8 m:dpi_overall_2013=68.2 m:high_needs_dpi_overall_2013=62.9 m:ell_dpi_overall_2013=47.2 m:dpi_math_2013=67.9

series e:hfi5-kdjh d:2013-01-01T00:00:00.000Z t:dpi_read_status=Yes t:dpi_science_status=Yes t:high_needs_dpi_overall_status=Yes t:district_name="Ashford School District" t:swd_dpi_overall_status=Yes t:dpi_overall_status=Yes t:dpi_write_status=Yes t:hispanic_dpi_overall_status=n/a t:dpi_math_target_status=No t:district=3 t:frl_dpi_overall_status=Yes m:dpi_write_2013=80.8 m:swd_dpi_overall_2013=56.6 m:dpi_read_2013=79.1 m:frl_dpi_overall_2013=71.8 m:dpi_science_2013=85.6 m:dpi_overall_2013=80.4 m:high_needs_dpi_overall_2013=66.9 m:dpi_math_2013=82
```

## Meta Commands

```ls
metric m:dpi_overall_2013 p:float l:"DPI OVERALL 2013" t:dataTypeName=number

metric m:black_dpi_overall_2013 p:double l:"Black DPI OVERALL 2013" t:dataTypeName=number

metric m:hispanic_dpi_overall_2013 p:float l:"Hispanic DPI OVERALL 2013" t:dataTypeName=number

metric m:ell_dpi_overall_2013 p:float l:"ELL DPI OVERALL 2013" t:dataTypeName=number

metric m:frl_dpi_overall_2013 p:float l:"FRL DPI OVERALL 2013" t:dataTypeName=number

metric m:swd_dpi_overall_2013 p:float l:"SWD DPI OVERALL 2013" t:dataTypeName=number

metric m:high_needs_dpi_overall_2013 p:float l:"High Needs DPI OVERALL 2013" t:dataTypeName=number

metric m:dpi_math_2013 p:float l:"DPI MATH 2013" t:dataTypeName=number

metric m:dpi_read_2013 p:float l:"DPI READ 2013" t:dataTypeName=number

metric m:dpi_write_2013 p:float l:"DPI WRITE 2013" t:dataTypeName=number

metric m:dpi_science_2013 p:float l:"DPI SCIENCE 2013" t:dataTypeName=number

entity e:hfi5-kdjh l:"CMT District Performance: 2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/hfi5-kdjh

property e:hfi5-kdjh t:meta.view v:id=hfi5-kdjh v:category=Education v:averageRating=0 v:name="CMT District Performance: 2013" v:attribution="State Department of Education"

property e:hfi5-kdjh t:meta.view.license v:name="Public Domain"

property e:hfi5-kdjh t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:hfi5-kdjh t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| district | district_name               | dpi_overall_2013 | dpi_overall_status | black_dpi_overall_2013 | black_dpi_overall_status | hispanic_dpi_overall_2013 | hispanic_dpi_overall_status | ell_dpi_overall_2013 | ell_dpi_overall_status | frl_dpi_overall_2013 | frl_dpi_overall_status | swd_dpi_overall_2013 | swd_dpi_overall_status | high_needs_dpi_overall_2013 | high_needs_dpi_overall_status | dpi_math_2013 | dpi_math_target_status | dpi_read_2013 | dpi_read_status | dpi_write_2013 | dpi_write_status | dpi_science_2013 | dpi_science_status | 
| ======== | =========================== | ================ | ================== | ====================== | ======================== | ========================= | =========================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | =========================== | ============================= | ============= | ====================== | ============= | =============== | ============== | ================ | ================ | ================== | 
| 1        | Andover School District     | 88.9             | Yes                |                        |                          |                           |                             |                      |                        | 77.4                 | No                     |                      |                        | 69.6                        | No                            | 90.1          | Yes                    | 86.9          | No              | 91.3           | Yes              | 90.3             | Yes                | 
| 2        | Ansonia School District     | 68.2             | No                 | 60.8                   | No                       | 64.3                      | No                          | 47.2                 | No                     | 64.7                 | No                     | 34.4                 | No                     | 62.9                        | No                            | 67.9          | No                     | 65.1          | No              | 77.1           | No               | 58.4             | No                 | 
| 3        | Ashford School District     | 80.4             | Yes                |                        |                          |                           | n/a                         |                      |                        | 71.8                 | Yes                    | 56.6                 | Yes                    | 66.9                        | Yes                           | 82            | No                     | 79.1          | Yes             | 80.8           | Yes              | 85.6             | Yes                | 
| 4        | Avon School District        | 93.8             | Yes                | 80.5                   | No                       | 86.6                      | No                          | 82.5                 | Yes                    | 79.4                 | No                     | 71.8                 | No                     | 75.9                        | No                            | 94.2          | Yes                    | 93.4          | Yes             | 94.7           | Yes              | 93.3             | Yes                | 
| 5        | Barkhamsted School District | 89.3             | Yes                |                        |                          |                           |                             |                      |                        |                      |                        | 68.5                 | No                     | 73.2                        | No                            | 90.6          | Yes                    | 86.6          | No              | 91.3           | Yes              | 95.1             | Yes                | 
| 7        | Berlin School District      | 86.8             | No                 | 64.5                   | No                       | 69.6                      | No                          | 54.9                 | No                     | 69.5                 | No                     | 51.1                 | No                     | 64.7                        | No                            | 87.1          | No                     | 85.9          | No              | 89.5           | Yes              | 87.2             | No                 | 
| 8        | Bethany School District     | 84.2             | No                 |                        |                          |                           |                             |                      |                        |                      |                        | 55.7                 | No                     | 59.3                        | No                            | 85.8          | No                     | 83.8          | No              | 85.2           | No               | 86               | No                 | 
| 9        | Bethel School District      | 88.9             | Yes                | 80.2                   | Yes                      | 84.4                      | No                          | 73.9                 | No                     | 82.9                 | No                     | 61.8                 | No                     | 76.6                        | No                            | 90            | Yes                    | 87.2          | No              | 90.1           | Yes              | 91.3             | Yes                | 
| 11       | Bloomfield School District  | 77.8             | Yes                | 77.5                   | Yes                      | 75.9                      | Yes                         | 61                   | Yes                    | 75.7                 | Yes                    | 48.8                 | Yes                    | 73.7                        | Yes                           | 78.8          | Yes                    | 76.3          | Yes             | 84.6           | Yes              | 64.8             | No                 | 
| 12       | Bolton School District      | 87               | No                 |                        | n/a                      |                           |                             |                      |                        | 68.8                 | Yes                    | 44.3                 | No                     | 60.6                        | No                            | 86.8          | No                     | 86.8          | Yes             | 88.1           | Yes              | 89.7             | Yes                | 
```