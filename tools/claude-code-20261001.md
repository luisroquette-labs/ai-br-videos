# Claude Code

Claude Code é o agente de programação da Anthropic que roda direto no terminal. A versão 2.1.286 chega com 88 mudanças na CLI. Nenhuma delas é chamativa, mas várias afetam o fluxo diário de quem usa o agente em sessões longas.

## Por que importa

Três correções merecem atenção.

A primeira: prompts de permissão agora mostram contadores como "2 de 5" quando várias requisições empilham. Você vê quantas faltam antes de decidir aprovar ou negar em lote. Menos contexto perdido no meio de uma tarefa.

A segunda: quando a API da Anthropic recusa um modelo, a sessão tenta uma vez com o modelo anterior. Isso evita falhas repetidas a cada turno — um problema comum em sessões longas com rate limits ou mudanças de disponibilidade.

A terceira é a mais séria: o redaction de logs foi corrigido para mascarar segredos mesmo quando os nomes das chaves contêm caracteres invisíveis. Isso fecha um vetor de vazamento que passaria despercebido em revisão manual. Se você usa secrets em variáveis de ambiente ou arquivos de config, atualize antes do próximo deploy.

---

**Fonte original:** https://x.com/ClaudeCodeLog/status/2105377563698696459

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
