# CAMAGIS_Property_Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/camagis-property-details) |
| Metadata | [Link](https://data.hartford.gov/api/views/uepu-9ktm) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/uepu-9ktm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/uepu-9ktm/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | uepu-9ktm |
| Name | CAMAGIS_Property_Details |
| Attribution | City of Hartford |
| Category | Financial |
| Tags | assessor, property, owner information, hartford, ct |
| Created | 2014-04-14T17:39:35Z |
| Publication Date | 2015-04-27T10:20:17Z |

## Description

This table has owner and property information. Updated nightly. For more information on the LUC codes select the about tab and scroll down to the attachments and open the PDF document

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | accountnumber    | AccountNumber    | text      | number      |
| Yes      | series tag     | gisparcelnumber  | GISParcelNumber  | text      | text        |
| Yes      | series tag     | parcelnumber     | ParcelNumber     | text      | text        |
| Yes      | series tag     | cardnumber       | CardNumber       | text      | number      |
| Yes      | series tag     | streetnumberfrom | StreetNumberFrom | text      | text        |
| Yes      | series tag     | streetnumberto   | StreetNumberTo   | text      | text        |
| Yes      | series tag     | streetname       | StreetName       | text      | text        |
| Yes      | series tag     | condonumber      | CondoNumber      | text      | text        |
| Yes      | series tag     | ownerfullname    | OwnerFullName    | text      | text        |
| Yes      | series tag     | owner1fname      | Owner1FName      | text      | text        |
| Yes      | series tag     | owner1last       | Owner1Last       | text      | text        |
| Yes      | series tag     | owner2fname      | Owner2FName      | text      | text        |
| Yes      | series tag     | owner2last       | Owner2Last       | text      | text        |
| Yes      | series tag     | owner3fname      | Owner3FName      | text      | text        |
| Yes      | series tag     | owner3last       | Owner3Last       | text      | text        |
| No       |                | mailingaddress1  | MailingAddress1  | text      | text        |
| No       |                | mailingaddress2  | MailingAddress2  | text      | text        |
| Yes      | series tag     | mailingstreet    | MailingStreet    | text      | text        |
| Yes      | series tag     | city             | City             | text      | text        |
| Yes      | series tag     | state            | State            | text      | text        |
| Yes      | series tag     | zip10            | Zip10            | text      | text        |
| Yes      | numeric metric | luc              | LUC              | number    | text        |
| Yes      | series tag     | lucdescription   | LUCDescription   | text      | text        |
| Yes      | series tag     | zoning           | Zoning           | text      | text        |
| Yes      | series tag     | nbhdcode         | NbhdCode         | text      | text        |
| Yes      | series tag     | nbhddesc         | NbhdDesc         | text      | text        |
| Yes      | series tag     | lastgrantor      | LastGrantor      | text      | text        |
| Yes      | time           | lastsaledate     | LastSaleDate     | date      | date        |
| Yes      | numeric metric | lastsaleprice    | LastSalePrice    | money     | money       |
| Yes      | series tag     | lastsalecode     | LastSalecode     | text      | text        |
| Yes      | series tag     | lastsaletype     | LastSaleType     | text      | text        |
| Yes      | series tag     | legalref         | LegalRef         | text      | text        |
| Yes      | numeric metric | livingunits      | LivingUnits      | number    | number      |
| No       |                | yearbuilt        | YearBuilt        | number    | number      |
| Yes      | numeric metric | totapprsdvalue   | TotApprsdValue   | money     | money       |
| Yes      | numeric metric | grossbuiltarea   | GrossBuiltArea   | number    | number      |
| Yes      | numeric metric | totfinishdarea   | TotFinishdArea   | number    | number      |
| Yes      | numeric metric | totacreage       | TotAcreage       | number    | number      |
| Yes      | numeric metric | storyheight      | StoryHeight      | number    | text        |
| Yes      | series tag     | bldgtype         | BldgType         | text      | text        |
| Yes      | series tag     | bldgfoundation   | BldgFoundation   | text      | text        |
| Yes      | series tag     | bldgframetype    | BldgFrameType    | text      | text        |
| Yes      | series tag     | primextwall      | PrimExtWall      | text      | text        |
| Yes      | series tag     | bldgrooftype     | BldgRoofType     | text      | text        |
| Yes      | series tag     | bldgroofcover    | BldgRoofCover    | text      | text        |
| Yes      | series tag     | primintwall      | PrimIntWall      | text      | text        |
| Yes      | numeric metric | bedrooms         | Bedrooms         | number    | number      |
| Yes      | numeric metric | primheatfuel     | PrimHeatFuel     | number    | text        |
| Yes      | series tag     | primheatfueldesc | PrimHeatFuelDesc | text      | text        |
| Yes      | series tag     | primheattype     | PrimHeatType     | text      | text        |
| Yes      | series tag     | primheattypedesc | PrimHeatTypeDesc | text      | text        |
```

## Time Field

```ls
Value = lastsaledate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailingaddress1,mailingaddress2,yearbuilt
```

## Data Commands

```ls
series e:uepu-9ktm d:2010-09-09T00:00:00.000Z t:parcelnumber=144699013 t:primheattype=4 t:lucdescription="RESIDENTIAL ONE FAMILY" t:ownerfullname="MIRIAM GRANT" t:bldgrooftype=GABLE/HIP t:state=CT t:city=HARTFORD t:bldgroofcover=Asphalt t:lastgrantor=PODGORSKI,JANINA t:bldgframetype="Wood Frame" t:gisparcelnumber=144699013 t:owner1last=GRANT t:legalref=06374-0064 t:accountnumber=90 t:streetnumberfrom=0046 t:nbhdcode="SOUTH WEST" t:zoning=N3-1 t:streetname="MARION ST" t:bldgtype=Ranch t:primheatfueldesc=Oil t:primheattypedesc="Forced Hot Water" t:cardnumber=1 t:nbhddesc=SouthWest t:lastsaletype=0 t:bldgfoundation=Concrete t:primextwall=Aluminum/Vinyl t:zip10=06106 t:lastsalecode="Valid Sale" t:owner1fname=MIRIAM t:primintwall=DRYWALL m:livingunits=1 m:primheatfuel=4 m:storyheight=1 m:luc=101 m:grossbuiltarea=2727 m:bedrooms=3 m:totacreage=0.177916 m:totfinishdarea=1316 m:lastsaleprice=154000 m:totapprsdvalue=156900

series e:uepu-9ktm d:1997-12-17T00:00:00.000Z t:parcelnumber=171054151 t:primheattype=2 t:lucdescription="RESIDENTIAL ONE FAMILY" t:ownerfullname="DOROTHY A FRASIER" t:bldgrooftype=GABLE/HIP t:state=CT t:city=HARTFORD t:bldgroofcover=Asphalt t:bldgframetype="Wood Frame" t:gisparcelnumber=171054151 t:owner1last=FRASIER t:legalref="03899 0076" t:accountnumber=17976 t:streetnumberfrom=0066 t:nbhdcode="BLUE HILLS" t:zoning=N4-1 t:streetname="BRANFORD ST" t:bldgtype="Cape Cod" t:primheatfueldesc=Gas t:primheattypedesc="Forced Air" t:cardnumber=1 t:nbhddesc="Blue Hills" t:lastsaletype=25 t:bldgfoundation=Concrete t:primextwall=Aluminum/Vinyl t:zip10=06112-1520 t:lastsalecode="Other Reason" t:owner1fname="DOROTHY A" t:primintwall=PLASTER m:livingunits=1 m:primheatfuel=2 m:storyheight=1 m:luc=101 m:grossbuiltarea=2271 m:bedrooms=2 m:totacreage=0.138889 m:totfinishdarea=1080 m:lastsaleprice=0 m:totapprsdvalue=98300

series e:uepu-9ktm d:1996-11-27T00:00:00.000Z t:parcelnumber=261121115 t:primheattype=4 t:lucdescription="RESIDENTIAL ONE FAMILY" t:ownerfullname="LINDA F MARTIN" t:bldgrooftype=GABLE/HIP t:state=CT t:city=HARTFORD t:bldgroofcover=Asphalt t:bldgframetype="Wood Frame" t:gisparcelnumber=261121115 t:owner1last=MARTIN t:legalref="03762 0218" t:accountnumber=21018 t:streetnumberfrom=0103 t:nbhdcode=NORTHEAST t:streetnumberto=0105 t:zoning=N3-2 t:streetname="CLEVELAND AV" t:bldgtype="Old Style" t:primheatfueldesc=Gas t:primheattypedesc="Forced Hot Water" t:cardnumber=1 t:nbhddesc=NorthEast t:bldgfoundation=Concrete t:primextwall=Aluminum/Vinyl t:zip10=06120-1345 t:owner1fname="LINDA F" t:primintwall=PLASTER m:livingunits=1 m:primheatfuel=2 m:storyheight=2 m:luc=101 m:grossbuiltarea=2995 m:bedrooms=3 m:totacreage=0.315083 m:totfinishdarea=2022 m:lastsaleprice=0 m:totapprsdvalue=127800
```

## Meta Commands

```ls
metric m:luc p:integer l:LUC t:dataTypeName=number

metric m:lastsaleprice p:integer l:LastSalePrice t:dataTypeName=money

metric m:livingunits p:integer l:LivingUnits t:dataTypeName=number

metric m:totapprsdvalue p:integer l:TotApprsdValue t:dataTypeName=money

metric m:grossbuiltarea p:integer l:GrossBuiltArea t:dataTypeName=number

metric m:totfinishdarea p:double l:TotFinishdArea t:dataTypeName=number

metric m:totacreage p:double l:TotAcreage t:dataTypeName=number

metric m:storyheight p:integer l:StoryHeight t:dataTypeName=number

metric m:bedrooms p:integer l:Bedrooms t:dataTypeName=number

metric m:primheatfuel p:integer l:PrimHeatFuel t:dataTypeName=number

entity e:uepu-9ktm l:CAMAGIS_Property_Details t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/uepu-9ktm

property e:uepu-9ktm t:meta.view v:id=uepu-9ktm v:category=Financial v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name=CAMAGIS_Property_Details v:attribution="City of Hartford"

property e:uepu-9ktm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:uepu-9ktm t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:uepu-9ktm t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| accountnumber | gisparcelnumber | parcelnumber | cardnumber | streetnumberfrom | streetnumberto | streetname      | condonumber | ownerfullname           | owner1fname | owner1last              | owner2fname | owner2last | owner3fname | owner3last | mailingaddress1  | mailingaddress2 | mailingstreet | city          | state | zip10      | luc | lucdescription                        | zoning | nbhdcode      | nbhddesc     | lastgrantor                             | lastsaledate | lastsaleprice | lastsalecode | lastsaletype | legalref   | livingunits | yearbuilt | totapprsdvalue | grossbuiltarea | totfinishdarea | totacreage | storyheight | bldgtype                 | bldgfoundation | bldgframetype | primextwall    | bldgrooftype | bldgroofcover | primintwall | bedrooms | primheatfuel | primheatfueldesc | primheattype | primheattypedesc | 
| ============= | =============== | ============ | ========== | ================ | ============== | =============== | =========== | ======================= | =========== | ======================= | =========== | ========== | =========== | ========== | ================ | =============== | ============= | ============= | ===== | ========== | === | ===================================== | ====== | ============= | ============ | ======================================= | ============ | ============= | ============ | ============ | ========== | =========== | ========= | ============== | ============== | ============== | ========== | =========== | ======================== | ============== | ============= | ============== | ============ | ============= | =========== | ======== | ============ | ================ | ============ | ================ | 
| 90            | 144699013       | 144699013    | 1          | 0046             |                | MARION ST       |             | MIRIAM GRANT            | MIRIAM      | GRANT                   |             |            |             |            | 46 MARION ST     |                 |               | HARTFORD      | CT    | 06106      | 101 | RESIDENTIAL ONE FAMILY                | N3-1   | SOUTH WEST    | SouthWest    | PODGORSKI,JANINA                        | 1283990400   | 154000        | Valid Sale   | 0            | 06374-0064 | 1           | 1961      | 156900         | 2727           | 1316           | 0.177916   | 1.0         | Ranch                    | Concrete       | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | DRYWALL     | 3        | 4            | Oil              | 4            | Forced Hot Water | 
| 17976         | 171054151       | 171054151    | 1          | 0066             |                | BRANFORD ST     |             | DOROTHY A FRASIER       | DOROTHY A   | FRASIER                 |             |            |             |            | 66 BRANFORD ST   |                 |               | HARTFORD      | CT    | 06112-1520 | 101 | RESIDENTIAL ONE FAMILY                | N4-1   | BLUE HILLS    | Blue Hills   |                                         | 882316800    | 0             | Other Reason | 25           | 03899 0076 | 1           | 1943      | 98300          | 2271           | 1080           | 0.138889   | 1.0         | Cape Cod                 | Concrete       | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | PLASTER     | 2        | 2            | Gas              | 2            | Forced Air       | 
| 21018         | 261121115       | 261121115    | 1          | 0103             | 0105           | CLEVELAND AV    |             | LINDA F MARTIN          | LINDA F     | MARTIN                  |             |            |             |            | 105 CLEVELAND AV |                 |               | HARTFORD      | CT    | 06120-1345 | 101 | RESIDENTIAL ONE FAMILY                | N3-2   | NORTHEAST     | NorthEast    |                                         | 849052800    | 0             |              |              | 03762 0218 | 1           | 1900      | 127800         | 2995           | 2022           | 0.315083   | 2.0         | Old Style                | Concrete       | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | PLASTER     | 3        | 2            | Gas              | 4            | Forced Hot Water | 
| 19592         | 238060017       | 238060017    | 1          | 0026             |                | CHARLOTTE ST    |             | DONNA A LONG            | DONNA A     | LONG                    |             |            |             |            | 26 CHARLOTTE ST  |                 |               | HARTFORD      | CT    | 06120-1711 | 101 | RESIDENTIAL ONE FAMILY                | N3-1   | NORTHEAST     | NorthEast    | LONG,ALFRED D                           | 1384905600   | 0             | Will         | 10           | 06758-0243 | 1           | 1983      | 137400         | 1690           | 1509.3         | 0.284389   | 1.0         | Raised Ranch             | Concrete       | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | DRYWALL     | 4        | 2            | Gas              | 4            | Forced Hot Water | 
| 18329         | 176200185       | 176200185    | 1          | 1011             | 1019           | ALBANY AV       |             | YONG LI INVESTMENTS LLC |             | YONG LI INVESTMENTS LLC |             |            |             |            | 20 LAWLER RD     |                 |               | WEST HARTFORD | CT    | 06117      | 210 | PRIMARILY COMMERCIAL WITH RESIDENTIAL | MS-1   | UPPER ALBANY  | Commercial   | YOUG LI INVESTMENTS LLC,                | 1378857600   | 0             | Corr/Conveni | 04           | 06730-0180 | 2           | 1910      | 252900         | 7243           | 5054.5         | 0.163912   | 2.5         | BUILT AS A RESIDENCE     | Stone/Brick    | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | PLASTER     | 4        | 2            | Gas              | 2            | Forced Air       | 
| 20882         | 261061022       | 261061022    | 1          | 0161             |                | CLEVELAND AV    |             | JOSE RAMIREZ            | JOSE        | RAMIREZ                 |             |            |             |            | 161 CLEVELAND AV |                 |               | HARTFORD      | CT    | 06120-1022 | 101 | RESIDENTIAL ONE FAMILY                | N3-1   | NORTHEAST     | NorthEast    | HARTFORD AREA HABITAT FOR,HUMANITY, INC | 934848000    | 80574         | To/from Govt | 15           | 04136-0064 | 1           | 1999      | 138400         | 2091           | 1200           | 0.315771   | 2.0         | Colonial                 | Concrete       | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | DRYWALL     | 2        | 2            | Gas              | 4            | Forced Hot Water | 
| 19368         | 218156075       | 218156075    | 1          | 0045             |                | VINELAND TER    |             | LLC TIFANY REALTY       | LLC         | TIFANY REALTY           |             |            |             |            | 15 WEBSTER ST    |                 |               | HARTFORD      | CT    | 06114-1220 | 101 | RESIDENTIAL ONE FAMILY                | NX-1   | NORTHEAST     | NorthEast    | REATEGUI,ROSARIO                        | 1427414400   | 1             | Corr/Conveni | 04           | 06920-0151 | 1           | 1963      | 110200         | 2336           | 1075.2         | 0.284665   | 1.0         | Cape Cod                 | Concrete       | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | DRYWALL     | 3        | 2            | Gas              | 4            | Forced Hot Water | 
| 8305          | 278816900       | 278816127    | 1          | 0926             |                | WETHERSFIELD AV | 0001        | WEHTTAM ASSOC LLC       |             | WEHTTAM ASSOC LLC       |             |            |             |            | PO BOX 223       |                 |               | CROMWELL      | CT    | 06416-0223 | 105 | RESIDENTIAL CONDOMINIUM               | NX-1   | SOUTH MEADOWS | Wethersfld G | ROLLING THUNDER, LLC,                   | 1026777600   | 0             | Corr/Conveni | 04           | 04588-0158 | 1           | 1958      | 20000          | 654            | 654            | 0          | 1.0         | Condominium Single Story | Concrete       | Wood Frame    | Brick          | FLAT         | Asphalt       | DRYWALL     | 2        | 2            | Gas              | 4            | Forced Hot Water | 
| 17863         | 170028204       | 170028204    | 1          | 0095             | 0097           | LEBANON ST      |             | CHERYL B REID           | CHERYL B    | REID                    |             |            |             |            | 97 LEBANON ST    |                 |               | HARTFORD      | CT    | 06112-1238 | 102 | RESIDENTIAL TWO FAMILY                | N4-2   | BLUE HILLS    | Blue Hills   |                                         | 869184000    | 0             |              |              | 03843 0228 | 2           | 1942      | 154100         | 3426           | 2014           | 0.148301   | 2.0         | Duplex                   | Concrete       | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | PLASTER     | 6        | 4            | Oil              | 2            | Forced Air       | 
| 9562          | 132309085       | 132309085    | 1          | 0142             |                | KENYON ST       |             | RONALD KAPRASZEWSKI     | RONALD      | KAPRASZEWSKI            |             |            |             |            | 142 KENYON ST    |                 |               | HARTFORD      | CT    | 06105-2238 | 101 | RESIDENTIAL ONE FAMILY                | N2-1   | WEST END      | West End     | DEGRANDI,JOSEPH                         | 1408665600   | 220508        | Corr/Conveni | 04           | 06853-0181 | 1           | 1920      | 378500         | 6856           | 4213.5         | 0.30854    | 2.75        | Old Style                | Stone/Brick    | Wood Frame    | Aluminum/Vinyl | GABLE/HIP    | Asphalt       | PLASTER     | 8        | 2            | Gas              | 2            | Forced Air       | 
```