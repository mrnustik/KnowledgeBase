# Knowledge base

KnowledgeBase is a repository used for combining blog posts and information that might prove useful inthe future.

## .NET Knowledge Base

* [Deterministic GUID generation](https://github.com/LogosBible/Logos.Utility/blob/master/src/Logos.Utility/GuidUtility.cs) by Bradley Grainger

### Functional Programming

* [Monads in C# explained](https://mikhail.io/2018/07/monads-explained-in-csharp-again/) by Mikhail Shilkov

### .NET 6

* [Minimal APIs](https://gist.github.com/davidfowl/ff1addd02d239d2d26f4648a06158727) by David Fowler
* [.NET 6 migration guide](https://gist.github.com/davidfowl/0e0372c3c1d895c3ce195ba983b1e03d) by David Fowler
* [Migration to ASP.NET Core in .NET 6](https://gist.github.com/davidfowl/0e0372c3c1d895c3ce195ba983b1e03d) by David Fowler
* [Exploring .NET 6](https://andrewlock.net/series/exploring-dotnet-6/) by Andrew lock
* [Source generators list](https://github.com/amis92/csharp-source-generators) by amis92
* [.NET 6 features](https://github.com/okyrylchuk/dotnet6_features) okyrylchuk

### .NET 7

* [Rate Limiting API](https://devblogs.microsoft.com/dotnet/announcing-rate-limiting-for-dotnet/) by Brennan Conroy

### Open Telemetry

* [Observing .NET microservices with OpenTelemetry - logs, traces and metrics](https://blog.codingmilitia.com/2023/09/05/observing-dotnet-microservices-with-opentelemetry-logs-traces-metrics/) by João Antunes

## Architecture

### Paterns

* [BFF: Backend for frontend in Decathlon](https://medium.com/decathlondigital/bff-a-design-pattern-helping-teams-gain-ownership-677846e26b20) by Raphaël Tahar

### GraphQL

* [Exploring GraphQL’s performance tradeoffs](https://blog.allegro.tech/2022/06/graphql-perf-tradeoffs.html) by Alicja Halamska and Dawid Kubicki

### CQRS

* [Using Mediator](https://altkomsoftware.pl/en/blog/microservices-net-core-cqrs-mediatr/) - description of architecting a CQRS based system using Mediator by Ewelina Polska-Brzostowska

### DDD

* [Domain events handling](http://www.kamilgrzybek.com/design/handling-domain-events-missing-part/) by Kamil Grzybek

### Distributed systems

#### Messaging

* [Messaging back pressure relieving](https://clearmeasure.com/backpressure-in-message-based-systems) by Corey Keller
* [Saga and process manager patterns](https://event-driven.io/pl/saga_process_manager_distributed_transactions/) by Oskar Dudycz

### Microservices

* [CQRS and Event Sourcing Intro For Developers](https://altkomsoftware.pl/en/blog/cqrs-event-sourcing/) by Wojciech Suwała and Robert Witkowski

#### Service Discovery

* [Service Discovery with eureka](https://altkomsoftware.pl/en/blog/service-discovery-eureka/) - description of setting up .NET Core app with service discoveries, part of series about Microservices Architecture by Wojciech Suwała and Robert Witkowski
* [Steeltoe](https://steeltoe.io) - .NET library for Service Discovery using Eureka

#### API Gateways

* [API gateways setup using Ocelot](https://altkomsoftware.pl/en/blog/building-api-gateways-with-ocelot/) - description of API gateway setup using Ocelot library by Wojciech Suwała
  
## Persistence

### Event Sourcing

* [Event Sourcing: The Good, The Bad and The Ugly](https://www.continuousimprover.com/2017/11/event-sourcing-good-bad-and-ugly.html) - overview of articles about event sourcing by Dennis Doomen
* [Event Sourcing vs Command Sourcing](https://thinkbeforecoding.com/post/2013/07/28/Event-Sourcing-vs-Command-Sourcing) critique of Martin Fowlers Event Sourcing description by jeremie chassaing

#### [Marten](http://jasperfx.github.io/marten/)

* [Saving Domain Aggregates in Marten](https://altkomsoftware.pl/en/blog/building-microservices-domain-aggregates/) - basics of Marten, part of series about Microservices Architecture by Wojciech Suwała
* [Compiled Queries](http://jasperfx.github.io/marten/documentation/documents/querying/compiled_queries/) - documentation on usage of compiled queries

### Libraries

#### DDD

* [ValueOf](https://github.com/mcintyre321/ValueOf) - value object abstraction library
* [StronglyTypedIds](https://github.com/andrewlock/StronglyTypedId) - strongly typed id generator

### Testing

* [How to get ASP.NET Core logs in the output of xUnit tests](https://www.meziantou.net/how-to-get-asp-net-core-logs-in-the-output-of-xunit-tests.htm) by Gérald Barré

## DevOps

### Docker

* [Docker for beginners](https://docker-curriculum.com) - basic docker tutorial by Prakhar Srivasta basic docker tutorial by Prakhar Srivastavv
* [Running Posgtres in Docker](https://hackernoon.com/dont-install-postgres-docker-pull-postgres-bee20e200198) - guide on running Postgres database in Docker by Syed

### Kubernetes

* [An Introduction to Kubernetes](https://andrewlock.net/deploying-asp-net-core-applications-to-kubernetes-part-1-an-introduction-to-kubernetes/) - intro to Kubernetes from Andrew Lock

## React

### Redux

* [Mark Erikson - The Tao of Redux, Part 1 - Implementation and Intent](https://blog.isquaredsoftware.com/2017/05/idiomatic-redux-tao-of-redux-part-1/) - describes Redux internals
* [Mark Erikson - The Tao of Redux, Part 2 - Practice and Philosophy](https://blog.isquaredsoftware.com/2017/05/idiomatic-redux-tao-of-redux-part-2/) - discuses practical usage of Redux
