# Symbolic Execution Papers

This repository is for collecting and grouping the symbolic execution papers and opensource tools in recent years.


## Table of Contents

* [Summary](#Summary)
* [Path Explosion](#Path-Explosion)
* [Memory Model](#Memory-Model) 
* [Constraint Solving](#Constraint-Solving) 
* [Environment Interaction](#Environment-Interaction)
* [Hybrid Fuzzing](#Hybrid-Fuzzing)
* [Engine](#Engine)
* [Others](#Others) 

## Summary

* 1976 Symbolic Execution and Program Testing

* 2010 All You Ever Wanted to Know about Dynamic Taint Analysis and Forward Symbolic Execution (but Might Have Been Afraid to Ask)

* 2013 Symbolic Execution for Software Testing: Three Decades Later

* 2016 On the Techniques We Create, the Tools We Build, and Their Misalignments: A Study of KLEE

* 2018 A Survey of Symbolic Execution Techniques

## Path Explosion

* 2011 Directed Incremental Symbolic Execution

* 2015 Under-Constrained Symbolic Execution Correctness Checking for Real Code

* 2018 Chopped Symbolic Execution ([chopper](https://github.com/davidtr1037/chopper))

* 2018 Automatically Generating Search Heuristics for Concolic Testing ([ParaDySE](https://github.com/kupl/ParaDySE))

* 2019 Concolic Testing with Adaptively Changing Search Heuristics ([Chameleon](https://github.com/kupl/Chameleon))

* 2020 Efficient Multiplex Symbolic Execution with Adaptive Search Strategy

* 2020 Making Symbolic Execution Promising by Learning Aggressive State-Pruning Strategy ([HOMI](https://github.com/kupl/HOMI_public)) 

* 2020 Analyzing System Software Components using API Model Guided Symbolic Execution

* 2021 SyML: Guiding Symbolic Execution Toward Vulnerable States Through Pattern Learning ([SyML](https://github.com/ucsb-seclab/syml))

* 2021 Learning to Explore Paths for Symbolic Execution ([LEARCH](https://github.com/eth-sri/learch))

* 2021 Metrinome: Path Complexity Predicts Symbolic Execution Path Explosion ([Metrinome](https://github.com/hmc-alpaqa/metrinome))

* 2021 TracerX: Dynamic Symbolic Execution with Interpolation ([TraceX](https://github.com/tracer-x/tracer-x.github.io))

* 2022 Ferry: State-Aware Symbolic Execution for Exploring State-Dependent Program Paths

* 2022 Combining Static Analysis Error Traces with Dynamic Symbolic Execution ([KLEE-sa](https://srg.doc.ic.ac.uk/projects/klee-sa/artifact.html))

## Constraint Solving

* 2019 Neuro-Symbolic Execution: Augmenting Symbolic Execution with Neural Constraints

* 2019 Enhancing Symbolic Execution by Machine Learning Based Solver Selection ([PCC](https://github.com/csienslab-PCC/PathConstraintClassifier))

* 2019 Constraints in Dynamic Symbolic Execution: Bitvectors or Integers? ([Data](https://srg.doc.ic.ac.uk/projects/klee-z3-int-vs-bv/artifact.html))

* 2019 Just Fuzz It Solving Floating-Point Constraints using Coverage-Guided Fuzzing ([JFS](https://github.com/mc-imperial/jfs))

* 2020 Pending Constraints in Symbolic Execution for Better Exploration and Seeding ([Pending](https://srg.doc.ic.ac.uk/projects/pending-constraints/artifact.html))

* 2020 Multiplex Symbolic Execution Exploring Multiple Paths by Solving Once

* 2021 Type and Interval Aware Array Constraint Solving for Symbolic Execution

* 2021 Synthesize Solving Strategy for Symbolic Execution

* 2021 Boosting Symbolic Execution via Constraint Solving Time Prediction ([SMTimer](https://github.com/Artisan-Lab/SMTimer))

* 2021 Address-Aware Query Caching for Symbolic Execution ([KLEE-aaqc](https://github.com/davidtr1037/klee-aaqc))

* 2022 Satisfiability Modulo Fuzzing: A Synergistic Combination of SMT Solving and Fuzzing

* 2023 Intelligent Constraint Classification for Symbolic Execution

## Memory Model

* 2017 Rethinking pointer reasoning in symbolic execution ([MEMSIGHT](https://github.com/season-lab/memsight))

* 2019 Fine-grain Memory Object Representation in Symbolic Execution 

* 2019 A Segmented Memory Model for Symbolic Execution

* 2020 Relocatable addressing model for symbolic execution ([KLEE-ram](https://www.tau.ac.il/~davivtra/projects/ram/))

* 2020 Past-Sensitive Pointer Analysis for Symbolic Execution ([KLEE-pspa](https://github.com/davidtr1037/klee-pspa))

* 2021 A Bounded Symbolic-Size Model for Symbolic Execution ([KLEE-symsize](https://github.com/davidtr1037/klee-symsize))

* 2022 A Deterministic Memory Allocator for Dynamic Symbolic Execution

## Environment Interaction

* 2018 Avatar2: A Multi-target Orchestration Platform ([Avatar2](https://github.com/avatartwo/avatar2))

* 2020 SYMBION: Interleaving Symbolic with Concrete Execution ([SYMBION](https://github.com/angr/angr))

* 2020 Mousse: A System for Selective Symbolic Execution of Programs with Untamed ([Mousse](https://github.com/trusslab/mousse))

* 2020 Device-agnostic Firmware Execution is Possible: A Concolic Execution Approach for Peripheral Emulation ([Laelaps](https://github.com/dongmu/Laelaps))

* 2021 Automatic Firmware Emulation through Invalidity-guided Knowledge Inference ([uEmu](https://github.com/MCUSec/uEmu))

* 2021 Jetset: Targeted Firmware Rehosting for Embedded Systems ([Jetset](https://github.com/aerosec/jetset/))

* 2022 Fuzzware: Using Precise MMIO Modeling for Effective Firmware Fuzzing ([Fuzzware](https://github.com/fuzzware-fuzzer/fuzzware))

## Hybrid Fuzzing

* 2016 Driller: Augmenting Fuzzing Through Selective Symbolic Execution ([Driller](https://github.com/shellphish/driller))

* 2019 Intriguer: Field-Level Constraint Solving for Hybrid Fuzzing ([Intriguer](https://github.com/seclab-yonsei/intriguer))

* 2019 Matryoshka: Fuzzing Deeply Nested Branches

* 2019 Send Hardest Problems My Way: Probabilistic Path Prioritization for Hybrid Fuzzing ([DigFuzz](https://github.com/shouc/digfuzz))

* 2019 Grey-box Concolic Testing on Binary Code ([Eclipser](https://github.com/SoftSec-KAIST/Eclipser))

* 2020 PANGOLIN: Incremental Hybrid Fuzzing with Polyhedral Path Abstraction

* 2020 SAVIOR: Towards Bug-Driven Hybrid Testing ([SAVIOR](https://github.com/evanmak/savior-source))

* 2021 Fuzzing Symbolic Expressions ([FUZZY-SAT](https://season-lab.github.io/fuzzolic/))

* 2021 LeanSym: Efficient Hybrid Fuzzing Through Conservative Constraint Debloating

* 2022 JIGSAW: Efficient and Scalable Path Constraints Fuzzing ([JIGSAW](https://github.com/R-Fuzz/jigsaw))

* 2022 CONFETTI: Amplifying Concolic Guidance for Fuzzers ([CONFETTI](https://github.com/neu-se/CONFETTI))

## Engine

* 2008 KLEE: Unassisted and Automatic Generation of High-Coverage Tests for Complex Systems Programs ([KLEE](https://github.com/klee/klee))

* 2011 S2E: A Platform for In-Vivo Multi-Path Analysis of Software Systems ([S2E](https://github.com/S2E/s2e))

* 2016 (State of) The Art of War: Offensive Techniques in Binary Analysis ([Angr](https://github.com/angr/angr))

* 2018 QSYM: A Practical Concolic Execution Engine ([QSYM](https://github.com/sslab-gatech/qsym))

* 2020 Symbolic execution with SymCC: Don't interpret, compile! ([SymCC](https://github.com/eurecom-s3/symcc))

* 2021 SymQEMU: Compilation-based symbolic execution for binaries ([SymQEMU](https://github.com/eurecom-s3/symqemu))

* 2022 SymFusion: Hybrid Instrumentation for Concolic Execution ([SymFusion](https://season-lab.github.io/SymFusion/))

* 2022 SIFT: A Tool for Property Directed Symbolic Execution of Multithreaded Software ([SIFT](https://github.com/sysrel/SIFT))

* 2022 SolSEE: A Source-Level Symbolic Execution Engine for Solidity([SolSEE](https://sites.google.com/view/solsee/))

## Others

* 2019 Computing Summaries of String Loops in C for Better Testing and Refacto ([KLEE-loops](https://srg.doc.ic.ac.uk/projects/loop-summaries/artifact.html))

* 2019 Systematic Comparison of Symbolic Execution Systems: Intermediate Representation and its Generation ([Data](https://www.s3.eurecom.fr/tools/symbolic_execution/ir_study.html))

* 2019 Deferred Concretization in Symbolic Execution via Fuzzing

* 2020 Running Symbolic Execution Forever ([MoKLEE](https://srg.doc.ic.ac.uk/projects/moklee/artifact.html))

* 2021 TASE: Reducing Latency of Symbolic Execution with Transactional Memory

* 2022 SymTuner: Maximizing the Power of Symbolic Execution by Adaptively Tuning External Parameters ([SymTuner](https://github.com/skkusal/symtuner))

* 2022 SYMSAN: Time and Space Efficient Concolic Execution via Dynamic Data-flow Analysis ([SYMSAN](https://github.com/R-Fuzz/symsan))

* 2022 Characterizing and Improving Bug-Finders with Synthetic Bugs

* 2022 SIFT: A Tool for Property Directed Symbolic Execution of Multithreaded Software

* 2022 Can symbolic execution be a productivity multiplier for human bug-finders?

* 2022 SYMBEXCEL: Automated Analysis and Understanding of Malicious Excel 4.0 Macros ([SYMBEXCEL](https://github.com/ucsb-seclab/symbexcel))

* 2022 Symbolic Execution for Randomized Programs
