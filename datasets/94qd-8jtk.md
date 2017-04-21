# Image Dataset with Form

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/image-dataset-with-form-b9aa9) |
| Metadata | [Link](https://data.oregon.gov/api/views/94qd-8jtk) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/94qd-8jtk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/94qd-8jtk/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 94qd-8jtk |
| Name | Image Dataset with Form |
| Category | Administrative |
| Created | 2014-02-04T17:05:25Z |
| Publication Date | 2014-05-29T19:00:29Z |

## Description

Form with file up load to be embedded on a page

## Columns

```ls
| Included | Schema Type | Field Name                                                                                                                                                                                                                          | Name                                                                                                                                                                                                                                    | Data Type      | Render Type    |
| ======== | =========== | =================================================================================================================================================================================================================================== | ======================================================================================================================================================================================================================================= | ============== | ============== |
| No       | time        | :updated_at                                                                                                                                                                                                                         | updated_at                                                                                                                                                                                                                              | meta_data      | meta_data      |
| Yes      | series tag  | first_name                                                                                                                                                                                                                          | Your Full Name                                                                                                                                                                                                                          | text           | text           |
| No       |             | date_picture_was_taken                                                                                                                                                                                                              | Date Picture Was Taken (m/d/y)                                                                                                                                                                                                          | text           | text           |
| Yes      | series tag  | near_what_city_was_this_picture_taken                                                                                                                                                                                               | Near What City Was This Picture Taken?                                                                                                                                                                                                  | dataset_link   | dataset_link   |
| Yes      | series tag  | image_category                                                                                                                                                                                                                      | Image Category                                                                                                                                                                                                                          | drop_down_list | drop_down_list |
| Yes      | series tag  | image_description_provide_details_such_as_klamath_falls                                                                                                                                                                             | Image Description (provide details such as "Klamath Falls")                                                                                                                                                                             | text           | text           |
| Yes      | series tag  | image                                                                                                                                                                                                                               | Image                                                                                                                                                                                                                                   | photo          | photo          |
| Yes      | series tag  | by_checking_this_box_i_acknowledge_that_i_have_read_the_full_photo_submission_policy_above_that_i_agree_to_these_guidelines_and_that_i_hereby_certify_that_the_copyright_to_the_photo_i_am_uploading_is_owned_by_me_and_no_one_else | By checking this box, I acknowledge that I have read the full Photo Submission Policy above, that I agree to these guidelines, and that I hereby certify that the copyright to the photo I am uploading is owned by me and no one else. | checkbox       | checkbox       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_picture_was_taken
```

## Data Commands

```ls
series e:94qd-8jtk d:2014-05-29T11:58:29.000Z t:first_name=Sample t:image_category=y32e-e9rr t:image=dh5WVl6nGelPtvojnd6vhH-vsdN87XTayiPMLDzku2A t:image_description_provide_details_such_as_klamath_falls="Minto Brown Slough" t:near_what_city_was_this_picture_taken=Salem m:row_number.94qd-8jtk=1

series e:94qd-8jtk d:2014-05-29T11:58:29.000Z m:row_number.94qd-8jtk=2

series e:94qd-8jtk d:2014-05-29T12:02:21.000Z t:first_name=My t:image_category=6p3i-rmgf t:image_description_provide_details_such_as_klamath_falls=Here t:near_what_city_was_this_picture_taken=Albany m:row_number.94qd-8jtk=3
```

## Meta Commands

```ls
metric m:row_number.94qd-8jtk p:long l:"Row Number"

entity e:94qd-8jtk l:"Image Dataset with Form" t:url=https://data.oregon.gov/api/views/94qd-8jtk

property e:94qd-8jtk t:meta.view v:id=94qd-8jtk v:category=Administrative v:averageRating=0 v:name="Image Dataset with Form"

property e:94qd-8jtk t:meta.view.owner v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:displayName="Linda Morrell"

property e:94qd-8jtk t:meta.view.tableauthor v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:roleName=editor v:displayName="Linda Morrell"
```

## Top Records

```ls
| :updated_at | first_name | date_picture_was_taken | near_what_city_was_this_picture_taken | image_category | image_description_provide_details_such_as_klamath_falls | image                                       | by_checking_this_box_i_acknowledge_that_i_have_read_the_full_photo_submission_policy_above_that_i_agree_to_these_guidelines_and_that_i_hereby_certify_that_the_copyright_to_the_photo_i_am_uploading_is_owned_by_me_and_no_one_else | 
| =========== | ========== | ====================== | ===================================== | ============== | ======================================================= | =========================================== | =================================================================================================================================================================================================================================== | 
| 1401364709  | Sample     | 10/11/2013             | Salem                                 | y32e-e9rr      | Minto Brown Slough                                      | dh5WVl6nGelPtvojnd6vhH-vsdN87XTayiPMLDzku2A |                                                                                                                                                                                                                                     | 
| 1401364709  |            |                        |                                       |                |                                                         |                                             |                                                                                                                                                                                                                                     | 
| 1401364941  | My         | today                  | Albany                                | 6p3i-rmgf      | Here                                                    |                                             |                                                                                                                                                                                                                                     | 
| 1401365416  |            | today                  |                                       |                |                                                         |                                             |                                                                                                                                                                                                                                     | 
```