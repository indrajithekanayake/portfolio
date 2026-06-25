---
title: "OpenSearch for Association Rule Mining: With ActivityWatch"
draft: false
date: 2026-06-15
tags:
  - 2026_talks
  - opensearch
---
This session was about the recent productivity study we ran in our open source lab (OSL). I walked through the end-to-end architecture: extracting device telemetry, transforming it into task sessions, and running association rule mining on top of OpenSearch to compute support and confidence for goal-relevant activity patterns. The entire setup runs locally, therefore no risk of activity data theft.  
  
ActivityWatch is a cross-platform open-source time tracker that collects telemetry on how we spend time on devices. It comes with watchers that can do all the data collection from AFK to browser windows. In our setup, ActivityWatch runs on each device, and OpenSearch is self-hosted on our research lab’s local LAN, and then we ingest logs into it every 10 seconds using API-based ingestion. While ActivityWatch runs, users tag their intended task (e.g., #learn, #java). We align tags with telemetry windows, sessionize events into transactions (items[]=apps/domains, duration), and mine rules with support/confidence/lift per tag. If the current window drifts from the active tag with high confidence for a short period, we send a nudge reminding they are distracted from the original goal.

**Event Slides:**

<iframe src="https://drive.google.com/file/d/1AJ3wYXHaWZvKcE4Fk6adqmCH_3Dh4mOz/preview" width="640" height="480"></iframe>
**Event Photographs:**

<p>
  <img src="../../images/2026-opensearchcon-india.jpg" alt="India OpenSearchCon1"/>
  <img src="../../images/2026-opensearchcon-india-2.jpg" alt="India OpenSearchCon2"/> 
</p>

<span style="font-size:0.8em;"> * location: Jio World Convention Centre, Mumbai, India</span>

