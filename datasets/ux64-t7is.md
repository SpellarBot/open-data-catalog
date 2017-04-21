# Austin Water - Active Permitted Industrial Users

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-active-permitted-industrial-users) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ux64-t7is) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ux64-t7is/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ux64-t7is/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ux64-t7is |
| Name | Austin Water - Active Permitted Industrial Users |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, permitted, wastewater, industrial waste |
| Created | 2015-08-14T20:17:45Z |
| Publication Date | 2015-08-14T20:20:22Z |

## Description

List of active permitted Industrial Users (IU) of the Austin Water Utility's sanitary sewer system under the Industrial Waste Control/Pretreatement Program.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | business_name   | BUSINESS_NAME   | text      | text        |
| No       |             | service_address | SERVICE_ADDRESS | text      | text        |
| Yes      | series tag  | permit_number   | PERMIT_NUMBER   | text      | text        |
| Yes      | series tag  | permit_type     | PERMIT_TYPE     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = service_address
```

## Data Commands

```ls
series e:ux64-t7is d:2015-08-14T13:17:47.000Z t:business_name="10001 S IH 35 INVESTMENTS (RETAIL BLDG 2)" t:permit_type=General t:permit_number=747AUS0003071 m:row_number.ux64-t7is=1

series e:ux64-t7is d:2015-08-14T13:17:47.000Z t:business_name="112 ACADEMY LLC (HOTEL ST. CECILIA)" t:permit_type=General t:permit_number=704AUS0003128 m:row_number.ux64-t7is=2

series e:ux64-t7is d:2015-08-14T13:17:47.000Z t:business_name="1123 CONGRESS LLP (DOC'S MOTORWORKS BAR & GRILL)" t:permit_type=General t:permit_number=704AUS0000002 m:row_number.ux64-t7is=3
```

## Meta Commands

```ls
metric m:row_number.ux64-t7is p:long l:"Row Number"

entity e:ux64-t7is l:"Austin Water - Active Permitted Industrial Users" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/ux64-t7is

property e:ux64-t7is t:meta.view v:id=ux64-t7is v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - Active Permitted Industrial Users" v:attribution="Austin Water"

property e:ux64-t7is t:meta.view.license v:name="Public Domain"

property e:ux64-t7is t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:ux64-t7is t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| :updated_at | business_name                                    | service_address                    | permit_number | permit_type | 
| =========== | ================================================ | ================================== | ============= | =========== | 
| 1439558267  | 10001 S IH 35 INVESTMENTS (RETAIL BLDG 2)        | 10001 S IH 35 SVRD NB BLDG 2 78747 | 747AUS0003071 | General     | 
| 1439558267  | 112 ACADEMY LLC (HOTEL ST. CECILIA)              | 112 ACADEMY DR 78704               | 704AUS0003128 | General     | 
| 1439558267  | 1123 CONGRESS LLP (DOC'S MOTORWORKS BAR & GRILL) | 1123 S CONGRESS AVE 78704          | 704AUS0000002 | General     | 
| 1439558267  | 11301 LAKELINE LP (BUILDING #11)                 | 11301 LAKELINE BLVD BLDG 11 78717  | 717AUS0000007 | General     | 
| 1439558267  | 11301 LAKELINE LP (BUILDING #12)                 | 11301 LAKELINE BLVD BLDG 12 78717  | 717AUS0000005 | General     | 
| 1439558267  | 11301 LAKELINE LP (BUILDING #4)                  | 11301 LAKELINE BLVD BLDG 4 78717   | 717AUS0000006 | General     | 
| 1439558267  | 1135 GUNTER LLC (AUSTIN CAB COMPANY)             | 1135 GUNTER ST UNIT 2 78702        | 702AUS0001436 | General     | 
| 1439558267  | 1219 S LAMAR VENTURE LLC (ODD DUCK)              | 1201 S LAMAR BLVD 78704            | 704AUS0003664 | General     | 
| 1439558267  | 1315 WEST LLC (WINFLO OSTERIA)                   | 1315 W 6TH ST BLDG B 78703         | 703AUS0003359 | General     | 
| 1439558267  | 1417 SOUTH 1ST LLC (SWAY)                        | 1417 S 1ST ST 78704                | 704AUS0003401 | General     | 
```