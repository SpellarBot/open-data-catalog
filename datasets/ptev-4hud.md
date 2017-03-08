# License Applications

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/ptev-4hud/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/license-applications)
* [Metadata URL](https://data.cityofnewyork.us/api/views/ptev-4hud)
* Id = ptev-4hud
* Name = License Applications
* Attribution = Department of Consumer Affairs (DCA)
* Category = Business
* Tags = [city government, business, dca, department of consumer affairs, license, application]
* Created = 2016-01-26T14:50:15Z
* Publication Date = 2016-02-08T16:50:47Z
* Rows Updated = 2017-03-03T19:52:30Z

## Description

This data set features license applications received during the last and current calendar years, including applications where a license was issued, denied, withdrawn, or remains pending. For a list of legally operating businesses, please refer to the DCA ? Legally Operating Businesses data set. This data set is updated on a weekly basis.

## Columns

```ls
| Name                      | Field Name                | Data Type     | Render Type   | Schema Type | Included | 
| ========================= | ========================= | ============= | ============= | =========== | ======== | 
| Application ID            | application_id            | text          | text          | series tag  | Yes      | 
| License Number            | license_number            | text          | text          | series tag  | Yes      | 
| License Type              | license_type              | text          | text          | series tag  | Yes      | 
| Application or Renewal    | application_or_renewal    | text          | text          | series tag  | Yes      | 
| Business Name             | business_name             | text          | text          | series tag  | Yes      | 
| Status                    | status                    | text          | text          | series tag  | Yes      | 
| Start Date                | start_date                | calendar_date | calendar_date | time        | Yes      | 
| End Date                  | end_date                  | calendar_date | calendar_date |             | No       | 
| Temp Op Letter Issued     | temp_op_letter_issued     | text          | text          | series tag  | Yes      | 
| Temp Op Letter Expiration | temp_op_letter_expiration | text          | text          | series tag  | Yes      | 
| License Category          | license_category          | text          | text          | series tag  | Yes      | 
| Application Category      | application_category      | text          | text          | series tag  | Yes      | 
| Building Number           | building_number           | text          | text          | series tag  | Yes      | 
| Street                    | street                    | text          | text          | series tag  | Yes      | 
| Street 2                  | street_2                  | text          | text          | series tag  | Yes      | 
| Unit Type                 | unit_type                 | text          | text          | series tag  | Yes      | 
| Unit                      | unit                      | text          | text          | series tag  | Yes      | 
| Description               | description               | text          | text          | series tag  | Yes      | 
| City                      | city                      | text          | text          | series tag  | Yes      | 
| State                     | state                     | text          | text          | series tag  | Yes      | 
| Zip                       | zip                       | text          | text          | series tag  | Yes      | 
| Contact Phone             | contact_phone             | text          | text          | series tag  | Yes      | 
| Longitude                 | longitude                 | number        | number        |             | No       | 
| Latitude                  | latitude                  | number        | number        |             | No       | 
| Active Vehicles           | active_vehicles           | text          | text          | series tag  | Yes      | 
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = end_date,longitude,latitude
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:ptev-4hud l:"License Applications" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/ptev-4hud

property e:ptev-4hud t:meta.view d:2017-03-07T17:28:20.195Z v:id=ptev-4hud v:category=Business v:averageRating=0 v:name="License Applications" v:attribution="Department of Consumer Affairs (DCA)"

property e:ptev-4hud t:meta.view.owner d:2017-03-07T17:28:20.195Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:ptev-4hud t:meta.view.tableauthor d:2017-03-07T17:28:20.195Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```