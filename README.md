# Oi, eu sou o César 👋

Estudante de Engenharia de Software na PUC Minas, em Belo Horizonte. Trabalho com automação e IA aplicada a operações.

## O que já construí

Na Versiani Swim, um e-commerce de moda praia e fitness, construí com o Claude Code cerca de 20 automações em produção, em Node.js e Cloudflare Workers, integrando ERP (Bling), WMS, Shopify, TikTok Shop, Google Sheets, Airtable e Discord:

- **Conferência de estoque** entre ERP e armazém a cada 15 min, reservando a diferença para não vender o que não existe
- **Alerta de ruptura de estoque** migrado de polling para webhook: atraso do dashboard de até 24h para cerca de 15 min
- **Envio automático de NF-e de devolução**, sem duplicar nota, numa operação que chegou a mais de 1.000 trocas e devoluções por mês
- **Painel diário de métricas** com cerca de 20 indicadores de 8 sistemas, preenchido sozinho às 7h

O código é da empresa e não fica público. Os estudos de caso abaixo explicam o problema, a arquitetura e as decisões de cada projeto.

## Estudos de caso

_Em breve._

## Como trabalho com IA

- 10 agentes especializados no Claude Code, um por automação
- Servidores MCP somente-consulta, para que nada mudasse em produção sem teste e aprovação
- Revisão cruzada entre duas IAs (Claude Code e Codex) antes de mexer em código crítico

## Ferramentas

Claude Code · Codex · JavaScript · Node.js · APIs REST · OAuth2 · Webhooks · Cloudflare Workers · GitHub Actions · Make · Google Sheets · Git

## Estudando agora

JavaScript (DOM e eventos), estruturas de repetição e funções, teoria da computação.

## Contato

[LinkedIn](https://www.linkedin.com/in/cesarcasagrandelopes) · ccasagrandelopes@gmail.com
