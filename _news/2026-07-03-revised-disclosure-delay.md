---
layout: single
toc: false
title: "CPANSec CNA Has Revised Our Default Disclosure Dates"
date: 2026-07-06 18:00:00 +0100
collection: news
tags: cna cve embargo llm ai disclosure
authors:
  - robrwo
author_profile: false
header:
  overlay_image: /assets/images/header/SJN07451.JPG
  teaser: assets/images/teaser/SJN07974.JPG
  overlay_filter: 0.6
  caption: "Photo credit: [@sjn](https://github.com/sjn)"
---

At the [Perl Toolchain Summit in April 2026](https://perltoolchainsummit.org/pts2026/),
members of the CPANSec CNA decided to reduce the _default_ disclosure date ("embargo") for publishing vulnerabilities from 28 days to 14 days.

The feedback from some CPAN authors about this change has not always been positive, so we wanted to write down in detail why we have made this change:

- LLMs are powering vulnerability discovery, and many consider security issues that AI can discover to be public already.
- The vulnerability landscape is becoming more urgent.
  Informing users and the community faster of a vulnerability, allows for mitigations regardless of upstream action.
- To adjust to this new situation, long embargoes are going away.
- When we can confirm the validity of a vulnerability we assign a CVE indentifier immediately, notify authors about the vulnerability, and offer a default 14-day planned disclosure date before the CVE is published.
-  This is the standard process.
   We can do longer disclosure delays if there is a good rationale.
- We may post issues about a vulnerability in an issue tracker or pull request as part of the disclosure process.

See [CPANSec CNA Revised Grace Period](/docs/revised-disclosure-delay) for the full document.
