# Framework for Proportional AI Responsibility, Resource Governance, and Biosphere Preservation (v2.0)

This framework is maintained as an open, community-driven policy proposal by **[SustainAI.global](https://sustainai.global/)** — a Texas nonprofit (501(c)(3) pending) dedicated to workforce upskilling, ethical AI research, sustainable compute, and human–AI collaboration.

**Canonical repository.** This repo ([SustainAI-Global/ai-policy-proposal](https://github.com/SustainAI-Global/ai-policy-proposal)) is the actively maintained version. It began as work by Jack Camier and is now developed and stewarded through SustainAI Global. An earlier individual draft remains at [jcamier/ai-policy-proposal](https://github.com/jcamier/ai-policy-proposal) for reference; this version is expected to diverge substantially as community input and nonprofit work continue.

The preamble below sets out philosophical intent; the operational sections that follow are meant to be refined through public consultation, sandboxes, and stakeholder feedback. The project is released under the [MIT License](LICENSE).

## Preamble and Legislative Intent

### Purpose and Scope
This framework establishes proportional, tier-scaled governance for AI development and deployment. Its purpose is threefold: to safeguard individuals and collective human communities from harm arising from AI systems; to preserve a legal safe harbor for researchers, startups, nonprofit organizations, and universities and colleges engaged in good-faith creation, publication, and experimentation; and to require practicable recording of computational resource consumption—including energy source, energy units, and water use where data exists—for entities of sufficient scale to employ dedicated personnel for that function. Regulatory obligations rise with an entity's resource tier: a large nonprofit with substantial revenue bears greater liability and compliance duties than a small startup with limited resources, regardless of mission or tax status. At the same time, certain absolute safety prohibitions apply at every tier—no entity, however small, may develop or deploy AI for universally prohibited purposes, including biological, chemical, radiological, or nuclear weaponization support.

AI systems, algorithms, and models cannot be held legally accountable. Liability rests exclusively with humans, companies, governments, and other organizations—the people and institutions that choose to build, deploy, and monitor these tools—so that human judgment and oversight remain essential no matter how capable the technology becomes. Environmental reporting is designed as a transparency mechanism intended to encourage deliberate resource stewardship rather than impose uniform audit burdens on organizations lacking the capacity to comply.

### The North Star: Human Dignity and Biosphere Care
Technology must serve as a force multiplier for human flourishing and planetary stewardship. AI systems must function as auxiliary tools that augment human capabilities rather than mechanisms that substitute for human dignity, erode fundamental civil liberties, or deplete natural resources. 

Furthermore, this policy explicitly recognizes the preservation of the **Biosphere**—the delicate, closed global ecosystem of humans, animals, plants, and supporting environments—as a paramount duty. The biosphere is humanity’s shared lifecycle, a fragile vessel sustaining our current existence and serving as the foundational launchpad for long-term multi-planetary and interstellar horizons. Algorithmic deployments must be audited for environmental sustainability, and their regulatory burdens must be allocated equitably to ensure that environmental and societal protections do not stifle localized, public-good innovations.

---

## I. Core Axioms and Definitions

### 1.1 The Principle of Algorithmic Non-Agency
Artificial Intelligence systems, source code, neural network weights, and foundational mathematical models do not possess legal personhood, moral agency, or intrinsic liability. An algorithm cannot hold intent, experience culpability, or satisfy financial judgments. Consequently, legal accountability cannot be transferred, delegated, or imputed to an automated system. Moral and legal responsibility rests strictly, exclusively, and immutably with the legal persons—specifically humans, corporate entities, or government organs—that choose to operationalize and deploy these tools.

### 1.2 Definitional Boundaries
* **Upstream Creator / Contributor:** Any individual, volunteer network, academic researcher, or organization that writes, trains, maintains, publishes, or distributes software source code, foundational model architectures, weights, or documentation under an open-source or public license without directly operationalizing it into a commercial or public-facing endpoint.
* **Downstream Deployer:** Any individual, commercial enterprise, or institutional entity that embeds an AI system into an active operational workflow, exposes its interfaces to end-users, uses its computational outputs to automate consequential decisions, or derives direct commercial monetization from its live execution.
* **Systemic Failure:** A severe, widespread, or structurally embedded breakdown in an AI system's performance that results in significant material harm, systemic discrimination, physical endangerment, or environmental damage. This is distinct from routine software "bugs" or standard edge-case errors inherent to all software engineering.

---

## II. The Proportional Resource Governance Matrix

Traditional regulatory frameworks frequently cause market stagnation by imposing uniform, checklist-heavy compliance mandates that small organizations lack the resources to fulfill. This framework neutralizes that risk by shifting from a purely use-case-driven risk architecture to an **Entity-Based Resource Tiering Model**. 

While high-risk application areas (e.g., healthcare diagnostics, critical infrastructure, credit/employment scoring) require heightened awareness, the administrative burden, auditing obligations, and financial liabilities are scaled strictly by the deploying entity's financial capacity and paid workforce size.

```
+-------------------------------------------------------------------------+
|                      UNIVERSAL HIGH-RISK RED LINES                      |
|  Strict global prohibitions on extreme existential/human rights threats  |
+-------------------------------------------------------------------------+
                                     |
         +---------------------------+---------------------------+
         |                           |                           |
         v                           v                           v
+-----------------+         +-----------------+         +-----------------+
|     TIER 1      |         |     TIER 2      |         |     TIER 3      |
| Micro & Grass   |         |      SMBs       |         | Enterprise/State|
+-----------------+         +-----------------+         +-----------------+
| * Sandbox Space |         | * Scaled Audits |         | * Independent   |
| * Fix-First     |         | * Capped Fines  |         |   Third-Party   |
|   Immunity      |         |   (% of Rev)    |         |   Audits & Red- |
| * No Penalties  |         |                 |         |   Teaming       |
|   for Volunteers|         |                 |         | * Uncapped /    |
|                 |         |                 |         |   Global Fines  |
+-----------------+         +-----------------+         +-----------------+
```

### 2.1 Universal High-Risk Red Lines (Prohibited Capabilities)
Regardless of an entity’s size, resource tier, or operational intent, certain absolute boundaries are universally prohibited. No entity shall develop, deploy, or commercialize AI systems designed for:
1.  **Autonomous Lethal Kinetic Operations:** Weaponized hardware or software systems designed to select and engage human targets with lethal force entirely absent meaningful human-in-command confirmation.
2.  **Untargeted Mass Biometric Surveillance:** Real-time, indiscriminate biometric tracking and predictive policing algorithms deployed in public spaces by non-cooperative state or corporate actors.
3.  **CBRN Weaponization Support:** Software optimization loops or expert systems configured to lower the technical barriers to synthesis, engineering, or deployment of Chemical, Biological, Radiological, or Nuclear weapons.

### 2.2 Tier 1: Micro-Enterprises, Grassroots Initiatives, and Volunteer Non-Profits
* **Target Metrics:** Independent developers, academic labs, bootstrapped early-stage startups, and volunteer-driven non-profit organizations characterized by minimal annual revenue (e.g., under $2,000,000 USD) and relying primarily on unpaid volunteers or a small cohort of paid personnel. **Unpaid volunteers are explicitly excluded from personnel headcounts.**
* **Compliance Posture:** Maximum regulatory latitude. Tier 1 entities are exempt from heavy administrative documentation, independent third-party auditing, and pre-market safety case filings. When operating in higher-impact domains (such as deploying an educational assistant or a community-level ecological tracking tool), compliance is restricted to standard user disclaimers, data privacy compliance, and registration within public regulatory sandboxes.
* **Liability and Penalty Structure:** **"Fix-First" Absolute Immunity.** Tier 1 entities face zero financial penalties for non-willful algorithmic errors or unintended compliance failures. If an asset or system causes harm or breaches standard thresholds, regulatory bodies issue a remediation order. The entity is granted a mandatory grace period to patch, roll back, or deactivate the system without financial duress. Personal liability for founders, maintainers, or volunteers is strictly prohibited absent proven criminal intent or fraudulent concealment.

### 2.3 Tier 2: Small to Medium-Sized Businesses (SMBs)
* **Target Metrics:** Mid-sized commercial operations, well-funded regional corporations, and institutional entities possessing moderate annual revenues and a standard workforce of paid employees.
* **Compliance Posture:** Scalable and standardized compliance. Tier 2 deployers must maintain basic internal risk logs, self-certified safety checklists, clear documentation of training data provenance, and establish direct human-in-command operational overrides. If deploying systems within designated high-impact sectors (e.g., housing, employment, finance), they must maintain a 72-hour incident reporting window to log systemic failures with the appropriate sector regulator.
* **Liability and Penalty Structure:** **Strictly Capped Financial Exposure.** Financial liabilities for Tier 2 entities are statutorily capped at a low, pre-defined percentage of their gross local revenue (e.g., maximum 1-2%). Penalties are mathematically structured to incentivize robust internal engineering discipline, quality assurance, and proactive post-market telemetry, ensuring that an operational error never results in corporate bankruptcy or structural liquidation.

### 2.4 Tier 3: Enterprise Corporations, Tech Giants, and State Organs
* **Target Metrics:** Multinational conglomerates, massive technology platforms, market-dominant corporations, and major government agencies possessing expansive capital assets, vast compute allocations, and substantial paid staff.
* **Compliance Posture:** Comprehensive, independent accountability. Because Tier 3 entities possess the financial runway, physical infrastructure, and human capital required to thoroughly stress-test their operational environments, they bear the full administrative burden of governance. They must conduct mandatory, independent third-party safety audits, publish open verification of adversarial red-teaming, maintain immutable telemetry logs, and demonstrate robust bias-mitigation frameworks prior to wide-scale deployment.
* **Liability and Penalty Structure:** **Uncapped and Systemic Strict Liability.** Tier 3 deployers assume total legal and financial accountability for failures originating from their operational choices. Because they are the primary entities financializing technology at scale, penalties for negligence, willful ignorance of known hazards, or systemic biosphere harms are un-capped or anchored directly to global annual turnover scales. This structure ensures that thorough safety verification remains structurally cheaper than corporate negligence.

---

## III. The Open-Source Shield and Downstream Transfer Mechanics

This framework treats open-source software, public model repositories, and algorithmic research as vital public goods equivalent to basic mathematics, literacy, and open scientific inquiry. 

### 3.1 The "As-Is" Upstream Developer Immunity Clause
All software source code, algorithmic weights, configuration parameters, and architectural frameworks published under open-source licenses (e.g., MIT, Apache 2.0, GPL) are provided strictly **"as-is," without warranty of any kind**, express or implied. 
* **Absolute Safe Harbor:** Upstream creators, maintainers, individual contributors, and repository hosting platforms possess zero legal or moral agency regarding how downstream entities choose to configure, download, fine-tune, or operationalize their files.
* **Litigation Immunity:** Open-source maintainers enjoy absolute civil and criminal immunity from harms, security vulnerabilities, or algorithmic biases manifested by downstream applications of their public code. Publishing open software is recognized as a protected exercise of permissionless innovation, academic speech, and shared human knowledge.

### 3.2 The Operational Trigger for Liability Transfer
Legal accountability is an operational function triggered exclusively by **deployment and monetization, not by codebase creation**. 
* The exact moment a Tier 2 or Tier 3 entity chooses to pull code from an open-source repository and embed it into a commercial workflow, **100% of the legal liability transfers strictly to that deploying entity**.
* **No Backward Deflection:** A commercial deployer cannot deflect blame, pass regulatory fines backward, or initiate civil litigation against upstream open-source authors for system failures, unexpected adversarial jailbreaks, or un-patched vulnerabilities. The deployer chooses to integrate the tool; the deployer bears the exclusive burden of vetting its safety to the extent of their resource tier.

### 3.3 The Standardized "Known Hazard" Protocol
To maintain the safety of the ecosystem without compromising open-source safe harbors, a structured, neutral notification mechanism is established:
1.  **Vulnerability Reporting:** If a critical, reproducible exploit or high-risk capability flag is discovered within an open-source codebase, it must be reported through a decentralized vulnerability registry or public security portal.
2.  **No Retroactive Liability:** The upstream maintainer is under no legal obligation to fix the code, write a patch, or perform administrative labor, as the software remains public property.
3.  **The Safe Harbor Exception:** An open-source contributor only faces liability if they *actively maintain a commercialized, closed-source fork* of that exact tool for their own Tier 2/3 profit, receive a formal, verified hazard notification, and intentionally ignore the risk vector while continuing to profit from its exposure to end-users.

---

## IV. Enforcement, Redress, and Community Impact

### 4.1 Local Ombuds and Citizen Redress Mechanisms
To ensure that citizens, workers, and localized populations have immediate paths to remedy when impacted by algorithmic automated decisions, an independent network of **Local Ombuds** offices shall be maintained. These neutral offices sit entirely outside corporate structures and provide a zero-cost interface for public grievances.
* **The Right to Explanation:** Any individual subjected to a significant automated decision by a Tier 2 or Tier 3 system (e.g., denial of credit, healthcare access, housing, or employment termination) possesses an enforceable right to a clear, plain-language explanation of the system's logic and data inputs.
* **Redress Execution:** If an investigation reveals systematic bias or algorithmic malfunction, the Ombuds holds the authority to mandate corporate rollback, file for immediate data correction, and oversee appropriate financial compensation or alternative remedies provided by the responsible deployer.

### 4.2 Workforce Transition and Upskilling Mandates
Technological shifts must not isolate working communities. To align market-driven automation with broad-based human flourishing, human capital transition strategies are required—funded strictly by the entities with the scale to support them.
* **The Tier 3 Upskilling Set-Aside:** Tier 3 Enterprise corporations executing large-scale automation frameworks that directly displace human operational workflows must allocate a standardized percentage of that specific deployment's budget (or utilize an equivalent tax-credit matching structure) to fund localized upskilling, trade education, and career transition programs for impacted workers.
* **Tier 1 and Tier 2 Exemptions:** To protect early-stage runways, preserve small business viability, and prevent market consolidation, Tier 1 grassroots initiatives and Tier 2 small businesses are entirely exempt from external upskilling taxations or workforce transition set-asides.

---

## V. Evolution and Bottom-Up Maturation

### 5.1 Regulatory Sandboxes and Experimental Safe Spaces
To ensure policy definitions evolve alongside rapid scientific advancements, state and regional oversight committees shall maintain live, low-barrier **Regulatory Sandboxes**. These sandboxes permit Tier 1 and Tier 2 entities to experiment with boundary-pushing frontier models or high-impact use cases under a temporary, time-boxed legal shield. Shared telemetry, localized incident tracking, and open feedback loops from these sandboxes will inform future iterations of the framework.

### 5.2 Mandatory Sunset Clauses
Every administrative rule, technical metric, and compliance standard enacted under this framework carries an automatic **24-month sunset clause**. Regulatory bodies must actively re-justify, modernize, and re-ratify constraints every two years based on real-world market outcomes, grassroots developer feedback, and updated biosphere impact metrics. This prevents stale, legacy legislation from hardening into a tool for market capture or artificial consolidation.

---

## VI. Open Questions (Community-Driven)

The sections above state direction and principle. Many implementation details are **deliberately left open** so this framework can mature through community input — researchers, open-source maintainers, small nonprofits, policymakers, workers, and large deployers alike.

If you have views on any of the questions below, please [open an issue](https://github.com/SustainAI-Global/ai-policy-proposal/issues), start a discussion, or submit a pull request. There are no wrong answers at this stage; the goal is to surface trade-offs before anything becomes rigid law.

### Tier boundaries and classification
- **Tier 2 thresholds:** Tier 1 cites an example revenue ceiling (~$2M USD). What revenue band and paid-headcount range should define Tier 2 — and where does Tier 2 end and Tier 3 begin?
- **Who certifies tier status?** Self-declaration, annual filing, third-party attestation, or a hybrid?
- **Crossing thresholds:** What happens when an organization grows mid-year (e.g., raises funding, hires staff, or crosses a revenue band)? Grace period, prospective-only application, or retroactive reclassification?

### Red lines and dual-use research
- **CBRN carve-outs:** How should the framework distinguish weaponization support from legitimate academic, defensive, or public-health research — and who decides?
- **Surveillance boundaries:** Where is the line between prohibited untargeted mass biometric surveillance and consent-based, warrant-backed, or narrowly scoped uses?

### Open-source edge cases
- **Public demos and endpoints:** When a Tier 1 maintainer runs a free public demo or inference endpoint, are they still upstream — or do they become a deployer?
- **Hosting platforms:** Repositories and model hubs that host weights but do not operate live inference — always upstream safe harbor?
- **Abandoned projects:** If a maintainer receives a verified hazard notice but cannot patch (no contributors, archived repo), does full immunity still apply unless a commercial fork exception applies?

### Enforcement and governance
- **Local Ombuds:** How are offices funded, staffed, and made independent of corporate and political capture? Do their orders bind multinationals across jurisdictions?
- **Government as deployer:** State organs are listed as Tier 3 — same liability structure, or sovereign-immunity exceptions with alternative accountability?
- **Penalty structure:** For Tier 3 “uncapped” liability, should there be per-incident caps, annual caps, or truly unlimited exposure for willful systemic harm?

### Workforce and community impact
- **Upskilling set-aside:** What percentage of a Tier 3 deployment budget (or tax-credit equivalent) is appropriate?
- **Defining displacement:** How do we distinguish direct automation-driven displacement from normal attrition, market shifts, or unrelated layoffs?

### Biosphere and compute
- **Environmental obligations:** The preamble treats biosphere preservation as paramount. Should Tier 2 and Tier 3 carry explicit compute-energy reporting, renewable-use targets, or environmental impact assessments — and at what scale?

### International application
- **Cross-border deployers:** When a Tier 3 multinational deploys in multiple countries, which jurisdiction’s tier rules, Ombuds, and penalties apply — incorporation country, user country, or harm location?

These questions do not weaken the framework; they mark where **community wisdom** is needed next. [SustainAI.global](https://sustainai.global/) exists to work on these ideas in practice — through education, research, and open collaboration — and this repository is one place to help shape them in policy.

---

## Contributing

This policy is a living document, and it only gets better through collaboration. You do not need to be an AI expert or policy maker to participate — every perspective adds value.

### Ways to Contribute
- **Open an Issue**: Share your thoughts, questions, or concerns in plain language. No technical background required.
- **Submit a Pull Request**: Suggest edits or new sections. If you’re new to GitHub, don’t worry — we can help guide you.
- **Join Discussions**: Use the Discussions tab to brainstorm, debate, and refine ideas together.
- **Spread the Word**: Share this project with others who care about building a better future with AI.

### A Note on Contributions
There are no “wrong” contributions. Drafts, rough ideas, questions, or even one-sentence suggestions are all welcome. The goal is to capture diverse voices and refine them into a balanced and pragmatic AI policy.

By contributing (issues, discussions, or pull requests), you agree that your contributions are licensed under the same [MIT License](LICENSE) as the rest of this repository, and may be maintained by SustainAI Global as part of this project.

Your voice matters. Even a small suggestion can make a big difference. Let’s work together to build a sustainable and flourishing future for humanity and the biosphere.
