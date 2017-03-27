# LSTA Allotments (FY 2003-2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lsta-allotments-fy-2003-2016) |
| Metadata | [Link](https://data.imls.gov/api/views/fg2z-wgcj) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/fg2z-wgcj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/fg2z-wgcj/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | fg2z-wgcj |
| Name | LSTA Allotments (FY 2003-2016) |
| Attribution | IMLS |
| Category | Administrative Data |
| Tags | lsta, library services and technology act, allotments, budget, administrative, trends |
| Created | 2014-10-29T21:01:56Z |
| Publication Date | 2016-08-29T18:45:41Z |

## Description

Review Library Services and Technology Act (LSTA) allotments by state from FY 2003 to FY 2016.

The Grants to States program is the largest source of federal funding support for library services in the U.S. Using a population-based formula, more than $150 million is distributed among the state library agencies every year. 

Visit https://www.imls.gov/grants/grants-states to learn more about Grants to States.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | numeric metric | fy2016     | FY 2016 | money     | money       |
| Yes      | numeric metric | fy2015     | FY 2015 | money     | money       |
| Yes      | numeric metric | fy2014     | FY 2014 | money     | money       |
| Yes      | numeric metric | fy2013     | FY 2013 | money     | money       |
| Yes      | numeric metric | fy2012     | FY 2012 | money     | money       |
| Yes      | numeric metric | fy2011     | FY 2011 | money     | money       |
| Yes      | numeric metric | fy2010     | FY 2010 | money     | money       |
| Yes      | numeric metric | fy2009     | FY 2009 | money     | money       |
| Yes      | numeric metric | fy2008     | FY 2008 | money     | money       |
| Yes      | numeric metric | fy2007     | FY 2007 | money     | money       |
| Yes      | numeric metric | fy2006     | FY 2006 | money     | money       |
| Yes      | numeric metric | fy2005     | FY 2005 | money     | money       |
| Yes      | numeric metric | fy2004     | FY 2004 | money     | money       |
| Yes      | numeric metric | fy2003     | FY 2003 | money     | money       |
```

## Time Field

```ls
Value = 2003
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fg2z-wgcj d:2003-01-01T00:00:00.000Z m:fy2005=65977 m:fy2014=80642 m:fy2006=65739 m:fy2015=80129 m:fy2016=80264 m:fy2003=71777 m:fy2004=71777 m:fy2010=89708 m:fy2011=86309 m:fy2012=81378 m:fy2013=80076 m:fy2009=88735 m:fy2007=65449 m:fy2008=65133

series e:fg2z-wgcj d:2003-01-01T00:00:00.000Z m:fy2005=75106 m:fy2014=79303 m:fy2006=75737 m:fy2015=79389 m:fy2016=79993 m:fy2003=76185 m:fy2004=76184 m:fy2010=83305 m:fy2011=80639 m:fy2012=80748 m:fy2013=79484 m:fy2009=98393 m:fy2007=76310 m:fy2008=76850

series e:fg2z-wgcj d:2003-01-01T00:00:00.000Z m:fy2005=203404 m:fy2014=254300 m:fy2006=203371 m:fy2015=253590 m:fy2016=254576 m:fy2003=216389 m:fy2004=216389 m:fy2010=267255 m:fy2011=257272 m:fy2012=254658 m:fy2013=250113 m:fy2009=265072 m:fy2007=203225 m:fy2008=203040
```

## Meta Commands

```ls
metric m:fy2016 p:integer l:"FY 2016" d:"Fiscal Year 2016" t:dataTypeName=money

metric m:fy2015 p:integer l:"FY 2015" d:"Fiscal Year 2015" t:dataTypeName=money

metric m:fy2014 p:integer l:"FY 2014" d:"Fiscal Year 2014" t:dataTypeName=money

metric m:fy2013 p:integer l:"FY 2013" d:"Fiscal Year 2013" t:dataTypeName=money

metric m:fy2012 p:integer l:"FY 2012" d:"Fiscal Year 2012" t:dataTypeName=money

metric m:fy2011 p:integer l:"FY 2011" d:"Fiscal Year 2011" t:dataTypeName=money

metric m:fy2010 p:integer l:"FY 2010" d:"Fiscal Year 2010" t:dataTypeName=money

metric m:fy2009 p:integer l:"FY 2009" d:"Fiscal Year 2009" t:dataTypeName=money

metric m:fy2008 p:integer l:"FY 2008" d:"Fiscal Year 2008" t:dataTypeName=money

metric m:fy2007 p:integer l:"FY 2007" d:"Fiscal Year 2007" t:dataTypeName=money

metric m:fy2006 p:integer l:"FY 2006" d:"Fiscal Year 2006" t:dataTypeName=money

metric m:fy2005 p:integer l:"FY 2005" d:"Fiscal Year 2005" t:dataTypeName=money

metric m:fy2004 p:integer l:"FY 2004" d:"Fiscal Year 2004" t:dataTypeName=money

metric m:fy2003 p:integer l:"FY 2003" d:"Fiscal Year 2003" t:dataTypeName=money

entity e:fg2z-wgcj l:"LSTA Allotments (FY 2003-2016)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/fg2z-wgcj

property e:fg2z-wgcj t:meta.view v:id=fg2z-wgcj v:category="Administrative Data" v:attributionLink=https://www.imls.gov/grants/grants-state/state-allotments v:averageRating=0 v:name="LSTA Allotments (FY 2003-2016)" v:attribution=IMLS

property e:fg2z-wgcj t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:fg2z-wgcj t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:fg2z-wgcj t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:fg2z-wgcj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```