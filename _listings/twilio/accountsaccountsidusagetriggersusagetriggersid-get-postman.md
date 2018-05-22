{
  "info": {
    "name": "Twilio Get Account Usage Trigger",
    "_postman_id": "14a2ef4d-e952-41cc-8f64-bf6a7d0e24da",
    "description": "Returns a repesentation of the UsageTrigger.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "5a75329a-5d07-4d81-8b31-f0d3998fda4b",
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
              "id": "fe62b52b-09b2-4033-be19-4b6e4191ff63"
            }
          ]
        },
        {
          "id": "aeec82b0-01bb-4848-a245-8ce031e065c8",
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
              "id": "ba2f300b-b2c1-45a7-a16b-cdbf3e3ff0df"
            }
          ]
        },
        {
          "id": "87f7776c-56c8-43df-9377-f24006e67ac1",
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
              "id": "916adff9-613d-4b5d-837d-eb0b502ec93a"
            }
          ]
        },
        {
          "id": "4b93ce76-2c3c-4c27-819a-677d6cf72702",
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
              "id": "211f35bf-eadb-41bc-9178-80b2883372f9"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "2eb2dd08-6fd0-4133-a42d-b18e4decd28a",
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
              "id": "ebbe0aa3-cb30-4ac0-80d3-85d5c6f56e09"
            }
          ]
        },
        {
          "id": "5e37148a-f060-4055-9123-81948abc7eb0",
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
              "id": "00226b61-9db1-456e-a572-a268a9c1e7a6"
            }
          ]
        },
        {
          "id": "133d19ea-b3c9-4b2b-9f0c-1d908d95cdd7",
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
              "id": "d3055654-4f65-466f-ac6c-7f080447a285"
            }
          ]
        },
        {
          "id": "653dec44-cd65-49ac-96d2-b7a535057d09",
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
              "id": "f1cc10f9-ca4c-434b-9251-4636285db14b"
            }
          ]
        },
        {
          "id": "01f3fc91-5780-4c2b-9f1e-a33b9d950633",
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
              "id": "83ee3ceb-999f-4ed5-af81-4ef80a05f260"
            }
          ]
        },
        {
          "id": "467f411b-8937-4d63-a3f7-1d6c4d832f99",
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
              "id": "b8036357-e2c0-4769-920d-3c08c18dbae5"
            }
          ]
        },
        {
          "id": "46381120-6b06-4eb0-bf54-5ce6a48151f4",
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
              "id": "24586e25-e383-432a-a28b-62b36c5bb08a"
            }
          ]
        },
        {
          "id": "a7c6f576-3577-4497-b0c4-69388235241c",
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
              "id": "7cf027a5-92b9-426c-9dde-9cb01c503d22"
            }
          ]
        },
        {
          "id": "399f8629-a4a8-40a5-8b70-77e9d1a0d971",
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
              "id": "26fca174-b9f6-4768-a620-e5fb1eda9304"
            }
          ]
        },
        {
          "id": "139be81c-2660-4f83-b66b-cf5ab7541e18",
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
              "id": "daa31c52-75bc-4611-98ce-963c31c76924"
            }
          ]
        }
      ]
    },
    {
      "name": "Phone Numbers",
      "item": [
        {
          "id": "73b00a65-cc5c-46be-bc21-15eb47cd0a29",
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
              "id": "f8284a1d-0463-4140-9501-526d22caa028"
            }
          ]
        },
        {
          "id": "fccc1c70-b3d7-4eb0-ac5e-cda1b28cf635",
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
              "id": "97df5d2b-b4b3-4048-85ac-e1192d4b280b"
            }
          ]
        },
        {
          "id": "9138cd03-9d60-45ff-8b3f-2ba43b59a916",
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
              "id": "576c4d8b-f434-449f-bd57-24da4fa690ab"
            }
          ]
        }
      ]
    },
    {
      "name": "Recordings",
      "item": [
        {
          "id": "2491623f-a998-4f97-8a38-92a3b3353186",
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
              "id": "bd1a0282-dafc-468a-8365-6fc04b5ceafa"
            }
          ]
        },
        {
          "id": "083cbf65-f60e-4590-888f-4707efabbe63",
          "name": "returns-a-set-of-transcription-resource-representations-that-includes-paginginformation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Recordings/:RecordingSid/Transcriptions"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "RecordingSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a set of Transcription resource representations that includes pagingninformation.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a30335d-68f6-4a65-90ae-e71a0d6df9ab"
            }
          ]
        },
        {
          "id": "9e21a597-e0ce-40f0-896d-dc3efdb76aa1",
          "name": "returns-one-of-several-representationswithout-an-extension-or-with-a-wav-a-binary-wav-audio-file-is-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Recordings/:RecordingSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "RecordingSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns one of several representations:nWithout an extension, or with a .wav, a binary WAV audio file is returnednwith mime-type audio/x-wav.nAppending .mp3 to the URI returns a binary MP3 audio file with mime-typentype audio/mpeg.nAppending .xml to the URI returns a XML representation.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ed78d9ba-6853-4733-a4ad-44fba6686d20"
            }
          ]
        },
        {
          "id": "9e8cceb1-9780-456d-b066-6eab154b5849",
          "name": "deletes-a-recording--from-your-account",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Recordings/:RecordingSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "RecordingSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a recording  from your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eeda4711-9b60-4295-bd3c-fd287b12996f"
            }
          ]
        },
        {
          "id": "9c0c602f-9f02-4f33-a286-359abe90b424",
          "name": "returns-a-list-of-recording-resource-representations-each-representing-arecording-generated-during-t",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Recordings"
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
            "description": "Returns a list of Recording resource representations, each representing anrecording generated during the course of a phone call.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "913ae301-0427-4880-b885-74efce4c7c09"
            }
          ]
        }
      ]
    },
    {
      "name": "Calls",
      "item": [
        {
          "id": "021a73d7-6df0-458e-83a3-3bf9e3761d06",
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
              "id": "dc1db69d-6560-406a-b7d1-5a93e082c6d8"
            }
          ]
        },
        {
          "id": "182097d9-9f7f-4a5c-bc47-1ef0196320d4",
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
              "id": "b8675d1a-ce04-4a24-a4a6-f6d4d3327724"
            }
          ]
        },
        {
          "id": "9028361f-db4a-4e02-87b5-6401db366ac6",
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
              "id": "5760ce66-430f-4798-af9c-861b5e215b78"
            }
          ]
        }
      ]
    },
    {
      "name": "Conferences",
      "item": [
        {
          "id": "daa922ec-83a6-4782-ada3-0a05d5608da2",
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
              "id": "319a78ab-8a8c-4636-9449-9e5a07eeee44"
            }
          ]
        },
        {
          "id": "6f0f3da4-a3ed-4f68-a348-4dd34cdf9983",
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
              "id": "5c8326aa-89f0-4f32-ae43-35206a87f7cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Conference Calls",
      "item": [
        {
          "id": "d9e11e80-7334-4e12-8949-a65a9ba00cab",
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
              "id": "23653c8b-9590-487a-836b-50545a4ab579"
            }
          ]
        },
        {
          "id": "6ff28f3a-645a-4597-8f65-9ca75fadd891",
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
              "id": "1e1409b2-b675-4e72-9cf5-0903a0353f6c"
            }
          ]
        },
        {
          "id": "36484889-f766-4a86-8a54-ab8e8cbcfe87",
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
              "id": "df060e34-856d-4b14-9390-49d188f66d2f"
            }
          ]
        },
        {
          "id": "38c49365-f449-41e4-8382-b1740ec6cb79",
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
              "id": "ad96f48c-5347-4668-b43f-d3b7918f2554"
            }
          ]
        }
      ]
    },
    {
      "name": "Incoming Phone Numbers",
      "item": [
        {
          "id": "ea464810-b4e0-4959-afd0-30f72ede64af",
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
              "id": "159203e1-4555-43db-98f7-5e57e116dae0"
            }
          ]
        },
        {
          "id": "64a4a43f-28c8-424c-854a-19ac461b6bee",
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
              "id": "a04d20e2-2128-41b1-86ce-5080c47675c3"
            }
          ]
        },
        {
          "id": "db7c109a-bd4c-4f81-b193-3824433f7561",
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
              "id": "083c17fd-9f1a-4dbe-aea8-f0803757d356"
            }
          ]
        },
        {
          "id": "bec2e10f-12a8-4c74-b940-fcf73b50797d",
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
              "id": "7acb5d66-fcce-4280-a21c-ea5eacc5a363"
            }
          ]
        },
        {
          "id": "2a50e2ea-1788-4194-96ab-6ddc0e0ac0cf",
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
              "id": "da5a25ce-7d11-4aae-a180-4ebd9259417d"
            }
          ]
        },
        {
          "id": "e5ad2363-adf8-4ec0-b824-00085652dc10",
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
              "id": "8964b5cf-d9a3-4ffa-b945-95292f9078ac"
            }
          ]
        },
        {
          "id": "26f3421b-300b-441a-b790-a98baa696871",
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
              "id": "88a1e1a2-98d7-4a1d-8290-30573a9fc53f"
            }
          ]
        }
      ]
    },
    {
      "name": "Messages",
      "item": [
        {
          "id": "716aa3b7-e457-49d2-9387-44d7e4b13d23",
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
              "id": "d413a4be-6d1a-4bc5-b60a-a7264d51bba8"
            }
          ]
        },
        {
          "id": "423adad4-d494-411b-8f49-f859f77f16d4",
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
              "id": "d0a7c5ce-e266-4b74-a648-69c013647f71"
            }
          ]
        },
        {
          "id": "04052126-85b7-4f67-8d59-ca838a26156f",
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
              "id": "e1e7b310-ec41-4bfd-859a-bd5926d7a2ec"
            }
          ]
        },
        {
          "id": "a9ba01f7-c12b-4263-9768-b792e88e22fe",
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
              "id": "fd3e6896-8f33-4e8b-9fc6-175b2824abfb"
            }
          ]
        },
        {
          "id": "8b479ee1-5898-4c1c-a95e-a11399317caf",
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
              "id": "64f30524-c67b-43e9-9672-b5b1b1d2bedb"
            }
          ]
        }
      ]
    },
    {
      "name": "Outgoing Caller IDs",
      "item": [
        {
          "id": "63c29670-8e60-4da4-89fc-2d6585f1f587",
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
              "id": "a500e5ef-f1e2-4a9f-9a2c-1a82a3bbb957"
            }
          ]
        },
        {
          "id": "6300694a-11cf-4369-900f-e040377b7b1d",
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
              "id": "f3e58fc8-e515-438c-8f37-189c861fbba3"
            }
          ]
        },
        {
          "id": "c71c7b8c-43b9-4b16-a1d5-f4af8aa6b97d",
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
              "id": "16ba5f61-7bfd-4f8d-b4b5-ff00c0203a26"
            }
          ]
        },
        {
          "id": "69d13b66-2d49-44c9-8f03-b2baa9f54aaf",
          "name": "deleteoutgoingcallerid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/OutgoingCallerIds/:OutgoingCallerIdSid"
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
                  "id": "OutgoingCallerIdSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "DeleteOutgoingCallerId"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae8c9fe1-8bc3-42a0-8b0e-2797cadf389a"
            }
          ]
        },
        {
          "id": "ea8c9fae-d048-4261-8338-7baeedbd524d",
          "name": "returns-a-list-of-outgoingcallerid-resource-representations-each-representinga-caller-id-number-vali",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/OutgoingCallerIds"
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
            "description": "Returns a list of OutgoingCallerId resource representations, each representingna Caller ID number valid for an account. The list includes paging information.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3c5668f5-44e9-4d71-9ddc-19d1310545cd"
            }
          ]
        },
        {
          "id": "a089c932-065c-484b-b85e-6c7278e05dd2",
          "name": "adds-a-new-callerid-to-your-account",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/OutgoingCallerIds"
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
            "description": "Adds a new CallerID to your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de777b79-f5e7-4947-8524-5fc732921d2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Queues",
      "item": [
        {
          "id": "b7e43b56-d26c-40c5-bf46-e3e0ddd27f13",
          "name": "get-a-front-member",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues/:QueueSid/Members/Front"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "QueueSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a front member."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f03040e4-5d9a-41e6-bd0d-816a0117bc61"
            }
          ]
        },
        {
          "id": "af7a7de2-d162-497f-b933-002af48004b2",
          "name": "posting-a-url-and-method-to-a-queue-instance-will-dequeue-a-member-from-aqueue-and-have-the-members-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues/:QueueSid/Members/Front"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "QueueSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Posting a URL and Method to a Queue instance will dequeue a member from anqueue and have the members call begin executing the TwiML document at that URLnWhen dequeuing the Front of the queue, the next call in the queue will be redirected.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3e254a0-a412-4679-a52a-2d5039b65506"
            }
          ]
        },
        {
          "id": "254a91d8-0c1a-4e13-9179-175a6ce3271d",
          "name": "get-a-specific-member",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues/:QueueSid/Members/:CallSid"
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
                  "id": "QueueSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a specific member."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d8ece31-509c-4733-a377-9a94818d3ef7"
            }
          ]
        },
        {
          "id": "902a4174-b340-4dd0-8b34-042b7bc523cd",
          "name": "posting-a-url-and-method-to-a-queue-instance-will-dequeue-a-member-from-aqueue-and-have-the-members-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues/:QueueSid/Members/:CallSid"
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
                  "id": "QueueSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Posting a URL and Method to a Queue instance will dequeue a member from anqueue and have the members call begin executing the TwiML document at that URLnWhen redirecting a member of a queue addressed by CallSid, only the first requestnwill succeed and return a 200 response code. A second request will fail andnreturn an appropriate 400 response code.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9706b71f-b4c5-401b-8c34-c72a03c9c0b4"
            }
          ]
        },
        {
          "id": "d772f1e7-e7fd-4c37-8fad-9e7c21591f8b",
          "name": "returns-the-list-of-members-in-the-queue-identified-by-queuesid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues/:QueueSid/Members"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "QueueSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the list of members in the queue identified by {QueueSid}."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1c86d09-c899-4134-94dc-3ce6ebde428b"
            }
          ]
        },
        {
          "id": "8c6968b1-7389-4596-8e79-8bc533ef6a65",
          "name": "get-resources-individual-queue-instance",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues/:QueueSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "QueueSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get resources individual Queue instance.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f460b464-f6f1-4550-b5a3-529b2d8c782c"
            }
          ]
        },
        {
          "id": "a4d1ec22-4b9c-4531-8e32-cb6af26333e5",
          "name": "this-post-request-allows-you-to-change-the-friendlyname-or-maxsize",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues/:QueueSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "QueueSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "This POST request allows you to change the FriendlyName or MaxSize.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "453ca57d-4042-42fc-b576-bcc22123c1db"
            }
          ]
        },
        {
          "id": "8a52c107-f5e2-4499-be0a-0623118dca93",
          "name": "the-delete-method-allows-you-to-remove-a-queue-only-empty-queues-aredeletable",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues/:QueueSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "QueueSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "The DELETE method allows you to remove a Queue. Only empty queues arendeletable.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1401b017-2265-479c-9a35-1affb3dcdd39"
            }
          ]
        },
        {
          "id": "ba220c2e-b35d-42af-aab9-4a1294c21735",
          "name": "returns-a-list-of-queues-within-an-account-the-list-includes-paginginformation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues"
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
            "description": "Returns a list of queues within an account. The list includes pagingninformation.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e243b2e6-673b-44b8-93e4-4565e635f112"
            }
          ]
        },
        {
          "id": "7d2540b4-d4b9-4902-b5f6-5febdddff489",
          "name": "create-a-new-queue-resource",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Queues"
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
            "description": "Create a new Queue resource.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bbec15f4-8f8c-45b7-9827-e15572c40ae2"
            }
          ]
        }
      ]
    },
    {
      "name": "SIP Credential Lists",
      "item": [
        {
          "id": "a2027153-6c28-4d03-a8e2-a2168858ddda",
          "name": "get-a-specific-credential-in-a-list-though-a-password-is-stored-for-each-username-in-your-list-the-p",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists/:CLSid/Credentials/:CredentialSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CredentialSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a specific Credential in a list. Though a password is stored for each username in your list, the password is not returned to protect your password. If you cannot remember your password, you will need to POST to this resource to update it."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7a341cf-3728-4af2-b49f-ac9356256956"
            }
          ]
        },
        {
          "id": "523aa1b3-3dd4-44f6-be0a-1553feff6f76",
          "name": "change-the-password-of-a-credential-recordif-the-change-is-successful-twilio-will-respond-with-the-c",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists/:CLSid/Credentials/:CredentialSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CredentialSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Change the password of a Credential record.nnIf the change is successful, Twilio will respond with the Credential record but will not include the password in the response.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c351bf1-b5a6-4eb4-9bf3-7f4730f93229"
            }
          ]
        },
        {
          "id": "a258b51d-dfc3-43ed-8488-ffd45180720a",
          "name": "remove-a-credential-from-a-credentiallist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists/:CLSid/Credentials/:CredentialSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CredentialSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Credential from a CredentialList."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc928d44-8521-44b2-86b1-61adae9fbd70"
            }
          ]
        },
        {
          "id": "1114a6f8-3aae-46d5-a26b-6be75540bce1",
          "name": "get-the-list-of-credentials-in-a-credentiallist-the-passwords-for-the-credentials-are-intentionally-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists/:CLSid/Credentials"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the list of Credentials in a CredentialList. The passwords for the Credentials are intentionally not returned so as to protect them."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "465bda66-6f08-4033-a553-4149fadbbe4f"
            }
          ]
        },
        {
          "id": "531ce3c8-da05-48da-af31-05d559ccbca3",
          "name": "add-a-credential-to-the-credentiallistwhen-creating-a-credential-you-will-post-both-a-username-and-p",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists/:CLSid/Credentials"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Credential to the CredentialList.nnWhen creating a Credential, you will POST both a username and password, but only receive the username back in the response. The password is intentionally not returned so as to protect it.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f579b203-d75c-41f4-a07b-2f1529ea0f9e"
            }
          ]
        },
        {
          "id": "7f07c709-4ac7-41b5-aa66-80b02ce37e44",
          "name": "get-a-credential-list-instance-resource",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists/:CLSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a credential list instance resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f481829-69e0-4f97-9ed1-ceccc8fad758"
            }
          ]
        },
        {
          "id": "1238a78e-97e5-4fa8-a97b-5d82b92db4f6",
          "name": "change-the-friendlyname-of-the-list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists/:CLSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Change the FriendlyName of the list"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27202d3a-3992-4446-a1be-b740d8002b78"
            }
          ]
        },
        {
          "id": "ad6d4264-4c79-4d7e-befc-62af3c24d733",
          "name": "delete-a-credentiallist-from-your-account-it-can-only-be-deleted-if-no-domains-are-mapped-to-it-if-y",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists/:CLSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a CredentialList from your account. It can only be deleted if no domains are mapped to it. If you attempt to delete one that is mapped to a domain, you will receive an error."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8e756e7-37dc-42ac-969d-683f6ae5d02d"
            }
          ]
        },
        {
          "id": "f599b8d3-38e6-4da3-a9bb-70d8eca628fc",
          "name": "gets-a-list-of-credential-lists-for-an-account",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists"
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
            "description": "Gets a list of Credential Lists for an account"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb0bace5-3dcf-45a4-8549-dcef45a955a3"
            }
          ]
        },
        {
          "id": "b183f426-9b23-47d1-b101-b9053aadb8b0",
          "name": "create-a-new-credential-list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/CredentialLists"
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
            "description": "Create a new Credential List."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33a245f1-bccf-4a14-9f6b-90ec74f1a9f0"
            }
          ]
        }
      ]
    },
    {
      "name": "SIP Domains",
      "item": [
        {
          "id": "c4136063-8154-4c6b-a444-d7cbe48e0f12",
          "name": "remove-a-credentiallistmapping-from-a-domain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid/CredentialListMappings/:CLSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CLSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a CredentialListMapping from a domain"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b80b0639-ce0d-4116-80ff-e07d97c2e612"
            }
          ]
        },
        {
          "id": "d79f2bf7-ed77-47d7-8fe8-7be7a903ede2",
          "name": "get-the-user-lists-mapped-to-this-domain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid/CredentialListMappings"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the user lists mapped to this domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b5f0bc92-cde9-4577-be1c-98e3360b5275"
            }
          ]
        },
        {
          "id": "e16b80e1-7d4b-4df0-9373-d8392f6fafab",
          "name": "map-a-credentiallist-to-the-domain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid/CredentialListMappings"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Map a CredentialList to the domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d5b30f0-f65f-4704-99a6-d2e7d8f991af"
            }
          ]
        },
        {
          "id": "cef6639a-fad7-48d1-b6a4-33cc7ffa6fe6",
          "name": "return-a-specific-ipaccesscontrollistmapping-instance-by-sid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid/IpAccessControlListMappings/:ALSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ALSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return a specific IpAccessControlListMapping instance by Sid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7271cd1-b810-4513-bdf3-bb045aaad111"
            }
          ]
        },
        {
          "id": "93335643-2753-49bb-a78f-f3a69a5a34c4",
          "name": "remove-a-mapping-from-this-domain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid/IpAccessControlListMappings/:ALSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ALSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a mapping from this domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76d91bfc-cb22-4834-85e1-76a72283340f"
            }
          ]
        },
        {
          "id": "3a3f077a-3ac7-4d73-b9d1-a332e1107c08",
          "name": "return-the-ipaccesscontrollistmappings-that-are-associated-to-this-domain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid/IpAccessControlListMappings"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return the IpAccessControlListMappings that are associated to this domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc014b82-662f-4cfb-b2e7-c61db4f83174"
            }
          ]
        },
        {
          "id": "46be7f40-1da9-4a0f-b196-15cb9187efc1",
          "name": "map-an-ipaccesscontrollist-to-this-domain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid/IpAccessControlListMappings"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Map an IpAccessControlList to this domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bad7a278-42e6-42b2-bd59-24f66d9610a6"
            }
          ]
        },
        {
          "id": "83ba11b2-a680-4f7d-97ee-eaf3168e1e66",
          "name": "return-a-specific-instance-by-sid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return a specific instance by Sid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a710e58-777a-4c57-ad19-d63650382fe9"
            }
          ]
        },
        {
          "id": "b194d3e5-76bd-4354-863b-6b31f2e10a42",
          "name": "update-the-attributes-of-a-domain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Update the attributes of a domain."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "680d086c-10c2-4d1d-b1d4-7bb7d4ad38cc"
            }
          ]
        },
        {
          "id": "01040f62-dcd3-429f-a007-fbadb94d59ae",
          "name": "delete-a-domain-if-you-have-created-subdomains-of-a-domain-you-will-not-be-able-to-delete-the-domain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains/:SipDomainSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SipDomainSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a domain. If you have created subdomains of a domain, you will not be able to delete the domain until you first delete all subdomains of it."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "292e3a34-5f14-463d-80a0-26a872077992"
            }
          ]
        },
        {
          "id": "a27f3933-4025-46b5-b624-5eddc4719533",
          "name": "returns-a-paged-list-of-the-domains-for-an-account",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains"
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
            "description": "Returns a paged list of the domains for an account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18133d0c-9276-4c50-bace-1c078deccb6c"
            }
          ]
        },
        {
          "id": "a56e590d-1411-4119-95d5-7f2746991ac9",
          "name": "creates-a-new-domain-and-returns-its-instance-resource-you-must-pick-a-unique-domain-name-that-ends-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/Domains"
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
            "description": "Creates a new Domain and returns its instance resource. You must pick a unique domain name that ends in .sip.twilio.com.nAfter creating a Domain, you must map it to an authentication method before the domain is ready to receive traffic.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd2df928-8f2d-4795-b3f0-ab11e14d788f"
            }
          ]
        }
      ]
    },
    {
      "name": "SIP IP Access Control Lists",
      "item": [
        {
          "id": "a29781ac-5569-4047-b05b-eda4eab45d3b",
          "name": "return-a-single-ip-address-resource",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid/IpAddresses/:IpAddressSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAddressSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return a single IP Address resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1166260e-de37-4687-9ae5-e88df11083bd"
            }
          ]
        },
        {
          "id": "3b021cb5-2af3-475c-b262-33eb7b196ccb",
          "name": "change-the-description-or-ip-address-of-a-given-ipaddress-instance-resource",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid/IpAddresses/:IpAddressSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAddressSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Change the description or IP address of a given IpAddress instance resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40ee121d-2f8a-4cec-803d-ccaf7844600d"
            }
          ]
        },
        {
          "id": "08bdd23f-2458-4738-83e0-1a236f31fd74",
          "name": "deletes-an-ip-address-entry-from-the-list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid/IpAddresses/:IpAddressSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAddressSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes an IP address entry from the list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a9fa4c7-5012-4e6c-b2b9-256dc72fac91"
            }
          ]
        },
        {
          "id": "f777fce9-8611-4585-8b1e-2a06296f4cb3",
          "name": "list-the-ip-addresses-contained-in-this-list",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid/IpAddresses"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the IP Addresses contained in this list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd44f2d2-1a66-4235-b116-e1783734bc88"
            }
          ]
        },
        {
          "id": "31975e8b-391f-485b-9604-7d47af1308bb",
          "name": "add-an-ip-address-to-the-list-with-a-description",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid/IpAddresses"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add an IP Address to the list with a description."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b5da40a-6cb9-4eee-b2c3-f2977f6bc8b3"
            }
          ]
        },
        {
          "id": "f14dd54b-96cc-488a-b72f-3cabaa427c5f",
          "name": "return-a-specific-ipaccesscontrollist-resource",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Return a specific IpAccessControlList resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e88ab696-0748-4b20-94df-58864de239d8"
            }
          ]
        },
        {
          "id": "84756506-0073-41c0-8592-fd365595aff9",
          "name": "rename-an-ipaccesscontrollist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Rename an IpAccessControlList."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09e9dac4-8842-485f-befb-f44e5a4e9270"
            }
          ]
        },
        {
          "id": "dafce7be-3cfe-40da-9c77-1c2c22762c99",
          "name": "delete-an-ipaccesscontrollist-from-your-account-it-can-only-be-deleted-if-no-domains-are-mapped-to-i",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists/:IpAccessControlListSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "IpAccessControlListSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete an IpAccessControlList from your account. It can only be deleted if no domains are mapped to it. If you attempt to delete one that is mapped to a domain, you will receive an error."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fc558b9-8344-4341-bf2d-84e9201cc61b"
            }
          ]
        },
        {
          "id": "1ec35841-d940-40b8-b42d-909cba0062b2",
          "name": "return-a-paged-list-of-all-ipaccesscontrollists-under-this-account",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists"
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
            "description": "Return a paged list of all IpAccessControlLists under this account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aeeedc76-1f54-4901-8d4f-a830e81429bd"
            }
          ]
        },
        {
          "id": "f5ba26cb-5758-45ef-8acb-efdb0a395354",
          "name": "create-a-new-ipaccesscontrollist-resourcewhen-created-the-list-will-contain-no-ip-addresses-you-will",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SIP/IpAccessControlLists"
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
            "description": "Create a new IpAccessControlList resource.nnWhen created, the list will contain no IP addresses. You will need to add IP addresses to the list for it to be active. To add IP addresses, you will need to POST to the IpAddresses List subresource.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8aecbbb-2fd0-46e6-9ba9-e098ee7a8f95"
            }
          ]
        }
      ]
    },
    {
      "name": "Short Codes",
      "item": [
        {
          "id": "b59c31a9-bbc4-433f-9885-8b61b8580aa3",
          "name": "get-a-single-message",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SMS/ShortCodes/:ShortCodeSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ShortCodeSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a single message."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c2bb309-faab-4bfc-8f68-a17c58c600b7"
            }
          ]
        },
        {
          "id": "4deb5707-a07e-44d7-a0f7-3024734fadd1",
          "name": "tries-to-update-the-shortcodes-properties-and-returns-the-updatedresource-representation-if-successf",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SMS/ShortCodes/:ShortCodeSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "ShortCodeSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Tries to update the shortcodes properties, and returns the updatednresource representation if successful.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b124c145-912c-46aa-a4a3-19f05763b306"
            }
          ]
        },
        {
          "id": "004f3cc4-7515-498f-9a51-66c5adbd22e0",
          "name": "returns-a-list-of-shortcode-resource-representations-each-representing-ashort-code-within-your-accou",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SMS/ShortCodes"
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
            "description": "Returns a list of ShortCode resource representations, each representing anshort code within your account. The list includes paging information.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6391a02-dea4-4b7d-93df-09e732c66bb6"
            }
          ]
        }
      ]
    },
    {
      "name": "SMS Messages",
      "item": [
        {
          "id": "01c6dbd0-1c1b-46f3-8add-908e8614f2c0",
          "name": "getsmslist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SMS/Messages.json"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "GetSMSList"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd9ecdd4-fa55-4b1e-8534-9d828d5694b7"
            }
          ]
        },
        {
          "id": "bd065814-3ec0-4355-a49b-53fc51d548a7",
          "name": "sendsms",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SMS/Messages.json"
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
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "SendSMS"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acbd65e7-4b63-46a3-a623-8fdb07ed176e"
            }
          ]
        },
        {
          "id": "e62878e4-d85f-4c5c-9052-b17d0166d2a9",
          "name": "getsms",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/SMS/Messages/:SMSMessageSid.json"
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
                  "id": "SMSMessageSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "GetSMS"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a7924e6-ca1d-4f60-86e8-58a128f69ed4"
            }
          ]
        }
      ]
    },
    {
      "name": "Transcriptions",
      "item": [
        {
          "id": "97f03c4c-578e-4b66-9162-2fad555a2bb8",
          "name": "returns-a-single-transcription-resource-representation-identified-by-thegiven-transcriptionsid-by-de",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Transcriptions/:TranscriptionSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "TranscriptionSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a single Transcription resource representation identified by thengiven {TranscriptionSid}. By default Twilio will respond with the XML metadata for the Transcription. If you append .txt to the end of the Transcription resources URI Twilio will just return you the transcription tex.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9093e49a-c412-4be4-a128-3cf4b588d3ac"
            }
          ]
        },
        {
          "id": "6c0658ed-2512-4c94-82a9-68510421e22f",
          "name": "deletes-a-transcription-from-your-account",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Transcriptions/:TranscriptionSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "TranscriptionSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a transcription from your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32cdc636-c89b-4f21-b170-6a1286518806"
            }
          ]
        },
        {
          "id": "0bd8d341-3d1e-4db3-9882-9667ce82bfb2",
          "name": "returns-a-set-of-transcription-resource-representations-that-includes-paginginformation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Transcriptions"
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
            "description": "Returns a set of Transcription resource representations that includes pagingninformation.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "397c357d-1f60-41f0-a70d-9803d407f70b"
            }
          ]
        },
        {
          "id": "a94314bd-a97c-40e6-87ae-d7f0a5792a1f",
          "name": "gettranscriptionlist",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Transcriptions.json"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "GetTranscriptionList"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5f28125-adbc-409a-ba42-8e74f66ffd47"
            }
          ]
        },
        {
          "id": "34c016d8-2358-41fc-8f4e-2da69aea3417",
          "name": "gettranscription",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Transcriptions/:TranscriptionSid.json"
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
                  "id": "TranscriptionSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "GetTranscription"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea26f62d-587d-434a-888f-507b320a50a9"
            }
          ]
        }
      ]
    },
    {
      "name": "Usage Records",
      "item": [
        {
          "id": "cb8bbb0f-d1f4-4350-bcbf-e5aec84020e3",
          "name": "returns-usagerecords-for-all-usage-categories-for-a-specified-period",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Usage/Records/:Subresource"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "Subresource",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns UsageRecords for all usage categories for a specified period.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab1fed56-3479-4f3b-9a14-79d1d83a010e"
            }
          ]
        },
        {
          "id": "bc02e62e-eed1-46b1-a9bb-42c158d07d77",
          "name": "returns-usagerecords-for-all-usage-categories-the-list-includes-paginginformationby-default-the-usag",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Usage/Records"
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
            "description": "Returns UsageRecords for all usage categories. The list includes pagingninformation.nBy default, the UsageRecords resource will return one UsageRecord forneach Category, representing all usage accrued all-time for the account.nYou can filter the usage Category or change the date-range over which usagenis counted using optional GET query parameters.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2efbd96-2dc5-47f2-8b4c-33e691ba9601"
            }
          ]
        }
      ]
    },
    {
      "name": "Usage Triggers",
      "item": [
        {
          "id": "1ab8133f-b061-4dce-ab6e-be649ebab88b",
          "name": "returns-a-repesentation-of-the-usagetrigger",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Usage/Triggers/:UsageTriggerSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "UsageTriggerSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a repesentation of the UsageTrigger."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3838577-20d7-473a-b054-7737151052ef"
            }
          ]
        },
        {
          "id": "adb5f719-3050-42bd-bad4-c7ab04c0decf",
          "name": "delete-this-usagetrigger",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.twilio.com",
              "path": [
                "2010-04-01",
                "Accounts/:AccountSid/Usage/Triggers/:UsageTriggerSid"
              ],
              "variable": [
                {
                  "id": "AccountSid",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "UsageTriggerSid",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete this UsageTrigger."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69ebb7f6-044b-4b5a-b35c-f9eea88c9a4c"
            }
          ]
        }
      ]
    }
  ]
}