---
layout: page
title: Knowledge Plane for SDN
description: Learned embeddings of network state to build a knowledge plane for software-defined networks.
img: assets/img/3.jpg
importance: 2
category: research
related_publications: true
---

Software-defined networking separated control from data; the missing layer is a **knowledge plane** — a learned, queryable representation of network state that drives control decisions. SUTRA studies knowledge embeddings for networks: compressing telemetry, topology, and flow behaviour into representations a controller can reason over.

It descends from our work on distributed SDN control and scalable service chaining {% cite chattopadhyay2020amalgam %} and on SDN security {% cite prasad2015sdn %}. The new capability is representation learning over network graphs and telemetry — a natural sibling to the continuum orchestrator, which consumes exactly this kind of learned state.

**Open directions:** graph representation learning for control, intent-to-configuration translation, and trustworthy/robust knowledge planes.
