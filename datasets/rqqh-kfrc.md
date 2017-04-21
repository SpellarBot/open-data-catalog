# 2012 Adopted Budget - Expenditure Allowance by Budget Control Level (BCL)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-adopted-budget-expenditure-allowance-by-budget-control-level-bcl-8e7b1) |
| Metadata | [Link](https://data.seattle.gov/api/views/rqqh-kfrc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/rqqh-kfrc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/rqqh-kfrc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | rqqh-kfrc |
| Name | 2012 Adopted Budget - Expenditure Allowance by Budget Control Level (BCL) |
| Attribution | City Budget Office |
| Category | Finance |
| Tags | 2012 adopted budget |
| Created | 2012-02-13T23:00:22Z |
| Publication Date | 2012-02-13T23:05:44Z |

## Description

This data reflects all appropriations (by budget control level) included in the 2012 Adopted Budget.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| Yes      | series tag     | fund_name                       | Fund Name                         | text      | text        |
| Yes      | series tag     | department                      | Department                        | text      | text        |
| Yes      | series tag     | budget_control_level_bcrls_code | Budget Control Level (BCRLS) Code | text      | text        |
| Yes      | series tag     | budget_control_level_bcl_name   | Budget Control Level (BCL) Name   | text      | text        |
| Yes      | series tag     | bcl_purpose                     | BCL Purpose                       | text      | text        |
| Yes      | numeric metric | expenditure_allowance           | 2012 Expenditure Allowance        | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rqqh-kfrc d:2012-01-01T00:00:00.000Z t:fund_name="General Subfund" t:budget_control_level_bcrls_code=00100-CZ000 t:bcl_purpose="The purpose of the City Budget Office Budget Control Level is to develop and monitor the budget, carry out budget-related functions, and oversee fiscal policy and financial planning activities." t:department="City Budget Office" t:budget_control_level_bcl_name="City Budget Office" m:expenditure_allowance=4030780

series e:rqqh-kfrc d:2012-01-01T00:00:00.000Z t:fund_name="General Subfund" t:budget_control_level_bcrls_code=00100-V1CIV t:bcl_purpose="The purpose of the Civil Service Commissions Budget Control Level is to provide administrative support to the Public Safety Civil Service Commission (PSCSC) and the Civil Service Commission (CSC). The PSCSC provides sworn police and uniformed fire employees with a quasi-judicial process for hearings on appeals concerning disciplinary actions, examination and testing, and other related issues. The CSC directs the civil service system for all other employees of the City. It investigates allegations of political patronage so the City's hiring process conforms to the merit system set forth in the City Charter. These commissions will at times improve the City personnel system by developing legislation for the Mayor and City Council." t:department="Civil Service Commissions" t:budget_control_level_bcl_name="Civil Service Commissions" m:expenditure_allowance=344266

series e:rqqh-kfrc d:2012-01-01T00:00:00.000Z t:fund_name="General Subfund" t:budget_control_level_bcrls_code=00100-A1GM1 t:bcl_purpose="The purpose of the General Government Facilities - General Budget Control Level (BCL) is to execute capital projects in general government facilities. This BCL is funded by the General Fund dollars (Fund 00100)." t:department="Department of Finance & Administrative Services" t:budget_control_level_bcl_name="General Government Facilities - General (00100-CIP)" m:expenditure_allowance=419000
```

## Meta Commands

```ls
metric m:expenditure_allowance p:integer l:"2012 Expenditure Allowance" t:dataTypeName=money

entity e:rqqh-kfrc l:"2012 Adopted Budget - Expenditure Allowance by Budget Control Level (BCL)" t:attribution="City Budget Office" t:url=https://data.seattle.gov/api/views/rqqh-kfrc

property e:rqqh-kfrc t:meta.view v:id=rqqh-kfrc v:category=Finance v:attributionLink=http://www.seattle.gov/financedepartment/ v:averageRating=0 v:name="2012 Adopted Budget - Expenditure Allowance by Budget Control Level (BCL)" v:attribution="City Budget Office"

property e:rqqh-kfrc t:meta.view.owner v:id=tdaq-haqd v:screenName="Brandon Johns" v:displayName="Brandon Johns"

property e:rqqh-kfrc t:meta.view.tableauthor v:id=tdaq-haqd v:screenName="Brandon Johns" v:roleName=publisher v:displayName="Brandon Johns"
```

## Top Records

```ls
| fund_name       | department                                      | budget_control_level_bcrls_code | budget_control_level_bcl_name                       | bcl_purpose                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | expenditure_allowance | 
| =============== | =============================================== | =============================== | =================================================== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ===================== | 
| General Subfund | City Budget Office                              | 00100-CZ000                     | City Budget Office                                  | The purpose of the City Budget Office Budget Control Level is to develop and monitor the budget, carry out budget-related functions, and oversee fiscal policy and financial planning activities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 4030780               | 
| General Subfund | Civil Service Commissions                       | 00100-V1CIV                     | Civil Service Commissions                           | The purpose of the Civil Service Commissions Budget Control Level is to provide administrative support to the Public Safety Civil Service Commission (PSCSC) and the Civil Service Commission (CSC). The PSCSC provides sworn police and uniformed fire employees with a quasi-judicial process for hearings on appeals concerning disciplinary actions, examination and testing, and other related issues. The CSC directs the civil service system for all other employees of the City. It investigates allegations of political patronage so the City's hiring process conforms to the merit system set forth in the City Charter. These commissions will at times improve the City personnel system by developing legislation for the Mayor and City Council. | 344266                | 
| General Subfund | Department of Finance & Administrative Services | 00100-A1GM1                     | General Government Facilities - General (00100-CIP) | The purpose of the General Government Facilities - General Budget Control Level (BCL) is to execute capital projects in general government facilities. This BCL is funded by the General Fund dollars (Fund 00100).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 419000                | 
| General Subfund | Department of Neighborhoods                     | 00100-I3300                     | Community Building                                  | The purpose of the Community Building Budget Control Level is to deliver technical assistance, support services, and programs in neighborhoods to strengthen local communities, engage residents in neighborhood improvement, leverage resources, and complete neighborhood-initiated projects.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2392178               | 
| General Subfund | Department of Neighborhoods                     | 00100-I3100                     | Director's Office                                   | The purpose of the Director's Office Budget Control Level is to provide executive leadership, communications, and operational support for the entire department.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 1191992               | 
| General Subfund | Department of Neighborhoods                     | 00100-I3200                     | Internal Operations                                 | The purpose of the Internal Operations Budget Control Level is to provide financial, human resources, facilities, office management, and information technology services to the Department's employees to serve customers efficiently and effectively.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | 1503807               | 
| General Subfund | Department of Neighborhoods                     | 00100-I4100                     | Youth Violence Prevention                           | The purpose of the Youth Violence Prevention Budget Control Level is to reduce juvenile violent crimes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 3376079               | 
| General Subfund | Ethics and Elections Commission                 | 00100-V1T00                     | Ethics and Elections                                | The purpose of the Ethics and Elections Budget Control Level is threefold: 1) to audit, investigate, and conduct hearings regarding non-compliance with, or violations of, Commission-administered ordinances; 2) to advise all City officials and employees of their obligations under Commission-administered ordinances; and 3) to publish and broadly distribute information about the City's ethical standards, City election campaigns, campaign financial disclosure statements, and lobbyist disclosure statements.                                                                                                                                                                                                                                       | 759952                | 
| General Subfund | Executive                                       | 00100-X1R00                     | Civil Rights                                        | The purpose of the Civil Rights Budget Control Level is to work toward eliminating discrimination in employment, housing, public accommodations, contracting, and lending in Seattle through enforcement, and policy and outreach activities. The Office seeks to encourage and promote equal access and opportunity, diverse participation, and social and economic equity. In addition, the Office is responsible for directing the Race and Social Justice Initiative, leading other City departments to design and implement programs which eliminate institutionalized racism.                                                                                                                                                                               | 2566277               | 
| General Subfund | Executive                                       | 00100-VJ500                     | Indigent Defense Services                           | The purpose of the Indigent Defense Services Budget Control Level is to secure legal defense services, as required by state law, for indigent people facing criminal charges in Seattle Municipal Court.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 6169790               | 
```