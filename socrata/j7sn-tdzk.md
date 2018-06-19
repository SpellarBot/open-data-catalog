# Public Art Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-art-data-92959) |
| Metadata | [Link](https://data.seattle.gov/api/views/j7sn-tdzk) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/j7sn-tdzk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/j7sn-tdzk/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | j7sn-tdzk |
| Name | Public Art Data |
| Category | Community |
| Created | 2012-04-11T18:24:11Z |
| Publication Date | 2012-04-28T18:08:47Z |

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | sac_id            | sac_id            | text      | text        |
| Yes      | series tag  | project           | project           | text      | text        |
| Yes      | series tag  | artist_first_name | artist_first_name | text      | text        |
| Yes      | series tag  | artist_last_name  | artist_last_name  | text      | text        |
| Yes      | series tag  | title             | title             | text      | text        |
| Yes      | series tag  | description       | description       | text      | text        |
| Yes      | series tag  | classification    | classification    | text      | text        |
| Yes      | series tag  | media             | media             | text      | text        |
| Yes      | series tag  | measurements      | measurements      | text      | text        |
| No       |             | date              | date              | text      | text        |
| Yes      | series tag  | location          | location          | text      | text        |
| No       |             | address           | address           | text      | text        |
| No       |             | latitude          | latitude          | number    | number      |
| No       |             | longitude         | longitude         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date,address,latitude,longitude
```

## Data Commands

```ls
series e:j7sn-tdzk d:2012-04-11T11:24:15.000Z t:project="CENTRAL LIBRARY" t:title="Fountain of Wisdom" t:location="Central Library, Spring St Plaza" t:sac_id=ESD00.074.02 t:artist_last_name=Tsutakawa t:description='' t:classification=Sculpture t:artist_first_name=George t:media="Welded bronze" m:row_number.j7sn-tdzk=1

series e:j7sn-tdzk d:2012-04-11T11:24:15.000Z t:project="SEATTLE CENTER SCULPTURE GARDEN" t:title="Moon Gates" t:location="Space Needle Sculpture Garden" t:sac_id=CL77.025 t:artist_last_name=Chase t:description='' t:classification=Sculpture t:artist_first_name=Doris m:row_number.j7sn-tdzk=2

series e:j7sn-tdzk d:2012-04-11T11:24:15.000Z t:project="WEST GILMAN BRIDGE" t:title="Seattle Scatter Piece" t:location="West Gilman Bridge" t:sac_id=CL99.053 t:artist_last_name=Lere t:description='' t:classification=Sculpture t:artist_first_name=Mark t:media="Concrete, terrazzo" m:row_number.j7sn-tdzk=3
```

## Meta Commands

```ls
metric m:row_number.j7sn-tdzk p:long l:"Row Number"

entity e:j7sn-tdzk l:"Public Art Data" t:url=https://data.seattle.gov/api/views/j7sn-tdzk

property e:j7sn-tdzk t:meta.view v:id=j7sn-tdzk v:category=Community v:averageRating=0 v:name="Public Art Data"

property e:j7sn-tdzk t:meta.view.license v:name="Public Domain"

property e:j7sn-tdzk t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:j7sn-tdzk t:meta.view.tableauthor v:id=n96i-9u3b v:screenName="Pierce, Jeffrey" v:roleName=publisher v:displayName="Pierce, Jeffrey"
```

## Top Records

```ls
| :updated_at | sac_id           | project                                             | artist_first_name | artist_last_name | title                                        | description                                                                                                                                                                                                    | classification          | media                                                               | measurements                                                                                              | date                     | location                                         | address                   | latitude  | longitude   | 
| =========== | ================ | =================================================== | ================= | ================ | ============================================ | ============================================================================================================================================================================================================== | ======================= | =================================================================== | ========================================================================================================= | ======================== | ================================================ | ========================= | ========= | =========== | 
| 1334143455  | ESD00.074.02     | CENTRAL LIBRARY                                     | George            | Tsutakawa        | Fountain of Wisdom                           | ''                                                                                                                                                                                                             | Sculpture               | Welded bronze                                                       |                                                                                                           | 1957-60                  | Central Library, Spring St Plaza                 | 1000 4th Ave              | 47.6065   | -122.33312  | 
| 1334143455  | CL77.025         | SEATTLE CENTER SCULPTURE GARDEN                     | Doris             | Chase            | Moon Gates                                   | ''                                                                                                                                                                                                             | Sculpture               |                                                                     |                                                                                                           | 6/23/99                  | Space Needle Sculpture Garden                    | 305 Harrison St           | 47.620033 | -122.348917 | 
| 1334143455  | CL99.053         | WEST GILMAN BRIDGE                                  | Mark              | Lere             | Seattle Scatter Piece                        | ''                                                                                                                                                                                                             | Sculpture               | Concrete, terrazzo                                                  |                                                                                                           | 1991                     | West Gilman Bridge                               | 23rd Ave W & Gilman Ave W | 47.632467 | -122.37565  | 
| 1334143455  | PR99.077         | DOUGLAS-TRUTH BRANCH LIBRARY                        | Richard           | Spaulding        | Renouveau                                    | ''                                                                                                                                                                                                             | Structures              | Stained glass                                                       |                                                                                                           | 1979                     | Douglas Truth Branch Library                     | 2300 E Yesler St          | 47.601833 | -122.301767 | 
| 1334143455  | CL77.026         | SECOND AVENUE PROJECT                               | Kurt              | Kiefer           | Second Avenue Additions                      | ''                                                                                                                                                                                                             | Structures              | Permanently sited                                                   |                                                                                                           | 2/15/00                  | 2nd Ave & Denny Wy                               | 2nd Ave & Denny Wy        | 47.61805  | -122.35205  | 
| 1334143455  | CL77.023         | SEATTLE ARTISTS 1990                                |                   |                  | Untitled (Kiosk)                             | ''                                                                                                                                                                                                             | Sculpture               | Mixed media; wood; metal                                            | 108x45x22"                                                                                                | MARCH- JUNE 1994         | Belltown                                         | 4th Ave & Bell St         | 47.615617 | -122.344583 | 
| 1334143455  | CL91.015a,b      | IN PUBLIC: SEATTLE 1991                             | Edgar Hachivi     | Heap of Birds    | Day/Night                                    | 'Lutshootseed and English texts painted on panels installed on either side of a historical bust of Chief Sealth dedicated to the many transient intertribal native people who live on the streets of Seattle.' | IN PUBLIC: SEATTLE 1991 | Porcelain enamel on steel panel                                     | 42" X 84" EACH                                                                                            | JUNE 1991-JANUARY 1992   | Pioneer Square                                   | 1st Ave & Yesler Wy       | 47.601983 | -122.33395  | 
| 1334143455  | PR81.014a-c      | JOSE RIZAL PARK                                     | Val               | Laigo            | East is West                                 | 'Wall mural of ceramic and glass tile depicting Filipino history.'                                                                                                                                             | 2-Dimensional           | Ceramic & glass tile                                                | 12'x14'7x3'2.5"                                                                                           | FEBRUARY 1978- JUNE 1981 | Dr. Jose P. Rizal Park                           | 1008 12th Ave S           | 47.59205  | -122.317417 | 
| 1334143455  | GCK74.074        | ALKI BEACH                                          | Bartoldi          | After            | Little Liberty                               | 'Replica of the Statue of Liberty'                                                                                                                                                                             | Sculpture               | Copper alloy                                                        | 6'10"x3'6"x2'11"                                                                                          | ca. 1952                 | Alki Beach                                       | 61st Ave SW & Alki Ave SW | 47.579383 | -122.410633 | 
| 1334143455  | LIB06.011.01-.03 | LIBRARIES FOR ALL - CENTRAL LIBRARY/LIBRARY UNBOUND | Mandy             | Greer            | Babe, The Phoenix Fairy, and The Magic Grove | 'The three artworks for the Faye G. Allen Children's Center are based on a series of folk tale themes found in the folklore section of the Central Library. '                                                  | Sculpture               | Wood, steel, pink foam, paper mache fabric, beads, glitter, acrylic | Babe - .01: 4'h x 8'w x 3.5'd; Phoenix Fairy - .02: 5'h x 6.5'w x 4'd; Magic Grove - .03 4'h x 8'w x 10'd | 2005. 2005, 2006         | Central Library, Faye G. Allen Children's Center | 1000 4th Ave              | 47.6065   | -122.333117 | 
```