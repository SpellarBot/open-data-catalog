# CMT School Performance: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cmt-school-performance-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/t7dz-qwpn) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/t7dz-qwpn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/t7dz-qwpn/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | t7dz-qwpn |
| Name | CMT School Performance: 2013 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, school, cmt, school performance |
| Created | 2014-03-21T15:43:49Z |
| Publication Date | 2014-03-21T15:47:51Z |

## Description

This dataset contains the school classifications, school performance indices (SPIs), and SPI target attainment status for 2012-13 for all schools that administered the Connecticut Mastery Test (CMT). It also includes school classifications assigned to elementary/middle schools with non-tested grades. These data were published in the School Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)

Note: Target attainment status says ?n/a? if there is no 2012-13 SPI target or if there is no 2012-13 SPI, which happens when there are small N sizes for a particular subgroup or subject.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | facility_code                 | Facility Code                 | text      | text        |
| Yes      | series tag     | districtname                  | DistrictName                  | text      | text        |
| Yes      | series tag     | schoolname                    | SchoolName                    | text      | text        |
| Yes      | series tag     | cmt_school_classification     | CMT School Classification     | text      | text        |
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
series e:t7dz-qwpn d:2013-01-01T00:00:00.000Z t:spi_write_status=Yes t:schoolname="Andover Elementary School" t:spi_overall_status=Yes t:frl_spi_overall_status=No t:districtname="Andover School District" t:spi_math_target_status=Yes t:spi_read_status=No t:facility_code=0010111 t:high_needs_spi_overall_status=No t:cmt_school_classification=PROGRESSING t:spi_science_status=Yes m:spi_overall_2013=89.7 m:frl_spi_overall_2013=79.2 m:spi_math_2013=90.8 m:spi_read_2013=87.6 m:spi_write_2013=92.4 m:spi_science_2013=92.1 m:high_needs_spi_overall_2013=72.4

series e:t7dz-qwpn d:2013-01-01T00:00:00.000Z t:frl_spi_overall_status=Yes t:spi_overall_status=No t:districtname="Ansonia School District" t:hispanic_spi_overall_status=Yes t:facility_code=0020311 t:cmt_school_classification=TRANSITIONING t:spi_write_status=Yes t:swd_spi_overall_status=Yes t:black_spi_overall_status=Yes t:schoolname="Mead School" t:spi_math_target_status=No t:spi_read_status=Yes t:high_needs_spi_overall_status=Yes t:spi_science_status=No m:spi_overall_2013=76.6 m:hispanic_spi_overall_2013=72.5 m:frl_spi_overall_2013=74.5 m:swd_spi_overall_2013=44.9 m:black_spi_overall_2013=73.6 m:spi_math_2013=74.2 m:spi_read_2013=72.5 m:spi_write_2013=87.6 m:spi_science_2013=72.7 m:high_needs_spi_overall_2013=72

series e:t7dz-qwpn d:2013-01-01T00:00:00.000Z t:frl_spi_overall_status=No t:spi_overall_status=No t:districtname="Ansonia School District" t:hispanic_spi_overall_status=No t:facility_code=0020811 t:cmt_school_classification=TRANSITIONING t:spi_write_status=No t:swd_spi_overall_status=No t:black_spi_overall_status=No t:schoolname="Prendergast School" t:spi_math_target_status=No t:spi_read_status=No t:high_needs_spi_overall_status=No t:spi_science_status=No m:spi_overall_2013=65.3 m:hispanic_spi_overall_2013=60.2 m:frl_spi_overall_2013=59.7 m:swd_spi_overall_2013=32.2 m:black_spi_overall_2013=53.7 m:spi_math_2013=66.2 m:spi_read_2013=58.2 m:spi_write_2013=74.1 m:spi_science_2013=67.5 m:high_needs_spi_overall_2013=59.2
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

metric m:spi_read_2013 p:float l:"SPI READ 2013" t:dataTypeName=number

metric m:spi_write_2013 p:float l:"SPI WRITE 2013" t:dataTypeName=number

metric m:spi_science_2013 p:float l:"SPI SCIENCE 2013" t:dataTypeName=number

entity e:t7dz-qwpn l:"CMT School Performance: 2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/t7dz-qwpn

property e:t7dz-qwpn t:meta.view v:id=t7dz-qwpn v:category=Education v:averageRating=0 v:name="CMT School Performance: 2013" v:attribution="State Department of Education"

property e:t7dz-qwpn t:meta.view.license v:name="Public Domain"

property e:t7dz-qwpn t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:t7dz-qwpn t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| facility_code | districtname                | schoolname                    | cmt_school_classification | spi_overall_2013 | spi_overall_status | black_spi_overall_2013 | black_spi_overall_status | hispanic_spi_overall_2013 | hispanic_spi_overall_status | ell_spi_overall_2013 | ell_spi_overall_status | frl_spi_overall_2013 | frl_spi_overall_status | swd_spi_overall_2013 | swd_spi_overall_status | high_needs_spi_overall_2013 | high_needs_spi_overall_status | spi_math_2013 | spi_math_target_status | spi_read_2013 | spi_read_status | spi_write_2013 | spi_write_status | spi_science_2013 | spi_science_status | 
| ============= | =========================== | ============================= | ========================= | ================ | ================== | ====================== | ======================== | ========================= | =========================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | =========================== | ============================= | ============= | ====================== | ============= | =============== | ============== | ================ | ================ | ================== | 
| 0010111       | Andover School District     | Andover Elementary School     | PROGRESSING               | 89.7             | Yes                |                        |                          |                           |                             |                      |                        | 79.2                 | No                     |                      |                        | 72.4                        | No                            | 90.8          | Yes                    | 87.6          | No              | 92.4           | Yes              | 92.1             | Yes                | 
| 0020311       | Ansonia School District     | Mead School                   | TRANSITIONING             | 76.6             | No                 | 73.6                   | Yes                      | 72.5                      | Yes                         |                      |                        | 74.5                 | Yes                    | 44.9                 | Yes                    | 72                          | Yes                           | 74.2          | No                     | 72.5          | Yes             | 87.6           | Yes              | 72.7             | No                 | 
| 0020811       | Ansonia School District     | Prendergast School            | TRANSITIONING             | 65.3             | No                 | 53.7                   | No                       | 60.2                      | No                          |                      |                        | 59.7                 | No                     | 32.2                 | No                     | 59.2                        | No                            | 66.2          | No                     | 58.2          | No              | 74.1           | No               | 67.5             | No                 | 
| 0025111       | Ansonia School District     | Ansonia Middle School         | TRANSITIONING             | 67               | No                 | 60.8                   | No                       | 63                        | No                          |                      | n/a                    | 63.7                 | No                     | 31.1                 | No                     | 62.4                        | No                            | 68.1          | No                     | 68.6          | No              | 73.6           | Yes              | 50               | No                 | 
| 0030111       | Ashford School District     | Ashford School                | TRANSITIONING             | 80.7             | No                 |                        |                          |                           | n/a                         |                      |                        | 71.8                 | Yes                    | 57.6                 | Yes                    | 67.5                        | Yes                           | 82.2          | No                     | 79.3          | Yes             | 81.3           | Yes              | 85.6             | Yes                | 
| 0040311       | Avon School District        | Roaring Brook School          | PROGRESSING               | 92.7             | Yes                |                        |                          |                           |                             |                      |                        |                      |                        | 65.6                 | No                     | 70.2                        | No                            | 92.3          | Yes                    | 92.1          | Yes             | 94.2           | Yes              |                  |                    | 
| 0040411       | Avon School District        | Pine Grove School             | PROGRESSING               | 92.9             | Yes                |                        |                          |                           |                             |                      |                        |                      | n/a                    | 74.8                 | Yes                    | 72.5                        | No                            | 94            | Yes                    | 92.3          | Yes             | 92.5           | Yes              |                  |                    | 
| 0040511       | Avon School District        | Thompson Brook School         | EXCELLING                 | 93.3             | Yes                |                        |                          | 87.8                      | No                          | 84.2                 | n/a                    | 81.2                 | No                     | 69.9                 | No                     | 77.1                        | No                            | 93.5          | Yes                    | 91.9          | Yes             | 95.7           | Yes              | 92.4             | Yes                | 
| 0045111       | Avon School District        | Avon Middle School            | PROGRESSING               | 95.7             | Yes                |                        |                          | 91                        | Yes                         |                      |                        | 81.8                 | No                     | 79.2                 | No                     | 81.5                        | No                            | 96.3          | Yes                    | 96.4          | Yes             | 95.6           | Yes              | 94.7             | Yes                | 
| 0050111       | Barkhamsted School District | Barkhamsted Elementary School | PROGRESSING               | 89.6             | Yes                |                        |                          |                           |                             |                      |                        |                      |                        | 69.9                 | No                     | 74.4                        | No                            | 90.8          | Yes                    | 87.1          | No              | 91.5           | Yes              | 95.1             | Yes                | 
```