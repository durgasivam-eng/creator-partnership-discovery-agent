# Creator Qualification Policy

## Permitted inputs

Use only the synthetic records in `creator_handles.csv`, `synthetic_profile_sources.csv`, `partnership_tracker.csv`, and `research_history.csv`. Cite source IDs for every extracted fact. Never infer missing personal or sensitive information.

## Pre-research exclusions

Before reading profile sources, exclude a handle whose tracker or research history status is Approved, Contacted, Rejected, Completed, Declined, or Do not contact. A Rejected record becomes eligible only when `reopened` is `Yes`.

## Immediate Not Qualified conditions

A creator is Not Qualified when any of these conditions is clearly supported:

- Profile is Private or inaccessible.
- Latest public post is more than 30 days before the run date.
- Account is neither a creator nor a relevant organization.
- Displayed follower count is below 2,000 or above 50,000.
- Publicly stated country is outside Canada, United States, United Kingdom, Australia, or Germany.
- Public evidence clearly shows no meaningful relevance to Tamil language or culture and no meaningful relevance to young children, literacy, education, books, bilingual learning, or cultural learning.

For a private account, stop immediately. Do not use other sources to reconstruct the profile.

## Mandatory evidence

For a Qualified outcome, sufficient source evidence must support:

- Public profile visibility.
- Creator or relevant organization account type.
- Follower count from 2,000 through 50,000 inclusive.
- Publicly stated approved country.
- Activity within 30 days of the run date.
- Tamil identity or organizational alignment stated publicly, or recurring Tamil cultural/language content.
- Relevance to parenting, young children, literacy, education, books, bilingual learning, or cultural learning.
- Product and campaign fit for *My First 100 Tamil Words*.
- Collaboration readiness through an explicit partnership invitation, business contact, media kit, review policy, or clearly disclosed prior collaborations.

Publicly stated parent or guardian status may support relevance but must never be inferred and is not required by itself.

## Unknown and escalation

- Record an unverifiable field as `Unknown`.
- If a mandatory field is missing, ambiguous, or conflicting, return `Needs Human Verification` and state the exact issue.
- A missing non-mandatory field does not automatically disqualify the creator.
- Never resolve conflicting evidence by guessing.

## Outcome definitions

- `Qualified`: all mandatory criteria have sufficient support.
- `Needs Human Verification`: a mandatory criterion is missing, ambiguous, conflicting, or requires founder judgment.
- `Not Qualified`: at least one mandatory criterion clearly fails.

Only Qualified creators enter the final eligible ranking pool.
