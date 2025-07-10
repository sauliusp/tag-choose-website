---
title: Technical Details
---

## Updates

- 2025-07-10: ❌ after the Chrome update you might see the following error in the extension popup: "AI features are not supported in your browser. However, you can still tag this bookmark manually using autocomplete.". I am working on it - once I have a fix, I will update the extension.

## One-Time Chrome Setup

To use Gemini Nano in your browser, you’ll need to adjust three experimental Chrome flags. These allow Chrome’s Prompt API and on-device models to function:

> chrome://flags/#optimization-guide-on-device-model → Enabled (BypassPerfRequirement)

> chrome://flags/#prompt-api-for-gemini-nano → Enabled

> chrome://flags/#text-safety-classifier → Disabled

## Will it work on my machine?

Please find the system requirements here: [Gemini Nano System Requirements](https://docs.google.com/document/d/1VG8HIyz361zGduWgNG7R_R8Xkv0OOJ8b5C9QKeCjU0c/edit?tab=t.0)

## Chrome's Prompt API Is Experimental

Because TagChoose uses a Chrome Origin Trial (Prompt API), it is subject to change. You may need to re-enable flags, update Chrome, or reinstall the extension in future releases.

- This is not a permanent browser feature (yet)
- Future Chrome versions may break compatibility
- We’ll update this page if anything changes