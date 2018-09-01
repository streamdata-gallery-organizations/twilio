{
  "info": {
    "name": "Twilio",
    "_postman_id": "963860bc-cd2e-45fd-ae33-2cf1f039a546",
    "description": "Twilio is a cloud communications Infrastructure as a Service(IaaS) company based in San Francisco, California. Twilio allows software developers to programmatically make and receive phone calls and send and receive text messages using its web service APIs. Twilio's services are accessed over HTTP and are billed based on usage.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "applications",
      "item": [
        {
          "id": "1aafc32f-ef95-49bd-a42d-8d1449b7e35d",
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
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"uri\": \"uri\",\r\n    \"firstpageuri\": \"firstpageuri\",\r\n    \"nextpageuri\": \"nextpageuri\",\r\n    \"previouspageuri\": \"previouspageuri\",\r\n    \"page\": \"page\",\r\n    \"pagesize\": \"pagesize\",\r\n    \"applications\": {}\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "f556b74e-9966-4723-9fc7-41d001db030f"
            }
          ]
        }
      ]
    }
  ]
}