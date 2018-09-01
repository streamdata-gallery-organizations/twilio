{
  "info": {
    "name": "Twilio Add Queue",
    "_postman_id": "11a71c9e-8853-4493-ba4c-560ab4c0c049",
    "description": "Create a new Queue resource.n",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "queues",
      "item": [
        {
          "id": "6e5d65ef-23e3-4c39-9e7f-4d404a23d3e5",
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
            "description": "Create a new Queue resource"
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
              "body": "[\r\n  {\r\n    \"uri\": \"uri\",\r\n    \"firstpageuri\": \"firstpageuri\",\r\n    \"nextpageuri\": \"nextpageuri\",\r\n    \"previouspageuri\": \"previouspageuri\",\r\n    \"page\": \"page\",\r\n    \"pagesize\": \"pagesize\",\r\n    \"queue\": {}\r\n  }\r\n]",
              "status": "Successful response",
              "code": 201,
              "name": "Response_201",
              "id": "d6622110-63f4-4ff3-8061-a903523a37af"
            },
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "{\r\n  \"Status\": \"Status\",\r\n  \"Message\": \"Message\",\r\n  \"Code\": \"Code\",\r\n  \"MoreInfo\": \"MoreInfo\"\r\n}",
              "status": "The data given in the POST or PUT failed validation",
              "code": 400,
              "name": "Response_400",
              "id": "0fa1d574-238d-4362-9f0d-20ec6acab4b8"
            },
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "{\r\n  \"Status\": \"Status\",\r\n  \"Message\": \"Message\",\r\n  \"Code\": \"Code\",\r\n  \"MoreInfo\": \"MoreInfo\"\r\n}",
              "status": "The supplied credentials, if any, are not sufficient to create or update the resource",
              "code": 401,
              "name": "Response_401",
              "id": "13173f67-5a25-494e-8409-e8d41ba68647"
            },
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "{\r\n  \"Status\": \"Status\",\r\n  \"Message\": \"Message\",\r\n  \"Code\": \"Code\",\r\n  \"MoreInfo\": \"MoreInfo\"\r\n}",
              "status": "You know this one",
              "code": 404,
              "name": "Response_404",
              "id": "4667e9a3-d32b-418e-8c91-fe325780d2d7"
            },
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "{\r\n  \"Status\": \"Status\",\r\n  \"Message\": \"Message\",\r\n  \"Code\": \"Code\",\r\n  \"MoreInfo\": \"MoreInfo\"\r\n}",
              "status": "You can't POST or PUT to the resource",
              "code": 405,
              "name": "Response_405",
              "id": "99029179-33e5-4b3e-9752-d89654cbc012"
            },
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "{\r\n  \"Status\": \"Status\",\r\n  \"Message\": \"Message\",\r\n  \"Code\": \"Code\",\r\n  \"MoreInfo\": \"MoreInfo\"\r\n}",
              "status": "Your application is sending too many simultaneous requests",
              "code": 429,
              "name": "Response_429",
              "id": "da66a03d-12b9-4b76-8af5-794c8e00f45a"
            },
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "{\r\n  \"Status\": \"Status\",\r\n  \"Message\": \"Message\",\r\n  \"Code\": \"Code\",\r\n  \"MoreInfo\": \"MoreInfo\"\r\n}",
              "status": "We couldn't create or update the resource",
              "code": 500,
              "name": "Response_500",
              "id": "aefbaa85-6ec4-4577-93e6-2987b76ba23f"
            }
          ]
        }
      ]
    }
  ]
}