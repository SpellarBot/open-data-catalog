# EGP Nonprofits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/egp-nonprofits-3bc6b) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/4wxy-htkj) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/4wxy-htkj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/4wxy-htkj/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 4wxy-htkj |
| Name | EGP Nonprofits |
| Attribution | King County Employee Giving Program |
| Category | Employees |
| Created | 2013-09-03T17:19:09Z |
| Publication Date | 2017-02-27T20:23:46Z |

## Description

List of nonprofits in the King County Employee Giving Program Annual Drive

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | organization_name         | Organization Name         | text      | text        |
| Yes      | series tag  | category                  | Category                  | text      | text        |
| Yes      | series tag  | tax_identification_number | Tax Identification Number | text      | text        |
| Yes      | series tag  | kcegp_code                | KCEGP Code                | text      | number      |
| Yes      | series tag  | website                   | Website                   | url       | url         |
| Yes      | series tag  | short_description         | Short Description         | html      | html        |
| Yes      | series tag  | category_2                | Category 2                | text      | text        |
| Yes      | series tag  | category_3                | Category 3                | text      | text        |
| Yes      | series tag  | wa_sec_of_state_link      | WA Sec of State Link      | url       | url         |
| Yes      | series tag  | link_1                    | Link 1                    | url       | url         |
| Yes      | series tag  | link_2                    | Link 2                    | url       | url         |
| Yes      | series tag  | link_3                    | Link 3                    | url       | url         |
| Yes      | series tag  | link_4                    | Link 4                    | url       | url         |
| Yes      | series tag  | status                    | Status                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4wxy-htkj d:2017-02-25T00:33:07.000Z t:category=Environment t:short_description="Conserving and restoring Northwest environments through education." t:status=New t:website=http://www.ncascades.org t:kcegp_code=2709 t:wa_sec_of_state_link="http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=3291" t:tax_identification_number=91-1327775 t:organization_name="North Cascade Institute" m:row_number.4wxy-htkj=1

series e:4wxy-htkj d:2017-02-25T00:33:07.000Z t:category=Animals t:short_description="Tigers confined to circus wagons. Lions bred for photos then to be shot in cages. Lynx farmed for their fur. Help us save big cats." t:status=Returning t:website=http://www.bigcatrescue.org t:kcegp_code=2731 t:wa_sec_of_state_link="http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=35033" t:tax_identification_number=59-3330495 t:organization_name="Big Cat Rescue Corp" m:row_number.4wxy-htkj=2

series e:4wxy-htkj d:2017-02-25T00:33:07.000Z t:category="International Relief & Development" t:short_description="LUA collaborates with local partners to support programs that encourage self-reliance and provide for basic needs including healthcare, education and economic empowerment." t:category_3="Children & Youth" t:status=Returning t:website=http://www.liftupafrica.org t:kcegp_code=9206 t:category_2="Community Development" t:wa_sec_of_state_link="http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=21976" t:tax_identification_number=74-3116756 t:organization_name="Lift Up Africa" m:row_number.4wxy-htkj=3
```

## Meta Commands

```ls
metric m:row_number.4wxy-htkj p:long l:"Row Number"

entity e:4wxy-htkj l:"EGP Nonprofits" t:attribution="King County Employee Giving Program" t:url=https://data.kingcounty.gov/api/views/4wxy-htkj

property e:4wxy-htkj t:meta.view v:id=4wxy-htkj v:category=Employees v:attributionLink=http://www.kingcounty.gov/employees/giving.aspx v:averageRating=0 v:name="EGP Nonprofits" v:attribution="King County Employee Giving Program"

property e:4wxy-htkj t:meta.view.license v:name="Public Domain"

property e:4wxy-htkj t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:4wxy-htkj t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | organization_name                                   | category                           | tax_identification_number | kcegp_code | website                                      | short_description                                                                                                                                                           | category_2                            | category_3            | wa_sec_of_state_link                                                          | link_1                                                                                             | link_2                                                                                                                                                                             | link_3       | link_4       | status    | 
| =========== | =================================================== | ================================== | ========================= | ========== | ============================================ | =========================================================================================================================================================================== | ===================================== | ===================== | ============================================================================= | ================================================================================================== | ================================================================================================================================================================================== | ============ | ============ | ========= | 
| 1487982787  | North Cascade Institute                             | Environment                        | 91-1327775                | 2709       | [http://www.ncascades.org, null]             | Conserving and restoring Northwest environments through education.                                                                                                          |                                       |                       | [http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=3291, null]    | [null, null]                                                                                       | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | New       | 
| 1487982787  | Big Cat Rescue Corp                                 | Animals                            | 59-3330495                | 2731       | [http://www.bigcatrescue.org, null]          | Tigers confined to circus wagons. Lions bred for photos then to be shot in cages. Lynx farmed for their fur. Help us save big cats.                                         |                                       |                       | [http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=35033, null]   | [null, null]                                                                                       | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | Returning | 
| 1487982787  | Lift Up Africa                                      | International Relief & Development | 74-3116756                | 9206       | [http://www.liftupafrica.org, null]          | LUA collaborates with local partners to support programs that encourage self-reliance and provide for basic needs including healthcare, education and economic empowerment. | Community Development                 | Children & Youth      | [http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=21976, null]   | [null, null]                                                                                       | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | Returning | 
| 1487982787  | VIVA Hispanic Foundation NW                         | Education & Literacy               | 91-2105316                | 9094       | [http://vivahispanicfoundation.com, null]    | Provides educational support and opportunities, conducts programs aimed at empowering the Hispanic and other minority communities in the State of Washington.               | Community Development                 | Children & Youth      | [http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=9087, null]    | [http://www.guidestar.org/profile/91-2105316, Guidestar]                                           | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | Returning | 
| 1487982787  | Seattle Children's Hospital and Research Foundation | Health (general)                   | 91-1156519                | 9002       | [http://seattlechildrens.org, null]          | Seattle Children's Hospital, Foundation and Research Institute together deliver superior patient care, advance new discoveries and treatments through pediatric research.   | Disease, Disorders & Medical Research | Children & Youth      | [http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=843, null]     | [null, null]                                                                                       | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | Returning | 
| 1487982787  | North Kitsap Fishline                               | Food & Hunger                      | 91-1244431                | 6821       | [http://www.nkfishline.org, null]            | Food bank providing temporary shelter for the homeless, food, rent, utilities, transportation and medical copays in North Kitsap County.                                    |                                       |                       | [http://www.sos.wa.gov/charities/search-app.aspx#/detail-charity/6630, null]  | [null, null]                                                                                       | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | Returning | 
| 1487982787  | PUP Dog Rescue                                      | Animals                            | 20-5054914                | 9745       | [http://www.PUPDogRescue.org, null]          | Our mission is to help homeless dogs and cats find homes. We also hope to enrich the lives of those who adopt them through our support programs.                            | Children & Youth                      | Community Development | [http://www.sos.wa.gov/charities/search-app.aspx#/detail-charity/32107, null] | [null, null]                                                                                       | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | Returning | 
| 1487982787  | Audubon Washington                                  | Environment                        | 13?1624102                | 2504       | [http://wa.audubon.org/, null]               | We work to protect birds and habitat through education, conservation action, community engagement and collaboration.                                                        |                                       |                       | [http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=3119, null]    | [null, null]                                                                                       | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | Returning | 
| 1487982787  | Freedom Project                                     | Education & Literacy               | 91-2129474                | 9632       | [http://www.freedomprojectseattle.org, null] | Transforming prisoners into peacemakers through teaching mindfulness and nonviolent communication is our work. Lives are transformed and communities are safer.             | Social & Economic Justice             | Community Development | [http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=23962, null]   | [http://www.guidestar.org/profile/91-2129474, Guidestar]                                           | [null, null]                                                                                                                                                                       | [null, null] | [null, null] | Returning | 
| 1487982787  | Cowgirl Spirit Equine Rescue                        | Animals                            | 20-3454564                | 9406       | [http://www.cowgirlspirit.org, null]         | Rescue, rehabilitate abused, neglected and slaughter bound horses. When the horse is ready we adopt them to their forever home                                              | Women                                 | Community Development | [http://www.sos.wa.gov/charities/search_detail.aspx?charity_id=23363, null]   | [http://www.guidestar.org/organization/20-345464/cowgirl-spirit-rescue-drill-team.aspx, Guidestar] | [http://www.charitynavigator.org/index.cfm?keyword_list=Cowgirl+Spirit+Equine+rescue&bay=search.results&EIN=&cgid=&cuid=&location=2&state=&city=&Submit=Submit, Charity Navigator] | [null, null] | [null, null] | Returning | 
```