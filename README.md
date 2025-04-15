# Awesome API Clients & Postman/Insomnia Alternatives

A curated list of awesome **API Clients**, including the best **Postman Alternatives** and **Insomnia Alternatives** for API development, testing, documentation, and more. This repository aims to provide developers with a comprehensive overview of available API client tools, focusing on open-source and actively maintained projects where possible.

*Criteria: Generally open-source (unless specified), popular (e.g., >200 stars, >2 contributors if OS), and actively maintained where possible.*

## Keywords

API Clients, Postman Alternative, Insomnia Alternative, REST Client, GraphQL Client, gRPC Client, API Testing, API Development Tools, HTTP Client, API Debugging, API Documentation

## Contents
- [Overall Best Postman Alternative](#overall-best-postman-alternative)
- [Web-Based API Clients](#web-based-api-clients)
- [Desktop API Clients](#desktop-api-clients)
- [IDE Extensions](#ide-extensions)
- [CLI Tools](#cli-tools)
- [Automated API Testing & Load Testing Tools](#automated-api-testing--load-testing-tools)
- [API Design & Documentation Tools](#api-design--documentation-tools)
- [Specialized API Clients (GraphQL, gRPC, WebSocket)](#specialized-api-clients-graphql-grpc-websocket)
- [Proxy & Interception Tools](#proxy--interception-tools)
- [Language-Specific API Testing Libraries](#language-specific-api-testing-libraries)
- [Contributing](#contributing)
- [License](#license)

## Overall Best Postman Alternative

### 1. [Apidog](https://apidog.com/)
A comprehensive API development platform that integrates API design, debugging, testing, and documentation in one place. (Note: Not open-source, but included by request).
- **GitHub Repository**: [https://github.com/Apidog](https://github.com/Apidog) (Organization)
- **Features**: API design, debugging, mock services, automated testing, team collaboration, OpenAPI support

[![image](https://github.com/user-attachments/assets/2feef159-8530-4e96-8e60-a9ce704328cd)](https://apidog.com)

## Web-Based API Clients

### 2. [Hoppscotch](https://hoppscotch.io/)
Open source API development ecosystem (formerly Postwoman). Lightweight, web-based API client with a clean UI.
- **GitHub Repository**: [https://github.com/hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch)
- **Features**: REST, GraphQL, WebSockets, SSE, MQTT, Socket.IO, Server Sent Events

### 3. [Restfox](https://restfox.dev/)
Offline-first web HTTP client focused on privacy and simplicity.
- **GitHub Repository**: [https://github.com/flawiddsouza/Restfox](https://github.com/flawiddsouza/Restfox)
- **Features**: Offline-first, collections, environment variables, code generation

### 4. [Firecamp](https://firecamp.io/)
Open-source Postman alternative designed for collaborative API development, inspired by VS Code DX.
- **GitHub Repository**: [https://github.com/firecamp-dev/firecamp](https://github.com/firecamp-dev/firecamp)
- **Features**: Multi-protocol testing (REST, GraphQL, WebSockets, SocketIO, MQTT), collaborative workspaces

### 5. [RecipeUI](https://recipeui.com/)
A type-safe API client with automatic documentation generation.
- **GitHub Repository**: [https://github.com/RecipeUI/RecipeUI](https://github.com/RecipeUI/RecipeUI)
- **Features**: Type safety, automatic documentation, intuitive UI

### 6. [Yaade](https://yaade.io/)
Self-hosted, collaborative API development environment.
- **GitHub Repository**: [https://github.com/EsperoTech/yaade](https://github.com/EsperoTech/yaade)
- **Features**: Collaboration, self-hosted, environment variables, auth support

### 7. [Prestige](https://prestige.dev/)
Text-based in-browser HTTP client without UI clutter. An interface-less Postman alternative.
- **GitHub Repository**: [https://github.com/prestigejs/prestige](https://github.com/prestigejs/prestige)
- **Features**: Markdown-like syntax, simple interface, code generation

### 8. [Requestly](https://requestly.io/)
Browser extension and Desktop App with API Client, API Mocking & API Interception and Modification capabilities.
- **GitHub Repository**: [https://github.com/requestly/requestly](https://github.com/requestly/requestly)
- **Features**: API client, mocking, request interception, debugging, collaboration

### 9. [Testfully](https://testfully.io/)
Cloud-based API testing platform with collaboration features.
- **GitHub Repository**: [https://github.com/testfully/testfully](https://github.com/testfully/testfully) (Website/Docs Repo)
- **Features**: Automated testing, monitoring, team collaboration

### 10. [HTTPBox](https://httpbox.io)
In-browser collaborative REST API client.
- **GitHub Repository**: [https://github.com/httpbox/httpbox](https://github.com/httpbox/httpbox)
- **Features**: Real-time collaboration, request history, response visualization

### 11. [Caido](https://caido.io/)
Lightweight web security auditing toolkit including HTTP proxy and replay capabilities. (Free tier available, not fully OS).
- **Features**: HTTP Proxy, Replay, Intruder-like features, Scripting

## Desktop API Clients

### 12. [Bruno](https://www.usebruno.com/)
Git-friendly, open-source API client (IDE) with collections stored as files.
- **GitHub Repository**: [https://github.com/usebruno/bruno](https://github.com/usebruno/bruno)
- **Features**: Git integration, file-based collections (Bru Lang), offline-first, scripting

### 13. [Insomnia](https://insomnia.rest/)
Popular desktop API client with REST, GraphQL, gRPC, SOAP, and WebSockets support.
- **GitHub Repository**: [https://github.com/Kong/insomnia](https://github.com/Kong/insomnia)
- **Features**: Plugin ecosystem, design tools (OpenAPI), Git sync, testing, environment variables

### 14. [Insomnium](https://insomnium.rest/)
Privacy-focused fork of Insomnia without telemetry or account requirements. (Note: Development seems stalled/unmaintained as of late 2023).
- **GitHub Repository**: [https://github.com/ArchGPT/insomnium](https://github.com/ArchGPT/insomnium)
- **Features**: Privacy-focused, no telemetry, local storage, based on Insomnia core

### 15. [Yaak](https://yaak.app/)
Intuitive desktop API client focused on user experience.
- **GitHub Repository**: [https://github.com/raiyanyahya/yaak](https://github.com/raiyanyahya/yaak)
- **Features**: Clean UI, multi-protocol support (REST, GraphQL, gRPC), easy environment management

### 16. [API Dash](https://apidash.dev/)
Cross-platform, beautiful open-source API client with advanced features.
- **GitHub Repository**: [https://github.com/foss42/apidash](https://github.com/foss42/apidash) (Corrected Repo Link)
- **Features**: Cross-platform (Flutter-based), OAuth support, request chaining, code generation

### 17. [Pororoca](https://pororoca.io/)
HTTP inspection tool with HTTP/2 and HTTP/3 support.
- **GitHub Repository**: [https://github.com/alexandrehtrb/Pororoca](https://github.com/alexandrehtrb/Pororoca)
- **Features**: HTTP/2, HTTP/3 support, clean interface, Windows focus

### 18. [Nightingale REST Client](https://nightingale.rest/)
Modern, open-source, resource-efficient REST API client for Windows.
- **GitHub Repository**: [https://github.com/jenius-apps/nightingale-rest-api-client](https://github.com/jenius-apps/nightingale-rest-api-client)
- **Features**: Resource efficiency, Windows-optimized (UWP), collection management, Fluent design

### 19. [Milkman](https://github.com/warmuuh/milkman)
Extensible request/response workbench with plugin support.
- **GitHub Repository**: [https://github.com/warmuuh/milkman](https://github.com/warmuuh/milkman)
- **Features**: Plugin ecosystem (SQL, gRPC, WebSockets), extensibility, environment management

### 20. [Requestly](https://requestly.io/desktop/)
Desktop app version of Requestly (see Web-Based).
- **GitHub Repository**: [https://github.com/requestly/requestly](https://github.com/requestly/requestly)
- **Features**: API client, mocking, request interception, modification, collaboration

## IDE Extensions

### 21. [Thunder Client](https://www.thunderclient.com/)
Lightweight VS Code extension with GUI for API testing.
- **GitHub Repository**: [https://github.com/rangav/thunder-client-support](https://github.com/rangav/thunder-client-support) (Support Repo)
- **Features**: VS Code integration, collections, environment variables, scripting, tests

### 22. [REST Client (Huachao)](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
Popular VS Code extension for sending HTTP requests using a simple plain text format (`.http` or `.rest` files).
- **GitHub Repository**: [https://github.com/Huachao/vscode-restclient](https://github.com/Huachao/vscode-restclient)
- **Features**: Plain text requests, response handling, environment variables, code snippets, GraphQL, cURL conversion

### 23. [HTTP Client (JetBrains)](https://www.jetbrains.com/help/idea/http-client-in-product-code-editor.html)
Built-in HTTP client in JetBrains IDEs (IntelliJ IDEA, WebStorm, PyCharm, etc.) using `.http` files.
- **GitHub Repository**: N/A (Part of IDEs like [https://github.com/JetBrains/intellij-community](https://github.com/JetBrains/intellij-community))
- **Features**: IntelliJ integration, request scripting (JavaScript), environment variables, response assertions, UI runner

### 24. [REST Client (Firefox Add-on)](https://addons.mozilla.org/en-US/firefox/addon/restclient/)
Firefox debugger/client for RESTful web services.
- **GitHub Repository**: [https://github.com/chao/RESTClient](https://github.com/chao/RESTClient)
- **Features**: Firefox integration, request history, response formatting, authentication support

### 25. [Restclient.el](https://github.com/pashky/restclient.el)
HTTP REST client tool for Emacs using a plain text format similar to Org mode.
- **GitHub Repository**: [https://github.com/pashky/restclient.el](https://github.com/pashky/restclient.el)
- **Features**: Emacs integration, plain text format, syntax highlighting, variable substitution

### 26. [Verb](https://github.com/federicotdn/verb)
Organize and send HTTP requests from Emacs, often used with Org mode.
- **GitHub Repository**: [https://github.com/federicotdn/verb](https://github.com/federicotdn/verb)
- **Features**: Emacs integration, org-mode support, templating, environment management

### 27. [Rest.nvim](https://github.com/rest-nvim/rest.nvim)
A fast Neovim HTTP client written in Lua, using `.http` file format.
- **GitHub Repository**: [https://github.com/rest-nvim/rest.nvim](https://github.com/rest-nvim/rest.nvim)
- **Features**: Neovim integration, syntax highlighting, response preview, environment variables

### 28. [kulala.nvim](https://github.com/akshayKrSingh/kulala.nvim)
Minimal REST-Client interface for Neovim.
- **GitHub Repository**: [https://github.com/akshayKrSingh/kulala.nvim](https://github.com/akshayKrSingh/kulala.nvim)
- **Features**: Lightweight, Neovim integration, simple setup

## CLI Tools

### 29. [curl](https://curl.se/)
The ubiquitous command line tool and library for transferring data with URLs (since 1998). The foundation for many others.
- **GitHub Repository**: [https://github.com/curl/curl](https://github.com/curl/curl)
- **Features**: Universal support, extensive protocol support, robust options, scripting essential

### 30. [HTTPie](https://httpie.io/)
Human-friendly command-line HTTP client for the API era. Designed for intuitive syntax and formatted output.
- **GitHub Repository**: [https://github.com/httpie/httpie](https://github.com/httpie/httpie)
- **Features**: User-friendly syntax, JSON formatting & highlighting, plugin support, sessions

### 31. [xh](https://github.com/ducaale/xh)
Friendly and fast tool for sending HTTP requests, aiming for HTTPie compatibility with Rust performance.
- **GitHub Repository**: [https://github.com/ducaale/xh](https://github.com/ducaale/xh)
- **Features**: Rust-based performance, HTTPie-like syntax, JSON formatting, download resumption

### 32. [curlie](https://github.com/rs/curlie)
Combines the power and features of curl with the ease of use (syntax, output formatting) of HTTPie.
- **GitHub Repository**: [https://github.com/rs/curlie](https://github.com/rs/curlie)
- **Features**: Curl compatibility, improved output formatting & highlighting

### 33. [posting](https://github.com/barthap/posting)
Terminal-based API client with an intuitive TUI (Text User Interface).
- **GitHub Repository**: [https://github.com/barthap/posting](https://github.com/barthap/posting)
- **Features**: TUI interface, collections, environment variables, history

### 34. [Wuzz](https://github.com/asciimoo/wuzz)
Interactive command-line HTTP inspection tool with a TUI.
- **GitHub Repository**: [https://github.com/asciimoo/wuzz](https://github.com/asciimoo/wuzz)
- **Features**: TUI interface, live inspection, keyboard shortcuts, request modification

### 35. [HttpRepl](https://docs.microsoft.com/en-us/aspnet/core/web-api/http-repl/)
.NET command-line tool for exploring and testing HTTP APIs, allows navigating API structure.
- **GitHub Repository**: [https://github.com/dotnet/HttpRepl](https://github.com/dotnet/HttpRepl)
- **Features**: .NET integration, interactive navigation (`cd`, `ls`), OpenAPI integration, autocomplete

### 36. [ain](https://github.com/jonaslu/ain)
HTTP API client for the terminal that acts as a wrapper around curl, wget or httpie.
- **GitHub Repository**: [https://github.com/jonaslu/ain](https://github.com/jonaslu/ain)
- **Features**: Multiple backend support, simple configuration, scripting

### 37. [httpYac](https://httpyac.com/)
Command-line tool and library using the `.http` file format (like VS Code REST Client / JetBrains HTTP Client).
- **GitHub Repository**: [https://github.com/AnWeber/httpyac](https://github.com/AnWeber/httpyac)
- **Features**: Multi-protocol support (REST, SOAP, GraphQL, gRPC, WebSockets), variables, pre/post request scripts, CLI & JS API

### 38. [ATAC](https://github.com/daveshanley/atac)
Simple Postman-like API client for the terminal, using a TUI.
- **GitHub Repository**: [https://github.com/daveshanley/atac](https://github.com/daveshanley/atac)
- **Features**: Terminal UI, collections, environment support, runs `.atac` files

### 39. [Newman](https://github.com/postmanlabs/newman)
Command-line collection runner for Postman. Allows running Postman collections (`.json` export) in CI/CD pipelines.
- **GitHub Repository**: [https://github.com/postmanlabs/newman](https://github.com/postmanlabs/newman)
- **Features**: Runs Postman collections, CI/CD integration, reporting options

## Automated API Testing & Load Testing Tools

### 40. [Step CI](https://stepci.com/)
Open-source API Test Automation framework focusing on declarative testing using YAML.
- **GitHub Repository**: [https://github.com/stepci/stepci](https://github.com/stepci/stepci)
- **Features**: Declarative testing (YAML), CI integration, monitoring, response validation

### 41. [Hurl](https://hurl.dev/)
Run and test HTTP requests defined in a simple plain text format (`.hurl` files). Uses libcurl.
- **GitHub Repository**: [https://github.com/Orange-OpenSource/hurl](https://github.com/Orange-OpenSource/hurl)
- **Features**: Plain text format, assertions, chaining requests, capturing values, CI integration

### 42. [Karate](https://github.com/karatelabs/karate)
Test Automation framework using BDD syntax (Gherkin-like) for API testing, mocking, performance testing, and UI automation.
- **GitHub Repository**: [https://github.com/karatelabs/karate](https://github.com/karatelabs/karate)
- **Features**: BDD syntax, multi-protocol support (REST, SOAP, GraphQL), built-in mocking, reporting, parallel execution

### 43. [Tavern](https://taverntesting.github.io/)
Pytest plugin for automated RESTful API testing, using a declarative YAML syntax.
- **GitHub Repository**: [https://github.com/taverntesting/tavern](https://github.com/taverntesting/tavern)
- **Features**: YAML-based, pytest integration, response validation, MQTT/HTTP testing

### 44. [Venom](https://github.com/ovh/venom)
Manage and run integration tests (including API tests) defined in YAML.
- **GitHub Repository**: [https://github.com/ovh/venom](https://github.com/ovh/venom)
- **Features**: Multi-protocol testing (HTTP, gRPC, WebSockets, DB, etc.), CI integration, extensible, test suites

### 45. [pyresttest](https://github.com/svanoort/pyresttest)
Simple REST API testing and microbenchmarking tool based on YAML or JSON configuration files.
- **GitHub Repository**: [https://github.com/svanoort/pyresttest](https://github.com/svanoort/pyresttest)
- **Features**: Python-based, benchmarking, validation, generators, extractors

### 46. [runn](https://github.com/k1LoW/runn)
Tool for running operations (API calls, DB queries, commands) following a scenario defined in YAML.
- **GitHub Repository**: [https://github.com/k1LoW/runn](https://github.com/k1LoW/runn)
- **Features**: Scenario-based testing (YAML), multi-protocol support (HTTP, gRPC, DB), debugging features

### 47. [scenarigo](https://github.com/zoncoen/scenarigo)
End-to-end scenario testing tool for HTTP/gRPC services, using YAML definitions.
- **GitHub Repository**: [https://github.com/zoncoen/scenarigo](https://github.com/zoncoen/scenarigo)
- **Features**: Scenario-based (YAML), gRPC support, extensibility (Go plugins), data-driven testing

### 48. [Schemathesis](https://schemathesis.readthedocs.io/)
Property-based testing tool for web APIs built with OpenAPI / Swagger specifications. Generates test cases based on the schema.
- **GitHub Repository**: [https://github.com/schemathesis/schemathesis](https://github.com/schemathesis/schemathesis)
- **Features**: Schema-based testing (OpenAPI, GraphQL), fuzzing, property-based testing, finds edge cases

### 49. [Dredd](https://dredd.org/)
Language-agnostic HTTP API Testing Tool that validates API description documents (OpenAPI, API Blueprint) against backend implementation.
- **GitHub Repository**: [https://github.com/apiaryio/dredd](https://github.com/apiaryio/dredd)
- **Features**: API description validation, hooks (various languages), CI integration, reporting

### 50. [abao](https://github.com/cybertk/abao)
REST API automated testing tool based on API Blueprint or RAML. (Note: Less active recently).
- **GitHub Repository**: [https://github.com/cybertk/abao](https://github.com/cybertk/abao)
- **Features**: API Blueprint/RAML-based, assertions, hooks for customization

### 51. [HttpRunner](https://httprunner.com/)
One-stop solution for HTTP(S) API testing, supporting YAML/JSON testcases, written in Go.
- **GitHub Repository**: [https://github.com/httprunner/httprunner](https://github.com/httprunner/httprunner)
- **Features**: Record and replay (HAR), multiple protocols, flexible testcase formats, reporting, plugin support

### 52. [k6](https://k6.io/)
Modern load testing tool using Go and JavaScript for writing test scripts. Developed by Grafana Labs.
- **GitHub Repository**: [https://github.com/grafana/k6](https://github.com/grafana/k6)
- **Features**: Load testing, performance metrics, JavaScript scripting, goal-oriented, extensibility, Grafana integration

### 53. [Artillery](https://www.artillery.io/)
Modern load testing and API testing platform, using YAML or JavaScript for defining scenarios.
- **GitHub Repository**: [https://github.com/artilleryio/artillery](https://github.com/artilleryio/artillery)
- **Features**: Load testing, scenario-based, multiple protocols (HTTP, WebSockets, Socket.IO), cloud execution, reporting

### 54. [Playwright](https://playwright.dev/docs/api-testing)
While primarily for E2E browser automation, Playwright includes powerful and convenient API testing capabilities within its framework.
- **GitHub Repository**: [https://github.com/microsoft/playwright](https://github.com/microsoft/playwright)
- **Features**: Integrated API testing (`request` context), shared context/auth with browser tests, multi-language support (TS/JS, Python, Java, .NET)

### 55. [Pact](https://pact.io/)
Enables consumer-driven contract testing, ensuring services (e.g., a frontend and a backend API) can communicate correctly.
- **GitHub Repository**: [https://github.com/pact-foundation](https://github.com/pact-foundation) (Organization)
- **Features**: Contract testing, prevents integration issues, language-agnostic (Pact Specification), Pact Broker for sharing contracts

## API Design & Documentation Tools

### 56. [Swagger Editor](https://editor.swagger.io/)
Browser-based editor for designing and documenting APIs with the OpenAPI Specification.
- **GitHub Repository**: [https://github.com/swagger-api/swagger-editor](https://github.com/swagger-api/swagger-editor)
- **Features**: OpenAPI design (YAML/JSON), validation, real-time preview (Swagger UI), code generation options

### 57. [Stoplight Studio](https://stoplight.io/studio/)
Visual OpenAPI and JSON Schema designer with mocking, documentation generation, and Git integration. (Free desktop app, cloud features are paid).
- **GitHub Repository**: [https://github.com/stoplightio/studio](https://github.com/stoplightio/studio) (Issue Tracking/Docs)
- **Features**: Visual design (OpenAPI), form-based editing, mocking, documentation generation (uses Elements), Git sync

## Specialized API Clients (GraphQL, gRPC, WebSocket)

### 58. [Altair GraphQL Client](https://altair.sirmuel.design/)
Feature-rich GraphQL Client available for Web, Desktop (Windows, Mac, Linux), and IDE Extensions (VS Code, Chrome, Firefox).
- **GitHub Repository**: [https://github.com/altair-graphql/altair](https://github.com/altair-graphql/altair)
- **Features**: GraphQL focused, query autocompletion, documentation explorer, file uploads, subscriptions, environments

### 59. [gRPC UI](https://github.com/fullstorydev/grpcui)
An interactive web UI for gRPC, often used alongside `grpcurl`. Provides a GUI for exploring and invoking gRPC methods.
- **GitHub Repository**: [https://github.com/fullstorydev/grpcui](https://github.com/fullstorydev/grpcui)
- **Features**: gRPC Web UI, interacts with reflection-enabled servers, method invocation, metadata support

### 60. [grpcurl](https://github.com/fullstorydev/grpcurl)
Command-line tool (like cURL) for interacting with gRPC servers.
- **GitHub Repository**: [https://github.com/fullstorydev/grpcurl](https://github.com/fullstorydev/grpcurl)
- **Features**: gRPC CLI testing, reflection support, TLS configuration, various output formats

### 61. [Kreya](https://kreya.app/)
Feature-rich gRPC, REST and Identity client with a focus on developer experience and file-based configuration.
- **GitHub Repository**: N/A (Proprietary, free tier available)
- **Features**: gRPC (including streaming), REST, OpenAPI import, templating, authentication helpers, environments

### 62. [Wombat](https://github.com/rogchap/wombat)
Cross-platform gRPC client GUI built with Wails (Go + Svelte).
- **GitHub Repository**: [https://github.com/rogchap/wombat](https://github.com/rogchap/wombat)
- **Features**: gRPC client, cross-platform, reflection support, unary & streaming calls

### 63. [ezy](https://ezy.demo.dofr.dev/)
GUI client specifically for gRPC/gRPC-Web services.
- **GitHub Repository**: [https://github.com/dofazed/ezy](https://github.com/dofazed/ezy)
- **Features**: gRPC/gRPC-Web focused, streaming support, schema generation, reflection

### 64. [BloomRPC](https://github.com/bloomrpc/bloomrpc)
GUI Client for gRPC services. (Note: Unmaintained since late 2021, but still functional for many).
- **GitHub Repository**: [https://github.com/bloomrpc/bloomrpc](https://github.com/bloomrpc/bloomrpc)
- **Features**: gRPC GUI, proto parsing, metadata, streaming support

### 65. [evans](https://evans.syfm.me/)
More expressive universal gRPC client with REPL (Read-Eval-Print Loop) capabilities.
- **GitHub Repository**: [https://github.com/ktr0731/evans](https://github.com/ktr0731/evans)
- **Features**: gRPC CLI & REPL, reflection support, interactive mode, auto-completion

### 66. [WebSocket King](https://websocketking.com/)
Simple WebSocket GUI Client for testing and debugging WebSockets.
- **GitHub Repository**: [https://github.com/AppDoctorIo/WebSocketKing](https://github.com/AppDoctorIo/WebSocketKing) (Landing page repo)
- **Features**: WebSocket client, message history, connection management

## Proxy & Interception Tools

### 67. [mitmproxy](https://mitmproxy.org/)
An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers. Available as CLI (`mitmproxy`), Web UI (`mitmweb`), and Python library.
- **GitHub Repository**: [https://github.com/mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy)
- **Features**: HTTP/S interception, modification, replay, scripting (Python), various modes (proxy, reverse proxy, etc.)

### 68. [Caido](https://caido.io/) (See Web-Based)
Also functions as a powerful desktop proxy and interception tool.

### 69. [Requestly](https://requestly.io/) (See Web-Based / Desktop)
Core feature includes network interception and modification.

## Language-Specific API Testing Libraries

### 70. [REST Assured](https://rest-assured.io/)
Java DSL (Domain Specific Language) for easy testing of REST services.
- **GitHub Repository**: [https://github.com/rest-assured/rest-assured](https://github.com/rest-assured/rest-assured)
- **Features**: Fluent Java API, BDD syntax (Given/When/Then), validation, XPath/JSONPath support

### 71. [Frisby.js](https://www.frisbyjs.com/)
REST API testing framework built on Node.js and Jest (or Jasmine BDD). Aims for easy, fast, and reliable tests.
- **GitHub Repository**: [https://github.com/vlucas/frisby](https://github.com/vlucas/frisby)
- **Features**: Node.js based, Jest integration, BDD syntax, built-in matchers, easy setup

### 72. [Chakram](https://github.com/dareid/chakram)
REST API testing framework using node.js, mocha, chai, and superagent, supporting BDD and promises. (Note: Less active recently).
- **GitHub Repository**: [https://github.com/dareid/chakram](https://github.com/dareid/chakram)
- **Features**: Node.js based, BDD syntax (expect), promise-based, hooks

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

1. Fork it (`https://github.com/YOUR_USERNAME/awesome-api-clients/fork`)
2. Create your feature branch (`git checkout -b feature/add-amazing-client`)
3. Commit your changes (`git commit -am 'Add some amazing client'`)
4. Push to the branch (`git push origin feature/add-amazing-client`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details (or assume MIT if no file present yet).

---

⭐ If you find this repository helpful, please consider giving it a star! ⭐

```

It seems I encountered an error trying to edit the `Untitled-1` file directly, possibly because it's read-only or doesn't exist in a writable location.

Instead, here is the complete merged and updated markdown content. You can copy and paste this into your file:

```markdown
# Awesome API Clients & Postman/Insomnia Alternatives

A curated list of awesome **API Clients**, including the best **Postman Alternatives** and **Insomnia Alternatives** for API development, testing, documentation, and more. This repository aims to provide developers with a comprehensive overview of available API client tools, focusing on open-source and actively maintained projects where possible.

*Criteria: Generally open-source (unless specified), popular (e.g., >200 stars, >2 contributors if OS), and actively maintained where possible.*

## Keywords

API Clients, Postman Alternative, Insomnia Alternative, REST Client, GraphQL Client, gRPC Client, API Testing, API Development Tools, HTTP Client, API Debugging, API Documentation

## Contents
- [Overall Best Postman Alternative](#overall-best-postman-alternative)
- [Web-Based API Clients](#web-based-api-clients)
- [Desktop API Clients](#desktop-api-clients)
- [IDE Extensions](#ide-extensions)
- [CLI Tools](#cli-tools)
- [Automated API Testing & Load Testing Tools](#automated-api-testing--load-testing-tools)
- [API Design & Documentation Tools](#api-design--documentation-tools)
- [Specialized API Clients (GraphQL, gRPC, WebSocket)](#specialized-api-clients-graphql-grpc-websocket)
- [Proxy & Interception Tools](#proxy--interception-tools)
- [Language-Specific API Testing Libraries](#language-specific-api-testing-libraries)
- [Contributing](#contributing)
- [License](#license)

## Overall Best Postman Alternative

### 1. [Apidog](https://apidog.com/)
A comprehensive API development platform that integrates API design, debugging, testing, and documentation in one place. (Note: Not open-source, but included by request).
- **GitHub Repository**: [https://github.com/Apidog](https://github.com/Apidog) (Organization)
- **Features**: API design, debugging, mock services, automated testing, team collaboration, OpenAPI support

[![image](https://github.com/user-attachments/assets/2feef159-8530-4e96-8e60-a9ce704328cd)](https://apidog.com)

## Web-Based API Clients

### 2. [Hoppscotch](https://hoppscotch.io/)
Open source API development ecosystem (formerly Postwoman). Lightweight, web-based API client with a clean UI.
- **GitHub Repository**: [https://github.com/hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch)
- **Features**: REST, GraphQL, WebSockets, SSE, MQTT, Socket.IO, Server Sent Events

### 3. [Restfox](https://restfox.dev/)
Offline-first web HTTP client focused on privacy and simplicity.
- **GitHub Repository**: [https://github.com/flawiddsouza/Restfox](https://github.com/flawiddsouza/Restfox)
- **Features**: Offline-first, collections, environment variables, code generation

### 4. [Firecamp](https://firecamp.io/)
Open-source Postman alternative designed for collaborative API development, inspired by VS Code DX.
- **GitHub Repository**: [https://github.com/firecamp-dev/firecamp](https://github.com/firecamp-dev/firecamp)
- **Features**: Multi-protocol testing (REST, GraphQL, WebSockets, SocketIO, MQTT), collaborative workspaces

### 5. [RecipeUI](https://recipeui.com/)
A type-safe API client with automatic documentation generation.
- **GitHub Repository**: [https://github.com/RecipeUI/RecipeUI](https://github.com/RecipeUI/RecipeUI)
- **Features**: Type safety, automatic documentation, intuitive UI

### 6. [Yaade](https://yaade.io/)
Self-hosted, collaborative API development environment.
- **GitHub Repository**: [https://github.com/EsperoTech/yaade](https://github.com/EsperoTech/yaade)
- **Features**: Collaboration, self-hosted, environment variables, auth support

### 7. [Prestige](https://prestige.dev/)
Text-based in-browser HTTP client without UI clutter. An interface-less Postman alternative.
- **GitHub Repository**: [https://github.com/prestigejs/prestige](https://github.com/prestigejs/prestige)
- **Features**: Markdown-like syntax, simple interface, code generation

### 8. [Requestly](https://requestly.io/)
Browser extension and Desktop App with API Client, API Mocking & API Interception and Modification capabilities.
- **GitHub Repository**: [https://github.com/requestly/requestly](https://github.com/requestly/requestly)
- **Features**: API client, mocking, request interception, debugging, collaboration

### 9. [Testfully](https://testfully.io/)
Cloud-based API testing platform with collaboration features.
- **GitHub Repository**: [https://github.com/testfully/testfully](https://github.com/testfully/testfully) (Website/Docs Repo)
- **Features**: Automated testing, monitoring, team collaboration

### 10. [HTTPBox](https://httpbox.io)
In-browser collaborative REST API client.
- **GitHub Repository**: [https://github.com/httpbox/httpbox](https://github.com/httpbox/httpbox)
- **Features**: Real-time collaboration, request history, response visualization

### 11. [Caido](https://caido.io/)
Lightweight web security auditing toolkit including HTTP proxy and replay capabilities. (Free tier available, not fully OS).
- **Features**: HTTP Proxy, Replay, Intruder-like features, Scripting

## Desktop API Clients

### 12. [Bruno](https://www.usebruno.com/)
Git-friendly, open-source API client (IDE) with collections stored as files.
- **GitHub Repository**: [https://github.com/usebruno/bruno](https://github.com/usebruno/bruno)
- **Features**: Git integration, file-based collections (Bru Lang), offline-first, scripting

### 13. [Insomnia](https://insomnia.rest/)
Popular desktop API client with REST, GraphQL, gRPC, SOAP, and WebSockets support.
- **GitHub Repository**: [https://github.com/Kong/insomnia](https://github.com/Kong/insomnia)
- **Features**: Plugin ecosystem, design tools (OpenAPI), Git sync, testing, environment variables

### 14. [Insomnium](https://insomnium.rest/)
Privacy-focused fork of Insomnia without telemetry or account requirements. (Note: Development seems stalled/unmaintained as of late 2023).
- **GitHub Repository**: [https://github.com/ArchGPT/insomnium](https://github.com/ArchGPT/insomnium)
- **Features**: Privacy-focused, no telemetry, local storage, based on Insomnia core

### 15. [Yaak](https://yaak.app/)
Intuitive desktop API client focused on user experience.
- **GitHub Repository**: [https://github.com/raiyanyahya/yaak](https://github.com/raiyanyahya/yaak)
- **Features**: Clean UI, multi-protocol support (REST, GraphQL, gRPC), easy environment management

### 16. [API Dash](https://apidash.dev/)
Cross-platform, beautiful open-source API client with advanced features.
- **GitHub Repository**: [https://github.com/foss42/apidash](https://github.com/foss42/apidash) (Corrected Repo Link)
- **Features**: Cross-platform (Flutter-based), OAuth support, request chaining, code generation

### 17. [Pororoca](https://pororoca.io/)
HTTP inspection tool with HTTP/2 and HTTP/3 support.
- **GitHub Repository**: [https://github.com/alexandrehtrb/Pororoca](https://github.com/alexandrehtrb/Pororoca)
- **Features**: HTTP/2, HTTP/3 support, clean interface, Windows focus

### 18. [Nightingale REST Client](https://nightingale.rest/)
Modern, open-source, resource-efficient REST API client for Windows.
- **GitHub Repository**: [https://github.com/jenius-apps/nightingale-rest-api-client](https://github.com/jenius-apps/nightingale-rest-api-client)
- **Features**: Resource efficiency, Windows-optimized (UWP), collection management, Fluent design

### 19. [Milkman](https://github.com/warmuuh/milkman)
Extensible request/response workbench with plugin support.
- **GitHub Repository**: [https://github.com/warmuuh/milkman](https://github.com/warmuuh/milkman)
- **Features**: Plugin ecosystem (SQL, gRPC, WebSockets), extensibility, environment management

### 20. [Requestly](https://requestly.io/desktop/)
Desktop app version of Requestly (see Web-Based).
- **GitHub Repository**: [https://github.com/requestly/requestly](https://github.com/requestly/requestly)
- **Features**: API client, mocking, request interception, modification, collaboration

## IDE Extensions

### 21. [Thunder Client](https://www.thunderclient.com/)
Lightweight VS Code extension with GUI for API testing.
- **GitHub Repository**: [https://github.com/rangav/thunder-client-support](https://github.com/rangav/thunder-client-support) (Support Repo)
- **Features**: VS Code integration, collections, environment variables, scripting, tests

### 22. [REST Client (Huachao)](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
Popular VS Code extension for sending HTTP requests using a simple plain text format (`.http` or `.rest` files).
- **GitHub Repository**: [https://github.com/Huachao/vscode-restclient](https://github.com/Huachao/vscode-restclient)
- **Features**: Plain text requests, response handling, environment variables, code snippets, GraphQL, cURL conversion

### 23. [HTTP Client (JetBrains)](https://www.jetbrains.com/help/idea/http-client-in-product-code-editor.html)
Built-in HTTP client in JetBrains IDEs (IntelliJ IDEA, WebStorm, PyCharm, etc.) using `.http` files.
- **GitHub Repository**: N/A (Part of IDEs like [https://github.com/JetBrains/intellij-community](https://github.com/JetBrains/intellij-community))
- **Features**: IntelliJ integration, request scripting (JavaScript), environment variables, response assertions, UI runner

### 24. [REST Client (Firefox Add-on)](https://addons.mozilla.org/en-US/firefox/addon/restclient/)
Firefox debugger/client for RESTful web services.
- **GitHub Repository**: [https://github.com/chao/RESTClient](https://github.com/chao/RESTClient)
- **Features**: Firefox integration, request history, response formatting, authentication support

### 25. [Restclient.el](https://github.com/pashky/restclient.el)
HTTP REST client tool for Emacs using a plain text format similar to Org mode.
- **GitHub Repository**: [https://github.com/pashky/restclient.el](https://github.com/pashky/restclient.el)
- **Features**: Emacs integration, plain text format, syntax highlighting, variable substitution

### 26. [Verb](https://github.com/federicotdn/verb)
Organize and send HTTP requests from Emacs, often used with Org mode.
- **GitHub Repository**: [https://github.com/federicotdn/verb](https://github.com/federicotdn/verb)
- **Features**: Emacs integration, org-mode support, templating, environment management

### 27. [Rest.nvim](https://github.com/rest-nvim/rest.nvim)
A fast Neovim HTTP client written in Lua, using `.http` file format.
- **GitHub Repository**: [https://github.com/rest-nvim/rest.nvim](https://github.com/rest-nvim/rest.nvim)
- **Features**: Neovim integration, syntax highlighting, response preview, environment variables

### 28. [kulala.nvim](https://github.com/akshayKrSingh/kulala.nvim)
Minimal REST-Client interface for Neovim.
- **GitHub Repository**: [https://github.com/akshayKrSingh/kulala.nvim](https://github.com/akshayKrSingh/kulala.nvim)
- **Features**: Lightweight, Neovim integration, simple setup

## CLI Tools

### 29. [curl](https://curl.se/)
The ubiquitous command line tool and library for transferring data with URLs (since 1998). The foundation for many others.
- **GitHub Repository**: [https://github.com/curl/curl](https://github.com/curl/curl)
- **Features**: Universal support, extensive protocol support, robust options, scripting essential

### 30. [HTTPie](https://httpie.io/)
Human-friendly command-line HTTP client for the API era. Designed for intuitive syntax and formatted output.
- **GitHub Repository**: [https://github.com/httpie/httpie](https://github.com/httpie/httpie)
- **Features**: User-friendly syntax, JSON formatting & highlighting, plugin support, sessions

### 31. [xh](https://github.com/ducaale/xh)
Friendly and fast tool for sending HTTP requests, aiming for HTTPie compatibility with Rust performance.
- **GitHub Repository**: [https://github.com/ducaale/xh](https://github.com/ducaale/xh)
- **Features**: Rust-based performance, HTTPie-like syntax, JSON formatting, download resumption

### 32. [curlie](https://github.com/rs/curlie)
Combines the power and features of curl with the ease of use (syntax, output formatting) of HTTPie.
- **GitHub Repository**: [https://github.com/rs/curlie](https://github.com/rs/curlie)
- **Features**: Curl compatibility, improved output formatting & highlighting

### 33. [posting](https://github.com/barthap/posting)
Terminal-based API client with an intuitive TUI (Text User Interface).
- **GitHub Repository**: [https://github.com/barthap/posting](https://github.com/barthap/posting)
- **Features**: TUI interface, collections, environment variables, history

### 34. [Wuzz](https://github.com/asciimoo/wuzz)
Interactive command-line HTTP inspection tool with a TUI.
- **GitHub Repository**: [https://github.com/asciimoo/wuzz](https://github.com/asciimoo/wuzz)
- **Features**: TUI interface, live inspection, keyboard shortcuts, request modification

### 35. [HttpRepl](https://docs.microsoft.com/en-us/aspnet/core/web-api/http-repl/)
.NET command-line tool for exploring and testing HTTP APIs, allows navigating API structure.
- **GitHub Repository**: [https://github.com/dotnet/HttpRepl](https://github.com/dotnet/HttpRepl)
- **Features**: .NET integration, interactive navigation (`cd`, `ls`), OpenAPI integration, autocomplete

### 36. [ain](https://github.com/jonaslu/ain)
HTTP API client for the terminal that acts as a wrapper around curl, wget or httpie.
- **GitHub Repository**: [https://github.com/jonaslu/ain](https://github.com/jonaslu/ain)
- **Features**: Multiple backend support, simple configuration, scripting

### 37. [httpYac](https://httpyac.com/)
Command-line tool and library using the `.http` file format (like VS Code REST Client / JetBrains HTTP Client).
- **GitHub Repository**: [https://github.com/AnWeber/httpyac](https://github.com/AnWeber/httpyac)
- **Features**: Multi-protocol support (REST, SOAP, GraphQL, gRPC, WebSockets), variables, pre/post request scripts, CLI & JS API

### 38. [ATAC](https://github.com/daveshanley/atac)
Simple Postman-like API client for the terminal, using a TUI.
- **GitHub Repository**: [https://github.com/daveshanley/atac](https://github.com/daveshanley/atac)
- **Features**: Terminal UI, collections, environment support, runs `.atac` files

### 39. [Newman](https://github.com/postmanlabs/newman)
Command-line collection runner for Postman. Allows running Postman collections (`.json` export) in CI/CD pipelines.
- **GitHub Repository**: [https://github.com/postmanlabs/newman](https://github.com/postmanlabs/newman)
- **Features**: Runs Postman collections, CI/CD integration, reporting options

## Automated API Testing & Load Testing Tools

### 40. [Step CI](https://stepci.com/)
Open-source API Test Automation framework focusing on declarative testing using YAML.
- **GitHub Repository**: [https://github.com/stepci/stepci](https://github.com/stepci/stepci)
- **Features**: Declarative testing (YAML), CI integration, monitoring, response validation

### 41. [Hurl](https://hurl.dev/)
Run and test HTTP requests defined in a simple plain text format (`.hurl` files). Uses libcurl.
- **GitHub Repository**: [https://github.com/Orange-OpenSource/hurl](https://github.com/Orange-OpenSource/hurl)
- **Features**: Plain text format, assertions, chaining requests, capturing values, CI integration

### 42. [Karate](https://github.com/karatelabs/karate)
Test Automation framework using BDD syntax (Gherkin-like) for API testing, mocking, performance testing, and UI automation.
- **GitHub Repository**: [https://github.com/karatelabs/karate](https://github.com/karatelabs/karate)
- **Features**: BDD syntax, multi-protocol support (REST, SOAP, GraphQL), built-in mocking, reporting, parallel execution

### 43. [Tavern](https://taverntesting.github.io/)
Pytest plugin for automated RESTful API testing, using a declarative YAML syntax.
- **GitHub Repository**: [https://github.com/taverntesting/tavern](https://github.com/taverntesting/tavern)
- **Features**: YAML-based, pytest integration, response validation, MQTT/HTTP testing

### 44. [Venom](https://github.com/ovh/venom)
Manage and run integration tests (including API tests) defined in YAML.
- **GitHub Repository**: [https://github.com/ovh/venom](https://github.com/ovh/venom)
- **Features**: Multi-protocol testing (HTTP, gRPC, WebSockets, DB, etc.), CI integration, extensible, test suites

### 45. [pyresttest](https://github.com/svanoort/pyresttest)
Simple REST API testing and microbenchmarking tool based on YAML or JSON configuration files.
- **GitHub Repository**: [https://github.com/svanoort/pyresttest](https://github.com/svanoort/pyresttest)
- **Features**: Python-based, benchmarking, validation, generators, extractors

### 46. [runn](https://github.com/k1LoW/runn)
Tool for running operations (API calls, DB queries, commands) following a scenario defined in YAML.
- **GitHub Repository**: [https://github.com/k1LoW/runn](https://github.com/k1LoW/runn)
- **Features**: Scenario-based testing (YAML), multi-protocol support (HTTP, gRPC, DB), debugging features

### 47. [scenarigo](https://github.com/zoncoen/scenarigo)
End-to-end scenario testing tool for HTTP/gRPC services, using YAML definitions.
- **GitHub Repository**: [https://github.com/zoncoen/scenarigo](https://github.com/zoncoen/scenarigo)
- **Features**: Scenario-based (YAML), gRPC support, extensibility (Go plugins), data-driven testing

### 48. [Schemathesis](https://schemathesis.readthedocs.io/)
Property-based testing tool for web APIs built with OpenAPI / Swagger specifications. Generates test cases based on the schema.
- **GitHub Repository**: [https://github.com/schemathesis/schemathesis](https://github.com/schemathesis/schemathesis)
- **Features**: Schema-based testing (OpenAPI, GraphQL), fuzzing, property-based testing, finds edge cases

### 49. [Dredd](https://dredd.org/)
Language-agnostic HTTP API Testing Tool that validates API description documents (OpenAPI, API Blueprint) against backend implementation.
- **GitHub Repository**: [https://github.com/apiaryio/dredd](https://github.com/apiaryio/dredd)
- **Features**: API description validation, hooks (various languages), CI integration, reporting

### 50. [abao](https://github.com/cybertk/abao)
REST API automated testing tool based on API Blueprint or RAML. (Note: Less active recently).
- **GitHub Repository**: [https://github.com/cybertk/abao](https://github.com/cybertk/abao)
- **Features**: API Blueprint/RAML-based, assertions, hooks for customization

### 51. [HttpRunner](https://httprunner.com/)
One-stop solution for HTTP(S) API testing, supporting YAML/JSON testcases, written in Go.
- **GitHub Repository**: [https://github.com/httprunner/httprunner](https://github.com/httprunner/httprunner)
- **Features**: Record and replay (HAR), multiple protocols, flexible testcase formats, reporting, plugin support

### 52. [k6](https://k6.io/)
Modern load testing tool using Go and JavaScript for writing test scripts. Developed by Grafana Labs.
- **GitHub Repository**: [https://github.com/grafana/k6](https://github.com/grafana/k6)
- **Features**: Load testing, performance metrics, JavaScript scripting, goal-oriented, extensibility, Grafana integration

### 53. [Artillery](https://www.artillery.io/)
Modern load testing and API testing platform, using YAML or JavaScript for defining scenarios.
- **GitHub Repository**: [https://github.com/artilleryio/artillery](https://github.com/artilleryio/artillery)
- **Features**: Load testing, scenario-based, multiple protocols (HTTP, WebSockets, Socket.IO), cloud execution, reporting

### 54. [Playwright](https://playwright.dev/docs/api-testing)
While primarily for E2E browser automation, Playwright includes powerful and convenient API testing capabilities within its framework.
- **GitHub Repository**: [https://github.com/microsoft/playwright](https://github.com/microsoft/playwright)
- **Features**: Integrated API testing (`request` context), shared context/auth with browser tests, multi-language support (TS/JS, Python, Java, .NET)

### 55. [Pact](https://pact.io/)
Enables consumer-driven contract testing, ensuring services (e.g., a frontend and a backend API) can communicate correctly.
- **GitHub Repository**: [https://github.com/pact-foundation](https://github.com/pact-foundation) (Organization)
- **Features**: Contract testing, prevents integration issues, language-agnostic (Pact Specification), Pact Broker for sharing contracts

## API Design & Documentation Tools

### 56. [Swagger Editor](https://editor.swagger.io/)
Browser-based editor for designing and documenting APIs with the OpenAPI Specification.
- **GitHub Repository**: [https://github.com/swagger-api/swagger-editor](https://github.com/swagger-api/swagger-editor)
- **Features**: OpenAPI design (YAML/JSON), validation, real-time preview (Swagger UI), code generation options

### 57. [Stoplight Studio](https://stoplight.io/studio/)
Visual OpenAPI and JSON Schema designer with mocking, documentation generation, and Git integration. (Free desktop app, cloud features are paid).
- **GitHub Repository**: [https://github.com/stoplightio/studio](https://github.com/stoplightio/studio) (Issue Tracking/Docs)
- **Features**: Visual design (OpenAPI), form-based editing, mocking, documentation generation (uses Elements), Git sync

## Specialized API Clients (GraphQL, gRPC, WebSocket)

### 58. [Altair GraphQL Client](https://altair.sirmuel.design/)
Feature-rich GraphQL Client available for Web, Desktop (Windows, Mac, Linux), and IDE Extensions (VS Code, Chrome, Firefox).
- **GitHub Repository**: [https://github.com/altair-graphql/altair](https://github.com/altair-graphql/altair)
- **Features**: GraphQL focused, query autocompletion, documentation explorer, file uploads, subscriptions, environments

### 59. [gRPC UI](https://github.com/fullstorydev/grpcui)
An interactive web UI for gRPC, often used alongside `grpcurl`. Provides a GUI for exploring and invoking gRPC methods.
- **GitHub Repository**: [https://github.com/fullstorydev/grpcui](https://github.com/fullstorydev/grpcui)
- **Features**: gRPC Web UI, interacts with reflection-enabled servers, method invocation, metadata support

### 60. [grpcurl](https://github.com/fullstorydev/grpcurl)
Command-line tool (like cURL) for interacting with gRPC servers.
- **GitHub Repository**: [https://github.com/fullstorydev/grpcurl](https://github.com/fullstorydev/grpcurl)
- **Features**: gRPC CLI testing, reflection support, TLS configuration, various output formats

### 61. [Kreya](https://kreya.app/)
Feature-rich gRPC, REST and Identity client with a focus on developer experience and file-based configuration.
- **GitHub Repository**: N/A (Proprietary, free tier available)
- **Features**: gRPC (including streaming), REST, OpenAPI import, templating, authentication helpers, environments

### 62. [Wombat](https://github.com/rogchap/wombat)
Cross-platform gRPC client GUI built with Wails (Go + Svelte).
- **GitHub Repository**: [https://github.com/rogchap/wombat](https://github.com/rogchap/wombat)
- **Features**: gRPC client, cross-platform, reflection support, unary & streaming calls

### 63. [ezy](https://ezy.demo.dofr.dev/)
GUI client specifically for gRPC/gRPC-Web services.
- **GitHub Repository**: [https://github.com/dofazed/ezy](https://github.com/dofazed/ezy)
- **Features**: gRPC/gRPC-Web focused, streaming support, schema generation, reflection

### 64. [BloomRPC](https://github.com/bloomrpc/bloomrpc)
GUI Client for gRPC services. (Note: Unmaintained since late 2021, but still functional for many).
- **GitHub Repository**: [https://github.com/bloomrpc/bloomrpc](https://github.com/bloomrpc/bloomrpc)
- **Features**: gRPC GUI, proto parsing, metadata, streaming support

### 65. [evans](https://evans.syfm.me/)
More expressive universal gRPC client with REPL (Read-Eval-Print Loop) capabilities.
- **GitHub Repository**: [https://github.com/ktr0731/evans](https://github.com/ktr0731/evans)
- **Features**: gRPC CLI & REPL, reflection support, interactive mode, auto-completion

### 66. [WebSocket King](https://websocketking.com/)
Simple WebSocket GUI Client for testing and debugging WebSockets.
- **GitHub Repository**: [https://github.com/AppDoctorIo/WebSocketKing](https://github.com/AppDoctorIo/WebSocketKing) (Landing page repo)
- **Features**: WebSocket client, message history, connection management

## Proxy & Interception Tools

### 67. [mitmproxy](https://mitmproxy.org/)
An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers. Available as CLI (`mitmproxy`), Web UI (`mitmweb`), and Python library.
- **GitHub Repository**: [https://github.com/mitmproxy/mitmproxy](https://github.com/mitmproxy/mitmproxy)
- **Features**: HTTP/S interception, modification, replay, scripting (Python), various modes (proxy, reverse proxy, etc.)

### 68. [Caido](https://caido.io/) (See Web-Based)
Also functions as a powerful desktop proxy and interception tool.

### 69. [Requestly](https://requestly.io/) (See Web-Based / Desktop)
Core feature includes network interception and modification.

## Language-Specific API Testing Libraries

### 70. [REST Assured](https://rest-assured.io/)
Java DSL (Domain Specific Language) for easy testing of REST services.
- **GitHub Repository**: [https://github.com/rest-assured/rest-assured](https://github.com/rest-assured/rest-assured)
- **Features**: Fluent Java API, BDD syntax (Given/When/Then), validation, XPath/JSONPath support

### 71. [Frisby.js](https://www.frisbyjs.com/)
REST API testing framework built on Node.js and Jest (or Jasmine BDD). Aims for easy, fast, and reliable tests.
- **GitHub Repository**: [https://github.com/vlucas/frisby](https://github.com/vlucas/frisby)
- **Features**: Node.js based, Jest integration, BDD syntax, built-in matchers, easy setup

### 72. [Chakram](https://github.com/dareid/chakram)
REST API testing framework using node.js, mocha, chai, and superagent, supporting BDD and promises. (Note: Less active recently).
- **GitHub Repository**: [https://github.com/dareid/chakram](https://github.com/dareid/chakram)
- **Features**: Node.js based, BDD syntax (expect), promise-based, hooks

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.

1. Fork it (`https://github.com/YOUR_USERNAME/awesome-api-clients/fork`)
2. Create your feature branch (`git checkout -b feature/add-amazing-client`)
3. Commit your changes (`git commit -am 'Add some amazing client'`)
4. Push to the branch (`git push origin feature/add-amazing-client`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details (or assume MIT if no file present yet).

---

⭐ If you find this repository helpful, please consider giving it a star! ⭐
