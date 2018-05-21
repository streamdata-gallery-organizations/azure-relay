{
  "info": {
    "name": "Azure Relay API Operations List",
    "_postman_id": "8c90de03-6537-4698-8147-a46887554d1e",
    "description": "Lists all of the available Relay REST API operations.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "operations",
      "item": [
        {
          "id": "fee2581f-ac39-4ca9-9b4f-4eb04bcd5bba",
          "name": "Operations_List",
          "request": {
            "url": "http://management.azure.com/providers/Microsoft.Relay/operations?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the available Relay REST API operations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0fbeb3a-2653-4cde-a6fa-72497f7b910a"
            }
          ]
        }
      ]
    }
  ]
}