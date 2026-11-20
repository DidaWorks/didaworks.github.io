# didaworks.github.io

Public website for the DidaWorks project: free and open-source tools designed around real teaching workflows.

## What's here

| Path | What it is |
|---|---|
| `/` | Home page |
| `/commons/` | DidaCommons: what it is and a link to GitHub Discussions |
| `/teaching-tools/` | Hub for the browser-based teaching tools |
| `/teaching-tools/workload-estimator/` | Course Workload Estimator (CC BY-NC-SA 4.0 adaptation; see below) |
| `/teaching-tools/date-shifter/` | Syllabus Date Shifter |
| `/teaching-tools/nursing-exam-tools/` | Item analysis, test blueprint, exam timing, NGN case builder |
| `/teaching-tools/nursing-clinical-tools/` | Dosage problems, clinical hours, rotation grid, feedback comment bank |
| `/licenses/` | Every license and attribution used on the site |
| `/assets/fonts/` | Roboto (SIL OFL 1.1) and Roboto Slab (Apache 2.0), with license texts |

Every tool is a single self-contained HTML page. Nothing is sent to a server: files, data, and text stay in the visitor's browser. Pages are marked `noindex` while they're prototypes.

## Brand

Colors, type and voice follow the DidaWorks brand standards (Flagstaff palette: Ponderosa, Aspen gold, Aspen bark, Meadow, Peaks blue, Cinder, Basalt, Limestone, Dark sky). Each page carries the shared site layer in its `<style>` block, marked `DidaWorks site layer (shared)`; change it on every page together.

## Licenses

- **DidaWorks code:** MIT License (see `LICENSE`), except where noted.
- **Exception: `teaching-tools/workload-estimator/`** adapts the Course Workload Estimator by Betsy Barre, Allen Brown, and Justin Esarey (Rice University; Workload Estimator 2.0, Wake Forest University) and is licensed **CC BY-NC-SA 4.0**, as the original is. See `teaching-tools/workload-estimator/LICENSE.md`.
- **Third-party software, fonts, and content credits:** see `THIRD_PARTY_NOTICES.md` and the `/licenses/` page.

## Hosting

GitHub Pages from the `main` branch. The custom domain (didaworks.org) is set in **Settings → Pages** once DNS points here; GitHub then adds the `CNAME` file itself.
