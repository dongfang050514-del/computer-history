# Computer History

**A daily history for your computer, ready when you want to look back.**

[简体中文](README.md) · English · [日本語](README.ja.md)

Computer History is an early-stage personal open-source project exploring a simple activity timeline and app usage statistics. Its purpose is to help you review your day: which apps you used, where your time went, and when you worked on something.

Browsers have a history. Your computer could have a daily memory, too. That is the starting point of this small project.

> Status: concept and design stage. No installable release is available. The following describes intended behavior, not implemented features.

## Design principles

- **Clarity:** generous spacing, readable typography, and restrained visual hierarchy.
- **Quiet operation:** background recording with no unsolicited pop-ups or sounds; open the interface when needed.
- **Low overhead:** separate recording from the interface and minimize memory, CPU, and disk activity. Measurements will be published once an implementation is tested.
- **User control:** local storage by default, a clear recording scope, and controls to pause, exclude, and delete.

## Planned first release

- Foreground app usage statistics.
- A daily timeline of app activity.
- Idle, lock, and sleep detection.
- Tray controls to pause, resume, or quit.
- App exclusions, record deletion, and retention settings.

Windows 10/11 is the initial target. Compatibility and resource usage remain subject to implementation and testing.

## Privacy scope

Basic records are intended to contain app identifiers, time intervals, and idle states. Window titles will not be collected by default. Screenshots, audio recording, keystroke content, and activity uploads are outside the planned basic scope. Any future expansion should require a separate, explicit user choice.

Local storage is not a guarantee of absolute security. Storage protection, deletion behavior, and logging must still be verified.

## Roadmap

- [x] Define the product direction and create the public repository
- [ ] Validate Windows foreground activity and idle detection
- [ ] Build an interface prototype and a working minimum version
- [ ] Test accuracy and overhead on lower-spec computers
- [ ] Publish the first installable release

## Feedback

Share everyday use cases, privacy concerns, and experience suggestions through [Issues](https://github.com/dongfang050514-del/computer-history/issues). Please do not include private activity records or sensitive information.

Initiated by [dongfang050514-del](https://github.com/dongfang050514-del).
