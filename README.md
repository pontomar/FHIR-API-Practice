# FHIR API Practice

Getting acquainted with the FHIR standard and API interaction. This repository includes examples of FHIR resource creation and retrieval using HTTP requests, as well as the tools I used to streamline the development process.

## Tools Used

- **[Visual Studio Code (VS Code)](https://code.visualstudio.com/)**: My go-to code editor for working on FHIR-related requests and projects.
- **[REST Client VS Code Extension](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)**: Used for crafting and sending HTTP requests directly from VS Code.
- **[FHIR Tools for VS Code Extension](https://marketplace.visualstudio.com/items?itemName=cqframework.fhir-json)**: A powerful extension for working with FHIR resources, including validation, autocomplete, and other productivity features.

## What’s Included

- `createProfile.http`: A POST request payload to create a new Patient Resource on a FHIR server.
- `observation.http`: A POST request payload to create a Body Weight Observation Resource on a FHIR server.
- `search.http`: A GET request to search for Observations of a Patient with known Id.
- `query.http`: A GET request to retrieve Patient data based on specified search parameters.

## FHIR Servers

If the baseR4 server should not be available, here are some [alternative Servers](https://confluence.hl7.org/display/FHIR/Public+Test+Servers#PublicTestServers-Servers)
