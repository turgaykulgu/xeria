# Frequently Asked Questions

## What is XERIA?

XERIA is a Windows desktop application for secure PDF watermarking, personalized batch PDF generation, PDF encryption, trace-code watermarking, optional QR traceability, email delivery, cloud-connected workflows, and controlled document distribution.

## Is XERIA open source?

No. XERIA is commercial closed-source software.

This repository is used for public product information, documentation, release notes, security notices, installation guidance, and support references. It does not contain the application source code.

## Where can I download XERIA?

Recommended:

https://apps.microsoft.com/detail/9P37ZD7SQNZP

Direct installer:

https://xeriasoft.com/downloads/XERIA-setup.exe

Do not download XERIA from unofficial mirrors or repackaged sources.

## What is the current XERIA version?

| Channel | Current Version | Status |
|---|---:|---|
| Microsoft Store | 1.9.4 | Recommended |
| Direct Installer | 1.9.4 | Alternative official installer |

Microsoft Store and direct installer channels are aligned on XERIA 1.9.4.

## What changed in XERIA 1.9.4?

XERIA 1.9.4 focuses on 4K and large-display workspace behavior.

Maximized windows now make better use of the available screen area on large high-resolution monitors. Restored windows on large displays also use the available window area correctly instead of leaving the interface inside a limited centered region.

The release fixes remaining empty-space issues that could appear after leaving maximized mode and improves layout recalculation during maximized, restored, and manual resize transitions while preserving the responsive behavior introduced in XERIA 1.9.1.

See [XERIA 1.9.4 Release Notes](releases/RELEASE-NOTES-1.9.4.md).

## What changed in XERIA 1.9.1?

XERIA 1.9.1 introduced the adaptive display system and improved watermark rendering quality.

It added adaptive scaling for high-DPI and different screen resolutions, automatic compact navigation on smaller displays, improved mixed-DPI multi-monitor behavior, better secondary-window sizing, and localized navigation tooltips.

It also improved rendering quality for small text and Trace Code watermarks and streamlined the Dropbox connection flow.

See [XERIA 1.9.1 Release Notes](releases/RELEASE-NOTES-1.9.1.md).

## What resolution does XERIA support?

Minimum supported resolution: **1024 × 768**

Recommended resolution: **1366 × 768 or higher**

Recommended Windows display scaling: **100% to 175%**

See [Display Requirements](../DISPLAY-REQUIREMENTS.md).

## Does XERIA support high-DPI and multiple monitors?

Yes.

XERIA recalculates the interface for the active monitor, supports per-monitor DPI behavior, and preserves usability when moved between monitors with different Windows scaling values. XERIA 1.9.4 further improves maximized and restored-window behavior on 4K and other large displays.

## Does XERIA support 4K displays?

Yes.

XERIA 1.9.4 improves how the application uses 4K and other large high-resolution displays. Maximized windows can use the available workspace, and large restored windows recalculate their layout to avoid large unused margins around the interface.

## Why does the navigation menu become compact?

On low-resolution displays or when a normal window is made narrow, XERIA can switch automatically to compact icon navigation so that more usable width remains available for the main content.

Localized tooltips identify the navigation icons while compact mode is active.

## Are Trace Code and text watermarks selectable in the generated PDF?

No.

XERIA 1.9.1 improved the rendering quality of small text and Trace Code watermarks while preserving their non-selectable and non-copyable behavior as normal PDF text. This behavior is retained in XERIA 1.9.4.

## Can very small text or Trace Code watermarks be used?

Yes.

XERIA improves sharpness and stability at very small watermark size settings. Practical visibility still depends on size, opacity, color, page content, and zoom level.

## Is the Microsoft Store version recommended?

Yes. For most users, Microsoft Store is the recommended installation method.

## Is the direct installer official?

Yes, when downloaded from:

https://xeriasoft.com/downloads/XERIA-setup.exe

The direct installer is digitally signed.

## Is XERIA free?

XERIA includes an unlimited free trial.

Email sending is disabled in trial mode, generated PDFs include a visible trial banner, and licensed functionality requires a valid license.

Pricing and purchase information:

https://xeriasoft.com/pricing.html

## Does XERIA work offline after activation?

XERIA can continue using the latest verified license status while temporarily offline.

Since XERIA 1.9.0, the latest verified license status is stored securely on the local device and license synchronization handles administrative license changes more reliably.

Internet access may still be required for activation, periodic validation, license changes, updates, cloud integrations, email integrations, and other online services.

## What is trace-code watermarking?

Trace-code watermarking places recipient-specific trace information into generated PDF copies to help identify the intended recipient or distribution record.

## Is QR traceability required?

No. QR-based traceability is optional.

## Can XERIA process multiple recipients?

Yes. XERIA supports personalized batch PDF generation for recipient lists.

## Can XERIA encrypt PDF files?

Yes. XERIA supports open and owner passwords and PDF permission controls such as printing, copying, and modification restrictions.

## Can XERIA send generated PDFs by email?

Yes, when email integration is configured and a valid license is active. Email sending is disabled in trial mode.

## Does XERIA support cloud-connected workflows?

Yes. XERIA supports Dropbox, OneDrive, and Google Drive connected workflows.

Cloud features require internet access and provider authorization.

## What changed in the Dropbox connection flow in 1.9.1?

The connection flow was simplified by removing the unnecessary informational dialog that previously appeared before Dropbox authorization. Selecting **Connect** now proceeds directly to the authorization flow.

## Were the PDF preview controls improved?

Yes. XERIA 1.9.0 fixed page navigation and zoom behavior, XERIA 1.9.1 kept preview behavior compatible with the adaptive display system, and XERIA 1.9.4 improves use of additional workspace on large displays.

## Why might Microsoft Defender or SmartScreen show a warning?

Newly released direct-installer builds may occasionally trigger reputation-based warnings.

Install only from Microsoft Store or the official XERIA website and verify the direct installer's digital signature.

For suspected false positives, contact [support@xeriasoft.com](mailto:support@xeriasoft.com).

## Does XERIA include adware or bundled software?

No.

XERIA does not include bundled adware, browser extensions, cryptocurrency miners, unwanted background payloads, spyware, or third-party installers.

## Where can I watch tutorials?

https://xeriasoft.com/video-tutorials.html

https://www.youtube.com/@xeriasoft

## How can I get support?

[support@xeriasoft.com](mailto:support@xeriasoft.com)

Do not share confidential PDFs, license keys, passwords, or personal data in public GitHub areas.
