# MDTA Structurally Deficient Bridges

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mdta-structurally-deficient-bridges-57cb3) |
| Metadata | [Link](https://data.maryland.gov/api/views/g2ds-rrjk) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/g2ds-rrjk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/g2ds-rrjk/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | g2ds-rrjk |
| Name | MDTA Structurally Deficient Bridges |
| Attribution | Maryland Transportation Authority |
| Category | Public Safety |
| Tags | bridges, structurally deficient, mdta, transportation |
| Created | 2013-02-12T14:45:37Z |
| Publication Date | 2015-02-26T14:47:51Z |

## Description

This measure provides the number of structurally deficient bridges and number of total bridges owned by MDTA. The latitude and longitude is also provided for the structurally deficient bridges. 

The MDTA's Annual Inspection Report consists of a walk/climb through physical inspection resulting in a thorough hands-on inspection of all structures, roadways, tunnels and tunnel ventilation buildings (including the mechanical and electrical systems), drainage structures, toll plazas, Variable Message Signs (VMS), incident detection equipment housings and structures, retaining walls, noise barriers, traffic and safety equipment, and truck weigh scales under the jurisdiction of the Maryland Transportation Authority at the following facilities: I-95 (John F. Kennedy Memorial Highway), I-895 (Baltimore Harbor Tunnel Thruway), Seagirt Marine Terminal, Thomas J. Hatem Memorial Bridge, I-395 and I-95 in Baltimore City (Fort McHenry Tunnel), I-695 (Francis Scott Key Bridge), Harry W. Nice Memorial Bridge, the Bay Bridge (twin structures) and the Intercounty Connector (ICC/MD200). The annual inspection process includes the development of a Structural Inventory and Appraisal (SI&A) assessment that is submitted to the Federal Highway Administration each April for the preceding calendar year.The data for this measure is collected from the SI&A assessment that is performed yearly by the MDTA's facilities inspection consultant. 

 The MDTA continued to be successful in having 100 percent of its bridges fully operational and functioning (no weight restrictions), allowing all emergency vehicles, school buses, vehicles serving the economy of an area, and legally loaded vehicles to safely traverse. Bridges are considered structurally deficient if significant load carrying elements are found to be in a poor (or worse) condition due to deterioration and/or damage, or have a low weight restriction.  The fact that a bridge is structurally deficient does not imply that it is unsafe.

Data submitted for the CY are provided in February, but the data is not provided to FHWA until April. In some cases, the number could change if repairs are made to a structurally deficient bridge.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| Yes      | time        | calendar_year | Calendar Year | number    | text        |
| Yes      | series tag  | bridge_name   | Bridge Name   | text      | text        |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:g2ds-rrjk l:"MDTA Structurally Deficient Bridges" t:attribution="Maryland Transportation Authority" t:url=https://data.maryland.gov/api/views/g2ds-rrjk

property e:g2ds-rrjk t:meta.view v:id=g2ds-rrjk v:category="Public Safety" v:averageRating=0 v:name="MDTA Structurally Deficient Bridges" v:attribution="Maryland Transportation Authority"

property e:g2ds-rrjk t:meta.view.owner v:id=5x9h-2zmw v:screenName="Sarah Clifford" v:displayName="Sarah Clifford"

property e:g2ds-rrjk t:meta.view.tableauthor v:id=5x9h-2zmw v:screenName="Sarah Clifford" v:roleName=publisher v:displayName="Sarah Clifford"
```

## Top Records

```ls
| calendar_year | bridge_name               | 
| ============= | ========================= | 
| 2011          | MD 43EB                   | 
| 2011          | I-895 over Patapsco Flats | 
| 2011          | K-Truss                   | 
| 2011          | Canton Viaduct            | 
| 2012          | Canton Viaduct            | 
| 2011          | MD 43WB                   | 
| 2013          | Canton Viaduct            | 
| 2013          | NB I-895 over Transway    | 
| 2014          | Canton Viaduct            | 
```