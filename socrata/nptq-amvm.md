# Upper Columbia -- 1062015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/upper-columbia-1062015) |
| Metadata | [Link](https://data.wa.gov/api/views/nptq-amvm) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/nptq-amvm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/nptq-amvm/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | nptq-amvm |
| Name | Upper Columbia -- 1062015 |
| Created | 2014-12-31T18:45:01Z |
| Publication Date | 2015-01-06T16:18:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name        | Name               | Data Type | Render Type |
| ======== | ============== | ================= | ================== | ========= | =========== |
| No       | time           | :updated_at       | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | watershed         | Watershed          | text      | text        |
| Yes      | series tag     | indicator         | Indicator          | text      | text        |
| Yes      | numeric metric | estimated_mean    | Estimated Mean     | number    | number      |
| Yes      | numeric metric | 90_ci_lower_bound | 90% CI lower bound | number    | number      |
| Yes      | numeric metric | 90_ci_upper_bound | 90% CI upper bound | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nptq-amvm d:2015-01-06T08:17:44.000Z t:watershed="Methow Watershed" t:indicator="Canopy Cover (%)" m:estimated_mean=36.84 m:90_ci_lower_bound=33.58 m:90_ci_upper_bound=40.09

series e:nptq-amvm d:2015-01-06T08:17:44.000Z t:watershed="Methow Watershed" t:indicator="Large Woody Debris (m3/100m)" m:estimated_mean=17.24 m:90_ci_lower_bound=4.46 m:90_ci_upper_bound=30.03

series e:nptq-amvm d:2015-01-06T08:17:44.000Z t:watershed="Methow Watershed" t:indicator="Residual Pool Depth (cm)" m:estimated_mean=71 m:90_ci_lower_bound=55 m:90_ci_upper_bound=87
```

## Meta Commands

```ls
metric m:estimated_mean p:float l:"Estimated Mean" t:dataTypeName=number

metric m:90_ci_lower_bound p:float l:"90% CI lower bound" t:dataTypeName=number

metric m:90_ci_upper_bound p:float l:"90% CI upper bound" t:dataTypeName=number

entity e:nptq-amvm l:"Upper Columbia -- 1062015" t:url=https://data.wa.gov/api/views/nptq-amvm

property e:nptq-amvm t:meta.view v:id=nptq-amvm v:averageRating=0 v:name="Upper Columbia -- 1062015"

property e:nptq-amvm t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:nptq-amvm t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | watershed           | indicator                             | estimated_mean | 90_ci_lower_bound | 90_ci_upper_bound | 
| =========== | =================== | ===================================== | ============== | ================= | ================= | 
| 1420532264  | Methow Watershed    | Canopy Cover (%)                      | 36.84          | 33.58             | 40.09             | 
| 1420532264  | Methow Watershed    | Large Woody Debris (m3/100m)          | 17.24          | 4.46              | 30.03             | 
| 1420532264  | Methow Watershed    | Residual Pool Depth (cm)              | 71.00          | 55.00             | 87.00             | 
| 1420532264  | Methow Watershed    | Standard Deviation Thalweg Depth (cm) | 42.00          | 32.00             | 53.00             | 
| 1420532264  | Methow Watershed    | Percent Fines (%)                     | 18.68          | 14.08             | 23.29             | 
| 1420532264  | Wenatchee Watershed | Canopy Cover (%)                      | 63.63          | 55.97             | 71.28             | 
| 1420532264  | Wenatchee Watershed | Large Woody Debris (m3/100m)          | 8.59           | -0.85             | 18.03             | 
| 1420532264  | Wenatchee Watershed | Residual Pool Depth (cm)              | 49.00          | 35.00             | 63.00             | 
| 1420532264  | Wenatchee Watershed | Standard Deviation Thalweg Depth (cm) | 59.00          | 48.00             | 70.00             | 
| 1420532264  | Wenatchee Watershed | Percent Fines (%)                     | 33.61          | 19.67             | 47.55             | 
```