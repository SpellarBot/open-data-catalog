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
| Rows Updated | 2014-03-21T17:00:28Z |

## Description

This dataset contains the Connecticut Academic Performance Test (CAPT) district performance indices (DPIs) and DPI target attainment status for 2012-13. These data were published in the District Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)

Note: Target attainment status will say ?n/a? if there is no 2012-13 DPI target or if there is no 2012-13 DPI, which happens when there are small N sizes for a particular subgroup or subject.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
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
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bj6v-3hfz d:2014-03-21T10:00:13.000Z t:dpi_read_status=No t:dpi_science_status=Yes t:black_dpi_overall_status=Yes t:high_needs_dpi_overall_status=Yes t:district_name="Ansonia School District" t:swd_dpi_overall_status=n/a t:dpi_overall_status=No t:dpi_write_status=Yes t:hispanic_dpi_overall_status=Yes t:dpi_math_target_status=No t:district=2 t:frl_dpi_overall_status=Yes m:dpi_write_2013=69.2 m:hispanic_dpi_overall_2013=61 m:dpi_read_2013=55.9 m:dpi_science_2013=63.1 m:frl_dpi_overall_2013=55.5 m:black_dpi_overall_2013=52.3 m:high_needs_dpi_overall_2013=52.6 m:dpi_overall_2013=57.8 m:dpi_math_2013=52.4

series e:bj6v-3hfz d:2014-03-21T10:00:13.000Z t:dpi_read_status=Yes t:dpi_science_status=Yes t:high_needs_dpi_overall_status=Yes t:district_name="Avon School District" t:swd_dpi_overall_status=No t:dpi_overall_status=Yes t:dpi_write_status=Yes t:dpi_math_target_status=Yes t:district=4 m:dpi_write_2013=94.8 m:swd_dpi_overall_2013=61.4 m:dpi_read_2013=88.6 m:dpi_science_2013=92.3 m:high_needs_dpi_overall_2013=70.9 m:dpi_overall_2013=91.7 m:dpi_math_2013=92.5

series e:bj6v-3hfz d:2014-03-21T10:00:13.000Z t:dpi_read_status=No t:dpi_science_status=Yes t:high_needs_dpi_overall_status=No t:district_name="Berlin School District" t:swd_dpi_overall_status=No t:dpi_overall_status=No t:dpi_write_status=Yes t:hispanic_dpi_overall_status=n/a t:dpi_math_target_status=No t:district=7 t:frl_dpi_overall_status=No m:dpi_write_2013=92.7 m:hispanic_dpi_overall_2013=61.7 m:swd_dpi_overall_2013=55.4 m:dpi_read_2013=83.9 m:dpi_science_2013=86.3 m:frl_dpi_overall_2013=60.9 m:high_needs_dpi_overall_2013=62.2 m:dpi_overall_2013=85.4 m:dpi_math_2013=83
```

## Meta Commands

```ls
metric m:dpi_overall_2013 l:"DPI OVERALL 2013" t:dataTypeName=number

metric m:black_dpi_overall_2013 l:"Black DPI OVERALL 2013" t:dataTypeName=number

metric m:hispanic_dpi_overall_2013 l:"Hispanic DPI OVERALL 2013" t:dataTypeName=number

metric m:ell_dpi_overall_2013 l:"ELL DPI OVERALL 2013" t:dataTypeName=number

metric m:frl_dpi_overall_2013 l:"FRL DPI OVERALL 2013" t:dataTypeName=number

metric m:swd_dpi_overall_2013 l:"SWD DPI OVERALL 2013" t:dataTypeName=number

metric m:high_needs_dpi_overall_2013 l:"High Needs DPI OVERALL 2013" t:dataTypeName=number

metric m:dpi_math_2013 l:"DPI MATH 2013" t:dataTypeName=number

metric m:dpi_read_2013 l:"DPI READ 2013" t:dataTypeName=number

metric m:dpi_write_2013 l:"DPI WRITE 2013" t:dataTypeName=number

metric m:dpi_science_2013 l:"DPI SCIENCE 2013" t:dataTypeName=number

entity e:bj6v-3hfz l:"CAPT District Performance: 2013" t:attribution="State Department of Education" t:url=https://data.ct.gov/api/views/bj6v-3hfz

property e:bj6v-3hfz t:meta.view v:id=bj6v-3hfz v:category=Education v:averageRating=0 v:name="CAPT District Performance: 2013" v:attribution="State Department of Education"

property e:bj6v-3hfz t:meta.view.license v:name="Public Domain"

property e:bj6v-3hfz t:meta.view.owner v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"

property e:bj6v-3hfz t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"
```