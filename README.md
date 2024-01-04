# Formal-Verification Reference List

## 1. Introduction

1. Clarke, EdmundM., et al. **“Handbook of Model Checking.”** Springer International Publishing eBooks, 2018, [Handbook](https://doi.org/10.1007/978-3-319-10575-8);
2. [Formal verification in hardware design: a survey](https://dl.acm.org/doi/10.1145/307988.307989);
3. [Model Checking (standford lecture)](https://web.stanford.edu/class/cs357/lecture12.pdf);
4. [Slides: SMT-based Model Checking of Transition Systems](https://www.di.ens.fr/~pouzet/cours/mpri/cours-smt.pdf)

### 1.1 Resources
1. **Formal Methods and Machine Learning**, related paper collections in git repo [jdnklau/fm-ml](https://github.com/jdnklau/fm-ml)
2. **Fuzzing Methods**, related paper collections in git repo [wcventure/FuzzingPaper](https://github.com/wcventure/FuzzingPaper#difuzzrtl-differential-fuzz-testing-to-find-cpu-bug-sp-2021)
3. **Neural Network Verifier**, git repo [Verified-Intelligence/alpha-beta-CROWN](https://github.com/Verified-Intelligence/alpha-beta-CROWN?tab=readme-ov-file)
4. **Formal Verification for Machine Learning** Credit to He Bowei [link](https://docs.google.com/document/d/1tQYUGaPM-oWp0gunGaDKpzOLThG7oT78dVPi085vzI0/edit?pli=1)

### 1.2 Application Scenarios

## 2. Model Checking Algorithms
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
2. StringFuzz: A fuzzer for string solvers, CAV 2018
3. Feedback-Guided Circuit Structure Mutation for Testing Hardware Model Checkers, ICCAD 2021
4. BMC+Fuzz: Efficient and Effective Test Generation, DATE 2022, [paper](https://ieeexplore.ieee.org/abstract/document/9774672)

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

### 3.6 Software Tester

## 4 Other Topics
### 4.1 Verification for Neural Network and Machine Learning
1. **WFVML** (ICML Workshop on Formal Verification of Machine Learning) <br />
   i. [2023 Workshop](https://icml.cc/virtual/2023/workshop/21471) <br />
   ii. [2022 Workshop](https://icml.cc/virtual/2022/workshop/13473) <br />

## 5 Researchers to Follow-up
### 5.1 Europe
1. [USI - Formal Verification and Security Lab](https://verify.inf.usi.ch/)
2. [JKU-Institute for Formal Models and Verification Group](https://fmv.jku.at/index.html) (Organizer of HWMCC'20)

## 6 Related Conference
0. [Upcoming Formal Methods Events](https://www.fmeurope.org/feature/upcoming_conferences/)

1. **FMCAD** (Formal Methods in Computer-Aided Design) <br />
   i. Accepted Papers <br />
         a. [2023 Accepted Papers](https://fmcad.org/FMCAD23/accepted/) <br />
         b. [2022 Accepted Papers](https://fmcad.org/FMCAD22/accepted/) <br />
   ii. Submission Deadline <br />
         a. Deadlines for 2024 to be announced <br />
         b. May 22, 2023 last year <br />
   iii. Recent Highlights <br />
   
2. **VMCAI** (International Conference on Verification, Model Checking, and Abstract Interpretation) <br />
   i. Accepted Papers <br />
   &emsp; a. [2024 Accepted Papers](https://popl24.sigplan.org/home/VMCAI-2024#event-overview) <br />
   &emsp; b. [2023 Accepted Papers](https://popl23.sigplan.org/home/VMCAI-2023#event-overview) <br />
   &emsp; c. [2022 Accepted Papers](https://popl22.sigplan.org/home/VMCAI-2022#event-overview) <br />
   ii. Submission Deadline <br />
   &emsp; a. Deadlines for 2024 to be announced <br />
   &emsp; b. Spe 7, 2023 last year <br />
   iii. Recent Highlights <br />

3. **CAV** (Computer Aided Verification) <br />
   i. Accepted Papers <br />
   &emsp; a. [2023 Accepted Papers](http://www.i-cav.org/2023/accepted-papers/) <br />
   &emsp; b. [2022 Accepted Papers](http://i-cav.org/2022/accepted-papers/) <br />
   ii. Submission Deadline <br />
   &emsp; a. Jan 19, 2024 <br />
   iii. Recent Highlights <br />

4. **TACAS** (International Conference on Tools and Algorithms for the Construction and Analysis of Systems) <br />

5. **FM** (International Symposium on Formal Methods) <br />

6. **NFM** (NASA Formal Methods Symposium) <br />

7. **FormaliSE** (International Conference on Formal Methods in Software Engineering) <br />

8. **ESOP** (European Symposium on Programming) <br />

8. **ATAV** (International Symposium on Automated Thecnology for Verification and Analysis) <br />



   
## 7 Related Competition
1. Software Verification Competition (**SV-COMP**), [link](https://sv-comp.sosy-lab.org/)
2. Software Testing Competition (**Test-COMP**), [publication 2024](https://test-comp.sosy-lab.org/2024/), [resuls](https://test-comp.sosy-lab.org/2023/results/results-verified/)
3. hardware Model Ceching Competition (**HWMCC**), [link](https://fmv.jku.at/hwmcc20/) <br />
   i. HWMCC-2020 all world-level checkers and their configuarations, [link](https://figshare.com/articles/software/CAV_2021_Artifact_Pono_Model_Checker/14479542)

## 8 Benchmark
### SMT2 Format

