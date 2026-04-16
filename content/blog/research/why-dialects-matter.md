---
title: "Why Dialect Robustness Is a Fairness Problem"
date: 2025-09-01
---

Most NLP benchmarks are built on standard varieties of a language. English means American English. Arabic means Modern Standard Arabic. The implicit assumption is that a model performing well on these benchmarks performs well for everyone who speaks the language.

It doesn't.

Speakers of non-standard dialects — African American English, Nigerian Pidgin, Egyptian Arabic — consistently receive worse outcomes from NLP systems. Worse transcriptions, worse sentiment analysis, worse information retrieval. This isn't a niche concern; it's a systematic exclusion of hundreds of millions of people from the benefits of language technology.

The framing matters here. Dialect robustness is often treated as a *performance* problem: how do we get higher numbers on dialect benchmarks? But the more honest framing is that it is a *fairness* problem: whose language use is treated as the default, and who bears the cost when systems fail?

This distinction shapes everything — what datasets we build, what evaluation metrics we use, and what "solved" would even mean.
