# Evidence register

Status as of 2026-09-10. Source links assume sibling local checkouts.

| Project | Inspected material | Current role | Main comparability issue |
|---|---|---|---|
| [caste_name_information](../../caste_name_information/README.md) | README and existing project structure | Name information, posterior versus prior, geographic context | Multiple populations, targets and label sources; headline figures are not one common benchmark |
| [caste_economic_overlap](../../caste_economic_overlap/output/ihds-first-look.md) | Reproduced income pilot, generated aggregate tables and figures | Economic overlap and reverse composition; broad versus detailed reported labels | Historical price years; household/person distinction; literal jati labels are not harmonized identities |
| [land](../../land/scripts/97_ihds_ingest.ipynb) | IHDS notebooks 97/98 and local survey release | Existing ingestion conventions and land analysis | Ownership, titling and income are distinct outcomes; some survey blocks have structural skips |
| [ror_rajasthan_2026](../../ror_rajasthan_2026/README.md) | Parser, pilot Parquet schema and aggregate diagnostics | Recorded jati, land area and ownership shares: potential economic extension | Landholder selection, repeated owners, missing subdivided plots, and reused source-plot areas in `via` records |
| [ror_odisha_2026](../../ror_odisha_2026/README.md) | Parser/fetcher, tenant Parquet schema and metadata | Large direct caste/name/place corpus | Tenant occurrences, not unique people; extracted records do not currently retain land area; settlement vintage and selective coverage |
| [chehra](../../chehra/README.md) | README only | Related appearance project; methodological context for separating model scores from observer judgments | Surname-derived labels, selected subjects and a different outcome; no portrait analysis or model execution undertaken for this synthesis |

The [additional land-source audit](../../caste_economic_overlap/docs/additional-land-sources.md)
documents which economic variables are actually retained. A repository described
as land records is not necessarily an analysis-ready land-distribution dataset.

The synthesis has not combined individual records across projects. A cross-project
result requires a separately documented shared population, independent target
labels, validated joins where relevant, and compatible measurements.
