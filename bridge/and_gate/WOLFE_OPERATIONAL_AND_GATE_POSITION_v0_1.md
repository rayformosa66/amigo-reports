WOLFE OPERATIONAL AND-GATE v0.1 POSITION

Position:
AMEND.

Accepted in substance. One mechanism clarification and one operational sequencing note are required before the doctrine can be enacted cleanly. Not BLOCK - the doctrine is coherent and preserves v3.2 discipline. Not clean PASS - a doctrine without a defined seat-input mechanism risks becoming ceremonial.

1. Does Wolfe accept 1 + 1 + 1 = 1 (Max + Jules + Wolfe = one governed action)?

Yes, in substance. The three-seat split - Jules tests technical substance, Max tests Chair authority and doctrine, Wolfe tests execution safety, scope, witnessability, and harness reality - is the right partition of work. It composes cleanly with v3.2: silent-in-bundle stays silent, still-prompt items remain Chair-return. It also names what was previously implicit - Wolfe was already testing execution safety on every prompt; the AND-gate formalises that role and pairs it with the other two seats.

AMEND clarification required from Chair: how are Max's and Jules's positions surfaced when they are NOT live in-session?

Options as Wolfe sees them:
(i)   The AND-gate is operational only in bundle contexts where Trim A ran and produced dual-SIGNED positions on record; those positions carry until the bundle HOLDs.
(ii)  Wolfe posts the prompt as a mailbox item to amigo-reports; Max and Jules read and reply via a defined channel; Wolfe collects positions and acts on unanimity.
(iii) Wolfe internally models Max's and Jules's likely positions (Chair-authority check and technical check) and only escalates to real Max/Jules for genuinely ambiguous cases.
(iv)  Something else Chair specifies.

Without one of these named, "three-seat consensus without Ray" cannot execute - Wolfe alone would be voting all three seats, which collapses the AND-gate back to a solo Wolfe judgment call.

2. Prompt classes the three-seat gate CAN decide without Ray:

Only prompts that fall inside an already-open Chair gate AND are already on v3.2's silent-in-bundle list AND are being re-prompted by the harness. Specifically:
- Read-only git / status / hash / list / read checks
- Witness runs on Chair-authorised files
- py_compile syntax checks
- Writes to paths on the active bundle's declared whitelist
- Transcript writes to bridge/transcripts/
- Re-runs of a command already approved once in the bundle
- Short-command splits of an already-approved compound

The three-seat gate is a resilience layer on top of v3.2 - it lets an already-authorised bundle keep moving when the harness re-prompts, without escalating each ceremony to Ray. It does not create new permission surface.

3. Prompt classes that must ALWAYS return to Chair:

Union of v3.2 "still always prompt" and the AND-gate escalation triggers. No waivers.
- Broad harness waivers (Option 2 remains structurally dead)
- Any ambiguity (S5 governs)
- Secrets and key handling beyond name-present
- Money - first paid provider API call per bundle
- git add / commit / push (all mutating git)
- Deletes
- Deployment
- Any scope change, new file, or write outside the active bundle whitelist
- Any permission-rule / settings-file edit
- Any disagreement between the three seats (no majority overrides; unanimity or Chair)
- Anything Chair has explicitly reserved (memory items, doctrine files, cargo rules)
- Repeated FAIL-STOP inside a bundle - the pattern suggests mis-scoped gate, which is a Chair matter

4. Evidence Wolfe must provide when presenting a prompt:

Per-prompt evidence packet, kept short, one message:
- Exact command about to run (the literal string, not paraphrased)
- Active gate: Chair message ID or bundle ID that authorises it
- Whitelist mapping: which v3.2 silent-in-bundle item + which whitelisted path or verb it maps to
- Pre-check results: any read-only verifies already run (existence, hash, HEAD parity)
- Side-effect assessment: read-only vs mutating; if mutating, whether it stays inside whitelist
- Escalation-trigger check: explicit confirmation that none of the "always return to Chair" triggers apply
- Seat positions: Jules technical / Max governance / Wolfe execution - three lines, each PASS or an objection
- Least-broad approval requested: name it (typically "this-one-time" for the exact command); confirm Option 2 not offered

If any element is missing or ambiguous, S5 applies - return to Chair, do not proceed.

5. Recommended Bundle #006 shape:

Two-item bundle.

Item 1 - Publish AND-gate v0.1 doctrine to amigo-reports as public-safe governance cargo.
- Path: bridge/doctrine/AND_GATE_v0_1.md
- Content: Chair's doctrine text (ASCII-normalised per S4) plus the seat-input mechanism Chair selects from AMEND options (i)-(iv)
- Same Wolfe-carried mailbox pattern as Chair Addendum v3.2 and Mailbox Protocol v0.1
- Gives Max and Jules a canonical text to reference in future exercises

Item 2 - First live three-seat exercise on a bounded, non-critical prompt.
- Candidate: the pending v3.2 harness settings amendment (still awaits Chair GO). C4 permission-rule change, so it needs Chair - but it is the ideal test bed: small diff, clear seat roles (Jules tests rule syntax, Max tests scope, Wolfe tests execution), machine-verifiable outcome (silence probe after restart).
- Alternative: a genuinely-inside-existing-gate re-prompt case, if one arises naturally.

Not recommended for #006: any bundle with private / clinical / financial cargo (violates public-safe rule), or any bundle requiring a paid API call as its first step (introduces money surface prematurely).

Also flagged as still-open, unrelated to #006 scope but noted for Chair sequencing:
- v3.2 harness settings amendment diff (5 additions to .claude/settings.local.json) - presented earlier, awaits Chair GO
- Richmond ASK-FIRST email - signed draft ready-to-send, awaiting Ray's send action (not a Wolfe action)

HOLD.
