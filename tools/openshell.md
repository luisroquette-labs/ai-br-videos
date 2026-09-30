# OpenShell

OpenShell é a ferramenta da NVIDIA para conter agente de IA durante avaliação e teste. A ideia é direta: o modelo roda isolado, sem acesso ao sistema além do que foi explicitamente liberado. O nome não é à toa — você interage com o agente dentro de um ambiente controlado, com monitoramento de atividade.

## Por que importa

O Jensen Huang foi enfático: nunca confie que o modelo está contido. Mesmo com isolamento, é preciso observar o que o agente faz. OpenShell ataca exatamente isso — dá uma jaula e um log do que acontece dentro dela. Para time que está testando agente com ferramentas, isso separa "funcionou" de "quase vazou".

## Como começar

Clone o repositório e leia o README. O projeto tem exemplos de configuração de ambiente isolado. Rode um agente de teste dentro do shell e acompanhe os logs. Se o agente tentar acessar algo fora do permitido, o shell bloqueia e registra. Ajuste as permissões conforme o comportamento esperado.

---

**Fonte / repositório original:** https://github.com/NVIDIA/OpenShell

**Visto primeiro em:** https://x.com/XFreeze/status/2105097131493372217

**Veja o vídeo:** [@ai_br_videos no Instagram](https://instagram.com/ai_br_videos)
