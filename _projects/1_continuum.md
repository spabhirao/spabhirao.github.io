---
layout: page
title: Edge–Space–Cloud Continuum Orchestrator
description: Learned orchestration of workloads across edge, LEO-space, and cloud tiers under SLOs and intermittent connectivity.
img: assets/img/1.jpg
importance: 1
category: research
related_publications: true
---

Modern applications no longer live in a single datacenter — they span the edge, the cloud, and, increasingly, low-earth-orbit satellite tiers. SUTRA is building an orchestrator that decides *what to place where, when to scale, and when to migrate* across this continuum, learning policies that respect service-level objectives under mobility and intermittent connectivity.

This work builds directly on our lineage of resource-configuration and serverless research: optimal and robust configuration of complex services {% cite prasad2017rconf prasad2018rconfpd %}, deep-RL-based configuration management {% cite hegde2023counsel %}, and cross-cloud characterization and benchmarking of FaaS workflow platforms {% cite kulkarni2026faas kulkarni2024xfbench %}. The "space" tier is the new variable; the orchestration machinery is ours.

**Open directions:** LEO-aware scheduling, cost/latency/energy trade-offs, and reproducible cross-tier benchmarking.
