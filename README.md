# Kirill Smirnov

I build data warehouses and the teams that run them.
Remote-first. My location is a Type 2 dimension — history preserved, current row somewhere in GMT+3.

[LinkedIn](https://www.linkedin.com/in/smirnovkirilll)

## What I do

- Deputy head of engineering for an analytical DWH — grew the team from zero to about a dozen
- The warehouse: ~1000 data objects, ~1 PB, ingest from external perimeters, reactive pipelines, layered architecture
- I set the engineering standards — code review, on-call, incident policy, sprints — and still ship pipelines myself. Mostly so nobody can tell me the standards are unrealistic
- Before that: five years at a ride-hailing bigtech — a ~5 PB warehouse, led its largest engineering group, engineer → team lead
- There I prototyped an approach to data-quality monitoring that became the standard in our in-house data platform — roughly ten warehouses, a couple hundred engineers still work that way

## Strong opinions

**The harness decides the outcome, not the model.** Picking a model is the least interesting part of the job. What works is the scaffolding: the context you set, the boundaries you draw, the steps you can verify, the antipatterns you write down. Corollary — an agent reporting success is not evidence of success. Go look.

**Story points are a tax.** I introduced them in 2023 and ran the planning poker myself, down to backfilling actuals and comparing them against the estimates. Having performed the entire ritual, I dropped it the day I started building the current team, and wrote down why. Sprints yes, planning yes, poker no. I'll argue this as someone who built the process rather than avoided it.

**Find the constraint.** A system moves at the speed of its bottleneck. Optimising anything else is cardio. (Hi, Goldratt.)

## Stack

Python and SQL day to day, YQL when the data lives on YTsaurus. Greenplum and ClickHouse for analytics, Kafka and Airflow to move things around, Terraform so the infrastructure is a file rather than a memory. Claude Code, plus a pile of agent skills I wrote myself — and ChatGPT, which gets the questions I'd be embarrassed to ask a colleague.

## Weekend builds

- [lookmomimadataengineer](https://github.com/smirnovkirilll/lookmomimadataengineer) — a curated must-read / must-watch list on the data landscape
- [gridkit](https://github.com/smirnovkirilll/gridkit) — thin wrapper over AG Grid that turns a JSON file into a filterable table site
- [properly_made_dictionary](https://github.com/smirnovkirilll/properly_made_dictionary) — Turkish–English dictionary as a table you can actually filter
- [i_know_words](https://github.com/smirnovkirilll/i_know_words) — a menubar app for people who obviously don't know all the words yet
- [document_preprocessor](https://github.com/smirnovkirilll/document_preprocessor) — primary processing of document photographs, so that OCR stands a chance

Common thread: the list is the work. The table around it is a thin wrapper over someone else's grid — writing my own would be optimising the wrong thing.

## Say hi

I'm employed, not unavailable — those are different things.

Warehouse architecture, engineering process, growing a data team without breaking it — happy to talk about any of it. Consulting and advisory too.

Find me on [LinkedIn](https://www.linkedin.com/in/smirnovkirilll). My inbox is append-only.
