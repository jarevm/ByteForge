# Team ByteForge · CCSFEN1L Software Engineering

> **NOTE: Thesis is still TBA.** Once proposed topic is decided this file will be subject to revision.

**Proposed thesis:** *TBA: short description*

This repository holds Team ByteForge's laboratory work, proposal artifacts, and proof-of-concept spike for CCSFEN1L Software Engineering (2nd Term, A.Y. 2026-2027).

## Team

| Active Role | Name | Alternative Role |   
| --- | --- | --- |
| Project Lead | Cabrera, Edrei Ansel N. | Reasearch Lead |
| Technical Lead | Madanglog, John Rev D. | QA and Data Lead |
| Research Lead | Nepomuceno, Julliana P. | Technical Lead |

Roles, norms, and the conflict process are in [`CHARTER.md`](CHARTER.md). Thesis ideas from every lab are in [`TOPIC_BANK.md`](TOPIC_BANK.md).

## Repository layout

```text
.
├── README.md             # this file
├── CHARTER.md            # team charter
├── TOPIC_BANK.md         # one entry per lab, Labs 01 to 10
├── docs/
│   ├── requirements.md   # stakeholders, requirements, user stories (Week 4)
│   ├── adr/              # architecture decision records (Week 7)
│   ├── diagrams/         # C4 and UML diagrams (Week 7)
│   ├── test-plan.md      # test levels and cases traced to requirements (Week 9)
│   ├── project-plan.md   # WBS, Gantt chart, risk register, budget (Week 10)
│   └── decisions.md      # team decision log
├── labs/
│   └── lab01/ ... lab11/ # notebooks, results, and REPORT.md for each lab
├── poc/                  # proof-of-concept spike (AgriScan Edge)
│   ├── src/
│   └── tests/
├── .github/
│   ├── ISSUE_TEMPLATE/   # user story and bug templates
│   └── workflows/ci.yml  # runs the tests on every pull request
├── requirements.txt
└── .gitignore
```

The proposal itself is written on Overleaf (IEEE template), and references are kept in our shared Zotero library.

## Getting started

```bash
git clone https://github.com/jarevm/ByteForge.git
cd ByteForge
python -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
pytest                             # runs the spike's tests
```

Lab notebooks run in Google Colab. Open them from `labs/labNN/` with **File > Open notebook > GitHub**.

## How we work

- **Branching:** GitHub flow. `main` is protected. Every change goes through a branch and a pull request.
- **Branch names:** `feature/<issue>-<short-name>`, `fix/<issue>-<short-name>`, or `docs/<short-name>`. For example, `feature/23-int8-export`.
- **Pull requests:** at least one approving review and a passing CI run before merging. Link the issue with `Closes #23`.
- **Commits:** short, imperative messages, for example `Add int8 export script`.
- **Board:** every task is an issue on our GitHub Projects board (Backlog, To Do, In Progress, In Review, Done).
- **Secrets:** never commit API keys, passwords, or raw photos with farmer details. Use environment variables, and keep local secret files in `.gitignore`.

A story is done only when it meets the Definition of Done in [`CHARTER.md`](CHARTER.md#6-quality-standards).

## Labs

| Lab | Paradigm | Folder | Status |
| --- | --- | --- | --- |
| 01 | Paradigm scan and toolchain setup | [`labs/lab01`](labs/lab01) | Done |
| 02 | Classical machine learning pipeline | [`labs/lab02`](labs/lab02) | TBA |
| 03 | Transfer learning for image classification | [`labs/lab03`](labs/lab03) | TBA |
| 04 | Retrieval-augmented generation | [`labs/lab04`](labs/lab04) | TBA |
| 05 | Agents and a responsible AI audit | [`labs/lab05`](labs/lab05) | TBA |
| 06 | Qubits and quantum circuits | [`labs/lab06`](labs/lab06) | TBA |
| 07 | Quantum algorithms and post-quantum cryptography | [`labs/lab07`](labs/lab07) | TBA |
| 08 | Deploy a model to the edge | [`labs/lab08`](labs/lab08) | TBA |
| 09 | Attack, defend, or federate | [`labs/lab09`](labs/lab09) | TBA |
| 10 | Emerging paradigms and spike demo | [`labs/lab10`](labs/lab10) | TBA |
| 11 | Proof-of-concept showcase | [`labs/lab11`](labs/lab11) | TBA |

## Proof of concept

The spike in [`poc/`](poc) tests our riskiest assumption: an int8 model under 5 MB can classify four rice leaf classes with at least 85% accuracy on photos from an unseen farm, in under 2 seconds on a 2 GB Android phone. The model met the size and speed targets but reached 0.81 accuracy on the unseen farm. The full result and what we changed are at the end of [`TOPIC_BANK.md`](TOPIC_BANK.md#outcome-proof-of-concept-showcase-week-11).

## Use of AI tools

We use AI assistants for brainstorming, coding help, and language editing. Each lab's `REPORT.md` says what we used them for. We can explain every line we submit, and we check every cited source ourselves.

## License

Code in this repository is released under the MIT License (see `LICENSE`). Field photos are not included, because they belong to the participating farmers and are covered by our consent forms.
