# Campaign Finance Data - Committee Purpose

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-data-committee-purpose) |
| Metadata | [Link](https://data.austintexas.gov/api/views/u3cd-iecr) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/u3cd-iecr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/u3cd-iecr/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | u3cd-iecr |
| Name | Campaign Finance Data - Committee Purpose |
| Attribution | Office of the City Clerk |
| Category | Financial |
| Created | 2016-07-08T22:00:36Z |
| Publication Date | 2016-07-18T23:54:26Z |

## Description

If a political committee has supported, opposed, or assisted a candidate, officeholder, or ballot measure during the reporting period, this activity will be reported in the Committee Purpose Dataset.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | report              | Report              | text          | text          |
| Yes      | series tag  | purpose_id          | Purpose_ID          | text          | text          |
| Yes      | series tag  | committee_purp_id   | Committee_Purp_ID   | text          | text          |
| Yes      | series tag  | filer_name          | Filer_Name          | text          | text          |
| Yes      | series tag  | link_to_report      | View_Report         | url           | url           |
| Yes      | series tag  | cor_flag            | COR_Flag            | text          | text          |
| Yes      | series tag  | committee_activity  | Committee_Activity  | text          | text          |
| Yes      | series tag  | purpose_type        | Purpose_Type        | text          | text          |
| Yes      | series tag  | recipient           | Recipient           | text          | text          |
| Yes      | series tag  | office_held         | Office_Held         | text          | text          |
| Yes      | series tag  | office_sought       | Office_Sought       | text          | text          |
| Yes      | time        | election_date       | Election_Date       | calendar_date | calendar_date |
| Yes      | series tag  | measure_description | Measure_Description | text          | text          |
```

## Time Field

```ls
Value = election_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:u3cd-iecr d:2014-11-04T00:00:00.000Z t:filer_name="DeRail Austin" t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258013" t:committee_purp_id=R20160715112612-CP0001 t:purpose_type=MEASURE t:report=R20160715112612 t:measure_description="rail bond" t:purpose_id=CP0001 t:committee_activity=Oppose t:recipient="Proposition 1" m:row_number.u3cd-iecr=1

series e:u3cd-iecr d:2016-03-01T00:00:00.000Z t:filer_name="Stonewall Democrats of Austin" t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258187" t:committee_purp_id=R20160715174520-CP0001 t:purpose_type=MEASURE t:report=R20160715174520 t:measure_description="Fingerprint requirements for TNCs" t:purpose_id=CP0001 t:committee_activity=Oppose t:recipient="Proposition 1" m:row_number.u3cd-iecr=2

series e:u3cd-iecr d:2016-03-01T00:00:00.000Z t:filer_name="Stonewall Democrats of Austin" t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258187" t:committee_purp_id=R20160715174520-CP0002 t:purpose_type=COH t:office_sought="State Representative" t:report=R20160715174520 t:office_held="State Representative" t:purpose_id=CP0002 t:committee_activity=Support t:recipient="Israel, Celia" m:row_number.u3cd-iecr=3
```

## Meta Commands

```ls
metric m:row_number.u3cd-iecr p:long l:"Row Number"

entity e:u3cd-iecr l:"Campaign Finance Data - Committee Purpose" t:attribution="Office of the City Clerk" t:url=https://data.austintexas.gov/api/views/u3cd-iecr

property e:u3cd-iecr t:meta.view v:id=u3cd-iecr v:category=Financial v:averageRating=0 v:name="Campaign Finance Data - Committee Purpose" v:attribution="Office of the City Clerk"

property e:u3cd-iecr t:meta.view.owner v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:displayName="Kathryn Darnall"

property e:u3cd-iecr t:meta.view.tableauthor v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```

## Top Records

```ls
| report          | purpose_id | committee_purp_id      | filer_name                    | link_to_report                                                         | cor_flag | committee_activity | purpose_type | recipient             | office_held          | office_sought         | election_date       | measure_description               | 
| =============== | ========== | ====================== | ============================= | ====================================================================== | ======== | ================== | ============ | ===================== | ==================== | ===================== | =================== | ================================= | 
| R20160715112612 | CP0001     | R20160715112612-CP0001 | DeRail Austin                 | [http://www.austintexas.gov/edims/document.cfm?id=258013, View Report] |          | Oppose             | MEASURE      | Proposition 1         |                      |                       | 2014-11-04T00:00:00 | rail bond                         | 
| R20160715174520 | CP0001     | R20160715174520-CP0001 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Oppose             | MEASURE      | Proposition 1         |                      |                       | 2016-03-01T00:00:00 | Fingerprint requirements for TNCs | 
| R20160715174520 | CP0002     | R20160715174520-CP0002 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Support            | COH          | Israel, Celia         | State Representative | State Representative  | 2016-03-01T00:00:00 |                                   | 
| R20160715174520 | CP0003     | R20160715174520-CP0003 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Support            | COH          | Fischer, Huey         |                      | State Representative  | 2016-03-01T00:00:00 |                                   | 
| R20160715174520 | CP0004     | R20160715174520-CP0004 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Support            | COH          | Lloyd, Doggett        | Congress - CD35      | Congress - CD35       | 2016-03-01T00:00:00 |                                   | 
| R20160715174520 | CP0005     | R20160715174520-CP0005 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Support            | COH          | Gallaher, Scot        |                      | Congress - CD10       | 2016-03-01T00:00:00 |                                   | 
| R20160715174520 | CP0006     | R20160715174520-CP0006 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Support            | COH          | Matta, William        |                      | Congress - CD17       | 2016-03-01T00:00:00 |                                   | 
| R20160715174520 | CP0007     | R20160715174520-CP0007 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Support            | COH          | Burnam, Lon           |                      | Railroad Commissioner | 2016-03-01T00:00:00 |                                   | 
| R20160715174520 | CP0008     | R20160715174520-CP0008 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Support            | COH          | Bell-Meterau, Rebecca |                      | SBOE 5                | 2016-03-01T00:00:00 |                                   | 
| R20160715174520 | CP0009     | R20160715174520-CP0009 | Stonewall Democrats of Austin | [http://www.austintexas.gov/edims/document.cfm?id=258187, View Report] |          | Support            | COH          | Jennings, Judy        |                      | SBOE 10               | 2016-03-01T00:00:00 |                                   | 
```