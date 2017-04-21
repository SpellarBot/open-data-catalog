# Comment on Cleaner Air Oregon Regulatory Overhaul Advisory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comment-on-cleaner-air-oregon-regulatory-overhaul-advisory) |
| Metadata | [Link](https://data.oregon.gov/api/views/hxyg-7kyi) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/hxyg-7kyi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/hxyg-7kyi/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | hxyg-7kyi |
| Name | Comment on Cleaner Air Oregon Regulatory Overhaul Advisory |
| Created | 2016-05-12T23:58:11Z |
| Publication Date | 2016-05-13T16:57:38Z |

## Description

DEQ and OHA invite you to comment on which 5-7 additional stakeholder positions should be included on this rulemaking?s Advisory Committee. All comments must be received by 4:00 p.m. on Friday, May 27, 2016.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email_address       | Email Address       | text      | text        |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional Document | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hxyg-7kyi d:2016-05-13T17:00:35.000Z t:first_name=Paul t:organization="Lane Community College" t:state=Oregon t:last_name=Ruscher t:comment="This advisory committee needs to have scientific advisors on the committee who will be unbiased, in my opinion.  I'd like to see the following types of individuals:

&acirc;&euro;&cent; Atmospheric Scientist (PhD) with experience in atmospheric chemistry or air pollution
&acirc;&euro;&cent; Professional Chemist or Chemical Engineer (PhD) with experience in air toxics and controls
&acirc;&euro;&cent; Physician (MD) with Public Health Experience (perhaps MPH)

The role that this committee will play must have appropriate unbiased expertise.  Thank you.

Paul Ruscher, Fellow, American Meteorological Society" t:email_address=ruscherp@lanecc.edu m:row_number.hxyg-7kyi=1

series e:hxyg-7kyi d:2016-05-13T17:09:26.000Z t:first_name=Jennifer t:organization="Eastside Portland Air Coalition" t:state=Oregon t:last_name=Jones t:comment="As an organizer with Eastside Portland Air Coalition I would respectfully request that our coalition, which represents over 3,000 Oregonians, be offered a voice in this process. Our access to people and our commitment to transparency and coalition building make us a strong ally in transparent and inclusive reform." t:email_address=Jennifer@eastsideportlandair.com m:row_number.hxyg-7kyi=2

series e:hxyg-7kyi d:2016-05-13T17:15:55.000Z t:first_name=Jessica t:organization="EastsidePortland Air Coalition" t:state=Oregon t:last_name=Applegate t:comment="http://eastsideportlandair.org/

We're a neighborhood group with a mission: 
to mobilize neighbors impacted by toxic air pollution, support one another in dealing with immediate needs, and partner with other stakeholders to enact permanent change." t:email_address=eastsideportlandair@gmail.com m:row_number.hxyg-7kyi=3
```

## Meta Commands

```ls
metric m:row_number.hxyg-7kyi p:long l:"Row Number"

entity e:hxyg-7kyi l:"Comment on Cleaner Air Oregon Regulatory Overhaul Advisory" t:url=https://data.oregon.gov/api/views/hxyg-7kyi

property e:hxyg-7kyi t:meta.view v:id=hxyg-7kyi v:averageRating=0 v:name="Comment on Cleaner Air Oregon Regulatory Overhaul Advisory"

property e:hxyg-7kyi t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:hxyg-7kyi t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| :updated_at | first_name | last_name   | email_address                    | organization                    | state  | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | additional_document      | 
| =========== | ========== | =========== | ================================ | =============================== | ====== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ======================== | 
| 1463158835  | Paul       | Ruscher     | ruscherp@lanecc.edu              | Lane Community College          | Oregon | This advisory committee needs to have scientific advisors on the committee who will be unbiased, in my opinion. I'd like to see the following types of individuals: ??? Atmospheric Scientist (PhD) with experience in atmospheric chemistry or air pollution ??? Professional Chemist or Chemical Engineer (PhD) with experience in air toxics and controls ??? Physician (MD) with Public Health Experience (perhaps MPH) The role that this committee will play must have appropriate unbiased expertise. Thank you. Paul Ruscher, Fellow, American Meteorological Society     | [null, null, null, null] | 
| 1463159366  | Jennifer   | Jones       | Jennifer@eastsideportlandair.com | Eastside Portland Air Coalition | Oregon | As an organizer with Eastside Portland Air Coalition I would respectfully request that our coalition, which represents over 3,000 Oregonians, be offered a voice in this process. Our access to people and our commitment to transparency and coalition building make us a strong ally in transparent and inclusive reform.                                                                                                                                                                                                                                                       | [null, null, null, null] | 
| 1463159755  | Jessica    | Applegate   | eastsideportlandair@gmail.com    | EastsidePortland Air Coalition  | Oregon | http://eastsideportlandair.org/ We're a neighborhood group with a mission: to mobilize neighbors impacted by toxic air pollution, support one another in dealing with immediate needs, and partner with other stakeholders to enact permanent change.                                                                                                                                                                                                                                                                                                                             | [null, null, null, null] | 
| 1463160102  | Alma       | Velazquez   | advelazquez@comcast.net          | Eastside Portland Air Coalition | Oregon | EPAC has been a true advocate for Portland area residents fighting for clean air. They have focused on advocacy and rallied thousands of people toward this environmental justice issue. It's essential for me that they be involved in the conversation with other stakeholders representing my interests and those of other residents from throughout Portland.                                                                                                                                                                                                                 | [null, null, null, null] | 
| 1463160132  | Alma       | Velazquez   | advelazquez@comcast.net          | Eastside Portland Air Coalition | Oregon | EPAC has been a true advocate for Portland area residents fighting for clean air. They have focused on advocacy and rallied thousands of people toward this environmental justice issue. It's essential for me that they be involved in the conversation with other stakeholders representing my interests and those of other residents from throughout Portland.                                                                                                                                                                                                                 | [null, null, null, null] | 
| 1463162271  | Gene       | Zilberstein | family@genia.org                 | Eastside Portland Air Coalition | Oregon | I nominate the Eastside Portland Air Coalition as a stakeholder in the Cleaner Air Oregon process. As a resident of the affected neighborhood for over 15 years, I trust this local organization to be a voice for the citizens. Thank you, Gene Zilberstein                                                                                                                                                                                                                                                                                                                      | [null, null, null, null] | 
| 1463162283  | Katie      | Smith       | Smithkc1@klsoaps.com             | Eastside Portland Air Coalition | Oregon | I nominate Eastside Portland Air Coalition and Portland Clean Air to be part of the advisory committee that DEQ seeks. Both of these organizations have worked tirelessly in solidarity with the communities in/around Portland affected by the air pollution problems..                                                                                                                                                                                                                                                                                                          | [null, null, null, null] | 
| 1463164823  | Paulette   | Marchand    | yellowgardenhouse@yahoo.com      |                                 | Oregon | I request EPAC have a voice in this process.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | [null, null, null, null] | 
| 1463168594  | Katharine  | Salzmann    | katharinesalzmann@gmail.com      | Ms                              | Oregon | Please include the Eastside Portland Air Coalition in this long-overdue conversation. They have earned a voice at the table. EPAC has been working tirelessly on the ground in the community, with the agencies and local legislators, educating the public and supporting other communities affected by toxic air pollution. We all look forward to the creation of new rules that will be based in the Precautionary Principle and truly protective of human health and the health of the environment. EPAC will be certain to keep this committee honest and true to its task. | [null, null, null, null] | 
| 1463171447  | Kerry      | Ryan        | kerrysilvaryan@gmail.com         |                                 | Oregon | Please give the Eastside Portland Air Coalition a seat at the table. EPAC represents 3000 stakeholders in Portland. A large majority of EPAC members live in toxic hotspots, and deserve an active voice.                                                                                                                                                                                                                                                                                                                                                                         | [null, null, null, null] | 
```