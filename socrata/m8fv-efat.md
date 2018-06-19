# Oregon Weeds Biocontrol Guide

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-weeds-biocontrol-guide-23b07) |
| Metadata | [Link](https://data.oregon.gov/api/views/m8fv-efat) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/m8fv-efat/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/m8fv-efat/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | m8fv-efat |
| Name | Oregon Weeds Biocontrol Guide |
| Attribution | Oregon Department of Agriculture |
| Category | Natural Resources |
| Tags | oregon, oda, agriculture, weeds, biocontrol |
| Created | 2013-01-10T00:01:54Z |
| Publication Date | 2014-08-21T16:12:22Z |

## Description

Biocontrol planning guide by target weed and biocontrol agent

## Columns

```ls
| Included | Schema Type    | Field Name        | Name               | Data Type | Render Type |
| ======== | ============== | ================= | ================== | ========= | =========== |
| No       | time           | :updated_at       | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | agent_target      | Agent Target       | url       | url         |
| Yes      | series tag     | agent_name        | Agent name         | text      | text        |
| Yes      | series tag     | agent_image       | Agent Image        | photo     | photo       |
| Yes      | series tag     | role              | Role               | text      | text        |
| Yes      | numeric metric | releasedinoregon  | Released in OR     | number    | text        |
| Yes      | series tag     | agentdistribution | Agent distribution | text      | text        |
| Yes      | series tag     | attackrate        | Attack rate        | text      | text        |
| Yes      | series tag     | control           | Control            | text      | text        |
| Yes      | series tag     | collectability    | Collectability     | text      | text        |
| Yes      | series tag     | releasequantity   | Release quantity   | text      | text        |
| Yes      | series tag     | timing            | Timing             | text      | text        |
| Yes      | series tag     | technique         | Technique          | text      | text        |
| Yes      | series tag     | lifestage         | Life stage         | text      | text        |
| Yes      | series tag     | comments          | Comments           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:m8fv-efat d:2014-08-18T15:37:21.000Z t:technique="Sweep net" t:releasequantity=500 t:control=Excellent t:collectability=Mass t:agentdistribution=Widespread t:attackrate=Heavy t:lifestage=Adult t:role="root/defoliating flea beetle" t:timing=Jun-Jul t:agent_name="Aphthona cyparissiae" t:comments="Often present in species complex" m:releasedinoregon=1989

series e:m8fv-efat d:2014-08-18T15:39:42.000Z t:technique="Sweep net" t:releasequantity=500 t:control=Excellent t:collectability=Mass t:agentdistribution=Widespread t:attackrate=Heavy t:lifestage=Adult t:role="root/defoliating flea beetle" t:timing=Jun-Jul t:agent_name="Aphthona nigriscutis" t:comments="Often present in species complex, better for drier areas." m:releasedinoregon=1989

series e:m8fv-efat d:2014-08-18T15:39:52.000Z t:technique="Sweep net" t:releasequantity=500 t:control=Excellent t:collectability=Mass t:agentdistribution=Widespread t:attackrate=Heavy t:lifestage=Adult t:role="root/defoliating flea beetle" t:timing=Jun-Jul t:agent_name="Aphthona lacertosa" t:comments="Often present in species complex, better for wetter areas." m:releasedinoregon=1993
```

## Meta Commands

```ls
metric m:releasedinoregon p:integer l:"Released in OR" t:dataTypeName=number

entity e:m8fv-efat l:"Oregon Weeds Biocontrol Guide" t:attribution="Oregon Department of Agriculture" t:url=https://data.oregon.gov/api/views/m8fv-efat

property e:m8fv-efat t:meta.view v:id=m8fv-efat v:category="Natural Resources" v:attributionLink=http://oregon.gov/ODA v:averageRating=0 v:name="Oregon Weeds Biocontrol Guide" v:attribution="Oregon Department of Agriculture"

property e:m8fv-efat t:meta.view.owner v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"

property e:m8fv-efat t:meta.view.tableauthor v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"
```

## Top Records

```ls
| :updated_at | agent_target                                    | agent_name               | agent_image | role                         | releasedinoregon | agentdistribution | attackrate | control   | collectability | releasequantity | timing  | technique                   | lifestage  | comments                                                                    | 
| =========== | =============================================== | ======================== | =========== | ============================ | ================ | ================= | ========== | ========= | ============== | =============== | ======= | =========================== | ========== | =========================================================================== | 
| 1408376241  | [null, Leafy spurge (Euphorbia esula)]          | Aphthona cyparissiae     |             | root/defoliating flea beetle | 1989             | Widespread        | Heavy      | Excellent | Mass           | 500             | Jun-Jul | Sweep net                   | Adult      | Often present in species complex                                            | 
| 1408376382  | [null, Leafy spurge (Euphorbia esula)]          | Aphthona nigriscutis     |             | root/defoliating flea beetle | 1989             | Widespread        | Heavy      | Excellent | Mass           | 500             | Jun-Jul | Sweep net                   | Adult      | Often present in species complex, better for drier areas.                   | 
| 1408376392  | [null, Leafy spurge (Euphorbia esula)]          | Aphthona lacertosa       |             | root/defoliating flea beetle | 1993             | Widespread        | Heavy      | Excellent | Mass           | 500             | Jun-Jul | Sweep net                   | Adult      | Often present in species complex, better for wetter areas.                  | 
| 1408376722  | [null, dalmatian toadflax (Linaria dalmatica)]  | Metzneria paucipunctella |             | seed head moth               | 1981             | Limited           | Light      | Poor      | Limited        | 200             | March   | Harvest infested seed heads | Larva/pupa | Occurs in Hood River and Douglas Counties, heavily parasitized.             | 
| 1408377025  | [null, Italian thistle (Carduus pycnocephalus)] | Rhinocyllus conicus      |             | seed head weevil             | 1979             | Widespread        | Heavy      | Excellent | Mass*          | 100*            | April*  | Sweep net/racquet*          | Adult*     | * Not recommended, attacks native thistles, interstate shipment prohibited. | 
| 1408382289  | [null, mediterranean sage (Salvia aethiopis)]   | Phrydiuchus tau          |             | crown/root fly               | 1991             | Unknown           | Unknown    | Unknown   | Limited        | 100             | July    | Harvest infested plants     | Pupa       | Experimental, not established on musk thistle.                              | 
| 1408383239  | [null, leafy spurge (Euphorbia esula)]          | Aphthona czwalinae       |             | root/defoliating flea beetle | 1993             | Widespread        | Heavy      | Excellent | Mass           | 500             | Jun-Jul | Sweep net                   | Adult      | Less common, difficult to tell from and usually mixed with A. lacertosa.    | 
| 1408383259  | [null, leafy spurge (Euphorbia esula)]          | Aphthona flava           |             | root/defoliating flea beetle | 1989             | Widespread        | Heavy      | Excellent | Mass           | 500             | Jun-Jul | Sweep net                   | Adult      | Less common in species complex                                              | 
| 1408383323  | [null, Gorse (Ulex europaeus)]                  | Tetranychus lintearius   |             | spider mite                  | 1994             | Widespread        | Light      | Poor      | Limited        | 500             | Aug-Sep | Harvest infested plants     | All        | Limited by predatory mite, ineffective agent.                               | 
| 1408383398  | [null, leafy spurge (Euphorbia esula)]          | Oberea erythrocephala    |             | root/stem boring beetle      | 1982             | Widespread        | Heavy      | Good      | Mass           | 100             | July    | Sweep net                   | Adult      | Look for girdled upper quarter of plants.                                   | 
```