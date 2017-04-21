# Mined Land Permits: Beginning 1974

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mined-land-permits-beginning-1974) |
| Metadata | [Link](https://data.ny.gov/api/views/va8e-9s3h) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/va8e-9s3h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/va8e-9s3h/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | va8e-9s3h |
| Name | Mined Land Permits: Beginning 1974 |
| Attribution | New York State Dept. of Environmental Conservation |
| Category | Energy & Environment |
| Tags | mined land, mines, aggregate, stone, gravel, minerals |
| Created | 2014-09-12T16:09:24Z |
| Publication Date | 2017-04-20T10:14:18Z |

## Description

This coverage contains data from the Division of Mineral Resources Mined Lands permit files.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                             | Data Type     | Render Type   |
| ======== | ============== | ========================= | ================================ | ============= | ============= |
| Yes      | series tag     | mine_id_number            | Mine ID Number                   | text          | number        |
| Yes      | series tag     | permittee_name            | Permittee Name                   | text          | text          |
| Yes      | series tag     | mine_name                 | Mine Name                        | text          | text          |
| Yes      | series tag     | status                    | Status                           | text          | text          |
| Yes      | series tag     | facility_location         | Facility Location                | text          | text          |
| Yes      | series tag     | facility_county           | County                           | text          | text          |
| Yes      | series tag     | facility_town             | Town                             | text          | text          |
| Yes      | numeric metric | acres_controlled          | Acres Controlled                 | number        | number        |
| Yes      | numeric metric | acres_life_of_mine        | Acres Permitted for Life Of Mine | number        | number        |
| Yes      | numeric metric | acres_affected            | Acres Affected                   | number        | number        |
| Yes      | numeric metric | acres_reclaimed           | Acres Reclaimed                  | number        | number        |
| Yes      | numeric metric | acres_bb                  | Acres BB                         | number        | number        |
| Yes      | numeric metric | acresbb_range             | Acres BB Range                   | number        | number        |
| Yes      | series tag     | commodity                 | Commodity                        | text          | text          |
| No       |                | initial_permit_date       | Initial Permit Date              | calendar_date | calendar_date |
| No       |                | permit_issue_date         | Permit Issue Date                | calendar_date | calendar_date |
| No       |                | permit_end_date           | Permit End Date                  | calendar_date | calendar_date |
| No       |                | date_of_last_inspection   | Date Of Last Inspection          | calendar_date | calendar_date |
| No       |                | latitude                  | Latitude                         | number        | number        |
| No       |                | longitude                 | Longitude                        | number        | number        |
| Yes      | series tag     | reclamationtype           | Reclamation Type                 | text          | text          |
| Yes      | numeric metric | financial_security_amount | Financial Security Amount        | number        | number        |
| Yes      | series tag     | underground_mine          | Underground Mine                 | text          | text          |
| Yes      | time           | last_modified_date        | Last Modified Date               | calendar_date | calendar_date |
| Yes      | series tag     | map_flag                  | Map Flag                         | text          | text          |
```

## Time Field

```ls
Value = last_modified_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = permit_issue_date,initial_permit_date,date_of_last_inspection,latitude,longitude,permit_end_date
```

## Data Commands

```ls
series e:va8e-9s3h d:2003-03-19T00:00:00.000Z t:permittee_name="North Hempstead, Town of Sol Waste Manag" t:map_flag=UCR t:commodity="Sand and Gravel" t:status=R t:mine_id_number=10006 t:reclamationtype=R/C t:facility_location="802 West Shore Rd, Port Washington, NY, 11050 0239" t:facility_county=Nassau t:facility_town="North Hempstead" t:underground_mine=No m:acres_reclaimed=273 m:acresbb_range=1 m:financial_security_amount=0 m:acres_affected=273 m:acres_bb=0 m:acres_life_of_mine=273 m:acres_controlled=460

series e:va8e-9s3h d:2017-03-06T00:00:00.000Z t:permittee_name="Wainscott Properties Inc" t:map_flag=UCR t:commodity="Sand and Gravel" t:status=R t:mine_id_number=10012 t:reclamationtype=OTH t:facility_location="P.O. Box 1259, Wainscott, NY, 11975-0125" t:facility_county=Suffolk t:facility_town="East Hampton" t:underground_mine=No m:acres_reclaimed=26 m:acresbb_range=1 m:financial_security_amount=80000 m:acres_affected=26 m:acres_bb=0 m:acres_life_of_mine=26 m:acres_controlled=70

series e:va8e-9s3h d:2010-06-10T00:00:00.000Z t:permittee_name="Riverhead, Town of" t:map_flag=UCR t:commodity="Sand and Gravel" t:status=R t:mine_id_number=10013 t:reclamationtype=R/C t:facility_location="Town Hall 200 Howell Ave, Riverhead, NY, 11901" t:facility_county=Suffolk t:mine_name="Town Of Riverhead" t:facility_town=Riverhead t:underground_mine=No m:acres_reclaimed=19 m:acresbb_range=1 m:financial_security_amount=0 m:acres_affected=19 m:acres_bb=0 m:acres_life_of_mine=19 m:acres_controlled=29.5
```

## Meta Commands

```ls
metric m:acres_controlled p:float l:"Acres Controlled" d:"Total acreage currently controlled by a permittee at any given mine site" t:dataTypeName=number

metric m:acres_life_of_mine p:float l:"Acres Permitted for Life Of Mine" d:"The amount of acres that were/are or going to be permitted over the entire life of the mine." t:dataTypeName=number

metric m:acres_affected p:float l:"Acres Affected" d:"Total amount of acres affected or to be affected from April 1, 1975 to present." t:dataTypeName=number

metric m:acres_reclaimed p:float l:"Acres Reclaimed" d:"Acres Reclaimed represents the number of acres approved as reclaimed at permitted sites since 1975." t:dataTypeName=number

metric m:acres_bb p:float l:"Acres BB" d:"The current net affected acres or to be affected acres at the mine site, derived from AcresAffected minus AcresReclaimed and used to determine the billable acres at a mine site." t:dataTypeName=number

metric m:acresbb_range p:float l:"Acres BB Range" d:"Range of net affected acres for fee billing purposes. An abbreviated number representation of the amount of net affected acres currently permitted and billed. 1 = a mine with a net affected acreage of up to and including 5 acres, 2 = a mine with a net affected acreage greater than 5 up to and including 10 acres, 3 = a mine with a net affected acreage greater than 10 up to and including 20 acres, 4 = a mine with a net affected acreage greater than 20 up to and including 30 acres, 5 = a mine with a net affected acreage greater than 30 acres." t:dataTypeName=number

metric m:financial_security_amount p:integer l:"Financial Security Amount" d:"Amount of financial security required to ensure reclamation of the site. Financial security funds are held in escrow until such time as an operator has completed mining and reclamation at the site." t:dataTypeName=number

entity e:va8e-9s3h l:"Mined Land Permits: Beginning 1974" t:attribution="New York State Dept. of Environmental Conservation" t:url=https://data.ny.gov/api/views/va8e-9s3h

property e:va8e-9s3h t:meta.view v:id=va8e-9s3h v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/lands/5020.html v:averageRating=0 v:name="Mined Land Permits: Beginning 1974" v:attribution="New York State Dept. of Environmental Conservation"

property e:va8e-9s3h t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:va8e-9s3h t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:va8e-9s3h t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| mine_id_number | permittee_name                           | mine_name               | status | facility_location                                  | facility_county | facility_town   | acres_controlled | acres_life_of_mine | acres_affected | acres_reclaimed | acres_bb | acresbb_range | commodity       | initial_permit_date | permit_issue_date   | permit_end_date     | date_of_last_inspection | latitude           | longitude           | reclamationtype | financial_security_amount | underground_mine | last_modified_date  | map_flag | 
| ============== | ======================================== | ======================= | ====== | ================================================== | =============== | =============== | ================ | ================== | ============== | =============== | ======== | ============= | =============== | =================== | =================== | =================== | ======================= | ================== | =================== | =============== | ========================= | ================ | =================== | ======== | 
| 10006          | North Hempstead, Town of Sol Waste Manag |                         | R      | 802 West Shore Rd, Port Washington, NY, 11050 0239 | Nassau          | North Hempstead | 460.00           | 273.00             | 273.00         | 273.00          | 0.00     | 1.00          | Sand and Gravel |                     | 1997-04-28T00:00:00 | 2001-04-30T00:00:00 | 2000-10-05T00:00:00     | 40.825600000000001 | -73.664370000000005 | R/C             | 0                         | No               | 2003-03-19T00:00:00 | UCR      | 
| 10012          | Wainscott Properties Inc                 |                         | R      | P.O. Box 1259, Wainscott, NY, 11975-0125           | Suffolk         | East Hampton    | 70.00            | 26.00              | 26.00          | 26.00           | 0.00     | 1.00          | Sand and Gravel |                     |                     | 1995-04-10T00:00:00 |                         | 40.950600000000001 | -72.244129999999998 | OTH             | 80000                     | No               | 2017-03-06T00:00:00 | UCR      | 
| 10013          | Riverhead, Town of                       | Town Of Riverhead       | R      | Town Hall 200 Howell Ave, Riverhead, NY, 11901     | Suffolk         | Riverhead       | 29.50            | 19.00              | 19.00          | 19.00           | 0.00     | 1.00          | Sand and Gravel | 1981-01-06T00:00:00 |                     | 1992-08-01T00:00:00 | 2010-06-07T00:00:00     | 40.942300000000003 | -72.722440000000006 | R/C             | 0                         | No               | 2010-06-10T00:00:00 | UCR      | 
| 10015          | M T C Realty Inc                         |                         | R      | P.O. Box 278, Hicksville, NY 11802-0027            | Nassau          | Oyster Bay      | 0.00             | 10.00              | 10.00          | 10.00           | 0.00     | 1.00          | Sand and Gravel |                     |                     | 1987-05-10T00:00:00 |                         | 40.710599999999999 | -73.184560000000005 | IND             | 14000                     | No               | 2017-03-06T00:00:00 | UCR      | 
| 10022          | Little Joseph Realty Corp                |                         | R      | P O Box 246, Farmingdale, NY, 11735 0024           | Suffolk         | Southampton     | 11.00            | 0.00               | 11.00          | 11.00           | 0.00     | 1.00          | Sand and Gravel |                     |                     | 1994-10-23T00:00:00 |                         | 40.8245            | -72.686040000000006 | R/C             | 33000                     | No               | 2007-04-11T00:00:00 | UCR      | 
| 10023          | Cardo, Charles & Son Inc                 |                         | R      | Box 477 Lamb Ave, Quogue, NY, 11959                | Suffolk         | Southampton     | 6.00             | 2.00               | 2.00           | 2.00            | 0.00     | 1.00          | Sand and Gravel |                     | 1993-02-05T00:00:00 | 1998-02-05T00:00:00 |                         | 40.826700000000002 | -72.626739999999998 | R/C             | 5000                      | No               | 2017-03-02T00:00:00 | UCR      | 
| 10030          | F & F Structures Inc                     |                         | N      | 100 Broad Hollow Road, Farmingdale, NY, 11735 0481 | Suffolk         | Huntington      | 0.00             | 0.00               | 10.00          | 10.00           | 0.00     | 1.00          | Sand and Gravel |                     |                     | 1985-01-20T00:00:00 |                         | 40.803600000000003 | -73.220759999999999 | IND             | 10000                     | No               | 2007-04-11T00:00:00 | UC       | 
| 10031          | Suffolk Material Mining                  | Suffolk Material Mining | R      |                                                    | Suffolk         | Brookhaven      | 12.00            | 12.00              | 12.00          | 12.00           | 0.00     | 1.00          | Sand and Gravel | 1981-12-19T00:00:00 |                     | 1990-04-27T00:00:00 | 2009-06-08T00:00:00     | 40.928600000000003 | -73.077849999999998 | R/C             | 12500                     | No               | 2009-06-09T00:00:00 | UCR      | 
| 10032          | Expressway Aggregates                    |                         | R      | P O Box 348, Commack, NY, 11725 0034               | Suffolk         | Smithtown       | 0.00             | 36.00              | 36.00          | 36.00           | 0.00     | 1.00          | Sand and Gravel |                     |                     | 1989-07-25T00:00:00 |                         | 40.803600000000003 | -73.282160000000005 | IND             | 100000                    | No               | 2007-04-11T00:00:00 | UCR      | 
| 10040          | Conklin, Thomas O                        | Conklin Sand and Gravel | R      | HAYGROUND RD, BRIDGEHAMPTON                        | Suffolk         | Southampton     | 0.00             | 3.00               | 3.00           | 3.00            | 0.00     | 1.00          | Sand and Gravel |                     |                     | 1992-08-25T00:00:00 |                         | 40.929699999999997 | -72.331429999999997 | AGRI            | 5000                      | No               | 2016-07-26T00:00:00 | UCR      | 
```