# ToolDepth: A Recursive Framework for Measuring Intelligence Across Species and Systems

**White Paper v1.0**
**Author:** Rogério Figurelli
**Date:** May 5, 2025

---

## Executive Summary

Current intelligence assessments in biological and artificial domains rely on coarse, binary markers of tool use—simply whether an agent uses tools or not. This method overlooks the nuanced, multi-layered processes that distinguish mere tool use from deeply recursive tool-making and fails to capture incremental advances in cognitive and engineering sophistication.

**Innovation of ToolDepth:** ToolDepth introduces the concept of **Recursive Instrumental Index (RII),** a metric that quantifies the number of sequential tool-production layers. Each layer represents a tool employed to create the next, forming a chain whose depth correlates with strategic planning, foresight, and adaptive learning. By focusing on lineage rather than end results, RII reveals hidden dimensions of intelligence.

**Relevance to AGI Research:** The pursuit of artificial general intelligence hinges on systems that autonomously plan, design, and refine tools or subroutines across multiple stages. ToolDepth provides:

* **AGI Progress Benchmarks:** RII thresholds define milestones toward AGI, marking when an AI system achieves truly recursive self-improvement capabilities.
* **Anomaly Detection:** Real-time RII monitoring can signal emergent AGI-like behavior when depth indices exceed expected human benchmarks.
* **Cross-Domain Validation:** By comparing AI RII scores against anthropological and ethological data, researchers can contextualize AI developments within natural intelligence evolution.

**Key Contributions:**

* **Granular Depth Measurement:** Integer-based RII scores expose incremental improvements in AI architectures and learning algorithms.
* **Unified Comparative Framework:** Directly aligns machine capabilities with biological tool-use evolution, fostering interdisciplinary insights.
* **Operational Transparency:** Dependency graphs trace each recursion step, facilitating explainability and auditability in AGI systems.

This white paper elaborates on:

1. **Hierarchical Classification (Classes 0–12):** Taxonomy of tool-making depth across species and machines.
2. **RII Computation:** Algorithms for extracting and scoring dependency graphs from logs and observations.
3. **Data Infrastructure:** End-to-end pipeline for ingestion, processing, storage, and visualization.
4. **Use Cases:** Strategic applications in anthropology, AI benchmarking, education, and industrial innovation.
5. **Future Directions:** Embodied AI integration, AGI detection via RII anomalies, and planetary-scale recursive modeling.

By shifting focus from tool use to tool-making depth, ToolDepth equips AGI research with precise metrics and scientific rigor, accelerating the path toward truly autonomous, self-improving systems.

---

## 1 Introduction

The ToolDepth framework categorizes both artificial and biological systems by the depth of their recursive tool-making abilities. By aligning machine classes with analogous species behaviors, we can compare technological autonomy with natural cognition on a unified scale. The table below provides context and concrete examples for each class, emphasizing how tool complexity and lineage reflect varying levels of intelligence:

| **Class** | **Machine Class Description**                                                                                        | **Biological Class Description**                                                                        | **Example (Machine / Species)**                                                           |
| --------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| 0         | Passive Machines — Execute fixed operations without sensing or adaptation \[5].                                      | Non-Tool Organisms — No documented tool use \[16].                                                      | Electric drill \[5] / Sponge \[16]                                                        |
| 1         | Reactive Tool Users — Employ preconfigured tools in response to stimuli \[6].                                        | Basic Tool Users — Use natural objects without modification \[13].                                      | Industrial robot arm \[6] / Sea otter shell-breaking with rocks \[13]                     |
| 2         | Tool Assemblers — Assemble components into tools using predefined instructions \[7].                                 | Tool Modifiers — Modify objects for specific tasks \[12].                                               | Assembly-line robot \[7] / Chimpanzee fashions twig for termite fishing \[12]             |
| 3         | Tool Designers — Create novel tool designs based on specifications or simulations \[9].                              | Compound Tool Users — Combine tools sequentially \[14].                                                 | AI-assisted CAD system \[9] / New Caledonian crow multi-step tool use \[13]               |
| 4         | Meta-Tool Engineers — Develop tools that automate the design or fabrication of other tools \[5].                     | Cumulative Culture Species — Intergenerational refinement of tool traditions \[16].                     | Self-improving design software \[5] / Homo erectus lithic refinement \[14]                |
| 5         | Recursive Agents — Plan, execute, and iteratively refine multi-step tool production pipelines autonomously \[4]\[6]. | Recursive Technologists — Humans designing tools that create subsequent tool generations \[15].         | Reinforcement-learning fabrication pipeline \[4]\[6] / CNC + 3D printing workflow \[15]   |
| 6         | Basic Fabricators — Automate reproduction of existing tools with minimal oversight \[9].                             | Early Hominins — Flint knapping of hand axes \[14].                                                     | CNC lathe replication \[9] / Homo habilis hand axe production \[14]                       |
| 7         | Composite Manufacturers — Integrate multiple automated processes for complex assemblies \[7].                        | Early Industrializers — Steam-powered factories creating machinery \[15].                               | Multi-robot cell production \[7] / 19th-century textile mills \[15]                       |
| 8         | Digital-Centric Technologists — Employ generative design and CAM for optimized tool creation \[9].                   | Modern Engineers — Parametric CAD and CAM workflows \[19].                                              | Generative-design software + 3D printer \[9] / Turbine blade manufacturing \[19]          |
| 9         | Autonomous Tool Engineers — Use closed-loop AI systems to autonomously iterate tool designs \[4].                    | AI-Enhanced Labs — Automated experimentation platforms \[17].                                           | Closed-loop materials discovery labs \[17] / Automated corvid tool-learning studies \[13] |
| 10        | Adaptive Fabrication Ecosystems — Distributed networks of agents evolving toolchains collaboratively \[4].           | Advanced Cumulative Cultures — Highly interdependent tool traditions \[16].                             | Industry 4.0 smart factories \[4] / Modern technological ecosystems \[16]                 |
| 11        | Symbiotic Meta-Tool Networks — Human-AI co-evolution of tool systems \[20].                                          | Biocultural Networks — Co-evolving ecological and cultural tool traditions \[16].                       | Collaborative AI-human design platforms \[20] / Coral reef engineering symbiosis          |
| 12        | Metadevices — Self-organizing, cross-domain tool systems with emergent properties \[20].                             | Planetary-Scale Technological Ecosystems — Hypothetical global cultural-ecological tool networks \[16]. | Theoretical global AI mesh networks \[20] / Earth’s microbiome-material engineering       |

> **Note:** AGI emergence aligns with achieving Class 5 (Recursive Agents), where full autonomous, multi-level tool recursion is realized.

---

## 2 Problem Statement

Current frameworks measure intelligence by isolated outcomes: task completion, adaptation, or communication. They typically ignore the process lineage and depth of instrumental recursion. As a result:

* Tool use is often treated as binary \[12].
* Hierarchical tool-making depth is rarely quantified \[13].
* Cumulative culture lacks structural metrics \[14]\[16].
* AI and robotics have no standard technical recursion benchmarks \[6]\[7].
* Education systems do not track layered abstraction skills \[19].
* No unified framework compares intelligence across biological and artificial domains \[6]\[15].

---

## 3 Proposed Solutions

ToolDepth addresses these gaps via:

1. **Recursive Instrumental Index (RII):** Quantifies the maximum tool-production chain length \[4].
2. **Tool Ancestry Graphs:** Visualize dependencies among tools over time \[15].
3. **Cross-Domain Benchmarks:** Standardized tests for recursive tool-making across species and AI \[13].
4. **Cognitive Correlates:** Align RII scores with problem-solving and foresight metrics \[17]\[19].
5. **Machine Classification:** Stratify artificial systems by recursive design autonomy \[4]\[6].

### 3.1 Recursive Instrumental Index (RII)

The Recursive Instrumental Index (RII) is the core metric of ToolDepth. It represents the longest sequence of tool-making steps—each tool enabling the production of the next—within a given context. Key features:

* **Depth Measurement:** RII is an integer value equal to the number of edges in the longest path of the tool dependency graph.
* **Weighting Factors:** Optional weightings can adjust for cognitive load (e.g., complexity of design), material difficulty, or time investment.
* **Normalization:** RII scores may be normalized by domain-specific maxima to facilitate cross-system comparisons.
* **Computation:** Extracted from directed acyclic graphs (DAGs) using depth-first search or dynamic programming algorithms, ensuring efficient computation even for large graphs.

By quantifying depth rather than mere presence of tool use, RII captures the recursive sophistication of both biological behaviors and AI-driven processes.

---

## 4 Core Principles

* **Recursive Depth:** Intelligence correlates with tool ancestry length \[4].
* **Minimal Sufficiency:** Only necessary toolchain steps are counted \[14].
* **Causal Traceability:** Each tool’s creation is linked to its precursor \[15].
* **Cross-Domain Neutrality:** Uniform applicability to animals, humans, and machines \[12]\[13].
* **Cultural and Synthetic Accrual:** Includes intergenerational and system-generated tool lineage \[16]\[18].

---

## 5 Comparative Analysis

ToolDepth offers a transformative perspective on intelligence metrics by quantifying the **recursive depth** of tool-making processes. This depth-based approach surpasses traditional models in several critical dimensions:

1. **Precision Measurement:**

   * *Legacy:* Tool use is often recorded as a simple yes/no variable or coarse performance metric.
   * *ToolDepth:* Provides an integer-valued Recursive Instrumental Index (RII), capturing the exact number of sequential tool-creation steps.

2. **Unified Cross-Domain Benchmarking:**

   * *Legacy:* Separate assessment frameworks for biological cognition and AI capabilities, hindering direct comparison.
   * *ToolDepth:* Applies the same depth-based scale to animals, humans, and machines, enabling a coherent, cross-domain intelligence spectrum.

3. **Process Lineage Transparency:**

   * *Legacy:* Black-box or outcome-based evaluations that obscure the underlying mechanisms.
   * *ToolDepth:* Leverages directed dependency graphs to trace each tool’s origin and role, ensuring full transparency and auditability.

4. **Temporal and Evolutionary Context:**

   * *Legacy:* Static snapshots of performance lacking temporal resolution.
   * *ToolDepth:* Maps RII values onto evolutionary timelines or AI development cycles, revealing progression patterns and milestones.

5. **AGI Development Metrics:**

   * *Legacy:* No explicit metric for emergent general intelligence.
   * *ToolDepth:* Uses RII anomaly detection to flag AI systems that surpass human benchmarks in recursive depth, serving as an indicator of AGI-like capabilities.

| **Aspect**           | **Legacy Models**                   | **ToolDepth**                                                       |
| -------------------- | ----------------------------------- | ------------------------------------------------------------------- |
| Measurement Scale    | Binary or scalar performance scores | Integer Recursive Instrumental Index (RII)                          |
| Domain Applicability | Domain-specific (biology vs. AI)    | Unified cross-domain framework                                      |
| Transparency         | Black-box, outcome-based            | Tool ancestry graphs with causal traceability                       |
| Temporal Analysis    | Absent or limited                   | Longitudinal RII trends aligned with historical or development data |
| AGI Signal Detection | Undefined                           | RII threshold alerts for anomalous recursive complexity             |

By centering on recursive tool-making depth, ToolDepth establishes a **scientifically rigorous**, **quantitative**, and **interdisciplinary** foundation—essential for advancing comparative cognition research and guiding AGI development strategies.

## 6 Architecture Overview

The Architecture Overview details the computational and data components underpinning ToolDepth, ensuring reproducibility and scalability across domains.

### 6.1 ToolDepth Pipeline

1. **Data Ingestion:** Collect observational and experimental data on tool usage, manufacturing logs, archaeological records, and AI system architectures.
2. **Dependency Extraction:** Parse raw data to identify tool components, usage sequences, and inter-tool relationships using NLP and graph algorithms to build preliminary dependency graphs.
3. **Graph Construction:** Generate directed acyclic graphs (DAGs) representing each tool-production chain. Nodes represent tools or subtools; edges denote "built-with" relationships.
4. **Recursive Scoring:** Apply the RII algorithm to each DAG to compute metrics such as maximum depth, mean depth, and branching factor, incorporating weightings for cognitive load and material complexity.
5. **Metadata Enrichment:** Tag nodes and edges with metadata (domain, material, cognitive effort, temporal context) to support cross-domain queries and longitudinal studies.
6. **Storage and Versioning:** Store graphs and metrics in a scalable graph database with version control for iterative updates, enabling rollback and comparative analysis over time.

### 6.2 Depth Index Engine

* **Input Interface:** Accepts dependency graphs and time-stamped metadata.
* **Computation Core:** Utilizes optimized graph traversal algorithms and dynamic programming to calculate:

  * **Max Recursive Depth:** Longest path length in a graph.
  * **Average Depth:** Mean path length across all root-to-leaf paths.
  * **Branching Complexity:** Average out-degree and subgraph complexity metrics.
* **API Layer:** Exposes RESTful endpoints for querying individual RII scores, batch computations, and comparative analyses.
* **Scalability:** Supports distributed computation across clusters, leveraging parallel graph processing frameworks (e.g., Apache Giraph, GraphX).

### 6.3 Comparative Dashboard

* **User Interface:** Web-based dashboard built with React and d3.js for interactive visualization of tool ancestries and RII metrics.
* **Visualization Modules:**

  * **Depth Heatmaps:** Display distribution of RII scores across species or system classes.
  * **Lineage Trees:** Interactive DAG views with zoom, filter, and highlight capabilities.
  * **Temporal Trends:** Time-series plots tracking evolution of RII over historical periods or AI model generations.
* **Filters and Export:** Enable filtering by domain, time period, or class, with options to export visualizations and raw metrics in CSV or JSON formats.
* **Collaboration Features:** Annotative layers for expert commentary, shareable links, and versioned snapshots for reproducible research.

---

## 7 Use Cases

ToolDepth's unified framework enables diverse applications across research, education, and industry:

1. **Evolutionary Anthropology:** Quantitatively measure cognitive leaps in early hominins by comparing archaeological lithic RII scores against extant primate tool use benchmarks.
2. **Animal Cognition Studies:** Standardize assessments of corvids, primates, and marine mammals by applying consistent recursive depth metrics to field and laboratory observations.
3. **AI Benchmarking:** Evaluate artificial agents across development stages, ranking models by their ability to autonomously construct and refine toolchains in simulated environments.
4. **Machine Class Stratification:** Inform robotics and automation design by categorizing systems according to their recursive autonomy, guiding research investment and regulatory standards.
5. **STEM Education:** Integrate RII-based assessments in curricula, teaching students to document and analyze multi-step design processes using dependency graphs and depth scoring.
6. **Civilizational Complexity Analysis:** Map technological evolution by tracking RII trends across historical periods, correlating tool depth with socio-economic indicators.
7. **Design Thinking Workshops:** Use ancestry graphs to visualize project dependencies, fostering collaborative problem-solving and innovation workflow optimization.
8. **Robotics Development:** Program robots with recursive assembly behaviors, enabling them to plan and execute multi-stage manufacturing tasks based on depth-driven algorithms.

---

## 8 Future Exploration

To extend ToolDepth’s impact, future work can pursue:

* **Integration with Embodied AI:** Embed RII algorithms into autonomous agents capable of physical tool interaction, bridging simulated and real-world recursive tool-making.
* **Temporal Evolution Visualizations:** Develop interactive timelines illustrating how RII scores have changed over human history and across AI model generations.
* **Cultural vs. Synthetic Contributions:** Disentangle the roles of human teaching, cultural transmission, and autonomous learning in building cumulative tool depth.
* **Educational Toolkits:** Create open-source platforms allowing students and researchers to annotate tool dependencies and compute RII directly from experiment logs or CAD files.
* **Cross-Cultural Studies:** Compare RII across diverse societies to investigate how environmental and cultural factors influence recursive tool-making practices.
* **AGI Detection Metrics:** Establish RII thresholds and anomaly detection in real-time systems to signal emergent AGI-like behaviors based on unprecedented recursive depth.
* **Ecosystem-Level Modeling:** Simulate co-evolutionary scenarios where human, animal, and artificial agents interact in shared environments, tracking RII dynamics across species and systems.

---

## 9 References

1. Figurelli, R. (2025). *Wisdom Kernel: What if a system for reflective, ethical computation?*. [https://github.com/rfigurelli/wisdom-native-operating-systems](https://github.com/rfigurelli/wisdom-native-operating-systems)
2. Figurelli, R. (2025). *Wisdom Kernel for Self-Modifying Systems.* [https://github.com/rfigurelli/Wisdom-Kernel-for-Self-Modifying-Systems](https://github.com/rfigurelli/Wisdom-Kernel-for-Self-Modifying-Systems)
3. Figurelli, R. (2025). *Conscious Model Swarms.* [https://github.com/rfigurelli/Conscious-Model-Swarms](https://github.com/rfigurelli/Conscious-Model-Swarms)
4. Figurelli, R. (2025). *Evolving Language Models Toward Wisdom.* [https://github.com/rfigurelli/Evolving-Language-Models-Toward-Wisdom](https://github.com/rfigurelli/Evolving-Language-Models-Toward-Wisdom)
5. Figurelli, R. (2025). *Sentient by Design.* [https://github.com/rfigurelli/Sentient-by-Design](https://github.com/rfigurelli/Sentient-by-Design)
6. Figurelli, R. (2025). *From Darwin to AI Agency.* [https://github.com/rfigurelli/Darwin-to-AI-Agency](https://github.com/rfigurelli/Darwin-to-AI-Agency)
7. Figurelli, R. (2025). *From Darwin to Design.* [https://github.com/rfigurelli/Darwin-to-Design](https://github.com/rfigurelli/Darwin-to-Design)
8. Figurelli, R. (2025). *VALIA: Value Assessment Layer.* [https://github.com/rfigurelli/VALIA](https://github.com/rfigurelli/VALIA)
9. Figurelli, R. (2025). *PromptDepth: A Framework for Evaluating Prompt Engineering.* [https://github.com/rfigurelli/promptdepth](https://github.com/rfigurelli/promptdepth)
10. Figurelli, R. (2025). *PromptCode: Tool Classification Structure.* [https://github.com/rfigurelli/promptcode](https://github.com/rfigurelli/promptcode)
11. Figurelli, R. (2023). *Recursividade Criativa.* [https://github.com/rfigurelli/recursividade-criativa](https://github.com/rfigurelli/recursividade-criativa)
12. Goodall, J. (1986). *The Chimpanzees of Gombe*. Harvard University Press. [https://www.hup.harvard.edu/catalog.php?isbn=9780674116498](https://www.hup.harvard.edu/catalog.php?isbn=9780674116498)
13. Hunt, G. R., & Gray, R. D. (2003). *Diversification and cumulative evolution in New Caledonian crow tool manufacture*. PNAS, 100(11), 6461-6466. [https://www.pnas.org/content/100/11/6461](https://www.pnas.org/content/100/11/6461)
14. Mithen, S. (1996). *The Prehistory of the Mind*. Thames & Hudson. [https://thamesandhudson.com/the-prehistory-of-the-mind-9780500280434](https://thamesandhudson.com/the-prehistory-of-the-mind-9780500280434)
15. Clark, A. (2003). *Natural-Born Cyborgs*. Oxford University Press. [https://global.oup.com/academic/product/natural-born-cyborgs-9780195177510](https://global.oup.com/academic/product/natural-born-cyborgs-9780195177510)
16. Tomasello, M. (1999). *The Cultural Origins of Human Cognition*. Harvard University Press. [https://www.hup.harvard.edu/catalog.php?isbn=9780674005822](https://www.hup.harvard.edu/catalog.php?isbn=9780674005822)
17. Simondon, G. (1958). *Du mode d'existence des objets techniques*. Aubier. [https://fr.wikipedia.org/wiki/Du\_mode\_d%27existence\_des\_objets\_techniques](https://fr.wikipedia.org/wiki/Du_mode_d%27existence_des_objets_techniques)
18. Turing, A. M. (1950). *Computing Machinery and Intelligence*. Mind, 59(236), 433-460. [https://academic.oup.com/mind/article/LIX/236/433/986238](https://academic.oup.com/mind/article/LIX/236/433/986238)
19. Piaget, J. (1952). *The Origins of Intelligence in Children*. International Universities Press. [https://archive.org/details/originsofintelli00piag](https://archive.org/details/originsofintelli00piag)
20. Vygotsky, L. S. (1978). *Mind in Society*. Harvard University Press. [https://www.hup.harvard.edu/catalog.php?isbn=9780674576292](https://www.hup.harvard.edu/catalog.php?isbn=9780674576292)

---

## 10 License

Creative Commons Attribution 4.0 International (CC BY 4.0)
© 2025 Rogério Figurelli. This framework is provided "as is" without warranty. You are free to share and adapt under the terms of CC BY 4.0.
