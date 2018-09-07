Jasny Swagger (phpdoc)
===

[![Build Status](https://travis-ci.org/jasny/swagger-phpdoc.svg?branch=master)](https://travis-ci.org/jasny/swagger-phpdoc)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/jasny/swagger-phpdoc/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/jasny/swagger-phpdoc/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/jasny/swagger-phpdoc/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/jasny/swagger-phpdoc/?branch=master)
[![Packagist Stable Version](https://img.shields.io/packagist/v/jasny/swagger-phpdoc.svg)](https://packagist.org/packages/jasny/swagger-phpdoc)
[![Packagist License](https://img.shields.io/packagist/l/jasny/swagger-phpdoc.svg)](https://packagist.org/packages/jasny/swagger-phpdoc)

Document your code and keep a live and reusable OpenAPI (Swagger) specification. This specification can be the core of
your API-driven project: generate documentation, servers, clients, tests and much more based on the rich
[OpenAPI ecosystem of tools](http://swagger.io/).

This project is inspired on the JavaScript project [swagger-jsdoc](https://github.com/Surnet/swagger-jsdoc).

### Goals

**swagger-phpdoc** enables you to integrate [Swagger](http://swagger.io) using annotations in your code. Just add
`@swagger` on top of your DocComment and declare the meaning of your code in `yaml` complying to the OpenAPI
specification. Anything above `@swagger` is ignored.

`swagger-phpdoc` will parse your documentation from your actual living code and output an OpenAPI specification to
integrate any server and client technology as long as both sides comply with the specification.

Thus, the `swagger-phpdoc` project assumes that you want document your existing working code in a way to "give life"
to it, generating a specification which can then be fed into other Swagger tools, and not the vice-versa.

If you prefer to write the OpenAPI specification first and separately, you might check other projects facilitating 
his, such as

- [swagger-editor](http://swagger.io/swagger-editor/)
- [swagger-node](https://github.com/swagger-api/swagger-node)

This project differs from zircote/swagger-php which uses the Doctrine Annotation syntax instead of plain `yaml`.

### Supported versions

- OpenAPI 3.x

You can find the corresponding documentation in the
[official repository of the specification](https://github.com/OAI/OpenAPI-Specification).


Installation
---

    composer require jasny/swagger-phpdoc

