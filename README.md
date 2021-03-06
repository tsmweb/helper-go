# helper-go
Helper for services written in Golang.

## Features
* Package auth provides authentication and authorization methods using JSON Web Tokens.
* Package cerror provides customized errors that represent status for HTTP responses and specific treatments.
* Package concurrent/flow provides a Flow implementation to perform background processing and notify your subscribers through an Emitter.
* Package concurrent/executor provides an implementation of the Executor to perform background processing, limiting resource consumption when executing a collection of jobs.
* Package controller implements a Controller with utility methods.
* Package integration is a simple wrapper for the kafka-go segmentio library, providing tools for consuming and producing events and working with the event outbox pattern.
* Package middleware provides settings for CORS, GZIP and JWT token validation.
* Package hashutil provides utility functions to generate and validate hash.
