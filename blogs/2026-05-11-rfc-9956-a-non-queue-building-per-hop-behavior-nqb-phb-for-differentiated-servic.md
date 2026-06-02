---
title: 'RFC 9956: A Non-Queue-Building Per-Hop Behavior (NQB PHB) for Differentiated
  Services'
url: https://www.rfc-editor.org/info/rfc9956/
date: '2026-05-11'
author: ''
feed_url: https://www.rfc-editor.org/rfcrss.xml
---
This document specifies characteristics of a Non-Queue-Building Per-Hop Behavior (NQB PHB).  The NQB PHB provides a shallow-buffered, best-effort service as a complement to a Default deep-buffered, best-effort service for Internet services.  The purpose of this NQB PHB is to provide a separate queue that enables smooth (i.e., non-bursty), low-data-rate, application-limited traffic microflows, to avoid the delay, delay variation and loss that would ordinarily be caused by sharing a queue with bursty, capacity-seeking traffic.  This PHB is implemented without prioritization and can be implemented without rate policing, making it suitable for environments where the use of these features is restricted.  The NQB PHB has been developed primarily for use by access network segments, where queuing delay and queuing loss caused by Queue-Building (QB) protocols are manifested; however, its use is not limited to such segments.  In particular, the application of NQB PHB to cable broadband links, Wi-Fi links, and mobile network radio/core segments are discussed in this document.  This document recommends a specific Differentiated Services Code Point (DSCP) to identify NQB microflows and updates the guidance in RFC 8325 on mapping Differentiated Services (Diffserv or DS) to IEEE 802.11 for this codepoint.
