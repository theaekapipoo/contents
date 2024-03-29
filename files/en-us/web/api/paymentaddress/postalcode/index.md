---
title: "PaymentAddress: postalCode property"
short-title: postalCode
slug: Web/API/PaymentAddress/postalCode
page-type: web-api-instance-property
status:
  - deprecated
  - non-standard
browser-compat: api.PaymentAddress.postalCode
---

{{APIRef("Payment Request API")}}{{SecureContext_Header}}{{Deprecated_Header}}{{Non-standard_Header}}

The **`postalCode`** read-only property of the
{{domxref('PaymentAddress')}} interface returns a string containing a code used by a
jurisdiction for mail routing, for example, the [ZIP Code](https://en.wikipedia.org/wiki/ZIP_Code)
in the United States or the [Postal Index Number](https://en.wikipedia.org/wiki/Postal_Index_Number) (PIN code)
in India.

## Value

A string which contains the postal code portion of the address. A
postal code is a string (either numeric or alphanumeric) which is used by a postal
service to optimize mail routing and delivery.

Various countries use different terms for this. In most of the world, it's known as the
"post code" or "postal code." In the United States, the ZIP code is used. India uses PIN
codes.

## Browser compatibility

{{Compat}}

## See also

- Universal Postal Union: [Universal Post\*Code® Database](https://www.upu.int/en/Postal-Solutions/Programmes-Services/Addressing-Solutions)
