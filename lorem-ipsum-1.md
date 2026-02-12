# IRIS Technical Architecture

## Contents

[TOC]

## Solution Description

### Provide solution summary

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

#### Current State

Currently there\'s a solution called Current Global Risk Profile, CRR,
that consists of:​

- **Operating environment factors:** Organizational governance,
    physical security, nosiness continuity, budget, acquisitions,
    geopolitical assessment, supply chain, and information privacy.​

- **Continuous monitoring factors:** Policy violations, vulnerability
    management, patch management, antivirus management, encryption
    management, monitoring and alerting security incidents,
    threat intelligence, asset management, admin vs standard users,
    privileged account management.

The diagram below represents the current state architecture:

![Current state architecture diagram of the solution](./assets/current_state.PNG)

/// caption
Figure 1- Current state architecture diagram of the solution.
///

Listed below are the pain points associated with the current state
architecture, corresponding to the numerical yellow circles in the above
current state architecture diagram:

1.  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
2.  Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
3.  Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
4.  Nisi ut aliquip ex ea commodo consequat.
5.  Duis aute irure dolor in reprehenderit in voluptate velit esse.
6.  Cillum dolore eu fugiat nulla pariatur.

#### Moving from Risk profiles to IRIS

The Interim Solution will provide the steppingstone for a more
significant KRI focused delivery in the near future. Below are five key
changes based on key identified improvement opportunities as ratified by
our core customer base for the incumbent Risk Profiles solution.

| **Risk Profile (CRR)** | | **Interim Solution (April 2023)** |  |**IRIS** |
|-----------|---------------|----------------------------------|------|-----|
| Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent id justo in neque elementum porta. | &rarr; | Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation. | &rarr; | Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. |
| Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. | &rarr; | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus magna justo, lacinia eget consectetur sed. | &rarr; | Convallis tellus id interdum velit. Pretium quam vulputate dignissim suspendisse in est. |
| Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. | &rarr; | Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. | &rarr; | Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi. |
| Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. | &rarr; | Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. | &rarr; | Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl. |
| Risus commodo viverra maecenas accumsan lacus vel. Neque viverra justo nec ultrices dui. | &rarr; | Ornare arcu dui vivamus arcu felis bibendum ut. Nibh praesent tristique magna sit amet purus. | &rarr; | Tincidunt arcu non sodales neque sodales ut etiam. Amet volutpat consequat mauris nunc. |

#### Target State Integrated Risk Information System (IRIS)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper. Amet justo donec enim diam vulputate ut pharetra. Egestas purus viverra accumsan in nisl nisi. At quis risus sed vulputate odio ut enim. Massa tincidunt dui ut ornare lectus sit. Viverra mauris in aliquam sem fringilla ut morbi.

Tellus in metus vulputate eu scelerisque felis imperdiet proin. Faucibus a pellentesque sit amet porttitor. Porttitor eget dolor morbi non arcu. Eget nullam non nisi est sit amet facilisis. Amet consectetur adipiscing elit duis tristique. Id aliquet lectus proin nibh nisl.

- **KPMG Entity** Lorem ipsum dolor sit amet, consectetur adipiscing elit.
- **Risk** Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
- **KRI** Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris.
- **Metric** Nisi ut aliquip ex ea commodo consequat.
- **Formula** Duis aute irure dolor in reprehenderit in voluptate velit esse.

##### Knowledge Graph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

| What        | Description                                                                                                     |
|-------------|-----------------------------------------------------------------------------------------------------------------|
| KPMG entity | KPMG Lisbon                                                                                                     |
| Risk        | Risk #2: System intrusion                                                                                       |
| Sub-Risk    | Risk #2.1: System intrustion initiated by exploit of security vulnerability                                     |
| KRI         | KRI 1.1 - Health of IT assets and IT services inventories                                                       |
| Metric      | A 1.1                                                                                                           |
| Formula     | %: ## of IT assets in the IT asset inventory vs ## of discovered internal IT assets on all KPMG internal networks |

/// caption | <
Table 1 - Illustrative Knowledge Graph Instance
///

![Illustrative Knowledge Graph Instance](./assets/image1.png)

/// caption
Figure 2 - Illustrative Knowledge Graph Instance
///

From the above ontology diagram a representation of the data model underlying IRIS can be built.

![IRIS Data Model](./assets/image1.png)

/// caption
Figure 3 - IRIS Data Model.
///

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Pellentesque habitant morbi tristique senectus et netus et malesuada. Arcu cursus vitae congue mauris rhoncus aenean. Amet justo donec enim diam vulputate ut pharetra. In est ante in nibh mauris cursus mattis. Sed libero enim sed faucibus turpis in eu. Eget sit amet tellus cras adipiscing enim eu turpis.

Nunc pulvinar sapien et ligula ullamcorper




## FeedBack

- If a doc has images that are being referenced, I assume they convert seamlessly.
