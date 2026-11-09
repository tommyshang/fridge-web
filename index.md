# Privacy Policy — Fridge

_Last updated: 2026-11-08_

Fridge ("the app") is a fridge/pantry inventory tracker. This policy explains what data the app touches and how it is used.

## Data the app collects

The app does **not** require an account, does **not** include advertising or crash-reporting SDKs, and does **not** transmit your inventory data to any server. Barcode and text scanning use Google ML Kit, which reads your camera images on your device and sends limited diagnostics to Google, as listed below.

| Data type | Collected? | Stored where | Shared with third parties? |
|---|---|---|---|
| Camera images (barcode scans, item photos, OCR of expiration dates) | Yes, on-device only | Local device storage | No |
| Photo library access | Yes, only when you choose a photo | Local device storage | No |
| Inventory items, grocery list, quantities, expiration dates | Yes | Local SQLite database on your device | No |
| App settings / preferences | Yes | Local device storage | No |
| Local notifications (expiration reminders) | Generated on-device | Not transmitted anywhere | No |
| Product barcode (when you scan a product) | Sent to Open Food Facts (openfoodfacts.org), a public open database, to look up product name/details | N/A — processed by Open Food Facts | Sent only to Open Food Facts; see their [privacy policy](https://world.openfoodfacts.org/privacy) |
| Scanner diagnostics from Google ML Kit (device model and OS version, app package name and version, performance metrics, error codes, per-installation identifiers) | Sent to Google over HTTPS to diagnose and measure the scanner. Camera images and your inventory are not included. | N/A — processed by Google | Sent only to Google; see the [ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure) |

## What we do not do

- No user accounts or sign-in, and no names, email addresses, or other personal details collected
- No advertising or ad tracking
- No analytics of our own; the only usage data sent is the Google ML Kit diagnostics described above
- No sale of data to third parties
- No data leaves your device except the barcode lookup and Google ML Kit diagnostics described above

## Permissions used

- **Camera** — to scan barcodes and photograph items/expiration dates
- **Photo library** — to attach an existing photo to an inventory item
- **Notifications** — to remind you before food expires

## Data retention & deletion

All inventory data lives in a local database on your device. Uninstalling the app deletes all locally stored data. There is no server-side account to delete. Barcode lookups and Google ML Kit diagnostics are handled by Open Food Facts and Google under their own policies, and cannot be deleted from within the app.

## Changes to this policy

If this policy changes, the "Last updated" date above will be revised.

## Contact

For questions about this policy, contact: niushang1997@gmail.com
