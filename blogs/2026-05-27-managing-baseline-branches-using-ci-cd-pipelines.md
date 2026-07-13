---
title: "Managing Baseline Branches Using CI/CD Pipelines"
url: "https://app14743.cloudwayssites.com/blog/managing-baseline-branches-using-ci-cd-pipelines/"
date: "2026-05-27"
author: "Tim Hosey"
feed_url: "https://applitools.com/blog/feed/"
---
TL;DR To automate Applitools baseline branch merging within CI/CD pipelines, use a Shared Library to call the Applitools Eyes Server API. This eliminates manual baseline maintenance in the Eyes Dashboard, ensures visual consistency across Git branches, and establishes automated gatekeeping. Best practices dictate running verification ( onlyCheck: true ) during Pull Requests and executing actual merges ( onlyCheck: false ) post-merge in CD pipelines to avoid blocking active runner threads.
