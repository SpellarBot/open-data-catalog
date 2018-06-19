# Utility Customer Service Performance Indicators: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utility-customer-service-performance-indicators-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/rnus-dqn7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rnus-dqn7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rnus-dqn7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rnus-dqn7 |
| Name | Utility Customer Service Performance Indicators: Beginning 2009 |
| Attribution | New York State electric and gas utilities, through the Public Service Commission |
| Category | Energy & Environment |
| Tags | service quality, customer service, performance indicators |
| Created | 2013-02-26T17:33:42Z |
| Publication Date | 2016-10-27T18:50:08Z |

## Description

Summary of the NYS gas and electric utilities? customer service performance indicators for each of the last three calendar years. Reported by the utilities on a uniform basis, these performance indicators allow comparative analysis of customer service, identification of overall trends in customer service, and identification of service deficiencies.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                             | Data Type | Render Type |
| ======== | ============== | ============================= | ================================ | ========= | =========== |
| Yes      | time           | year                          | Year                             | number    | number      |
| Yes      | series tag     | utility                       | Utility                          | text      | text        |
| Yes      | numeric metric | psc_complaint_rate            | PSC Complaint Rate               | number    | number      |
| Yes      | numeric metric | appointments_kept             | Appointments Kept                | percent   | percent     |
| Yes      | numeric metric | telephone_response_in_30_secs | Telephone Response (in 30 secs.) | percent   | percent     |
| Yes      | numeric metric | adjusted_bills                | Adjusted Bills                   | percent   | percent     |
| Yes      | numeric metric | estimated_readings            | Estimated Readings               | percent   | percent     |
| Yes      | numeric metric | utility_sort_order            | Utility Sort Order               | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rnus-dqn7 d:2009-01-01T00:00:00.000Z t:utility="Central Hudson" m:estimated_readings=3.03 m:adjusted_bills=1.16 m:appointments_kept=99.82 m:utility_sort_order=10 m:psc_complaint_rate=0.4 m:telephone_response_in_30_secs=29.81

series e:rnus-dqn7 d:2009-01-01T00:00:00.000Z t:utility="Con Edison" m:estimated_readings=12.66 m:adjusted_bills=0.44 m:appointments_kept=99.81 m:utility_sort_order=20 m:psc_complaint_rate=1.9 m:telephone_response_in_30_secs=56.7

series e:rnus-dqn7 d:2009-01-01T00:00:00.000Z t:utility=KEDLI m:estimated_readings=20.5 m:adjusted_bills=1.06 m:appointments_kept=96.09 m:utility_sort_order=30 m:psc_complaint_rate=0.5 m:telephone_response_in_30_secs=43
```

## Meta Commands

```ls
metric m:psc_complaint_rate p:float l:"PSC Complaint Rate" d:"Escalated complaints per 100,000 customers" t:dataTypeName=number

metric m:appointments_kept p:float l:"Appointments Kept" d:"Percentage of appointment kept" t:dataTypeName=percent

metric m:telephone_response_in_30_secs p:float l:"Telephone Response (in 30 secs.)" d:"Percentage of calls answered by live representative within 30 seconds" t:dataTypeName=percent

metric m:adjusted_bills p:float l:"Adjusted Bills" d:"Percentage of bills adjusted (recalculated and reissued)" t:dataTypeName=percent

metric m:estimated_readings p:float l:"Estimated Readings" d:"Percentage of meters with estimated, rather than actual, reads" t:dataTypeName=percent

metric m:utility_sort_order p:integer l:"Utility Sort Order" d:"Indicates Sort Order of the Utility Column" t:dataTypeName=number

entity e:rnus-dqn7 l:"Utility Customer Service Performance Indicators: Beginning 2009" t:attribution="New York State electric and gas utilities, through the Public Service Commission" t:url=https://data.ny.gov/api/views/rnus-dqn7

property e:rnus-dqn7 t:meta.view v:id=rnus-dqn7 v:category="Energy & Environment" v:averageRating=0 v:name="Utility Customer Service Performance Indicators: Beginning 2009" v:attribution="New York State electric and gas utilities, through the Public Service Commission"

property e:rnus-dqn7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rnus-dqn7 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:rnus-dqn7 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | utility        | psc_complaint_rate | appointments_kept | telephone_response_in_30_secs | adjusted_bills | estimated_readings | utility_sort_order | 
| ==== | ============== | ================== | ================= | ============================= | ============== | ================== | ================== | 
| 2009 | Central Hudson | 0.4                | 99.82             | 29.81                         | 1.16           | 3.03               | 10                 | 
| 2009 | Con Edison     | 1.9                | 99.81             | 56.70                         | 0.44           | 12.66              | 20                 | 
| 2009 | KEDLI          | 0.5                | 96.09             | 43.00                         | 1.06           | 20.50              | 30                 | 
| 2009 | KEDNY          | 0.9                | 78.40             | 71.52                         | 1.53           | 8.85               | 40                 | 
| 2009 | Median         | 0.9                | 96.93             | 65.61                         | 1.05           | 7.98               | 98                 | 
| 2009 | National Fuel  | 0.5                | 99.58             | 85.20                         | 1.23           | 13.81              | 50                 | 
| 2009 | National Grid  | 1                  | 99.34             | 81.80                         | 0.58           | 1.25               | 60                 | 
| 2009 | NYSEG          | 0.7                | 99.92             | 78.00                         | 0.63           | 3.83               | 70                 | 
| 2009 | O&R            | 0.7                | 100.00            | 66.00                         | 2.41           | 5.93               | 80                 | 
| 2009 | RG&E           | 1.4                | 99.42             | 78.50                         | 0.42           | 1.96               | 90                 | 
```