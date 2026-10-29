# Michal Kaszubski

AI/ML engineer and founder, London. MSc AI and Medical Imaging at UCL, BSc Computer Science at City, University of London.

I investigate how models fail, build production AI systems and create products that people actually use.

**[kaszub.ski](https://kaszub.ski)** · [LinkedIn](https://www.linkedin.com/in/m1k) · [CV](https://kaszub.ski/cv)

## Selected work

| | What it is | Evidence |
|---|---|---|
| [MIQA](https://kaszub.ski/work/miqa) · [code](https://github.com/Cashubski/miqa-prostate-dwi) | MSc thesis: automated detection of geometric distortion in prostate diffusion-weighted MRI, and whether a model can tell when its own judgement is unreliable. PyTorch, patient-level cross-validation, deep ensembles, selective prediction. | 1,027 acquisitions from 627 patients; three-seed DenseNet-121 ensemble at mean AUROC 0.82 across five folds; a heterogeneous ensemble that recovers usable uncertainty, distilled to one model at a ninth of the inference cost. |
| [AI Zuzi](https://kaszub.ski/work/aizuzi) | AI social-media management and content platform, engineered for a client through NeuralTake. Django, React, PostgreSQL; seven third-party publishing integrations, payments, MFA. | About 50 business users. Security audit, encryption at rest, GDPR-aligned deletion and a zero-data-loss live migration from SQLite to PostgreSQL. |
| [NeuralKite](https://kaszub.ski/work/neuralkite) · [live](https://neuralkite.com) | Acquisition-target intelligence for fragmented UK private markets. Next.js, TypeScript, Prisma, PostgreSQL, Claude agents. | An email discovery and verification engine that grades every address into a risk tier with a written rationale, streamed live over SSE. |
| [ChefBot](https://kaszub.ski/work/chefbot) | A cooking assistant for ChatGPT, a [plugin](https://chefbot.neuraltake.com) (formerly a GPT): photo of the fridge to recipe, 18 skills and 7 tested scripts for scaling, shopping lists, schedules, nutrition and baking formulas; [source](https://github.com/Cashubski/chefbot). | 25,000+ conversations and a 4.7 rating from 100+ ratings as a GPT. |

Closed: an entry in the [RSNA Knee Abnormality Detection](https://kaszub.ski/work/rsna-kaggle) challenge on Kaggle (1,849th of 6,425; the post-mortem is on the page). Experiments in generative media and audience analytics are under [kaszub.ski/experiments](https://kaszub.ski/experiments).

## Open source

Fixes merged into quantitative-finance libraries, each found by testing the library against itself (Greeks against finite differences, parities, closed forms against Monte Carlo, one engine against another). Notes on each are on [kaszub.ski/open-source](https://kaszub.ski/open-source).

| Library | Merged | What |
|---|---|---|
| [FinancePy](https://github.com/domokane/FinancePy) | 16 | US Treasury yield convention, CDS premium leg and index spread adjustment, FRA sign, floating-rate note pricing, SABR volatility formula, swaption vol surface, American option pricer at zero dividend, date-schedule generation, forward-start option, Monte Carlo wrappers, equity and FX variance swaps, FX double digital and rainbow options, FX error paths |
| [vectorbt](https://github.com/polakowo/vectorbt) | 2 | Deflated Sharpe ratio (kurtosis convention and missing data), Numba/Rust engine parity |
| [skfolio](https://github.com/skfolio/skfolio) | 4 (+2 in review) | Online Schur allocation (credited in source); regime-adjusted covariance bias fix; information criteria for fixed-parameter marginals; walk-forward calendar offsets; Student-t copula CDF finding fixed upstream by the maintainer; parametric portfolio policies (Brandt, Santa-Clara and Valkanov 2009) and rolling-window factor exposures in review |

## Experience

- **NeuralTake Limited**, Managing Director and AI Engineer, October 2024 to present. AI consultancy for professional services firms: workflow audits and fixed-fee automation builds delivered into the client's own stack.
- **WorldQuant Brain**, Quantitative Research Consultant, October 2023 to October 2024. Researched and backtested systematic trading signals in Python: risk-adjusted performance, turnover, decay and robustness.

## Working in

Python, PyTorch, scikit-learn, pandas, NumPy, NiBabel · Django, PostgreSQL, TypeScript, React, Next.js, REST APIs · GCP, Docker, Playwright, CI/CD · English and Polish, both native.

## Contact

Message me on [LinkedIn](https://www.linkedin.com/in/m1k). CV and references are available on request.



