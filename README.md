# Figma API & MCP Sandbox
This is an API sandbox for the Figma API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## APIs.json
There is an APIs.yml file in the root of this repository, providing an index of all the artifacts used as part of this API sandbox, providing a machine-readable way to read, manage, and execute the sandbox available here.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the Figma API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the Figma API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the Figma API & MCP Sandbox.

- Number of Paths: 12
- Number of Operations: 13
- Number of Read Operations: 10
- Number of Write Operations: 3
- Number of Schemas: 111
- Number of Responses: 67
- Number of Parameters: 32
- Number of Examples: 45
- Number of Request Bodies: 2
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the Figma API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Figma Activity Logs API](openapi/figma-activity-logs-api-openapi.yml)
  - [Figma Analytics API](openapi/figma-analytics-api-openapi.yml)
  - [Figma API](openapi/figma-api-openapi.yml)
  - [Figma Component Sets API](openapi/figma-component-sets-api-openapi.yml)
  - [Figma Dev Resources API](openapi/figma-dev-resources-api-openapi.yml)
  - [Figma Files API](openapi/figma-files-api-openapi.yml)
  - [Figma Images API](openapi/figma-images-api-openapi.yml)
  - [Figma Me API](openapi/figma-me-api-openapi.yml)
  - [Figma Payments API](openapi/figma-payments-api-openapi.yml)
  - [Figma Projects API](openapi/figma-projects-api-openapi.yml)
  - [Figma Styles API](openapi/figma-styles-api-openapi.yml)
  - [Figma Teams API](openapi/figma-teams-api-openapi.yml)

## Resources
These are the resources available via the Figma API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Activity Logs
  - Component Sets
  - Dev Resources
  - Files
  - Images
  - Keys
  - Library Analytics
  - Me
  - Payments
  - Projects
  - Styles
  - Teams
  - Users
  - Webhooks

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked Figma API & MCP Sandbox.

  - Create Dev Resources
  - Delete Dev Resource
  - Get Activity Logs
  - Get Component Set
  - Get Current User
  - Get Current User
  - Get Files In A Project
  - Get Library Analytics Usage Data
  - Get Payments
  - Get Style
  - Get Team Webhooks
  - Render Images Of File Nodes
  - Update Dev Resources

## Backstage
We provide a Backstage software catalog entity for the Figma API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Figma Activity Logs API](backstage/figma-activity-logs-api-api-sandbox-backstage.yml)
  - [Figma Analytics API](backstage/figma-analytics-api-api-sandbox-backstage.yml)
  - [Figma API](backstage/figma-api-api-sandbox-backstage.yml)
  - [Figma Component Sets API](backstage/figma-component-sets-api-api-sandbox-backstage.yml)
  - [Figma Dev Resources API](backstage/figma-dev-resources-api-api-sandbox-backstage.yml)
  - [Figma Files API](backstage/figma-files-api-api-sandbox-backstage.yml)
  - [Figma Images API](backstage/figma-images-api-api-sandbox-backstage.yml)
  - [Figma Me API](backstage/figma-me-api-api-sandbox-backstage.yml)
  - [Figma Payments API](backstage/figma-payments-api-api-sandbox-backstage.yml)
  - [Figma Projects API](backstage/figma-projects-api-api-sandbox-backstage.yml)
  - [Figma Styles API](backstage/figma-styles-api-api-sandbox-backstage.yml)
  - [Figma Teams API](backstage/figma-teams-api-api-sandbox-backstage.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party Figma API & MCP Sandbox.

