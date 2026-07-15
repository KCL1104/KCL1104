## Chi Lin Kuo (Charlie)

Backend engineer in Taiwan. LLM agent systems and Solana.

Agent work is most of what I do. Multi-agent orchestration, MCP servers, tool integration, RAG pipelines, and the harness around all of it that decides whether the output is shippable. I've built agent features into production products, and I build my own tooling for the agents I work with daily: MCP servers and agent skills for issue triage, code review, commit standardization.

The rest is Solana programs in Anchor and the services that sit between them and users. Next.js on the frontend when I need to own a feature end to end.

🏆 Encode Solana Hackathon, Cypherpunk side track (hosted by Sanctum)
🏆 AI Financial Innovation Hackathon, winner

<!-- delete this line if you don't want it public -->
Currently looking for backend / AI agent engineering work. Remote or Taipei.

---

### Projects

**[LorePack](https://github.com/KCL1104/LorePack)**
Collaborative storytelling platform. Users build persistent worlds; specialised agents generate illustrated chapters across them. Built on Google ADK, with A2A protocol handling inter-agent messaging, task delegation, and result aggregation. The interesting part was not the generation, it was making a set of agents hand work to each other without the context falling apart.
`Google ADK` `A2A` `FastAPI` `Next.js`

**[PinTool](https://demo.pintool.fun/)**
Solana strategy automation. Creators publish on-chain strategies, subscribers pay for access in USDC on chain. I built the backend architecture, the subscription verification logic, and the Anchor integration, including keeping on-chain and off-chain state in sync.
`NestJS` `Anchor` `Solana` `Supabase` `TypeScript`

**[DeepFlow](https://github.com/KCL1104/DeepFlow)**
Takes webhooks from Slack, Jira and Gmail, runs each one through an agent layer that parses the signal and scores urgency, then serves them back in priority order. The queue is a Redis sorted set, so reordering stays O(log N).
`LangChain` `FastAPI` `Redis` `Next.js`

---

### Stack

**Agents** Multi-agent orchestration, MCP, RAG, tool calling, LangChain, Google ADK, Pydantic AI
**Backend** Node.js, NestJS, Python, FastAPI, PostgreSQL, Supabase, Redis, MongoDB
**Chain** Solana, Anchor
**Frontend** TypeScript, React, Next.js
**Infra** Docker, CI/CD

---

[Portfolio](https://kcl1104.github.io/) · [LinkedIn](https://www.linkedin.com/in/chi-lin-kuo-a47608209/) · [charlie011111@gmail.com](mailto:charlie011111@gmail.com)
