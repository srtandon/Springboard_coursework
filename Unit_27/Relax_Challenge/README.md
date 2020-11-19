  
# Future User adoption

The goal was to identify which factors predict future user adoption.

Data:
- **name**: the user's name
- **object_id**: the user's id
- **email**: email address
- **creation_source**: how their account was created. This takes on one of 5 values:
  - **PERSONAL_PROJECTS**: invited to join another user's personal workspace
  - **GUEST_INVITE**: invited to an organization as a guest (limited permissions)
  - **ORG_INVITE**: invited to an organization (as a full member)
  - **SIGNUP**: signed up via the website
  - **SIGNUP_GOOGLE_AUTH**: signed up using Google Authentication (using a Google email account for their login id)
- **creation_time**: when they created their account
- **last_session_creation_time**: unix timestamp of last login
- **opted_in_to_mailing_list**: whether they have opted into receiving marketing emails
- enabled_for_marketing_drip**: whether they are on the regular marketing email drip
- **org_id**: the organization (group of users) they belong to
- **invited_by_user_id**: which user invited them to join (if applicable).
