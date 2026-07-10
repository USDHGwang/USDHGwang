# John Wang

Agent × Web3 authorization — making sure an AI agent's on-chain actions
stay inside what the user actually signed, even when the agent itself is
deceived or compromised.

A model generating an action is not the same as that action being
authorized. I work on that gap from both ends:

| Project | What it does | Evidence |
|---|---|---|
| [aip-protocol](https://github.com/USDHGwang/aip-protocol) | On-chain enforcement: intent-execution consistency inside one atomic transaction (ERC-7579 Hook + EIP-1153 transient storage) | 44 tests on mainnet fork; deployed on 0G mainnet |
| [EIV-Core](https://github.com/USDHGwang/EIV-Core) | Off-chain independent verification: did an executed tx comply with the signed authorization? Zero-dependency Python, EIP-712 → deterministic verdict | Z.AI track 3rd @ AI × Web3 School Hackathon (73 teams); flags a real $175K drain tx as FAIL |
| [aip-safeharness](https://github.com/USDHGwang/aip-safeharness) | Verifiable agent execution lifecycle: agent loop + 0G Storage + AIP on-chain enforcement | Live on 0G Aristotle mainnet |

Next: how authorization should propagate between agents.

X: [@0xUSDHG](https://x.com/0xUSDHG)## Hi there 👋

<!--
**USDHGwang/USDHGwang** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
