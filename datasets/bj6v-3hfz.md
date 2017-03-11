# CAPT District Performance: 2013

## Dataset

* [Dataset URL](https://data.ct.gov/api/views/bj6v-3hfz/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/capt-district-performance-2013)
* [Metadata URL](https://data.ct.gov/api/views/bj6v-3hfz)
* Id = bj6v-3hfz
* Name = CAPT District Performance: 2013
* Attribution = State Department of Education
* Category = Education
* Tags = [education, school district, capt, school performance]
* Created = 2014-03-21T17:00:09Z
* Publication Date = 2014-03-21T17:01:58Z
* Rows Updated = 2014-03-21T17:00:28Z

## Description

This dataset contains the Connecticut Academic Performance Test (CAPT) district performance indices (DPIs) and DPI target attainment status for 2012-13. These data were published in the District Performance Reports released by the CT State Department of Education (CSDE) in December 2013 (see http://www.csde.state.ct.us/public/performancereports/20122013reports.asp)

Note: Target attainment status will say ?n/a? if there is no 2012-13 DPI target or if there is no 2012-13 DPI, which happens when there are small N sizes for a particular subgroup or subject.

## Columns

```ls
| Name                          | Field Name                    | Data Type | Render Type | Schema Type    | Included | 
| ============================= | ============================= | ========= | =========== | ============== | ======== | 
| updated_at                    | :updated_at                   | meta_data | meta_data   | time           | No       | 
| District                      | district                      | text      | number      | series tag     | Yes      | 
| District Name                 | district_name                 | text      | text        | series tag     | Yes      | 
| DPI OVERALL 2013              | dpi_overall_2013              | number    | number      | numeric metric | Yes      | 
| DPI OVERALL Status            | dpi_overall_status            | text      | text        | series tag     | Yes      | 
| Black DPI OVERALL 2013        | black_dpi_overall_2013        | number    | number      | numeric metric | Yes      | 
| Black DPI OVERALL Status      | black_dpi_overall_status      | text      | text        | series tag     | Yes      | 
| Hispanic DPI OVERALL 2013     | hispanic_dpi_overall_2013     | number    | number      | numeric metric | Yes      | 
| Hispanic DPI OVERALL Status   | hispanic_dpi_overall_status   | text      | text        | series tag     | Yes      | 
| ELL DPI OVERALL 2013          | ell_dpi_overall_2013          | number    | number      | numeric metric | Yes      | 
| ELL DPI OVERALL Status        | ell_dpi_overall_status        | text      | text        | series tag     | Yes      | 
| FRL DPI OVERALL 2013          | frl_dpi_overall_2013          | number    | number      | numeric metric | Yes      | 
| FRL DPI OVERALL Status        | frl_dpi_overall_status        | text      | text        | series tag     | Yes      | 
| SWD DPI OVERALL 2013          | swd_dpi_overall_2013          | number    | number      | numeric metric | Yes      | 
| SWD DPI OVERALL Status        | swd_dpi_overall_status        | text      | text        | series tag     | Yes      | 
| High Needs DPI OVERALL 2013   | high_needs_dpi_overall_2013   | number    | number      | numeric metric | Yes      | 
| High Needs DPI OVERALL Status | high_needs_dpi_overall_status | text      | text        | series tag     | Yes      | 
| DPI MATH 2013                 | dpi_math_2013                 | number    | number      | numeric metric | Yes      | 
| DPI MATH Target Status        | dpi_math_target_status        | text      | text        | series tag     | Yes      | 
| DPI READ 2013                 | dpi_read_2013                 | number    | number      | numeric metric | Yes      | 
| DPI READ Status               | dpi_read_status               | text      | text        | series tag     | Yes      | 
| DPI WRITE 2013                | dpi_write_2013                | number    | number      | numeric metric | Yes      | 
| DPI WRITE Status              | dpi_write_status              | text      | text        | series tag     | Yes      | 
| DPI SCIENCE 2013              | dpi_science_2013              | number    | number      | numeric metric | Yes      | 
| DPI SCIENCE Status            | dpi_science_status            | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:bj6v-3hfz t:meta.view d:2017-03-07T16:46:30.829Z v:id=bj6v-3hfz v:category=Education v:averageRating=0 v:name="CAPT District Performance: 2013" v:attribution="State Department of Education"

property e:bj6v-3hfz t:meta.view.license d:2017-03-07T16:46:30.829Z v:name="Public Domain"

property e:bj6v-3hfz t:meta.view.owner d:2017-03-07T16:46:30.829Z v:id=nyku-jy9c v:screenName="Stephanie O'Day" v:roleName=editor v:displayName="Stephanie O'Day"

property e:bj6v-3hfz t:meta.view.tableauthor d:2017-03-07T16:46:30.829Z v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:displayName="Tyler Kleykamp"
```