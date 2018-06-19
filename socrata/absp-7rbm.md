# Division of Water Biological Monitoring Sampling Locations: Beginning 1994

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/division-of-water-biological-monitoring-sampling-locations-beginning-1994) |
| Metadata | [Link](https://data.ny.gov/api/views/absp-7rbm) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/absp-7rbm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/absp-7rbm/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | absp-7rbm |
| Name | Division of Water Biological Monitoring Sampling Locations: Beginning 1994 |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | rivers, streams, ribs, ras, water quality assessment, macroinvertebrates |
| Created | 2015-04-03T16:27:00Z |
| Publication Date | 2016-03-17T14:51:54Z |

## Description

The Division of Water Stream Biomonitoring Unit (SBU) dataset contains the point sampling locations at which benthic macroinvertebrates, field chemistry, and at some locations, sediment, fish or diatoms have been collected as part of the Rotating Integrated Basin Studies (RIBS) program, Rapid Biological Assessments (RAS), or special studies. The data collected are used for water quality assessment (input to the Waterbody Inventory, completion of the 305(b) report and 303(d) list of impaired Waters) and for track-down of water quality problems. The data set is maintained by the Division of Water, Bureau of Water Assessment and Management, Stream Biomonitoring Unit.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | name              | Name              | text      | text        |
| Yes      | series tag     | description       | Description       | text      | text        |
| Yes      | series tag     | municipality      | Municipality      | text      | text        |
| Yes      | series tag     | county            | County            | text      | text        |
| Yes      | numeric metric | basin             | Basin             | number    | text        |
| No       |                | latitude          | Latitude          | number    | number      |
| No       |                | longitude         | Longitude         | number    | number      |
| Yes      | series tag     | huc_8             | HUC 8             | text      | text        |
| Yes      | time           | year_last_sampled | Year Last Sampled | number    | number      |
| Yes      | series tag     | status            | Status            | text      | text        |
```

## Time Field

```ls
Value = year_last_sampled
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:absp-7rbm d:2005-01-01T00:00:00.000Z t:status=Active t:county=Chautauqua t:description="At West Middle Rd bridge, just past airport" t:name="Beaver Creek" t:municipality=Dunkirk t:huc_8=04120101 m:basin=1

series e:absp-7rbm d:2005-01-01T00:00:00.000Z t:status=Active t:county=Wyoming t:description="80 m below Rte 78" t:name="Beaver Meadow Creek" t:municipality="Java Village" t:huc_8=04120103 m:basin=1

series e:absp-7rbm d:2015-01-01T00:00:00.000Z t:status=Inactive t:county=Erie t:description="10 m below Rapids Rd bridge" t:name="Beeman Creek" t:municipality=Wolcottburg t:huc_8=04120104 m:basin=1
```

## Meta Commands

```ls
metric m:basin p:integer l:Basin d:"Two-digit code of the basin in which the sampling site is located; one of the seventeen major hydrologic basins defined for New York State (parts of the basin may exist outside the state). Codes are as follows: 1: Niagara River/Lake Erie basin; 2: Allegheny River basin; 3: Lake Ontario basin; 4: Genesee River basin; 5: Chemung River basin; 6: Susquehanna River basin; 7: Seneca Oneida Onondaga Rivers basin; 8: Black River basin; 9: St. Lawrence River basin; 10: Lake Champlain basin; 11: Upper Hudson River basin; 12: Mohawk River basin; 13: Lower Hudson River basin; 14: Delaware River basin; 15: Passaic River/Newark Bay basin; 16: Housatonic River basin; 17: Atlantic Ocean Long Island Sound basin." t:dataTypeName=number

entity e:absp-7rbm l:"Division of Water Biological Monitoring Sampling Locations: Beginning 1994" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/absp-7rbm

property e:absp-7rbm t:meta.view v:id=absp-7rbm v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/23847.html v:averageRating=0 v:name="Division of Water Biological Monitoring Sampling Locations: Beginning 1994" v:attribution="New York State Department of Environmental Conservation"

property e:absp-7rbm t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:absp-7rbm t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:absp-7rbm t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| name                | description                                                 | municipality  | county      | basin | latitude | longitude | huc_8    | year_last_sampled | status   | 
| =================== | =========================================================== | ============= | =========== | ===== | ======== | ========= | ======== | ================= | ======== | 
| Beaver Creek        | At West Middle Rd bridge, just past airport                 | Dunkirk       | Chautauqua  | 1     | 42.50187 | -79.2683  | 04120101 | 2005              | Active   | 
| Beaver Meadow Creek | 80 m below Rte 78                                           | Java Village  | Wyoming     | 1     | 42.67204 | -78.43686 | 04120103 | 2005              | Active   | 
| Beeman Creek        | 10 m below Rapids Rd bridge                                 | Wolcottburg   | Erie        | 1     | 43.06947 | -78.59766 | 04120104 | 2015              | Inactive | 
| Belson Creek        | 30 m below SR 76 culvert                                    | Ripley        | Erie        | 1     | 42.24472 | -79.69725 | 04120101 | 2010              | Active   | 
| Bergholtz Creek     | 10 m above Williams Rd bridge                               | Niagara Falls | Niagara     | 1     | 43.09239 | -78.94073 | 04120104 | 2015              | Inactive | 
| Big Indian Creek    | 20 m above Wardtown Rd bridge                               | Perrysburg    | Cattaraugus | 1     | 42.51183 | -79.0433  | 04120102 | 2005              | Active   | 
| Big Sister Creek    | 10 m below Cain Rd bridge                                   | Angola        | Erie        | 1     | 42.60895 | -78.94638 | 04120103 | 2005              | Active   | 
| Big Sister Creek    | 20 m below Rt. 5 bridge                                     | Evans Center  | Erie        | 1     | 42.65706 | -79.03609 | 04120103 | 2005              | Active   | 
| Big Sister Creek    | between Pontiac and Versailles Road bridge, split in stream | Pontiac       | Erie        | 1     | 42.6237  | -78.966   | 04120103 | 2011              | Active   | 
| Black Creek         | Smith Rd bridge                                             | Swormville    | Erie        | 1     | 43.05013 | -78.7118  | 04120104 | 2000              | Inactive | 
```