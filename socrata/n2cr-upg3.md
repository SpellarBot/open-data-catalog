# 2016 Adopted Budget Attachment A

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-adopted-budget-attachment-a) |
| Metadata | [Link](https://data.seattle.gov/api/views/n2cr-upg3) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/n2cr-upg3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/n2cr-upg3/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | n2cr-upg3 |
| Name | 2016 Adopted Budget Attachment A |
| Attribution | City of Seattle |
| Category | Finance |
| Tags | 2016 adopted budget attachment |
| Created | 2016-08-04T20:52:27Z |
| Publication Date | 2016-08-04T21:20:42Z |

## Description

2016 Adopted Budget Attachment A

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | fund                    | Fund                    | text      | text        |
| Yes      | series tag     | appropriatingdepartment | AppropriatingDepartment | text      | text        |
| Yes      | series tag     | fund_code               | Fund Code               | text      | number      |
| Yes      | series tag     | summit_code             | Summit Code             | text      | text        |
| Yes      | series tag     | bclrs_code              | BCLRS Code              | text      | text        |
| Yes      | series tag     | bcl_name                | BCL Name                | text      | text        |
| Yes      | series tag     | bcl_purpose             | BCL Purpose             | text      | text        |
| Yes      | numeric metric | 2016_appropriation      | 2016 Appropriation      | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:n2cr-upg3 d:2016-01-01T00:00:00.000Z t:fund_code=100 t:summit_code=CZ000 t:bcl_purpose="The purpose of the City Budget Office Budget Control Level is to develop and monitor the budget, carrying out budget-related functions, oversee financial policies and plans, and provide financial and other strategic analysis." t:bclrs_code=00100-CZ000 t:appropriatingdepartment=Executive t:fund="General Subfund" t:bcl_name="City Budget Office" m:2016_appropriation=5895076

series e:n2cr-upg3 d:2016-01-01T00:00:00.000Z t:fund_code=100 t:summit_code=VJ100 t:bcl_purpose="The purpose of the Jail Services Budget Control Level is to provide for the booking, housing, transporting, and guarding of City inmates.  The jail population, for which the City pays, are adults charged with or convicted of misdemeanor crimes alleged to have been committed within the Seattle city limits." t:bclrs_code=00100-VJ100 t:appropriatingdepartment=Executive t:fund="General Subfund" t:bcl_name="Jail Services" m:2016_appropriation=17087312

series e:n2cr-upg3 d:2016-01-01T00:00:00.000Z t:fund_code=100 t:summit_code=VJ500 t:bcl_purpose="The purpose of the Indigent Defense Services Budget Control Level is to secure legal defense services, as required by State law, for indigent people facing criminal charges in Seattle Municipal Court." t:bclrs_code=00100-VJ500 t:appropriatingdepartment=Executive t:fund="General Subfund" t:bcl_name="Indigent Defense Services" m:2016_appropriation=7333471
```

## Meta Commands

```ls
metric m:2016_appropriation p:integer l:"2016 Appropriation" t:dataTypeName=number

entity e:n2cr-upg3 l:"2016 Adopted Budget Attachment A" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/n2cr-upg3

property e:n2cr-upg3 t:meta.view v:id=n2cr-upg3 v:category=Finance v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="2016 Adopted Budget Attachment A" v:attribution="City of Seattle"

property e:n2cr-upg3 t:meta.view.license v:name="Public Domain"

property e:n2cr-upg3 t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:n2cr-upg3 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| fund            | appropriatingdepartment | fund_code | summit_code | bclrs_code  | bcl_name                                  | bcl_purpose                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 2016_appropriation | 
| =============== | ======================= | ========= | =========== | =========== | ========================================= | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ================== | 
| General Subfund | Executive               | 100       | CZ000       | 00100-CZ000 | City Budget Office                        | The purpose of the City Budget Office Budget Control Level is to develop and monitor the budget, carrying out budget-related functions, oversee financial policies and plans, and provide financial and other strategic analysis.                                                                                                                                                                                                                                                                                                                                         | 5895076            | 
| General Subfund | Executive               | 100       | VJ100       | 00100-VJ100 | Jail Services                             | The purpose of the Jail Services Budget Control Level is to provide for the booking, housing, transporting, and guarding of City inmates. The jail population, for which the City pays, are adults charged with or convicted of misdemeanor crimes alleged to have been committed within the Seattle city limits.                                                                                                                                                                                                                                                         | 17087312           | 
| General Subfund | Executive               | 100       | VJ500       | 00100-VJ500 | Indigent Defense Services                 | The purpose of the Indigent Defense Services Budget Control Level is to secure legal defense services, as required by State law, for indigent people facing criminal charges in Seattle Municipal Court.                                                                                                                                                                                                                                                                                                                                                                  | 7333471            | 
| General Subfund | Executive               | 100       | X1000       | 00100-X1000 | Office of Sustainability and Environment  | The purpose of the Office of Sustainability and Environment Budget Control Level is to coordinate interdepartmental environmental sustainability initiatives, identify and develop next generation policies and programs, and lead the City's climate change action planning to move towards carbon neutrality.                                                                                                                                                                                                                                                           | 3374826            | 
| General Subfund | Executive               | 100       | X1A00       | 00100-X1A00 | Office of the Mayor                       | The purpose of the Office of the Mayor Budget Control Level is to provide executive leadership to support City departments, engage and be responsive to residents of the city, develop policy for the City, and provide executive administrative and management support to the City.                                                                                                                                                                                                                                                                                      | 5833014            | 
| General Subfund | Executive               | 100       | X1D00       | 00100-X1D00 | Office of Economic Development            | The purpose of the Office of Economic Development Budget Control Level is to provide vital services to individual businesses and economic development leadership to support a strong local economy, thriving neighborhood business districts, and broadly-shared prosperity.                                                                                                                                                                                                                                                                                              | 10066072           | 
| General Subfund | Executive               | 100       | X1G00       | 00100-X1G00 | Intergovernmental Relations               | The purpose of the Intergovernmental Relations Budget Control Level is to promote and protect the City's federal, state, regional, and international interests by providing strategic advice, representation, and advocacy to, and on behalf of, City elected officials on a variety of issues. These include: federal and state executive and legislative actions; issues and events relating to the City's international relations; and jurisdictional issues involving King County, suburban cities, and regional governmental organizations.                          | 2794643            | 
| General Subfund | Executive               | 100       | X1N00       | 00100-X1N00 | Office of Immigrant and Refugee Affairs   | The purpose of the Office of Immigrant and Refugee Affairs Budget Control Level is to facilitate the successful integration of immigrants and refugees into Seattle's civic, economic, and cultural life, to celebrate their diverse cultures and contributions to Seattle, and to advocate on behalf of immigrants and refugees.                                                                                                                                                                                                                                         | 2261083            | 
| General Subfund | Executive               | 100       | X1P00       | 00100-X1P00 | Office of the Community Police Commission | The purpose of the Office of the Community Police Commission BCL is to leverage the ideas, talents, experience, and expertise of the community to provide ongoing community input into the development of Seattle Police Department reforms, the establishment of police priorities, and facilitation of police/community relationships necessary to promote public safety.                                                                                                                                                                                               | 850480             | 
| General Subfund | Executive               | 100       | X1R00       | 00100-X1R00 | Civil Rights                              | The purpose of the Civil Rights Budget Control Level is to encourage and promote equal access and opportunity, diverse participation, and social and economic equity in Seattle. OCR works to eliminate discrimination in employment, housing, public accommodations, contracting and lending in Seattle through enforcement, and policy and outreach activities. In addition, OCR is responsible for directing the Race and Social Justice Initiative, which leads other City departments to design and implement programs that help eliminate institutionalized racism. | 3074357            | 
```