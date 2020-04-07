---
title: Accordion Sample 2
permalink: /accordion-sample
accordion:
  - title: title 1
    content: Content for title 1.1
  - title: title 2
    content: |
      Content for title 2
      This is a second line

      A third line after a line break
---

# Accordion Test

This is the first paragraph that should appear before the accordion.

{% include accordion.html %}

This is the paragraph that should appear after the accordion.