# Child Support Enforcement Administration's FFY 2012 Jurisdictional Performance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/child-support-enforcement-administrations-ffy-2012-jurisdictional-performance-d0e38) |
| Metadata | [Link](https://data.maryland.gov/api/views/2ua9-wand) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/2ua9-wand/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/2ua9-wand/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 2ua9-wand |
| Name | Child Support Enforcement Administration's FFY 2012 Jurisdictional Performance |
| Attribution | Department of Human Resources |
| Tags | support order, caseload |
| Created | 2012-10-05T18:49:25Z |
| Publication Date | 2012-10-05T18:56:34Z |

## Description

CSEA's local department of social services Federal fiscal year 2012 performance for support orders as well as caseload.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type | Render Type |
| ======== | ============== | ============================== | ================================ | ========= | =========== |
| Yes      | series tag     | local_department               | Local Department                 | text      | text        |
| Yes      | numeric metric | support_order_caseload         | Support Order Caseload           | number    | number      |
| Yes      | numeric metric | ffy_2012_performance_10_1_2011 | FFY 2012 Performance - 10/1/2011 | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_11_1_2011 | FFY 2012 Performance - 11/1/2011 | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_12_1_2011 | FFY 2012 Performance - 12/1/2011 | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_1_1_2012  | FFY 2012 Performance - 1/1/2012  | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_2_1_2012  | FFY 2012 Performance - 2/1/2012  | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_3_1_2012  | FFY 2012 Performance - 3/1/2012  | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_4_1_2012  | FFY 2012 Performance - 4/1/2012  | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_5_1_2012  | FFY 2012 Performance - 5/1/2012  | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_6_1_2012  | FFY 2012 Performance - 6/1/2012  | percent   | percent     |
| Yes      | numeric metric | ffy_2012_performance_7_1_2012  | FFY 2012 Performance - 7/1/2012  | percent   | percent     |
| Yes      | numeric metric | rate_required_mar_2012         | Rate required - Mar 2012         | percent   | percent     |
| Yes      | numeric metric | ffy_2012_goal                  | FFY 2012 Goal                    | percent   | percent     |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2ua9-wand d:2012-01-01T00:00:00.000Z t:local_department="Baltimore City" m:ffy_2012_performance_10_1_2011=80.95 m:ffy_2012_goal=77.25 m:ffy_2012_performance_3_1_2012=80.18 m:ffy_2012_performance_7_1_2012=78.15 m:ffy_2012_performance_1_1_2012=80.08 m:rate_required_mar_2012=77.25 m:ffy_2012_performance_4_1_2012=80.21 m:ffy_2012_performance_11_1_2011=80.6 m:ffy_2012_performance_12_1_2011=80.47 m:ffy_2012_performance_5_1_2012=80.3 m:ffy_2012_performance_6_1_2012=80.2 m:support_order_caseload=74918 m:ffy_2012_performance_2_1_2012=80.17

series e:2ua9-wand d:2012-01-01T00:00:00.000Z t:local_department="Prince George's" m:ffy_2012_performance_10_1_2011=78.37 m:ffy_2012_goal=88.1 m:ffy_2012_performance_3_1_2012=78.27 m:ffy_2012_performance_7_1_2012=79.14 m:ffy_2012_performance_1_1_2012=78.16 m:rate_required_mar_2012=88.1 m:ffy_2012_performance_4_1_2012=78.72 m:ffy_2012_performance_11_1_2011=78.39 m:ffy_2012_performance_12_1_2011=78.31 m:ffy_2012_performance_5_1_2012=79.05 m:ffy_2012_performance_6_1_2012=79.7 m:support_order_caseload=45176 m:ffy_2012_performance_2_1_2012=78.17

series e:2ua9-wand d:2012-01-01T00:00:00.000Z t:local_department="Baltimore County" m:ffy_2012_performance_10_1_2011=83.08 m:ffy_2012_goal=88.1 m:ffy_2012_performance_3_1_2012=84.28 m:ffy_2012_performance_7_1_2012=84.72 m:ffy_2012_performance_1_1_2012=82.92 m:rate_required_mar_2012=88.1 m:ffy_2012_performance_4_1_2012=84.42 m:ffy_2012_performance_11_1_2011=82.73 m:ffy_2012_performance_12_1_2011=83 m:ffy_2012_performance_5_1_2012=84.71 m:ffy_2012_performance_6_1_2012=85.08 m:support_order_caseload=22162 m:ffy_2012_performance_2_1_2012=84.22
```

## Meta Commands

```ls
metric m:support_order_caseload p:integer l:"Support Order Caseload" t:dataTypeName=number

metric m:ffy_2012_performance_10_1_2011 p:float l:"FFY 2012 Performance - 10/1/2011" t:dataTypeName=percent

metric m:ffy_2012_performance_11_1_2011 p:float l:"FFY 2012 Performance - 11/1/2011" t:dataTypeName=percent

metric m:ffy_2012_performance_12_1_2011 p:float l:"FFY 2012 Performance - 12/1/2011" t:dataTypeName=percent

metric m:ffy_2012_performance_1_1_2012 p:float l:"FFY 2012 Performance - 1/1/2012" t:dataTypeName=percent

metric m:ffy_2012_performance_2_1_2012 p:float l:"FFY 2012 Performance - 2/1/2012" t:dataTypeName=percent

metric m:ffy_2012_performance_3_1_2012 p:float l:"FFY 2012 Performance - 3/1/2012" t:dataTypeName=percent

metric m:ffy_2012_performance_4_1_2012 p:float l:"FFY 2012 Performance - 4/1/2012" t:dataTypeName=percent

metric m:ffy_2012_performance_5_1_2012 p:float l:"FFY 2012 Performance - 5/1/2012" t:dataTypeName=percent

metric m:ffy_2012_performance_6_1_2012 p:float l:"FFY 2012 Performance - 6/1/2012" t:dataTypeName=percent

metric m:ffy_2012_performance_7_1_2012 p:float l:"FFY 2012 Performance - 7/1/2012" t:dataTypeName=percent

metric m:rate_required_mar_2012 p:float l:"Rate required - Mar 2012" t:dataTypeName=percent

metric m:ffy_2012_goal p:float l:"FFY 2012 Goal" t:dataTypeName=percent

entity e:2ua9-wand l:"Child Support Enforcement Administration's FFY 2012 Jurisdictional Performance" t:attribution="Department of Human Resources" t:url=https://data.maryland.gov/api/views/2ua9-wand

property e:2ua9-wand t:meta.view v:id=2ua9-wand v:averageRating=0 v:name="Child Support Enforcement Administration's FFY 2012 Jurisdictional Performance" v:attribution="Department of Human Resources"

property e:2ua9-wand t:meta.view.owner v:id=6amv-2brc v:screenName="Maria Tillman" v:displayName="Maria Tillman"

property e:2ua9-wand t:meta.view.tableauthor v:id=6amv-2brc v:screenName="Maria Tillman" v:roleName=editor v:displayName="Maria Tillman"
```

## Top Records

```ls
| local_department    | support_order_caseload | ffy_2012_performance_10_1_2011 | ffy_2012_performance_11_1_2011 | ffy_2012_performance_12_1_2011 | ffy_2012_performance_1_1_2012 | ffy_2012_performance_2_1_2012 | ffy_2012_performance_3_1_2012 | ffy_2012_performance_4_1_2012 | ffy_2012_performance_5_1_2012 | ffy_2012_performance_6_1_2012 | ffy_2012_performance_7_1_2012 | rate_required_mar_2012 | ffy_2012_goal | 
| =================== | ====================== | ============================== | ============================== | ============================== | ============================= | ============================= | ============================= | ============================= | ============================= | ============================= | ============================= | ====================== | ============= | 
| Baltimore City      | 74918                  | 80.95                          | 80.60                          | 80.47                          | 80.08                         | 80.17                         | 80.18                         | 80.21                         | 80.30                         | 80.20                         | 78.15                         | 77.25                  | 77.25         | 
| Prince George's     | 45176                  | 78.37                          | 78.39                          | 78.31                          | 78.16                         | 78.17                         | 78.27                         | 78.72                         | 79.05                         | 79.70                         | 79.14                         | 88.10                  | 88.10         | 
| Baltimore County    | 22162                  | 83.08                          | 82.73                          | 83.00                          | 82.92                         | 84.22                         | 84.28                         | 84.42                         | 84.71                         | 85.08                         | 84.72                         | 88.10                  | 88.10         | 
| Montgomery          | 18647                  | 85.36                          | 85.67                          | 85.65                          | 85.72                         | 85.62                         | 86.19                         | 86.71                         | 87.54                         | 87.79                         | 86.89                         | 88.10                  | 88.10         | 
| Anne Arundel County | 14382                  | 86.75                          | 86.80                          | 86.95                          | 86.89                         | 86.57                         | 87.00                         | 87.22                         | 87.71                         | 88.11                         | 87.61                         | 88.10                  | 88.10         | 
| Harford             | 6530                   | 87.51                          | 87.25                          | 87.50                          | 88.21                         | 88.57                         | 88.72                         | 88.83                         | 88.86                         | 88.83                         | 88.72                         | 88.10                  | 88.10         | 
| Charles             | 6124                   | 81.36                          | 80.67                          | 80.44                          | 81.34                         | 81.63                         | 82.24                         | 83.14                         | 82.93                         | 83.58                         | 83.15                         | 88.10                  | 88.10         | 
| Washington          | 6088                   | 87.80                          | 87.47                          | 87.38                          | 87.63                         | 87.68                         | 87.80                         | 88.50                         | 88.25                         | 87.84                         | 87.97                         | 88.10                  | 88.10         | 
| Frederick           | 5582                   | 86.97                          | 87.02                          | 87.61                          | 87.35                         | 88.04                         | 87.69                         | 88.38                         | 88.41                         | 88.80                         | 88.58                         | 88.10                  | 88.10         | 
| Wicomico            | 5013                   | 83.59                          | 83.39                          | 84.22                          | 84.80                         | 83.95                         | 84.43                         | 85.27                         | 85.85                         | 86.25                         | 86.39                         | 88.10                  | 88.10         | 
```