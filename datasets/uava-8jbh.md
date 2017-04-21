# Performance Metrics - Family & Support Services - Workforce Services Monthly Utilization

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-family-support-services-workforce-services-monthly-utilization-ae8b4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/uava-8jbh) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/uava-8jbh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/uava-8jbh/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | uava-8jbh |
| Name | Performance Metrics - Family & Support Services - Workforce Services Monthly Utilization |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, human services |
| Created | 2011-08-01T17:08:21Z |
| Publication Date | 2014-09-02T22:06:58Z |

## Description

This metric tracks workforce employment services including basic services, skills training and job placement per month. DFSS provides workforce development services to low income adults, dislocated workers and ex-offenders. These services include job readiness training, vocational training, job placement, supportive services and post-placement retention services.
The Chicago-Cook Workforce Partnership, a newly created agency designed to reform and revitalize workforce development in the greater Chicagoland area, took over operation of DFSS?s Workforce Investment Act funding and delegate agency contracts on July 1, 2012.  http://www.workforceboard.org

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | month                     | Month                     | text      | text        |
| Yes      | time           | year                      | Year                      | number    | text        |
| Yes      | numeric metric | newly_enrolled_in_program | Newly Enrolled in Program | number    | number      |
| Yes      | numeric metric | entering_skills_training  | Entering Skills Training  | number    | number      |
| Yes      | numeric metric | placed_in_employment      | Placed in Employment      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:uava-8jbh d:2011-01-01T00:00:00.000Z t:month=11-Jan m:placed_in_employment=348 m:entering_skills_training=266 m:newly_enrolled_in_program=696

series e:uava-8jbh d:2011-01-01T00:00:00.000Z t:month=11-Feb m:placed_in_employment=322 m:entering_skills_training=418 m:newly_enrolled_in_program=519

series e:uava-8jbh d:2011-01-01T00:00:00.000Z t:month=11-Mar m:placed_in_employment=583 m:entering_skills_training=340 m:newly_enrolled_in_program=772
```

## Meta Commands

```ls
metric m:newly_enrolled_in_program p:integer l:"Newly Enrolled in Program" t:dataTypeName=number

metric m:entering_skills_training p:integer l:"Entering Skills Training" t:dataTypeName=number

metric m:placed_in_employment p:integer l:"Placed in Employment" t:dataTypeName=number

entity e:uava-8jbh l:"Performance Metrics - Family & Support Services - Workforce Services Monthly Utilization" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/uava-8jbh

property e:uava-8jbh t:meta.view v:id=uava-8jbh v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Family & Support Services - Workforce Services Monthly Utilization" v:attribution="City of Chicago"

property e:uava-8jbh t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:uava-8jbh t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| month  | year | newly_enrolled_in_program | entering_skills_training | placed_in_employment | 
| ====== | ==== | ========================= | ======================== | ==================== | 
| 11-Jan | 2011 | 696                       | 266                      | 348                  | 
| 11-Feb | 2011 | 519                       | 418                      | 322                  | 
| 11-Mar | 2011 | 772                       | 340                      | 583                  | 
| 11-Apr | 2011 | 678                       | 228                      | 667                  | 
| 11-May | 2011 | 714                       | 268                      | 424                  | 
| 11-Jun | 2011 | 783                       | 403                      | 662                  | 
| 11-Jul | 2011 | 524                       | 173                      | 592                  | 
| 11-Aug | 2011 | 452                       | 275                      | 488                  | 
| 11-Sep | 2011 | 1018                      | 211                      | 331                  | 
| 11-Oct | 2011 | 265                       | 165                      | 572                  | 
```