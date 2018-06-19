# Aircraft Noise Complaint Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aircraft-noise-complaint-data) |
| Metadata | [Link](https://data.sfgov.org/api/views/q3xd-hfi8) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/q3xd-hfi8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/q3xd-hfi8/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | q3xd-hfi8 |
| Name | Aircraft Noise Complaint Data |
| Category | Transportation |
| Tags | aircraft, noise, complaints, sfo, airlines |
| Created | 2016-04-08T22:31:19Z |
| Publication Date | 2016-04-08T23:04:50Z |

## Description

Counts of aircraft noise complaints by community and by month.  The Aircraft Noise Abatement Office collects this data via the Complaint Hotline, Online Complaint Form, emails, letters and telephone calls to our office. This information is collected and published in a monthly report which is presented at the SFO Airport Community Roundtable meetings. It is used to understand community's aircraft noise concerns, to collaborate with stakeholders in an effort to reduce and manage aircraft noise.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       |                | year                    | Year                    | number    | number      |
| No       |                | month                   | Month                   | number    | number      |
| Yes      | series tag     | community               | Community               | text      | text        |
| Yes      | numeric metric | total_complaints        | Total Complaints        | number    | number      |
| Yes      | numeric metric | total_number_of_callers | Total Number of Callers | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:q3xd-hfi8 d:2005-01-01T00:00:00.000Z t:community=Alameda m:total_complaints=7 m:total_number_of_callers=1

series e:q3xd-hfi8 d:2005-01-01T00:00:00.000Z t:community=Atherton m:total_complaints=242 m:total_number_of_callers=1

series e:q3xd-hfi8 d:2005-01-01T00:00:00.000Z t:community=Belmont m:total_complaints=75 m:total_number_of_callers=1
```

## Meta Commands

```ls
metric m:total_complaints p:integer l:"Total Complaints" t:dataTypeName=number

metric m:total_number_of_callers p:integer l:"Total Number of Callers" t:dataTypeName=number

entity e:q3xd-hfi8 l:"Aircraft Noise Complaint Data" t:url=https://data.sfgov.org/api/views/q3xd-hfi8

property e:q3xd-hfi8 t:meta.view v:id=q3xd-hfi8 v:category=Transportation v:averageRating=0 v:name="Aircraft Noise Complaint Data"

property e:q3xd-hfi8 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:q3xd-hfi8 t:meta.view.owner v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:displayName=NoiseAbatementOffice@flysfo.com

property e:q3xd-hfi8 t:meta.view.tableauthor v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:roleName=editor v:displayName=NoiseAbatementOffice@flysfo.com
```

## Top Records

```ls
| year | month | community   | total_complaints | total_number_of_callers | 
| ==== | ===== | =========== | ================ | ======================= | 
| 2005 | 1     | Alameda     | 7                | 1                       | 
| 2005 | 1     | Atherton    | 242              | 1                       | 
| 2005 | 1     | Belmont     | 75               | 1                       | 
| 2005 | 1     | Berkeley    | 8                | 1                       | 
| 2005 | 1     | Brisbane    | 239              | 7                       | 
| 2005 | 1     | Daly City   | 16               | 6                       | 
| 2005 | 1     | El Granada  | 1                | 1                       | 
| 2005 | 1     | Foster City | 6                | 1                       | 
| 2005 | 1     | Millbrae    | 2                | 1                       | 
| 2005 | 1     | Oakland     | 2                | 1                       | 
```