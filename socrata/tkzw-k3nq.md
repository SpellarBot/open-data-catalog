# Street Tree List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-tree-list-9464e) |
| Metadata | [Link](https://data.sfgov.org/api/views/tkzw-k3nq) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tkzw-k3nq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tkzw-k3nq/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tkzw-k3nq |
| Name | Street Tree List |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | trees |
| Created | 2012-09-25T00:51:48Z |
| Publication Date | 2016-06-03T21:07:15Z |

## Description

List of dpw maintained street trees including: Planting date, species, and location

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | treeid         | TreeID         | text          | number        |
| Yes      | series tag     | qlegalstatus   | qLegalStatus   | text          | text          |
| Yes      | series tag     | qspecies       | qSpecies       | text          | text          |
| No       |                | qaddress       | qAddress       | text          | text          |
| Yes      | numeric metric | siteorder      | SiteOrder      | number        | number        |
| Yes      | series tag     | qsiteinfo      | qSiteInfo      | text          | text          |
| Yes      | series tag     | planttype      | PlantType      | text          | text          |
| Yes      | series tag     | qcaretaker     | qCaretaker     | text          | text          |
| Yes      | series tag     | qcareassistant | qCareAssistant | text          | text          |
| Yes      | time           | plantdate      | PlantDate      | calendar_date | calendar_date |
| Yes      | numeric metric | dbh            | DBH            | number        | number        |
| Yes      | series tag     | plotsize       | PlotSize       | text          | text          |
| Yes      | series tag     | permitnotes    | PermitNotes    | text          | text          |
| No       |                | xcoord         | XCoord         | number        | number        |
| No       |                | ycoord         | YCoord         | number        | number        |
| No       |                | latitude       | Latitude       | number        | number        |
| No       |                | longitude      | Longitude      | number        | number        |
```

## Time Field

```ls
Value = plantdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = qaddress,xcoord,ycoord,latitude,longitude
```

## Data Commands

```ls
series e:tkzw-k3nq d:1988-07-21T00:00:00.000Z t:qspecies="Myoporum laetum :: Myoporum" t:permitnotes="Permit Number 25401" t:plotsize="Width 0ft" t:qcaretaker=Private t:qlegalstatus="Permitted Site" t:treeid=141565 t:qsiteinfo="Sidewalk: Curb side : Cutout" t:planttype=Tree m:siteorder=1 m:dbh=21

series e:tkzw-k3nq d:2017-03-20T00:00:00.000Z t:qspecies="Metrosideros excelsa :: New Zealand Xmas Tree" t:permitnotes="Permit Number 779625" t:plotsize="Width 4ft" t:qcaretaker=Private t:qlegalstatus=Undocumented t:treeid=232565 t:qsiteinfo="Sidewalk: Curb side : Yard" t:planttype=Tree m:siteorder=1 m:dbh=3

series e:tkzw-k3nq d:2016-07-21T08:10:41.000Z t:qspecies="Pinus radiata :: Monterey Pine" t:plotsize=10x30 t:qcaretaker=DPW t:qlegalstatus="DPW Maintained" t:treeid=119263 t:qsiteinfo="Median : Yard" t:planttype=Tree m:siteorder=1
```

## Meta Commands

```ls
metric m:siteorder p:integer l:SiteOrder t:dataTypeName=number

metric m:dbh p:integer l:DBH t:dataTypeName=number

entity e:tkzw-k3nq l:"Street Tree List" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/tkzw-k3nq

property e:tkzw-k3nq t:meta.view v:id=tkzw-k3nq v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=80 v:name="Street Tree List" v:attribution="San Francisco Department of Public Works"

property e:tkzw-k3nq t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tkzw-k3nq t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:tkzw-k3nq t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| treeid | qlegalstatus   | qspecies                                                             | qaddress          | siteorder | qsiteinfo                    | planttype | qcaretaker | qcareassistant | plantdate           | dbh | plotsize  | permitnotes          | xcoord        | ycoord        | latitude         | longitude         | 
| ====== | ============== | ==================================================================== | ================= | ========= | ============================ | ========= | ========== | ============== | =================== | === | ========= | ==================== | ============= | ============= | ================ | ================= | 
| 141565 | Permitted Site | Myoporum laetum :: Myoporum                                          | 501X Baker St     | 1         | Sidewalk: Curb side : Cutout | Tree      | Private    |                | 1988-07-21T00:00:00 | 21  | Width 0ft | Permit Number 25401  | 6000609       | 2110829       | 37.7759676911831 | -122.441396661871 | 
| 232565 | Undocumented   | Metrosideros excelsa :: New Zealand Xmas Tree                        | 940 Elizabeth St  | 1         | Sidewalk: Curb side : Yard   | Tree      | Private    |                | 2017-03-20T00:00:00 | 3   | Width 4ft | Permit Number 779625 | 6000396.48544 | 2101998.8644  | 37.7517102172731 | -122.441498017841 | 
| 119263 | DPW Maintained | Pinus radiata :: Monterey Pine                                       | 495X Lakeshore Dr | 1         | Median : Yard                | Tree      | DPW        |                |                     |     | 10x30     |                      |               |               |                  |                   | 
| 207368 | Undocumented   | Ligustrum japonicum :: Japanese Privet                               | 920 Kirkham St    | 1         | Sidewalk: Curb side : Cutout | Tree      | Private    |                |                     | 6   | Width 1ft |                      | 5992009.48044 | 2105269.9271  | 37.760210314285  | -122.47073935813  | 
| 188702 | DPW Maintained | Acacia melanoxylon :: Blackwood Acacia                               | 1501 Evans Ave    | 2         | :                            | Tree      | DPW        |                |                     | 17  | Width 4ft |                      | 6015994.71985 | 2098219.31717 | 37.7422086702947 | -122.387293152263 | 
| 141566 | Permitted Site | Myoporum laetum :: Myoporum                                          | 501X Baker St     | 2         | Sidewalk: Curb side : Cutout | Tree      | Private    |                |                     | 14  | Width 0ft |                      | 6000587.8822  | 2110733.5952  | 37.7757045307049 | -122.441462866076 | 
| 188697 | DPW Maintained | Acacia melanoxylon :: Blackwood Acacia                               | 1301 Evans Ave    | 13        | :                            | Tree      | DPW        |                |                     | 15  | Width 3ft |                      | 6017236.81305 | 2097292.98379 | 37.7397338556296 | -122.38293388291  | 
| 122650 | Permitted Site | Acer rubrum :: Red Maple                                             | 300x Hickory St   | 6         | Sidewalk: Curb side : Cutout | Tree      | Private    |                | 2016-11-10T00:00:00 | 3   | 3x3       |                      |               |               |                  |                   | 
| 203507 | Undocumented   | Agonis flexuosa :: Peppermint Willow                                 | 920 Kirkham St    | 2         | Sidewalk: Curb side : Cutout | Tree      | Private    |                |                     | 23  | Width 3ft |                      | 5991972.62617 | 2105259.84917 | 37.7601805116332 | -122.470866084321 | 
| 122670 | Permitted Site | Lyonothamnus floribundus subsp. asplenifolius :: Santa Cruz Ironwood | 301x Hickory St   | 3         | Sidewalk: Curb side : Cutout | Tree      | Private    |                | 2016-11-10T00:00:00 | 3   | 3X3       |                      |               |               |                  |                   | 
```