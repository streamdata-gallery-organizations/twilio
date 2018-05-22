{
  "info": {
    "name": "Twilio Add Account Usage Trigger",
    "_postman_id": "a88922c7-0c81-4b0e-b4c6-dab5a6789b29",
    "description": "Tries to update the UsageTriggers properties, and returns the updatednresource representation if successful.n",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "3003e288-fcd5-4d16-b649-6807d718ea18",
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
              "id": "24b616dc-0dda-4149-bef4-4edcac042563"
            }
          ]
        },
        {
          "id": "3f4586e8-3661-4933-8052-3cfc92a26ab9",
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
              "id": "65718ff1-7c83-413c-9043-23bb5c7c9141"
            }
          ]
        },
        {
          "id": "ce1f9352-c82b-49ec-b1c1-34c55dedaac6",
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
              "id": "484c9746-65a9-4e76-84e4-22442805199a"
            }
          ]
        },
        {
          "id": "b4ed2d54-4946-4426-8e40-880b90cbc9ed",
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
              "id": "e579bdec-4e68-4981-a665-be42a827fbbe"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "4461f087-d9bd-4abf-9827-523884db644e",
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
              "id": "fa27d53b-2f3b-4b9e-8b8e-addb5193ac0f"
            }
          ]
        },
        {
          "id": "85f13e65-e0cb-4867-a262-cf9cb41366e7",
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
              "id": "1c2980ca-03f5-49f7-bbca-0694007d2d18"
            }
          ]
        },
        {
          "id": "ce928f2f-3ed1-45b3-99d3-7c504cefedf8",
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
              "id": "31f9290c-be20-4f32-8388-938cabd61bf7"
            }
          ]
        },
        {
          "id": "be4c15f3-6a4b-490c-a8a2-fd1668391b3e",
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
              "id": "baecb8d3-c1a5-419a-8ef9-0312c49d9497"
            }
          ]
        },
        {
          "id": "d58c7989-185d-4ee5-b08f-ca3f5cdd2baf",
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
              "id": "5c5f2ad6-b61b-49e5-86ba-1a5ce432e900"
            }
          ]
        },
        {
          "id": "73c3c504-5d11-4733-846c-ee1e6ed0bce4",
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
              "id": "59c5b0d1-3e23-48ea-a975-05311078be8d"
            }
          ]
        },
        {
          "id": "7b1b41ad-03d4-46c5-ae85-aae4646e930a",
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
              "id": "8849c5be-945d-40d4-91f9-b3277e439668"
            }
          ]
        },
        {
          "id": "3b124f73-c8ad-4db5-b0b7-655aab97bdb3",
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
              "id": "dded4668-7032-4b1d-bb1c-50692ccfeeb4"
            }
          ]
        },
        {
          "id": "a5633168-2f55-4587-8dc8-70198f86ce0c",
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
              "id": "f02d6cdc-ff9e-47f5-872f-f51a5e23de21"
            }
          ]
        },
        {
          "id": "824f866d-20b6-4402-8968-8837c4502c18",
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
              "id": "85d30d67-f6df-447b-92ff-8e5f7f8224f2"
            }
          ]
        }
      ]
    },
    {
      "name": "Phone Numbers",
      "item": [
        {
          "id": "dd82c8cf-f425-4e32-b666-ec284c3ae136",
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
              "id": "acd66b61-ca34-4750-b9eb-13cbd4cfc92b"
            }
          ]
        },
        {
          "id": "6aac5656-26be-461c-9cff-e01c8943a80f",
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
              "id": "0c87f597-189d-42e6-aa04-996043512734"
            }
          ]
        },
        {
          "id": "6750e9af-a7f7-4aec-821e-23432bfc40d5",
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
              "id": "608849a6-dbed-4b9f-b9f2-18e41a94eb72"
            }
          ]
        }
      ]
    },
    {
      "name": "Recordings",
      "item": [
        {
          "id": "266a7381-508b-42c4-b918-424eca54787e",
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
              "id": "6f2a2c33-d187-4c7c-870f-d378632d5157"
            }
          ]
        },
        {
          "id": "3c7d83d6-4ec4-4348-a08d-91968c07cda5",
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
              "id": "d545f5d6-3660-4ff9-b682-4934bba653f0"
            }
          ]
        },
        {
          "id": "8d151c8c-db69-4dec-994b-d9e4dc99e1b0",
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
              "id": "deb338d7-317f-40d3-a080-8952e2e2fc25"
            }
          ]
        },
        {
          "id": "f4f157c9-6b4c-4c51-93fc-c3abee2a7933",
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
              "id": "1fa6edf2-edca-4647-82d6-a3680151149d"
            }
          ]
        },
        {
          "id": "1c7b2b12-e0e0-4d03-893f-7c790718fae9",
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
              "id": "3058ece7-9596-4de4-882b-755243dd20a7"
            }
          ]
        }
      ]
    },
    {
      "name": "Calls",
      "item": [
        {
          "id": "ea6f4a39-c929-4082-9f5f-7913df17f706",
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
              "id": "25ea72bc-4e5e-40f6-81ff-76fb8281a0da"
            }
          ]
        },
        {
          "id": "76ef9ca0-ca43-4240-b48d-8d363db11199",
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
              "id": "619e9d5f-77d8-40dd-8026-5ba356320c10"
            }
          ]
        },
        {
          "id": "c1f60337-4d5e-47bb-aa3b-d2d819ac3788",
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
              "id": "e94919f7-90e4-41d5-a43e-4e15cda9522a"
            }
          ]
        }
      ]
    },
    {
      "name": "Conferences",
      "item": [
        {
          "id": "6e03afb6-82a9-499b-9ce4-416b56cf0591",
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
              "id": "66fbc049-6425-4096-9bad-1856903acf53"
            }
          ]
        },
        {
          "id": "1daaca0e-8f0c-449c-9c52-8f074af2ca3b",
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
              "id": "c2121580-ec03-4756-8c79-a49b101199a9"
            }
          ]
        }
      ]
    },
    {
      "name": "Conference Calls",
      "item": [
        {
          "id": "6619899f-a425-46f9-9243-fcf73fef2e3f",
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
              "id": "9f4a1c64-dfe4-4e47-8c21-25f055b3f4a4"
            }
          ]
        },
        {
          "id": "8bbcbe28-6184-43c9-9cab-85026484a546",
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
              "id": "a1083acc-c4f3-45dd-9ca7-8c6d2b75989e"
            }
          ]
        },
        {
          "id": "4867493b-15ef-45d0-b670-3315bfd2ee03",
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
              "id": "59b671e7-945c-4918-a460-07db703138a8"
            }
          ]
        },
        {
          "id": "b9d62108-a502-47e2-8e41-4c2dd8171805",
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
              "id": "c94172c2-136a-4067-8d8e-82c379268e53"
            }
          ]
        }
      ]
    },
    {
      "name": "Incoming Phone Numbers",
      "item": [
        {
          "id": "5f8e4219-8606-4656-88cf-7de1da5358f7",
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
              "id": "33235218-3185-4781-a1ec-b39a4240202a"
            }
          ]
        },
        {
          "id": "34845f50-0933-4507-8659-32b0064bc5e3",
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
              "id": "b3afa96d-daf4-44ef-9564-5181ae3abb3d"
            }
          ]
        },
        {
          "id": "7af1a8a6-32dd-471c-b6a8-7bcf7706a5a2",
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
              "id": "f51c7076-ecb5-439c-a2d3-6a210983c7d0"
            }
          ]
        },
        {
          "id": "caca2296-4357-42ac-ba11-df5ecbabd077",
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
              "id": "4df7fc67-7338-4e8a-83a9-98132f5b96fa"
            }
          ]
        },
        {
          "id": "0f3608d8-300e-4390-93dc-d6b9d6014806",
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
              "id": "e1399391-2826-49d4-9560-e2327e972eae"
            }
          ]
        },
        {
          "id": "eeff1657-0c5b-4993-aa6b-32f936adb371",
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
              "id": "9e2f4223-9a1f-4022-8b00-5043007435f6"
            }
          ]
        },
        {
          "id": "ffb0799a-0149-4445-8d11-6178cd12d6de",
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
              "id": "c2def244-7c1b-4aa1-b199-f87ca35f6317"
            }
          ]
        }
      ]
    },
    {
      "name": "Messages",
      "item": [
        {
          "id": "2b86e8f9-b3b4-49f9-be8b-de59cb628d4d",
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
              "id": "b46791b5-a549-4db5-9c74-24741f630dac"
            }
          ]
        },
        {
          "id": "49643b24-d869-4236-80b7-d8dbafd19a32",
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
              "id": "f2957452-b798-4afa-b48e-51d0025d90a9"
            }
          ]
        },
        {
          "id": "613c0c5d-f2f8-49a0-9709-5d6b5e5a428b",
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
              "id": "921c13df-d305-479b-88ab-264f709d0184"
            }
          ]
        },
        {
          "id": "496d5e66-ca4f-49dd-a416-8e6fb51f7ef2",
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
              "id": "52d2cf66-cfb3-4e4e-a3b0-7a4a3ad041c0"
            }
          ]
        },
        {
          "id": "bf80ee5e-3ceb-4550-b017-0e2cbbd70b09",
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
              "id": "f5218d47-2bf9-495e-8d2f-744eb31e2ee7"
            }
          ]
        }
      ]
    },
    {
      "name": "Outgoing Caller IDs",
      "item": [
        {
          "id": "64c20a5e-c74f-42a8-8f37-d67a1c348116",
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
              "id": "c67023d6-62ad-4c84-b681-83638f0fa9db"
            }
          ]
        },
        {
          "id": "af970751-9186-47e5-afc0-73f3347b4b28",
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
              "id": "52cc91be-7ad5-4e10-8e1e-9d6fd1367da9"
            }
          ]
        },
        {
          "id": "06bd5232-17fe-4cd1-bdfa-ef4ea27b5301",
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
              "id": "dd34766e-bab8-4d01-bf25-664ee81c219b"
            }
          ]
        },
        {
          "id": "e3ad47de-3527-4b56-82f5-e750447b3f91",
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
              "id": "02106057-cbcd-430b-9a4b-9c23a9ab178c"
            }
          ]
        },
        {
          "id": "e26f1cad-cf7e-43a3-912d-ea30b9dc1f31",
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
              "id": "1f74b8e6-3785-441b-9f46-81b10f53dba3"
            }
          ]
        },
        {
          "id": "d8ddbf5f-cdbb-45a0-b68d-95dcd7b46939",
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
              "id": "9cc55619-69a8-4ece-9040-1cc63d553d48"
            }
          ]
        }
      ]
    },
    {
      "name": "Queues",
      "item": [
        {
          "id": "12d21574-4e30-44b2-8ada-1cc4c161ccd7",
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
              "id": "6016fc1b-e3df-499b-a452-f71c86c77363"
            }
          ]
        },
        {
          "id": "07be1d4e-fc52-476f-91eb-8bf3838e2e2e",
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
              "id": "6eab4f3c-786e-4ad9-ad88-94e958b18b79"
            }
          ]
        },
        {
          "id": "1cd1c3a7-571e-4352-9677-8c34f57114bb",
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
              "id": "b820ec40-056f-4a99-9415-87c06df97a29"
            }
          ]
        },
        {
          "id": "544c201e-0f2a-4a6f-b5ff-ee3b670cde0f",
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
              "id": "6f64bf2f-d2a5-4681-85c6-841c194b30bd"
            }
          ]
        },
        {
          "id": "af9605dd-a1a1-4e66-98fa-a861a8826431",
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
              "id": "da9364fc-f73b-41a8-9006-ec145257c0eb"
            }
          ]
        },
        {
          "id": "2a430037-7f94-4c45-824c-ca1bb25b427a",
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
              "id": "a266ead6-2e00-45d0-a08f-6ab8dcde9937"
            }
          ]
        },
        {
          "id": "f6ce5017-ad49-4b93-a70d-14185c0617ec",
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
              "id": "bc1c0162-4785-4757-bb06-9397188ab8ac"
            }
          ]
        },
        {
          "id": "91b74fea-689d-4550-b301-10b5ac10b226",
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
              "id": "3167d954-78c8-4f91-a47a-1ec2455481e8"
            }
          ]
        },
        {
          "id": "4a9c90cd-17f5-4110-bf2f-b4e0a485cf14",
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
              "id": "a598538f-8e09-4b8d-911e-431575723a22"
            }
          ]
        },
        {
          "id": "9f18d9a2-414f-42e4-9a17-339e0939d327",
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
              "id": "52ca910d-8958-4e62-85eb-11e52e707d35"
            }
          ]
        }
      ]
    },
    {
      "name": "SIP Credential Lists",
      "item": [
        {
          "id": "f3a88157-6fba-4536-8d9d-a26bb06f069d",
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
              "id": "9a94f4a9-06e7-4c84-8007-0039252a04b8"
            }
          ]
        },
        {
          "id": "950eb317-15cc-41c7-88d9-c505e078befb",
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
              "id": "ce2f448e-34d4-4743-910d-ff2fb9e72714"
            }
          ]
        },
        {
          "id": "321f5fa6-c6ad-433b-8af8-6ce8b18715b6",
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
              "id": "8d271620-fbf4-452b-8390-247fa805c42b"
            }
          ]
        },
        {
          "id": "3934d48a-a8b2-47b2-baaf-ebcd474fefaa",
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
              "id": "f518226d-d0a7-436b-bac5-17c9283f54f7"
            }
          ]
        },
        {
          "id": "a9579c43-fa57-435f-be85-9de9535c7519",
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
              "id": "993c33a7-456f-4be5-b85d-576b29299199"
            }
          ]
        },
        {
          "id": "97811f4d-efdc-4577-b622-9f8606ef8d2e",
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
              "id": "af218eca-a62c-43d8-82e7-79f88c33e48c"
            }
          ]
        },
        {
          "id": "2c075d01-9713-40b9-8d74-151f894c76d1",
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
              "id": "c9ff29f6-fe11-4fae-93f9-8298a8ce84f4"
            }
          ]
        },
        {
          "id": "06ea4625-36f2-4f35-b666-035cacc4f9e8",
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
              "id": "23577110-e90d-4b78-bdd4-d024f4d8b00f"
            }
          ]
        },
        {
          "id": "a69f699f-9644-4a9e-9a99-15883b0e55d0",
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
              "id": "917e38c5-12e0-45fa-9da9-a1cbe8ab456f"
            }
          ]
        },
        {
          "id": "ec214cec-5262-4cc6-a179-1ed1eaa6ec1c",
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
              "id": "9cf656f5-3875-4fe2-8d00-82de6b186b5b"
            }
          ]
        }
      ]
    },
    {
      "name": "SIP Domains",
      "item": [
        {
          "id": "e54010fe-a79a-4313-a257-b83b6992b2ef",
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
              "id": "7675d90f-a8bb-43b5-bd18-c193c6f5950a"
            }
          ]
        },
        {
          "id": "8db25afe-9cd5-4ff1-98e1-43f1be0c8b02",
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
              "id": "9fb20c14-7e48-405f-8700-0dc9a45eef38"
            }
          ]
        },
        {
          "id": "3bf6d85f-3940-4912-9258-8d4dbe5cd5a5",
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
              "id": "50b0eaa7-da6b-40f3-b019-3306659c333a"
            }
          ]
        },
        {
          "id": "54fef9df-4e86-4d47-a577-64852b242659",
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
              "id": "39afc3e1-d6c6-4d03-afd4-fd204cc63ff8"
            }
          ]
        },
        {
          "id": "60cc6fa9-6650-4ef8-99ef-eb7d6e2e3ef6",
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
              "id": "532c9bce-78de-4fb9-818a-0d9c0a9175ed"
            }
          ]
        },
        {
          "id": "f6b1852f-48bb-4c0d-a315-d029ff46104e",
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
              "id": "27b01f2e-fcc3-4f50-b189-25f7738031a0"
            }
          ]
        },
        {
          "id": "ac443591-47c9-4047-a68b-aaaf7dbea8b9",
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
              "id": "2ca27ba4-8404-4dc6-b414-0ecf2992972d"
            }
          ]
        },
        {
          "id": "96df4ade-8eea-46cc-869c-d1807ce48fe8",
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
              "id": "8090c3b4-c26b-4cea-aeb4-d9c9719ee7a7"
            }
          ]
        },
        {
          "id": "989b2607-927e-4874-85dd-fe76621ec23a",
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
              "id": "c7b4202f-01a4-478f-b083-f2a854bc53c8"
            }
          ]
        },
        {
          "id": "c629de7a-ab81-4c1c-ab31-ae7b62818ef3",
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
              "id": "5a9a7aaa-a272-44f9-a24c-cb6d737199e9"
            }
          ]
        },
        {
          "id": "5f1039ca-3d9d-45b8-8a35-58fdbbaa870c",
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
              "id": "7027287e-96b5-492f-af22-9a057dab1b10"
            }
          ]
        },
        {
          "id": "9f09cb2c-fd70-4aa9-a6d1-df58335e2ad2",
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
              "id": "5eccb854-dbbf-44a7-9073-f8f857c4e34d"
            }
          ]
        }
      ]
    },
    {
      "name": "SIP IP Access Control Lists",
      "item": [
        {
          "id": "9036f69d-b7ed-4754-8425-67f563bbac15",
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
              "id": "8cc7535d-103e-4f54-bb01-36f9f2d69197"
            }
          ]
        },
        {
          "id": "36d7e054-f12d-483f-a17f-0971abe69b6b",
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
              "id": "f0ed0d78-5e67-40af-b18a-f3cc9623005f"
            }
          ]
        },
        {
          "id": "342b6368-fa1b-446e-bcd4-a8f7d555e1e8",
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
              "id": "07015cc3-ee16-485d-9bff-96d26726239c"
            }
          ]
        },
        {
          "id": "f27360b7-f44e-4aaa-8fb0-7479bdbbb3b7",
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
              "id": "a4cbd416-8737-4dc3-a124-ae9c8407fbfe"
            }
          ]
        },
        {
          "id": "de3eb633-6991-4eea-b380-e51055b6f415",
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
              "id": "beff3e33-aeb6-4342-a6b2-ec5eccd967ed"
            }
          ]
        },
        {
          "id": "629e67ba-9bae-4544-84de-b1710abe3525",
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
              "id": "9b09952c-324e-4e15-a0de-a35c2a51be9b"
            }
          ]
        },
        {
          "id": "5bba798b-59a1-498b-b12d-9d1c25a9324f",
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
              "id": "379769f3-40fd-4fb7-ad76-6ab695fca69c"
            }
          ]
        },
        {
          "id": "5cf4fa99-d52b-431c-be8f-a3497c81460c",
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
              "id": "434ad716-7ff4-44bc-91e2-e272f4ce77ba"
            }
          ]
        },
        {
          "id": "0e946a45-d4b3-423a-ad71-1f36d4d176c3",
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
              "id": "64b257d1-bad5-4204-b442-687adcdefe76"
            }
          ]
        },
        {
          "id": "cdf10cd1-4230-4878-b3b6-d30bed44106d",
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
              "id": "6f69ac3b-e212-44c7-ba76-5698e4b4f6f8"
            }
          ]
        }
      ]
    },
    {
      "name": "Short Codes",
      "item": [
        {
          "id": "58924652-dde1-4f33-81db-0eaf23fe7f6b",
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
              "id": "3103faa3-13d4-4ca7-a847-90fa04afaab7"
            }
          ]
        },
        {
          "id": "37618fca-0c1b-4617-8579-5f192692734a",
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
              "id": "cc2d77fb-cb68-4d59-898d-497602500409"
            }
          ]
        },
        {
          "id": "b7d0eefd-035e-4003-8354-bcff0726fae5",
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
              "id": "d6774425-4ca0-42ca-b615-7ff73e90291c"
            }
          ]
        }
      ]
    },
    {
      "name": "SMS Messages",
      "item": [
        {
          "id": "68698e58-bf67-49c6-97b2-8b4d57d51b5c",
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
              "id": "7db9d225-4c4b-4f72-8ce6-0c9613abc66d"
            }
          ]
        },
        {
          "id": "dd168f23-b6ae-4c0d-b1ef-ed73df17e9d0",
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
              "id": "983485a7-1939-4b6d-a203-4ecd2e2d2804"
            }
          ]
        },
        {
          "id": "ee2f12a0-6e0c-4112-8347-cf0b41cf34bd",
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
              "id": "c6375597-c28f-4038-a12e-f7bd9af74f06"
            }
          ]
        }
      ]
    },
    {
      "name": "Transcriptions",
      "item": [
        {
          "id": "7c09801d-e99a-4e7c-96a3-9ac279eea660",
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
              "id": "21ca16a6-9473-41ce-ab04-6d08145ddc59"
            }
          ]
        },
        {
          "id": "a01d7a3b-7e59-47e2-8528-d85741ead206",
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
              "id": "36c365d0-cc0b-4aac-9cb8-013dbbe527f8"
            }
          ]
        },
        {
          "id": "1f90e431-a0f5-4ba6-b8e8-203308d7efa8",
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
              "id": "ca2620f0-b574-4cd7-9995-7a8aad82e419"
            }
          ]
        },
        {
          "id": "61e7c8e5-871c-4e2b-8aee-11e7f1452577",
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
              "id": "afdde7e8-1714-4cbb-b81a-bf7187c1afbf"
            }
          ]
        },
        {
          "id": "ecaf1776-e973-4d63-adb1-417cfc69f205",
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
              "id": "5dd8d725-8c05-4ae6-b37e-5eeb0306f247"
            }
          ]
        }
      ]
    },
    {
      "name": "Usage Records",
      "item": [
        {
          "id": "72456375-d0cc-40a6-bbb2-b8eec98bf644",
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
              "id": "ca94b986-2f82-41c5-b0f1-8e05a5e68a5d"
            }
          ]
        },
        {
          "id": "b169bc4e-d8ed-48e1-bf5b-b143f992651d",
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
              "id": "4ca31cf3-99ea-48a1-aa59-4426142c811a"
            }
          ]
        }
      ]
    },
    {
      "name": "Usage Triggers",
      "item": [
        {
          "id": "2cf5baca-11f0-49a7-8500-bb9a9340588a",
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
              "id": "89a0c6cf-ae49-452c-a455-b4e6ea94e6c6"
            }
          ]
        },
        {
          "id": "4751222b-3fe2-4713-92a2-98e3d76c6e32",
          "name": "tries-to-update-the-usagetriggers-properties-and-returns-the-updatedresource-representation-if-succe",
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
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Tries to update the UsageTriggers properties, and returns the updatednresource representation if successful.n"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "517d253e-16fd-4b85-8785-2259aca3b79d"
            }
          ]
        },
        {
          "id": "0b053218-23e9-4379-bb73-b3c7cfd278ae",
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
              "id": "73a62373-e631-4ffe-aa51-d0baf2f2c8e9"
            }
          ]
        }
      ]
    }
  ]
}