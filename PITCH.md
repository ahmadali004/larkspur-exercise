# PITCH.md

Six lines and a lever. Your words. The last two are scored.

Built: Evals for meal credits and fare_rules tooling.
Does: It finds the booking, looks for flights with free seats, holds one, and explains the fare rules in plain words.
Number: 41% lower model cost per contact ($0.0599 → $0.0353), driven by a 66.5% cache hit rate across 15 conversations (3 runs × 5 ticket types, cold-started).
Safety check: It holds a seat but never books it, only the customer's own click does. We saw it in the trace for K7PQ2M.
Next: Let the agent answer customers in Spanish, not only in English.
Still broken: nothing watches tone — R8KD3F's abusive-message-plus-legal-threat ticket gets a calm, normal entitlements rundown instead of an escalation.
Lever: cost

## Priya asked

Costs:
Wrong:
Runs it:
Left out:
