---
swagger: "2.0"
x-collection-name: Twilio
x-complete: 0
info:
  title: Twilio Get SIP Credentials List
  description: Get the list of Credentials in a CredentialList. The passwords for
    the Credentials are intentionally not returned so as to protect them.
  termsOfService: https://www.twilio.com/legal/tos
  version: v1
host: api.twilio.com
basePath: /2010-04-01/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Accounts/{AccountSid}.{format}:
    get:
      summary: Get Acount
      description: Get Account
      operationId: getAccount
      x-api-path-slug: accountsaccountsid-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Accounts
    post:
      summary: Add Account
      description: Add Account
      operationId: addAccount
      x-api-path-slug: accountsaccountsid-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Accounts
    put:
      summary: Update Account
      description: Update Account
      operationId: updateAccount
      x-api-path-slug: accountsaccountsid-format-put
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /Accounts.{format}:
    get:
      summary: Get Accounts
      description: Get Accounts
      operationId: getAccounts
      x-api-path-slug: accounts-format-get
      parameters:
      - in: formData
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /Accounts/{AccountSid}/Applications/{ApplicationSid}.{format}:
    delete:
      summary: Delete Application
      description: Delete Application
      operationId: delete-this-application
      x-api-path-slug: accountsaccountsidapplicationsapplicationsid-format-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: ApplicationSid
        description: The ID for the Twilio application
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
    get:
      summary: Get Application
      description: Get application instance resource.
      operationId: get-application-instance-resource
      x-api-path-slug: accountsaccountsidapplicationsapplicationsid-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: ApplicationSid
        description: The ID for the Twilio application
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
    post:
      summary: Add Application
      description: Tries to update the applications properties, and returns the updatednresource
        representation if successful. The returned response is identicalnto that returned
        above when making a GET request.n
      operationId: tries-to-update-the-applications-properties-and-returns-the-updatedresource-representation-if-succes
      x-api-path-slug: accountsaccountsidapplicationsapplicationsid-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: ApplicationSid
        description: The ID for the Twilio application
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /Accounts/{AccountSid}/Applications.{format}:
    get:
      summary: Get Applications
      description: Get Applications
      operationId: returns-a-list-of-application-resource-representations-each-representingan-application-within-your-a
      x-api-path-slug: accountsaccountsidapplications-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
    post:
      summary: Add Applications
      description: Add Applications
      operationId: creates-a-new-application-within-your-account
      x-api-path-slug: accountsaccountsidapplications-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /Accounts/{AccountSid}/AuthorizedConnectApps/{ConnectAppSid}.{format}:
    get:
      summary: Get Authorized Connected App
      description: Get the properties of the authorized application.
      operationId: get-the-properties-of-the-authorized-application
      x-api-path-slug: accountsaccountsidauthorizedconnectappsconnectappsid-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: ConnectAppSid
        description: A 34 character string that uniquely identifies the connected
          app
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /Accounts/{AccountSid}/AuthorizedConnectApps.{format}:
    get:
      summary: Get Authorized Connected Apps
      description: Returns a list of Connect App resource representations, each representing
        anConnect App youve authorized to access your account. The list includesnpaging
        information.n
      operationId: returns-a-list-of-connect-app-resource-representations-each-representing-aconnect-app-youve-authoriz
      x-api-path-slug: accountsaccountsidauthorizedconnectapps-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /Accounts/{AccountSid}/AvailablePhoneNumbers/{IsoCountryCode}/Local.{format}:
    get:
      summary: Get Available Local Phone Numbers
      description: Returns a list of local AvailablePhoneNumber resource representationsnthat
        match the specified filters, each representing a phone number thanis currently
        available for provisioning within your account.n
      operationId: returns-a-list-of-local-availablephonenumber-resource-representationsthat-match-the-specified-filter
      x-api-path-slug: accountsaccountsidavailablephonenumbersisocountrycodelocal-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      - in: path
        name: IsoCountryCode
        description: ISO 3166-1 alpha-2
      responses:
        200:
          description: OK
      tags:
      - Phone Numbers
  /Accounts/{AccountSid}/AvailablePhoneNumbers/{IsoCountryCode}/Mobile.{format}:
    get:
      summary: Get Available Mobile Phone Numbers
      description: Returns a list of mobile AvailablePhoneNumber resource representations
        that match the specified filters, each representing a phone number that is
        currently available for provisioning within your account.
      operationId: returns-a-list-of-mobile-availablephonenumber-resource-representations-that-match-the-specified-filt
      x-api-path-slug: accountsaccountsidavailablephonenumbersisocountrycodemobile-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      - in: path
        name: IsoCountryCode
        description: ISO 3166-1 alpha-2
      responses:
        200:
          description: OK
      tags:
      - Phone Numbers
  /Accounts/{AccountSid}/AvailablePhoneNumbers/{IsoCountryCode}/TollFree.{format}:
    get:
      summary: Get Available Toll Free Phone Numbers
      description: Returns a list of toll-free AvailablePhoneNumber elements that
        match thenspecified filters, each representing a phone number that is currentlynavailable
        for provisioning within your account. To provision an availablenphone number,
        POST the number to the IncomingPhoneNumbers resource.n
      operationId: returns-a-list-of-tollfree-availablephonenumber-elements-that-match-thespecified-filters-each-repres
      x-api-path-slug: accountsaccountsidavailablephonenumbersisocountrycodetollfree-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      - in: path
        name: IsoCountryCode
        description: ISO 3166-1 alpha-2
      responses:
        200:
          description: OK
      tags:
      - Phone Numbers
  /Accounts/{AccountSid}/Calls/{CallSid}/Recordings.{format}:
    get:
      summary: Get Recordings
      description: Returns a list of Recording resource representations, each representing
        anrecording generated during the course of a phone call.n
      operationId: returns-a-list-of-recording-resource-representations-each-representing-arecording-generated-during-t
      x-api-path-slug: accountsaccountsidcallscallsidrecordings-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CallSid
        description: A 34 character string that uniquely identifies the call
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Recordings
  /Accounts/{AccountSid}/Calls/{CallSid}.{format}:
    get:
      summary: Get Call
      description: Get Call
      operationId: getCall
      x-api-path-slug: accountsaccountsidcallscallsid-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CallSid
        description: A 34 character string that uniquely identifies the call
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Calls
  /Accounts/{AccountSid}/Calls.{format}:
    get:
      summary: Get Calls
      description: Get Calls
      operationId: getCalls
      x-api-path-slug: accountsaccountsidcalls-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Calls
    post:
      summary: Make Call
      description: To make a call, make an HTTP POST request. Initiate a new phone
        call.
      operationId: to-make-a-call-make-an-http-post-request-initiate-a-new-phone-call
      x-api-path-slug: accountsaccountsidcalls-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Calls
  /Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants/{CallSid}.{format}:
    delete:
      summary: Delete Conference Call Participants
      description: Kick this participant from the conference.
      operationId: kick-this-participant-from-the-conference
      x-api-path-slug: accountsaccountsidconferencesconferencesidparticipantscallsid-format-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CallSid
        description: A 34 character string that uniquely identifies the call
      - in: path
        name: ConferenceSid
        description: A 34 character string that uniquely identifies the conference
          call object
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Conference Calls
    post:
      summary: Add Conference Call Participants
      description: Updates the status of a participant.
      operationId: updates-the-status-of-a-participant
      x-api-path-slug: accountsaccountsidconferencesconferencesidparticipantscallsid-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CallSid
        description: A 34 character string that uniquely identifies the call
      - in: path
        name: ConferenceSid
        description: A 34 character string that uniquely identifies the conference
          call object
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Conference Calls
    get:
      summary: GetParticipantForConference
      description: GetParticipantForConference
      operationId: getparticipantforconference
      x-api-path-slug: accountsaccountsidconferencesconferencesidparticipantscallsid-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CallSid
        description: A 34 character string that uniquely identifies the call
      - in: path
        name: ConferenceSid
        description: A 34 character string that uniquely identifies the conference
          call object
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
      responses:
        200:
          description: OK
      tags:
      - Conferences
  /Accounts/{AccountSid}/Conferences/{ConferenceSid}/Participants.{format}:
    get:
      summary: Get Conference Call Participants
      description: Returns the list of participants in the conference identified byn{ConferenceSid}.n
      operationId: returns-the-list-of-participants-in-the-conference-identified-byconferencesid
      x-api-path-slug: accountsaccountsidconferencesconferencesidparticipants-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: ConferenceSid
        description: A 34 character string that uniquely identifies the conference
          call object
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Conference Calls
  /Accounts/{AccountSid}/Conferences.{format}:
    get:
      summary: Get Conference Calls
      description: Returns a list of conferences within an account. The list includes
        pagingninformation.n
      operationId: returns-a-list-of-conferences-within-an-account-the-list-includes-paginginformation
      x-api-path-slug: accountsaccountsidconferences-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Conference Calls
  /Accounts/{AccountSid}/Conferences/{ConferenceSid}.{format}:
    get:
      summary: Get Conference
      description: Get Conference
      operationId: getConference
      x-api-path-slug: accountsaccountsidconferencesconferencesid-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: ConferenceSid
        description: A 34 character string that uniquely identifies the conference
          call object
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
      responses:
        200:
          description: OK
      tags:
      - Conferences
  /Accounts/{AccountSid}/ConnectApps/{ConnectAppSid}.{format}:
    get:
      summary: Get Connected App
      description: Get the properties of a Connect App.
      operationId: get-the-properties-of-a-connect-app
      x-api-path-slug: accountsaccountsidconnectappsconnectappsid-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: ConnectAppSid
        description: A 34 character string that uniquely identifies the connected
          app
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
    post:
      summary: Add Connected App
      description: Tries to update the Connect Apps properties, and returns the updatednresource
        representation if successful. The returned response is identicalnto that returned
        above when making a GET request.n
      operationId: tries-to-update-the-connect-apps-properties-and-returns-the-updatedresource-representation-if-succes
      x-api-path-slug: accountsaccountsidconnectappsconnectappsid-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: ConnectAppSid
        description: A 34 character string that uniquely identifies the connected
          app
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /Accounts/{AccountSid}/ConnectApps.{format}:
    get:
      summary: Get Connected Apps
      description: Returns a list of Connect App resource representations, each representingna
        Connect App in your account. The list includes paging information.n
      operationId: returns-a-list-of-connect-app-resource-representations-each-representinga-connect-app-in-your-accoun
      x-api-path-slug: accountsaccountsidconnectapps-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /Accounts/{AccountSid}/IncomingPhoneNumbers/Local.{format}:
    get:
      summary: Get Incoming Local Phone Numbers
      description: Returns a list of local <IncomingPhoneNumber> elements, each representing
        a local (not toll-free) phone number given to your account, under an <IncomingPhoneNumbers>
        list element that includes paging information. Works exactly the same as the
        IncomingPhoneNumber resource, but filters out toll-free numbers.
      operationId: returns-a-list-of-local-incomingphonenumber-elements-each-representing-a-local-not-tollfree-phone-nu
      x-api-path-slug: accountsaccountsidincomingphonenumberslocal-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Incoming Phone Numbers
    post:
      summary: Add Incoming Local Phone Numbers
      description: Adds a new phone number to your account. If a phone number is found
        for your request, Twilio will add it to your account and bill you for the
        first months cost of the phone number.
      operationId: adds-a-new-phone-number-to-your-account-if-a-phone-number-is-found-for-your-request-twilio-will-add-
      x-api-path-slug: accountsaccountsidincomingphonenumberslocal-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Incoming Phone Numbers
  /Accounts/{AccountSid}/IncomingPhoneNumbers/Mobile.{format}:
    get:
      summary: Get Incoming Phone Numbers
      description: Returns a list of local <IncomingPhoneNumber> elements, each representing
        a mobile phone number given to your account, under an <IncomingPhoneNumbers>
        list element that includes paging information. Works exactly the same as the
        IncomingPhoneNumber resource, but filters out local and toll free numbers.
      operationId: returns-a-list-of-local-incomingphonenumber-elements-each-representing-a-mobile-phone-number-given-t
      x-api-path-slug: accountsaccountsidincomingphonenumbersmobile-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Incoming Phone Numbers
  /Accounts/{AccountSid}/IncomingPhoneNumbers/{IncomingPhoneNumberSid}.{format}:
    delete:
      summary: Delete Incoming Phone Number
      description: Release this phone number from your account. Twilio will no longer
        answerncalls to this number, and you will stop being billed the monthly phonennumber
        fee. The phone number will eventually be recycled and potentiallyngiven to
        another customer, so use with care. If you make a mistake, contacnus. We may
        be able to give you the number back.n
      operationId: release-this-phone-number-from-your-account-twilio-will-no-longer-answercalls-to-this-number-and-you
      x-api-path-slug: accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      - in: path
        name: IncomingPhoneNumberSid
        description: A 34 character string that uniquely identifies the incoming phone
          number
      responses:
        200:
          description: OK
      tags:
      - Incoming Phone Numbers
    get:
      summary: Get Incoming Phone Number
      description: Get info about incoming calls phone number.
      operationId: get-info-about-incoming-calls-phone-number
      x-api-path-slug: accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      - in: path
        name: IncomingPhoneNumberSid
        description: A 34 character string that uniquely identifies the incoming phone
          number
      responses:
        200:
          description: OK
      tags:
      - Incoming Phone Numbers
    post:
      summary: Add Incoming Phone Number
      description: Tries to update the incoming phone numbers properties, and returns
        thenupdated resource representation if successful. The returned response isnidentical
        to that returned above when making a GET request.n
      operationId: tries-to-update-the-incoming-phone-numbers-properties-and-returns-theupdated-resource-representation
      x-api-path-slug: accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      - in: path
        name: IncomingPhoneNumberSid
        description: A 34 character string that uniquely identifies the incoming phone
          number
      responses:
        200:
          description: OK
      tags:
      - Incoming Phone Numbers
    put:
      summary: Update Incoming Phone Number
      description: Tries to update the incoming phone numbers properties, and returns
        thenupdated resource representation if successful. The returned response isnidentical
        to that returned above when making a GET request.n
      operationId: tries-to-update-the-incoming-phone-numbers-properties-and-returns-theupdated-resource-representation
      x-api-path-slug: accountsaccountsidincomingphonenumbersincomingphonenumbersid-format-put
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      - in: path
        name: IncomingPhoneNumberSid
        description: A 34 character string that uniquely identifies the incoming phone
          number
      responses:
        200:
          description: OK
      tags:
      - Incoming Phone Numbers
  /Accounts/{AccountSid}/Messages/{MessageSid}/Media/{MediaSid}:
    get:
      summary: Get Message Media
      description: Without an extension, the media is returned using the mime-type
        provided when the media was generated.
      operationId: without-an-extension-the-media-is-returned-using-the-mimetype-provided-when-the-media-was-generated
      x-api-path-slug: accountsaccountsidmessagesmessagesidmediamediasid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: MediaSid
        description: A 34 character string that uniquely identifies the media object
      - in: path
        name: MessageSid
        description: A 34 character string that uniquely identifies the message
      responses:
        200:
          description: OK
      tags:
      - Messages
  /Accounts/{AccountSid}/Messages/{MessageSid}/Media:
    get:
      summary: Get Message Media
      description: Returns a list of media associated with your message.
      operationId: returns-a-list-of-media-associated-with-your-message
      x-api-path-slug: accountsaccountsidmessagesmessagesidmedia-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: MessageSid
        description: A 34 character string that uniquely identifies the message
      responses:
        200:
          description: OK
      tags:
      - Messages
  /Accounts/{AccountSid}/Messages/{MessageSid}:
    get:
      summary: Get Message Media
      description: Returns a single message specified by the provided {MessageSid}.n
      operationId: returns-a-single-message-specified-by-the-provided-messagesid
      x-api-path-slug: accountsaccountsidmessagesmessagesid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: MessageSid
        description: A 34 character string that uniquely identifies the message
      responses:
        200:
          description: OK
      tags:
      - Messages
  /Accounts/{AccountSid}/Messages.{format}:
    get:
      summary: Get Message Media
      description: Returns a list of messages associated with your account. The list
        includes paging information.
      operationId: returns-a-list-of-messages-associated-with-your-account-the-list-includes-paging-information
      x-api-path-slug: accountsaccountsidmessages-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Messages
    post:
      summary: Add Message
      description: To send a new outgoing message, make an HTTP POST to your Messages
        list resource URI
      operationId: to-send-a-new-outgoing-message-make-an-http-post-to-your-messages-list-resource-uri
      x-api-path-slug: accountsaccountsidmessages-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Messages
  /Accounts/{AccountSid}/OutgoingCallerIds/{OutgoingCallerIdSid}:
    get:
      summary: Get Outgoing Caller Ids
      description: Get the set of an accounts verified phone numbers.
      operationId: get-the-set-of-an-accounts-verified-phone-numbers
      x-api-path-slug: accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: OutgoingCallerIdSid
        description: A 34 character string that uniquely identifies the outgoing caller
          id
      responses:
        200:
          description: OK
      tags:
      - Outgoing Caller IDs
    post:
      summary: Add Outgoing Caller Id
      description: Updates the caller id, and returns the updated resource if successful.
      operationId: updates-the-caller-id-and-returns-the-updated-resource-if-successful
      x-api-path-slug: accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: OutgoingCallerIdSid
        description: A 34 character string that uniquely identifies the outgoing caller
          id
      responses:
        200:
          description: OK
      tags:
      - Outgoing Caller IDs
    put:
      summary: Update Outgoing Caller Id
      description: Updates the caller id, and returns the updated resource if successful.
      operationId: updates-the-caller-id-and-returns-the-updated-resource-if-successful
      x-api-path-slug: accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-put
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: OutgoingCallerIdSid
        description: A 34 character string that uniquely identifies the outgoing caller
          id
      responses:
        200:
          description: OK
      tags:
      - Outgoing Caller IDs
    delete:
      summary: Delete Outgoing Caller ID
      description: DeleteOutgoingCallerId
      operationId: deleteoutgoingcallerid
      x-api-path-slug: accountsaccountsidoutgoingcalleridsoutgoingcalleridsid-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
      - in: path
        name: OutgoingCallerIdSid
        description: A 34 character string that uniquely identifies the outgoing caller
          id
      responses:
        200:
          description: OK
      tags:
      - Outgoing Caller IDs
  /Accounts/{AccountSid}/OutgoingCallerIds:
    get:
      summary: Get Outgoing Caller Ids
      description: Returns a list of OutgoingCallerId resource representations, each
        representingna Caller ID number valid for an account. The list includes paging
        information.n
      operationId: returns-a-list-of-outgoingcallerid-resource-representations-each-representinga-caller-id-number-vali
      x-api-path-slug: accountsaccountsidoutgoingcallerids-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      responses:
        200:
          description: OK
      tags:
      - Outgoing Caller IDs
    post:
      summary: Add Outgoing Caller Id
      description: Adds a new CallerID to your account.
      operationId: adds-a-new-callerid-to-your-account
      x-api-path-slug: accountsaccountsidoutgoingcallerids-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      responses:
        200:
          description: OK
      tags:
      - Outgoing Caller IDs
  /Accounts/{AccountSid}/Queues/{QueueSid}/Members/Front:
    get:
      summary: Get Queue Members In Front
      description: Get a front member.
      operationId: get-a-front-member
      x-api-path-slug: accountsaccountsidqueuesqueuesidmembersfront-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
    post:
      summary: Update Queue Members In Front
      description: Posting a URL and Method to a Queue instance will dequeue a member
        from anqueue and have the members call begin executing the TwiML document
        at that URLnWhen dequeuing the Front of the queue, the next call in the queue
        will be redirected.n
      operationId: posting-a-url-and-method-to-a-queue-instance-will-dequeue-a-member-from-aqueue-and-have-the-members-
      x-api-path-slug: accountsaccountsidqueuesqueuesidmembersfront-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
  /Accounts/{AccountSid}/Queues/{QueueSid}/Members/{CallSid}:
    get:
      summary: Get Queue Members
      description: Get a specific member.
      operationId: get-a-specific-member
      x-api-path-slug: accountsaccountsidqueuesqueuesidmemberscallsid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CallSid
        description: A 34 character string that uniquely identifies the call
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
    post:
      summary: Update Queue Members
      description: Posting a URL and Method to a Queue instance will dequeue a member
        from anqueue and have the members call begin executing the TwiML document
        at that URLnWhen redirecting a member of a queue addressed by CallSid, only
        the first requestnwill succeed and return a 200 response code. A second request
        will fail andnreturn an appropriate 400 response code.n
      operationId: posting-a-url-and-method-to-a-queue-instance-will-dequeue-a-member-from-aqueue-and-have-the-members-
      x-api-path-slug: accountsaccountsidqueuesqueuesidmemberscallsid-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CallSid
        description: A 34 character string that uniquely identifies the call
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
  /Accounts/{AccountSid}/Queues/{QueueSid}/Members:
    get:
      summary: Get Queue Members
      description: Returns the list of members in the queue identified by {QueueSid}.
      operationId: returns-the-list-of-members-in-the-queue-identified-by-queuesid
      x-api-path-slug: accountsaccountsidqueuesqueuesidmembers-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
  /Accounts/{AccountSid}/Queues/{QueueSid}:
    delete:
      summary: Delete Queue Members
      description: The DELETE method allows you to remove a Queue. Only empty queues
        arendeletable.n
      operationId: the-delete-method-allows-you-to-remove-a-queue-only-empty-queues-aredeletable
      x-api-path-slug: accountsaccountsidqueuesqueuesid-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
    get:
      summary: Get Queue Members
      description: Get resources individual Queue instance.n
      operationId: get-resources-individual-queue-instance
      x-api-path-slug: accountsaccountsidqueuesqueuesid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
    post:
      summary: Add Queue Members
      description: This POST request allows you to change the FriendlyName or MaxSize.n
      operationId: this-post-request-allows-you-to-change-the-friendlyname-or-maxsize
      x-api-path-slug: accountsaccountsidqueuesqueuesid-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: QueueSid
        description: A 34 character string that uniquely identifies the queue
      responses:
        200:
          description: OK
      tags:
      - Queues
  /Accounts/{AccountSid}/Queues:
    get:
      summary: Get Queues
      description: Returns a list of queues within an account. The list includes pagingninformation.n
      operationId: returns-a-list-of-queues-within-an-account-the-list-includes-paginginformation
      x-api-path-slug: accountsaccountsidqueues-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      responses:
        200:
          description: OK
      tags:
      - Queues
    post:
      summary: Add Queue
      description: Create a new Queue resource.n
      operationId: create-a-new-queue-resource
      x-api-path-slug: accountsaccountsidqueues-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      responses:
        200:
          description: OK
      tags:
      - Queues
  /Accounts/{AccountSid}/Recordings/{RecordingSid}/Transcriptions:
    get:
      summary: Get Recording Transcriptions
      description: Returns a set of Transcription resource representations that includes
        pagingninformation.n
      operationId: returns-a-set-of-transcription-resource-representations-that-includes-paginginformation
      x-api-path-slug: accountsaccountsidrecordingsrecordingsidtranscriptions-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: RecordingSid
        description: A 34 character string that uniquely identifies the recording
      responses:
        200:
          description: OK
      tags:
      - Recordings
  /Accounts/{AccountSid}/Recordings/{RecordingSid}:
    delete:
      summary: Delete Recording
      description: Deletes a recording  from your account.
      operationId: deletes-a-recording--from-your-account
      x-api-path-slug: accountsaccountsidrecordingsrecordingsid-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: RecordingSid
        description: A 34 character string that uniquely identifies the recording
      responses:
        200:
          description: OK
      tags:
      - Recordings
    get:
      summary: Get Recording
      description: Returns one of several representations:nWithout an extension, or
        with a .wav, a binary WAV audio file is returnednwith mime-type audio/x-wav.nAppending
        .mp3 to the URI returns a binary MP3 audio file with mime-typentype audio/mpeg.nAppending
        .xml to the URI returns a XML representation.n
      operationId: returns-one-of-several-representationswithout-an-extension-or-with-a-wav-a-binary-wav-audio-file-is-
      x-api-path-slug: accountsaccountsidrecordingsrecordingsid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: RecordingSid
        description: A 34 character string that uniquely identifies the recording
      responses:
        200:
          description: OK
      tags:
      - Recordings
  /Accounts/{AccountSid}/Recordings:
    get:
      summary: Get Recordings
      description: Returns a list of Recording resource representations, each representing
        anrecording generated during the course of a phone call.n
      operationId: returns-a-list-of-recording-resource-representations-each-representing-arecording-generated-during-t
      x-api-path-slug: accountsaccountsidrecordings-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      responses:
        200:
          description: OK
      tags:
      - Recordings
  /Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}/Credentials/{CredentialSid}:
    delete:
      summary: Delete SIP Credential From List
      description: Remove a Credential from a CredentialList.
      operationId: remove-a-credential-from-a-credentiallist
      x-api-path-slug: accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-delete
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CLSid
        description: A 34 character string that uniquely identifies the credential
          list
      - in: path
        name: CredentialSid
      responses:
        200:
          description: OK
      tags:
      - SIP Credential Lists
    get:
      summary: Get SIP Credentials List
      description: Get a specific Credential in a list. Though a password is stored
        for each username in your list, the password is not returned to protect your
        password. If you cannot remember your password, you will need to POST to this
        resource to update it.
      operationId: get-a-specific-credential-in-a-list-though-a-password-is-stored-for-each-username-in-your-list-the-p
      x-api-path-slug: accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CLSid
        description: A 34 character string that uniquely identifies the credential
          list
      - in: path
        name: CredentialSid
      responses:
        200:
          description: OK
      tags:
      - SIP Credential Lists
    post:
      summary: Add To SIP Credentials List
      description: Change the password of a Credential record.nnIf the change is successful,
        Twilio will respond with the Credential record but will not include the password
        in the response.n
      operationId: change-the-password-of-a-credential-recordif-the-change-is-successful-twilio-will-respond-with-the-c
      x-api-path-slug: accountsaccountsidsipcredentiallistsclsidcredentialscredentialsid-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CLSid
        description: A 34 character string that uniquely identifies the credential
          list
      - in: path
        name: CredentialSid
      responses:
        200:
          description: OK
      tags:
      - SIP Credential Lists
  /Accounts/{AccountSid}/SIP/CredentialLists/{CLSid}/Credentials:
    get:
      summary: Get SIP Credentials List
      description: Get the list of Credentials in a CredentialList. The passwords
        for the Credentials are intentionally not returned so as to protect them.
      operationId: get-the-list-of-credentials-in-a-credentiallist-the-passwords-for-the-credentials-are-intentionally-
      x-api-path-slug: accountsaccountsidsipcredentiallistsclsidcredentials-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: CLSid
        description: A 34 character string that uniquely identifies the credential
          list
      responses:
        200:
          description: OK
      tags:
      - SIP Credential Lists
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---