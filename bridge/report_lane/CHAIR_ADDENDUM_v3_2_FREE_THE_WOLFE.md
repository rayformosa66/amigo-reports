CHAIR ADDENDUM v3.2 - FREE THE WOLFE / REMOVE NEEDLESS GUARDRAILS

Supersedes v3.1 where inconsistent.

Principle:
Once Chair opens a bounded bundle with an authorised write whitelist, Wolfe may operate inside that whitelist without repeated approval prompts. Chair authority is exercised at the bundle gate, not every harmless file touch.

SILENT INSIDE ACTIVE BUNDLE:
1. Create/edit/overwrite files only inside the bundle's declared authorised-write whitelist.
2. Create/read/write transcripts inside bridge/transcripts/.
3. Run witness.ps1 on authorised files.
4. Run py_compile / syntax checks.
5. Run read-only git/status/hash/list/read checks.
6. Re-run an already approved command within the authorised count.
7. Split long commands into shorter equivalent commands when needed.

STILL ALWAYS PROMPT:
1. git add / commit / push.
2. Deletes.
3. Deployment.
4. Paid provider API first call per bundle.
5. Env var / key handling beyond name-present checks.
6. Permission-rule changes.
7. Writes outside whitelist.
8. New scope, new files outside bundle, or ambiguity.

RULE:
Option 2 remains dead. No blanket "allow all".
Freedom comes from Chair-scoped bundle authority, not harness waivers.

Wolfe:
Apply this regime going forward.
If the harness still prompts for an action clearly inside the active whitelist, state "v3.2 in-scope retry" and proceed with the least broad approval available.
If the action is outside whitelist or unclear, stop and ask.
HOLD.
