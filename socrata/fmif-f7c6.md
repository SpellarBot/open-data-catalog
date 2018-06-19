# CAPT District Performance: 2010-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capt-district-performance-2010-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/fmif-f7c6) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/fmif-f7c6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/fmif-f7c6/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | fmif-f7c6 |
| Name | CAPT District Performance: 2010-2012 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, school district, capt, school performance |
| Created | 2014-04-01T13:30:33Z |
| Publication Date | 2014-04-01T13:32:37Z |

## Description

This dataset contains the Connecticut Academic Performance Test (CAPT) district performance indices (DPIs) for 2009-10 (2010), 2010-11 (2011), and 2011-12 (2012). These data were published in the District Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)

Note: Cells are left blank if there is no DPI, which happens when there are small N sizes for a particular subgroup or subject.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | district                    | District                    | text      | number      |
| Yes      | series tag     | district_name               | District Name               | text      | text        |
| Yes      | numeric metric | overall_dpi_overall_2010    | Overall DPI OVERALL 2010    | number    | number      |
| Yes      | numeric metric | overall_dpi_overall_2011    | Overall DPI OVERALL 2011    | number    | number      |
| Yes      | numeric metric | overall_dpi_overall_2012    | Overall DPI OVERALL 2012    | number    | number      |
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
series e:fmif-f7c6 d:2010-01-01T00:00:00.000Z t:district_name="Ansonia School District" t:district=2 m:overall_dpi_write_2010=64 m:overall_dpi_write_2012=69 m:overall_dpi_write_2011=65.8 m:black_dpi_overall_2010=39.7 m:black_dpi_overall_2011=45.5 m:black_dpi_overall_2012=44 m:swd_dpi_overall_2012=24.8 m:swd_dpi_overall_2010=34.2 m:overall_dpi_math_2010=55.6 m:overall_dpi_math_2011=50.2 m:overall_dpi_math_2012=50.6 m:hispanic_dpi_overall_2012=46.5 m:hispanic_dpi_overall_2011=49.2 m:hispanic_dpi_overall_2010=57.2 m:high_needs_dpi_overall_2012=49.7 m:high_needs_dpi_overall_2011=47.2 m:high_needs_dpi_overall_2010=51.1 m:overall_dpi_science_2012=59.2 m:overall_dpi_science_2011=58.1 m:overall_dpi_science_2010=63.7 m:overall_dpi_overall_2010=61.2 m:frl_dpi_overall_2010=52.3 m:overall_dpi_overall_2012=58.5 m:frl_dpi_overall_2011=47.9 m:overall_dpi_overall_2011=55.6 m:frl_dpi_overall_2012=50.8 m:overall_dpi_read_2010=63.3 m:overall_dpi_read_2011=54.4 m:overall_dpi_read_2012=61.4

series e:fmif-f7c6 d:2010-01-01T00:00:00.000Z t:district_name="Avon School District" t:district=4 m:overall_dpi_write_2010=94.5 m:overall_dpi_write_2012=94.9 m:overall_dpi_write_2011=94.8 m:high_needs_dpi_overall_2012=66.3 m:high_needs_dpi_overall_2011=69.8 m:high_needs_dpi_overall_2010=66.6 m:overall_dpi_science_2012=91 m:overall_dpi_science_2011=90.2 m:overall_dpi_science_2010=90.6 m:overall_dpi_overall_2010=91.2 m:overall_dpi_overall_2012=90.6 m:swd_dpi_overall_2012=56.6 m:overall_dpi_overall_2011=90.1 m:swd_dpi_overall_2010=62.6 m:swd_dpi_overall_2011=62.1 m:overall_dpi_math_2010=90.9 m:overall_dpi_read_2010=89.7 m:overall_dpi_math_2011=88.9 m:overall_dpi_read_2011=88.3 m:overall_dpi_math_2012=90.4 m:overall_dpi_read_2012=87.5

series e:fmif-f7c6 d:2010-01-01T00:00:00.000Z t:district_name="Berlin School District" t:district=7 m:overall_dpi_write_2010=90.5 m:overall_dpi_write_2012=94.5 m:overall_dpi_write_2011=92.7 m:high_needs_dpi_overall_2012=64.4 m:high_needs_dpi_overall_2011=64.2 m:high_needs_dpi_overall_2010=58.2 m:overall_dpi_science_2012=83.7 m:overall_dpi_science_2011=84.2 m:overall_dpi_science_2010=82.6 m:overall_dpi_overall_2010=84.2 m:overall_dpi_overall_2012=86.5 m:swd_dpi_overall_2012=57.7 m:frl_dpi_overall_2011=62.1 m:overall_dpi_overall_2011=86.3 m:swd_dpi_overall_2010=51.2 m:frl_dpi_overall_2012=64.6 m:overall_dpi_math_2010=84.9 m:overall_dpi_read_2010=82.1 m:overall_dpi_math_2011=86.1 m:overall_dpi_read_2011=84.3 m:overall_dpi_math_2012=83.6 m:overall_dpi_read_2012=86.2
```

## Meta Commands

```ls
metric m:overall_dpi_overall_2010 p:float l:"Overall DPI OVERALL 2010" t:dataTypeName=number

metric m:overall_dpi_overall_2011 p:float l:"Overall DPI OVERALL 2011" t:dataTypeName=number

metric m:overall_dpi_overall_2012 p:float l:"Overall DPI OVERALL 2012" t:dataTypeName=number

metric m:black_dpi_overall_2010 p:float l:"Black DPI OVERALL 2010" t:dataTypeName=number

metric m:black_dpi_overall_2011 p:float l:"Black DPI OVERALL 2011" t:dataTypeName=number

metric m:black_dpi_overall_2012 p:float l:"Black DPI OVERALL 2012" t:dataTypeName=number

metric m:hispanic_dpi_overall_2010 p:float l:"Hispanic DPI OVERALL 2010" t:dataTypeName=number

metric m:hispanic_dpi_overall_2011 p:float l:"Hispanic DPI OVERALL 2011" t:dataTypeName=number

metric m:hispanic_dpi_overall_2012 p:float l:"Hispanic DPI OVERALL 2012" t:dataTypeName=number

metric m:ell_dpi_overall_2010 p:float l:"ELL DPI OVERALL 2010" t:dataTypeName=number

metric m:ell_dpi_overall_2011 p:float l:"ELL DPI OVERALL 2011" t:dataTypeName=number

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

entity e:fmif-f7c6 l:"CAPT District Performance: 2010-2012" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/fmif-f7c6

property e:fmif-f7c6 t:meta.view v:id=fmif-f7c6 v:category=Education v:averageRating=0 v:name="CAPT District Performance: 2010-2012" v:attribution="State Department of Education"

property e:fmif-f7c6 t:meta.view.license v:name="Public Domain"

property e:fmif-f7c6 t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:fmif-f7c6 t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| district | district_name              | overall_dpi_overall_2010 | overall_dpi_overall_2011 | overall_dpi_overall_2012 | black_dpi_overall_2010 | black_dpi_overall_2011 | black_dpi_overall_2012 | hispanic_dpi_overall_2010 | hispanic_dpi_overall_2011 | hispanic_dpi_overall_2012 | ell_dpi_overall_2010 | ell_dpi_overall_2011 | ell_dpi_overall_2012 | frl_dpi_overall_2010 | frl_dpi_overall_2011 | frl_dpi_overall_2012 | swd_dpi_overall_2010 | swd_dpi_overall_2011 | swd_dpi_overall_2012 | high_needs_dpi_overall_2010 | high_needs_dpi_overall_2011 | high_needs_dpi_overall_2012 | overall_dpi_math_2010 | overall_dpi_math_2011 | overall_dpi_math_2012 | overall_dpi_read_2010 | overall_dpi_read_2011 | overall_dpi_read_2012 | overall_dpi_write_2010 | overall_dpi_write_2011 | overall_dpi_write_2012 | overall_dpi_science_2010 | overall_dpi_science_2011 | overall_dpi_science_2012 | 
| ======== | ========================== | ======================== | ======================== | ======================== | ====================== | ====================== | ====================== | ========================= | ========================= | ========================= | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | =========================== | =========================== | =========================== | ===================== | ===================== | ===================== | ===================== | ===================== | ===================== | ====================== | ====================== | ====================== | ======================== | ======================== | ======================== | 
| 2        | Ansonia School District    | 61.2                     | 55.6                     | 58.5                     | 39.7                   | 45.5                   | 44                     | 57.2                      | 49.2                      | 46.5                      |                      |                      |                      | 52.3                 | 47.9                 | 50.8                 | 34.200000000000003   |                      | 24.8                 | 51.1                        | 47.2                        | 49.7                        | 55.6                  | 50.2                  | 50.6                  | 63.3                  | 54.4                  | 61.4                  | 64                     | 65.8                   | 69                     | 63.7                     | 58.1                     | 59.2                     | 
| 4        | Avon School District       | 91.2                     | 90.1                     | 90.6                     |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      |                      |                      | 62.6                 | 62.1                 | 56.6                 | 66.599999999999994          | 69.8                        | 66.3                        | 90.9                  | 88.9                  | 90.4                  | 89.7                  | 88.3                  | 87.5                  | 94.5                   | 94.8                   | 94.9                   | 90.6                     | 90.2                     | 91                       | 
| 7        | Berlin School District     | 84.2                     | 86.3                     | 86.5                     |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      | 62.1                 | 64.599999999999994   | 51.2                 |                      | 57.7                 | 58.2                        | 64.2                        | 64.400000000000006          | 84.9                  | 86.1                  | 83.6                  | 82.1                  | 84.3                  | 86.2                  | 90.5                   | 92.7                   | 94.5                   | 82.6                     | 84.2                     | 83.7                     | 
| 9        | Bethel School District     | 84.4                     | 84.6                     | 83.5                     |                        |                        |                        | 77.1                      | 75.1                      | 76.1                      |                      |                      |                      | 70.2                 | 68.400000000000006   | 68.3                 | 49.9                 | 46.9                 | 56.2                 | 63.2                        | 62.7                        | 64.5                        | 81                    | 83.3                  | 81.599999999999994    | 83.8                  | 82.8                  | 83.9                  | 92.4                   | 91.3                   | 91.4                   | 81.7                     | 82.3                     | 78                       | 
| 11       | Bloomfield School District | 54.6                     | 56.2                     | 63.1                     | 53.8                   | 56                     | 63.6                   |                           |                           |                           |                      |                      |                      | 50.6                 | 52.3                 | 56.9                 | 34.6                 |                      | 31.6                 | 49                          | 51.6                        | 57.2                        | 43                    | 44.2                  | 52.1                  | 52.6                  | 54.9                  | 63.7                  | 71.5                   | 73.2                   | 79.400000000000006     | 56.5                     | 56.4                     | 65.7                     | 
| 12       | Bolton School District     | 88.2                     | 81.2                     | 86.4                     |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      |                      |                      |                      |                      |                      |                             | 52.5                        |                             | 83.1                  | 77                    | 84.7                  | 90.8                  | 82                    | 84.2                  | 90.9                   | 91                     | 91.8                   | 87.9                     | 84.7                     | 85.2                     | 
| 13       | Bozrah School District     | 89.1                     | 80.900000000000006       | 80.2                     |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      |                      |                      |                      |                      |                      |                             |                             |                             | 84.6                  | 82.2                  | 76                    | 89.4                  | 73.900000000000006    | 74.8                  | 90.5                   | 81                     | 84.6                   | 91.8                     | 86.4                     | 85.2                     | 
| 14       | Branford School District   | 83.6                     | 80.8                     | 80                       |                        |                        |                        |                           |                           | 77.1                      |                      |                      |                      | 74.6                 | 70.400000000000006   | 75.400000000000006   | 53.5                 | 50.9                 | 53.8                 | 65.7                        | 62.3                        | 66.900000000000006          | 79.400000000000006    | 77.400000000000006    | 73.7                  | 84.2                  | 77.2                  | 80.2                  | 91                     | 90.5                   | 87.9                   | 84.3                     | 81.7                     | 80.3                     | 
| 15       | Bridgeport School District | 36.700000000000003       | 40.700000000000003       | 40.5                     | 35.7                   | 38                     | 39.7                   | 33.5                      | 38.6                      | 38.2                      | 20.3                 | 22.8                 | 22.9                 | 36                   | 40.700000000000003   | 40.4                 | 11.8                 | 10.6                 | 12                   | 35.9                        | 40.700000000000003          | 40.299999999999997          | 31.3                  | 35.799999999999997    | 34.1                  | 38.9                  | 42                    | 40.200000000000003    | 47.6                   | 52.9                   | 54.3                   | 36.200000000000003       | 38.9                     | 38.299999999999997       | 
| 17       | Bristol School District    | 77.599999999999994       | 73.3                     | 75                       | 69.1                   | 61.3                   | 58.4                   | 62.2                      | 60                        | 61.5                      |                      |                      |                      | 65.8                 | 62.8                 | 62.1                 | 42.5                 | 39.7                 | 41.5                 | 63.6                        | 57.7                        | 59                          | 77.2                  | 73.8                  | 75.900000000000006    | 76                    | 69.400000000000006    | 71.5                  | 81.400000000000006     | 79.5                   | 80.7                   | 78.8                     | 74.2                     | 75.5                     | 
```