# 2010 Adopted Budget - Expenditures Allowance by Budget Control Level (BCL)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-adopted-budget-expenditures-allowance-by-budget-control-level-bcl-c7203) |
| Metadata | [Link](https://data.seattle.gov/api/views/emai-dima) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/emai-dima/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/emai-dima/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | emai-dima |
| Name | 2010 Adopted Budget - Expenditures Allowance by Budget Control Level (BCL) |
| Attribution | City Budget Office |
| Category | Finance |
| Tags | 2010 adopted budget, city budget office, budget control level, expenditure, city funds |
| Created | 2010-10-06T18:52:27Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Excel version of Attachment A to Ordinance 123177, the Budget Adoption Ordinance for 2010.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | fund                               | Fund                               | text      | text        |
| Yes      | series tag     | department                         | Department                         | text      | text        |
| Yes      | series tag     | bcl_code                           | BCL Code                           | text      | text        |
| Yes      | series tag     | bcl_name                           | BCL Name                           | text      | text        |
| Yes      | series tag     | bcl_purpose                        | BCL Purpose                        | text      | text        |
| Yes      | numeric metric | adopted_2010_expenditure_allowance | Adopted 2010 Expenditure Allowance | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:emai-dima d:2010-01-01T00:00:00.000Z t:bcl_code=33850-K72440 t:bcl_purpose="The purpose of the Debt Service and Contract Obligation Budget Control Level (BCL) is to meet principal repayment and interest obligations on funds borrowed to meet Parks and Recreation's capital expenditure requirements and to provide funds for centrally allocated contracting services. This BCL is funded by the 2000 Parks Levy Fund dollars (Fund 33850)." t:department="Department of Parks and Recreation" t:fund="2000 Parks Levy Fund" t:bcl_name="Debt Service and Contract Obligation (33850-CIP)" m:adopted_2010_expenditure_allowance=137000

series e:emai-dima d:2010-01-01T00:00:00.000Z t:bcl_code=34440-A1FL1 t:bcl_purpose="The purpose of the Neighborhood Fire Stations Budget Control Level (BCL) is to replace and renovate fire stations and other emergency response facilities as part of the Fire Facilities and Emergency Response Levy program.  This BCL is funded by 2003 Fire Facilities Fund dollars (Fund 34440)." t:department="Fleets and Facilities Department" t:fund="2003 Fire Facilities Subfund" t:bcl_name="Neighborhood Fire Stations (34440-CIP)" m:adopted_2010_expenditure_allowance=3830000

series e:emai-dima d:2010-01-01T00:00:00.000Z t:bcl_code=34800-S03P02 t:bcl_purpose="The purpose of the Facility Infrastructure Renovation and Repair Budget Control Level (BCL) is to provide for seismic improvements, roof repair and replacement, and other infrastructure improvements to facilities on the Seattle Center campus. This BCL is funded by 2003 LTGO Bond dollars (Fund 34800)." t:department="Seattle Center" t:fund="2003 LTGO Capital Project Fund" t:bcl_name="Facility Infrastructure Renovation and Repair (34800-CIP)" m:adopted_2010_expenditure_allowance=727000
```

## Meta Commands

```ls
metric m:adopted_2010_expenditure_allowance p:long l:"Adopted 2010 Expenditure Allowance" t:dataTypeName=number

entity e:emai-dima l:"2010 Adopted Budget - Expenditures Allowance by Budget Control Level (BCL)" t:attribution="City Budget Office" t:url=https://data.seattle.gov/api/views/emai-dima

property e:emai-dima t:meta.view v:id=emai-dima v:category=Finance v:averageRating=0 v:name="2010 Adopted Budget - Expenditures Allowance by Budget Control Level (BCL)" v:attribution="City Budget Office"

property e:emai-dima t:meta.view.owner v:id=4fw3-mzms v:profileImageUrlMedium=/api/users/4fw3-mzms/profile_images/THUMB v:profileImageUrlLarge=/api/users/4fw3-mzms/profile_images/LARGE v:screenName="City Budget Office" v:profileImageUrlSmall=/api/users/4fw3-mzms/profile_images/TINY v:displayName="City Budget Office"

property e:emai-dima t:meta.view.tableauthor v:id=4fw3-mzms v:profileImageUrlMedium=/api/users/4fw3-mzms/profile_images/THUMB v:profileImageUrlLarge=/api/users/4fw3-mzms/profile_images/LARGE v:screenName="City Budget Office" v:profileImageUrlSmall=/api/users/4fw3-mzms/profile_images/TINY v:roleName=publisher v:displayName="City Budget Office"
```

## Top Records

```ls
| fund                             | department                         | bcl_code      | bcl_name                                                  | bcl_purpose                                                                                                                                                                                                                                                                                                                                                                    | adopted_2010_expenditure_allowance | 
| ================================ | ================================== | ============= | ========================================================= | ============================================================================================================================================================================================================================================================================================================================================================================== | ================================== | 
| 2000 Parks Levy Fund             | Department of Parks and Recreation | 33850-K72440  | Debt Service and Contract Obligation (33850-CIP)          | The purpose of the Debt Service and Contract Obligation Budget Control Level (BCL) is to meet principal repayment and interest obligations on funds borrowed to meet Parks and Recreation's capital expenditure requirements and to provide funds for centrally allocated contracting services. This BCL is funded by the 2000 Parks Levy Fund dollars (Fund 33850).           | 137000                             | 
| 2003 Fire Facilities Subfund     | Fleets and Facilities Department   | 34440-A1FL1   | Neighborhood Fire Stations (34440-CIP)                    | The purpose of the Neighborhood Fire Stations Budget Control Level (BCL) is to replace and renovate fire stations and other emergency response facilities as part of the Fire Facilities and Emergency Response Levy program. This BCL is funded by 2003 Fire Facilities Fund dollars (Fund 34440).                                                                            | 3830000                            | 
| 2003 LTGO Capital Project Fund   | Seattle Center                     | 34800-S03P02  | Facility Infrastructure Renovation and Repair (34800-CIP) | The purpose of the Facility Infrastructure Renovation and Repair Budget Control Level (BCL) is to provide for seismic improvements, roof repair and replacement, and other infrastructure improvements to facilities on the Seattle Center campus. This BCL is funded by 2003 LTGO Bond dollars (Fund 34800).                                                                  | 727000                             | 
| 2005 LTGO Capital Project Fund   | Department of Parks and Recreation | 31032-K72440  | Debt Service and Contract Obligation (31032-CIP)          | The purpose of the Debt Service and Contract Obligation Budget Control Level (BCL) is to meet principal repayment and interest obligations on funds borrowed to meet Parks and Recreation's capital expenditure requirements and to provide funds for centrally allocated contracting services. This BCL is funded by the 2005 LTGO Capital Project Fund dollars (Fund 31032). | 1285000                            | 
| 2006 LTGO Capital Projects Fund  | Department of Parks and Recreation | 34900-K72440  | Debt Service and Contract Obligation (34900-CIP)          | The purpose of the Debt Service and Contract Obligation Budget Control Level (BCL) is to meet principal repayment and interest obligations on funds borrowed to meet Parks and Recreation?s capital expenditure requirements and to provide funds for centrally allocated contracting services. This BCL is funded by 2006 LTGO Bond dollars (Fund 34900).                     | 70000                              | 
| 2007 Multipurpose LTGO Bond Fund | Department of Parks and Recreation | 35100-K72440  | Debt Service and Contract Obligation (35100-CIP)          | The purpose of the Debt Service and Contract Obligation Budget Control Level (BCL) is to meet principal repayment and interest obligations on funds borrowed to meet Parks and Recreation?s capital expenditure requirements and to provide funds for centrally allocated contracting services. This BCL is funded by 2007 LTGO Bond dollars (Fund 35100).                     | 241000                             | 
| 2007 Multipurpose LTGO Bond Fund | Seattle Center                     | 35100-S9403   | Monorail Improvements (35100-CIP)                         | The purpose of the Monorail Improvements Budget Control Level (BCL) is to provide for the renovation of the Seattle Center Monorail, including the two trains, the two stations and the guideways that run in between. This BCL is funded by LTGO bond dollars (Fund 35100).                                                                                                   | 553000                             | 
| 2008 Multipurpose LTGO Bond Fund | Fleets and Facilities Department   | 35200-A1FL1   | Neighborhood Fire Stations (35200-CIP)                    | The purpose of the Neighborhood Fire Stations Budget Control Level (BCL) is to replace and renovate fire stations and other emergency response facilities as part of the Fire Facilities and Emergency Response Levy program. This BCL is funded by 2008 LTGO Bond dollars (Fund 35200).                                                                                       | 700000                             | 
| 2008 Parks Levy Fund             | Department of Parks and Recreation | 33860-K720010 | Neighborhood Park Acquisition (33860-CIP)                 | The purpose of the 2008 Parks Levy- Neighborhood Park Acquisition Budget Control Level (BCL) is to provide for neighborhood park acquisitions identified in the 2008 Parks Levy. This BCL is funded by the 2008 Parks Levy Fund (33860).                                                                                                                                       | 300000                             | 
| 2008 Parks Levy Fund             | Department of Parks and Recreation | 33860-K720011 | Green Space Acquisition (33860-CIP)                       | The purpose of the 2008 Parks Levy ? Green Space Acquisitions Budget Control Level (BCL) is to provide for green space park acquisitions identified in the 2008 Parks Levy. This BCL is funded by the 2008 Parks Levy Fund (Fund 33860).                                                                                                                                       | 1050000                            | 
```