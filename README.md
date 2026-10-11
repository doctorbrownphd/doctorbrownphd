## Jeremy Haynes

The handle is a *Back to the Future* nod, not a credential.

I direct enterprise IT and data systems at a regulated electric and gas utility in New England, and I build. Most of my work sits between the meter and the bill: CIS, AMI, and MDMS implementations, the integrations that feed billing, and the regulatory data a utility shares with states and customers. More of it now is AI: retrieval over regulatory filings, LLM evaluation, and AI governance under the NIST AI Risk Management Framework.

I've been writing software for 25 years. These projects are my own, built on my own time with public data.

### Projects

- [RateMap New England](https://github.com/doctorbrownphd/ratemap-newengland): a bill calculator and rate explorer for 38 rate plans from 11 New England utilities. Every rate comes from a tariff filing. You can run synthetic load profiles or upload your own interval data, including Green Button XML.
- [OpenSynth New England](https://github.com/doctorbrownphd/opensynth-newengland): synthetic 15-minute smart meter load profiles for New England homes. A conditional VAE trained on NREL ResStock data generates profiles by housing type, heating fuel, weather, and solar or EV ownership, checked against EIA and ISO-NE statistics.
- [OpenSTEF Narrator](https://github.com/doctorbrownphd/openstef-narrator): plain-language situation reports for probabilistic feeder load forecasts. A template engine writes every number, an LLM only rephrases the prose around them, and a validator rejects any rewrite that adds or changes a fact.
- [Duck curve days in New England](https://github.com/doctorbrownphd/isone-duck-curve): which days New England's grid demand bottoms out mid-afternoon instead of overnight, and why. A PySpark pipeline on AWS Glue and Athena over ISO-NE hourly load and NOAA weather, with a logistic regression that finds installed rooftop solar, clear skies, weekends, and spring driving those days. My capstone for the MS in Data Analytics.
- A retrieval system over FERC and New England state commission filings, with hybrid search, page-level citations, and an evaluation harness. The code is private; I'm glad to demo it.

### Tools I use

Python, SQL, C# and .NET, TypeScript and React, PostgreSQL with pgvector, PyTorch, and FastAPI. I build with Claude Code.

### Contact

[LinkedIn](https://www.linkedin.com/in/jeremyshaynes/)
