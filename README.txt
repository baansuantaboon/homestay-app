Baan Suan Taboon Homestay Manager — Version 9.1

Fix:
- Corrected the Version 9 sign-in failure.
- The Version 9 JavaScript expected new PDF/Image button IDs while the page still used
  the old print button ID. This caused JavaScript to stop before attaching the login handler.
- Added defensive checks so optional export buttons cannot break login initialization.
- Retains blue signature, one-page A4 printing, PNG export, per-room dates, discounts,
  billing/tax fields and Firebase cloud sync.
