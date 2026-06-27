# AI Agent Evidence Checklist

When an AI or agentic system is held up in a security, procurement, or audit
review, "here is what it did" logs often don't settle the reviewer's real
question. This is what a reviewer can require — and a vendor should be able
to answer.

1. **Approved scope** — the data, tools, and actions the agent was authorized
   to use, defined before execution.
2. **Participating agents / workers** — which agents acted, and under whose
   authority.
3. **Human approval** — where it was required, and that it was obtained.
4. **Out-of-scope non-occurrence** — whether the agent *could* have acted
   outside the approved scope, not merely that it did not this time.
5. **Tamper-evidence** — that these records cannot be altered after the fact
   without detection.
6. **Independent verifiability** — that a party who trusts neither the agent
   nor its operator can check the above.

Items 4 and 6 are the hard ones: positive logs and self-attestation do not
satisfy them. They need a negative ("could not have") and an independent check.

## What this is — and isn't

This is an open checklist, offered for discussion. It is **not** a standard, a
product, or a compliance claim. It does **not** define *how* to satisfy any
item — in particular 4 and 6, which are deliberately left open. It makes no
claim of conformance to any framework (EU AI Act, ISO/IEC 42001, SOC 2, NIST).

Issues and pull requests welcome.

---

Maintained by Tatsuhiko Nagoshi ([AgentGymLeader](https://github.com/AgentGymLeader)).
Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
