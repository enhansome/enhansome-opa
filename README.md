# awesome-opa with stars

<img src="assets/awesome-opa.png" width="150"><br/><br/>

A curated list of [awesome](https://github.com/sindresorhus/awesome) ⭐ 495,606 | 🐛 100 | 📅 2026-06-30 Open Policy Agent (OPA) related tools, frameworks and articles.

## Contents

* [Official Projects](#official-projects)
  * [Repositories](#repositories)
  * [Docs](#docs)
  * [Blogs and Articles](#blogs-and-articles)
* [Policy Packages](#policy-packages)
* [Language and Platform Integrations](#language-and-platform-integrations)
  * [Java](#java)
  * [Python](#python)
  * [Go](#go)
  * [PHP](#php)
  * [.NET](#net)
  * [Node.js](#nodejs)
  * [Clojure](#clojure)
  * [Docker](#docker)
  * [CPP](#cpp)
  * [Rust](#rust)
  * [Swift](#swift)
  * [Typescript](#typescript)
* [WebAssembly (Wasm)](#webassembly-wasm)
  * [Blogs and Articles](#webassembly-blogs-and-articles)
* [Kubernetes](#kubernetes)
  * [Service Mesh Authorization](#service-mesh-authorization)
  * [Blogs and Articles](#blogs-and-articles)
* [Nomad](#nomad)
* [Datasource Integrations](#datasource-integrations)
  * [Blogs and Articles](#datasource-integrations-blogs-and-articles)
* [IDE and Editor Integrations](#ide-and-editor-integrations)
* [Infrastructure as Code](#infrastructure-as-code)
  * [Blogs and Articles](#infrastructure-as-code-blogs-and-articles)
* [Serverless](#serverless)
  * [Blogs and Articles](#serverless-blogs-and-articles)
* [Testing](#testing)
  * [Blogs and Articles](#testing-blogs-and-articles)
* [Tools and Utilities](#tools-and-utilities)
* [Other Usecases](#other-usecases)
* [Fun and Quirky](#fun-and-quirky)
* [Support and Community](#support-and-community)
* [Recommended Reading](#recommended-reading)
* [People](#people)
  * [Maintainers](#maintainers)
  * [Community Stars](#community-stars)
  * [Meetup Groups](#meetup-groups)
* [Commercial Tools](#commercial-tools)
* [Contributing](#contributing)

## Official projects

### Repositories

* [OPA](https://github.com/open-policy-agent/opa) ⭐ 12,099 | 🐛 346 | 🌐 Go | 📅 2026-08-13 - Open Policy Agent Github repository
* [Gatekeeper](https://github.com/open-policy-agent/gatekeeper) ⭐ 4,263 | 🐛 172 | 🌐 Go | 📅 2026-08-10 - Kubernetes admission controller using OPA
* [Conftest](https://github.com/open-policy-agent/conftest) ⭐ 3,235 | 🐛 59 | 🌐 Go | 📅 2026-08-11 - Write tests against structured configuration data

### Docs

* [OPA](https://www.openpolicyagent.org/docs/) - Official OPA documentation
* [Gatekeeper](https://open-policy-agent.github.io/gatekeeper/website/docs/) - OPA Gatekeeper docs
* [Conftest](https://www.conftest.dev/) - Conftest documentation
* [Rego Style Guide](https://github.com/StyraOSS/rego-style-guide) ⭐ 205 | 🐛 5 | 📅 2026-06-18 - Style guide for Rego, providing pointers on best practices for policy authoring
* [Regal Docs](https://www.openpolicyagent.org/projects/regal) - Documentation for 60+ linter rules, providing an excellent reference for learning Rego

### Blogs and Articles

* [OPA](https://blog.openpolicyagent.org/) - Official blog for the OPA project
* [Logo](https://cncf-branding.netlify.app/projects/opa/) - The OPA Logo in different versions

## Policy Packages

* [Confectionary](https://github.com/Cigna/confectionery) ⭐ 193 | 🐛 0 | 🌐 Open Policy Agent | 📅 2022-09-20 - A library of rules for Conftest used to detect Terraform misconfigurations.
* [Kubernetes Security Policies](https://github.com/raspbernetes/k8s-security-policies) ⭐ 177 | 🐛 15 | 🌐 Open Policy Agent | 📅 2026-06-20 - Raspernetes library for fortifying cluster configurations
* [Rego policies](https://github.com/redhat-cop/rego-policies) ⭐ 171 | 🐛 11 | 🌐 Shell | 📅 2026-08-13 - Rego policies from the the Red Hat community of practice
* [Kubescape Rego library](https://github.com/kubescape/regolibrary) ⭐ 131 | 🐛 21 | 🌐 Open Policy Agent | 📅 2026-08-14 - Comprehensive set of Kubernetes policies from Kubescape
* [Appshield](https://github.com/aquasecurity/appshield) ⚠️ Archived - Open Database of rego policies for common Infrastructure as Code files
* [Library](https://github.com/open-policy-agent/library) ⭐ 105 | 🐛 3 | 🌐 Open Policy Agent | 📅 2023-10-16 - Community-owned policy library for OPA
* [Policy Hub CLI](https://github.com/policy-hub/policy-hub-cli) ⭐ 105 | 🐛 8 | 🌐 Go | 📅 2022-02-05 - CLI tool that makes Rego policies searchable
* [Conftest policy packs](https://github.com/rallyhealth/conftest-policy-packs) ⭐ 61 | 🐛 8 | 🌐 Open Policy Agent | 📅 2023-10-19 - Collection of Conftest policies for "Compliance-as-Code" security policies and general engineering standards. Policies targeting Terraform, Dockerfiles, package.json (NodeJS) files, etc
* [agt-policies-nigeria](https://github.com/kingztech2019/agt-policies-nigeria) ⭐ 5 | 🐛 0 | 🌐 Open Policy Agent | 📅 2026-07-04 - Policy-as-Code for African AI agent compliance: NDPA 2023, CBN transaction limits, BVN/NIN data protection, NFIU AML/CFT, and POPIA. Includes 88 OPA tests, CI pipeline, and full compliance mapping.

## Language and Platform Integrations

### Java

* [Jarl](https://github.com/johanfylling/jarl) ⭐ 43 | 🐛 25 | 🌐 Clojure | 📅 2024-02-01 - Native evaluation of Rego in the JVM, via OPA's IR format ([blog](https://blog.openpolicyagent.org/i-have-a-plan-exploring-the-opa-intermediate-representation-ir-format-7319cd94b37d))
* [OPA Java Client](https://github.com/Bisnode/opa-java-client) ⭐ 40 | 🐛 10 | 🌐 Java | 📅 2024-10-28 - Generic Java client to query OPA's REST API
* [Thunx](https://github.com/xenit-eu/thunx) ⭐ 40 | 🐛 1 | 🌐 Java | 📅 2026-07-29 - Thunx is a pluggable ABAC system using OPA, Spring Cloud Gateway and Spring Data REST
* [Spring Security](https://github.com/Bisnode/opa-spring-security) ⭐ 35 | 🐛 8 | 🌐 Java | 📅 2021-04-13 - OPA Spring Security Library
* [Spring Security Reactive](https://github.com/massenz/jwt-opa) ⭐ 35 | 🐛 14 | 🌐 Java | 📅 2023-11-01 - OPA with Spring Security Reactive
* [Java SDK](https://github.com/open-policy-agent/opa-java) ⭐ 25 | 🐛 10 | 🌐 Java | 📅 2026-06-16 - Java SDK for interacting with OPA ([documentation](https://open-policy-agent.github.io/opa-java/))
* [Gradle](https://github.com/Bisnode/opa-gradle-plugin) ⭐ 13 | 🐛 11 | 🌐 Java | 📅 2025-03-01 - OPA plugin for Gradle

### Python

* [regorus](https://github.com/microsoft/regorus/tree/main/bindings/python) ⭐ 337 | 🐛 59 | 🌐 Rust | 📅 2026-08-13 - Evaluate Rego policies in Python using Regorus, a fast, lightweight Rego interpreter written in Rust.
* [OPA Python client](https://github.com/Turall/OPA-python-client) ⭐ 65 | 🐛 0 | 🌐 Python | 📅 2026-06-25 - Python client for OPA's REST API
* [Rego Python](https://github.com/open-policy-agent/rego-python) ⭐ 59 | 🐛 1 | 🌐 Python | 📅 2021-07-15 - Python package for interacting with Rego
* [Flask OPA](https://github.com/EliuX/flask-opa) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2021-03-16 - OPA client for the Flask microframework
* [Sphinx Rego](https://github.com/zenitysec/sphinx-rego) ⚠️ Archived - Sphinx extension that automatically documents Rego policies
* [OPA Python](https://github.com/heliconhq/opa-python) ⭐ 5 | 🐛 4 | 🌐 Python | 📅 2022-12-14 - Python client library for Open Policy Agent
* [Bottle Authorization](https://github.com/dolevf/bottle-acl-openpolicyagent) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2021-07-06 - Custom Bottle Application Authorization
* [regopy](https://pypi.org/project/regopy/) - Python module which uses the C FFI for rego-cpp, allowing in-process Pythonic Rego policy evaluation

### Go

* [regorus](https://github.com/microsoft/regorus/tree/main/bindings/go) ⭐ 337 | 🐛 59 | 🌐 Rust | 📅 2026-08-13 - Golang bindings to Regorus, a fast, lightweight Rego interpreter written in Rust.
* [Fiber OPA Integration](https://github.com/gofiber/contrib/tree/main/opafiber) ⭐ 304 | 🐛 22 | 🌐 Go | 📅 2026-08-14 - OPA integration for Fiber web framework. Enables to execute Rego policies in the middlewares.
* [Go Example API Authorization](https://github.com/open-policy-agent/example-api-authz-go) ⭐ 101 | 🐛 1 | 🌐 Go | 📅 2024-03-06 - Example API authorization using OPA
* [HTTP API OPA middlewares](https://github.com/Joffref/opa-middleware) ⭐ 22 | 🐛 2 | 🌐 Go | 📅 2024-03-14 - Collection of OPA middlewares for your HTTP/Gin/Fiber API.

### PHP

* [OPA Library for PHP](https://github.com/segrax/openpolicyagent) ⭐ 21 | 🐛 0 | 🌐 PHP | 📅 2024-03-06 - OPA client, a PSR-15 authorization middleware and a PSR-15 bundle distributor middleware

### .NET

* [regorus](https://github.com/microsoft/regorus/tree/main/bindings/csharp) ⭐ 337 | 🐛 59 | 🌐 Rust | 📅 2026-08-13 - C# bindings to Regorus, a fast, lightweight Rego interpreter written in Rust.
* [C# SDK](https://github.com/open-policy-agent/opa-csharp) ⭐ 6 | 🐛 9 | 🌐 C# | 📅 2026-08-10 - C# SDK for interacting with OPA ([documentation](https://open-policy-agent.github.io/opa-csharp/))
* [OpaDotNet.Extensions.AspNetCore](https://github.com/me-viper/OpaDotNet.Extensions) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2025-03-13 - ASP.NET Core authorization infrastructure
* [ASP.NET Core](https://github.com/build-security/OPA-AspDotNetCore-Middleware) - ASP.NET Core authorization middleware

### Node.js

* [regorus](https://github.com/microsoft/regorus/tree/main/bindings/wasm) ⭐ 337 | 🐛 59 | 🌐 Rust | 📅 2026-08-13 - Evaluate Rego policies in WASM using Regorus. Try it out at [Regorus Playground](https://anakrish.github.io/regorus-playground/).

### Clojure

* [Jarl](https://github.com/johanfylling/jarl) ⭐ 43 | 🐛 25 | 🌐 Clojure | 📅 2024-02-01 - Native evaluation of Rego in the JVM (written in Clojure), via OPA's IR format ([blog](https://blog.openpolicyagent.org/i-have-a-plan-exploring-the-opa-intermediate-representation-ir-format-7319cd94b37d))
* [clj-opa](https://github.com/anderseknert/clj-opa) ⭐ 13 | 🐛 5 | 🌐 Clojure | 📅 2025-12-12 - Middleware and utilities for app authorization with OPA in Clojure

### Docker

* [Dockerfile security](https://github.com/gbrindisi/dockerfile-security) ⭐ 270 | 🐛 4 | 🌐 Open Policy Agent | 📅 2022-06-22 - A collection of OPA rules to statically analyze Dockerfiles to improve security
* [OPA Docker authorization](https://github.com/open-policy-agent/opa-docker-authz) ⭐ 104 | 🐛 19 | 🌐 Go | 📅 2026-06-25 - OPA to help policy-enable an existing services
* [Docker Security Checker](https://github.com/madhuakula/docker-security-checker) ⭐ 63 | 🐛 0 | 🌐 Open Policy Agent | 📅 2022-06-27 - OPA Rego policies for Dockerfile Security checks using Conftest

### Containers

* [Konveyor Forklift Validation Service](https://github.com/konveyor/forklift-validation) ⚠️ Archived - VM migration suitability assessment to avoid migrating VMs that are not fit for Kubevirt. Rules are applied on all the VMs of the source provider (VMware) during the initial inventory collection, then whenever a VM configuration changes.

### CPP

* [rego-cpp](https://microsoft.github.io/rego-cpp/) - Rego compiler and runtime implemented in C++. It provides a C FFI with Rust and Python bindings in addition to an extensible C++ implementation.
* [regorus](https://github.com/microsoft/regorus/tree/main/bindings/cpp) ⭐ 337 | 🐛 59 | 🌐 Rust | 📅 2026-08-13 - C++ bindings to Regorus, a fast, lightweight Rego interpreter written in Rust.

### Rust

* [regorus](https://crates.io/crates/regorus) - A fast, lightweight Rego interpreter written in Rust. In addition to bringing the power of Rego to Rust-only environments, it is intended as a platform for developing Rego tools and exploring Rego language enhancements.
* [regorust](https://crates.io/crates/regorust) - Rust crate wrapping the C FFI for rego-cpp, allowing in-process Rego policy evaluation using idiomatic Rust.

### Swift

* [swift-opa](https://github.com/open-policy-agent/swift-opa) ⭐ 36 | 🐛 14 | 🌐 Swift | 📅 2026-08-14 - Swift package for evaluating OPA IR Plans compiled from Rego policies

### Typescript

* [OPA Typescript SDK](https://github.com/open-policy-agent/opa-typescript) ⭐ 34 | 🐛 16 | 🌐 TypeScript | 📅 2025-11-20 - Typescript SDK for interacting with OPA ([documentation](https://open-policy-agent.github.io/opa-typescript/))

## WebAssembly (Wasm)

* [Go SDK](https://github.com/open-policy-agent/opa/tree/main/internal/wasm/sdk) ⭐ 12,099 | 🐛 346 | 🌐 Go | 📅 2026-08-13 - a small Go library for using WebAssembly compiled Open Policy Agent Rego policies
* [regorus](https://github.com/microsoft/regorus/tree/main/bindings/wasm) ⭐ 337 | 🐛 59 | 🌐 Rust | 📅 2026-08-13 - Evaluate Rego policies in WASM using Regorus. Try it out at [Regorus Playground](https://anakrish.github.io/regorus-playground/).
* [NPM module](https://github.com/open-policy-agent/npm-opa-wasm/) ⭐ 156 | 🐛 16 | 🌐 JavaScript | 📅 2026-07-10 - a small SDK for using WebAssembly compiled Open Policy Agent Rego policies
* [Rust](https://github.com/matrix-org/rust-opa-wasm) ⭐ 79 | 🐛 12 | 🌐 Rust | 📅 2026-08-04 - A crate to use OPA policies compiled to Wasm.
* [.NET Core Library](https://github.com/christophwille/csharp-opa-wasm) ⭐ 45 | 🐛 9 | 🌐 C# | 📅 2026-05-26 - .NET SDK for calling Wasm-compiled OPA policies from .NET Core
* [JVM](https://github.com/sangkeon/java-opa-wasm) ⭐ 18 | 🐛 4 | 🌐 Java | 📅 2024-04-10 - Java SDK for calling Wasm-compiled policies. Uses wasmtime.
* [Python Library](https://github.com/a2d24/python-opa-wasm) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2023-06-25 - Open Policy Agent WebAssembly SDK for Python
* [OpaDotNet](https://github.com/me-viper/OpaDotNet) ⭐ 8 | 🐛 7 | 🌐 C# | 📅 2026-08-04 - Open Policy Agent (OPA) WebAssembly dotnet core SDK
* [OpaDotNet.Compilation](https://github.com/me-viper/OpaDotNet.Compilation) ⭐ 0 | 🐛 1 | 🌐 C# | 📅 2025-05-28 - dotnet core backend for packaging Open Policy Agent Rego policies and data files into WASM policy bundles
* [opa-wasmtime](https://github.com/nickdeis/python-opa-wasmtime) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-09-14 - An OPA WebAssembly SDK for Python based on wasmtime (for Python versions greater than 3.9)

### WebAssembly Blogs and Articles

* [Enforce policies in the browser with Open Policy Agent](https://medium.com/@robertgartman/enforce-policies-in-the-browser-with-open-policy-agent-22d8e32fbfb6?source=friends_link\&sk=b7a58aecd84bf7367622347a91772947) - *first* article in a series of three covering why and how to reuse backend Policy-as-Code in the browser.
* [Reuse Policy as Code — stay DRY](https://medium.com/@robertgartman/reuse-policy-as-code-stay-dry-7ad1229be160?source=friends_link\&sk=196fd624a4027f5c33366f596dc75935) - *second* article in a series of three covering why and how to reuse backend Policy-as-Code in the browser. This article focus on Rego and HOW
* [OPA & Angular: Policy-as-Code in the browser](https://medium.com/@robertgartman/opa-angular-policy-as-code-in-the-browser-7bb3e5a8f60c?source=friends_link\&sk=69f87b120d716a4f4f7abe5d3e1680ec) - *third* article in a series of three covering why and how to reuse backend Policy-as-Code in the browser. Angular Proof of Concept based on article 1 & 2.
* [Rego on WebAssembly](https://blog.openpolicyagent.org/opa-v0-15-1-rego-on-webassembly-81c226c51be4) - original OPA Wasm support blog post which summarizes how OPA's Wasm functionality works.

### Docs

* [Wasm](https://www.openpolicyagent.org/docs/latest/wasm/) - Official docs on WebAssembly for OPA

### Built with Wasm

* [Snyk CLI](https://github.com/snyk/snyk) ⭐ 5,637 | 🐛 135 | 🌐 TypeScript | 📅 2026-08-14 - Test Infrastructure as Code source code for security misconfigurations and best practices in the local console. The npm-opa-wasm library is used to run WASM bundle of Rego policies to detect misconfiguration.
* [regorus](https://github.com/microsoft/regorus/tree/main/bindings/wasm) ⭐ 337 | 🐛 59 | 🌐 Rust | 📅 2026-08-13 - Evaluate Rego policies in WASM using Regorus. Try it out at [Regorus Playground](https://anakrish.github.io/regorus-playground/).
* [OPA Wasm demo](https://opa-wasm.glitch.me/) - Demonstration of evaluating OPA's Wasm modules in the browser

## Kubernetes

* [Kubescape](https://github.com/armosec/kubescape) ⭐ 11,603 | 🐛 119 | 🌐 Go | 📅 2026-08-14 - Kubescape is tool for scanning Kubernetes clusters for security issues. Kubescape tests (rules) are based completely on OPA. See the regos [here](https://github.com/armosec/regolibrary) ⭐ 131 | 🐛 21 | 🌐 Open Policy Agent | 📅 2026-08-14
* [Gatekeeper](https://github.com/open-policy-agent/gatekeeper) ⭐ 4,263 | 🐛 172 | 🌐 Go | 📅 2026-08-10 - A validating and mutating webhook that enforces CRD-based policies executed by OPA for Kubernetes
* [GKE Policy Automation](https://github.com/google/gke-policy-automation) ⭐ 526 | 🐛 6 | 🌐 Go | 📅 2026-08-09 - Tool and policy library for reviewing GKE clusters against best practices
* [Konstraint](https://github.com/plexsystems/konstraint) ⭐ 393 | 🐛 21 | 🌐 Go | 📅 2025-11-20 - CLI tool for working with templates and constraints when using Gatekeeper
* [Gatekeeper Policy Manager](https://github.com/sighupio/gatekeeper-policy-manager) ⭐ 328 | 🐛 26 | 🌐 TypeScript | 📅 2026-08-12 - Web UI for Gatekeeper policies
* [kube-mgmt](https://github.com/open-policy-agent/kube-mgmt) ⭐ 261 | 🐛 13 | 🌐 Go | 📅 2026-08-11 - Sidecar providing data from Kubernetes to OPA. Includes Helm charts for both projects
* [Red Hat Rego Policies](https://github.com/redhat-cop/rego-policies) ⭐ 171 | 🐛 11 | 🌐 Shell | 📅 2026-08-13 - Red Hat Rego policies collection
* [MagTape](https://github.com/tmobile/magtape) ⭐ 152 | 🐛 27 | 🌐 Python | 📅 2024-04-24 - OPA-based admission controller for policy enforcement
* [KubeStellar Console](https://github.com/kubestellar/console) ⭐ 127 | 🐛 31 | 🌐 TypeScript | 📅 2026-08-14 - Open source AI-powered multi-cluster Kubernetes dashboard with built-in OPA/Gatekeeper policy visualization, real-time compliance monitoring across hybrid edge and cloud environments. CNCF Sandbox project (Apache 2.0)
* [Cosign Gatekeeper Provider](https://github.com/developer-guy/cosign-gatekeeper-provider) ⚠️ Archived - Cosign Provider a new provider of OPA Gatekeeper's ExternalData feature to verify container images
* [Kove](https://github.com/cmacrae/kove) ⭐ 50 | 🐛 5 | 🌐 Go | 📅 2023-07-04 - Watch your in-cluster Kubernetes manifests for OPA policy violations and export them as Prometheus metrics
* [Admission policy development](https://github.com/k8spin/opa-k8s-development) ⭐ 14 | 🐛 0 | 📅 2019-09-08 - OPA Kubernetes validation and mutation testing environment
* [Gatekeeper Conftest plugin](https://github.com/clover/gatekeeper-conftest) ⭐ 14 | 🐛 2 | 🌐 Go | 📅 2024-01-26 - A Conftest plugin that transforms input objects to be compatible with OPA Gatekeeper policies.
* [Validating and Mutating Admission Control Example](https://github.com/tsandall/validating-and-mutating-example) ⭐ 4 | 🐛 0 | 🌐 Open Policy Agent | 📅 2020-01-10 - Example validating and mutation admission controller
* [Gatekeeper Policy Library](https://www.github.com/open-policy-agent/gatekeeper-library) - A collection of constraint templates and sample constraints that you can use with Gatekeeper
* [Meshery](https://meshery.io/) - Meshery leverages built-in relationships to enforce Kubernetes configuration best practices and enhances the development process through custom rules in OPA's Rego query language

### Service Mesh Authorization

* [OPA Envoy Plugin](https://github.com/open-policy-agent/opa-envoy-plugin) ⭐ 360 | 🐛 17 | 🌐 Go | 📅 2026-08-14 - The OPA Envoy Plugin (compatible with Envoy, Istio, Gloo Edge, more)
* [Open Service Mesh](https://release-v0-11.docs.openservicemesh.io/docs/guides/integrations/external_auth_opa/#osm-with-opa-plugin-external-authorization-walkthrough) - Envoy based service mesh using OPA for external authorization
* [Kuma](https://konghq.com/videos/microservice-authorization-with-open-policy-agent-and-kuma/) - OPA for Kuma service mesh
* [Kong Mesh](https://konghq.com/blog/kong-service-mesh-and-opa-policy/) - OPA for Kong Mesh authorization ([docs](https://docs.konghq.com/mesh/1.5.x/features/opa/))

### Blogs and Articles

* [Policy Enabled Kubernetes with OPA](https://www.capitalone.com/tech/software-engineering/policy-enabled-kubernetes-with-open-policy-agent/) - Guide on setting up OPA for kubernetes admission control
* [Integrating OPA with Kubernetes](https://techblost.com/integrating-open-policy-agent-opa-with-kubernetes/) - Comprehensive introduction to OPA and Gatekeeper
* [Using OPA on EKS](https://aws.amazon.com/blogs/opensource/using-open-policy-agent-on-amazon-eks/) - Using Open Policy Agent on Amazon EKS
* [OPA and Gatekeeper](https://www.infracloud.io/blogs/opa-and-gatekeeper/) - Comparison between OPA and Gatekeeper with lots of useful information
* [Kubernetes Authorization](https://itnext.io/kubernetes-authorization-via-open-policy-agent-a9455d9d5ceb) - Guide on using OPA for Kubernetes authorization
* [Gatekeeper in a CI/CD pipeline](https://arapulido.github.io/blog/2021/08/02/testing-your-kubernetes-config-against-policy-ci/) - Guide on how to setup your CI environment to test your Kubernetes configuration against your policy in a CI environment as part of a GitOps strategy
* [Verifying container signatures on Kubernetes with Gatekeeper](https://medium.com/@LachlanEvenson/verifying-container-signatures-on-kubernetes-with-gatekeeper-19a4519c3016) - Verifying container signatures on Kubernetes with Gatekeeper
* [Gator CLI](https://medium.com/@LachlanEvenson/testing-gatekeeper-constraints-with-gator-cli-da31050a6564) - Testing Gatekeeper constraints with Gator CLI
* [Kubernetes: An Enterprise Guide, 2nd Ed Chapter 8 - Extending Security with OpenPolicyAgent](https://youtu.be/_GQZ8Qahu48) - Walk through labs that show you how to build, debug, and deploy GateKeeper policies and mutations in your cluster.
* [Kubernetes: An Enterprise Guide, 2nd Ed Chapter 9 - Node Security with GateKeeper](https://youtu.be/UrSvh74n24E) - Walk through labs that show the differences between VMs and containers with a breakout, creating `securityContext` defaults using mutations, replacing `PodSecurityPolicy` using GateKeeper, debuging audit violations, and policies for multi-tenant clusters.
* [OPA Gatekeeper: Policy and Governance for Kubernetes](https://kubernetes.io/blog/2019/08/06/opa-gatekeeper-policy-and-governance-for-kubernetes/) - Kubernetes blog post
* [Using OPA Gatekeeper on Azure](https://docs.microsoft.com/en-us/azure/governance/policy/concepts/policy-for-kubernetes) - Azure Policy for Kubernetes clusters

## Nomad

* [Nomad Admission Control Proxy](https://github.com/mxab/nacp) ⭐ 51 | 🐛 5 | 🌐 Go | 📅 2026-08-14 - An admission controller that can be used as a proxy to Nomad's API for mutation and validation with builtin OPA support.

## Terraform

* [awesome-terraform-compliance](https://github.com/antonbabenko/awesome-terraform-compliance) ⭐ 142 | 🐛 2 | 📅 2026-07-29 - Curated list of OPA/Rego policy libraries, IaC scanners (Conftest, Regula, Fugue), and compliance resources for Terraform and OpenTofu.

## Datasource Integrations

* [Elasticsearch](https://github.com/open-policy-agent/contrib/tree/master/data_filter_elasticsearch) ⭐ 348 | 🐛 22 | 🌐 Go | 📅 2026-07-16 - OPA-Elasticsearch Data Filtering Example
* [Inspektor](https://github.com/poonai/inspektor) ⭐ 285 | 🐛 18 | 🌐 Rust | 📅 2022-07-15 - Access Control as Code for databases using OPA to make its access decision
* [Kafka Authorizer](https://github.com/StyraInc/opa-kafka-plugin) ⭐ 63 | 🐛 8 | 🌐 Scala | 📅 2025-04-15 - Kafka authorizer plugin using OPA, with example policies
* [Data Filtering on Spring Data](https://github.com/jferrater/opa-data-filter-spring-boot-starter) ⭐ 30 | 🐛 4 | 🌐 Java | 📅 2023-12-20 - Data filtering for MongoDB and JPA using OPA
* [OPA SpiceDB](https://github.com/umbrellaassociates/opa-spicedb) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2025-10-11 - OPA integration with Authzed SpiceDB that allows to use ReBAC in policies for authorization
* [Trino OPA Authorizer](https://github.com/stackabletech/trino-opa-authorizer/) ⚠️ Archived - Plugin for Trino that allows using OPA for authorization
* [Google Calendar](https://github.com/anderseknert/opa-google-calendar) ⭐ 4 | 🐛 0 | 🌐 Open Policy Agent | 📅 2021-11-09 - Integrating OPA with the Google Calendar API
* [OPA Single Message Transformer](https://github.com/opencredo/opa-single-message-transformer) ⚠️ Archived - Single Message Transformer for Kafka. Uses OPA to choose which records to filter out based on policy.
* [Strimzi](https://strimzi.io/) - Kafka in kubernetes, with built-in support for OPA as authorizer
* [Alluxio](https://www.alluxio.io/) - Alluxio is a data orchestration tool which allows [delegating access control decisions to OPA](https://docs.alluxio.io/ee/user/2.10.0/en/security/OpenPolicyAgent-Integration.html)

### Datasource Integrations Blogs and Articles

* [Google Calendar Integration](https://blog.styra.com/blog/the-power-of-data-calendar-based-policy-enforcement) - The Power of Data: Calendar-based Policy Enforcement
* [Apache Kafka](https://opencredo.com/blogs/controlling-kafka-data-flows-using-open-policy-agent/) - Controlling Kafka Data Flows using Open Policy Agent

## IDE and Editor Integrations

* [Atom](https://github.com/open-policy-agent/opa/tree/master/misc/syntax/atom) ⭐ 12,099 | 🐛 346 | 🌐 Go | 📅 2026-08-13 - Syntax highlighting for the Atom editor
* [TextMate](https://github.com/open-policy-agent/opa/tree/master/misc/syntax/textmate) ⭐ 12,099 | 🐛 346 | 🌐 Go | 📅 2026-08-13 - Syntax highlighting for TextMate
* [Sublime](https://github.com/open-policy-agent/opa/tree/master/misc/syntax/sublime) ⭐ 12,099 | 🐛 346 | 🌐 Go | 📅 2026-08-13 - Syntax highlighting for Sublime
* [Nano](https://github.com/scopatz/nanorc) ⭐ 3,258 | 🐛 117 | 🌐 Shell | 📅 2024-05-27 - Syntax highlighting for Nano
* [IntelliJ plugin](https://github.com/open-policy-agent/opa-idea-plugin) ⭐ 62 | 🐛 35 | 🌐 Kotlin | 📅 2026-08-12 - OPA plugin for the IntelliJ IDE
* [Vim](https://github.com/tsandall/vim-rego) ⭐ 47 | 🐛 1 | 🌐 Vim script | 📅 2024-01-11 - Vim plugin for the Rego language, with support for syntax highlighting
* [Emacs](https://github.com/psibi/rego-mode) ⭐ 30 | 🐛 2 | 🌐 Emacs Lisp | 📅 2021-07-22 - Emacs Major mode for working with Rego
* [tree-sitter-rego](https://github.com/FallenAngel97/tree-sitter-rego) ⭐ 12 | 🐛 7 | 🌐 JavaScript | 📅 2026-07-11 - Tree-sitter grammar for Rego ([blog](https://decodeapps.pp.ua/blog/post/rego-treesitter))
* [codemirror-lang-rego](https://github.com/HZMonama/codemirror-lang-rego) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2025-12-10 - Complete Rego language support for CodeMirror 6, with syntax highlighting, autocomplete, and intelligent data context awareness.
* [VS Code plugin](https://marketplace.visualstudio.com/items?itemName=tsandall.opa) - Develop, test, debug, and analyze policies for OPA in VS Code
* [Zed Extension](https://github.com/StyraInc/zed-rego) - Zed extension for OPA and Rego leveraging [Regal](https://www.openpolicyagent.org/projects/regal)
* [Null-ls](https://github.com/jose-elias-alvarez/null-ls.nvim) - Use Neovim as a language server to inject LSP diagnostics, code actions, and more. Supports linting rego files.
* [CodeMirror](https://github.com/StyraInc/codemirror-rego) - Rego mode and minimal key map for [CodeMirror](https://codemirror.net/)
* [Prism](https://prismjs.com/) - Prism is a lightweight, extensible syntax highlighter, built with modern web standards in mind (supports Rego)
* [highlight.js](https://github.com/StyraInc/highlightjs-rego) - Rego syntax support for [highlight.js](https://highlightjs.org/)

## Infrastructure as Code

* [Trivy](https://github.com/aquasecurity/trivy) ⭐ 37,401 | 🐛 238 | 🌐 Go | 📅 2026-08-14 - Scan your code and artifacts for known vulnerabilities and misconfiguration issues.
* [Infracost](https://github.com/infracost/infracost/) ⭐ 12,449 | 🐛 24 | 🌐 Go | 📅 2026-08-11 - Infracost generates cloud cost estimates for Terraform and integrates with OPA, it can be used to write [cost policies](https://www.infracost.io/docs/features/cost_policies/)
* [Terrascan](https://github.com/accurics/terrascan) ⚠️ Archived - [500+ Policies](https://github.com/accurics/terrascan/tree/master/pkg/policies/opa/rego) ⚠️ Archived written in OPA for security best practices.
* [KICS](https://github.com/Checkmarx/kics) ⭐ 2,685 | 🐛 325 | 🌐 Open Policy Agent | 📅 2026-08-14 - Keeping Infrastructure as Code Secure or KICS scans IaC projects for security vulnerabilities, compliance issues, and infrastructure misconfiguration. Currently working with Terraform projects, Kubernetes manifests, Dockerfiles, AWS CloudFormation Templates, and Ansible playbooks.
* [Regula](https://github.com/fugue/regula) ⚠️ Archived - Evaluates Terraform code for potential security misconfigurations and compliance violations.
* [GCP policy guardrails for Terraform](https://github.com/GoogleCloudPlatform/policy-library/tree/main/validator) ⚠️ Archived - Rego reference policy library for GCP controls (originally from forseti). Originally used by `terraform-validator` and now on `gcloud beta terraform vet`. More info at [Policy Validation](https://cloud.google.com/docs/terraform/policy-validation)
* [Example Terraform policies](https://github.com/Scalr/sample-tf-opa-policies) ⭐ 179 | 🐛 6 | 🌐 Open Policy Agent | 📅 2025-06-19 - Example Terraform policies
* [TFLint OPA Ruleset](https://github.com/terraform-linters/tflint-ruleset-opa) ⭐ 85 | 🐛 4 | 🌐 Go | 📅 2026-08-10 - Write custom TFLint rules in Rego
* [OPA AWS CloudFormation Hook](https://github.com/StyraInc/opa-aws-cloudformation-hook) ⭐ 37 | 🐛 9 | 🌐 Python | 📅 2025-12-15 - AWS CloudFormation Hook calling OPA for policy decisions. See also [tutorial](https://www.openpolicyagent.org/docs/latest/aws-cloudformation-hooks/).
* [Terraform OPA IBM](https://github.com/IBM-Cloud/terraform-opa-ibm) ⭐ 17 | 🐛 0 | 🌐 Open Policy Agent | 📅 2022-09-26 - Terraform policy library for IBM Cloud
* [Pulumi OPA Bridge for CrossGuard](https://github.com/pulumi/pulumi-policy-opa) ⭐ 13 | 🐛 3 | 🌐 Go | 📅 2026-06-25 - This project allows OPA rules to be run in the context of Pulumi's policy system, CrossGuard

### Infrastructure as Code Blogs and Articles

* [Using OPA with Pulumi CrossGuard](https://www.pulumi.com/blog/opa-support-for-crossguard/) - Authoring Pulumi CrossGuard Policy with OPA
* [AWS CDK with OPA](https://aws.amazon.com/blogs/opensource/realize-policy-as-code-with-aws-cloud-development-kit-through-open-policy-agent/) - Realize Policy-as-Code with AWS Cloud Development Kit through Open Policy Agent
* [Kubernetes Authorization](https://itnext.io/kubernetes-authorization-via-open-policy-agent-a9455d9d5ceb) - Kubernetes Authorization via Open Policy Agent
* [Using OPA with Spacelift](https://spacelift.io/blog/what-is-open-policy-agent-and-how-it-works) - Open Policy Agent: What Is OPA and How It Works (Examples)

## Serverless

* [OPA Lambda Extension Plugin](https://github.com/godaddy/opa-lambda-extension-plugin) ⚠️ Archived - A custom plugin for running OPA in AWS Lambda as a Lambda Extension

### Serverless Blogs and Articles

* [Serverless Policy Enforcement](https://blog.openpolicyagent.org/serverless-policy-enforcement-connecting-opa-and-aws-lambda-e624f7176a3) - Connecting Open Policy Agent and AWS Lambda
* [Lambda Authorizer](https://aws.amazon.com/blogs/opensource/creating-a-custom-lambda-authorizer-using-open-policy-agent/) - Creating a custom Lambda authorizer using Open Policy Agent

## Testing

* [kube-review](https://github.com/anderseknert/kube-review) ⭐ 161 | 🐛 5 | 🌐 Go | 📅 2026-05-02 - CLI tool to quickly create [AdmissionReview](https://kubernetes.io/docs/reference/access-authn-authz/extensible-admission-controllers/) requests from Kubernetes resources
* [rego-test-assertions](https://github.com/anderseknert/rego-test-assertions) ⭐ 40 | 🐛 1 | 🌐 Open Policy Agent | 📅 2026-06-19 - Helper library for working with assertions in Rego unit tests
* [github-action-opa-rego-test](https://github.com/masterpointio/github-action-opa-rego-test) ⭐ 23 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-01 - GitHub Action to automate testing for your OPA Rego policies and generates a report.
* [ocov](https://github.com/C5T/ocov) ⭐ 5 | 🐛 1 | 🌐 C++ | 📅 2023-04-06 - Colors `opa test --coverage` reports in the terminal
* [opa-codecov](https://github.com/SVilgelm/opa-codecov) ⭐ 1 | 🐛 1 | 🌐 Go | 📅 2025-11-24 - Convert OPA test coverage report to a JSON format supported by Codecov
* [gator CLI](https://open-policy-agent.github.io/gatekeeper/website/docs/gator/) - Command line unit test runner for OPA Gatekeeper

### Testing Blogs and Articles

* [Advanced Rego Testing Techniques](https://www.styra.com/blog/advanced-rego-testing-techniques/) - Great blog on testing patterns for Rego, by Nicholaos Mouzourakis

## Tools and Utilities

* [Topaz](https://github.com/aserto-dev/topaz) ⭐ 1,356 | 🐛 12 | 🌐 Go | 📅 2026-08-11 - Topaz is an open-source application authorization project that uses OPA as the decision engine and supports Rego policies.
* [Regal](https://github.com/open-policy-agent/regal) ⭐ 398 | 🐛 138 | 🌐 Go | 📅 2026-08-11 - Regal is a linter for Rego, with the goal of making your Rego magnificent! ([blog](https://www.styra.com/blog/guarding-the-guardrails-introducing-regal-the-rego-linter/))
* [Open Policy Containers](https://github.com/opcr-io/policy) ⭐ 259 | 🐛 8 | 🌐 Go | 📅 2026-07-25 - Secure software supply chains for OPA policies. Push, pull, tag, test, version, and sign OPA policies.
* [Fregot](https://github.com/fugue/fregot) ⭐ 233 | 🐛 10 | 🌐 Haskell | 📅 2022-06-30 - Alternative REPL implementation for Rego
* [Rönd](https://github.com/rond-authz/rond) ⭐ 161 | 🐛 35 | 🌐 Go | 📅 2026-02-11 - Rönd is a lightweight container that distributes security policy enforcement throughout your application
* [OPAL](https://github.com/authorizon/opal) ⭐ 99 | 🐛 1 | 🌐 Python | 📅 2024-08-12 - Realtime policy and data updates for your OPA agents on top of websockets pub/sub
* [OPA pre-commit](https://github.com/anderseknert/pre-commit-opa) ⭐ 69 | 🐛 0 | 📅 2025-07-06 - Pre-commit hooks for OPA/Rego/Conftest development
* [setup-opa](https://github.com/open-policy-agent/setup-opa) ⭐ 55 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-21 - GitHub action to configure the Open Policy Agent CLI in your GitHub Actions workflows
* [alfred](https://github.com/dolevf/Open-Policy-Agent-Alfred) ⭐ 36 | 🐛 0 | 🌐 HTML | 📅 2025-05-19 - A self-hosted OPA Playground Alternative
* [opactl](https://github.com/onelittlenightmusic/opactl) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2022-06-01 - A simple tool to turn your Rego rule into CLI command ([blog](https://itnext.io/implement-a-policy-and-use-it-in-cli-de906237c6ab))
* [OpenAPI to Rego](https://github.com/ashutosh-narkar/openapi-to-rego) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2019-11-04 - Generate Rego code given an OpenAPI 3.0 Specification
* [rego-skill](https://github.com/Void3110/rego-skill) ⭐ 17 | 🐛 0 | 🌐 Open Policy Agent | 📅 2026-05-31 - Claude Code skill for AI-assisted Rego policy development with mandatory test workflow, security review checklist, and 114 tests covering RBAC, API Gateway, and ABAC patterns
* [Monitor OPA Gatekeeper](https://github.com/developer-guy/monitor-opa-gatekeeper) ⭐ 14 | 🐛 0 | 📅 2020-12-17 - Monitoring implementation guide for OPA Gatekeeper ([blog](https://sysdig.com/blog/monitor-gatekeeper-prometheus/))
* [Snyk IaC Rules](https://github.com/snyk/snyk-iac-rules) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2026-06-04 - Maintain library of Rego rules, run integration tests and build WASM bundles for distribution of rules. The OPA libraries are used to build WASM bundles.
* [Temporal reasoning with OPA](https://github.com/mhausenblas/temporal-opa) ⭐ 11 | 🐛 0 | 🌐 Open Policy Agent | 📅 2020-06-11 - Examples for working with time in Rego
* [opa-explorer](https://github.com/srenatus/opa-explorer) ⚠️ Archived - Visual tool for exploring the different compilation stages of the OPA topdown compiler
* [OPA Schema Examples](https://github.com/aavarghese/opa-schema-examples) ⭐ 10 | 🐛 0 | 🌐 Open Policy Agent | 📅 2021-08-01 - Examples of extending the OPA type checker with JSON [schemas](https://www.openpolicyagent.org/docs/latest/schemas/)
* [mcov](https://github.com/styrainc/mcov) ⭐ 5 | 🐛 8 | 🌐 Go | 📅 2026-01-30 - A tool that'll check your Rego source files and report the minimum compatible OPA version required
* [RegoLab](https://github.com/HZMonama/regolab) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-06 - RegoLab is a web-based playground for writing and testing Open Policy Agent Rego policies with real-time evaluation and data simulation.
* [rq (Rego Query)](https://git.sr.ht/~charles/rq) - jq-inspired tool to bring Rego to your shell pipelines
* [dependency-management-data (DMD)](https://dmd.tanna.dev) is a set of tooling to get a better understanding of the use of dependencies across your organisation. DMD supports using Open Policy Agent to write more complex rules around dependency usage than can be done using the SQL interface.
* [nopa](https://gitlab.com/sencillodev/nopa) - Nopa is a simple way to store OPA bundles in NATS object storage with real time updates and custom module injection.
* [Regoround](https://gitlab.com/sencillodev/regoround) - A Rego playground that you can run locally. It allows you to load a custom bundle into the playground. URLs are safe to share, the URL parameters are built from the code itself and so cannot be guessed. A live version with the example bundle in the repo is at <https://regoround.fly.dev>

## Other Usecases

* [ScubaGear](https://github.com/cisagov/ScubaGear/) ⭐ 2,640 | 🐛 227 | 🌐 PowerShell | 📅 2026-08-13 - Using Rego policies to assess the security posture of M365 tenants, by CISA
* [Reposaur](https://github.com/reposaur/reposaur) ⚠️ Archived - Audit, verify and report on development platforms (GitHub and others) easily with pre-defined and/or custom policies.
* [SansShell](https://github.com/Snowflake-Labs/sansshell) ⭐ 122 | 🐛 40 | 🌐 Go | 📅 2026-08-13 - A non-interactive daemon for host management, where any action is authorized by OPA
* [goast](https://github.com/m-mizutani/goast) ⭐ 75 | 🐛 0 | 🌐 Go | 📅 2026-07-10 - Go AST (Abstract Syntax Tree) based static analysis tool using Rego
* [backstage-opa-plugins](https://github.com/Parsifal-M/backstage-opa-plugins) ⭐ 65 | 🐛 2 | 🌐 TypeScript | 📅 2026-07-17 - Plugins for integrating OPA with [Backstage](https://backstage.io/), including OPA-based authorisation.

## Fun and Quirky

* [Policing Christmas Tree](https://github.com/charlieegan3/policing-christmas-trees) ⚠️ Archived - Using Rego to determine the correctness of Christmas tree decorations
* [Colorized](https://github.com/anderseknert/colorized) ⭐ 3 | 🐛 0 | 🌐 Open Policy Agent | 📅 2022-03-28 - Colorized output for the OPA print function!
* [How I Used OPA to Help Me Solve Wordle](https://www.styra.com/blog/how-i-used-opa-to-help-me-solve-wordle/) - OPA as a Wordle assistant
* [Corrupting OPA to Run My Games](https://kevinhoffman.medium.com/corrupting-the-open-policy-agent-to-run-my-game-711f340adb5a) - Fun blog on using OPA for game engines

## Support and Community

* [Stack Overflow](https://stackoverflow.com/questions/tagged/open-policy-agent) - Stack Overflow OPA section
* [OPA Slack](https://openpolicyagent.slack.com) - Open Policy Agent Slack workspace
* [GitHub Discussions](https://github.com/open-policy-agent/feedback/discussions) ⭐ 46 | 🐛 1 | 📅 2025-03-26 - Open Policy Agent Discussion Board

## Recommended Reading

* [OPA Guidebook](https://sangkeon.github.io/opaguide/) - Open source, free book on Open Policy Agent, by Sangkeon Lee ([source code](https://github.com/sangkeon/opaguide_src) ⭐ 20 | 🐛 0 | 🌐 WebAssembly | 📅 2023-11-22)
* [Microservices Security in Action](https://www.manning.com/books/microservices-security-in-action) - Book on microservices security, with dedicated section covering OPA. Freely available online
* [Gusto Engineering](https://engineering.gusto.com/why-logic-programming-is-the-best-choice-for-authorization-70f95164dee7) — Why logic programming is the best choice for authorization
* [Fugue (now Snyk)](https://snyk.io/blog/5-tips-for-using-the-rego-language-for-open-policy-agent-opa/) - 5 tips for using the Rego language for Open Policy Agent
* [Integration](https://medium.com/@nikman/control-user-access-and-permissions-in-cvat-with-open-policy-agent-a2abbd09774d) - Control User Access and Permissions in CVAT with Open Policy Agent

## People

### Maintainers

* [@open-policy-agent](https://github.com/open-policy-agent) - Official OPA account 🌎 ([Mastodon](https://infosec.exchange/@openpolicyagent), [Bluesky](https://bsky.app/profile/openpolicyagent.bsky.social), [Twitter](https://twitter.com/OpenPolicyAgent))
* [@tsandall](https://github.com/tsandall) - Torin Sandall 🇨🇦 - OPA co-creator ([Twitter](https://twitter.com/sometorin))
* [@timothyhinrichs](https://github.com/timothyhinrichs) - Tim Hinrichs 🇺🇸 - OPA co-creator ([Twitter](https://twitter.com/tlhinrichs))
* [@ashutosh-narkar](https://github.com/ashutosh-narkar) - Ash Narkar 🇺🇸 - OPA maintainer ([Twitter](https://twitter.com/ashtalk))
* [@johanfylling](https://github.com/johanfylling/) - Johan Fylling 🇸🇪 - OPA maintainer ([Mastodon](https://hachyderm.io/@johanfylling))
* [@philipaconrad](https://github.com/philipaconrad) - Philip Conrad 🇺🇸 - OPA maintainer ([Twitter](https://twitter.com/philip_conrad))
* [@anderseknert](https://github.com/anderseknert) - Anders Eknert 🇸🇪 - OPA developer advocate ([Mastodon](https://swecyb.com/@anderseknert))
* [@charlieegan3](https://github.com/charlieegan3) - Charlie Egan 🇬🇧 - OPA developer advocate ([Mastodon](https://hachyderm.io/@charlieegan3))
* [@ritazh](https://github.com/ritazh) - Rita Zhang 🇺🇸 - Gatekeeper maintainer ([Mastodon](https://hachyderm.io/@ritazh), [Twitter](https://twitter.com/ritazzhang))
* [@sozercan](https://github.com/sozercan) - Sertaç Özercan 🇺🇸 - Gatekeeper maintainer ([Mastodon](https://hachyderm.io/@sozercan@mastodon.social), [Twitter](https://twitter.com/sozercan))
* [@jpreese](https://github.com/jpreese) - John Reese 🇺🇸 - Conftest maintainer ([Mastodon](https://hachyderm.io/@jpreese), [Twitter](https://twitter.com/johnpreese))

### Community Stars

* [@Parsifal-M](https://github.com/Parsifal-M) - Peter Macdonald 🇬🇧 - OPA contributor and active community member ([Mastodon](https://hachyderm.io/@parcifal), [Twitter](https://twitter.com/_PeterM_))
* [@m-mizutani](https://github.com/m-mizutani) - Masayoshi Mizutani 🇯🇵 - Security engineer. Prolific OPA & Rego advocate ([Twitter](https://twitter.com/m_mizutani))
* [@RoyOsaki](https://github.com/RoyOsaki) - Roy Hiroyuki OSAKI 🇺🇸 - Research engineer. OPA community contributor ([Twitter](https://twitter.com/Hiroyuki_OSAKI))
* [@developer-guy](https://github.com/developer-guy) - Batuhan Apaydin 🇹🇷 - OPA and many CNCF projects ([Mastodon](https://hachyderm.io/@developerguy), [Twitter](https://twitter.com/developerguyba))
* [@nmeisenzahl](https://github.com/nmeisenzahl) - Nico Meisenzahl 🇩🇪 - All about OPA and cloud native topics ([Twitter](https://twitter.com/nmeisenzahl))
* [@jaspervdj](https://github.com/jaspervdj) - Jasper Van der Jeugt 🇨🇭 - OPA contributor ([Mastodon](https://functional.cafe/@jaspervdj))
* [@willbeason](https://github.com/willbeason) - Will Beason 🇺🇸 - Ex Gatekeeper maintainer ([Mastodon](https://dair-community.social/@willbeason))
* [@peteroneilljr](https://github.com/peteroneilljr) - Peter O'Neill 🌎 - Ex OPA community advocate ([Mastodon](https://hachyderm.io/@Peteroneilljr), [Twitter](https://twitter.com/peteroneilljr))
* [@antonioberben](https://github.com/antonioberben) - Antonio Berben 🇪🇸 - OPA Contributor & Blogger

### Meetup Groups

* [Amsterdam OPA Users](https://www.meetup.com/opa-amsterdam/) 🇳🇱
* [London OPA Meetup](https://www.meetup.com/london-opa-meetup/) 🇬🇧
* [Stockholm OPA Users](https://www.meetup.com/stockholm-opa-meetup/) 🇸🇪

## Commercial Tools

* [Scalr](https://scalr.com/) - Collaboration and Automation for Terraform, backed by OPA
* [Fairwinds Insights](https://fairwinds.com/insights) - Run OPA policies consistently across CI/CD, Admission Control, and an multi-cluster scanner
* [Snyk IaC](https://snyk.io/product/infrastructure-as-code-security/) - Test Infrastructure as Code source code repositories for security misconfigurations and best practices. The OPA golang libraries are used to evaluate Rego policies to detect misconfigurations in the repositories.
* [Spacelift](https://spacelift.io/): Flexible management platform for Infrastructure as Code, backed by OPA
* [env0](https://www.env0.com): Infrastructure as Code automation platform, with OPA extensibility.

## Contributing

Built a great OPA integration or wrote an interesting blog or article on the topic? Submit a PR!
Please just make sure to include something that describes how the project uses OPA, or how OPA is otherwise related.

## Community

For questions, discussions and announcements related to our open source projects, please join
the Slack community!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
