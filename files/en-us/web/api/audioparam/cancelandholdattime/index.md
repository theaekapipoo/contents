---
title: "AudioParam: cancelAndHoldAtTime() method"
short-title: cancelAndHoldAtTime()
slug: Web/API/AudioParam/cancelAndHoldAtTime
page-type: web-api-instance-method
browser-compat: api.AudioParam.cancelAndHoldAtTime
---

{{APIRef("Web Audio API")}}

The **`cancelAndHoldAtTime()`** method of the
{{domxref("AudioParam")}} interface cancels all scheduled future changes to the
`AudioParam` but holds its value at a given time until further changes are
made using other methods.

## Syntax

```js-nolint
cancelAndHoldAtTime(cancelTime)
```

### Parameters

- `cancelTime`
  - : A double representing the time (in seconds) after the [`AudioContext`](/en-US/docs/Web/API/AudioContext) was
    first created after which all scheduled changes will be cancelled.

### Return value

A reference to the {{domxref("AudioParam")}} it was called on.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
