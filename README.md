# DagMeister

**Build, run, and watch any workflow, from data pipelines to AI agents.**

DagMeister is a cloud platform for teams that need their work to run reliably every time. Sign in from your
browser, connect your files, databases, and services, describe the steps in a visual graph, and DagMeister
runs them in order, retries what fails, and keeps a full record of every run. There is nothing to install
or maintain.

Use it for anything that happens in a sequence: moving and cleaning data, processing files as they arrive,
running nightly jobs, or orchestrating AI agents that read documents, make decisions, and act on the results.

---

## What you can do with it

- **Process data as it arrives.** Watch folders, SFTP servers, and S3 buckets. When a file lands, DagMeister
  reads it, loads it into your database, and starts the workflows that depend on it. Common formats such as
  CSV, Excel, and fixed-width files are supported out of the box, along with industry formats such as EDI
  and X12.
- **Transform data with SQL.** Write the transformations you already know, run them against your own
  databases, and chain them together in the order they need to run.
- **Automate anything with code.** Add Python or Bash steps for custom logic, calls to external services, or
  anything else you can script.
- **Orchestrate AI agents.** Build agent workflows that fetch documents, call language models, make
  decisions, and pass results to the next step. Every agent run is logged, retried on failure, and easy to
  review.
- **Run big jobs on demand.** Submit Spark and PySpark jobs to Amazon EMR Serverless from any step, and
  DagMeister waits for the result before moving on.
- **Schedule and chain work.** Run workflows on a cron schedule in any timezone, trigger one workflow from
  another, or start a run with one click.

---

## Built for reliability

- **See everything.** The visual graph shows each step as it runs, with live status updates.
- **Recover automatically.** Failed steps retry on their own. If something still fails, you can rerun a
  single step, a step and everything after it, or the whole workflow.
- **Keep the history.** Every attempt keeps its own log, so you can see exactly what happened and when.
- **Stay in control of secrets.** Shared settings and credentials are kept per environment and hidden in
  logs.
- **Test before you go live.** Pipelines are scoped to staging or production, and a workflow can be
  promoted from one to the other once it's ready.
- **Isolate each step.** Steps can run in their own container, so one workflow can't interfere with another.

---

## Connectors and tools

DagMeister connects to the places your work already lives, and it's built to grow with them.

- **Files and storage:** local disk, SFTP, and Amazon S3
- **Databases:** PostgreSQL, with a built-in query tool for exploring data
- **Cloud compute:** Amazon EMR Serverless and AWS Glue
- **AI and agents:** language model calls and agent steps inside any workflow
- **Tools and integrations:** a growing library of ready-made connectors and tools so you can wire up new
  services without writing the integration yourself

---

## Who it's for

- **Data teams** who want reliable pipelines without a pile of scripts to maintain
- **Operations teams** who need recurring work to run on time and to show what happened
- **Builders of AI agents** who want their agents to run like production software
- **Organizations** that need separate workspaces for each customer, team, or environment

---

## License

Copyright © 2026 [Company Name]. All rights reserved.

DagMeister is proprietary software. Its source code and documentation are not licensed for use,
copying, modification, or distribution without written permission. DagMeister is offered as a hosted
service, and access is governed by the terms agreed with the service provider.
