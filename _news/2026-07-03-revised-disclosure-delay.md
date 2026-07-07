---
layout: single
toc: false
title: "CPANSec Has Revised Our Default Disclosure Dates"
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
members of the CPANSec CNA discussed disclosure periods and decided to reduce the _default_ disclosure date ("embargo") for publishing vulnerabilities from 28 days to 14 days.

Some CPAN authors have expressed concerns about this change so we wanted to detail the reasons for this change:

- LLMs are powering vulnerability discovery, and many consider security issues that AI can discover to be public already.
- The vulnerability landscape is becoming more urgent.
  Informing users and the community faster of a vulnerability, allows for mitigations regardless of upstream action.
- To adjust to this new situation, long embargoes are going away.
- When we can confirm the validity of a vulnerability we assign a CVE indentifier immediately, notify authors about the vulnerability, and offer a default 14-day planned disclosure date before the CVE is published.
-  This is the standard process.
   Upon request we will work with maintainers who need longer disclosure periods.
- We may post issues about a vulnerability in an issue tracker or pull request as part of the disclosure process.

See [CPANSec Has Revied Our Default Disclosure Date](/docs/revised-disclosure-delay) for the full document.
