# CS230-Speculators
Repo for CS230 Project 

**Project Topic: Data prefetching for SPEC, SAT solvers, Servers, and Graph Analytics**


**Tasks:** 
- Evaluate existing prefetchers and propose enhancements 
- Check the prefetching folder of ChampSim and make your changes

Roll Numbers:
210050008 - Akkapally Shasmith Krishna <br>
210050167 - Vutukuri Vinay Mohan <br>
210050130 - R Pragnan Maharshi <br>
210050114 - Prahashith Pasnoor <br>

Link for Project Details: https://docs.google.com/document/d/1jjadc53Z0DxNcrOkxFYAKPgoQLXBbqPUuWe3zEu17xg/edit <br>
Link for Research Paper:  https://dpc3.compas.cs.stonybrook.edu/pdfs/Bouquet.pdf <br>
Traces we have done our improvements on..

**SPEC Traces**<br><br>
600.perlbench_s-570B.champsimtrace.xz<br>
605.mcf_s-994B.champsimtrace.xz<br>
620.omnetpp_s-141B.champsimtrace.xz<br>
657.xz_s-2302B.champsimtrace.xz<br>
654.roms_s-294B.champsimtrace.xz<br>
602.gcc_s-2226B.champsimtrace.xz<br>
607.cactuBSSN_s-3477B.champsimtrace.xz<br>

**Graph Traces**<br><br>
sssp-5<br>
cc-5<br>
pr-3<br>
bfs-3<br>
bc-0<br>

# Implementation
We have implemented following changes
In l1d - used prefetch_degree based on confidence<br>
In l2c - implemented complex stride prefetcher<br>
In llc - implmented ipcp <br>
# Contributions
Shasmith Krishna - Code Changes, Presentation
Vinay Mohan - Data Analysis of Graph, Presentation
Prahasith Pasnoor - Data Analysis of SPEC, Presentation
Pragnan Maharshi - Code Changes





