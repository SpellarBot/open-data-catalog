# Electronic Government Portal Advisory Board Meetings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electronic-government-portal-advisory-board-meetings-95ece) |
| Metadata | [Link](https://data.oregon.gov/api/views/arrt-f5ji) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/arrt-f5ji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/arrt-f5ji/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | arrt-f5ji |
| Name | Electronic Government Portal Advisory Board Meetings |
| Attribution | Department of Administrative Services, E-Government Portal Advisory Board |
| Tags | epab, e-government, portal advisory board |
| Created | 2011-09-30T18:31:13Z |
| Publication Date | 2017-03-09T19:01:03Z |

## Description

Dates, agendas, minutes, and handouts of the E-Government Portal Advisory Board meetings. The board was formed by Oregon Revised Statute 182.128 http://www.oregon.gov/eapb

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | time        | meeting_date          | Meeting Date          | calendar_date | calendar_date |
| Yes      | series tag  | meeting_name          | Meeting Name          | text          | text          |
| Yes      | series tag  | agenda                | Agenda                | document      | document      |
| Yes      | series tag  | minutes               | Minutes               | document      | document      |
| Yes      | series tag  | consolidated_handouts | Consolidated Handouts | document      | document      |
```

## Time Field

```ls
Value = meeting_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:arrt-f5ji d:2011-06-29T00:00:00.000Z t:minutes.content_type="application/pdf; charset=binary" t:minutes.filename=EPABFinalMinutes062911.pdf t:minutes.file_id=C8L-jNx97kiPlQaltg2XxMFDNm4ilEkSRE0DfuS8_GY t:agenda.content_type="application/msword; charset=binary" t:agenda.size=92160 t:minutes.size=40561 t:meeting_name="June Board Meeting" t:agenda.file_id=4Nm_xdPKdFqZFUnxp2ziLHkjQWwuJTFUcEy_mmqpQE4 t:agenda.filename=Agenda_-_June2911.doc m:row_number.arrt-f5ji=1

series e:arrt-f5ji d:2010-11-17T00:00:00.000Z t:consolidated_handouts.file_id=fc3d6338-ac0d-4cb1-8e9f-6920aa27ca58 t:minutes.content_type="application/msword; charset=binary" t:consolidated_handouts.filename=11-17-10_Consolidated_Documents.pdf t:consolidated_handouts.content_type="application/pdf; charset=binary" t:minutes.file_id=Z_olOmPWKQr3I992L5dIqBc1ozl-q7qvu8Z6gyYs5rE t:minutes.filename=EPABMinutes11172010.doc t:agenda.content_type="application/msword; charset=binary" t:agenda.size=97792 t:minutes.size=102400 t:consolidated_handouts.size=167924 t:meeting_name="November Board Meeting" t:agenda.file_id=CGpPW3yC1vtwp7MHbZar_cCJZjEGkHIOUjLS2pWnNu4 t:agenda.filename="EPAB Agenda - November2010.doc" m:row_number.arrt-f5ji=2

series e:arrt-f5ji d:2011-01-05T00:00:00.000Z t:consolidated_handouts.file_id=e6de7028-301c-4008-b37d-bb9b1126766a t:minutes.content_type="application/pdf; charset=binary" t:consolidated_handouts.filename=1-5-11_Consolidated_Documents.pdf t:consolidated_handouts.content_type="application/pdf; charset=binary" t:minutes.file_id=w-V1BJ90dqXsS0OU3a4EvdDJgRFATdcATzBJmesDsf8 t:minutes.filename=EPABFinalMinutes010511.pdf t:agenda.content_type="application/msword; charset=binary" t:agenda.size=99328 t:minutes.size=48166 t:consolidated_handouts.size=8816191 t:meeting_name="January Board Meeting" t:agenda.file_id=y3rSQKmI3wKpD2U9CPIseSrUZmxg1ZTY5Z7f5ViRkjY t:agenda.filename=EPABAgenda_1-5-2011.doc m:row_number.arrt-f5ji=3
```

## Meta Commands

```ls
metric m:row_number.arrt-f5ji p:long l:"Row Number"

entity e:arrt-f5ji l:"Electronic Government Portal Advisory Board Meetings" t:attribution="Department of Administrative Services, E-Government Portal Advisory Board" t:url=https://data.oregon.gov/api/views/arrt-f5ji

property e:arrt-f5ji t:meta.view v:id=arrt-f5ji v:averageRating=0 v:name="Electronic Government Portal Advisory Board Meetings" v:attribution="Department of Administrative Services, E-Government Portal Advisory Board"

property e:arrt-f5ji t:meta.view.owner v:id=x7ch-rbs5 v:profileImageUrlMedium=/api/users/x7ch-rbs5/profile_images/THUMB v:profileImageUrlLarge=/api/users/x7ch-rbs5/profile_images/LARGE v:screenName="Wally Rogers" v:profileImageUrlSmall=/api/users/x7ch-rbs5/profile_images/TINY v:displayName="Wally Rogers"

property e:arrt-f5ji t:meta.view.tableauthor v:id=x7ch-rbs5 v:profileImageUrlMedium=/api/users/x7ch-rbs5/profile_images/THUMB v:profileImageUrlLarge=/api/users/x7ch-rbs5/profile_images/LARGE v:screenName="Wally Rogers" v:profileImageUrlSmall=/api/users/x7ch-rbs5/profile_images/TINY v:roleName=administrator v:displayName="Wally Rogers"
```

## Top Records

```ls
| meeting_date        | meeting_name           | agenda                                                                                                                   | minutes                                                                                                            | consolidated_handouts                                                                                                 | 
| =================== | ====================== | ======================================================================================================================== | ================================================================================================================== | ===================================================================================================================== | 
| 2011-06-29T00:00:00 | June Board Meeting     | [application/msword; charset=binary, 4Nm_xdPKdFqZFUnxp2ziLHkjQWwuJTFUcEy_mmqpQE4, Agenda_-_June2911.doc, 92160]          | [application/pdf; charset=binary, C8L-jNx97kiPlQaltg2XxMFDNm4ilEkSRE0DfuS8_GY, EPABFinalMinutes062911.pdf, 40561]  | [null, null, null, null]                                                                                              | 
| 2010-11-17T00:00:00 | November Board Meeting | [application/msword; charset=binary, CGpPW3yC1vtwp7MHbZar_cCJZjEGkHIOUjLS2pWnNu4, EPAB Agenda - November2010.doc, 97792] | [application/msword; charset=binary, Z_olOmPWKQr3I992L5dIqBc1ozl-q7qvu8Z6gyYs5rE, EPABMinutes11172010.doc, 102400] | [application/pdf; charset=binary, fc3d6338-ac0d-4cb1-8e9f-6920aa27ca58, 11-17-10_Consolidated_Documents.pdf, 167924]  | 
| 2011-01-05T00:00:00 | January Board Meeting  | [application/msword; charset=binary, y3rSQKmI3wKpD2U9CPIseSrUZmxg1ZTY5Z7f5ViRkjY, EPABAgenda_1-5-2011.doc, 99328]        | [application/pdf; charset=binary, w-V1BJ90dqXsS0OU3a4EvdDJgRFATdcATzBJmesDsf8, EPABFinalMinutes010511.pdf, 48166]  | [application/pdf; charset=binary, e6de7028-301c-4008-b37d-bb9b1126766a, 1-5-11_Consolidated_Documents.pdf, 8816191]   | 
| 2011-11-18T00:00:00 | November Board Meeting | [application/pdf; charset=binary, MS9BV78cenltqeS7l_kpS6zJubZqot2K_2UuXjdFed0, Agenda - 111811v2.pdf, 27261]             | [application/pdf; charset=binary, hNyqXmB9VbWoygZQmOqKtWlXMgUOKjIqmbBsW1SUEdo, EPABFinalMinutes111811.pdf, 57496]  | [application/pdf; charset=binary, 246e92c6-7ad5-4567-b2a0-651d82b90e56, 11-18-11_Consolidated_Documents.pdf, 4418509] | 
| 2012-04-06T00:00:00 | April Board Meeting    | [application/pdf; charset=binary, Z2pqV7Y6ct-MsMHj87agf5PvQalmlRV2kk2fyVcdQOA, EPABAgenda040612.pdf, 31838]              | [application/pdf; charset=binary, LCR_HYdYwLG_9q4QElMhaT3yuEDM46_O-dmlV7JCHfI, EPABFinalMinutes040612.pdf, 43207]  | [application/pdf; charset=binary, 2520b3ca-7af0-4b6f-bbae-d0e75bd2cc47, 4-6-12_Consolidated_Documents.pdf, 2023228]   | 
| 2012-10-31T00:00:00 | October Board Meeting  | [application/pdf; charset=binary, -LxgG-J2RTioPFn3-MFfQpDGfuJaCInBcDshUFOPPzw, EPAB Agenda 10-24-12.pdf, 20903]          | [application/pdf; charset=binary, YOQoKxQTOy5MTrljWeu_YUv6_aijzTNuYKDHYN1sGRM, EPABFinalMinutes103112.pdf, 171974] | [application/pdf; charset=binary, e73b085b-6e00-45c0-aa84-b39ff994f4c4, 10-31-12_Consolidated_Documents.pdf, 2128331] | 
| 2013-06-06T00:00:00 | June Board Meeting     | [application/pdf; charset=binary, nw1-vSQB2wOWDEfO_8ZaRhVkMCKDct_DVFs5tQNjPbw, EPAB Agenda 6-6-13.pdf, 112637]           | [application/pdf; charset=binary, ilF3u11WKDxCZQvhBikfo_jffr-3d4m8TogZ4Z3_ayg, EPABFinalMinutes060613.pdf, 114560] | [application/pdf; charset=binary, d17d7cd9-2405-4a0e-9066-8c9ec83bfcd5, 6-6-13_Consolidated_Documents.pdf, 1552561]   | 
| 2013-08-14T00:00:00 | August Board Meeting   | [application/pdf; charset=binary, By9w3jVFk0O-5U0_1ysfTI2spV5lag5er_s9RiHcMfo, EPAB Agenda 8-14-13.pdf, 104251]          | [application/pdf; charset=binary, 1T7orll9z0uJxX_clH6DzZ3aIy98kpm7DY8tJ6hOBW8, EPABFinalMinutes081413.pdf, 118254] | [application/pdf; charset=binary, e94ac733-64d1-442a-97f1-7ad0bf13c588, 8-14-13_Consolidated_Documents.pdf, 4672808]  | 
| 2014-03-12T00:00:00 | March Board Meeting    | [application/pdf; charset=binary, 6_l4NCGzX7XPj16h9g4ukBiKSNp5fEZYbA6AwwGtl44, EPAB Agenda 3-12-14.pdf, 112634]          | [application/pdf; charset=binary, IfCdmztE_PkdM150gaIHPMifzQwCwlR9ahl25Nns-O0, EPABFinalMinutes031214.pdf, 167733] | [application/pdf; charset=binary, 7f4610d7-59e1-4e0a-a6bb-ee0c105a6292, 3-12-14_Consolidated_Documents.pdf, 10140011] | 
| 2014-08-13T00:00:00 | August Board Meeting   | [application/pdf; charset=binary, KB0bzo_l-tW2X4cjG5BeXEzwBGfCavXvFr1Mb0hDlaM, EPAB_Agenda_8-13-14.pdf, 98581]           | [application/pdf; charset=binary, gquVNUxn7R3mQp_68tHzXVKxbxOKMmhB6Y-dBqiaEm4, EPABFinalMinutes081314.pdf, 164359] | [application/pdf; charset=binary, 21768af8-99aa-41a8-9334-7bf5ff244d33, 8-13-14_Consolidated_Documents.pdf, 3077088]  | 
```