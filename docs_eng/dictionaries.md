# Directories

`GET /dictionaries` returns the object with the directories of fields and entities used in our service.
Most often, each directory consists of a list of objects containing an `id` and a `name`.

Example: [https://api.hh.ru/dictionaries?locale=EN](https://api.hh.ru/dictionaries?locale=EN)


## Directories for fields used in CVs

* `education_level` - education
* `gender` - gender
* `language_level` - language level
* `preferred_contact_type` - preferred method of communication
* `relocation_type` - willingness to relocate
* `travel_time` - travel time to work
* `resume_access_type` - CV access level
* `business_trip_readiness` - willingness to travel
* `resume_contacts_site_type` - website type in the "contacts" field
* `resume_status` - CV status
* `resume_moderation_note` - moderator's comment


## Directories for CV search parameters

* `resume_search_order` - CV sorting type
* `resume_search_label` - additional filter of CV search results
* `resume_search_relocation` - willingness to relocate
* `resume_search_experience_period` - search in work experience for the indicated period
* `resume_search_logic` - search logic by phrase
* `resume_search_fields` - parts of CV to search in


## Directories for vacancy fields

* `employment` - employment type
* `experience` - work experience
* `schedule` - work schedule
* `vacancy_type` - vacancy type
* `vacancy_label` - vacancy tags
* `vacancy_relation` - types of vacancy connection to the user
* `vacancy_billing_type` - vacancy placement options with relation to billing
* `vacancy_site` - possible website values for vacancy placement


## Directories for vacancy search parameters

* `vacancy_search_fields` - vacancy search field
* `vacancy_search_order` - vacancy sorting type
* `vacancy_cluster` - cluster type


## Directories for sorting employer's vacancies

* `employer_active_vacancies_order` - sorting type of the published vacancy list
* `employer_archived_vacancies_order` - sorting type of the archived vacancy list


## Directories for applications and invitations (messaging)

* `negotiations_order` - application display order types
* `negotiations_state` - application state types
* `messaging_status` - status of the message sending possibility in messaging
* `negotiations_participant_type` - types of messaging participants


## Other directories

* `site_lang` - website language
* `currency` - currency directory
* `employer_type` - employer type
* `employer_relation` - methods of contacting applicants