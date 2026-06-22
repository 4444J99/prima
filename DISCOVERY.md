# Discovery — organvm/prima

**Verdict: real value — promoted to ranked tier**

`organvm/prima` is the ORGANVM estate's first fully-realized AI companion pet *and*, more importantly, the reference implementation of a portable, privacy-safe pet package standard. The repo ships a validated 1536×1872 spritesheet with nine animation rows covering all eight required workflow states (idle, active, waiting, blocked, complete, error, unknown, stale), a formal JSON Schema (`tools/pets/pet-manifest.schema.json`), and a deterministic package validator (`tools/pets/validate-pet-package.mjs`) that enforces checksum integrity, forbidden-field rules (no user history, mood, or memory may leak into the package), and spritesheet dimension math — all with zero external runtime dependencies. The highest latent value is the **package protocol and validator together**: every future pet in the ORGANVM estate can be published against the same schema and cleared by the same tool, making this repo the load-bearing foundation for a scalable pet distribution layer. Prima itself is a polished, funded, user-facing creative asset (GitHub Sponsors + Payrail are live) that creates developer engagement and Codex stickiness; the seven-level evolutionary plan shows a clear governance-first path to capability-bearing pets with signing, sandboxing, and permission prompts explicitly deferred until the passive standard is stable.

**Best first task:** implement the Level 2 runtime state adapter contract — a typed interface and deterministic state-transition replay fixture — so the protocol moves from documented-but-unverified to testable and multi-pet portable, unblocking the plan's Milestones C and G.

*Auto-discovered 2026-06-22*
