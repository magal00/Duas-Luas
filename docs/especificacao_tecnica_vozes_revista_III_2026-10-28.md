# Especificação técnica de voz e revista — Capítulo III

Registro de 28/10/2026. Versão completa disponível no arquivo `Especificacao_Tecnica_Vozes_Revista_III_2026-10-28.md` entregue no chat. A especificação cobre: vozes e interpretação, segmentação, sincronização, iPhone/Safari, segurança, fluxo de revisão e prompt mestre de implementação.

Estado: **documento de produção; síntese de voz e integração não executadas nem homologadas**.

Fonte obrigatória: `Registro_Dialogos_Aprovados_Capitulo_III_2026-10-28.docx`. **Todas as páginas 01–20 aprovadas**, incluindo variantes 06A–10A, 06B–10B, 14A e 14B. Narração integral deve ser consolidada antes de geração, pois o documento de diálogos não a inclui inteira.

**Nota:** a contagem correta, conforme enumeração atual, é 20 páginas por percurso e 26 nós únicos (5+10+3+2+6). Não nomear a estrutura colossal como nave antes da revelação.

## Tarefas do agente programador
1. Ingerir fontes aprovadas e apontar narrações faltantes.
2. Separar cada página em narrador/anão/mago/SFX/silêncio.
3. Testar vozes expressivas em PT-BR, nunca ler nomes de locutores.
4. Gerar clips pré-gravados em backend com credenciais seguras e cache.
5. Sincronizar balões HTML e narração por segmento; permitir texto OFF/ON.
6. Testar navegação, rotas, áudio iOS Safari e fallback manual de play.
7. Requerer aprovação humana das vozes e imagens antes de publicar.

Consultar o documento técnico completo antes de implementar.
