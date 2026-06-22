# Shashank Rana
[shashankrana108@outlook.com](mailto:shashankrana108@outlook.com) | [linkedin](linkedin.com/in/shashank-rana-nw) | 9811827287 | Bengaluru, India

## About Me
I am Shashank. Systems, efficiency and scale excite me, in that order.
- Software Engineer with operational expertise in high-throughput, low-latency distributed systems.
- Passionate about making systems go faster with less, and making systems fit perfectly with each other.
- Currently, I am working at **Google Search** in the [RankEmbed](https://www.justice.gov/atr/media/1398866/dl), where I am helping RankEmbed scale through growing pains as we strive to serve both the growing AI traffic and an ever-larger share of search traffic.
- I am always looking to work at low-level systems engineering problems where I can squeeze the last bit of performance out of hardware.
- I write performant and well factored code; and have delivered features with ownership.

## Academic Details

### BITS Pilani Goa Campus (2025)
- B.E. (Hons.) Computer Science
- **CGPA:** 9.17/10.0

## Research Experience

### Data, Systems & High Performance Computing (DaSH) Lab

_Undergrad Researcher, BITS Goa (Project FLOps)_ | _03/2024 – 01/2025_

- Investigated different InfraDrift contributors in FL, in collaboration with [Prof. Arnab Paul](https://arnab.dashlab.in).
- Proposed strategies to counter them in [our publication](https://www.computer.org/csdl/proceedings-article/hipcw/2024/091100a171/24MFmedlM3u).
- Designed and managed a heterogeneous FL testbed consisting of 13 nodes.
- Nodes ranged in compute from Nvidia Orin NX to Raspi 400.
- Designed and orchestrated experiments simulating real FL challenges: Data skew, straggler clients, and network heterogeneity.

## Publications

*   **[Understanding Infrastructure Drift in Federated Learning Systems](https://www.computer.org/csdl/proceedings-article/hipcw/2024/091100a171/24MFmedlM3u)** | _HiPC'24_

    **Shashank Rana**, Vimarsh Shah, Aishwarya Jaishankar, Arnab K Paul
* **[Hardware Analysis for Low-Cost Wearable ECG Monitoring and Analysis System](https://link.springer.com/chapter/10.1007/978-3-031-95571-6_7)** | _ICWH 24_

    **Shashank Rana**, Aditya Handur-Kulkarni, Akhil Binu, Shubhangi Gawali, Neena Goveas

## Work Experience

### Google

_Software Engineer_ | _07/2025 – Present_ | _Bengaluru_

- Member of the [**RankEmbed** team](https://www.justice.gov/atr/media/1398866/dl), owning the system for vector embedding-based retrieval for Search; it is world's largest such system, searching **XXX Bi** documents at **XX Mi** QPS, at **X ms** 95p latency. 
-   **Automated RankEmbed's eval backend refreshes** : Designed and implemented an agentic pipeline to automate backend refreshes, reducing human toil from **2 SWE days** to **4 hours** and minimizing error.
-   **API Migration**: Drove a P0 architectural migration of critical RankEmbed clients (Search, AI Grounding, etc) to a unified API, migrating **X M QPS** worth of clients with **XX M+ QPS** in the pipeline.
    - This involved writing performant code in some of the most complex and hottest critical paths in Google Search, extensively testing and profiling changes to eke out the last ms of latency, while ensuring complete production stability.
    - Transitioned clients from using legacy raw cosine similarity scores to stable percentile conversions offered by the new API, effectively decoupling downstream clients from ML model refreshes.
    - Coordinated with the latency team to minimize migration overhead.
    - **Planned and implemented** a strategy to reduce additional latency of a major migration from **0.4ms to 0.14ms** by breaking the migration into multiple parts.
    - Implemented libraries to enable clients to reconstruct the new API's percentiles to raw scores locally, preventing massive network payload bloat.
- Engineered and deployed a plan to decouple RankEmbed's backend routing from binary rollouts using Google's internal datapush tools.
    - Enabled real-time updates to routing, significantly improving system agility and reducing reaction time for outages from **XX hrs to X mins**.

### Harness.io

_SWE Intern_ | _01/2025 – 06/2025_ | _Bengaluru_

- Worked on AI Test Automation agent.
- Led migration of long-running tasks from self-managed/self-scaled (EKS) cluster to serverless (AWS Batch).
- Reduced scale-up time from **XX mins to X mins** and enabled infinite scaling.
- Delivered end-to-end features: engineered peripheral services for managing serverless jobs, including a scheduler, sentinel, and validator.

### Google

_MLE Mentee_ | _10/2023 – 01/2024_

Participated in a 10-week program focusing on ML Engineering projects.

- Investigated abuse patterns across multiple platforms and aimed to build **resilient cross-platform models** for universal abuse detection. Developed and implemented robust pipelines, **addressing data skew** and managing varied features across platforms.
- Achieved **F1 scores over 0.76** in cross platform tasks, and uncovered how abuse patterns carry across different platforms. [Slides](https://docs.google.com/presentation/d/1jZHp-kw42Hf16lbdKuX4akz2lYfpXBkiCx5Q74aIQaY/edit?usp=drive_link).

## Courses

Intro to DB systems (**CMU DB** - on YT), Data Storage Technology and Networks, Computer Networks, Operating Systems, Database Systems, Compilers

## Technical Proficiency

* **Google Specific:** pprof, Hg/git, anti-gravity SDK (power-user), automon (graphana)
* **Languages:** C++, Python, Java/Kotlin, Picolo, GCL
* **Others:** SQL, DBs, Sockets programming, Raspberry Pi/dev boards, Android development, Git, Angular


## Accomplishments and Stats

* **Stats** (Time Period: 11 Months):
    * Delta: **44k**
    * CLs submitted: **133**
    * Bugs closed: **134**

* **Won JPMC Code for Good:** Won the 24-hour JPMC Code for Good Hackathon, which saw participation from over 79 shortlisted teams from across the country.

## Teaching

### Database Systems
_07/2024 – 11/2024_

### Software Dev for Android

_01/2024 – 06/2024_

- Secured academic integrity by setting up a pipeline to run MOSS for labs.


## Projects

### HRMAA: Heart Health Monitoring and Analysis

_08/2022 – 05/2024_

- Developed a Bluetooth and TCP/IP based communication module for portable ECG sensors, reducing packet loss from **15% to <1%** and achieving a **stable 10ms real-time latency**.
- Was the hardware lead, developed a lean and portable prototype. Analysis was [published here](https://www.computer.org/csdl/proceedings-article/hipcw/2024/091100a171/24MFmedlM3u).

### BITS TAlloc: The TA allocation system of BITS Goa

_08/2024 – 05/2025_

- **Architected automated allocation systems:** Developed a customized Gale-Shapley **Stable Marriage algorithm** to automate TA and Faculty assignments, reducing manual processing time from **one week to 6 seconds.**
- Successfully allocated **173 TAs to 30 courses** and **29 faculty members to 27 courses** with a **98.2%** success rate, ensuring **87.3%** of students received their top preference.
- **Engineered end-to-end data pipelines** for ingestion and interfaced directly with the university’s SQL database to handle complex edge cases and real-time record synchronization.

