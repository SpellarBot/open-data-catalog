# Council Committee Meeting Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/council-committee-meeting-data) |
| Metadata | [Link](https://data.austintexas.gov/api/views/uv94-fems) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/uv94-fems/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/uv94-fems/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | uv94-fems |
| Name | Council Committee Meeting Data |
| Category | Government |
| Created | 2016-08-17T20:41:12Z |
| Publication Date | 2016-08-17T20:51:05Z |

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | committee_name    | Committee_Name    | text          | text          |
| Yes      | time        | meetingdate       | MeetingDate       | calendar_date | calendar_date |
| Yes      | series tag  | itemno            | ItemNo            | text          | text          |
| Yes      | series tag  | postinglanguage   | PostingLanguage   | text          | text          |
| Yes      | series tag  | linktosire        | LinkToSIRE        | url           | url           |
| Yes      | series tag  | linktomeetingpage | LinktoMeetingPage | url           | url           |
| Yes      | series tag  | linktoitem        | LinkToItem        | url           | url           |
```

## Time Field

```ls
Value = meetingdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:uv94-fems d:2016-01-11T00:00:00.000Z t:linktoitem=http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC001 t:committee_name="Economic Opportunity Committee" t:linktomeetingpage=http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm t:itemno=EOC001 t:postinglanguage="Approve the minutes of the Economic Opportunity Committee Meeting of December 14, 2015." t:linktosire="https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda" m:row_number.uv94-fems=1

series e:uv94-fems d:2016-01-11T00:00:00.000Z t:linktoitem=http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC002 t:committee_name="Economic Opportunity Committee" t:linktomeetingpage=http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm t:itemno=EOC002 t:postinglanguage="The first five speakers signed up prior to the meeting being called to order will each be allowed three minutes to address their concerns regarding items not posted on the agenda." t:linktosire="https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda" m:row_number.uv94-fems=2

series e:uv94-fems d:2016-01-11T00:00:00.000Z t:linktoitem=http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC003 t:committee_name="Economic Opportunity Committee" t:linktomeetingpage=http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm t:itemno=EOC003 t:postinglanguage="Briefing by the Austin Technology Council regarding the partnership between the City of Austin and the Austin Technology Council." t:linktosire="https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda" m:row_number.uv94-fems=3
```

## Meta Commands

```ls
metric m:row_number.uv94-fems p:long l:"Row Number"

entity e:uv94-fems l:"Council Committee Meeting Data" t:url=https://data.austintexas.gov/api/views/uv94-fems

property e:uv94-fems t:meta.view v:id=uv94-fems v:category=Government v:averageRating=0 v:name="Council Committee Meeting Data"

property e:uv94-fems t:meta.view.owner v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:displayName="Kathryn Darnall"

property e:uv94-fems t:meta.view.tableauthor v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```

## Top Records

```ls
| committee_name                    | meetingdate         | itemno  | postinglanguage                                                                                                                                                                           | linktosire                                                                                    | linktomeetingpage                                                                 | linktoitem                                                                                | 
| ================================= | =================== | ======= | ========================================================================================================================================================================================= | ============================================================================================= | ================================================================================= | ========================================================================================= | 
| Economic Opportunity Committee    | 2016-01-11T00:00:00 | EOC001  | Approve the minutes of the Economic Opportunity Committee Meeting of December 14, 2015.                                                                                                   | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm, null]  | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC001, null]   | 
| Economic Opportunity Committee    | 2016-01-11T00:00:00 | EOC002  | The first five speakers signed up prior to the meeting being called to order will each be allowed three minutes to address their concerns regarding items not posted on the agenda.       | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm, null]  | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC002, null]   | 
| Economic Opportunity Committee    | 2016-01-11T00:00:00 | EOC003  | Briefing by the Austin Technology Council regarding the partnership between the City of Austin and the Austin Technology Council.                                                         | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm, null]  | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC003, null]   | 
| Economic Opportunity Committee    | 2016-01-11T00:00:00 | EOC004  | Presentation by the Small and Minority Business Resources Department regarding the status of the Minority, Women and Veteran-Owned Business Enterprise (MBE/WBE and VBE) Disparity Study. | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm, null]  | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC004, null]   | 
| Economic Opportunity Committee    | 2016-01-11T00:00:00 | EOC005  | Briefing and discussion of the Minority and Women-Owned Business Enterprise (MBE/WBE) Quarterly Update.                                                                                   | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm, null]  | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC005, null]   | 
| Economic Opportunity Committee    | 2016-01-11T00:00:00 | EOC006  | Briefing by the Austin Technology Incubator's Bioscience and Wireless incubators program of the University of Texas IC2 Institute.                                                        | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1046&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm, null]  | [http://www.austintexas.gov/department/city-council/2016/20160111-EOC.htm#EOC006, null]   | 
| Council Transition Work Group     | 2016-01-12T00:00:00 | CTWG001 | Discuss topics related to council procedures and processes.                                                                                                                               | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1055&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160112-CTWG.htm, null] | [http://www.austintexas.gov/department/city-council/2016/20160112-CTWG.htm#CTWG001, null] | 
| Council Transition Work Group     | 2016-01-12T00:00:00 | CTWG002 | Update on the activities of the Public Engagement Task Force.                                                                                                                             | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1055&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160112-CTWG.htm, null] | [http://www.austintexas.gov/department/city-council/2016/20160112-CTWG.htm#CTWG002, null] | 
| Health & Human Services Committee | 2016-01-13T00:00:00 | HHSC001 | Approve the minutes of the Health and Human Services Committee meeting of December 11, 2015.                                                                                              | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1028&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160113-HHSC.htm, null] | [http://www.austintexas.gov/department/city-council/2016/20160113-HHSC.htm#HHSC001, null] | 
| Health & Human Services Committee | 2016-01-13T00:00:00 | HHSC002 | Speakers signed up prior to the meeting being called to order will each be allowed two minutes to address their concerns regarding items not posted on the agenda (limit of 10 speakers). | [https://austin.siretechnologies.com/sirepub/mtgviewer.aspx?meetid=1028&doctype=Agenda, null] | [http://www.austintexas.gov/department/city-council/2016/20160113-HHSC.htm, null] | [http://www.austintexas.gov/department/city-council/2016/20160113-HHSC.htm#HHSC002, null] | 
```