# Oregon Weeds Biocontrol Guide-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-weeds-biocontrol-guide-2-adb52) |
| Metadata | [Link](https://data.oregon.gov/api/views/kiwy-fuw2) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kiwy-fuw2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kiwy-fuw2/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kiwy-fuw2 |
| Name | Oregon Weeds Biocontrol Guide-2 |
| Attribution | ODA |
| Category | Natural Resources |
| Tags | biological control, biological agent, oregon bio control |
| Created | 2014-08-22T22:01:43Z |
| Publication Date | 2016-08-05T22:18:39Z |

## Description

biological control agents of Oregon and their current status and release information.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | agent_target       | Agent Target       | url       | url         |
| Yes      | series tag     | biocontrol_agent   | Biocontrol agent   | url       | url         |
| Yes      | series tag     | agent_name         | Agent name         | text      | text        |
| Yes      | series tag     | agent_image_2      | Agent image        | photo     | photo       |
| Yes      | series tag     | profile_pdf        | Profile PDF        | document  | document    |
| Yes      | series tag     | role               | Role               | text      | text        |
| Yes      | numeric metric | released_in_or     | Released in OR     | number    | text        |
| Yes      | series tag     | agent_distribution | Agent distribution | text      | text        |
| Yes      | series tag     | attack_rate        | Attack rate        | text      | text        |
| Yes      | series tag     | control            | Control            | text      | text        |
| Yes      | series tag     | collectability     | Collectability     | text      | text        |
| Yes      | series tag     | release_quantity   | Release quantity   | text      | text        |
| Yes      | series tag     | timing             | Timing             | text      | text        |
| Yes      | series tag     | technique          | Technique          | text      | text        |
| Yes      | series tag     | life_stage         | Life stage         | text      | text        |
| Yes      | series tag     | comments           | Comments           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kiwy-fuw2 d:2016-04-08T15:30:50.000Z t:technique="Sweep net/racquet" t:control=Excellent t:agent_image_2=9Kq5zSpzSFx-V1FnePKo3Wve_adCaOGevQN-Phk6WS8 t:agent_distribution=Widespread t:collectability=Mass t:agent_target=http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/diffuseknapweedProfile.pdf t:profile_pdf.filename=knapweeds_BAFA.pdf t:attack_rate=Heavy t:life_stage=Adult t:profile_pdf.file_id=bb975cfe-e994-415b-b845-d1a94c52ac16 t:profile_pdf.size=637102 t:role="seed head weevil" t:release_quantity=100 t:timing=June t:agent_name="Bangasternus fausti" t:profile_pdf.content_type="application/pdf; charset=binary" t:comments="Best collecting at bud stage." m:released_in_or=1989

series e:kiwy-fuw2 d:2016-04-08T15:49:49.000Z t:technique="Handpick larvae" t:control=Fair t:agent_image_2=nPR4UJGcK7gDODenr8tlr6oH1mQM5N7PnatFxNAtZQs t:agent_distribution=Limited t:collectability=Limited t:agent_target=http://www.oregon.gov/ODA/shared/Documents/Publications/Weeds/DalmatianToadflaxProfile.pdf t:profile_pdf.filename=Toadflax_CALU.pdf t:attack_rate=Light t:life_stage=Larva t:profile_pdf.file_id=2e1f1372-c5c9-482f-b313-8556ed405463 t:profile_pdf.size=655139 t:role="defoliating moth" t:release_quantity=100-200 t:timing=Jun-Jul t:agent_name="Calophasia lunula" t:profile_pdf.content_type="application/pdf; charset=binary" t:comments="Occurs in Wallowa Co., release 1-2 larvae per plant." m:released_in_or=1982

series e:kiwy-fuw2 d:2016-04-09T10:53:06.000Z t:technique="Harvest infested seed heads" t:control=Poor t:agent_image_2=0imV_n4D-rLhiY3qVMxblSSjZoSlo-VhxcuePstzRtg t:agent_distribution=Limited t:collectability=Limited t:agent_target=https://data.oregon.gov/Natural-Resources/Oregon-Weeds-Biocontrol-Guide-2/8kq9-pra6 t:profile_pdf.filename=knapweed_MEPA.pdf t:attack_rate=Light t:life_stage=Larva/pupa t:profile_pdf.file_id=73a7335d-99fc-4a41-8b85-39bc8ee96fda t:profile_pdf.size=710181 t:role="seed head moth" t:release_quantity=200 t:timing=March t:agent_name="Metzneria paucipunctella" t:profile_pdf.content_type="application/pdf; charset=binary" t:comments="Experimental, recovered in one county." m:released_in_or=1981
```

## Meta Commands

```ls
metric m:released_in_or p:integer l:"Released in OR" t:dataTypeName=number

entity e:kiwy-fuw2 l:"Oregon Weeds Biocontrol Guide-2" t:attribution=ODA t:url=https://data.oregon.gov/api/views/kiwy-fuw2

property e:kiwy-fuw2 t:meta.view v:id=kiwy-fuw2 v:category="Natural Resources" v:averageRating=0 v:name="Oregon Weeds Biocontrol Guide-2" v:attribution=ODA

property e:kiwy-fuw2 t:meta.view.owner v:id=mxzg-tghe v:profileImageUrlMedium=/api/users/mxzg-tghe/profile_images/THUMB v:profileImageUrlLarge=/api/users/mxzg-tghe/profile_images/LARGE v:screenName="Patricia Rasmussen" v:profileImageUrlSmall=/api/users/mxzg-tghe/profile_images/TINY v:displayName="Patricia Rasmussen"

property e:kiwy-fuw2 t:meta.view.tableauthor v:id=mxzg-tghe v:profileImageUrlMedium=/api/users/mxzg-tghe/profile_images/THUMB v:profileImageUrlLarge=/api/users/mxzg-tghe/profile_images/LARGE v:screenName="Patricia Rasmussen" v:profileImageUrlSmall=/api/users/mxzg-tghe/profile_images/TINY v:roleName=editor v:displayName="Patricia Rasmussen"
```

## Top Records

```ls
| :updated_at | agent_target                                                                                                                         | biocontrol_agent | agent_name               | agent_image_2                               | profile_pdf                                                                                           | role                         | released_in_or | agent_distribution | attack_rate | control   | collectability | release_quantity | timing  | technique                   | life_stage | comments                                                                                     | 
| =========== | ==================================================================================================================================== | ================ | ======================== | =========================================== | ===================================================================================================== | ============================ | ============== | ================== | =========== | ========= | ============== | ================ | ======= | =========================== | ========== | ============================================================================================ | 
| 1460129450  | [http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/diffuseknapweedProfile.pdf, diffuse knapweed (Centaurea diffusa)]     | [null, null]     | Bangasternus fausti      | 9Kq5zSpzSFx-V1FnePKo3Wve_adCaOGevQN-Phk6WS8 | [application/pdf; charset=binary, bb975cfe-e994-415b-b845-d1a94c52ac16, knapweeds_BAFA.pdf, 637102]   | seed head weevil             | 1989           | Widespread         | Heavy       | Excellent | Mass           | 100              | June    | Sweep net/racquet           | Adult      | Best collecting at bud stage.                                                                | 
| 1460130589  | [http://www.oregon.gov/ODA/shared/Documents/Publications/Weeds/DalmatianToadflaxProfile.pdf, dalmatian toadflax (Centaurea diffusa)] | [null, null]     | Calophasia lunula        | nPR4UJGcK7gDODenr8tlr6oH1mQM5N7PnatFxNAtZQs | [application/pdf; charset=binary, 2e1f1372-c5c9-482f-b313-8556ed405463, Toadflax_CALU.pdf, 655139]    | defoliating moth             | 1982           | Limited            | Light       | Fair      | Limited        | 100-200          | Jun-Jul | Handpick larvae             | Larva      | Occurs in Wallowa Co., release 1-2 larvae per plant.                                         | 
| 1460199186  | [https://data.oregon.gov/Natural-Resources/Oregon-Weeds-Biocontrol-Guide-2/8kq9-pra6, diffuse knapweed (Centaurea diffusa)]          | [null, null]     | Metzneria paucipunctella | 0imV_n4D-rLhiY3qVMxblSSjZoSlo-VhxcuePstzRtg | [application/pdf; charset=binary, 73a7335d-99fc-4a41-8b85-39bc8ee96fda, knapweed_MEPA.pdf, 710181]    | seed head moth               | 1981           | Limited            | Light       | Poor      | Limited        | 200              | March   | Harvest infested seed heads | Larva/pupa | Experimental, recovered in one county.                                                       | 
| 1460373608  | [http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/GorseProfile.pdf, gorse (Ulex europaeus)]                             | [null, null]     | Tetranychus lintearius   | wtExTHpIqw1axRwiXm8UD91rmnDWUdSDPSTIc52OdNc | [application/pdf; charset=binary, 09e5499b-9f68-4d7c-be5c-55fba1900c99, Gorse_TELI.pdf, 661995]       | spider mite                  | 1994           | Widespread         | Light       | Poor      | Limited        | 500              | Aug-Sep | Harvest infested plants     | All        | Limited by predatory mite, ineffective agent.                                                | 
| 1460374984  | [http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/ItalianThistleProfile.pdf, Italian thistle (Carduus pycnocephalus)]   | [null, null]     | Trichosirocalus horridus | 16e1e638-1e84-4589-bdff-104f0126d5a8        | [application/pdf; charset=binary, 520f27bb-b575-4afc-b6c5-5a8e8ad28eba, Thistles_TRHO.pdf, 667207]    | crown/root weevil            | 1994           | Widespread         | Heavy       | Good      | Mass           | 100              | Feb-May | Sweep net/beating sheet     | Adult      | Douglas County only                                                                          | 
| 1460375764  | [http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/diffuseknapweedProfile.pdf, diffuse knapweed (Centaurea diffusa)]     | [null, null]     | Urophora quadrifasciata  | tvlNG2Ta5M8tHB-60bJVJR6brxfnd1YvzjgNuZyYtAA | [application/pdf; charset=binary, 457f2c03-732c-4cf8-9ed8-1ad032227618, knapweed_URQU.pdf, 670496]    | seed head gall fly           | 1979           | Widespread         | Heavy       | Good      | Mass           | 100              | Jun-Aug | Aerial net                  | Adult      | No need for further redistribution. Gently sweep seed heads at bud stage, aspirate from net. | 
| 1460128180  | [http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/LeafySpurgeProfile.pdf, leafy spurge (Euphorbia esula)]               | [null, null]     | Aphthona czwalinae       | pFTRoIs6LKnWOQHnMAZv7TopJrrasxG8lDRtoYibdqU | [application/pdf; charset=binary, 59d3f1e1-cc64-48cf-b563-cc0ee94dd733, Leafyspurge_APCZ.pdf, 644458] | root/defoliating flea beetle | 1993           | Widespread         | Heavy       | Excellent | Mass           | 500              | Jun-Jul | Sweep net                   | Adult      | Less common, difficult to tell from and usually mixed with A. lacertosa.                     | 
| 1460128660  | [http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/LeafySpurgeProfile.pdf, leafy spurge (Euphorbia esula)]               | [null, null]     | Aphthona flava           | oSPiJ9M3I054GRgClXetOGjxwJIKcQUJNpwJyL6Y3mA | [application/pdf; charset=binary, 979ec5ca-98a2-4e01-8b22-6273e1662a14, Leafyspurge_APFL.pdf, 647910] | root/defoliating flea beetle | 1989           | Widespread         | Heavy       | Excellent | Mass           | 500              | Jun-Jul | Sweep net                   | Adult      | Less common in species complex                                                               | 
| 1460199217  | [http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/MeadowKnapweedProfile.pdf, meadow knapweed (Centaurea jacea x nigra)] | [null, null]     | Metzneria paucipunctella | 0imV_n4D-rLhiY3qVMxblSSjZoSlo-VhxcuePstzRtg | [application/pdf; charset=binary, f6e6234c-61b6-4241-9772-ce0246694091, knapweed_MEPA.pdf, 710181]    | seed head moth               | 1981           | Limited            | Light       | Poor      | Limited        | 200              | March   | Harvest infested seed heads | Larva/pupa | Occurs in Hood River and Douglas Counties, heavily parasitized.                              | 
| 1460199380  | [http://www.oregon.gov/oda/shared/Documents/Publications/Weeds/PuncturevineProfile.pdf, puncturevine (Tribulus terrestris)]          | [null, null]     | Microlarinus lareynii    | fddiQ-9g8thElBbEsfZBilAX-JfqBcX__hy7wmg7-ls | [application/pdf; charset=binary, ca29c3fb-2db0-4709-ab58-0c72aecb28e5, Pucturevine_MILA.pdf, 714072] | seed head weevil             | 1963           | Limited            | Light       | Fair      | Mass           | 100              | Aug-Sep | Aspirate                    | Adult      | Susceptible to cold winters, lift stems and aspirate adults when they move.                  | 
```