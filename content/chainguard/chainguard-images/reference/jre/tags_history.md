---
title: "jre Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the jre Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-04-15 03:08:24
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/jre/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/jre/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/jre/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/jre/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest`     | April 11th   | `sha256:cda68ba366e46bbda98cc73ea919ac048cbf81547f66448424d4f866963d1107` |
|  `latest-dev` | April 11th   | `sha256:88aceb7ab090f339ba70fed2c432dae806bece0aacf02805408fbf1a10b08392` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                                                            | Last Changed | Digest                                                                    |
|------------------------------------------------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `openjdk-8-dev` `openjdk-8.392.08-dev` `openjdk-8.392-dev`                        | April 12th   | `sha256:70066c1b52ddc68d9dde393c367b6e1af6b83c8bc6f5591abb61d66a0d5f5553` |
|  `openjdk-17.0.10` `openjdk-17` `openjdk-17.0`                                     | April 12th   | `sha256:4b16b3e9b03d8a91bb0435f67001754f82ff1fc65ab8d67b0114188a91acbb25` |
|  `openjdk-17.0.10-dev` `openjdk-17-dev` `openjdk-17.0-dev`                         | April 12th   | `sha256:84ec1db02e835ed53aba81513bc4e36d63f24fd728f2a68d4d830f6cd826fde6` |
|  `latest-dev` `openjdk-22.0-dev` `openjdk-22-dev` `openjdk-22.0.0-dev`             | April 12th   | `sha256:2e5ed6339e6ba8bbbf73203586d51b4a02549f75e9034b6a8f44930525d69162` |
|  `openjdk-16.0-dev` `openjdk-16.0.2-dev` `openjdk-16-dev` `openjdk-16.0.2.7-dev`   | April 12th   | `sha256:3e6db41f1a7a0fb8a05996d877d4977c3d06ee09e31906f5190d3531441af2ee` |
|  `openjdk-16.0` `openjdk-16.0.2.7` `openjdk-16` `openjdk-16.0.2`                   | April 12th   | `sha256:e4bcbb11e53587315fd039c60924b064bbd6951c7a5f2d8d683a0f3d5922500f` |
|  `openjdk-21` `openjdk-21.0` `openjdk-21.0.2`                                      | April 12th   | `sha256:ba10d0b63a7035b2291dd9051856e50be3517731ce6672cebc1f6daaba9d5ab8` |
|  `openjdk-8` `openjdk-8.392.08` `openjdk-8.392`                                    | April 12th   | `sha256:3721724cc370c9287c5ff95fe381c9650836f2fa8dc6ad916ca394b6cdc0857a` |
|  `openjdk-22.0` `openjdk-22.0.0` `openjdk-22` `latest`                             | April 12th   | `sha256:bc6824cd3807473ed4722d4519036f83b474ba332800daded94cefd178778850` |
|  `openjdk-11.0.22-dev` `openjdk-11-dev` `openjdk-11.0-dev`                         | April 12th   | `sha256:38736b2878c0068dab1451acfd6b7a79e4f471840f07066f7630a2c530847027` |
|  `openjdk-14.0.2` `openjdk-14` `openjdk-14.0` `openjdk-14.0.2.12`                  | April 12th   | `sha256:435712667300dc498f9e58999619e7b319316e7b5d184fe61a27db814555165e` |
|  `openjdk-21-dev` `openjdk-21.0.2-dev` `openjdk-21.0-dev`                          | April 12th   | `sha256:3d2aaabb17c620a1d469a9a500d3095370bd43c95537cbc4875a642ad0d5ae2f` |
|  `openjdk-15.0.10.5` `openjdk-15.0` `openjdk-15.0.10` `openjdk-15`                 | April 12th   | `sha256:baa5ddb14ba98494f781a30d7446152d2d74ee52f6911e90a63c09d217132bda` |
|  `openjdk-14.0.2.12-dev` `openjdk-14-dev` `openjdk-14.0.2-dev` `openjdk-14.0-dev`  | April 12th   | `sha256:4560bea6ae147520dd0f494771be23882203f6322c8244295d840546c757522e` |
|  `openjdk-15.0.10-dev` `openjdk-15-dev` `openjdk-15.0-dev` `openjdk-15.0.10.5-dev` | April 12th   | `sha256:62abfa9cb9440abec5e74aa1a526ba2990cae3bfed64cecb6bb41966503f035c` |
|  `openjdk-11.0.22` `openjdk-11` `openjdk-11.0`                                     | April 12th   | `sha256:15a3894105a0a488f6fd0bf7f877b62cbc8048606ef27cdb2a25468d3f10fa66` |

