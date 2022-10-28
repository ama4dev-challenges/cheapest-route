# Find the Cheapest Route

In this exercise you will have to find the cheapest way to **reach the conference** by plane from your place of birth.

Luckily the Munich Airport (IATA: MUC) is very well connected, so you will be able to find an [aiport near your city of birth](https://www.flightconnections.com/flights-from-munich-muc).

![FlightConnections](assets/muc_connections.png)

## Point Breakdown

| **Points**      | **Challenge** |
| ----------- | ----------- |
| **5** | Find the cheapest route from a given airport to the conference.<br />_See [Flight Offers Search](https://developers.amadeus.com/self-service/category/air/api-doc/flight-offers-search)_ |
| **8** | Find the cheapest route from the airport that is closest of your city of origin.<br />_See [Airport Nearest Relevant](https://developers.amadeus.com/self-service/category/air/api-doc/airport-nearest-relevant)_ |
| **10** | Find the cheapest route from the airport that is closest of your city of origink and direct connection to Munich.<br />_See [Airport Routes API](https://developers.amadeus.com/self-service/category/air/api-doc/airport-routes)_ |
| **+3** | DevOps Bonus: Wrap up your tool on a docker image |
| **+7** | DevOps Bonus: Put your input parameters and API key in an `input.json` and get your code running and printing the result for every commit via Github Actions |

## Getting started
You can retrieve your personal API key by following the [Quick Start Guide](https://alonsomoya.github.io/ama4dev/quick-start/).

If you are to add your API key to your repository, make sure **the [repository is private](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/setting-repository-visibility#making-a-repository-private)**!

## Choose your favorite weapon

We have a number of SDKs available to help you integrate Amadeus Self-Service APIs into your applications. To give more context to how each of the SDKs can be used, we also have a dedicated tutorial per programming language.

| **SDK source files**      | **SDK tutorial** |
| ----------- | ----------- |
| [Amadeus Node SDK](https://github.com/amadeus4dev/amadeus-node)| [Amadeus Node SDK tutorial](node-sdk.md) |
| [Amadeus Python SDK](https://github.com/amadeus4dev/amadeus-python)| [Amadeus Python SDK tutorial](python-sdk.md) |
| [Amadeus Java SDK](https://github.com/amadeus4dev/amadeus-node)| [Amadeus Java SDK tutorial](java-sdk.md) |

If you need an SDK in a different language, feel free to use the [OpenAPI Generator](https://openapi-generator.tech/) to automatically create an SDK from our [OpenAPI Specification files](https://github.com/amadeus4dev/amadeus-open-api-specification). We also have a [tutorial](openapi-generator.md) on how to do this.

