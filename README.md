# Introduction

API designed for interoperate with the National Health Service (NHS) [mock system](https://github.com/Morail/introsde_project_ws_nhs). These APIs are developed to query a Web Services which retrieves data about recorded patients from its database.

# Description

The API is composed by a single resource `/patients` that can ben invoked passing the patient's tax code as a query parameter.

Example query:
 `GET /patients?filter[taxCode]=PRVTST70A01L378Q`

Response:

    {
            "nhrCode": "a8098c1a-f86e-11da-bd1a-00112444be1e",
            "lastName": "PROVA",
            "firstName": "TEST",
            "gender": "M",
            "taxCode": "PRVTST70A01L378Q",
            "birthDate": "1970-01-01",
            "entryDate": "2020-09-28",
            "expiryDate": null
    }
