# 2014 Daily Vehicle Miles Travelled By Town And Roadway Classification

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-daily-vehicle-miles-travelled-by-town-and-roadway-classification) |
| Metadata | [Link](https://data.ct.gov/api/views/dpat-eygf) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/dpat-eygf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/dpat-eygf/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | dpat-eygf |
| Name | 2014 Daily Vehicle Miles Travelled By Town And Roadway Classification |
| Attribution | Al Iallonardo - Office of Roadway Systems Information |
| Category | Transportation |
| Created | 2015-10-19T18:36:26Z |
| Publication Date | 2015-10-19T18:38:55Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | town_num                 | Town Num                 | text      | number      |
| Yes      | series tag     | town                     | Town                     | text      | text        |
| Yes      | series tag     | county                   | County                   | text      | text        |
| Yes      | series tag     | region                   | Region                   | text      | text        |
| Yes      | numeric metric | interstate_miles         | Interstate Miles         | number    | number      |
| Yes      | numeric metric | interstate_dvmt          | Interstate DVMT          | number    | number      |
| Yes      | numeric metric | freeway_miles            | Freeway Miles            | number    | number      |
| Yes      | numeric metric | freeway_dvmt             | Freeway DVMT             | number    | number      |
| Yes      | numeric metric | principal_arterial_miles | Principal Arterial Miles | number    | number      |
| Yes      | numeric metric | principal_arterial_dvmt  | Principal Arterial DVMT  | number    | number      |
| Yes      | numeric metric | minor_arterial_miles     | Minor Arterial Miles     | number    | number      |
| Yes      | numeric metric | minor_arterial_dvmt      | Minor Arterial DVMT      | number    | number      |
| Yes      | numeric metric | major_colelctormiles     | Major ColelctorMiles     | number    | number      |
| Yes      | numeric metric | major_collector_dvmt     | Major Collector DVMT     | number    | number      |
| Yes      | numeric metric | minor_collector_miles    | Minor Collector Miles    | number    | number      |
| Yes      | numeric metric | minor_collector_dvmt     | Minor Collector DVMT     | number    | number      |
| Yes      | numeric metric | local_miles              | Local Miles              | number    | number      |
| Yes      | numeric metric | local_dvmt               | Local DVMT               | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dpat-eygf d:2014-01-01T00:00:00.000Z t:region="Capitol Region" t:county=Tolland t:town_num=1 t:town=Andover m:minor_arterial_miles=0 m:principal_arterial_miles=4.98 m:freeway_miles=0 m:major_collector_dvmt=8502 m:freeway_dvmt=0 m:local_dvmt=13111 m:minor_collector_miles=2.47 m:interstate_miles=0 m:minor_arterial_dvmt=0 m:minor_collector_dvmt=2716 m:local_miles=32.64 m:principal_arterial_dvmt=88426 m:major_colelctormiles=4.12 m:interstate_dvmt=0

series e:dpat-eygf d:2014-01-01T00:00:00.000Z t:region=Valley t:county="New Haven" t:town_num=2 t:town=Ansonia m:minor_arterial_miles=9.77 m:principal_arterial_miles=2.31 m:freeway_miles=1.49 m:major_collector_dvmt=16303 m:freeway_dvmt=87366 m:local_dvmt=36849 m:minor_collector_miles=0 m:interstate_miles=0 m:minor_arterial_dvmt=59904 m:minor_collector_dvmt=0 m:local_miles=47.92 m:principal_arterial_dvmt=20338 m:major_colelctormiles=7.46 m:interstate_dvmt=0

series e:dpat-eygf d:2014-01-01T00:00:00.000Z t:region="Northeastern CT" t:county=Windham t:town_num=3 t:town=Ashford m:minor_arterial_miles=6.08 m:principal_arterial_miles=0 m:freeway_miles=0 m:major_collector_dvmt=32560 m:freeway_dvmt=0 m:local_dvmt=25432 m:minor_collector_miles=4.01 m:interstate_miles=1.6 m:minor_arterial_dvmt=43850 m:minor_collector_dvmt=2071 m:local_miles=63.58 m:principal_arterial_dvmt=0 m:major_colelctormiles=12.49 m:interstate_dvmt=81980
```

## Meta Commands

```ls
metric m:interstate_miles p:float l:"Interstate Miles" t:dataTypeName=number

metric m:interstate_dvmt p:integer l:"Interstate DVMT" t:dataTypeName=number

metric m:freeway_miles p:float l:"Freeway Miles" t:dataTypeName=number

metric m:freeway_dvmt p:integer l:"Freeway DVMT" t:dataTypeName=number

metric m:principal_arterial_miles p:float l:"Principal Arterial Miles" t:dataTypeName=number

metric m:principal_arterial_dvmt p:integer l:"Principal Arterial DVMT" t:dataTypeName=number

metric m:minor_arterial_miles p:float l:"Minor Arterial Miles" t:dataTypeName=number

metric m:minor_arterial_dvmt p:integer l:"Minor Arterial DVMT" t:dataTypeName=number

metric m:major_colelctormiles p:float l:"Major ColelctorMiles" t:dataTypeName=number

metric m:major_collector_dvmt p:integer l:"Major Collector DVMT" t:dataTypeName=number

metric m:minor_collector_miles p:float l:"Minor Collector Miles" t:dataTypeName=number

metric m:minor_collector_dvmt p:integer l:"Minor Collector DVMT" t:dataTypeName=number

metric m:local_miles p:float l:"Local Miles" t:dataTypeName=number

metric m:local_dvmt p:integer l:"Local DVMT" t:dataTypeName=number

entity e:dpat-eygf l:"2014 Daily Vehicle Miles Travelled By Town And Roadway Classification" t:attribution="Al Iallonardo - Office of Roadway Systems Information" t:url=https://data.ct.gov/api/views/dpat-eygf

property e:dpat-eygf t:meta.view v:id=dpat-eygf v:category=Transportation v:averageRating=0 v:name="2014 Daily Vehicle Miles Travelled By Town And Roadway Classification" v:attribution="Al Iallonardo - Office of Roadway Systems Information"

property e:dpat-eygf t:meta.view.owner v:id=krit-g9ue v:screenName="James Spencer" v:displayName="James Spencer"

property e:dpat-eygf t:meta.view.tableauthor v:id=krit-g9ue v:screenName="James Spencer" v:roleName=editor v:displayName="James Spencer"
```

## Top Records

```ls
| town_num | town         | county     | region            | interstate_miles | interstate_dvmt | freeway_miles | freeway_dvmt | principal_arterial_miles | principal_arterial_dvmt | minor_arterial_miles | minor_arterial_dvmt | major_colelctormiles | major_collector_dvmt | minor_collector_miles | minor_collector_dvmt | local_miles | local_dvmt | 
| ======== | ============ | ========== | ================= | ================ | =============== | ============= | ============ | ======================== | ======================= | ==================== | =================== | ==================== | ==================== | ===================== | ==================== | =========== | ========== | 
| 1        | Andover      | Tolland    | Capitol Region    | 0.00             | 0               | 0.00          | 0            | 4.98                     | 88426                   | 0.00                 | 0                   | 4.12                 | 8502                 | 2.47                  | 2716                 | 32.64       | 13111      | 
| 2        | Ansonia      | New Haven  | Valley            | 0.00             | 0               | 1.49          | 87366        | 2.31                     | 20338                   | 9.77                 | 59904               | 7.46                 | 16303                | 0.00                  | 0                    | 47.92       | 36849      | 
| 3        | Ashford      | Windham    | Northeastern CT   | 1.60             | 81980           | 0.00          | 0            | 0.00                     | 0                       | 6.08                 | 43850               | 12.49                | 32560                | 4.01                  | 2071                 | 63.58       | 25432      | 
| 4        | Avon         | Hartford   | Capitol Region    | 0.00             | 0               | 0.00          | 0            | 8.23                     | 151286                  | 7.65                 | 68657               | 18.89                | 68453                | 0.00                  | 0                    | 90.23       | 62144      | 
| 5        | Barkhamsted  | Litchfield | Litchfield Hills  | 0.00             | 0               | 0.00          | 0            | 3.94                     | 48417                   | 0.00                 | 0                   | 28.76                | 61793                | 0.00                  | 0                    | 42.48       | 20363      | 
| 6        | Beacon Falls | New Haven  | Central Naugatuck | 0.00             | 0               | 4.23          | 203474       | 0.00                     | 0                       | 0.00                 | 0                   | 12.62                | 36296                | 1.37                  | 1507                 | 18.98       | 12335      | 
| 7        | Berlin       | Hartford   | Central CT        | 0.00             | 0               | 5.36          | 247673       | 10.17                    | 186227                  | 17.19                | 126829              | 17.03                | 61303                | 0.30                  | 180                  | 86.87       | 60890      | 
| 8        | Bethany      | New Haven  | South Central     | 0.00             | 0               | 0.00          | 0            | 5.31                     | 34759                   | 5.57                 | 40839               | 11.27                | 18961                | 2.71                  | 1455                 | 51.01       | 26355      | 
| 9        | Bethel       | Fairfield  | Housatonic Valley | 1.43             | 115944          | 0.00          | 0            | 0.00                     | 0                       | 16.10                | 135491              | 5.29                 | 27871                | 0.00                  | 0                    | 77.22       | 63152      | 
| 10       | Bethlehem    | Litchfield | Central Naugatuck | 0.00             | 0               | 0.00          | 0            | 0.00                     | 0                       | 0.00                 | 0                   | 11.69                | 23612                | 1.57                  | 3787                 | 43.93       | 17739      | 
```