# SF Civic Art Collection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sf-civic-art-collection-a73e5) |
| Metadata | [Link](https://data.sfgov.org/api/views/zfw6-95su) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/zfw6-95su/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/zfw6-95su/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | zfw6-95su |
| Name | SF Civic Art Collection |
| Attribution | San Francisco Arts Commission |
| Category | Culture and Recreation |
| Tags | civic art collection, historic monuments, public art, san francisco arts commission |
| Created | 2011-11-09T23:16:47Z |
| Publication Date | 2011-11-09T23:19:22Z |

## Description

This data set includes all of the publicly-sited works in the Civic Art Collection, which includes historic monuments, murals, and artworks commissioned through the City's Public Art Program. The data set includes the following categories: artist name, title of work, medium, dimensions and location.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | id_                  | _id_                 | text      | text        |
| Yes      | series tag  | rev                  | _rev                 | text      | text        |
| Yes      | series tag  | accession_id         | accession_id         | text      | text        |
| Yes      | series tag  | artist               | artist               | text      | text        |
| Yes      | time        | created_at           | created_at           | date      | date        |
| Yes      | series tag  | credit_line          | credit_line          | text      | text        |
| Yes      | series tag  | display_dimensions   | display_dimensions   | text      | text        |
| Yes      | series tag  | geometry             | geometry             | text      | text        |
| Yes      | series tag  | location_description | location_description | text      | text        |
| Yes      | series tag  | medium               | medium               | text      | text        |
| Yes      | series tag  | source               | source               | text      | text        |
| Yes      | series tag  | title                | title                | text      | text        |
```

## Time Field

```ls
Value = created_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:zfw6-95su d:2011-11-09T15:16:49.000Z t:title=title t:rev=_rev t:source=source t:id_=_id t:artist=artist t:display_dimensions=display_dimensions t:location_description=location_description t:accession_id=accession_id t:medium=medium t:credit_line=credit_line t:geometry=geometry m:row_number.zfw6-95su=1

series e:zfw6-95su d:1970-01-01T00:33:15.000Z t:title="Promenade Ribbon" t:rev=2-2a0d31161230cdd59c47cbf4459ad806 t:source="San Francisco Arts Commission" t:id_=63daabb62278559f8a0643be882613c5 t:artist="Acconci, Saitowitz and Soloman" t:display_dimensions="2 1/2 miles X 5 feet" t:location_description="Public Display : District 3 : Embarcadero/Waterfront" t:accession_id=1995.18 t:medium="Black concrete, with a strip of glass blocks, to be illuminated at night" t:credit_line="Commissioned by the San Francisco Art Commission for the Waterfront Project." t:geometry="{""type"":""Point"",""coordinates"":[-122.4120591,37.8085303]}" m:row_number.zfw6-95su=2

series e:zfw6-95su d:2011-11-09T15:16:49.000Z t:title="Two Wings for Wall and Person" t:rev=2-8418bc9b09e27aba350721c0de8b98ee t:source="San Francisco Arts Commission" t:id_=63daabb62278559f8a0643be88261503 t:artist="Acconci, Vito" t:display_dimensions="26 1/2"" H X 41"" W" t:location_description="International Airport : T3 : Lower Level" t:accession_id=1986.2 t:medium="Etching on Paper" t:credit_line="Purchased by the San Francisco Art Commission for the San Francisco International Airport" t:geometry="{""type"":""Point"",""coordinates"":[-122.389979,37.615223]}" m:row_number.zfw6-95su=3
```

## Meta Commands

```ls
metric m:row_number.zfw6-95su p:long l:"Row Number"

entity e:zfw6-95su l:"SF Civic Art Collection" t:attribution="San Francisco Arts Commission" t:url=https://data.sfgov.org/api/views/zfw6-95su

property e:zfw6-95su t:meta.view v:id=zfw6-95su v:category="Culture and Recreation" v:attributionLink=http://www.sfartscommission.org/ v:averageRating=0 v:name="SF Civic Art Collection" v:attribution="San Francisco Arts Commission"

property e:zfw6-95su t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:zfw6-95su t:meta.view.owner v:id=et45-cce5 v:screenName=anhthang.dao-shah v:displayName=anhthang.dao-shah

property e:zfw6-95su t:meta.view.tableauthor v:id=et45-cce5 v:screenName=anhthang.dao-shah v:roleName=editor v:displayName=anhthang.dao-shah
```

## Top Records

```ls
| id_                              | rev                                | accession_id | artist                         | created_at | credit_line                                                                                 | display_dimensions          | geometry                                                 | location_description                                 | medium                                                                   | source                        | title                                                | 
| ================================ | ================================== | ============ | ============================== | ========== | =========================================================================================== | =========================== | ======================================================== | ==================================================== | ======================================================================== | ============================= | ==================================================== | 
| _id                              | _rev                               | accession_id | artist                         |            | credit_line                                                                                 | display_dimensions          | geometry                                                 | location_description                                 | medium                                                                   | source                        | title                                                | 
| 63daabb62278559f8a0643be882613c5 | 2-2a0d31161230cdd59c47cbf4459ad806 | 1995.18      | Acconci, Saitowitz and Soloman | 1995       | Commissioned by the San Francisco Art Commission for the Waterfront Project.                | 2 1/2 miles X 5 feet        | {"type":"Point","coordinates":[-122.4120591,37.8085303]} | Public Display : District 3 : Embarcadero/Waterfront | Black concrete, with a strip of glass blocks, to be illuminated at night | San Francisco Arts Commission | Promenade Ribbon                                     | 
| 63daabb62278559f8a0643be88261503 | 2-8418bc9b09e27aba350721c0de8b98ee | 1986.2       | Acconci, Vito                  |            | Purchased by the San Francisco Art Commission for the San Francisco International Airport   | 26 1/2" H X 41" W           | {"type":"Point","coordinates":[-122.389979,37.615223]}   | International Airport : T3 : Lower Level             | Etching on Paper                                                         | San Francisco Arts Commission | Two Wings for Wall and Person                        | 
| 63daabb62278559f8a0643be88261cca | 2-673d0a4a69a242adeb9852979da1e295 | 2002.7       | Acconci, Vito                  | 2002       | Commission for the San Francisco International Airport by the San Francisco Arts Commission |                             | {"type":"Point","coordinates":[-122.389979,37.615223]}   | Airport : International Terminal, transfer corridor  | mixed medium                                                             | San Francisco Arts Commission | Light Beams for the Sky of Transfer Cooridor         | 
| 63daabb62278559f8a0643be8826291a | 2-7ffc3bec57f459d5e478899e0f129bf0 | 1977.33      | Adams, Gloria Cozzo            | 1977       | Purchased by the San Francisco Art Commission for the San Francisco International Airport   | 481/2                       | {"type":"Point","coordinates":[-122.389979,37.615223]}   | Airport : Business and Finance                       | Acrylic and ink on canvas                                                | San Francisco Arts Commission | Cityscape #33                                        | 
| 63daabb62278559f8a0643be88262f39 | 2-b62dd5bf7e5f6b7e8a62cd78a216d052 | 1985.5.3     | Adams, Mark                    | 1982       | Purchased by the San Francisco Art Commission for the San Francisco International Airport   | 84" H X 144" W              | {"type":"Point","coordinates":[-122.389979,37.615223]}   | Airport : Terminal 2 : Meeting Area                  | Flat weave wool tapestry                                                 | San Francisco Arts Commission | Garden Outside the Gate (The Garden Tapestries)      | 
| 63daabb62278559f8a0643be88263e67 | 2-0857c73da09a7df8750689d22872110d | 1985.5.2     | Adams, Mark                    |            | Purchased by the San Francisco Art Commission for the San Francisco International Airport   | 84" H X 204" W              | {"type":"Point","coordinates":[-122.389979,37.615223]}   | Airport : Terminal 2 : Meeting Area                  | Flat weave wool tapestry                                                 | San Francisco Arts Commission | Garden in San Andreas Valley (The Garden Tapestries) | 
| 63daabb62278559f8a0643be882646e1 | 2-710e5caa71a55fd99577ae8e3a7ccbbf | 1985.5.1     | Adams, Mark                    | 1981       | Purchased by the San Francisco Art Commission for the San Francisco International Airport   | 84" H X 96" W               | {"type":"Point","coordinates":[-122.389979,37.615223]}   | Airport : Terminal 2 : Meeting Area                  | Flat weave wool tapestry                                                 | San Francisco Arts Commission | Pond in Golden Gate Park (The Garden Tapestries)     | 
| 63daabb62278559f8a0643be88264f4a | 2-6656bcb2f49f1ca2587677345cacf7b1 | 1902.1       | Aitken, Robert Ingersoll       | 1901       | Funds raised by public subscription. Dedicated by President Theodore Roosevelt.             | Figure: 12' H; Shaft: 83' H | {"type":"Point","coordinates":[-122.4075,37.7880556]}    | Public Display : District 6 : Union Square           | Bronze figure on granite base                                            | San Francisco Arts Commission | The Dewey Monument (Admiral George Dewey, 1837-1917) | 
| 63daabb62278559f8a0643be88265047 | 2-9fa9a901cf1dd3120ea9e85bd3334578 | 1899.1       | Aitken, Robert Ingersoll       | 1899       | Commissioned in 1898 by the architect of the Music Concourse and Claus Spreckles.           | 20' H                       | {"type":"Point","coordinates":[-122.4666711,37.7703537]} | Public Display : District 1 : GGP: Music Concourse   | Cast Concrete                                                            | San Francisco Arts Commission | Spandrels on Spreckles Temple of Music               | 
```