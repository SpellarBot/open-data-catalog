# Voluntary Clean Water Guidance for Agriculture Proposed Process Comments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/voluntary-clean-water-guidance-for-agriculture-proposed-process-comments) |
| Metadata | [Link](https://data.wa.gov/api/views/ferj-zqte) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ferj-zqte/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ferj-zqte/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ferj-zqte |
| Name | Voluntary Clean Water Guidance for Agriculture Proposed Process Comments |
| Category | Natural Resources & Environment |
| Tags | ecology, agriculture |
| Created | 2017-01-12T22:50:25Z |
| Publication Date | 2017-02-06T23:13:06Z |

## Description

Comments for our proposed process for developing voluntary clean water guidance for agriculture

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | name         | Name         | text      | text        |
| Yes      | series tag  | organization | Organization | text      | text        |
| Yes      | series tag  | email        | Email        | email     | email       |
| Yes      | series tag  | comments     | Comments     | html      | html        |
| Yes      | series tag  | attachment   | Attachment   | document  | document    |
| Yes      | series tag  | attachment_2 | Attachment 2 | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ferj-zqte d:2017-01-25T03:23:47.000Z t:organization=Public t:email=pgypsy@wavecable.com t:name="Peter Haase" t:comments="1.  I am leery since even now, enforcement of obvious agricultural pollution situations does not often happen.  So why should anyone voluntarily do more?

2.  I see this as another &quot;soon to be failed&quot; approach to voluntary agricultural pollution control.  Kicking the can further on down the road.  Sorry.

3.  Where I live, Skagit County, hundreds of cows frequently loiter in plain sight within 2 feet of the edge of a waterway for days on end.  It does not take a scientific study to know what is happening to that water.  Nothing at all is done about it.  Oh - except millions of dollars over several years have been spent trying to open the downstream shellfish beds." m:row_number.ferj-zqte=1

series e:ferj-zqte d:2017-02-01T00:14:06.000Z t:organization=citizen t:email=pgypsy@wavecable.com t:name="peter haase" t:comments="testing ..." m:row_number.ferj-zqte=2

series e:ferj-zqte d:2017-02-03T01:17:52.000Z t:email=eric.b@elltel.net t:name="Eric Bartrand" t:comments="Implement restoration of natural channel cross-sections, planforms, and floodplains. Implement effective vegetative buffers to trap sediments, pollutants, and provide cover from insolation." m:row_number.ferj-zqte=3
```

## Meta Commands

```ls
metric m:row_number.ferj-zqte p:long l:"Row Number"

entity e:ferj-zqte l:"Voluntary Clean Water Guidance for Agriculture Proposed Process Comments" t:url=https://data.wa.gov/api/views/ferj-zqte

property e:ferj-zqte t:meta.view v:id=ferj-zqte v:category="Natural Resources & Environment" v:averageRating=0 v:name="Voluntary Clean Water Guidance for Agriculture Proposed Process Comments"

property e:ferj-zqte t:meta.view.owner v:id=us76-w9xc v:screenName="Tim Lewis" v:displayName="Tim Lewis"

property e:ferj-zqte t:meta.view.tableauthor v:id=us76-w9xc v:screenName="Tim Lewis" v:roleName=publisher v:displayName="Tim Lewis"
```

## Top Records

```ls
| :updated_at | name                | organization                                            | email                          | comments                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | attachment                                                                                                                                     | attachment_2             | 
| =========== | =================== | ======================================================= | ============================== | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ============================================================================================================================================== | ======================== | 
| 1485314627  | Peter Haase         | Public                                                  | pgypsy@wavecable.com           | 1. I am leery since even now, enforcement of obvious agricultural pollution situations does not often happen. So why should anyone voluntarily do more? 2. I see this as another "soon to be failed" approach to voluntary agricultural pollution control. Kicking the can further on down the road. Sorry. 3. Where I live, Skagit County, hundreds of cows frequently loiter in plain sight within 2 feet of the edge of a waterway for days on end. It does not take a scientific study to know what is happening to that water. Nothing at all is done about it. Oh - except millions of dollars over several years have been spent trying to open the downstream shellfish beds. | [null, null, null, null]                                                                                                                       | [null, null, null, null] | 
| 1485908046  | peter haase         | citizen                                                 | pgypsy@wavecable.com           | testing ...                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | [null, null, null, null]                                                                                                                       | [null, null, null, null] | 
| 1486084672  | Eric Bartrand       |                                                         | eric.b@elltel.net              | Implement restoration of natural channel cross-sections, planforms, and floodplains. Implement effective vegetative buffers to trap sediments, pollutants, and provide cover from insolation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | [null, null, null, null]                                                                                                                       | [null, null, null, null] | 
| 1487349076  | Ben Rau             | ECY                                                     | ben.rau@ecy.wa.gov             | test                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | [null, null, null, null]                                                                                                                       | [null, null, null, null] | 
| 1487723749  | Steve Parker        | Stevens County Commissioners                            | commissioners@co.stevens.wa.us | Attachment for the record                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [application/pdf, 612baa6b-7a80-4dbd-8327-21a9c7276b21, DOE - re proposed process to develop voluntary clean water guidance for ag.pdf, 60302] | [null, null, null, null] | 
| 1487889698  | Nichole Embertson   | WSCC Center for Technical Development                   | nembertson@whatcomcd.org       | See comments in document attached.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | [application/pdf, b7dca375-d7d1-48e4-93b9-c4cdd0c1857a, CTD_Letter_ECYProcessComments_022117.pdf, 153020]                                      | [null, null, null, null] | 
| 1487895476  | Robert L. Schroeter | WACD (Washington Association of Conservation Districts) | bschroeter@wadistricts.org     | Please see the attached letter, in PDF format, which we incorporate within these comments.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [application/pdf, 928786bf-5541-42e9-b234-7fbd3c645dca, WACD DOE Ag BMPs Ltr.pdf, 340636]                                                      | [null, null, null, null] | 
| 1487896349  | Robert L Schroeter  | WACD (Washington Association of Conservation Districts) | bschroeter@wadistricts.org     | Please incorporate the attached letter as our comments on the proposed process. Thank you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [application/pdf, da09b818-425c-445e-8ca9-c57b9464ce64, WACD DOE Ag BMPs Ltr.pdf, 340583]                                                      | [null, null, null, null] | 
| 1487903924  | Dean White          | Lincoln County Conservation District                    | dwhite@wadistrict.net          | Please refer to attached comments in a Word document.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | [application/msword, 43b7194c-775f-43f9-b737-426d3ec36dd3, Comments_CleanWaterGuidance_02232017.doc, 26112]                                    | [null, null, null, null] | 
| 1487956981  | Jeff Killelea       | Interagency Team                                        | killelj@co.thurston.wa.us      | See attached comment letter. Thank you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | [application/pdf, 06d3203a-e042-480b-98b3-904c6ac3488e, IAT Final Letter on Nonpoint Guidance Process Design.pdf, 78239]                       | [null, null, null, null] | 
```