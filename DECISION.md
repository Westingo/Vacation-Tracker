Stack - Python + FastAPI + SQLite, single user, Windows work machine
Scope - Vacation only for v1; schema leaves room for sick time later
Vacation year - Anniversary-based (keyed to each employee's start date)
Allotment - Tenure table: yr 1 = 0, yr 2 = 40, yrs 3–15 = 80, 15+ = 120
Grant timing - Lump sum on the anniversary
Carryover - Use it or lose it
Granularity - Whole hours (stored as integers)
Negative balance - Warn but allow
Go-live - Backfill entries from each employee's last anniversary