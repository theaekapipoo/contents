---
title: "XRDepthInformation: width property"
short-title: width
slug: Web/API/XRDepthInformation/width
page-type: web-api-instance-property
status:
  - experimental
browser-compat: api.XRDepthInformation.width
---

{{APIRef("WebXR Device API")}}{{SeeCompatTable}}{{SecureContext_Header}}

The _read-only_ **`width`** property of the {{DOMxRef("XRDepthInformation")}} interface contains the width of the depth buffer (number of columns).

## Value

An unsigned long integer.

## Examples

Use {{domxref("XRFrame.getDepthInformation()")}} (CPU) or {{domxref("XRWebGLBinding.getDepthInformation()")}} (WebGL) to obtain depth information. The returned objects will contain the `width` of the depth buffer, which you can use for further calculations.

```js
const smallerDepthDimension = Math.min(depthInfo.width, depthInfo.height);
const largerDepthDimension = Math.max(depthInfo.width, depthInfo.height);
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
