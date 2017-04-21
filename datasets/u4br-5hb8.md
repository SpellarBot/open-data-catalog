# Historic Zoning Districts - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historic-zoning-districts-2009-caecd) |
| Metadata | [Link](https://data.sfgov.org/api/views/u4br-5hb8) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/u4br-5hb8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/u4br-5hb8/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | u4br-5hb8 |
| Name | Historic Zoning Districts - 2009 |
| Category | Geographic Locations and Boundaries |
| Tags | planning, zoning, gis, shapefile |
| Created | 2016-07-28T17:17:20Z |
| Publication Date | 2016-08-19T21:39:53Z |

## Description

Zoning Districts from 2009. Part of the San Francisco Planning Code. Data is a zipped GIS shapefile.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | districtna | districtna | text      | text        |
| Yes      | numeric metric | shape_area | shape_area | number    | number      |
| Yes      | numeric metric | shape_len  | shape_len  | number    | number      |
| Yes      | series tag     | url        | url        | text      | text        |
| Yes      | series tag     | zoning_sim | zoning_sim | text      | text        |
| No       |                | geometry   | geometry   | polygon   | polygon     |
| Yes      | series tag     | multigeom  | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = geometry
```

## Data Commands

```ls
series e:u4br-5hb8 d:2009-01-01T00:00:00.000Z t:multigeom=false t:zoning_sim=CRNC t:districtna="CHINATOWN- RESIDENTIAL- NEIGHBORHOOD COMMERCIAL" t:url="http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=52008df43dfdb3bd97da0e5f91dda23a" m:shape_area=14753.47707 m:shape_len=528.837895

series e:u4br-5hb8 d:2009-01-01T00:00:00.000Z t:multigeom=false t:zoning_sim=NCD t:districtna="FILLMORE STREET NEIGHBORHOOD COMMERCIAL" t:url="http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=9fc9d7d65dc17f164aefeafb39673124" m:shape_area=19185.99929 m:shape_len=724.398038

series e:u4br-5hb8 d:2009-01-01T00:00:00.000Z t:multigeom=false t:zoning_sim=M-1 t:districtna="LIGHT INDUSTRIAL" t:url="http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=6f5128c8e08cdd31b1440b9c4ff1124f" m:shape_area=7038.07942 m:shape_len=464.515596
```

## Meta Commands

```ls
metric m:shape_area p:long l:shape_area t:dataTypeName=number

metric m:shape_len p:long l:shape_len t:dataTypeName=number

entity e:u4br-5hb8 l:"Historic Zoning Districts - 2009" t:url=https://data.sfgov.org/api/views/u4br-5hb8

property e:u4br-5hb8 t:meta.view v:id=u4br-5hb8 v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Historic Zoning Districts - 2009"

property e:u4br-5hb8 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:u4br-5hb8 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:u4br-5hb8 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| districtna                                      | shape_area   | shape_len   | url                                                                                                                                  | zoning_sim | geometry                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | multigeom | 
| =============================================== | ============ | =========== | ==================================================================================================================================== | ========== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ========= | 
| CHINATOWN- RESIDENTIAL- NEIGHBORHOOD COMMERCIAL | 14753.47707  | 528.837895  | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=52008df43dfdb3bd97da0e5f91dda23a | CRNC       | POLYGON ((-122.40892244387226 37.79715516238853, -122.40893647651146 37.79722291181668, -122.40866305284594 37.797257531016214, -122.40864902156179 37.79718978063677, -122.4086361678559 37.79712772217306, -122.4085596198422 37.796758119767716, -122.40883289270616 37.796722784951164, -122.40890959105599 37.79709310303501, -122.40892244387226 37.79715516238853))                                                                                                                                                                                                                                                                                                                                                              | false     | 
| FILLMORE STREET NEIGHBORHOOD COMMERCIAL         | 19185.99929  | 724.398038  | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=9fc9d7d65dc17f164aefeafb39673124 | NCD        | POLYGON ((-122.43439588637003 37.79106997155651, -122.43433938990982 37.79078945442326, -122.43442616138073 37.790778416707546, -122.43447330180011 37.79101255833413, -122.43455873548226 37.79100172902525, -122.43456808041685 37.7910481434249, -122.43465351410272 37.79103731314665, -122.43474920167316 37.7910251835273, -122.43476285150173 37.791092981665884, -122.43477263793869 37.79109174142485, -122.43478619046732 37.79115902926532, -122.43482715607146 37.7913624224944, -122.4348422792437 37.79143750982719, -122.43447918232938 37.791483537336745, -122.43446405840321 37.79140845087746, -122.43442309376805 37.79120505752399, -122.43440954155999 37.79113776964231, -122.43439588637003 37.79106997155651)) | false     | 
| LIGHT INDUSTRIAL                                | 7038.07942   | 464.515596  | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=6f5128c8e08cdd31b1440b9c4ff1124f | M-1        | POLYGON ((-122.38930832078337 37.79057060788327, -122.38928459217553 37.79052638275386, -122.38974251507278 37.790891214151145, -122.38972055397068 37.79090855930885, -122.38955836971549 37.79103665538844, -122.38930832078337 37.79057060788327))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | false     | 
| OUTER CLEMENT STREET NEIGHBORHOOD COMMERCIAL    | 7614.80292   | 365.260888  | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=85f820cc162f09f340fa34fdbecdeb5d | NCD        | POLYGON ((-122.48629638032014 37.782064335019776, -122.48631993838111 37.78238862950406, -122.48623356692657 37.78239248102722, -122.48609739641292 37.78239855390344, -122.48607386441321 37.78207460322217, -122.48621001850631 37.78206832065294, -122.48629638032014 37.782064335019776))                                                                                                                                                                                                                                                                                                                                                                                                                                           | false     | 
| PUBLIC                                          | 193702.51581 | 1767.734568 | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=2afda33ec40f4af8b91758b4390a786f | P          | POLYGON ((-122.41011283971466 37.76312792848552, -122.41021743081495 37.76423043101678, -122.40855321399476 37.76432454606335, -122.408451201368 37.76322560919495, -122.41011283971466 37.76312792848552))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | false     | 
| RESIDENTIAL- COMMERCIAL, MEDIUM DENSITY         | 5643.39645   | 337.138378  | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=7983f9d2767541ef2eea5be2f55298a5 | RC-3       | POLYGON ((-122.41135040175357 37.79584430323424, -122.4113245950094 37.795715469659925, -122.41128384873137 37.795512048761545, -122.41144228710182 37.79549205927791, -122.41150688578567 37.79582455984251, -122.41135040175357 37.79584430323424))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | false     | 
| DOWNTOWN- GENERAL                               | 11789.49498  | 447.5747    | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=df2abcda7f4a87c2f326e21c93a03ca2 | C-3-G      | POLYGON ((-122.41766933784693 37.771841451186646, -122.41779520668227 37.771650491190655, -122.41797915909 37.77172339526579, -122.41804519019233 37.77193055080312, -122.41808233561103 37.77204883141268, -122.4180821036722 37.77205853499065, -122.41807899349999 37.77206709038686, -122.41807422071903 37.77207382533975, -122.41806700923723 37.77207994568915, -122.41805898073709 37.772084412079536, -122.41805078552575 37.772087039093336, -122.41804181135608 37.77208847475441, -122.41803119799724 37.772088117527744, -122.41802011255442 37.7720857023908, -122.41762235974183 37.771912959177875, -122.41766933784693 37.771841451186646))                                                                            | false     | 
| RESIDENTIAL- HOUSE, TWO FAMILY                  | 14486.49596  | 489.239019  | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=31b327685942e2a6c487b2164d73a8b4 | RH-2       | POLYGON ((-122.46775878292252 37.77717266713559, -122.46784514238503 37.77716874093623, -122.46785188330612 37.77726185490168, -122.46785851197582 37.77735343144412, -122.46786510229228 37.77744445977818, -122.46777874239088 37.7774483814878, -122.46769238139319 37.777452304954785, -122.46736744923108 37.77746706197438, -122.46736248719179 37.777398516384366, -122.4673575251616 37.77732997079324, -122.46735256316444 37.77726142610192, -122.46734749289647 37.777191365551076, -122.46767242345082 37.7771765932717, -122.46775878292252 37.77717266713559))                                                                                                                                                            | false     | 
| RESIDENTIAL- MIXED, MODERATE DENSITY            | 7425.00106   | 345.000027  | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=48cff71c87957bdc222a10e1b9a942e4 | RM-2       | POLYGON ((-122.4280041864786 37.77467831563192, -122.42772234483846 37.774714199798716, -122.42767291293768 37.774470164046015, -122.4279547547873 37.77443427907645, -122.4280041864786 37.77467831563192))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | false     | 
| RESIDENTIAL- MIXED, MEDIUM DENSITY              | 18811.3632   | 548.78304   | http://library4.municode.com:80/4201/home.htm?view=home&doc_action=setdoc&doc_keytype=tocid&doc_key=48cff71c87957bdc222a10e1b9a942e4 | RM-3       | POLYGON ((-122.42118423992154 37.80284663935113, -122.42138294480833 37.802821552209345, -122.42144940384024 37.80318503534736, -122.4212445563854 37.803212396379905, -122.42097142621859 37.803248877503314, -122.42090434495269 37.802881976959604, -122.42118423992154 37.80284663935113))                                                                                                                                                                                                                                                                                                                                                                                                                                          | false     | 
```