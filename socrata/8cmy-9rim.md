# Greenhouse Gas Emissions Estimates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/greenhouse-gas-emissions-estimates) |
| Metadata | [Link](https://data.maryland.gov/api/views/8cmy-9rim) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8cmy-9rim/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8cmy-9rim/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8cmy-9rim |
| Name | Greenhouse Gas Emissions Estimates |
| Attribution | Maryland Energy Administration |
| Category | Energy and Environment |
| Tags | greenhouse gas, emissions, carbon, governor's office of performance improvement, pollution |
| Created | 2012-10-18T16:04:30Z |
| Publication Date | 2015-09-09T16:04:03Z |

## Description

The State conducted a detailed inventory of greenhouse gasses in 2006 and 2011. The 2014 detailed inventory will be released at the end of 2015.  Estimated actual emissions for those two years represent the results of these inventories.  

Projected emissions under a "business as usual" scenario were estimated based on the 2006 inventory, projected forward using a protocol set forth by the Environmental Protection Agency.  The business as usual estimates were revised due to changes in the economy since the protocol was set out.  It is important to bear in mind that a BAU projected emissions inventory is a forecast that may, or may not, prove to be an entirely accurate predictor of future emissions. 

Annual actual emission estimates were calculated for the intervening years from 2006 through 2011 by utilizing three surrogates as indicators of emissions (energy, transportation and residential, commercial and industrial fuel combustion).  These three sectors account for over 85 percent of greenhouse gas emissions in Maryland.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| Yes      | time           | year                                       | Year                                       | number    | text        |
| Yes      | numeric metric | estimated_actual_emissions                 | Estimated Actual Emissions                 | number    | number      |
| Yes      | numeric metric | projected_emissions_business_as_usual      | Projected Emissions - Business As Usual    | number    | number      |
| Yes      | numeric metric | goal                                       | 2020 Goal                                  | number    | number      |
| Yes      | numeric metric | projected_progress_under_current_programs  | Projected Progress under Current Programs  | number    | number      |
| Yes      | numeric metric | projected_progress_under_enhanced_programs | Projected Progress under Enhanced Programs | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8cmy-9rim d:2006-01-01T00:00:00.000Z m:estimated_actual_emissions=107229536.5 m:projected_emissions_business_as_usual=107229536.6 m:goal=80400000

series e:8cmy-9rim d:2007-01-01T00:00:00.000Z m:estimated_actual_emissions=109120613.2 m:projected_emissions_business_as_usual=109087677.6 m:goal=80400000

series e:8cmy-9rim d:2008-01-01T00:00:00.000Z m:estimated_actual_emissions=107167938.9 m:projected_emissions_business_as_usual=110944370.5 m:goal=80400000
```

## Meta Commands

```ls
metric m:estimated_actual_emissions p:double l:"Estimated Actual Emissions" t:dataTypeName=number

metric m:projected_emissions_business_as_usual p:double l:"Projected Emissions - Business As Usual" t:dataTypeName=number

metric m:goal p:integer l:"2020 Goal" t:dataTypeName=number

metric m:projected_progress_under_current_programs p:integer l:"Projected Progress under Current Programs" d:"These are the emissions estimates through 2020 given the reductions expected from the programs currently in place as of the 2013 release of the Greenhouse Gas Reduction Plan." t:dataTypeName=number

metric m:projected_progress_under_enhanced_programs p:integer l:"Projected Progress under Enhanced Programs" d:"These are the emissions estimates through 2020 given the reductions that would occur under the enhanced programs listed in the Greenhouse Gas Reduction Plan." t:dataTypeName=number

entity e:8cmy-9rim l:"Greenhouse Gas Emissions Estimates" t:attribution="Maryland Energy Administration" t:url=https://data.maryland.gov/api/views/8cmy-9rim

property e:8cmy-9rim t:meta.view v:id=8cmy-9rim v:category="Energy and Environment" v:attributionLink=http://energy.maryland.gov/ v:averageRating=0 v:name="Greenhouse Gas Emissions Estimates" v:attribution="Maryland Energy Administration"

property e:8cmy-9rim t:meta.view.owner v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:displayName="Kristen Ahearn"

property e:8cmy-9rim t:meta.view.tableauthor v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:roleName=publisher v:displayName="Kristen Ahearn"
```

## Top Records

```ls
| year | estimated_actual_emissions | projected_emissions_business_as_usual | goal     | projected_progress_under_current_programs | projected_progress_under_enhanced_programs | 
| ==== | ========================== | ===================================== | ======== | ========================================= | ========================================== | 
| 2006 | 107229536.5                | 107229536.6                           | 80400000 |                                           |                                            | 
| 2007 | 109120613.2                | 109087677.6                           | 80400000 |                                           |                                            | 
| 2008 | 107167938.9                | 110944370.5                           | 80400000 |                                           |                                            | 
| 2010 | 100126383.9                | 115750950.4                           | 80400000 |                                           |                                            | 
| 2009 | 98489353.1                 | 113828287.4                           | 80400000 |                                           |                                            | 
| 2011 | 99283829.7                 | 117655483.4                           | 80400000 |                                           |                                            | 
| 2014 |                            | 123453222.4                           | 80400000 | 96107500                                  | 93762500                                   | 
| 2015 |                            | 125263220.5                           | 80400000 | 95021250                                  | 91503750                                   | 
| 2016 |                            | 127380964.8                           | 80400000 | 93935000                                  | 89245000                                   | 
| 2017 |                            | 129350013.6                           | 80400000 | 92848750                                  | 86986250                                   | 
```