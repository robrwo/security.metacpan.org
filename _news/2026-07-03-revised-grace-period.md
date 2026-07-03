---
layout: single
toc: false
title: "CPANSec CNA Revised Grace Period"
date: 2026-07-03 11:00:00 +0000
collection: news
date: 2026-07-03 12:00:00 +0000
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
members of the CPANSec CNA decided to reduce the _default_ grace period ("embargo") for publishing vulnerabilities from 28 days to 14 days.

The feedback from some CPAN authors about this change has not always been positive, so we wanted to write down in detail why we have made this change:

- LLMs are powering vulnerability discovery, and many consider their results to be public already.
- This means the vulnerability landscape is becoming more urgent. Slow response times mean more time to exploit.
- To reduce the impact of this change, generous embargoes are going away.
- Instead, we assign a CVE immediately, notify authors about the vulnerability, and offer a default 14-day grace period before the CVE is published.
- We may post issues about a vulnerability in an issue tracker or pull request as part of the disclosure process.
- This grace period can still be extended, if the author offers a reason.

See [CPANSec CNA Revised Grace Period](/docs/revised-grace-period) for the full document.
