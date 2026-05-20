---
title: "The Trouble with Topology Aware Routing, Part II: Introducing High Availability, Zone-Aware Load Balancing"
url: "https://www.buoyant.io/blog/topology-aware-routing-introducing-high-availability-zone-aware-load-balancing"
date: "Wed, 03 Jul 2024 18:22:00 GMT"
author: ""
feed_url: "https://buoyant.io/blog/rss.xml"
---
Part I of this post covered TAR, a Kubernetes feature that restricts traffic within an availability zone from crossing to other zones, cutting cloud spend. But TAR is not without drawbacks: it can lead to worse overall system reliability.
