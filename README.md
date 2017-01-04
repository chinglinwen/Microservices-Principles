# Microservices-Principles

微服务架构的原则

## 1. 微服务的特点
###### 1. Componentization via Services ( encourage reusability and independence )
###### 2. Organized around Business Capabilities ( Conway's Law )
###### 3. Products not Projects ( you build, you run it )
###### 4. Smart endpoints and dumb pipes ( better performance/more resilience )
###### 5. Decentralized Governance ( self-direct team )
###### 6. Decentralized Data Management ( remove the dependence/avoid impact )
###### 7. Infrastructure Automation ( for more efficiency )
###### 8. Design for failure ( resilience )
###### 9. Evolutionary Design ( service refactoring / adding service )

## 2. 微服务的原则
###### 1. Hide Internal Implementation Details ( API access only )
###### 2. Independently Deployable ( upgrade, update, migrate, refactoring)
###### 3. Isolate Failure ( avoid wide range of impact, reduce cost/time )
###### 4. Highly Observable ( better monitoring )


## 3. 微服务的核心技术

About gRPC [http://www.grpc.io/](http://www.grpc.io/)

gRPC is a modern open source high performance RPC framework that can run in any environment. It can efficiently connect services in and across data centers with pluggable support for load balancing, tracing, health checking and authentication. It is also applicable in last mile of distributed computing to connect devices, mobile applications and browsers to backend services.

The main usage scenarios:

* Efficiently connecting polyglot services in microservices style architecture
* Connecting mobile devices, browser clients to backend services
* Generating efficient client libraries

Core Features that make it awesome:

* Idiomatic client libraries in 10 languages
* Highly efficient on wire and with a simple service definition framework
* Bi-directional streaming with http/2 based transport
* Pluggable auth, tracing, load balancing and health checking

更多内容请见 doc下文档： [doc](doc)