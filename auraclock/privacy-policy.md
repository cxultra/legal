# Privacy Policy

**Effective Date: 5 May 2026**

CX Ultra ("we", "us", or "our") built AuraClock as a free, ad-supported Android application with an optional premium upgrade. This Privacy Policy explains what information the app collects, how that information is used, and the choices available to you.

By installing or using AuraClock, you acknowledge that you have read and understood this Privacy Policy. If you do not agree with any part of it, please uninstall the application.

---

## 1. Information We Collect

### 1.1 Information You Provide Directly

AuraClock does not require you to create an account, provide your name, email address, phone number, or any other personally identifiable information.

When you use the app, you may enter:

- **City search queries** — text you type when searching for a city to add to your dashboard.
- **Alarm names and times** — labels and schedule details for alarms you create.
- **App preferences** — your preferred currency, temperature unit, theme, clock format, and clock face style.

All of this information is stored locally on your device. It is never transmitted to our servers because we do not operate any.

### 1.2 Information Collected Automatically

AuraClock itself does not collect analytics, usage metrics, or device identifiers. However, the app integrates third-party services that may collect certain information automatically:

**Google AdMob (Advertising)**

The free version of AuraClock displays advertisements served by Google AdMob. Google's advertising SDK may collect:

- Your device's Advertising ID
- Device make, model, and operating system version
- IP address (used for coarse geographic ad targeting)
- Ad interaction data (impressions, clicks)

This data is collected and processed by Google in accordance with [Google's Privacy Policy](https://policies.google.com/privacy) and [Google's Advertising Technology Policy](https://policies.google.com/technologies/ads). We do not have access to this data.

Users who purchase the "Remove Ads" premium upgrade will no longer be served advertisements, and AdMob will no longer collect data from their device.

**Sentry (Crash Reporting)**

AuraClock uses Sentry to detect and diagnose application crashes. When a crash or unhandled error occurs, Sentry may collect:

- Stack traces and error messages
- Device model, operating system, and app version
- A randomly generated event identifier

Sentry does not collect your name, email address, location, or any content you have entered into the app. Crash reports are used solely to identify and fix bugs. Sentry's data handling practices are described in [Sentry's Privacy Policy](https://sentry.io/privacy/).

**Google Play Billing (In-App Purchases)**

If you choose to purchase the premium upgrade, the transaction is handled entirely by the Google Play Store. We do not receive or store your payment information, billing address, or financial details. Purchase processing is governed by [Google Play's Terms of Service](https://play.google.com/intl/en_us/about/play-terms/).

### 1.3 Information We Do Not Collect

To be clear, AuraClock does **not** collect:

- Your name, email address, or phone number
- Your precise or approximate geographic location (the app does not use GPS, Wi-Fi, or cell tower location)
- Contacts, photos, files, or any content from other apps on your device
- Browsing history or activity in other applications
- Biometric data

The city coordinates displayed in the app are retrieved from a public geocoding service based on the city name you search for. Your device's own location is never accessed.

---

## 2. How We Use Information

| Purpose | Data Used | Basis |
|---|---|---|
| Display world clocks and time zones | City names, coordinates (from geocoding), timezone identifiers | Core app functionality |
| Show current weather conditions | City latitude and longitude sent to Open-Meteo API | Core app functionality |
| Display currency exchange rates | Currency codes sent to ExchangeRate-API | Core app functionality |
| Serve advertisements | Data collected by Google AdMob SDK | Legitimate interest / consent (see Section 7) |
| Diagnose and fix crashes | Crash reports collected by Sentry SDK | Legitimate interest in maintaining app stability |
| Process premium purchases | Transaction data handled by Google Play | Contract performance |
| Remember your preferences | Settings stored in local SharedPreferences | Core app functionality |

We do not sell, rent, share, or trade any user information with third parties for their own marketing purposes.

---

## 3. Third-Party Services

AuraClock communicates with the following external services. Each operates under its own privacy policy:

| Service | Purpose | Data Sent | Privacy Policy |
|---|---|---|---|
| **Google AdMob** | Advertising | Device identifiers, ad interaction data | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **Google Play Billing** | In-app purchases | Transaction details (handled by Google) | [play.google.com/about/play-terms](https://play.google.com/intl/en_us/about/play-terms/) |
| **Sentry** | Crash reporting | Stack traces, device info, app version | [sentry.io/privacy](https://sentry.io/privacy/) |
| **Open-Meteo** | Weather data | Latitude, longitude | [open-meteo.com/en/terms](https://open-meteo.com/en/terms) |
| **OpenStreetMap Nominatim** | City search / geocoding | Search query text | [wiki.osmfoundation.org/wiki/Privacy_Policy](https://wiki.osmfoundation.org/wiki/Privacy_Policy) |
| **ExchangeRate-API** | Currency conversion rates | Currency codes | [exchangerate-api.com/terms](https://www.exchangerate-api.com/terms) |

API requests are sent directly from your device to these services. They do not pass through any server operated by us.

---

## 4. Data Storage and Security

All user-generated data — your saved cities, alarms, and preferences — is stored locally on your device using an embedded database (Isar) and local key-value storage (SharedPreferences). Your premium purchase status is stored in Android's encrypted secure storage.

We do not operate backend servers. There is no cloud sync, no remote database, and no user data stored outside your device.

The app disables Android's automatic backup feature (`android:allowBackup="false"`) to prevent your app data from being included in device backups that you have not explicitly chosen to create.

---

## 5. Data Retention and Deletion

Because all data is stored on your device, you have complete control over it:

- **Delete individual cities or alarms** within the app at any time.
- **Uninstall AuraClock** to permanently delete all locally stored data, including your settings, saved cities, alarms, and purchase status.

We retain no data on our side to delete, because we have no servers or databases.

Crash reports sent to Sentry are retained according to Sentry's data retention policy and are automatically deleted after their retention period expires.

---

## 6. Children's Privacy

AuraClock is not directed at children under the age of 13 (as defined by the U.S. Children's Online Privacy Protection Act) or under the age of 16 (as defined by the EU General Data Protection Regulation). We do not knowingly collect personal information from children.

If you are a parent or guardian and believe your child has provided information through one of the third-party services integrated into this app, please contact the relevant service provider directly or contact us at the email address below so we can assist.

---

## 7. Advertising and Consent

AuraClock's free tier displays advertisements served by Google AdMob. In regions where consent is required by law — including the European Economic Area (EEA), the United Kingdom, and other jurisdictions subject to the General Data Protection Regulation (GDPR) or equivalent legislation — Google's consent management framework will present you with a consent dialog before serving personalised advertisements.

You may choose to:

- **Consent** to personalised ads, which uses the data described in Section 1.2.
- **Decline** personalised ads, in which case you will see non-personalised advertisements that do not rely on your Advertising ID or browsing behaviour.

You can also reset or delete your device's Advertising ID at any time through your Android device settings under **Settings > Privacy > Ads**.

Purchasing the "Remove Ads" premium upgrade eliminates all advertisements and stops AdMob from collecting data on your device entirely.

---

## 8. Your Rights

Depending on where you live, you may have certain rights regarding information collected by the third-party services used in this app.

### European Economic Area, United Kingdom, and Switzerland (GDPR)

If you are located in the EEA, UK, or Switzerland, you have the right to:

- Request access to the personal data held about you
- Request correction of inaccurate data
- Request deletion of your data
- Object to or restrict processing of your data
- Data portability

Because we do not collect or store personal data on our servers, most of these rights are exercised by uninstalling the app (which deletes all local data) or by contacting the relevant third-party service directly. If you need assistance identifying or exercising your rights, contact us at the email address below.

### California, United States (CCPA / CPRA)

If you are a California resident, you have the right to:

- Know what personal information is collected about you
- Request deletion of your personal information
- Opt out of the sale or sharing of personal information

We do not sell or share your personal information as those terms are defined under the CCPA. Advertising-related data collection by Google AdMob is governed by Google's own CCPA compliance measures.

### All Users

Regardless of your location, you can:

- Uninstall the app to delete all locally stored data
- Opt out of personalised advertising via your device settings
- Contact us with questions or concerns at any time

---

## 9. Permissions

AuraClock requests the following Android permissions:

| Permission | Purpose |
|---|---|
| `INTERNET` | Fetch weather, currency, and city data from external APIs; load advertisements |
| `RECEIVE_BOOT_COMPLETED` | Reschedule alarms after device restart |
| `WAKE_LOCK` | Keep the device awake while an alarm is ringing |
| `VIBRATE` | Vibrate the device when an alarm sounds |
| `USE_FULL_SCREEN_INTENT` | Display the alarm screen over the lock screen |
| `SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM` | Schedule alarms to ring at the exact time you set |
| `POST_NOTIFICATIONS` | Show alarm notifications |

The app does **not** request location, camera, microphone, contacts, or storage permissions.

---

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will revise the "Effective Date" at the top of this page. Material changes will be communicated through an update to this page. We encourage you to review this policy periodically.

Your continued use of AuraClock after any changes constitutes your acceptance of the revised policy.

---

## 11. Contact

If you have questions, concerns, or requests regarding this Privacy Policy, you can reach us at:

**CX Ultra**
Email: [chrisxadev@gmail.com](mailto:chrisxadev@gmail.com)

---

*This document was last updated on 5 May 2026.*
