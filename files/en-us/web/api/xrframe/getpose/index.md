---
title: "XRFrame: getPose() method"
short-title: getPose()
slug: Web/API/XRFrame/getPose
page-type: web-api-instance-method
status:
  - experimental
browser-compat: api.XRFrame.getPose
---

{{APIRef("WebXR Device API")}}{{SeeCompatTable}}{{SecureContext_Header}}

The {{domxref("XRFrame")}} method **`getPose()`** returns the relative position and
orientation—the pose—of one {{domxref("XRSpace")}} to that of another space. With this, you can observe the motion of objects relative to each other and to fixed locations throughout the scene.

For example, to get the position of a controller relative to the viewer's head, you would compare the controller's {{domxref("XRInputSource.gripSpace", "gripSpace")}} to the {{domxref("XRReferenceSpace")}} of type `viewer`.

## Syntax

```js-nolint
getPose(space, baseSpace)
```

### Parameters

- `space`
  - : An {{domxref("XRSpace")}} specifying the space for which to obtain an
    {{domxref("XRPose")}} describing the item's position and orientation.
- `baseSpace`
  - : An {{domxref("XRSpace")}} to use as the base or origin for the purposes of computing
    the relative position and orientation.

### Return value

An {{domxref("XRPose")}} object specifying the position and orientation, relative to
the {{domxref("XRSpace")}} indicated by `baseSpace`.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
