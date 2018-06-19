# IMLS Appropriations (FY 2002-2017)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/imls-appropriations-fy-2002-2017) |
| Metadata | [Link](https://data.imls.gov/api/views/pv6v-66cr) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/pv6v-66cr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/pv6v-66cr/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | pv6v-66cr |
| Name | IMLS Appropriations (FY 2002-2017) |
| Attribution | IMLS |
| Category | Administrative Data |
| Tags | appropriations, budget, administrative |
| Created | 2015-02-09T16:21:46Z |
| Publication Date | 2016-08-09T15:33:01Z |

## Description

Review the history of Institute of Museum and Library Services (IMLS) appropriations from FY 2002 to FY 2017.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | statutory_authority | Statutory Authority | text      | text        |
| Yes      | numeric metric | fy_2017             | FY 2017 Request     | money     | money       |
| Yes      | numeric metric | fy_2016             | FY 2016 Enacted     | money     | money       |
| Yes      | numeric metric | fy2015              | FY 2015 Enacted     | money     | money       |
| Yes      | numeric metric | fy2014              | FY 2014 Enacted     | money     | money       |
| Yes      | numeric metric | fy2013              | FY 2013 Enacted     | money     | money       |
| Yes      | numeric metric | fy2012              | FY 2012 Enacted     | money     | money       |
| Yes      | numeric metric | fy2011              | FY 2011 Enacted     | money     | money       |
| Yes      | numeric metric | fy2010              | FY 2010 Enacted     | money     | money       |
| Yes      | numeric metric | fy2009              | FY 2009 Enacted     | money     | money       |
| Yes      | numeric metric | fy2008              | FY 2008 Enacted     | money     | money       |
| Yes      | numeric metric | fy2007              | FY 2007 Enacted     | money     | money       |
| Yes      | numeric metric | fy2006              | FY 2006 Enacted     | money     | money       |
| Yes      | numeric metric | fy2005              | FY 2005 Enacted     | money     | money       |
| Yes      | numeric metric | fy2004              | FY 2004 Enacted     | money     | money       |
| Yes      | numeric metric | fy2003              | FY 2003 Enacted     | money     | money       |
| Yes      | numeric metric | fy2002              | FY 2002 Enacted     | money     | money       |
```

## Time Field

```ls
Value = 2002
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pv6v-66cr d:2002-01-01T00:00:00.000Z t:statutory_authority="LSTA: Grants to States" m:fy2014=154848000 m:fy2005=160704000 m:fy2015=154848000 m:fy2006=163746000 m:fy_2016=155789000 m:fy2003=150435000 m:fy2004=157628000 m:fy2010=172561000 m:fy2011=160032000 m:fy2002=149014000 m:fy2012=156365000 m:fy2013=150000000 m:fy2009=171500000 m:fy2007=163746000 m:fy2008=160885000 m:fy_2017=154848000

series e:pv6v-66cr d:2002-01-01T00:00:00.000Z t:statutory_authority="LSTA: Native American Library Services" m:fy2014=3861000 m:fy2005=3472000 m:fy2015=3861000 m:fy2006=3638000 m:fy_2016=4063000 m:fy2003=3055000 m:fy2004=3206000 m:fy2010=4000000 m:fy2011=3960000 m:fy2002=2941000 m:fy2012=3869000 m:fy2013=3667000 m:fy2009=3717000 m:fy2007=3638000 m:fy2008=3574000 m:fy_2017=3861000

series e:pv6v-66cr d:2002-01-01T00:00:00.000Z t:statutory_authority="LSTA: National Leadership: Libraries" m:fy2014=12200000 m:fy2005=12301000 m:fy2015=12200000 m:fy2006=12375000 m:fy_2016=13092000 m:fy2003=11009000 m:fy2004=11263000 m:fy2010=12437000 m:fy2011=12225000 m:fy2002=11081000 m:fy2012=11946000 m:fy2013=11377000 m:fy2009=12437000 m:fy2007=12375000 m:fy2008=12159000 m:fy_2017=13720000
```

## Meta Commands

```ls
metric m:fy_2017 p:integer l:"FY 2017 Request" t:dataTypeName=money

metric m:fy_2016 p:integer l:"FY 2016 Enacted" t:dataTypeName=money

metric m:fy2015 p:integer l:"FY 2015 Enacted" t:dataTypeName=money

metric m:fy2014 p:integer l:"FY 2014 Enacted" t:dataTypeName=money

metric m:fy2013 p:integer l:"FY 2013 Enacted" t:dataTypeName=money

metric m:fy2012 p:integer l:"FY 2012 Enacted" t:dataTypeName=money

metric m:fy2011 p:integer l:"FY 2011 Enacted" t:dataTypeName=money

metric m:fy2010 p:integer l:"FY 2010 Enacted" t:dataTypeName=money

metric m:fy2009 p:integer l:"FY 2009 Enacted" t:dataTypeName=money

metric m:fy2008 p:integer l:"FY 2008 Enacted" t:dataTypeName=money

metric m:fy2007 p:integer l:"FY 2007 Enacted" t:dataTypeName=money

metric m:fy2006 p:integer l:"FY 2006 Enacted" t:dataTypeName=money

metric m:fy2005 p:integer l:"FY 2005 Enacted" t:dataTypeName=money

metric m:fy2004 p:integer l:"FY 2004 Enacted" t:dataTypeName=money

metric m:fy2003 p:integer l:"FY 2003 Enacted" t:dataTypeName=money

metric m:fy2002 p:integer l:"FY 2002 Enacted" t:dataTypeName=money

entity e:pv6v-66cr l:"IMLS Appropriations (FY 2002-2017)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/pv6v-66cr

property e:pv6v-66cr t:meta.view v:id=pv6v-66cr v:category="Administrative Data" v:attributionLink=https://www.imls.gov/about-us/legislation-budget/imls-budget v:averageRating=0 v:name="IMLS Appropriations (FY 2002-2017)" v:attribution=IMLS

property e:pv6v-66cr t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:pv6v-66cr t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:pv6v-66cr t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:pv6v-66cr t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| statutory_authority                              | fy_2017   | fy_2016   | fy2015    | fy2014    | fy2013    | fy2012    | fy2011    | fy2010    | fy2009    | fy2008    | fy2007    | fy2006    | fy2005    | fy2004    | fy2003    | fy2002    | 
| ================================================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | 
| LSTA: Grants to States                           | 154848000 | 155789000 | 154848000 | 154848000 | 150000000 | 156365000 | 160032000 | 172561000 | 171500000 | 160885000 | 163746000 | 163746000 | 160704000 | 157628000 | 150435000 | 149014000 | 
| LSTA: Native American Library Services           | 3861000   | 4063000   | 3861000   | 3861000   | 3667000   | 3869000   | 3960000   | 4000000   | 3717000   | 3574000   | 3638000   | 3638000   | 3472000   | 3206000   | 3055000   | 2941000   | 
| LSTA: National Leadership: Libraries             | 13720000  | 13092000  | 12200000  | 12200000  | 11377000  | 11946000  | 12225000  | 12437000  | 12437000  | 12159000  | 12375000  | 12375000  | 12301000  | 11263000  | 11009000  | 11081000  | 
| LSTA: Laura Bush 21st Century Librarian          | 10000000  | 10000000  | 10000000  | 10000000  | 10000000  | 12524000  | 12818000  | 24525000  | 24525000  | 23345000  | 23760000  | 23760000  | 22816000  | 19882000  | 9935000   | 0         | 
| SUBTOTAL, LIBRARY SERVICES TECHNOLOGY ACT (LSTA) | 182429000 | 182944000 | 180909000 | 180909000 | 175044000 | 184704000 | 189035000 | 213523000 | 212179000 | 199963000 | 203519000 | 203519000 | 199293000 | 191979000 | 174434000 | 163036000 | 
| MSA: Museums for America                         | 20200000  | 21149000  | 20200000  | 20200000  | 19564000  | 18030000  | 18453000  | 19176000  | 19176000  | 16852000  | 17152000  | 17152000  | 16864000  | 16342000  | 15381000  | 15482000  | 
| MSA: Museum Assessment Program                   | 0         | 0         | 0         | 0         | 0         | 0         | 0         | 460000    | 460000    | 434000    | 442000    | 442000    | 446000    | 447000    | 447000    | 450000    | 
| MSA: 21st Century Museum Professionals           | 0         | 0         | 0         | 0         | 0         | 1969000   | 2015000   | 1280000   | 1280000   | 965000    | 982000    | 982000    | 992000    | 0         | 0         | 0         | 
| MSA: Conservation Project Support                | 0         | 0         | 0         | 0         | 0         | 2613000   | 2675000   | 3052000   | 3052000   | 2724000   | 2772000   | 2772000   | 2788000   | 2782000   | 2792000   | 2310000   | 
| MSA: Conservation Assessment Program             | 0         | 0         | 0         | 0         | 0         | 0         | 0         | 803000    | 803000    | 793000    | 807000    | 807000    | 813000    | 815000    | 815000    | 820000    | 
```