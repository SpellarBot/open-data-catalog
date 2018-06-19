# 2016 NYC Open Data Plan - List of Datasets Removed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-nyc-open-data-plan-list-of-datasets-removed) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/eivx-q94q) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/eivx-q94q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/eivx-q94q/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | eivx-q94q |
| Name | 2016 NYC Open Data Plan - List of Datasets Removed |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Created | 2016-07-15T13:52:18Z |
| Publication Date | 2017-02-16T23:20:08Z |

## Description

An inventory of data sets removed in the 2016 update to the Open Data Plan.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | agency               | Agency               | text      | text        |
| Yes      | series tag  | data_set_title       | Data Set Title       | text      | text        |
| Yes      | series tag  | data_set_description | Data Set Description | text      | text        |
| Yes      | series tag  | agency_comment       | Agency Comment       | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:eivx-q94q d:2016-01-01T00:00:00.000Z t:data_set_description="This list contains information on taxicab brokers." t:data_set_title="SHL Vehicles ? Brokers" t:agency="Taxi and Limousine Commission (TLC)" t:agency_comment="Under review ? data may/may not apply to SHL entity" m:row_number.eivx-q94q=1

series e:eivx-q94q d:2016-01-01T00:00:00.000Z t:data_set_description="The Mayor shall ensure that copies of City contracts and other standard information regarding City contracts and vendors (including information relating to the vendor's qualification and performance evaluations, contract audits, and decisions regarding suspension and debarment) are reasonably available for public inspection as provided by law, with adequate protection for confidential information." t:data_set_title="Performance Evaluations" t:agency="Office of the Mayor (OTM)" t:agency_comment="Does not qualify as ?data? according to Local Law 11 of 2012" m:row_number.eivx-q94q=2

series e:eivx-q94q d:2016-01-01T00:00:00.000Z t:data_set_description="Names, locations and dates of events permitted by Street Activity Permit Office and the DSNY cost of clean-up efforts billed to event organizers." t:data_set_title="Events and clean-up costs" t:agency="Department of Sanitation (DSNY)" t:agency_comment="Under review ? dataset may not be public" m:row_number.eivx-q94q=3
```

## Meta Commands

```ls
metric m:row_number.eivx-q94q p:long l:"Row Number"

entity e:eivx-q94q l:"2016 NYC Open Data Plan - List of Datasets Removed" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/eivx-q94q

property e:eivx-q94q t:meta.view v:id=eivx-q94q v:averageRating=0 v:name="2016 NYC Open Data Plan - List of Datasets Removed" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:eivx-q94q t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:eivx-q94q t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| agency                                                | data_set_title                                | data_set_description                                                                                                                                                                                                                                                                                                                                                                                             | agency_comment                                                                                                                                                                    | 
| ===================================================== | ============================================= | ================================================================================================================================================================================================================================================================================================================================================================================================================ | ================================================================================================================================================================================= | 
| Taxi and Limousine Commission (TLC)                   | SHL Vehicles ? Brokers                        | This list contains information on taxicab brokers.                                                                                                                                                                                                                                                                                                                                                               | Under review ? data may/may not apply to SHL entity                                                                                                                               | 
| Office of the Mayor (OTM)                             | Performance Evaluations                       | The Mayor shall ensure that copies of City contracts and other standard information regarding City contracts and vendors (including information relating to the vendor's qualification and performance evaluations, contract audits, and decisions regarding suspension and debarment) are reasonably available for public inspection as provided by law, with adequate protection for confidential information. | Does not qualify as ?data? according to Local Law 11 of 2012                                                                                                                      | 
| Department of Sanitation (DSNY)                       | Events and clean-up costs                     | Names, locations and dates of events permitted by Street Activity Permit Office and the DSNY cost of clean-up efforts billed to event organizers.                                                                                                                                                                                                                                                                | Under review ? dataset may not be public                                                                                                                                          | 
| Department of Sanitation (DSNY)                       | Resource Plans                                | Planned number of personnel to be assigned to Cleaning and Collection functions, by Sanitation District, date, and function.                                                                                                                                                                                                                                                                                     | Under review ? dataset may not be public                                                                                                                                          | 
| Department of Sanitation (DSNY)                       | Resource Utilization                          | Actual number of personnel assigned to Cleaning and Collection functions, by Sanitation District, date, and function. Also number of personnel not available by category and personnel detached to/attached from other districts.                                                                                                                                                                                | Under review ? dataset may not be public                                                                                                                                          | 
| NYC School Construction Authority (SCA)               | MWBE Vendors                                  | List of MWBE certified vendors.                                                                                                                                                                                                                                                                                                                                                                                  | Data is included in "Prequalified Firms" dataset                                                                                                                                  | 
| Department of Citywide Administrative Services (DCAS) | 100 Year Association - College Scholar Award  | The Hundred Year Association of New York honors outstanding civil servants and provides college scholarships for the children of City employees.                                                                                                                                                                                                                                                                 | Under review ? this dataset may not qualify as data                                                                                                                               | 
| Department of Consumer Affairs (DCA)                  | Consumer Restitution Awarded through Tribunal | Restitution awarded to consumers via settlements and decisions.                                                                                                                                                                                                                                                                                                                                                  | This data will be reported as part of the OATH Health and Consumer Case dataset when DCA disbands its tribunal and begins to file its cases at OATH for either hearings or trials | 
| Department of Consumer Affairs (DCA)                  | Case Workflow                                 | Status of cases in DCA's Administrative Tribunal.                                                                                                                                                                                                                                                                                                                                                                | This data will be reported as part of the OATH Health and Consumer Case dataset when DCA disbands its tribunal and begins to file its cases at OATH for either hearings or trials | 
| Department of Consumer Affairs (DCA)                  | Licensing Fees Rate Table                     | Fee table for DCA license applications.                                                                                                                                                                                                                                                                                                                                                                          | Data does not exist                                                                                                                                                               | 
```