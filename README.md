# Umbra - Discord AI Agent (RAG & Function Calling)

> ⚠️ **Nota de Engenharia:** Este repositório documenta a arquitetura de integração do agente. O código-fonte original é mantido em um repositório privado para proteger a propriedade intelectual da lógica de *Prompt Engineering* e *System Instructions*.

Umbra é um agente autônomo desenvolvido para o Discord, arquitetado para atuar como um assistente técnico especializado em mecânicas e comandos de Minecraft Bedrock. 

Ao invés de depender apenas do conhecimento estático do LLM, o sistema utiliza **Function Calling (Tools)** integrado à API do Gemini para realizar chamadas dinâmicas (RAG). A IA toma decisões autônomas para consultar o banco de dados da Minecraft Wiki via API e ler arquivos JSON locais de sintaxe antes de responder ao usuário, garantindo precisão factual em tempo real.

**Stack:** Node.js, `discord.js`, `@google/generative-ai` (Gemini 2.5), Consumo de APIs REST.
