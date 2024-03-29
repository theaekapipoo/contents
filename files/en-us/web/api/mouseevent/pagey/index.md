---
title: "MouseEvent: pageY property"
short-title: pageY
slug: Web/API/MouseEvent/pageY
page-type: web-api-instance-property
browser-compat: api.MouseEvent.pageY
---

{{APIRef("UI Events")}}

The **`pageY`** read-only property of the {{domxref("MouseEvent")}} interface returns the Y (vertical) coordinate in pixels of the event relative to the whole document.
This property takes into account any vertical scrolling of the page.

## Value

A `double` floating point value.

## Examples

```js
let pageY = event.pageY;
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("MouseEvent.pageX")}}
- [Coordinate systems](/en-US/docs/Web/CSS/CSSOM_view/Coordinate_systems)
