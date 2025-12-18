## Security Model

- Row Level Security (RLS) enforced on all tables
- Household isolation is absolute
- Seat #1 = Primary Admin (cannot be locked out)
- Token-based invites (no email dependency)
- Presence Registry scoped by household
- PIN gating for sensitive modules (local session only)

Explicit Non-Goals:
- No background monitoring
- No biometric storage
- No hidden data collection
