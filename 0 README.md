# ⏱️ Real Time Systems UUniFast Algorithm Research 

This repository accompanies a research report that provides a clear, structured overview of three core components of real-time systems: **task generation**, **scheduling simulation**, and **schedulability analysis**.

## 📋 Overview

### 🎲 Exercise H — Task Generation
100 periodic task sets are generated using the **UUniFast algorithm** to achieve a target total utilization between 0 and 1, supporting both implicit and constrained deadlines.

### ⚙️ Exercise J — Scheduling Simulation
Real-time scheduling policies are simulated to observe runtime behavior and catch missed deadlines:
- 🥇 **FCFS** — First-Come-First-Served
- ⏳ **SJF** — Shortest Job First
- 🔁 **RM** — Rate Monotonic
- 🎯 **EDF** — Earliest Deadline First

### ✅ Exercise L — Schedulability Analysis
Four schedulability tests are implemented:
- 📈 EDF utilization analysis for implicit deadlines
- 📊 Rate Monotonic (RM) response-time analysis (RTA) for implicit deadlines
- 🧮 EDF demand-based analysis for constrained deadlines
- ⏲️ Deadline Monotonic (DM) response-time analysis (RTA) for constrained deadlines

## 🎉 Summary

Together, these results show **consistent agreement** between simulation outcomes and theoretical schedulability tests — offering a deeper, hands-on understanding of how real-time feasibility can be evaluated experimentally. 🚀

## 📄 Full Report

See the `RTSFinalResearchLinda` file in this repository for complete methodology, results, and discussion. 🔍

In addition, I've provided some of my test files linked to my research analysis for further support. 
