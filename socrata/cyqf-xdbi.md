# Board of Commissioners Contingency Accounts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-commissioners-contingency-accounts) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/cyqf-xdbi) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cyqf-xdbi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cyqf-xdbi/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | cyqf-xdbi |
| Name | Board of Commissioners Contingency Accounts |
| Attribution | Board of Commissioners |
| Category | Finance & Administration |
| Created | 2016-06-23T02:25:22Z |
| Publication Date | 2016-06-23T02:31:04Z |

## Description

Board member contingency funds forms submitted for reimbursement approval to the Ethics Department.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | link                 | Link                 | url           | url           |
| Yes      | series tag  | commissioner_name    | Commissioner Name    | text          | text          |
| Yes      | series tag  | district             | District             | text          | number        |
| Yes      | time        | start_date           | Start Date           | calendar_date | calendar_date |
| No       |             | end_date             | End Date             | calendar_date | calendar_date |
| Yes      | series tag  | current_commissioner | Current Commissioner | checkbox      | checkbox      |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:cyqf-xdbi d:2011-12-01T00:00:00.000Z t:commissioner_name="Robert Steele" t:link=http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-12-01-11-thru-02-29-12-Form.pdf t:current_commissioner=true t:district=2 m:row_number.cyqf-xdbi=1

series e:cyqf-xdbi d:2012-03-01T00:00:00.000Z t:commissioner_name="Robert Steele" t:link=http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-03-01-12-thru-05-31-12-Form.pdf t:current_commissioner=true t:district=2 m:row_number.cyqf-xdbi=2

series e:cyqf-xdbi d:2012-06-01T00:00:00.000Z t:commissioner_name="Robert Steele" t:link=http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-06-01-12-thru-08-31-12-form.pdf t:current_commissioner=true t:district=2 m:row_number.cyqf-xdbi=3
```

## Meta Commands

```ls
metric m:row_number.cyqf-xdbi p:long l:"Row Number"

entity e:cyqf-xdbi l:"Board of Commissioners Contingency Accounts" t:attribution="Board of Commissioners" t:url=https://datacatalog.cookcountyil.gov/api/views/cyqf-xdbi

property e:cyqf-xdbi t:meta.view v:id=cyqf-xdbi v:category="Finance & Administration" v:averageRating=0 v:name="Board of Commissioners Contingency Accounts" v:attribution="Board of Commissioners"

property e:cyqf-xdbi t:meta.view.license v:name="Public Domain"

property e:cyqf-xdbi t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:cyqf-xdbi t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                                                                   | commissioner_name | district | start_date          | end_date            | current_commissioner | 
| ====================================================================================================================================================== | ================= | ======== | =================== | =================== | ==================== | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-12-01-11-thru-02-29-12-Form.pdf, Steele ? 12-01-11 thru 02-29-12 Form]     | Robert Steele     | 2        | 2011-12-01T00:00:00 | 2012-02-29T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-03-01-12-thru-05-31-12-Form.pdf, Steele ? 03-01-12 thru 05-31-12 Form]     | Robert Steele     | 2        | 2012-03-01T00:00:00 | 2012-05-31T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-06-01-12-thru-08-31-12-form.pdf, Steele 06-01-12 thru 08-31-12 form]       | Robert Steele     | 2        | 2012-06-01T00:00:00 | 2012-08-31T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-09-01-12-thru-11-30-12-_-Form.pdf, Steele 09-01-12 thru 11-30-12 _ Form]   | Robert Steele     | 2        | 2012-09-01T00:00:00 | 2012-11-30T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-12-01-12-thru-02-28-13-Form.pdf, Steele 12-01-12 thru 02-28-13 Form]       | Robert Steele     | 2        | 2012-12-01T00:00:00 | 2013-02-28T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-03-01-13-thru-05-31-13-Form.pdf, Steele 03-01-13 thru 05-31-13 Form]       | Robert Steele     | 2        | 2013-03-01T00:00:00 | 2013-05-31T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-09-01-13-through-11-30-13-Form.pdf, Steele 09-01-13 through 11-30-13 Form] | Robert Steele     | 2        | 2013-09-01T00:00:00 | 2013-11-30T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-12-01-14-thru-02-28-15-Form.pdf, Steele 12-01-14 thru 02-28-15 Form]       | Robert Steele     | 2        | 2014-12-01T00:00:00 | 2015-02-28T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Steele-03-01-15-thru-05-31-15-Form.pdf, Steele 03-01-15 thru 05-31-15 Form]       | Robert Steele     | 2        | 2015-03-01T00:00:00 | 2015-05-31T00:00:00 | true                 | 
| [http://opendocs.cookcountyil.gov/commissioners/contingency-accounts/Sims-12-01-11-thru-02-29-12-Form.pdf, Sims 12-01-11 thru 02-29-12 Form]           | Deborah Sims      | 5        | 2011-12-01T00:00:00 | 2012-02-29T00:00:00 | true                 | 
```