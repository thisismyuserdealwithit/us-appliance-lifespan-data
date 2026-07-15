# US Appliance Lifespan by State, Brand and Common Issue

This repository contains the structured research behind [Lifespan Lab](https://appliance-lifespan-guide.masterblaster1.chatgpt.site), an interactive guide to appliance working life, common faults, brand fit and broad state conditions across the United States.

The release contains 300 state-and-appliance estimates covering six appliance categories and all 50 states. It also includes 11 brand profiles, 18 common-issue records, 25 detailed brand-and-appliance research records and a source register. The longer research fields are included intact so journalists, analysts and homeowners can understand the reasoning behind a score instead of seeing a number without context.

## What is included

| File | Contents |
| --- | --- |
| [data/appliances.csv](data/appliances.csv) | National planning ranges, confidence labels, summaries and care tips for six appliance categories. |
| [data/brands.csv](data/brands.csv) | Brand profiles, editorial scores, strengths and covered appliance categories. |
| [data/appliance_brand_scores.csv](data/appliance_brand_scores.csv) | Ranked brand shortlists for each appliance category. |
| [data/common_issues.csv](data/common_issues.csv) | Common symptoms and broad US repair-cost ranges. |
| [data/state_profiles.csv](data/state_profiles.csv) | Climate profiles, adjustment factors, state guide links and a deep link to each relevant [Warranty Index](https://warrantyindex.com/) state page. |
| [data/state_appliance_estimates.csv](data/state_appliance_estimates.csv) | The complete 50-state by six-category model, including state and appliance guide URLs. |
| [data/brand_appliance_research.csv](data/brand_appliance_research.csv) | Longer verdict, evidence, ownership and fit notes for 25 brand-and-appliance combinations. |
| [data/research_sources.csv](data/research_sources.csv) | Sources with a plain-language note explaining what each one can and cannot establish. |
| [data/data_dictionary.csv](data/data_dictionary.csv) | Definitions for the fields most likely to be misread. |

## Read this before using the numbers

These are editorial planning estimates, not observed warranty claims or measured failure probabilities. The national category range is multiplied by a restrained state factor and rounded to one decimal place. A state border cannot predict the life of an individual machine. Installation, room temperature, water chemistry, household use, maintenance, parts availability and local service can matter more.

Brand scores are also editorial. First-year service rates, recent-owner satisfaction and long-term survival are different measurements, so the research never treats one as a substitute for another. Read [METHODOLOGY.md](METHODOLOGY.md) before publishing comparisons or rankings.

## Explore and contribute

Use the [interactive research site](https://appliance-lifespan-guide.masterblaster1.chatgpt.site) to compare products and open the longer brand-type pages. If you find an error, have a better primary source or want to share a local service observation, open a GitHub issue. Please include the appliance category, brand, state and source or firsthand context so a proposed change can be evaluated transparently.

## Citation

Suggested citation:

> Lifespan Lab. *US Appliance Lifespan by State, Brand and Common Issue*. Version 1.0, July 2026. https://github.com/thisismyuserdealwithit/us-appliance-lifespan-data

Machine-readable citation metadata is available in [CITATION.cff](CITATION.cff).

## License

The dataset and original documentation are released under [Creative Commons Attribution 4.0 International](LICENSE.md). Please credit Lifespan Lab and link to this repository. Third-party source material remains subject to its original terms.
