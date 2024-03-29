# Formal-Verification Reference List

## Contents

1. Introduction <br />
&emsp;1.1 [Paper Collections](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#11-paper-collections) <br />
&emsp;1.2 [Online Courses](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#12-online-courses) <br />
&emsp;1.3 [Application Scenarios](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#13-application-scenarios) <br />
2. Formal Verification Algorithms <br />
&emsp;2.1 [Bounded Model Checking](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#21-bounded-model-checking) <br />
&emsp;2.2 [Interpolation](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#22-interpolation) <br />
&emsp;2.3 [IC3/PDR](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#23-ic3pdr) <br />
&emsp;2.4 [Fuzzing](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#24-fuzzing) <br />
&emsp;2.5 [Localization Abstraction](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#25-localization-abstraction) <br />
&emsp;2.6 [AI + Formal](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#26-ai--formal) <br />
&emsp;2.7 [CEGAR](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#27-cegar) <br />
3. [Tools](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#3-tools) <br />
4. Other Topics <br />
&emsp;4.1 [Verification for Neural Network and Machine Learning](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#41-verification-for-neural-network-and-machine-learning) <br />
&emsp;4.2 [Fuzzing with LLMs](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#42-fuzzing-with-llms) <br />
5. Researchers to Follow-up <br />
&emsp;4.1 [Europe](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#51-europe) <br />
&emsp;4.2 [North America](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#52-north-america) <br />
&emsp;4.2 [Assia](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#53-asia) <br />
6. [Related Conference](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#6-related-conference) <br />
7. [Related Competition](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#7-related-competition) <br />
8. Benchmark <br />
&emsp;8.1 [Classification by Application Scenarios](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#81-classification-by-application-scenario) <br />
&emsp;8.2 [Classification by Data Format](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/README.md#82-classification-by-data-format) <br />


## 1. Introduction

1. Clarke, EdmundM., et al. **“Handbook of Model Checking.”** Springer International Publishing eBooks, 2018, [Handbook](https://doi.org/10.1007/978-3-319-10575-8);
2. [Formal verification in hardware design: a survey](https://dl.acm.org/doi/10.1145/307988.307989);
3. [Model Checking (standford lecture)](https://web.stanford.edu/class/cs357/lecture12.pdf);
4. [Slides: SMT-based Model Checking of Transition Systems](https://www.di.ens.fr/~pouzet/cours/mpri/cours-smt.pdf)
5. A Survey of Practical Formal Methods for Security, 2020, [paper](https://dl.acm.org/doi/full/10.1145/3522582)

### 1.1 Paper Collections
0. **Our Reading Group**, [link](https://github.com/LihaoYin/Formal-Verification-Reference/blob/main/Paper-Reading-Group)
1. **Formal Methods and Machine Learning**, related paper collections in git repo [jdnklau/fm-ml](https://github.com/jdnklau/fm-ml)
2. **Fuzzing Methods**, related paper collections in git repo [wcventure/FuzzingPaper](https://github.com/wcventure/FuzzingPaper#difuzzrtl-differential-fuzz-testing-to-find-cpu-bug-sp-2021)
3. **Neural Network Verifier**, git repo [Verified-Intelligence/alpha-beta-CROWN](https://github.com/Verified-Intelligence/alpha-beta-CROWN?tab=readme-ov-file)
4. **Formal Verification for Machine Learning / LLMs** Credit to He Bowei [link](https://docs.google.com/document/d/1tQYUGaPM-oWp0gunGaDKpzOLThG7oT78dVPi085vzI0/edit?pli=1)

### 1.2 Online Courses
1. Introduction to Model Checking, Prof. Katoen, 2018
   1. [slide](https://moves.rwth-aachen.de/teaching/ss-18/introduction-to-model-checking/)
   2. [video](https://www.youtube.com/watch?v=Y5Hg4MvUXc4&list=PLwabKnOFhE38C0o6z_bhlF_uOUlblDTjh)
2. Model Checking, Prof. B. Srivathsan, 2015
   1. [slide](https://archive.nptel.ac.in/courses/106/106/106106136/)
   2. [video](https://www.youtube.com/watch?v=piISG8bV2GI&list=PLJ5C_6qdAvBGojQMUzL4x5Y0N5gBJmT4l)

3. Formal Verification Meets Machine Learning, [link](https://moves.rwth-aachen.de/teaching/ss-18/fvmml/)
4. Neural Network Verification Tutorial, [link](https://neural-network-verification.com/)

### 1.3 Application Scenarios
1. Hardware Verification
2. Concurrency Verification <br />
   i. [Slides: Concurrency and Security](https://www.dcc.fc.up.pt/~edrdo/aulas/qses/lectures/qses-07-concurrency.pdf) <br />
   ii. [Princeton Report](https://www.cs.princeton.edu/techreports/2019/012.pdf) <br />
3. Verification in Safety and Trustworthiness of LLMs <br />
   i. [survey paper](https://arxiv.org/abs/2305.11391) <br />
   ii. [FuzzGPT](https://arxiv.org/abs/2304.02014) <br />
4. Side-Channel Detection <br />
   i. QFuzz: Quantitative Fuzzing for Side Channels, ISSTA, 2021, [paper](https://dl.acm.org/doi/pdf/10.1145/3460319.3464817) <br />
5. Data Flow Sensitivity <br />
6. IoT Protocols <br />
   i. A State-of-the-Art Survey on Formal Verification of the Internet of Things Applications, 2019, [paper](https://link.springer.com/article/10.1007/s12927-019-0003-8) <br />
   ii. Towards formal verification of IoT protocols: A Review, 2020, [paper](https://www.sciencedirect.com/science/article/pii/S1389128619317116) <br />
   iii. A Survey on Formal Verification and Validation Techniques for Internet of Things, 2023, [paper](https://www.mdpi.com/2076-3417/13/14/8122) <br />
7. Testing Deep Learning Libraries <br />
   i. DocTer: Documentation-Guided Fuzzing for Testing Deep Learning API Functions, ISSTA, 2022, [paper](https://dl.acm.org/doi/abs/10.1145/3533767.3534220) <br />
   ii. Fuzzing Deep-Learning Libraries via Automated Relational API Inference, ESEC/FSE, 2022, [paper](https://dl.acm.org/doi/abs/10.1145/3575693.3575707) <br />
   iii. Incremental Bounded Model Checking of Artificial Neural Networks in CUDA, 2019, [paper](https://ieeexplore.ieee.org/abstract/document/9046094) <br />
   iV. Free Lunch for Testing: Fuzzing Deep-Learning Libraries from Open Source, ICSE, 2022, [paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510041) <br />
   v. Muffin: Testing Deep Learning Libraries via Neural Architecture Fuzzing, ICSE, 2022, [paper](https://dl.acm.org/doi/abs/10.1145/3510003.3510092) <br />


## 2. Formal Verification Algorithms
### 2.1 Bounded Model Checking
1. **BMC and K-IND**, Armin Biere et al.， Bounded Model Checking，2003, [paper](https://www.cs.cmu.edu/~emc/papers/Books%20and%20Edited%20Volumes/Bounded%20Model%20Checking.pdf)
2. **K-Induction**, 
Sheeran, Singh, and Stålmarck, Checking
Safety Properties Using Induction and a SAT-Solver, 2000, [paper](https://www.di.ens.fr/~pouzet/cours/mpri/bib/sheeran-FMCAD00.pdf)

### 2.2 Interpolation
1. McMillan, Interpolation and SAT-based model checking, 2003, [paper](https://people.eecs.berkeley.edu/~alanmi/courses/2008_290A/papers/mcmillan_cav03.pdf)
2. McMillan, Interpolants and Symbolic Model Checking, 2007, [paper](https://link.springer.com/chapter/10.1007/978-3-540-69738-1_6)
   
### 2.3 IC3/PDR
1. Unbounded Model Checking, IC3 and PDR, [slides](https://ece.uwaterloo.ca/~agurfink/ece750t29f18/assets/pdf/05_IC3_PDR.pdf)
2. Bradley, SAT-Based Model Checking without Unrolling, VMCAI 2011, [paper](https://theory.stanford.edu/~arbrad/papers/IC3.pdf)
3. Efficient Implementation of Property Directed Reachability, FMCAD 2011, [paper](https://people.eecs.berkeley.edu/~alanmi/publications/2011/fmcad11_pdr.pdf)
4. Infinite-state Invariant Checking with IC3 and Predicate Abstraction, FMSD, 2016, [paper](https://link.springer.com/article/10.1007/s10703-016-0257-4) (IC3 via Implicit Predicate Abstraction)
5. Model Checking of Verilog RTL Using IC3 with Syntaxguided Abstraction, NFM, 2019, [paper](https://aman-goel.github.io/publications/goel2019model_preprint.pdf) (IC3 with Syntax-Guided Abstraction)
6. Syntax-Guided Synthesis for Lemma Generation in Hardware Model Checking, VMCAI, 2021, [paper](https://oar.princeton.edu/bitstream/88435/pr1zc3s/1/SyntaxGuided.pdf), (SyGuS-PDR)

### 2.4 Fuzzing
1. [Slides: Software Verification: Testing vs. Model Checking](https://research.ibm.com/haifa/conferences/hvc2017/images/HVC17_Lemberger_Software%20Verification%20-%20Testing%20vs%20Model%20Checking.%20A%20Comparative%20Evaluation%20of%20the%20State%20of%20the%20Art.pdf), IBM Research
2. [Fuzzing: a survey](https://cybersecurity.springeropen.com/articles/10.1186/s42400-018-0002-y)
3. Survey of Software Fuzzing Techniques, [paper](https://www.researchgate.net/publication/356980212_Survey_of_Software_Fuzzing_Techniques)
4. BMC+Fuzz: Efficient and Effective Test Generation, DATE 2022, [paper](https://ieeexplore.ieee.org/abstract/document/9774672)
5. A Review of Fuzzing Tools and Methods, [paper](https://wcventure.github.io/FuzzingPaper/Paper/2017_review.pdf)

### 2.5 Localization Abstraction
1. Efficient Abstraction and Refinement for Word-level Model Checking, Yen-Sheng Ho's Thesis, [link](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2017/EECS-2017-198.pdf)
2. Yen-Sheng Ho, Enhancing PDR/IC3 with Localization Abstraction, IWLS, 2017, [paper](https://people.eecs.berkeley.edu/~alanmi/publications/2017/iwls17_pdr.pdf)

### 2.6 AI + Formal
1. MachSMT: A Machine Learning-based Algorithm Selector for SMT Solvers, TACAS 2021, [paper](https://link.springer.com/chapter/10.1007/978-3-030-72013-1_16)
2. Code2Inv: A Deep Learning Framework for Program Verification, CAV 2020, [paper](https://link.springer.com/chapter/10.1007/978-3-030-53291-8_9)
3. A Data-Driven CHC Solver, PLDI 2018, [paper](https://dl.acm.org/doi/abs/10.1145/3296979.3192416)
4. ICE: A Robust Framework for Learning Invariants, CAV 2014, [paper](https://link.springer.com/chapter/10.1007/978-3-319-08867-9_5)

### 2.7 CEGAR
1. Counterexample Guided Abstraction Refinement Via Program Execution, 2004, [paper](https://link.springer.com/chapter/10.1007/978-3-540-30482-1_23)
2. Counterexample-guided prophecy for model checking modulo the theory of arrays, TACAS 2021, [paper](https://lmcs.episciences.org/9984/pdf) (CEGAR algorithm uses uninterpreted functions (UF))

## 3. Tools
### 3.1 Bit-level Hardware Model Checker
1. **abc**, including abc, abc-zz, super prove (best performace in open-source), [intro](https://people.eecs.berkeley.edu/~alanmi/abc/), [github](https://github.com/berkeley-abc)
2. **iimc**, [github](https://github.com/mgudemann/iimc)

### 3.2 Bit-level Hardware Logic Synthesis
1. **Yosys**, [link](https://yosyshq.net/yosys/), [link](https://yosyshq.readthedocs.io/projects/yosys/en/latest/), [manual](https://yosyshq.net/yosys/files/yosys_manual.pdf), [github](https://github.com/YosysHQ/yosys)

### 3.3 Bit-level Hardware Data Structure
1. **AIGER**, [paper](https://fmv.jku.at/papers/Biere-FMV-TR-07-1.pdf), [github](https://github.com/arminbiere/aiger)

### 3.4 Word-level Hardware Model Checker
1. **Pono**, [paper](https://theory.stanford.edu/~barrett/pubs/MIL+21.pdf), [github](https://github.com/stanford-centaur/pono)
2. **Avr** (best performace in open-source), [paper](https://link.springer.com/content/pdf/10.1007/978-3-030-45190-5_23.pdf), [github](https://github.com/aman-goel/avr)
3. **Spacer in Z3 Theorem Prover**, [introduction](https://spacer.bitbucket.io/), [github](https://github.com/Z3Prover/z3/tree/master/src/muz/spacer)

### 3.5 Word-level Data Structure
1. **Btor2**, [paper](https://fmv.jku.at/papers/NiemetzPreinerWolfBiere-CAV18.pdf), [btor2tools](https://github.com/Boolector/btor2tools)
2. **SMT-LIB**, [Intro](https://smtlib.cs.uiowa.edu/)
3. **SMV**, [slides](https://web.cs.wpi.edu/~kfisler/Courses/525V/S02/Readings/smv-cadence.pdf), [slides](https://www.cs.cmu.edu/~emc/15414-f11/lecture/lec13_SMV.pdf) <br />
   i. **Verilog2SMV**, [link](https://es-static.fbk.eu/tools/verilog2smv/), [paper](https://ieeexplore.ieee.org/document/7459485)

### 3.6 Software Model Checker

| Checker | Ref | github | Affiliation | For Which Language | Comments |
| :-----| ----: | :----: | :-----| ----: | ----: |
| CBMC | [paper](https://doi.org/10.1007/978-3-540-24730-2_15), [paper](https://doi.org/10.1007/978-3-642-54862-8_26) |  | Queen Mary U. London, UK | C |  |
| CPAchecker | [paper](https://doi.org/10.1007/978-3-642-22110-1_16), [paper](https://doi.org/10.1007/978-3-662-46681-0_34) |  | LMU Munich, Germany | C |  |
| DEAGLE | [paper](https://doi.org/10.1007/978-3-030-99527-0_25) |  | Tsinghua U., China | C | Best Perfomance in Concurrecy Benchmark |
| GDART | [paper](https://doi.org/10.1007/978-3-030-99527-0_27) |  | TU Dortmund, Germany | JAVA |  |
| JBMC | [paper](https://doi.org/10.1007/978-3-319-96145-3_10), [paper](https://doi.org/10.1007/978-3-030-17502-3_17) |  | U. of Sussex / Difblue, UK | JAVA |  |
| Symbiotic | [paper](https://doi.org/10.1007/978-3-319-94111-0_7), [paper](https://doi.org/10.1007/978-3-030-99527-0_32) |  | Masaryk U., Brno, Czechia | C |  |
| UAutomizer | [paper](https://doi.org/10.1007/978-3-642-39799-8_2) |  | U. of Freiburg, Germany | C |  |
| VeriAbs | [paper](https://ieeexplore.ieee.org/document/8952452), [paper](https://doi.org/10.1007/978-3-030-72013-1_32) |  | TCS, India | C |  |
| VeriFuzz | [paper](https://doi.org/10.23919/DATE54114.2022.9774672) |  | TCS, India | C |  |

### 3.6 Software Tester

| Tester | Ref | github | Affiliation | Comments |
| :-----| ----: | :----: | :-----| ----: |
| VeriFuzz | [paper](https://link.springer.com/chapter/10.1007/978-3-030-99429-7_20) |  | Tata Consultancy Services, India |  |
| FuSeBMC | [paper](https://link.springer.com/chapter/10.1007/978-3-030-99429-7_19), [paper](https://link.springer.com/chapter/10.1007/978-3-030-79379-1_6) |  | U. of Manchester, UK |  |
| FuSeBMC_IA | [paper](https://link.springer.com/chapter/10.1007/978-3-031-30826-0_18), [paper](https://arxiv.org/abs/2012.11245) |  | U. of Manchester, UK |  |
| ESBMC_KIND | [paper](https://doi.org/10.1007/978-3-030-17502-3_15), [paper](https://link.springer.com/article/10.1007/s10009-015-0407-9) |  | U. of Manchester, UK |  |

## 4 Other Topics
### 4.1 Verification for Neural Network and Machine Learning
1. **WFVML** (ICML Workshop on Formal Verification of Machine Learning) <br />
   i. [2023 Workshop](https://icml.cc/virtual/2023/workshop/21471) <br />
   ii. [2022 Workshop](https://icml.cc/virtual/2022/workshop/13473) <br />
   iii. A review of formal methods applied to machine learning, 2021, [paper](https://arxiv.org/pdf/2104.02466.pdf) <br />

### 4.2 Fuzzing with LLMs
1. Large Language Models are Zero-Shot Fuzzers: Fuzzing Deep-Learning Libraries via Large Language Models, 2022, [paper](https://export.arxiv.org/abs/2212.14834)
2. Large Language Models are Few-shot Testers: Exploring LLM-based General Bug Reproduction, 2023, [paper](https://arxiv.org/abs/2209.11515)

## 5 Researchers to Follow-up
### 5.1 Europe
1. [USI - Formal Verification and Security Lab](https://verify.inf.usi.ch/)
2. [JKU-Institute for Formal Models and Verification Group](https://fmv.jku.at/index.html) (Organizer of HWMCC'20)

### 5.2 North America

### 5.3 Asia



## 6 Related Conference
0. [Upcoming Formal Methods Events](https://www.fmeurope.org/feature/upcoming_conferences/)

1. **FMCAD** (Formal Methods in Computer-Aided Design) <br />
   i. Accepted Papers <br />
   &emsp; a. [2023 Accepted Papers](https://fmcad.org/FMCAD23/accepted/) <br />
   &emsp; b. [2022 Accepted Papers](https://fmcad.org/FMCAD22/accepted/) <br />
   ii. Next Submission Deadline <br />
   &emsp; a. Deadlines for 2024 to be announced <br />
   &emsp; b. May 22, 2023 last year <br />
   iii. Recent Highlights <br />
   
2. **VMCAI** (International Conference on Verification, Model Checking, and Abstract Interpretation) <br />
   i. Accepted Papers <br />
   &emsp; a. [2024 Accepted Papers](https://popl24.sigplan.org/home/VMCAI-2024#event-overview) <br />
   &emsp; b. [2023 Accepted Papers](https://popl23.sigplan.org/home/VMCAI-2023#event-overview) <br />
   &emsp; c. [2022 Accepted Papers](https://popl22.sigplan.org/home/VMCAI-2022#event-overview) <br />
   ii. Next Submission Deadline <br />
   &emsp; a. Deadlines for 2024 to be announced <br />
   &emsp; b. Spe 7, 2023 last year <br />
   iii. Recent Highlights <br />

3. **CAV** (Computer Aided Verification) <br />
   i. Accepted Papers <br />
   &emsp; a. [2023 Accepted Papers](http://www.i-cav.org/2023/accepted-papers/) <br />
   &emsp; b. [2022 Accepted Papers](http://i-cav.org/2022/accepted-papers/) <br />
   ii. Next Submission Deadline <br />
   &emsp; a. Jan 19, 2024 <br />
   iii. Recent Highlights <br />

4. **TACAS** (International Conference on Tools and Algorithms for the Construction and Analysis of Systems) <br />

5. **FM** (International Symposium on Formal Methods) <br />

6. **NFM** (NASA Formal Methods Symposium) <br />

7. **FormaliSE** (International Conference on Formal Methods in Software Engineering) <br />

8. **ESOP** (European Symposium on Programming) <br />

8. **ATAV** (International Symposium on Automated Technology for Verification and Analysis) <br />




## 7 Related Competition
1. Software Verification Competition (**SV-COMP**), [link](https://sv-comp.sosy-lab.org/)
2. Software Testing Competition (**Test-COMP**), [publication 2024](https://test-comp.sosy-lab.org/2024/), [resuls](https://test-comp.sosy-lab.org/2023/results/results-verified/)
3. Hardware Model Ceching Competition (**HWMCC**), [link](https://fmv.jku.at/hwmcc20/) <br />
   i. HWMCC-2020 all world-level checkers and their configuarations, [link](https://figshare.com/articles/software/CAV_2021_Artifact_Pono_Model_Checker/14479542)
4. International Verification of Neural Networks Competition (**VNN-COMP**), [link](https://vnncomp.christopher-brix.de/)

## 8 Benchmark
### 8.1 Classification by Application Scenario

### 8.2 Classification by Data Format

