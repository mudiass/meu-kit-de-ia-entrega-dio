# Meu Kit de IA

Desafio de Projeto da [DIO](https://dio.me/): monte o seu kit de IA para o dia a dia e delegue uma tarefa real, com você no comando.

Este repositório documenta a aplicação prática dos modelos do [Meu Kit de IA da DIO](https://github.com/digitalinnovationone/meu-kit-de-ia). A proposta foi usar IA para organizar uma atividade real: preparar a rotina semanal de estudos para processos seletivos de estágio em tecnologia.

**Copie → adapte → teste → confira → melhore**

## Minha Entrega

### Minha Tarefa Real

Escolhi organizar minha preparação semanal para processos seletivos de estágio na área de tecnologia.

Essa tarefa é relevante porque as oportunidades de estágio podem cobrar conteúdos diferentes, como lógica de programação, Java, SQL, desenvolvimento web, APIs e raciocínio lógico. Sem uma organização, posso estudar assuntos sem prioridade ou deixar de revisar pontos importantes.

O objetivo foi transformar essa preparação em uma rotina semanal objetiva, com atividades práticas e critérios simples para acompanhar o andamento. A IA foi usada como apoio à organização; a escolha do que estudar e a validação do plano continuam sob minha responsabilidade.

### Meus Atalhos

Adaptei dois pedidos reutilizáveis. O primeiro ajuda a analisar uma oportunidade; o segundo transforma os requisitos identificados em um plano de preparação.

#### Atalho 1 — Análise de oportunidade

**Modelo de origem:** prompt de pesquisa e decisão, seguindo o fluxo pergunta → pesquisa → critérios → comparação → decisão.  
**O que fica fixo:** papel de analista, categorias de análise, exigência de separar fatos de inferências e proibição de inventar qualificações.  
**O que muda:** descrição da oportunidade, empresa, requisitos e tecnologias.

O prompt completo está em [`prompts/01-analise-de-oportunidade.md`](prompts/01-analise-de-oportunidade.md).

#### Atalho 2 — Planejamento semanal

**Modelo de origem:** bom pedido estruturado com contexto, instrução, objetivo e formato.  
**O que fica fixo:** papel de tutor, divisão semanal, atividades práticas, revisão e critérios de acompanhamento.  
**O que muda:** objetivo do processo seletivo, conteúdos prioritários, disponibilidade de tempo e prazo.

O prompt completo está em [`prompts/02-planejamento-semanal.md`](prompts/02-planejamento-semanal.md).

### Minha Delegação

Usei o template oficial de delegação da DIO, preservando os cinco elementos: **objetivo, contexto, recursos, limites e sucesso**. O pedido adaptado está em [`delegacao/pedido-delegacao.md`](delegacao/pedido-delegacao.md).

### O Plano da IA

Antes de executar a organização, a IA propôs:

1. Definir o resultado esperado e considerar o contexto informado.
2. Separar os conhecimentos a revisar em blocos de estudo.
3. Distribuir os blocos ao longo de uma semana.
4. Incluir prática e revisão, em vez de apenas leitura.
5. Definir como conferir se o plano é realista e útil.

**Ajuste aplicado:** mantive o plano como uma sugestão inicial e evitei presumir domínio avançado de qualquer tecnologia. O cronograma prioriza fundamentos e prática, podendo ser adaptado conforme a vaga específica.

O registro textual do plano está em [`execucao/01-plano-da-ia.md`](execucao/01-plano-da-ia.md).

### O Resultado

A delegação foi executada e gerou um cronograma semanal de preparação, com foco em fundamentos, prática e revisão. O resultado completo está em [`execucao/02-resultado.md`](execucao/02-resultado.md).

A entrega foi conferida com o checklist **Pare, Confira, Use** da DIO:

- **Pare:** considerei o impacto de seguir um plano inadequado e tratei o cronograma como orientação, não como garantia de aprovação.
- **Confira:** verifiquei se as atividades estavam relacionadas ao objetivo, se a carga era compreensível e se o texto não atribuía conhecimentos não confirmados.
- **Use:** o plano pode ser usado como ponto de partida e ajustado conforme a descrição da vaga e o tempo realmente disponível.

O registro da conferência está em [`validacao/pare-confira-use.md`](validacao/pare-confira-use.md).

### Como Foi para Você

A IA ajudou a transformar uma intenção ampla — estudar para processos seletivos — em etapas menores e organizadas. O principal ganho foi ter uma sequência de atividades e critérios para revisar o planejamento, em vez de decidir todos os dias do zero.

Também ficou claro que delegar não significa aceitar qualquer resposta: foi necessário definir limites, conferir se o plano fazia sentido e manter a decisão final comigo.

## Evidências

Os registros textuais do plano, do resultado e da validação estão incluídos neste repositório. A atividade original da DIO solicita capturas de tela das interações. Para não apresentar imagens simuladas como se fossem capturas reais, a pasta [`evidencias/`](evidencias/README.md) explica como adicionar prints autênticos da conversa antes da entrega final na plataforma.

## Referências do kit oficial

- [Template: Delegar uma Tarefa para a IA](https://github.com/digitalinnovationone/meu-kit-de-ia/blob/main/02-templates/03-delegacao.md)
- [Template: Pesquisa e Decisão com IA](https://github.com/digitalinnovationone/meu-kit-de-ia/blob/main/02-templates/02-pesquisa-e-decisao.md)
- [Checklist: Pare, Confira, Use](https://github.com/digitalinnovationone/meu-kit-de-ia/blob/main/03-checklists/01-pare-confira-use.md)
- [Repositório original — Meu Kit de IA](https://github.com/digitalinnovationone/meu-kit-de-ia)

> A IA pode ajudar a escrever, pesquisar, organizar e executar. A responsabilidade pelo resultado continua sendo minha.
