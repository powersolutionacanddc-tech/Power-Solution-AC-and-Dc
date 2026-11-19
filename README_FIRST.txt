POWER SOLUTIONS AC & DC — ANDROID SOURCE PROJECT
FINAL CONSOLIDATED SOURCE PACKAGE

WHAT IS INCLUDED
- Android Studio project (Kotlin + Android WebView)
- Company banner artwork used throughout the app and on printed documents
- App launcher icon
- GitHub Actions workflow to build a debug APK
- Quotations, invoices and official receipts
- Separate transport fee line, excluded from item subtotal and included in grand total
- VAT calculation, payment method, amount paid and balance due
- Create a receipt directly from an invoice payment (including online payments)
- Activity log for document creation/updates/deletion, payments, sharing and stock receipts
- Product catalogue, editable prices, default 20% markup, stock receiving and invoice stock deduction
- Share document text and document image using the Android share chooser
- Print / Save as PDF using the Android print service
- Local data backup export and restore (JSON)
- Draft and business records stored locally on the device

IMPORTANT
- This is a source-code ZIP, not a prebuilt APK. Build the APK using the included GitHub Actions workflow.
- Records are stored on this phone only; they do not synchronise to another phone or cloud account.
- Export a backup regularly. Clearing app storage or uninstalling the app can erase local records.
- The image-share option captures the current document screen. Check the preview before sending.
- PDF creation uses Android Print / Save as PDF.
- The app does not connect to banks, Ecocash, card processors or payment gateways. Select the actual payment method and record the amount received after confirming payment in the relevant provider.
- The app does not automatically publish to Google Play, Huawei AppGallery or other app stores. Store publication requires separate developer accounts, signing and review.
- The included workflow builds a debug APK for testing. A signed release APK/AAB is required for store distribution.

BUILD ON GITHUB FROM AN ANDROID PHONE
1. Extract this ZIP on your phone.
2. Upload the contents inside the PowerSolutionsAndroid folder to the root of your GitHub repository (keep the .github folder).
3. Open the repository on GitHub, select Actions, then Build Power Solutions Android APK.
4. Tap Run workflow and wait for the green successful result.
5. Open the completed run and download the artifact named Power-Solutions-AC-DC-APK.
6. Extract the artifact ZIP and install app-debug.apk. Allow installation from your browser/files app if Android asks.

PROJECT DETAILS
Application ID: com.powersolutions.acdc
Minimum Android: 6.0 (API 23)
Java: 17
Gradle wrapper is not bundled; GitHub Actions installs Gradle 8.9.

COMPANY
POWER SOLUTIONS AC & DC
12 Tilbury Road, Willowvale, Harare
Main WhatsApp: 0779331564
Other WhatsApp: 0784981579 (Mike Dube); 0771340158 (Petros Dube)
Calls: 0773955255; Calls only: 0714472898
