# Public Determinations of the NYS Commission on Judicial Conduct: Beginning 1977

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-determinations-of-the-nys-commission-on-judicial-conduct-beginning-1977) |
| Metadata | [Link](https://data.ny.gov/api/views/gnpf-e4p2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/gnpf-e4p2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/gnpf-e4p2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | gnpf-e4p2 |
| Name | Public Determinations of the NYS Commission on Judicial Conduct: Beginning 1977 |
| Attribution | New York State Commission on Judicial Conduct |
| Category | Transparency |
| Tags | judicial conduct, judge, court |
| Created | 2013-12-27T18:29:37Z |
| Publication Date | 2016-01-07T23:01:39Z |

## Description

All public determinations of judicial misconduct rendered by the NYS Commission on Judicial Conduct since the current Commission's inception in 1978, together with earlier determinations of the prior Commission.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | name_last_first         | Name - Last, First      | text      | text        |
| Yes      | series tag     | judicial_title          | Judicial Title          | text      | text        |
| Yes      | series tag     | court                   | Court                   | text      | text        |
| Yes      | series tag     | county                  | County                  | text      | text        |
| Yes      | series tag     | determination           | Determination           | text      | text        |
| Yes      | numeric metric | year_of_determination   | Year of Determination   | number    | number      |
| Yes      | series tag     | court_of_appeals_review | Court of Appeals Review | text      | text        |
| Yes      | series tag     | link                    | Link                    | url       | url         |
```

## Time Field

```ls
Value = 1977
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gnpf-e4p2 d:1977-01-01T00:00:00.000Z t:county=Wayne t:judicial_title=Justice t:link=http://cjc.ny.gov/Determinations/A/abbott.htm t:determination=Censure t:court="Palmyra Town Court" t:name_last_first="Abbott, William E." m:year_of_determination=1989

series e:gnpf-e4p2 d:1977-01-01T00:00:00.000Z t:county=Saratoga t:judicial_title=Judge t:link=http://cjc.ny.gov/Determinations/A/Abramson.htm t:determination=Removal t:court="Family Court" t:name_last_first="Abramson, Gilbert L." m:year_of_determination=2010

series e:gnpf-e4p2 d:1977-01-01T00:00:00.000Z t:county=Ontario t:judicial_title=Justice t:link=http://cjc.ny.gov/Determinations/A/adams.htm t:determination=Removal t:court="Phelps Town Court" t:name_last_first="Adams, Paul W." m:year_of_determination=1978
```

## Meta Commands

```ls
metric m:year_of_determination p:integer l:"Year of Determination" t:dataTypeName=number

entity e:gnpf-e4p2 l:"Public Determinations of the NYS Commission on Judicial Conduct: Beginning 1977" t:attribution="New York State Commission on Judicial Conduct" t:url=https://data.ny.gov/api/views/gnpf-e4p2

property e:gnpf-e4p2 t:meta.view v:id=gnpf-e4p2 v:category=Transparency v:attributionLink=http://www.cjc.ny.gov v:averageRating=0 v:name="Public Determinations of the NYS Commission on Judicial Conduct: Beginning 1977" v:attribution="New York State Commission on Judicial Conduct"

property e:gnpf-e4p2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:gnpf-e4p2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:gnpf-e4p2 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| name_last_first          | judicial_title | court                                                                    | county      | determination | year_of_determination | court_of_appeals_review        | link                                                               | 
| ======================== | ============== | ======================================================================== | =========== | ============= | ===================== | ============================== | ================================================================== | 
| Abbott, William E.       | Justice        | Palmyra Town Court                                                       | Wayne       | Censure       | 1989                  |                                | [http://cjc.ny.gov/Determinations/A/abbott.htm, null]              | 
| Abramson, Gilbert L.     | Judge          | Family Court                                                             | Saratoga    | Removal       | 2010                  |                                | [http://cjc.ny.gov/Determinations/A/Abramson.htm, null]            | 
| Adams, Paul W.           | Justice        | Phelps Town Court                                                        | Ontario     | Removal       | 1978                  |                                | [http://cjc.ny.gov/Determinations/A/adams.htm, null]               | 
| Agresta, Thomas S.       | Justice        | Supreme Court, 11th Judicial District                                    | Queens      | Censure       | 1984                  | Censure accepted               | [http://cjc.ny.gov/Determinations/A/agresta.htm, null]             | 
| Ain, Stuart L.           | Judge          | County Court and an Acting Supreme Court Justice, 10th Judicial District | Nassau      | Censure       | 1992                  |                                | [http://cjc.ny.gov/Determinations/A/ain.htm, null]                 | 
| Aison, Howard M.         | Judge          | Amsterdam City Court                                                     | Montgomery  | Censure       | 2009                  |                                | [http://cjc.ny.gov/Determinations/A/aison.htm, null]               | 
| Albanese, Mario M.       | Judge          | County Court                                                             | Fulton      | Admonition    | 1980                  |                                | [http://cjc.ny.gov/Determinations/A/albanese.htm, null]            | 
| Aldrich, Raymond E., Jr. | Judge          | County Court                                                             | Dutchess    | Removal       | 1982                  | Removal accepted               | [http://cjc.ny.gov/Determinations/A/aldrich.htm, null]             | 
| Alessandro, Francis M.   | Judge          | New York City Civil Court                                                | Bronx       | Removal       | 2009                  | Removal modified to Admonition | [http://cjc.ny.gov/Determinations/A/alessandro,_francis.htm, null] | 
| Alessandro, Joseph S.    | Justice        | Supreme Court, 9th Judicial District                                     | Westchester | Removal       | 2009                  | Removal accepted               | [http://cjc.ny.gov/Determinations/A/alessandro,_joseph.htm, null]  | 
```