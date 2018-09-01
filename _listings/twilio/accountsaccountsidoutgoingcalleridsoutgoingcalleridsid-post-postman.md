{
  "info": {
    "name": "Twilio Add Outgoing Caller Id",
    "_postman_id": "09c2b9b9-40aa-4782-b389-0c2292c29b73",
    "description": "Updates the caller id, and returns the updated resource if successful.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "501bcb2c-8534-48de-95ec-ba5bf55b23f2",
          "name": "getAccount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93b69d74-f7f5-42c3-b29d-a4e2887ac71c"
            }
          ]
        },
        {
          "id": "4c8aef80-2799-4042-bf65-e22a2ffc6751",
          "name": "updateAccount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update Account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb94d3f6-07d9-4739-b83d-1d85f4c03b07"
            }
          ]
        },
        {
          "id": "a84e6ef6-712e-4c59-a97f-24f3fbd26388",
          "name": "addAccount",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add Account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fbb98892-157a-4ba4-b061-87e7d3e0c9af"
            }
          ]
        },
        {
          "id": "e3a47b59-1d7a-48d8-acba-5755b29f7c2b",
          "name": "getAccounts",
          "request": {
            "url": "http://api.twilio.com/2010-04-01/Accounts.json?format=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Accounts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0160d447-1dc0-44e9-89a9-1194fd76917c"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "4c42f52f-7647-44e6-b8ab-0db2a1f4c0ae",
          "name": "get-application-instance-resource",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Applications/:ApplicationSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ApplicationSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get application instance resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1caad90-3f20-466b-8671-ecdc20c6a5ca"
            }
          ]
        },
        {
          "id": "5977d91a-1b25-4a26-93fa-58ec75195d80",
          "name": "tries-to-update-the-applications-properties-and-returns-the-updatedresource-representation-if-succes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Applications/:ApplicationSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ApplicationSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Tries to update the applications properties, and returns the updatednresource representation if successful. The returned response is identicalnto that returned above when making a GET request.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92cc31ea-4912-46e8-82da-66da84ab95ce"
            }
          ]
        },
        {
          "id": "4df271e1-a433-477e-8019-6122c11a20eb",
          "name": "delete-this-application",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Applications/:ApplicationSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ApplicationSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Application"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a339f166-dd72-43e3-b276-672d1a0822e7"
            }
          ]
        },
        {
          "id": "156de031-a35f-40ac-9e19-1fee0cf8a797",
          "name": "returns-a-list-of-application-resource-representations-each-representingan-application-within-your-a",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Applications.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Applications"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "969a729f-0ce8-4e23-b2e8-c4be87145b85"
            }
          ]
        },
        {
          "id": "b78fda04-148d-427e-a705-f574e6d92d17",
          "name": "creates-a-new-application-within-your-account",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Applications.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add Applications"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e8a2644-bd0c-49aa-92b0-4023d645bbb6"
            }
          ]
        },
        {
          "id": "b99c1a68-b75c-4cbc-9955-dea4a5ae2cb5",
          "name": "get-the-properties-of-the-authorized-application",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/AuthorizedConnectApps/:ConnectAppSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ConnectAppSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the properties of the authorized application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d8ac211-31e9-4c2d-a842-18f6d200110d"
            }
          ]
        },
        {
          "id": "5b4af06c-a721-48b1-84be-b0666c31a632",
          "name": "returns-a-list-of-connect-app-resource-representations-each-representing-aconnect-app-youve-authoriz",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/AuthorizedConnectApps.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of Connect App resource representations, each representing anConnect App youve authorized to access your account. The list includesnpaging information.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8c73a8e-1f71-4021-a1a8-23676dde0221"
            }
          ]
        },
        {
          "id": "6d2c2f3f-2783-402a-8943-1af189402dc7",
          "name": "get-the-properties-of-a-connect-app",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/ConnectApps/:ConnectAppSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ConnectAppSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the properties of a Connect App."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "346efdd4-a956-4daa-95cf-c1397109eca5"
            }
          ]
        },
        {
          "id": "f1bbf584-b59d-4a73-8257-1f2dc6bcb8bd",
          "name": "tries-to-update-the-connect-apps-properties-and-returns-the-updatedresource-representation-if-succes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/ConnectApps/:ConnectAppSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ConnectAppSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Tries to update the Connect Apps properties, and returns the updatednresource representation if successful. The returned response is identicalnto that returned above when making a GET request.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d5d76e5-5424-46a4-afde-148de40aa67d"
            }
          ]
        },
        {
          "id": "cb55f26f-d0ce-43c0-8f4c-f39726f6776e",
          "name": "returns-a-list-of-connect-app-resource-representations-each-representinga-connect-app-in-your-accoun",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/ConnectApps.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of Connect App resource representations, each representingna Connect App in your account. The list includes paging information.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c432c668-2890-4cb0-9d98-1d013a0c0ef9"
            }
          ]
        }
      ]
    },
    {
      "name": "Phone Numbers",
      "item": [
        {
          "id": "2a403c29-15f4-4bb2-8686-c3bbf72aefe9",
          "name": "returns-a-list-of-local-availablephonenumber-resource-representationsthat-match-the-specified-filter",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/AvailablePhoneNumbers/:IsoCountryCode/Local.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IsoCountryCode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of local AvailablePhoneNumber resource representationsnthat match the specified filters, each representing a phone number thanis currently available for provisioning within your account.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ccb1879a-37a4-4bce-b4f8-2244746ee633"
            }
          ]
        },
        {
          "id": "d3b0f0e0-99fe-4809-98da-59a3b058eb58",
          "name": "returns-a-list-of-mobile-availablephonenumber-resource-representations-that-match-the-specified-filt",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/AvailablePhoneNumbers/:IsoCountryCode/Mobile.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IsoCountryCode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of mobile AvailablePhoneNumber resource representations that match the specified filters, each representing a phone number that is currently available for provisioning within your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68ca10ce-5783-45f2-9293-ab4eeafa9f2b"
            }
          ]
        },
        {
          "id": "964f0197-7157-4efa-a0c9-b589cedba36e",
          "name": "returns-a-list-of-tollfree-availablephonenumber-elements-that-match-thespecified-filters-each-repres",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/AvailablePhoneNumbers/:IsoCountryCode/TollFree.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IsoCountryCode",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of toll-free AvailablePhoneNumber elements that match thenspecified filters, each representing a phone number that is currentlynavailable for provisioning within your account. To provision an availablenphone number, POST the number to the IncomingPhoneNumbers resource.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48e01170-f2ec-4d0b-a826-cb70a0d269b8"
            }
          ]
        }
      ]
    },
    {
      "name": "Recordings",
      "item": [
        {
          "id": "0af733fd-95a9-40e6-9ed3-14d76d500e64",
          "name": "returns-a-list-of-recording-resource-representations-each-representing-arecording-generated-during-t",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Calls/:CallSid/Recordings.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CallSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of Recording resource representations, each representing anrecording generated during the course of a phone call.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68c1a729-6609-49f2-9ba5-4c515f056618"
            }
          ]
        }
      ]
    },
    {
      "name": "Calls",
      "item": [
        {
          "id": "3abab3e0-d81a-4f65-bbbd-98c7f5490752",
          "name": "getCall",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Calls/:CallSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CallSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Call"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8be8e377-b395-40ba-ad7d-de22e1f886fd"
            }
          ]
        },
        {
          "id": "8b131d70-8c7a-498d-b185-418e1fd0d172",
          "name": "getCalls",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Calls.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Calls"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9d04649-7d79-47ef-a32b-58135c8374da"
            }
          ]
        },
        {
          "id": "fca5a380-38bc-404d-b8b4-d3b4a2ba6ca6",
          "name": "to-make-a-call-make-an-http-post-request-initiate-a-new-phone-call",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Calls.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "To make a call, make an HTTP POST request. Initiate a new phone call."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fdf12980-13ac-4a50-8d02-d98d9779d60f"
            }
          ]
        }
      ]
    },
    {
      "name": "Conferences",
      "item": [
        {
          "id": "4dd91276-8755-4ab3-8fa8-7339b08ad24b",
          "name": "getparticipantforconference",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Conferences/:ConferenceSid/Participants/:CallSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CallSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ConferenceSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "GetParticipantForConference"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a8a97fc-56dd-4e03-bbc2-02df811cf226"
            }
          ]
        },
        {
          "id": "a66d7f80-243b-46ba-9dc0-63b38624607a",
          "name": "getConference",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Conferences/:ConferenceSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ConferenceSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Conference"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd8de6d3-a418-4260-9cee-495d8bcb51bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Conference Calls",
      "item": [
        {
          "id": "ad65b286-034a-4d33-ac7f-fe4f952912ed",
          "name": "updates-the-status-of-a-participant",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Conferences/:ConferenceSid/Participants/:CallSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CallSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ConferenceSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the status of a participant."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "477cf915-1e6f-4674-bc0c-4061d6338dd2"
            }
          ]
        },
        {
          "id": "28a10cd2-bcdd-4563-9433-67156ae143b3",
          "name": "kick-this-participant-from-the-conference",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Conferences/:ConferenceSid/Participants/:CallSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CallSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ConferenceSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Kick this participant from the conference."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae99b05d-c1b6-4036-bfc6-36ddeda65046"
            }
          ]
        },
        {
          "id": "1f4078e1-9ec9-4402-8e14-64b7e83ee929",
          "name": "returns-the-list-of-participants-in-the-conference-identified-byconferencesid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Conferences/:ConferenceSid/Participants.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ConferenceSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of participants in the conference identified byn{ConferenceSid}.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e7f767b-eabc-40d1-bb0f-60976ca12d3b"
            }
          ]
        },
        {
          "id": "33f560af-ffc0-4789-85ef-03bf06288fb7",
          "name": "returns-a-list-of-conferences-within-an-account-the-list-includes-paginginformation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Conferences.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of conferences within an account. The list includes pagingninformation.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d300ad6-bfaa-494b-abd6-9037b52a8b88"
            }
          ]
        }
      ]
    },
    {
      "name": "Incoming Phone Numbers",
      "item": [
        {
          "id": "e3ab80a5-0659-45b4-a7bb-a82f488e7326",
          "name": "returns-a-list-of-local-incomingphonenumber-elements-each-representing-a-local-not-tollfree-phone-nu",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/IncomingPhoneNumbers/Local.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of local <IncomingPhoneNumber> elements, each representing a local (not toll-free) phone number given to your account, under an <IncomingPhoneNumbers> list element that includes paging information. Works exactly the same as the IncomingPhoneNumber resource, but filters out toll-free numbers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2adab728-252a-4a64-9aed-6b856770be33"
            }
          ]
        },
        {
          "id": "7146355b-5419-4ab4-8061-ec51f3edaa2f",
          "name": "adds-a-new-phone-number-to-your-account-if-a-phone-number-is-found-for-your-request-twilio-will-add-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/IncomingPhoneNumbers/Local.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a new phone number to your account. If a phone number is found for your request, Twilio will add it to your account and bill you for the first months cost of the phone number."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b48fa902-172a-42b5-8cf2-33e7c9c6a593"
            }
          ]
        },
        {
          "id": "6b3c20c8-75d5-4420-9ebb-78aa7748b1d8",
          "name": "returns-a-list-of-local-incomingphonenumber-elements-each-representing-a-mobile-phone-number-given-t",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/IncomingPhoneNumbers/Mobile.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of local <IncomingPhoneNumber> elements, each representing a mobile phone number given to your account, under an <IncomingPhoneNumbers> list element that includes paging information. Works exactly the same as the IncomingPhoneNumber resource, but filters out local and toll free numbers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a96f3b4a-6b75-4fa0-884e-fb947938ecc5"
            }
          ]
        },
        {
          "id": "77684edc-b928-4a80-a5de-6e7db47a98f7",
          "name": "get-info-about-incoming-calls-phone-number",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/IncomingPhoneNumbers/:IncomingPhoneNumberSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IncomingPhoneNumberSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get info about incoming calls phone number."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38a2b442-d771-4ed3-b4c0-7a01193dbbea"
            }
          ]
        },
        {
          "id": "cd0b47e9-41cf-40c6-a341-ef8a3249c977",
          "name": "tries-to-update-the-incoming-phone-numbers-properties-and-returns-theupdated-resource-representation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/IncomingPhoneNumbers/:IncomingPhoneNumberSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IncomingPhoneNumberSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Tries to update the incoming phone numbers properties, and returns thenupdated resource representation if successful. The returned response isnidentical to that returned above when making a GET request.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25b9841b-094b-498b-95c4-5f16607a7ea7"
            }
          ]
        },
        {
          "id": "fa5ecd57-7873-44da-9da8-647547d34fbe",
          "name": "tries-to-update-the-incoming-phone-numbers-properties-and-returns-theupdated-resource-representation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/IncomingPhoneNumbers/:IncomingPhoneNumberSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IncomingPhoneNumberSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Tries to update the incoming phone numbers properties, and returns thenupdated resource representation if successful. The returned response isnidentical to that returned above when making a GET request.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e89560a-f320-48c4-a765-eef0bf631189"
            }
          ]
        },
        {
          "id": "b5220848-0086-44c6-b9cb-f68bd56807e8",
          "name": "release-this-phone-number-from-your-account-twilio-will-no-longer-answercalls-to-this-number-and-you",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/IncomingPhoneNumbers/:IncomingPhoneNumberSid.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IncomingPhoneNumberSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Release this phone number from your account. Twilio will no longer answerncalls to this number, and you will stop being billed the monthly phonennumber fee. The phone number will eventually be recycled and potentiallyngiven to another customer, so use with care. If you make a mistake, contacnus. We may be able to give you the number back.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5735baaf-2437-4200-9958-fabe3d19793b"
            }
          ]
        }
      ]
    },
    {
      "name": "Messages",
      "item": [
        {
          "id": "50e5b877-5ca0-4bc3-a960-dbb1b084b5fd",
          "name": "without-an-extension-the-media-is-returned-using-the-mimetype-provided-when-the-media-was-generated",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Messages/:MessageSid/Media/:MediaSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "MediaSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "MessageSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Without an extension, the media is returned using the mime-type provided when the media was generated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f34f7567-8fe7-4313-bafa-0936de46914c"
            }
          ]
        },
        {
          "id": "ffa7e010-f438-40a1-bad3-c1dc91a46cc1",
          "name": "returns-a-list-of-media-associated-with-your-message",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Messages/:MessageSid/Media"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "MessageSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of media associated with your message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ec5012d-f75a-4144-aa46-d01bca7868e7"
            }
          ]
        },
        {
          "id": "760154d3-5da1-44ef-806f-4e4c68f58fac",
          "name": "returns-a-single-message-specified-by-the-provided-messagesid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Messages/:MessageSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "MessageSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a single message specified by the provided {MessageSid}.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fe4fcad-3b2b-49dc-8d77-d01f43dee56f"
            }
          ]
        },
        {
          "id": "3f698421-b824-4227-8636-e2c0164be7e1",
          "name": "returns-a-list-of-messages-associated-with-your-account-the-list-includes-paging-information",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Messages.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of messages associated with your account. The list includes paging information."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d1ba15e-bd4c-4372-9489-f88110f3d62d"
            }
          ]
        },
        {
          "id": "50998ac1-dd0d-4062-a0fc-2fd4a81430a6",
          "name": "to-send-a-new-outgoing-message-make-an-http-post-to-your-messages-list-resource-uri",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Messages.json"
              ],
              "query": [
                {
                  "key": "format",
                  "value": "format",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "To send a new outgoing message, make an HTTP POST to your Messages list resource URI"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "494a7af2-fcad-43e1-9441-b3d2235ce21c"
            }
          ]
        }
      ]
    },
    {
      "name": "Outgoing Caller IDs",
      "item": [
        {
          "id": "5529f495-5140-41e2-bbf5-af0aa6e84d84",
          "name": "get-the-set-of-an-accounts-verified-phone-numbers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/OutgoingCallerIds/:OutgoingCallerIdSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "OutgoingCallerIdSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the set of an accounts verified phone numbers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a940f5a-b304-46f8-b090-e4bad5d48ebb"
            }
          ]
        },
        {
          "id": "55425714-01cd-4296-b18a-103f9f4b4bed",
          "name": "updates-the-caller-id-and-returns-the-updated-resource-if-successful",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/OutgoingCallerIds/:OutgoingCallerIdSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "OutgoingCallerIdSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the caller id, and returns the updated resource if successful."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ef73f1e-6a86-4b9d-8475-edf26b3667cc"
            }
          ]
        }
      ]
    }
  ]
}