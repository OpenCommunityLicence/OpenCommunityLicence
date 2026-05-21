# Changelog

All notable changes to the Open Community License are tracked here.

## v1.1

### License text (`LICENSE`)

- **Terminology**: "product" reframed as **"licensed item - hardware and/or software"**, with components covered explicitly.
- **Non-commercial END USER**: derivatives must now be redistributed **under OCL itself**, not "any non-commercial share-alike license". This tightens the share-alike condition.
- **Commercial BUSINESS USER**:
  - "Internal production" broadened to **"internal business use (including internal production)"**.
  - The standalone "MUST NOT modify for commercial purpose" clause has been removed; the remaining restriction is on **copying / replication** for commercial purpose, with the internal right-to-repair carve-out preserved.
- **New mechanism - add-on conditions**: licensors may expand OCL conditions only by including add-ons defined in this repository. Distributions must reference both OCL version and applicable add-on versions; derivatives must retain them.
- **New clause**: OCL does not override imperative exceptions and limitations under applicable law.
- The OCL good-practice **database is now optional** ("may keep and update") rather than mandatory.

### New: add-on conditions (`addons/`)

Four add-ons introduced alongside v1.1:

- **GAtt v1** - General Attribution (non-commercial end users; retain creator identification in derivatives).
- **SWAtt v1** - Software Attribution (as GAtt, plus visible attribution in UI and source code).
- **Micro v1** - Micro Business (caps free commercial use at EUR 1,000,000 annual gross revenue, including affiliates).
- **RnD v1** - Research & Development (commercial use limited to R&D and prototyping; no manufacturing without separate license).

### Examples (`examples/prusa-ocl-examples.md`)

- Scenario 1 updated: derivative now redistributed under **OCL** (not CC BY-NC-SA), reflecting the tightened share-alike rule.
- Scenario 5 rewritten around **dual licensing (OCL + GPLv2)** to illustrate how OCL coexists with prior incompatible licenses.
- Scenario 7 strengthened: derived-design creator **must** (not "should") be contacted for commercial license.
- **New Scenario 9**: demonstrates `OCL + RnD` for prototyping vs. manufacturing.
- **New Scenario 10**: demonstrates `OCL + SWAtt` for a software fork with attribution duties.

## v1

Initial release of the Open Community License. See git tag `v1` for the historical text.
