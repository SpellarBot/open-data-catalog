# University of Illinois at Chicago Health Policy Center - Funding

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/university-of-illinois-at-chicago-health-policy-center-funding-27085) |
| Metadata | [Link](https://data.cdc.gov/api/views/vw7y-v3uk) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vw7y-v3uk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vw7y-v3uk/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vw7y-v3uk |
| Name | University of Illinois at Chicago Health Policy Center - Funding |
| Category | Funding |
| Tags | osh, office on smoking and health, state system, tobacco, funding, funds, appropriation, expenditure, spending, allocation, dollars, money, grants, awards, federal, best practices, state and commu... |
| Created | 2014-08-27T13:18:51Z |
| Publication Date | 2017-02-06T17:27:04Z |

## Description

1991-2014. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System.  Funding Data, Appropriations (1991-2014) and Expenditures (2008-2014).  Appropriations data show public funds allocated to/by a particular state for tobacco prevention and control.  They are not necessarily expended.  Appropriations are from four major funding sources, Federal, state, Robert Wood Johnson Foundation (RWJF), and the American Legacy Foundation (Legacy).  Expenditures are amounts spent by state tobacco control programs on tobacco prevention and control.  Expenditure data are available by 2007 CDC Best Practices Program Components (State and Community Interventions, Health Communication Interventions, Cessation Interventions, Surveillance and Evaluation, and Administration and Management).

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | YEAR                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | topicdesc                  | TopicDesc                  | text      | text        |
| Yes      | series tag     | measuredesc                | MeasureDesc                | text      | text        |
| Yes      | series tag     | source                     | Source                     | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | series tag     | funding_cycle              | Funding_Cycle              | text      | text        |
| Yes      | series tag     | topictypeid                | TopicTypeId                | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | measureid                  | MeasureId                  | text      | text        |
| Yes      | series tag     | datasourcedesc             | DataSourceDesc             | text      | text        |
| Yes      | series tag     | submeasureid               | SubMeasureID               | text      | text        |
| No       |                | displayorder               | DisplayOrder               | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote,displayorder
```

## Data Commands

```ls
series e:vw7y-v3uk d:2013-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=400FND t:source="American Legacy Foundation" t:measureid=400APP t:measuredesc=Appropriations/Grants t:topicdesc=Funding t:datasourcedesc="Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC)" t:submeasureid=SRC06 t:datasource=UIC t:topictypeid=FND m:data_value=0

series e:vw7y-v3uk d:2013-01-01T00:00:00.000Z t:funding_cycle=04/12-03/13 t:locationabbr=AL t:locationdesc=Alabama t:topicid=400FND t:source=Federal t:measureid=400APP t:measuredesc=Appropriations/Grants t:topicdesc=Funding t:datasourcedesc="Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC)" t:submeasureid=SRC03 t:datasource=UIC t:topictypeid=FND m:data_value=2975150

series e:vw7y-v3uk d:2013-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=400FND t:source="Robert Wood Johnson Foundation" t:measureid=400APP t:measuredesc=Appropriations/Grants t:topicdesc=Funding t:datasourcedesc="Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC)" t:submeasureid=SRC05 t:datasource=UIC t:topictypeid=FND m:data_value=0
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:"Value of the data" t:dataTypeName=number

entity e:vw7y-v3uk l:"University of Illinois at Chicago Health Policy Center - Funding" t:url=https://data.cdc.gov/api/views/vw7y-v3uk

property e:vw7y-v3uk t:meta.view v:id=vw7y-v3uk v:category=Funding v:attributionLink=http://www.impacteen.org/ v:averageRating=0 v:name="University of Illinois at Chicago Health Policy Center - Funding"

property e:vw7y-v3uk t:meta.view.license v:name="Public Domain"

property e:vw7y-v3uk t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:vw7y-v3uk t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:vw7y-v3uk t:meta.view.metadata.custom_fields.common_core v:Contact_Email=OSHData@cdc.gov v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | topicdesc | measuredesc           | source                                                | datasource | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote | funding_cycle | topictypeid | topicid | measureid | datasourcedesc                                                                                    | submeasureid | displayorder | 
| ==== | ============ | ============ | ========= | ===================== | ===================================================== | ========== | =============== | =============== | ========== | ========================== | =================== | ============= | =========== | ======= | ========= | ================================================================================================= | ============ | ============ | 
| 2013 | AL           | Alabama      | Funding   | Appropriations/Grants | American Legacy Foundation                            | UIC        | $               | Dollars         | 0          |                            |                     |               | FND         | 400FND  | 400APP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC06        | 6            | 
| 2013 | AL           | Alabama      | Funding   | Appropriations/Grants | Federal                                               | UIC        | $               | Dollars         | 2975150    |                            |                     | 04/12-03/13   | FND         | 400FND  | 400APP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC03        | 3            | 
| 2013 | AL           | Alabama      | Funding   | Appropriations/Grants | Robert Wood Johnson Foundation                        | UIC        | $               | Dollars         | 0          |                            |                     |               | FND         | 400FND  | 400APP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC05        | 5            | 
| 2013 | AL           | Alabama      | Funding   | Appropriations/Grants | State                                                 | UIC        | $               | Dollars         | 331730     |                            |                     | 10/12-09/13   | FND         | 400FND  | 400APP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC04        | 4            | 
| 2013 | AL           | Alabama      | Funding   | Appropriations/Grants | Total                                                 | UIC        | $               | Dollars         | 3306880    |                            |                     |               | FND         | 400FND  | 400APP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC01        | 1            | 
| 2013 | AL           | Alabama      | Funding   | Appropriations/Grants | Total Per Capita                                      | UIC        | $               | Dollars         | 0.68       |                            |                     |               | FND         | 400FND  | 400APP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC02        | 2            | 
| 2013 | AL           | Alabama      | Funding   | Expenditures          | 2007 CDC Best Practices Recommended Annual Investment | UIC        | $               | Dollars         | 56700000   |                            |                     |               | FND         | 400FND  | 401EXP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC09        | 3            | 
| 2013 | AL           | Alabama      | Funding   | Expenditures          | Administration and Management                         | UIC        | $               | Dollars         | 553000     |                            |                     |               | FND         | 400FND  | 401EXP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC16        | 10           | 
| 2013 | AL           | Alabama      | Funding   | Expenditures          | All Interventions Subtotal                            | UIC        | $               | Dollars         | 2757000    |                            |                     |               | FND         | 400FND  | 401EXP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC14        | 8            | 
| 2013 | AL           | Alabama      | Funding   | Expenditures          | Cessation Interventions                               | UIC        | $               | Dollars         | 1200000    |                            |                     |               | FND         | 400FND  | 401EXP    | Bridging the Gap/ImpacTeen Project, University of Iillinois at Chicago Health Policy Center (UIC) | SRC12        | 6            | 
```