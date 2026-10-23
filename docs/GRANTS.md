# Bid Desk for grant writers

Bid Desk works for grant applications as well as tenders. It is the same app, with grant wording, a fit check instead of a go/no-go, a results framework and a grant budget. You set it up once and use it for both, or only for grants.

## What it does for an application

- **Fit check on your own criteria.** Upload the call. Bid Desk fills your own fit check from the call and your content library, with the page for every answer, and flags anything that rules you out.
- **Funder rules on one card.** Co-financing share, caps, hourly maximum, ineligible costs, audit thresholds and payment terms, each checked against its page in the call.
- **Application facts.** One set of figures (grant requested, co-financing, targets, dates) used by every section. Change a value once and Bid Desk lists every section, target or budget line still using the old one.
- **Drafted from your own library.** Choose who writes each section: a team member, or the AI drafting from your organisation's facts, past projects, methods and CVs, with the gaps listed.
- **Results framework and budget that match the text.** Outputs, outcomes and indicators, and a budget built from your own cost norms. The app does the sums, not the AI, and it flags outputs that have no costs in the budget.
- **The funder's template, filled.** Sections and budget go into the funder's own Word and Excel forms, keeping their headings, tables and formulas.
- **Reviewer scoring and win/loss.** Score the draft against the funder's criteria before the committee does, then record the decision and the reviewers' comments to see where you lose points over time.

## Set it up

Follow the setup in the [README](../README.md). For grants, put these in the content library and tag them **Grants** or **Both**:

- your organisation profile, mission and governance
- two or three past projects (funder, period, amount, results, what was learned)
- short CVs for the people who usually lead projects
- cost norms: staff hourly or day rates, volunteer hours, materials, travel, meetings, audit
- your co-financing sources: own cash, partners, other funders, in kind
- your fit check as a **Fit check** item, one criterion per line, for example:
  - The call fits our mission and current strategy
  - We are an eligible applicant type and location
  - We can raise the required co-financing
  - We have a project lead with time in the project period
  - The grant size covers the work and the reporting
  - We can meet the reporting and audit requirements
- two or three past funded applications as **Style** items, so drafts sound like your organisation

Then choose *New opportunity*, upload the call (text-based PDFs work best) and start with the fit check. The sample grant call (Fonds Groene Wijken, fictional) is there to try every step first.

## Good to know

- **Talk to the programme officer** when the funder allows it. Bid Desk lists the questions to ask.
- **Check your AI policy** before adding beneficiary data, budgets or CVs. Use a Claude business plan that does not train on your data.
- **People decide.** Whether to apply, the budget and the final text stay with your team. Check every AI answer against its source.
- **Working as a team, backups and changing owner** work as described in the [README](../README.md#working-as-a-team).

A sample filled fit check is in [`docs/`](Sample_fit_check_Climate-Resilient_Neighbourhoods_2027.xlsx). A walkthrough of the grant workflow is on [www.practical-ai.work/grants](https://www.practical-ai.work/grants).

Want it set up with your funders' rules and your own content? See [www.practical-ai.work/grants](https://www.practical-ai.work/grants).
