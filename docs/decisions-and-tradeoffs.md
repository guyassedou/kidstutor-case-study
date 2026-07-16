# Decisions and Tradeoffs

## Touch scratch work

**Observation:** Children sometimes need temporary space for calculations, especially on touch devices.

**Risk:** A modal or oversized tool can hide the question, trigger the keyboard, or create a second interaction problem.

**Decision:** Keep scratch work connected to the active question and make expansion explicit and reversible.

**Tradeoff:** The interaction requires more viewport and focus choreography than a standalone canvas, but better supports the actual learning task.

## Mobile keyboard behavior

**Observation:** Desktop-oriented focus recovery can open virtual keyboards without user intent.

**Decision:** Treat coarse-pointer devices differently and allow the child to summon the keyboard explicitly.

**Tradeoff:** Desktop and touch behavior diverge, increasing test surface but reducing disruptive mobile behavior.

## Hebrew vocalization

**Observation:** Correct adult-readable Hebrew is not always accessible to early readers, and automated vocalization tools can preserve pronunciation while changing spelling incorrectly.

**Decision:** Combine independent language tools with deterministic letter-level comparison.

**Tradeoff:** The workflow adds verification cost but avoids trusting one fallible transformation.

## Economy centralization

**Observation:** Progression and reward rules can silently drift when duplicated across product surfaces and operational tools.

**Decision:** Centralize policy and build parity checks before changing live behavior.

**Tradeoff:** The first change primarily improves architecture rather than immediately changing the child experience. It makes later tuning smaller and safer.

## Parent reporting

**Observation:** Parents need progress information, but adding reporting directly to the child experience can introduce complexity prematurely.

**Decision:** Develop reporting as a separate operational capability before committing to product UI.

**Tradeoff:** Parents do not immediately receive a full in-product dashboard, but the team can validate which information is useful before increasing interface and privacy complexity.

## Multi-agent implementation

**Observation:** Different AI tools can accelerate different classes of work, but their private conversational memory is fragmented.

**Decision:** Move durable project knowledge into repository context and require explicit handoffs.

**Tradeoff:** Maintaining context documents requires discipline, but reduces rework and prevents tools from inventing incompatible project state.

