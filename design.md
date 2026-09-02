# The Rebecca Ledger: A Design for Publicly Owned Corporate Accountability

Working draft — September 2026

Named for Rebecca Sue Smith. A ledger is where you write down what is owed.

## 1. Purpose

Make corruption and exploitative pay structurally unprofitable by combining three things that each work on their own but have never been combined at scale: mutual AI monitoring, randomly selected human oversight, and whistleblower bounties large enough that exposing wrongdoing pays better than participating in it.

The system does not make companies ethical. It makes hiding unethical behavior more expensive than fixing it.

## 2. Core Principles

1. **No single point of trust.** No one entity — company, government, or AI — can see everything, decide everything, or be the only channel.
2. **Everything inspectable.** Code, training data, audit logs, and every enforcement decision are public.
3. **Detection is separate from judgment.** AIs find and publish. Humans decide and penalize.
4. **Incentives run toward exposure.** At every layer, the person who reveals a problem is paid more than the person who hides it.
5. **Rules are set by people, enforced by machines.** The system guarantees compliance, not fairness. Fairness stays a human argument.

## 3. Architecture

### Layer 1 — The Three Monitors

Three independent AI systems, each operated by a different organization, each auditing the other two and every company in scope.

Requirements for the three:
- **Different jurisdictions.** No two based in the same country.
- **Different funding.** No shared investors above a small ownership threshold.
- **Different lineage.** Separate training data, separate teams, separate model architectures where practical, to reduce correlated blind spots.
- **Open monitoring logic.** Each monitor's auditing rules and code are published and reviewable by the other two and by the public.

Each monitor ingests the same public data feeds (Section 4), runs its own analysis, and publishes findings. Disagreement between monitors is itself a published signal.

### Layer 2 — Citizen Cross-Check Panels

Humans selected by lottery, not election, from the general public.

- **Selection:** stratified random sampling across regions, income levels, and occupations. No one who has worked for a monitor, a monitored company above a size threshold, or a government regulator in the prior five years.
- **Term:** 12–18 months, non-renewable. Thousands rotate through every year so that institutional knowledge lives in the public, not in a staff.
- **Compensation:** full salary replacement plus a premium, so service is not a sacrifice and members are harder to buy.
- **Powers:** audit any monitor's findings, demand explanations in plain language, order re-analysis, and escalate to enforcement bodies. Panels cannot be overruled by a monitor.
- **Protection:** identities shielded during service; retaliation is itself a bounty-eligible offense.

### Layer 3 — The Bounty

Anyone — employee, contractor, supplier worker, journalist, or a staffer inside one of the three monitors — who exposes corruption or concealment receives a payout.

- **Size:** 20–40% of the penalty or recovered amount, with a floor high enough that low-level workers are motivated (e.g., minimum one year of the reporter's pay).
- **Funding:** paid from the penalty itself. Costs the public nothing.
- **Tiering:** exposing collusion *among the monitors* or *within a citizen panel* pays the highest tier, because those are the failures that break the whole system.
- **Protection:** legal immunity for good-faith reports, anonymous submission channels through all three monitors simultaneously, and a public fund covering legal costs and lost income.

### Layer 4 — Enforcement

The monitors and panels do not impose penalties. Findings that survive cross-check go to courts or public enforcement bodies in the relevant jurisdiction. This keeps the AI as auditor, not judge, and keeps due process in human hands.

## 4. What Gets Monitored

Data feeds, mandatory for companies above a size threshold (suggested: 1,000 employees or $1B revenue, including their tier-1 and tier-2 suppliers):

- Full payroll by role, level, and location (anonymized individual records, aggregate bands public)
- All executive compensation, including deferred, in-kind, and off-book arrangements
- Supplier contracts and supplier payroll for manufacturing and extraction
- Political and lobbying spend
- Related-party transactions
- Internal complaint and retaliation records

Every person can also submit reports directly — pay stubs, observations, documents — to all three monitors at once. Submissions stay visible in raw form; the AI aggregates but never replaces them.

## 5. The Rules Enforced (Compensation)

the Ledger enforces whatever rules the public sets. The starting proposal, using Apple as the reference case:

| Tier | Rule |
|---|---|
| Floor | Local living wage in every country of operation, including suppliers |
| Retail / support | Living wage plus meaningful equity; full-time available to all who want it |
| Skilled / engineering | Market pay, published bands by level and location |
| Executives | Total compensation capped at 15–20× company median |
| Innovation reward | Inventor and team royalties on specific products, paid to the people who built them, capped per person per breakthrough |
| Profit share | Fixed percentage of net income distributed to all employees |
| Transparency | Pay ratio and bands published annually |

## 6. Worked Example: Apple

| | Today | Under the Ledger |
|---|---|---|
| Retail specialist (all-in) | ~$60–85k | ~$75–95k |
| Median employee | $139k | ~$150k |
| Senior engineer (ICT4) | ~$358k | ~$360k |
| SVP | $27M | ~$2.5–3M |
| CEO | $74.3M | ~$2.5–3M |
| CEO : median ratio | 533 : 1 | ~18 : 1 |
| Supply-chain floor | Legal minimum | Local living wage |
| Direct payroll change | — | +$2–3B / yr |
| Supply-chain cost change | — | +$5–15B / yr |
| Net income (2025) | $112B | ~$95–105B |

The company remains the most profitable on earth. The change is absorbed almost entirely by buybacks (~$90B/yr today).

## 7. Failure Modes and Mitigations

| Failure | Mitigation |
|---|---|
| The three monitors collude | Highest bounty tier for exposing it; jurisdictional and funding separation; citizen panels can order independent re-analysis |
| Correlated AI blind spots | Separate lineages; human panels specifically tasked with challenging unanimous findings |
| Panel capture | Lottery selection, short terms, retaliation bounties, identity shielding |
| Gaming the metrics | Raw submissions stay public; monitors reward pattern detection, not checkbox compliance |
| Public apathy | Mandatory plain-language public dashboards; large rotating panel membership so millions have sat inside the system within a decade |
| Regulatory capture of the rules | Rules amended only by citizen panels with public comment, never by monitors or monitored companies |
| Capital flight to non-participating jurisdictions | Market-access requirement: sell in participating markets, submit to monitoring |

## 8. Rollout

1. **Pilot (years 1–2):** One sector, one region, voluntary participation with tax incentives. Prove the monitors agree, disagree, and get corrected by panels.
2. **Mandate (years 3–5):** All companies above threshold in participating jurisdictions. Bounty program live.
3. **Supply chain (years 5–8):** Extend monitoring to tier-1 and tier-2 suppliers. This is where the largest human impact is.
4. **Global (years 8+):** Market-access rule. Sell here, get monitored here.

## 9. What This System Cannot Do

- It cannot decide what "fair" means. That is a permanent human argument, and the system should surface the argument, not settle it.
- It cannot prevent people from agreeing on bad rules. It can only guarantee that whatever rules exist are actually followed.
- It cannot replace courts, unions, journalism, or elections. It feeds them.
