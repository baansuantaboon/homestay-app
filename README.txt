Baan Suan Taboon Homestay Manager — Version 3 (Firebase Cloud Sync)

Upload all files in this folder to the existing GitHub repository root, replacing older files.

Changes:
- Firebase Email/Password sign-in
- Firestore cloud synchronization across devices
- Shared homestay login
- Real-time booking/calendar updates
- JSON export/import remains available
- Version 2 local bookings can be migrated after first sign-in
- Receipt counter starts at RCV0002 to avoid collision with the existing RCV0001 receipt

Do not put guest data or passwords in GitHub files. The Firebase web configuration is intentionally client-side; Firestore access is protected by Authentication + Firestore rules.
