# Seattle Communities Online Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-communities-online-inventory-7c00c) |
| Metadata | [Link](https://data.seattle.gov/api/views/5ytf-wban) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/5ytf-wban/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/5ytf-wban/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 5ytf-wban |
| Name | Seattle Communities Online Inventory |
| Attribution | Community Technology, Department of Information Technology, City of Seattle |
| Category | Community |
| Tags | neighborhood groups, blogs, wikis, facebook, twitter |
| Created | 2010-03-18T21:03:56Z |
| Publication Date | 2015-02-19T00:15:46Z |

## Description

This dataset provides a list of websites, blogs, wikis, Twitter feeds, and Facebook pages associated with neighborhood-specific groups and organizations. To add a new site visit http://www.seattle.gov/communitiesonline/addform.htm/jmzd-2qjz

## Columns

```ls
| Included | Schema Type | Field Name           | Name                  | Data Type | Render Type |
| ======== | =========== | ==================== | ===================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | name                 | Name                  | text      | text        |
| Yes      | series tag  | url                  | url                   | url       | url         |
| Yes      | series tag  | neighborhood         | Neighborhood          | text      | text        |
| Yes      | series tag  | district             | district              | text      | text        |
| Yes      | series tag  | category             | category              | text      | text        |
| Yes      | series tag  | community_commercial | community, commercial | text      | text        |
| Yes      | series tag  | type                 | type                  | text      | text        |
| Yes      | series tag  | region               | region                | text      | text        |
| Yes      | series tag  | council_district     | Council District      | text      | number      |
| Yes      | series tag  | email_contact        | Email Contact         | email     | email       |
| No       |             | validate             | Validate              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = validate
```

## Data Commands

```ls
series e:5ytf-wban d:2015-02-03T09:25:58.000Z t:region=E t:community_commercial=community t:category="15th avenue residents" t:name="15th Ave Community" t:neighborhood="Capitol Hill" t:council_district=3 t:district=East t:type="email list" t:url=http://groups.yahoo.com/group/15thAve_Community/ t:email_contact=15thave_community@yahoogroups.com m:row_number.5ytf-wban=1

series e:5ytf-wban d:2015-02-03T09:25:58.000Z t:region=SW t:community_commercial=community t:category="neighborhood association" t:name="Admiral Neighborhood Association" t:neighborhood=Admiral t:council_district=1 t:district=Southwest t:type="email list" t:url=http://groups.yahoo.com/group/AdmiralNeighborhood/ t:email_contact=admiralneighborhood@yahoogroups.com m:row_number.5ytf-wban=2

series e:5ytf-wban d:2015-02-03T09:25:58.000Z t:region=SW t:community_commercial=community t:category="news, council meetings" t:name="Alki News/Alki Community Council" t:neighborhood=Alki t:council_district=1 t:district=Southwest t:type=blog t:url=http://alkinews.wordpress.com/ t:email_contact=larry@alkinews.com m:row_number.5ytf-wban=3
```

## Meta Commands

```ls
metric m:row_number.5ytf-wban p:long l:"Row Number"

entity e:5ytf-wban l:"Seattle Communities Online Inventory" t:attribution="Community Technology, Department of Information Technology, City of Seattle" t:url=https://data.seattle.gov/api/views/5ytf-wban

property e:5ytf-wban t:meta.view v:id=5ytf-wban v:category=Community v:attributionLink=http://www.seattle.gov/communitiesonline/neighborhoods.htm v:averageRating=0 v:name="Seattle Communities Online Inventory" v:attribution="Community Technology, Department of Information Technology, City of Seattle"

property e:5ytf-wban t:meta.view.owner v:id=mfpe-tfi4 v:screenName="Community Technology" v:displayName="Community Technology"

property e:5ytf-wban t:meta.view.tableauthor v:id=mfpe-tfi4 v:screenName="Community Technology" v:roleName=publisher v:displayName="Community Technology"
```

## Top Records

```ls
| :updated_at | name                                  | url                                                         | neighborhood   | district         | category                           | community_commercial | type       | region | council_district | email_contact                       | validate | 
| =========== | ===================================== | =========================================================== | ============== | ================ | ================================== | ==================== | ========== | ====== | ================ | =================================== | ======== | 
| 1422955558  | 15th Ave Community                    | [http://groups.yahoo.com/group/15thAve_Community/, null]    | Capitol Hill   | East             | 15th avenue residents              | community            | email list | E      | 3                | 15thave_community@yahoogroups.com   |          | 
| 1422955558  | Admiral Neighborhood Association      | [http://groups.yahoo.com/group/AdmiralNeighborhood/, null]  | Admiral        | Southwest        | neighborhood association           | community            | email list | SW     | 1                | admiralneighborhood@yahoogroups.com |          | 
| 1422955558  | Alki News/Alki Community Council      | [http://alkinews.wordpress.com/, null]                      | Alki           | Southwest        | news, council meetings             | community            | blog       | SW     | 1                | larry@alkinews.com                  |          | 
| 1422955558  | All About Belltown                    | [http://www.belltown.org/, null]                            | Belltown       | Downtown         | community council                  | community            | website    | W      | 7                | info@belltown.org                   |          | 
| 1422955558  | All About South Park                  | [http://www.allaboutsouthpark.com/, null]                   | South Park     | Greater Duwamish | neighborhood info                  | community            | website    | S      | 1                | info@allaboutsouthpark.com          |          | 
| 1422955558  | Angel-Morgan Neighborhood Association | [http://groups.yahoo.com/group/angelmorganneighbors/, null] | Brighton       | Southeast        | crime, events, neighborhood-issues | community            | website    | SE     | 2                | angelmorganneighbors@yahoo.com      |          | 
| 1422955558  | ArtsWest                              | [http://www.artswest.org/?q=node/28, null]                  | West Seattle   | Southwest        | arts                               | community            | website    | SW     | 1                | sandyf@artswest.org                 |          | 
| 1422955558  | At Large in Ballard                   | [http://blog.seattlepi.com/ballard/, null]                  | Ballard        | Ballard          | news, human interest               | commercial           | blog       | NW     | 6                | newmedia@seattlepi.com              |          | 
| 1422955558  | Aurora Seattle                        | [http://www.auroraseattle.com/, null]                       | Regional Sites | Northeast        | news, traffic, planning            | community            | blog       | NE     | 5                |                                     |          | 
| 1422955558  | Ballard Chamber of Commerce           | [http://www.ballardchamber.com/, null]                      | Ballard        | Ballard          | chamber of commerce                | community            | website    | NW     | 6                | info@ballardchamber.com             |          | 
```