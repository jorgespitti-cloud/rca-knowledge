# 30 — Confiabilidade de Equipamentos e Manutenção

## Finalidade

Este arquivo apoia a **pesquisa de causas contribuintes** e o **teste de hipóteses** relacionadas à confiabilidade de equipamentos, manutenção preventiva, manutenção corretiva, calibração e verificação.

As descrições e os códigos da LCC são preservados. Os blocos de evidências, perguntas e testes são orientações complementares para operacionalizar a investigação.

> **Regra para o agente:** uma hipótese desta categoria somente deve ser confirmada quando houver evidência de que a condição existia no período relevante, afetava o equipamento ou instrumento relacionado ao evento e contribuiu para o resultado observado. A mera existência de uma pendência de manutenção ou calibração não prova, isoladamente, o vínculo causal.

---

## Visão geral da categoria

| Grupo | Tema |
|---|---|
| 30.01 a 30.14 | Programa de manutenção e manutenção preventiva |
| 30.10 a 30.14 | Evento de manutenção corretiva |
| 30.15 a 30.25 | Programa de calibração ou verificação |

> **Nota:** os grupos se sobrepõem nos códigos 30.10 a 30.14 porque a estrutura original da LCC introduz o tema “Evento de Manut. Corretiva” no código 30.10.

---

# Programa de manutenção e manutenção preventiva

## 30.01 — Programa de Manutenção

**Tipo de item:** aspecto da causa-raiz e ponto inicial de investigação.

### Pesquisa de causas contribuintes

**Investigar quando:** o evento puder estar relacionado à degradação, indisponibilidade, falha funcional, perda de desempenho ou condição inadequada de equipamento, instrumento, instalação ou sistema.

**Evidências a pesquisar:**

- inventário e cadastro de ativos;
- programa ou plano de manutenção;
- recomendações do fabricante;
- análise de criticidade e histórico de falhas;
- ordens de serviço e registros de execução;
- indicadores de cumprimento e reincidência;
- alterações de frequência, escopo e estratégia;
- inspeções e condição atual do equipamento.

**Perguntas de investigação:**

- O ativo relacionado ao evento estava identificado no programa?
- Qual estratégia de manutenção era aplicável?
- Frequência, escopo e critérios eram compatíveis com a criticidade e o modo de falha?
- As intervenções previstas foram executadas e aceitas?
- A condição investigada era detectável ou evitável pelo programa?

### Teste da causa

- **Hipótese:** uma deficiência no programa de manutenção permitiu a ocorrência ou evolução de uma condição que contribuiu para o evento.
- **Confirmação:** demonstrar a deficiência do programa, o mecanismo pelo qual a deficiência afetou o ativo e o vínculo com o evento.
- **Refutação:** comprovar que o programa era adequado, estava cumprido e que a falha decorreu de condição não controlável pela manutenção aplicável.
- **Inconclusivo:** quando o histórico, a condição anterior ou o mecanismo de falha não puderem ser reconstruídos.

---

## 30.02 — Sem programa definido.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** cadastro de ativos, plano mestre, sistema informatizado de manutenção, contratos, recomendações do fabricante, análise de criticidade e responsabilidades definidas.

**Perguntas:**

- O ativo exigia manutenção planejada?
- Existiam recomendações, requisitos legais ou experiência de falha conhecida?
- Quem deveria incluir o ativo em um programa?
- Como a ausência do programa influenciou a condição encontrada?

### Teste da causa

- **Hipótese:** a inexistência de programa impediu intervenções necessárias e permitiu degradação ou falha do ativo.
- **Confirmar se:** comprovar que não havia programa aplicável, que uma intervenção necessária deixou de ocorrer e que isso contribuiu para o evento.
- **Refutar se:** o ativo possuía estratégia equivalente, adequada e executada, ou se o modo de falha não era prevenível pelo programa esperado.
- **Próximos porquês:** ativo não cadastrado; responsabilidade indefinida; criticidade não avaliada; processo de comissionamento incompleto.

---

## 30.03 — Equip. não consta no programa.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** inventário de ativos, lista do programa, registros de aquisição e comissionamento, análise de criticidade, identificação física, transferências e alterações de processo.

**Perguntas:**

- O equipamento estava cadastrado no inventário, mas ausente do programa?
- Quando entrou em operação?
- Houve mudança, transferência ou substituição não incorporada?
- A ausência resultou em manutenção não realizada?

### Teste da causa

- **Hipótese:** a exclusão do equipamento do programa impediu atividades necessárias e contribuiu para a falha.
- **Confirmar se:** demonstrar ausência no programa, atividade necessária não executada e vínculo com a condição do evento.
- **Refutar se:** existia controle equivalente ou se a manutenção omitida não poderia prevenir ou detectar a falha.
- **Próximos porquês:** processo de cadastro falho; gestão de mudança não realizada; interface entre aquisição e manutenção inadequada.

---

## 30.04 — Escopo de preventiva falho.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** planos e rotinas, listas de tarefas, recomendações do fabricante, modos de falha, relatórios anteriores, pontos de inspeção, peças substituídas e critérios técnicos.

**Perguntas:**

- O escopo cobria os componentes e modos de falha críticos?
- As tarefas eram tecnicamente adequadas e suficientemente detalhadas?
- Alguma tarefa necessária foi omitida ou executada de forma superficial?
- A deficiência do escopo se relaciona ao componente que falhou?

### Teste da causa

- **Hipótese:** o escopo da preventiva não continha atividade necessária para controlar o modo de falha relacionado ao evento.
- **Confirmar se:** identificar a lacuna técnica e demonstrar que a tarefa adequada teria possibilidade razoável de prevenir ou detectar a condição.
- **Refutar se:** o escopo cobria adequadamente o modo de falha ou se a falha não era detectável ou prevenível pela atividade.
- **Próximos porquês:** plano não baseado em criticidade; manual não considerado; histórico de falhas não analisado; competência técnica insuficiente.

---

## 30.05 — Frequência de manut. inadequada.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** frequência planejada, base técnica, recomendações do fabricante, condições de uso, horas ou ciclos, ambiente, histórico de falhas e mudanças operacionais.

**Perguntas:**

- A frequência considerava intensidade e condições reais de uso?
- A degradação ocorria antes da intervenção programada?
- Houve aumento de carga, ciclos, severidade ou exposição ambiental?
- A frequência havia sido revisada com base no desempenho?

### Teste da causa

- **Hipótese:** o intervalo definido era insuficiente para prevenir ou detectar a degradação antes do evento.
- **Confirmar se:** demonstrar que a condição evoluiu dentro do intervalo e que uma frequência tecnicamente adequada poderia detectá-la ou tratá-la.
- **Refutar se:** o intervalo era adequado ao modo de falha ou a condição surgiu de maneira súbita e não previsível.
- **Próximos porquês:** criticidade desatualizada; mudança de uso não comunicada; tendência não monitorada; recomendação técnica ignorada.

---

## 30.06 — Frequência não cumprida.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** calendário, ordens de serviço, datas planejadas e realizadas, backlog, adiamentos, justificativas, disponibilidade do ativo, recursos e autorizações.

**Perguntas:**

- Qual intervenção venceu ou foi adiada?
- Qual foi o atraso real em horas, ciclos ou dias?
- O adiamento foi avaliado e aprovado com base em risco?
- A condição associada ao evento se desenvolveu durante o atraso?

### Teste da causa

- **Hipótese:** o descumprimento da frequência permitiu a progressão de uma condição que contribuiu para o evento.
- **Confirmar se:** comprovar atraso, evolução da condição no período e probabilidade razoável de detecção ou prevenção na data prevista.
- **Refutar se:** a atividade foi executada no prazo aplicável ou o atraso não possuía relação técnica com o modo de falha.
- **Próximos porquês:** indisponibilidade de recurso; planejamento falho; prioridade inadequada; equipamento não liberado; peça indisponível.

---

## 30.07 — Critério de aceitação da manut. falho.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** critérios de aceitação, tolerâncias, parâmetros pós-manutenção, testes funcionais, checklists, especificações, relatórios e aprovação para retorno ao serviço.

**Perguntas:**

- Qual critério determinava que o ativo estava apto ao retorno?
- O critério era objetivo, mensurável e tecnicamente válido?
- O resultado real atendia às necessidades de operação segura e confiável?
- Um resultado inadequado foi aceito?

### Teste da causa

- **Hipótese:** um critério de aceitação inadequado permitiu liberar o ativo em condição incapaz de atender ao desempenho requerido.
- **Confirmar se:** demonstrar falha do critério, aceitação da condição inadequada e vínculo com o evento.
- **Refutar se:** o critério era adequado e atendido, ou se a condição surgiu após a liberação.
- **Próximos porquês:** especificação incompleta; ausência de validação do teste; responsabilidade técnica inadequada; requisito operacional não comunicado.

---

## 30.08 — Manut. preventiva feita incompleta.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** ordem de serviço, checklist preenchido, apontamentos, peças e materiais consumidos, fotos, duração, assinaturas, desvios e entrevistas com executantes.

**Perguntas:**

- Quais tarefas previstas não foram executadas?
- A execução parcial foi registrada e aprovada?
- Houve restrição de acesso, tempo, recurso, peça ou competência?
- A tarefa omitida estava ligada ao modo de falha?

### Teste da causa

- **Hipótese:** a execução incompleta deixou de controlar uma condição que contribuiu para o evento.
- **Confirmar se:** identificar a tarefa omitida e demonstrar sua relação técnica com a condição encontrada.
- **Refutar se:** todas as tarefas críticas foram executadas ou a tarefa não realizada não se relacionava ao evento.
- **Próximos porquês:** checklist inadequado; pressão de tempo; supervisão insuficiente; acesso ou recurso indisponível.

---

## 30.09 — Sem registros de manut. preventiva.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** sistema de manutenção, ordens de serviço, apontamentos, consumo de peças, registros de acesso, dados do equipamento, e-mails, fotos, notas de serviço e entrevistas.

**Perguntas:**

- A atividade ocorreu sem registro ou não ocorreu?
- É possível reconstruir data, escopo, responsável, resultado e pendências?
- A falta de registro impediu controlar recorrências ou programar intervenções?
- Há evidências independentes da execução?

### Teste da causa

- **Hipótese:** a ausência de registros comprometeu a rastreabilidade e contribuiu para que uma condição não fosse identificada ou tratada.
- **Confirmar se:** demonstrar efeito concreto da falta de registro sobre uma decisão, acompanhamento ou intervenção relacionada ao evento.
- **Refutar se:** houver evidência equivalente, íntegra e rastreável de execução adequada.
- **Atenção:** ausência de registro não prova automaticamente que a manutenção não ocorreu.

---

# Evento de manutenção corretiva

## 30.10 — Evento de Manut. Corretiva

**Tipo de item:** aspecto da causa-raiz e ponto inicial de investigação.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** notificação da falha, ordem corretiva, diagnóstico, análise do modo de falha, peças retiradas, testes, histórico anterior, comunicação e retorno ao serviço.

**Perguntas:**

- Como a necessidade corretiva foi identificada e comunicada?
- O diagnóstico localizou o mecanismo real da falha?
- A correção restaurou integralmente a função?
- Permaneceram causas ou danos secundários não tratados?

### Teste da causa

- **Hipótese:** uma deficiência na identificação, programação, execução ou aceitação da manutenção corretiva contribuiu para o evento.
- **Confirmação:** demonstrar a deficiência específica e sua ligação com a condição posterior do ativo.
- **Refutação:** comprovar comunicação, execução, teste e liberação adequados, sem relação com o evento.

---

## 30.11 — Necessidade não comunicada.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** relatos de anomalia, livros de turno, chamados, alarmes, mensagens, inspeções, reuniões, registro de passagem de serviço e entrevistas.

**Perguntas:**

- Quem percebeu a necessidade e quando?
- Qual canal deveria ter sido utilizado?
- A informação foi retida, perdida ou não reconhecida?
- A falta de comunicação atrasou a correção e permitiu agravamento?

### Teste da causa

- **Hipótese:** uma necessidade conhecida não foi comunicada, impedindo ação corretiva em tempo adequado.
- **Confirmar se:** comprovar percepção prévia, ausência de comunicação eficaz e progressão da condição até o evento.
- **Refutar se:** a necessidade foi comunicada corretamente ou ainda não era detectável antes do evento.
- **Próximos porquês:** canal não definido; cultura de reporte inadequada; responsabilidade ambígua; sinal de falha não reconhecido.

---

## 30.12 — Comunicada, mas não programada.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** chamados, notificações, backlog, reuniões de programação, critérios de prioridade, avaliação de risco, disponibilidade de recursos e decisões de adiamento.

**Perguntas:**

- O chamado foi recebido e reconhecido?
- Por que não foi convertido em ordem ou programação?
- A prioridade refletia criticidade e potencial de falha?
- Houve acompanhamento da condição enquanto aguardava atendimento?

### Teste da causa

- **Hipótese:** a necessidade comunicada não foi programada e a condição evoluiu até contribuir para o evento.
- **Confirmar se:** demonstrar recebimento, ausência de programação, evolução da condição e vínculo técnico.
- **Refutar se:** a programação ocorreu em prazo adequado ou a condição não estava relacionada ao evento.
- **Próximos porquês:** triagem falha; backlog sem controle; prioridade inadequada; responsabilidade não definida.

---

## 30.13 — Programada, mas não realizada.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** programação, ordem de serviço, cancelamento, reprogramações, indisponibilidade do ativo, equipe, ferramentas, materiais, permissões e justificativas.

**Perguntas:**

- Qual data e escopo estavam programados?
- Por que a execução não ocorreu?
- O cancelamento ou adiamento foi formalmente avaliado?
- A condição foi monitorada ou mitigada durante a espera?

### Teste da causa

- **Hipótese:** a manutenção programada não executada permitiu a permanência ou agravamento de condição relacionada ao evento.
- **Confirmar se:** comprovar não execução e que a intervenção planejada poderia corrigir ou detectar a condição.
- **Refutar se:** a atividade foi executada por meio equivalente ou não apresentava relação com o evento.
- **Próximos porquês:** conflito de programação; liberação operacional negada; recurso ou peça indisponível; acompanhamento insuficiente.

---

## 30.14 — Manut. Corretiva feita incompleta.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** diagnóstico, ordem de serviço, tarefas previstas e executadas, peças substituídas, testes finais, pendências, recomendações e histórico de recorrência.

**Perguntas:**

- A correção tratou o mecanismo real ou apenas o sintoma?
- Quais tarefas ou componentes deixaram de ser tratados?
- O equipamento foi liberado com pendências?
- A falha posterior reproduz o modo de falha anterior?

### Teste da causa

- **Hipótese:** a correção incompleta deixou uma condição residual que contribuiu para o evento ou recorrência.
- **Confirmar se:** demonstrar lacuna na correção, permanência do mecanismo de falha e vínculo com o evento.
- **Refutar se:** a correção foi completa e validada ou o evento decorreu de mecanismo distinto.
- **Próximos porquês:** diagnóstico insuficiente; peça indisponível; teste inadequado; pressão para retorno; causa anterior não investigada.

---

# Programa de calibração ou verificação

## 30.15 — Programa de Calibração/Verificação

**Tipo de item:** aspecto da causa-raiz e ponto inicial de investigação.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** inventário metrológico, programa, certificados, etiquetas, padrões, rastreabilidade, métodos, critérios de aceitação, histórico de resultados e impacto sobre medições anteriores.

**Perguntas:**

- O instrumento relacionado ao evento estava controlado?
- Grandeza, faixa, resolução e pontos eram adequados ao uso?
- A frequência considerava criticidade e estabilidade?
- Resultados fora de tolerância foram avaliados quanto ao impacto?

### Teste da causa

- **Hipótese:** uma deficiência no controle de calibração ou verificação comprometeu a confiabilidade da medição associada ao evento.
- **Confirmação:** demonstrar a deficiência metrológica, o efeito sobre o resultado e como esse resultado influenciou o evento.
- **Refutação:** comprovar adequação metrológica e ausência de impacto relevante na decisão ou processo.

---

## 30.16 — Sem programa definido.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** inventário de instrumentos, requisitos de processo, critérios legais ou normativos, manuais, análises de criticidade e responsabilidades metrológicas.

**Perguntas:**

- O instrumento era usado para aceitar, controlar, monitorar ou proteger o processo?
- Era necessária calibração, verificação ou outro controle?
- Quem deveria definir e administrar o programa?
- A ausência do programa afetou a confiabilidade do resultado?

### Teste da causa

- **Hipótese:** a inexistência de programa permitiu uso de instrumento sem evidência de adequação metrológica.
- **Confirmar se:** demonstrar necessidade de controle, ausência do programa e impacto plausível e mensurável no evento.
- **Refutar se:** existia controle equivalente adequado ou a medição não influenciou o evento.
- **Próximos porquês:** instrumento não cadastrado; requisito metrológico não definido; responsabilidade inexistente; processo novo não incorporado.

---

## 30.17 — Equip. não consta no programa.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** cadastro e inventário, lista do programa, aquisição, comissionamento, identificação física, transferências, uso real e gestão de mudanças.

**Perguntas:**

- O equipamento era utilizado para medição relevante?
- Por que não estava no inventário ou programa?
- Houve substituição, inclusão temporária ou mudança de uso?
- A ausência resultou em falta de calibração ou verificação necessária?

### Teste da causa

- **Hipótese:** a exclusão do equipamento do programa permitiu seu uso sem controle metrológico adequado.
- **Confirmar se:** comprovar uso relevante, ausência do programa e impacto do resultado sobre o evento.
- **Refutar se:** havia controle equivalente ou a medição não afetou a decisão relacionada ao evento.
- **Próximos porquês:** cadastro falho; aquisição descentralizada; mudança não comunicada; identificação inadequada.

---

## 30.18 — Escopo inadequado (grandeza,faixa,ptos).

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** certificado, procedimento, faixa de uso, pontos calibrados, grandezas, resolução, exatidão requerida, incerteza e condições ambientais.

**Perguntas:**

- A grandeza calibrada correspondia à grandeza utilizada?
- A faixa e os pontos cobriam as condições reais de medição?
- A resolução e a incerteza eram adequadas ao limite de decisão?
- O ponto associado ao evento estava fora do escopo avaliado?

### Teste da causa

- **Hipótese:** o escopo metrológico não representava o uso real e não assegurava a confiabilidade da medição relevante.
- **Confirmar se:** demonstrar incompatibilidade entre escopo e uso, quantificar o possível efeito e ligar esse efeito ao evento.
- **Refutar se:** escopo e uso eram compatíveis ou a diferença não alterava a decisão.
- **Próximos porquês:** uso pretendido não informado; especificação incompleta; fornecedor selecionado inadequadamente; revisão técnica falha.

---

## 30.19 — Frequência inadequada.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** intervalo definido, estabilidade histórica, intensidade de uso, ambiente, recomendações, criticidade, resultados anteriores e ocorrências de ajuste.

**Perguntas:**

- O intervalo refletia estabilidade e criticidade do instrumento?
- Houve tendência de deriva antes do vencimento?
- Mudanças de uso ou ambiente foram consideradas?
- O intervalo foi revisado com base no histórico?

### Teste da causa

- **Hipótese:** o intervalo era excessivo e permitiu deriva metrológica relevante antes da próxima calibração ou verificação.
- **Confirmar se:** demonstrar deriva no período, impacto na medição e possibilidade razoável de detecção com frequência adequada.
- **Refutar se:** o instrumento permaneceu estável ou a deriva não influenciou o evento.
- **Próximos porquês:** histórico não analisado; criticidade inadequada; mudança de uso não incorporada; critério de frequência genérico.

---

## 30.20 — Frequência não cumprida.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** datas de vencimento, certificados, etiquetas, bloqueios do sistema, extensão de validade, avaliações de risco, uso durante atraso e programação.

**Perguntas:**

- Por quanto tempo o instrumento foi usado após o vencimento?
- Houve extensão tecnicamente justificada?
- Quais medições foram realizadas no período?
- O resultado posterior indicou deriva ou inadequação?

### Teste da causa

- **Hipótese:** o uso após o vencimento permitiu medições não confiáveis que contribuíram para o evento.
- **Confirmar se:** comprovar vencimento, uso relevante, resultado metrológico inadequado ou incerteza significativa e efeito sobre a decisão.
- **Refutar se:** avaliação posterior demonstrar estabilidade e ausência de impacto, ou se o instrumento não foi usado no período relevante.
- **Próximos porquês:** alerta ineficaz; equipamento indisponível para envio; planejamento falho; bloqueio de uso inexistente.

---

## 30.21 — Sem critério de aceitação

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** tolerância necessária ao processo, especificação do instrumento, procedimento, certificado, limite de erro, incerteza, regra de decisão e requisitos do cliente.

**Perguntas:**

- Qual erro máximo era aceitável para o uso?
- Quem deveria definir e aprovar o critério?
- Como o resultado foi considerado aprovado sem critério?
- A falta do critério permitiu aceitar condição inadequada?

### Teste da causa

- **Hipótese:** a ausência de critério impediu avaliar adequadamente o resultado e permitiu uso de instrumento inadequado.
- **Confirmar se:** demonstrar inexistência do critério, aceitação sem base técnica e impacto no evento.
- **Refutar se:** havia critério equivalente claro e aplicado ou se o resultado não influenciou o evento.
- **Próximos porquês:** requisito de processo não traduzido; responsabilidade indefinida; procedimento incompleto; competência metrológica insuficiente.

---

## 30.22 — Critério de aceitação da falho.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** critérios de aceitação, requisitos do processo, tolerância, incerteza, regra de decisão, histórico de aprovações e revisão técnica.

**Perguntas:**

- O critério era compatível com o erro permitido no processo?
- A incerteza de medição era considerada?
- O critério poderia aprovar instrumento incapaz para o uso?
- O resultado investigado foi aceito por esse critério?

### Teste da causa

- **Hipótese:** um critério inadequado levou à aprovação de instrumento ou sistema de medição incapaz de atender ao uso.
- **Confirmar se:** comparar critério, necessidade real e resultado, demonstrando o efeito sobre o evento.
- **Refutar se:** o critério era tecnicamente adequado ou a medição aprovada não se relacionava ao evento.
- **Próximos porquês:** tolerância de processo desconhecida; regra de decisão não definida; revisão técnica inadequada.

---

## 30.23 — Calib. / Verificação não validada.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** método de calibração ou verificação, validação do método, padrões utilizados, competência, estudos de repetibilidade, software, cálculos e condições ambientais.

**Perguntas:**

- O método era reconhecido, validado ou tecnicamente demonstrado?
- Padrões, equipamentos e software eram adequados?
- A execução produzia resultados repetíveis e rastreáveis?
- Uma limitação do método poderia ocultar o erro relevante?

### Teste da causa

- **Hipótese:** o método não validado produziu resultado não confiável e permitiu aceitação inadequada.
- **Confirmar se:** demonstrar deficiência do método, efeito sobre o resultado e vínculo com a medição associada ao evento.
- **Refutar se:** o método era validado ou verificado por evidência adequada e produzia resultado confiável.
- **Próximos porquês:** método desenvolvido sem validação; fornecedor não qualificado; alteração de software não controlada; competência insuficiente.

---

## 30.24 — Calib. / Verificação inadequada aceita.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** certificado, escopo, resultados, incerteza, rastreabilidade, acreditação quando aplicável, análise crítica, aprovação e liberação do instrumento.

**Perguntas:**

- Qual inadequação existia no serviço ou certificado?
- A análise crítica deveria ter detectado a inadequação?
- Quem aceitou e liberou o instrumento?
- A inadequação afetava a faixa, grandeza ou uso relacionado ao evento?

### Teste da causa

- **Hipótese:** uma calibração ou verificação inadequada foi aceita e o instrumento foi liberado sem confiabilidade suficiente.
- **Confirmar se:** demonstrar inadequação, aceitação indevida, uso do instrumento e impacto na decisão ou processo.
- **Refutar se:** a inadequação era apenas formal e não afetava o uso, ou se houve correção antes da utilização.
- **Próximos porquês:** análise crítica inexistente; critério de aprovação falho; competência inadequada; fornecedor não monitorado.

---

## 30.25 — Sem registros de calib./verificação.

### Pesquisa de causas contribuintes

**Evidências a pesquisar:** certificados, banco de dados, etiquetas, registros internos, relatórios do fornecedor, padrões utilizados, notas fiscais, e-mails, backups e histórico do instrumento.

**Perguntas:**

- A calibração ou verificação ocorreu sem registro ou não ocorreu?
- É possível reconstruir data, método, padrão, resultado e decisão?
- O instrumento foi utilizado sem evidência de condição metrológica?
- A falta de registro impediu avaliar o impacto sobre medições anteriores?

### Teste da causa

- **Hipótese:** a ausência de registros impediu assegurar a confiabilidade metrológica e contribuiu para decisão baseada em medição não demonstrada.
- **Confirmar se:** demonstrar efeito concreto da falta de registro sobre controle, rastreabilidade ou avaliação de impacto ligada ao evento.
- **Refutar se:** houver evidência equivalente, íntegra e rastreável de calibração ou verificação adequada.
- **Atenção:** ausência de registro não prova automaticamente ausência da atividade nem erro de medição.

---

# Relações com outras categorias da LCC

Ao investigar a categoria 30, considerar também, quando aplicável:

- **29 — Projeto:** quando confiabilidade, manutenibilidade ou requisitos metrológicos não tiverem sido considerados no projeto;
- **31 — Informação documentada:** quando manuais, históricos, registros, materiais ou dados de processo estiverem indisponíveis ou incorretos;
- **32 — Fornecedores, materiais e serviços:** quando peças, serviços de manutenção ou calibração e especificações externas forem relevantes;
- **33 — Riscos, mudanças e monitoramento:** quando riscos, modificações, auditorias ou ocorrências anteriores não tiverem sido tratados;
- **34 — Protocolos operacionais:** quando procedimentos, instruções ou checklists de manutenção estiverem ausentes ou inadequados;
- **35 — Interação humano e ambiente:** quando acesso, ferramentas, ambiente, energia perigosa ou carga de trabalho afetarem a intervenção;
- **36 — Capacitação:** quando competência, qualificação ou treinamento dos executantes forem relevantes;
- **37 — Responsabilidades, planejamento e supervisão:** quando programação, recursos, coordenação ou supervisão contribuírem;
- **38 — Comunicação:** quando necessidade, anomalia, adiamento ou resultado não tiver sido comunicado;
- **39 — Desempenho de pessoal:** somente quando sustentado por evidências e sem substituir a investigação das condições sistêmicas.

---

# Modelo de resposta esperado do agente

Ao aplicar este arquivo, o agente deve apresentar:

1. **Código e hipótese investigada**;
2. **Ativo, instrumento ou sistema relacionado**;
3. **Função requerida e modo de falha considerado**;
4. **Motivo para considerar a hipótese**;
5. **Evidências pesquisadas**;
6. **Evidências favoráveis e desfavoráveis**;
7. **Análise do vínculo causal**;
8. **Resultado:** confirmada, refutada ou inconclusiva;
9. **Próximos porquês**, quando confirmada;
10. **Lacunas de informação e ações necessárias**.

---

**Documento de origem:** Lista Compreensiva de Causas — FOG 222, revisão 00, de 24/10/2023.

**Nota de integridade:** os códigos e as descrições da LCC foram mantidos conforme a fonte. Evidências, perguntas, critérios de teste e relações são orientações complementares elaboradas para apoiar agentes de IA e investigadores humanos.
