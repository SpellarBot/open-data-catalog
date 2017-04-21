# Contract Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contract-data) |
| Metadata | [Link](https://data.oregon.gov/api/views/h3a5-bh3f) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/h3a5-bh3f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/h3a5-bh3f/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | h3a5-bh3f |
| Name | Contract Data |
| Created | 2016-10-12T17:36:05Z |
| Publication Date | 2016-11-23T16:38:00Z |

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | service_category     | Service Category     | text      | text        |
| Yes      | series tag  | service_name         | Service Name         | text      | text        |
| Yes      | series tag  | products_services    | Products Services    | text      | text        |
| Yes      | series tag  | vendor               | Vendor               | text      | text        |
| Yes      | series tag  | contract_information | Contract Information | html      | html        |
| Yes      | series tag  | expiration           | Expiration           | text      | text        |
| Yes      | series tag  | mtrics               | Metrics              | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:h3a5-bh3f d:2016-11-23T16:37:36.000Z t:contract_information="<a href=""http://orpin.oregon.gov/open.dll/submitLogin?disID=1837607"" target=""_blank"">Contract Information</a>" t:service_category="Business Management" t:expiration=7/16/2020 t:mtrics="<a><div class=""tableauPlaceholder"" style=""width: 564px; height: 669px; position: relative; overflow: hidden; display: block;""><noscript><a href='https:&#47;&#47;interworks.co.uk&#47;blog&#47;url-parameters-tableau&#47;'><img alt='Parameter Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;PADBSample1&#47;Dashboard1&#47;1_rss.png' style='border: none'/></a></noscript><iframe frameborder=""0"" marginheight=""0"" marginwidth=""0"" allowtransparency=""true"" allowfullscreen=""true"" class=""tableauViz"" height=""669"" style=""display: block; margin: 0px; padding: 0px; border: none; width: 564px; height: 669px;"" width=""564"" src=""https://public.tableau.com/views/PADBSample1/Dashboard1?:embed=y&:showVizHome=no&:host_url=https%3A%2F%2Fpublic.tableau.com%2F&:tabs=no&:toolbar=yes&:animate_transition=yes&:display_static_image=no&:display_spinner=no&:display_overlay=yes&:display_count=yes&:loadOrderID=0&KNo=0450""></iframe></div></a>" t:vendor="BCA Services" t:service_name=Laptops t:products_services="No installing" m:row_number.h3a5-bh3f=1

series e:h3a5-bh3f d:2016-11-23T16:37:36.000Z t:contract_information="<a href=""http://orpin.oregon.gov/open.dll/submitLogin?disID=1837607"" target=""_blank"">Contract Information</a>" t:service_category=Networking t:expiration=8/25/2026 t:mtrics="<a><div class=""tableauPlaceholder"" style=""width: 564px; height: 669px; position: relative; overflow: hidden; display: block;""><noscript><a href='https:&#47;&#47;interworks.co.uk&#47;blog&#47;url-parameters-tableau&#47;'><img alt='Parameter Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;PADBSample1&#47;Dashboard1&#47;1_rss.png' style='border: none'/></a></noscript><iframe frameborder=""0"" marginheight=""0"" marginwidth=""0"" allowtransparency=""true"" allowfullscreen=""true"" class=""tableauViz"" height=""669"" style=""display: block; margin: 0px; padding: 0px; border: none; width: 564px; height: 669px;"" width=""564"" src=""https://public.tableau.com/views/PADBSample1/Dashboard1?:embed=y&:showVizHome=no&:host_url=https%3A%2F%2Fpublic.tableau.com%2F&:tabs=no&:toolbar=yes&:animate_transition=yes&:display_static_image=no&:display_spinner=no&:display_overlay=yes&:display_count=yes&:loadOrderID=0&KNo=0450""></iframe></div></a>" t:vendor="CAB Services" t:service_name=Applications t:products_services=Removing m:row_number.h3a5-bh3f=2

series e:h3a5-bh3f d:2016-11-23T16:37:36.000Z t:contract_information="<a href=""http://orpin.oregon.gov/open.dll/submitLogin?disID=1837607"" target=""_blank"">Contract Information</a>" t:service_category="Business Management" t:expiration=6/12/2016 t:mtrics="<a><div class=""tableauPlaceholder"" style=""width: 564px; height: 669px; position: relative; overflow: hidden; display: block;""><noscript><a href='https:&#47;&#47;interworks.co.uk&#47;blog&#47;url-parameters-tableau&#47;'><img alt='Parameter Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pa&#47;PADBSample1&#47;Dashboard1&#47;1_rss.png' style='border: none'/></a></noscript><iframe frameborder=""0"" marginheight=""0"" marginwidth=""0"" allowtransparency=""true"" allowfullscreen=""true"" class=""tableauViz"" height=""669"" style=""display: block; margin: 0px; padding: 0px; border: none; width: 564px; height: 669px;"" width=""564"" src=""https://public.tableau.com/views/PADBSample1/Dashboard1?:embed=y&:showVizHome=no&:host_url=https%3A%2F%2Fpublic.tableau.com%2F&:tabs=no&:toolbar=yes&:animate_transition=yes&:display_static_image=no&:display_spinner=no&:display_overlay=yes&:display_count=yes&:loadOrderID=0&KNo=0450""></iframe></div></a>" t:vendor="ABC Services" t:service_name="Netwrok Cable Install" t:products_services="Installing the networkcable" m:row_number.h3a5-bh3f=3
```

## Meta Commands

```ls
metric m:row_number.h3a5-bh3f p:long l:"Row Number"

entity e:h3a5-bh3f l:"Contract Data" t:url=https://data.oregon.gov/api/views/h3a5-bh3f

property e:h3a5-bh3f t:meta.view v:id=h3a5-bh3f v:averageRating=0 v:name="Contract Data"

property e:h3a5-bh3f t:meta.view.owner v:id=yr5y-ep82 v:profileImageUrlMedium=/api/users/yr5y-ep82/profile_images/THUMB v:profileImageUrlLarge=/api/users/yr5y-ep82/profile_images/LARGE v:screenName="Jason Rood" v:profileImageUrlSmall=/api/users/yr5y-ep82/profile_images/TINY v:displayName="Jason Rood"

property e:h3a5-bh3f t:meta.view.tableauthor v:id=yr5y-ep82 v:profileImageUrlMedium=/api/users/yr5y-ep82/profile_images/THUMB v:profileImageUrlLarge=/api/users/yr5y-ep82/profile_images/LARGE v:screenName="Jason Rood" v:profileImageUrlSmall=/api/users/yr5y-ep82/profile_images/TINY v:roleName=publisher v:displayName="Jason Rood"
```

## Top Records

```ls
| :updated_at | service_category    | service_name          | products_services           | vendor       | contract_information | expiration | mtrics | 
| =========== | =================== | ===================== | =========================== | ============ | ==================== | ========== | ====== | 
| 1479919056  | Business Management | Laptops               | No installing               | BCA Services | Contract Information | 7/16/2020  |        | 
| 1479919056  | Networking          | Applications          | Removing                    | CAB Services | Contract Information | 8/25/2026  |        | 
| 1479919056  | Business Management | Netwrok Cable Install | Installing the networkcable | ABC Services | Contract Information | 6/12/2016  |        | 
| 1479919056  | Networking          | Laptops               | No installing               | BCA Services | Contract Information | 7/16/2020  |        | 
| 1479919056  | Business Management | Applications          | Removing                    | CAB Services | Contract Information | 8/25/2026  |        | 
| 1479919056  | Networking          | Netwrok Cable Install | Installing the networkcable | ABC Services | Contract Information | 6/12/2016  |        | 
| 1479919056  | Business Management | Laptops               | No installing               | BCA Services | Contract Information | 7/16/2020  |        | 
| 1479919056  | Networking          | Applications          | Removing                    | CAB Services | Contract Information | 8/25/2026  |        | 
| 1479919056  | Business Management | Netwrok Cable Install | Installing the networkcable | ABC Services | Contract Information | 6/12/2016  |        | 
| 1479919056  | Networking          | Laptops               | No installing               | BCA Services | Contract Information | 7/16/2020  |        | 
```