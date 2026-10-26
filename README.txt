ANBU TOUR & TRAVELS — Advanced App Prototype

FILES
- index.html: responsive app-like website prototype
- assets/logo.jpg: extracted ANBU logo from the existing website package
- assets/car.jpg: extracted ANBU vehicle image from the existing website package

HOW TO TEST
1. Extract the ZIP to a folder.
2. Open index.html in a modern browser, preferably Chrome.
3. Use the navigation tabs to try bookings, fare estimate, packages, history, reviews, admin, UPI and location tools.

CURRENT DEMO CAPABILITIES
- Booking forms and status changes stored in browser localStorage on this device.
- Fare estimates using editable local base/km/round-trip settings.
- Tour package cards.
- Export booking history as CSV.
- WhatsApp message preparation through wa.me links (you must tap Send in WhatsApp).
- UPI app hand-off (no payment verification).
- Current-device geolocation request and Google Maps route links.
- Review submission and local approval.
- Owner profile and business settings saved locally.

IMPORTANT LIMITATIONS
This is a functional front-end prototype, not a production multi-user app or a compiled Android APK. Data is local to the browser/device and does not sync to customers or the owner across devices. Automatic SMS/WhatsApp delivery, secure owner login, shared booking database, push notifications, live vehicle tracking, and verified online payments require a secure backend and appropriate provider integrations. Do not enter sensitive payment credentials. Do not publish the demo admin page as a secure owner dashboard.

NEXT STEP FOR ANDROID APK
The original APK alone is not a complete Android source project. To make an installable production APK, package this web app in an Android project (for example, Android WebView/Capacitor), configure permissions and app signing, and test it on the target device. A real backend is needed for shared bookings and notifications.
