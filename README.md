# PEP Tracker

A small checklist app, hosted here only so it has a real URL a phone can reach.

No data lives in this repo. All reads/writes go straight to Supabase, gated by a
per-person PIN and row-level security policies checked server-side — the anon key in
`index.html` is a public-safe "publishable" key, not a secret.

Source of truth for this project (planning docs, decisions, schema) lives in a private
repo and is not published here.
