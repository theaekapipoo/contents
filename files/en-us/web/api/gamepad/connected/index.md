---
title: "Gamepad: connected property"
short-title: connected
slug: Web/API/Gamepad/connected
page-type: web-api-instance-property
browser-compat: api.Gamepad.connected
---

{{APIRef("Gamepad API")}}{{SecureContext_Header}}

The **`Gamepad.connected`** property of the
{{domxref("Gamepad") }} interface returns a boolean indicating whether the gamepad is
still connected to the system.

If the gamepad is connected, the value is `true`; if not, it is
`false`.

## Value

A boolean.

## Examples

```js
const gp = navigator.getGamepads()[0];
console.log(gp.connected);
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

[Using the Gamepad API](/en-US/docs/Web/API/Gamepad_API/Using_the_Gamepad_API)
