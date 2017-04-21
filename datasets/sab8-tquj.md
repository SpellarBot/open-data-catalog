# Importing Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/importing-plants-623d7) |
| Metadata | [Link](https://data.oregon.gov/api/views/sab8-tquj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/sab8-tquj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/sab8-tquj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | sab8-tquj |
| Name | Importing Plants |
| Tags | oregon quarantines, oregon regulations, shipping regulations, oregon import regulations, oregon import quarantines |
| Created | 2014-05-21T21:42:21Z |
| Publication Date | 2014-08-13T15:00:27Z |

## Description

Regulations for importing plants into Oregon

## Columns

```ls
| Included | Schema Type | Field Name             | Name             | Data Type | Render Type |
| ======== | =========== | ====================== | ================ | ========= | =========== |
| No       | time        | :updated_at            | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | plant_part             | Plant            | text      | text        |
| Yes      | series tag  | area_under_quarantine  | Quarantine Area  | text      | text        |
| Yes      | series tag  | regulation             | Regulation       | text      | text        |
| Yes      | series tag  | requirements           | Requirements     | text      | text        |
| Yes      | series tag  | additional_information | More information | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:sab8-tquj d:2014-05-21T14:42:23.000Z t:plant_part="Ash (Fraxinus spp.), birch (Betula spp.), elm (Ulmus spp.), hackberry (Celtis spp.), horse chestnut (Aesculus spp.), maple (Acer spp.), mimosa (Albizia spp.), mountain ash (Sorbus spp.), Populus, sycamore (Platanus spp.)), willow (Salix spp.)" t:regulation="Asian longhorned beetle" t:area_under_quarantine="Parts of IL, NJ and NY; ask ODA for details" t:requirements=Prohibited t:additional_information="Federal Quarantine" m:row_number.sab8-tquj=1

series e:sab8-tquj d:2014-05-21T14:42:23.000Z t:plant_part="Blueberry plants (Vaccinium spp.) bareroot exempt, blueberry fruit" t:regulation="Blueberry  maggot" t:area_under_quarantine="All of United States east of and including ND, SD, NE, KS, OK, TX" t:requirements=Prohibited t:additional_information="Plants must be certified washed bareroot; Plants exempt from regulation when free from soil and growing media; clumps of soil or growing media larger than 1/2 inch diameter will be cause for rejection." m:row_number.sab8-tquj=2

series e:sab8-tquj d:2014-05-21T14:42:23.000Z t:plant_part="European corn borer host plants: corn, beets, celery, endive, swiss chard, rhubarb, aster, Chrysanthemum, calendula, cosmos, hollyhock, marigold, zinnia, Japanese hops, dahlias (except tubers without stems) and gladiolus (except corms without stems), and pepper fruits." t:regulation="European corn borer" t:area_under_quarantine="All of United States except: AK, AZ, CA, HI, ID, NV, NM, UT, WA" t:requirements=Certificate m:row_number.sab8-tquj=3
```

## Meta Commands

```ls
metric m:row_number.sab8-tquj p:long l:"Row Number"

entity e:sab8-tquj l:"Importing Plants" t:url=https://data.oregon.gov/api/views/sab8-tquj

property e:sab8-tquj t:meta.view v:id=sab8-tquj v:averageRating=0 v:name="Importing Plants"

property e:sab8-tquj t:meta.view.owner v:id=sjvb-xabp v:screenName="lisa rehms" v:displayName="lisa rehms"

property e:sab8-tquj t:meta.view.tableauthor v:id=sjvb-xabp v:screenName="lisa rehms" v:roleName=editor v:displayName="lisa rehms"
```

## Top Records

```ls
| :updated_at | plant_part                                                                                                                                                                                                                                                                    | area_under_quarantine                                                                                                                                          | regulation                                                   | requirements                                                | additional_information                                                                                                                                                                                                                                                                 | 
| =========== | ============================================================================================================================================================================================================================================================================= | ============================================================================================================================================================== | ============================================================ | =========================================================== | ====================================================================================================================================================================================================================================================================================== | 
| 1400683343  | Ash (Fraxinus spp.), birch (Betula spp.), elm (Ulmus spp.), hackberry (Celtis spp.), horse chestnut (Aesculus spp.), maple (Acer spp.), mimosa (Albizia spp.), mountain ash (Sorbus spp.), Populus, sycamore (Platanus spp.)), willow (Salix spp.)                            | Parts of IL, NJ and NY; ask ODA for details                                                                                                                    | Asian longhorned beetle                                      | Prohibited                                                  | Federal Quarantine                                                                                                                                                                                                                                                                     | 
| 1400683343  | Blueberry plants (Vaccinium spp.) bareroot exempt, blueberry fruit                                                                                                                                                                                                            | All of United States east of and including ND, SD, NE, KS, OK, TX                                                                                              | Blueberry maggot                                             | Prohibited                                                  | Plants must be certified washed bareroot; Plants exempt from regulation when free from soil and growing media; clumps of soil or growing media larger than 1/2 inch diameter will be cause for rejection.                                                                              | 
| 1400683343  | European corn borer host plants: corn, beets, celery, endive, swiss chard, rhubarb, aster, Chrysanthemum, calendula, cosmos, hollyhock, marigold, zinnia, Japanese hops, dahlias (except tubers without stems) and gladiolus (except corms without stems), and pepper fruits. | All of United States except: AK, AZ, CA, HI, ID, NV, NM, UT, WA                                                                                                | European corn borer                                          | Certificate                                                 |                                                                                                                                                                                                                                                                                        | 
| 1400683343  | Hop plants (Humulus lapulus) and all parts, except dried cones                                                                                                                                                                                                                | All of United States except ID and WA                                                                                                                          | Powdery mildew of hops                                       | Prohibited                                                  | From ID and WA: certification from powdery mildew is required. Plants prohibited from other states.                                                                                                                                                                                    | 
| 1407915509  | All plants; plant parts including logs, wood chips, and pulpwood                                                                                                                                                                                                              | CT, DE, DC, IN, KY, ME, MD, MA, MI, MN, NC, NH, NJ, OH, PA, RI, TN, VT, VA, WI, WV                                                                             | Gypsy moth                                                   | Certificate; Notification to ODA                            | Federal Quarantine; plant material certified free from gypsy moth.                                                                                                                                                                                                                     | 
| 1407915512  | All plants; in growing media, sod, soil, hay, straw                                                                                                                                                                                                                           | AL, AR, CA, FL, GA, LA, MS, NC, NM, OK, PR, SC, TN, TX                                                                                                         | Imported fire ant                                            | Certificate; Notification to ODA                            | Federal Quarantine; plant material certified free from imported fire ant.                                                                                                                                                                                                              | 
| 1407915523  | Blueberry plants (Vaccinium spp..)                                                                                                                                                                                                                                            | All of United States and all countries                                                                                                                         | Blueberry scorch virus                                       | Certificate; Notification to ODA                            | Blueberry plants must meet one of the following conditions to be certified: originate in a pest free area, laboratory tested and found free of blueberry scorch virus, or grown in a insect proof greenhouse originating from mother plants that were tested free of blueberry scorch. | 
| 1407915528  | Grape (Vitis spp.) all parts                                                                                                                                                                                                                                                  | All of United States                                                                                                                                           | Grape quarantine: grape pests and diseases                   | Certificate; Notification to ODA                            | Plants certified free of pests and diseases. No field grown stock.                                                                                                                                                                                                                     | 
| 1407915576  | Grape (Vitis spp.) plants                                                                                                                                                                                                                                                     | AL, AR, CA, FL, GA, LA, MS, MO, NC, SC, TX, OR- any infested site; Mexico                                                                                      | Glassy-winged sharp-shooter (a leafhopper); Pierce's disease | Certificate; Notification to ODA                            | Plants grown under compliance agreement or treated for sharpshooter. Plants tested for Pierce's disease.                                                                                                                                                                               | 
| 1407915582  | All plants; in growing media, sod, bulbs, rhizomes, crowns; all plant parts, soil, humus, compost, manure                                                                                                                                                                     | AL, AR, CO, CT, DE, GA, IL, IN, IA, KS, KY, ME, MD, MA, MI, MN, MS, MO, NE, NH, NJ, NM, NY, NC, OH, OK, PA, RI, SC, TN, TX, VT, VA, WV, WI, DC; Canada: ON, QB | Japanese beetle                                              | Certificate; Pre notification from shipper to ODA required. | Federal Quarantine; plants in soil or growing media must be certified as fumigated or otherwise treated; washed bareroot plants, bulbs, etc. require certification.                                                                                                                    | 
```