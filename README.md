# BEAD Policy Gates

A single-page, mobile-first interactive timeline tracking every deadline, dependency, promise, congressional recess, and federal-systems change bearing on one question: **when will states learn how they can use the roughly $21 billion in BEAD nondeployment funds?**

**Live:** https://deuslexxmachina.github.io/BEADPolicyGates/

Covers December 2025 through October 1, 2026. Every event is sourced to the primary record and carries its citation on the card.

## What it shows

The page is a split layout. A frozen dependency spine on the left holds the four-step lock created by Executive Order 14365 (DOJ list, section 3; Commerce evaluation, section 4; NTIA policy notice, section 5a; FCC proceeding, section 6). The right column scrolls forward through time. As you pass each missed nondeployment-guidance deadline, a running counter climbs, because the accumulation of broken and reset commitments is the point.

There is deliberately no "today" marker. The subject is the pattern of movement across time, not the present moment.

Five analytical throughlines carry the argument:

1. **The dependency chain problem.** The section 3 DOJ list, the legal predicate for everything downstream, was due around January 10, 2026 and never published. Every gate below it stays frozen at step one.
2. **The slipping guidance deadline.** Four sequential commitments for nondeployment guidance (March 11, per NTIA staff; March 26, per Rep. Dingell; "two months" or roughly June 22, per Lutnick on April 22; and "this summer," per Roth on June 30), each vaguer than the last.
3. **The $21B framing trap.** Executed grant agreements are not deployed broadband. Homes are connected in only two states, and GAO has an open recommendation that NTIA better communicate program financial sustainability to Congress.
4. **Two speeds, one order.** The EO's litigation arm moved fast and off-script (DOJ intervened behind xAI against Colorado's SB 24-205 before Commerce ever published the section 4 list, and Colorado then repealed the law itself), while the BEAD-conditioning chain that actually gates the money never fired.
5. **The October 1 wall.** Three regime shifts land on one date: the OMB 2 CFR 200 rewrite takes effect, FY2027 begins, and NTIA's grants system cuts over to eRA/GEMS. Any nondeployment award not executed before October 1 meets all three at once.

## Methodology and source discipline

Every event card names its source. The analysis distinguishes what officials said (transcribed from the record) from what is inferred, and it flags interpretive readings rather than presenting them as settled fact. Where two officials describe the same missed deadline differently (March 11 versus March 26), both dates are plotted, because the divergence is itself the record.

Litigation events (the xAI suit, the DOJ intervention, the enforcement stay, and the Colorado repeal) are shown in the time stream as a parallel thread. They do not move the spine, because the spine represents the BEAD-conditioning pathway, which remains frozen. The distinction is intentional: going around the sequence in court did not unlock the money.

## Sources

- Executive Order 14365, "Ensuring a National Policy Framework for Artificial Intelligence" (Dec 11, 2025)
- House Energy & Commerce Subcommittee on Communications and Technology, NTIA oversight hearing (Jun 30, 2026)
- Senate Commerce-Justice-Science Appropriations Subcommittee, testimony of Secretary Lutnick (Feb 10 and Apr 22, 2026)
- OMB 2 CFR 200 Notice of Proposed Rulemaking
- DOC GEMS/eRA Program Management Office recipient notice (May 1, 2026)
- DOC Office of Inspector General, OIG-25-025-A, "The Department's Vision for an Enterprise Grants Management System Has Not Been Realized" (Jun 30, 2025)
- GAO-26-109042, Priority Open Recommendations: NTIA (Jun 22, 2026)
- Colorado SB 26-189 (signed May 14, 2026) and the xAI v. Colorado docket
- 2026 House and Senate legislative calendars
- Ready.net internal 2RPN delay-hypotheses analysis (Mar 17, 2026)

## Viewing locally

No build step. Open `index.html` in any browser, or serve the folder:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html` — the timeline (self-contained: HTML, CSS, and JS in one file, fonts loaded from Google Fonts)
- `preview.png` — social-card image referenced by the Open Graph and Twitter meta tags (1200x627)
- `README.md` — this file
- `LICENSE` — CC BY 4.0

## License

Licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). Share and adapt with attribution.

Published by DeusLexxMachina. This is independent policy analysis and is not legal advice; confirm any operational decision against current NTIA guidance and your Federal Program Officer.
