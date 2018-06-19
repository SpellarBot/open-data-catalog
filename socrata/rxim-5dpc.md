# Historic Zoning Districts - 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historic-zoning-districts-2007-efa0c) |
| Metadata | [Link](https://data.sfgov.org/api/views/rxim-5dpc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/rxim-5dpc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/rxim-5dpc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | rxim-5dpc |
| Name | Historic Zoning Districts - 2007 |
| Category | Geographic Locations and Boundaries |
| Tags | planning, zoning |
| Created | 2016-07-28T19:56:58Z |
| Publication Date | 2016-08-19T21:39:38Z |

## Description

Zoning Districts from 2007. Part of the San Francisco Planning Code. Data is a zipped GIS shapefile.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| No       |                | address1   | address1   | text      | text        |
| No       |                | address2   | address2   | text      | text        |
| Yes      | series tag     | annotation | annotation | text      | text        |
| Yes      | numeric metric | bdrms      | bdrms      | number    | number      |
| Yes      | numeric metric | bldgsqft   | bldgsqft   | number    | number      |
| Yes      | series tag     | blklot     | blklot     | text      | text        |
| Yes      | series tag     | block_num  | block_num  | text      | text        |
| Yes      | numeric metric | censustrac | censustrac | number    | number      |
| Yes      | numeric metric | changedsin | changedsin | number    | number      |
| Yes      | numeric metric | cie        | cie        | number    | number      |
| Yes      | series tag     | from_st    | from_st    | text      | text        |
| Yes      | numeric metric | from_st_nu | from_st_nu | number    | number      |
| Yes      | series tag     | heightlimi | heightlimi | text      | text        |
| Yes      | series tag     | landname   | landname   | text      | text        |
| Yes      | series tag     | landuse    | landuse    | text      | text        |
| Yes      | series tag     | landuse_20 | landuse_20 | text      | text        |
| Yes      | numeric metric | landval    | landval    | number    | number      |
| Yes      | numeric metric | lcu        | lcu        | number    | number      |
| Yes      | numeric metric | lidarsqft  | lidarsqft  | number    | number      |
| Yes      | numeric metric | lidarstori | lidarstori | number    | number      |
| Yes      | series tag     | lot_num    | lot_num    | text      | text        |
| Yes      | series tag     | lu_cleanup | lu_cleanup | text      | text        |
| Yes      | series tag     | mapblklot  | mapblklot  | text      | text        |
| Yes      | numeric metric | med        | med        | number    | number      |
| Yes      | numeric metric | mips       | mips       | number    | number      |
| Yes      | series tag     | mixed_use  | mixed_use  | text      | text        |
| Yes      | series tag     | neighborho | neighborho | text      | text        |
| Yes      | series tag     | objectid   | objectid   | text      | number      |
| Yes      | series tag     | odd_even   | odd_even   | text      | text        |
| Yes      | series tag     | ownrname   | ownrname   | text      | text        |
| Yes      | numeric metric | paperlot   | paperlot   | number    | number      |
| Yes      | numeric metric | pdr        | pdr        | number    | number      |
| Yes      | numeric metric | publicfacs | publicfacs | number    | number      |
| Yes      | numeric metric | rescom_uni | rescom_uni | number    | number      |
| Yes      | series tag     | restype    | restype    | text      | text        |
| Yes      | numeric metric | resunits   | resunits   | number    | number      |
| Yes      | numeric metric | retail     | retail     | number    | number      |
| Yes      | numeric metric | shape_area | shape_area | number    | number      |
| Yes      | numeric metric | shape_len  | shape_len  | number    | number      |
| Yes      | series tag     | source     | source     | text      | text        |
| Yes      | numeric metric | stories    | stories    | number    | number      |
| Yes      | series tag     | street     | street     | text      | text        |
| Yes      | numeric metric | strucval   | strucval   | number    | number      |
| Yes      | series tag     | st_type    | st_type    | text      | text        |
| Yes      | numeric metric | taz        | taz        | number    | number      |
| Yes      | numeric metric | temp       | temp       | number    | number      |
| Yes      | numeric metric | total_uses | total_uses | number    | number      |
| Yes      | series tag     | to_st      | to_st      | text      | text        |
| Yes      | series tag     | to_st_num  | to_st_num  | text      | number      |
| Yes      | series tag     | update_dat | update_dat | text      | text        |
| Yes      | series tag     | usetype    | usetype    | text      | text        |
| Yes      | numeric metric | visitor    | visitor    | number    | number      |
| Yes      | numeric metric | yrbuilt    | yrbuilt    | number    | number      |
| Yes      | series tag     | zip        | zip        | text      | text        |
| Yes      | series tag     | zoning     | zoning     | text      | text        |
| Yes      | series tag     | zoning_gen | zoning_gen | text      | text        |
| Yes      | series tag     | zoning_sim | zoning_sim | text      | text        |
| No       |                | geometry   | geometry   | polygon   | polygon     |
| Yes      | series tag     | multigeom  | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address1,address2,geometry
```

## Data Commands

```ls
series e:rxim-5dpc d:2007-01-01T00:00:00.000Z t:neighborho="Rest of the City" t:update_dat=2010-01-20 t:zip=94133 t:blklot=0061006 t:lot_num=006 t:landuse_20=RESIDENT t:usetype=D t:mixed_use=RESIDENT t:street=LOMBARD t:zoning_sim=RH-3 t:zoning_gen=Residentia t:odd_even=E t:to_st=364 t:source=Assessor t:to_st_num=364 t:block_num=0061 t:heightlimi=40-X t:multigeom=false t:st_type=ST t:from_st=364 t:landuse=RESIDENT t:objectid=580 t:mapblklot=0061006 t:zoning=RH-3 t:restype=SINGLE m:med=0 m:landval=2387718 m:pdr=0 m:strucval=1591812 m:shape_area=1996.36542748 m:publicfacs=0 m:bdrms=3 m:rescom_uni=0 m:from_st_nu=364 m:mips=0 m:lcu=0 m:changedsin=0 m:yrbuilt=1908 m:paperlot=0 m:cie=0 m:visitor=0 m:taz=822 m:stories=3 m:total_uses=0 m:temp=0 m:shape_len=239.638004055 m:bldgsqft=3719 m:censustrac=10400 m:lidarsqft=4786 m:resunits=1 m:lidarstori=0 m:retail=0

series e:rxim-5dpc d:2007-01-01T00:00:00.000Z t:neighborho="Rest of the City" t:update_dat=2010-01-20 t:zip=94133 t:blklot=0061007 t:lot_num=007 t:landuse_20=RESIDENT t:usetype=F t:mixed_use=RESIDENT t:street=LOMBARD t:zoning_sim=RH-3 t:zoning_gen=Residentia t:odd_even=E t:to_st=370 t:source=DAHI t:to_st_num=370 t:block_num=0061 t:heightlimi=40-X t:multigeom=false t:st_type=ST t:from_st=368 t:landuse=RESIDENT t:objectid=581 t:mapblklot=0061007 t:zoning=RH-3 t:restype=APTS m:med=0 m:landval=445917 m:pdr=0 m:strucval=445917 m:shape_area=3311.18619928 m:publicfacs=0 m:bdrms=10 m:rescom_uni=0 m:from_st_nu=368 m:mips=0 m:lcu=0 m:changedsin=0 m:yrbuilt=1912 m:paperlot=0 m:cie=0 m:visitor=0 m:taz=822 m:stories=3 m:total_uses=0 m:temp=0 m:shape_len=303.706039951 m:bldgsqft=6810 m:censustrac=10400 m:lidarsqft=9859 m:resunits=3 m:lidarstori=0 m:retail=0

series e:rxim-5dpc d:2007-01-01T00:00:00.000Z t:neighborho="Rest of the City" t:update_dat=2010-01-20 t:zip=94133 t:blklot=0061008 t:lot_num=008 t:landuse_20=RESIDENT t:usetype=A t:mixed_use=RESIDENT t:street=LOMBARD t:zoning_sim=RH-3 t:zoning_gen=Residentia t:odd_even=E t:to_st=374 t:source=DAHI t:to_st_num=374 t:block_num=0061 t:heightlimi=40-X t:multigeom=false t:st_type=ST t:from_st=374 t:landuse=RESIDENT t:objectid=582 t:mapblklot=0061008 t:zoning=RH-3 t:restype=APTS m:med=0 m:landval=1485690 m:pdr=0 m:strucval=955086 m:shape_area=1882.11686615 m:publicfacs=0 m:bdrms=0 m:rescom_uni=0 m:from_st_nu=374 m:mips=0 m:lcu=0 m:changedsin=0 m:yrbuilt=1907 m:paperlot=0 m:cie=0 m:visitor=0 m:taz=822 m:stories=3 m:total_uses=0 m:temp=0 m:shape_len=196.779034126 m:bldgsqft=5354 m:censustrac=10400 m:lidarsqft=6706 m:resunits=5 m:lidarstori=0 m:retail=0
```

## Meta Commands

```ls
metric m:bdrms p:long l:bdrms t:dataTypeName=number

metric m:bldgsqft p:long l:bldgsqft t:dataTypeName=number

metric m:censustrac p:long l:censustrac t:dataTypeName=number

metric m:changedsin p:long l:changedsin t:dataTypeName=number

metric m:cie p:long l:cie t:dataTypeName=number

metric m:from_st_nu p:long l:from_st_nu t:dataTypeName=number

metric m:landval p:long l:landval t:dataTypeName=number

metric m:lcu p:long l:lcu t:dataTypeName=number

metric m:lidarsqft p:long l:lidarsqft t:dataTypeName=number

metric m:lidarstori p:long l:lidarstori t:dataTypeName=number

metric m:med p:long l:med t:dataTypeName=number

metric m:mips p:long l:mips t:dataTypeName=number

metric m:paperlot p:long l:paperlot t:dataTypeName=number

metric m:pdr p:long l:pdr t:dataTypeName=number

metric m:publicfacs p:long l:publicfacs t:dataTypeName=number

metric m:rescom_uni p:long l:rescom_uni t:dataTypeName=number

metric m:resunits p:long l:resunits t:dataTypeName=number

metric m:retail p:long l:retail t:dataTypeName=number

metric m:shape_area p:long l:shape_area t:dataTypeName=number

metric m:shape_len p:long l:shape_len t:dataTypeName=number

metric m:stories p:long l:stories t:dataTypeName=number

metric m:strucval p:long l:strucval t:dataTypeName=number

metric m:taz p:long l:taz t:dataTypeName=number

metric m:temp p:long l:temp t:dataTypeName=number

metric m:total_uses p:long l:total_uses t:dataTypeName=number

metric m:visitor p:long l:visitor t:dataTypeName=number

metric m:yrbuilt p:long l:yrbuilt t:dataTypeName=number

entity e:rxim-5dpc l:"Historic Zoning Districts - 2007" t:url=https://data.sfgov.org/api/views/rxim-5dpc

property e:rxim-5dpc t:meta.view v:id=rxim-5dpc v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Historic Zoning Districts - 2007"

property e:rxim-5dpc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:rxim-5dpc t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:rxim-5dpc t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| address1                    | address2                    | annotation | bdrms | bldgsqft | blklot  | block_num | censustrac | changedsin | cie | from_st | from_st_nu | heightlimi | landname | landuse  | landuse_20 | landval | lcu | lidarsqft | lidarstori | lot_num | lu_cleanup | mapblklot | med | mips | mixed_use | neighborho       | objectid | odd_even | ownrname | paperlot | pdr | publicfacs | rescom_uni | restype | resunits | retail | shape_area    | shape_len     | source       | stories | street  | strucval | st_type | taz | temp | total_uses | to_st | to_st_num | update_dat | usetype | visitor | yrbuilt | zip   | zoning | zoning_gen | zoning_sim | geometry                                                                                                                                                                                                                                                                                      | multigeom | 
| =========================== | =========================== | ========== | ===== | ======== | ======= | ========= | ========== | ========== | === | ======= | ========== | ========== | ======== | ======== | ========== | ======= | === | ========= | ========== | ======= | ========== | ========= | === | ==== | ========= | ================ | ======== | ======== | ======== | ======== | === | ========== | ========== | ======= | ======== | ====== | ============= | ============= | ============ | ======= | ======= | ======== | ======= | === | ==== | ========== | ===== | ========= | ========== | ======= | ======= | ======= | ===== | ====== | ========== | ========== | ============================================================================================================================================================================================================================================================================================= | ========= | 
| MADERIS GAIL                | 364 LOMBARD ST              |            | 3     | 3719     | 0061006 | 0061      | 10400      | 0          | 0   | 364     | 364        | 40-X       |          | RESIDENT | RESIDENT   | 2387718 | 0   | 4786      | 0          | 006     |            | 0061006   | 0   | 0    | RESIDENT  | Rest of the City | 580      | E        |          | 0        | 0   | 0          | 0          | SINGLE  | 1        | 0      | 1996.36542748 | 239.638004055 | Assessor     | 3       | LOMBARD | 1591812  | ST      | 822 | 0    | 0          | 364   | 364       | 2010-01-20 | D       | 0       | 1908    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40762064433537 37.80359116645068, -122.40767632628732 37.803861758050225, -122.40760794548679 37.80387031626603, -122.4075522794155 37.80359980278697, -122.40762064433537 37.80359116645068))                                                                                 | false     | 
| JULIUS LOMBARD ASSOCS LLC   | 12 JULIUS STREET            |            | 10    | 6810     | 0061007 | 0061      | 10400      | 0          | 0   | 368     | 368        | 40-X       |          | RESIDENT | RESIDENT   | 445917  | 0   | 9859      | 0          | 007     |            | 0061007   | 0   | 0    | RESIDENT  | Rest of the City | 581      | E        |          | 0        | 0   | 0          | 0          | APTS    | 3        | 0      | 3311.18619928 | 303.706039951 | DAHI         | 3       | LOMBARD | 445917   | ST      | 822 | 0    | 0          | 370   | 370       | 2010-01-20 | F       | 0       | 1912    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40770951924732 37.80357993806405, -122.40774988375442 37.80377609321568, -122.40783877967284 37.803764967133446, -122.40785411832468 37.80383950593001, -122.40767632628732 37.803861758050225, -122.40762064433537 37.80359116645068, -122.40770951924732 37.80357993806405)) | false     | 
| LAZZARETTI WILLIAM H&KATHRY | WILLIAM H&KATHRYN A LAZZARE |            | 0     | 5354     | 0061008 | 0061      | 10400      | 0          | 0   | 374     | 374        | 40-X       |          | RESIDENT | RESIDENT   | 1485690 | 0   | 6706      | 0          | 008     |            | 0061008   | 0   | 0    | RESIDENT  | Rest of the City | 582      | E        |          | 0        | 0   | 0          | 0          | APTS    | 5        | 0      | 1882.11686615 | 196.779034126 | DAHI         | 3       | LOMBARD | 955086   | ST      | 822 | 0    | 0          | 374   | 374       | 2010-01-20 | A       | 0       | 1907    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40783877967284 37.803764967133446, -122.40774988375442 37.80377609321568, -122.40770951924732 37.80357993806405, -122.40779839299708 37.80356870962879, -122.40783877967284 37.803764967133446))                                                                               | false     | 
| JOHN TRAVERSO BYPASS TRUST  | TRAVERSO FRANCES TRUSTEE    |            | 0     | 3646     | 0061009 | 0061      | 10400      | 0          | 0   | 396     | 396        | 40-X       |          | RESIDENT | RESIDENT   | 53959   | 0   | 3654      | 0          | 009     |            | 0061009   | 0   | 2100 | RESIDENT  | Rest of the City | 583      | E        |          | 0        | 0   | 0          | 0          | APTS    | 4        | 0      | 1718.75972397 | 187.501260829 | DAHI/D&B     | 2       | LOMBARD | 93452    | ST      | 822 | 0    | 2100       | 396   | 396       | 2010-01-20 | A       | 0       | 1926    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40786959378627 37.80362923752172, -122.40785564918959 37.80356147580429, -122.40809065387904 37.803531785590344, -122.40810459752608 37.80359954639788, -122.40786959378627 37.80362923752172))                                                                                | false     | 
| JOHN TRAVERSO SURVIVORS TRU | TRAVERSO FRANCES TRUSTEE    |            | 0     | 1753     | 0061010 | 0061      | 10400      | 0          | 0   | 1806    | 1806       | 40-X       |          | RESIDENT | RESIDENT   | 48096   | 0   | 4013      | 0          | 010     |            | 0061010   | 0   | 996  | RESIDENT  | Rest of the City | 584      | E        |          | 0        | 0   | 0          | 0          | FLATS   | 3        | 0      | 1546.87851602 | 182.50085602  | Assessor/D&B | 2       | GRANT   | 42056    | AVE     | 822 | 0    | 996        | 1806  | 1806      | 2010-01-20 | F       | 0       | 1906    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40810459752608 37.80359954639788, -122.40811714719165 37.803660531927754, -122.40788214324067 37.8036902221754, -122.40786959378627 37.80362923752172, -122.40810459752608 37.80359954639788))                                                                                 | false     | 
| KEN & KATHY BACCETTI REVOC  | %KENNETH L & KATHLEEN A BAC |            | 0     | 1317     | 0061011 | 0061      | 10400      | 0          | 0   | 1818    | 1818       | 40-X       |          | RESIDENT | RESIDENT   | 274637  | 0   | 3612      | 0          | 011     |            | 0061011   | 0   | 0    | RESIDENT  | Rest of the City | 585      | E        |          | 0        | 0   | 0          | 0          | SINGLE  | 1        | 0      | 2320.32884128 | 205.001470826 | Assessor     | 1       | GRANT   | 147131   | AVE     | 822 | 0    | 0          | 1818  | 1818      | 2010-01-20 | D       | 0       | 1949    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40811714719165 37.803660531927754, -122.40813597227313 37.80375200930879, -122.40790096692797 37.80378170051263, -122.40788214324067 37.8036902221754, -122.40811714719165 37.803660531927754))                                                                                | false     | 
| BACCETTI REVOCABLE TRUST    | BACCETTI LOUIS J TRUSTEE    |            | 0     | 5721     | 0061012 | 0061      | 10400      | 0          | 0   | 1820    | 1820       | 40-X       |          | RESIDENT | RESIDENT   | 245728  | 0   | 5792      | 0          | 012     |            | 0061012   | 0   | 332  | RESIDENT  | Rest of the City | 586      | E        |          | 0        | 0   | 0          | 0          | APTS    | 6        | 0      | 2320.33586837 | 205.001842067 | DAHI/D&B     | 3       | GRANT   | 298132   | AVE     | 822 | 0    | 332        | 1826  | 1826      | 2010-01-20 | A       | 0       | 1912    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40813597227313 37.80375200930879, -122.40815479742413 37.80384348758604, -122.40791979177384 37.80387317792606, -122.40790096692797 37.80378170051263, -122.40813597227313 37.80375200930879))                                                                                 | false     | 
| LOUIE LOLA REV TRUST        | 1834 GRANT AVE              |            | 0     | 2736     | 0061017 | 0061      | 10400      | 0          | 0   | 1834    | 1834       | 40-X       |          | RESIDENT | RESIDENT   | 36890   | 0   | 1792      | 0          | 017     |            | 0061017   | 0   | 0    | RESIDENT  | Rest of the City | 588      | E        |          | 0        | 0   | 0          | 0          | FLATS   | 2        | 0      | 1120.01533865 | 172.002703632 | Assessor     | 2       | GRANT   | 87586    | AVE     | 822 | 0    | 0          | 1834  | 1834      | 2010-01-20 | F       | 0       | 1915    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40793918523254 37.80398872467313, -122.40817852106348 37.8039587704774, -122.40818744564316 37.80400213741166, -122.40794810969923 37.804032092526086, -122.40793918523254 37.80398872467313))                                                                                 | false     | 
| TOM & KATE CARROLL WHELAN R | TOM & KATE CARROLL WHELAN,  |            | 0     | 1616     | 0061018 | 0061      | 10400      | 0          | 0   | 1838    | 1838       | 40-X       |          | RESIDENT | RESIDENT   | 749088  | 0   | 1670      | 0          | 018     |            | 0061018   | 0   | 0    | RESIDENT  | Rest of the City | 589      | E        |          | 0        | 0   | 0          | 0          | FLATS   | 2        | 0      | 1120.02708569 | 172.00307294  | Assessor     | 2       | GRANT   | 499392   | AVE     | 822 | 0    | 0          | 1838  | 1838      | 2010-01-20 | F       | 0       | 1915    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40794810969923 37.804032092526086, -122.40818744564316 37.80400213741166, -122.40819637025648 37.804045505245654, -122.40795703417633 37.804075460377994, -122.40794810969923 37.804032092526086))                                                                             | false     | 
| FAMILY SUBTRUST TRUST       | MADELILNE SCHROEDER, TRUSTE |            | 0     | 1760     | 0061019 | 0061      | 10400      | 0          | 0   | 1844    | 1844       | 40-X       |          | RESIDENT | RESIDENT   | 32905   | 0   | 2032      | 0          | 019     |            | 0061019   | 0   | 0    | RESIDENT  | Rest of the City | 590      | E        |          | 0        | 0   | 0          | 0          | FLATS   | 2        | 0      | 1120.01733686 | 172.002701636 | Assessor     | 2       | GRANT   | 54115    | AVE     | 822 | 0    | 0          | 1844  | 1844      | 2010-01-20 | F       | 0       | 1916    | 94133 | RH-3   | Residentia | RH-3       | POLYGON ((-122.40795703417633 37.804075460377994, -122.40819637025648 37.804045505245654, -122.4082052937448 37.80408887309706, -122.40804459729468 37.80410898544526, -122.40796595866382 37.80411882822889, -122.40795703417633 37.804075460377994))                                        | false     | 
```