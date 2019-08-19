---
layout: post
title: Endpoints Elm
date: 2017-09-12 13:32:19 +0300
description: Elm code generator based on Scala endpoints library
---

Elm code generator based on Scala [endpoints library](https://github.com/julienrf/endpoints).

The project provides:
- interpreter for all basic endpoints algebras that targets [data structures](src/main/scala/io/scalaland/endpoints/elm/model) that resemble elm type system
- code emitter that takes these data structures and emits elm code containing:
  - elm type definitions
  - json encoders and decoders
  - initial value providers
  - url construction methods targeting [elm-url](https://github.com/elm/url)
  - api client methods targeting [elm-http-builder](https://github.com/lukewestby/elm-http-builder)

See also project [README](https://github.com/scalalandio/endpoints-elm/blob/master/README.md).

[![Build Status](https://travis-ci.org/scalalandio/endpoints-elm.svg?branch=master)](https://travis-ci.org/scalalandio/endpoints-elm)
[![Maven Central](https://img.shields.io/maven-central/v/io.scalaland/endpoints-elm_2.12.svg)](http://search.maven.org/#search%7Cga%7C1%7Cendpoints-elm)
[![License](http://img.shields.io/:license-Apache%202-green.svg)](http://www.apache.org/licenses/LICENSE-2.0.txt)