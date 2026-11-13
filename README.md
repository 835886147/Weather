# Privacy Policy for Today Weather

**Effective date:** 13 November 2026
**App:** Today Weather (package name `com.ymwm.weather`), version 1.0.1
**Developer:** the developer of Today Weather ("we", "us", "our")
**Contact:** see Section 12

## 1. Summary

Today Weather is built to work without collecting personal information about you.

- The app does **not** request access to your device location. You choose a city by searching for it by name.
- The app contains **no advertising SDK, no analytics SDK, and no crash-reporting SDK**.
- There is **no account, no registration, and no sign-in**.
- Your saved cities, settings and cached forecasts are stored **locally on your device**.
- The app contacts **a single third-party weather data provider** over HTTPS, and nothing else.

The only information that leaves your device is the city you search for or select, sent to the weather data provider so it can return a forecast for that city. Section 4 describes this precisely.

## 2. Information the app handles

### 2.1 Information you enter

When you search for a city, the text you type is sent to the provider's place search service so it can return matching places. Search text is not stored by the app after the search completes, and is not sent anywhere else.

### 2.2 Information stored on your device

The app stores the following in its own private storage area, which other apps cannot read:

| What | Where | Why |
|---|---|---|
| Saved cities: name, region, country, time zone, latitude and longitude | App private files (`places/`) | To show your saved places and switch between them |
| Cached forecast for each saved city, plus the time it was downloaded | App private files (`forecasts/`) | To let you read the last forecast while offline |
| Currently selected city | App preferences | To reopen on the city you last viewed |
| Unit preferences (temperature, rain, showers, snow, precipitation, pressure, visibility, wind) | App preferences | To display values in the units you chose |
| Theme preference (dark, light, follow system) | App preferences | To display the app in your chosen appearance |

This information is **not uploaded to us**. We operate no server that receives it, and we have no ability to read it.

### 2.3 Information we do not collect

The app does not collect, access or transmit:

- Your device's GPS or network-derived location (the app holds no location permission)
- Your name, email address, phone number, or contacts
- Photos, files, calendar, call logs, or messages
- Device identifiers, IMEI, serial number, or advertising ID
- Usage statistics, behavioural analytics, or crash reports
- Any account credentials, because no account exists

## 3. Permissions

The app requests exactly two Android permissions:

- **INTERNET** - to download forecasts and to search for cities.
- **ACCESS_NETWORK_STATE** - to tell whether a connection is available and show an appropriate message when you are offline.

The app requests no location, storage, camera, microphone, contacts or phone permissions.

## 4. The weather data provider

Forecasts and city search results are supplied by a third-party weather data provider. The app makes only two kinds of request, both encrypted with HTTPS:

**a) Forecast request**
- The latitude and longitude of the city you selected, **rounded to two decimal places** (a precision of roughly 1 km). This is the coordinate of the city you chose, not your device's position.
- A technical User-Agent header identifying the app and its version.

**b) City search request**
- The city name you typed.
- Your app language code, so results are returned in your language.
- The same technical User-Agent header.

No API key, account identifier, device identifier or advertising identifier is included in either request.

**Please note:** as with any internet request, your IP address is necessarily visible to the provider's servers when the app contacts them. The provider's handling of its server logs is governed by its own terms and privacy policy, not by ours. We do not receive, store or have access to those logs.

The app contains no WebView and loads no remote content other than the two requests above.

## 5. Android backup and device transfer

Today Weather has Android's backup feature enabled. This means your saved cities, app preferences and cached forecasts **may be included** in:

- **Cloud backup** - on most devices this is stored in your Google account's backup, handled by Google under Google's own privacy policy; and
- **Device-to-device transfer** - when you move your data to a new device.

This is a function of the Android operating system and your own backup settings, not a transmission to us. We cannot access these backups. If you do not want this data backed up, you can disable backup for the app in your device's system settings, or delete the app's backup from your Google account.

## 6. Data retention and deletion

- **Cached forecasts** are refreshed about once an hour while you use the app. A cached forecast is kept until you delete that city or uninstall the app.
- **Deleting a city** in the app permanently deletes both its saved place record and its cached forecast from your device.
- **Uninstalling the app** removes all locally stored app data. Copies held in Android cloud backup are separate and must be deleted from your backup settings if you want them gone.
- Because we operate no server and collect no personal data, there is nothing for us to retain, export or delete on your behalf.

## 7. Security

All network requests use HTTPS. Local data is kept in the app's private storage, which Android isolates from other apps. No data is transmitted to the developer.

## 8. Children's privacy

The app does not collect personal information from anyone, including children. It requires no account and contains no advertising, no in-app purchases, no social features and no user-generated content. It is suitable for a general audience.

## 9. International data transfers

The weather data provider may process requests on servers located outside your country. By using the forecast and city search features, the city coordinate or search text described in Section 4 is sent to that provider. No other data is transferred.

## 10. Your rights and choices

Because we hold no personal data about you, there is no personal data for us to access, correct, export or erase. You remain in full control of the data on your device: you can delete any saved city at any time, change your settings, disable system backup, or uninstall the app to remove all local data.

If you are in a jurisdiction that grants data-subject rights (such as the GDPR or CCPA) and you have a question about how the app handles data, contact us using the address in Section 12 and we will respond.

## 11. Changes to this policy

If the app's data practices change, we will update this policy and revise the effective date above. Material changes will be reflected in the app's store listing. Continued use of the app after an update constitutes acceptance of the revised policy.

## 12. Contact

Questions about this policy or the app's data practices: [noww6446@gmail.com]
