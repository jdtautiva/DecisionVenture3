# Decision Venture 3
> **Interactive Opportunity Analysis simulator for evaluating innovation opportunities through sequential evidence, iterative investment decisions, and strategic managerial judgment.** Developed by Julián Díaz Tautiva, PhD

---
## Overview

**Decision Venture 3** is a browser-based pedagogical simulation designed for undergraduate and graduate courses on innovation viability, entrepreneurship, opportunity analysis, and managerial decision-making. Students take the role of decision-makers who must allocate scarce resources among competing innovation opportunities and revise those allocations as new evidence becomes available.

The simulation begins with 100 investment points and four alternative opportunities. Students initially allocate points using only their intuition and the basic idea description. They then progress through three analytical rounds—external analysis, financial analysis, and internal analysis—reassessing their investment portfolio after each new layer of information. The activity makes changes in judgment visible by recording the allocation made in every round and showing the evolution of investment at the end.

Rather than treating an attractive idea as equivalent to a viable opportunity, the simulator requires students to examine whether market conditions support demand, whether the economics appear viable, and whether the organization has the resources and capabilities required to execute the opportunity. Financial evidence includes prices, costs, contribution margins, fixed costs, initial investment, and break-even estimates, while the internal analysis focuses on capabilities, operational constraints, partnerships, and organizational fit.

After completing the analytical rounds, students make a strategic recommendation, **GO, MODIFY, WAIT, or NO-GO**, only for opportunities in which they still maintain a positive investment. The activity then moves into a metacognitive closure in which students reconstruct the Opportunity Analysis process, identify which dimension most changed their judgment, compare their initial and final allocations, and connect the exercise to the distinction between an idea and an investable opportunity.

The simulator runs as a single HTML file and requires no backend or JavaScript libraries. It can be opened locally, shared through a learning management system, hosted on a web server, or published using a static hosting service such as GitHub Pages.

---
## Learning Objectives

By completing the simulation, students are able to:

- Distinguish between an attractive idea and an actionable business opportunity
- Allocate scarce resources across competing innovation opportunities
- Revise investment decisions when new evidence becomes available
- Evaluate market attractiveness using demand, willingness to pay, competition, substitutes, customer behavior, and adoption barriers
- Interpret contribution margin, fixed costs, initial investment, and break-even estimates in an opportunity analysis
- Assess whether expected demand appears consistent with the financial requirements of an opportunity
- Evaluate organizational fit through resources, capabilities, operational experience, partnerships, legitimacy, and implementation constraints
- Recognize that an opportunity may be attractive in the market but unsuitable for a specific organization
- Compare initial intuition with evidence-based managerial judgment
- Use changes in investment allocation as an explicit representation of learning and belief updating
- Recommend whether an opportunity should proceed, be modified, wait for additional information, or be abandoned
- Explain how external, financial, and internal analyses jointly inform opportunity evaluation
- Identify which type of evidence most strongly changed a managerial decision
- Reflect on why Opportunity Analysis should precede the commitment of significant resources

---
## Key Features

**Four differentiated innovation opportunities** — students compare QuickBite Campus, StudyAI, CampusBike, and EcoRefill, each with a distinct value proposition, market context, financial structure, and organizational challenge.

**100-point investment portfolio** — students receive 100 investment points that can be concentrated in one opportunity, distributed across several opportunities, or partially reserved. The simulator prevents total investment from exceeding the available resource constraint.

**Intuition-first decision** — the first allocation is made before analytical information is revealed. This creates a behavioral baseline that can later be compared with evidence-based decisions.

**Three sequential analytical rounds** — students move through external analysis, financial analysis, and internal analysis. Each round adds a new layer of evidence to the opportunity evaluation process.

**Investment can be changed in every analytical round** — after each new set of information is revealed, students can freely reallocate their points before confirming the round. This makes the activity explicitly iterative rather than treating the first decision as fixed.

**Comparative opportunity matrix** — information is presented in a table-like matrix with opportunities in rows and analytical dimensions in columns, allowing students to compare alternatives using a common decision structure.

**Cumulative evidence display** — later rounds preserve earlier information, enabling students to assess each opportunity using the complete evidence accumulated up to that point.

**Market-oriented external analysis** — students examine indicators such as market size, expressed demand, willingness to pay, substitutes, competition, adoption barriers, seasonality, and behavioral constraints.

**Embedded financial logic** — the simulator presents prices, variable costs, contribution margins, fixed costs, initial investment, and break-even calculations so students can connect market assumptions with economic viability.

**Organizational capability analysis** — students evaluate whether the organization has the capabilities needed to execute the opportunity, including technology, logistics, capital, operations, partnerships, institutional relationships, and domain expertise.

**Round-by-round investment tracking** — the simulator stores the allocation from the intuition, external, financial, and internal rounds and visually displays the evolution of investment for each opportunity.

**Visible decision deltas** — increases, decreases, and unchanged allocations are displayed during the analytical rounds, helping students recognize how new evidence affects their judgment.

**Strategic final decision** — students classify eligible opportunities using four managerial actions: **GO** (continue), **MODIFY** (redesign), **WAIT** (seek more information or delay), or **NO-GO** (do not pursue).

**Positive-investment eligibility rule** — only opportunities with more than 0 investment points after the internal analysis enter the strategic final-decision stage. Opportunities that have been fully divested are automatically excluded.

**Investment evolution visualization** — the final decision stage includes a visual comparison of how many points each opportunity received across the four decision rounds.

**Metacognitive Opportunity Analysis route** — students reconstruct the sequence **Idea → External Analysis → Financial Analysis → Internal Analysis → Decision** and connect it to the conceptual relationship between market attractiveness, economic viability, and organizational fit.

**Decision-change reflection** — students identify whether market evidence, financial evidence, or organizational capabilities most strongly changed their perception of each opportunity.

**Initial-versus-final comparison** — the simulator compares the intuition-stage allocation with the final analytical allocation and displays the direction and magnitude of each change.

**Class-transition question** — the activity ends on a separate page with the question: *“¿Cuándo una idea atractiva se convierte realmente en una oportunidad en la que vale la pena invertir?”* This provides a direct bridge from the ludic activity to the subsequent class discussion.

**Progress persistence** — activity state is stored locally in the browser using `localStorage`, allowing the simulation to restore progress after a page refresh in the same browser environment.

**Reset functionality** — students or instructors can restart the activity and clear stored progress through the built-in reset control.

**Accessibility-oriented interface elements** — the HTML includes keyboard-focus states, ARIA labels, live announcements, reduced-motion support, and a skip-to-content link.

---
## Technical Details

| Attribute              | Detail                                                        |
| ---------------------- | ------------------------------------------------------------- |
| Format                 | Single `.html` file                                           |
| Backend required       | None                                                          |
| JavaScript libraries   | None                                                          |
| Main technologies      | HTML, CSS, JavaScript                                         |
| Core decision model    | Sequential Opportunity Analysis                               |
| Investment resource    | 100 points                                                    |
| Investment increment   | 5 points                                                      |
| Opportunities          | 4                                                             |
| Analytical rounds      | Intuition, external, financial, internal                      |
| Final strategic actions| GO, MODIFY, WAIT, NO-GO                                      |
| Financial logic        | Contribution margin, fixed costs, initial investment, break-even |
| Storage                | Browser `localStorage`                                        |
| External assets        | Institutional logo image; core simulation has no library dependency |
| Browser support        | Modern browsers such as Chrome, Firefox, Safari, and Edge     |
| Screen                 | Desktop optimized; comparison matrix supports horizontal scrolling on smaller screens |
| Language               | Spanish                                                       |
| Estimated duration     | 20–30 minutes   |
| Course context         | Opportunity Analysis / Viabilidad de la Innovación            |
| Instructor attribution | Julián Díaz Tautiva, PhD                                      |

---
## Suggested Citation

Díaz Tautiva, J. A. (2026). *Decision Venture 3 — Opportunity Analysis simulator* [Interactive teaching simulator].
