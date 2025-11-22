# Plano de Experimento – Scoping e Planejamento  
## Impacto de Micro-Recompensas Gamificadas na Permanência do Usuário

---

## 1. Identificação básica

### 1.1 Título do experimento
Impacto de micro-recompensas gamificadas na permanência de usuários em uma aplicação web.

### 1.2 ID / código
EXP-GAMIF-001

### 1.3 Versão do documento e histórico de revisão
- **v1.0 (22/11/2025)** – primeira versão elaborada para entrega da disciplina.

### 1.4 Datas
- Criação: 22/11/2025  
- Última atualização: 22/11/2025

### 1.5 Autores
- Nome: Arthur  
  Área: Engenharia de Software  
  Contato: (informar)

### 1.6 Responsável principal
Arthur – responsável pelo desenho, execução e análise do experimento.

### 1.7 Projeto relacionado
Estudo acadêmico aplicado ao desenvolvimento de interfaces gamificadas focadas em UX e engajamento.

---

## 2. Contexto e problema

### 2.1 Descrição do problema
Aplicações digitais frequentemente sofrem com baixa permanência e alto abandono durante tarefas simples. Há forte hipótese prática de que micro-recompensas (como badges, pontuação crescente e feedback imediato) aumentem motivação e engajamento, porém evidências empíricas controladas ainda precisam ser avaliadas.

### 2.2 Contexto organizacional e técnico
O experimento será conduzido em ambiente acadêmico, com uma aplicação web simples desenvolvida para teste. Participantes serão estudantes ou usuários convidados, realizando a mesma tarefa em duas versões da aplicação: com e sem micro-recompensas.

### 2.3 Trabalhos e evidências prévias
- Estudos de gamificação indicam que recompensas imediatas aumentam dopamina e engajamento em curto prazo.
- Pesquisas de UX sugerem que feedback instantâneo melhora retenção e satisfação.
- No entanto, resultados variam conforme contexto, reforçando a necessidade de experimentação controlada.

### 2.4 Referencial teórico essencial
- Economia comportamental e reforço positivo (Skinner).
- Estruturas de gamificação como PBL (points, badges, leaderboards).
- Teorias de motivação extrínseca aplicadas a produtos digitais.

---

## 3. Objetivos e questões (GQM)

### 3.1 Objetivo geral
Analisar se a presença de micro-recompensas em uma tarefa digital aumenta a permanência dos usuários, na perspectiva da experiência de uso, em ambiente controlado de teste.

### 3.2 Objetivos específicos
- **O1:** Medir diferenças de tempo médio de permanência entre versões da aplicação.
- **O2:** Avaliar diferença na taxa de conclusão da tarefa.
- **O3:** Analisar retorno voluntário à aplicação após a primeira sessão.
- **O4:** Avaliar engajamento qualitativo e satisfação do usuário com a experiência gamificada.

### 3.3 GQM (Goal — Question — Metric)

| Objetivo | Pergunta | Métricas |
|---|---|---|
| O1: Tempo médio de permanência | Q1.1: A versão gamificada aumenta o tempo total de sessão? | Tempo de sessão; Tempo médio por tarefa |
| O1: Tempo médio de permanência | Q1.2: A gamificação aumenta o número de interações por sessão? | Nº de interações por sessão; Nº de cliques em recompensas |
| O1: Tempo médio de permanência | Q1.3: A gamificação reduz o tempo até a primeira interação? | Tempo até primeira interação; Taxa de abandono |
| O2: Taxa de conclusão | Q2.1: A versão gamificada aumenta % de conclusão da tarefa? | Taxa de conclusão; Nº de tarefas completas |
| O2: Taxa de conclusão | Q2.2: A gamificação reduz retrabalho (retries) durante a tarefa? | Nº de retries; Tempo médio por tarefa |
| O2: Taxa de conclusão | Q2.3: A gamificação altera o ponto médio de abandono dentro da tarefa? | Taxa de abandono; Ponto de abandono médio (%) |
| O3: Retorno voluntário | Q3.1: Usuários retornam mais em 1 dia com gamificação? | Taxa de retorno em 1 dia; Taxa de retorno em 7 dias |
| O3: Retorno voluntário | Q3.2: Gamificação aumenta sessões por usuário na semana? | Sessões por usuário (7 dias); Nº de retornos por usuário |
| O3: Retorno voluntário | Q3.3: Gamificação aumenta a recomendação ou compartilhamento? | Nº de compartilhamentos; Nº de convites enviados |
| O4: Engajamento qualitativo e satisfação | Q4.1: Gamificação melhora satisfação percebida? | Satisfação auto-relatada (Likert); NPS simplificado |
| O4: Engajamento qualitativo e satisfação | Q4.2: Gamificação aumenta a sensação de progresso percebida? | Pontos ganhos; Badges desbloqueados |
| O4: Engajamento qualitativo e satisfação | Q4.3: Gamificação aumenta a interação com feedback imediato? | Taxa de interação com feedback; Tempo de feedback visível |

### 3.4 Tabela de métricas (descrição e unidade)

| Métrica | Descrição | Unidade |
|---|---|---|
| Tempo de sessão | Duração total da sessão do usuário, desde o carregamento até o encerramento | segundos (s) |
| Tempo médio por tarefa | Tempo médio gasto para completar a tarefa proposta | segundos (s) |
| Nº de interações por sessão | Quantidade total de eventos de interação (cliques, submissões, etc.) por sessão | contagem |
| Nº de cliques em recompensas | Número de cliques em elementos de recompensa (badges, botões de pontos, etc.) | contagem |
| Tempo até primeira interação | Tempo desde o carregamento da página até a primeira ação do usuário | segundos (s) |
| Taxa de abandono | Percentual de sessões em que o usuário não concluiu a tarefa | porcentagem (%) |
| Taxa de conclusão | Percentual de usuários que completam a tarefa com sucesso | porcentagem (%) |
| Nº de tarefas completas | Contagem absoluta de tarefas finalizadas | contagem |
| Nº de retries | Número médio de tentativas repetidas para completar a mesma etapa ou tarefa | contagem |
| Ponto de abandono médio (%) | Ponto médio (em percentual de progresso) em que os usuários abandonam | porcentagem (%) |
| Taxa de retorno em 1 dia | Percentual de usuários que retornam à aplicação em até 1 dia após a primeira sessão | porcentagem (%) |
| Taxa de retorno em 7 dias | Percentual de usuários que retornam à aplicação em até 7 dias | porcentagem (%) |
| Sessões por usuário (7 dias) | Média de sessões por usuário no período de 7 dias | contagem |
| Nº de compartilhamentos | Número de vezes que usuários compartilharam conteúdo/convites | contagem |
| Nº de convites enviados | Quantidade de convites enviados pelos usuários a outros possíveis participantes | contagem |
| Pontos ganhos | Soma de pontos acumulados pelo usuário durante a sessão/tarefa | pontos |
| Badges desbloqueados | Contagem de badges ou selos conquistados pelo usuário | contagem |
| Satisfação auto-relatada (Likert) | Avaliação subjetiva do usuário sobre a experiência (pós-tarefa) | escala 1–5 |
| NPS simplificado | Pergunta de recomendação em escala (-100 a 100) simplificada para contexto acadêmico | índice (-100..100) |


---

## 4. Escopo e contexto do experimento

### 4.1 Escopo incluído
- Teste de uma mesma tarefa em duas versões da aplicação.
- Coleta de métricas automáticas.

### 4.2 Escopo excluído
- Análise de motivação de longo prazo.
- Outras técnicas de gamificação não relacionadas a recompensas imediatas.

### 4.3 Premissas
- Ambiente web estável durante o experimento.
- Participantes terão acesso continuado à aplicação.

### 4.4 Restrições
- Amostra limitada a estudantes ou público voluntário.
- Tempo reduzido para coleta de dados.

### 4.5 Limitações previstas
- Generalização pode ser limitada devido a amostragem por conveniência.
- Participantes podem estar mais motivados por se tratar de ambiente acadêmico.

---

## 5. Stakeholders e impacto esperado

### 5.1 Stakeholders principais
- Estudantes/participantes
- Pesquisador
- Professores

### 5.2 Interesses dos stakeholders
- Participantes: experiência direta com aplicação simples.
- Pesquisador: evidências quantitativas.
- Professores: qualidade metodológica do experimento.

### 5.3 Impactos potenciais
- Ajustes futuros em interfaces gamificadas.
- Melhoria de processos de design baseados em dados.

---

## 6. Riscos de alto nível

### 6.1 Riscos
- Baixa taxa de participação.
- Problemas técnicos de coleta de dados.

### 6.2 Critérios de sucesso globais
O experimento é útil se produzir dados suficientes para testar H0 e H1 de forma estatisticamente válida.

### 6.3 Critérios de parada antecipada
- Falha do sistema de coleta.
- Menos de 10 participantes por grupo.

---

## 7. Modelo conceitual e hipóteses

### 7.1 Modelo conceitual
A presença de micro-recompensas aumenta motivação imediata, levando a maior permanência e maior taxa de conclusão.

### 7.2 Hipóteses formais
- **H0:** A aplicação gamificada não produz diferença significativa na permanência dos usuários.
- **H1:** A aplicação gamificada aumenta significativamente a permanência dos usuários.

### 7.3 Nível de significância
- α = 0,05.

---

## 8. Variáveis e fatores

### 8.1 Objetos de estudo
Interfaces web com e sem micro-recompensas.

### 8.2 Participantes
Usuários voluntários com conhecimento básico de navegação web.

### 8.3 Variáveis independentes
- Presença de micro-recompensas (sim/não).

### 8.4 Tratamentos
- **Grupo A – Controle:** versão sem recompensas.
- **Grupo B – Tratamento:** versão com pontos, badges e feedback imediato.

### 8.5 Variáveis dependentes
- Tempo de permanência.
- Taxa de conclusão.
- Taxa de retorno.

### 8.6 Variáveis de controle
- Mesmo layout.
- Mesma tarefa.
- Mesmo conteúdo.

### 8.7 Variáveis de confusão possíveis
- Motivação pessoal prévia.
- Interrupções externas.
- Diferenças de dispositivos.

---

## 9. Desenho experimental

### 9.1 Tipo
Experimento AB com comparação entre dois grupos independentes.

### 9.2 Randomização
Participantes serão alocados aleatoriamente usando sorteio no primeiro acesso.

### 9.3 Balanceamento
Mesma quantidade aproximada por grupo.

### 9.4 Número de grupos e sessões
- 2 grupos.
- 1 sessão por participante.

---

## 10. População e amostragem

### 10.1 População-alvo
Usuários de aplicações web que realizam tarefas curtas em plataformas digitais.

### 10.2 Critérios de inclusão
- Saber usar navegador.
- Consentir participação.

### 10.3 Critérios de exclusão
- Participantes que não concluírem sequer o carregamento da interface.
- Conflitos de interesse claros.

### 10.4 Tamanho da amostra
Entre 20 e 40 participantes no total (10–20 por grupo).

### 10.5 Método de seleção
Amostra por conveniência (turma, formulários ou grupo fechado).

### 10.6 Treinamento
Instruções simples e padronizadas antes de iniciar a tarefa.

---

## 11. Instrumentação e protocolo

### 11.1 Instrumentos
- Logs da aplicação.
- Scripts de processamento de dados.
- Formulário opcional de feedback.

### 11.2 Materiais de suporte
- Página de instruções breves.
- Tutorial de funcionamento.

### 11.3 Procedimento experimental
1. Convite aos participantes.  
2. Consentimento informado.  
3. Acesso à aplicação.  
4. Randomização para grupo A ou B.  
5. Realização da tarefa.  
6. Registro automático dos dados.  
7. Encerramento e agradecimento.

### 11.4 Plano piloto
Será realizado com 2–3 participantes para validação do fluxo e coleta.

---

## 12. Plano de análise de dados

### 12.1 Estratégia geral
Comparar médias dos dois grupos e verificar significância das diferenças.

### 12.2 Métodos estatísticos
- Teste t para diferença de médias (ou Mann-Whitney caso não normal).
- Testes de proporção para taxas de conclusão ou retorno.

### 12.3 Dados faltantes e outliers
- Sessões sem registro completo serão descartadas.
- Outliers serão analisados caso a caso com base no protocolo.

### 12.4 Dados qualitativos
Comentários opcionais serão categorizados manualmente.

---

## 13. Avaliação de validade

### 13.1 Validade de conclusão
- Risco de amostra pequena → mitigado com maior recrutamento.
- Checagem de normalidade antes do teste paramétrico.

### 13.2 Validade interna
- Controle de layout e conteúdo.
- Randomização dos participantes.

### 13.3 Validade de constructo
Métricas diretas e objetivas (tempo e taxas) reduzem ambiguidade.

### 13.4 Validade externa
Resultados válidos principalmente para aplicativos web com tarefas curtas.

### 13.5 Resumo
| Tipo | Ameaça | Mitigação |
|---|---|---|
| Conclusão | Baixa amostra | Recrutamento amplo |
| Interna | Diferenças de contexto | Randomização |
| Constructo | Métrica inadequada | Métricas objetivas |

---

## 14. Ética, privacidade e conformidade

### 14.1 Questões éticas
Participação voluntária, sem incentivo financeiro obrigatório.

### 14.2 Consentimento informado
Apresentado antes do início, com aceite explícito.

### 14.3 Privacidade
Dados coletados serão anonimizados e armazenados localmente pelo pesquisador.

### 14.4 Aprovações
Não há necessidade de comitê formal devido ao baixo risco.

---

## 15. Recursos e orçamento

### 15.1 Equipe
- Arthur – execução completa.

### 15.2 Infraestrutura
- Aplicação web simples.
- Servidor para hospedagem ou execução local.

### 15.3 Materiais
- Navegador e computador dos participantes.

### 15.4 Orçamento
Custo estimado: zero ou muito próximo disso.

---

## 16. Cronograma

### 16.1 Marco geral
- Planejamento: 22/11–25/11  
- Piloto: 26/11  
- Coleta: 27/11–02/12  
- Análise: 03/12–07/12

### 16.2 Dependências
Coleta só inicia após piloto validado.

### 16.3 Riscos
Falta de participantes → mitigação via convite ampliado.

---

## 17. Governança

### 17.1 Papéis
- Arthur: decide, executa, documenta e analisa.

### 17.2 Ritos
- Revisões internas antes de coleta.

### 17.3 Controle de mudanças
Mudanças estruturais serão registradas em histórico de versão.

---

## 18. Documentação

### 18.1 Repositórios
GitHub com aplicação, logs e scripts.

### 18.2 Templates
- Formulário de coleta.
- Planilha de registro.

### 18.3 Replicação futura
Código e instruções serão publicados junto ao repositório.

---

## 19. Comunicação

### 19.1 Públicos
- Participantes
- Professores

### 19.2 Canais
- E-mail
- Mensagens diretas

### 19.3 Pontos obrigatórios
- Confirmação de início
- Ajustes relevantes

---

## 20. Critérios de prontidão

### 20.1 Checklist
- Aplicação funcional
- Logs testados
- Piloto executado
- Consentimento pronto

### 20.2 Aprovação
Início autorizado após validação do piloto e infraestrutura estável.
