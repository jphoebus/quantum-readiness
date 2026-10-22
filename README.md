# Are State Rules Ready for Quantum Computing? A Five-State Check

Whether the rules Pennsylvania, Virginia, Ohio, Maryland, and Georgia wrote for data centers would apply to quantum computing facilities: tax exemptions, large-load tariffs, reporting, each state's quantum strategy, and how ready each state's own systems are for post-quantum encryption. Current as of October 22, 2026.

**Interactive version:** [jphoebus.github.io/quantum-readiness](https://jphoebus.github.io/quantum-readiness/)

**All projects:** [jphoebus.github.io](https://jphoebus.github.io/)

## Why this comparison

The other comparisons in this series look at decisions states have already made about data centers: what they give, what counts, who pays, whether they check, and what changed in 2026. This one looks ahead. States wrote their data center rules before AI changed the scale of the industry, and costs and definitions struggled to keep up. Quantum computing is early enough that states can decide deliberately how it fits, before the first large facilities arrive.

## Federal timeline and the states

**What the federal orders require.** [Executive Order 14412](https://www.govinfo.gov/content/pkg/FR-2026-06-25/pdf/2026-12909.pdf) (June 22, 2026) requires federal agencies to move their most sensitive systems to post-quantum cryptography for key establishment by December 31, 2030, and for digital signatures by December 31, 2031. It directs the FAR Council to propose a rule holding covered federal contractors to the same standards by the end of 2030. [Executive Order 14413](https://www.federalregister.gov/documents/2026/06/25/2026-12910/ushering-in-the-next-frontier-of-quantum-innovation), signed the same day, creates a national effort to deliver at least one quantum computer "at a scale intended to initiate the era of quantum-enabled scientific discovery" to a Department of Energy facility, and directs at least three quantum sensor projects to be fielded by September 30, 2028.

**Who they bind.** Federal agencies and, once the rule is final, federal contractors. Neither order binds state governments.

**How states get pulled in anyway.** Neither order mentions state governments, but several existing channels reach them:

- [National Security Memorandum 10](https://www.govinfo.gov/content/pkg/DCPD-202200355/html/DCPD-202200355.htm) (May 4, 2022) directs the Department of Homeland Security, through CISA, to "engage with critical infrastructure and SLTT partners regarding the risks posed by quantum computers" and to report annually on accelerating their migration. Executive Order 14412 did not revoke it.
- Federal data-sharing rules follow NIST's encryption standards. [IRS Publication 1075](https://www.irs.gov/privacy-disclosure/encryption-requirements-of-publication-1075) requires federal tax information to be encrypted with "the latest FIPS 140 validated mechanism," and the FBI's [CJIS Security Policy](https://www.oag.ca.gov/system/files/media/2026-isrs-001.pdf) (version 6.1, June 2026) requires FIPS 140-3 modules. Neither mentions quantum yet; as NIST's validated modules move to post-quantum algorithms, these rules will carry the change to state agencies.
- Executive Order 14412 directs federal agencies to help critical infrastructure owners and operators, and states regulate much of that infrastructure through their utility commissions.
- Major technology companies have set earlier targets: Google and Cloudflare have each [set 2029 goals](https://blog.cloudflare.com/post-quantum-eo-2026/) for their own post-quantum migrations.

**How states compare nationally.** A [Howard Center and Scripps News review](https://www.scrippsnews.com/scripps-news-investigates/q-day-americas-quantum-computing-blindspot/the-coming-q-day-us-states-largely-unprepared-as-quantum-computing-threats-loom) of all 50 states (Sept. 10, 2026) rated four states as actively preparing, including Maryland, and 16 as having taken no action (as reported). New York's [2025 encryption standard](https://its.ny.gov/system/files/documents/2025/06/nys-s14-007-encryption.pdf) requires state entities to inventory their cryptographic systems within one year. The State and Local Cybersecurity Grant Program, the main federal cybersecurity grant for states, [lapsed on Sept. 30, 2026](https://www.fdd.org/analysis/federal-grant-programs-third-lapse-endangers-state-cybersecurity/) (as reported) and has never named post-quantum work as an eligible use.

**The continuity question.** The 2030 and 2031 deadlines fall after the January 2029 inauguration, and a future administration can revise an executive order. Underneath the orders, the Quantum Computing Cybersecurity Preparedness Act, enacted in 2022, requires federal agencies to inventory their cryptographic systems, and executive action has built on earlier policy rather than replacing it: Executive Order 14412 moved an earlier 2035 target up to 2030. The open question is whether the accelerated dates hold, and whether states set timelines of their own.

## What stands out

- **Quantum is not in any state's data center law.** All five exemptions define covered equipment in terms of classical computing. None mentions quantum, and no state agency has ruled on whether a quantum processor counts as computer equipment.
- **The equipment could fit; the facilities mostly would not.** Cooling and equipment language in every state is broad enough to plausibly reach cryogenic systems. The barrier is the facility test: what counts as a data center, and investment floors of $75 million to $250 million in four states. Maryland's $2 million to $5 million floor is the exception.
- **Power rules do not reach today's quantum systems.** A superconducting quantum computer draws roughly 15 to 30 kilowatts, about one-thousandth of a 25 MW large-load threshold and about one-four-hundredth of Pennsylvania's 10 MW reporting trigger. Future utility-scale quantum campuses, and quantum systems inside large AI and supercomputing campuses, could change that.
- **State support runs through budgets, not tax law.** Maryland's appropriations, Ohio's $7 million institute, and Virginia's regional grant fund quantum directly. Unlike open-ended exemptions, budget lines come up for decision every cycle, which makes them easier to evaluate.
- **State systems are at different starting points.** Maryland's February 2026 standard is the only one among the five that names post-quantum encryption in a state IT requirement, as a preference rather than a deadline. Georgia has a long-term goal, Virginia has 2019 guidance, and Pennsylvania and Ohio are at the hearing or study stage. None of the five requires a cryptographic inventory or sets a migration date.

## What to watch

- December 2026: Pennsylvania's review of its state Encryption Policy.
- Dec. 31, 2026: Report due from Ohio's proposed Frontier Technologies and Quantum Commission, if HB 650 passes the Senate.
- About March 19, 2027: CISA and NIST guidance on minimum elements for a cryptographic bill of materials, due under Executive Order 14412.
- Whether any state revenue agency rules on quantum equipment under its data center exemption.
- Maryland's FY2028 budget and construction of IonQ's College Park headquarters.
- Whether Pennsylvania legislation follows the House committee's August 2026 quantum hearing.
- Reauthorization of the National Quantum Initiative (S. 3597), introduced January 8, 2026, which is pending in Congress.
- The FAR Council's proposed rule holding federal contractors to post-quantum standards by the end of 2030.
- Whether any of the five states sets its own post-quantum timeline for state systems.
- Hybrid facilities: whether quantum systems placed inside AI data centers fall under those campuses' tariffs and reporting rules.

The question I expect to shape the next round: whether states clarify how quantum fits rules written for server farms before the first large quantum facilities arrive, rather than after.

## About the data

The full comparison is in [quantum-readiness.csv](quantum-readiness.csv), with one row per state and 23 columns covering quantum strategy, confirmed state funding, key institutions, data center tax law and equipment language, facility qualification, large-load tariffs, facility reporting, quantum-specific incentives, and how ready state systems are for post-quantum encryption (IT standards, cryptographic inventories, strategies, legislation, procurement terms, encryption validation standards, utility regulators, and public discussion). Each row lists its sources. "Plausibly covered" means the statute's language could reasonably reach cryogenic systems; no state agency has ruled on the question. Power comparisons rely on published measurements of superconducting systems ([Arute et al.](https://arxiv.org/pdf/1910.11333); [Villalonga et al.](https://arxiv.org/pdf/1905.00444); [2025 case study](https://arxiv.org/pdf/2509.12949)). This comparison is for policy analysis and is not legal, tax, or technical advice.

## Related projects

- [What states changed on data centers in 2026](https://jphoebus.github.io/data-center-legislation-2026/)
- [State data center incentives, compared](https://jphoebus.github.io/state-incentive-comparison/)
- [What counts as exempt data center equipment](https://jphoebus.github.io/data-center-exempt-equipment/)
- [How states check their tax incentives](https://jphoebus.github.io/tax-incentive-evaluation/)
- [DOE's SPARK grid selections, tracked](https://jphoebus.github.io/spark-grid-tracker/)
- [Who pays for data center power](https://jphoebus.github.io/large-load-tariffs/)
- [Which data center load counts](https://jphoebus.github.io/large-load-screening/)

## About me

I'm Joshua Phoebus. I spent seven and a half years in Pennsylvania state government, including four years as Director of Performance and Transformation in the Office of Governor Tom Wolf, where I led the Commonwealth's performance-based budgeting engagement across twenty-nine executive agencies and guided agencies on compliance with the tax credit reviews required under Act 48.

- LinkedIn: [linkedin.com/in/joshuaphoebus](https://www.linkedin.com/in/joshuaphoebus)
- Website: [joshuaphoebusllc.com](https://www.joshuaphoebusllc.com)
