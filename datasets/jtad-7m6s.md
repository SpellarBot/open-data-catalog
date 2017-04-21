# Lobbyist Reportable Business Relationships with State Officials and Employees: Beginning 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyist-reportable-business-relationships-with-state-officials-and-employees-beginning-20) |
| Metadata | [Link](https://data.ny.gov/api/views/jtad-7m6s) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jtad-7m6s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jtad-7m6s/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jtad-7m6s |
| Name | Lobbyist Reportable Business Relationships with State Officials and Employees: Beginning 2012 |
| Attribution | NYS Joint Commission on Public Ethics |
| Category | Transparency |
| Tags | lobbyist, business relationships, integrity |
| Created | 2013-04-16T15:30:32Z |
| Publication Date | 2016-11-30T21:23:23Z |

## Description

Data provided by Lobbyist in the Biennial Registration filings submitted to NYS Joint Commission on Public Ethics.

## Columns

```ls
| Included | Schema Type | Field Name                       | Name                             | Data Type | Render Type |
| ======== | =========== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag  | lobbyist_name                    | Lobbyist Name                    | text      | text        |
| Yes      | series tag  | report_year                      | Report Year                      | text      | text        |
| Yes      | series tag  | business_relationship_form_filed | Business Relationship Form Filed | url       | url         |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jtad-7m6s d:2012-01-01T00:00:00.000Z t:lobbyist_name="ANSI Partners, LLC" t:report_year=2013-2014 t:business_relationship_form_filed=http://www.jcope.ny.gov/rbr/forms/lobbyist/Lobby.2013-2014.ANSI.Partners.LLC.pdf m:row_number.jtad-7m6s=1

series e:jtad-7m6s d:2012-01-01T00:00:00.000Z t:lobbyist_name="TWC Administration, LLC" t:report_year=2013-2014 t:business_relationship_form_filed=http://www.jcope.ny.gov/rbr/forms/lobbyist/Lobby.2013-2014.TWC.Administration.LLC.pdf m:row_number.jtad-7m6s=2

series e:jtad-7m6s d:2012-01-01T00:00:00.000Z t:lobbyist_name="Brown, Arthur M" t:report_year=2011-2012 t:business_relationship_form_filed=http://www.jcope.ny.gov/rbr/forms/lobbyist/2011-12.Brown%20Arthur%20M..pdf m:row_number.jtad-7m6s=3
```

## Meta Commands

```ls
metric m:row_number.jtad-7m6s p:long l:"Row Number"

entity e:jtad-7m6s l:"Lobbyist Reportable Business Relationships with State Officials and Employees: Beginning 2012" t:attribution="NYS Joint Commission on Public Ethics" t:url=https://data.ny.gov/api/views/jtad-7m6s

property e:jtad-7m6s t:meta.view v:id=jtad-7m6s v:category=Transparency v:attributionLink=http://www.jcope.ny.gov v:averageRating=0 v:name="Lobbyist Reportable Business Relationships with State Officials and Employees: Beginning 2012" v:attribution="NYS Joint Commission on Public Ethics"

property e:jtad-7m6s t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jtad-7m6s t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jtad-7m6s t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| lobbyist_name           | report_year | business_relationship_form_filed                                                                  | 
| ======================= | =========== | ================================================================================================= | 
| ANSI Partners, LLC      | 2013-2014   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/Lobby.2013-2014.ANSI.Partners.LLC.pdf, null]          | 
| TWC Administration, LLC | 2013-2014   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/Lobby.2013-2014.TWC.Administration.LLC.pdf, null]     | 
| Brown, Arthur M         | 2011-2012   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/2011-12.Brown%20Arthur%20M..pdf, null]                | 
| Greenberg Traurig, LLP  | 2013-2014   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/RBRGreenberg%20Traurig,%20LLP%202013.pdf, null]       | 
| Greenberg Traurig, LLP  | 2011-2012   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/RBRGreenberg%20Traurig,%20LLP%202011.pdf, null]       | 
| Greenberg Traurig, LLP  | 2011-2012   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/2011-12.Greenberg%20Traurig,%20LLP.pdf, null]         | 
| Hill Gosdeck McGraw LLC | 2013-2014   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/2013-14.Hill%20Gosdeck%20%20McGraw%20LLC.pdf, null]   | 
| Hill Gosdeck McGraw LLC | 2011-2012   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/2011-12%20Hill%20Gosdeck%20%20McGraw%20LLC.pdf, null] | 
| National Grid           | 2011-2012   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/2011.2012.National%20Grid.pdf, null]                  | 
| Baruch College          | 2013-2014   | [http://www.jcope.ny.gov/rbr/forms/lobbyist/Baruch%20College%20(13-14)%20Lobbyist.pdf, null]      | 
```