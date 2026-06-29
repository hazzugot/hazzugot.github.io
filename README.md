# Privacy Policy for FuelChecker

_Last updated: June 2026_

## 1. Introduction
FuelChecker ("the App") is a fuel price comparison app provided by Harry Miles. This privacy policy explains how we handle your data when you use the App.

## 2. Data we collect

### Location data
The App requests your device's location to show fuel stations near you. **This data is used only on your device** — it is never sent to us, stored on our servers, or shared with third parties. You can deny location permission and the App will set a default location (London).

### Vehicle registration data
If you choose to use the DVLA vehicle lookup feature, your registration number is sent directly from your device to the **DVLA Vehicle Enquiry Service** (a UK government API). We do not store, log, or transmit your registration number to any other service. The DVLA's privacy policy applies to that data transfer.

### App usage data
The App does **not** collect analytics, crash reports, or usage statistics. There are no third-party analytics SDKs (no Firebase, no Google Analytics, no Mixpanel).

## 3. Advertising
The App displays banner ads via **Google AdMob**. AdMob may collect device identifiers (such as Advertising ID) and usage data to serve relevant ads. This is governed by Google's privacy policy at `policies.google.com/privacy`. AdMob data collection starts only after you swap the test ad IDs for real ones in a production build.

## 4. Data storage
All user preferences (your car details, settings, theme choice) are stored **locally** on your device using SharedPreferences. Nothing is stored on a remote server.

## 5. Data we do NOT collect
- Email addresses
- Names
- Phone numbers
- Payment information
- Account passwords
- Contact lists
- Photos or media
- Browsing history

## 6. Third-party services

| Service | Purpose | Data shared |
|---------|---------|-------------|
| jsDelivr CDN | Loading fuel price data from the fuel-data GitHub repo | IP address (standard HTTP request) |
| CartoDB (via flutter_map) | Map tile rendering | IP address, tile coordinates (standard web map behaviour) |
| DVLA Vehicle Enquiry Service | Registration plate lookup (optional) | Registration number, IP address |
| Google AdMob | Banner advertising (in production builds) | Advertising ID, IP address |

## 7. Children's privacy
The App is not directed at children under 13. We do not knowingly collect personal information from children.

## 8. Changes to this policy
If this policy changes, the updated version will be listed here with a new date. Continued use of the App after changes constitutes acceptance.

## 9. Contact
For questions about this privacy policy, contact: `harry.miles@n3i.co.uk` (or the contact method you specify)

***

_This policy was created using a free privacy policy generator and tailored for the FuelChecker app._
