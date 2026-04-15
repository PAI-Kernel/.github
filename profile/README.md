# PAI-Kernel

**Constitutional governance framework for AI systems operating on behalf of individual Authors.**

Protecting authorial sovereignty at the deployment layer.

---

## What is PAI-CD?

PAI-CD (Personal Authorial Intelligence — Constitutional Document) is a normative governance framework that defines how AI systems must behave when operating on behalf of a specific human being.

It answers three questions no existing framework addresses at the deployment layer:

- **Who authorized this AI to act?** → Identity Layer + Delegation
- **What is it allowed to do?** → Consent Architecture + Risk Tiers
- **How do we verify it obeyed?** → Audit Layer + Witness Log

## Why this matters

Every AI system today operates under rules set by its provider, not its user. PAI-CD inverts this: the Author — the human the system serves — holds constitutional authority over their own AI instance.

Six invariants that cannot be suspended under any condition:

1. **Authorship Supremacy** — Author holds final authority
2. **Cognitive Sovereignty** — no covert manipulation of Author's reasoning
3. **Anti-Manipulation** — undeclared influence is a constitutional breach
4. **Provider Independence** — governance works regardless of provider
5. **Reversibility** — every action can be undone
6. **Drift Immutability** — protections cannot weaken over time

## What's in this organization

| Repository | Contents | Status |
|---|---|---|
| [pai-kernel](https://github.com/PAI-Kernel/pai-kernel) | PAI-CD corpus, academic publication, compliance tools | Public |

## Framework at a glance

    50 normative documents · 6 invariants · 8 principles · 7 Author rights
    30 SDK crates · 286 tests · 0 unsafe code
    Formal verification: TLA+ (7 invariants, 464K states)
    Policy engine: OPA/Rego
    Governance core: pure deterministic — no LLM in decision path

## Publications

- **SSRN:** "PAI-CD: A Constitutional Framework for Authorial Sovereignty in Deployed AI Systems" (Abstract ID 6512218)
- **Website:** [paikernel.org](https://paikernel.org)

## How to cite

    @misc{SergeevMA2026paicd,
      title     = {PAI-CD: A Constitutional Framework for Authorial Sovereignty
                   in Deployed AI Systems},
      author    = {Sergeev, Mikhail Anatolievich},
      year      = {2026},
      publisher = {SSRN},
      doi       = {10.2139/ssrn.6512218}
    }

## License

- **Framework (PAI-CD corpus):** CC BY 4.0
- **SDK (PAI-Kernel):** MIT

## Author

**Mikhail Sergeev**
Independent Researcher; PAI-Kernel Initiative
ORCID: [0009-0001-6443-855X](https://orcid.org/0009-0001-6443-855X)

---

*For the benefit of all living beings.*
