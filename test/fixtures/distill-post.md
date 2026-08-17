---
layout: distill
title: distill integration test fixture
description: minimal fixture post used only by test/integration_distill.sh to verify the distill layout renders
date: 2021-05-22
giscus_comments: true
mermaid:
  enabled: true
tikzjax: true

authors:
  - name: Test Fixture
    url: "https://github.com/al-org-dev"
    affiliations:
      name: al-folio

toc:
  - name: Fixture Section
---

This post is a build-time fixture, not real site content. It exists solely so
`test/integration_distill.sh` can verify that the `distill` layout, the
distillpub runtime, mermaid, tikzjax, and giscus comments all still render
correctly. It is copied into `_posts/` only for the duration of the test run
and is never committed there.

## Fixture Section

Some inline math to keep the layout non-trivial: $E = mc^2$.
