# Crimes - 2001 to present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/crimes-2001-to-present-398a4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ijzp-q8t2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ijzp-q8t2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ijzp-q8t2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ijzp-q8t2 |
| Name | Crimes - 2001 to present |
| Attribution | Chicago Police Department |
| Category | Public Safety |
| Tags | crime, police |
| Created | 2011-09-30T17:59:31Z |
| Publication Date | 2016-06-08T21:22:41Z |

## Description

This dataset reflects reported incidents of crime (with the exception of murders where data exists for each victim) that occurred in the City of Chicago from 2001 to present, minus the most recent seven days. Data is extracted from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. In order to protect the privacy of crime victims, addresses are shown at the block level only and specific locations are not identified. Should you have questions about this dataset, you may contact the Research & Development Division of the Chicago Police Department at PSITAdministration@ChicagoPolice.org.  Disclaimer: These crimes may be based upon preliminary information supplied to the Police Department by the reporting parties that have not been verified. The preliminary crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the Chicago Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The Chicago Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The Chicago Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of Chicago or Chicago Police Department web page. The user specifically acknowledges that the Chicago Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user.  The unauthorized use of the words "Chicago Police Department," "Chicago Police," or any colorable imitation of these words or the unauthorized use of the Chicago Police Department logo is unlawful. This web page does not, in any way, authorize such use. Data are updated daily. The dataset contains more than 65,000 records/rows of data and cannot be viewed in full in Microsoft Excel. Therefore, when downloading the file, select CSV from the Export menu. Open the file in an ASCII text editor, such as Wordpad, to view and search. To access a list of Chicago Police Department - Illinois Uniform Crime Reporting (IUCR) codes, go to http://data.cityofchicago.org/Public-Safety/Chicago-Police-Department-Illinois-Uniform-Crime-R/c7ck-438e

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| No       |             | id                   | ID                   | text          | number        |
| Yes      | series tag  | case_number          | Case Number          | text          | text          |
| Yes      | time        | date                 | Date                 | calendar_date | calendar_date |
| Yes      | series tag  | block                | Block                | text          | text          |
| Yes      | series tag  | iucr                 | IUCR                 | text          | text          |
| Yes      | series tag  | primary_type         | Primary Type         | text          | text          |
| Yes      | series tag  | description          | Description          | text          | text          |
| Yes      | series tag  | location_description | Location Description | text          | text          |
| Yes      | series tag  | arrest               | Arrest               | checkbox      | checkbox      |
| Yes      | series tag  | domestic             | Domestic             | checkbox      | checkbox      |
| Yes      | series tag  | beat                 | Beat                 | text          | text          |
| Yes      | series tag  | district             | District             | text          | text          |
| Yes      | series tag  | ward                 | Ward                 | text          | number        |
| Yes      | series tag  | community_area       | Community Area       | text          | text          |
| Yes      | series tag  | fbi_code             | FBI Code             | text          | text          |
| No       |             | x_coordinate         | X Coordinate         | number        | number        |
| No       |             | y_coordinate         | Y Coordinate         | number        | number        |
| No       |             | year                 | Year                 | number        | number        |
| No       |             | updated_on           | Updated On           | calendar_date | calendar_date |
| No       |             | latitude             | Latitude             | number        | number        |
| No       |             | longitude            | Longitude            | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,x_coordinate,y_coordinate,updated_on,latitude,longitude,year
```

## Data Commands

```ls
series e:ijzp-q8t2 d:2012-04-24T09:00:00.000Z t:beat=0631 t:case_number=HV398745 t:primary_type="OTHER OFFENSE" t:block="080XX S DREXEL AVE" t:location_description=RESIDENCE t:iucr=2820 t:domestic=false t:arrest=false t:ward=8 t:description="TELEPHONE THREAT" t:fbi_code=26 t:community_area=44 t:district=006 m:row_number.ijzp-q8t2=1

series e:ijzp-q8t2 d:2012-07-24T21:45:00.000Z t:beat=0522 t:case_number=HV398864 t:primary_type=ROBBERY t:block="0000X W 111TH ST" t:location_description=SIDEWALK t:iucr=0313 t:domestic=false t:arrest=false t:ward=34 t:description="ARMED: OTHER DANGEROUS WEAPON" t:fbi_code=03 t:community_area=49 t:district=005 m:row_number.ijzp-q8t2=2

series e:ijzp-q8t2 d:2012-07-24T09:00:00.000Z t:beat=1632 t:case_number=HV398879 t:primary_type="OTHER OFFENSE" t:block="036XX N NEWLAND AVE" t:location_description=RESIDENCE t:iucr=2825 t:domestic=true t:arrest=false t:ward=36 t:description="HARASSMENT BY TELEPHONE" t:fbi_code=26 t:community_area=17 t:district=016 m:row_number.ijzp-q8t2=3
```

## Meta Commands

```ls
metric m:row_number.ijzp-q8t2 p:long l:"Row Number"

entity e:ijzp-q8t2 l:"Crimes - 2001 to present" t:attribution="Chicago Police Department" t:url=https://data.cityofchicago.org/api/views/ijzp-q8t2

property e:ijzp-q8t2 t:meta.view v:id=ijzp-q8t2 v:category="Public Safety" v:attributionLink=https://portal.chicagopolice.org/portal/page/portal/ClearPath v:averageRating=0 v:name="Crimes - 2001 to present" v:attribution="Chicago Police Department"

property e:ijzp-q8t2 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ijzp-q8t2 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| id      | case_number | date                | block                | iucr | primary_type      | description                   | location_description              | arrest | domestic | beat | district | ward | community_area | fbi_code | x_coordinate | y_coordinate | year | updated_on          | latitude     | longitude     | 
| ======= | =========== | =================== | ==================== | ==== | ================= | ============================= | ================================= | ====== | ======== | ==== | ======== | ==== | ============== | ======== | ============ | ============ | ==== | =================== | ============ | ============= | 
| 8722256 | HV398745    | 2012-04-24T09:00:00 | 080XX S DREXEL AVE   | 2820 | OTHER OFFENSE     | TELEPHONE THREAT              | RESIDENCE                         | false  | false    | 0631 | 006      | 8    | 44             | 26       | 1183631      | 1851826      | 2012 | 2016-02-04T06:33:39 | 41.748596176 | -87.602681146 | 
| 8722257 | HV398864    | 2012-07-24T21:45:00 | 0000X W 111TH ST     | 0313 | ROBBERY           | ARMED: OTHER DANGEROUS WEAPON | SIDEWALK                          | false  | false    | 0522 | 005      | 34   | 49             | 03       | 1177987      | 1831364      | 2012 | 2016-02-04T06:33:39 | 41.692575418 | -87.62398042  | 
| 8722258 | HV398879    | 2012-07-24T09:00:00 | 036XX N NEWLAND AVE  | 2825 | OTHER OFFENSE     | HARASSMENT BY TELEPHONE       | RESIDENCE                         | false  | true     | 1632 | 016      | 36   | 17             | 26       | 1129433      | 1923388      | 2012 | 2016-02-04T06:33:39 | 41.946065234 | -87.799655849 | 
| 8722260 | HV398881    | 2012-07-24T22:05:00 | 036XX W WOLFRAM ST   | 1330 | CRIMINAL TRESPASS | TO LAND                       | CHURCH/SYNAGOGUE/PLACE OF WORSHIP | true   | false    | 2523 | 025      | 30   | 21             | 26       | 1151607      | 1918709      | 2012 | 2016-02-04T06:33:39 | 41.932817907 | -87.718274183 | 
| 8722261 | HV398807    | 2012-07-24T20:50:00 | 012XX W 95TH ST      | 0554 | ASSAULT           | AGG PO HANDS NO/MIN INJURY    | STREET                            | false  | false    | 2213 | 022      | 21   | 73             | 08A      | 1169568      | 1841771      | 2012 | 2016-02-04T06:33:39 | 41.721319971 | -87.654503446 | 
| 8722262 | HV398860    | 2012-07-24T22:10:00 | 074XX S KINGSTON AVE | 1811 | NARCOTICS         | POSS: CANNABIS 30GMS OR LESS  | SIDEWALK                          | true   | false    | 0334 | 003      | 7    | 43             | 18       | 1194374      | 1856216      | 2012 | 2016-02-04T06:33:39 | 41.760385599 | -87.563171652 | 
| 8722263 | HV398690    | 2012-07-24T19:15:00 | 133XX S CORLISS AVE  | 1310 | CRIMINAL DAMAGE   | TO PROPERTY                   | RESIDENCE                         | false  | false    | 0533 | 005      | 9    | 54             | 14       | 1184055      | 1817414      | 2012 | 2016-02-04T06:33:39 | 41.654155378 | -87.602197973 | 
| 8722264 | HV398822    | 2012-07-24T22:00:00 | 066XX S HALSTED ST   | 1330 | CRIMINAL TRESPASS | TO LAND                       | GAS STATION                       | true   | false    | 0723 | 007      | 6    | 68             | 26       | 1172118      | 1860614      | 2012 | 2016-02-04T06:33:39 | 41.772972076 | -87.644610871 | 
| 8722265 | HV398739    | 2012-07-24T19:44:00 | 026XX W WINNEMAC AVE | 4387 | OTHER OFFENSE     | VIOLATE ORDER OF PROTECTION   | SIDEWALK                          | true   | true     | 2031 | 020      | 40   | 4              | 26       | 1157772      | 1933439      | 2012 | 2016-02-04T06:33:39 | 41.97311432  | -87.695215272 | 
| 8722266 | HV398912    | 2012-07-24T22:35:00 | 051XX W NORTH AVE    | 1330 | CRIMINAL TRESPASS | TO LAND                       | PARKING LOT/GARAGE(NON.RESID.)    | true   | false    | 2533 | 025      | 37   | 25             | 26       | 1141936      | 1910153      | 2012 | 2016-02-04T06:33:39 | 41.909524222 | -87.754026988 | 
```