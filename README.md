# BirdStatsGPT

## Introduction
BirdStatsGPT is a custom GPT that combines the strengths of OpenAI's LLM (currently GPT-4-1106-preview)  / gpt-4-gizmo) with the eBird and BirdWeather APIs (among others), aimed at enhancing the interpretation of BirdNET Analysis data. This project is a nod to the incredible work done in the fields of ornithology and technology, and it's an effort to contribute to this vibrant community.


## Project Background
BirdStats GPT is an endeavor to merge the many AI/ML resources and databases, into a one-stop-shop for natural language based, high-level analysis.

## Setup Challenges
As I navigate through the early stages of this project, I'm focusing on the integration of the APIs for Birdweather (both REST and GraphQL), eBird, iNaturalist, and Xeno Cantu. With the intention of pulling data from the BirdBuddy Heartbeat project as well.  

## Contributing and Acknowledgements
This project thrives on community collaboration, starting with BirdNET and the subsequent Pi project.  A special shout-out to the creators and maintainers of the eBird, BirdWeather, and iNaturalist APIs – particularly Tim and Patrick. Your work inspires and enables projects like this.

## Current Technical Roadblocks
- **eBird API**: Running into some 401 errors with a simple test API-call; this has been a known issue from OpenAI; however, recent updates to the handling of tokens in headers and OAuth should have this resolved. The eBird API in OpenAPI json/yml, in it's entireity, is seemingly ellusive. 
- **BirdWeather API**: Working on getting the OpenAPI (yaml) GraphQL API structure under control; the REST API is, as of 2025-12-25, functional.
- **BirdBuddy Heartbeat API** I am nowhere with this...
- **iNaturalist will likely be the next live integration, but any help would be very greatly appreciated. 


