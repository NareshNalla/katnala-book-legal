# Play Console — Data safety draft (Katnala Book)

Use this when filling Data safety. Confirm against the live build before submit.

## Data collected

| Type | Collected | Shared with third parties | Required | Purpose |
|---|---|---|---|---|
| Name | Yes | No (except Firebase if sync on) | Yes for account | App functionality |
| Phone number | Yes | Same | Optional | App functionality |
| Other user content (gift notes, photos) | Yes | Gemini if user scans a page; Firebase if sync on | Optional | App functionality |
| Financial info (gift cash amounts) | Yes | Firebase if sync on | Yes for ledger | App functionality |
| App activity | Notifications / language prefs | No | Optional | App functionality |

## Security

- Data encrypted in transit (HTTPS to Firebase / Gemini)
- Users can request deletion (document email on Play listing)

## Privacy policy URL

https://nareshnalla.github.io/katnala-book-legal/privacy.html

Fallback until GitHub Pages is on:

https://nareshnalla.github.io/katnala-book-legal/
or
https://github.com/NareshNalla/katnala-book-legal/blob/main/privacy.html
