# llmops-SMS-appendix
Exploring Large Language Model Operations (LLMOps) and Related Challenges in Production Environments: A Systematic Mapping Study

## Appendix A: Quality Assessment Template for Included Studies

**Table 13: Quality Assessment Template for Included Studies**

| QA ID | Target Criterion | Justification (Why this matters) | LOW Risk (High Quality) [Score: 1] | HIGH Risk (Low Quality) [Score: 0] | UNCLEAR (Risk) [Score: 0.5] |
|---|---|---|---|---|---|
| QA1 | Is the operational context clearly defined (e.g., production scale, model size)? | Ensures the study is relevant to real-world "Production Environments" rather than just academic toy examples. | The study explicitly details the production environment, scale, infrastructure, and specific models used. | The study uses purely theoretical scenarios, toy datasets, or local execution with no mention of production scale. | The study mentions a production environment but lacks specific details on the actual scale, constraints, or models used. |
| QA2 | Is the proposed LLMOps framework, architecture, or tool adequately described? | Necessary to accurately map, extract, and compare architectures to answer RQ2 and RQ3. | Comprehensive architectural details, workflows, or code repositories are provided, making the system clear. | The framework is only mentioned conceptually or at a marketing level without technical or architectural depth. | The framework is described at a high level, but specific technical integrations or lifecycle stages are vague. |
| QA3 | Are the research findings based on empirical evidence? | Ensures the study's conclusions are grounded in actual data, real-world deployments, or structured experiments rather than purely hypothetical scenarios. | Findings are explicitly supported by real-world deployments, quantitative experiments, case studies, or structured qualitative data. | Findings are purely speculative, assumed, or based solely on the authors' opinions without any supporting data. | It is difficult to distinguish whether the reported findings were actually observed in practice or merely hypothesized, or the data methodology is vague. |
| QA4 | Does the study have relevance with any research questions? | Reduces bias by prioritizing papers with the most actionable data for the research questions. | Targets at least one of the research questions directly and offers significant actionable data. | Meets inclusion criteria but offers minimal actionable data for the RQs. | Relevant to the broader field of LLMOps but is not the core focus of a specific RQ. |
| QA5 | Are the threats of validity of the research described? | Evaluates the authors' transparency regarding the limitations, potential biases, and generalizability of their study. | Threats to validity along with mitigation actions are discussed for the findings. | There is no discussion of threats to validity of the study findings. | Threats to validity of the findings of the study are discussed without mitigation actions. |
| QA6 | Is the aim of the study discussed? | Ensures the paper has a clear purpose and research objective, providing necessary context for why the study was conducted. | The aim of the study is explicitly discussed. | There are no mentions of the study's aim. | The aim can be inferred but is not explicitly stated. |

## Appendix B: Data Extraction Properties for LLMOps SLR

**Table 14: Data Extraction Properties for LLMOps SLR**

| ID | Target RQ | Property Name | Description / Focus Area |
|---|---|---|---|
| DP1 | NA | Publication Identifier | Unique study identifier for tracking and cross-referencing throughout the review. |
| DP2 | NA | Publication Year | Publication year (2017–2026) used to map evolution of LLMOps literature over time. |
| DP3 | NA | Geography | Explains the Authors' affiliations by country, and will be used to map the authors' affiliations geographically. |
| DP4 | NA | Publication Source | Venue type (journal/conference/workshop) for assessing publication context. |
| DP5 | NA | Research Method | Reported empirical method (e.g., case study, survey, experiment). |
| DP6 | NA | Artifact Readiness | Readiness level of contribution: theoretical artifact, prototype, or production implementation. |
| DP7 | RQ1 | LLMOps Definition | Extracted definitions and direct terminology statements for conceptual synthesis. |
| DP8 | RQ1 | Scope | Statements distinguishing LLMOps from other operational paradigms. |
| DP9 | RQ2 | Lifecycle Stages | Coverage of design, development, and operations phases in the LLM lifecycle. |
| DP10 | RQ2 | Frameworks and Architecture | Architectural or pipeline patterns (e.g., RAG, agentic workflows). |
| DP11 | RQ2 | Platforms and Tools | Tooling and platform stack used in implementation (e.g., LangChain, Pinecone). |
| DP12 | RQ3.1 | Technical Challenges | Implementation and operational technical challenges (e.g., hallucination control). |
| DP13 | RQ3.2 | Regulatory Challenges | Compliance, governance, and policy constraints (e.g., GDPR-related requirements). |
| DP14 | NA | Performance Metrics | Evaluation indicators used by studies (e.g., perplexity, latency, cost). |
| DP15 | NA | Aim of the study | Aim of the study in context of LLMOps. Captures the core research objective to understand the primary focus and intended contribution of the paper (e.g., "To propose a scalable framework for RAG deployment"). |
| DP16 | NA | Abstract | Direction, goal and context of LLMOps. Captures the direction and goal of the study and how it contributes to the research. Example abstract quote from the paper. |

## Appendix C: Selected Primary Studies in the Systematic Literature Review

**Table 15: Selected Primary Studies in the Systematic Literature Review**

| Paper ID | Title | Author | Verified Link / DOI | Publication Source (Journal / Conference) |
|---|---|---|---|---|
| P1 | Playlist Search Reinvented: LLMs Behind the Curtain | Geetha S. Aluri, Siddharth Sharma, Tarun Sharma, and Joaquin Delgado | https://dl.acm.org/doi/10.1145/3640457.3688047 | Conference |
| P2 | Securing Rag: A Risk Assessment and Mitigation Framework | Lukas Ammann, Sara Ott, Christoph R. Landolt, and Marco P. Lehmann | https://arxiv.org/abs/2505.08728 | Conference |
| P3 | ChainForge: A Visual Toolkit for Prompt Engineering and LLM Hypothesis Testing | Ian Arawjo, Chelse Swoopes, Priyan Vaithilingam, Martin Wattenberg, Elena L. Glassman | https://arxiv.org/abs/2309.09128 | Conference |
| P4 | Secure and Scalable LLM-Based Recommendation Systems: An MLOps and Security by Design | Adi Saputra, Erma Suryani (and Nur Aini Rakhmawati) | https://ieeexplore.ieee.org/document/10791207 | Conference |
| P5 | Integration of web scraping, fine-tuning, and data enrichment in a continuous monitoring context via large language model operations | Anas Bodor, Meriem Hnida, and Najima Daoudi | https://doi.org/10.11591/ijece.v15i1.pp1027-1037 | Journal |
| P6 | Benchmarking Techniques for Real-Time Evaluation of LLMs In Production Systems | Reena Chandra, Rishab Bansal, and Karan Lulla | https://doi.org/10.52088/ijesty.v5i3.955 | Journal |
| P7 | Prompt Sapper: A LLM-Empowered Production Tool for Building AI Chains | Yu Cheng, Jieshan Chen, Qing Huang, Zhenchang Xing, Sherry Xu, Qinghua Lu | https://dl.acm.org/doi/10.1145/3638247 | Journal |
| P8 | Design Principles and Guidelines for LLM Observability: Insights from Developers | Xin Chen, Yan Feng Li, and Xiaoming Wang | https://dl.acm.org/doi/10.1145/3706599.3719914 | Conference |
| P9 | Establishing a Robust LLMOps Framework for Intelligent Automation: Strategies and Best Practices | Dasaprakash Krishnamurthy and Vinod Neelanath | https://ieeexplore.ieee.org/document/10961869 | Conference |
| P10 | Responsible Engineering of Information Systems Based on Generative Artificial Intelligence: An Action Design Research Study at a German Premium Car Manufacturer | Dominik Fetzer, Henner Gimpel, Oliver Meindl, and Jan Strickmann | https://link.springer.com/article/10.1007/s12599-025-00950-6 | Journal |
| P11 | AU-RAG: Agent-based Universal Retrieval Augmented Generation | Jisoo Jang, Wen-Syan Li | https://dl.acm.org/doi/10.1145/3673791.3698416 | Conference |
| P12 | Navigating MLOps: Insights into Maturity, Lifecycle, Tools, and Careers | Jasper Stone, Raj Patel, Farbod Ghiasi, Sudip Mittal, and Shahram Rahimi | https://ieeexplore.ieee.org/document/11050687 | Conference |
| P13 | Real-Time ML and LLM Optimization: Orchestrating Scalable Workflows in Distributed Commerce Environments | Karan Alang, Sana Zia Hassan, Venugopal Katkam, Shazia Hassan | https://ieeexplore.ieee.org/document/11158822 | Conference |
| P14 | Towards the Versioning of LLM-Agent-Based Software | Chengwei Liu, Lyuye Zhang, Xiufeng Xu, Wenbo Guo, and Yang Liu | https://dl.acm.org/doi/10.1145/3696630.3728714 | Conference |
| P15 | Powering Job Search at Scale: LLM-Enhanced Query Understanding in Job Matching Systems | Ping Liu, Jianqiang Shen, Qianqi Shen, Chunnan Yao, Kevin Kao, Dan Xu, Rajat Arora, Baofen Zheng, Caleb Johnson, Liangjie Hong, Jingwei Wu, and Wenjing Zhang | https://dl.acm.org/doi/10.1145/3746252.3760913 | Conference |
| P16 | LogLM: From Task-based to Instruction-based Automated Log Analysis | Yilun Liu, Yuhe Ji, Shimin Tao, Minggui He, Weibin Meng, Shenglin Zhang, Yongqian Sun, Yuming Xie, Boxing Chen, Hao Yang | https://ieeexplore.ieee.org/document/11121704 | Conference |
| P17 | LLMOps: Definitions, Framework and Best Practices | Megha Sinha, Sreekanth Menon, Ram Sagar | https://ieeexplore.ieee.org/document/10698359 | Conference |
| P18 | Beyond the Comfort Zone: Emerging Solutions to Overcome Challenges in Integrating LLMs into Software Products | Nadia Nahar, Christian Kästner, Jenna Butler, Chris Parnin, Thomas Zimmermann, Christian Bird | https://ieeexplore.ieee.org/document/11121725 | Conference |
| P19 | DataOps Meets LLMOps: Automating Cloud-Based AI Workflows from Data Ingestion to Prompt Optimization | Prasad Gadiraju, Srinivas Reddy Kosna, Kushal Shah, Santosh Kumar Vududala, Satya Manesh Veerapaneni, Anil Kumar Jonnalagadda | https://ieeexplore.ieee.org/document/11135202 | Conference |
| P20 | Enterprise LLMOps: Advancing Large Language Models Operations Practice | Richard Shan, Tony Shan | https://ieeexplore.ieee.org/document/10630923 | Conference |
| P21 | Green MLOps to Green GenOps: An Empirical Study of Energy Consumption in Discriminative and Generative AI Operations | Adrián Sánchez-Mompó, Ioannis Mavromatis, Peizheng Li, Konstantinos Katsaros, Aftab Khan | https://arxiv.org/abs/2503.23934 | Journal |
| P22 | Cloud-Native LLMOps Meets DataOps: A Unified Framework for High-Volume Analytical Systems | Shivareddy Devarapalli, Venumadhav Goud Vathsavai, Venugopal Katkam | https://ieeexplore.ieee.org/document/11158069 | Conference |
| P23 | Who Validates the Validators? Aligning LLM-Assisted Evaluation of LLM Outputs with Human Preferences | Shreya Shankar, J.D. Zamfirescu-Pereira, Björn Hartmann, Aditya G. Parameswaran, Ian Arawjo | https://arxiv.org/abs/2404.12272 | Conference |
| P24 | Challenges and Opportunities in Integrating LLMs into Continuous Integration/Continuous Deployment (CI/CD) Pipelines | Tianyi Chen (T. Chen) | https://ieeexplore.ieee.org/document/10581784 | Conference |
| P25 | CuLao - Constructing Utilities of Large Language Models in Resource-Constrained Environments | Hong-Linh Truong, Ngoc Nhu Trang Nguyen | https://dl.acm.org/doi/10.1145/3677525.3678648 | Conference |
| P26 | RAGVA: Engineering retrieval augmented generation-based virtual assistants in practice | Rui Yang, Michael Fu, Chakkrit Tantithamthavorn, Chetan Arora, Lisa Vandenhurk, Joey Chua | [https://arxiv.org/abs/2502.14930](https://doi.org/10.1016/j.jss.2025.112436) | Journal |
| P27 | LM-PACE: Confidence Estimation by Large Language Models for Effective Root Causing of Cloud Incidents | Shizhuo Zhang, Xuchao Zhang, Chetan Bansal, Pedro Las-Casas, Rodrigo Fonseca, Saravan Rajmohan | https://dl.acm.org/doi/10.1145/3663529.3663858 | Conference |
