# Business Idea Auditor

**Don't build it. Audit it first.**

An evidence-driven Agent Skill for stripping hype from viral business ideas, uncovering hidden costs and stress-testing commercial viability before spending money.

For solo founders, indie hackers and entrepreneurs who collect business ideas on X, Reddit, Xiaohongshu or elsewhere but want to know whether those ideas actually work.

## What it does

- Reconstructs the real operating workflow and comparable product opportunities.
- Investigates software pricing tiers, regulatory obligations and platform risk.
- Compares documented successes and failures, without inventing evidence.
- Models startup capital, unit economics, working capital and payback scenarios.
- Examines competition, geographic constraints and founder feasibility.
- Designs a 72-hour validation experiment under CNY 500 (or local equivalent).
- Salvages transferable techniques even from rejected ideas.
- Maintains a local, reviewable library of business pitfall hypotheses.

## Quick start

For Claude Code, clone the repository into your personal skills directory:

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/YouanLi/business-idea-auditor.git ~/.claude/skills/business-idea-auditor
```

For other Agent Skills-compatible clients, consult your client's skill installation documentation and place this directory in its supported skills location. The repository uses the [Agent Skills](https://agentskills.io/) file layout; individual client compatibility has not been tested.

For ChatGPT, Claude or other chat interfaces, copy SKILL.md into project instructions or the conversation, and provide references/pitfall-rules.md as an additional reference. File access, browsing, visualization and writeback depend on the host.

Example prompt:

> Use business-idea-auditor to audit this post. Verify the claims, calculate the actual economics, and propose the cheapest test of purchase intent. [Paste post]

English is the repository language; audits default to the user's language.

## Illustrative audit: “AI livestreams make CNY 1 million per month”

The following is a synthetic demonstration of the audit method, not a documented business or claim about real sellers. All numbers are assumptions, not current quotes.

### 1. Reconstruct the business

Source products → create approved livestream content → acquire viewers → convert sales → fulfill orders → handle returns and reconcile payouts.

Comparable products to investigate: tissues, socks, garbage bags, screen protectors and local service vouchers. Their suitability depends on contribution margin, customer trust, channel rules and fulfillment costs.

### 2. Tool and platform risks

Compare official virtual-presenter offerings, specialist SaaS and basic streaming tools using current vendor quotes. Verify whether the proposed livestream format is permitted by the platform. No reliable account lifespan is assumed.

### 3. Compare business mechanisms

| Illustrative scenario | Advantage or failure mechanism |
| --- | --- |
| Manufacturer selling its own socks | Lower sourcing cost and greater fulfillment control |
| Affiliate seller purchasing traffic | Acquisition cost may exceed commission |
| Local restaurant promoting vouchers | Existing premises and service capacity |
| Apparel seller using unattended automation | Fit questions, returns and trust may increase support costs |

These scenarios are hypotheses, not verified success or failure stories.

### 4. Model the economics

Assume a CNY 19.90 order, CNY 8 product cost, CNY 3 shipping, CNY 1 fees, CNY 1 returns allowance and CNY 5 acquisition cost. Contribution is CNY 1.90 per order before fixed expenses, labor and taxes.

At CNY 3,000 monthly fixed expenses, approximately 1,579 orders are required for operating break-even before labor and taxes. If acquisition cost rises to CNY 7, contribution becomes negative. A CNY 1 million GMV screenshot alone says nothing about profitability.

### 5. Competition and geography

Investigate supplier quotes, local delivery costs, customer density, existing sellers and channel dependency. A supply cluster may offer an advantage, but actual quotes matter more than a city label.

### 6. Verdict and salvage

**INSUFFICIENT EVIDENCE.** Do not commit to software subscriptions or inventory until actual costs, platform permissions and purchase intent are verified.

A possible validation experiment: obtain supplier and fulfillment quotes, check official channel policies, and test a compliant offer with a capped CNY 500 budget after approval. Measure actual purchase intent and contribution, not impressions alone.

Salvage hypothesis: test whether underserved time slots or long-tail search queries offer cheaper acquisition. Do not assume that off-peak traffic is always cheaper or converts equally well.

## Repository structure

```text
business-idea-auditor/
├── SKILL.md
├── references/
│   └── pitfall-rules.md
└── README.md
```

No dedicated server, database or runtime dependency is included. Host AI subscriptions, API usage and research tools may still cost money. The skill is an instruction protocol, not an autonomous application or a guarantee of financial outcomes.

## Contributing

Pull requests are welcome. Submit reproducible findings with primary evidence, dates, geography, counterexamples and limitations. Keep confidential business information out of public contributions. Proposed rules remain candidates until independently corroborated.

## License

See the repository license if provided. Until a license is selected, public visibility alone does not grant unrestricted reuse rights.
