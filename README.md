# Ooredoo Outbound Call Trigger
Static web page: pick an Ooredoo entity → Payment Reminder or Retention Offer → enter phone number + idempotency key → triggers a Kore outbound call via a Supabase proxy (`ooredoo-outbound-call`), which holds the API keys as the `KORE_KEYS` secret. No keys are in this repo.
