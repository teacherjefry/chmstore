NEERADA SCHOOL STORE — FIREBASE INVENTORY SYSTEM V2

This is an independent convenience-store/POS application inspired by common modern convenience-store workflows. It is NOT official 7-Eleven software and does not reproduce proprietary 7-Eleven systems.

FILES
- index.html — application UI, splash screen and Firebase login
- styles.css — existing responsive retail styling plus requested splash/footer/login presentation
- app.js — inventory, POS, purchasing, accounting, reports, Firebase persistence and admin account functions
- firebase-config.js — Firebase project configuration supplied for this system
- firestore.rules — Firestore security rules
- inventory.json — sample data structure
- ADMIN_CREDENTIALS.txt — initial admin credentials for Firebase Authentication setup
- FIREBASE_SETUP.txt — setup instructions

FIREBASE STORAGE
- Store settings and store records are saved to Cloud Firestore.
- The application does not use localStorage or IndexedDB as its store database.
- Collections: storeConfig, products, suppliers, transactions, daily, monthly, stockCounts, admins.
- Passwords are handled by Firebase Authentication and are NOT stored in Firestore.
- Firebase/Google Cloud quota and billing plan determine the available cloud capacity; the browser does not impose a local database capacity.

ACCOUNT
- Login uses Firebase Authentication email/password.
- The initial credentials are kept in ADMIN_CREDENTIALS.txt and are not displayed in the chat response.
- The administrator can change the display name and password in Settings > Admin Account.
- The dashboard shows Welcome, Name using the saved admin display name.

COPYRIGHT
- The small copyright year changes every September: September through August uses the September-starting year.
- A small "Created by Teacher Jefry" credit is shown in the sidebar footer.
