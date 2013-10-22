---
title: Project Open Data JSON Schema
layout: default
---

Project Open Data: Schema Demos
-------------------------------

Here we look at a few things that you can do with [Project Open Data Schema](http://project-open-data.github.io/schema)
expressed in [JSON schema](http://json-schema.org/)

Things to see
=============
* View the [raw schema](schema/schema_1_0_final.json)
* **Demo:** [Autogenerate HTML form from schema](form.html)
* **Demo:** [Validate raw JSON](validate.html)

Libraries for many popular languages
====================================
Since we are using standard JSON schema, we can use any
[JSON-schema compliant software](http://json-schema.org/implementations.html) for **validation/parsing/generation and
more!**


Things to do still
==================
* Autogenerate schema documentation like at [Project Open Data schema](http://project-open-data.github.io/schema)
* Verify/correct/improve regex patterns for certain fields
* Some fields (like accessLevelComment) have conditions associated with them, need to find a way to express in schema
* Cleanup / improve look and feel of demos
* Cleanup demo code, remove redundant libraries and clean up project layout