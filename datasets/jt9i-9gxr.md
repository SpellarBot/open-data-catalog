# Environmentally Preferable Purchasing FY15 - Goods

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/environmentally-preferable-purchasing-fy15-goods) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jt9i-9gxr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jt9i-9gxr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jt9i-9gxr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jt9i-9gxr |
| Name | Environmentally Preferable Purchasing FY15 - Goods |
| Attribution | Mayor's Office of Contract Services (MOCS) |
| Category | City Government |
| Created | 2015-12-17T17:42:35Z |
| Publication Date | 2015-12-17T17:55:41Z |

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                            | Data Type     | Render Type   |
| ======== | ============== | ============================== | =============================== | ============= | ============= |
| Yes      | series tag     | description                    | Description                     | text          | text          |
| Yes      | series tag     | epp_minimum_standard_indicated | EPP Minimum Standard Indicated? | text          | text          |
| Yes      | series tag     | contract_start_end_dates       | Contract Start/ End Dates       | text          | text          |
| Yes      | time           | registration_date              | Registration Date               | calendar_date | calendar_date |
| Yes      | numeric metric | contract_value                 | Contract Value                  | money         | money         |
```

## Time Field

```ls
Value = registration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jt9i-9gxr d:2014-07-02T00:00:00.000Z t:epp_minimum_standard_indicated="Yes - Energy Star Compliant" t:description="Shredding Machines- Paper Re-ad" t:contract_start_end_dates="09/01/14 thru 08/31/19" m:contract_value=1511280

series e:jt9i-9gxr d:2014-07-30T00:00:00.000Z t:epp_minimum_standard_indicated="Yes - Energy Star Compliant" t:description="Shredding Machines- Paper Re-ad" t:contract_start_end_dates="09/01/14 thru 08/31/19" m:contract_value=169940

series e:jt9i-9gxr d:2015-06-24T00:00:00.000Z t:epp_minimum_standard_indicated="Yes - 30% Minimum Recycled Content" t:description="Calendars, Diaries, Planners & Journals" t:contract_start_end_dates="09/25/15 thru 09/24/20" m:contract_value=724438
```

## Meta Commands

```ls
metric m:contract_value p:integer l:"Contract Value" t:dataTypeName=money

entity e:jt9i-9gxr l:"Environmentally Preferable Purchasing  FY15 - Goods" t:attribution="Mayor's Office of Contract Services (MOCS)" t:url=https://data.cityofnewyork.us/api/views/jt9i-9gxr

property e:jt9i-9gxr t:meta.view v:id=jt9i-9gxr v:category="City Government" v:averageRating=0 v:name="Environmentally Preferable Purchasing  FY15 - Goods" v:attribution="Mayor's Office of Contract Services (MOCS)"

property e:jt9i-9gxr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jt9i-9gxr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| description                               | epp_minimum_standard_indicated     | contract_start_end_dates | registration_date   | contract_value | 
| ========================================= | ================================== | ======================== | =================== | ============== | 
| Shredding Machines- Paper Re-ad           | Yes - Energy Star Compliant        | 09/01/14 thru 08/31/19   | 2014-07-02T00:00:00 | 1511280        | 
| Shredding Machines- Paper Re-ad           | Yes - Energy Star Compliant        | 09/01/14 thru 08/31/19   | 2014-07-30T00:00:00 | 169940         | 
| Calendars, Diaries, Planners & Journals   | Yes - 30% Minimum Recycled Content | 09/25/15 thru 09/24/20   | 2015-06-24T00:00:00 | 724438         | 
| Business Cards                            | Yes - 30% Minimum Recycled Content | 07/01/14 thru 06/30/19   | 2014-08-16T00:00:00 | 656713         | 
| Ballasts                                  | Yes - Energy Star Compliant        | 09/01/14 thru 08/31/19   | 2014-08-19T00:00:00 | 170000         | 
| Fans: Desk, Wall, and Floor               | Yes - Energy Star Compliant        | 09/01/14 thru 08/31/19   | 2014-08-21T00:00:00 | 2068021        | 
| Various Paper Stock                       | Yes - 30% Minimum Recycled Content | 10/01/14 thru 09/30/17   | 2014-09-22T00:00:00 | 241122         | 
| Paper, Bond, Sub 16                       | Yes - 30% Minimum Recycled Content | 01/04/15 thru 01/03/20   | 2014-11-24T00:00:00 | 9690           | 
| Machines, Stamping: Time/Date and Payroll | Yes - Energy Star Compliant        | 01/01/15 thru 12/31/19   | 2014-12-31T00:00:00 | 728740         | 
| Machines, Stamping: Time/Date and Payroll | Yes - Energy Star Compliant        | 01/01/15 thru 12/31/19   | 2014-12-19T00:00:00 | 286770         | 
```