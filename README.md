<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/masthead-dark.svg">
  <img src="assets/masthead-light.svg" alt="Anklesh Rawat. Investment research and strategy, built as running code." width="100%">
</picture>

I work on investment research and strategy: equity valuation, bank economics, M&A and LBO screens, market-entry cases and policy questions, mostly on India.

Each case ships as a repo with a Python pipeline, tests, a public site, and a GitHub Action that refreshes the numbers from public sources. Every figure traces back to a filing, a regulator or an open dataset.

### Questions I've worked on

| Question | What the data said | Built with |
| :-- | :-- | :-- |
| [Can HDFC Bank get back to a 2% RoA by FY29?](https://site-two-eta-4o267upa77.vercel.app) | Yes, but only with six levers, and the share price already assumes it | `Python` `DuckDB` `Svelte` `Excel` |
| [Who captures the value in UPI when merchant payments are priced at zero?](https://india-fs-pulse.vercel.app) | Merchant payments are 63.9% of transactions but 23% of value | `Python` `pandas` `Astro` |
| [How much of India's announced data-centre capacity is switched on?](https://datacenter-capacity-audit.vercel.app) | About 619 MW of the 10.6 GW announced, across 8 operators | `Python` `Next.js` |
| [Where should Indian carriers fly their next 100 long-haul aircraft?](https://india-widebody-window.vercel.app) | Europe first, North America second. The recommendation reversed midway, and the case records why | `Python` `Next.js` |
| [What is each stock's price already assuming?](https://sellside-research-engine.vercel.app) | Reverse DCF, comps and factor ranks on 21 US names, refreshed every weekday | `Python` `Plotly` |
| [Which NSE mid-caps have room for a leveraged take-private?](https://india-lbo-take-pv-screener.vercel.app) | A screen plus a paper LBO on each candidate, under RBI's February 2026 acquisition-finance rules | `Python` `Next.js` |

### Results that came back no

1. **[Signals Before Storms](https://github.com/DogInfantry/Signals-Before-Storms).** A Hidden Markov regime model, graded on 1,814 out-of-sample days. It found the regimes; the strategy built on it did not beat a 60/40. The diagnosis and a retraction are published.
2. **[ENSO Macro Risk Desk](https://github.com/DogInfantry/El_Nino).** Seven El Niño to commodity-price links, each run through Granger, convergent cross mapping and a surrogate null. None survives.
3. **[merger-lab](https://github.com/DogInfantry/merger-lab).** An accretion/dilution engine for Indian M&A. Two of its three sample deals come back DECLINE.

### Writing

- [Regulating the Retail Options Boom](https://papers.ssrn.com/abstract=7135161). SSRN working paper on SEBI's 2024–25 index-derivatives curbs and what they did to retail participation.
- [Awareness Without Uptake](https://papers.ssrn.com/abstract=7239538). SSRN working paper on why rural households who know about a benefit still do not receive it.
- [Bharti Airtel: initiation of coverage](https://portfolio-five-rouge-90.vercel.app/research/bharti-airtel-initiation). Sum-of-the-parts valuation, HOLD, with the event that would change the rating set out in advance.

### Toolkit

**Analysis** &nbsp; DCF and reverse DCF, LBO, comparables, bank P&L, market sizing, difference-in-differences, Granger and CCM<br>
**Build** &nbsp; `Python` `pandas` `DuckDB` `SQL` `TypeScript` `Next.js` `Svelte` `Astro`<br>
**Ship** &nbsp; `GitHub Actions` `pytest` `Vercel` `Hugging Face Spaces` `Docker`

The most-starred thing here is not a finance model: [a Claude skill](https://github.com/DogInfantry/claude-skill-management-consultant-B1) that gives an LLM a consultant's structure (hypothesis first, MECE, pyramid principle) for working through business problems.

### Recently pushed

<!-- recent:start -->
- [Bank-Profitability](https://github.com/DogInfantry/Bank-Profitability) · HDFC Bank: the path back to 2% RoA · <sub>2026-11-04</sub>
- [Signals-Before-Storms](https://github.com/DogInfantry/Signals-Before-Storms) · I built a Hidden Markov Model to find market regimes and allocate on them · <sub>2026-11-04</sub>
- [sellside-research-engine](https://github.com/DogInfantry/sellside-research-engine) · Equity research dashboard and Python pipeline: DCF, reverse DCF, comps, factor screening and risk… · <sub>2026-11-04</sub>
- [portfolio](https://github.com/DogInfantry/portfolio) · Portfolio - Strategy, Investment Research & Quantitative Tools · <sub>2026-11-02</sub>
- [El_Nino](https://github.com/DogInfantry/El_Nino) · ENSO Macro Risk Desk - A Bloomberg-style terminal mapping El Niño/La Niña to commodity & sector… · <sub>2026-10-06</sub>
<!-- recent:end -->

---

<sub>[Portfolio](https://portfolio-five-rouge-90.vercel.app) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/anklesh-rawat-00508a1aa/) &nbsp;·&nbsp; [SSRN](https://papers.ssrn.com/abstract=7135161) &nbsp;·&nbsp; [ORCID](https://orcid.org/0009-0001-2399-8032) &nbsp;·&nbsp; [anklesh.r@merinth.in](mailto:anklesh.r@merinth.in)</sub>
