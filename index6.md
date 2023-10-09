# Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections:

# Title

## Status

Approved. 

## Context

We need a localization framework. 

## Decision

We will use Google Translate's API. It is also compatible with React Native: "npm i translate-google-api". 

## Consequences

The cost of using Google Translate is that we will have to pay 20$ for 500,000 to 1B characters translated per month. Lower values will be free.
