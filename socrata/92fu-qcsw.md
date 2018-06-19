# CAPT School Performance: 2010-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capt-school-performance-2010-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/92fu-qcsw) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/92fu-qcsw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/92fu-qcsw/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 92fu-qcsw |
| Name | CAPT School Performance: 2010-2012 |
| Attribution | State Department of Education |
| Category | Education |
| Tags | education, school, capt, school performance |
| Created | 2014-04-01T13:05:53Z |
| Publication Date | 2014-04-01T13:08:38Z |

## Description

This dataset contains the school performance indices (SPIs) for 2009-10 (2010), 2010-11 (2011), and 2011-12 (2012) for all schools that administered the Connecticut Academic Performance Test (CAPT). These data were published in the School Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)

Note: Cells are left blank if there is no SPI, which happens when there are small N sizes for a particular subgroup or subject.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | facility_code               | Facility Code               | text      | text        |
| Yes      | series tag     | district_name               | District Name               | text      | text        |
| Yes      | series tag     | school_name                 | School Name                 | text      | text        |
| Yes      | numeric metric | overall_spi_overall_2010    | Overall SPI OVERALL 2010    | number    | number      |
| Yes      | numeric metric | overall_spi_overall_2011    | Overall SPI OVERALL 2011    | number    | number      |
| Yes      | numeric metric | overall_spi_overall_2012    | Overall SPI OVERALL 2012    | number    | number      |
| Yes      | numeric metric | black_spi_overall_2010      | Black SPI OVERALL 2010      | number    | number      |
| Yes      | numeric metric | black_spi_overall_2011      | Black SPI OVERALL 2011      | number    | number      |
| Yes      | numeric metric | black_spi_overall_2012      | Black SPI OVERALL 2012      | number    | number      |
| Yes      | numeric metric | hispanic_spi_overall_2010   | Hispanic SPI OVERALL 2010   | number    | number      |
| Yes      | numeric metric | hispanic_spi_overall_2011   | Hispanic SPI OVERALL 2011   | number    | number      |
| Yes      | numeric metric | hispanic_spi_overall_2012   | Hispanic SPI OVERALL 2012   | number    | number      |
| Yes      | numeric metric | ell_spi_overall_2010        | ELL SPI OVERALL 2010        | number    | number      |
| Yes      | numeric metric | ell_spi_overall_2011        | ELL SPI OVERALL 2011        | number    | number      |
| Yes      | numeric metric | ell_spi_overall_2012        | ELL SPI OVERALL 2012        | number    | number      |
| Yes      | numeric metric | frl_spi_overall_2010        | FRL SPI OVERALL 2010        | number    | number      |
| Yes      | numeric metric | frl_spi_overall_2011        | FRL SPI OVERALL 2011        | number    | number      |
| Yes      | numeric metric | frl_spi_overall_2012        | FRL SPI OVERALL 2012        | number    | number      |
| Yes      | numeric metric | swd_spi_overall_2010        | SWD SPI OVERALL 2010        | number    | number      |
| Yes      | numeric metric | swd_spi_overall_2011        | SWD SPI OVERALL 2011        | number    | number      |
| Yes      | numeric metric | swd_spi_overall_2012        | SWD SPI OVERALL 2012        | number    | number      |
| Yes      | numeric metric | high_needs_spi_overall_2010 | High Needs SPI OVERALL 2010 | number    | number      |
| Yes      | numeric metric | high_needs_spi_overall_2011 | High Needs SPI OVERALL 2011 | number    | number      |
| Yes      | numeric metric | high_needs_spi_overall_2012 | High Needs SPI OVERALL 2012 | number    | number      |
| Yes      | numeric metric | overall_spi_math_2010       | Overall SPI MATH 2010       | number    | number      |
| Yes      | numeric metric | overall_spi_math_2011       | Overall SPI MATH 2011       | number    | number      |
| Yes      | numeric metric | overall_spi_math_2012       | Overall SPI MATH 2012       | number    | number      |
| Yes      | numeric metric | overall_spi_read_2010       | Overall SPI READ 2010       | number    | number      |
| Yes      | numeric metric | overall_spi_read_2011       | Overall SPI READ 2011       | number    | number      |
| Yes      | numeric metric | overall_spi_read_2012       | Overall SPI READ 2012       | number    | number      |
| Yes      | numeric metric | overall_spi_write_2010      | Overall SPI WRITE 2010      | number    | number      |
| Yes      | numeric metric | overall_spi_write_2011      | Overall SPI WRITE 2011      | number    | number      |
| Yes      | numeric metric | overall_spi_write_2012      | Overall SPI WRITE 2012      | number    | number      |
| Yes      | numeric metric | overall_spi_science_2010    | Overall SPI SCIENCE 2010    | number    | number      |
| Yes      | numeric metric | overall_spi_science_2011    | Overall SPI SCIENCE 2011    | number    | number      |
| Yes      | numeric metric | overall_spi_science_2012    | Overall SPI SCIENCE 2012    | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:92fu-qcsw d:2010-01-01T00:00:00.000Z t:district_name="Ansonia School District" t:school_name="Ansonia High School" t:facility_code=0026111 m:overall_spi_overall_2010=61.9 m:overall_spi_overall_2011=55.8 m:overall_spi_read_2010=63.9 m:overall_spi_overall_2012=60.1 m:overall_spi_read_2011=54.6 m:overall_spi_read_2012=63.1 m:black_spi_overall_2012=46.6 m:black_spi_overall_2010=39.7 m:black_spi_overall_2011=45.5 m:overall_spi_science_2010=64 m:overall_spi_science_2011=58.2 m:overall_spi_science_2012=60.6 m:overall_spi_math_2010=56.5 m:hispanic_spi_overall_2012=46.5 m:overall_spi_math_2011=50.5 m:overall_spi_math_2012=52.1 m:hispanic_spi_overall_2010=58.2 m:hispanic_spi_overall_2011=49.2 m:frl_spi_overall_2011=48.1 m:frl_spi_overall_2012=52.2 m:frl_spi_overall_2010=52.5 m:high_needs_spi_overall_2010=52.1 m:overall_spi_write_2010=64.6 m:overall_spi_write_2011=65.9 m:high_needs_spi_overall_2012=51.6 m:high_needs_spi_overall_2011=47.4 m:overall_spi_write_2012=71.1

series e:92fu-qcsw d:2010-01-01T00:00:00.000Z t:district_name="Avon School District" t:school_name="Avon High School" t:facility_code=0046111 m:swd_spi_overall_2010=63.7 m:overall_spi_science_2010=90.6 m:swd_spi_overall_2011=66.1 m:overall_spi_science_2011=90.6 m:swd_spi_overall_2012=58.8 m:overall_spi_science_2012=91.3 m:overall_spi_math_2010=91.2 m:overall_spi_math_2011=89.7 m:overall_spi_overall_2010=91.5 m:overall_spi_math_2012=90.9 m:overall_spi_overall_2011=90.9 m:overall_spi_read_2010=90 m:overall_spi_read_2011=89.3 m:overall_spi_overall_2012=91 m:overall_spi_read_2012=87.8 m:high_needs_spi_overall_2010=67.6 m:overall_spi_write_2010=94.5 m:overall_spi_write_2011=95.7 m:high_needs_spi_overall_2012=68.3 m:high_needs_spi_overall_2011=73 m:overall_spi_write_2012=95.2

series e:92fu-qcsw d:2010-01-01T00:00:00.000Z t:district_name="Berlin School District" t:school_name="Berlin High School" t:facility_code=0076111 m:swd_spi_overall_2010=52.8 m:overall_spi_science_2010=83 m:overall_spi_science_2011=84.3 m:swd_spi_overall_2012=59.6 m:overall_spi_science_2012=84.1 m:overall_spi_math_2010=85.2 m:overall_spi_math_2011=86.2 m:overall_spi_overall_2010=84.5 m:overall_spi_math_2012=84 m:overall_spi_overall_2011=86.5 m:overall_spi_read_2010=82.4 m:overall_spi_read_2011=84.3 m:overall_spi_overall_2012=86.9 m:overall_spi_read_2012=86.9 m:frl_spi_overall_2011=62.5 m:frl_spi_overall_2012=64.5 m:high_needs_spi_overall_2010=59.5 m:overall_spi_write_2010=90.8 m:overall_spi_write_2011=93 m:high_needs_spi_overall_2012=65.6 m:high_needs_spi_overall_2011=64.6 m:overall_spi_write_2012=94.7
```

## Meta Commands

```ls
metric m:overall_spi_overall_2010 p:float l:"Overall SPI OVERALL 2010" t:dataTypeName=number

metric m:overall_spi_overall_2011 p:float l:"Overall SPI OVERALL 2011" t:dataTypeName=number

metric m:overall_spi_overall_2012 p:float l:"Overall SPI OVERALL 2012" t:dataTypeName=number

metric m:black_spi_overall_2010 p:float l:"Black SPI OVERALL 2010" t:dataTypeName=number

metric m:black_spi_overall_2011 p:float l:"Black SPI OVERALL 2011" t:dataTypeName=number

metric m:black_spi_overall_2012 p:double l:"Black SPI OVERALL 2012" t:dataTypeName=number

metric m:hispanic_spi_overall_2010 p:float l:"Hispanic SPI OVERALL 2010" t:dataTypeName=number

metric m:hispanic_spi_overall_2011 p:float l:"Hispanic SPI OVERALL 2011" t:dataTypeName=number

metric m:hispanic_spi_overall_2012 p:float l:"Hispanic SPI OVERALL 2012" t:dataTypeName=number

metric m:ell_spi_overall_2010 p:float l:"ELL SPI OVERALL 2010" t:dataTypeName=number

metric m:ell_spi_overall_2011 p:float l:"ELL SPI OVERALL 2011" t:dataTypeName=number

metric m:ell_spi_overall_2012 p:float l:"ELL SPI OVERALL 2012" t:dataTypeName=number

metric m:frl_spi_overall_2010 p:float l:"FRL SPI OVERALL 2010" t:dataTypeName=number

metric m:frl_spi_overall_2011 p:float l:"FRL SPI OVERALL 2011" t:dataTypeName=number

metric m:frl_spi_overall_2012 p:float l:"FRL SPI OVERALL 2012" t:dataTypeName=number

metric m:swd_spi_overall_2010 p:float l:"SWD SPI OVERALL 2010" t:dataTypeName=number

metric m:swd_spi_overall_2011 p:float l:"SWD SPI OVERALL 2011" t:dataTypeName=number

metric m:swd_spi_overall_2012 p:float l:"SWD SPI OVERALL 2012" t:dataTypeName=number

metric m:high_needs_spi_overall_2010 p:float l:"High Needs SPI OVERALL 2010" t:dataTypeName=number

metric m:high_needs_spi_overall_2011 p:float l:"High Needs SPI OVERALL 2011" t:dataTypeName=number

metric m:high_needs_spi_overall_2012 p:float l:"High Needs SPI OVERALL 2012" t:dataTypeName=number

metric m:overall_spi_math_2010 p:float l:"Overall SPI MATH 2010" t:dataTypeName=number

metric m:overall_spi_math_2011 p:float l:"Overall SPI MATH 2011" t:dataTypeName=number

metric m:overall_spi_math_2012 p:float l:"Overall SPI MATH 2012" t:dataTypeName=number

metric m:overall_spi_read_2010 p:float l:"Overall SPI READ 2010" t:dataTypeName=number

metric m:overall_spi_read_2011 p:float l:"Overall SPI READ 2011" t:dataTypeName=number

metric m:overall_spi_read_2012 p:float l:"Overall SPI READ 2012" t:dataTypeName=number

metric m:overall_spi_write_2010 p:float l:"Overall SPI WRITE 2010" t:dataTypeName=number

metric m:overall_spi_write_2011 p:float l:"Overall SPI WRITE 2011" t:dataTypeName=number

metric m:overall_spi_write_2012 p:float l:"Overall SPI WRITE 2012" t:dataTypeName=number

metric m:overall_spi_science_2010 p:float l:"Overall SPI SCIENCE 2010" t:dataTypeName=number

metric m:overall_spi_science_2011 p:float l:"Overall SPI SCIENCE 2011" t:dataTypeName=number

metric m:overall_spi_science_2012 p:float l:"Overall SPI SCIENCE 2012" t:dataTypeName=number

entity e:92fu-qcsw l:"CAPT School Performance: 2010-2012" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/92fu-qcsw

property e:92fu-qcsw t:meta.view v:id=92fu-qcsw v:category=Education v:averageRating=0 v:name="CAPT School Performance: 2010-2012" v:attribution="State Department of Education"

property e:92fu-qcsw t:meta.view.license v:name="Public Domain"

property e:92fu-qcsw t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:displayName="Stephanie O'Day"

property e:92fu-qcsw t:meta.view.tableauthor v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"
```

## Top Records

```ls
| facility_code | district_name              | school_name            | overall_spi_overall_2010 | overall_spi_overall_2011 | overall_spi_overall_2012 | black_spi_overall_2010 | black_spi_overall_2011 | black_spi_overall_2012 | hispanic_spi_overall_2010 | hispanic_spi_overall_2011 | hispanic_spi_overall_2012 | ell_spi_overall_2010 | ell_spi_overall_2011 | ell_spi_overall_2012 | frl_spi_overall_2010 | frl_spi_overall_2011 | frl_spi_overall_2012 | swd_spi_overall_2010 | swd_spi_overall_2011 | swd_spi_overall_2012 | high_needs_spi_overall_2010 | high_needs_spi_overall_2011 | high_needs_spi_overall_2012 | overall_spi_math_2010 | overall_spi_math_2011 | overall_spi_math_2012 | overall_spi_read_2010 | overall_spi_read_2011 | overall_spi_read_2012 | overall_spi_write_2010 | overall_spi_write_2011 | overall_spi_write_2012 | overall_spi_science_2010 | overall_spi_science_2011 | overall_spi_science_2012 | 
| ============= | ========================== | ====================== | ======================== | ======================== | ======================== | ====================== | ====================== | ====================== | ========================= | ========================= | ========================= | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | ==================== | =========================== | =========================== | =========================== | ===================== | ===================== | ===================== | ===================== | ===================== | ===================== | ====================== | ====================== | ====================== | ======================== | ======================== | ======================== | 
| 0026111       | Ansonia School District    | Ansonia High School    | 61.9                     | 55.8                     | 60.1                     | 39.7                   | 45.5                   | 46.6                   | 58.2                      | 49.2                      | 46.5                      |                      |                      |                      | 52.5                 | 48.1                 | 52.2                 |                      |                      |                      | 52.1                        | 47.4                        | 51.6                        | 56.5                  | 50.5                  | 52.1                  | 63.9                  | 54.6                  | 63.1                  | 64.599999999999994     | 65.900000000000006     | 71.099999999999994     | 64                       | 58.2                     | 60.6                     | 
| 0046111       | Avon School District       | Avon High School       | 91.5                     | 90.9                     | 91                       |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      |                      |                      | 63.7                 | 66.1                 | 58.8                 | 67.599999999999994          | 73                          | 68.3                        | 91.2                  | 89.7                  | 90.9                  | 90                    | 89.3                  | 87.8                  | 94.5                   | 95.7                   | 95.2                   | 90.6                     | 90.6                     | 91.3                     | 
| 0076111       | Berlin School District     | Berlin High School     | 84.5                     | 86.5                     | 86.9                     |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      | 62.5                 | 64.5                 | 52.8                 |                      | 59.6                 | 59.5                        | 64.599999999999994          | 65.599999999999994          | 85.2                  | 86.2                  | 84                    | 82.4                  | 84.3                  | 86.9                  | 90.8                   | 93                     | 94.7                   | 83                       | 84.3                     | 84.1                     | 
| 0096111       | Bethel School District     | Bethel High School     | 84.9                     | 84.6                     | 84.1                     |                        |                        |                        | 77.1                      | 75.1                      | 76.1                      |                      |                      |                      | 72.400000000000006   | 68.5                 | 68.3                 | 52.4                 | 46.9                 | 58.6                 | 65.099999999999994          | 62.6                        | 65.7                        | 81.3                  | 83.3                  | 82.3                  | 84.6                  | 82.9                  | 84.4                  | 93.2                   | 91.4                   | 91.9                   | 82                       | 82.4                     | 78.599999999999994       | 
| 0116111       | Bloomfield School District | Bloomfield High School | 56.2                     | 59.2                     | 62.9                     | 55.1                   | 59.5                   | 63.1                   |                           |                           |                           |                      |                      |                      | 52.2                 | 53.8                 | 57.2                 | 39.700000000000003   |                      |                      | 51                          | 53.6                        | 57.5                        | 43.5                  | 46.3                  | 51.1                  | 53.8                  | 58                    | 63.8                  | 74.5                   | 77.900000000000006     | 79.900000000000006     | 58.8                     | 60                       | 65.7                     | 
| 0126111       | Bolton School District     | Bolton High School     | 88.2                     | 82.2                     | 87.8                     |                        |                        |                        |                           |                           |                           |                      |                      |                      |                      |                      |                      |                      |                      |                      |                             | 55                          |                             | 83.1                  | 77.900000000000006    | 85.7                  | 90.8                  | 83                    | 85.8                  | 90.9                   | 91                     | 93.7                   | 87.9                     | 84.7                     | 86.4                     | 
| 0146111       | Branford School District   | Branford High School   | 85.1                     | 80.900000000000006       | 80.900000000000006       |                        |                        |                        |                           |                           | 77.1                      |                      |                      |                      | 77.099999999999994   | 70.400000000000006   | 79.7                 | 58.4                 | 50.3                 | 56.5                 | 69.900000000000006          | 62.2                        | 69.099999999999994          | 80.900000000000006    | 77.400000000000006    | 74.5                  | 85.1                  | 77.3                  | 80.8                  | 92.1                   | 90.6                   | 89.1                   | 85.7                     | 81.599999999999994       | 80.900000000000006       | 
| 0156111       | Bridgeport School District | Bassick High School    | 20.8                     | 32.5                     | 34.1                     | 20.8                   | 33.1                   | 32.2                   | 19.5                      | 32.5                      | 32.9                      | 11                   | 17.1                 | 23.2                 | 20.7                 | 32.5                 | 34.1                 | 7.9                  |                      | 14.1                 | 20.8                        | 32.5                        | 34.1                        | 16.899999999999999    | 28.9                  | 26.5                  | 21.2                  | 28.5                  | 34.299999999999997    | 32.9                   | 45.7                   | 48.7                   | 20.8                     | 29.8                     | 31.4                     | 
| 0156211       | Bridgeport School District | Central High School    | 48.5                     | 52.8                     | 48.4                     | 43.8                   | 48                     | 47.9                   | 49.5                      | 51.3                      | 46                        | 24.4                 | 36.2                 | 25.9                 | 47.5                 | 52.8                 | 48.4                 | 14.3                 | 14.1                 | 15.2                 | 47.4                        | 52.8                        | 48.2                        | 42.6                  | 46.2                  | 42.2                  | 49.4                  | 54                    | 47.6                  | 57.4                   | 61.5                   | 61.5                   | 46.3                     | 51.8                     | 47.1                     | 
| 0156311       | Bridgeport School District | Harding High School    | 30.9                     | 28.9                     | 36.5                     | 33.2                   | 31.3                   | 38.5                   | 29.1                      | 26.2                      | 32.9                      | 24.5                 | 18                   | 19.9                 | 30.8                 | 28.9                 | 36.299999999999997   | 12.7                 | 8.9                  | 6.8                  | 30.8                        | 28.9                        | 36.299999999999997          | 24.5                  | 25.2                  | 29.9                  | 35                    | 32.5                  | 36.299999999999997    | 43.3                   | 47.6                   | 53.5                   | 28                       | 23.2                     | 30.2                     | 
```