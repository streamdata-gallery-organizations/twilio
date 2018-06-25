---
name: Twilio
x-slug: twilio
description: Cloud communications platform for building SMS, Voice & Messaging applications
  on an API built for global scale. Get started with a free trial.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
x-kinRank: "10"
x-alexaRank: "9195"
tags: Twilio
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/apis.md
specificationVersion: "0.14"
apis:
- name: Twilio Get Acount
  x-api-slug: twilio
  description: Get Account
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}.{format}
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsid-format-get-openapi.md
- name: Twilio Add Account
  x-api-slug: twilio
  description: Add Account
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}.{format}
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsid-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsid-format-post-openapi.md
- name: Twilio Update Account
  x-api-slug: twilio
  description: Update Account
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}.{format}
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsid-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsid-format-put-openapi.md
- name: Twilio Get Accounts
  x-api-slug: twilio
  description: Get Accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts.{format}
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accounts-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accounts-format-get-openapi.md
- name: Twilio Delete Application
  x-api-slug: twilio
  description: Delete Application
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Applications/{ApplicationSid}.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplicationsapplicationsid-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplicationsapplicationsid-format-delete-openapi.md
- name: Twilio Get Application
  x-api-slug: twilio
  description: Get application instance resource.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Applications/{ApplicationSid}.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplicationsapplicationsid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplicationsapplicationsid-format-get-openapi.md
- name: Twilio Add Application
  x-api-slug: twilio
  description: Tries to update the applications properties, and returns the updatednresource
    representation if successful. The returned response is identicalnto that returned
    above when making a GET request.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Applications/{ApplicationSid}.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplicationsapplicationsid-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplicationsapplicationsid-format-post-openapi.md
- name: Twilio Get Applications
  x-api-slug: twilio
  description: Get Applications
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Applications.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplications-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplications-format-get-openapi.md
- name: Twilio Add Applications
  x-api-slug: twilio
  description: Add Applications
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Applications.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplications-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidapplications-format-post-openapi.md
- name: Twilio Get Authorized Connected App
  x-api-slug: twilio
  description: Get the properties of the authorized application.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/AuthorizedConnectApps/{ConnectAppSid}.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidauthorizedconnectappsconnectappsid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidauthorizedconnectappsconnectappsid-format-get-openapi.md
- name: Twilio Get Authorized Connected Apps
  x-api-slug: twilio
  description: Returns a list of Connect App resource representations, each representing
    anConnect App youve authorized to access your account. The list includesnpaging
    information.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/AuthorizedConnectApps.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidauthorizedconnectapps-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidauthorizedconnectapps-format-get-openapi.md
- name: Twilio Get Available Local Phone Numbers
  x-api-slug: twilio
  description: Returns a list of local AvailablePhoneNumber resource representationsnthat
    match the specified filters, each representing a phone number thanis currently
    available for provisioning within your account.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/AvailablePhoneNumbers/{IsoCountryCode}/Local.{format}
  tags: Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidavailablephonenumbersisocountrycodelocal-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidavailablephonenumbersisocountrycodelocal-format-get-openapi.md
- name: Twilio Get Available Mobile Phone Numbers
  x-api-slug: twilio
  description: Returns a list of mobile AvailablePhoneNumber resource representations
    that match the specified filters, each representing a phone number that is currently
    available for provisioning within your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/AvailablePhoneNumbers/{IsoCountryCode}/Mobile.{format}
  tags: Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidavailablephonenumbersisocountrycodemobile-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidavailablephonenumbersisocountrycodemobile-format-get-openapi.md
- name: Twilio Get Available Toll Free Phone Numbers
  x-api-slug: twilio
  description: Returns a list of toll-free AvailablePhoneNumber elements that match
    thenspecified filters, each representing a phone number that is currentlynavailable
    for provisioning within your account. To provision an availablenphone number,
    POST the number to the IncomingPhoneNumbers resource.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/AvailablePhoneNumbers/{IsoCountryCode}/TollFree.{format}
  tags: Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidavailablephonenumbersisocountrycodetollfree-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidavailablephonenumbersisocountrycodetollfree-format-get-openapi.md
- name: Twilio Get Recordings
  x-api-slug: twilio
  description: Returns a list of Recording resource representations, each representing
    anrecording generated during the course of a phone call.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Calls/{CallSid}/Recordings.{format}
  tags: Recordings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidcallscallsidrecordings-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidcallscallsidrecordings-format-get-openapi.md
- name: Twilio Get Call
  x-api-slug: twilio
  description: Get Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Calls/{CallSid}.{format}
  tags: Calls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidcallscallsid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidcallscallsid-format-get-openapi.md
- name: Twilio Get Calls
  x-api-slug: twilio
  description: Get Calls
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Calls.{format}
  tags: Calls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidcalls-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidcalls-format-get-openapi.md
- name: Twilio Make Call
  x-api-slug: twilio
  description: To make a call, make an HTTP POST request. Initiate a new phone call.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Calls.{format}
  tags: Calls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidcalls-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidcalls-format-post-openapi.md
- name: Twilio Delete Conference Call Participants
  x-api-slug: twilio
  description: Kick this participant from the conference.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants/{CallSid}.{format}
  tags: Conference Calls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesidparticipantscallsid-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesidparticipantscallsid-format-delete-openapi.md
- name: Twilio Add Conference Call Participants
  x-api-slug: twilio
  description: Updates the status of a participant.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants/{CallSid}.{format}
  tags: Conference Calls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesidparticipantscallsid-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesidparticipantscallsid-format-post-openapi.md
- name: Twilio Get Conference Call Participants
  x-api-slug: twilio
  description: Returns the list of participants in the conference identified byn{ConferenceSid}.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants.{format}
  tags: Conference Calls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesidparticipants-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesidparticipants-format-get-openapi.md
- name: Twilio Get Conference Calls
  x-api-slug: twilio
  description: Returns a list of conferences within an account. The list includes
    pagingninformation.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Conferences.{format}
  tags: Conference Calls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferences-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferences-format-get-openapi.md
- name: Twilio Get Conference
  x-api-slug: twilio
  description: Get Conference
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Conferences/{ConferenceSid}.{format}
  tags: Conferences
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesid-format-get-openapi.md
- name: Twilio GetParticipantForConference
  x-api-slug: twilio
  description: GetParticipantForConference
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants/{CallSid}.{format}
  tags: Conferences
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesidparticipantscallsid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconferencesconferencesidparticipantscallsid-format-get-openapi.md
- name: Twilio Get Connected App
  x-api-slug: twilio
  description: Get the properties of a Connect App.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/ConnectApps/{ConnectAppSid}.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconnectappsconnectappsid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconnectappsconnectappsid-format-get-openapi.md
- name: Twilio Add Connected App
  x-api-slug: twilio
  description: Tries to update the Connect Apps properties, and returns the updatednresource
    representation if successful. The returned response is identicalnto that returned
    above when making a GET request.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/ConnectApps/{ConnectAppSid}.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconnectappsconnectappsid-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconnectappsconnectappsid-format-post-openapi.md
- name: Twilio Get Connected Apps
  x-api-slug: twilio
  description: Returns a list of Connect App resource representations, each representingna
    Connect App in your account. The list includes paging information.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/ConnectApps.{format}
  tags: Applications
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconnectapps-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidconnectapps-format-get-openapi.md
- name: Twilio Get Incoming Local Phone Numbers
  x-api-slug: twilio
  description: Returns a list of local <IncomingPhoneNumber> elements, each representing
    a local (not toll-free) phone number given to your account, under an <IncomingPhoneNumbers>
    list element that includes paging information. Works exactly the same as the IncomingPhoneNumber
    resource, but filters out toll-free numbers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/IncomingPhoneNumbers/Local.{format}
  tags: Incoming Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumberslocal-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumberslocal-format-get-openapi.md
- name: Twilio Add Incoming Local Phone Numbers
  x-api-slug: twilio
  description: Adds a new phone number to your account. If a phone number is found
    for your request, Twilio will add it to your account and bill you for the first
    months cost of the phone number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/IncomingPhoneNumbers/Local.{format}
  tags: Incoming Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumberslocal-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumberslocal-format-post-openapi.md
- name: Twilio Get Incoming Phone Numbers
  x-api-slug: twilio
  description: Returns a list of local <IncomingPhoneNumber> elements, each representing
    a mobile phone number given to your account, under an <IncomingPhoneNumbers> list
    element that includes paging information. Works exactly the same as the IncomingPhoneNumber
    resource, but filters out local and toll free numbers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/IncomingPhoneNumbers/Mobile.{format}
  tags: Incoming Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersmobile-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersmobile-format-get-openapi.md
- name: Twilio Delete Incoming Phone Number
  x-api-slug: twilio
  description: Release this phone number from your account. Twilio will no longer
    answerncalls to this number, and you will stop being billed the monthly phonennumber
    fee. The phone number will eventually be recycled and potentiallyngiven to another
    customer, so use with care. If you make a mistake, contacnus. We may be able to
    give you the number back.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/IncomingPhoneNumbers/{IncomingPhoneNumberSid}.{format}
  tags: Incoming Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-delete-openapi.md
- name: Twilio Get Incoming Phone Number
  x-api-slug: twilio
  description: Get info about incoming calls phone number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/IncomingPhoneNumbers/{IncomingPhoneNumberSid}.{format}
  tags: Incoming Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-get-openapi.md
- name: Twilio Add Incoming Phone Number
  x-api-slug: twilio
  description: Tries to update the incoming phone numbers properties, and returns
    thenupdated resource representation if successful. The returned response isnidentical
    to that returned above when making a GET request.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/IncomingPhoneNumbers/{IncomingPhoneNumberSid}.{format}
  tags: Incoming Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-post-openapi.md
- name: Twilio Update Incoming Phone Number
  x-api-slug: twilio
  description: Tries to update the incoming phone numbers properties, and returns
    thenupdated resource representation if successful. The returned response isnidentical
    to that returned above when making a GET request.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/IncomingPhoneNumbers/{IncomingPhoneNumberSid}.{format}
  tags: Incoming Phone Numbers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-put-openapi.md
- name: Twilio Get Message Media
  x-api-slug: twilio
  description: Without an extension, the media is returned using the mime-type provided
    when the media was generated.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Messages/{MessageSid}/Media/{MediaSid}
  tags: Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessagesmessagesidmediamediasid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessagesmessagesidmediamediasid-get-openapi.md
- name: Twilio Get Message Media
  x-api-slug: twilio
  description: Returns a list of media associated with your message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Messages/{MessageSid}/Media
  tags: Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessagesmessagesidmedia-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessagesmessagesidmedia-get-openapi.md
- name: Twilio Get Message Media
  x-api-slug: twilio
  description: Returns a single message specified by the provided {MessageSid}.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Messages/{MessageSid}
  tags: Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessagesmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessagesmessagesid-get-openapi.md
- name: Twilio Get Message Media
  x-api-slug: twilio
  description: Returns a list of messages associated with your account. The list includes
    paging information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Messages.{format}
  tags: Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessages-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessages-format-get-openapi.md
- name: Twilio Add Message
  x-api-slug: twilio
  description: To send a new outgoing message, make an HTTP POST to your Messages
    list resource URI
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Messages.{format}
  tags: Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessages-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidmessages-format-post-openapi.md
- name: Twilio Get Outgoing Caller Ids
  x-api-slug: twilio
  description: Get the set of an accounts verified phone numbers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/OutgoingCallerIds/{OutgoingCallerIdSid}
  tags: Outgoing Caller IDs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-get-openapi.md
- name: Twilio Add Outgoing Caller Id
  x-api-slug: twilio
  description: Updates the caller id, and returns the updated resource if successful.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/OutgoingCallerIds/{OutgoingCallerIdSid}
  tags: Outgoing Caller IDs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-post-openapi.md
- name: Twilio Update Outgoing Caller Id
  x-api-slug: twilio
  description: Updates the caller id, and returns the updated resource if successful.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/OutgoingCallerIds/{OutgoingCallerIdSid}
  tags: Outgoing Caller IDs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-put-openapi.md
- name: Twilio Get Outgoing Caller Ids
  x-api-slug: twilio
  description: Returns a list of OutgoingCallerId resource representations, each representingna
    Caller ID number valid for an account. The list includes paging information.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/OutgoingCallerIds
  tags: Outgoing Caller IDs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcallerids-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcallerids-get-openapi.md
- name: Twilio Add Outgoing Caller Id
  x-api-slug: twilio
  description: Adds a new CallerID to your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/OutgoingCallerIds
  tags: Outgoing Caller IDs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcallerids-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcallerids-post-openapi.md
- name: Twilio Delete Outgoing Caller ID
  x-api-slug: twilio
  description: DeleteOutgoingCallerId
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/OutgoingCallerIds/{OutgoingCallerIdSid}
  tags: Outgoing Caller IDs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-delete-openapi.md
- name: Twilio Get Queue Members In Front
  x-api-slug: twilio
  description: Get a front member.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues/{QueueSid}/Members/Front
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmembersfront-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmembersfront-get-openapi.md
- name: Twilio Update Queue Members In Front
  x-api-slug: twilio
  description: Posting a URL and Method to a Queue instance will dequeue a member
    from anqueue and have the members call begin executing the TwiML document at that
    URLnWhen dequeuing the Front of the queue, the next call in the queue will be
    redirected.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues/{QueueSid}/Members/Front
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmembersfront-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmembersfront-post-openapi.md
- name: Twilio Get Queue Members
  x-api-slug: twilio
  description: Get a specific member.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues/{QueueSid}/Members/{CallSid}
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmemberscallsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmemberscallsid-get-openapi.md
- name: Twilio Update Queue Members
  x-api-slug: twilio
  description: Posting a URL and Method to a Queue instance will dequeue a member
    from anqueue and have the members call begin executing the TwiML document at that
    URLnWhen redirecting a member of a queue addressed by CallSid, only the first
    requestnwill succeed and return a 200 response code. A second request will fail
    andnreturn an appropriate 400 response code.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues/{QueueSid}/Members/{CallSid}
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmemberscallsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmemberscallsid-post-openapi.md
- name: Twilio Get Queue Members
  x-api-slug: twilio
  description: Returns the list of members in the queue identified by {QueueSid}.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues/{QueueSid}/Members
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesidmembers-get-openapi.md
- name: Twilio Delete Queue Members
  x-api-slug: twilio
  description: The DELETE method allows you to remove a Queue. Only empty queues arendeletable.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues/{QueueSid}
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesid-delete-openapi.md
- name: Twilio Get Queue Members
  x-api-slug: twilio
  description: Get resources individual Queue instance.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues/{QueueSid}
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesid-get-openapi.md
- name: Twilio Add Queue Members
  x-api-slug: twilio
  description: This POST request allows you to change the FriendlyName or MaxSize.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues/{QueueSid}
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueuesqueuesid-post-openapi.md
- name: Twilio Get Queues
  x-api-slug: twilio
  description: Returns a list of queues within an account. The list includes pagingninformation.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueues-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueues-get-openapi.md
- name: Twilio Add Queue
  x-api-slug: twilio
  description: Create a new Queue resource.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Queues
  tags: Queues
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueues-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidqueues-post-openapi.md
- name: Twilio Get Recording Transcriptions
  x-api-slug: twilio
  description: Returns a set of Transcription resource representations that includes
    pagingninformation.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Recordings/{RecordingSid}/Transcriptions
  tags: Recordings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidrecordingsrecordingsidtranscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidrecordingsrecordingsidtranscriptions-get-openapi.md
- name: Twilio Delete Recording
  x-api-slug: twilio
  description: Deletes a recording  from your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Recordings/{RecordingSid}
  tags: Recordings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidrecordingsrecordingsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidrecordingsrecordingsid-delete-openapi.md
- name: Twilio Get Recording
  x-api-slug: twilio
  description: Returns one of several representations:nWithout an extension, or with
    a .wav, a binary WAV audio file is returnednwith mime-type audio/x-wav.nAppending
    .mp3 to the URI returns a binary MP3 audio file with mime-typentype audio/mpeg.nAppending
    .xml to the URI returns a XML representation.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Recordings/{RecordingSid}
  tags: Recordings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidrecordingsrecordingsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidrecordingsrecordingsid-get-openapi.md
- name: Twilio Get Recordings
  x-api-slug: twilio
  description: Returns a list of Recording resource representations, each representing
    anrecording generated during the course of a phone call.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Recordings
  tags: Recordings
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidrecordings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidrecordings-get-openapi.md
- name: Twilio Delete SIP Credential From List
  x-api-slug: twilio
  description: Remove a Credential from a CredentialList.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}/Credentials/{CredentialSid}
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-delete-openapi.md
- name: Twilio Get SIP Credentials List
  x-api-slug: twilio
  description: Get a specific Credential in a list. Though a password is stored for
    each username in your list, the password is not returned to protect your password.
    If you cannot remember your password, you will need to POST to this resource to
    update it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}/Credentials/{CredentialSid}
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-get-openapi.md
- name: Twilio Add To SIP Credentials List
  x-api-slug: twilio
  description: Change the password of a Credential record.nnIf the change is successful,
    Twilio will respond with the Credential record but will not include the password
    in the response.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}/Credentials/{CredentialSid}
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-post-openapi.md
- name: Twilio Get SIP Credentials List
  x-api-slug: twilio
  description: Get the list of Credentials in a CredentialList. The passwords for
    the Credentials are intentionally not returned so as to protect them.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}/Credentials
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentials-get-openapi.md
- name: Twilio Get SIP Credentials List
  x-api-slug: twilio
  description: Add a Credential to the CredentialList.nnWhen creating a Credential,
    you will POST both a username and password, but only receive the username back
    in the response. The password is intentionally not returned so as to protect it.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}/Credentials
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentials-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsidcredentials-post-openapi.md
- name: Twilio Delete SIP Credential List
  x-api-slug: twilio
  description: Delete a CredentialList from your account. It can only be deleted if
    no domains are mapped to it. If you attempt to delete one that is mapped to a
    domain, you will receive an error.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsid-delete-openapi.md
- name: Twilio Get SIP Credentials List
  x-api-slug: twilio
  description: Get a credential list instance resource
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsid-get-openapi.md
- name: Twilio Add SIP Credentials List
  x-api-slug: twilio
  description: Change the FriendlyName of the list
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallistsclsid-post-openapi.md
- name: Twilio Get SIP Credentials List
  x-api-slug: twilio
  description: Gets a list of Credential Lists for an account
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallists-get-openapi.md
- name: Twilio Get SIP Credentials List
  x-api-slug: twilio
  description: Create a new Credential List.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/CredentialLists
  tags: SIP Credential Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallists-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipcredentiallists-post-openapi.md
- name: Twilio Delete Domains Credentials
  x-api-slug: twilio
  description: Remove a CredentialListMapping from a domain
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}/CredentialListMappings/{CLSid}
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidcredentiallistmappingsclsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidcredentiallistmappingsclsid-delete-openapi.md
- name: Twilio Get Domains Credentials
  x-api-slug: twilio
  description: Get the user lists mapped to this domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}/CredentialListMappings
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidcredentiallistmappings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidcredentiallistmappings-get-openapi.md
- name: Twilio Add Domains Credentials
  x-api-slug: twilio
  description: Map a CredentialList to the domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}/CredentialListMappings
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidcredentiallistmappings-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidcredentiallistmappings-post-openapi.md
- name: Twilio Delete Domains Credentials
  x-api-slug: twilio
  description: Remove a mapping from this domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}/IpAccessControlListMappings/{ALSid}
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidipaccesscontrollistmappingsalsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidipaccesscontrollistmappingsalsid-delete-openapi.md
- name: Twilio Get Domains IP Access Control List Mappings
  x-api-slug: twilio
  description: Return a specific IpAccessControlListMapping instance by Sid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}/IpAccessControlListMappings/{ALSid}
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidipaccesscontrollistmappingsalsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidipaccesscontrollistmappingsalsid-get-openapi.md
- name: Twilio Get Domains IP Access Control List Mapping
  x-api-slug: twilio
  description: Return the IpAccessControlListMappings that are associated to this
    domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}/IpAccessControlListMappings
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidipaccesscontrollistmappings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidipaccesscontrollistmappings-get-openapi.md
- name: Twilio Add Domains IP Access Control List Mappings
  x-api-slug: twilio
  description: Map an IpAccessControlList to this domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}/IpAccessControlListMappings
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidipaccesscontrollistmappings-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsidipaccesscontrollistmappings-post-openapi.md
- name: Twilio Delete Domains IP Access Control List Mappings
  x-api-slug: twilio
  description: Delete a domain. If you have created subdomains of a domain, you will
    not be able to delete the domain until you first delete all subdomains of it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsid-delete-openapi.md
- name: Twilio Get Domains
  x-api-slug: twilio
  description: Return a specific instance by Sid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsid-get-openapi.md
- name: Twilio Add Domains
  x-api-slug: twilio
  description: Update the attributes of a domain.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains/{SipDomainSid}
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomainssipdomainsid-post-openapi.md
- name: Twilio Get Domains
  x-api-slug: twilio
  description: Returns a paged list of the domains for an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomains-get-openapi.md
- name: Twilio Add Domains
  x-api-slug: twilio
  description: Creates a new Domain and returns its instance resource. You must pick
    a unique domain name that ends in .sip.twilio.com.nAfter creating a Domain, you
    must map it to an authentication method before the domain is ready to receive
    traffic.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/Domains
  tags: SIP Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomains-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipdomains-post-openapi.md
- name: Twilio Delete SIP IP Access Control List IP Address
  x-api-slug: twilio
  description: Deletes an IP address entry from the list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses/{IpAddressSid}
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-delete-openapi.md
- name: Twilio Get SIP IP Access Control List IP Address
  x-api-slug: twilio
  description: Return a single IP Address resource.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses/{IpAddressSid}
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-get-openapi.md
- name: Twilio Add SIP IP Access Control List IP Address
  x-api-slug: twilio
  description: Change the description or IP address of a given IpAddress instance
    resource
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses/{IpAddressSid}
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddressesipaddresssid-post-openapi.md
- name: Twilio Get SIP IP Access Control List IP Address
  x-api-slug: twilio
  description: List the IP Addresses contained in this list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddresses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddresses-get-openapi.md
- name: Twilio Add SIP IP Access Control List IP Address
  x-api-slug: twilio
  description: Add an IP Address to the list with a description.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}/IpAddresses
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddresses-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsidipaddresses-post-openapi.md
- name: Twilio Delete SIP IP Access Control List IP Address
  x-api-slug: twilio
  description: Delete an IpAccessControlList from your account. It can only be deleted
    if no domains are mapped to it. If you attempt to delete one that is mapped to
    a domain, you will receive an error.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-delete-openapi.md
- name: Twilio Get SIP IP Access Control List IP Address
  x-api-slug: twilio
  description: Return a specific IpAccessControlList resource.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-get-openapi.md
- name: Twilio Add SIP IP Access Control List IP Address
  x-api-slug: twilio
  description: Rename an IpAccessControlList.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists/{IpAccessControlListSid}
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollistsipaccesscontrollistsid-post-openapi.md
- name: Twilio Get SIP IP Access Control List
  x-api-slug: twilio
  description: Return a paged list of all IpAccessControlLists under this account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollists-get-openapi.md
- name: Twilio Add SIP IP Access Control List
  x-api-slug: twilio
  description: Create a new IpAccessControlList resource.nnWhen created, the list
    will contain no IP addresses. You will need to add IP addresses to the list for
    it to be active. To add IP addresses, you will need to POST to the IpAddresses
    List subresource.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SIP/IpAccessControlLists
  tags: SIP IP Access Control Lists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollists-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsipipaccesscontrollists-post-openapi.md
- name: Twilio Get SMS Short Code Media
  x-api-slug: twilio
  description: Get a single message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SMS/ShortCodes/{ShortCodeSid}
  tags: Short Codes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsshortcodesshortcodesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsshortcodesshortcodesid-get-openapi.md
- name: Twilio Add SMS Short Code Media
  x-api-slug: twilio
  description: Tries to update the shortcodes properties, and returns the updatednresource
    representation if successful.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SMS/ShortCodes/{ShortCodeSid}
  tags: Short Codes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsshortcodesshortcodesid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsshortcodesshortcodesid-post-openapi.md
- name: Twilio Get SMS Short Code Media
  x-api-slug: twilio
  description: Returns a list of ShortCode resource representations, each representing
    anshort code within your account. The list includes paging information.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SMS/ShortCodes
  tags: Short Codes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsshortcodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsshortcodes-get-openapi.md
- name: Twilio GetSMSList
  x-api-slug: twilio
  description: GetSMSList
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SMS/Messages.{format}
  tags: SMS Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsmessages-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsmessages-format-get-openapi.md
- name: Twilio SendSMS
  x-api-slug: twilio
  description: SendSMS
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SMS/Messages.{format}
  tags: SMS Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsmessages-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsmessages-format-post-openapi.md
- name: Twilio GetSMS
  x-api-slug: twilio
  description: GetSMS
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/SMS/Messages/{SMSMessageSid}.{format}
  tags: SMS Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsmessagessmsmessagesid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidsmsmessagessmsmessagesid-format-get-openapi.md
- name: Twilio Delete Transcription
  x-api-slug: twilio
  description: Deletes a transcription from your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Transcriptions/{TranscriptionSid}
  tags: Transcriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptionstranscriptionsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptionstranscriptionsid-delete-openapi.md
- name: Twilio Get Transcription
  x-api-slug: twilio
  description: Returns a single Transcription resource representation identified by
    thengiven {TranscriptionSid}. By default Twilio will respond with the XML metadata
    for the Transcription. If you append .txt to the end of the Transcription resources
    URI Twilio will just return you the transcription tex.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Transcriptions/{TranscriptionSid}
  tags: Transcriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptionstranscriptionsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptionstranscriptionsid-get-openapi.md
- name: Twilio Get Transcriptions
  x-api-slug: twilio
  description: Returns a set of Transcription resource representations that includes
    pagingninformation.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Transcriptions
  tags: Transcriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptions-get-openapi.md
- name: Twilio GetTranscriptionList
  x-api-slug: twilio
  description: GetTranscriptionList
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Transcriptions.{format}
  tags: Transcriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptions-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptions-format-get-openapi.md
- name: Twilio GetTranscription
  x-api-slug: twilio
  description: GetTranscription
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Transcriptions/{TranscriptionSid}.{format}
  tags: Transcriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptionstranscriptionsid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidtranscriptionstranscriptionsid-format-get-openapi.md
- name: Twilio Get Account Usage Record Sub Resource
  x-api-slug: twilio
  description: Returns UsageRecords for all usage categories for a specified period.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Usage/Records/{Subresource}
  tags: Usage Records
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagerecordssubresource-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagerecordssubresource-get-openapi.md
- name: Twilio Get Account Usage Record
  x-api-slug: twilio
  description: Returns UsageRecords for all usage categories. The list includes pagingninformation.nBy
    default, the UsageRecords resource will return one UsageRecord forneach Category,
    representing all usage accrued all-time for the account.nYou can filter the usage
    Category or change the date-range over which usagenis counted using optional GET
    query parameters.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Usage/Records
  tags: Usage Records
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagerecords-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagerecords-get-openapi.md
- name: Twilio Delete Account Usage Trigger
  x-api-slug: twilio
  description: Delete this UsageTrigger.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Usage/Triggers/{UsageTriggerSid}
  tags: Usage Triggers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggersusagetriggersid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggersusagetriggersid-delete-openapi.md
- name: Twilio Get Account Usage Trigger
  x-api-slug: twilio
  description: Returns a repesentation of the UsageTrigger.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Usage/Triggers/{UsageTriggerSid}
  tags: Usage Triggers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggersusagetriggersid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggersusagetriggersid-get-openapi.md
- name: Twilio Add Account Usage Trigger
  x-api-slug: twilio
  description: Tries to update the UsageTriggers properties, and returns the updatednresource
    representation if successful.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Usage/Triggers/{UsageTriggerSid}
  tags: Usage Triggers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggersusagetriggersid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggersusagetriggersid-post-openapi.md
- name: Twilio Get Account Usage Triggers
  x-api-slug: twilio
  description: Returns a list of UsageTrigger resource representations. The list includesnpaging
    information.nBy default, all UsageTriggers are returned. You can filter the list
    bynspecifying one or more query parameters. Note that the query parameters arencase-sensitiven
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Usage/Triggers
  tags: Usage Triggers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggers-get-openapi.md
- name: Twilio Add Account Usage Triggers
  x-api-slug: twilio
  description: Creates a new UsageTrigger. Each account can create up to 1,000 UsageTriggers.nCurrently,
    UsageTriggers that are no longer active are not deleted automatically.nUse DELETE
    to delete triggers you no longer need.n
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01///Accounts/{AccountSid}/Usage/Triggers
  tags: Usage Triggers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/accountsaccountsidusagetriggers-post-openapi.md
- name: Twilio
  x-api-slug: twilio
  description: Cloud communications platform for building SMS, Voice & Messaging applications
    on an API built for global scale. Get started with a free trial.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/143-twilio.jpg
  humanURL: http://www.twilio.com
  baseURL: https://api.twilio.com//2010-04-01/
  tags: Twilio
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/twilio/master/_listings/twilio/openapi.md
x-common:
- type: x--net-library
  url: https://www.twilio.com/docs/csharp/install
- type: x-acceptable-use-policy
  url: https://www.twilio.com/legal/aup
- type: x-application-gallery
  url: https://www.twilio.com/showcase
- type: x-base-url
  url: https://api.twilio.com
- type: x-blog
  url: http://www.twilio.com/blog
- type: x-blog-rss
  url: http://www.twilio.com/blog/feed
- type: x-community-supported-libraries
  url: https://www.twilio.com/docs/libraries
- type: x-contact-form
  url: https://www.twilio.com/help/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/twilio
- type: x-crunchbase
  url: https://crunchbase.com/organization/twilio
- type: x-documentation
  url: https://www.twilio.com/docs/api
- type: x-email
  url: help@twilio.com
- type: x-email
  url: privacy@twilio.com
- type: x-email
  url: legalnotices@twilio.com
- type: x-email
  url: trademark@twilio.com
- type: x-email
  url: kyleky@twilio.com
- type: x-getting-started
  url: https://www.twilio.com/docs/quickstart
- type: x-github
  url: https://github.com/twilio
- type: x-how-to-guides
  url: https://www.twilio.com/docs/howto
- type: x-java-library
  url: https://www.twilio.com/docs/java/install
- type: x-node-js-library
  url: https://www.twilio.com/docs/node/install
- type: x-paid-support
  url: https://www.twilio.com/premium-support#features
- type: x-partners
  url: https://www.twilio.com/partners
- type: x-php-library
  url: https://www.twilio.com/docs/php/install
- type: x-pricing
  url: https://www.twilio.com/pricing
- type: x-privacy
  url: https://www.twilio.com/legal/privacy
- type: x-python-library
  url: https://www.twilio.com/docs/python/install
- type: x-ruby-library
  url: https://www.twilio.com/docs/ruby/install
- type: x-salesforce-pdk
  url: https://www.twilio.com/docs/salesforce/install
- type: x-security
  url: https://www.twilio.com/docs/security
- type: x-service-level-agreement
  url: https://www.twilio.com/legal/service-level-agreement
- type: x-stack-overflow
  url: http://stackoverflow.com/questions/tagged/twilio
- type: x-status
  url: http://status.twilio.com/
- type: x-status-rss
  url: http://status.twilio.com/rss
- type: x-terms-of-service
  url: https://www.twilio.com/legal/tos
- type: x-trademarks
  url: https://www.twilio.com/legal/trademark
- type: x-transparency-report
  url: https://www.twilio.com/blog/2015/07/transparency-report-for-government-requests-for-customer-information.html
- type: x-transparency-report
  url: https://www.twilio.com/legal/transparency
- type: x-twitter
  url: https://twitter.com/twilio
- type: x-website
  url: http://www.twilio.com
- type: x-website
  url: http://twilio.com
- type: x-website
  url: http://stackoverflow.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---