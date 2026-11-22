# Awesome API Gateways

A curated directory of API gateways and API-management platforms, open source and managed.

## 📑 Table of Contents

- [Open Source Gateways (11)](#open-source-gateways)
- [AI Gateways (5)](#ai-gateways)
- [API Management Suites (10)](#api-management-suites)
- [Developer Portals (7)](#developer-portals)
- [Kubernetes Gateway API (1)](#kubernetes-gateway-api)
- [Managed / Cloud Gateways (4)](#managed--cloud-gateways)


## Open Source Gateways

- [Hasura](https://github.com/hasura/graphql-engine) - Fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also triggers webhooks on database events. Released under Apache-2.0 license with Docker and Kubernetes support for self-hosted deployment. ([Read more](/details/hasura.md)) `Open Source` `Self Hosted` `GraphQL` `Kubernetes`
- [Kong Gateway](https://konghq.com/products/kong-gateway) - Kong Gateway is a lightweight, cloud-native API gateway built on NGINX that helps teams manage API traffic. It provides security, authentication, transformation, and analytics capabilities through plugins. Available in open source, Enterprise, and Kong Konnect offerings, it supports deployment on-premises, in the cloud, on Kubernetes, and in serverless environments. ([Read more](/details/kong-gateway.md)) `Open Source` `Self Hosted` `API` `NGINX Based`
- [Aastro](https://github.com/aastro/aastro) - Extensible API Gateway written in Go, released under the Apache-2.0 license. Provides API gateway capabilities with Docker support for self-hosted deployment. ([Read more](/details/aastro.md)) `Open Source` `Self Hosted` `Gateway`
- [Apache APISIX](https://apisix.apache.org/) - Apache APISIX is a cloud-native API gateway under the Apache Software Foundation, built on OpenResty and etcd. It supports dynamic routing, plugins, and is designed for high-performance microservices traffic management. ([Read more](/details/apache-apisix.md)) `Open Source` `Self Hosted` `Free Plan` `API` `Cloud-Native`
- [Apache ShenYu](https://shenyu.apache.org/) - Apache ShenYu is a Java-native API Gateway for service proxy, protocol conversion, and API governance. It is an open-source project under the Apache License 2.0, with source hosted at github.com/apache/shenyu, and is designed for self-hosted deployment. ([Read more](/details/apache-shenyu.md)) `Open Source` `Java` `Self Hosted` `Api Gateway`
- [Graphweaver](https://github.com/exogte/graphweaver) - Turns multiple data sources into a single GraphQL API. Open source project released under MIT license for self-hosted deployment. ([Read more](/details/graphweaver.md)) `Open Source` `Self Hosted` `GraphQL` `API`
- [Kong](https://konghq.com/) - Kong Gateway is a cloud-native API gateway built on NGINX and OpenResty, offering traffic management, security, and plugin extensibility. It is available as open-source Kong Gateway and as managed Kong Konnect. Pricing includes a free tier and paid enterprise plans. ([Read more](/details/kong.md)) `Open Source` `Self Hosted` `Free Plan` `Freemium` `Enterprise` `API`
- [KrakenD](https://www.krakend.io/) - KrakenD is a high-performance open-source API gateway focused on aggregation and stateless request processing. It is designed for enterprises needing ultra-low latency and simple configuration without a database. ([Read more](/details/krakend.md)) `Open Source` `Self Hosted` `Free Plan` `Freemium` `API` `Enterprise`
- [Svix](https://github.com/svix/svix-webhooks) - Webhooks as a service that makes it super easy for API providers to send webhooks. Released under MIT license with Docker support for self-hosted deployment. ([Read more](/details/svix.md)) `Open Source` `Self Hosted` `Webhooks`
- [Traefik](https://traefik.io/) - Traefik is a cloud-native edge router and API gateway that automatically discovers services and configures routing for Docker, Kubernetes, and other orchestrators. It supports Let's Encrypt, middleware, and observability. ([Read more](/details/traefik.md)) `Open Source` `Self Hosted` `Free Plan` `Freemium` `API` `Kubernetes`
- [Tyk](https://tyk.io/) - Tyk is an open-source API gateway and management platform written in Go, providing rate limiting, authentication, analytics, and a developer portal. It offers self-hosted open-source editions and managed cloud options. ([Read more](/details/tyk.md)) `Open Source` `Self Hosted` `Free Plan` `Freemium` `API` `Gateway`

## AI Gateways

- [GoModel](https://github.com/go-model/go-model) - AI gateway written in Go with a unified OpenAI-compatible API for multiple LLM providers, USD cost tracking, budgets, usage analytics, guardrails, caching, and an admin dashboard. Released under MIT license with Docker support for self-hosted deployment. ([Read more](/details/gomodel.md)) `Open Source` `Self Hosted` `AI Powered` `API`
- [one-api](https://github.com/songquanpeng/one-api) - one-api is an LLM API management and key redistribution system that unifies multiple model providers under a single OpenAI-compatible API. It supports providers including OpenAI, Azure, Anthropic Claude, Google Gemini, and others, enabling API key management and secondary distribution. It is a self-hosted, single-binary, Docker-ready open-source project (MIT licensed) with an English UI. ([Read more](/details/one-api.md)) `Open Source` `Self Hosted` `AI Powered` `Llm`
- [OpenRouter](https://openrouter.ai) - OpenRouter is a router for LLMs and other AI models, providing unified access to multiple language models through a single API interface. It enables developers to route requests to different AI models, compare model performance, and manage AI model integrations from one endpoint. ([Read more](/details/openrouter.md)) `AI Powered` `Gateway` `Llm`
- [Opik](https://github.com/comet-ml/opik) - Evaluate, test, and ship LLM applications with a suite of observability tools to calibrate language model outputs across dev and production lifecycles. Released under Apache-2.0 license with Docker support for self-hosted deployment. ([Read more](/details/opik.md)) `Open Source` `Self Hosted` `AI Powered`
- [Tempreon](https://tempreon.com) - Tempreon is a personal memory layer for AI tools, connected over MCP (Model Context Protocol). It provides cross-LLM memory capabilities, a core imprint system, a knowledge vault, and a learning system layer to help AI tools retain context and learn from interactions. Pricing is freemium, starting at $19 per month when billed annually. ([Read more](/details/tempreon.md)) `AI Powered` `Freemium` `MCP`

## API Management Suites

- [Axway Amplify API Management](https://www.axway.com/en/products/amplify-api-management) - Axway Amplify API Management is an enterprise platform for securing, governing, and monetizing APIs across hybrid and multi-cloud environments. It includes an API gateway, catalog, and analytics. ([Read more](/details/axway-amplify-api-management.md)) `Paid` `Enterprise` `API Management` `Hybrid Cloud` `Governance`
- [Boomi API Management](https://boomi.com/) - Boomi API Management is part of the Boomi AtomSphere platform, providing API gateway, lifecycle management, and developer portal capabilities. It is a cloud-native integration platform for connecting applications and data. ([Read more](/details/boomi-api-management.md)) `Paid` `Enterprise` `API Management` `Integration` `Cloud`
- [DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory) - Turns any SQL/NoSQL/Structured data into RESTful API. Open source platform released under Apache-2.0 license with Docker and Kubernetes support for self-hosted deployment. ([Read more](/details/dreamfactory.md)) `Open Source` `Self Hosted` `API`
- [Fusio](https://github.com/apioo/fusio) - API management platform which helps to build and manage REST APIs. Released under AGPL-3.0 license with Docker support for self-hosted deployment. ([Read more](/details/fusio.md)) `Open Source` `Self Hosted` `API Management`
- [Google Apigee](https://cloud.google.com/apigee) - Apigee is Google Cloud's API management platform for designing, securing, deploying, and monitoring APIs at scale. It provides analytics, developer portals, and enterprise-grade security and monetization features. ([Read more](/details/google-apigee.md)) `Managed` `Cloud` `Paid` `Enterprise` `API Management` `Google Cloud`
- [Gravitee](https://gravitee.io/) - Gravitee is an open-source API management platform offering a gateway, management console, developer portal, and analytics. It supports full API lifecycle management with self-hosted and cloud deployment options. ([Read more](/details/gravitee.md)) `Open Source` `Self Hosted` `Free Plan` `Freemium` `Enterprise` `API Management`
- [MuleSoft Anypoint Platform](https://www.mulesoft.com/) - MuleSoft Anypoint Platform is a commercial integration and API management suite for designing, building, and managing APIs and integrations. It targets enterprises with API-led connectivity and includes an API gateway, designer, and exchange. ([Read more](/details/mulesoft-anypoint-platform.md)) `Paid` `Enterprise` `API Management` `Integration` `Cloud` `Self Hosted`
- [Para](https://github.com/Erudika/para) - Flexible and modular backend framework/server for object persistence, API development and authentication. Released under Apache-2.0 license with Docker support for self-hosted deployment. ([Read more](/details/para.md)) `Open Source` `Self Hosted` `API`
- [WSO2 API Manager](https://wso2.com/api-manager) - WSO2 API Manager is an open-source API management platform for designing, publishing, and securing APIs. It includes a gateway, publisher, developer portal, and analytics, with self-hosted and cloud deployment options. ([Read more](/details/wso2-api-manager.md)) `Open Source` `Self Hosted` `Free Plan` `Freemium` `Enterprise` `API Management`
- [Zapier](https://zapier.com) - Zapier is an automation platform that connects over 1000 apps to automate workflows without coding. It enables users to create integrations between popular web applications, set up custom automations, and scale workflows as needed. The platform offers a free tier with paid plans for higher task volumes and premium features. ([Read more](/details/zapier.md)) `Integration` `Automation` `Freemium` `Paid`

## Developer Portals

- [cURL](https://curl.se) - cURL is a computer software project providing a library and command-line tool for transferring data using various network protocols. It is versatile, cross-platform, and designed for command-line usage and automation. The project is open source and widely used for API testing, data transfer, and scripting. ([Read more](/details/curl.md)) `Open Source` `CLI` `API`
- [FastAPI](https://fastapi.tiangolo.com) - FastAPI is an open-source, modern, high-performance web framework for building APIs with Python 3.6+ based on standard Python type hints. It offers automatic interactive API documentation, type checking and validation, and ease of use. The framework is designed for building production-ready APIs quickly with minimal code. ([Read more](/details/fastapi.md)) `Open Source` `Python` `API` `Web Framework`
- [Hoppscotch](https://hoppscotch.io) - Hoppscotch is an open-source API development ecosystem that provides a lightweight, real-time API request builder and client. It features a user-friendly interface, multi-platform support, and real-time collaboration capabilities for designing and testing APIs. The tool is available as a web application and desktop client, with a freemium pricing model. ([Read more](/details/hoppscotch.md)) `Open Source` `Freemium` `API` `Developer Experience`
- [Insomnia REST](https://insomnia.rest) - Insomnia is an open-source API client for designing, debugging, testing, and mocking APIs locally, on Git, or in the cloud. It supports multiple protocols including REST, GraphQL, gRPC, and WebSockets, with environment management, custom plugins, and themes. The tool offers a developer-friendly UI with built-in automation and an extensible plugin ecosystem. ([Read more](/details/insomnia-rest.md)) `Open Source` `API` `Developer Experience` `Self Hosted`
- [Paw](https://paw.cloud) - Paw is a REST client for macOS that provides a native Mac interface for designing, testing, and debugging HTTP APIs. It features team collaboration capabilities, advanced request capabilities, and support for extensions and plugins. The tool is designed for macOS developers who need a full-featured HTTP client for API development. ([Read more](/details/paw.md)) `API` `Mac` `Client`
- [Postman](https://www.postman.com) - Postman is a collaboration platform for API development that provides tools for designing, testing, documenting, and monitoring APIs. It offers a user-friendly interface for building API requests, team collaboration features, comprehensive testing capabilities, and extensive API documentation generation. Pricing includes a free tier with paid plans for advanced team and enterprise features. ([Read more](/details/postman.md)) `API` `Developer Experience` `Freemium`
- [RapidAPI](https://rapidapi.com) - RapidAPI is an API marketplace for finding and connecting to the world's top APIs. It provides a unified platform for developers to discover, test, and integrate APIs with unified billing and a testing environment. The platform supports a wide variety of APIs across different categories and offers both free and paid API access. ([Read more](/details/rapidapi.md)) `API` `Marketplace` `Freemium`

## Kubernetes Gateway API

- [Envoy Gateway](https://gateway.envoyproxy.io/) - Envoy Gateway is an open-source project that implements the Kubernetes Gateway API using Envoy as the data plane. It manages ingress and API traffic for Kubernetes clusters and is maintained by the Envoy community. ([Read more](/details/envoy-gateway.md)) `Open Source` `Kubernetes` `Gateway API` `Envoy` `Self Hosted`

## Managed / Cloud Gateways

- [AWS API Gateway](https://aws.amazon.com/api-gateway) - Amazon API Gateway is a fully managed service for creating, publishing, maintaining, and securing REST, HTTP, and WebSocket APIs at scale. It integrates with AWS Lambda and other AWS services and uses pay-as-you-go pricing. ([Read more](/details/aws-api-gateway.md)) `Managed` `Cloud` `Paid` `API` `AWS` `Serverless`
- [Azure API Management](https://azure.microsoft.com/en-us/products/api-management) - Azure API Management is a hybrid, multi-cloud API management platform for publishing, securing, transforming, and monitoring APIs. It includes a developer portal, policy engine, and integration with Azure services. ([Read more](/details/azure-api-management.md)) `Managed` `Cloud` `Paid` `Enterprise` `API` `Azure`
- [Cloudflare API Gateway](https://www.cloudflare.com/products/api-gateway) - Cloudflare API Gateway is a managed service for securing and managing API traffic at the edge, built on Cloudflare's network. It offers rate limiting, authentication, and schema validation with free and paid tiers. ([Read more](/details/cloudflare-api-gateway.md)) `Managed` `Cloud` `Free Plan` `Freemium` `API` `Edge`
- [Zuplo](https://zuplo.com/) - Zuplo is a developer-first API gateway and management platform built on Cloudflare Workers, offering edge deployment, API keys, and OpenAPI integration. It targets teams wanting quick API productization with minimal infrastructure. ([Read more](/details/zuplo.md)) `Managed` `Cloud` `Free Plan` `Freemium` `API` `Developer Experience`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg