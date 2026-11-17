# Awesome Embodied Perception

Companion to **A Survey of Embodied Perception across Modalities, Time, and Agents**.

Shulan Ruan, Zhibo Zhang, Rongwei Wang, Xuchen Shen, Huijie Liu, Yu Liu, and You He

How can an agent recover what a single sensor, a single instant, or a single viewpoint misses? This survey follows those three questions across road vehicles, robots, aerial platforms, and surface vessels. It also examines how multimodal language models use sensory evidence for scene interpretation and spatial reasoning.

[All 150 references](REFERENCES.md) · [Browse by chapter](CHAPTERS.md) · [Figure 2 method index](METHODS.md) · [15 datasets](DATASETS.md) · [Reference CSV](references.csv)

## Explore the methods

| Topic | Where to start | Example |
| --- | --- | --- |
| Across modalities | [Point, voxel, region, and multi-level fusion](CHAPTERS.md#sec-3) | [TransFusion](REFERENCES.md#ref-040) uses LiDAR-guided queries to select image features for 3D detection. |
| Across time | [Object, scene, and object–scene representations](CHAPTERS.md#sec-4) | [ConceptGraphs](REFERENCES.md#ref-041) associates observations across views to build a 3D scene graph. |
| Across agents | [Collaborative fusion and communication](CHAPTERS.md#sec-5) | [Where2comm](REFERENCES.md#ref-091) uses spatial confidence maps to choose which spatial features to transmit. |
| Language and perception | [Vision–language models and other sensor inputs](CHAPTERS.md#sec-6) | [Talk2BEV](REFERENCES.md#ref-103) connects bird’s-eye-view representations with language. |

## Browse by chapter

| Section | Focus |
| --- | --- |
| [1. Introduction](CHAPTERS.md#sec-1) | Scope and prior surveys |
| [2. Background](CHAPTERS.md#sec-2) | Platforms, sensor data, datasets, and perception tasks |
| [3. Multi-modal Fusion Methods](CHAPTERS.md#sec-3) | Fusion at point, voxel, region, and multiple levels |
| [4. Multi-time Fusion Methods](CHAPTERS.md#sec-4) | Object and scene representations over time |
| [5. Multi-agent Fusion Methods](CHAPTERS.md#sec-5) | Shared observations and bandwidth-aware communication |
| [6. LLM-Based Multi-Sensor Fusion](CHAPTERS.md#sec-6) | Semantic and geometric evidence for scene reasoning |
| [7. Open Challenges and Future Opportunities](CHAPTERS.md#sec-7) | Data generation, cross-platform evaluation, memory, uncertainty, collaboration, and active perception |
| [8. Conclusion](CHAPTERS.md#sec-8) | Synthesis of the survey |

## Datasets

The [dataset table](DATASETS.md) links to the official resources and compares sensor streams, operating environments, and dataset scale. It includes road-driving datasets such as nuScenes, robot and aerial datasets such as M3ED, and the water-surface dataset WaterScenes.

## Edition and corrections

Reference numbers follow the 17 November 2026 manuscript. Figure 2 groups 93 of the 150 works into 11 method categories. Each entry in the full bibliography links back to the text or the figure where it appears.

For a correction or an author-released implementation, open an issue with the reference number and the source link.
