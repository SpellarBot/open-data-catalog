# Street Tree Inventory - 1990s

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-tree-inventory-1990s) |
| Metadata | [Link](https://data.lacity.org/api/views/vt5t-mscf) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/vt5t-mscf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/vt5t-mscf/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | vt5t-mscf |
| Name | Street Tree Inventory - 1990s |
| Category | A Livable and Sustainable City |
| Created | 2016-03-24T04:20:50Z |
| Publication Date | 2016-03-24T04:54:39Z |

## Description

Converted from elderly Microsoft Access database.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | trees_id                 | trees_id                 | text          | number        |
| Yes      | series tag     | trees_id2                | trees_id2                | text          | text          |
| Yes      | numeric metric | tr_rec                   | Tr_rec                   | number        | number        |
| Yes      | series tag     | locarea                  | Locarea                  | text          | text          |
| Yes      | numeric metric | locunit                  | Locunit                  | number        | number        |
| Yes      | series tag     | locsubunit               | Locsubunit               | text          | text          |
| Yes      | numeric metric | locsite                  | Locsite                  | number        | number        |
| Yes      | numeric metric | spp                      | Spp                      | number        | number        |
| Yes      | series tag     | common                   | Common                   | text          | text          |
| Yes      | series tag     | botanical                | Botanical                | text          | text          |
| Yes      | series tag     | on_strt                  | On_strt                  | text          | text          |
| Yes      | series tag     | from_strt                | From_strt                | text          | text          |
| Yes      | series tag     | to_strt                  | To_strt                  | text          | text          |
| Yes      | numeric metric | gisno                    | Gisno                    | number        | number        |
| Yes      | series tag     | ext                      | Ext                      | text          | text          |
| Yes      | series tag     | area                     | Area                     | text          | text          |
| Yes      | series tag     | treeloc                  | Treeloc                  | text          | text          |
| Yes      | series tag     | dbh                      | Dbh                      | text          | text          |
| Yes      | time           | inv_date                 | Inv_date                 | calendar_date | calendar_date |
| Yes      | series tag     | drgmapname               | Drgmapname               | text          | text          |
| Yes      | series tag     | drglayer                 | Drglayer                 | text          | text          |
| Yes      | numeric metric | drgxcoord                | Drgxcoord                | number        | number        |
| Yes      | numeric metric | drgycoord                | Drgycoord                | number        | number        |
| Yes      | numeric metric | x_original               | X_original               | number        | number        |
| Yes      | numeric metric | y_original               | Y_original               | number        | number        |
| Yes      | series tag     | dir                      | DIR                      | text          | text          |
| Yes      | numeric metric | des_spp1                 | DES_SPP1                 | number        | number        |
| Yes      | series tag     | trunks                   | TRUNKS                   | text          | text          |
| No       |                | ht                       | HT                       | text          | text          |
| Yes      | series tag     | cond                     | COND                     | text          | text          |
| No       |                | mt                       | MT                       | text          | text          |
| Yes      | series tag     | pest                     | PEST                     | text          | text          |
| Yes      | series tag     | veg                      | VEG                      | text          | text          |
| Yes      | series tag     | wellstat                 | WELLSTAT                 | text          | text          |
| Yes      | series tag     | wellcov                  | WELLCOV                  | text          | text          |
| Yes      | series tag     | guard                    | GUARD                    | text          | text          |
| No       |                | ut                       | UT                       | text          | text          |
| Yes      | series tag     | utob                     | UTOB                     | text          | text          |
| No       |                | cd                       | CD                       | number        | number        |
| Yes      | series tag     | dist                     | DIST                     | text          | text          |
| Yes      | numeric metric | tg_pg                    | TG_PG                    | number        | number        |
| Yes      | series tag     | tg_coord                 | TG_COORD                 | text          | text          |
| Yes      | series tag     | cmap                     | CMAP                     | text          | text          |
| No       |                | hd                       | HD                       | text          | text          |
| Yes      | numeric metric | grow                     | GROW                     | number        | number        |
| Yes      | series tag     | hist_id                  | HIST_ID                  | text          | text          |
| Yes      | series tag     | exp_id                   | EXP_ID                   | text          | text          |
| No       |                | up_date                  | UP_DATE                  | text          | text          |
| Yes      | series tag     | staff                    | STAFF                    | text          | text          |
| No       |                | un                       | UN                       | number        | number        |
| Yes      | numeric metric | blsd                     | BLSD                     | number        | number        |
| Yes      | series tag     | download                 | DOWNLOAD                 | text          | text          |
| Yes      | series tag     | notes                    | NOTES                    | text          | text          |
| Yes      | series tag     | city_name                | CITY_NAME                | text          | text          |
| Yes      | numeric metric | blsdval                  | BLSDVAL                  | number        | number        |
| Yes      | series tag     | mdist                    | MDIST                    | text          | text          |
| Yes      | series tag     | growmatl                 | GROWMATL                 | text          | text          |
| Yes      | series tag     | growsize                 | GROWSIZE                 | text          | text          |
| Yes      | series tag     | growtype                 | GROWTYPE                 | text          | text          |
| Yes      | series tag     | type                     | TYPE                     | text          | text          |
| No       |                | x                        | X                        | number        | number        |
| No       |                | y                        | Y                        | number        | number        |
| Yes      | series tag     | utdescription            | utdescription            | text          | text          |
| Yes      | series tag     | utdescription_other      | utdescription_other      | text          | text          |
| Yes      | series tag     | curb                     | curb                     | text          | text          |
| Yes      | series tag     | stock_size               | stock_size               | text          | text          |
| Yes      | series tag     | sidewalk                 | sidewalk                 | text          | text          |
| Yes      | series tag     | trees_street_id          | trees_street_id          | text          | number        |
| No       |                | date_root_prune_curb     | date_root_prune_curb     | text          | text          |
| No       |                | date_root_prune_driveway | date_root_prune_driveway | text          | text          |
| No       |                | date_root_prune_sidewalk | date_root_prune_sidewalk | text          | text          |
| Yes      | series tag     | note_id                  | note_id                  | text          | text          |
```

## Time Field

```ls
Value = inv_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = ht,mt,ut,cd,hd,up_date,un,x,y,date_root_prune_curb,date_root_prune_driveway,date_root_prune_sidewalk
```

## Data Commands

```ls
series e:vt5t-mscf d:1991-06-19T00:00:00.000Z t:city_name="LOS ANGELES" t:hist_id=NULL t:utob=NULL t:common=NULL t:tg_coord=F2 t:curb=NULL t:growmatl=NULL t:download=NULL t:mdist=NULL t:type=original t:botanical=NULL t:cond=NULL t:dbh=3-12 t:ext=NULL t:locarea="YOAKUM DR" t:staff=BL t:growtype=NULL t:area=NULL t:from_strt=DEADEND t:dir=O t:growsize=NULL t:guard=NULL t:trees_id=2 t:trunks=NULL t:trees_id2=384592f6173 t:to_strt="BENEDICT CANYON DR" t:drglayer=NULL t:exp_id=NULL t:drgmapname=NULL t:locsubunit=F t:trees_street_id=402860 t:utdescription_other=NULL t:treeloc=S t:veg=NULL t:note_id=NULL t:on_strt="YOAKUM DR" t:wellstat=NULL t:cmap=NULL t:pest=NULL t:stock_size=NULL t:utdescription=NULL t:wellcov=NULL t:notes=NULL t:dist=MT t:sidewalk=NULL m:tg_pg=32 m:y_original=0 m:spp=308 m:x_original=0 m:drgxcoord=0 m:gisno=329230 m:drgycoord=0 m:blsd=200 m:des_spp1=0 m:blsdval=200 m:locsite=1 m:tr_rec=329230 m:grow=99 m:locunit=9655

series e:vt5t-mscf d:1991-07-15T00:00:00.000Z t:city_name="LOS ANGELES" t:hist_id=NULL t:utob=NULL t:common=NULL t:tg_coord=F5 t:curb=NULL t:growmatl=NULL t:download=NULL t:mdist=NULL t:type=original t:botanical=NULL t:cond=NULL t:dbh=3-12 t:ext=X t:locarea="CHALON RD" t:staff=CS t:growtype=NULL t:area=NULL t:from_strt="ARBUTUS DR" t:dir=O t:growsize=NULL t:guard=NULL t:trees_id=3 t:trunks=NULL t:trees_id2=3845921a21e t:to_strt="WESTRIDGE RD" t:drglayer=NULL t:exp_id=NULL t:drgmapname=NULL t:locsubunit=F t:trees_street_id=123041 t:utdescription_other=NULL t:treeloc=S t:veg=NULL t:note_id=NULL t:on_strt="CHALON RD" t:wellstat=NULL t:cmap=NULL t:pest=NULL t:stock_size=NULL t:utdescription=NULL t:wellcov=NULL t:notes=NULL t:dist=MT t:sidewalk=NULL m:tg_pg=30 m:y_original=0 m:spp=308 m:x_original=0 m:drgxcoord=0 m:gisno=279656 m:drgycoord=0 m:blsd=54 m:des_spp1=0 m:blsdval=54 m:locsite=1 m:tr_rec=279656 m:grow=99 m:locunit=13241

series e:vt5t-mscf d:1991-05-03T00:00:00.000Z t:city_name="LOS ANGELES" t:hist_id=NULL t:utob=NULL t:common="CHINESE FLAME TREE" t:tg_coord=D3 t:curb=NULL t:growmatl="ORGANIC (SOIL, TURF)" t:download=NULL t:mdist=NULL t:type=original t:botanical="KOELREUTERIA BIPINNATA" t:cond=NULL t:dbh=3-6 t:ext=X t:locarea="VENTURA BL" t:staff=BL t:growtype=NULL t:area=NULL t:from_strt="ENCINO AV" t:dir=O t:growsize=NULL t:guard=NULL t:trees_id=4 t:trunks=NULL t:trees_id2=384591f857 t:to_strt="WHITE OAK AV" t:drglayer=NULL t:exp_id=NULL t:drgmapname=NULL t:locsubunit=F t:trees_street_id=375483 t:utdescription_other=NULL t:treeloc=S t:veg=NULL t:note_id=NULL t:on_strt="VENTURA BL" t:wellstat=NULL t:cmap=NULL t:pest=NULL t:stock_size=NULL t:utdescription=NULL t:wellcov=NULL t:notes=NULL t:dist=WV t:sidewalk=NULL m:tg_pg=561 m:y_original=0 m:spp=120 m:x_original=0 m:drgxcoord=0 m:gisno=270227 m:drgycoord=0 m:blsd=70 m:des_spp1=0 m:blsdval=70 m:locsite=1 m:tr_rec=270227 m:grow=99 m:locunit=17635
```

## Meta Commands

```ls
metric m:tr_rec p:integer l:Tr_rec t:dataTypeName=number

metric m:locunit p:integer l:Locunit t:dataTypeName=number

metric m:locsite p:integer l:Locsite t:dataTypeName=number

metric m:spp p:integer l:Spp t:dataTypeName=number

metric m:gisno p:integer l:Gisno t:dataTypeName=number

metric m:drgxcoord p:integer l:Drgxcoord t:dataTypeName=number

metric m:drgycoord p:integer l:Drgycoord t:dataTypeName=number

metric m:x_original p:integer l:X_original t:dataTypeName=number

metric m:y_original p:long l:Y_original t:dataTypeName=number

metric m:des_spp1 p:integer l:DES_SPP1 t:dataTypeName=number

metric m:tg_pg p:integer l:TG_PG t:dataTypeName=number

metric m:grow p:integer l:GROW t:dataTypeName=number

metric m:blsd p:integer l:BLSD t:dataTypeName=number

metric m:blsdval p:integer l:BLSDVAL t:dataTypeName=number

entity e:vt5t-mscf l:"Street Tree Inventory - 1990s" t:url=https://data.lacity.org/api/views/vt5t-mscf

property e:vt5t-mscf t:meta.view v:id=vt5t-mscf v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Street Tree Inventory - 1990s"

property e:vt5t-mscf t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vt5t-mscf t:meta.view.owner v:id=vb5u-hhhh v:screenName="Peter Marx" v:displayName="Peter Marx"

property e:vt5t-mscf t:meta.view.tableauthor v:id=vb5u-hhhh v:screenName="Peter Marx" v:roleName=publisher v:displayName="Peter Marx"
```

## Top Records

```ls
| trees_id | trees_id2   | tr_rec | locarea         | locunit | locsubunit | locsite | spp | common                    | botanical                 | on_strt      | from_strt       | to_strt            | gisno  | ext  | area | treeloc | dbh  | inv_date            | drgmapname | drglayer | drgxcoord | drgycoord | x_original | y_original | dir | des_spp1 | trunks | ht   | cond | mt         | pest | veg  | wellstat | wellcov | guard | ut   | utob | cd | dist | tg_pg | tg_coord | cmap | hd   | grow | hist_id | exp_id | up_date | staff | un | blsd | download | notes | city_name   | blsdval | mdist | growmatl             | growsize | growtype | type     | x        | y       | utdescription | utdescription_other | curb | stock_size | sidewalk | trees_street_id | date_root_prune_curb | date_root_prune_driveway | date_root_prune_sidewalk | note_id | 
| ======== | =========== | ====== | =============== | ======= | ========== | ======= | === | ========================= | ========================= | ============ | =============== | ================== | ====== | ==== | ==== | ======= | ==== | =================== | ========== | ======== | ========= | ========= | ========== | ========== | === | ======== | ====== | ==== | ==== | ========== | ==== | ==== | ======== | ======= | ===== | ==== | ==== | == | ==== | ===== | ======== | ==== | ==== | ==== | ======= | ====== | ======= | ===== | == | ==== | ======== | ===== | =========== | ======= | ===== | ==================== | ======== | ======== | ======== | ======== | ======= | ============= | =================== | ==== | ========== | ======== | =============== | ==================== | ======================== | ======================== | ======= | 
| 2        | 384592f6173 | 329230 | YOAKUM DR       | 9655    | F          | 1       | 308 | NULL                      | NULL                      | YOAKUM DR    | DEADEND         | BENEDICT CANYON DR | 329230 | NULL | NULL | S       | 3-12 | 1991-06-19T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | O   | 0        | NULL   | 0-20 | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 5  | MT   | 32    | F2       | NULL | NULL | 99   | NULL    | NULL   | NULL    | BL    | 39 | 200  | NULL     | NULL  | LOS ANGELES | 200     | NULL  | NULL                 | NULL     | NULL     | original | -118.429 | 34.1137 | NULL          | NULL                | NULL | NULL       | NULL     | 402860          | NULL                 | NULL                     | NULL                     | NULL    | 
| 3        | 3845921a21e | 279656 | CHALON RD       | 13241   | F          | 1       | 308 | NULL                      | NULL                      | CHALON RD    | ARBUTUS DR      | WESTRIDGE RD       | 279656 | X    | NULL | S       | 3-12 | 1991-07-15T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | O   | 0        | NULL   | 0-20 | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 11 | MT   | 30    | F5       | NULL | NULL | 99   | NULL    | NULL   | NULL    | CS    | 25 | 54   | NULL     | NULL  | LOS ANGELES | 54      | NULL  | NULL                 | NULL     | NULL     | original | -118.502 | 34.0775 | NULL          | NULL                | NULL | NULL       | NULL     | 123041          | NULL                 | NULL                     | NULL                     | NULL    | 
| 4        | 384591f857  | 270227 | VENTURA BL      | 17635   | F          | 1       | 120 | CHINESE FLAME TREE        | KOELREUTERIA BIPINNATA    | VENTURA BL   | ENCINO AV       | WHITE OAK AV       | 270227 | X    | NULL | S       | 3-6  | 1991-05-03T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | O   | 0        | NULL   | 0-20 | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 5  | WV   | 561   | D3       | NULL | NULL | 99   | NULL    | NULL   | NULL    | BL    | 8  | 70   | NULL     | NULL  | LOS ANGELES | 70      | NULL  | ORGANIC (SOIL, TURF) | NULL     | NULL     | original | -118.517 | 34.1622 | NULL          | NULL                | NULL | NULL       | NULL     | 375483          | NULL                 | NULL                     | NULL                     | NULL    | 
| 5        | 384591f875  | 270237 | VENTURA BL      | 17701   | S          | 3       | 597 | VACANT/INADEQUATE SPACING | VACANT/INADEQUATE SPACING | WHITE OAK AV | VENTURA BL      | MAGNOLIA BL        | 270237 | NULL | NULL | S       | NULL | 1991-05-06T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | O   | 0        | NULL   | 0-20 | NULL | NO REPLANT | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 11 | MT   | 21    | D2       | NULL | NULL | 99   | NULL    | NULL   | NULL    | BL    | 8  | 93   | NULL     | NULL  | LOS ANGELES | 93      | NULL  | NULL                 | NULL     | NULL     | original | -118.519 | 34.1625 | NULL          | NULL                | NULL | NULL       | NULL     | 375488          | NULL                 | NULL                     | NULL                     | NULL    | 
| 6        | 3845907c104 | 191749 | DAY ST          | 7929    | F          | 1       | 308 | NULL                      | NULL                      | DAY ST       | DEADEND         | WOODWARD AV        | 191749 | NULL | NULL | S       | 3-12 | 1991-04-04T00:00:00 | NULL       | NULL     | 0         | 0         | 118305000  | 34254800   | O   | 0        | NULL   | 0-20 | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 2  | EV   | 10    | E3       | NULL | NULL | 99   | NULL    | NULL   | NULL    | WW    | 43 | 88   | NULL     | NULL  | LOS ANGELES | 88      | NULL  | NULL                 | NULL     | NULL     | original | -118.305 | 34.2547 | NULL          | NULL                | NULL | NULL       | NULL     | 147380          | NULL                 | NULL                     | NULL                     | NULL    | 
| 7        | 384592962ed | 306579 | WOODMAN AV      | 4130    | F          | 1       | 308 | NULL                      | NULL                      | WOODMAN AV   | VALLEY VISTA BL | VENTURA BL         | 306579 | NULL | NULL | S       | 0-3  | 1991-06-12T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | E   | 0        | NULL   | 0-20 | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 13 | MT   | 22    | F4       | NULL | NULL | 99   | NULL    | NULL   | NULL    | JL    | 27 | 14   | NULL     | NULL  | LOS ANGELES | 14      | NULL  | NULL                 | NULL     | NULL     | original | 0        | 0       | NULL          | NULL                | NULL | NULL       | NULL     | 400490          | NULL                 | NULL                     | NULL                     | NULL    | 
| 8        | 384591ff26  | 272300 | WOODLEY AV      | 4604    | F          | 1       | 308 | NULL                      | NULL                      | WOODLEY AV   | VALLEY VISTA BL | VENTURA BL         | 272300 | NULL | NULL | S       | 0-3  | 1991-05-17T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | E   | 0        | NULL   | 0-20 | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 11 | MT   | 22    | A2       | NULL | NULL | 99   | NULL    | NULL   | NULL    | WW    | 13 | 52   | NULL     | NULL  | LOS ANGELES | 52      | NULL  | NULL                 | NULL     | NULL     | original | -118.484 | 34.155  | NULL          | NULL                | NULL | NULL       | NULL     | 400030          | NULL                 | NULL                     | NULL                     | NULL    | 
| 9        | 384591fa1b2 | 270967 | VISTA DE ORO AV | 4541    | S          | 1       | 308 | NULL                      | NULL                      | CHAPTER DR   | VISTA DE ORO AV | DEADEND            | 270967 | NULL | NULL | S       | 0-3  | 1991-05-06T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | O   | 0        | NULL   | 0-20 | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 11 | MT   | 13    | E3       | NULL | NULL | 99   | NULL    | NULL   | NULL    | WW    | 2  | 197  | NULL     | NULL  | LOS ANGELES | 197     | NULL  | NULL                 | NULL     | NULL     | original | -118.581 | 34.1525 | NULL          | NULL                | NULL | NULL       | NULL     | 381993          | NULL                 | NULL                     | NULL                     | NULL    | 
| 10       | 384591fa1b5 | 270968 | VISTA DE ORO AV | 4541    | S          | 2       | 308 | NULL                      | NULL                      | CHAPTER DR   | VISTA DE ORO AV | DEADEND            | 270968 | NULL | NULL | S       | 0-3  | 1991-05-06T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | O   | 0        | NULL   | 0-20 | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 11 | MT   | 13    | E3       | NULL | NULL | 99   | NULL    | NULL   | NULL    | WW    | 2  | 197  | NULL     | NULL  | LOS ANGELES | 197     | NULL  | NULL                 | NULL     | NULL     | original | -118.581 | 34.1525 | NULL          | NULL                | NULL | NULL       | NULL     | 381993          | NULL                 | NULL                     | NULL                     | NULL    | 
| 11       | 384591b927b | 255699 | IDAHO AV        | 11867   | S          | 1       | 26  | AMERICAN SWEETGUM         | LIQUIDAMBAR STYRACIFLUA   | WESTGATE AV  | SANTA MONICA BL | IDAHO AV           | 255699 | NULL | NULL | S       | NULL | 1991-05-28T00:00:00 | NULL       | NULL     | 0         | 0         | 0          | 0          | O   | 0        | NULL   | 50 + | NULL | NULL       | NULL | NULL | NULL     | NULL    | NULL  | NULL | NULL | 11 | MT   | 41    | B4       | NULL | NULL | 99   | NULL    | NULL   | NULL    | CS    | 18 | 512  | NULL     | NULL  | LOS ANGELES | 512     | NULL  | NULL                 | NULL     | NULL     | original | -118.458 | 34.0407 | NULL          | NULL                | NULL | NULL       | NULL     | 216960          | NULL                 | NULL                     | NULL                     | NULL    | 
```