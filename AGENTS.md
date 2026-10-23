# Instruções do projeto

## Memória persistente no Obsidian

A memória do projeto é obrigatória em todas as tarefas, inclusive investigações, revisões e alterações apenas documentais. Não conclua uma tarefa sem consultar e atualizar as notas relevantes.

### Ao iniciar

1. Leia `/home/rodrigo/Obsidian/Personal/Dev/Projetos/Securo/Securo.md` para localizar as notas.
2. Leia `Contexto.md`, `Bugs e TODOs.md` e a sessão mais recente em `Sessões.md`.
3. Consulte `Decisões.md` antes de fazer escolhas que afetem comportamento, arquitetura, deploy ou compatibilidade.
4. Confirme no código e na documentação do repositório qualquer detalhe técnico que possa ter mudado.

### Durante e ao concluir

- Registre descobertas duráveis e decisões com motivo nas notas correspondentes; não espere até o fim quando isso puder evitar perda de contexto.
- Antes de concluir, acrescente uma entrada no topo de `Sessões.md` com o que mudou ou foi investigado, verificações executadas, limites conhecidos e próximo passo.
- Atualize `Contexto.md` quando a configuração ou o comportamento atual mudar. Registre decisões duráveis em `Decisões.md` e mantenha `Bugs e TODOs.md` alinhado: feche itens resolvidos e acrescente pendências confirmadas.
- Preserve entradas históricas. Não copie documentação extensa do repositório para o vault; mantenha resumos concisos e links para as fontes oficiais.
- Não registre credenciais, tokens, chaves privadas, segredos de `.env` nem dados financeiros ou pessoais privados.
- Revise os links Obsidian das notas alteradas e informe na resposta que a memória foi atualizada.

Se o vault estiver indisponível, continue o trabalho independente, não afirme que a memória foi atualizada e informe claramente qual registro ficou pendente.

## Comandos privilegiados

- Não execute `sudo` nem outros comandos que exijam elevação de privilégio.
- Se uma etapa realmente precisar de `sudo`, informe o comando exato para o usuário executar em um shell separado e continue apenas com o trabalho que não dependa dessa etapa.
