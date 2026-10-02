# Diário de Bordo: O Dilema do Servidor em Nuvem - CloudData

## Visão geral

Este projeto reúne o registro acadêmico e a análise do problema de escalonamento de processos em um ambiente de servidor em nuvem, com foco em como o Sistema Operacional gerencia chamadas de sistema, modo de execução e alocação de CPU.

O trabalho está documentado no arquivo principal: [01-10-2026.MD](01-10-2026.MD).

## Objetivo

Analisar como um processo de geração de relatórios em um sistema cloud interage com o Sistema Operacional, identificando:

- a necessidade de chamadas de sistema para acesso ao disco;
- a diferença entre modo usuário e modo kernel;
- o impacto do algorítmo FCFS em sistemas com tarefas pesadas e interativas;
- a importância de escalonadores preemptivos, como Round-Robin;
- a relação entre starvation e aging no contexto de prioridade de processos.

## Estrutura do material

- [01-10-2026.MD](01-10-2026.MD): texto principal do diário de bordo e análise do tema.
- [diagrama.jpeg](diagrama.jpeg): imagem ilustrativa do fluxo lógico do problema e da solução proposta.

## Conteúdo principal

### Parte A: Entendendo a barreira do sistema

Explora a relação entre processo, Sistema Operacional e hardware, incluindo a atuação de chamadas de sistema e a mudança de modo de execução.

### Parte B: Diagnosticando o escalonador

Aborda o problema causado pelo algoritmo FCFS e explica por que ele pode gerar congelamento em sistemas interativos.

### Parte C: Propondo a solução

Apresenta o Round-Robin como alternativa adequada, além de discutir starvation e aging como mecanismos para manter a justiça e a responsividade do sistema.

## Referências

O trabalho inclui referências de vídeo, podcast e literatura técnica sobre sistemas operacionais e escalonamento, com base no material acadêmico e em fontes citadas no arquivo principal.

## Observação

Este repositório foi organizado para servir como material de apresentação e estudo do tema, com a documentação principal em Markdown e a imagem ilustrativa em arquivo local na mesma pasta.
