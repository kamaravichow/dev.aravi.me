---
title: Amazing AI
subtitle: Generate images from text using Stable Diffusion
pubDate: 2022-12-21
platforms:
  - macOS
appStoreId: 1660147028
---

Simply describe the image you desire, and the app will generate it for you like magic!

**Developed exclusively for Apple silicon (M1/M2) - The app is NOT compatible with devices running on Intel chips.**

[Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion) is a deep learning, text-to-image model used to generate detailed images conditioned on text descriptions.

The app is [highly optimized](https://machinelearning.apple.com/research/stable-diffusion-coreml-apple-silicon) and runs on the [Apple Neural Engine](https://apple.fandom.com/wiki/Neural_Engine).

<br>

### Tips

#### Preview

Click a thumbnail to view a larger version of it. Click again to exit.

#### Keyboard shortcuts

When in preview mode, there are some keyboard shortcuts available:
- <kbd>◀</kbd> — Previous image
- <kbd>▶</kbd> — Next image
- <kbd>Space</kbd> — Save image
- <kbd>Command + C</kbd> — Copy image
- <kbd>Esc</kbd> — Exit preview

#### Negative prompt

To write a [negative prompt](https://dreamlike.art/guides/guide-to-stable-diffusion-negative-prompt-parameter) (what to exclude), write `##` after your prompt, followed by your negative prompt. For example, “photo of a cake, high-quality ## strawberry, out of frame”, where `strawberry, out of frame` is your negative prompt. Anything after the `##` is your negative prompt. You only write `##` once.

#### Metadata

When you save a generated image, it includes a lot of useful metadata (prompt, steps, etc). You can [view this in Finder](https://twitter.com/sindresorhus/status/1611441129622278146/photo/1) by right-clicking the image file and selecting “Get Info”. The file also includes some relevant tags which can be used to create [smart folders](https://support.apple.com/guide/mac-help/tag-files-and-folders-mchlp15236/mac).

<br>

### Frequently Asked Questions {#faq}

#### I have a feature request, bug report, or some feedback

[Send it here.](https://sindresorhus.com/feedback?product=Amazing%20AI&referrer=Website-FAQ)

#### Why not use Stable Diffusion 2?

It will eventually be supported, but right now, it's worse than 1.5.

#### Why does the app require macOS 13.1 and Apple silicon?

The app takes advantage of recent [optimizations by Apple](https://machinelearning.apple.com/research/stable-diffusion-coreml-apple-silicon).

#### What are the usage restrictions for the generated images?

You can use the images for commercial or non-commercial purposes, but you must adhere to the [Creative ML OpenRAIL-M license's usage restrictions](https://github.com/CompVis/stable-diffusion/blob/21f890f9da3cfbeaba8e2ac3c425ee9e998d5229/LICENSE#L69-L82). These restrictions include not using the images for illegal activity, false information, discrimination, or medical advice.

#### Can you support custom models?

It's something I plan to support, but other things are a higher priority at the moment.

#### Can you support inpainting/outpainting?

I don't plan to support this. [DiffusionBee](https://diffusionbee.com) supports this (see below for comparison).

#### Can it generate images with aspect ratios other than a square?

The Stable Diffusion library used by this app only supports squares.

#### Why can it not generate adult images?

The app would not be allowed on the App Store if it allowed creating such images.

#### Why does it take so long to generate?

Several factors can affect the speed of image generation, including the performance of your device and the amount of available memory and CPU. Try closing down other apps or restarting your device before generating images.

And bear in mind that the initial generation after installing the app may take longer due to model validation.

#### Why does the app take up so much space on disk and memory?

The AI model used to generate images is large. This is reasonable given the model's capabilities.

#### Can you support iOS?

I plan to add iOS support when the app is more mature.

#### How does it compare to [DiffusionBee](https://github.com/divamgupta/diffusionbee-stable-diffusion-ui)? {#diffusionbee}

**Amazing AI benefits**

- Faster and more energy efficient as it uses the [Apple Neural Engine](https://apple.fandom.com/wiki/Neural_Engine) and recent [macOS optimizations](https://machinelearning.apple.com/research/stable-diffusion-coreml-apple-silicon)
- Native user interface (DiffusionBee is a web app wrapped with Electron which does not follow platform conventions)
- Batch generation of different prompts (DiffusionBee supports batch for the same prompt only)
- Shortcuts support
- Automatic upscaling (DiffusionBee requires you to manually click an upscale button for each image)
- Sandboxed (More secure)
- Available on the App Store

**DiffusionBee benefits**

- Inpainting
- Outpainting
- Image to image (planned for Amazing AI too)
- Custom models (planned for Amazing AI too)

#### Why is this free without ads?

I just enjoy making Mac apps. Consider leaving a nice review on the App Store.

#### Where can I find the changelog?

Go [here](https://apps.apple.com/app/id1660147028) and click “Version History”.

#### Can you localize the app into my language?

I don't have any immediate plans to localize the app.

<br>

### Non-App Store Version

A special version for users that cannot access the App Store. It won't receive automatic updates. I will update it here once a year.

[Download](https://drive.google.com/file/d/1mcEhAKhmQGYzmSS-zlejt3_qsKFzqm0h/view?usp=sharing) *(1.2.2)*

*Requires macOS 13 or later*
