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
1. {{% resource_link "854e6c45-05c0-4987-b8e5-c93b9f612821" "Sequence alignment" %}}
    - Inputs:
        - *Explicit*—Two sequences {a1, a2, …., am} and {b1, b2, …., bn} (e.g. query and database)
        - *Implicit*—A scoring procedure, e.g. pairwise scores s(ai,bj) and gap costs
    - Alignment algorithm: global, local, gapped, gapless (dynamic programming, applet)
    - Output: matching (sub)sequences with an overall score S . ({{% resource_link "84a35b85-6ab1-4bb7-8791-e2d5536d2fb5" "example" %}})
    - Significance: What is the probability of getting a score S by chance?
2. Statistics of gapless local alignments:
    - Random walks of scores as a function of matching length
    - {{% resource_link "e70f48fa-3bfe-42b5-8640-fa76a46943c9" "Extreme Value Distributions" %}}, the {{% resource_link "666346bd-c635-42ae-a62d-a000b18f260a" "Gumbel distribution" %}}
    - Tails of distribution in a {{% resource_link "06fdb32d-e952-42c3-b482-e9fd2eba17f6" "gapless alignment" %}}
    - The Karlin-Dembo formula
3. Gapped alignments and Statistical Physics
    - Transfer Matrix method for {{% resource_link "3431e042-65ed-45dc-b710-93ae3a33105b" "Directed Paths in Random Media (PDF)" %}}

- {{% resource_link "5dd13004-7f67-466d-b638-52831b8657a0" "Tutorial by Ralf Bundschuh" %}} on Sequence Alignment (and {{% resource_link "fc710a68-7e72-4354-9c3b-f0bf204ea8ea" "associated paper" %}})

({{% resource_link "7432aff1-a1e8-4331-5134-3a618946f2e3" "Detailed Lecture Notes (PDF)" %}})