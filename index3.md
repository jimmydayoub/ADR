# Decision record template by Michael Nygard

This is the template in [Documenting architecture decisions - Michael Nygard](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions).
You can use [adr-tools](https://github.com/npryce/adr-tools) for managing the ADR files.

In each ADR file, write these sections:

# Title

## Status

Approved

## Context

We will need to use a payment provider to accept payments for this app.

## Decision

We are going to be using PayPal. It is a well-known service that supports more than 200 countries. The reason is because it is secure. This will reduce fears of the customer not wanting to put their credit cards due to fears of it being stolen.

## Consequences

We will have to pay 2.9% service fees by using this payment provider.
