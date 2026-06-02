---
title: 'RFC 9959: Careful Resume: Convergence of Congestion Control from Retained
  State'
url: https://www.rfc-editor.org/info/rfc9959/
date: '2026-05-11'
author: ''
feed_url: https://www.rfc-editor.org/rfcrss.xml
---
This document specifies a cautious method for Internet transports that enables fast startup of Congestion Control (CC) for a wide range of connections, known as "Careful Resume". It reuses a set of computed CC parameters that are based on previously observed path characteristics between the same pair of transport endpoints. These parameters are saved, allowing them to be later used to modify the CC behaviour of a subsequent connection.

 This document describes the assumptions and defines the requirements for how a sender utilises these parameters to provide opportunities for a connection to more rapidly get up to speed and utilise available capacity. It discusses how the use of this method impacts the capacity at a shared network bottleneck and the safe response that is needed after any indication that the new rate is inappropriate.
