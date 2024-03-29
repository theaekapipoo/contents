---
title: "XRSession: interactionMode property"
short-title: interactionMode
slug: Web/API/XRSession/interactionMode
page-type: web-api-instance-property
status:
  - experimental
browser-compat: api.XRSession.interactionMode
---

{{APIRef("WebXR Device API")}}{{SeeCompatTable}}{{SecureContext_Header}}

The {{domxref("XRSession")}} interface's _read-only_ **`interactionMode`** property
describes the best space (according to the user agent) for the application to draw an interactive UI for the current session.

## Value

A string describing the best space (according to the user agent) for the application to draw an interactive UI
for the current session.

Possible values are:

- `screen-space`
  - : Indicates that the UI should be drawn directly to the screen without projection. This is typically the mode reported from handheld devices.
- `world-space`
  - : Indicates that the UI should be drawn in the world, some distance from the user, so that they may interact with it using controllers. This is typically the mode reported from headworn devices.

## Examples

```js
if (xrSession.interactionMode === "world-space") {
  // draw UI in the world
} else {
  // draw UI directly to the screen
}
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
