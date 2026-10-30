# Oğuzhan Balım

Product and technology leader who builds AI-driven platforms for government, elite sport and enterprise finance.
Istanbul, Türkiye (UTC+3) · open to relocation to the UK or EU.

**Anthropic Claude Certified Architect:** Foundations (CCAR-F) and Professional (CCAR-P).

## Open source

Agents on Claude where code computes the numbers, the model explains them and a human approves anything that matters. Each README separates what has been measured from what has not yet run.

**Agents**
- [agentic-ledger-sleuth](https://github.com/oguzhanbalim/agentic-ledger-sleuth): investigates reconciliation exceptions and suspicious transactions on synthetic ERP data, over MCP, with a deterministic evidence gate.
- [agentic-touchline](https://github.com/oguzhanbalim/agentic-touchline): football match analysis on StatsBomb Open Data (Arda Güler and more), with a player conversation in Turkish, Spanish and English.
- [agentic-volunteer-desk](https://github.com/oguzhanbalim/agentic-volunteer-desk): reference design for an event-volunteer assistant. Cited answers only; emergencies bypass the model in code.
- [agentic-approval-gate](https://github.com/oguzhanbalim/agentic-approval-gate): agents propose, people approve, with a hash-chained log.

**Trust and evals**
- [llm-receipts](https://github.com/oguzhanbalim/llm-receipts): every number in an LLM answer must show its receipt.
- [injection-gauntlet](https://github.com/oguzhanbalim/injection-gauntlet): fifty hidden instructions, a canary in each, in English and Turkish.
- [citation-verifier](https://github.com/oguzhanbalim/citation-verifier): checks that citations really exist in the source.
- [llm-golden](https://github.com/oguzhanbalim/llm-golden): golden-set evals with a locked test split and judge calibration.

**Agent infrastructure**
- [mcp-guardrail](https://github.com/oguzhanbalim/mcp-guardrail): a firewall for MCP tool calls.
- [agent-flight-recorder](https://github.com/oguzhanbalim/agent-flight-recorder): record, replay and diff agent runs.
- [agent-trace-viewer](https://github.com/oguzhanbalim/agent-trace-viewer): one HTML file for any transcript.
- [agent-cost-meter](https://github.com/oguzhanbalim/agent-cost-meter): cost per task, with a CI budget check.

**Linters for the Claude stack**
- [messages-api-lint](https://github.com/oguzhanbalim/messages-api-lint): finds stale Messages API usage.
- [tool-schema-lint](https://github.com/oguzhanbalim/tool-schema-lint): lints tool definitions.
- [agent-skill-lint](https://github.com/oguzhanbalim/agent-skill-lint): lints Agent Skill packages.
- [prompt-cache-lens](https://github.com/oguzhanbalim/prompt-cache-lens): finds why prompt caching misses.

**Turkish and finance**
- [pii-shield-tr](https://github.com/oguzhanbalim/pii-shield-tr): masks Turkish personal data before it reaches an LLM.
- [turkish-rag-kit](https://github.com/oguzhanbalim/turkish-rag-kit): retrieval that respects Turkish.
- [ledger-forensics](https://github.com/oguzhanbalim/ledger-forensics): deterministic forensic accounting on a CSV.

## How I build

I work with Claude Code every day. I own the architecture, the interface contracts and the golden tests; Claude Code does much of the implementation across parallel worktrees. More than 1,100 commits in iFinances alone were co-authored with it.

My product and client work lives in private repositories. I'm happy to walk through the architecture and the trade-offs on a call.

## Stack

Python · TypeScript · SQL · PostgreSQL · Flask · React · Next.js · Node.js · Docker · applied ML · LLM applications · Claude Code

[LinkedIn](https://www.linkedin.com/in/o%C4%9Fuzhan-bal%C4%B1m)
