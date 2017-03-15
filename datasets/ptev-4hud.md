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
series e:ptev-4hud d:2017-01-09T00:00:00.000Z t:business_name="PEYKO TZENOV" t:zip=10467 t:license_type=Business t:status=Issued t:application_category=Special t:license_number=1294131-DCA t:street="RESERVOIR OVAL E" t:contact_phone=9178047161 t:license_category="Home Improvement Contractor" t:state=NY t:building_number=3280 t:application_id=1066-2017-RHIC t:application_or_renewal=Renewal t:city=BRONX m:row_number.ptev-4hud=1

series e:ptev-4hud d:2016-12-28T00:00:00.000Z t:business_name="T-MOBILE NORTHEAST LLC" t:zip=11201 t:license_type=Business t:status=Issued t:application_category=Basic t:license_number=2010590-DCA t:street="FULTON ST" t:contact_phone=8009279801 t:license_category="Electronics Store" t:state=NY t:building_number=435 t:application_id=33312-2016-RELE t:application_or_renewal=Renewal t:city=BROOKLYN m:row_number.ptev-4hud=2

series e:ptev-4hud d:2016-12-31T00:00:00.000Z t:business_name="LUCAS ELECTRONICS INC" t:zip=11222 t:license_type=Business t:status=Issued t:application_category=Basic t:license_number=2025971-DCA t:street="MANHATTAN AVE" t:contact_phone=347-987-3235 t:license_category="Electronics Store" t:state=NY t:building_number=886 t:application_id=33701-2016-RELE t:application_or_renewal=Renewal t:city=BROOKLYN m:row_number.ptev-4hud=3
```

## Meta Commands

```ls
metric m:row_number.ptev-4hud p:long l:"Row Number"

entity e:ptev-4hud l:"License Applications" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/ptev-4hud

property e:ptev-4hud t:meta.view v:id=ptev-4hud v:category=Business v:averageRating=0 v:name="License Applications" v:attribution="Department of Consumer Affairs (DCA)"

property e:ptev-4hud t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:ptev-4hud t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```