# Water Withdrawals by Facility: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-withdrawals-by-facility-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/94ue-tysy) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/94ue-tysy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/94ue-tysy/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 94ue-tysy |
| Name | Water Withdrawals by Facility: Beginning 2009 |
| Attribution | New York State Department of Environmental Conservationn(DEC) |
| Category | Energy & Environment |
| Tags | water withdrawal, public water supply, water conservation |
| Created | 2014-12-05T20:02:17Z |
| Publication Date | 2016-11-28T23:21:42Z |

## Description

Data regarding water withdrawals is collected by New York State Department of Environmental Conservation (DEC).  The reporting requirements have expanded since collection began in 1990. Data is currently collected in accordance with the requirements of ECL 15-1501. ECL 15-1501 requires a DEC permit and annual usage reporting for all facilities using water for any purpose and having the capacity to withdraw 100,000 gallons or more per day of surface or groundwater. These facilities may or may not be permitted with other agencies that regulate water supplies in New York State.  This dataset begins with 2009 data and includes facility name, town, county and withdrawal information.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================== | ============================ | ========= | =========== |
| Yes      | series tag     | program_id                 | Program ID                   | text      | text        |
| Yes      | series tag     | facility_name              | Facility Name                | text      | text        |
| Yes      | series tag     | town                       | Town                         | text      | text        |
| Yes      | series tag     | county                     | County                       | text      | text        |
| Yes      | series tag     | withdrawal_category        | Withdrawal Category          | text      | text        |
| Yes      | series tag     | withdrawal_type            | Withdrawal Type              | text      | text        |
| Yes      | time           | reporting_year             | Reporting Year               | number    | number      |
| Yes      | numeric metric | average_day_withdrawal_mgd | Average Day Withdrawal (MGD) | number    | number      |
| Yes      | numeric metric | maximum_day_withdrawal_mgd | Maximum Day Withdrawal (MGD) | number    | number      |
| Yes      | numeric metric | easting                    | Easting                      | number    | number      |
| Yes      | numeric metric | northing                   | Northing                     | number    | number      |
```

## Time Field

```ls
Value = reporting_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:94ue-tysy d:2009-01-01T00:00:00.000Z t:facility_name="59th Street Steam Station" t:county="New York" t:withdrawal_category="Power - Fossil Fuel" t:withdrawal_type="Surface Water" t:town="New York (T)" t:program_id=WWR0000002 m:average_day_withdrawal_mgd=2.38 m:maximum_day_withdrawal_mgd=2.59 m:northing=4513964 m:easting=584930

series e:94ue-tysy d:2010-01-01T00:00:00.000Z t:facility_name="59th Street Steam Station" t:county="New York" t:withdrawal_category="Power - Fossil Fuel" t:withdrawal_type="Surface Water" t:town="New York (T)" t:program_id=WWR0000002 m:average_day_withdrawal_mgd=2.64 m:maximum_day_withdrawal_mgd=2.59 m:northing=4513964 m:easting=584930

series e:94ue-tysy d:2011-01-01T00:00:00.000Z t:facility_name="59th Street Steam Station" t:county="New York" t:withdrawal_category="Power - Fossil Fuel" t:withdrawal_type="Surface Water" t:town="New York (T)" t:program_id=WWR0000002 m:average_day_withdrawal_mgd=3.92 m:maximum_day_withdrawal_mgd=4.3 m:northing=4513964 m:easting=584930
```

## Meta Commands

```ls
metric m:average_day_withdrawal_mgd p:double l:"Average Day Withdrawal (MGD)" d:"Average daily withdrawal in millions of gallons per day (MGD). Blank indicates the value was not reported. Zero (0) indicates a zero value was reported." t:dataTypeName=number

metric m:maximum_day_withdrawal_mgd p:double l:"Maximum Day Withdrawal (MGD)" d:"Largest single day withdrawal rate of the source during the reporting year in millions of gallons per day (MGD). Blank indicates the value was not reported. Zero (0) indicates a zero value was reported." t:dataTypeName=number

metric m:easting p:integer l:Easting d:"NAD83 UTM Zone 18N (geographic Cartesian coordinates for location)" t:dataTypeName=number

metric m:northing p:integer l:Northing d:"NAD83 UTM Zone 18N (geographic Cartesian coordinates for location)" t:dataTypeName=number

entity e:94ue-tysy l:"Water Withdrawals by Facility:  Beginning 2009" t:attribution="New York State Department of Environmental Conservationn(DEC)" t:url=https://data.ny.gov/api/views/94ue-tysy

property e:94ue-tysy t:meta.view v:id=94ue-tysy v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/lands/55509.html v:averageRating=0 v:name="Water Withdrawals by Facility:  Beginning 2009" v:attribution="New York State Department of Environmental Conservationn(DEC)"

property e:94ue-tysy t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:94ue-tysy t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:94ue-tysy t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| program_id | facility_name             | town         | county   | withdrawal_category | withdrawal_type | reporting_year | average_day_withdrawal_mgd | maximum_day_withdrawal_mgd | easting | northing | 
| ========== | ========================= | ============ | ======== | =================== | =============== | ============== | ========================== | ========================== | ======= | ======== | 
| WWR0000002 | 59th Street Steam Station | New York (T) | New York | Power - Fossil Fuel | Surface Water   | 2009           | 2.38                       | 2.59                       | 584930  | 4513964  | 
| WWR0000002 | 59th Street Steam Station | New York (T) | New York | Power - Fossil Fuel | Surface Water   | 2010           | 2.64                       | 2.59                       | 584930  | 4513964  | 
| WWR0000002 | 59th Street Steam Station | New York (T) | New York | Power - Fossil Fuel | Surface Water   | 2011           | 3.92                       | 4.3                        | 584930  | 4513964  | 
| WWR0000002 | 59th Street Steam Station | New York (T) | New York | Power - Fossil Fuel | Surface Water   | 2012           | 3.21                       | 4.3                        | 584930  | 4513964  | 
| WWR0000002 | 59th Street Steam Station | New York (T) | New York | Power - Fossil Fuel | Surface Water   | 2013           | 3.14                       | 4.32                       | 584930  | 4513964  | 
| WWR0000002 | 59th Street Steam Station | New York (T) | New York | Power - Fossil Fuel | Surface Water   | 2014           | 4.32                       | 4.32                       | 584930  | 4513964  | 
| WWR0000002 | 59th Street Steam Station | New York (T) | New York | Power - Fossil Fuel | Surface Water   | 2015           | 4.32                       | 4.32                       | 584930  | 4513964  | 
| WWR0000003 | A Zimmerman & Son         | Lloyd (T)    | Ulster   | Agricultural        | Surface Water   | 2011           |                            |                            | 578367  | 4618651  | 
| WWR0000003 | A Zimmerman & Son         | Lloyd (T)    | Ulster   | Agricultural        | Surface Water   | 2012           |                            |                            | 578367  | 4618651  | 
| WWR0000003 | A Zimmerman & Son         | Lloyd (T)    | Ulster   | Agricultural        | Surface Water   | 2015           | 0                          |                            | 578367  | 4618651  | 
```