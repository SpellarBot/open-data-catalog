# Maryland Green Registry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-green-registry) |
| Metadata | [Link](https://data.maryland.gov/api/views/7dpk-qv7c) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/7dpk-qv7c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/7dpk-qv7c/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 7dpk-qv7c |
| Name | Maryland Green Registry |
| Attribution | Maryland Dept. of the Environment |
| Category | Energy and Environment |
| Tags | mde, maryland green registry, sustainability |
| Created | 2015-02-20T16:22:18Z |
| Publication Date | 2016-05-17T17:38:17Z |

## Description

Locations of Maryland Green Registry member organizations. See http://www.mde.state.md.us/marylandgreen/Pages/Home.aspx.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | organization         | Organization         | text      | text        |
| Yes      | series tag  | city_state_zip       | City, State, Zip     | text      | text        |
| Yes      | series tag  | phone                | Phone #              | text      | text        |
| Yes      | series tag  | type_of_organization | Type of Organization | text      | text        |
| Yes      | series tag  | profile              | Profile              | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7dpk-qv7c d:2016-05-16T12:58:41.000Z t:phone=443-543-5573 t:city_state_zip="Baltimore, MD 21227" t:organization="Amethyst Technologies LLC" t:profile=http://www.mde.state.md.us/assets/other/Amethyst_Profile.pdf t:type_of_organization=Biotechnology m:row_number.7dpk-qv7c=1

series e:7dpk-qv7c d:2016-05-16T12:58:41.000Z t:phone=410-703-2697 t:city_state_zip="Annapolis, MD 21403" t:organization="Annapolis Green LLC" t:profile=http://www.mde.state.md.us/marylandgreen/Documents/Annapolis_Green_Profile.pdf t:type_of_organization=Nonprofit m:row_number.7dpk-qv7c=2

series e:7dpk-qv7c d:2016-05-16T12:58:41.000Z t:phone=410-523-7300 t:city_state_zip="Baltimore, MD 21215" t:organization="B&B Lighting Supply Inc." t:profile=http://www.mde.state.md.us/assets/other/BB_Lighting_Profile.pdf t:type_of_organization="Building Materials" m:row_number.7dpk-qv7c=3
```

## Meta Commands

```ls
metric m:row_number.7dpk-qv7c p:long l:"Row Number"

entity e:7dpk-qv7c l:"Maryland Green Registry" t:attribution="Maryland Dept. of the Environment" t:url=https://data.maryland.gov/api/views/7dpk-qv7c

property e:7dpk-qv7c t:meta.view v:id=7dpk-qv7c v:category="Energy and Environment" v:attributionLink=http://www.mde.state.md.us/marylandgreen/Pages/Home.aspx v:averageRating=0 v:name="Maryland Green Registry" v:attribution="Maryland Dept. of the Environment"

property e:7dpk-qv7c t:meta.view.license v:name="Public Domain"

property e:7dpk-qv7c t:meta.view.owner v:id=nts9-k3vt v:screenName="Maryland Green Registry" v:displayName="Maryland Green Registry"

property e:7dpk-qv7c t:meta.view.tableauthor v:id=nts9-k3vt v:screenName="Maryland Green Registry" v:roleName=editor v:displayName="Maryland Green Registry"
```

## Top Records

```ls
| :updated_at | organization                         | city_state_zip               | phone        | type_of_organization | profile                                                                                      | 
| =========== | ==================================== | ============================ | ============ | ==================== | ============================================================================================ | 
| 1463403521  | Amethyst Technologies LLC            | Baltimore, MD 21227          | 443-543-5573 | Biotechnology        | [http://www.mde.state.md.us/assets/other/Amethyst_Profile.pdf, null]                         | 
| 1463403521  | Annapolis Green LLC                  | Annapolis, MD 21403          | 410-703-2697 | Nonprofit            | [http://www.mde.state.md.us/marylandgreen/Documents/Annapolis_Green_Profile.pdf, null]       | 
| 1463403521  | B&B Lighting Supply Inc.             | Baltimore, MD 21215          | 410-523-7300 | Building Materials   | [http://www.mde.state.md.us/assets/other/BB_Lighting_Profile.pdf, null]                      | 
| 1463403521  | Cecil College                        | North East, MD 21901         | 410-287-1027 | Higher Education     | [http://www.mde.state.md.us/assets/other/Cecil_College_Profile.pdf, null]                    | 
| 1463403521  | Chesapeake College                   | Wye Mills, MD 21679          | 410-827-5768 | Higher Education     | [http://www.mde.state.md.us/assets/other/Chesapeake_College_Profile.pdf, null]               | 
| 1463403521  | City of Mount Rainier Maryland       | Mount Rainier, MD 20712      | 301-237-3889 | Local Government     | [http://www.mde.state.md.us/marylandgreen/Documents/City_of_Mount_Rainier_Profile.pdf, null] | 
| 1463403521  | CTCG                                 | Glen Burnie, MD 21060        | 443-962-5145 | IT Services          | [http://www.mde.state.md.us/marylandgreen/Documents/CTCG_Profile.pdf, null]                  | 
| 1463403521  | D.C. Air National Guard (113th Wing) | Joint Base Andrews, MD 20762 | 240-857-0434 | Federal Government   | [http://www.mde.state.md.us/marylandgreen/Documents/DC_Air_National_Guard_Profile.pdf, null] | 
| 1463403521  | Davis, Bowen and Friedel, Inc.       | Salisbury, MD 21801          | 410 543 9091 | Architecture         | [http://www.mde.state.md.us/assets/other/Davis_Bowen_Friedel_Profile.pdf, null]              | 
| 1463403521  | ENERActive Solutions                 | Beltsville, MD 20705         | 443-589-1004 | Energy Services      | [http://www.mde.state.md.us/assets/other/ENERactive_Solutions_Profile.pdf, null]             | 
```