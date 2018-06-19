# Legislation in Committee

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/legislation-in-committee-5cadd) |
| Metadata | [Link](https://data.seattle.gov/api/views/pbfu-t32n) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/pbfu-t32n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/pbfu-t32n/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | pbfu-t32n |
| Name | Legislation in Committee |
| Attribution | Office of the City Clerk |
| Category | City Business |
| Created | 2011-09-21T13:56:15Z |
| Publication Date | 2012-07-13T14:48:51Z |

## Description

City of Seattle Legislation in Committee

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | =========== | ===================================== | ===================================== | ========= | =========== |
| No       | time        | :updated_at                           | updated_at                            | meta_data | meta_data   |
| No       |             | date_data_retrieved                   | Date data retrieved                   | text      | text        |
| Yes      | series tag  | record_type                           | Record Type                           | text      | text        |
| Yes      | series tag  | cf_ord_res_no_                        | CF/Ord/Res No.                        | text      | text        |
| Yes      | series tag  | url                                   | URL                                   | url       | url         |
| No       |             | date_introduced_referred_to_committee | Date Introduced/Referred to Committee | text      | text        |
| Yes      | series tag  | title                                 | Title                                 | text      | text        |
| Yes      | series tag  | sponsor                               | Sponsor                               | text      | text        |
| Yes      | series tag  | committee                             | Committee                             | text      | text        |
| Yes      | series tag  | indexing_terms                        | Indexing Terms                        | text      | text        |
| Yes      | series tag  | misc_notes                            | Misc. Notes                           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_data_retrieved,date_introduced_referred_to_committee
```

## Data Commands

```ls
series e:pbfu-t32n d:2012-07-13T07:48:19.000Z t:title="Appointment of Rita Brogan as member, Seattle ChinatownInternational District Preservation and Development Authority Council, for aterm of confirmation to December 31, 2014." t:committee="Planning,Land Use, and Sustainability" t:cf_ord_res_no_=312456 t:record_type="Clerk File" t:sponsor=Conlin t:url="http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312456&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S" m:row_number.pbfu-t32n=1

series e:pbfu-t32n d:2012-07-13T07:48:19.000Z t:title="Appointment of M. Lorena Gonzalez as member, Seattle Ethics andElections Commission, for a term of confirmation to December 31,2013." t:committee="Government Performance andFinance" t:cf_ord_res_no_=312455 t:record_type="Clerk File" t:sponsor=Burgess t:url="http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312455&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S" m:row_number.pbfu-t32n=2

series e:pbfu-t32n d:2012-07-13T07:48:19.000Z t:title="Application of AnMarCo / Pier 1 LLC to rezone approximately 6acres of land at 2130 Harbor Avenue Southwest from General Industrial 2 with an85 foot height limit (IG2 U/85) to Industrial Commercial with a 40 foot heightlimit (IC 40) and to redesignate the Seattle Shoreline Master Programenvironment from Urban Industrial (UI) to Urban Stable (US) (Project No.3009298, Type IV)." t:committee="Planning, Land Use,and Sustainability" t:cf_ord_res_no_=312432 t:record_type="Clerk File" t:sponsor="No Sponsor Required" t:url="http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312432&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S" m:row_number.pbfu-t32n=3
```

## Meta Commands

```ls
metric m:row_number.pbfu-t32n p:long l:"Row Number"

entity e:pbfu-t32n l:"Legislation in Committee" t:attribution="Office of the City Clerk" t:url=https://data.seattle.gov/api/views/pbfu-t32n

property e:pbfu-t32n t:meta.view v:id=pbfu-t32n v:category="City Business" v:attributionLink=http://clerk.seattle.gov v:averageRating=0 v:name="Legislation in Committee" v:attribution="Office of the City Clerk"

property e:pbfu-t32n t:meta.view.license v:name="Public Domain"

property e:pbfu-t32n t:meta.view.owner v:id=89pw-ch87 v:screenName="Office of the City Clerk" v:displayName="Office of the City Clerk"

property e:pbfu-t32n t:meta.view.tableauthor v:id=89pw-ch87 v:screenName="Office of the City Clerk" v:roleName=publisher v:displayName="Office of the City Clerk"
```

## Top Records

```ls
| :updated_at | date_data_retrieved  | record_type | cf_ord_res_no_ | url                                                                                                                                           | date_introduced_referred_to_committee | title                                                                                                                                                                                                                                                                                                                                                                                                                                                          | sponsor             | committee                                   | indexing_terms                                                | misc_notes | 
| =========== | ==================== | =========== | ============== | ============================================================================================================================================= | ===================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =========================================== | ============================================================= | ========== | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312456         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312456&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | Jul 16,2012                           | Appointment of Rita Brogan as member, Seattle ChinatownInternational District Preservation and Development Authority Council, for aterm of confirmation to December 31, 2014.                                                                                                                                                                                                                                                                                  | Conlin              | Planning,Land Use, and Sustainability       |                                                               |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312455         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312455&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | Jul 16,2012                           | Appointment of M. Lorena Gonzalez as member, Seattle Ethics andElections Commission, for a term of confirmation to December 31,2013.                                                                                                                                                                                                                                                                                                                           | Burgess             | Government Performance andFinance           |                                                               |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312432         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312432&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | Jun 25,2012                           | Application of AnMarCo / Pier 1 LLC to rezone approximately 6acres of land at 2130 Harbor Avenue Southwest from General Industrial 2 with an85 foot height limit (IG2 U/85) to Industrial Commercial with a 40 foot heightlimit (IC 40) and to redesignate the Seattle Shoreline Master Programenvironment from Urban Industrial (UI) to Urban Stable (US) (Project No.3009298, Type IV).                                                                      | No Sponsor Required | Planning, Land Use,and Sustainability       |                                                               |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312426         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312426&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | Jun 18,2012                           | Report of the Office of Professional Accountability Review Board(OPARB) on recommendations regarding civilian oversight of the Seattle PoliceDepartment.                                                                                                                                                                                                                                                                                                       | Harrell             | Public Safety, Civil Rights, andTechnology  |                                                               |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312425         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312425&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | Jun 18,2012                           | Petition of City Investors XX, LLC to vacate a portion of thealley in Block 93, D.T. Denny's First Addition to North Seattle, bounded byMercer Street, Westlake Avenue North, Republican Street, and 9th AvenueNorth.                                                                                                                                                                                                                                          | No sponsor required | Transportation                              |                                                               |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312413         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312413&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | Jun 11,2012                           | Reappointment and Oath of Office of Jorge Carrasco asSuperintendent of Seattle City Light, for a term of confirmation to July 23,2016.                                                                                                                                                                                                                                                                                                                         | O'Brien             | Energy and Environment                      | CITY-LIGHT,CITY-OFFICIALS-AND-AGENCIES                        |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312380         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312380&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | Jun 4,2012                            | Appointment and Oath of Office of Magdaleno M. Leno Rose-Avilaas Director of the Office of Immigrant and Refugee Affairs.                                                                                                                                                                                                                                                                                                                                      | Harrell             | Public Safety, Civil Rights, andTechnology  |                                                               |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312367         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312367&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | May 29,2012                           | Appointment of Judith M. Tobin as member, Pacific HospitalPreservation and Development Authority Governing Council, for a term ofconfirmation to December 31, 2015.                                                                                                                                                                                                                                                                                            | Licata              | Housing, HumanServices, Health, and Culture | APPOINTMENT, PUBLIC-CORPORATIONS,HOSPITALS, HEALTH-CARE       |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312365         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312365&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | May 29,2012                           | 2011 Annual Report of the Seattle City Attorney'sOffice.                                                                                                                                                                                                                                                                                                                                                                                                       | Harrell             | Public Safety, Civil Rights, andTechnology  | CITY-ATTORNEY                                                 |            | 
| 1342165699  | July 13 2012 7:43 AM | Clerk File  | 312357         | [http://clerk.seattle.gov/~scripts/nph-brs.exe?s1=&s3=312357&l=20&Sect5=CFCF1&Sect6=HITOFF&d=CFCF&p=1&u=%2F~public%2FCFCF1.htm&r=0&f=S, null] | May 21,2012                           | Application of Wallace GT-Northgate II LLC, for a contractrezone of 72,985 square feet of land at 525 NE Northgate Way from NeighborhoodCommercial 3 with a 65 foot height limit (NC3-65) to Neighborhood Commercial 3with an 85 foot height limit (NC3-85) for future construction of a seven-storystructure containing 22,976 square feet of commercial space, 262 residentialunits, and below-grade parking for 270 vehicles (Project No. 3012842, TypeIV.) | No Sponsor Required | Planning, Land Use, andSustainability       | CONTRACT-REZONES, MIXED-USE-DEVELOPMENT, NORTHGATE,MAPLE-LEAF |            | 
```