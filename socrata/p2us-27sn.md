# EMS - Quarterly Cardiac Arrest Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-quarterly-cardiac-arrest-measures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/p2us-27sn) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/p2us-27sn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/p2us-27sn/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | p2us-27sn |
| Name | EMS - Quarterly Cardiac Arrest Measures |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, atcems, clinical data, clinical performance, clinical measures, patient care, cardiac arrest, rosc, resuscitation |
| Created | 2017-02-02T22:38:46Z |
| Publication Date | 2017-02-07T15:49:40Z |

## Description

This table contains performance data regarding resuscitation of cardiac arrest patients.  It is limited to patients whose arrest is of presumed cardiac origin, and for whom resuscitation was attempted.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                                              | Data Type     | Render Type   |
| ======== | ============== | ========================== | ================================================= | ============= | ============= |
| Yes      | numeric metric | fiscal_quarter_key         | Fiscal Quarter Key                                | number        | number        |
| No       |                | fiscal_quarter             | Fiscal Quarter                                    | text          | text          |
| Yes      | time           | fiscal_quarter_start_date  | Fiscal Quarter Start Date                         | calendar_date | calendar_date |
| No       |                | fiscal_quarter_end_date    | Fiscal Quarter End Date                           | calendar_date | calendar_date |
| Yes      | numeric metric | count_cardiac_arrest       | Count ? Cardiac Arrests                           | number        | number        |
| Yes      | numeric metric | count_pulse_at_ed          | Count ? Cardiac Arrests with Pulse at ED          | number        | number        |
| Yes      | numeric metric | percent_pulse_at_ed        | Percent ? Cardiac Arrests with Pulse at ED        | percent       | percent       |
| Yes      | numeric metric | percent_pulse_at_ed_target | Target - Percent Cardiac Arrests with Pulse at ED | percent       | percent       |
```

## Time Field

```ls
Value = fiscal_quarter_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_quarter_end_date,fiscal_quarter
```

## Data Commands

```ls
series e:p2us-27sn d:2013-10-01T00:00:00.000Z m:fiscal_quarter_key=201401 m:count_pulse_at_ed=42 m:percent_pulse_at_ed_target=30 m:count_cardiac_arrest=150 m:percent_pulse_at_ed=28

series e:p2us-27sn d:2014-01-01T00:00:00.000Z m:fiscal_quarter_key=201402 m:count_pulse_at_ed=52 m:percent_pulse_at_ed_target=30 m:count_cardiac_arrest=159 m:percent_pulse_at_ed=32.7

series e:p2us-27sn d:2014-04-01T00:00:00.000Z m:fiscal_quarter_key=201403 m:count_pulse_at_ed=47 m:percent_pulse_at_ed_target=30 m:count_cardiac_arrest=117 m:percent_pulse_at_ed=40.17
```

## Meta Commands

```ls
metric m:fiscal_quarter_key p:integer l:"Fiscal Quarter Key" d:"Row identifier ? numeric representation of fiscal quarter in <yyyyqq> format." t:dataTypeName=number

metric m:count_cardiac_arrest p:integer l:"Count ? Cardiac Arrests" d:"Count of patients with cardiac arrest of suspected cardiac origin, for whom resuscitation was attempted." t:dataTypeName=number

metric m:count_pulse_at_ed p:integer l:"Count ? Cardiac Arrests with Pulse at ED" d:"Count of cardiac arrest patients who have a spontaneous pulse on arrival at an emergency department." t:dataTypeName=number

metric m:percent_pulse_at_ed p:float l:"Percent ? Cardiac Arrests with Pulse at ED" d:"Percent of cardiac arrest patients who had a spontaneous pulse on arrival at an emergency department." t:dataTypeName=percent

metric m:percent_pulse_at_ed_target p:integer l:"Target - Percent Cardiac Arrests with Pulse at ED" d:"Target performance level for percent of cardiac arrest patients who had a spontaneous pulse on arrival at an emergency department." t:dataTypeName=percent

entity e:p2us-27sn l:"EMS - Quarterly Cardiac Arrest Measures" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/p2us-27sn

property e:p2us-27sn t:meta.view v:id=p2us-27sn v:category="Public Safety" v:averageRating=0 v:name="EMS - Quarterly Cardiac Arrest Measures" v:attribution="Austin-Travis County EMS"

property e:p2us-27sn t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:p2us-27sn t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| fiscal_quarter_key | fiscal_quarter | fiscal_quarter_start_date | fiscal_quarter_end_date | count_cardiac_arrest | count_pulse_at_ed | percent_pulse_at_ed | percent_pulse_at_ed_target | 
| ================== | ============== | ========================= | ======================= | ==================== | ================= | =================== | ========================== | 
| 201401             | 2014-Q1        | 2013-10-01T00:00:00       | 2013-12-31T23:59:50     | 150                  | 42                | 28.00               | 30                         | 
| 201402             | 2014-Q2        | 2014-01-01T00:00:00       | 2014-03-31T23:59:59     | 159                  | 52                | 32.70               | 30                         | 
| 201403             | 2014-Q3        | 2014-04-01T00:00:00       | 2014-06-30T23:59:59     | 117                  | 47                | 40.17               | 30                         | 
| 201404             | 2014-Q4        | 2014-07-01T00:00:00       | 2014-09-30T23:59:59     | 116                  | 30                | 25.86               | 30                         | 
| 201501             | 2015-Q1        | 2014-10-01T00:00:00       | 2014-12-31T23:59:50     | 138                  | 41                | 29.71               | 30                         | 
| 201502             | 2015-Q2        | 2015-01-01T00:00:00       | 2015-03-31T23:59:59     | 135                  | 41                | 30.37               | 30                         | 
| 201503             | 2015-Q3        | 2015-04-01T00:00:00       | 2015-06-30T23:59:59     | 155                  | 52                | 33.55               | 30                         | 
| 201504             | 2015-Q4        | 2015-07-01T00:00:00       | 2015-09-30T23:59:59     | 128                  | 33                | 25.78               | 30                         | 
| 201601             | 2016-Q1        | 2015-10-01T00:00:00       | 2015-12-31T23:59:50     | 141                  | 37                | 26.24               | 30                         | 
| 201602             | 2016-Q2        | 2016-01-01T00:00:00       | 2016-03-31T23:59:59     | 138                  | 41                | 29.71               | 30                         | 
```