# Mill Rates for FY 2014 through FY 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mill-rates-for-fy-2014-and-fy-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/ds7v-z32c) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ds7v-z32c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ds7v-z32c/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ds7v-z32c |
| Name | Mill Rates for FY 2014 through FY 2016 |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | opm, mill rate, grand list |
| Created | 2014-10-01T18:21:23Z |
| Publication Date | 2015-09-01T15:15:05Z |

## Description

A mill is equal to $1.00 of tax for each $1,000 of assessment. To calculate the property tax, multiply the assessment of the property by the mill rate and divide by 1,000. For example, a property with a assessed value of $50,000 located in a municipality with a mill rate of 20 mills would have a property tax bill of $1,000 per year.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | town_code             | Town Code             | text      | number      |
| Yes      | series tag     | service_district_code | Service District Code | text      | number      |
| Yes      | series tag     | municipality          | Municipality          | text      | text        |
| Yes      | numeric metric | millrate              | Millrate              | number    | number      |
| Yes      | time           | grand_list_year       | Grand List Year       | number    | text        |
| No       |                | fiscal_year           | Fiscal Year           | number    | text        |
```

## Time Field

```ls
Value = grand_list_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:ds7v-z32c d:2013-01-01T00:00:00.000Z t:town_code=1 t:municipality=Andover t:service_district_code=0 m:millrate=30.72

series e:ds7v-z32c d:2013-01-01T00:00:00.000Z t:town_code=2 t:municipality=Ansonia t:service_district_code=0 m:millrate=38.61

series e:ds7v-z32c d:2013-01-01T00:00:00.000Z t:town_code=3 t:municipality=Ashford t:service_district_code=0 m:millrate=32.16
```

## Meta Commands

```ls
metric m:millrate p:float l:Millrate t:dataTypeName=number

entity e:ds7v-z32c l:"Mill Rates for FY 2014  through FY 2016" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/ds7v-z32c

property e:ds7v-z32c t:meta.view v:id=ds7v-z32c v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?A=2987&Q=385976" v:averageRating=0 v:name="Mill Rates for FY 2014  through FY 2016" v:attribution="Office of Policy and Management"

property e:ds7v-z32c t:meta.view.license v:name="Public Domain"

property e:ds7v-z32c t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:ds7v-z32c t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| town_code | service_district_code | municipality              | millrate | grand_list_year | fiscal_year | 
| ========= | ===================== | ========================= | ======== | =============== | =========== | 
| 1         | 0                     | Andover                   | 30.72    | 2013            | 2015        | 
| 2         | 0                     | Ansonia                   | 38.61    | 2013            | 2015        | 
| 3         | 0                     | Ashford                   | 32.16    | 2013            | 2015        | 
| 4         | 0                     | Avon                      | 28.32    | 2013            | 2015        | 
| 5         | 0                     | Barkhamsted               | 27.37    | 2013            | 2015        | 
| 5         | 1                     | Barkhamsted Fire District | 1.63     | 2013            | 2015        | 
| 6         | 0                     | Beacon Falls              | 32.50    | 2013            | 2015        | 
| 7         | 0                     | Berlin                    | 28.92    | 2013            | 2015        | 
| 7         | 1                     | Berlin - Kensington FD    | 1.10     | 2013            | 2015        | 
| 7         | 2                     | Berlin -Worthington FD    | 2.00     | 2013            | 2015        | 
```