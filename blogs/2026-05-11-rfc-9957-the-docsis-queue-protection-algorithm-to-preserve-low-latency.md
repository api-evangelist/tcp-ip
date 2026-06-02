---
title: 'RFC 9957: The DOCSIS Queue Protection Algorithm to Preserve Low Latency'
url: https://www.rfc-editor.org/info/rfc9957/
date: '2026-05-11'
author: ''
feed_url: https://www.rfc-editor.org/rfcrss.xml
---
This Informational RFC explains the specification of the queue protection algorithm introduced into Data-Over-Cable Service Interface Specification (DOCSIS) technology at version 3.1.  A shared low-latency queue relies on the non-queue-building behaviour of every traffic flow using it.  However, some flows might not take such care, either accidentally or maliciously.  If a queue is about to exceed a threshold level of delay, the Queue Protection algorithm can rapidly detect the flows most likely to be responsible.  It can then prevent harm to other traffic in the low-latency queue by ejecting selected packets (or all packets) of these flows.  This document is designed for four audiences: a) congestion control designers who need to understand how to keep on the "good" side of the algorithm; b) implementers of the algorithm who want to understand it in more depth; c) designers of algorithms with similar goals, perhaps for non-DOCSIS scenarios; and d) researchers interested in evaluating the algorithm.
