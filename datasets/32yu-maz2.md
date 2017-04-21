# New York City Health and Hospitals Corporation (HHC): HHC Options (family level)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-health-and-hospitals-corporation-hhc-hhc-options-family-level-34769) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/32yu-maz2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/32yu-maz2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/32yu-maz2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 32yu-maz2 |
| Name | New York City Health and Hospitals Corporation (HHC): HHC Options (family level) |
| Attribution | Health and Hospitals Corporation (HHC) |
| Category | Health |
| Tags | health, patient, healthcare, healthcare provider, hospital, income, family affordable healthcare, healthy living |
| Created | 2011-09-30T18:24:31Z |
| Publication Date | 2011-10-11T19:27:27Z |

## Description

Through HHC Options, low and moderate-income HHC patients can get affordable healthcare.  If a patient is not eligible for public insurance, we reduce the patient's fee to an affordable amount, based on family size and income. This data shows the minimum and maximum income at each level.
Update Frequency: As needed

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| No       | time           | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | numeric metric | family_size                   | Family Size                   | number    | number      |
| Yes      | numeric metric | income_more_than              | Income more than              | number    | number      |
| Yes      | numeric metric | income_less_than              | Income Less Than              | number    | number      |
| Yes      | numeric metric | hhc_options_reduced_fee_level | HHC Options Reduced Fee Level | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:32yu-maz2 d:2011-09-30T11:24:32.000Z m:family_size=1 m:income_more_than=0 m:hhc_options_reduced_fee_level=1 m:income_less_than=16335

series e:32yu-maz2 d:2011-09-30T11:24:32.000Z m:family_size=2 m:income_more_than=0 m:hhc_options_reduced_fee_level=1 m:income_less_than=22065

series e:32yu-maz2 d:2011-09-30T11:24:32.000Z m:family_size=3 m:income_more_than=0 m:hhc_options_reduced_fee_level=1 m:income_less_than=27795
```

## Meta Commands

```ls
metric m:family_size p:integer l:"Family Size" t:dataTypeName=number

metric m:income_more_than p:integer l:"Income more than" t:dataTypeName=number

metric m:income_less_than p:integer l:"Income Less Than" t:dataTypeName=number

metric m:hhc_options_reduced_fee_level p:integer l:"HHC Options Reduced Fee Level" t:dataTypeName=number

entity e:32yu-maz2 l:"New York City Health and Hospitals Corporation (HHC): HHC Options (family level)" t:attribution="Health and Hospitals Corporation (HHC)" t:url=https://data.cityofnewyork.us/api/views/32yu-maz2

property e:32yu-maz2 t:meta.view v:id=32yu-maz2 v:category=Health v:averageRating=0 v:name="New York City Health and Hospitals Corporation (HHC): HHC Options (family level)" v:attribution="Health and Hospitals Corporation (HHC)"

property e:32yu-maz2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:32yu-maz2 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | family_size | income_more_than | income_less_than | hhc_options_reduced_fee_level | 
| =========== | =========== | ================ | ================ | ============================= | 
| 1317381872  | 1           | 0                | 16335            | 1                             | 
| 1317381872  | 2           | 0                | 22065            | 1                             | 
| 1317381872  | 3           | 0                | 27795            | 1                             | 
| 1317381872  | 4           | 0                | 33525            | 1                             | 
| 1317381872  | 5           | 0                | 39255            | 1                             | 
| 1317381872  | 6           | 0                | 44985            | 1                             | 
| 1317381872  | 7           | 0                | 50715            | 1                             | 
| 1317381872  | 1           | 16336            | 21780            | 2                             | 
| 1317381872  | 2           | 22066            | 29420            | 2                             | 
| 1317381872  | 3           | 27796            | 37060            | 2                             | 
```