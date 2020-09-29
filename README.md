# Introduction

The API for the [NHR mock system](https://github.com/Morail/introsde_project_ws_nhr) are developed to query the database for retrieving info about recorded patients.

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
