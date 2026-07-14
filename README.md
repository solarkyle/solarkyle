# Kyle B.

I build products people use and run experiments designed to prove me wrong. Systems builder, researcher, tinkerer; hopelessly curious.

Self-taught. I got into machine learning in 2019 by hand-labeling satellite imagery and training segmentation models for automated residential solar quotes. That start left a lasting habit: distrust claims that have not survived contact with reality.

## Research

**[jspace](https://github.com/solarkyle/jspace)**: same-day replication and extension of Anthropic's Jacobian-lens global-workspace research on open models, grown into a pre-registered cross-domain hallucination-detection campaign. 25k graded Gemma-12B traces, classifiers frozen and hashed before prospective data arrived, honest gate verdicts including a formal miss, and a methodological confound (answer-identity readout) documented so others do not rediscover it the hard way. Artifacts: [lenses + frozen classifiers](https://huggingface.co/solarkyle/jspace-lenses), [24.5k-trace dataset](https://huggingface.co/datasets/solarkyle/jspace-hallucination-campaign).

**[solar-roof-cv-2019](https://github.com/solarkyle/solar-roof-cv-2019)**: the 2019 origin project, preserved as built. A U-Net (ResNet-34) segmenting rooftops from satellite imagery into 16 compass-orientation classes for automated solar quoting, trained on homes I labeled by hand, with a custom direction-aware loss that penalizes near-miss compass predictions less than opposite ones. Published with its provenance and limitations stated plainly.

**[tabfm-ufc-benchmark](https://github.com/solarkyle/tabfm-ufc-benchmark)**: a clean negative result. Google's TabFM beats a tuned 5-model ensemble on UFC prediction out of the box, and both lose decisively to the betting market. Public-data sports modeling has no moneyline edge; the write-up shows why, and includes a forward test committed to git before the event it predicts.

**[pit](https://github.com/solarkyle/pit)**: a minimal coding and general agent I fully own (one dependency), plus an empirical lab for the harness itself: context-memory designs tested against vanilla baselines across ~25 local model and quantization configs.

**[trading-lab](https://github.com/solarkyle/trading-lab) + [daytrader-lab](https://github.com/solarkyle/daytrader-lab)**: a market-ML lab in two acts. A 30-experiment walk-forward campaign that took SPY Sharpe from -0.86 to +0.91 under purged validation, and a deliberately pessimistic intraday backtest harness (halt traps, short-sale rules, participation caps) whose first published result is a refutation of my own strategy.

## Products

**[Resource Pack Creator](https://resourcepackcreator.com)**: browser-based Minecraft resource pack builder, built and operated solo. 2M+ monthly pageviews, sessions averaging 15 minutes. React 19.

**[PixelLock](https://github.com/solarkyle/pixellock)**: footprint-locked AI pixel-art retexturing (Build Small hackathon). A fine-tuned text LLM restyles sprites through a llama.cpp GBNF grammar compiled from the input's silhouette, so shape is preserved by construction, not by hope. [Live Space](https://huggingface.co/spaces/solarkyle/PixelLock), [weights](https://huggingface.co/solarkyle/pixellock-gemma-12b-pixelart-gguf).

**[Alibi](https://github.com/solarkyle/alibi)**: AI murder-mystery interrogation game. Every suspect is a fine-tuned LLM with its own personality, alibi, and breaking point. [Model](https://huggingface.co/solarkyle/alibi-suspect-qwen3.5-4b-gguf), [1,736-conversation dataset](https://huggingface.co/datasets/solarkyle/alibi-interrogation-dataset).

**[eg4-agent](https://github.com/solarkyle/eg4-agent)**: local-first, read-only monitor and LLM diagnostic agent for EG4 solar inverters. Advises, never actuates, by design.

## How I work

- Build before claiming certainty.
- Separate observations from interpretations.
- Preserve negative results. They are results.
- Update fast when the evidence breaks the hypothesis.
- Learn whatever the problem requires and keep iterating until it is real.

## Contact

fintechkyle@gmail.com · [Hugging Face](https://huggingface.co/solarkyle)
