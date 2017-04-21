# Street Sweeper Scheduled Routes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-sweeper-scheduled-routes-zipped-shapefile-format-a411f) |
| Metadata | [Link](https://data.sfgov.org/api/views/u2ac-gv9v) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/u2ac-gv9v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/u2ac-gv9v/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | u2ac-gv9v |
| Name | Street Sweeper Scheduled Routes |
| Category | City Infrastructure |
| Tags | public works, street, sweeping, sweep, clean, mechanical, sweeper |
| Created | 2016-07-28T23:36:02Z |
| Publication Date | 2016-08-19T21:34:03Z |

## Description

Street sweeper schedule that includes: when and where. The data is provided as is. The data in this dataset is for expected time it takes to sweep a route which usually but not always coincides with the no parking sign time posted by MTA in the street. When in doubt always refer to the sign posted by MTA in the street as the official time. Please use the data understanding the limitations.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | blockside   | blockside  | text      | text        |
| Yes      | series tag  | blocksweep  | blocksweep | text      | text        |
| Yes      | series tag  | cnn         | cnn        | text      | text        |
| Yes      | series tag  | cnnrightle  | cnnrightle | text      | text        |
| Yes      | series tag  | corridor    | corridor   | text      | text        |
| Yes      | series tag  | district    | district   | text      | text        |
| Yes      | series tag  | fromhour    | fromhour   | text      | text        |
| Yes      | series tag  | holidays    | holidays   | text      | text        |
| Yes      | series tag  | lf_fadd     | lf_fadd    | text      | text        |
| Yes      | series tag  | lf_toadd    | lf_toadd   | text      | text        |
| Yes      | series tag  | nhood       | nhood      | text      | text        |
| Yes      | series tag  | rt_fadd     | rt_fadd    | text      | text        |
| Yes      | series tag  | rt_toadd    | rt_toadd   | text      | text        |
| Yes      | series tag  | streetname  | streetname | text      | text        |
| Yes      | series tag  | tohour      | tohour     | text      | text        |
| Yes      | series tag  | week1ofmon  | week1ofmon | text      | text        |
| Yes      | series tag  | week2ofmon  | week2ofmon | text      | text        |
| Yes      | series tag  | week3ofmon  | week3ofmon | text      | text        |
| Yes      | series tag  | week4ofmon  | week4ofmon | text      | text        |
| Yes      | series tag  | week5ofmon  | week5ofmon | text      | text        |
| Yes      | series tag  | weekday     | weekday    | text      | text        |
| Yes      | series tag  | zip_code    | zip_code   | text      | text        |
| Yes      | series tag  | geometry    | geometry   | line      | line        |
| Yes      | series tag  | multigeom   | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u2ac-gv9v d:2017-04-15T15:21:15.000Z t:lf_fadd=221 t:blocksweep=1642922 t:zip_code=94127 t:rt_toadd=298 t:lf_toadd=299 t:week4ofmon=N t:corridor="Corona St" t:holidays=N t:rt_fadd=222 t:cnn=13798000 t:geometry="LINESTRING (-122.46659772741017 37.72592447531233, -122.46653820792527 37.72600813459566, -122.46654501473395 37.726092655875306, -122.46662269919527 37.726149395842484, -122.46671578168625 37.72616593870182, -122.466832802132 37.726142308565606, -122.46689767769827 37.72606137786607, -122.46686650091911 37.7259772625764, -122.46674090994827 37.72592981579539, -122.46659772741017 37.72592447531233)" t:week2ofmon=N t:nhood="Ingleside Terrace" t:weekday=Fri t:tohour=14:00 t:week1ofmon=Y t:multigeom=false t:fromhour=12:00 t:week5ofmon=N t:cnnrightle=R t:week3ofmon=Y t:streetname="CORONA ST" m:row_number.u2ac-gv9v=1

series e:u2ac-gv9v d:2017-04-15T15:21:15.000Z t:blockside=East t:lf_fadd=1 t:blocksweep=1635302 t:zip_code=94124 t:rt_toadd=198 t:lf_toadd=199 t:week4ofmon=Y t:corridor="West Point Rd" t:holidays=N t:rt_fadd=2 t:cnn=13576001 t:geometry="LINESTRING (-122.3809902966386 37.735956150208374, -122.38063892904172 37.73557861078668, -122.38027572132883 37.73535830967027, -122.37983280413408 37.7352397674908, -122.379414567742 37.73524467503165)" t:week2ofmon=Y t:nhood="Hunters Point" t:weekday=Fri t:tohour=11:00 t:week1ofmon=Y t:multigeom=false t:fromhour=09:00 t:week5ofmon=Y t:cnnrightle=L t:week3ofmon=Y t:streetname="WEST POINT RD" m:row_number.u2ac-gv9v=2

series e:u2ac-gv9v d:2017-04-15T15:21:15.000Z t:lf_fadd=1 t:blocksweep=1601353 t:zip_code=94134 t:rt_toadd=98 t:lf_toadd=99 t:week4ofmon=Y t:corridor="Hester Ave" t:holidays=N t:rt_fadd=2 t:cnn=6894003 t:geometry="LINESTRING (-122.39899104926616 37.71533878961713, -122.3988346192445 37.715264995938355, -122.39850233545577 37.714933103849674, -122.39835080222676 37.714687714499355, -122.39821181525218 37.71441266361886)" t:week2ofmon=Y t:nhood="Visitacion Valley" t:weekday=Thu t:tohour=08:00 t:week1ofmon=Y t:multigeom=false t:fromhour=07:00 t:week5ofmon=Y t:cnnrightle=R t:week3ofmon=Y t:streetname="HESTER AVE" m:row_number.u2ac-gv9v=3
```

## Meta Commands

```ls
metric m:row_number.u2ac-gv9v p:long l:"Row Number"

entity e:u2ac-gv9v l:"Street Sweeper Scheduled Routes" t:url=https://data.sfgov.org/api/views/u2ac-gv9v

property e:u2ac-gv9v t:meta.view v:id=u2ac-gv9v v:category="City Infrastructure" v:averageRating=0 v:name="Street Sweeper Scheduled Routes"

property e:u2ac-gv9v t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:u2ac-gv9v t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:u2ac-gv9v t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | blockside | blocksweep | cnn      | cnnrightle | corridor            | district | fromhour | holidays | lf_fadd | lf_toadd | nhood             | rt_fadd | rt_toadd | streetname          | tohour | week1ofmon | week2ofmon | week3ofmon | week4ofmon | week5ofmon | weekday | zip_code | geometry                                                                                                                                                                                                                                                                                                                                                                                                          | multigeom | 
| =========== | ========= | ========== | ======== | ========== | =================== | ======== | ======== | ======== | ======= | ======== | ================= | ======= | ======== | =================== | ====== | ========== | ========== | ========== | ========== | ========== | ======= | ======== | ================================================================================================================================================================================================================================================================================================================================================================================================================= | ========= | 
| 1492269675  |           | 1642922    | 13798000 | R          | Corona St           |          | 12:00    | N        | 221     | 299      | Ingleside Terrace | 222     | 298      | CORONA ST           | 14:00  | Y          | N          | Y          | N          | N          | Fri     | 94127    | LINESTRING (-122.46659772741017 37.72592447531233, -122.46653820792527 37.72600813459566, -122.46654501473395 37.726092655875306, -122.46662269919527 37.726149395842484, -122.46671578168625 37.72616593870182, -122.466832802132 37.726142308565606, -122.46689767769827 37.72606137786607, -122.46686650091911 37.7259772625764, -122.46674090994827 37.72592981579539, -122.46659772741017 37.72592447531233) | false     | 
| 1492269675  | East      | 1635302    | 13576001 | L          | West Point Rd       |          | 09:00    | N        | 1       | 199      | Hunters Point     | 2       | 198      | WEST POINT RD       | 11:00  | Y          | Y          | Y          | Y          | Y          | Fri     | 94124    | LINESTRING (-122.3809902966386 37.735956150208374, -122.38063892904172 37.73557861078668, -122.38027572132883 37.73535830967027, -122.37983280413408 37.7352397674908, -122.379414567742 37.73524467503165)                                                                                                                                                                                                       | false     | 
| 1492269675  |           | 1601353    | 6894003  | R          | Hester Ave          |          | 07:00    | N        | 1       | 99       | Visitacion Valley | 2       | 98       | HESTER AVE          | 08:00  | Y          | Y          | Y          | Y          | Y          | Thu     | 94134    | LINESTRING (-122.39899104926616 37.71533878961713, -122.3988346192445 37.715264995938355, -122.39850233545577 37.714933103849674, -122.39835080222676 37.714687714499355, -122.39821181525218 37.71441266361886)                                                                                                                                                                                                  | false     | 
| 1492269675  |           | 1642803    | 6894003  | L          | Hester Ave          |          | 07:00    | N        | 1       | 99       | Visitacion Valley | 2       | 98       | HESTER AVE          | 08:00  | Y          | Y          | Y          | Y          | Y          | Tues    | 94134    | LINESTRING (-122.39899104926616 37.71533878961713, -122.3988346192445 37.715264995938355, -122.39850233545577 37.714933103849674, -122.39835080222676 37.714687714499355, -122.39821181525218 37.71441266361886)                                                                                                                                                                                                  | false     | 
| 1492269675  |           | 1601354    | 6894004  | R          | Hester Ave          |          | 07:00    | N        | 101     | 211      | Visitacion Valley | 100     | 210      | HESTER AVE          | 08:00  | Y          | Y          | Y          | Y          | Y          | Thu     | 94134    | LINESTRING (-122.39821181525218 37.71441266361886, -122.39765768790123 37.7133160457775)                                                                                                                                                                                                                                                                                                                          | false     | 
| 1492269675  |           | 1642804    | 6894004  | L          | Hester Ave          |          | 07:00    | N        | 101     | 211      | Visitacion Valley | 100     | 210      | HESTER AVE          | 08:00  | Y          | Y          | Y          | Y          | Y          | Tues    | 94134    | LINESTRING (-122.39821181525218 37.71441266361886, -122.39765768790123 37.7133160457775)                                                                                                                                                                                                                                                                                                                          | false     | 
| 1492269675  |           | 1601340    | 5371001  | L          | Executive Park Blvd |          | 10:00    | N        | 1       | 91       | Bayview Heights   | 2       | 90       | EXECUTIVE PARK BLVD | 15:00  | Y          | Y          | Y          | Y          | Y          | Fri     | 94134    | LINESTRING (-122.39440306589806 37.70890382584192, -122.39451745042867 37.709516440290564, -122.39457067947 37.70967179564975, -122.39482362530634 37.71102502498754)                                                                                                                                                                                                                                             | false     | 
| 1492269675  |           | 1601346    | 5371001  | R          | Executive Park Blvd |          | 10:00    | N        | 1       | 91       | Bayview Heights   | 2       | 90       | EXECUTIVE PARK BLVD | 15:00  | Y          | Y          | Y          | Y          | Y          | Fri     | 94134    | LINESTRING (-122.39440306589806 37.70890382584192, -122.39451745042867 37.709516440290564, -122.39457067947 37.70967179564975, -122.39482362530634 37.71102502498754)                                                                                                                                                                                                                                             | false     | 
| 1492269675  |           | 1612953    | 4640103  | R          | De Haro St          |          | 12:00    | N        | 1357    | 1399     | Potrero Hill      | 0       | 0        | DE HARO ST          | 14:00  | Y          | Y          | Y          | Y          | Y          | Wed     | 94107    | LINESTRING (-122.40033143927789 37.75267525002336, -122.40037575677154 37.75218059002223, -122.40041559015594 37.752074817098894)                                                                                                                                                                                                                                                                                 | false     | 
| 1492269675  |           | 1612952    | 4640102  | R          | De Haro St          |          | 12:00    | N        | 1321    | 1355     | Potrero Hill      | 0       | 0        | DE HARO ST          | 14:00  | Y          | Y          | Y          | Y          | Y          | Wed     | 94107    | LINESTRING (-122.40035838369721 37.753066623249126, -122.40033143927789 37.75267525002336)                                                                                                                                                                                                                                                                                                                        | false     | 
```