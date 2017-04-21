# NNDSS - Table IV. Tuberculosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-iv-tuberculosis-fd056) |
| Metadata | [Link](https://data.cdc.gov/api/views/pxa6-asqb) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/pxa6-asqb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/pxa6-asqb/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | pxa6-asqb |
| Name | NNDSS - Table IV. Tuberculosis |
| Attribution | Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention |
| Category | NNDSS |
| Tags | 2014, mmwr, nndss, wonder, nedss, netss, tuberculosis, tb |
| Created | 2014-04-07T01:13:40Z |
| Publication Date | 2015-01-15T22:00:07Z |

## Description

NNDSS - Table IV. Tuberculosis - 2014.This Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States will exclude counts from US territories.  Footnote:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable    Cum: Cumulative year-to-date counts.    Min: Minimum.    Max: Maximum. * Case counts for reporting year 2013 and 2014 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf Updated reports to the National Center for HIV/AIDS, Viral Hepatitis, STD and TB Prevention. Data for TB are displayed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                         | Data Type | Render Type |
| ======== | ============== | ========================================= | ============================================ | ========= | =========== |
| Yes      | series tag     | reporting_area                            | Reporting area                               | text      | text        |
| No       |                | mmwr_year                                 | MMWR Year                                    | number    | number      |
| No       |                | mmwr_quarter                              | MMWR Quarter                                 | number    | number      |
| No       |                | tuberculosis_current_quarter              | Tuberculosis*, Current quarter               | number    | number      |
| No       |                | tuberculosis_current_quarter_flag         | Tuberculosis*, Current quarter, flag         | text      | text        |
| Yes      | numeric metric | tuberculosis_previous_4_quarters_min      | Tuberculosis*, Previous 4 quarters Min       | number    | number      |
| No       |                | tuberculosis_previous_4_quarters_min_flag | Tuberculosis*, Previous 4 quarters Min, flag | text      | text        |
| Yes      | numeric metric | tuberculosis_previous_4_quarters_max      | Tuberculosis*, Previous 4 quarters Max       | number    | number      |
| No       |                | tuberculosis_previous_4_quarters_max_flag | Tuberculosis*, Previous 4 quarters Max, flag | text      | text        |
| Yes      | numeric metric | tuberculosis_cum_2014                     | Tuberculosis*, Cum 2014                      | number    | number      |
| No       |                | tuberculosis_cum_2014_flag                | Tuberculosis*, Cum 2014, flag                | text      | text        |
| Yes      | numeric metric | tuberculosis_cum_2013                     | Tuberculosis*, Cum 2013                      | number    | number      |
| No       |                | tuberculosis_cum_2013_flag                | Tuberculosis*, Cum 2013, flag                | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = tuberculosis_current_quarter,tuberculosis_current_quarter_flag,tuberculosis_previous_4_quarters_min_flag,tuberculosis_previous_4_quarters_max_flag,tuberculosis_cum_2014_flag,tuberculosis_cum_2013_flag,mmwr_year,mmwr_quarter
```

## Data Commands

```ls
series e:pxa6-asqb d:2014-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:tuberculosis_previous_4_quarters_max=2784 m:tuberculosis_previous_4_quarters_min=1157 m:tuberculosis_cum_2013=1259 m:tuberculosis_cum_2014=1157

series e:pxa6-asqb d:2014-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:tuberculosis_previous_4_quarters_max=89 m:tuberculosis_previous_4_quarters_min=46 m:tuberculosis_cum_2013=42 m:tuberculosis_cum_2014=46

series e:pxa6-asqb d:2014-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:tuberculosis_previous_4_quarters_max=399 m:tuberculosis_previous_4_quarters_min=205 m:tuberculosis_cum_2013=200 m:tuberculosis_cum_2014=205
```

## Meta Commands

```ls
metric m:tuberculosis_previous_4_quarters_min p:integer l:"Tuberculosis*, Previous 4 quarters Min" t:dataTypeName=number

metric m:tuberculosis_previous_4_quarters_max p:integer l:"Tuberculosis*, Previous 4 quarters Max" t:dataTypeName=number

metric m:tuberculosis_cum_2014 p:integer l:"Tuberculosis*, Cum 2014" t:dataTypeName=number

metric m:tuberculosis_cum_2013 p:integer l:"Tuberculosis*, Cum 2013" t:dataTypeName=number

entity e:pxa6-asqb l:"NNDSS - Table IV. Tuberculosis" t:attribution="Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention" t:url=https://data.cdc.gov/api/views/pxa6-asqb

property e:pxa6-asqb t:meta.view v:id=pxa6-asqb v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table IV. Tuberculosis" v:attribution="Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention"

property e:pxa6-asqb t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:pxa6-asqb t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:pxa6-asqb t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_quarter | tuberculosis_current_quarter | tuberculosis_current_quarter_flag | tuberculosis_previous_4_quarters_min | tuberculosis_previous_4_quarters_min_flag | tuberculosis_previous_4_quarters_max | tuberculosis_previous_4_quarters_max_flag | tuberculosis_cum_2014 | tuberculosis_cum_2014_flag | tuberculosis_cum_2013 | tuberculosis_cum_2013_flag | 
| ============== | ========= | ============ | ============================ | ================================= | ==================================== | ========================================= | ==================================== | ========================================= | ===================== | ========================== | ===================== | ========================== | 
| UNITED STATES  | 2014      | 1            | 1157                         |                                   | 1157                                 |                                           | 2784                                 |                                           | 1157                  |                            | 1259                  |                            | 
| NEW ENGLAND    | 2014      | 1            | 46                           |                                   | 46                                   |                                           | 89                                   |                                           | 46                    |                            | 42                    |                            | 
| MID. ATLANTIC  | 2014      | 1            | 205                          |                                   | 205                                  |                                           | 399                                  |                                           | 205                   |                            | 200                   |                            | 
| E.N. CENTRAL   | 2014      | 1            | 89                           |                                   | 89                                   |                                           | 229                                  |                                           | 89                    |                            | 99                    |                            | 
| W.N. CENTRAL   | 2014      | 1            | 36                           |                                   | 36                                   |                                           | 110                                  |                                           | 36                    |                            | 46                    |                            | 
| S. ATLANTIC    | 2014      | 1            | 231                          |                                   | 231                                  |                                           | 519                                  |                                           | 231                   |                            | 230                   |                            | 
| E.S. CENTRAL   | 2014      | 1            | 84                           |                                   | 84                                   |                                           | 105                                  |                                           | 84                    |                            | 59                    |                            | 
| W.S. CENTRAL   | 2014      | 1            | 175                          |                                   | 175                                  |                                           | 402                                  |                                           | 175                   |                            | 226                   |                            | 
| MOUNTAIN       | 2014      | 1            | 21                           |                                   | 21                                   |                                           | 168                                  |                                           | 21                    |                            | 31                    |                            | 
| PACIFIC        | 2014      | 1            | 270                          |                                   | 270                                  |                                           | 775                                  |                                           | 270                   |                            | 326                   |                            | 
```