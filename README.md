# Message Security Layer

Message Security Layer (MSL) is an extensible and flexible secure messaging protocol that can be used to transport data between two or more communicating entities. Data may also be associated with specific users, and treated as confidential or non-replayable if so desired.

## Documentation

The [MSL Protocol](https://github.com/Netflix/msl/wiki/) provides a complete description of the protocol and implementation requirements. The [Configuration Guide](https://github.com/Netflix/msl/wiki/Configuration-Guide) presents some common client and server MSL configurations.

The set of public interfaces and classes an application must implement and use is documented in the [Public Javadoc](http://netflix.github.com/msl/javadoc-public/). Documentation on all of the code, including internal classes and private methods, can be found in the full [Javadoc](http://netflix.github.com/msl/javadoc/).

## Third-Party Libraries

The Java MSL code base requires the [org.json](http://www.json.org/java/) library and the [JUnit 4](http://junit.org).

The JavaScript MSL code base includes some third-party libraries within the lib/ directory, most notably the [Clarinet](https://github.com/dscape/clarinet) parser. The [jsrsasign](http://kjur.github.io/jsrsasign/) and [crypto-js](https://code.google.com/p/crypto-js/) libraries are currently included but are planned for removal.

All third-party libraries are subject to their respective license agreements.

## Getting Started

## LICENSE

Copyright 2014 Netflix, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
