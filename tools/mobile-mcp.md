# mobile-mcp

O mobile-mcp é um servidor MCP que conecta sua IA a dispositivos móveis — emuladores de iOS e Android ou aparelhos físicos (com free tier). Com isso, Claude Code, Codex ou Gemini conseguem operar o aparelho: abrir apps, navegar pela interface, inspecionar elementos e até corrigir bugs, como no vídeo em que o Claude encontrou 3 problemas num app e resolveu sozinho.

## Por que importa
Teste de app mobile é manual e repetitivo. Com um servidor MCP, a IA opera o dispositivo como um humano faria, mas com repetição consistente de fluxo e validação de comportamento. Isso encurta o ciclo entre escrever o código e ver o resultado rodando num aparelho real. O projeto é open source, então dá para adaptar ao seu fluxo de QA ou desenvolvimento.

## Como começar
Clone o repositório e leia o README. O servidor expõe as ferramentas via protocolo MCP, então você configura o cliente (Claude Code, Codex, Gemini etc.) para apontar para ele e conecta um emulador ou dispositivo físico. Depois disso, é só pedir para a IA interagir com o app e reportar o que encontrar.

---

**Fonte / repositório original:** https://github.com/mobile-next/mobile-mcp

**Visto primeiro em:** https://x.com/midudev/status/2104210723408597366

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
