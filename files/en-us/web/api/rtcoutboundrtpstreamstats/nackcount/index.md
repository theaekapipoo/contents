---
title: "RTCOutboundRtpStreamStats: nackCount property"
short-title: nackCount
slug: Web/API/RTCOutboundRtpStreamStats/nackCount
page-type: web-api-instance-property
browser-compat: api.RTCStatsReport.type_outbound-rtp.nackCount
---

{{APIRef("WebRTC")}}

The **`nackCount`** property of the
{{domxref("RTCOutboundRtpStreamStats")}} dictionary is a numeric value indicating the
number of times the {{domxref("RTCRtpSender")}} described by this object received a
**NACK** packet from the remote receiver.

A NACK (Negative
ACKnowledgement, also called "Generic NACK") packet is used by the
{{domxref("RTCRtpReceiver")}} to inform the sender that one or more {{Glossary("RTP")}}
packets it sent were lost in transport.

## Value

An integer value indicating how many times the sender received a NACK packet from the
receiver, indicating the loss of one or more packets.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
