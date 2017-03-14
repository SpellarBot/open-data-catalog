# NYC Parks Monuments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-parks-monuments) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6rrm-vxj9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6rrm-vxj9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6rrm-vxj9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6rrm-vxj9 |
| Name | NYC Parks Monuments |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Recreation |
| Tags | parks, monuments, dpr |
| Created | 2016-09-15T18:35:50Z |
| Publication Date | 2016-09-19T20:14:30Z |
| Rows Updated | 2016-09-19T20:11:53Z |

## Description

This data is table of monuments that is maintained by NYC Parks. Prior to being stored electronically the original data was stored on index cards dating back to the 1940s. The database is updated periodically to include new monuments, and information updated for existing monuments. For questions about the dataset please contact Parks? Art & Antiquities division at (212) 360-8143.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | name              | name              | text          | text          |
| Yes      | series tag     | fileorder         | fileorder         | text          | text          |
| Yes      | numeric metric | number            | number            | number        | number        |
| Yes      | series tag     | parkprop          | parkprop          | text          | text          |
| Yes      | series tag     | borough           | borough           | text          | text          |
| Yes      | series tag     | parkname          | parkname          | text          | text          |
| Yes      | series tag     | parknumber        | parknumber        | text          | text          |
| Yes      | numeric metric | commboard         | commboard         | number        | number        |
| Yes      | numeric metric | council           | council           | number        | number        |
| Yes      | series tag     | location          | Location          | text          | text          |
| Yes      | series tag     | extant            | extant            | text          | text          |
| Yes      | series tag     | dedicated         | dedicated         | text          | text          |
| Yes      | series tag     | cast              | cast              | text          | text          |
| Yes      | series tag     | descrip           | descrip           | text          | text          |
| Yes      | series tag     | dimen             | dimen             | text          | text          |
| Yes      | series tag     | sponsor           | sponsor           | text          | text          |
| Yes      | series tag     | materials         | materials         | text          | text          |
| Yes      | series tag     | foundry           | foundry           | text          | text          |
| Yes      | series tag     | fabricator        | fabricator        | text          | text          |
| Yes      | series tag     | sculptor          | sculptor          | text          | text          |
| Yes      | series tag     | architect         | architect         | text          | text          |
| Yes      | series tag     | donor             | donor             | text          | text          |
| Yes      | series tag     | maintain          | maintain          | text          | text          |
| Yes      | series tag     | contractor        | contractor        | text          | text          |
| Yes      | time           | created           | created           | calendar_date | calendar_date |
| Yes      | series tag     | name2             | Name2             | text          | text          |
| Yes      | series tag     | name3             | Name3             | text          | text          |
| Yes      | series tag     | maintainedbyparks | MaintainedByParks | text          | text          |
| No       |                | installation      | Installation      | calendar_date | calendar_date |
| No       |                | rededication      | Rededication      | calendar_date | calendar_date |
| Yes      | series tag     | cost              | Cost              | text          | text          |
| Yes      | series tag     | categories        | Categories        | text          | text          |
| Yes      | series tag     | inscribed         | inscribed         | text          | text          |
```

## Time Field

```ls
Value = created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = installation,rededication
```

## Data Commands

```ls
series e:6rrm-vxj9 d:2017-03-14T07:25:22.129Z t:parknumber=M099 t:location="Haven Avenue between West 173rd Street and West 176th Street" t:borough=Manhattan t:dimen="H: 35' W: 3' D: 1'" t:materials="Magnesium, aluminum, steel, concrete" t:inscribed="3000 A. D. BY TERRY FUGATE-WILCOX / THE ALUMINUM & MAGNESIUM WILL MIX TOGETHER BY 3000 A.D" t:donor="Public Arts Council and Neighborhood Action Council" t:dedicated=1974 t:name="3000 A.D. Diffusion Piece" t:extant=Y t:maintainedbyparks=Y t:parkprop=Y t:descrip="Monolith of eight magnesium and aluminum plates with steel bolts set on steel base set in concrete pad with plaque" t:sculptor="Tery Fugate-Wilcox" m:commboard=12 m:number=2109 m:council=10

series e:6rrm-vxj9 d:1993-07-01T00:00:00.000Z t:parknumber=M010 t:location="East of Mall" t:borough=Manhattan t:dimen="see memo" t:parkname="Central Park" t:materials="Bronze, Indiana limestone, concrete" t:inscribed="1917 HONOR ROLL OF THE 307TH INFANTRY 1919 / 77TH DIVISION A.E.F. BACCARAT-OISE-MEUSE-ARGONNE/  (NAMES OF 590 MEN ARE LISTED IN 9 COLUMNS.) ON OPPOSITE SIDE OF BOULDER: TO THE DEAD / OF THE / 307TH INFANTRY A.E.F / 590 OFFICERS AND MEN / 1917-1919/" t:donor="Knights of Pythias (?)" t:dedicated=1925 t:name="307th Infantry Memorial Grove" t:extant=Y t:maintainedbyparks=Y t:parkprop=Y t:descrip="15 tree markers, boulder, plaque" t:categories="War Memorial, World War I" m:commboard=7 m:number=1014 m:council=8

series e:6rrm-vxj9 d:2017-03-14T07:25:22.129Z t:location="Fifth Avenue and West 142nd Street" t:fabricator="J. P. Chaudron, Pompes Funebres, Vouziers, France" t:borough=Manhattan t:dimen="H: 12'4""" t:materials="Granite (gray, polished) with hand-cut gilt lettering and painting" t:inscribed="North side: 93RD ST / DIVISION / (US) / [Insignia] / 369TH / INFANTRY / REGIMENT / (15TH REG-NYG) / (COLORED) / IN MEMORY / 1918 / MEUSE-ARGONNE / OFFENSIVE / RIPONT / MONT-CUVELET / SECHAULT / 26 SEP - 1OCT /   South side: 161 ST / DIVISION / (FR) / [Insignia] / 369TH / INFANTRY / REGIMENT / (15TH REG-NYG) / (COLORED) / IN MEMORY / 1918 / MEUSE-ARGONNE / OFFENSIVE / RIPONT / MONT-CUVELET / SECHAULT / 26 SEP - 1OCT /" t:donor="369th Historical Society & Veterans Association" t:dedicated="September 29, 2006" t:name="369th Infantry Regiment Memorial" t:extant=Y t:maintainedbyparks=Y t:descrip="Obelisk (in 3 sections) with engraved and painted inscriptions" t:parkprop=Y t:categories="Soldier, War Memorial, World War I" m:commboard=11 m:number=1980 m:council=9
```

## Meta Commands

```ls
metric m:number p:integer l:number t:dataTypeName=number

metric m:commboard p:integer l:commboard t:dataTypeName=number

metric m:council p:integer l:council t:dataTypeName=number

entity e:6rrm-vxj9 l:"NYC Parks Monuments" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/6rrm-vxj9

property e:6rrm-vxj9 t:meta.view v:id=6rrm-vxj9 v:category=Recreation v:averageRating=0 v:name="NYC Parks Monuments" v:attribution="Department of Parks and Recreation (DPR)"

property e:6rrm-vxj9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:6rrm-vxj9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```