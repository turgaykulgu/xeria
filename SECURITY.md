# Security Policy

## Trusted Installation Sources

XERIA should only be installed from trusted official sources.

### Recommended: Microsoft Store

https://apps.microsoft.com/detail/9P37ZD7SQNZP

Current Microsoft Store version:

**XERIA 1.9.4**

### Alternative: Direct Installer

https://xeriasoft.com/downloads/XERIA-setup.exe

Current direct installer version:

**XERIA 1.9.4**

The direct installer remains an official alternative installation method.

Do not download XERIA from unofficial mirrors, third-party file-sharing websites, repackaged installer sources, or unknown download locations.

## Code Signing

The XERIA direct Windows installer is digitally signed.

Before installing the direct installer, users should verify that:

* The installer was downloaded only from the official XERIA website
* The installer came from https://xeriasoft.com/downloads/XERIA-setup.exe
* The Windows publisher information matches the official publisher identity
* The installer has not been obtained from an unofficial mirror or modified source
* The installer is digitally signed

For most users, Microsoft Store remains the recommended installation method.

## Product Purpose

XERIA is a legitimate Windows desktop application for secure PDF watermarking, personalized batch PDF generation, PDF encryption, trace-code watermarking, optional QR traceability, email delivery, cloud-connected workflows, and controlled document distribution.

XERIA does not include bundled adware, browser extensions, cryptocurrency miners, unwanted background payloads, spyware, or third-party installers.

## Watermark Rendering and Traceability

XERIA 1.9.1 introduced improved rendering quality for small text and Trace Code watermarks, and this behavior is retained in XERIA 1.9.4.

Text and Trace Code watermarks are rendered so that they are not exposed as normal selectable or copyable PDF text. This helps preserve their intended role as visual identification and traceability elements.

Watermarking and traceability are security-supporting controls, not substitutes for access control, encryption, organizational policy, or other document-protection measures.

## License Validation and Offline Use

XERIA validates licenses through the official XERIA licensing system.

Since XERIA 1.9.0, license synchronization supports extended, shortened, revoked, withdrawn, and reactivated licenses, and the latest verified license status is stored securely on the local device to support reliable offline use.

An internet connection may still be required for initial activation, periodic validation, license changes, updates, and online services.

## Security Reports

If you believe you have found a security issue related to XERIA, contact:

[support@xeriasoft.com](mailto:support@xeriasoft.com)

Please include:

* A clear description of the issue
* Steps to reproduce the issue
* The XERIA version number
* Whether XERIA was installed from Microsoft Store or the direct installer
* Windows version
* Relevant screenshots or logs, if available

Do not post confidential documents, license keys, passwords, customer data, or security-sensitive information in public GitHub issues.

## False Positive Reports

Microsoft Defender, Microsoft SmartScreen, or another security product may sometimes show a warning for newly released or recently updated desktop software, especially when a new standalone installer file has not yet built enough reputation.

This mainly applies to the direct installer.

If the official direct installer is incorrectly flagged, you may use the Microsoft Store version instead:

https://apps.microsoft.com/detail/9P37ZD7SQNZP

To report a suspected false positive:

[support@xeriasoft.com](mailto:support@xeriasoft.com)

Please include the exact warning, installer file name, download URL, security product, Windows version, and a screenshot if available.

## Supported Versions

| Channel | Current Version | Status |
|---|---:|---|
| Microsoft Store | 1.9.4 | Recommended |
| Direct Installer | 1.9.4 | Alternative official installer |

Microsoft Store and direct installer distribution channels are aligned on XERIA 1.9.4.

## Important Notice

Install XERIA only from Microsoft Store or the official XERIA website.

Official website: https://xeriasoft.com

Microsoft Store: https://apps.microsoft.com/detail/9P37ZD7SQNZP

Direct installer: https://xeriasoft.com/downloads/XERIA-setup.exe
