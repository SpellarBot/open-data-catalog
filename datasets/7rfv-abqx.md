# King County weather-related closures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-weather-related-closures-300c3) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/7rfv-abqx) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/7rfv-abqx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/7rfv-abqx/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 7rfv-abqx |
| Name | King County weather-related closures |
| Attribution | King County |
| Category | Operations |
| Tags | operations, office closures |
| Created | 2012-01-17T14:33:49Z |
| Publication Date | 2012-01-20T13:38:23Z |

## Description

Some King County agencies are reporting delayed operations today. These agencies include:

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | office_or_agency | Office or agency | html      | html        |
| Yes      | series tag  | closure_details  | Closure details  | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7rfv-abqx d:2012-01-18T08:45:55.000Z t:office_or_agency="<p><strong><span style=""color:#ffffff;"">2</span>...More information</strong></p>" t:closure_details="<p>Check <a target=""_blank"" href=""http://www.kingcounty.gov/news/"">http://www.kingcounty.gov/news/</a> for updates containing additional information</p>" m:row_number.7rfv-abqx=1

series e:7rfv-abqx d:2012-01-18T17:04:10.000Z t:office_or_agency="<p><strong>Metro Transit</strong></p>" t:closure_details="<p><span>King County Metro Transit will continue to operate with buses on snow routes. Expect delays&nbsp;and cancellations. As travel conditions deteriorate, please consider limiting travel if at all possible. Check Metro's snow page (</span><a target=""_blank"" href=""http://www.kingcounty.gov/metro/snow"">www.kingcounty.gov/metro/snow</a><span>) for the current status of bus service.</span></p>" m:row_number.7rfv-abqx=2

series e:7rfv-abqx d:2012-01-19T04:52:15.000Z t:office_or_agency="<p><strong>Airport (King County International)</strong></p>" t:closure_details="<p>L<span>arge runway open, small runway closed, no impact to normal operations.</span></p>" m:row_number.7rfv-abqx=3
```

## Meta Commands

```ls
metric m:row_number.7rfv-abqx p:long l:"Row Number"

entity e:7rfv-abqx l:"King County weather-related closures" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/7rfv-abqx

property e:7rfv-abqx t:meta.view v:id=7rfv-abqx v:category=Operations v:attributionLink=http://www.kingcounty.gov/ v:averageRating=0 v:name="King County weather-related closures" v:attribution="King County"

property e:7rfv-abqx t:meta.view.license v:name="Public Domain"

property e:7rfv-abqx t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:7rfv-abqx t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | office_or_agency                    | closure_details                                                                                                                                                                                                                                                                                                                                                                                 | 
| =========== | =================================== | =============================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1326876355  | 2...More information                | Check http://www.kingcounty.gov/news/ for updates containing additional information                                                                                                                                                                                                                                                                                                             | 
| 1326906250  | Metro Transit                       | King County Metro Transit will continue to operate with buses on snow routes. Expect delays and cancellations. As travel conditions deteriorate, please consider limiting travel if at all possible. Check Metro's snow page (www.kingcounty.gov/metro/snow) for the current status of bus service.                                                                                             | 
| 1326948735  | Airport (King County International) | Large runway open, small runway closed, no impact to normal operations.                                                                                                                                                                                                                                                                                                                         | 
| 1326951903  | Water taxi                          | Service is expected to be normal, but may be impacted by high winds. Sign up for alerts http://metro.kingcounty.gov/signup/ to receive notification if weather impacts sailings later in the day.                                                                                                                                                                                               | 
| 1326961192  | Garbage collection service          | No residential garbage collection in King County. Customers should secure their garbage and put it out for collection on their regular day next week. There are several companies providing garbage collection services throughout King County, and residents are urged to contact their individual hauler for information: http://your.kingcounty.gov/solidwaste/garbage-recycling/garbage.asp | 
| 1326970267  | 1...Online services available       | King County residents may be able to obtain some services online, such as pet licensing,car tabs, marriage licenses by mail, property tax payments, business licensing and more.                                                                                                                                                                                                                | 
| 1326994270  | Public Health                       | Public Health Centers will open at 10:00 a.m. Friday and some may have limited services. Please call ahead to find out if the service is available. Contact information is available on the Public Health website at www.kingcounty.gov/health.                                                                                                                                                 | 
| 1327007553  | Court (Superior)                    | Superior Court will open at 10:30 a.m. Friday.                                                                                                                                                                                                                                                                                                                                                  | 
| 1327007586  | Court (District)                    | District Court will open at 10:30 a.m. Friday.                                                                                                                                                                                                                                                                                                                                                  | 
| 1327007775  | Elections                           | Elections office will be closed Friday. There will be limited staffing, but phones and email will be monitored as much as possible by staff working remotely.                                                                                                                                                                                                                                   | 
```