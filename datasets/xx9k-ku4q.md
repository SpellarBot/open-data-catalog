# State Art Collection Published 2016-05-25

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-art-collection-published-2016-05-25) |
| Metadata | [Link](https://data.wa.gov/api/views/xx9k-ku4q) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xx9k-ku4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xx9k-ku4q/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xx9k-ku4q |
| Name | State Art Collection Published 2016-05-25 |
| Attribution | Washington State Arts Commission (ArtsWA) |
| Category | Education |
| Tags | public art, culture, art, visual art, architecture, sculpture, paintings, state art collection, washington state arts commission, artswa, colleges, universities, artwork, work of art, heritage, ar... |
| Created | 2016-05-25T23:15:05Z |
| Publication Date | 2016-05-25T23:17:23Z |

## Description

Artworks included in this dataset are part of the State Art Collection, a collection that is publicly owned, publicly sited, and publicly selected.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | artwork_city      | ARTWORK CITY      | text      | text        |
| No       |                | arwork_address    | ARWORK ADDRESS    | text      | text        |
| Yes      | series tag     | zip_code          | ZIP CODE          | text      | text        |
| No       |                | artwork_latitude  | ARTWORK LATITUDE  | number    | number      |
| Yes      | series tag     | id_number         | ID NUMBER         | text      | text        |
| Yes      | series tag     | artist            | ARTIST            | text      | text        |
| Yes      | series tag     | title             | TITLE             | text      | text        |
| Yes      | numeric metric | date              | DATE              | number    | number      |
| Yes      | series tag     | materials         | MATERIALS         | text      | text        |
| Yes      | series tag     | measurements      | MEASUREMENTS      | text      | text        |
| Yes      | series tag     | credit_line       | CREDIT LINE       | text      | text        |
| Yes      | series tag     | artwork_site      | ARTWORK SITE      | text      | text        |
| Yes      | series tag     | specific_location | SPECIFIC LOCATION | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = arwork_address,artwork_latitude
```

## Data Commands

```ls
series e:xx9k-ku4q d:2016-01-01T00:00:00.000Z t:artwork_city=Aberdeen t:measurements="4 1/2 ft x 13 ft" t:title="The Grays Harbor College Tapestry" t:artwork_site="Grays Harbor College" t:materials="Cotton and wool fiber tapestry" t:zip_code=98520 t:id_number=WSAC2003.071.000 t:specific_location="Library, 2nd floor behind reference desk" t:artist="Blomberg, Cecilia" t:credit_line="This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Grays Harbor College" m:date=2004

series e:xx9k-ku4q d:2016-01-01T00:00:00.000Z t:artwork_city=Aberdeen t:measurements="94 in x 38 in x 18 in (each)" t:title="Out Where Grays Harbor Meets the Pacific; Upriver Grays Harbor" t:artwork_site="Grays Harbor College" t:materials="Carved and painted Poplar" t:zip_code=98520 t:id_number=WSAC2005.016.00A-B t:specific_location="1st and 2nd floor in Instructional Building" t:artist="DeVoe, Mike" t:credit_line="This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Grays Harbor College" m:date=2006

series e:xx9k-ku4q d:2016-01-01T00:00:00.000Z t:artwork_city=Aberdeen t:measurements="29 in x 29 in (sheet)" t:title="Geometries: Cross" t:artwork_site="Grays Harbor College" t:materials="Lithograph on paper" t:zip_code=98532 t:id_number=WSAC2010.004.000 t:specific_location="2000 bldg, Human Resources office" t:artist="Guzak, Karen" t:credit_line="This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Grays Harbor College" m:date=1992
```

## Meta Commands

```ls
metric m:date p:integer l:DATE t:dataTypeName=number

entity e:xx9k-ku4q l:"State Art Collection Published 2016-05-25" t:attribution="Washington State Arts Commission (ArtsWA)" t:url=https://data.wa.gov/api/views/xx9k-ku4q

property e:xx9k-ku4q t:meta.view v:id=xx9k-ku4q v:category=Education v:attributionLink=http://www.arts.wa.gov v:averageRating=0 v:name="State Art Collection Published 2016-05-25" v:attribution="Washington State Arts Commission (ArtsWA)"

property e:xx9k-ku4q t:meta.view.license v:name="Public Domain"

property e:xx9k-ku4q t:meta.view.owner v:id=6hjb-isx8 v:screenName="Valerie Peterman" v:displayName="Valerie Peterman"

property e:xx9k-ku4q t:meta.view.tableauthor v:id=6hjb-isx8 v:screenName="Valerie Peterman" v:roleName=publisher v:displayName="Valerie Peterman"
```

## Top Records

```ls
| artwork_city   | arwork_address           | zip_code   | artwork_latitude  | id_number          | artist                             | title                                                          | date | materials                                              | measurements                 | credit_line                                                                                                                                                   | artwork_site                      | specific_location                                  | 
| ============== | ======================== | ========== | ================= | ================== | ================================== | ============================================================== | ==== | ====================================================== | ============================ | ============================================================================================================================================================= | ================================= | ================================================== | 
| Aberdeen       | 1620 Edward P Smith Dr,  | 98520      | 46.953347         | WSAC2003.071.000   | Blomberg, Cecilia                  | The Grays Harbor College Tapestry                              | 2004 | Cotton and wool fiber tapestry                         | 4 1/2 ft x 13 ft             | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Grays Harbor College          | Grays Harbor College              | Library, 2nd floor behind reference desk           | 
| Aberdeen       | 1620 Edward P Smith Dr,  | 98520      | 46.953615         | WSAC2005.016.00A-B | DeVoe, Mike                        | Out Where Grays Harbor Meets the Pacific; Upriver Grays Harbor | 2006 | Carved and painted Poplar                              | 94 in x 38 in x 18 in (each) | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Grays Harbor College          | Grays Harbor College              | 1st and 2nd floor in Instructional Building        | 
| Aberdeen       | 1620 Edward P Smith Dr,  | 98532      | 46.954330         | WSAC2010.004.000   | Guzak, Karen                       | Geometries: Cross                                              | 1992 | Lithograph on paper                                    | 29 in x 29 in (sheet)        | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Grays Harbor College          | Grays Harbor College              | 2000 bldg, Human Resources office                  | 
| Aberdeen       | 1620 Edward P Smith Dr,  | 98520      | 46.954394         | WSAC1993.018.000   | Sogabe, Aki                        | Night Ocean                                                    | 1992 | Cut paper                                              | 24 in x 13 in                | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Grays Harbor College          | Grays Harbor College              | 2000 Bldg, Business Office Hallway                 | 
| Aberdeen       | 1620 Edward P Smith Dr,  | 98520      | 46.954464         | WSAC2005.020.000   | Franklin, David                    | Chinookan Sunset                                               | 2007 | Carved Douglas fir, Western redcedar, and Sitka spruce | 14 ft x 14 ft x 1 ft         | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Grays Harbor College          | Grays Harbor College              | Main lobby, main floor of Instructional Building   | 
| Aberdeen       | 191 Constantine Way,     | 99156      | 46.925452         | WSAC2001.056.002   | Ralph Helmick and Stuart Schechter | Migration II                                                   | 2003 | Cast urethane resin and stainless steel cable          | 4 ft x 12 ft x 12 ft         | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Department of Corrections     | Stafford Creek Corrections Center | Stafford Creek Public Access Area & Visiting Areas | 
| Aberdeen       | 410 North G St.,         | 98601      | 46.97964921408333 | WSAC2007.048.000   | Paquette, Virginia                 | The Chehalis and the Wishkah River Path                        | 2009 | Aluminum, dyes, and stainless steel                    | 4 ft x 84 ft                 | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Aberdeen School District      | Aberdeen-Weatherwax High School   | Commons                                            | 
| Airway Heights | 12824 W 12th Street,     | 98466-6100 | 47.645051         | WSAC1994.028.000   | Sogabe, Aki                        | Carps                                                          | 1994 | Cut paper                                              | 14 in x 10 in                | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Cheney School District        | Sunset Elementary                 | Hallway toward 600 wing                            | 
| Amboy          | 22115 NE Chelatchie Rd., | 98601      | 45.913503         | WSAC2008.013.003   | Frug?-Brown, Kathleen              | Path Through the Woods                                         | 2009 | Vitreous enamel on steel                               | 42 in x 108 in               | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Battle Ground School District | Amboy Middle School               | entry hallway                                      | 
| Amboy          | 22115 NE Chelatchie Rd., | 98601      | 45.913503         | WSAC2008.013.002   | Frug?-Brown, Kathleen              | Creek in a Pasture                                             | 2009 | Vitreous enamel on steel                               | 42 in x 105 in               | This artwork is a part of the State Art Collection and was acquired by the Washington State Arts Commission in partnership with Battle Ground School District | Amboy Middle School               | Entry hallway                                      | 
```