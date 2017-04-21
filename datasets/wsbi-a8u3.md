# Environmental Control - Asbestos Demolition Summary Report - February 2011 to August 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/environmental-control-asbestos-demolition-summary-report-february-2011-to-august-2012-12ec5) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/wsbi-a8u3) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wsbi-a8u3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wsbi-a8u3/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | wsbi-a8u3 |
| Name | Environmental Control - Asbestos Demolition Summary Report - February 2011 to August 2012 |
| Attribution | Cook County Bureau of Environmental Control |
| Category | Finance & Administration |
| Created | 2012-08-27T19:29:58Z |
| Publication Date | 2014-10-09T21:25:50Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | permit_number         | Permit Number         | text          | text          |
| No       |                | issue_date            | Issue Date            | text          | text          |
| Yes      | series tag     | permit_type           | Permit Type           | text          | text          |
| Yes      | numeric metric | permit_fee            | Permit Fee            | money         | money         |
| Yes      | time           | start_date            | Start Date            | calendar_date | calendar_date |
| No       |                | end_date              | End Date              | calendar_date | calendar_date |
| Yes      | series tag     | property_type         | Property Type         | text          | text          |
| No       |                | property_address      | Property Address      | text          | text          |
| Yes      | series tag     | demolition_contractor | Demolition Contractor | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issue_date,end_date,property_address
```

## Data Commands

```ls
series e:wsbi-a8u3 d:2011-01-14T08:00:00.000Z t:permit_type=0.00 t:permit_number=A1100128 t:property_type=Residence t:demolition_contractor="Chicago Diversified Projects, Inc." m:permit_fee=200

series e:wsbi-a8u3 d:2011-01-01T08:00:00.000Z t:permit_type=0.00 t:permit_number=A1100138 t:property_type="UOP LLC" t:demolition_contractor="APD Environmental, Inc." m:permit_fee=200

series e:wsbi-a8u3 d:2011-01-04T08:00:00.000Z t:permit_type=100.00 t:permit_number=A1100118 t:property_type=AMD t:demolition_contractor="The Luse Companies" m:permit_fee=200
```

## Meta Commands

```ls
metric m:permit_fee p:double l:"Permit Fee" t:dataTypeName=money

entity e:wsbi-a8u3 l:"Environmental Control - Asbestos Demolition Summary Report - February 2011 to August 2012" t:attribution="Cook County Bureau of Environmental Control" t:url=https://datacatalog.cookcountyil.gov/api/views/wsbi-a8u3

property e:wsbi-a8u3 t:meta.view v:id=wsbi-a8u3 v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/environmental_control/291 v:averageRating=0 v:name="Environmental Control - Asbestos Demolition Summary Report - February 2011 to August 2012" v:attribution="Cook County Bureau of Environmental Control"

property e:wsbi-a8u3 t:meta.view.license v:name="Public Domain"

property e:wsbi-a8u3 t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:wsbi-a8u3 t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| permit_number | issue_date | permit_type | permit_fee | start_date          | end_date            | property_type                     | property_address         | demolition_contractor              | 
| ============= | ========== | =========== | ========== | =================== | =================== | ================================= | ======================== | ================================== | 
| A1100128      | 05-Jan-11  | 0.00        | 200.00     | 2011-01-14T08:00:00 | 2011-01-14T08:00:00 | Residence                         | 182 Lapier St.           | Chicago Diversified Projects, Inc. | 
| A1100138      | 10-Jan-11  | 0.00        | 200.00     | 2011-01-01T08:00:00 | 2011-12-31T08:00:00 | UOP LLC                           | 50 E. Algonquin Road - C | APD Environmental, Inc.            | 
| A1100118      | 04-Jan-11  | 100.00      | 200.00     | 2011-01-04T08:00:00 | 2011-01-12T08:00:00 | AMD                               | 4620 W. 19th St.         | The Luse Companies                 | 
| A1100124      | 04-Jan-11  | 2,000.00    | 200.00     | 2011-01-12T08:00:00 | 2011-01-17T08:00:00 | Church (Victory Outreach Spanish) | 3148 Clinton             | Crowne Environmental               | 
| A1100134      | 10-Jan-11  | 0.00        | 200.00     | 2011-01-19T08:00:00 | 2011-01-19T08:00:00 | Coach House                       | 4221 Anna Ave.           | Bluestone Environmental, Inc.      | 
| A1100135      | 10-Jan-11  | 2,000.00    | 200.00     | 2011-01-18T08:00:00 | 2011-01-19T08:00:00 | St. Odilo                         | 2244 East Ave.           | Celtic Environmental Company       | 
| A1100136      | 10-Jan-11  | 0.00        | 200.00     | 2011-01-01T08:00:00 | 2011-12-31T08:00:00 | UOP LLC                           | 50 E. Algonquin Rd -A    | APD Environmental, Inc.            | 
| A1100130      | 05-Jan-11  | 800.00      | 200.00     | 2011-01-14T08:00:00 | 2011-01-17T08:00:00 | International Paper               | 100 E. Oakton St.        | Colfax Corporation                 | 
| A1100133      | 07-Jan-11  | 1,200.00    | 200.00     | 2011-01-10T08:00:00 | 2011-01-10T08:00:00 | Warehouse                         | 1400 Morse Ave           | Celtic Environmental Company       | 
| A1100117      | 04-Jan-11  | 0.00        | 200.00     | 2011-01-05T08:00:00 | 2011-01-06T08:00:00 | Residence                         | 264 Brookhaven Dr.       | Gold Piece Enterprises, Inc.       | 
```