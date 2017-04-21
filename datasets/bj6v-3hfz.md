# CAPT District Performance: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capt-district-performance-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/bj6v-3hfz) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/bj6v-3hfz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/bj6v-3hfz/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | bj6v-3hfz |
| Name | CAPT District Performance: 2013 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, school district, capt, school performance |
| Created | 2014-03-21T17:00:09Z |
| Publication Date | 2014-03-21T17:01:58Z |

## Description

This dataset contains the Connecticut Academic Performance Test (CAPT) district performance indices (DPIs) and DPI target attainment status for 2012-13. These data were published in the District Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)

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
| Yes      | series tag     | dpi_write_status              | DPI WRITE Status              | text      | text        |
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
series e:bj6v-3hfz d:2013-01-01T00:00:00.000Z t:dpi_read_status=No t:dpi_science_status=Yes t:black_dpi_overall_status=Yes t:high_needs_dpi_overall_status=Yes t:district_name="Ansonia School District" t:swd_dpi_overall_status=n/a t:dpi_overall_status=No t:dpi_write_status=Yes t:hispanic_dpi_overall_status=Yes t:dpi_math_target_status=No t:district=2 t:frl_dpi_overall_status=Yes m:dpi_write_2013=69.2 m:hispanic_dpi_overall_2013=61 m:dpi_read_2013=55.9 m:frl_dpi_overall_2013=55.5 m:dpi_science_2013=63.1 m:black_dpi_overall_2013=52.3 m:dpi_overall_2013=57.8 m:high_needs_dpi_overall_2013=52.6 m:dpi_math_2013=52.4

series e:bj6v-3hfz d:2013-01-01T00:00:00.000Z t:dpi_read_status=Yes t:dpi_science_status=Yes t:high_needs_dpi_overall_status=Yes t:district_name="Avon School District" t:swd_dpi_overall_status=No t:dpi_overall_status=Yes t:dpi_write_status=Yes t:dpi_math_target_status=Yes t:district=4 m:dpi_write_2013=94.8 m:swd_dpi_overall_2013=61.4 m:dpi_read_2013=88.6 m:dpi_science_2013=92.3 m:dpi_overall_2013=91.7 m:high_needs_dpi_overall_2013=70.9 m:dpi_math_2013=92.5

series e:bj6v-3hfz d:2013-01-01T00:00:00.000Z t:dpi_read_status=No t:dpi_science_status=Yes t:high_needs_dpi_overall_status=No t:district_name="Berlin School District" t:swd_dpi_overall_status=No t:dpi_overall_status=No t:dpi_write_status=Yes t:hispanic_dpi_overall_status=n/a t:dpi_math_target_status=No t:district=7 t:frl_dpi_overall_status=No m:dpi_write_2013=92.7 m:hispanic_dpi_overall_2013=61.7 m:swd_dpi_overall_2013=55.4 m:dpi_read_2013=83.9 m:frl_dpi_overall_2013=60.9 m:dpi_science_2013=86.3 m:dpi_overall_2013=85.4 m:high_needs_dpi_overall_2013=62.2 m:dpi_math_2013=83
```

## Meta Commands

```ls
metric m:dpi_overall_2013 p:float l:"DPI OVERALL 2013" t:dataTypeName=number

metric m:black_dpi_overall_2013 p:double l:"Black DPI OVERALL 2013" t:dataTypeName=number

metric m:hispanic_dpi_overall_2013 p:float l:"Hispanic DPI OVERALL 2013" t:dataTypeName=number

metric m:ell_dpi_overall_2013 p:float l:"ELL DPI OVERALL 2013" t:dataTypeName=number

metric m:frl_dpi_overall_2013 p:double l:"FRL DPI OVERALL 2013" t:dataTypeName=number

metric m:swd_dpi_overall_2013 p:float l:"SWD DPI OVERALL 2013" t:dataTypeName=number

metric m:high_needs_dpi_overall_2013 p:float l:"High Needs DPI OVERALL 2013" t:dataTypeName=number

metric m:dpi_math_2013 p:float l:"DPI MATH 2013" t:dataTypeName=number

metric m:dpi_read_2013 p:float l:"DPI READ 2013" t:dataTypeName=number

metric m:dpi_write_2013 p:float l:"DPI WRITE 2013" t:dataTypeName=number

metric m:dpi_science_2013 p:float l:"DPI SCIENCE 2013" t:dataTypeName=number

entity e:bj6v-3hfz l:"CAPT District Performance: 2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/bj6v-3hfz

property e:bj6v-3hfz t:meta.view v:id=bj6v-3hfz v:category=Education v:averageRating=0 v:name="CAPT District Performance: 2013" v:attribution="State Department of Education"

property e:bj6v-3hfz t:meta.view.license v:name="Public Domain"

property e:bj6v-3hfz t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:bj6v-3hfz t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1491400192 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| district | district_name              | dpi_overall_2013 | dpi_overall_status | black_dpi_overall_2013 | black_dpi_overall_status | hispanic_dpi_overall_2013 | hispanic_dpi_overall_status | ell_dpi_overall_2013 | ell_dpi_overall_status | frl_dpi_overall_2013 | frl_dpi_overall_status | swd_dpi_overall_2013 | swd_dpi_overall_status | high_needs_dpi_overall_2013 | high_needs_dpi_overall_status | dpi_math_2013 | dpi_math_target_status | dpi_read_2013 | dpi_read_status | dpi_write_2013 | dpi_write_status | dpi_science_2013 | dpi_science_status | 
| ======== | ========================== | ================ | ================== | ====================== | ======================== | ========================= | =========================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | =========================== | ============================= | ============= | ====================== | ============= | =============== | ============== | ================ | ================ | ================== | 
| 2        | Ansonia School District    | 57.8             | No                 | 52.3                   | Yes                      | 61                        | Yes                         |                      |                        | 55.5                 | Yes                    |                      | n/a                    | 52.6                        | Yes                           | 52.4          | No                     | 55.9          | No              | 69.2           | Yes              | 63.1             | Yes                | 
| 4        | Avon School District       | 91.7             | Yes                |                        |                          |                           |                             |                      |                        |                      |                        | 61.4                 | No                     | 70.9                        | Yes                           | 92.5          | Yes                    | 88.6          | Yes             | 94.8           | Yes              | 92.3             | Yes                | 
| 7        | Berlin School District     | 85.4             | No                 |                        |                          | 61.7                      | n/a                         |                      |                        | 60.9                 | No                     | 55.4                 | No                     | 62.2                        | No                            | 83            | No                     | 83.9          | No              | 92.7           | Yes              | 86.3             | Yes                | 
| 9        | Bethel School District     | 81.6             | No                 |                        |                          | 68.3                      | No                          |                      |                        | 71.8                 | Yes                    | 45.4                 | No                     | 63.7                        | No                            | 77.9          | No                     | 80.2          | No              | 90.4           | Yes              | 79.7             | No                 | 
| 11       | Bloomfield School District | 64.2             | Yes                | 64.3                   | Yes                      |                           |                             |                      |                        | 63.6                 | Yes                    | 34.3                 | No                     | 60.4                        | Yes                           | 56.9          | Yes                    | 61.8          | Yes             | 76.5           | Yes              | 68.5             | Yes                | 
| 12       | Bolton School District     | 82.6             | No                 |                        |                          |                           |                             |                      |                        |                      |                        |                      |                        | 52.9                        | No                            | 78.3          | No                     | 84            | No              | 85             | No               | 83.8             | No                 | 
| 13       | Bozrah School District     | 86.6             | Yes                |                        |                          |                           |                             |                      |                        |                      |                        |                      |                        |                             |                               | 79.5          | No                     | 82.6          | Yes             | 95.3           | Yes              | 89               | Yes                | 
| 14       | Branford School District   | 82.7             | Yes                |                        |                          |                           | n/a                         |                      |                        | 66.5                 | No                     | 44.6                 | No                     | 62                          | No                            | 77.3          | No                     | 81.2          | Yes             | 89.7           | Yes              | 84.9             | Yes                | 
| 15       | Bridgeport School District | 38.4             | No                 | 35.9                   | No                       | 38.1                      | No                          | 20.1                 | No                     | 38.2                 | No                     | 12.5                 | No                     | 37.9                        | No                            | 33.2          | No                     | 37.7          | No              | 54.1           | No               | 37               | No                 | 
| 17       | Bristol School District    | 72.7             | No                 | 62.9                   | No                       | 58.3                      | No                          |                      |                        | 61.3                 | No                     | 37.1                 | No                     | 58.5                        | No                            | 72.3          | No                     | 69.5          | No              | 77.7           | No               | 75.1             | No                 | 
```