# Police Incidents 01012005 to Current

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-incidents-01012005-to-current) |
| Metadata | [Link](https://data.hartford.gov/api/views/889t-nwfu) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/889t-nwfu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/889t-nwfu/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | 889t-nwfu |
| Name | Police Incidents 01012005 to Current |
| Attribution | City of Hartford |
| Category | Public Safety |
| Tags | crime, police, hartford police, incidents, police incidents, hartford, ct |
| Created | 2014-08-29T17:23:17Z |
| Publication Date | 2015-04-27T10:44:08Z |

## Description

This dataset reflects reported incidents of crime (with the exception of sexual assaults, which are excluded by statute) that occurred in the City of Hartford from 2005 to the present, minus the most recent ten days. Data is extracted from the City of Hartford Police Department's CrimeView database on a daily basis. Should you have questions about this dataset, you may contact the Crime Analysis Division of the Hartford Police Department at 860.757.4020 or policechief@Hartford.gov. Disclaimer: These incidents are based on crimes verified by the Hartford Police Department's Crime Analysis Division. The crime classifications may be changed at a later date based upon additional investigation and there is always the possibility of mechanical or human error. Therefore, the Hartford Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information and the information should not be used for comparison purposes over time. The Hartford Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate. The Hartford Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of Hartford or Hartford Police Department web page. The user specifically acknowledges that the Hartford Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. The unauthorized use of the words "Hartford Police Department", "Hartford Police", "HPD" or any colorable imitation of these words or the unauthorized use of the Hartford Police Department logo is unlawful. This web page does not, in any way, authorize such use. The dataset contains more than 400,000 records/rows of data and cannot be viewed in full in Microsoft Excel. Therefore, when downloading the file, select CSV from the Export menu. Open the file in an ASCII text editor, such as Wordpad, to view and search. To access a list of Hartford Police Department - Uniform Crime Reporting (UCR) codes, select the about tab on the right side of this page and scroll down to the attachments and open the PDF document.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| Yes      | series tag  | case_number       | Case_Number       | text      | number      |
| Yes      | time        | date              | Date              | date      | date        |
| No       |             | time_24hr         | Time_24HR         | text      | text        |
| No       |             | address           | Address           | text      | text        |
| Yes      | series tag  | ucr_1_category    | UCR_1_Category    | text      | text        |
| Yes      | series tag  | ucr_1_description | UCR_1_Description | text      | text        |
| Yes      | series tag  | ucr_1_code        | UCR_1_Code        | text      | number      |
| Yes      | series tag  | ucr_2_category    | UCR_2_Category    | text      | text        |
| Yes      | series tag  | ucr_2_description | UCR_2_Description | text      | text        |
| Yes      | series tag  | ucr_2_code        | UCR_2_Code        | text      | number      |
| Yes      | series tag  | neighborhood      | Neighborhood      | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = time_24hr,address
```

## Data Commands

```ls
series e:889t-nwfu d:2010-03-03T00:00:00.000Z t:ucr_1_code=3223 t:case_number=10008320 t:neighborhood="NORTH MEADOWS" t:ucr_2_category="23* - DRIVING LAWS" t:ucr_1_category="32* - PROPERTY DAMAGE ACCIDENT" t:ucr_2_description="FOLL TOO CLOSE" t:ucr_2_code=2334 t:ucr_1_description="PROP DAM ACC" m:row_number.889t-nwfu=1

series e:889t-nwfu d:2014-08-13T00:00:00.000Z t:ucr_1_code=3221 t:case_number=14026865 t:neighborhood="ASYLUM HILL" t:ucr_2_category="24* - MOTOR VEHICLE LAWS" t:ucr_1_category="32* - PROPERTY DAMAGE ACCIDENT" t:ucr_2_description="EVADING RESP" t:ucr_2_code=2401 t:ucr_1_description="PROP DAM ACC" m:row_number.889t-nwfu=2

series e:889t-nwfu d:2014-03-21T00:00:00.000Z t:ucr_1_code=2329 t:case_number=14009042 t:neighborhood="BEHIND THE ROCKS" t:ucr_2_category="24* - MOTOR VEHICLE LAWS" t:ucr_1_category="23* - DRIVING LAWS" t:ucr_2_description="OP UNREG M/V" t:ucr_2_code=2414 t:ucr_1_description="STOP SIGN" m:row_number.889t-nwfu=3
```

## Meta Commands

```ls
metric m:row_number.889t-nwfu p:long l:"Row Number"

entity e:889t-nwfu l:"Police Incidents 01012005 to Current" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/889t-nwfu

property e:889t-nwfu t:meta.view v:id=889t-nwfu v:category="Public Safety" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Police Incidents 01012005 to Current" v:attribution="City of Hartford"

property e:889t-nwfu t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:889t-nwfu t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:889t-nwfu t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| case_number | date       | time_24hr | address                      | ucr_1_category                 | ucr_1_description | ucr_1_code | ucr_2_category              | ucr_2_description | ucr_2_code | neighborhood        | 
| =========== | ========== | ========= | ============================ | ============================== | ================= | ========== | =========================== | ================= | ========== | =================== | 
| 10008320    | 1267574400 | 1355      | JENNINGS RD & LEIBERT RD     | 32* - PROPERTY DAMAGE ACCIDENT | PROP DAM ACC      | 3223       | 23* - DRIVING LAWS          | FOLL TOO CLOSE    | 2334       | NORTH MEADOWS       | 
| 14026865    | 1407888000 | 1035      | 25 SIGOURNEY ST              | 32* - PROPERTY DAMAGE ACCIDENT | PROP DAM ACC      | 3221       | 24* - MOTOR VEHICLE LAWS    | EVADING RESP      | 2401       | ASYLUM HILL         | 
| 14009042    | 1395360000 | 1055      | BROOKFIELD ST & ELLINGTON ST | 23* - DRIVING LAWS             | STOP SIGN         | 2329       | 24* - MOTOR VEHICLE LAWS    | OP UNREG M/V      | 2414       | BEHIND THE ROCKS    | 
| 15023364    | 1438041600 | 1118      | 104 LOVE LN                  | 29* - FOUND PERSON/PROPERTY    | ABANDONED M/V     | 2903       |                             |                   | 0          | NORTHEAST           | 
| 11008245    | 1299283200 | 1243      | AIRPORT RD & WETHERSFIELD AV | 31* - PERSONAL INJURY ACCIDENT | PERS INJ ACC      | 3124       | 23* - DRIVING LAWS          | FTGRW/DRIVEWAY    | 2336       | SOUTHEND            | 
| 12006910    | 1330300800 | 2024      | MAIN ST & MAPLE AV           | 23* - DRIVING LAWS             | MECH SIGNAL       | 2315       | 24* - MOTOR VEHICLE LAWS    | OP UNDER SUSP     | 2411       | SHELDON-CHARTER OAK | 
| 13024754    | 1374105600 | 1110      | MAHL AV & MAIN ST            | 39* - ANIMAL COMPLAINT         | ANIMAL COMPLNT    | 3901       |                             |                   | 0          | CLAY-ARSENAL        | 
| 10040458    | 1287964800 | 1349      | 124 EDGEWOOD ST              | 08* - SIMPLE ASSAULT           | INTFERING W PO    | 805        | 23* - DRIVING LAWS          | RECKLESS DRIVING  | 2326       | UPPER ALBANY        | 
| 12026919    | 1343952000 | 1602      | 7 ALBANY AV                  | 06* - LARCENY                  | LARC4-MISCELL     | 685        |                             |                   | 0          | CLAY-ARSENAL        | 
| 12002075    | 1326844800 | 1600      | 60 WADSWORTH ST              | 28* - MISSING PERSON/PROPERTY  | MISSING PERS      | 2801       | 29* - FOUND PERSON/PROPERTY | FOUND PERSON      | 2901       | SOUTH GREEN         | 
```