---
layout: post
title: Endpoints Json Schemas Macros
date: 2017-09-12 13:32:18 +0300
description: Generic derivation based macros for JsonSchema type class of Scala endpoints library
---

Generic derivation based macros for JsonSchema type class of Scala [endpoints library](https://github.com/julienrf/endpoints).

Endpoints have [generic derivation of json schemas](http://julienrf.github.io/endpoints/algebras/json-schemas.html#generic-derivation-of-json-schemas)
based on [Shapeless](https://github.com/milessabin/shapeless) library.

This project provides fully compatible, drop-in replacement that doesn't use Shapeless, but Scala macros directly.
This approach has several advantages:

- immediate compilation-time performance improvements
- more descriptive error messages
- no runtime overhead as materialization to `HList`/`Coproduct` is not required
- avoided runtime dependency on Shapeless

See also [README.md](https://github.com/scalalandio/endpoints-json-schemas-macros/blob/master/README.md).
