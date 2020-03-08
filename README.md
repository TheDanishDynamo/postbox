# PostBox
Server endpoint for capturing HTTP(S) request data for logging, forwarding and analysis. Similar service at https://webhook.site, we need the source for that to make our own.

# Requirement

| ID | Title | User Story | Overview | Type |  
|:--:|:--|:--|:--:|:--:|    
| U001 | Basic Capture | As a software developer I want to view the content of a HTTP request to postbox so I can see the payload and test client connectivity | This is the curated user story related to functional MVP | Functional |  
| U002 | Basic Security | As a owner of company XYZ, I want to prevent public access to payloads logged in PostBox | This is the curated user story related to security MVP | Non-functional |  
| U003 | Basic Handling - E-Mail forwarding | As a software developer I want to view the content of a HTTP request to PostBox in an email that is sent when PostBox receive a request | Variation of U001 with email delivery | Functional |  
