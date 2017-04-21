# CAPT School Performance: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capt-school-performance-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/y35x-5kpk) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/y35x-5kpk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/y35x-5kpk/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | y35x-5kpk |
| Name | CAPT School Performance: 2013 |
| Attribution | State |
| Category | Education |
| Tags | education, school, capt, school performance |
| Created | 2014-03-21T15:40:08Z |
| Publication Date | 2014-03-21T16:16:23Z |

## Description

This dataset contains the school classifications, school performance indices (SPIs), and SPI target attainment status for 2012-13 for all schools that administered the Connecticut Academic Performance Test (CAPT). It also includes school classifications assigned to high schools with non-tested grades. These data were published in the School Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)

Note: Target attainment status will say ?n/a? if there is no 2012-13 SPI target or if there is no 2012-13 SPI, which happens when there are small N sizes for a particular subgroup or subject.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | facility_code                 | Facility Code                 | text      | text        |
| Yes      | series tag     | district_name                 | District Name                 | text      | text        |
| Yes      | series tag     | school_name                   | School Name                   | text      | text        |
| Yes      | series tag     | capt_school_classification    | CAPT School Classification    | text      | text        |
| Yes      | numeric metric | spi_overall_2013              | SPI OVERALL 2013              | number    | number      |
| Yes      | series tag     | spi_overall_status            | SPI OVERALL Status            | text      | text        |
| Yes      | numeric metric | black_spi_overall_2013        | Black SPI OVERALL 2013        | number    | number      |
| Yes      | series tag     | black_spi_overall_status      | Black SPI OVERALL Status      | text      | text        |
| Yes      | numeric metric | hispanic_spi_overall_2013     | Hispanic SPI OVERALL 2013     | number    | number      |
| Yes      | series tag     | hispanic_spi_overall_status   | Hispanic SPI OVERALL Status   | text      | text        |
| Yes      | numeric metric | ell_spi_overall_2013          | ELL SPI OVERALL 2013          | number    | number      |
| Yes      | series tag     | ell_spi_overall_status        | ELL SPI OVERALL Status        | text      | text        |
| Yes      | numeric metric | frl_spi_overall_2013          | FRL SPI OVERALL 2013          | number    | number      |
| Yes      | series tag     | frl_spi_overall_status        | FRL SPI OVERALL Status        | text      | text        |
| Yes      | numeric metric | swd_spi_overall_2013          | SWD SPI OVERALL 2013          | number    | number      |
| Yes      | series tag     | swd_spi_overall_status        | SWD SPI OVERALL Status        | text      | text        |
| Yes      | numeric metric | high_needs_spi_overall_2013   | High Needs SPI OVERALL 2013   | number    | number      |
| Yes      | series tag     | high_needs_spi_overall_status | High Needs SPI OVERALL Status | text      | text        |
| Yes      | numeric metric | spi_math_2013                 | SPI MATH 2013                 | number    | number      |
| Yes      | series tag     | spi_math_target_status        | SPI MATH Target Status        | text      | text        |
| Yes      | numeric metric | spi_read_2013                 | SPI READ 2013                 | number    | number      |
| Yes      | series tag     | spi_read_status               | SPI READ Status               | text      | text        |
| Yes      | numeric metric | spi_write_2013                | SPI WRITE 2013                | number    | number      |
| Yes      | series tag     | spi_write_status              | SPI WRITE Status              | text      | text        |
| Yes      | numeric metric | spi_science_2013              | SPI SCIENCE 2013              | number    | number      |
| Yes      | series tag     | spi_science_status            | SPI SCIENCE Status            | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y35x-5kpk d:2013-01-01T00:00:00.000Z t:spi_write_status=Yes t:black_spi_overall_status=Yes t:district_name="Ansonia School District" t:spi_overall_status=No t:school_name="Ansonia High School" t:frl_spi_overall_status=Yes t:spi_math_target_status=No t:hispanic_spi_overall_status=Yes t:spi_read_status=No t:facility_code=0026111 t:capt_school_classification=REVIEW t:high_needs_spi_overall_status=Yes t:spi_science_status=Yes m:spi_overall_2013=58.3 m:hispanic_spi_overall_2013=61 m:frl_spi_overall_2013=55.9 m:black_spi_overall_2013=52.3 m:spi_math_2013=52.8 m:spi_read_2013=56.3 m:spi_write_2013=69.9 m:spi_science_2013=63.8 m:high_needs_spi_overall_2013=53.4

series e:y35x-5kpk d:2013-01-01T00:00:00.000Z t:spi_write_status=Yes t:swd_spi_overall_status=No t:district_name="Avon School District" t:spi_overall_status=Yes t:school_name="Avon High School" t:spi_math_target_status=Yes t:spi_read_status=Yes t:facility_code=0046111 t:capt_school_classification=PROGRESSING t:high_needs_spi_overall_status=Yes t:spi_science_status=Yes m:spi_overall_2013=92.1 m:swd_spi_overall_2013=63.8 m:spi_math_2013=92.9 m:spi_read_2013=89 m:spi_write_2013=95.1 m:spi_science_2013=92.7 m:high_needs_spi_overall_2013=72.7

series e:y35x-5kpk d:2013-01-01T00:00:00.000Z t:spi_write_status=Yes t:swd_spi_overall_status=No t:district_name="Berlin School District" t:spi_overall_status=No t:school_name="Berlin High School" t:frl_spi_overall_status=No t:spi_math_target_status=No t:hispanic_spi_overall_status=n/a t:spi_read_status=No t:facility_code=0076111 t:capt_school_classification=TRANSITIONING t:high_needs_spi_overall_status=No t:spi_science_status=Yes m:spi_overall_2013=85.7 m:hispanic_spi_overall_2013=61.7 m:frl_spi_overall_2013=60.9 m:swd_spi_overall_2013=56.4 m:spi_math_2013=83.4 m:spi_read_2013=84.3 m:spi_write_2013=92.9 m:spi_science_2013=86.4 m:high_needs_spi_overall_2013=62.9
```

## Meta Commands

```ls
metric m:spi_overall_2013 p:float l:"SPI OVERALL 2013" t:dataTypeName=number

metric m:black_spi_overall_2013 p:float l:"Black SPI OVERALL 2013" t:dataTypeName=number

metric m:hispanic_spi_overall_2013 p:float l:"Hispanic SPI OVERALL 2013" t:dataTypeName=number

metric m:ell_spi_overall_2013 p:float l:"ELL SPI OVERALL 2013" t:dataTypeName=number

metric m:frl_spi_overall_2013 p:float l:"FRL SPI OVERALL 2013" t:dataTypeName=number

metric m:swd_spi_overall_2013 p:float l:"SWD SPI OVERALL 2013" t:dataTypeName=number

metric m:high_needs_spi_overall_2013 p:float l:"High Needs SPI OVERALL 2013" t:dataTypeName=number

metric m:spi_math_2013 p:float l:"SPI MATH 2013" t:dataTypeName=number

metric m:spi_read_2013 p:double l:"SPI READ 2013" t:dataTypeName=number

metric m:spi_write_2013 p:float l:"SPI WRITE 2013" t:dataTypeName=number

metric m:spi_science_2013 p:float l:"SPI SCIENCE 2013" t:dataTypeName=number

entity e:y35x-5kpk l:"CAPT School Performance: 2013" t:attribution=State t:url=https://data.ct.gov/api/views/y35x-5kpk

property e:y35x-5kpk t:meta.view v:id=y35x-5kpk v:category=Education v:averageRating=0 v:name="CAPT School Performance: 2013" v:attribution=State

property e:y35x-5kpk t:meta.view.license v:name="Public Domain"

property e:y35x-5kpk t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:y35x-5kpk t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| facility_code | district_name              | school_name                     | capt_school_classification | spi_overall_2013 | spi_overall_status | black_spi_overall_2013 | black_spi_overall_status | hispanic_spi_overall_2013 | hispanic_spi_overall_status | ell_spi_overall_2013 | ell_spi_overall_status | frl_spi_overall_2013 | frl_spi_overall_status | swd_spi_overall_2013 | swd_spi_overall_status | high_needs_spi_overall_2013 | high_needs_spi_overall_status | spi_math_2013 | spi_math_target_status | spi_read_2013 | spi_read_status | spi_write_2013 | spi_write_status | spi_science_2013 | spi_science_status | 
| ============= | ========================== | =============================== | ========================== | ================ | ================== | ====================== | ======================== | ========================= | =========================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | =========================== | ============================= | ============= | ====================== | ============= | =============== | ============== | ================ | ================ | ================== | 
| 0026111       | Ansonia School District    | Ansonia High School             | REVIEW                     | 58.3             | No                 | 52.3                   | Yes                      | 61                        | Yes                         |                      |                        | 55.9                 | Yes                    |                      |                        | 53.4                        | Yes                           | 52.8          | No                     | 56.3          | No              | 69.9           | Yes              | 63.8             | Yes                | 
| 0046111       | Avon School District       | Avon High School                | PROGRESSING                | 92.1             | Yes                |                        |                          |                           |                             |                      |                        |                      |                        | 63.8                 | No                     | 72.7                        | Yes                           | 92.9          | Yes                    | 89            | Yes             | 95.1           | Yes              | 92.7             | Yes                | 
| 0076111       | Berlin School District     | Berlin High School              | TRANSITIONING              | 85.7             | No                 |                        |                          | 61.7                      | n/a                         |                      |                        | 60.9                 | No                     | 56.4                 | No                     | 62.9                        | No                            | 83.4          | No                     | 84.3          | No              | 92.9           | Yes              | 86.4             | Yes                | 
| 0096111       | Bethel School District     | Bethel High School              | TRANSITIONING              | 82.8             | No                 |                        |                          | 68.3                      | No                          |                      |                        | 73.6                 | Yes                    | 47.9                 | No                     | 66.6                        | Yes                           | 79.2          | No                     | 81.3          | No              | 91.4           | Yes              | 80.3             | No                 | 
| 0116111       | Bloomfield School District | Bloomfield High School          | TURNAROUND                 | 66.2             | Yes                | 65.8                   | Yes                      |                           |                             |                      |                        | 66.6                 | Yes                    |                      | n/a                    | 63.1                        | Yes                           | 58.9          | Yes                    | 65.8          | Yes             | 76.5           | No               | 70.6             | Yes                | 
| 0116311       | Bloomfield School District | Global Experience Magnet School | REVIEW                     | 58.8             | n/a                | 57.1                   | n/a                      |                           |                             |                      |                        |                      |                        |                      |                        |                             |                               | 53.3          | n/a                    | 47.8          | n/a             | 77.2           | n/a              | 60.8             | n/a                | 
| 0116411       | Bloomfield School District | Learning Academy at Bloomfield  | TRANSITIONING              |                  |                    |                        |                          |                           |                             |                      |                        |                      |                        |                      |                        |                             |                               |               |                        |               |                 |                |                  |                  |                    | 
| 0126111       | Bolton School District     | Bolton High School              | TRANSITIONING              | 83.2             | No                 |                        |                          |                           |                             |                      |                        |                      |                        |                      |                        |                             | n/a                           | 78.6          | No                     | 84.8          | No              | 85.9           | No               | 84.2             | No                 | 
| 0146111       | Branford School District   | Branford High School            | TRANSITIONING              | 84.9             | Yes                |                        |                          |                           | n/a                         |                      |                        | 69.6                 | No                     |                      | n/a                    | 68.6                        | No                            | 79.3          | Yes                    | 83.5          | Yes             | 92.2           | Yes              | 87.1             | Yes                | 
| 0156111       | Bridgeport School District | Bassick High School             | TURNAROUND                 | 31               | No                 | 28.8                   | No                       | 31.8                      | Yes                         | 22.3                 | Yes                    | 30.9                 | No                     | 12.7                 | No                     | 30.9                        | No                            | 24.3          | No                     | 30.7          | No              | 46.3           | Yes              | 29.3             | No                 | 
```