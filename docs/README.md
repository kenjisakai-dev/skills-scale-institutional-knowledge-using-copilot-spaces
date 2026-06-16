# OctoAcme — Processos de Gerenciamento de Projetos

Bem-vindo à documentação de processos de gerenciamento de projetos da OctoAcme. Este README fornece uma visão geral dos processos adotados pela equipe e links para todos os documentos de referência armazenados nesta pasta.

---

## Visão Geral dos Processos

O gerenciamento de projetos da OctoAcme segue um ciclo de vida estruturado em cinco fases: **Iniciação, Planejamento, Execução, Release e Retrospectiva**. Na fase de iniciação, toda nova ideia ou proposta de funcionalidade precisa ser validada por meio de um *Project One-pager* — que define o problema, objetivos SMART, métricas de sucesso e stakeholders — antes de receber aprovação para avançar. O planejamento transforma a iniciativa aprovada em um backlog priorizado com critérios de aceite, estimativas, mapa de marcos e um Registro de Riscos, garantindo que dependências e capacidade da equipe sejam consideradas antes do início da execução.

Durante a **execução e rastreamento**, a equipe opera com ritmos cadenciados: standups diários de 15 minutos, sincronização semanal de entrega e demos ao final de cada sprint ou marco. O fluxo de trabalho de Pull Requests privilegia PRs pequenos (≤ 400 linhas), vinculados a issues com critérios de aceite, passando por CI automatizado (testes, lint e varredura de segurança) e ao menos uma aprovação antes do merge. Métricas como velocidade, burndown e dashboards operacionais (erros, latência, uso) são monitoradas continuamente. Bloqueadores seguem um caminho de escalonamento em três níveis: triagem no standup → PM escala para o Product Lead → escalonamento ao Sponsor para questões de impacto no negócio.

A OctoAcme conta com **quatro personas centrais** com responsabilidades bem definidas: o *Project Manager (PM)* coordena entregas, cronogramas, riscos e comunicação; o *Product Manager (PdM)* define visão, prioriza o backlog e mede resultados; os *Developers* implementam funcionalidades com foco em confiabilidade, cobertura de testes e redução do ciclo de desenvolvimento; e o time de *QA* valida critérios de aceite por meio de testes unitários, de integração, *smoke tests* de ponta a ponta e varreduras de segurança em CI. A **comunicação** é estruturada com atualizações semanais de status (progresso, próximos passos, riscos e decisões necessárias), sincronia semanal entre PM e PdM, e atualizações mensais para stakeholders, além de escalonamentos ad hoc quando necessário.

Por fim, após cada sprint, release ou incidente, a OctoAcme realiza **retrospectivas** de 45 a 75 minutos no formato *"o que foi bem / o que pode melhorar / itens de ação"*, com 2 a 3 prioridades por ciclo para evitar sobrecarga. Os itens de ação são rastreados no backlog com proprietários e prazos definidos, e seu impacto é medido para promover uma cultura de melhoria contínua e iterativa. Todo o conhecimento — decisões, riscos, artefatos e aprendizados — é versionado e centralizado no repositório, tornando o processo transparente, repetível e acessível a todos os membros da equipe.

---

## Documentos de Processo

| Documento | Descrição |
|-----------|-----------|
| [Overview](octoacme-project-management-overview.md) | Visão geral, princípios, artefatos-chave e cadência de comunicação |
| [Project Initiation](octoacme-project-initiation.md) | Valida ideias, alinha stakeholders e define objetivos e entregáveis iniciais |
| [Project Planning](octoacme-project-planning.md) | Transforma iniciativas aprovadas em plano acionável, backlog priorizado e mapa de marcos |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Ritmos da equipe, fluxo de trabalho, qualidade e métricas de acompanhamento |
| [Risks & Communication](octoacme-risks-and-communication.md) | Registro de riscos, ciclo de vida de riscos e templates de comunicação |
| [Release & Deployment](octoacme-release-and-deployment.md) | Tipos de release, checklist de pré-release, deploy e playbook de rollback |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Formato de retrospectiva, itens de ação e acompanhamento |
| [Roles & Personas](octoacme-roles-and-personas.md) | Responsabilidades típicas de Developers, PM, PdM e QA |

---

> Este README serve como ponto de entrada para novos membros e referência rápida para toda a equipe. Atualize-o conforme novos documentos forem adicionados à pasta `docs/`.
