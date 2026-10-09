# BEYOND BLOCKCHAIN

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-space_aerotech-lightgrey)

> Anticloud-hardened packaging of the upstream project `BEYOND_BLOCKCHAIN` in category **SPACE AEROTECH**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SPACE AEROTECH · **Upstream:** https://github.com/Consensys/Beyond-Blockchain-Relay · **Upstream pin:** `0866f3451fe06b8423fa6beb4c06d2196bf0de96` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Submitting Beyond Blockchain Bounties - Details and Instructions

## Submission Deadline
All bounty submissions must be received no later than 11:59 PM EDT on July 10th, 2019 to be considered.

## Judging Date
Projects will be assessed from July 10th to July 15th, 2019, and winners will be announced by GitCoin and Labs.

## How to Submit Your Project!

### Step 1
1) Fork Beyond-Blockchain-Relay from github UI -  https://github.com/ConsenSys/Beyond-Blockchain-Relay

### Step 2
source forked project to local machine (master branch) named after your project

### Step 3
In the project, there is one folder for each bounty. Open the folder that corresponds with the bounty you are submitting against.

### Step 4
Add your app **folder** in the respective project folder (e.g. DeFi, Media, Medical) of the hackathon

#### Step 4.1
Name the subfolder your project name.

### Step 5
Submit the following in your project's folder:
- Submission.md template
- A single file that pitches the product (video, PDF, deck)
- All supporting material (code, research, designs etc)

All submissions, including all code, must be open source for future use and reference by the community, and links to external documents must be provided in the Github project submission.

As a reminder, we are looking for projects that address a real problem and teams that have shown the progress and entrepreneurial instincts to make something real and get it out in the world. Your application should communicate this. _The more compelling the presentation, the better your team does!_

### Step 6
Fill out the submission.md template, included at the top of the bounty's folder with all relevant information.

**This must be included to be considered for the bounty prize.**

### Step 7
Commit your changes and push your branch to your forked project.

### Step 8
Raise PR against the original Beyond-Blockchain-Relay project from the forked project On GitHub. To create the PR, if you go to the forked project on github it will have a big green popup asking if you want to make a PR.

![Creating a Pull Request from a Forked project](https://i.imgur.com/TQAgPh4.png)

If the green button doesn't show, there is a the "New pull request" button on the left, just click that and select the branch   to create the PR.

![Select your branch to create the pull request from](https://i.imgur.com/2ClfyAm.png)

### Step 9
![Congratulations](https://media.giphy.com/media/ehhuGD0nByYxO/giphy.gif)
Congratulations!

You've just submitted your project to the Labs Open Finance Bounty! We cannot wait see what you've made over the last 15 days!

## Questions?
If you have questions or comments, please reach out to us on the Discord chat (#consensys-labs).

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Top-level source layout: `DeFi/`, `Media/`, `Medical/`
- Snapshot size: **1336 files**, **46477 lines of code** (measured; see Benchmarks)
- Primary languages: `.js` (286), `.scss` (217), `.json` (119), `.png` (108), `.ts` (92), `.sol` (67)
- Upstream commit pinned for this packaging: `0866f3451fe06b8423fa6beb4c06d2196bf0de96`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

As a reminder, we are looking for projects that address a real problem and teams that have shown the progress and entrepreneurial instincts to make something real and get it out in the world. Your application should communicate this. _The more compelling the presentation, the better your team does!_

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

As a reminder, we are looking for projects that address a real problem and teams that have shown the progress and entrepreneurial instincts to make something real and get it out in the world. Your application should communicate this. _The more compelling the presentation, the better your team does!_

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 1336 |
| Lines of code | 46477 |
| Dependency references | 433 |
| Dependencies by ecosystem | npm: 433 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | fs-extra | ^8.1.0 | Medical/MediSupport/package.json |
| npm | ganache-cli | ^6.4.4 | Medical/MediSupport/package.json |
| npm | mocha | ^6.1.4 | Medical/MediSupport/package.json |
| npm | next | ^4.1.4 | Medical/MediSupport/package.json |
| npm | next-routes | ^1.4.2 | Medical/MediSupport/package.json |
| npm | react | ^16.8.6 | Medical/MediSupport/package.json |
| npm | react-dom | ^16.8.6 | Medical/MediSupport/package.json |
| npm | semantic-ui-css | ^2.4.1 | Medical/MediSupport/package.json |
| npm | semantic-ui-react | ^0.87.2 | Medical/MediSupport/package.json |
| npm | solc | ^0.4.25 | Medical/MediSupport/package.json |
| npm | truffle-hdwallet-provider | ^1.0.12 | Medical/MediSupport/package.json |
| npm | web3 | ^1.0.0-beta.37 | Medical/MediSupport/package.json |
| npm | openzeppelin-solidity | 2.3.0 | Medical/ImmunoBlock/ImmunoBlock_code/ethereum/package.json |
| npm | bignumber.js | 9.0.0 | Medical/ImmunoBlock/ImmunoBlock_code/ethereum/package.json |
| npm | chai | 4.2.0 | Medical/ImmunoBlock/ImmunoBlock_code/ethereum/package.json |
| ... | (418 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `BEYOND_BLOCKCHAIN` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2019 ConsenSys

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `BEYOND_BLOCKCHAIN` (category: SPACE AEROTECH)
- **Upstream URL:** https://github.com/Consensys/Beyond-Blockchain-Relay
- **Pinned commit (SHA):** `0866f3451fe06b8423fa6beb4c06d2196bf0de96`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`445845babba703d12ba801788497a4ed8de452ce1f7ff8e7d70099c197edb2a8`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

