# NYC Parks Monuments

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/6rrm-vxj9/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/nyc-parks-monuments)
* [Metadata URL](https://data.cityofnewyork.us/api/views/6rrm-vxj9)
* Id = 6rrm-vxj9
* Name = NYC Parks Monuments
* Attribution = Department of Parks and Recreation (DPR)
* Category = Recreation
* Tags = [parks, monuments, dpr]
* Created = 2016-09-15T18:35:50Z
* Publication Date = 2016-09-19T20:14:30Z
* Rows Updated = 2016-09-19T20:11:53Z

## Description

This data is table of monuments that is maintained by NYC Parks. Prior to being stored electronically the original data was stored on index cards dating back to the 1940s. The database is updated periodically to include new monuments, and information updated for existing monuments. For questions about the dataset please contact Parks? Art & Antiquities division at (212) 360-8143.

## Columns

```ls
| Name              | Field Name        | Data Type     | Render Type   | Schema Type    | Included | 
| ================= | ================= | ============= | ============= | ============== | ======== | 
| name              | name              | text          | text          | series tag     | Yes      | 
| fileorder         | fileorder         | text          | text          | series tag     | Yes      | 
| number            | number            | number        | number        | numeric metric | Yes      | 
| parkprop          | parkprop          | number        | text          | numeric metric | Yes      | 
| borough           | borough           | text          | text          | series tag     | Yes      | 
| parkname          | parkname          | text          | text          | series tag     | Yes      | 
| parknumber        | parknumber        | text          | text          | series tag     | Yes      | 
| commboard         | commboard         | number        | number        | numeric metric | Yes      | 
| council           | council           | number        | number        | numeric metric | Yes      | 
| Location          | location          | text          | text          | series tag     | Yes      | 
| extant            | extant            | text          | text          | series tag     | Yes      | 
| dedicated         | dedicated         | text          | text          | series tag     | Yes      | 
| cast              | cast              | text          | text          | series tag     | Yes      | 
| descrip           | descrip           | text          | text          | series tag     | Yes      | 
| dimen             | dimen             | text          | text          | series tag     | Yes      | 
| sponsor           | sponsor           | text          | text          | series tag     | Yes      | 
| materials         | materials         | text          | text          | series tag     | Yes      | 
| foundry           | foundry           | text          | text          | series tag     | Yes      | 
| fabricator        | fabricator        | text          | text          | series tag     | Yes      | 
| sculptor          | sculptor          | text          | text          | series tag     | Yes      | 
| architect         | architect         | text          | text          | series tag     | Yes      | 
| donor             | donor             | text          | text          | series tag     | Yes      | 
| maintain          | maintain          | text          | text          | series tag     | Yes      | 
| contractor        | contractor        | text          | text          | series tag     | Yes      | 
| created           | created           | calendar_date | calendar_date | time           | Yes      | 
| Name2             | name2             | text          | text          | series tag     | Yes      | 
| Name3             | name3             | text          | text          | series tag     | Yes      | 
| MaintainedByParks | maintainedbyparks | text          | text          | series tag     | Yes      | 
| Installation      | installation      | calendar_date | calendar_date |                | No       | 
| Rededication      | rededication      | calendar_date | calendar_date |                | No       | 
| Cost              | cost              | text          | text          | series tag     | Yes      | 
| Categories        | categories        | text          | text          | series tag     | Yes      | 
| inscribed         | inscribed         | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = installation,rededication
Annotation Fields = 
```

## Data Commands

```ls
series e:6rrm-vxj9 d:2017-03-08T01:01:38.042Z t:parknumber=M099 t:location="Haven Avenue between West 173rd Street and West 176th Street" t:borough=Manhattan t:dimen="H: 35' W: 3' D: 1'" t:materials="Magnesium, aluminum, steel, concrete" t:inscribed="3000 A. D. BY TERRY FUGATE-WILCOX / THE ALUMINUM & MAGNESIUM WILL MIX TOGETHER BY 3000 A.D" t:donor="Public Arts Council and Neighborhood Action Council" t:dedicated=1974 t:name="3000 A.D. Diffusion Piece" t:extant=Y t:maintainedbyparks=Y t:parkprop=Y t:descrip="Monolith of eight magnesium and aluminum plates with steel bolts set on steel base set in concrete pad with plaque" t:sculptor="Tery Fugate-Wilcox" m:commboard=12 m:number=2109 m:council=10

series e:6rrm-vxj9 d:1993-07-01T00:00:00.000Z t:parknumber=M010 t:location="East of Mall" t:borough=Manhattan t:dimen="see memo" t:parkname="Central Park" t:materials="Bronze, Indiana limestone, concrete" t:inscribed="1917 HONOR ROLL OF THE 307TH INFANTRY 1919 / 77TH DIVISION A.E.F. BACCARAT-OISE-MEUSE-ARGONNE/  (NAMES OF 590 MEN ARE LISTED IN 9 COLUMNS.) ON OPPOSITE SIDE OF BOULDER: TO THE DEAD / OF THE / 307TH INFANTRY A.E.F / 590 OFFICERS AND MEN / 1917-1919/" t:donor="Knights of Pythias (?)" t:dedicated=1925 t:name="307th Infantry Memorial Grove" t:extant=Y t:maintainedbyparks=Y t:parkprop=Y t:descrip="15 tree markers, boulder, plaque" t:categories="War Memorial, World War I" m:commboard=7 m:number=1014 m:council=8

series e:6rrm-vxj9 d:2017-03-08T01:01:38.042Z t:location="Fifth Avenue and West 142nd Street" t:fabricator="J. P. Chaudron, Pompes Funebres, Vouziers, France" t:borough=Manhattan t:dimen="H: 12'4""" t:materials="Granite (gray, polished) with hand-cut gilt lettering and painting" t:inscribed="North side: 93RD ST / DIVISION / (US) / [Insignia] / 369TH / INFANTRY / REGIMENT / (15TH REG-NYG) / (COLORED) / IN MEMORY / 1918 / MEUSE-ARGONNE / OFFENSIVE / RIPONT / MONT-CUVELET / SECHAULT / 26 SEP - 1OCT /   South side: 161 ST / DIVISION / (FR) / [Insignia] / 369TH / INFANTRY / REGIMENT / (15TH REG-NYG) / (COLORED) / IN MEMORY / 1918 / MEUSE-ARGONNE / OFFENSIVE / RIPONT / MONT-CUVELET / SECHAULT / 26 SEP - 1OCT /" t:donor="369th Historical Society & Veterans Association" t:dedicated="September 29, 2006" t:name="369th Infantry Regiment Memorial" t:extant=Y t:maintainedbyparks=Y t:descrip="Obelisk (in 3 sections) with engraved and painted inscriptions" t:parkprop=Y t:categories="Soldier, War Memorial, World War I" m:commboard=11 m:number=1980 m:council=9
```

## Meta Commands

```ls
metric m:number p:integer l:number t:dataTypeName=number

metric m:commboard p:integer l:commboard t:dataTypeName=number

metric m:council p:integer l:council t:dataTypeName=number

entity e:6rrm-vxj9 l:"NYC Parks Monuments" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/6rrm-vxj9

property e:6rrm-vxj9 t:meta.view d:2017-03-08T01:01:38.042Z v:id=6rrm-vxj9 v:category=Recreation v:averageRating=0 v:name="NYC Parks Monuments" v:attribution="Department of Parks and Recreation (DPR)"

property e:6rrm-vxj9 t:meta.view.owner d:2017-03-08T01:01:38.042Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:6rrm-vxj9 t:meta.view.tableauthor d:2017-03-08T01:01:38.042Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```