---
title: "The trouble with Topology Aware Routing: Sacrificing reliability in the name of cost savings"
url: "https://www.buoyant.io/blog/the-trouble-with-topology-aware-routing-sacrificing-reliability-to-avoid-cross-zone-traffic"
date: "Wed, 05 Jun 2024 13:15:00 GMT"
author: ""
feed_url: "https://buoyant.io/blog/rss.xml"
---
Topology Aware Routing is a feature of Kubernetes that prevents cluster traffic within one availability zone from crossing to another availability zone. For high-traffic applications deployed in multi-zone clusters, this can provide significant cost savings. However, Topology Aware Routing is designed to always prohibit cross-zone traffic, regardless of overall system health or performance.
