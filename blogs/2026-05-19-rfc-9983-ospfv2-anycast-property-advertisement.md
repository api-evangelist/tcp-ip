---
title: 'RFC 9983: OSPFv2 Anycast Property Advertisement'
url: https://www.rfc-editor.org/info/rfc9983/
date: '2026-05-19'
author: ''
feed_url: https://www.rfc-editor.org/rfcrss.xml
---
An IP prefix may be configured as anycast and, as such, the same value can be advertised by multiple routers. It is useful for other routers to know that the advertisement is for an anycast prefix.

 This document defines a new flag in the OSPFv2 Extended Prefix TLV Flags to advertise the anycast property. The document also specifies a companion YANG module for managing this function.
