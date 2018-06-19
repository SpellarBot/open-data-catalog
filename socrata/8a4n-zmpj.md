# Art in DOE buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/art-in-doe-buildings) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8a4n-zmpj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8a4n-zmpj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8a4n-zmpj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8a4n-zmpj |
| Name | Art in DOE buildings |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Tags | art, doe, sca |
| Created | 2015-01-28T21:11:45Z |
| Publication Date | 2015-01-28T21:13:19Z |

## Description

List of art, artist, medium and DOE building that the art is located in schools.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | numeric metric | accession        | Accession        | number        | number        |
| Yes      | series tag     | artwork_title    | Artwork Title    | text          | text          |
| Yes      | series tag     | artist_lastname  | Artist_Lastname  | text          | text          |
| Yes      | series tag     | artist_firstname | Artist_FirstName | text          | text          |
| Yes      | series tag     | medium           | Medium           | text          | text          |
| Yes      | time           | artwork_year     | Artwork Year     | calendar_date | calendar_date |
| Yes      | series tag     | dimension        | Dimension        | text          | text          |
| Yes      | series tag     | bldgid           | BLDGID           | text          | text          |
| Yes      | series tag     | school_name      | School Name      | text          | text          |
| Yes      | series tag     | borough          | Borough          | text          | text          |
```

## Time Field

```ls
Value = artwork_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8a4n-zmpj d:1968-01-01T00:00:00.000Z t:bldgid=M470 t:school_name="LOUIS D. BRANDEIS HS - MANHATTAN" t:artist_firstname=COSTANTINO t:borough=MANHATTAN t:artwork_title="ROOF PROMENADE SCULPTURE" t:artist_lastname=NIVOLA t:medium=CONCRETE m:accession=11000

series e:8a4n-zmpj d:1965-01-01T00:00:00.000Z t:bldgid=M470 t:school_name="LOUIS D. BRANDEIS HS - MANHATTAN" t:artist_firstname=COSTANTINO t:borough=MANHATTAN t:artwork_title="RELIEF PANELS" t:artist_lastname=NIVOLA t:medium=CONCRETE m:accession=11001

series e:8a4n-zmpj d:1956-01-01T00:00:00.000Z t:bldgid=M013 t:school_name="I.S. 13 - MANHATTAN" t:artist_firstname=COSTANTINO t:borough=MANHATTAN t:artwork_title="""SCULPTURED PANELS""" t:artist_lastname=NIVOLA t:medium=CONCRETE m:accession=11003
```

## Meta Commands

```ls
metric m:accession p:integer l:Accession t:dataTypeName=number

entity e:8a4n-zmpj l:"Art in DOE buildings" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/8a4n-zmpj

property e:8a4n-zmpj t:meta.view v:id=8a4n-zmpj v:category=Education v:averageRating=0 v:name="Art in DOE buildings" v:attribution="School Construction Authority (SCA)"

property e:8a4n-zmpj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8a4n-zmpj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| accession | artwork_title                    | artist_lastname | artist_firstname | medium            | artwork_year        | dimension | bldgid | school_name                      | borough   | 
| ========= | ================================ | =============== | ================ | ================= | =================== | ========= | ====== | ================================ | ========= | 
| 11000     | ROOF PROMENADE SCULPTURE         | NIVOLA          | COSTANTINO       | CONCRETE          | 1968-01-01T00:00:00 |           | M470   | LOUIS D. BRANDEIS HS - MANHATTAN | MANHATTAN | 
| 11001     | RELIEF PANELS                    | NIVOLA          | COSTANTINO       | CONCRETE          | 1965-01-01T00:00:00 |           | M470   | LOUIS D. BRANDEIS HS - MANHATTAN | MANHATTAN | 
| 11003     | "SCULPTURED PANELS"              | NIVOLA          | COSTANTINO       | CONCRETE          | 1956-01-01T00:00:00 |           | M013   | I.S. 13 - MANHATTAN              | MANHATTAN | 
| 11005     | THE LIFE OF SAMUEL DICKSTEIN     | GUARDUCCI       | OTELLO           | CAST STONE        | 1967-01-01T00:00:00 |           | M056   | J.H.S. 56 - MANHATTAN            | MANHATTAN | 
| 11006     | CITY OF MANHATTAN                | MATT            | JOHN             | BRONZE            | 1965-01-01T00:00:00 |           | M070   | I.S. 70 - MANHATTAN              | MANHATTAN | 
| 11007     | BRONZE SCULPTURES                | HASTINGS        | JACK             | BRONZE            | 1965-01-01T00:00:00 |           | M501   | ARTHUR SCHOMBURG HS (IS 201) - M | MANHATTAN | 
| 11008     | MARTIN LUTHER KING, JR. MEMORIAL | TARR            | WILLIAM          | STEEL, WEATHERING | 1973-01-01T00:00:00 |           | M490   | "MARTIN LUTHER KING              | 399       | 
| 17009     | "POTTERY"                        | TERKEN          | JOHN             | METAL PAINTED     | 1978-01-01T00:00:00 |           | X722   | P.S. 721 (OTC) - BRONX           | BRONX     | 
| 11010     | SUN, BIRDS, AND LIGHT/ EAGLE     | LUX             | GWEN             | MOSAIC            | 1959-01-01T00:00:00 |           | M019   | P.S. 19 - MANHATTAN              | MANHATTAN | 
| 11010     | SUN, BIRDS, AND LIGHT/ EAGLE     | LUX             | GWEN             | GLASS             | 1959-01-01T00:00:00 |           | M019   | P.S. 19 - MANHATTAN              | MANHATTAN | 
```