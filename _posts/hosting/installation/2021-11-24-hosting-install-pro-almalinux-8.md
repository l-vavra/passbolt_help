---
title: Install Passbolt PRO on AlmaLinux 8
date: 2021-11-24 00:00:00 Z
description: How to install Passbolt PRO on
card_title: AlmaLinux 8
card_teaser: Install passbolt PRO on AlmaLinux
card_position: 10
icon: fa-almalinux
categories: [hosting,install,pro]
sidebar: hosting
layout: default
slug: almalinux
permalink: /:categories/:slug.html
---

{% assign product = 'pro' %}
{% assign distribution = 'almalinux' %}
{% assign distributionVersion = '8' %}
{% assign distributionSlug = 'almalinux' %}
{% assign distributionLabel = 'AlmaLinux' %}
{% assign distributionPackage = 'dnf' %}

{% include layout/row_start.html %}
{% include layout/col_start.html column="7" %}

{% include hosting/install/packages/debian/install-debian-package.md %}

{% include date/updated.html %}

{% include layout/col_end.html %}
{% include layout/col_start.html column="4 last push1" %}

{% include aside/pro-support.html %}

{% include aside/contribute.html %}

{% include layout/row_end.html %}
