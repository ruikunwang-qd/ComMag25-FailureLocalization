# ComMag25-FailureLocalization
OptiFail dataset in IEEE Communications Magazine

This repository provides the OptiFail dataset, introduced in our IEEE Communications Magazine submission “Failure Localization in Optical Networks: How Much Machine Learning do We Need? ”. OptiFail is designed to support method-selection decisions between machine-learning (ML)–based and heuristic–based failure localization approaches in optical networks.

1. Dataset Overview
The OptiFail dataset is a scenario-level, structured dataset derived from a systematic review of representative prior studies on failure localization in optical networks. Each sample corresponds to a distinct failure-localization scenario, characterized by a set of network attributes and a binary label indicating which class of ML or heuristic been reported as more suitable under that scenario.

2. Dataset Structure
Each sample in OptiFail consists of:
| Field              | Description                         |
| ------------------ | ----------------------------------- |
| Failure Type       | Hard failure / Soft failure         |
| Number of Failures | Single / Multiple                   |
| Localization Level | Lightpath / Link / Network          |
| Monitor Locations  | Per-component / Per-link / Per-node |
| Monitoring Devices | e.g., OPM, OTDR                     |
| Monitoring Data    | e.g., Power, Spectrum, BER          |
| Label              | ML or Heuristic                     |

3. Limitations
The dataset is literature-derived and depends on the scope and reporting quality of existing studies. Moreover, as the research field evolves, some scenarios may change in suitability; future updates are expected.



