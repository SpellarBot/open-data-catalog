# Medicare Beneficiary Enrollment and Demographics, Washington State and Counties, 2007-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medicare-beneficiary-enrollment-and-demographics-washington-state-and-counties-2007-2014-76612) |
| Metadata | [Link](https://data.wa.gov/api/views/9bjy-hi93) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9bjy-hi93/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9bjy-hi93/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9bjy-hi93 |
| Name | Medicare Beneficiary Enrollment and Demographics, Washington State and Counties, 2007-2014 |
| Attribution | Wei Yen, Washington State Office of Financial Management |
| Category | Health |
| Tags | medicare enrollment, medicare beneficiary demographics |
| Created | 2016-05-12T22:33:18Z |
| Publication Date | 2016-05-12T22:39:53Z |

## Description

(Source: CMS Medicare Geographic Variation Public Use File, December 2015)

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | county                               | County                               | text      | text        |
| Yes      | numeric metric | to_sort_by_county_and_year           | (To sort by county and year)         | number    | text        |
| Yes      | numeric metric | to_sort_by_year_and_county           | (To sort by year and county)         | number    | text        |
| Yes      | time           | year                                 | Year                                 | number    | text        |
| Yes      | series tag     | state_and_county_fips_code           | State and County FIPS Code           | text      | text        |
| Yes      | numeric metric | beneficiaries_with_part_a_and_part_b | Beneficiaries with Part A and Part B | number    | number      |
| Yes      | numeric metric | ffs_beneficiaries                    | FFS Beneficiaries                    | number    | number      |
| Yes      | numeric metric | ma_beneficiaries                     | MA Beneficiaries                     | number    | number      |
| Yes      | numeric metric | ma_participation_rate                | MA Participation Rate (%)            | number    | number      |
| Yes      | numeric metric | average_age                          | Average Age                          | number    | number      |
| Yes      | numeric metric | percent_female                       | Percent Female                       | number    | number      |
| Yes      | numeric metric | percent_male                         | Percent Male                         | number    | number      |
| Yes      | numeric metric | percent_non_hispanic_white           | Percent Non-Hispanic White           | number    | number      |
| Yes      | numeric metric | percent_african_american             | Percent African American             | number    | number      |
| Yes      | numeric metric | percent_hispanic                     | Percent Hispanic                     | number    | number      |
| Yes      | numeric metric | percent_other_unknown                | Percent Other/Unknown                | number    | number      |
| Yes      | numeric metric | percent_eligible_for_medicaid        | Percent Eligible for Medicaid        | number    | number      |
| Yes      | numeric metric | average_hcc_score                    | Average HCC Score                    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9bjy-hi93 d:2007-01-01T00:00:00.000Z t:state_and_county_fips_code=. t:county="STATE TOTAL" m:average_age=72 m:ma_participation_rate=21.8 m:to_sort_by_county_and_year=0.2007 m:beneficiaries_with_part_a_and_part_b=844532 m:percent_female=54.3 m:percent_eligible_for_medicaid=18.3 m:percent_non_hispanic_white=89.4 m:percent_male=45.7 m:ma_beneficiaries=184279 m:ffs_beneficiaries=660253 m:percent_hispanic=2.5 m:average_hcc_score=0.91 m:to_sort_by_year_and_county=2007 m:percent_other_unknown=5.6 m:percent_african_american=2.4

series e:9bjy-hi93 d:2007-01-01T00:00:00.000Z t:state_and_county_fips_code=53001 t:county=ADAMS m:average_age=72 m:ma_participation_rate=8.9 m:percent_male=46.7 m:ma_beneficiaries=143 m:ffs_beneficiaries=1464 m:to_sort_by_county_and_year=530012007 m:average_hcc_score=0.86 m:beneficiaries_with_part_a_and_part_b=1607 m:to_sort_by_year_and_county=200753001 m:percent_female=53.4 m:percent_eligible_for_medicaid=17.6

series e:9bjy-hi93 d:2007-01-01T00:00:00.000Z t:state_and_county_fips_code=53003 t:county=ASOTIN m:average_age=72 m:ma_participation_rate=11.5 m:to_sort_by_county_and_year=530032007 m:beneficiaries_with_part_a_and_part_b=4700 m:percent_female=53.7 m:percent_eligible_for_medicaid=18.7 m:percent_non_hispanic_white=97.3 m:percent_male=46.3 m:ma_beneficiaries=538 m:ffs_beneficiaries=4162 m:percent_hispanic=1 m:average_hcc_score=0.93 m:to_sort_by_year_and_county=200753003 m:percent_other_unknown=1.3 m:percent_african_american=0.3
```

## Meta Commands

```ls
metric m:to_sort_by_county_and_year p:integer l:"(To sort by county and year)" t:dataTypeName=number

metric m:to_sort_by_year_and_county p:integer l:"(To sort by year and county)" t:dataTypeName=number

metric m:beneficiaries_with_part_a_and_part_b p:integer l:"Beneficiaries with Part A and Part B" t:dataTypeName=number

metric m:ffs_beneficiaries p:integer l:"FFS Beneficiaries" t:dataTypeName=number

metric m:ma_beneficiaries p:integer l:"MA Beneficiaries" t:dataTypeName=number

metric m:ma_participation_rate p:float l:"MA Participation Rate (%)" t:dataTypeName=number

metric m:average_age p:float l:"Average Age" t:dataTypeName=number

metric m:percent_female p:float l:"Percent Female" t:dataTypeName=number

metric m:percent_male p:float l:"Percent Male" t:dataTypeName=number

metric m:percent_non_hispanic_white p:float l:"Percent Non-Hispanic White" t:dataTypeName=number

metric m:percent_african_american p:float l:"Percent African American" t:dataTypeName=number

metric m:percent_hispanic p:float l:"Percent Hispanic" t:dataTypeName=number

metric m:percent_other_unknown p:float l:"Percent Other/Unknown" t:dataTypeName=number

metric m:percent_eligible_for_medicaid p:float l:"Percent Eligible for Medicaid" t:dataTypeName=number

metric m:average_hcc_score p:float l:"Average HCC Score" t:dataTypeName=number

entity e:9bjy-hi93 l:"Medicare Beneficiary Enrollment and Demographics, Washington State and Counties, 2007-2014" t:attribution="Wei Yen, Washington State Office of Financial Management" t:url=https://data.wa.gov/api/views/9bjy-hi93

property e:9bjy-hi93 t:meta.view v:id=9bjy-hi93 v:category=Health v:averageRating=0 v:name="Medicare Beneficiary Enrollment and Demographics, Washington State and Counties, 2007-2014" v:attribution="Wei Yen, Washington State Office of Financial Management"

property e:9bjy-hi93 t:meta.view.license v:name="Public Domain"

property e:9bjy-hi93 t:meta.view.owner v:id=8ghr-nmpd v:screenName="Wei Yen" v:displayName="Wei Yen"

property e:9bjy-hi93 t:meta.view.tableauthor v:id=8ghr-nmpd v:screenName="Wei Yen" v:roleName=publisher v:displayName="Wei Yen"
```

## Top Records

```ls
| county      | to_sort_by_county_and_year | to_sort_by_year_and_county | year | state_and_county_fips_code | beneficiaries_with_part_a_and_part_b | ffs_beneficiaries | ma_beneficiaries | ma_participation_rate | average_age | percent_female | percent_male | percent_non_hispanic_white | percent_african_american | percent_hispanic | percent_other_unknown | percent_eligible_for_medicaid | average_hcc_score | 
| =========== | ========================== | ========================== | ==== | ========================== | ==================================== | ================= | ================ | ===================== | =========== | ============== | ============ | ========================== | ======================== | ================ | ===================== | ============================= | ================= | 
| STATE TOTAL | 0.2007                     | 2007                       | 2007 | .                          | 844532                               | 660253            | 184279           | 21.8                  | 72.0        | 54.3           | 45.7         | 89.4                       | 2.4                      | 2.5              | 5.6                   | 18.3                          | 0.91              | 
| ADAMS       | 530012007                  | 200753001                  | 2007 | 53001                      | 1607                                 | 1464              | 143              | 8.9                   | 72.0        | 53.4           | 46.7         |                            |                          |                  |                       | 17.6                          | 0.86              | 
| ASOTIN      | 530032007                  | 200753003                  | 2007 | 53003                      | 4700                                 | 4162              | 538              | 11.5                  | 72.0        | 53.7           | 46.3         | 97.3                       | 0.3                      | 1.0              | 1.3                   | 18.7                          | 0.93              | 
| BENTON      | 530052007                  | 200753005                  | 2007 | 53005                      | 20800                                | 18391             | 2409             | 11.6                  | 72.0        | 54.6           | 45.4         | 93.1                       | 0.6                      | 3.5              | 2.7                   | 14.6                          | 0.93              | 
| CHELAN      | 530072007                  | 200753007                  | 2007 | 53007                      | 9227                                 | 8086              | 1141             | 12.4                  | 72.0        | 52.2           | 47.9         |                            |                          |                  |                       | 16.2                          | 0.85              | 
| CLALLAM     | 530092007                  | 200753009                  | 2007 | 53009                      | 18551                                | 17407             | 1144             | 6.2                   | 73.0        | 52.9           | 47.1         | 95.4                       | 0.3                      | 0.9              | 3.5                   | 11.0                          | 0.82              | 
| CLARK       | 530112007                  | 200753011                  | 2007 | 53011                      | 48364                                | 25250             | 23114            | 47.8                  | 70.0        | 53.5           | 46.5         | 91.7                       | 1.6                      | 2.0              | 4.6                   | 23.1                          | 0.92              | 
| COLUMBIA    | 530132007                  | 200753013                  | 2007 | 53013                      | 895                                  | 819               | 76               | 8.5                   | 72.0        | 51.2           | 48.8         |                            |                          |                  |                       | 22.0                          | 0.84              | 
| COWLITZ     | 530152007                  | 200753015                  | 2007 | 53015                      | 17040                                | 10361             | 6679             | 39.2                  | 70.0        | 52.2           | 47.8         | 95.7                       | 0.4                      | 1.3              | 2.5                   | 21.4                          | 0.97              | 
| DOUGLAS     | 530172007                  | 200753017                  | 2007 | 53017                      | 7875                                 | 6883              | 992              | 12.6                  | 74.0        | 55.2           | 44.8         | 94.5                       | 0.2                      | 3.8              | 1.6                   | 16.7                          | 0.94              | 
```