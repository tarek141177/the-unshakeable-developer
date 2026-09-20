## 🔍 Architectural Context
- **Business Goal:** What problem does this change solve?
- **Blast Radius Analysis:** What downstream services or tables are touched by this diff?
- **AI-Assisted Lines:** Were any portions of this change generated via LLM?

---

## 🛡️ Reviewer Covenant
*The reviewing engineer attests to the following before clicking Approve:*

- [ ] **Beyond Happy Path:** Audited failure modes, timeouts, and downstream retry storms.
- [ ] **No Hallucinated Boundaries:** Verified all dependencies and schema migrations against real infrastructure.
- [ ] **Shared Liability:** I understand this failure mode and am prepared to co-own its operational behavior.

**Approved by:** `@username`  
**Documented Rationale:** `[Why this is architecturally safe to ship]`
