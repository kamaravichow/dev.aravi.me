---
title: Shareful
subtitle: Give the macOS share menu superpowers
pubDate: 2020-09-08
platforms:
  - macOS
appStoreId: 1522267256
---

<br>

### Frequently Asked Questions {#faq}

#### I have a feature request, bug report, or some feedback

[Send it here.](https://sindresorhus.com/feedback?product=Shareful&referrer=Website-FAQ)

#### The share services do not show up in System Settings

Shareful provides share services (Copy, Open In, etc) which macOS is supposed to pick up. Shareful has no control over how it works. In some rare cases, macOS can fail to pick up these share services. This is a problem with macOS not Shareful.

Here are some things you could try:
- Restart your computer
- [Reset NVRAM](https://support.apple.com/en-us/HT204063)
- [Reset the share services registry](https://web.archive.org/web/20180711015728/https://support.apple.com/en-us/HT203129)

If you are on a work computer, it could also be that your company has blocked third-party share services.

#### Can you also add a “Move” action?

This is unfortunately not possible. [Share extensions](https://developer.apple.com/design/human-interface-guidelines/macos/extensions/share-extensions/), like the "Copy" action, only receive a copy of the file. They have no access to the original file.

#### Where can I find the changelog?

Go [here](https://apps.apple.com/app/id1522267256) and click “Version History”.

#### Why is this free without ads?

I just enjoy making apps. Consider leaving a nice review on the App Store.

<br>

### Older Versions

- [1.8.0](https://github.com/sindresorhus/meta/files/11297902/Shareful.1.8.0.-.macOS.12.zip) for macOS 12+
- [1.6.0](https://github.com/sindresorhus/meta/files/8800088/Shareful.1.6.0.-.macOS.11.zip) for macOS 11+
- [1.4.0](https://github.com/sindresorhus/meta/files/7119520/Shareful.1.4.0.-.macOS.10.15.zip) for macOS 10.15+

<br>

### Non-App Store Version

A special version for users that cannot access the App Store. It won't receive automatic updates. I will update it here once a year.

[Download](https://github.com/sindresorhus/meta/files/11297874/Shareful.1.9.0.zip) *(1.9.0)*

*Requires macOS 13 or later*
