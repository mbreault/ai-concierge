# Source index and provenance

Archived 2026-09-14 from the connected `mbreault/ai-concierge` repository and [AI Concierge Research](https://chatgpt.com/c/6aa7fce5-659c-83ea-9499-3fff6722ae42). Import date is distinct from a source's research or publication date.

## Requested material

| ID | Material | Archive | Preservation / attribution |
| --- | --- | --- | --- |
| S01 | Original offering draft, `offerings.md` attachment | [original-v1.md](../offerings/versions/original-v1.md) | Exact bytes; also identical to the existing root [offerings.md](../offerings.md). User-provided rough draft. |
| S02 | Gemini analysis, uploaded as `Pasted markdown(20260914-141601).md` | [gemini-analysis.md](sources/gemini-analysis.md) | Exact bytes, including references and formatting. Attributed to Gemini by the user's accompanying message; filename alone is not the attribution. |
| S03 | Claude research, `ai-concierge-market-research.md` | [claude-market-research.md](sources/claude-market-research.md) | Exact bytes. Report identifies September 2026; uploaded with the user's request to compare Claude's opinion. |
| S04 | Claude revised offering, `Claude offerings-v2.md` | [claude-offerings-v2.md](../offerings/versions/claude-offerings-v2.md) | Exact bytes, including internal comments, original vendor claims and the SLA arithmetic error. |
| S05 | ChatGPT discussion | [chatgpt-discussion.md](sources/chatgpt-discussion.md) | Chronological archive of all six retrieved turns; user/assistant text unchanged, with editorial headings and coverage note added. Attachment notices and native citation markers retained. |
| S06 | Mike's latest naming and entry-price feedback | [positioning-and-entry-feedback.md](../brainstorming/2026-09-14-positioning-and-entry-feedback.md) | Exact user messages in this Codex task, with separately labeled interpretation. Selects AI Concierge and an initial-call price below $1,000. |

The [integrity manifest](integrity-manifest.json) records original filenames, file sizes and SHA-256 hashes for the four attachment copies, plus original repository blob hashes and baseline content hashes. Temporary download paths are intentionally not part of the repository. These hashes verify preservation, not factual accuracy.

## Conversation coverage

The retrieval returned six turns with no further page cursor:

1. [Initial request](sources/chatgpt-discussion.md#turn-1): Mike's background, research brief and original attachment notice. **The original ChatGPT deep-research answer was not exposed.**
2. [Gemini comparison](sources/chatgpt-discussion.md#turn-2): user identifies Gemini's attachment; ChatGPT proposes $750 discovery, higher implementation prices and an off-menu hardware concept.
3. [Hardware follow-up](sources/chatgpt-discussion.md#turn-3): Mike explicitly supports addressing hardware liability and roughly tenfold pricing; ChatGPT proposes $15,000+ deployment and boundaries.
4. [Claude comparison](sources/chatgpt-discussion.md#turn-4): Claude's two attachments and ChatGPT's final synthesis, including $2,500/90-day discovery and Platform Adaptation.
5. [Repository access discussion](sources/chatgpt-discussion.md#turn-5).
6. [Archive/iteration request](sources/chatgpt-discussion.md#turn-6).

The missing initial report is a specific archival gap. Competitor prices mentioned in later messages remain **claims in that discussion**, not a reconstructed or reverified report. If the report becomes available, add it as a new source without replacing the discussion archive.

## Existing repository content

Baseline: [da7df57b6392afb8b3a183b6f9e9288d6f1b0623](https://github.com/mbreault/ai-concierge/commit/da7df57b6392afb8b3a183b6f9e9288d6f1b0623).

| File | Treatment | Context |
| --- | --- | --- |
| [README.md](../README.md) | Original two-line introduction retained; navigation appended | Existing project purpose |
| [offerings.md](../offerings.md) | Unchanged in place; exact additional O1 snapshot | Original offer, not current |
| [in-person-training.md](../in-person-training.md) | Unchanged | Workshop-growth excerpt; original author/link missing |
| [fiverr-refs.md](../fiverr-refs.md) | Unchanged | Two original marketplace-reference URLs, including query parameters |
| [corti-moore-orlando.md](../corti-moore-orlando.md) | Unchanged, including filename spelling and truncated ending | Firm-engagement snippet; authorship/relationship unconfirmed |

## Editorial derivatives

- [Gemini proposal](../offerings/versions/gemini-proposal.md): extracted from S02; no standalone Gemini offering attachment existed.
- [ChatGPT after Gemini](../offerings/versions/chatgpt-post-gemini.md): extracted from S05 turns 2–3, including both hardware price stages.
- [Synthesis v3](../offerings/versions/2026-09-14-synthesis-v3.md): based primarily on S05 turn 4, using S04's draft deliverables where explicitly identified. Editorial scope choices and unsettled terms are labeled.
- [AI Concierge v4](../offerings/versions/2026-09-14-ai-concierge-v4.md): incorporates S06; restores the $750 diagnostic from S05 turn 2 as a proposal under the user's price ceiling. Supersedes v3 without altering it.
- [Comparison](../offerings/comparison.md), [decision log](../decisions/README.md) and [brainstorming](../brainstorming/README.md): authored navigation and analysis, not original model attachments.

Read the [research caveats and corrections](README.md#evidence-and-corrections) before using source claims in a live proposal. No linked vendor pages were reverified as part of this preservation task.
