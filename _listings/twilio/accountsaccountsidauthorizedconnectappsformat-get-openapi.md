---
swagger: "2.0"
x-collection-name: Twilio
x-complete: 0
info:
  title: Twilio Get Authorized Connected Apps
  description: Returns a list of Connect App resource representations, each representing
    anConnect App youve authorized to access your account. The list includesnpaging
    information.n
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
      x-api-path-slug: accountsaccountsidformat-get
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
      x-api-path-slug: accountsaccountsidformat-post
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
      x-api-path-slug: accountsaccountsidformat-put
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
      x-api-path-slug: accountsformat-get
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
      x-api-path-slug: accountsaccountsidapplicationsapplicationsidformat-delete
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
      x-api-path-slug: accountsaccountsidapplicationsapplicationsidformat-get
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
      x-api-path-slug: accountsaccountsidapplicationsapplicationsidformat-post
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
      x-api-path-slug: accountsaccountsidapplicationsformat-get
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
      x-api-path-slug: accountsaccountsidapplicationsformat-post
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
      x-api-path-slug: accountsaccountsidauthorizedconnectappsconnectappsidformat-get
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
      x-api-path-slug: accountsaccountsidauthorizedconnectappsformat-get
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