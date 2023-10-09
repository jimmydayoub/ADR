
## Status

Approved

## Context

We will need to implement techniques to load images from our servers to the client. We also need it to be performant, as in the client's loading times.

## Decision

We will be implementing lazy loading as a technique. Due to the massive amount of pictures that are going to be loaded in at once, lazy loading will only load a part of the images and not the whole page. This will increase performance. Besides that, we can implement caching, so that clients can load the images faster once they reload the image.

## Consequences

Nothing. Just more performance.
