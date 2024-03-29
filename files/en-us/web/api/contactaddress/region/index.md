---
title: "ContactAddress: region property"
short-title: region
slug: Web/API/ContactAddress/region
page-type: web-api-instance-property
status:
  - experimental
browser-compat: api.ContactAddress.region
---

{{securecontext_header}}{{APIRef("Contact Picker API")}}{{SeeCompatTable}}

The read-only **`region`** property of the {{domxref("ContactAddress")}} interface returns a string containing the top-level administrative subdivision of the country in which the address is located. This may be a state, province, oblast, or prefecture.

## Value

A string specifying the top-level administrative subdivision within the country in which the address is located. This region has different names in different countries, such as: state, province, oblast, prefecture, or county.

## Usage notes

In some countries, like Belgium, it's uncommon for people to provide a region as part of their postal address. In such cases, the browser returns an empty string as the value of `region`. However, the address should still be acceptable to use for its intended purpose (e.g., to ship a product). However, always verify addresses to make sure what the user provides is usable.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
