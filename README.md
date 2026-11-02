# Rost M

Senior software engineer in Vancouver. Eight years of full-stack work, most of it in 0→1 startups, and the last stretch on AI features running in production with real people depending on them. Lately I build agents and then test them as hard as I build them.

## Restaurant ops agent

[Site](https://restaurant-ops-agent.vercel.app) · [Code](https://github.com/rostgoat/restaurant-ops-agent)

An agent that answers a restaurant owner's questions from their sales data and written policies, and proposes actions a person approves before anything happens. Code parses every query it writes, limits it to one restaurant, runs it read-only, and checks every proposed action against the owner's own limits.

39 test questions with the answers written down first. Ten runs, one change per run, every failure and every trace published. 34 of 38 on the first run, 39 of 39 on the tenth. Python, FastAPI, Next.js, Postgres with pgvector, Claude.

## Work nobody notices

- A FedEx integration behind a carrier migration that saves about $1.5M a month in shipping.
- A nightly warehouse ETL cut from 13 hours to 3 across 3.5M rows.
- An inventory report cut from 15 minutes to 1, with checks so it stays that way.

## Stack

Python, Django, FastAPI, GraphQL · TypeScript, React, Next.js · PostgreSQL, AWS, Kubernetes · Claude, embeddings and vector search.

Open to applied AI roles, including US relocation. [LinkedIn](https://www.linkedin.com/in/rostmyshkin/)
