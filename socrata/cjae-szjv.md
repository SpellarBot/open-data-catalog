# Air Quality Measures on the National Environmental Health Tracking Network

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/air-quality-measures-on-the-national-environmental-health-tracking-network) |
| Metadata | [Link](https://data.cdc.gov/api/views/cjae-szjv) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/cjae-szjv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/cjae-szjv/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | cjae-szjv |
| Name | Air Quality Measures on the National Environmental Health Tracking Network |
| Tags | environmental hazard, air quality, air quality system, daily maximum 8 hour average concentration, daily 24 hour average concentration, hourly observations, site monitoring data, regulatory resour... |
| Created | 2015-08-12T12:10:33Z |
| Publication Date | 2015-08-13T14:09:10Z |

## Description

The Environmental Protection Agency (EPA) provides air pollution data about ozone and particulate matter (PM2.5) to CDC for the Tracking Network. The EPA maintains a database called the Air Quality System (AQS) which contains data from approximately 4,000 monitoring stations around the country, mainly in urban areas. Data from the AQS is considered the "gold standard" for determining outdoor air pollution. However, AQS data are limited because the monitoring stations are usually in urban areas or cities and because they only take air samples for some air pollutants every three days or during times of the year when air pollution is very high. CDC and EPA have worked together to develop a statistical model (Downscaler) to make modeled predictions available for environmental public health tracking purposes in areas of the country that do not have monitors and to fill in the time gaps when monitors may not be recording data. This data does not include "Percent of population in counties exceeding NAAQS (vs. population in counties that either meet the standard or do not monitor PM2.5)". Please visit the Tracking homepage for this information.View additional information for indicator definitions and documentation by selecting Content Area "Air Quality" and the respective indicator at the following website: http://ephtracking.cdc.gov/showIndicatorsData.action

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | measureid           | MeasureId           | text      | number      |
| Yes      | series tag     | measurename         | MeasureName         | text      | text        |
| Yes      | series tag     | measuretype         | MeasureType         | text      | text        |
| Yes      | series tag     | stratificationlevel | StratificationLevel | text      | text        |
| Yes      | series tag     | statefips           | StateFips           | text      | text        |
| Yes      | series tag     | statename           | StateName           | text      | text        |
| Yes      | series tag     | countyfips          | CountyFips          | text      | text        |
| Yes      | series tag     | countyname          | CountyName          | text      | text        |
| Yes      | time           | reportyear          | ReportYear          | number    | text        |
| Yes      | numeric metric | value               | Value               | number    | number      |
| Yes      | series tag     | unit                | Unit                | text      | text        |
| Yes      | series tag     | unitname            | UnitName            | text      | text        |
| Yes      | series tag     | dataorigin          | DataOrigin          | text      | text        |
| Yes      | numeric metric | monitoronly         | MonitorOnly         | number    | number      |
```

## Time Field

```ls
Value = reportyear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cjae-szjv d:1999-01-01T00:00:00.000Z t:unit="No Units" t:measurename="Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard" t:countyname=Elmore t:countyfips=1051 t:dataorigin="Monitor Only" t:unitname="No Units" t:measureid=83 t:statefips=1 t:measuretype=Counts t:statename=Alabama t:stratificationlevel="State x County" m:value=5 m:monitoronly=1

series e:cjae-szjv d:1999-01-01T00:00:00.000Z t:unit="No Units" t:measurename="Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard" t:countyname=Jefferson t:countyfips=1073 t:dataorigin="Monitor Only" t:unitname="No Units" t:measureid=83 t:statefips=1 t:measuretype=Counts t:statename=Alabama t:stratificationlevel="State x County" m:value=39 m:monitoronly=1

series e:cjae-szjv d:1999-01-01T00:00:00.000Z t:unit="No Units" t:measurename="Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard" t:countyname=Lawrence t:countyfips=1079 t:dataorigin="Monitor Only" t:unitname="No Units" t:measureid=83 t:statefips=1 t:measuretype=Counts t:statename=Alabama t:stratificationlevel="State x County" m:value=28 m:monitoronly=1
```

## Meta Commands

```ls
metric m:value p:double l:Value d:"Data value specific to data measure in the stratified geography" t:dataTypeName=number

metric m:monitoronly p:integer l:MonitorOnly d:"Flags if data is Monitor only, compared to monitor and modeled data." t:dataTypeName=number

entity e:cjae-szjv l:"Air Quality Measures on the National Environmental Health Tracking Network" t:url=https://data.cdc.gov/api/views/cjae-szjv

property e:cjae-szjv t:meta.view v:id=cjae-szjv v:averageRating=0 v:name="Air Quality Measures on the National Environmental Health Tracking Network"

property e:cjae-szjv t:meta.view.owner v:id=94g5-7as2 v:screenName=Tracking v:displayName=Tracking

property e:cjae-szjv t:meta.view.tableauthor v:id=94g5-7as2 v:screenName=Tracking v:roleName=publisher v:displayName=Tracking

property e:cjae-szjv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cak8@cdc.gov v:Publisher="Environmental Health Tracking Network" v:Homepage=http://ephtracking.cdc.gov/ v:Is_Quality_Data=yes v:Contact_Name="Craig Kassinger" v:Bureau_Code=009:20 v:Language=English v:Update_Frequency=irregular v:Program_Code=009:032
```

## Top Records

```ls
| measureid | measurename                                                                                                   | measuretype | stratificationlevel | statefips | statename | countyfips | countyname | reportyear | value | unit     | unitname | dataorigin   | monitoronly | 
| ========= | ============================================================================================================= | =========== | =================== | ========= | ========= | ========== | ========== | ========== | ===== | ======== | ======== | ============ | =========== | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 1         | Alabama   | 1051       | Elmore     | 1999       | 5     | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 1         | Alabama   | 1073       | Jefferson  | 1999       | 39    | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 1         | Alabama   | 1079       | Lawrence   | 1999       | 28    | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 1         | Alabama   | 1089       | Madison    | 1999       | 31    | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 1         | Alabama   | 1097       | Mobile     | 1999       | 32    | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 1         | Alabama   | 1101       | Montgomery | 1999       | 15    | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 1         | Alabama   | 1117       | Shelby     | 1999       | 45    | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 1         | Alabama   | 1119       | Sumter     | 1999       | 3     | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 2         | Alaska    | 2068       | Denali     | 1999       | 0     | No Units | No Units | Monitor Only | 1           | 
| 83        | Number of days with maximum 8-hour average ozone concentration over the National Ambient Air Quality Standard | Counts      | State x County      | 4         | Arizona   | 4003       | Cochise    | 1999       | 1     | No Units | No Units | Monitor Only | 1           | 
```