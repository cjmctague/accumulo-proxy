<!--
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to You under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

[Apache Accumulo][accumulo] Proxy
--
[![Build Status][ti]][tl] [![Maven Central][mi]][ml] [![Javadoc][ji]][jl] [![Apache License][li]][ll]

This application acts as an Apache Accumulo Java client, and exposes its API as
an Apache [Thrift] service so that users can use their preferred programming
language to communicate with Accumulo (provided that language has a supported
Thrift language binding).

[accumulo]: https://accumulo.apache.org
[Thrift]: https://thrift.apache.org
[li]: https://img.shields.io/badge/license-ASL-blue.svg
[ll]: https://www.apache.org/licenses/LICENSE-2.0
[mi]: https://maven-badges.herokuapp.com/maven-central/org.apache.accumulo/accumulo-proxy/badge.svg
[ml]: https://maven-badges.herokuapp.com/maven-central/org.apache.accumulo/accumulo-proxy/
[ji]: https://www.javadoc.io/badge/org.apache.accumulo/accumulo-proxy.svg
[jl]: https://www.javadoc.io/doc/org.apache.accumulo/accumulo-proxy
[ti]: https://travis-ci.org/apache/accumulo-proxy.svg?branch=master
[tl]: https://travis-ci.org/apache/accumulo-proxy

