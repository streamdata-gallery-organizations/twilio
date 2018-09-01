{
  "info": {
    "name": "Twilio Update Outgoing Caller Id",
    "_postman_id": "d52ce9b3-da18-4430-8694-7fcd26aab7be",
    "description": "Updates the caller id, and returns the updated resource if successful.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "7ea416ee-90d1-4400-8271-e943bc6ad0a3",
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
              "id": "9f9b038e-4cfc-4fac-8687-c234ac72bbad"
            }
          ]
        },
        {
          "id": "a5710ba6-b9fb-4dca-a077-c14e06ea777f",
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
              "id": "a7a9c303-8a5f-4039-a8e7-b91c9acc7be7"
            }
          ]
        },
        {
          "id": "d5dbaa2c-359b-4efc-8e19-62f9b0ded098",
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
              "id": "bef13841-59f5-46ef-9045-0c349cb0be71"
            }
          ]
        },
        {
          "id": "66c4bd75-8736-413c-aa2c-47dcbe3893ee",
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
              "id": "1c5fb1d4-e72f-464c-acfc-25b669c116a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "2bde6973-8855-4c8b-a4c3-dbdf105fdbb3",
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
              "id": "791e9b16-a922-4060-957e-7f7282cb43f2"
            }
          ]
        },
        {
          "id": "0ae6f596-6e22-490c-bae0-8d0473beba64",
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
              "id": "c21b3465-118a-408c-ba68-5688d54b5416"
            }
          ]
        },
        {
          "id": "f457455a-58da-4ca0-9f59-32487f0f6470",
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
              "id": "94196a06-8694-4762-a19a-60fdc38bee7b"
            }
          ]
        },
        {
          "id": "6886e758-cfd6-45a5-8f4b-d95425e34713",
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
              "id": "d6d084e3-f8d4-4022-9790-ce6dc51e8a24"
            }
          ]
        },
        {
          "id": "d408cb40-bec9-48b3-82d5-eec35393fb1f",
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
              "id": "014b75ef-2d3c-4861-a534-844a2bae3cf3"
            }
          ]
        },
        {
          "id": "d5366f55-71a0-43e0-9f06-f78ab96e7866",
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
              "id": "1c348abd-9417-4249-933e-a8ff37389ae2"
            }
          ]
        },
        {
          "id": "8389f9a9-7269-49ea-a5f2-218b4677331c",
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
              "id": "93b8da01-3ad8-4914-bd62-de68ac5bd9e3"
            }
          ]
        },
        {
          "id": "f54a64e1-31a4-4310-9136-0f70cf7cdaf9",
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
              "id": "9d64b617-c2e8-4d14-8c9d-4bea96b75862"
            }
          ]
        },
        {
          "id": "f278b446-7bb1-44eb-832a-77b5414967ec",
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
              "id": "f09bc9c9-88c7-4bfd-8983-5efe7477decf"
            }
          ]
        },
        {
          "id": "75a7e0a8-adeb-4bfa-807e-7af5f31d2deb",
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
              "id": "037c1828-ebe6-4173-a9e0-416617b0bff5"
            }
          ]
        }
      ]
    },
    {
      "name": "Phone Numbers",
      "item": [
        {
          "id": "e173cb6e-b192-4db3-921d-dc14d5ecf3ef",
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
              "id": "e91bbf6b-1c3d-48ea-aeb1-fdcfd7dc5072"
            }
          ]
        },
        {
          "id": "7b9597cf-6bb8-4c10-9e0d-7afa81899cdd",
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
              "id": "03b351b5-a1e1-4fa3-aa7d-726ae9391aa1"
            }
          ]
        },
        {
          "id": "5f4b854a-373f-49a4-8523-87ac393b463f",
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
              "id": "bc78cd12-cb6f-4f62-8a63-f3cc96514a83"
            }
          ]
        }
      ]
    },
    {
      "name": "Recordings",
      "item": [
        {
          "id": "51df2dc6-8ffa-4d97-b712-92b45b1c7c44",
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
              "id": "56b8cb39-fc03-42b8-a5f3-a60d8245ddf0"
            }
          ]
        }
      ]
    },
    {
      "name": "Calls",
      "item": [
        {
          "id": "246fe091-84dc-4162-b827-0dee0082b9ed",
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
              "id": "b08245e3-8f12-45e0-bbca-ee03dfae83ce"
            }
          ]
        },
        {
          "id": "0377b513-87bb-43c9-beda-edfa643d15f8",
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
              "id": "97641f71-30c0-4657-83d3-6834cc33ae30"
            }
          ]
        },
        {
          "id": "98a9df24-7642-4da1-b71a-0871ec0a2e83",
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
              "id": "3940983b-e5e5-4050-9fcf-1ab14409f1eb"
            }
          ]
        }
      ]
    },
    {
      "name": "Conferences",
      "item": [
        {
          "id": "4b4f4e8a-a8eb-4b14-b152-6bba473ce852",
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
              "id": "1dabd7ac-02a1-4ce0-95db-161cff547904"
            }
          ]
        },
        {
          "id": "b0755c90-01c2-41be-9c96-60bc712c3163",
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
              "id": "8010f24c-eb66-4954-8fe7-02e582e9cae6"
            }
          ]
        }
      ]
    },
    {
      "name": "Conference Calls",
      "item": [
        {
          "id": "78007957-8afd-42ca-8277-5d13cd5c28a8",
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
              "id": "067a990b-63e7-4022-8336-977d533ecdb4"
            }
          ]
        },
        {
          "id": "ffb06e48-6a40-4d5a-9c9b-2531ea083968",
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
              "id": "a5cc04ce-3942-4aad-b216-208281ac0a62"
            }
          ]
        },
        {
          "id": "2b876ab6-a16e-4d9f-b0af-db6f9ba4d3b0",
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
              "id": "a98c9d58-3729-487c-8188-ab46d315ba8b"
            }
          ]
        },
        {
          "id": "b02db51e-8edb-468b-bdd7-91c20a2aade7",
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
              "id": "df3c85e5-3099-4646-baf0-ee27fb891c53"
            }
          ]
        }
      ]
    },
    {
      "name": "Incoming Phone Numbers",
      "item": [
        {
          "id": "95c33616-cf49-4128-a720-2bdc6b30a919",
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
              "id": "9a88535e-c86e-4230-a910-ac96445b0fb4"
            }
          ]
        },
        {
          "id": "efe35419-9dec-42d9-a804-ecd579d93103",
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
              "id": "74d5a497-449e-4709-89ec-ad7f5edc6aed"
            }
          ]
        },
        {
          "id": "8741223e-61ed-4133-bc6b-ecc0245bd617",
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
              "id": "43eb34ae-e4c0-4a1f-a65e-ac3b8f755529"
            }
          ]
        },
        {
          "id": "bb08f818-0acf-4ebc-aa84-0a2c58c2e7be",
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
              "id": "2d7fc2f0-1b25-4937-96f4-06bd9019abf8"
            }
          ]
        },
        {
          "id": "33229564-24a4-42ef-ad8d-d1a24e1d9ab6",
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
              "id": "b9aae2f9-3170-4803-a375-e19766ba5867"
            }
          ]
        },
        {
          "id": "8e054730-29ae-487f-8d70-6f27768a5924",
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
              "id": "dcfe357e-7bfc-4acd-9705-394c289a68d4"
            }
          ]
        },
        {
          "id": "4ac088b2-d3b0-4909-a990-2c7fe86021bd",
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
              "id": "2853ba8d-ccd0-42ff-8ec7-ea53bec6de5a"
            }
          ]
        }
      ]
    },
    {
      "name": "Messages",
      "item": [
        {
          "id": "cf9006bc-4804-473f-86c8-92bd5333a31c",
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
              "id": "07e3395a-cf08-4471-896c-19e9ba27a30e"
            }
          ]
        },
        {
          "id": "8d85c5d8-6b5e-481a-8d27-3b87d233b844",
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
              "id": "9e80c607-273e-4bda-a868-b66f707fb841"
            }
          ]
        },
        {
          "id": "3c6da430-ef7d-4578-8cbd-977b5d352bf8",
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
              "id": "33b09520-b8ba-43d9-8096-b093eb261051"
            }
          ]
        },
        {
          "id": "043c6826-25f8-4c10-9e31-edb4e6cfdc40",
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
              "id": "f825442f-22e6-4922-ad5c-832afa1c957e"
            }
          ]
        },
        {
          "id": "8fc20864-43d5-4ff1-8de4-402f05d020af",
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
              "id": "e731a069-d8dc-4724-9e8a-b1d8c3fa7557"
            }
          ]
        }
      ]
    },
    {
      "name": "Outgoing Caller IDs",
      "item": [
        {
          "id": "74158544-9b61-478f-b606-f61efcb5c4fd",
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
              "id": "e909940b-5f05-451d-8a72-458edc876122"
            }
          ]
        },
        {
          "id": "c0968dd0-427e-4487-912b-5c8249e80d03",
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
            "method": "PUT",
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
              "id": "577c551e-616c-4bf7-a77d-91a22c800dc3"
            }
          ]
        },
        {
          "id": "f45ff65c-9b2b-4013-87a8-13be08db97a1",
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
              "id": "b8a1b1ff-b359-402c-8056-58edab329f29"
            }
          ]
        }
      ]
    }
  ]
}