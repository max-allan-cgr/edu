---
title: "argo-cli Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the argo-cli Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-04-12 00:54:01
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/argo-cli/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/argo-cli/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/argo-cli/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/argo-cli/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | April 11th   | `sha256:be15a22e219987409b1eee123c89c303c97183df0cda4c470d36d4ec8c862a13` |
|  `latest`     | April 4th    | `sha256:18330bb880f458c699894c0c8481562b693da3bc7126c11bfdadbde3be78c4ea` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                     | Last Changed | Digest                                                                    |
|---------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `3-dev` `latest-dev` `3.5-dev` `3.5.5-dev` | April 11th   | `sha256:220a4514ddfc1dad7b1e9cfe05a99559bcbd4fd9af0642c6da5015adb6dd54af` |
|  `3.5` `latest` `3.5.5` `3`                 | April 4th    | `sha256:02c1d1ae567247c43fa2552bf774838b4803d267ad92c23c0bfd96ac303afc7c` |

