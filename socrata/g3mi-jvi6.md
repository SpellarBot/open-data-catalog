# CMT District Performance: 2010-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cmt-district-performance-2010-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/g3mi-jvi6) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/g3mi-jvi6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/g3mi-jvi6/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | g3mi-jvi6 |
| Name | CMT District Performance: 2010-2012 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, school district, cmt, school performance |
| Created | 2014-04-01T13:09:26Z |
| Publication Date | 2014-04-01T13:29:52Z |

## Description

This dataset contains the Connecticut Mastery Test (CMT) district performance indices (DPIs) for 2009-10 (2010), 2010-11 (2011), and 2011-12 (2012). These data were published in the District Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)
 
Note: Cells are left blank if there is no DPI, which happens when there are small N sizes for a particular subgroup or subject.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | district                    | District                    | text      | number      |
| Yes      | series tag     | district_name               | District Name               | text      | text        |
| Yes      | numeric metric | dpi_overall_2010            | DPI OVERALL 2010            | number    | number      |
| Yes      | numeric metric | dpi_overall_2011            | DPI OVERALL 2011            | number    | number      |
| Yes      | numeric metric | dpi_overall_2012            | DPI OVERALL 2012            | number    | number      |
| Yes      | numeric metric | black_dpi_overall_2010      | Black DPI OVERALL 2010      | number    | number      |
| Yes      | numeric metric | black_dpi_overall_2011      | Black DPI OVERALL 2011      | number    | number      |
| Yes      | numeric metric | black_dpi_overall_2012      | Black DPI OVERALL 2012      | number    | number      |
| Yes      | numeric metric | hispanic_dpi_overall_2010   | Hispanic DPI OVERALL 2010   | number    | number      |
| Yes      | numeric metric | hispanic_dpi_overall_2011   | Hispanic DPI OVERALL 2011   | number    | number      |
| Yes      | numeric metric | hispanic_dpi_overall_2012   | Hispanic DPI OVERALL 2012   | number    | number      |
| Yes      | numeric metric | ell_dpi_overall_2010        | ELL DPI OVERALL 2010        | number    | number      |
| Yes      | numeric metric | ell_dpi_overall_2011        | ELL DPI OVERALL 2011        | number    | number      |
| Yes      | numeric metric | ell_dpi_overall_2012        | ELL DPI OVERALL 2012        | number    | number      |
| Yes      | numeric metric | frl_dpi_overall_2010        | FRL DPI OVERALL 2010        | number    | number      |
| Yes      | numeric metric | frl_dpi_overall_2011        | FRL DPI OVERALL 2011        | number    | number      |
| Yes      | numeric metric | frl_dpi_overall_2012        | FRL DPI OVERALL 2012        | number    | number      |
| Yes      | numeric metric | swd_dpi_overall_2010        | SWD DPI OVERALL 2010        | number    | number      |
| Yes      | numeric metric | swd_dpi_overall_2011        | SWD DPI OVERALL 2011        | number    | number      |
| Yes      | numeric metric | swd_dpi_overall_2012        | SWD DPI OVERALL 2012        | number    | number      |
| Yes      | numeric metric | high_needs_dpi_overall_2010 | High Needs DPI OVERALL 2010 | number    | number      |
| Yes      | numeric metric | high_needs_dpi_overall_2011 | High Needs DPI OVERALL 2011 | number    | number      |
| Yes      | numeric metric | high_needs_dpi_overall_2012 | High Needs DPI OVERALL 2012 | number    | number      |
| Yes      | numeric metric | overall_dpi_math_2010       | Overall DPI MATH 2010       | number    | number      |
| Yes      | numeric metric | overall_dpi_math_2011       | Overall DPI MATH 2011       | number    | number      |
| Yes      | numeric metric | overall_dpi_math_2012       | Overall DPI MATH 2012       | number    | number      |
| Yes      | numeric metric | overall_dpi_read_2010       | Overall DPI READ 2010       | number    | number      |
| Yes      | numeric metric | overall_dpi_read_2011       | Overall DPI READ 2011       | number    | number      |
| Yes      | numeric metric | overall_dpi_read_2012       | Overall DPI READ 2012       | number    | number      |
| Yes      | numeric metric | overall_dpi_write_2010      | Overall DPI WRITE 2010      | number    | number      |
| Yes      | numeric metric | overall_dpi_write_2011      | Overall DPI WRITE 2011      | number    | number      |
| Yes      | numeric metric | overall_dpi_write_2012      | Overall DPI WRITE 2012      | number    | number      |
| Yes      | numeric metric | overall_dpi_science_2010    | Overall DPI SCIENCE 2010    | number    | number      |
| Yes      | numeric metric | overall_dpi_science_2011    | Overall DPI SCIENCE 2011    | number    | number      |
| Yes      | numeric metric | overall_dpi_science_2012    | Overall DPI SCIENCE 2012    | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g3mi-jvi6 d:2010-01-01T00:00:00.000Z t:district_name="Andover School District" t:district=1 m:overall_dpi_write_2010=91.3 m:overall_dpi_write_2012=90 m:overall_dpi_write_2011=93.8 m:high_needs_dpi_overall_2012=72.9 m:high_needs_dpi_overall_2011=80.3 m:high_needs_dpi_overall_2010=76 m:dpi_overall_2010=90.7 m:overall_dpi_science_2012=97.9 m:overall_dpi_science_2011=91.5 m:dpi_overall_2011=90.8 m:overall_dpi_science_2010=91.9 m:dpi_overall_2012=90.3 m:frl_dpi_overall_2011=86.8 m:frl_dpi_overall_2012=73.9 m:overall_dpi_math_2010=91.6 m:overall_dpi_read_2010=89.2 m:overall_dpi_math_2011=91.2 m:overall_dpi_read_2011=88.2 m:overall_dpi_math_2012=92.1 m:overall_dpi_read_2012=90.5

series e:g3mi-jvi6 d:2010-01-01T00:00:00.000Z t:district_name="Ansonia School District" t:district=2 m:overall_dpi_write_2010=77.1 m:overall_dpi_write_2012=79.5 m:overall_dpi_write_2011=78.9 m:black_dpi_overall_2010=64.8 m:black_dpi_overall_2011=64.6 m:black_dpi_overall_2012=59.6 m:swd_dpi_overall_2012=35.2 m:swd_dpi_overall_2010=38.8 m:swd_dpi_overall_2011=36 m:overall_dpi_math_2010=79.9 m:ell_dpi_overall_2012=51.7 m:ell_dpi_overall_2011=54.2 m:overall_dpi_math_2011=78 m:overall_dpi_math_2012=73.1 m:ell_dpi_overall_2010=55.2 m:hispanic_dpi_overall_2012=66.9 m:hispanic_dpi_overall_2011=68.2 m:hispanic_dpi_overall_2010=65.8 m:high_needs_dpi_overall_2012=65.3 m:high_needs_dpi_overall_2011=66.3 m:high_needs_dpi_overall_2010=66 m:dpi_overall_2010=72.9 m:overall_dpi_science_2012=67.2 m:dpi_overall_2011=72.9 m:overall_dpi_science_2011=63 m:dpi_overall_2012=70.8 m:overall_dpi_science_2010=66.6 m:frl_dpi_overall_2010=67.5 m:frl_dpi_overall_2011=67.9 m:frl_dpi_overall_2012=66.5 m:overall_dpi_read_2010=64.7 m:overall_dpi_read_2011=66.4 m:overall_dpi_read_2012=65

series e:g3mi-jvi6 d:2010-01-01T00:00:00.000Z t:district_name="Ashford School District" t:district=3 m:hispanic_dpi_overall_2012=70.5 m:overall_dpi_write_2010=78.7 m:overall_dpi_write_2012=82.1 m:overall_dpi_write_2011=78 m:high_needs_dpi_overall_2012=67.5 m:high_needs_dpi_overall_2011=63.7 m:high_needs_dpi_overall_2010=61.9 m:overall_dpi_science_2012=82.3 m:dpi_overall_2010=79 m:overall_dpi_science_2011=82.5 m:dpi_overall_2011=78.6 m:dpi_overall_2012=81 m:overall_dpi_science_2010=86 m:swd_dpi_overall_2012=51.2 m:frl_dpi_overall_2010=68.1 m:frl_dpi_overall_2011=67.8 m:swd_dpi_overall_2010=49 m:frl_dpi_overall_2012=72.6 m:swd_dpi_overall_2011=47.9 m:overall_dpi_math_2010=82.9 m:overall_dpi_read_2010=76.1 m:overall_dpi_math_2011=82.5 m:overall_dpi_read_2011=76.8 m:overall_dpi_math_2012=83.2 m:overall_dpi_read_2012=80
```

## Meta Commands

```ls
metric m:dpi_overall_2010 p:float l:"DPI OVERALL 2010" t:dataTypeName=number

metric m:dpi_overall_2011 p:float l:"DPI OVERALL 2011" t:dataTypeName=number

metric m:dpi_overall_2012 p:float l:"DPI OVERALL 2012" t:dataTypeName=number

metric m:black_dpi_overall_2010 p:float l:"Black DPI OVERALL 2010" t:dataTypeName=number

metric m:black_dpi_overall_2011 p:double l:"Black DPI OVERALL 2011" t:dataTypeName=number

metric m:black_dpi_overall_2012 p:float l:"Black DPI OVERALL 2012" t:dataTypeName=number

metric m:hispanic_dpi_overall_2010 p:float l:"Hispanic DPI OVERALL 2010" t:dataTypeName=number

metric m:hispanic_dpi_overall_2011 p:float l:"Hispanic DPI OVERALL 2011" t:dataTypeName=number

metric m:hispanic_dpi_overall_2012 p:float l:"Hispanic DPI OVERALL 2012" t:dataTypeName=number

metric m:ell_dpi_overall_2010 p:float l:"ELL DPI OVERALL 2010" t:dataTypeName=number

metric m:ell_dpi_overall_2011 p:double l:"ELL DPI OVERALL 2011" t:dataTypeName=number

metric m:ell_dpi_overall_2012 p:float l:"ELL DPI OVERALL 2012" t:dataTypeName=number

metric m:frl_dpi_overall_2010 p:float l:"FRL DPI OVERALL 2010" t:dataTypeName=number

metric m:frl_dpi_overall_2011 p:float l:"FRL DPI OVERALL 2011" t:dataTypeName=number

metric m:frl_dpi_overall_2012 p:float l:"FRL DPI OVERALL 2012" t:dataTypeName=number

metric m:swd_dpi_overall_2010 p:float l:"SWD DPI OVERALL 2010" t:dataTypeName=number

metric m:swd_dpi_overall_2011 p:float l:"SWD DPI OVERALL 2011" t:dataTypeName=number

metric m:swd_dpi_overall_2012 p:float l:"SWD DPI OVERALL 2012" t:dataTypeName=number

metric m:high_needs_dpi_overall_2010 p:float l:"High Needs DPI OVERALL 2010" t:dataTypeName=number

metric m:high_needs_dpi_overall_2011 p:float l:"High Needs DPI OVERALL 2011" t:dataTypeName=number

metric m:high_needs_dpi_overall_2012 p:float l:"High Needs DPI OVERALL 2012" t:dataTypeName=number

metric m:overall_dpi_math_2010 p:float l:"Overall DPI MATH 2010" t:dataTypeName=number

metric m:overall_dpi_math_2011 p:float l:"Overall DPI MATH 2011" t:dataTypeName=number

metric m:overall_dpi_math_2012 p:float l:"Overall DPI MATH 2012" t:dataTypeName=number

metric m:overall_dpi_read_2010 p:float l:"Overall DPI READ 2010" t:dataTypeName=number

metric m:overall_dpi_read_2011 p:float l:"Overall DPI READ 2011" t:dataTypeName=number

metric m:overall_dpi_read_2012 p:float l:"Overall DPI READ 2012" t:dataTypeName=number

metric m:overall_dpi_write_2010 p:float l:"Overall DPI WRITE 2010" t:dataTypeName=number

metric m:overall_dpi_write_2011 p:float l:"Overall DPI WRITE 2011" t:dataTypeName=number

metric m:overall_dpi_write_2012 p:float l:"Overall DPI WRITE 2012" t:dataTypeName=number

metric m:overall_dpi_science_2010 p:float l:"Overall DPI SCIENCE 2010" t:dataTypeName=number

metric m:overall_dpi_science_2011 p:float l:"Overall DPI SCIENCE 2011" t:dataTypeName=number

metric m:overall_dpi_science_2012 p:float l:"Overall DPI SCIENCE 2012" t:dataTypeName=number

entity e:g3mi-jvi6 l:"CMT District Performance: 2010-2012" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/g3mi-jvi6

property e:g3mi-jvi6 t:meta.view v:id=g3mi-jvi6 v:category=Education v:averageRating=0 v:name="CMT District Performance: 2010-2012" v:attribution="State Department of Education"

property e:g3mi-jvi6 t:meta.view.license v:name="Public Domain"

property e:g3mi-jvi6 t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:g3mi-jvi6 t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| district | district_name               | dpi_overall_2010   | dpi_overall_2011   | dpi_overall_2012 | black_dpi_overall_2010 | black_dpi_overall_2011 | black_dpi_overall_2012 | hispanic_dpi_overall_2010 | hispanic_dpi_overall_2011 | hispanic_dpi_overall_2012 | ell_dpi_overall_2010 | ell_dpi_overall_2011 | ell_dpi_overall_2012 | frl_dpi_overall_2010 | frl_dpi_overall_2011 | frl_dpi_overall_2012 | swd_dpi_overall_2010 | swd_dpi_overall_2011 | swd_dpi_overall_2012 | high_needs_dpi_overall_2010 | high_needs_dpi_overall_2011 | high_needs_dpi_overall_2012 | overall_dpi_math_2010 | overall_dpi_math_2011 | overall_dpi_math_2012 | overall_dpi_read_2010 | overall_dpi_read_2011 | overall_dpi_read_2012 | overall_dpi_write_2010 | overall_dpi_write_2011 | overall_dpi_write_2012 | overall_dpi_science_2010 | overall_dpi_science_2011 | overall_dpi_science_2012 | 
| ======== | =========================== | ================== | ================== | ================ | ====================== | ====================== | ====================== | ========================= | ========================= | ========================= | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | =========================== | =========================== | =========================== | ===================== | ===================== | ===================== | ===================== | ===================== | ===================== | ====================== | ====================== | ====================== | ======================== | ======================== | ======================== | 
| 1        | Andover School District     | 90.7               | 90.8               | 90.3             |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      | 86.8                 | 73.900000000000006   |                      |                      |                      | 76                          | 80.3                        | 72.900000000000006          | 91.6                  | 91.2                  | 92.1                  | 89.2                  | 88.2                  | 90.5                  | 91.3                   | 93.8                   | 90                     | 91.9                     | 91.5                     | 97.9                     | 
| 2        | Ansonia School District     | 72.900000000000006 | 72.900000000000006 | 70.8             | 64.8                   | 64.6                   | 59.6                   | 65.8                      | 68.2                      | 66.900000000000006        | 55.2                 | 54.2                 | 51.7                 | 67.5                 | 67.900000000000006   | 66.5                 | 38.799999999999997   | 36                   | 35.200000000000003   | 66                          | 66.3                        | 65.3                        | 79.900000000000006    | 78                    | 73.099999999999994    | 64.7                  | 66.400000000000006    | 65                    | 77.099999999999994     | 78.900000000000006     | 79.5                   | 66.599999999999994       | 63                       | 67.2                     | 
| 3        | Ashford School District     | 79                 | 78.599999999999994 | 81               |                        |                        |                        |                           |                           | 70.5                      |                      |                      |                      | 68.099999999999994   | 67.8                 | 72.599999999999994   | 49                   | 47.9                 | 51.2                 | 61.9                        | 63.7                        | 67.5                        | 82.9                  | 82.5                  | 83.2                  | 76.099999999999994    | 76.8                  | 80                    | 78.7                   | 78                     | 82.1                   | 86                       | 82.5                     | 82.3                     | 
| 4        | Avon School District        | 94.5               | 94.2               | 94.5             | 86                     | 79.7                   | 79.6                   | 91.3                      | 87.1                      | 86.2                      | 77                   | 82.3                 | 79.7                 | 84.3                 | 82                   | 80.2                 | 76                   | 74.599999999999994   | 73.3                 | 79.400000000000006          | 78.900000000000006          | 77.099999999999994          | 94.9                  | 95                    | 95.1                  | 94.1                  | 93.1                  | 93.8                  | 95.5                   | 95.4                   | 95.7                   | 95.2                     | 95.5                     | 95.1                     | 
| 5        | Barkhamsted School District | 89.4               | 92.2               | 90.7             |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      |                      |                      | 68.5                 | 81.3                 | 74.099999999999994   | 75.3                        | 85.5                        | 76.5                        | 90.3                  | 92.1                  | 92.3                  | 87.4                  | 90.2                  | 88.1                  | 91.3                   | 95.2                   | 93.3                   | 95.8                     | 91.6                     | 96.3                     | 
| 7        | Berlin School District      | 90                 | 89.8               | 89.4             | 62                     | 69.2                   | 64.7                   | 69.8                      | 76.5                      | 74.8                      | 74.9                 | 69                   | 62.1                 | 72.099999999999994   | 72.3                 | 72.900000000000006   | 63.3                 | 61.6                 | 56.7                 | 70.7                        | 70.099999999999994          | 68.2                        | 91.8                  | 90.3                  | 90.3                  | 88                    | 89                    | 88                    | 91.8                   | 91.2                   | 91.6                   | 90.2                     | 93                       | 92                       | 
| 8        | Bethany School District     | 84.3               | 87.3               | 87.2             |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      |                      |                      | 55.6                 | 59.2                 | 58                   | 59.3                        | 62.7                        | 64.400000000000006          | 89                    | 88.8                  | 89                    | 78.900000000000006    | 86.8                  | 85.4                  | 85.1                   | 88.4                   | 88.8                   | 86.8                     | 86                       | 94.2                     | 
| 9        | Bethel School District      | 89.3               | 91.1               | 90.7             | 83.8                   | 76.8                   | 75                     | 82                        | 86                        | 87.2                      | 72.2                 | 75.5                 | 76.7                 | 80.599999999999994   | 85.2                 | 85.5                 | 58.8                 | 62.9                 | 64.099999999999994   | 74.900000000000006          | 79.099999999999994          | 78.599999999999994          | 91.6                  | 93.2                  | 92.3                  | 87.5                  | 89.5                  | 89.1                  | 89.7                   | 91.4                   | 91.6                   | 89.8                     | 90.1                     | 90.4                     | 
| 11       | Bloomfield School District  | 72.099999999999994 | 72.400000000000006 | 75.5             | 71.9                   | 72.3                   | 75.3                   | 72.6                      | 67.1                      | 69.3                      |                      |                      | 52.7                 | 69.599999999999994   | 69                   | 72.900000000000006   | 48.7                 | 43.6                 | 43                   | 67.5                        | 66.400000000000006          | 70.7                        | 76.099999999999994    | 75.5                  | 76.8                  | 65                    | 65.3                  | 72.7                  | 78.599999999999994     | 80.599999999999994     | 82.1                   | 64.2                     | 64.400000000000006       | 63.1                     | 
| 12       | Bolton School District      | 88.6               | 86.5               | 88.6             | 73.6                   |                        |                        |                           |                           |                           |                      |                      |                      | 66.7                 | 58.9                 | 72.2                 | 49.1                 | 43.5                 | 41.2                 | 59                          | 54.6                        | 61.2                        | 90.8                  | 88.8                  | 89.6                  | 85.6                  | 84.9                  | 87.1                  | 90.6                   | 87.8                   | 90.9                   | 92.1                     | 85.1                     | 90.6                     | 
```