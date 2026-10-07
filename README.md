# Are State Rules Ready for Quantum Computing? A Five-State Check

Whether the rules Pennsylvania, Virginia, Ohio, Maryland, and Georgia wrote for data centers would apply to quantum computing facilities: tax exemptions, large-load tariffs, reporting, and each state's quantum strategy. Current as of October 2026.

**Interactive version:** [jphoebus.github.io/quantum-readiness](https://jphoebus.github.io/quantum-readiness/)

## Why this comparison

The other comparisons in this series look at decisions states have already made about data centers: what they give, what counts, who pays, whether they check, and what changed in 2026. This one looks ahead. States wrote their data center rules before AI changed the scale of the industry, and costs and definitions struggled to keep up. Quantum computing is early enough that states can decide deliberately how it fits, before the first large facilities arrive.

## Federal timeline and the states

**What the federal orders require.** [Executive Order 14412](https://www.govinfo.gov/content/pkg/FR-2026-06-25/pdf/2026-12909.pdf) (June 22, 2026) requires federal agencies to move their most sensitive systems to post-quantum cryptography for key establishment by December 31, 2030, and for digital signatures by December 31, 2031. It directs the FAR Council to propose a rule holding covered federal contractors to the same standards by the end of 2030. [Executive Order 14413](https://www.federalregister.gov/documents/2026/06/25/2026-12910/ushering-in-the-next-frontier-of-quantum-innovation), signed the same day, creates a national effort to deliver at least one quantum computer "at a scale intended to initiate the era of quantum-enabled scientific discovery" to a Department of Energy facility, and directs at least three quantum sensor projects to be fielded by September 30, 2028.

**Who they bind.** Federal agencies and, once the rule is final, federal contractors. Neither order binds state governments.

**How states get pulled in anyway.** Executive Order 14412 directs federal agencies to help critical infrastructure owners and operators with their transitions, and states regulate or run much of that infrastructure, including utilities overseen by state commissions. State systems also exchange data with federal agencies every day. And major technology companies have set earlier targets: Google and Cloudflare have each [set 2029 goals](https://blog.cloudflare.com/post-quantum-eo-2026/) for their own post-quantum migrations.

**The continuity question.** The 2030 and 2031 deadlines fall after the January 2029 inauguration, and a future administration can revise an executive order. Underneath the orders, the Quantum Computing Cybersecurity Preparedness Act, enacted in 2022, requires federal agencies to inventory their cryptographic systems, and executive action has built on earlier policy rather than replacing it: Executive Order 14412 moved an earlier 2035 target up to 2030. The open question is whether the accelerated dates hold, and whether states set timelines of their own.

## What stands out

- **Quantum is not in any state's data center law.** All five exemptions define covered equipment in terms of classical computing. None mentions quantum, and no state agency has ruled on whether a quantum processor counts as computer equipment.
- **The equipment could fit; the facilities mostly would not.** Cooling and equipment language in every state is broad enough to plausibly reach cryogenic systems. The barrier is the facility test: what counts as a data center, and investment floors of $75 million to $250 million in four states. Maryland's $2 million to $5 million floor is the exception.
- **Power rules do not reach today's quantum systems.** A superconducting quantum computer draws roughly 15 to 30 kilowatts, about one-thousandth of a 25 MW large-load threshold and about one-four-hundredth of Pennsylvania's 10 MW reporting trigger. Future utility-scale quantum campuses, and quantum systems inside large AI and supercomputing campuses, could change that.
- **State support runs through budgets, not tax law.** Maryland's appropriations, Ohio's $7 million institute, and Virginia's regional grant fund quantum directly. Unlike open-ended exemptions, budget lines come up for decision every cycle, which makes them easier to evaluate.

## What to watch

- Whether any state revenue agency rules on quantum equipment under its data center exemption.
- Maryland's FY2028 budget and construction of IonQ's College Park headquarters.
- Whether Pennsylvania legislation follows the House committee's August 2026 quantum hearing.
- Reauthorization of the National Quantum Initiative (S. 3597), introduced January 8, 2026, which is pending in Congress.
- The FAR Council's proposed rule holding federal contractors to post-quantum standards by the end of 2030.
- Whether any of the five states sets its own post-quantum timeline for state systems.
- Hybrid facilities: whether quantum systems placed inside AI data centers fall under those campuses' tariffs and reporting rules.

The question I expect to shape the next round: whether states clarify how quantum fits rules written for server farms before the first large quantum facilities arrive, rather than after.

## About the data

The full comparison is in [quantum-readiness.csv](quantum-readiness.csv), with one row per state and 16 columns covering quantum strategy, confirmed state funding, key institutions, data center tax law and equipment language, facility qualification, large-load tariffs, facility reporting, quantum-specific incentives, and post-quantum cryptography mandates. Each row lists its sources. "Plausibly covered" means the statute's language could reasonably reach cryogenic systems; no state agency has ruled on the question. Power comparisons rely on published measurements of superconducting systems ([Arute et al.](https://arxiv.org/pdf/1910.11333); [Villalonga et al.](https://arxiv.org/pdf/1905.00444); [2025 case study](https://arxiv.org/pdf/2509.12949)). This comparison is for policy analysis and is not legal, tax, or technical advice.

## Related projects

- [What states changed on data centers in 2026](https://jphoebus.github.io/data-center-legislation-2026/)
- [State data center incentives, compared](https://jphoebus.github.io/state-incentive-comparison/)
- [What counts as exempt data center equipment](https://jphoebus.github.io/data-center-exempt-equipment/)
- [How states check their tax incentives](https://jphoebus.github.io/tax-incentive-evaluation/)
- [DOE's SPARK grid selections, tracked](https://jphoebus.github.io/spark-grid-tracker/)
- [Who pays for data center power](https://jphoebus.github.io/large-load-tariffs/)

## About me

I'm Joshua Phoebus. I spent seven and a half years in Pennsylvania state government, including four years as Director of Performance and Transformation in the Office of Governor Tom Wolf, where I led the Commonwealth's performance-based budgeting engagement across twenty-nine executive agencies and guided agencies on compliance with the tax credit reviews required under Act 48.

- LinkedIn: [linkedin.com/in/joshuaphoebus](https://www.linkedin.com/in/joshuaphoebus)
- Website: [joshuaphoebusllc.com](https://www.joshuaphoebusllc.com)
