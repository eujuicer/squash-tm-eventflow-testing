# Test management with Squash TM — EventFlow lab

Lab on the complete test management cycle carried out during my QA Tester training (Bruxelles Formation / Cefora), using the **Squash TM** tool, run locally with Docker (`docker-compose.yml`).

Application under test: **EventFlow Sandbox**, provided by the trainer — see [Davit-Ners-Bstorm/BXL-FORMATION-QA-ENGINEER-labo-squash](https://github.com/Davit-Ners-Bstorm/BXL-FORMATION-QA-ENGINEER-labo-squash).

This repository contains my notes and analyses on the whole test management chain (Need → Requirement → Test case → Campaign → Iteration → Execution → Result). The documents themselves are written in French:

- analysis of an execution rate and a campaign success rate (`1. Taux d'exécution.txt`)
- risk-based testing matrix to prioritize test cases by impact and probability
- acceptance report (GO / conditional GO / NO-GO) with acceptance criteria
- Gherkin / BDD scenarios (booking, payment, login, cancellation) and UAT scenarios

Goal: demonstrate a concrete application of the test management and analysis techniques learned during the training (requirement ↔ test case traceability, risk-based prioritization, BDD writing, product acceptance), beyond simple manual execution.
