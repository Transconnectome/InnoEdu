# Branch B2: AI-데이터 기반 연구 방법론 — Data Charting (P0)

**Scoping Review Phase**: P0 (Preliminary Charting)
**Branch**: B2 — AI and Data-Driven Research Methodology
**Sources**: S13-S22 (10 sources)
**Charting Date**: 2026-03-12
**Reviewer**: Claude Opus 4.6 (Automated)

---

## Source Charting

---

### [S13] Using Large Language Models in Behavioral Science Interventions: Promise & Risk

- **저자/기관**: Cameron A. Hecht, Desmond C. Ong, Margarett Clapper, Michaela Jones, Dorottya Demszky, Diyi Yang, Johannes C. Eichstaedt, Christopher J. Bryan, David S. Yeager (Stanford University, National University of Singapore, University of Texas at Austin)
- **연도**: 2025
- **출처**: Behavioral Science & Policy (SAGE), 11(1), 1-9
- **DOI/URL**: https://doi.org/10.1177/23794607251344698
- **소스 유형 / Tier**: Peer-reviewed journal article / Tier 2 (Established journal, applied policy focus)
- **Knowledge Tree 위치**: B2.1.1 (LLM Applications in Behavioral Science)
- **PCC 적합성**: Population(Y) — behavioral science researchers, intervention designers, beneficiaries / Concept(Y) — AI integration in behavioral interventions, risk-benefit framework / Context(Y) — Higher education research context, 2025
- **핵심 발견 (3-5개)**:
  1. LLMs can revolutionize behavioral science interventions (nudges, psychologically-wise interventions) by making them more personalized, scalable, and cost-effective
  2. Three-tier user framework proposed: (a) intervention designers, (b) intermediaries who interact with beneficiaries, (c) intended beneficiaries themselves — each tier carries escalating benefits and risks
  3. Risk-benefit gradient: potential benefits and risks are lowest when designers interact with LLMs, higher for intermediaries, and highest when beneficiaries interact directly
  4. LLMs enable personalization of language-based interventions at unprecedented scale, addressing a core limitation of traditional behavioral interventions
  5. Ethical safeguards must scale proportionally with the directness of beneficiary-LLM interaction
- **서울대 심리학과 적용 시사점**: 행동과학 개입 설계 교육에 LLM을 활용하는 체계적 프레임워크를 제공. '심리과학을 위한 인공지능' 과목에서 3단계 사용자 모델(설계자-중개자-수혜자)을 활용한 윤리적 AI 개입 설계 실습에 적용 가능. PBL 기반 수업에서 학생들이 직접 LLM 기반 행동 개입을 설계하고 위험-편익을 평가하는 프로젝트로 발전 가능
- **관련 소스 교차참조**: S14 (LLM assessment), S15 (perils/opportunities), S16 (clinical LLM evaluation), S18 (ethics framework)
- **품질 평가 (MMAT)**: Methodological quality — Moderate. Conceptual/theoretical paper with clear framework but limited empirical validation. Strength: multi-stakeholder risk model. Limitation: no direct experimental evidence from the proposed framework

---

### [S14] Large Language Models for Psychological Assessment: A Comprehensive Overview

- **저자/기관**: Jocelyn Brickman (Xavier University), Mehak Gupta (Southern Methodist University), Joshua R. Oltmanns (Washington University in St. Louis)
- **연도**: 2025
- **출처**: Advances in Methods and Practices in Psychological Science (AMPPS), Vol. 8
- **DOI/URL**: https://doi.org/10.1177/25152459251343582
- **소스 유형 / Tier**: Peer-reviewed methodological review article / Tier 1 (Top-tier APS methods journal)
- **Knowledge Tree 위치**: B2.1.1 (LLM Applications in Psychological Assessment)
- **PCC 적합성**: Population(Y) — psychological scientists, graduate/undergraduate researchers / Concept(Y) — AI/data integration in assessment methods, methodology education / Context(Y) — Higher education psychology programs, 2025
- **핵심 발견 (3-5개)**:
  1. LLMs provide unprecedented opportunity to supplement self-report measures with scalable behavioral assessment using natural language processing
  2. Comprehensive methodological pipeline described: language data collection, audio processing/transcription, text preprocessing, model selection, output evaluation
  3. Transformer-based LLM architecture represents significant advances over earlier NLP approaches for psychological construct measurement
  4. Continuous working example using Big Five/FFM personality trait assessment from interview language demonstrates practical implementation
  5. Includes coding-based tutorial with GitHub-hosted code examples, enabling direct pedagogical application in methods courses
- **서울대 심리학과 적용 시사점**: '심리데이터 분석 I' 및 '심리과학을 위한 인공지능' 과목의 핵심 교재로 활용 가능. GitHub 코딩 튜토리얼은 실습 기반 수업 설계에 즉시 적용 가능. Method 모듈 전반에 걸쳐 전통적 자기보고 측정을 LLM 기반 행동 평가로 보완하는 방법론 교육의 근거 제공. 학부생 연구 캡스톤에서 NLP 기반 심리 평가 프로젝트 지도에 활용 가능
- **관련 소스 교차참조**: S13 (LLM behavioral interventions), S15 (research applications), S17 (AI literacy), S19 (data analysis pedagogy)
- **품질 평가 (MMAT)**: High quality. Comprehensive methodological review in top-tier methods journal with reproducible code examples. Strength: practical implementation guidance with working code. Limitation: rapidly evolving field may require frequent updates

---

### [S15] Perils and Opportunities in Using Large Language Models in Psychological Research

- **저자/기관**: Suhaib Abdurahman, Mohammad Atari (Harvard), Farzan Karimi-Malekabadi, Mona J. Xue, Jackson Trager, Peter S. Park (MIT), Preni Golazizian, Ali Omrani, Morteza Dehghani (University of Southern California)
- **연도**: 2024
- **출처**: PNAS Nexus, 3(7), pgae245
- **DOI/URL**: https://doi.org/10.1093/pnasnexus/pgae245
- **소스 유형 / Tier**: Peer-reviewed empirical review / Tier 1 (PNAS Nexus — top-tier interdisciplinary journal)
- **Knowledge Tree 위치**: B2.1.4 (Ethical and Responsible AI Use in Psychology)
- **PCC 적합성**: Population(Y) — psychological researchers, educators / Concept(Y) — AI integration risks, research methodology, education implications / Context(Y) — Higher education research context, 2024
- **핵심 발견 (3-5개)**:
  1. "GPTology" warning: treating LLMs as universal solutions without acknowledging fundamental constraints poses significant risks to psychological science
  2. LLMs cannot replace human participants — GPT-3.5's response variance was 43-121 times smaller than human data in moral judgment domains; strong bias toward individualistic/WEIRD populations (142% increased agreement odds)
  3. LLMs are not universal text-analysis tools — zero-shot ChatGPT achieved F1=0.22 for moral language detection, substantially underperforming fine-tuned BERT (F1=0.48) and even dictionary-based LIWC (F1=0.27)
  4. Reproducibility crisis with proprietary models: closed-source architecture prevents mechanism inspection, model updates change performance inconsistently, prompt variations significantly alter results
  5. Three categories of LLM applications identified: inappropriate (replacing human participants), limited utility (zero-shot analysis without validation), promising with caution (fine-tuned applications with proper validation)
- **서울대 심리학과 적용 시사점**: AI 거버넌스 태스크포스의 정책 수립에 직접 참고 가능한 경험적 근거 제공. '심리과학을 위한 인공지능' 과목에서 LLM의 한계와 편향을 실증적으로 이해하는 핵심 교재. 학부생 연구에서 LLM 활용 시 반드시 준수해야 할 검증 프로토콜(fine-tuning vs. zero-shot, open-source vs. proprietary, WEIRD bias 점검) 수립의 근거. 연구윤리·IRB 교육에서 AI 연구방법론의 윤리적 한계를 다루는 사례 교재로 활용 가능
- **관련 소스 교차참조**: S13 (behavioral interventions), S14 (assessment), S16 (clinical evaluation), S18 (ethics), S20 (reproducibility crisis)
- **품질 평가 (MMAT)**: Very high quality. Empirical evidence across multiple domains with quantitative benchmarks. Strength: specific performance metrics and bias quantification. Limitation: rapidly evolving LLM capabilities may shift some findings

---

### [S16] Large Language Models Could Change the Future of Behavioral Healthcare: A Proposal for Responsible Development and Evaluation

- **저자/기관**: Elizabeth C. Stade, Shannon Wiltsey Stirman, Lyle H. Ungar, Cody L. Boland, H. Andrew Schwartz, David B. Yaden, Joao Sedoc, Robert J. DeRubeis, Robb Willer, Johannes C. Eichstaedt (Stanford University, University of Pennsylvania, University of Stony Brook)
- **연도**: 2024
- **출처**: npj Mental Health Research, 3(1), Article 12
- **DOI/URL**: https://doi.org/10.1038/s44184-024-00056-z
- **소스 유형 / Tier**: Peer-reviewed proposal/perspective article / Tier 1 (Nature Portfolio journal)
- **Knowledge Tree 위치**: B2.1.4 (Ethical and Responsible AI Use — Clinical Application)
- **PCC 적합성**: Population(Y) — clinical psychology trainees, researchers, educators / Concept(Y) — AI integration in clinical training, responsible development framework / Context(Y) — Higher education clinical psychology training, 2024
- **핵심 발견 (3-5개)**:
  1. LLMs hold immense potential to support, augment, or eventually automate psychotherapy, addressing insufficient mental healthcare system capacity
  2. Autonomous vehicle parallel: proposes staged integration framework for LLMs in psychotherapy (analogous to SAE Levels 0-5), from no automation to full autonomy
  3. Psychology as "uncommonly high stakes application domain for AI systems" — requiring more rigorous safeguards than other LLM applications
  4. Four pillars of responsible development: (a) centering clinical science, (b) robust interdisciplinary collaboration, (c) rigorous assessment and risk detection, (d) transparency and bias mitigation
  5. Vision for enabling "a new generation of studies of evidence-based interventions at scale" through responsible LLM integration
- **서울대 심리학과 적용 시사점**: 임상심리 교육에서 AI의 단계적 통합 모델을 제시하여 교과과정 개편의 로드맵으로 활용 가능. Behavior 모듈(임상·상담심리) 수업에서 LLM 기반 치료 보조 도구의 윤리적 개발·평가를 다루는 PBL 사례로 적합. AI 거버넌스 태스크포스에서 임상 영역 특화 AI 정책 수립 시 '자율주행 단계 모델'을 차용한 단계적 도입 전략 수립 가능. 학제간 협업(전산센터, 법무팀) 필요성에 대한 근거 제공
- **관련 소스 교차참조**: S13 (behavioral interventions), S15 (perils/opportunities), S18 (ethics framework), S17 (AI literacy)
- **품질 평가 (MMAT)**: High quality. Well-structured proposal in Nature Portfolio journal with clear framework. Strength: staged integration model with practical milestones. Limitation: proposal/perspective rather than empirical study; framework not yet empirically validated

---

### [S17] AI Literacy in Psychology (APA Position Paper)

- **저자/기관**: APA (American Psychological Association) — attributed to Mayes, R. et al.; aligned with APA Board of Educational Affairs and APA Advisory Committee on AI
- **연도**: 2023-2024 (APA policy development period)
- **출처**: APA Policy Statement / Position Paper — "Artificial Intelligence and the Field of Psychology" (August 2024 formal adoption); related APA guidelines and committee outputs from 2023
- **DOI/URL**: https://www.apa.org/about/policy/artificial-intelligence-psychology
- **소스 유형 / Tier**: Grey literature — professional association policy statement / Tier 2 (Established professional body, AACODS applicable)
- **Knowledge Tree 위치**: B2.1.2 (AI Literacy Frameworks for Psychology)
- **PCC 적합성**: Population(Y) — psychology educators, students, practitioners / Concept(Y) — AI literacy competency, curriculum integration, faculty development / Context(Y) — Psychology education programs globally, 2023-2024
- **핵심 발견 (3-5개)**:
  1. APA affirms psychology's vital role in three AI domains: (a) shaping AI's societal impact, (b) using AI to promote health and well-being, (c) addressing ethics and privacy related to AI
  2. AI literacy for psychologists encompasses understanding AI capabilities, limitations, ethical implications, and integration into research and practice
  3. Psychology's unique contribution: deep scientific understanding of human cognition, behavior, and emotions positions the field to shape safe and effective AI systems
  4. Education and training recommendations emphasize integrating AI competency across psychology curricula, not as standalone topic but embedded in existing coursework
  5. Ethical guidance framework for AI use in professional practice of health service psychology published alongside policy statement
- **서울대 심리학과 적용 시사점**: 심리학혁신위원회에서 교과 개편의 정당성을 뒷받침하는 국제 전문가 단체 정책 근거로 활용. APA의 3대 AI 역할 도메인을 BMBM 모듈에 매핑하여 각 모듈별 AI 역량 목표 설정 가능. '심리학 연구 입문' 과목에서 AI 리터러시 기초 교육의 프레임워크로 활용. AI Teaching Bootcamp(교수진)에서 APA 가이드라인 기반 교수법 개발의 근거. APA Guidelines 3.0과의 연계를 통해 국제 기준 부합 확인
- **관련 소스 교차참조**: S18 (APS ethics), S15 (research perils), S14 (assessment methods), S16 (clinical AI)
- **품질 평가 (AACODS)**: Authority — High (APA is the primary professional body for psychology). Accuracy — Moderate (policy statement rather than empirical research). Coverage — Broad (field-wide scope). Objectivity — Moderate (advocacy position). Date — Current (2024 formal adoption). Significance — High (sets professional standards). **Note**: The exact "Mayes et al. 2023" citation could not be independently verified as a standalone paper; the content aligns with the APA's 2024 policy statement and related 2023 committee outputs. The source may represent pre-publication committee work that was incorporated into the formal 2024 policy

---

### [S18] Responsible AI for Psychology: Ethics, Transparency, and Accountability (APS Task Force)

- **저자/기관**: Association for Psychological Science (APS) Task Force — exact author list not independently verified; aligned with APS publications on AI and Machine Learning in psychological science
- **연도**: 2023 (attributed)
- **출처**: Attributed to Perspectives on Psychological Science; closest verified match: APS AI and Machine Learning topic area publications and related APA policy frameworks
- **DOI/URL**: https://www.psychologicalscience.org/topics/artificial-intelligence (APS AI topic hub)
- **소스 유형 / Tier**: Grey literature — professional association position / Tier 2 (Established professional body)
- **Knowledge Tree 위치**: B2.1.4 (Ethical and Responsible AI Use in Psychology)
- **PCC 적합성**: Population(Y) — psychological scientists, educators / Concept(Y) — AI ethics framework, transparency, accountability in research / Context(Y) — Psychological science research and education, 2023
- **핵심 발견 (3-5개)**:
  1. Psychological science has a unique role at the interface of AI development, providing insights from human cognition, behavior, and social dynamics research
  2. Ethics framework emphasizes transparency in AI use across research pipeline: data collection, analysis, interpretation, and publication
  3. Accountability standards proposed for AI-assisted research: clear disclosure of AI tools used, validation of AI-generated outputs, and human oversight requirements
  4. AI and Machine Learning identified as cross-cutting theme in psychological science requiring integration across subdisciplines rather than siloed treatment
  5. Research at the AI-psychology interface (2018-2022 review) shows rapid growth in applications but uneven ethical framework adoption
- **서울대 심리학과 적용 시사점**: AI 거버넌스 태스크포스의 윤리 정책 수립에 핵심 참고 자료. 연구윤리·IRB 교육에서 AI 활용 연구의 투명성·책무성 기준으로 활용. 학부생 연구 캡스톤에서 AI 도구 사용 시 필수 공개 사항 및 검증 절차의 표준 설정. 심리학혁신위원회에서 AI 정책 의사결정 시 국제 학술단체 기준 참조. 졸업논문 3트랙 모두에서 AI 활용 연구의 윤리적 가이드라인으로 적용
- **관련 소스 교차참조**: S17 (APA AI literacy), S15 (perils/opportunities), S16 (clinical AI ethics), S20 (reproducibility)
- **품질 평가 (AACODS)**: Authority — High (APS is a leading scientific psychology organization). Accuracy — Moderate (position/policy rather than primary research). Coverage — Broad (field-wide ethical framework). Objectivity — Moderate (advocacy position). Date — Current (2023). Significance — High (shapes research ethics standards). **Note**: The specific publication "Responsible AI for Psychology: Ethics, Transparency, and Accountability" as a formal APS Task Force report in Perspectives on Psychological Science could not be independently verified with exact DOI. The content synthesized here draws from APS's publicly available AI and Machine Learning position materials and related published work. This requires P1 verification to confirm exact publication details or reclassify as composite grey literature source

---

### [S19] Teaching Statistics and Data Analysis with Python and R

- **저자/기관**: Mine Cetinkaya-Rundel (Duke University / Posit) & Johanna Hardin (Pomona College)
- **연도**: 2021-2023 (Publication cycle: textbook 1st ed. 2021, 2nd ed. 2023; related journal article 2022)
- **출처**: Primary: *Introduction to Modern Statistics* (IMS), 2nd Edition, OpenIntro (2023). Related journal article: "An Educator's Perspective of the Tidyverse," Technology Innovations in Statistics Education, 14(1), 2022. DOI: 10.5070/T514154352
- **DOI/URL**: https://openintro-ims.netlify.app/ (free online textbook, 2nd ed.); https://doi.org/10.5070/T514154352 (Tidyverse pedagogy article)
- **소스 유형 / Tier**: Open educational resource (textbook) + Peer-reviewed pedagogical article / Tier 2 (Established statistics education resource, widely adopted)
- **Knowledge Tree 위치**: B2.3.1 (Python/R-based Data Analysis Pedagogy) / B2.3.2 (Statistical Computing Education)
- **PCC 적합성**: Population(Y) — statistics/data science educators and undergraduate students / Concept(Y) — curriculum design for data analysis, computing integration in statistics education / Context(Y) — Higher education, 2021-2023
- **핵심 발견 (3-5개)**:
  1. Modern statistics education must integrate computing as a core component, not an add-on — emphasis on exploratory data analysis, simulation-based inference, and reproducible workflows
  2. Tidyverse ecosystem (R) provides pedagogically optimized framework: consistent syntax, human-readable code, and integrated visualization-to-modeling pipeline
  3. 32 interactive R tutorials accompany the textbook, enabling hands-on learning with immediate feedback — model for active-learning computational pedagogy
  4. Simulation-based inference (randomization and bootstrapping) presented before Central Limit Theorem approaches, reducing mathematical barriers to conceptual understanding
  5. Open-source, free access model demonstrates sustainable pedagogical resource development — textbook always free online, with affordable print options
- **서울대 심리학과 적용 시사점**: '심리데이터 분석 I' (2학년, 3학점) 과목의 교재 및 교수법 모델로 직접 활용 가능. R/tidyverse 기반 데이터 분석 커리큘럼을 심리학 데이터에 적용하는 구체적 사례 제공. Method 모듈 전반에 걸쳐 시뮬레이션 기반 추론 교수법 도입의 근거. 32개 대화형 튜토리얼 형식을 심리학 데이터셋으로 변환하여 AI 튜터 도입과 연계 가능. 오픈소스 교육자료 개발 모델을 학과 차원에서 채택 가능
- **관련 소스 교차참조**: S14 (LLM assessment coding tutorial), S20 (reproducibility — reproducible workflows), S22 (OSF — open science tools)
- **품질 평가 (AACODS for textbook / MMAT for article)**: Textbook — Authority: Very High (Cetinkaya-Rundel is a leading statistics educator, RStudio/Posit affiliation). Accuracy: High (peer-reviewed content, regularly updated). Coverage: Comprehensive (full introductory statistics curriculum). Date: Current (2nd ed. 2023). Significance: Very High (widely adopted open textbook). Journal article — Methodological quality: High (clear pedagogical framework with evidence-based rationale). **Note**: The exact title "Teaching Statistics and Data Analysis with Python and R" in JSDSE could not be verified as a single publication. The charted content represents Cetinkaya-Rundel & Hardin's most relevant and verified work on this topic. P1 should verify whether the intended source is IMS 2e or a different specific journal article

---

### [S20] Estimating the Reproducibility of Psychological Science

- **저자/기관**: Open Science Collaboration (270+ contributing researchers); Lead: Brian A. Nosek (University of Virginia / Center for Open Science)
- **연도**: 2015
- **출처**: Science, 349(6251), aac4716
- **DOI/URL**: https://doi.org/10.1126/science.aac4716
- **소스 유형 / Tier**: Peer-reviewed empirical study / Tier 1 (Science — highest-tier general science journal)
- **Knowledge Tree 위치**: B2.2.4 (Reproducibility and Open Science)
- **PCC 적합성**: Population(Y) — psychological science researchers, students / Concept(Y) — research methodology, reproducibility, scientific rigor / Context(Y) — Higher education psychology research, 2015 (foundational, within extended timeframe)
- **핵심 발견 (3-5개)**:
  1. Only 36% of 100 replicated psychology studies achieved statistically significant results, compared to 97% of originals — establishing the scale of the reproducibility problem
  2. Replication effect sizes were approximately half the magnitude of original effects, representing substantial decline in observed phenomena
  3. 47% of original effect sizes fell within the 95% confidence interval of replication effect sizes; 39% were subjectively rated as successful replications
  4. Replication success better predicted by strength of original evidence (effect size, p-value) than by characteristics of either original or replication team
  5. Cognitive psychology topics showed stronger reproducibility than social psychology topics, revealing subdiscipline-specific vulnerability patterns
- **서울대 심리학과 적용 시사점**: 교과과정 개편의 핵심 동기 중 하나인 연구 방법론 강화의 근본 근거. '심리학 연구 입문' (1학년) 과목에서 재현성 위기의 규모를 학생들에게 소개하는 필수 교재. Method 모듈 전반에 걸쳐 사전등록, 검정력 분석, 효과크기 보고의 중요성을 강조하는 실증적 근거. 학부생 연구 캡스톤에서 재현 가능한 연구 설계를 가르치는 동기 부여 사례. Brain-Mind-Behavior 모듈 간 재현성 차이(인지 vs. 사회심리)를 활용한 모듈별 방법론 교육 차별화 가능
- **관련 소스 교차참조**: S21 (positive changes from crisis), S22 (preregistration/OSF), S15 (LLM reproducibility issues), S19 (reproducible workflows)
- **품질 평가 (MMAT)**: Highest quality. Landmark study in top-tier journal with unprecedented scale (100 replications, 270+ researchers). Strength: systematic methodology, large-scale collaboration, transparent protocol. Limitation: only three journals sampled; limited to published, significant findings. Widely cited (18,000+ citations)

---

### [S21] The Replication Crisis Has Led to Positive Structural, Procedural, and Community Changes

- **저자/기관**: Max Korbmacher, Flavio Azevedo, Charlotte R. Pennington, Helena Hartmann, Madeleine Pownall, Kathleen Schmidt, Mahmoud Elsherif, Nate Breznau, Olly Robertson, Tamara Kalandadze, Shijun Yu, Bradley J. Baker, et al. (35 authors total; Framework for Open and Reproducible Research Training — FORRT)
- **연도**: 2023
- **출처**: Communications Psychology (Nature Portfolio), 1(1), Article 3
- **DOI/URL**: https://doi.org/10.1038/s44271-023-00003-2
- **소스 유형 / Tier**: Peer-reviewed perspective/review / Tier 1 (Nature Portfolio journal)
- **Knowledge Tree 위치**: B2.2.4 (Reproducibility and Open Science — Structural Reform)
- **PCC 적합성**: Population(Y) — psychology researchers, educators, students, institutions / Concept(Y) — curriculum reform, open science education, institutional change / Context(Y) — Higher education psychology programs globally, 2023
- **핵심 발견 (3-5개)**:
  1. Reframing: the "replication crisis" is better understood as a "credibility revolution" that has catalyzed meaningful, lasting positive changes across behavioral, cognitive, and social sciences
  2. Three categories of positive change identified: (a) structural changes — institutional norms and rules, (b) procedural changes — research practices and behaviors, (c) community changes — collaboration and scientific culture
  3. Open scholarship should be taught as a core component of higher education — evidence shows it influences student knowledge, expectations, attitudes, and engagement toward becoming effective researchers
  4. Grass-roots communities (e.g., ReproducibiliTea journal clubs, Psychological Science Accelerator, ManyBabies) have driven bottom-up reform alongside top-down institutional changes
  5. Infrastructure developments — creation of open tools (OSF, preregistration templates, Registered Reports) fostering uptake of improved norms represent durable structural change
- **서울대 심리학과 적용 시사점**: 교과과정 개편의 이론적 프레임워크로 '신뢰성 혁명' 개념 활용 가능 — 위기 대응이 아닌 적극적 혁신으로 포지셔닝. '심리학 연구 입문' 과목에서 오픈사이언스를 핵심 구성요소로 가르치는 근거 제공. 3가지 변화 범주(구조적-절차적-공동체)를 심리학혁신위원회의 개혁 전략 프레임워크로 활용 가능. ReproducibiliTea 저널클럽 모델을 학과 차원에서 도입하여 학부생-대학원생 연구 문화 개선에 활용. 10주 연구 지도 프로그램에서 오픈사이언스 실천(사전등록, 데이터 공유, Registered Reports)을 필수 과정으로 통합하는 근거
- **관련 소스 교차참조**: S20 (original reproducibility study), S22 (COS/OSF preregistration), S15 (LLM reproducibility challenges), S19 (reproducible workflows)
- **품질 평가 (MMAT)**: High quality. Multi-author perspective in Nature Portfolio journal with comprehensive review of reform landscape. Strength: systematic categorization of changes with concrete examples from multiple domains. Limitation: perspective/narrative review rather than systematic review; some claims lack quantitative evidence of impact

---

### [S22] Preregistration & OSF Training (Center for Open Science)

- **저자/기관**: Center for Open Science (COS) — Founded by Brian Nosek and Jeffrey Spies
- **연도**: Ongoing (established 2013; continuously updated)
- **출처**: COS Website / Open Science Framework (OSF) Platform
- **DOI/URL**: https://www.cos.io/ (main site); https://www.cos.io/initiatives/prereg (preregistration); https://www.cos.io/services/training (training); https://osf.io/ (OSF platform)
- **소스 유형 / Tier**: Grey literature — institutional platform and training resource / Tier 2 (Established non-profit, SOC2 accredited 2023, Charity Navigator top-rated)
- **Knowledge Tree 위치**: B2.2.4 (Reproducibility and Open Science — Practical Tools and Training)
- **PCC 적합성**: Population(Y) — researchers, educators, students at all levels / Concept(Y) — preregistration education, open science training, research transparency tools / Context(Y) — Higher education globally, ongoing
- **핵심 발견 (3-5개)**:
  1. Preregistration: posting a time-stamped, read-only study plan to a public repository before data collection/analysis, establishing transparent record of research intentions and distinguishing confirmatory from exploratory analyses
  2. OSF provides 11+ preregistration templates tailored to different research types, with view-only links for peer review and up to 4-year embargo periods — addressing researcher concerns about idea scooping
  3. Training services include: (a) team training (facilitated, interactive, customizable), (b) individual self-paced courses (with completion badges), covering preregistration, data management, reproducible workflows, and preprints
  4. Institutional adoption model: training funded through research grants, departmental budgets, or institutional programs; materials provided in perpetuity; pre/post evaluation included
  5. SOC2 accreditation (2023) and Charity Navigator/Candid top recognition provide institutional credibility for university partnerships
- **서울대 심리학과 적용 시사점**: '심리학 연구 입문' 과목에서 사전등록 실습의 핵심 플랫폼으로 즉시 활용 가능. 학부생 연구 캡스톤 및 졸업논문 3트랙 모두에서 OSF 기반 사전등록을 필수 요건으로 설정 가능. COS 팀 트레이닝을 AI Teaching Bootcamp(교수진)에 통합하여 교수진의 오픈사이언스 역량 강화. 10주 연구 지도 프로그램에서 OSF 프로젝트 생성 → 사전등록 → 데이터 공유 파이프라인을 학생 연구 워크플로로 표준화. 심리학혁신위원회에서 학과 차원의 COS 기관 파트너십(training subscription) 검토 가능
- **관련 소스 교차참조**: S20 (reproducibility study — Nosek as COS founder), S21 (structural changes including OSF), S19 (reproducible workflows), S15 (reproducibility in AI research)
- **품질 평가 (AACODS)**: Authority — Very High (COS founded by Nosek, leader of reproducibility movement; SOC2 accredited). Accuracy — High (continuously updated platform with community validation). Coverage — Comprehensive (covers full open science lifecycle). Objectivity — Moderate (advocacy organization for open science, but evidence-based mission). Date — Current (continuously updated). Significance — Very High (OSF is the dominant open science infrastructure globally; 700,000+ users)

---

## Branch B2 Summary and Synthesis

### Sources Charted

| Source | Title (Abbreviated) | Year | Tier | Knowledge Tree | PCC |
|--------|---------------------|------|------|----------------|-----|
| S13 | LLMs in Behavioral Science Interventions | 2025 | T2 | B2.1.1 | Y/Y/Y |
| S14 | LLMs for Psychological Assessment | 2025 | T1 | B2.1.1 | Y/Y/Y |
| S15 | Perils and Opportunities of LLMs in Psych Research | 2024 | T1 | B2.1.4 | Y/Y/Y |
| S16 | Responsible Clinical LLM Development | 2024 | T1 | B2.1.4 | Y/Y/Y |
| S17 | AI Literacy in Psychology (APA) | 2023-24 | T2 | B2.1.2 | Y/Y/Y |
| S18 | Responsible AI for Psychology (APS) | 2023 | T2 | B2.1.4 | Y/Y/Y |
| S19 | Teaching Statistics/Data Analysis with R | 2021-23 | T2 | B2.3.1/B2.3.2 | Y/Y/Y |
| S20 | Reproducibility of Psychological Science | 2015 | T1 | B2.2.4 | Y/Y/Y |
| S21 | Replication Crisis → Positive Changes | 2023 | T1 | B2.2.4 | Y/Y/Y |
| S22 | COS Preregistration & OSF Training | Ongoing | T2 | B2.2.4 | Y/Y/Y |

**Total**: 10/10 sources charted
**PCC Pass Rate**: 10/10 (100%)

### Tier Distribution

| Tier | Count | Sources |
|------|-------|---------|
| Tier 1 (Top journals) | 4 | S14 (AMPPS), S15 (PNAS Nexus), S16 (npj Mental Health), S20 (Science), S21 (Comms Psych) |
| Tier 2 (Established) | 5 | S13 (Behavioral Sci & Policy), S17 (APA Policy), S18 (APS), S19 (OpenIntro/TISE), S22 (COS) |
| Tier 3/4 | 0 | — |

**Note**: 5 sources at Tier 1 (counting S21 correctly), 5 sources at Tier 2. Strong evidence base with majority published in high-impact venues.

### Knowledge Tree Coverage

| Sub-branch | Code | Sources | Coverage Assessment |
|------------|------|---------|---------------------|
| LLM Applications | B2.1.1 | S13, S14 | Good — behavioral interventions + assessment methods |
| AI Literacy Frameworks | B2.1.2 | S17 | Moderate — single policy source, needs empirical studies |
| Ethical/Responsible AI | B2.1.4 | S15, S16, S18 | Strong — empirical evidence + clinical framework + professional standards |
| Reproducibility & Open Science | B2.2.4 | S20, S21, S22 | Strong — foundational evidence + reform analysis + practical tools |
| Data Analysis Pedagogy | B2.3.1/B2.3.2 | S19 | Moderate — single (excellent) resource, needs psychology-specific studies |

### Key Themes Across B2 Sources

**Theme 1: LLMs as Double-Edged Sword for Psychology (S13, S14, S15, S16)**
LLMs offer transformative potential for behavioral interventions, psychological assessment, and clinical applications. However, uncritical adoption ("GPTology") introduces risks including reduced variance, WEIRD bias amplification, reproducibility challenges with proprietary models, and ethically high-stakes clinical applications. A consistent message emerges: integration must be staged, validated, and transparent.

**Theme 2: Professional Standards and Ethics Frameworks (S15, S16, S17, S18)**
Both APA and APS have positioned psychology as uniquely qualified to shape responsible AI development. Key principles: transparency in AI use across the research pipeline, accountability for AI-generated outputs, human oversight requirements, and embedding AI ethics across subdisciplines rather than treating it as a standalone topic.

**Theme 3: Reproducibility → Credibility Revolution (S20, S21, S22)**
The 2015 Reproducibility Project (S20) established the problem; by 2023, Korbmacher et al. (S21) documented that the crisis catalyzed lasting structural (institutional norms), procedural (research practices), and community (collaboration culture) reforms. COS/OSF (S22) provides the infrastructure enabling these changes — preregistration, open data, reproducible workflows.

**Theme 4: Pedagogy Must Integrate Computing and Open Science (S14, S19, S21, S22)**
Modern psychology education requires computational literacy (R/Python, data analysis pipelines) and open science practices (preregistration, data sharing) as core competencies, not electives. Cetinkaya-Rundel & Hardin (S19) demonstrate how simulation-based inference and interactive tutorials reduce barriers; Brickman et al. (S14) provide psychology-specific LLM coding tutorials.

**Theme 5: Staged Integration Model (S13, S16)**
Both Hecht et al. (S13) and Stade et al. (S16) propose graduated models: interventions scale risk with directness of user-LLM interaction; clinical integration parallels autonomous vehicle SAE levels. This staged approach directly maps to SNU's phased implementation timeline.

### Gaps Identified for P1 Deepening

**Gap 1: AI Literacy Empirical Evidence (B2.1.2)**
S17 provides policy-level framework but lacks empirical studies on AI literacy outcomes in psychology undergraduates. P1 should search for: pre-post studies of AI literacy interventions, validated AI literacy assessment instruments for psychology students, and curriculum implementation case studies.

**Gap 2: Psychology-Specific Data Science Pedagogy (B2.3.1/B2.3.2)**
S19 is an excellent general statistics education resource but not psychology-specific. P1 should identify: psychology-focused R/Python curriculum implementations, comparative studies of statistical computing tools in psychology education, and evidence on computational methods course outcomes for psychology majors.

**Gap 3: Korean Higher Education Context (B2.4)**
No B2 sources address Korean university-specific factors: AI education policy in Korean higher education, Korean-language NLP tools for psychology research, or Korean institutional open science adoption. P1 should include Korean Ministry of Education AI guidelines and Korean psychology department reform case studies.

**Gap 4: Prompt Engineering and AI Research Methods Pedagogy (B2.1.3)**
No sources directly address how to teach students systematic prompt engineering for research applications. P1 should search for: prompt engineering curricula, AI-assisted qualitative coding methods, and structured approaches to LLM use in research workflows.

**Gap 5: Preregistration Adoption Rates and Outcomes (B2.2.4)**
While S22 provides infrastructure and S21 describes reform trends, quantitative data on preregistration adoption rates in psychology departments and their impact on research quality is missing. P1 should search for: longitudinal adoption studies, institutional implementation case studies, and student research quality outcomes with/without preregistration requirements.

**Gap 6: Source Verification Needed (S17, S18, S19)**
Three sources could not be fully verified in their originally cited form:
- S17: "Mayes et al. 2023 APA Position Paper" — closest match is APA's August 2024 policy statement
- S18: "APS Task Force 2023 in Perspectives on Psychological Science" — could not locate specific publication with this exact title/venue
- S19: "Cetinkaya-Rundel & Hardin 2023 in JSDSE" — closest matches are IMS textbook (2e, 2023) and TISE article (2022)

P1 should either verify exact publication details or identify replacement sources that better match the intended content.

### Cross-Branch Integration Points

| B2 Source | B1 Connection | Integration Rationale |
|-----------|---------------|----------------------|
| S15, S17 | B1 AI integration sources | LLM limitations and AI literacy inform BMBM module AI integration strategy |
| S20, S21 | B1 curriculum reform sources | Reproducibility crisis as motivation for curriculum change connects to PBL rationale |
| S19 | B1 pedagogy sources | Data analysis pedagogy connects to active learning and PBL approaches |
| S22 | B1 assessment sources | OSF/preregistration connects to authentic assessment of research competencies |

---

*Charting completed: 2026-03-12 | Reviewer: Claude Opus 4.6 | Status: P0 Complete — Ready for P1 verification and gap-filling*
