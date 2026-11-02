# Rost M

Senior software engineer in Vancouver building AI products. Eight years
across backend systems, web apps, and early-stage startups. I build agents
and test them as hard as I build them.

Open to applied AI roles, including US relocation.

## Restaurant ops agent

[Demo & case study](https://restaurant-ops-agent.vercel.app) · [Code](https://github.com/rostgoat/restaurant-ops-agent)

An agent that answers a restaurant owner's questions using sales data and
written policies, then proposes actions for a person to approve.

The model proposes. Code controls what can run:
- SQL is parsed, scoped to one restaurant, and executed read-only.
- Proposed actions are checked against the owner's limits.
- Actions require human approval.

Published ten evaluation runs with failures, fixes, and execution traces.
The suite grew from 38 to 39 cases: 34/38 passed on the first run, 39/39
on the tenth.

The case study includes expected behavior, actual responses, and per-run
cost and latency. It uses fictional restaurants and generated sales data;
action execution is simulated.

Built with Python, FastAPI, Next.js, PostgreSQL/pgvector, and Claude.

## Work nobody notices

- Built the FedEx integration behind a carrier migration saving about
  $1.5M/month in shipping.
- Cut nightly warehouse ETL from 13 hours to 3 across 3.5M rows.
- Cut an inventory report from 15 minutes to 1 and added checks to catch
  future schema failures.

## Stack

Python, Django, FastAPI, GraphQL · TypeScript, React, Next.js ·
PostgreSQL, AWS, Kubernetes · Claude, embeddings, vector search

[LinkedIn](https://www.linkedin.com/in/rostmyshkin/)
