# PARC board and consultants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parc-board-and-consultants-9b861) |
| Metadata | [Link](https://data.oregon.gov/api/views/tigq-4sxk) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/tigq-4sxk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/tigq-4sxk/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | tigq-4sxk |
| Name | PARC board and consultants |
| Category | Natural Resources |
| Tags | parc |
| Created | 2014-04-18T17:23:32Z |
| Publication Date | 2017-01-19T17:52:54Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | name                    | Name                    | text      | text        |
| Yes      | series tag  | title                   | Position with PARC      | text      | text        |
| Yes      | series tag  | phone_number_2          | Phone number            | text      | text        |
| Yes      | series tag  | email                   | Email                   | email     | email       |
| Yes      | series tag  | fax_2                   | FAX                     | text      | text        |
| Yes      | series tag  | title_with_organization | Title with organization | text      | text        |
| Yes      | series tag  | organization            | Organization            | text      | text        |
| No       |             | address                 | Address                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:tigq-4sxk d:2015-10-20T14:50:51.000Z t:fax_2="(503) 986-4735" t:organization="Oregon Department of Agriculture" t:title="Board Administrator" t:email=rjaindl@oda.state.or.us t:name="Ray Jaindl" t:phone_number_2="(503) 986-4713" t:title_with_organization="Program Administrator, Natural Resources and Pesticides programs" m:row_number.tigq-4sxk=1

series e:tigq-4sxk d:2015-10-20T14:50:58.000Z t:fax_2="(503) 693-4999" t:organization="Environmental Assessment Division, Department of Environmental Quality" t:title=Representative t:email=boling.brian@deq.state.or.us t:name="Brian Boling" t:phone_number_2="(503) 693-5745" t:title_with_organization="Laboratory Program Manager" m:row_number.tigq-4sxk=2

series e:tigq-4sxk d:2015-10-20T14:51:00.000Z t:fax_2="(503) 693-4999" t:organization="Oregon OSHA/Salem Field Office" t:title=Representative t:email=garnet.r.cooke@state.or.us t:name="Garnet Cooke" t:phone_number_2="(503) 378-3274" t:title_with_organization="Pesticide Coordinator" m:row_number.tigq-4sxk=3
```

## Meta Commands

```ls
metric m:row_number.tigq-4sxk p:long l:"Row Number"

entity e:tigq-4sxk l:"PARC board and consultants" t:url=https://data.oregon.gov/api/views/tigq-4sxk

property e:tigq-4sxk t:meta.view v:id=tigq-4sxk v:category="Natural Resources" v:averageRating=0 v:name="PARC board and consultants"

property e:tigq-4sxk t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:tigq-4sxk t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| :updated_at | name                         | title                    | phone_number_2 | email                         | fax_2          | title_with_organization                                          | organization                                                           | address                                                                                      | 
| =========== | ============================ | ======================== | ============== | ============================= | ============== | ================================================================ | ====================================================================== | ============================================================================================ | 
| 1445352651  | Ray Jaindl                   | Board Administrator      | (503) 986-4713 | rjaindl@oda.state.or.us       | (503) 986-4735 | Program Administrator, Natural Resources and Pesticides programs | Oregon Department of Agriculture                                       | 635 Capitol St. NE, Salem, OR 97301-0110                                                     | 
| 1445352658  | Brian Boling                 | Representative           | (503) 693-5745 | boling.brian@deq.state.or.us  | (503) 693-4999 | Laboratory Program Manager                                       | Environmental Assessment Division, Department of Environmental Quality | 3150 NW 229th Ave., Suite 150, Hillsboro, OR 97124                                           | 
| 1445352660  | Garnet Cooke                 | Representative           | (503) 378-3274 | garnet.r.cooke@state.or.us    | (503) 693-4999 | Pesticide Coordinator                                            | Oregon OSHA/Salem Field Office                                         | PO Box 14513; 1340 Tandem Ave. NE, Suite 160, Salem, OR 97309                                | 
| 1445352661  | Danette Faucera              | Representative           | (503) 947-6092 | danette.l.faucera@state.or.us | (503) 947-6202 | Water Policy Coordinator                                         | Oregon Department of Fish and Wildlife                                 | 4034 Fairview Industrial Drive SE, Salem, OR 97302                                           | 
| 1445352662  | Sandy Giffin, RN             | Representative           | (503) 494-8600 | giffin@ohsu.edu               | (503) 494-4980 | Director                                                         | Oregon Poison Control Center                                           | 3181 SW Sam Jackson Park Road; mail code-CSB, Portland, OR 97201-3098                        | 
| 1445352670  | Fred W. Berman, D.V.M., PhD. | Consultant               | (503) 494-7366 | bermanf@ohsu.edu              | (503) 494-4278 | Director, Toxicology Information Center                          | Oregon Institute of Occupational Health Sciences                       | 3181 SW Sam Jackson Park Road, Portland, OR 97201-3098                                       | 
| 1445352672  | Jeff Jenkins, Ph.D.          | Consultant               | (541) 737-5993 | jenkinsj@ace.orst.edu         |                |                                                                  | Environmental & Molecular Tox Dept.                                    | Oregon State University, 333 Weniger Hall, Oregon State University, Corvallis, OR 97331-7301 | 
| 1445352789  | Jennifer Gervais, PhD        | Community representative |                | jen@oregonwildlife.org        |                | Community member                                                 | Oregon Wildlife Institute                                              | PO Box 1061, Corvallis, OR 97339                                                             | 
| 1445355239  | Theodore Bunch Jr.           | Board Co-Chair           | (503) 986-6470 | PARC@oda.state.or.us          | (503) 986-4735 | PARC Coordination Team Leader                                    | Oregon Department of Agriculture                                       | 635 Capitol St. NE, Salem, OR 97301                                                          | 
| 1454601468  | Curtis Cude                  | Board Co-Chair           | (971) 673-0975 | curtis.g.cude@state.or.us     |                | Manager                                                          | Environmental Public Health Surveillance Program                       | 800 NE Oregon St., Suite 640, Portland, OR 97232                                             | 
```