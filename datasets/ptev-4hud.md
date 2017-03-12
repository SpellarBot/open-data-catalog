# License Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/license-applications) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ptev-4hud) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ptev-4hud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ptev-4hud/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ptev-4hud |
| Name | License Applications |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | Business |
| Tags | city government, business, dca, department of consumer affairs, license, application |
| Created | 2016-01-26T14:50:15Z |
| Publication Date | 2016-02-08T16:50:47Z |
| Rows Updated | 2017-03-10T19:52:34Z |

## Description

This data set features license applications received during the last and current calendar years, including applications where a license was issued, denied, withdrawn, or remains pending. For a list of legally operating businesses, please refer to the DCA ? Legally Operating Businesses data set. This data set is updated on a weekly basis.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag  | application_id            | Application ID            | text          | text          |
| Yes      | series tag  | license_number            | License Number            | text          | text          |
| Yes      | series tag  | license_type              | License Type              | text          | text          |
| Yes      | series tag  | application_or_renewal    | Application or Renewal    | text          | text          |
| Yes      | series tag  | business_name             | Business Name             | text          | text          |
| Yes      | series tag  | status                    | Status                    | text          | text          |
| Yes      | time        | start_date                | Start Date                | calendar_date | calendar_date |
| No       |             | end_date                  | End Date                  | calendar_date | calendar_date |
| Yes      | series tag  | temp_op_letter_issued     | Temp Op Letter Issued     | text          | text          |
| Yes      | series tag  | temp_op_letter_expiration | Temp Op Letter Expiration | text          | text          |
| Yes      | series tag  | license_category          | License Category          | text          | text          |
| Yes      | series tag  | application_category      | Application Category      | text          | text          |
| Yes      | series tag  | building_number           | Building Number           | text          | text          |
| Yes      | series tag  | street                    | Street                    | text          | text          |
| Yes      | series tag  | street_2                  | Street 2                  | text          | text          |
| Yes      | series tag  | unit_type                 | Unit Type                 | text          | text          |
| Yes      | series tag  | unit                      | Unit                      | text          | text          |
| Yes      | series tag  | description               | Description               | text          | text          |
| Yes      | series tag  | city                      | City                      | text          | text          |
| Yes      | series tag  | state                     | State                     | text          | text          |
| Yes      | series tag  | zip                       | Zip                       | text          | text          |
| Yes      | series tag  | contact_phone             | Contact Phone             | text          | text          |
| No       |             | longitude                 | Longitude                 | number        | number        |
| No       |             | latitude                  | Latitude                  | number        | number        |
| Yes      | series tag  | active_vehicles           | Active Vehicles           | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,longitude,latitude
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:ptev-4hud l:"License Applications" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/ptev-4hud

property e:ptev-4hud t:meta.view v:id=ptev-4hud v:category=Business v:averageRating=0 v:name="License Applications" v:attribution="Department of Consumer Affairs (DCA)"

property e:ptev-4hud t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:ptev-4hud t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```