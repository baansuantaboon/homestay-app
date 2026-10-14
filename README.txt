Baan Suan Taboon Homestay Manager — Version 9.2

Fixes based on Android testing:
- Fixed blank PDF/print preview. The previous print CSS hid the document's parent container.
  V9.2 keeps the document in the print render tree and hides other content with visibility.
- Fixed Save as Image error "Cannot read properties of null (reading cloneNode)".
  The exporter now clones the actual #document element directly.
- Keeps Version 9.1 login fix.
- Keeps one-page A4 layout, embedded blue signature, Firebase sync, per-room dates,
  discounts and billing/tax fields.
