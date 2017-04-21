# Somerville 2011 5-year ACS Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/somerville-2011-5-year-acs-statistics-f2a25) |
| Metadata | [Link](https://data.somervillema.gov/api/views/qa92-wva4) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/qa92-wva4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/qa92-wva4/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | qa92-wva4 |
| Name | Somerville 2011 5-year ACS Statistics |
| Created | 2013-06-28T18:40:30Z |
| Publication Date | 2013-06-28T18:42:59Z |

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================== | ============================ | ========= | =========== |
| Yes      | numeric metric | geo_id2                    | GEO.id2                      | number    | number      |
| Yes      | series tag     | geo_display_label          | GEO.display-label            | text      | text        |
| Yes      | numeric metric | population_over_16         | Population over 16           | number    | number      |
| Yes      | numeric metric | median_hh_income           | Median HH Income             | money     | money       |
| Yes      | numeric metric | mean_hh_income             | Mean HH Income               | money     | money       |
| Yes      | numeric metric | food_stamps_snap_1         | Food Stamps/SNAP             | number    | number      |
| Yes      | numeric metric | food_stamps_snap_2         | % Food Stamps/SNAP           | number    | number      |
| Yes      | numeric metric | below_poverty_line         | % below poverty line         | number    | number      |
| Yes      | numeric metric | high_school_grad_or_higher | % High School Grad or Higher | number    | number      |
| Yes      | numeric metric | bachelors_or_higher        | % Bachelors or Higher        | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qa92-wva4 d:2011-01-01T00:00:00.000Z t:geo_display_label="Census Tract 3501.03" m:geo_id2=25017350103 m:bachelors_or_higher=46 m:high_school_grad_or_higher=90.6 m:population_over_16=1063 m:median_hh_income=66289 m:mean_hh_income=76268 m:food_stamps_snap_2=0 m:food_stamps_snap_1=0 m:below_poverty_line=17

series e:qa92-wva4 d:2011-01-01T00:00:00.000Z t:geo_display_label="Census Tract 3501.04" m:geo_id2=25017350104 m:bachelors_or_higher=31.1 m:high_school_grad_or_higher=78.9 m:population_over_16=5467 m:median_hh_income=43898 m:mean_hh_income=55693 m:food_stamps_snap_2=21 m:food_stamps_snap_1=554 m:below_poverty_line=27.5

series e:qa92-wva4 d:2011-01-01T00:00:00.000Z t:geo_display_label="Census Tract 3502" m:geo_id2=25017350200 m:bachelors_or_higher=41.2 m:high_school_grad_or_higher=90.4 m:population_over_16=5603 m:median_hh_income=66845 m:mean_hh_income=79625 m:food_stamps_snap_2=8 m:food_stamps_snap_1=215 m:below_poverty_line=9.1
```

## Meta Commands

```ls
metric m:geo_id2 p:long l:GEO.id2 t:dataTypeName=number

metric m:population_over_16 p:integer l:"Population over 16" t:dataTypeName=number

metric m:median_hh_income p:double l:"Median HH Income" t:dataTypeName=money

metric m:mean_hh_income p:double l:"Mean HH Income" t:dataTypeName=money

metric m:food_stamps_snap_1 p:integer l:"Food Stamps/SNAP" t:dataTypeName=number

metric m:food_stamps_snap_2 p:double l:"% Food Stamps/SNAP" t:dataTypeName=number

metric m:below_poverty_line p:float l:"% below poverty line" t:dataTypeName=number

metric m:high_school_grad_or_higher p:float l:"% High School Grad or Higher" t:dataTypeName=number

metric m:bachelors_or_higher p:float l:"% Bachelors or Higher" t:dataTypeName=number

entity e:qa92-wva4 l:"Somerville 2011 5-year ACS Statistics" t:url=https://data.somervillema.gov/api/views/qa92-wva4

property e:qa92-wva4 t:meta.view v:id=qa92-wva4 v:averageRating=0 v:name="Somerville 2011 5-year ACS Statistics"

property e:qa92-wva4 t:meta.view.owner v:id=b5yv-5dpg v:screenName="Chris Mathias" v:displayName="Chris Mathias"

property e:qa92-wva4 t:meta.view.tableauthor v:id=b5yv-5dpg v:screenName="Chris Mathias" v:displayName="Chris Mathias"
```

## Top Records

```ls
| geo_id2     | geo_display_label    | population_over_16 | median_hh_income | mean_hh_income | food_stamps_snap_1 | food_stamps_snap_2 | below_poverty_line | high_school_grad_or_higher | bachelors_or_higher | 
| =========== | ==================== | ================== | ================ | ============== | ================== | ================== | ================== | ========================== | =================== | 
| 25017350103 | Census Tract 3501.03 | 1063               | 66289.00         | 76268.00       | 0                  | 0                  | 17                 | 90.6                       | 46                  | 
| 25017350104 | Census Tract 3501.04 | 5467               | 43898.00         | 55693.00       | 554                | 21                 | 27.5               | 78.9                       | 31.1                | 
| 25017350200 | Census Tract 3502    | 5603               | 66845.00         | 79625.00       | 215                | 8                  | 9.1                | 90.4                       | 41.2                | 
| 25017350300 | Census Tract 3503    | 2121               | 72973.00         | 76950.00       | 81                 | 7.4                | 10.2               | 90.4                       | 47.6                | 
| 25017350400 | Census Tract 3504    | 5136               | 78592.00         | 87917.00       | 90                 | 3.7                | 15.1               | 96.7                       | 69.4                | 
| 25017350500 | Census Tract 3505    | 1522               | 84000.00         | 97143.00       | 29                 | 3.9                | 7.3                | 98.9                       | 70                  | 
| 25017350600 | Census Tract 3506    | 5155               | 89063.00         | 98973.00       | 16                 | 1.6                | 18.7               | 97.7                       | 75.8                | 
| 25017350700 | Census Tract 3507    | 5749               | 51319.00         | 60499.00       | 314                | 11.4               | 22                 | 85.3                       | 44.4                | 
| 25017350800 | Census Tract 3508    | 1681               | 70197.00         | 81399.00       | 10                 | 1.1                | 6.2                | 96.9                       | 67.4                | 
| 25017350900 | Census Tract 3509    | 2902               | 88229.00         | 100446.00      | 0                  | 0                  | 6.1                | 99.3                       | 80.2                | 
```