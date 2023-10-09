
# Scenario (1/6)

## Status

Approved

## Context

The application must be accessible in offline mode. 

## Decision

The type of this app will be a Native app. If it was a web app, it would need internet connection to be used. Since the requirements don't mention the app being used on multiple phone operating systems, it will not be hybrid.

## Consequences

Because of the app type being native, we can optimize the app according to the native operating system. We can get better performance this way. However, it is costlier and will take more development time.
