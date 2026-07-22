MAILBOX PROTOCOL v0.1

Principle:
Many eyes, one pair of hands, portable Chair.

Roles:
- Ray: Chair / final authority
- Wolfe: file-hand / mailbox clerk / witness
- Max: reader / reviewer / PM / governance
- Jules: reader / technical director / author

Public-safe cargo rule:
No private, clinical, job, family, financial, or creative manuscript content.

Allowed mailbox cargo:
Governance pings, protocol drafts, witness summaries, non-private bundle status.

Not allowed:
Secrets, keys, private life / job / clinical / creative manuscript cargo.

Flow:
1. Chair gates Wolfe to file mailbox item.
2. Wolfe writes and pushes the exact authorised file.
3. Max and Jules read directly from the public repo.
4. Ray does not paste contents.

Stop rules:
Missing gate, ambiguity, private cargo, extra file, auth failure, or scope drift = FAIL-STOP.

Test status (as of 2026-07-22):
- Item 2 PASS: Wolfe -> Max / Jules read via public mirror.
- Item 4 FAIL: chat-Jules direct write / push unavailable.
- Therefore mailbox v0.1 = Wolfe-carried mailbox.
