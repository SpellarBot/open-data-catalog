# State of Iowa Accountable Government Act Reports and Plans

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-iowa-accountable-government-act-reports-and-plans) |
| Metadata | [Link](https://data.iowa.gov/api/views/b2q5-faxg) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/b2q5-faxg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/b2q5-faxg/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | b2q5-faxg |
| Name | State of Iowa Accountable Government Act Reports and Plans |
| Attribution | Iowa Department of Management |
| Category | Government |
| Tags | state agencies, performance reports, performance plans, strategic plans, aga, accountable government act |
| Created | 2014-12-10T17:30:23Z |
| Publication Date | 2017-03-29T00:42:04Z |

## Description

The Iowa Department of Management is responsible for implementing and administering the state's Performance Management System established in 2001 through the Iowa Accountable Government Act. Iowa's performance management system provides a framework for actively using performance data to improve state government results so we can better serve customers. This framework ensures executive branch state agencies have sound performance planning and reporting, strategic planning and proven results.   Agency strategic plans identify essential goals, strategies, and measures to guide progress in achieving the department's vision and mission as well as define how the agency contributes to achievement of the enterprise goals.  Agency performance plans look at the agency's mission (the purpose or why the agency exists) and define the operations (core functions and key services, products and/or activities) that are in place to achieve that mission.  Agency performance reports compare actual performance with projected levels for key areas outlined in the agency strategic plan and the agency performance plan.  Agency performance plans are due to the Iowa Department of Management on December 15th for the preceding fiscal year.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type      | Render Type    |
| ======== | =========== | ============= | ============= | ============== | ============== |
| Yes      | time        | fiscal_year   | Fiscal Year   | number         | number         |
| Yes      | series tag  | document_type | Document Type | drop_down_list | drop_down_list |
| Yes      | series tag  | agency        | Agency        | text           | drop_down_list |
| Yes      | series tag  | report        | Document      | document       | document       |
| Yes      | series tag  | link          | Link          | url            | url            |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:b2q5-faxg l:"State of Iowa Accountable Government Act Reports and Plans" t:attribution="Iowa Department of Management" t:url=https://data.iowa.gov/api/views/b2q5-faxg

property e:b2q5-faxg t:meta.view v:id=b2q5-faxg v:category=Government v:averageRating=0 v:name="State of Iowa Accountable Government Act Reports and Plans" v:attribution="Iowa Department of Management"

property e:b2q5-faxg t:meta.view.license v:name="Public Domain"

property e:b2q5-faxg t:meta.view.owner v:id=gpbe-z67d v:profileImageUrlMedium=/api/users/gpbe-z67d/profile_images/THUMB v:profileImageUrlLarge=/api/users/gpbe-z67d/profile_images/LARGE v:screenName="IDOM, Performance Results" v:profileImageUrlSmall=/api/users/gpbe-z67d/profile_images/TINY v:displayName="IDOM, Performance Results"

property e:b2q5-faxg t:meta.view.tableauthor v:id=gpbe-z67d v:profileImageUrlMedium=/api/users/gpbe-z67d/profile_images/THUMB v:profileImageUrlLarge=/api/users/gpbe-z67d/profile_images/LARGE v:screenName="IDOM, Performance Results" v:profileImageUrlSmall=/api/users/gpbe-z67d/profile_images/TINY v:roleName=editor v:displayName="IDOM, Performance Results"
```

## Top Records

```ls
| fiscal_year | document_type | agency    | report                                                                                                                 | link         | 
| =========== | ============= | ========= | ====================================================================================================================== | ============ | 
| 2006        | tah6-iari     | ybnd-59e8 | [application/pdf; charset=binary, f6nNQUOy8dvCjyKiVcJ5O7Ww4qn_0gRIsbaGiWggbx0, Commerce_Credit_Union_2006.pdf, 77848]  | [null, null] | 
| 2009        | tah6-iari     | ybnd-59e8 | [application/pdf; charset=binary, 0P4bp3kMuRi139VI_gYjvgHTDSXLv2cKQMv-lIKMMeI, Commerce_Credit_Union_2009.pdf, 154571] | [null, null] | 
| 2006        | tah6-iari     | 5zsf-vecq | [application/pdf; charset=binary, 9kgKJCPf327nGi_qJma81a7VDaRNkH1CPYUK-xp-CwM, Civil_Rights_2006.pdf, 230183]          | [null, null] | 
| 2008        | tah6-iari     | 5zsf-vecq | [application/pdf; charset=binary, djfk_O0vHp6lc5swQLOgoJeyuWr86W-YFrwjqsMVSfc, Civil_Rights_2008.pdf, 244678]          | [null, null] | 
| 2009        | tah6-iari     | 5zsf-vecq | [application/pdf; charset=binary, SccO_BezMBIYh31GnhsItS_1j3tUpzliwGB_8ALRPKs, Civil_Rights_2009.pdf, 363164]          | [null, null] | 
| 2010        | tah6-iari     | 5zsf-vecq | [application/pdf; charset=binary, 3Z2D4whQ0gJNI6JrqSMaDWodqxlId63CT-G85VgyiMQ, Civil_Rights_2010.pdf, 122923]          | [null, null] | 
| 2011        | tah6-iari     | 5zsf-vecq | [application/pdf; charset=binary, Z7i69RPcz6KxBdWLM3qW2DcNBQ8OT0HEESp_C1_SYKs, Civil_Rights_2011.pdf, 590079]          | [null, null] | 
| 2012        | tah6-iari     | 5zsf-vecq | [application/pdf; charset=binary, LhkGnkI7UGuJE8JMCwt2YyI_U1gdTvQjDtOjuxpPJ9M, Civil_Rights_2012.pdf, 768059]          | [null, null] | 
| 2013        | tah6-iari     | rpq5-auu7 | [application/pdf; charset=binary, Kw_16luah7SWdJJWbNmnHS_rhdP6Gocrpci59d0guE4, Commerce_Insurance_2013.pdf, 171053]    | [null, null] | 
| 2006        | tah6-iari     | 6hja-hdxz | [application/pdf; charset=binary, VF08C5Pcaslt0BhcGbBNhcnMROVk3Fo8bwKpBPXd4b0, Cultural_Affairs_2006.pdf, 221782]      | [null, null] | 
```