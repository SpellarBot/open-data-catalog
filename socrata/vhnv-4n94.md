# SDOT Traffic Cameras

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-traffic-cameras) |
| Metadata | [Link](https://data.seattle.gov/api/views/vhnv-4n94) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vhnv-4n94/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vhnv-4n94/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vhnv-4n94 |
| Name | SDOT Traffic Cameras |
| Tags | storm response, sdot asset status and condition report, assets |
| Created | 2016-12-08T22:52:29Z |
| Publication Date | 2016-12-14T16:00:10Z |

## Description

Displays the location of traffic cameras maintained by SDOT and WSDOT along with live images from those camera?s locations.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | unitid      | UNITID     | text      | text        |
| Yes      | series tag     | comptype    | COMPTYPE   | text      | number      |
| Yes      | numeric metric | compkey     | COMPKEY    | number    | number      |
| Yes      | series tag     | ownership   | OWNERSHIP  | text      | text        |
| Yes      | series tag     | name        | NAME       | text      | text        |
| Yes      | series tag     | url         | URL        | text      | text        |
| Yes      | series tag     | district    | DISTRICT   | text      | text        |
| Yes      | series tag     | location    | LOCATION   | text      | text        |
| Yes      | series tag     | servstat    | SERVSTAT   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vhnv-4n94 d:2016-12-08T22:52:29.000Z t:servstat=ACTV t:ownership=SDOT t:unitid=CMR-0139 t:location="Roosevelt Ave NE & NE 75th St" t:name=Roosevelt_75.jpg t:comptype=16 t:objectid=3 t:url=http://www.seattle.gov/trafficcams/images/Roosevelt_75.jpg m:compkey=545978

series e:vhnv-4n94 d:2016-12-08T22:52:29.000Z t:servstat=ACTV t:ownership=SDOT t:unitid=CMR-0106 t:location="Elliott Ave & Broad St" t:name=Elliott_Broad.jpg t:comptype=16 t:objectid=4 t:url=http://www.seattle.gov/trafficcams/images/Elliott_Broad.jpg m:compkey=545775

series e:vhnv-4n94 d:2016-12-08T22:52:29.000Z t:servstat=ACTV t:ownership=SDOT t:unitid=CMR-0126 t:location="MLK Way S & S Alaska St NS" t:name=MLK_Alaska.jpg t:comptype=16 t:objectid=5 t:url=http://www.seattle.gov/trafficcams/images/MLK_Alaska.jpg m:compkey=545847
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

entity e:vhnv-4n94 l:"SDOT Traffic Cameras" t:url=https://data.seattle.gov/api/views/vhnv-4n94

property e:vhnv-4n94 t:meta.view v:id=vhnv-4n94 v:averageRating=0 v:name="SDOT Traffic Cameras"

property e:vhnv-4n94 t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:vhnv-4n94 t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| :updated_at | objectid | unitid    | comptype | compkey | ownership | name              | url                                                         | district | location                      | servstat | 
| =========== | ======== | ========= | ======== | ======= | ========= | ================= | =========================================================== | ======== | ============================= | ======== | 
| 0           | 1        | CMR-0151  | 16       |         | SDOT      | SR99_King_NB.jpg  | http://www.seattle.gov/trafficcams/images/SR99_King_NB.jpg  |          | SR-99 @ S King St NB          | ACTV     | 
| 0           | 2        | I5Holgate | 16       |         | WSDOT     | 005vc16396.jpg    | http://images.wsdot.wa.gov/nw/005vc16396.jpg                |          | I-5 @ S Holgate St            | ACTV     | 
| 0           | 3        | CMR-0139  | 16       | 545978  | SDOT      | Roosevelt_75.jpg  | http://www.seattle.gov/trafficcams/images/Roosevelt_75.jpg  |          | Roosevelt Ave NE & NE 75th St | ACTV     | 
| 0           | 4        | CMR-0106  | 16       | 545775  | SDOT      | Elliott_Broad.jpg | http://www.seattle.gov/trafficcams/images/Elliott_Broad.jpg |          | Elliott Ave & Broad St        | ACTV     | 
| 0           | 5        | CMR-0126  | 16       | 545847  | SDOT      | MLK_Alaska.jpg    | http://www.seattle.gov/trafficcams/images/MLK_Alaska.jpg    |          | MLK Way S & S Alaska St NS    | ACTV     | 
| 0           | 6        | SR99WMarg | 16       |         | WSDOT     | 099vc02671.jpg    | http://images.wsdot.wa.gov/nw/099vc02671.jpg                |          | SR-99 @ West Marginal Way     | ACTV     | 
| 0           | 7        | I5Roanoke | 16       |         | WSDOT     | 005vc16802.jpg    | http://images.wsdot.wa.gov/nw/005vc16802.jpg                |          | I-5 @ Roanoke St              | ACTV     | 
| 0           | 8        | I5LCW     | 16       |         | WSDOT     | 005vc17078.jpg    | http://images.wsdot.wa.gov/nw/005vc17078.jpg                |          | I-5 @ Lake City Way           | ACTV     | 
| 0           | 9        | I545      | 16       |         | WSDOT     | 005vc16939.jpg    | http://images.wsdot.wa.gov/nw/005vc16939.jpg                |          | I-5 @ NE 45th St              | ACTV     | 
| 0           | 10       | CMR-0152  | 16       |         | SDOT      | SR99_King_SB.jpg  | http://www.seattle.gov/trafficcams/images/SR99_King_SB.jpg  |          | SR-99 @ S King St SB          | ACTV     | 
```