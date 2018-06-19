# Creative Workspaces, Performance Venues, Galleries & Museums

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/creative-workspaces-performance-venues-galleries-museums) |
| Metadata | [Link](https://data.austintexas.gov/api/views/qxfh-ycp7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/qxfh-ycp7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/qxfh-ycp7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | qxfh-ycp7 |
| Name | Creative Workspaces, Performance Venues, Galleries & Museums |
| Attribution | City of Austin Economic Development Department, Cultural Arts Division |
| Category | Neighborhood |
| Tags | economic development, art, culture, music, venues, museums, galleries |
| Created | 2016-11-10T21:21:02Z |
| Publication Date | 2016-11-14T15:56:41Z |

## Description

This is a listing of creative workspaces, performance venues, and exhibition venues collected through CAMP: The Cultural Asset Mapping Project. CAMP is an initiative of the Economic Development Department to map arts and cultural facilities in Austin. The entries in this dataset were compiled by the CAMP team within the Cultural Arts Division and collected through council district community mapping sessions and online surveys conducted over the summer of 2016. This dataset is only an excerpt of the complete CAMP dataset which will be available in early 2017. For more information on how this dataset was created, visit www.austintexas.gov/culturemapping or contact camp@austintexas.gov

This dataset represents only the information collected by Cultural Arts Division staff and community input through the 2016 Cultural Asset Mapping Project and does not represent an on-the-ground survey. This product has been produced by the Economic Development Department of the City of Austin for the sole purpose of informational reference. No warranty is made by the City of Austin regarding specific accuracy or completeness.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | name_common      | Name_common      | text      | text        |
| Yes      | series tag     | councildistrict  | CouncilDistrict  | text      | number      |
| No       |                | address_provided | Address_provided | text      | text        |
| Yes      | series tag     | assettype        | AssetType        | text      | text        |
| Yes      | series tag     | assettype_notes  | AssetType_notes  | text      | text        |
| Yes      | series tag     | live_music       | Live_Music       | text      | text        |
| Yes      | series tag     | event_venue      | Event Venue      | text      | text        |
| Yes      | numeric metric | capacity         | Capacity         | number    | text        |
| Yes      | series tag     | discipline       | Discipline       | text      | text        |
| Yes      | series tag     | discp_note       | Discp_note       | text      | text        |
| Yes      | series tag     | website          | Website          | text      | text        |
| Yes      | series tag     | web_notes        | Web_notes        | text      | text        |
| Yes      | series tag     | zip              | ZIP              | text      | number      |
| Yes      | series tag     | camp_id          | CAMP_ID          | text      | number      |
| Yes      | time           | year_updated     | year_updated     | number    | number      |
```

## Time Field

```ls
Value = year_updated
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address_provided
```

## Data Commands

```ls
series e:qxfh-ycp7 d:2016-01-01T00:00:00.000Z t:camp_id=3352 t:zip=78767 t:website=http://austin360amphitheater.com/ t:councildistrict=2 t:discp_note="Country, Pop, Rock" t:name_common="Austin 360 Amphitheater" t:web_notes="The Austin 360 Amphitheater is Austin's new destination to see the brightest stars in a world-class, open-air amphitheater. The venue, which is situated within Circuit of The Americas? 1,300-acre sports and entertainment complex, has room for up to 14," t:live_music="Live Music" t:discipline=Music t:assettype=Theater t:assettype_notes=Theater m:capacity=14000

series e:qxfh-ycp7 d:2016-01-01T00:00:00.000Z t:camp_id=3073 t:zip=78757 t:website=http://www.violinshop.com/Events/Information.php t:councildistrict=7 t:discp_note="Classical, Country" t:name_common="Blackerby Recital Hall" t:web_notes="Blackerby Recital Hall is a beautiful and spacious location for music recitals, meetings, and other special events. The 1,200 square foot hall features a stage large enough for medium-sized ensembles, a regularly-maintained grand piano, wonderful acousti" t:live_music="Live Music" t:discipline=Music t:assettype=Theater t:assettype_notes=Theater m:capacity=60

series e:qxfh-ycp7 d:2016-01-01T00:00:00.000Z t:camp_id=1450 t:zip=78711 t:website=http://www.thestoryoftexas.com/ t:councildistrict=1 t:name_common="Bullock Texas State History Museum | Texas Spirit Theater" t:web_notes="The Bob Bullock Texas State History Museum's beautiful Texas Spirit Theater is available for evening performances.  A seating capacity of 195 allows the audience to have a unique and personal experience with the artists. The 35' x 20' stage will accommod" t:live_music="Live Music" t:discipline=Film/TV/Media t:assettype=Theater t:assettype_notes="Movie Theater" m:capacity=2000
```

## Meta Commands

```ls
metric m:capacity p:long l:Capacity t:dataTypeName=number

entity e:qxfh-ycp7 l:"Creative Workspaces, Performance Venues, Galleries & Museums" t:attribution="City of Austin Economic Development Department, Cultural Arts Division" t:url=https://data.austintexas.gov/api/views/qxfh-ycp7

property e:qxfh-ycp7 t:meta.view v:id=qxfh-ycp7 v:category=Neighborhood v:attributionLink=http://austintexas.gov/culturemapping v:averageRating=0 v:name="Creative Workspaces, Performance Venues, Galleries & Museums" v:attribution="City of Austin Economic Development Department, Cultural Arts Division"

property e:qxfh-ycp7 t:meta.view.license v:name="Public Domain"

property e:qxfh-ycp7 t:meta.view.owner v:id=baie-bcjd v:screenName="Shirley Rempe" v:displayName="Shirley Rempe"

property e:qxfh-ycp7 t:meta.view.tableauthor v:id=baie-bcjd v:screenName="Shirley Rempe" v:roleName=publisher v:displayName="Shirley Rempe"
```

## Top Records

```ls
| name_common                                               | councildistrict | address_provided | assettype                 | assettype_notes | live_music | event_venue | capacity | discipline    | discp_note             | website                                          | web_notes                                                                                                                                                                                                                                                      | zip   | camp_id | year_updated | 
| ========================================================= | =============== | ================ | ========================= | =============== | ========== | =========== | ======== | ============= | ====================== | ================================================ | ============================================================================================================================================================================================================================================================== | ===== | ======= | ============ | 
| Austin 360 Amphitheater                                   | 2               | yes              | Theater                   | Theater         | Live Music |             | 14000    | Music         | Country, Pop, Rock     | http://austin360amphitheater.com/                | The Austin 360 Amphitheater is Austin's new destination to see the brightest stars in a world-class, open-air amphitheater. The venue, which is situated within Circuit of The Americas? 1,300-acre sports and entertainment complex, has room for up to 14,   | 78767 | 3352    | 2016         | 
| Austin City Limits Live At The Moody Theater (Acl Live)   | 9               | yes              | Theater                   | Theater         | Live Music |             |          | Music         |                        |                                                  |                                                                                                                                                                                                                                                                | 78701 | 555     | 2014         | 
| Blackerby Recital Hall                                    | 7               | yes              | Theater                   | Theater         | Live Music |             | 60       | Music         | Classical, Country     | http://www.violinshop.com/Events/Information.php | Blackerby Recital Hall is a beautiful and spacious location for music recitals, meetings, and other special events. The 1,200 square foot hall features a stage large enough for medium-sized ensembles, a regularly-maintained grand piano, wonderful acousti | 78757 | 3073    | 2016         | 
| Bullock Texas State History Museum | Texas Spirit Theater | 1               | yes              | Theater                   | Movie Theater   | Live Music |             | 2000     | Film/TV/Media |                        | http://www.thestoryoftexas.com/                  | The Bob Bullock Texas State History Museum's beautiful Texas Spirit Theater is available for evening performances. A seating capacity of 195 allows the audience to have a unique and personal experience with the artists. The 35' x 20' stage will accommod  | 78711 | 1450    | 2016         | 
| Cactus Cafe, University Of Texas At Austin                | 9               | yes              | Theater                   | Theater         | Live Music |             | 1200     | Music         | Country, Folk/Acoustic | http://www.utexas.edu/student/txunion/ae/cactus  | The Cactus Cafe is one of Austin's great acoustic music traditions. The Cactus is an intimate live music performance venue, and since the Cafe opened in February 1979, the Cactus has acquired a national reputation, showcasing the top local, regional, nat | 78712 | 1487    | 2014         | 
| Curtain Theatre                                           | 0               | yes              | Theater                   | Theater         | Live Music |             |          | Music         |                        |                                                  | A little-known replica of William Shakespeare's Globe theater has been constructed on the banks of Lake Austin, and is the home of Austin's only historical Shakespeare company "The Baron's Men" as well as Austin Shakespeare Festival. Built by l           | 78730 | 1908    | 2016         | 
| El Coliseo Austin                                         | 6               | yes              | Theater                   | Theater         | Live Music |             |          | Music         |                        | http://www.elcoliseoaustin.com/                  | El Coliseo Austin is a new, upscale live music venue featuring international music, artists, and DJs.                                                                                                                                                          | 78719 | 1560    | 2016         | 
| Go Dance Studio                                           | 0               | yes              | Artist Studios/ Workshops | Dance Studio    |            |             |          | Dance         | Dance                  | http://www.godancestudio.com                     | Austin's premier social dance studio, Go Dance teaches a wide variety of dance styles including Ballroom, Latin, Swing, Country Western, Salsa and Wedding Dances. We offer over 50 group classes each week and offer private lessons every weekday, evening a | 78738 | 2124    | 2014         | 
| Go Dance Studio                                           | 5               | yes              | Artist Studios/ Workshops | Dance Studio    |            |             |          | Dance         | Dance                  | http://www.godancestudio.com                     | Our staff of more than 30 instructors teach beginning through advanced students in over 30 dances including Ballroom, Latin, Swing, Country Western, Salsa and wedding dances. We offer over 50 group classes each week, and private lessons are available dur | 78745 | 2268    | 2014         | 
| Go Dance Studio                                           | 7               | yes              | Artist Studios/ Workshops | Dance Studio    |            |             |          | Dance         | Dance                  | http://www.godancestudio.com                     | We offer over 50 group classes each week, and private lessons are available during the daytime, evenings and weekends. Our studio is unique, because we offer instruction in social and competitive dancing across all genres of partner dancing. We love the  | 78757 | 2956    | 2014         | 
```