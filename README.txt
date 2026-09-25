EQUB MANAGER — LOCAL DEMO
==========================

This version intentionally does NOT connect to Firebase.

Files:
- index.html
- style.css
- app.js

Features:
- Super Admin dashboard
- Member management (1–100 supported)
- Weekly cycle + amount
- Payment/slip submission simulation
- Verification: Confirm / Reject
- Paid status
- Local notification center
- Super Admin notification when a slip is submitted
- Member notification when payment is confirmed/rejected
- Equb draw from paid/eligible members
- Cryptographic randomness for final winner selection in the browser
- Draw history
- Responsive mobile layout
- localStorage persistence

Important:
This is a functional local prototype, not the production/security layer.
No real bank slip image is uploaded in this demo; the "View slip" button shows a local placeholder.
Real authentication, Firebase Firestore/Storage, FCM push notifications, Cloud Functions, security rules and real image uploads will be connected after approval.

For real FCM web push, Firebase's official documentation requires Firebase initialization, a service worker, notification permission and web credentials; FCM web requires HTTPS. See:
https://firebase.google.com/docs/cloud-messaging/web/get-started
