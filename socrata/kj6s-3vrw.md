# Open Budget Application: Content Configurations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-budget-application-content-configurations-1fada) |
| Metadata | [Link](https://data.seattle.gov/api/views/kj6s-3vrw) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/kj6s-3vrw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/kj6s-3vrw/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | kj6s-3vrw |
| Name | Open Budget Application: Content Configurations |
| Category | Finance |
| Created | 2014-09-22T22:56:43Z |
| Publication Date | 2015-02-17T17:18:11Z |

## Description

data powering openbudget.seattle.gov

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | homepage    | homepage   | html      | html        |
| Yes      | series tag  | about_page  | about page | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kj6s-3vrw d:2015-02-17T09:17:41.000Z t:about_page="<p>On Monday, September 22, 2014,&nbsp;<a target=""_blank"" href=""http://www.seattle.gov/mayor/"">Seattle Mayor Ed&nbsp;Murray</a>&nbsp; presented to the City Council&nbsp;<a target=""_blank"" href=""http://www.seattle.gov/financedepartment/15proposedbudget/"">his proposed budget for 2015-16</a>&nbsp;that brings more innovation, better organization and better performance to City government, including this interactive online budget tool that provides greater transparency to Seattle residents.&nbsp;&nbsp;Use the graphs, charts and maps below to view and compare budget information down to a program level for all departments.&nbsp;For additional information on the Seattle 2015-2016 Proposed Budget visit&nbsp;<a target=""_blank"" href=""http://murray.seattle.gov/mayor-ed-murrays-2015-16-proposed-budget/#sthash.B7lzgfxb.dpbs"">Mayor Murray&rsquo;s 2015-16 Proposed Budget</a>.</p>
<p>&nbsp;</p>
<p>City Council will begin the hearings on the budget proposal on&nbsp;October 2nd.&nbsp;<a target=""_blank"" href=""http://www.seattlechannel.org/videos/video.asp?ID=1031411"">Watch Mayor Ed Murray&rsquo;s budget speech</a>.</p>" t:homepage="<p><span>On Monday, September 22, 2014,&nbsp;</span><a target=""_blank"" href=""http://www.seattle.gov/mayor/""><span>Seattle Mayor Ed&nbsp;Murray</span></a><span>&nbsp; presented to the City Council&nbsp;</span><a target=""_blank"" href=""http://www.seattle.gov/financedepartment/15proposedbudget/""><span>his proposed budget for 2015-16</span></a><span>&nbsp;that brings more innovation, better organization and better performance to City government. For additional information on the Seattle 2015-2016 Proposed Budget visit&nbsp;</span><a target=""_blank"" href=""http://murray.seattle.gov/mayor-ed-murrays-2015-16-proposed-budget/#sthash.B7lzgfxb.dpbs""><span>Mayor Murray&rsquo;s 2015-16 Proposed Budget</span></a><span> or watch the </span><a target=""_blank"" href=""http://www.seattlechannel.org/videos/video.asp?ID=1031411""><span>Mayor&rsquo;s budget speech</span></a><span>.</span></p>
<p>On November 24, 2014, following nearly two months of intensive review and discussion, the Seattle City Council approved the 2015 Adopted and 2016 Endorsed Budget by a vote of 8-1.</p>
<p>The <a target=""_blank"" href=""http://www.seattle.gov/financedepartment/15adoptedbudget/default.htm"">detailed budget book is available in PDF form</a>, however you can also use <span>this interactive budget tool aimed at providing greater transparency to Seattle residents.&nbsp;</span>This tool helps the public analyze and understand how the City allocates and spends its funding in a highly intuitive and visualized way.</p>
<p><span>Use the graphs, charts, and maps below to view and compare budget information down to a program level for all departments.&nbsp;</span></p>" m:row_number.kj6s-3vrw=1
```

## Meta Commands

```ls
metric m:row_number.kj6s-3vrw p:long l:"Row Number"

entity e:kj6s-3vrw l:"Open Budget Application: Content Configurations" t:url=https://data.seattle.gov/api/views/kj6s-3vrw

property e:kj6s-3vrw t:meta.view v:id=kj6s-3vrw v:category=Finance v:averageRating=0 v:name="Open Budget Application: Content Configurations"

property e:kj6s-3vrw t:meta.view.license v:name="Public Domain"

property e:kj6s-3vrw t:meta.view.owner v:id=fycv-rw8e v:screenName="Jacob Rhoades" v:displayName="Jacob Rhoades"

property e:kj6s-3vrw t:meta.view.tableauthor v:id=fycv-rw8e v:screenName="Jacob Rhoades" v:displayName="Jacob Rhoades"
```

## Top Records

```ls
| :updated_at | homepage                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | about_page                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| =========== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1424164661  | On Monday, September 22, 2014, Seattle Mayor Ed Murray  presented to the City Council his proposed budget for 2015-16 that brings more innovation, better organization and better performance to City government. For additional information on the Seattle 2015-2016 Proposed Budget visit Mayor Murray?s 2015-16 Proposed Budget or watch the Mayor?s budget speech.
On November 24, 2014, following nearly two months of intensive review and discussion, the Seattle City Council approved the 2015 Adopted and 2016 Endorsed Budget by a vote of 8-1.
The detailed budget book is available in PDF form, however you can also use this interactive budget tool aimed at providing greater transparency to Seattle residents. This tool helps the public analyze and understand how the City allocates and spends its funding in a highly intuitive and visualized way.
Use the graphs, charts, and maps below to view and compare budget information down to a program level for all departments.  | On Monday, September 22, 2014, Seattle Mayor Ed Murray  presented to the City Council his proposed budget for 2015-16 that brings more innovation, better organization and better performance to City government, including this interactive online budget tool that provides greater transparency to Seattle residents.  Use the graphs, charts and maps below to view and compare budget information down to a program level for all departments. For additional information on the Seattle 2015-2016 Proposed Budget visit Mayor Murray?s 2015-16 Proposed Budget.
  City Council will begin the hearings on the budget proposal on October 2nd. Watch Mayor Ed Murray?s budget speech. | 
```