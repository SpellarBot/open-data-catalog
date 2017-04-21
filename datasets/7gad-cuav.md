# Community Investment Tax Credits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-investment-tax-credits) |
| Metadata | [Link](https://data.maryland.gov/api/views/7gad-cuav) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/7gad-cuav/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/7gad-cuav/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 7gad-cuav |
| Name | Community Investment Tax Credits |
| Attribution | Maryland Department of Housing and Community Development |
| Category | Housing |
| Tags | dhcd, citc, maryland, community investment tax credits |
| Created | 2015-05-04T15:57:41Z |
| Publication Date | 2016-12-02T20:44:23Z |

## Description

COMMUNITY INVESTMENT TAX CREDITS (CITC) support 501(c)(3) nonprofit organizations by awarding allocations of State tax credits for use as incentives to attract contributions from individuals and businesses to benefit local projects and services.
This data is to show possible donors what nonprofit organizations they can donate to and see the tax credits still available from those nonprofits.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | projid        | ProjID        | text      | text        |
| Yes      | series tag     | projnum       | ProjNum       | text      | text        |
| No       |                | fy            | FY            | number    | number      |
| Yes      | series tag     | awardee       | Awardee       | text      | text        |
| Yes      | series tag     | projname      | ProjName      | text      | text        |
| Yes      | series tag     | county        | County        | text      | text        |
| Yes      | series tag     | region        | Region        | text      | text        |
| Yes      | series tag     | applicanttype | ApplicantType | text      | text        |
| Yes      | series tag     | projtype      | ProjType      | text      | text        |
| Yes      | series tag     | projectdesc   | ProjectDesc   | text      | text        |
| Yes      | numeric metric | awardamount   | AwardAmount   | number    | number      |
| Yes      | numeric metric | taxcredited   | TaxCredited   | number    | number      |
| Yes      | numeric metric | taxcredbal    | TaxCredBal    | number    | number      |
| Yes      | series tag     | donationlink  | DonationLink  | text      | text        |
| Yes      | series tag     | website       | WebSite       | text      | text        |
| Yes      | numeric metric | y_coord       | Y_Coord       | number    | number      |
| Yes      | numeric metric | x_coord       | X_Coord       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:7gad-cuav d:2017-03-22T19:27:18.000Z t:region="Baltimore City" t:projectdesc="The Breakfast Club supports daily breakfasts for the homeless and very poor through community partnerships with businesses, churches and individuals who give $500 or more, and who volunteer to help prepare and serve the meals." t:county="Baltimore City" t:website=www.mannahouseinc.org t:applicanttype="Services for At-Risk Populations" t:awardee="Manna House, Inc." t:projtype=Operating t:donationlink=http://mannahouseinc.org/donate/ t:projnum=CITC-2016-MannaHouse-00055 t:projid=38152 t:projname="Manna House Breakfast Club" m:y_coord=39.31794 m:taxcredbal=4750 m:awardamount=10000 m:taxcredited=5250 m:x_coord=-76.61

series e:7gad-cuav d:2017-04-10T15:24:55.000Z t:region="Baltimore City" t:projectdesc="Live Baltimore?s creative campaign highlighting real people and the reasons they love and live in Baltimore. The campaign aims to affect Baltimore city living perceptions locally and nationally and help us realize net population growth." t:county="Baltimore City" t:website=www.livebaltimore.com t:applicanttype="Housing and Community Development" t:awardee="Live Baltimore Home Center, Inc." t:projtype=Operating t:donationlink=www.livebaltimore.com/donate t:projnum=CITC-2016-LBHC-00130 t:projid=38529 t:projname="BaltiMORE Creative Messaging" m:y_coord=39.29388 m:taxcredbal=8250 m:awardamount=10000 m:taxcredited=1750 m:x_coord=-76.6153

series e:7gad-cuav d:2017-04-10T15:24:55.000Z t:region="Baltimore City" t:projectdesc="A study to understand and promote the return on all investments to community development in Maryland." t:county="Baltimore City" t:website=www.communitydevelopmentmd.org t:applicanttype="Housing and Community Development" t:awardee="Community Development Network of Maryland, Inc" t:projtype=Operating t:donationlink=http://communitydevelopmentmd.org/join-us/ t:projnum=CITC-2016-CommDevNet-00091 t:projid=38366 t:projname="Community Development Return on Investment Study" m:y_coord=39.29184 m:taxcredbal=14000 m:awardamount=15000 m:taxcredited=1000 m:x_coord=-76.6107
```

## Meta Commands

```ls
metric m:awardamount p:integer l:AwardAmount t:dataTypeName=number

metric m:taxcredited p:float l:TaxCredited t:dataTypeName=number

metric m:taxcredbal p:double l:TaxCredBal t:dataTypeName=number

metric m:y_coord p:float l:Y_Coord t:dataTypeName=number

metric m:x_coord p:float l:X_Coord t:dataTypeName=number

entity e:7gad-cuav l:"Community Investment Tax Credits" t:attribution="Maryland Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/7gad-cuav

property e:7gad-cuav t:meta.view v:id=7gad-cuav v:category=Housing v:attributionLink=http://www.neighborhoodrevitalization.org/programs/citc/citc.aspx v:averageRating=0 v:name="Community Investment Tax Credits" v:attribution="Maryland Department of Housing and Community Development"

property e:7gad-cuav t:meta.view.owner v:id=e2fa-sxew v:profileImageUrlMedium=/api/users/e2fa-sxew/profile_images/THUMB v:profileImageUrlLarge=/api/users/e2fa-sxew/profile_images/LARGE v:screenName="Brad Wolters" v:profileImageUrlSmall=/api/users/e2fa-sxew/profile_images/TINY v:displayName="Brad Wolters"

property e:7gad-cuav t:meta.view.tableauthor v:id=e2fa-sxew v:profileImageUrlMedium=/api/users/e2fa-sxew/profile_images/THUMB v:profileImageUrlLarge=/api/users/e2fa-sxew/profile_images/LARGE v:screenName="Brad Wolters" v:profileImageUrlSmall=/api/users/e2fa-sxew/profile_images/TINY v:roleName=editor v:displayName="Brad Wolters"
```

## Top Records

```ls
| :updated_at | projid | projnum                     | fy   | awardee                                                      | projname                                                                    | county         | region              | applicanttype                                  | projtype  | projectdesc                                                                                                                                                                                                                                               | awardamount | taxcredited | taxcredbal | donationlink                                         | website                        | y_coord            | x_coord             | 
| =========== | ====== | =========================== | ==== | ============================================================ | =========================================================================== | ============== | =================== | ============================================== | ========= | ========================================================================================================================================================================================================================================================= | =========== | =========== | ========== | ==================================================== | ============================== | ================== | =================== | 
| 1490210838  | 38152  | CITC-2016-MannaHouse-00055  | 2016 | Manna House, Inc.                                            | Manna House Breakfast Club                                                  | Baltimore City | Baltimore City      | Services for At-Risk Populations               | Operating | The Breakfast Club supports daily breakfasts for the homeless and very poor through community partnerships with businesses, churches and individuals who give $500 or more, and who volunteer to help prepare and serve the meals.                        | 10000       | 5250        | 4750       | http://mannahouseinc.org/donate/                     | www.mannahouseinc.org          | 39.31794           | -76.61              | 
| 1491837895  | 38529  | CITC-2016-LBHC-00130        | 2016 | Live Baltimore Home Center, Inc.                             | BaltiMORE Creative Messaging                                                | Baltimore City | Baltimore City      | Housing and Community Development              | Operating | Live Baltimore?s creative campaign highlighting real people and the reasons they love and live in Baltimore. The campaign aims to affect Baltimore city living perceptions locally and nationally and help us realize net population growth.              | 10000       | 1750        | 8250       | www.livebaltimore.com/donate                         | www.livebaltimore.com          | 39.293880000000001 | -76.615300000000005 | 
| 1491837895  | 38366  | CITC-2016-CommDevNet-00091  | 2016 | Community Development Network of Maryland, Inc               | Community Development Return on Investment Study                            | Baltimore City | Baltimore City      | Housing and Community Development              | Operating | A study to understand and promote the return on all investments to community development in Maryland.                                                                                                                                                     | 15000       | 1000        | 14000      | http://communitydevelopmentmd.org/join-us/           | www.communitydevelopmentmd.org | 39.291840000000001 | -76.610699999999994 | 
| 1491837895  | 38165  | CITC-2016-MHP-00056         | 2016 | Montgomery Housing Partnership, Inc.                         | MHP Community LIfe Programs (Preschool Programs and Homework Clubs)         | Montgomery     | Washington Suburban | Housing and Community Development              | Operating | MHP is seeking support for two of its on-site educational programs: 1) Our Play and Learn programs help preschool children attain kindergarten readiness; 2) Our Homework Clubs provide afterschool academic support for children ages 5-11.              | 40000       | 20416.47    | 19583.53   | https://www.givedirect.org/give/givefrm.asp?CID=1110 | www.mhpartners.org             | 39.056789999999999 | -76.968100000000007 | 
| 1491837895  | 38283  | CITC-2016-H4HWcmco-00076    | 2016 | Habitat for Humanity of Wicomico County, Inc.                | Church Street Revitalization                                                | Wicomico       | Lower Eastern Shore | Housing and Community Development              | Capital   | Habitat for Humanity?s (HFH) mission is to bring people together to build homes, neighborhoods and hope. Our construction projects continue to focus on revitalize on the Church Street area which has been plagued by crime, prostitution and drugs.     | 50000       | 10625       | 39375      | https://www.givesendgo.com/GBEC                      | wicomicohabitat.org            | 38.370080000000002 | -75.611599999999996 | 
| 1491837895  | 39937  | CITC-2017-YMCACmbrlnd-00053 | 2017 | Young Men's Christian Association of Cumberland MD, Inc.,The | YMCA Young Adult Center                                                     | Allegany       | Western Maryland    | Education and Youth Services                   | Operating | To provide a safe place for disconnected and struggling youth adults-ages 16-25 to get the tools, guidance and resources for being more successful at reaching their full potential.                                                                      | 25000       | 0           | 25000      | www.cumberlandymca.org/donate.html                   | www.cumberlandymca.org         | 39.645350000000001 | -78.778599999999997 | 
| 1491837895  | 38288  | CITC-2016-LAB-00077         | 2016 | Legal Aid Bureau, Inc.                                       | Foreclosure & Eviction Prevention Legal Assistance Project                  | Baltimore City | Baltimore City      | Services for At-Risk Populations               | Operating | Maryland Legal Aid will provide free legal assistance to low-income residents who are at-risk of losing their affordable housing due to eviction or foreclosure in Baltimore City, Prince George?s and Montgomery counties in Priority Funding Areas.     | 50000       | 34000       | 16000      | https://donatenow.networkforgood.org/mdlab           | www.mdlab.org                  | 39.291490000000003 | -76.608599999999996 | 
| 1491837895  | 40061  | CITC-2017-HCHI-00102        | 2017 | Health Care for the Homeless                                 | Giving our homeless neighbors more places to receive lifesaving dental care | Baltimore City | Baltimore City      | Services for At-Risk Populations               | Operating | Health Care for the Homeless is taking the lead in bringing dental care to our poorest neighbors. In 2016 we are adding two new dental clinics in Baltimore City to expand access to preventive and restorative dental care for our clients.              | 40000       | 0           | 40000      | https://giving.hchmd.org/checkout/donation?eid=66461 | http://www.hchmd.org/          | 39.293729999999996 | -76.609499999999997 | 
| 1491837895  | 38131  | CITC-2016-WaverlyMnSt-00047 | 2016 | Waverly Main Street                                          | Merchant Medallion Program                                                  | Baltimore City | Baltimore City      | Enhancing Neighborhoods and Business Districts | Operating | The Waverly Main Street Merchant Medallion Program will provide enhanced services to district businesses while promoting our organization and the economic revitalization of the Greenmount Avenue business corridor.                                     | 15000       | 750         | 14250      | http://waverlymainstreet.net/?q=Welcome              | www.waverlymainstreet.org      | 39.327640000000002 | -76.610200000000006 | 
| 1491837895  | 40087  | CITC-2017-CarrotThtr-00111  | 2017 | Single Carrot Theatre                                        | CITC-2017-Single Carrot Theatre                                             | Baltimore City | Baltimore City      | Arts, Culture and Historic Preservation        | Operating | Single Carrot Theatre requests $25,000 in CITCs to leverage new contributions and increased support amongst its donors. These funds would sustain SCT's ongoing role as a cultural anchor and economic driver in the Remington neighborhood of Baltimore. | 20000       | 0           | 20000      | www.singlecarrot.com/donate                          | www.singlecarrot.com           | 39.319519999999997 | -76.620199999999997 | 
```