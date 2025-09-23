---
content_type: page
description: This section provides a lecture outline on sequence alignment with links
  to related materials and detailed lecture notes.
draft: false
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
parent_title: Lecture Notes
parent_type: CourseSection
parent_uid: 9e7f1aa8-38db-6648-8063-791ee60d518e
title: Significance of Alignments
uid: 11af0f00-dc54-78ce-d85a-e3567d5d0eb2
video_metadata:
  youtube_id: null
---
1. {{% resource_link "13ad751b-eab1-498d-acfd-0826b33ce061" "Sequence alignment" %}}
    - Inputs:
        - *Explicit*—Two sequences {a1, a2, …., am} and {b1, b2, …., bn} (e.g. query and database)
        - *Implicit*—A scoring procedure, e.g. pairwise scores s(ai,bj) and gap costs
    - Alignment algorithm: global, local, gapped, gapless (dynamic programming, applet)
    - Output: matching (sub)sequences with an overall score S . ({{% resource_link "cf86d751-86f4-4581-bfd0-f54b94e16648" "example" %}})
    - Significance: What is the probability of getting a score S by chance?
2. Statistics of gapless local alignments:
    - Random walks of scores as a function of matching length
    - {{% resource_link "07482498-8ea4-46bb-ac87-673508d9396e" "Extreme Value Distributions" %}}, the {{% resource_link "e532cca6-a5cb-49c0-b6f0-8309d4a7d596" "Gumbel distribution" %}}
    - Tails of distribution in a {{% resource_link "4ef017b7-bf7d-4971-9f34-9df27931a32f" "gapless alignment" %}}
    - The Karlin-Dembo formula
3. Gapped alignments and Statistical Physics
    - Transfer Matrix method for {{% resource_link "3c436836-eed5-49c6-8d85-188a02c7791d" "Directed Paths in Random Media (PDF)" %}}

- {{% resource_link "63036e1a-a69f-46e9-ab24-4d352472b2df" "Tutorial by Ralf Bundschuh" %}} on Sequence Alignment (and {{% resource_link "75376e21-e934-4979-bd02-0969ea3d810d" "associated paper" %}})

({{% resource_link "7432aff1-a1e8-4331-5134-3a618946f2e3" "Detailed Lecture Notes (PDF)" %}})