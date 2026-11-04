# Variance at the Seams of Emergency Care: interactive simulator

The interactive simulator for the research paper *Variance at the Seams of Emergency Care: A Stochastic Model of Delay Propagation Across the Interfaces of a Time-Critical Pathway, with Application to Severe Paracetamol Poisoning* (Maisie Mary Cu, Berlin School of Economics and Law).

It is applied science research using operational research and simulation. It models how delay at the handovers between teams (the *seams*) decides whether patients with a paracetamol overdose start the antidote within the 8-hour window, and tests what would reduce missed windows.

**Author and maintainer:** Maisie Mary Cu, Berlin School of Economics and Law ([ORCID 0009-0001-4684-1599](https://orcid.org/0009-0001-4684-1599))

**Live version:** https://maisiecu-web.github.io/variance-at-the-seams (or open `index.html` in any browser).

This is an open-source simulator: anyone can use, copy, change and share it, with credit to the paper.

## How it is organised

Seven groups, in the order you would read a study:

1. **Start**: results first (key findings, results dashboard, what it means for patients)
2. **The study**: the paper, research design, methodology, maths in everyday words
3. **The simulation**: live Monte Carlo (patients moving through the seams), process map, model, arrival and liver clock, pathway
4. **Where delay comes from**: operations, bottleneck analysis, time of day, infusion and handovers, coupling, rural routes
5. **What to do**: scenario lab, decisions at each pause, emergency plan, Six Sigma, risk management, hospital design
6. **Is it right?**: uncertainty (PSA), validation, power, calibrated significance, governance
7. **Reference**: code and equations, glossary

## What it contains

- **Seam model and Monte Carlo simulation**: up to 20 million simulated patients, with confidence intervals.
- **Maths in everyday words**: every idea (variance, covariance, power, queues…) explained with everyday examples.
- **The paper**: the full text, with every section linked to the part of the simulator where it can be run.
- **Research design**: research question, hypotheses H1–H5 tested live, evidence readiness and a field-study protocol.
- **Process maps**: swimlanes, the local emergency route and interactive step cards.
- **Operations and bottleneck analysis**: work against waiting, Little's law, the marginal value of capacity and the theory of constraints.
- **Decisions**: an emergency plan by patient state, decision rules at each pause, and a scenario lab.
- **Six Sigma (DMAIC)**: DPMO, sigma level, Ppk, Pareto analysis, and p- and X̄ control charts.
- **Risk management (FMEA)**: risk matrix, risk register and controls.
- **Calibrated significance**: thresholds chosen by expected loss, from *Testing the Test* by the same author.
- **Places and buildings**: 29 hospitals on every continent, city traffic, rural routes, patient pushing and energy.
- **Code and equations board**: every equation explained in simple terms, with JavaScript and Python code.
- **Methodology**: the method in six plain steps, a defence of every equation, where every number comes from, assumptions and the STRESS checklist.
- **Live self-checks**: ten tests the model runs on itself in the browser, including reproducing the paper's base case.
- **Glossary**: about 120 terms in plain language, grouped by where you would see them, each linked to the research behind it. Terms in the paper are clickable.
- **Governance**: what it is good for, how changes get in, a settings fingerprint, a changelog and a downloadable model card.

## Running it

`index.html` is a single self-contained file. It needs an internet connection only for web fonts and for the Excel and PDF export libraries; everything else runs offline in the browser.

## Notes

All values are illustrative and calibrated to published sources. They are not estimates for any real hospital. The simulator describes how a care system coordinates. It is not clinical guidance and contains no dosing information.

## Contributing

Found something odd? [Open an issue](https://github.com/maisiecu-web/variance-at-the-seams/issues) saying which tab, what you expected, and the settings ID shown on the Governance tab. To suggest a change: fork the repository, edit `index.html`, run the ten checks on the Governance tab, and open a pull request.

## Licence

MIT licence (see `LICENSE`). Please credit the paper when you use the simulator in teaching or research.

## Citation

Paper:

Cu, M. M. (2026). *Variance at the Seams of Emergency Care: A Stochastic Model of Delay Propagation Across the Interfaces of a Time-Critical Pathway, with Application to Severe Paracetamol Poisoning* [Research paper and interactive simulator]. Berlin School of Economics and Law.

Simulator:

Cu, M. M. (2026). *Variance at the Seams of Emergency Care: Interactive simulator* [Computer software]. https://github.com/maisiecu-web/variance-at-the-seams

## Acknowledgements

The model, code and research are by Maisie Mary Cu. Claude (Anthropic), an AI assistant, helped integrate the code into the interactive simulator.
