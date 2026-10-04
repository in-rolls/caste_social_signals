# Passing Glance

**How much of a person's social position is legible to a stranger?**

Two people can have different incomes and look materially much the same.
Someone living on ₹2,500 per person per month may have much the same clothing,
phone and transport as someone living on ₹2,000. If those signals barely
separate economic positions, they may reveal even less about a social identity
whose income distribution overlaps with several others.

This project synthesizes evidence about the information available in ordinary
encounters: names, place, visible material circumstances, and what an observer
believes those cues mean. It distinguishes economic inequality, observable
differences, and accurate social identification. A cue can change someone's
odds substantially without making a confident identification possible.

The hypothesis is **limited legibility**, not the absence of inequality. It is
also possible that mass-market goods erase some obvious markers while status
moves into subtler markers, or that insiders recognize differences strangers
miss. The empirical question is which cues distinguish whom, for which observer,
in which setting, and at what resolution.

## Research strands

| Strand | Existing work | Contribution to the synthesis |
|---|---|---|
| Names and local knowledge | [caste_name_information](../caste_name_information/README.md) | Aggregate information in names, base rates, coverage, and geographic context |
| Economic distributions | [caste_economic_overlap](../caste_economic_overlap/README.md) | Income/land overlap, two-draw comparisons, common thresholds, and reverse tail composition |
| Appearance and perception | [Perception literature](docs/literature.md); related local project `../chehra` | Distinguish actual information from impressions, stereotypes and observer confidence; critically assess existing claims rather than treating a machine score as human perception |
| Land and recorded jati | [Land-source audit](../caste_economic_overlap/docs/additional-land-sources.md) | Bihar, Rajasthan and Odisha records; direct labels, ownership selection and measurement limitations |
| Context and time | [Study design](docs/design.md) | Strangers versus local knowledge, changing consumer signals, income volatility and durable possessions |

The synthesis is a separate repository. Source analyses remain in their own
repositories; this one holds the argument, evidence inventory, comparative
standards and study designs. No combined multi-cue result has yet been estimated.
Appearance work here concerns published perception research, non-facial material
cues and aggregate methodological critique. It does not implement automated
caste categorization from portraits.

[Study design](docs/design.md) · [Initial literature](docs/literature.md) ·
[Evidence register](docs/evidence-register.md)

## What is already available

The linked economic project has a reproduced IHDS-II income pilot, broad-group
and within-state reported-label pairwise matrices, sorted distribution ranges,
threshold shares, held-out income-band forecasts and tail composition. It uses
the existing `../land` ingestion conventions. The detailed label field still
needs a reviewed crosswalk.

The research design separates three quantities that must not be compared as
though they were the same: separation between economic distributions,
information in a material cue, and an observer's actual judgment accuracy.
The United States comparison is a hypothesis to investigate with dated
consumption evidence, not a premise already established by common phone ownership.

## Working convention

Use links to source results instead of manually copying numerical claims. Any
new cross-project comparison must state its population, year, target categories,
cues, sampling weights, coverage, holdout design and uncertainty. Keep individual
records and any source portraits outside this synthesis repository.

This is a research-notes repository; there is no runtime package or build step.
