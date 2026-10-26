# Table Order – live setup (about 5 minutes)

1. Go to https://console.firebase.google.com and create a project (no Analytics needed).
2. Build > Firestore Database > Create database > Start in production mode > pick a region.
3. Firestore > Rules tab: paste the contents of firestore.rules and Publish.
4. Project settings (gear) > Your apps > Web (</>) > register an app. Copy the firebaseConfig values.
5. Open index.html and paste them into FIREBASE_CONFIG near the top of the script.
6. Upload index.html to your GitHub repo (replace the old one) and wait ~1 minute.
7. Open the site > Cashier > PIN 1234 > Menu > Load sample menu. Then add or delete items.

Customers use the site link. Cashier uses the same link, Cashier tab (PIN 1234 - change STAFF_PIN in index.html).
