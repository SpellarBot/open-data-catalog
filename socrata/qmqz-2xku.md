# Beach Water Quality - Automated Sensors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/beach-water-quality-automated-sensors-66a4b) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/qmqz-2xku) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/qmqz-2xku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/qmqz-2xku/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | qmqz-2xku |
| Name | Beach Water Quality - Automated Sensors |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | beaches, parks, chicago park district, open spaces, parks & recreation, recreation, water |
| Created | 2014-05-15T18:14:02Z |
| Publication Date | 2015-06-04T20:37:41Z |

## Description

The Chicago Park District maintains sensors in the water at beaches along Chicago's Lake Michigan lakefront. These sensors generally capture the indicated measurements hourly while the sensors are in operation during the summer.  During other seasons and at some other times, information from the sensors may not be available.  See https://data.cityofchicago.org/d/k7hf-8y75 for a dataset with land-based weather measurements at selected beaches.  The sensor locations are listed at https://data.cityofchicago.org/d/g3ip-u8rb.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | beach_name                  | Beach Name                  | text          | text          |
| Yes      | time           | measurement_timestamp       | Measurement Timestamp       | calendar_date | calendar_date |
| Yes      | numeric metric | water_temperature           | Water Temperature           | number        | number        |
| Yes      | numeric metric | turbidity                   | Turbidity                   | number        | number        |
| Yes      | numeric metric | transducer_depth            | Transducer Depth            | number        | number        |
| Yes      | numeric metric | wave_height                 | Wave Height                 | number        | number        |
| Yes      | numeric metric | wave_period                 | Wave Period                 | number        | number        |
| Yes      | numeric metric | battery_life                | Battery Life                | number        | number        |
| No       |                | measurement_timestamp_label | Measurement Timestamp Label | text          | text          |
| No       |                | measurement_id              | Measurement ID              | text          | text          |
```

## Time Field

```ls
Value = measurement_timestamp
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = measurement_timestamp_label,measurement_id
```

## Data Commands

```ls
series e:qmqz-2xku d:2013-08-30T08:00:00.000Z t:beach_name="Montrose Beach" m:transducer_depth=0.891 m:water_temperature=20.3 m:turbidity=1.18 m:wave_period=3 m:wave_height=0.08 m:battery_life=9.4

series e:qmqz-2xku d:2016-05-26T13:00:00.000Z t:beach_name="Ohio Street Beach" m:water_temperature=14.4 m:turbidity=1.23 m:wave_period=4 m:wave_height=0.111 m:battery_life=12.4

series e:qmqz-2xku d:2013-09-03T16:00:00.000Z t:beach_name="Calumet Beach" m:transducer_depth=1.201 m:water_temperature=23.2 m:turbidity=3.63 m:wave_period=6 m:wave_height=0.174 m:battery_life=9.4
```

## Meta Commands

```ls
metric m:water_temperature p:float l:"Water Temperature" d:"Water temperature in Celsius degrees." t:dataTypeName=number

metric m:turbidity p:float l:Turbidity d:"Water turbidity in Nephelometric Turbidity Units (NTU)," t:dataTypeName=number

metric m:transducer_depth p:float l:"Transducer Depth" d:"Transducer depth in meters." t:dataTypeName=number

metric m:wave_height p:float l:"Wave Height" d:"Wave height in meters." t:dataTypeName=number

metric m:wave_period p:float l:"Wave Period" d:"Wave period in seconds." t:dataTypeName=number

metric m:battery_life p:float l:"Battery Life" d:"Battery voltage, an indicator of remaining battery life used by the Chicago Park District to know when batteries should be replaced." t:dataTypeName=number

entity e:qmqz-2xku l:"Beach Water Quality - Automated Sensors" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/qmqz-2xku

property e:qmqz-2xku t:meta.view v:id=qmqz-2xku v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com v:averageRating=0 v:name="Beach Water Quality - Automated Sensors" v:attribution="Chicago Park District"

property e:qmqz-2xku t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:qmqz-2xku t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| beach_name        | measurement_timestamp | water_temperature | turbidity | transducer_depth | wave_height | wave_period | battery_life | measurement_timestamp_label | measurement_id              | 
| ================= | ===================== | ================= | ========= | ================ | =========== | =========== | ============ | =========================== | =========================== | 
| Montrose Beach    | 2013-08-30T08:00:00   | 20.3              | 1.18      | 0.891            | 0.08        | 3           | 9.4          | 8/30/2013 8:00 AM           | MontroseBeach201308300800   | 
| Ohio Street Beach | 2016-05-26T13:00:00   | 14.4              | 1.23      |                  | 0.111       | 4.0         | 12.4         | 05/26/2016 1:00 PM          | OhioStreetBeach201605261300 | 
| Calumet Beach     | 2013-09-03T16:00:00   | 23.2              | 3.63      | 1.201            | 0.174       | 6           | 9.4          | 9/3/2013 4:00 PM            | CalumetBeach201309031600    | 
| Calumet Beach     | 2014-05-28T12:00:00   | 16.2              | 1.26      | 1.514            | 0.147       | 4           | 11.7         | 5/28/2014 12:00 PM          | CalumetBeach201405281200    | 
| Montrose Beach    | 2014-05-28T12:00:00   | 14.4              | 3.36      | 1.388            | 0.298       | 4           | 11.9         | 5/28/2014 12:00 PM          | MontroseBeach201405281200   | 
| Montrose Beach    | 2014-05-28T13:00:00   | 14.5              | 2.72      | 1.395            | 0.306       | 3           | 11.9         | 5/28/2014 1:00 PM           | MontroseBeach201405281300   | 
| Calumet Beach     | 2014-05-28T13:00:00   | 16.3              | 1.28      | 1.524            | 0.162       | 4           | 11.7         | 5/28/2014 1:00 PM           | CalumetBeach201405281300    | 
| Montrose Beach    | 2014-05-28T14:00:00   | 14.8              | 2.97      | 1.386            | 0.328       | 3           | 11.9         | 5/28/2014 2:00 PM           | MontroseBeach201405281400   | 
| Calumet Beach     | 2014-05-28T14:00:00   | 16.5              | 1.32      | 1.537            | 0.185       | 4           | 11.7         | 5/28/2014 2:00 PM           | CalumetBeach201405281400    | 
| Calumet Beach     | 2014-05-28T15:00:00   | 16.8              | 1.31      | 1.568            | 0.196       | 4           | 11.7         | 5/28/2014 3:00 PM           | CalumetBeach201405281500    | 
```