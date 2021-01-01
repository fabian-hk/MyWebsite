---
title: "Improving OAuth App-to-App Security"
date: 2020-11-27
draft: false
github_link: ""
author: "Fabian Hauck, Daniel Fett, Joseph Heenan"
tags:
  - OAuth 2.0
  - OpenID Connect
  - Android
  - iOS
bg_image: ""
description: ""
---

OAuth flows on mobile devices can benefit a lot from native apps. With native apps, for example, it is possible to use already existing sessions and biometric authentication features. While apps improve the user experience, they also bring new security challenges to OAuth, especially for services like open banking. This document describes the challenges of redirections between native apps and web applications on Android and iOS and recommends solutions based on currently available features of the mobile operating systems and browsers. Our recommendations are more detailed than those from [RFC8252 (OAuth 2.0 for Native Apps)](https://tools.ietf.org/html/rfc8252) and also address use cases with very high security requirements. A [pull request for the AppAuth-Android project](https://github.com/openid/AppAuth-Android/pull/622) has been created.

Read the full post [here](https://danielfett.de/2020/11/27/improving-app2app/).
