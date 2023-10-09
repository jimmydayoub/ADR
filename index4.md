# Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections:

# Title

## Status

Approved

## Context

We need a service that will provide analytics on our app, like tracking product views, purchases, etc.

## Decision

We will be using Firebase Analytics. It is compatible with React Native: "npm i @react-native-firebase/analytics" 

## Consequences

Firebase has a free plan that we can use to test the water. If all goes well, we can start paying for it.

