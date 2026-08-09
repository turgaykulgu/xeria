# Display Requirements

XERIA includes adaptive display scaling for different screen resolutions, Windows scaling levels, and per-monitor DPI environments.

This document reflects the display behavior introduced and validated for XERIA 1.9.1.

## Minimum and Recommended Resolution

- **Minimum supported resolution:** 1024 × 768
- **Recommended resolution:** 1366 × 768 or higher
- **Recommended Windows display scaling:** 100% to 175%

Resolutions below 1024 × 768 are not supported. XERIA may still open on smaller displays, but text, icons, controls, and document previews may become too small for comfortable use.

## Adaptive Display Behavior

XERIA automatically adapts its interface to the available monitor work area:

- The main interface scales proportionally while preserving the original layout.
- On low-resolution displays or narrow windows, the navigation sidebar switches automatically to compact icon mode.
- Localized tooltips are shown for navigation icons while compact mode is active.
- The full navigation sidebar is restored automatically when the window becomes wide enough again.
- The window has a dynamic minimum size to prevent the interface from becoming unusably small.
- Large secondary windows and custom file-selection dialogs are automatically resized and centered within the usable screen area.
- The Windows taskbar and the active monitor's work area are taken into account.
- XERIA recalculates its layout when the DPI, display resolution, monitor, or window state changes.
- Manual resizing, restored-window behavior, and maximized-window behavior are handled separately to preserve readability and avoid unnecessary empty margins.

## High-DPI and Multi-Monitor Support

XERIA supports per-monitor DPI awareness. When the application is moved between monitors with different Windows scaling levels, the interface is recalculated for the active monitor.

The application preserves usability across mixed-DPI multi-monitor configurations and recalculates its physical display bounds using the active monitor's usable work area.

For the best result when changing Windows display scaling, close and reopen XERIA after applying the new Windows setting.

## Large and 4K Displays

On large or 4K displays, XERIA uses a maximum visual size instead of expanding indefinitely. The application interface remains centered and readable while avoiding excessively large controls and spacing.

## Internal Scrolling

Some pages contain long forms, tables, document previews, or configuration panels. These areas may use their own vertical or horizontal scrollbars when required. This is expected behavior and is separate from overall window scaling.

When a normal window is manually reduced below the preferred readable area, XERIA may preserve a minimum readable interface scale and use scrolling rather than continuously shrinking the complete interface.

## Tested Display Configurations

The adaptive display system has been tested with the following configurations:

- 1920 × 1080 at 100%, 125%, 150%, and 175%
- 1366 × 768 at 100% and 125%
- 1024 × 768 at 100%

Actual appearance may vary slightly depending on graphics drivers, taskbar placement, Windows theme, font rendering, and connected monitor configuration.
