# BRFSS Prevalence And Trends Data: Tobacco Use - Adults Who Are Current Smokers for 1995-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/brfss-prevalence-and-trends-data-tobacco-use-adults-who-are-current-smokers-for-1995-2010-76044) |
| Metadata | [Link](https://data.cdc.gov/api/views/j8jk-5ztv) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/j8jk-5ztv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/j8jk-5ztv/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | j8jk-5ztv |
| Name | BRFSS Prevalence And Trends Data: Tobacco Use - Adults Who Are Current Smokers for 1995-2010 |
| Attribution | Behavioral Risk Factor Surveillance System (BRFSS) |
| Category | Smoking & Tobacco Use |
| Tags | brfss, current smokers, adults |
| Created | 2013-06-10T19:09:30Z |
| Publication Date | 2013-08-01T15:52:21Z |

## Description

Percentages are weighted to population characteristics. Data are not available if it did not meet BRFSS stability requirements.For more information on these requirements, as well as risk factors and calculated variables, see the Technical Documents and Survey Data for a specific year - http://www.cdc.gov/brfss/annual_data/annual_data.htm.Recommended citation: Centers for Disease Control and Prevention (CDC). Behavioral Risk Factor Surveillance System. Atlanta, Georgia: U.S. Department of Health and Human Services, Centers for Disease Control and Prevention, [appropriate year].

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | number      |
| Yes      | series tag     | state      | State     | text      | text        |
| Yes      | series tag     | condition  | Condition | text      | text        |
| Yes      | numeric metric | yes        | Yes       | percent   | percent     |
| No       |                | no         | No        | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = no
```

## Data Commands

```ls
series e:j8jk-5ztv d:2003-01-01T00:00:00.000Z t:condition="Adults who are current smokers" t:state=Guam m:yes=34

series e:j8jk-5ztv d:2009-01-01T00:00:00.000Z t:condition="Adults who are current smokers" t:state=Texas m:yes=17.9

series e:j8jk-5ztv d:2003-01-01T00:00:00.000Z t:condition="Adults who are current smokers" t:state=Nevada m:yes=25.2
```

## Meta Commands

```ls
metric m:yes p:double l:Yes t:dataTypeName=percent

entity e:j8jk-5ztv l:"BRFSS Prevalence And Trends Data: Tobacco Use - Adults Who Are Current Smokers for 1995-2010" t:attribution="Behavioral Risk Factor Surveillance System (BRFSS)" t:url=https://data.cdc.gov/api/views/j8jk-5ztv

property e:j8jk-5ztv t:meta.view v:id=j8jk-5ztv v:category="Smoking & Tobacco Use" v:attributionLink=http://www.cdc.gov/brfss/ v:averageRating=0 v:name="BRFSS Prevalence And Trends Data: Tobacco Use - Adults Who Are Current Smokers for 1995-2010" v:attribution="Behavioral Risk Factor Surveillance System (BRFSS)"

property e:j8jk-5ztv t:meta.view.owner v:id=7vdi-f8f4 v:screenName=Mark@CDC v:displayName=Mark@CDC

property e:j8jk-5ztv t:meta.view.tableauthor v:id=7vdi-f8f4 v:screenName=Mark@CDC v:roleName=editor v:displayName=Mark@CDC

property e:j8jk-5ztv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| year | state        | condition                      | yes  | no   | 
| ==== | ============ | ============================== | ==== | ==== | 
| 2003 | Guam         | Adults who are current smokers | 34   | 66   | 
| 2009 | Texas        | Adults who are current smokers | 17.9 | 82.1 | 
| 2003 | Nevada       | Adults who are current smokers | 25.2 | 74.8 | 
| 1998 | Washington   | Adults who are current smokers | 21.4 | 78.6 | 
| 1998 | Nebraska     | Adults who are current smokers | 22   | 78   | 
| 1995 | California   | Adults who are current smokers | 15.5 | 84.5 | 
| 2007 | Arizona      | Adults who are current smokers | 19.8 | 80.2 | 
| 2002 | Louisiana    | Adults who are current smokers | 23.9 | 76.1 | 
| 2000 | Maryland     | Adults who are current smokers | 20.5 | 79.5 | 
| 2006 | South Dakota | Adults who are current smokers | 20.3 | 79.7 | 
```