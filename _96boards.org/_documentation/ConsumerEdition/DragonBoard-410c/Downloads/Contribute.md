---
layout: empty-container-page
page_title: Contributing to Linaro releases for Dragonboard 410c
permalink: /documentation/ConsumerEdition/DragonBoard-410c/Downloads/Contribute.md/
breadcrumb-page_title: Contribute to Linaro Releases for DragonBoard-410c
breadcrumb-section: Documentation
breadcrumb-section-two: Consumer Edition
breadcrumb-section-three: DragonBoard-410c
breadcrumb-section-four: Downloads
breadcrumb-subpage_title: Contribute to Releases
description: |-
    This page provides instructions for developers willing to contribute to the Linaro releases for Dragonboard 410c. This is applicable to the following components; Linaro maintained kernel (a.k.a LT kernel), Linaro Debian builds and Linaro OpenEmbedded builds.
---
# Contributing to Linaro releases for Dragonboard 410c

This page provides instructions for developers willing to contribute to the Linaro releases for Dragonboard 410c. This is applicable to the following components:
* Linaro maintained kernel (a.k.a LT kernel)
* Linaro Debian builds
* Linaro OpenEmbedded builds

# How to contribute

The following mailing list has been created to contributions:

https://lists.96boards.org/mailman/listinfo/dragonboard

This is a public mailing open to any developer.

# General rules

* This mailing list is not a substitute for proper upstreaming. We are willing to accept patches against our release (e.g. generally that means against a stable/LTS branch), if the submitters are also willing to upstream their changes. We will not be maintaining orphaned patches forever.
* Patches should be sent to the mailing list, as inline patches.
* When we do kernel upgrade we might not carry external patches, and they will have to be sent and tested again, if they have not been upstreamed in between.
* When patches add support for new hardware (such as other boards based on the same chipset), Linaro will not test, nor support these additional boards. It will be the submitter responsibility to maintain and test these patches over time, and also answer any support request (on the mailing list, on the forum or on IRC).
* The mailing list is for patches and code. Regular support will continue to be on the 96boards forum
* We expect all discussions to be held on the public mailing list and discourage private discussions over emails as much as possible.
* Of course any
* Patches will be reviewed by the maintainers of the involved sub projects, and these developers are responsible to accept or refuse any contribution.
