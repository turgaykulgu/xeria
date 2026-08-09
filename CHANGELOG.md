# Changelog

This changelog summarizes notable public updates for XERIA.

XERIA is a commercial Windows desktop application for secure PDF watermarking, personalized batch PDF generation, PDF encryption, trace-code watermarking, optional QR traceability, email delivery, cloud-connected workflows, and controlled document distribution.

## XERIA 1.9.1 — Display Compatibility and Watermark Rendering Update

Released: August 9, 2026

### Availability

* Available through Microsoft Store.
* Available as the standalone direct Windows installer from the official XERIA website.
* Microsoft Store and direct installer distribution channels are aligned on version 1.9.1.

Microsoft Store:

https://apps.microsoft.com/detail/9P37ZD7SQNZP

Direct installer:

https://xeriasoft.com/downloads/XERIA-setup.exe

### Added

* Added comprehensive adaptive display scaling for high-DPI settings and different screen resolutions.
* Added automatic compact navigation behavior for low-resolution displays and narrow windows.
* Added localized navigation tooltips in all nine supported interface languages.
* Added dynamic minimum window sizing to preserve usability on smaller work areas.
* Added public display requirements documentation.

### Improved

* Improved interface compatibility for displays with a resolution of 1024 × 768 or higher.
* Improved transitions between maximized, restored, and manually resized window states.
* Improved behavior when moving XERIA between monitors with different DPI settings.
* Improved positioning and sizing of secondary windows and custom file-selection dialogs within the usable monitor work area.
* Improved taskbar, monitor work-area, and window-position calculations.
* Improved PDF preview, watermark positioning, zoom, and page navigation compatibility with the adaptive scaling system.
* Improved rendering quality for small text and Trace Code watermarks, including very small watermark size settings.
* Improved text watermark sharpness while preserving non-selectable and non-copyable output behavior.
* Streamlined the Dropbox connection flow.

### Fixed

* Fixed text and Trace Code watermark rendering artifacts that could appear at small watermark sizes.
* Fixed additional window sizing and layout issues across different resolutions and Windows scaling levels.
* Removed the unnecessary informational dialog shown before Dropbox authorization.

## XERIA 1.9.0 — Unified Microsoft Store and Direct Release

Released: July 30, 2026

### Availability

* Available through Microsoft Store.
* Available as the standalone direct Windows installer from the official XERIA website.
* Microsoft Store and direct installer distribution channels were aligned on the same version.

### Improved

* Improved license synchronization for extended, shortened, revoked, withdrawn, and reactivated licenses.
* The latest verified license status is stored securely on the local device for reliable offline use.
* Improved consistency between online license validation and locally cached license information.
* Improved PDF preview page navigation and zoom controls.

### Fixed

* Fixed PDF preview page navigation issues.
* Fixed PDF preview zoom and slider behavior.
* Fixed cases where administrative license changes were not reflected correctly during offline use.

## XERIA 1.8.9 — Microsoft Store Test Release

Released: July 28, 2026

### Availability

* Distributed to Microsoft Store test accounts for validation.
* Not released as the general public production version.

### Fixed

* Fixed PDF preview page navigation issues.
* Fixed PDF preview zoom behavior.
* Fixed application icon and Microsoft Store package asset issues.

## XERIA 1.8.8 — Internal Unpublished Build

Build date: July 28, 2026

### Availability

* Internal development build.
* Not publicly released.

### Improved

* Improved server-side license synchronization.
* Added secure local storage of the latest verified license status for offline use.
* Improved license continuity when the application is temporarily offline.

## XERIA 1.8.7 — Microsoft Store Release

Released: July 27, 2026

### Availability

* Released through Microsoft Store.

### Improved

* Added subtle motion effects to the main-screen workflow buttons.
* Improved interaction feedback on the home screen.

### Fixed

* Fixed an opacity mismatch between the PDF preview and the generated PDF output.
* Improved consistency between watermark preview rendering and final document rendering.

## XERIA 1.8.6 — Microsoft Store Release

Released: July 2026

### Availability

* Available through Microsoft Store.
* Recommended installation method for most Windows users.

### Added

* Added initial Microsoft Store distribution support.
* Added Microsoft Store installation support.
* Added Store-aware update behavior.

### Improved

* Improved installation experience for Microsoft Store users.
* Store-installed versions rely on Microsoft Store-managed updates.
* Direct web installer updates are separated from Microsoft Store update behavior.

## XERIA 1.8.3 — Direct Installer Stable Release

Released: June 24, 2026

### Availability

* Available as the standalone direct Windows installer from the official XERIA website.

### Added

* Added light and dark theme support.
* Added application appearance options for system, light, and dark themes.

### Improved

* Improved user interface consistency across light and dark themes.
* Improved visual contrast, button visibility, and hover behavior in light theme.
* Improved theme behavior across PDF Edit, Email Management, Trace Analyzer, Cloud Access, License, Mail Log, Language, Update, Privacy, and About pages.
* Improved PDF Edit page appearance when selecting multiple pages.
* Improved overall application usability and visual polish.

### Fixed

* Fixed an issue where adding a new recipient to the default recipient list could fail.
* Fixed several light theme display and contrast issues.
* Fixed selected-row visual inconsistencies when switching between dark and light themes.
* Fixed general stability and usability issues reported during testing.

## Current Distribution Channels

| Channel | Current Version | Status |
|---|---:|---|
| Microsoft Store | 1.9.1 | Recommended |
| Direct Installer | 1.9.1 | Alternative official installer |

## Current Development Focus

* Secure PDF watermarking and traceability refinements
* Personalized batch workflow improvements
* Cloud-connected workflow usability
* Microsoft Store and direct installer release alignment
* Video tutorial expansion
* Website, Resource Center, and documentation improvements
* Public release communication improvements

## Recent Highlights

* Added high-DPI, mixed-DPI, and multi-resolution display compatibility in XERIA 1.9.1
* Added automatic compact navigation behavior for smaller displays
* Improved small text and Trace Code watermark rendering while preserving non-selectable output
* Streamlined Dropbox authorization
* Aligned Microsoft Store and direct installer releases on XERIA 1.9.1
* Improved online and offline license synchronization in XERIA 1.9.0
* Added secure local storage of the latest verified license status
* Fixed PDF preview navigation and zoom behavior
* Fixed watermark opacity consistency between preview and final output
* Added Microsoft Store availability
* Added digitally signed Windows installer support
* Added light and dark theme support
* Improved personalized batch PDF generation and batch email workflows
* Improved cloud access and multi-language user interface support

## Public Documentation

* Public GitHub product page
* Commercial closed-source license notice
* Security policy
* Display requirements
* Installation guide and FAQ
* Official website, Microsoft Store, and direct installer references
* Support and false-positive reporting guidance

## Official Downloads

Microsoft Store:

https://apps.microsoft.com/detail/9P37ZD7SQNZP

Direct Installer:

https://xeriasoft.com/downloads/XERIA-setup.exe

## Notes

This repository does not contain the XERIA application source code.

It is used for public product information, documentation, release notes, security notices, installation guidance, and support references.
