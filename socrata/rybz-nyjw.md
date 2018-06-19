# Accidental Drug Related Deaths 2012-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/accidental-drug-related-deaths-january-2012-sept-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/rybz-nyjw) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rybz-nyjw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rybz-nyjw/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rybz-nyjw |
| Name | Accidental Drug Related Deaths 2012-2016 |
| Attribution | Office of the Chief Medical Examiner |
| Category | Health and Human Services |
| Tags | death, drug, overdose, heroin, opioid, substance abuse |
| Created | 2015-10-09T16:18:38Z |
| Publication Date | 2017-02-27T17:56:11Z |

## Description

A listing of each accidental death associated with drug overdose in Connecticut from 2012 to 2015. A "Y" value under the different substance columns indicates that particular substance was detected.

Data are derived from an investigation by the Office of the Chief Medical Examiner which includes the toxicity report, death certificate, as well as a scene investigation.

The ?Morphine (Not Heroin)? values are related to the differences between how Morphine and Heroin are metabolized and therefor detected in the toxicity results. Heroin metabolizes to 6-MAM which then metabolizes to morphine.  6-MAM is unique to heroin, and has a short half-life (as does heroin itself). Thus, in some heroin deaths, the toxicity results will not indicate whether the morphine is from heroin or prescription morphine. In these cases the Medical Examiner may be able to determine the cause based on the scene investigation (such as  finding heroin needles). If they find prescription morphine at the scene it is certified as ?Morphine (not heroin).?  Therefor, the Cause of Death may indicate Morphine, but the Heroin or Morphine (Not Heroin) may not be indicated.

 ?Any Opioid? ? If the Medical Examiner cannot conclude whether it?s RX Morphine or heroin based morphine in the toxicity results, that column may be checked

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                  | Data Type     | Render Type   |
| ======== | ============== | ==================== | ===================== | ============= | ============= |
| Yes      | series tag     | casenumber           | CaseNumber            | text          | text          |
| Yes      | time           | date                 | Date                  | calendar_date | calendar_date |
| Yes      | series tag     | sex                  | Sex                   | text          | text          |
| Yes      | series tag     | race                 | Race                  | text          | text          |
| Yes      | numeric metric | age                  | Age                   | number        | number        |
| Yes      | series tag     | residence_city       | Residence City        | text          | text          |
| Yes      | series tag     | residence_state      | Residence State       | text          | text          |
| Yes      | series tag     | residence_county     | Residence County      | text          | text          |
| Yes      | series tag     | death_city           | Death City            | text          | text          |
| Yes      | series tag     | death_state          | Death State           | text          | text          |
| Yes      | series tag     | death_county         | Death County          | text          | text          |
| Yes      | series tag     | location             | Location              | text          | text          |
| Yes      | series tag     | descriptionofinjury  | DescriptionofInjury   | text          | text          |
| Yes      | series tag     | injuryplace          | InjuryPlace           | text          | text          |
| Yes      | series tag     | immediatecausea      | ImmediateCauseA       | text          | text          |
| Yes      | series tag     | heroin               | Heroin                | text          | text          |
| Yes      | series tag     | coc                  | Cocaine               | text          | text          |
| Yes      | series tag     | fentanyl             | Fentanyl              | text          | text          |
| Yes      | series tag     | oxyc                 | Oxycodone             | text          | text          |
| Yes      | series tag     | oxym                 | Oxymorphone           | text          | text          |
| Yes      | series tag     | etoh                 | EtOH                  | text          | text          |
| Yes      | series tag     | hydr_cod             | Hydro-codeine         | text          | text          |
| Yes      | series tag     | benzo_s              | Benzodiazepine        | text          | text          |
| Yes      | series tag     | methadone            | Methadone             | text          | text          |
| Yes      | series tag     | amphet               | Amphet                | text          | text          |
| Yes      | series tag     | tramad               | Tramad                | text          | text          |
| Yes      | series tag     | morphine_not_heroin  | Morphine (not heroin) | text          | text          |
| Yes      | series tag     | other                | Other                 | text          | text          |
| Yes      | series tag     | any_opioid           | Any Opioid            | text          | text          |
| Yes      | series tag     | mannerofdeath        | MannerofDeath         | text          | text          |
| Yes      | series tag     | amendedmannerofdeath | AmendedMannerofDeath  | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:rybz-nyjw d:2012-03-23T00:00:00.000Z t:residence_county=WINDHAM t:injuryplace=Other t:sex=Male t:casenumber=12-4443 t:location=Other t:mannerofdeath=Accident t:residence_city=ONECO t:immediatecausea="Heroin Toxicity" t:death_county=WINDHAM t:death_city=MOOSUP t:race=White t:heroin=Y m:age=22

series e:rybz-nyjw d:2012-02-21T00:00:00.000Z t:oxyc=Y t:residence_county=LITCHFIELD t:injuryplace=Other t:sex=Male t:casenumber=12-2808 t:mannerofdeath=Accident t:residence_city=WINCHESTER t:immediatecausea="Oxycodone Toxicity" t:death_county=LITCHFIELD t:death_city=WINCHESTER t:race=White m:age=28

series e:rybz-nyjw d:2016-05-20T00:00:00.000Z t:residence_state=CT t:residence_county=HARTFORD t:oxyc=Y t:sex=Male t:location=Residence t:immediatecausea="Acute Oxycodone Intoxication" t:death_city=AVON t:race=White t:injuryplace=Residence t:death_state=CT t:mannerofdeath=Accident t:residence_city=AVON t:death_county=HARTFORD m:age=36
```

## Meta Commands

```ls
metric m:age p:integer l:Age t:dataTypeName=number

entity e:rybz-nyjw l:"Accidental Drug Related Deaths  2012-2016" t:attribution="Office of the Chief Medical Examiner" t:url=https://data.ct.gov/api/views/rybz-nyjw

property e:rybz-nyjw t:meta.view v:id=rybz-nyjw v:category="Health and Human Services" v:attributionLink=http://www.ct.gov/ocme v:averageRating=0 v:name="Accidental Drug Related Deaths  2012-2016" v:attribution="Office of the Chief Medical Examiner"

property e:rybz-nyjw t:meta.view.license v:name="Public Domain"

property e:rybz-nyjw t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:rybz-nyjw t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| casenumber | date                | sex  | race            | age | residence_city | residence_state | residence_county | death_city | death_state | death_county | location  | descriptionofinjury | injuryplace | immediatecausea                                                               | heroin | coc | fentanyl | oxyc | oxym | etoh | hydr_cod | benzo_s | methadone | amphet | tramad | morphine_not_heroin | other | any_opioid | mannerofdeath | amendedmannerofdeath | 
| ========== | =================== | ==== | =============== | === | ============== | =============== | ================ | ========== | =========== | ============ | ========= | =================== | =========== | ============================================================================= | ====== | === | ======== | ==== | ==== | ==== | ======== | ======= | ========= | ====== | ====== | =================== | ===== | ========== | ============= | ==================== | 
| 12-4443    | 2012-03-23T00:00:00 | Male | White           | 22  | ONECO          |                 | WINDHAM          | MOOSUP     |             | WINDHAM      | Other     |                     | Other       | Heroin Toxicity                                                               | Y      |     |          |      |      |      |          |         |           |        |        |                     |       |            | Accident      |                      | 
| 12-2808    | 2012-02-21T00:00:00 | Male | White           | 28  | WINCHESTER     |                 | LITCHFIELD       | WINCHESTER |             | LITCHFIELD   |           |                     | Other       | Oxycodone Toxicity                                                            |        |     |          | Y    |      |      |          |         |           |        |        |                     |       |            | Accident      |                      | 
|            | 2016-05-20T00:00:00 | Male | White           | 36  | AVON           | CT              | HARTFORD         | AVON       | CT          | HARTFORD     | Residence |                     | Residence   | Acute Oxycodone Intoxication                                                  |        |     |          | Y    |      |      |          |         |           |        |        |                     |       |            | Accident      |                      | 
| 15-13536   | 2015-08-20T00:00:00 | Male | Black           | 63  | NEW HAVEN      | CT              | NEW HAVEN        | NEW HAVEN  | CT          | NEW HAVEN    | Residence |                     | Residence   | Liver Failure due to cirrhosis due to chronic hepatitis C (OSC Heroin)        | Y      |     |          |      |      |      |          |         |           |        |        |                     |       | Y          | Accident      |                      | 
| 12-12217   | 2012-08-29T00:00:00 | Male | White           | 39  | MIDDLETOWN     |                 | MIDDLESEX        | MIDDLETOWN |             | MIDDLESEX    | Residence |                     | Residence   | Opiate Toxicity                                                               |        |     |          | Y    | Y    |      | Y        |         |           |        |        |                     |       |            | Accident      |                      | 
| 15-6342    | 2015-04-11T00:00:00 | Male | White           | 46  | NEWTOWN        | CT              | FAIRFIELD        | NEWTOWN    | CT          | FAIRFIELD    | Residence |                     | Residence   | Intoxication due to the Combined Effects of Diazepam, Temazepam, and Fentanyl |        |     | Y        |      |      |      |          | Y       |           |        |        |                     |       | Y          | Accident      |                      | 
| 15-12442   | 2015-07-30T00:00:00 | Male | White           | 24  | HAMDEN         | CT              | NEW HAVEN        | HAMDEN     | CT          | NEW HAVEN    | Residence |                     | Residence   | Acute Heroin Toxicity                                                         | Y      |     |          |      |      |      |          |         |           |        |        |                     |       | Y          | Accident      |                      | 
| 13-6486    | 2013-04-25T00:00:00 | Male | White           | 31  | NEW HAVEN      |                 | NEW HAVEN        | NEW HAVEN  |             | NEW HAVEN    | Residence |                     | Residence   | Acute Heroin Toxicity                                                         | Y      |     |          |      |      |      |          |         |           |        |        |                     |       |            | Accident      |                      | 
| 15-12174   | 2015-07-26T00:00:00 | Male | Hispanic, White | 38  | MERIDEN        | CT              | NEW HAVEN        | MERIDEN    | CT          | NEW HAVEN    | Hospital  |                     | Hospital    | Acute Cocaine and Heroin Intoxication                                         | Y      | Y   |          |      |      |      |          |         |           |        |        |                     |       | Y          | Accident      |                      | 
| 12-378     | 2012-01-07T00:00:00 | Male | White           | 45  | HARTFORD       |                 | HARTFORD         | HARTFORD   |             | HARTFORD     | Residence |                     | Residence   | Heroin Toxicity                                                               | Y      |     |          |      |      |      |          |         |           |        |        |                     |       |            | Accident      |                      | 
```