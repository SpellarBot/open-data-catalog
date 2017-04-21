# Oregon InC Grants and Loans FY2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-inc-grants-and-loans-fy2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/5rri-u7xe) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/5rri-u7xe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/5rri-u7xe/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 5rri-u7xe |
| Name | Oregon InC Grants and Loans FY2016 |
| Attribution | Business Oregon |
| Category | Revenue & Expense |
| Tags | transparency, oregon inc, grant, loan, fiscal year 2016 report |
| Created | 2016-10-06T14:32:03Z |
| Publication Date | 2016-10-06T18:17:58Z |

## Description

Fiscal Year 2016 (annual) grants or loans from the Oregon Innovation Council (Oregon InC) under ORS 284.735 (Oregon Commercialization Research Fund) or ORS 284.742 (Oregon Innovation Fund). For more information visit www.oregon4biz.com/Innovate-&-Create/Oregon-InC/About/

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                          | Data Type | Render Type |
| ======== | ============== | ============================================= | ============================================= | ========= | =========== |
| Yes      | series tag     | names_of_persons_who_received_a_grant_or_loan | Names of persons who received a grant or loan | text      | text        |
| Yes      | series tag     | type_of_fund                                  | Type of Fund                                  | text      | text        |
| Yes      | series tag     | grant_or_loan                                 | Grant or Loan                                 | text      | text        |
| Yes      | numeric metric | amount                                        | Amount                                        | money     | money       |
| Yes      | series tag     | purpose                                       | Purpose                                       | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5rri-u7xe d:2016-01-01T00:00:00.000Z t:type_of_fund="Oregon Innovation Fund" t:grant_or_loan=Grant t:purpose="To support a signature research center to maximize collaborative ventures among research institutions, the federal government and private industry will capitalize on opportunities to obtain private and federal funding for research and development to enhance nano-and micro-technology research competencies within Oregon universities and industries and to commercialize research into Oregon products and businesses." t:names_of_persons_who_received_a_grant_or_loan="Oregon Nanoscience and Microtechnologies Institute" m:amount=5995325

series e:5rri-u7xe d:2016-01-01T00:00:00.000Z t:type_of_fund="Oregon Innovation Fund" t:grant_or_loan=Grant t:purpose="To finance the administrative costs of Drive Oregon and the costs incurred by Recipient to promote the development and commercialization of the electric vehicle industry, including electric vehicle technologies and components." t:names_of_persons_who_received_a_grant_or_loan="Drive Oregon" m:amount=750000

series e:5rri-u7xe d:2016-01-01T00:00:00.000Z t:type_of_fund="Oregon Innovation Fund" t:grant_or_loan=Grant t:purpose="To support a signature research center to maximize collaborative ventures among research institutions, the federal government and private industry will capitalize on opportunities to obtain private and federal funding to enhance therapeutic, vaccine and diagnostic research competencies within Oregon universities and industries and to develop research results into Oregon products and businesses." t:names_of_persons_who_received_a_grant_or_loan="Oregon Translational Research and Development Institute" m:amount=1989700
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:5rri-u7xe l:"Oregon InC Grants and Loans FY2016" t:attribution="Business Oregon" t:url=https://data.oregon.gov/api/views/5rri-u7xe

property e:5rri-u7xe t:meta.view v:id=5rri-u7xe v:category="Revenue & Expense" v:attributionLink=http://www.oregon4biz.com v:averageRating=0 v:name="Oregon InC Grants and Loans FY2016" v:attribution="Business Oregon"

property e:5rri-u7xe t:meta.view.owner v:id=ewcx-ibs2 v:profileImageUrlMedium=/api/users/ewcx-ibs2/profile_images/THUMB v:profileImageUrlLarge=/api/users/ewcx-ibs2/profile_images/LARGE v:screenName=carmens v:profileImageUrlSmall=/api/users/ewcx-ibs2/profile_images/TINY v:displayName=carmens

property e:5rri-u7xe t:meta.view.tableauthor v:id=ewcx-ibs2 v:profileImageUrlMedium=/api/users/ewcx-ibs2/profile_images/THUMB v:profileImageUrlLarge=/api/users/ewcx-ibs2/profile_images/LARGE v:screenName=carmens v:profileImageUrlSmall=/api/users/ewcx-ibs2/profile_images/TINY v:roleName=editor v:displayName=carmens
```

## Top Records

```ls
| names_of_persons_who_received_a_grant_or_loan                | type_of_fund           | grant_or_loan | amount  | purpose                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| ============================================================ | ====================== | ============= | ======= | ============================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| Oregon Nanoscience and Microtechnologies Institute           | Oregon Innovation Fund | Grant         | 5995325 | To support a signature research center to maximize collaborative ventures among research institutions, the federal government and private industry will capitalize on opportunities to obtain private and federal funding for research and development to enhance nano-and micro-technology research competencies within Oregon universities and industries and to commercialize research into Oregon products and businesses. | 
| Drive Oregon                                                 | Oregon Innovation Fund | Grant         | 750000  | To finance the administrative costs of Drive Oregon and the costs incurred by Recipient to promote the development and commercialization of the electric vehicle industry, including electric vehicle technologies and components.                                                                                                                                                                                             | 
| Oregon Translational Research and Development Institute      | Oregon Innovation Fund | Grant         | 1989700 | To support a signature research center to maximize collaborative ventures among research institutions, the federal government and private industry will capitalize on opportunities to obtain private and federal funding to enhance therapeutic, vaccine and diagnostic research competencies within Oregon universities and industries and to develop research results into Oregon products and businesses.                  | 
| Oregon Wave Energy Trust                                     | Oregon Innovation Fund | Grant         | 450000  | To finance the administrative costs of Recipient and the costs incurred by Recipient to promote the wave energy industry and the development of wave energy technologies.                                                                                                                                                                                                                                                      | 
| Oregon Built Environment and Sustainable Technologies Center | Oregon Innovation Fund | Grant         | 5923956 | To support a signature research center to maximize collaborative ventures among research institutions, the federal government and private industry will capitalize on opportunities to obtain private and federal funding for research and development in order to enhance clean technology research competencies within Oregon universities and industries and to commercialize research into Oregon products and businesses. | 
| SOAR Oregon                                                  | Oregon Innovation Fund | Grant         | 3000000 | To finance the administrative costs of Recipient and the costs incurred by Recipient to promote the development and commercialization of the unmanned aerial systems industry in Oregon.                                                                                                                                                                                                                                       | 
```