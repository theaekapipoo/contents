---
title: "RTCInboundRtpStreamStats: bytesReceived property"
short-title: bytesReceived
slug: Web/API/RTCInboundRtpStreamStats/bytesReceived
page-type: web-api-instance-property
browser-compat: api.RTCStatsReport.type_inbound-rtp.bytesReceived
---

{{APIRef("WebRTC")}}

The {{domxref("RTCInboundRtpStreamStats")}} dictionary's
**`bytesReceived`** property is an integer value which
indicates the total number of bytes received so far from this synchronization source
(SSRC).

## Value

An unsigned integer value indicating the total number of bytes received so far on this
RTP stream, not including header and padding bytes. This value can be used to calculate
an approximation of the average media data rate:

```js
avgDataRate = rtcInboundRtpStreamStats.bytesReceived / elapsedTime;
```

This value gets reset to zero if the sender's SSRC identifier changes for any reason.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
