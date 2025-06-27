---
title: "What are extracted features?"
description: "What are extracted features?"
nav_order: 3
date created: 2025-03-21
last revised: 2025-05-28
author: Janet Swatscheno
owner: Janet Swatscheno
layout: "post"
---

# What are extracted features?

Extracted features are pieces of information pulled from the volumes in the [HathiTrust Digital Library](https://www.hathitrust.org/). This includes bibliographic information (like title, author, and publication details) and detailed page-level information about the text and how it is structured.

Importantly, each extracted features file includes word counts for every word on the page, but they are not in order. This is called a "bag of words" model and is a simple way to represent text in a way that computers can understand and complies with U.S. copyright law.

Want to learn more about the dataset’s purpose, how it was built, and what it includes? You’ll find a complete overview on the [EF Dataset documentation page](https://htrc.atlassian.net/wiki/spaces/COM/pages/43295914/Extracted+Features+v.2.0).

HTRC Extracted Features 2.0 is the most current version of the dataset. It is composed of 17+ million JSON files representing a snapshot of the HathiTrust corpus from February 2020. This version includes non-consumptive data from both public-domain and in-copyright books.

## Extracted features data model

Extracted features files are JSON files that contain bibliographic meatdata for each volume such as title, author, place of publication, etc.

The files also contain page-level feature data such as part-of-speech tagged term token counts, header/footer identification, marginal character counts, and much more.

<img src="images/efmodel.png" alt="diagram of extracted features data model showing page features nested in a page which is nested in a volume" width="300"/>
