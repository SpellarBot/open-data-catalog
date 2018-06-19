# 2014 Endorsed Budget - Expenditure Allowance by Budget Control Level (BCL)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-endorsed-budget-expenditure-allowance-by-budget-control-level-bcl-d6f47) |
| Metadata | [Link](https://data.seattle.gov/api/views/nrfc-hypb) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/nrfc-hypb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/nrfc-hypb/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | nrfc-hypb |
| Name | 2014 Endorsed Budget - Expenditure Allowance by Budget Control Level (BCL) |
| Attribution | City Budget Office |
| Category | Finance |
| Tags | 2014 endorsed budget |
| Created | 2013-06-07T21:20:31Z |
| Publication Date | 2013-06-07T21:25:06Z |

## Description

The City of Seattle implements biennial budgeting through the sequential adoption
of two one-year budgets. When adopting the budget for the first year of the biennium, the Council endorses a budget for the second year. 

The Endorsed Budget is the basis for a Proposed Budget for the second year of the biennium, and is reviewed and adopted in the fall of the first year of the biennium.

This data reflects all appropriations (by budget control level) included in the 2014 Endorsed Budget.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | fund                       | Fund                       | text      | text        |
| Yes      | series tag     | department                 | Department                 | text      | text        |
| Yes      | series tag     | bcl_code                   | BCL Code                   | text      | text        |
| Yes      | series tag     | bcl_name                   | BCL Name                   | text      | text        |
| Yes      | series tag     | bcl_purpose                | BCL Purpose                | text      | text        |
| Yes      | numeric metric | 2014_expenditure_allowance | 2014 Expenditure Allowance | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nrfc-hypb d:2014-01-01T00:00:00.000Z t:bcl_code=V1CIV t:bcl_purpose="The purpose of the Civil Service Commissions Budget Control Level is to provide administrative support to the Public Safety Civil Service Commission (PSCSC) and the Civil Service Commission (CSC). The PSCSC provides sworn police and uniformed fire employees with a quasi-judicial process for hearings on appeals concerning disciplinary actions, examination and testing, and other related issues. The CSC directs the civil service system for all other employees of the City. Itinvestigates allegations of political patronage so the City's hiring process conforms to the merit system set forth in the City Charter. These commissions will at times improve the City personnel system by developing legislation for the Mayor and City Council." t:department="Civil Service Commissions" t:fund="General Subfund" t:bcl_name="Civil Service Commissions" m:2014_expenditure_allowance=385887

series e:nrfc-hypb d:2014-01-01T00:00:00.000Z t:bcl_code=I3100 t:bcl_purpose="The purpose of the Director's Office Budget Control Level is to provide executive leadership, communications, and operational support for the entire department." t:department="Department of Neighborhoods" t:fund="General Subfund" t:bcl_name="Director's Office" m:2014_expenditure_allowance=485705

series e:nrfc-hypb d:2014-01-01T00:00:00.000Z t:bcl_code=I3200 t:bcl_purpose="The purpose of the Internal Operations Budget Control Level is to provide financial, human resources, facility, administrative, and information technology services to the Department's employees to serve customers efficiently and effectively." t:department="Department of Neighborhoods" t:fund="General Subfund" t:bcl_name="Internal Operations" m:2014_expenditure_allowance=1426675
```

## Meta Commands

```ls
metric m:2014_expenditure_allowance p:integer l:"2014 Expenditure Allowance" t:dataTypeName=money

entity e:nrfc-hypb l:"2014 Endorsed Budget - Expenditure Allowance by Budget Control Level (BCL)" t:attribution="City Budget Office" t:url=https://data.seattle.gov/api/views/nrfc-hypb

property e:nrfc-hypb t:meta.view v:id=nrfc-hypb v:category=Finance v:averageRating=0 v:name="2014 Endorsed Budget - Expenditure Allowance by Budget Control Level (BCL)" v:attribution="City Budget Office"

property e:nrfc-hypb t:meta.view.owner v:id=4fw3-mzms v:profileImageUrlMedium=/api/users/4fw3-mzms/profile_images/THUMB v:profileImageUrlLarge=/api/users/4fw3-mzms/profile_images/LARGE v:screenName="City Budget Office" v:profileImageUrlSmall=/api/users/4fw3-mzms/profile_images/TINY v:displayName="City Budget Office"

property e:nrfc-hypb t:meta.view.tableauthor v:id=4fw3-mzms v:profileImageUrlMedium=/api/users/4fw3-mzms/profile_images/THUMB v:profileImageUrlLarge=/api/users/4fw3-mzms/profile_images/LARGE v:screenName="City Budget Office" v:profileImageUrlSmall=/api/users/4fw3-mzms/profile_images/TINY v:roleName=publisher v:displayName="City Budget Office"
```

## Top Records

```ls
| fund            | department                      | bcl_code | bcl_name                                 | bcl_purpose                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 2014_expenditure_allowance | 
| =============== | =============================== | ======== | ======================================== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | ========================== | 
| General Subfund | Civil Service Commissions       | V1CIV    | Civil Service Commissions                | The purpose of the Civil Service Commissions Budget Control Level is to provide administrative support to the Public Safety Civil Service Commission (PSCSC) and the Civil Service Commission (CSC). The PSCSC provides sworn police and uniformed fire employees with a quasi-judicial process for hearings on appeals concerning disciplinary actions, examination and testing, and other related issues. The CSC directs the civil service system for all other employees of the City. Itinvestigates allegations of political patronage so the City's hiring process conforms to the merit system set forth in the City Charter. These commissions will at times improve the City personnel system by developing legislation for the Mayor and City Council. | 385887                     | 
| General Subfund | Department of Neighborhoods     | I3100    | Director's Office                        | The purpose of the Director's Office Budget Control Level is to provide executive leadership, communications, and operational support for the entire department.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 485705                     | 
| General Subfund | Department of Neighborhoods     | I3200    | Internal Operations                      | The purpose of the Internal Operations Budget Control Level is to provide financial, human resources, facility, administrative, and information technology services to the Department's employees to serve customers efficiently and effectively.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 1426675                    | 
| General Subfund | Department of Neighborhoods     | I3300    | Community Building                       | The purpose of the Community Building Budget Control Level is to deliver technical assistance, support services, and programs in neighborhoods to strengthen local communities, engage residents in neighborhood improvement, leverage resources, and complete neighborhood-initiated projects.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 3458080                    | 
| General Subfund | Department of Neighborhoods     | I4100    | Youth Violence Prevention                | The purpose of the Youth Violence Prevention Budget Control Level is to reduce juvenile violent crimes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 5631045                    | 
| General Subfund | Ethics and Elections Commission | V1T00    | Ethics and Elections                     | The purpose of the Ethics and Elections Budget Control Level is threefold: 1) to audit, investigate, and conduct hearings regarding non-compliance with, or violations of, Commission-administered ordinances; 2) to advise all City officials and employees of their obligations under Commission-administered ordinances; and 3) to publish and broadly distribute information about the City's ethical standards, City election campaigns, campaign financial disclosure statements, and lobbyist disclosure statements.                                                                                                                                                                                                                                      | 782800                     | 
| General Subfund | Executive                       | CZ000    | City Budget Office                       | The purpose of the City Budget Office Budget Control Level is to develop and monitor the budget, carrying out budget-related functions, oversee financial policies and plans, and provide financial and other strategic analysis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 4206264                    | 
| General Subfund | Executive                       | VJ100    | Jail Services                            | The purpose of the Jail Services Budget Control Level is to provide for the booking, housing, transporting, and guarding of City inmates. The jail population, for which the City pays, are adults charged with or convicted of misdemeanor crimes alleged to have been committed within the Seattle city limits.                                                                                                                                                                                                                                                                                                                                                                                                                                                | 16702137                   | 
| General Subfund | Executive                       | VJ500    | Indigent Defense Services                | The purpose of the Indigent Defense Services Budget Control Level is to secure legal defense services, as required by state law, for indigent people facing criminal charges in Seattle Municipal Court.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 6533471                    | 
| General Subfund | Executive                       | X1000    | Office of Sustainability and Environment | The purpose of the Office of Sustainability and Environment Budget Control Level is to develop, communicate, implement, and lead the City's Climate Protection and Green Seattle initiatives.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 2092173                    | 
```