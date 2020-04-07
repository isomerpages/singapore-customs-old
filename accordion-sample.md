---
title: Accordion Sample
permalink: /accordion-sample
accordion:
  - title: title 1
    content: >
      This is folded line
      everything is made into one line
  - title: title 2
    content: |
      Content for title 2
      This is a second line

      A third line after a line break
  - title: title 3
    content: |
      * item 1
      * item 2
      * item 3

      testing lines 4

      testing lines 5
  - title: title 4
    content: |
      1. item 1
      2. item 2
      3. item 3

      testing lines 4

      testing lines 5
---

# Accordion Test 6

This is the first paragraph that should appear before the accordion.

{% include accordion.html %}

This is the paragraph that should appear after the accordion.