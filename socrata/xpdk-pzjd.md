# 2015 Project Appendix

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-project-appendix) |
| Metadata | [Link](https://data.sfgov.org/api/views/xpdk-pzjd) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/xpdk-pzjd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/xpdk-pzjd/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | xpdk-pzjd |
| Name | 2015 Project Appendix |
| Category | City Infrastructure |
| Created | 2015-08-10T18:37:24Z |
| Publication Date | 2015-08-10T18:42:01Z |

## Description

This is an appendix for future general fund capital projects as they have been entered by departments and collected by the capital planning program

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | projectid         | ProjectID         | text      | number      |
| Yes      | series tag     | projectname       | ProjectName       | text      | text        |
| Yes      | series tag     | short_description | Short description | text      | text        |
| Yes      | series tag     | plan_status       | Plan status       | text      | text        |
| Yes      | series tag     | departmentname    | DepartmentName    | text      | text        |
| Yes      | series tag     | fundingprinciple  | FundingPrinciple  | text      | text        |
| Yes      | numeric metric | 2016              | 2016              | money     | money       |
| Yes      | numeric metric | 2017              | 2017              | money     | money       |
| Yes      | numeric metric | 2018              | 2018              | money     | money       |
| Yes      | numeric metric | 2019              | 2019              | money     | money       |
| Yes      | numeric metric | 2020              | 2020              | money     | money       |
| Yes      | numeric metric | 2021              | 2021              | money     | money       |
| Yes      | numeric metric | 2022              | 2022              | money     | money       |
| Yes      | numeric metric | 2023              | 2023              | money     | money       |
| Yes      | numeric metric | 2024              | 2024              | money     | money       |
| Yes      | numeric metric | 2025              | 2025              | money     | money       |
| Yes      | numeric metric | fund_fy6_10       | Fund FY6-10       | money     | money       |
| Yes      | numeric metric | futurefund        | FutureFund        | money     | money       |
| Yes      | numeric metric | fundtotal         | FundTotal         | money     | money       |
| Yes      | numeric metric | plantotal         | PlanTotal         | money     | money       |
| Yes      | series tag     | fundname          | FundName          | text      | text        |
| Yes      | series tag     | groupname         | GroupName         | text      | text        |
| Yes      | series tag     | project_image     | Project Image     | photo     | photo       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xpdk-pzjd d:2015-01-01T00:00:00.000Z t:plan_status=Deferred t:short_description="This project will rehabilitate and reconfigure the right-of-way in the in the Bayview and Hunter?s Point Shipyard development areas to increase roadway capacities and increase safety and accessibility." t:projectid=100970 t:groupname="Local - General Fund Sources" t:projectname="Bayview Transportation Improvements" t:departmentname="Infrastructure and Streets" t:fundingprinciple="E - Enhancement (Uncategorized)" t:fundname="General Fund" m:2017=6939437 m:2018=6657286 m:fund_fy6_10=6392274 m:2019=7556919 m:plantotal=36962545 m:futurefund=0 m:fundtotal=36962545 m:2016=951055 m:2021=6392274 m:2025=0 m:2020=8465574 m:2024=0 m:2023=0 m:2022=0

series e:xpdk-pzjd d:2015-01-01T00:00:00.000Z t:plan_status=Emerging t:short_description="The current Police Academy does not adequately provide the required floor space to accommodate training programs for the  2100 police officers in the Department. The Academy is also considered a State Regional Training Academy where other departments send officers for in service training. It is probable that the San Francisco Polce Academy will lose its Regional certification because of its lack of space to acommodate programs and recruit classes. The preliminary project budget is based on an expansion need of an area of approximatley 16,260 square feet. The proposed preliminary budget includes costs for the design, construction, related project control cost. If you have any questions regarding the proposed schematic plans, program, and budget, call Edmund Shum at 415-557-4678, Bureau of Architecture." t:projectid=105530 t:groupname="Local - General Fund Sources" t:projectname="Expansion, Renovation- Relocation  of the Police Training Academy" t:departmentname="Public Safety" t:fundingprinciple="E - Enhancement (Uncategorized)" t:fundname="General Fund" m:2017=10000000 m:2018=5000000 m:fund_fy6_10=200000000 m:2019=35000000 m:plantotal=287000000 m:futurefund=0 m:fundtotal=287000000 m:2016=2000000 m:2021=35000000 m:2025=30000000 m:2020=35000000 m:2024=50000000 m:2023=50000000 m:2022=35000000

series e:xpdk-pzjd d:2015-01-01T00:00:00.000Z t:plan_status=Planned t:short_description="The Auxiliary Water Supply System (AWSS) is the City?s high-pressure emergency fire protection system. Completed in 1913 in response to the fire following the 1906 earthquake, the AWSS consists of 135 miles of high-pressure distribution lines, high pressure hydrants, suction connections, water storage tanks, underground cisterns, reservoirs, and pump stations. The system serves as an independent and redundant water supply that can be used to fight fires. Investments are needed to rehabilitate the system, seismically brace weak pipes and cisterns, and make other improvements to ensure its continued operation. The AWSS currently lacks a system wide capital assessment to inform the final scope of this project and the potential need to expand the system to other portions of the city." t:projectid=105580 t:groupname="Local - General Obligation Bonds" t:projectname="Auxiliary Water Supply System Improvements" t:departmentname="Public Safety" t:fundingprinciple="E - Enhancement (Uncategorized)" t:fundname="Earthquake Safety & Emergency Response Bond #2" m:2017=0 m:2018=0 m:fund_fy6_10=0 m:2019=0 m:plantotal=65000000 m:futurefund=0 m:fundtotal=65000000 m:2016=65000000 m:2021=0 m:2025=0 m:2020=0 m:2024=0 m:2023=0 m:2022=0
```

## Meta Commands

```ls
metric m:2016 p:double l:2016 t:dataTypeName=money

metric m:2017 p:double l:2017 t:dataTypeName=money

metric m:2018 p:double l:2018 t:dataTypeName=money

metric m:2019 p:double l:2019 t:dataTypeName=money

metric m:2020 p:double l:2020 t:dataTypeName=money

metric m:2021 p:double l:2021 t:dataTypeName=money

metric m:2022 p:double l:2022 t:dataTypeName=money

metric m:2023 p:double l:2023 t:dataTypeName=money

metric m:2024 p:double l:2024 t:dataTypeName=money

metric m:2025 p:double l:2025 t:dataTypeName=money

metric m:fund_fy6_10 p:double l:"Fund FY6-10" t:dataTypeName=money

metric m:futurefund p:double l:FutureFund t:dataTypeName=money

metric m:fundtotal p:double l:FundTotal t:dataTypeName=money

metric m:plantotal p:double l:PlanTotal t:dataTypeName=money

entity e:xpdk-pzjd l:"2015 Project Appendix" t:url=https://data.sfgov.org/api/views/xpdk-pzjd

property e:xpdk-pzjd t:meta.view v:id=xpdk-pzjd v:category="City Infrastructure" v:averageRating=0 v:name="2015 Project Appendix"

property e:xpdk-pzjd t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:xpdk-pzjd t:meta.view.owner v:id=a87g-a3ri v:screenName="Capital Planning Program" v:displayName="Capital Planning Program"

property e:xpdk-pzjd t:meta.view.tableauthor v:id=a87g-a3ri v:screenName="Capital Planning Program" v:roleName=editor v:displayName="Capital Planning Program"
```

## Top Records

```ls
| projectid | projectname                                                      | short_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | plan_status | departmentname             | fundingprinciple                | 2016        | 2017        | 2018        | 2019        | 2020        | 2021         | 2022        | 2023        | 2024        | 2025        | fund_fy6_10  | futurefund | fundtotal    | plantotal    | fundname                                       | groupname                                         | project_image | 
| ========= | ================================================================ | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =========== | ========================== | =============================== | =========== | =========== | =========== | =========== | =========== | ============ | =========== | =========== | =========== | =========== | ============ | ========== | ============ | ============ | ============================================== | ================================================= | ============= | 
| 100970    | Bayview Transportation Improvements                              | This project will rehabilitate and reconfigure the right-of-way in the in the Bayview and Hunter?s Point Shipyard development areas to increase roadway capacities and increase safety and accessibility.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Deferred    | Infrastructure and Streets | E - Enhancement (Uncategorized) | 951055.00   | 6939437.00  | 6657286.00  | 7556919.00  | 8465574.00  | 6392274.00   | 0.00        | 0.00        | 0.00        | 0.00        | 6392274.00   | 0.00       | 36962545.00  | 36962545.00  | General Fund                                   | Local - General Fund Sources                      |               | 
| 105530    | Expansion, Renovation- Relocation of the Police Training Academy | The current Police Academy does not adequately provide the required floor space to accommodate training programs for the 2100 police officers in the Department. The Academy is also considered a State Regional Training Academy where other departments send officers for in service training. It is probable that the San Francisco Polce Academy will lose its Regional certification because of its lack of space to acommodate programs and recruit classes. The preliminary project budget is based on an expansion need of an area of approximatley 16,260 square feet. The proposed preliminary budget includes costs for the design, construction, related project control cost. If you have any questions regarding the proposed schematic plans, program, and budget, call Edmund Shum at 415-557-4678, Bureau of Architecture. | Emerging    | Public Safety              | E - Enhancement (Uncategorized) | 2000000.00  | 10000000.00 | 5000000.00  | 35000000.00 | 35000000.00 | 35000000.00  | 35000000.00 | 50000000.00 | 50000000.00 | 30000000.00 | 200000000.00 | 0.00       | 287000000.00 | 287000000.00 | General Fund                                   | Local - General Fund Sources                      |               | 
| 105580    | Auxiliary Water Supply System Improvements                       | The Auxiliary Water Supply System (AWSS) is the City?s high-pressure emergency fire protection system. Completed in 1913 in response to the fire following the 1906 earthquake, the AWSS consists of 135 miles of high-pressure distribution lines, high pressure hydrants, suction connections, water storage tanks, underground cisterns, reservoirs, and pump stations. The system serves as an independent and redundant water supply that can be used to fight fires. Investments are needed to rehabilitate the system, seismically brace weak pipes and cisterns, and make other improvements to ensure its continued operation. The AWSS currently lacks a system wide capital assessment to inform the final scope of this project and the potential need to expand the system to other portions of the city.                      | Planned     | Public Safety              | E - Enhancement (Uncategorized) | 65000000.00 | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 0.00       | 65000000.00  | 65000000.00  | Earthquake Safety & Emergency Response Bond #2 | Local - General Obligation Bonds                  |               | 
| 105580    | Auxiliary Water Supply System Improvements                       | The Auxiliary Water Supply System (AWSS) is the City?s high-pressure emergency fire protection system. Completed in 1913 in response to the fire following the 1906 earthquake, the AWSS consists of 135 miles of high-pressure distribution lines, high pressure hydrants, suction connections, water storage tanks, underground cisterns, reservoirs, and pump stations. The system serves as an independent and redundant water supply that can be used to fight fires. Investments are needed to rehabilitate the system, seismically brace weak pipes and cisterns, and make other improvements to ensure its continued operation. The AWSS currently lacks a system wide capital assessment to inform the final scope of this project and the potential need to expand the system to other portions of the city.                      | Planned     | Public Safety              | E - Enhancement (Uncategorized) | 0.00        | 0.00        | 0.00        | 0.00        | 0.00        | 110000000.00 | 0.00        | 0.00        | 0.00        | 0.00        | 110000000.00 | 0.00       | 110000000.00 | 110000000.00 | Earthquake Safety & Emergency Response Bond #3 | Local - General Obligation Bonds                  |               | 
| 105680    | Street Resurfacing and Reconstruction                            | Total need to maintain an average Pavement Condition Index Score (PCI) of 70, or "good," on accepted city streets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Planned     | Infrastructure and Streets | S - Street Resurfacing          | 47000000.00 | 51000000.00 | 54000000.00 | 57000000.00 | 61000000.00 | 65000000.00  | 68000000.00 | 73000000.00 | 77000000.00 | 82000000.00 | 365000000.00 | 0.00       | 635000000.00 | 635000000.00 | General Fund                                   | Local - General Fund Sources                      |               | 
| 105680    | Street Resurfacing and Reconstruction                            | Total need to maintain an average Pavement Condition Index Score (PCI) of 70, or "good," on accepted city streets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Planned     | Infrastructure and Streets | S - Street Resurfacing          | 1141770.00  | 1207332.00  | 1207332.00  | 1207332.00  | 1207332.00  | 1207332.00   | 1207332.00  | 1207332.00  | 1207332.00  | 1207332.00  | 6036660.00   | 0.00       | 12007758.00  | 12007758.00  | Federal                                        | Federal                                           |               | 
| 105680    | Street Resurfacing and Reconstruction                            | Total need to maintain an average Pavement Condition Index Score (PCI) of 70, or "good," on accepted city streets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Planned     | Infrastructure and Streets | S - Street Resurfacing          | 14675382.00 | 14968890.00 | 15268268.00 | 15573633.00 | 15885106.00 | 16202808.00  | 16526864.00 | 16857401.00 | 17194549.00 | 17538440.00 | 84320062.00  | 0.00       | 160691341.00 | 160691341.00 | State                                          | State                                             |               | 
| 105680    | Street Resurfacing and Reconstruction                            | Total need to maintain an average Pavement Condition Index Score (PCI) of 70, or "good," on accepted city streets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Planned     | Infrastructure and Streets | S - Street Resurfacing          | 5365230.00  | 3907668.00  | 4519668.00  | 4634668.00  | 4505003.00  | 4640153.00   | 4779358.00  | 4922738.00  | 5070421.00  | 5222533.00  | 24635203.00  | 0.00       | 47567440.00  | 47567440.00  | Prop K Funding                                 | Local - Other (including TIF, Mello Roos, Prop K) |               | 
| 105680    | Street Resurfacing and Reconstruction                            | Total need to maintain an average Pavement Condition Index Score (PCI) of 70, or "good," on accepted city streets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Planned     | Infrastructure and Streets | S - Street Resurfacing          | 0.00        | 2210000.00  | 2004000.00  | 2004000.00  | 2004000.00  | 2004000.00   | 2004000.00  | 2004000.00  | 2004000.00  | 2004000.00  | 10020000.00  | 0.00       | 18242000.00  | 18242000.00  | Other Local Sources                            | Local - General Fund Sources                      |               | 
| 105690    | Street Structure Repair                                          | For the maintenance and renewal of 357 street structures including retaining walls, stairs, bridges, viaducts, tunnels, underpasses and overpasses, plus numerous guardrails. throughout the City.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Planned     | Infrastructure and Streets | R - Streets and ROW Renewal     | 35412000.00 | 0.00        | 2036190.00  | 17706000.00 | 0.00        | 0.00         | 0.00        | 0.00        | 0.00        | 0.00        | 0.00         | 0.00       | 55154190.00  | 55154190.00  | Federal                                        | Federal                                           |               | 
```