## Architecture Overview — X5

Frontend:
- Lovable (React + Vite)
- Presence-first UI
- Seat-scoped views
- HUD-driven navigation

Backend:
- Supabase (Postgres + RLS)
- Token-based seat claiming
- Household-scoped data
- Edge functions (presence-intake)

Core Concepts:
- Household = sovereign boundary
- Seat = role + authority
- PAN-1 = declared home origin (Pillar)
- Presence Registry = intake ledger (write once)

No surveillance.
No passive tracking.
All actions are user-initiated.
