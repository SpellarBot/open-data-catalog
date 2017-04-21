# Cook County Budget 1993-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-budget-1993-2011-3f224) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hd8u-wzhx) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hd8u-wzhx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hd8u-wzhx/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hd8u-wzhx |
| Name | Cook County Budget 1993-2011 |
| Attribution | Cook County, IL |
| Category | Economic Development |
| Created | 2011-08-18T16:02:28Z |
| Publication Date | 2014-10-27T16:06:35Z |

## Description

Every year your Cook County government budgets and spends more than $3 billion. Your County's budget impacts your life every day. All of its funding comes from you - your sales and property taxes, your purchase fees on gas and other goods. All of its spending exists to support you, too. County funding drives the forest preserve district, the jail, public hospitals and clinics, the Cook County courts and dozens of other civic institutions designed to make our region prosperous, efficient and fair.

Yet too many residents don't understand what Cook County government is or what it does. They keep asking, "where exactly does our money go?"

Commissioner John Fritchey created this budget transparency tool to answer that question, but it's only a first step. We need your help. What questions do you have about County spending? What do you want to know about the County budget that this visualization isn't explaining to you? What do you think of our spending? What can we do to make Cook County government better?

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | fund                   | Fund                   | text      | text        |
| Yes      | series tag     | department_id          | Department ID          | text      | number      |
| Yes      | series tag     | department             | Department             | text      | text        |
| Yes      | series tag     | short_title            | Short Title            | text      | text        |
| Yes      | series tag     | link_to_website        | Link to Website        | url       | url         |
| Yes      | series tag     | department_description | Department Description | text      | text        |
| Yes      | series tag     | control_officer        | Control Officer        | text      | text        |
| Yes      | numeric metric | appropriations_1993    | Appropriations 1993    | money     | money       |
| Yes      | numeric metric | appropriations_1994    | Appropriations 1994    | money     | money       |
| Yes      | numeric metric | appropriations_1995    | Appropriations 1995    | money     | money       |
| Yes      | numeric metric | appropriations_1996    | Appropriations 1996    | money     | money       |
| Yes      | numeric metric | appropriations_1997    | Appropriations 1997    | money     | money       |
| Yes      | numeric metric | appropriations_1998    | Appropriations 1998    | money     | money       |
| Yes      | numeric metric | appropriations_1999    | Appropriations 1999    | money     | money       |
| Yes      | numeric metric | appropriations_2000    | Appropriations 2000    | money     | money       |
| Yes      | numeric metric | appropriations_2001    | Appropriations 2001    | money     | money       |
| Yes      | numeric metric | appropriations_2002    | Appropriations 2002    | money     | money       |
| Yes      | numeric metric | appropriations_2003    | Appropriations 2003    | money     | money       |
| Yes      | numeric metric | appropriations_2004    | Appropriations 2004    | money     | money       |
| Yes      | numeric metric | appropriations_2005    | Appropriations 2005    | money     | money       |
| Yes      | numeric metric | appropriations_2006    | Appropriations 2006    | money     | money       |
| Yes      | numeric metric | appropriations_2007    | Appropriations 2007    | money     | money       |
| Yes      | numeric metric | appropriations_2008    | Appropriations 2008    | money     | money       |
| Yes      | numeric metric | appropriations_2009    | Appropriations 2009    | money     | money       |
| Yes      | numeric metric | appropriations_2010    | Appropriations 2010    | money     | money       |
| Yes      | numeric metric | appropriations_2011    | Appropriations 2011    | money     | money       |
| Yes      | numeric metric | expenditures_1993      | Expenditures 1993      | money     | money       |
| Yes      | numeric metric | expenditures_1994      | Expenditures 1994      | money     | money       |
| Yes      | numeric metric | expenditures_1995      | Expenditures 1995      | money     | money       |
| Yes      | numeric metric | expenditures_1996      | Expenditures 1996      | money     | money       |
| Yes      | numeric metric | expenditures_1997      | Expenditures 1997      | money     | money       |
| Yes      | numeric metric | expenditures_1998      | Expenditures 1998      | money     | money       |
| Yes      | numeric metric | expenditures_1999      | Expenditures 1999      | money     | money       |
| Yes      | numeric metric | expenditures_2000      | Expenditures 2000      | money     | money       |
| Yes      | numeric metric | expenditures_2001      | Expenditures 2001      | money     | money       |
| Yes      | numeric metric | expenditures_2002      | Expenditures 2002      | money     | money       |
| Yes      | numeric metric | expenditures_2003      | Expenditures 2003      | money     | money       |
| Yes      | numeric metric | expenditures_2004      | Expenditures 2004      | money     | money       |
| Yes      | numeric metric | expenditures_2005      | Expenditures 2005      | money     | money       |
| Yes      | numeric metric | expenditures_2006      | Expenditures 2006      | money     | money       |
| Yes      | numeric metric | expenditures_2007      | Expenditures 2007      | money     | money       |
| Yes      | numeric metric | expenditures_2008      | Expenditures 2008      | money     | money       |
| Yes      | numeric metric | expenditures_2009      | Expenditures 2009      | money     | money       |
| Yes      | numeric metric | expenditures_2010      | Expenditures 2010      | money     | money       |
| Yes      | numeric metric | expenditures_2011      | Expenditures 2011      | money     | money       |
```

## Time Field

```ls
Value = 1993
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hd8u-wzhx d:1993-01-01T00:00:00.000Z t:department_description="The Cook County Board of Ethics is responsible for enforcing the Cook County Ethics Ordinance. The Ethics Ordinance requires all Cook County officials and employees to abide by a Code of Conduct which sets forth general directives to ensure fair and honest government in Cook County. The Code of Conduct applies to officials, employees, person doing or seeking to do business with the County, persons regulated by the County, persons seeking official action by the County and lobbyists." t:short_title="Ethics Board" t:link_to_website=http://www.cookcountygov.com/portal/server.pt/community/board_of_ethics/293/ethics%2C_board_of t:department="Ethics Board" t:control_officer=President t:department_id=1 t:fund="Corporate Fund" m:appropriations_2002=0 m:appropriations_1999=0 m:expenditures_1996=186893 m:expenditures_1997=233306.45 m:appropriations_2007=0 m:expenditures_1998=159692 m:appropriations_2009=0 m:appropriations_2011=0 m:appropriations_2000=0 m:appropriations_2001=0 m:appropriations_2010=0 m:expenditures_1993=116071 m:appropriations_1993=195288 m:appropriations_1994=187912 m:expenditures_1995=98764 m:expenditures_1994=87540 m:appropriations_1997=232424 m:appropriations_1998=224416 m:appropriations_1995=252411 m:appropriations_1996=210462

series e:hd8u-wzhx d:1993-01-01T00:00:00.000Z t:department_description="This Department is the liaison to The Cook County Commission on Human Rights, which enforces the Cook County Human Rights Ordinance, and the Cook County Commission on Women's Issues which was  is composed of seventeen women of various racial, economic, ethic, and occupational backgrounds from across Cook County, to advise the President and members of the Cook County Board of Commissioners on the issues of concern to women and girls. The Commission develops policy and program recommendations, and collaborates with a wide range of governmental and private sector organizations on projects addressing a variety of issues." t:short_title="Human Rights" t:link_to_website=http://www.cookcountygov.com/portal/server.pt/community/human_rights%2C_commission_on/301/human_rights%2C_commission_on t:department="Department of Human Rights, Ethics, Women's Issues" t:control_officer=President t:department_id=2 t:fund="Corporate Fund" m:appropriations_1999=678529 m:expenditures_1996=337498 m:expenditures_1997=406772.36 m:expenditures_1998=505054.2 m:expenditures_1999=588255 m:expenditures_2005=714326 m:expenditures_2006=783986.48 m:expenditures_2003=747172.91 m:expenditures_2004=770139 m:appropriations_2011=753348 m:expenditures_2001=641714 m:expenditures_2002=835647 m:appropriations_2010=804818 m:expenditures_2000=587322.27 m:expenditures_2009=687120.43 m:expenditures_2008=616965.69 m:expenditures_2007=484061 m:expenditures_1993=259716 m:expenditures_1995=423800 m:expenditures_1994=421083 m:appropriations_2002=770125 m:appropriations_2003=804453 m:appropriations_2004=833877 m:appropriations_2005=716546 m:appropriations_2006=709034 m:appropriations_2007=643804 m:appropriations_2008=808600 m:appropriations_2009=727745 m:expenditures_2010=563218.97 m:appropriations_2000=768362 m:appropriations_2001=788693 m:appropriations_1993=368283 m:appropriations_1994=510251 m:appropriations_1997=524521 m:appropriations_1998=557221 m:appropriations_1995=504601 m:appropriations_1996=491713

series e:hd8u-wzhx d:1993-01-01T00:00:00.000Z t:department_description="The Department of Public Affairs and Communications operates under the Office of the President to centralize the efforts within the Offices under the President and increase public awareness and understanding of Cook County Government." t:short_title="Public Affairs" t:link_to_website=http://www.cookcountygov.com/portal/server.pt/community/public_affairs_and_communications/319/public_affairs_and_communications t:department="Department of Public Affairs and Communications" t:control_officer=President t:department_id=5 t:fund="Corporate Fund" m:appropriations_2003=831002 m:appropriations_2004=833497 m:appropriations_2005=723071 m:appropriations_2006=673295 m:appropriations_2007=533226 m:appropriations_2008=0 m:appropriations_2009=0 m:expenditures_2005=654504 m:expenditures_2006=680997.91 m:expenditures_2003=694922.82 m:expenditures_2004=723119 m:appropriations_2011=0 m:expenditures_2010=0 m:appropriations_2010=0 m:expenditures_2009=0 m:expenditures_2008=0 m:expenditures_2007=615808
```

## Meta Commands

```ls
metric m:appropriations_1993 p:integer l:"Appropriations 1993" t:dataTypeName=money

metric m:appropriations_1994 p:integer l:"Appropriations 1994" t:dataTypeName=money

metric m:appropriations_1995 p:integer l:"Appropriations 1995" t:dataTypeName=money

metric m:appropriations_1996 p:integer l:"Appropriations 1996" t:dataTypeName=money

metric m:appropriations_1997 p:integer l:"Appropriations 1997" t:dataTypeName=money

metric m:appropriations_1998 p:integer l:"Appropriations 1998" t:dataTypeName=money

metric m:appropriations_1999 p:integer l:"Appropriations 1999" t:dataTypeName=money

metric m:appropriations_2000 p:integer l:"Appropriations 2000" t:dataTypeName=money

metric m:appropriations_2001 p:integer l:"Appropriations 2001" t:dataTypeName=money

metric m:appropriations_2002 p:integer l:"Appropriations 2002" t:dataTypeName=money

metric m:appropriations_2003 p:integer l:"Appropriations 2003" t:dataTypeName=money

metric m:appropriations_2004 p:integer l:"Appropriations 2004" t:dataTypeName=money

metric m:appropriations_2005 p:double l:"Appropriations 2005" t:dataTypeName=money

metric m:appropriations_2006 p:integer l:"Appropriations 2006" t:dataTypeName=money

metric m:appropriations_2007 p:integer l:"Appropriations 2007" t:dataTypeName=money

metric m:appropriations_2008 p:integer l:"Appropriations 2008" t:dataTypeName=money

metric m:appropriations_2009 p:integer l:"Appropriations 2009" t:dataTypeName=money

metric m:appropriations_2010 p:integer l:"Appropriations 2010" t:dataTypeName=money

metric m:appropriations_2011 p:integer l:"Appropriations 2011" t:dataTypeName=money

metric m:expenditures_1993 p:integer l:"Expenditures 1993" t:dataTypeName=money

metric m:expenditures_1994 p:integer l:"Expenditures 1994" t:dataTypeName=money

metric m:expenditures_1995 p:integer l:"Expenditures 1995" t:dataTypeName=money

metric m:expenditures_1996 p:integer l:"Expenditures 1996" t:dataTypeName=money

metric m:expenditures_1997 p:double l:"Expenditures 1997" t:dataTypeName=money

metric m:expenditures_1998 p:double l:"Expenditures 1998" t:dataTypeName=money

metric m:expenditures_1999 p:integer l:"Expenditures 1999" t:dataTypeName=money

metric m:expenditures_2000 p:double l:"Expenditures 2000" t:dataTypeName=money

metric m:expenditures_2001 p:integer l:"Expenditures 2001" t:dataTypeName=money

metric m:expenditures_2002 p:integer l:"Expenditures 2002" t:dataTypeName=money

metric m:expenditures_2003 p:double l:"Expenditures 2003" t:dataTypeName=money

metric m:expenditures_2004 p:integer l:"Expenditures 2004" t:dataTypeName=money

metric m:expenditures_2005 p:integer l:"Expenditures 2005" t:dataTypeName=money

metric m:expenditures_2006 p:double l:"Expenditures 2006" t:dataTypeName=money

metric m:expenditures_2007 p:integer l:"Expenditures 2007" t:dataTypeName=money

metric m:expenditures_2008 p:double l:"Expenditures 2008" t:dataTypeName=money

metric m:expenditures_2009 p:double l:"Expenditures 2009" t:dataTypeName=money

metric m:expenditures_2010 p:integer l:"Expenditures 2010" t:dataTypeName=money

metric m:expenditures_2011 p:double l:"Expenditures 2011" t:dataTypeName=money

entity e:hd8u-wzhx l:"Cook County Budget 1993-2011" t:attribution="Cook County, IL" t:url=https://datacatalog.cookcountyil.gov/api/views/hd8u-wzhx

property e:hd8u-wzhx t:meta.view v:id=hd8u-wzhx v:category="Economic Development" v:attributionLink=http://data.cookcountyil.gov v:averageRating=0 v:name="Cook County Budget 1993-2011" v:attribution="Cook County, IL"

property e:hd8u-wzhx t:meta.view.owner v:id=83hr-92mi v:profileImageUrlMedium=/api/users/83hr-92mi/profile_images/THUMB v:profileImageUrlLarge=/api/users/83hr-92mi/profile_images/LARGE v:screenName="Kevin Merritt" v:profileImageUrlSmall=/api/users/83hr-92mi/profile_images/TINY v:lastNotificationSeenAt=1490391243 v:displayName="Kevin Merritt"

property e:hd8u-wzhx t:meta.view.tableauthor v:id=83hr-92mi v:profileImageUrlMedium=/api/users/83hr-92mi/profile_images/THUMB v:profileImageUrlLarge=/api/users/83hr-92mi/profile_images/LARGE v:screenName="Kevin Merritt" v:profileImageUrlSmall=/api/users/83hr-92mi/profile_images/TINY v:lastNotificationSeenAt=1490391243 v:displayName="Kevin Merritt"
```

## Top Records

```ls
| fund           | department_id | department                                         | short_title            | link_to_website                                                                                                                                                            | department_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | control_officer      | appropriations_1993 | appropriations_1994 | appropriations_1995 | appropriations_1996 | appropriations_1997 | appropriations_1998 | appropriations_1999 | appropriations_2000 | appropriations_2001 | appropriations_2002 | appropriations_2003 | appropriations_2004 | appropriations_2005 | appropriations_2006 | appropriations_2007 | appropriations_2008 | appropriations_2009 | appropriations_2010 | appropriations_2011 | expenditures_1993 | expenditures_1994 | expenditures_1995 | expenditures_1996 | expenditures_1997 | expenditures_1998 | expenditures_1999 | expenditures_2000 | expenditures_2001 | expenditures_2002 | expenditures_2003 | expenditures_2004 | expenditures_2005 | expenditures_2006 | expenditures_2007 | expenditures_2008 | expenditures_2009 | expenditures_2010 | expenditures_2011 | 
| ============== | ============= | ================================================== | ====================== | ========================================================================================================================================================================== | =============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ==================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | =================== | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | ================= | 
| Corporate Fund | 1             | Ethics Board                                       | Ethics Board           | [http://www.cookcountygov.com/portal/server.pt/community/board_of_ethics/293/ethics%2C_board_of, null]                                                                     | The Cook County Board of Ethics is responsible for enforcing the Cook County Ethics Ordinance. The Ethics Ordinance requires all Cook County officials and employees to abide by a Code of Conduct which sets forth general directives to ensure fair and honest government in Cook County. The Code of Conduct applies to officials, employees, person doing or seeking to do business with the County, persons regulated by the County, persons seeking official action by the County and lobbyists.                                                                                                                                          | President            | 195288              | 187912              | 252411              | 210462              | 232424              | 224416              | 0                   | 0                   | 0                   | 0                   |                     |                     |                     |                     | 0                   |                     | 0                   | 0                   | 0                   | 116071            | 87540             | 98764             | 186893            | 233306.45         | 159692            |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   | 
| Corporate Fund | 2             | Department of Human Rights, Ethics, Women's Issues | Human Rights           | [http://www.cookcountygov.com/portal/server.pt/community/human_rights%2C_commission_on/301/human_rights%2C_commission_on, null]                                            | This Department is the liaison to The Cook County Commission on Human Rights, which enforces the Cook County Human Rights Ordinance, and the Cook County Commission on Women's Issues which was is composed of seventeen women of various racial, economic, ethic, and occupational backgrounds from across Cook County, to advise the President and members of the Cook County Board of Commissioners on the issues of concern to women and girls. The Commission develops policy and program recommendations, and collaborates with a wide range of governmental and private sector organizations on projects addressing a variety of issues. | President            | 368283              | 510251              | 504601              | 491713              | 524521              | 557221              | 678529              | 768362              | 788693              | 770125              | 804453              | 833877              | 716546              | 709034              | 643804              | 808600              | 727745              | 804818              | 753348              | 259716            | 421083            | 423800            | 337498            | 406772.36         | 505054.20         | 588255            | 587322.27         | 641714            | 835647            | 747172.91         | 770139            | 714326            | 783986.48         | 484061            | 616965.69         | 687120.43         | 563218.97         |                   | 
| Corporate Fund | 5             | Department of Public Affairs and Communications    | Public Affairs         | [http://www.cookcountygov.com/portal/server.pt/community/public_affairs_and_communications/319/public_affairs_and_communications, null]                                    | The Department of Public Affairs and Communications operates under the Office of the President to centralize the efforts within the Offices under the President and increase public awareness and understanding of Cook County Government.                                                                                                                                                                                                                                                                                                                                                                                                      | President            |                     |                     |                     |                     |                     |                     |                     |                     |                     |                     | 831002              | 833497              | 723071              | 673295              | 533226              | 0                   | 0                   | 0                   | 0                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   | 694922.82         | 723119            | 654504            | 680997.91         | 615808            | 0                 | 0                 | 0                 |                   | 
| Corporate Fund | 7             | Revenue                                            | Revenue                | [http://www.cookcountygov.com/portal/server.pt/community/revenue%2C_department_of/313/revenue%2C_department_of, null]                                                      | The Department collects Cook County home rule taxes and other fees, and administers and enforces such collections. The Department audits and maintains delinquent property tax records. The Department of Revenue also researches and proposes new revenue sources for the County.                                                                                                                                                                                                                                                                                                                                                              | President            | 2258336             | 2138204             | 2012415             | 2060162             | 2405966             | 2449224             | 2463989             | 2731624             | 2974009             | 2883369             | 2922275             | 3170594             | 2661480             | 2709209             | 2123407             | 2274300             | 2450977             | 2572615             | 2036609             | 1708575           | 2022538           | 1827351           | 1917663           | 2246388.11        | 2197086.96        | 2124099           | 2437319.91        | 2603077           | 2590404           | 2584489.92        | 2477643           | 2304837           | 2359007.99        | 2087834           | 2276639.81        | 2380314.83        | 2417950.01        |                   | 
| Corporate Fund | 8             | Risk Management                                    | Risk Management        | [http://www.cookcountyrisk.com/index.php, null]                                                                                                                            | The Department of Risk Management is responsible for the administration of employee benefit plans, workers compensation claims, general liability claims and safety programs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | President            | 1960585             | 1993281             | 2092454             | 1835457             | 1788426             | 1814589             | 1847135             | 1983398             | 1967439             | 1905503             | 2036180             | 2143608             | 1821935             | 1780613             | 1292982             | 1592600             | 1636099             | 1644544             | 1450076             | 1216284           | 1567668           | 1654878           | 1359726           | 1491623.34        | 1453620.99        | 1470371           | 1728340.43        | 1729683           | 1805829           | 1898554.88        | 2048690           | 1790130           | 1691459.61        | 1326704           | 1462185.18        | 1664197.57        | 1620216.48        |                   | 
| Corporate Fund | 9             | Technology Policy & Planning                       | Technology             | [http://www.cookcountygov.com/portal/server.pt/community/technology%2C_bureau_of/287/technology_policy_and_planning, null]                                                 | The Department of Technology Policy and Planning helps improve the effectiveness and efficiency of Cook County government by providing technology leadership, oversight, products and services. The Department partners with Cook County departments and agencies in the design, development, deployment and support of mainframe, midrange, distributed and web-based applications.                                                                                                                                                                                                                                                            | President            |                     |                     |                     |                     | 271644              | 303530              | 317942              | 349849              | 389807              | 378553              | 396462              | 421153              | 383917              | 352463              | 377130              | 3276000             | 6266223             | 4941152             | 6177593             |                   |                   |                   |                   | 146987.47         | 285009.51         | 283095            | 236072.65         | 329625            | 368172            | 367874.50         | 407071            | 299556            | 263690.74         | 326345            | 1790546.88        | 5868487.78        | 2483273.44        |                   | 
| Corporate Fund | 10            | Office of the President                            | President              | [http://blog.cookcountygov.com/, null]                                                                                                                                     | The President is the chief executive officer of the the County and presides over the meetings of the County Board and directly supervises departments which provide a variety of direct and support services. The President is elected to a four-year term by the voters of the entire County.                                                                                                                                                                                                                                                                                                                                                  | President            | 979184              | 1168874             | 1168874             | 1168874             | 1168874             | 1230691             | 1530296             | 1728228             | 1790138             | 1784402             | 1758956             | 1734994             | 1519092             | 1684806             | 1365474             | 2641800             | 2475702             | 2362490             | 1914072             | 823371            | 787146            | 1168874           | 1023082           | 1168874           | 1174404.78        | 1405433           | 1504066.55        | 1440079           | 1317798           | 1512400.50        | 1451764           | 1553570           | 1539738.41        | 1434756           | 2664153.95        | 2643108.03        | 2597108.12        |                   | 
| Corporate Fund | 11            | Office of the Chief Administrative Officer         | Administrative Officer | [http://www.cookcountygov.com/portal/server.pt/community/administration%2C_bureau_of/238, null]                                                                            | The Chief Administrative Officer coordinates the activities of these Cook County departments and functions: Adoption & Child Custody Advocacy, Animal & Rabies Control, Child Support Compliance Enforcement, Environmental Control, Highway, Industrial Engineering, Law Library, Motor Fuel Tax ? Illinois First, Medical Examiner, Print Shop, Salvage Activity, Veterans Assistance Commission, Zoning Board of Appeals                                                                                                                                                                                                                     | President            | 1440007             | 1321970             | 1308428             | 1227930             | 1271362             | 1409451             | 1449996             | 1653655             | 1748375             | 1661581             | 1735544             | 1709668             | 1531089             | 1555488             | 1469182             | 2259700             | 2364337             | 2303804             | 1819286             | 1062860           | 998832            | 1160589           | 1153511           | 1206079.52        | 1306087.97        | 1441259           | 1511881.96        | 1708460           | 1660098           | 1513738.59        | 1518330           | 1429856           | 1468103.73        | 1410064           | 1421098.82        | 2225265.20        | 2066600.55        |                   | 
| Corporate Fund | 12            | Department of Management Information Systems       | Info Systems           | [null, null]                                                                                                                                                               | This Department merged for FY2011 into Department of Technology Policy and Planning (009)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | President            | 10907273            | 12398363            | 9165044             | 9597961             | 9321487             | 9087553             | 8432887             | 9213839             | 10111088            | 9926803             | 9845517             | 9849869             | 8401304             | 7387157             | 5980984             | 6280700             | 6007516             | 6266489             | 0                   | 10234913          | 11862906          | 7970778           | 8462573           | 8176040.15        | 8329145.93        | 7606892           | 7895023.28        | 9555499           | 8685321           | 8979783.20        | 9089280           | 6614564           | 6982353.19        | 6071658           | 5990818.92        | 6505499.41        | 5764261.95        |                   | 
| Corporate Fund | 83            | Third District -Office of the County Commissioner  | District 3             | [http://www.cookcountygov.com/portal/server.pt/gateway/PTARGS_0_0_336_226_0_43/http%3B/www.cookcountygov.com/ccWeb.Leadership/LeadershipProfile.aspx?commiss_id=110, null] | County Commissioners are elected officials who oversee county activities and work to ensure that citizens concerns are met, federal and state requirements are fulfilled and county operations run smoothly                                                                                                                                                                                                                                                                                                                                                                                                                                     | County Commissioners |                     |                     |                     |                     |                     |                     |                     |                     |                     |                     |                     |                     |                     |                     |                     | 391120              | 364831              | 348624              | 360000              |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   |                   | 270749            | 292463.85         | 288759.09         |                   | 
```