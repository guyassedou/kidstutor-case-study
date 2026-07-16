# Product Thinking

## Start with the child's moment, not the feature list

The central product question is not whether a learning application contains enough features. It is whether a child can understand what is being asked, respond without fighting the interface, recover from a mistake, and feel motivated to continue.

That framing changes prioritization. Small interaction failures can matter more than large new capabilities when they interrupt a child's confidence or concentration.

## Design for distinct operating environments

Desktop and touch devices are not interchangeable. Focus recovery that helps a keyboard user can unexpectedly open a virtual keyboard on a tablet. A drawing surface that appears useful in isolation can hide the question or answer field in the real viewport.

The product therefore treats device behavior as part of the learning experience:

- Touch input is deliberate rather than automatic.
- Scratch work stays connected to the current question.
- Scroll position and sticky elements are tested at realistic viewport sizes.
- The child retains control over when tools expand, collapse, or disappear.

## Localization is product design

Hebrew support is more than translation. Vocalization, text-to-speech, bidirectional layout, mathematical notation, and age-appropriate reading ability interact.

The operating principle is to convert language quality into a verifiable system:

- Preserve the intended consonant spelling.
- Add vocalization without silently changing letters.
- Cross-check uncertain language output.
- Build deterministic checks for errors tools cannot reliably detect.
- Make the verification workflow reusable for future content.

## Motivation needs an economy, not isolated rewards

Ranks, experience points, achievements, and shop items shape one another. If they are tuned independently, pacing and perceived value drift.

The product approach separates:

- Policy: progression thresholds, reward values, and catalog decisions
- Mechanism: deterministic calculations and eligibility rules
- Evidence: simulation and observed behavior
- Presentation: how progress and rewards appear to children

This allows later tuning to be treated as a product decision with measurable consequences rather than a collection of arbitrary edits.

## Feedback becomes traceable work

Raw feedback is not a roadmap. Feedback is translated through a sequence:

```text
Observation → underlying problem → product decision → scoped change → verification
```

The workplan records what is supported by evidence, what remains an assumption, what was approved, and what is still unresolved. Identifying feedback and private source material remain outside this public case study.

## Separate audiences when their jobs differ

Children need a focused practice experience. Parents need trustworthy progress information. Combining both jobs in one interface risks making the child's product feel administrative.

The product therefore explores parent reporting as a separate capability with its own information needs, privacy boundaries, and release criteria.

