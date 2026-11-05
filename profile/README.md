<p align="center">
  <img src="https://account.embarkai.io/assets/embark-ai.svg" alt="EmbarkAI" width="768" style="width: auto; max-width: 768px;" />
</p>

Smart account infrastructure for Web3 — Account Abstraction (ERC-4337) with MPC wallet security.

## Packages

| Package                                                 | Description                                    | Docs                                             |                                                                                                         |
| ------------------------------------------------------- | ---------------------------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| [@embarkai/core](https://github.com/embark-ai/core)     | Framework-agnostic SDK for Node.js and browser | [Core SDK](https://docs.embarkai.io/core-sdk)         | [![npm](https://img.shields.io/npm/v/@embarkai/core)](https://www.npmjs.com/package/@embarkai/core)     |
| [@embarkai/ui-kit](https://github.com/embark-ai/ui-kit) | React components and hooks                     | [Frontend SDK](https://docs.embarkai.io/frontend-sdk) | [![npm](https://img.shields.io/npm/v/@embarkai/ui-kit)](https://www.npmjs.com/package/@embarkai/ui-kit) |
| [@embarkai/mcp](https://github.com/embark-ai/mcp)       | MCP server — blockchain tools for AI agents    | [AI Agents](https://docs.embarkai.io/ai-agents)       | [![npm](https://img.shields.io/npm/v/@embarkai/mcp)](https://www.npmjs.com/package/@embarkai/mcp)       |

## Get Started

```bash
# Backend
npm install @embarkai/core viem
# server wallets (DKG and signing) also need the TSS WASM module
npm install dkls23-wasm

# Frontend (React)
npm install @embarkai/ui-kit @tanstack/react-query i18next react-i18next

# AI Agents (Claude Code / Claude Desktop)
npm install @embarkai/mcp
```
