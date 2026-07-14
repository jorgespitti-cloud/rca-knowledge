# 02 — Triagem de Fatores Causais

## Etapa D — Comece aqui, a partir de cada fator causal

## Finalidade

Este arquivo operacionaliza os passos **1 a 28** da Lista Compreensiva de Causas (LCC). A triagem deve ser iniciada somente depois das etapas A, B e C do arquivo `00-ROTEIRO-OPERACIONAL.md`.

A triagem tem duas funções:

1. classificar cada fator causal identificado;
2. direcionar a investigação para uma ou mais categorias 29 a 39.

> **Regra para o agente:** resposta “sim” indica necessidade de aprofundamento, não confirmação de causa. A causa somente pode ser confirmada após pesquisa e teste das hipóteses nas categorias recomendadas.

---

## Como executar

Para cada fator causal identificado na etapa C:

1. registre o fator e suas evidências;
2. aplique os passos 1 a 6 como triagem principal;
3. aplique os passos de aprofundamento relacionados;
4. considere separadamente os passos 8, 9, 21, 22, 24, 26 e 27 quando aplicáveis;
5. registre todas as respostas como **sim**, **não** ou **indeterminado**;
6. selecione as categorias 29 a 39 sugeridas;
7. formule hipóteses sem confirmá-las;
8. volte à coleta de evidências quando a resposta for indeterminada.

## Entrada mínima

```text
ID do fator causal:
Descrição:
Momento na cronologia:
Evidências associadas:
Barreira relacionada:
Lacunas conhecidas:
```

## Significado das respostas

- **Sim:** existem fatos ou indícios suficientes para aprofundar.
- **Não:** evidências disponíveis afastam razoavelmente a classe.
- **Indeterminado:** faltam evidências; registrar o que deve ser obtido.
- **Não aplicável:** a pergunta não corresponde ao fator analisado.

---

# Bloco 1 — Triagem principal

Os passos 1 a 6 classificam a família principal do fator causal. Mais de uma resposta pode ser positiva.

## Passo 1 — Máquinas / Equipamentos / Instrumentos / Hardwares podem ser fator causal?

**Classe de triagem:** Equipamentos, instrumentos e hardware.

### Objetivo

Determinar se o fator causal está relacionado a **equipamentos, instrumentos e hardware** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

identificação do ativo; função requerida; condição encontrada; configuração; alarmes; histórico de falhas; manutenção; calibração; alterações; interfaces.

### Perguntas de apoio

- Qual ativo participou da sequência?
- Qual função deveria desempenhar?
- Que condição, falha ou alteração foi observada?
- A condição precedeu e influenciou o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Se a resposta for “sim”

Avaliar também:

- **Passo 7 — Equipamentos e instrumentos de processo**.
- **Passo 10 — Equipamentos e instrumentos de utilidade**.
- **Passo 11 — Outras classes de equipamentos e instrumentos**.
- **Passo 12 — Hardware**.

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [30 — Manutenção](30-Manutencao.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 2 — Matérias-primas / Insumos / Materiais de Referência podem ser fator causal?

**Classe de triagem:** Materiais, insumos, produtos e padrões.

### Objetivo

Determinar se o fator causal está relacionado a **materiais, insumos, produtos e padrões** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

item, lote, especificação, certificado, validade, inspeção, armazenamento, preservação, rastreabilidade, consumo e resultados.

### Perguntas de apoio

- Qual item foi efetivamente utilizado?
- O item atendia à especificação e estava liberado?
- Como foi armazenado e preservado?
- Existe mecanismo técnico ligando a condição do item ao evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Se a resposta for “sim”

Avaliar também:

- **Passo 13 — Matéria-prima ou produto**.
- **Passo 14 — Insumo de produção**.
- **Passo 15 — Material ou padrão de referência**.

### Categorias para aprofundamento

- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 3 — A mão de obra direta / indireta podem ser fator causal?

**Classe de triagem:** Pessoas e organização do trabalho.

### Objetivo

Determinar se o fator causal está relacionado a **pessoas e organização do trabalho** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

função, tarefa, equipe, vínculo, competência, jornada, carga, procedimentos, recursos, planejamento, supervisão e comunicação.

### Perguntas de apoio

- Qual tarefa e decisão estavam envolvidas?
- Quais condições do sistema influenciaram a execução?
- Competência, recursos e supervisão eram adequados?
- Que barreiras deveriam prevenir ou detectar o desvio?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Se a resposta for “sim”

Avaliar também:

- **Passo 16 — Pessoal CLT**.
- **Passo 17 — Pessoal PJ ou RPA**.
- **Passo 18 — Pessoal de terceira parte**.

### Categorias para aprofundamento

- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)
- [39 — Desempenho de Pessoal](39-Desempenho-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 4 — Métodos de Trabalho podem ser fator causal?

**Classe de triagem:** Métodos de trabalho.

### Objetivo

Determinar se o fator causal está relacionado a **métodos de trabalho** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

procedimentos, instruções, sequência real, riscos, preparação, recursos, observação da tarefa, desvios e interfaces.

### Perguntas de apoio

- Qual método era previsto?
- Qual método foi realmente utilizado?
- O método era correto, disponível e executável?
- A diferença contribuiu para o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Se a resposta for “sim”

Avaliar também:

- **Passo 19 — Execução operacional**.
- **Passo 20 — Supervisão operacional**.
- **Passo 23 — Atividade de suporte**.

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 5 — Métodos de Controle / Monitoramento podem ser fator causal?

**Classe de triagem:** Controles e monitoramento.

### Objetivo

Determinar se o fator causal está relacionado a **controles e monitoramento** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

plano de controle, parâmetros, limites, instrumentos, frequência, registros, alarmes, tendências, análise crítica e ações.

### Perguntas de apoio

- O que deveria ser controlado ou monitorado?
- O método conseguia detectar o problema?
- O resultado foi analisado e comunicado?
- A falha do controle contribuiu para o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Se a resposta for “sim”

Avaliar também:

- **Passo 28 — Monitoramento**.

### Categorias para aprofundamento

- [30 — Manutenção](30-Manutencao.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 6 — Meio ambiente / Infraestrutura podem ser fator causal?

**Classe de triagem:** Meio ambiente e infraestrutura.

### Objetivo

Determinar se o fator causal está relacionado a **meio ambiente e infraestrutura** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

layout, instalações, utilidades, condições ambientais, acessos, eventos externos, controles de emergência, medições e registros.

### Perguntas de apoio

- Qual condição ambiental ou de infraestrutura estava presente?
- A condição era interna, natural ou externa?
- Quais controles e contingências eram esperados?
- A condição teve vínculo demonstrável com o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Se a resposta for “sim”

Avaliar também:

- **Passo 22 — Fenômenos naturais**.
- **Passo 25 — Infraestrutura ou meio ambiente**.
- **Passo 26 — Evento externo**.
- **Passo 27 — Sabotagem ou aspecto criminal**.

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---


# Bloco 2 — Aprofundamento e situações especiais

## Passo 7 — Problema ligado a Equip. / Instrum. de Processo?

**Classe de triagem:** Equipamentos e instrumentos de processo.

### Objetivo

Determinar se o fator causal está relacionado a **equipamentos e instrumentos de processo** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

identificação; função; configuração; condição; histórico; manutenção; calibração; alarmes; alterações e evidências físicas.

### Perguntas de apoio

- Qual função era requerida?
- Qual condição foi observada?
- Quando a condição surgiu?
- Como a condição influenciou o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [30 — Manutenção](30-Manutencao.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 8 — O que gerou o problema era considerado um risco tolerável.

**Classe de triagem:** Risco anteriormente considerado tolerável.

### Objetivo

Determinar se o fator causal está relacionado a **risco anteriormente considerado tolerável** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

análise de risco, critérios, premissas, controles, aprovações, mudanças, ocorrências e revisão de tolerabilidade.

### Perguntas de apoio

- Qual risco foi considerado tolerável?
- Quais premissas e controles sustentaram a decisão?
- As condições mudaram?
- A avaliação era adequada às informações disponíveis?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Regra específica

Não tratar a classificação anterior de risco tolerável como prova de adequação. Verificar premissas, qualidade da análise, controles previstos, mudanças e informações disponíveis à época.

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 9 — As causas não podem ser determinadas.

**Classe de triagem:** Causa não determinada.

### Objetivo

Determinar se o fator causal está relacionado a **causa não determinada** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

inventário de evidências, lacunas, cronologia, hipóteses testadas, limitações, registros indisponíveis e pareceres técnicos.

### Perguntas de apoio

- Quais hipóteses foram testadas?
- Quais evidências faltam?
- As limitações impedem conclusão segura?
- Que ações reduzem risco sem atribuir causa não demonstrada?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Regra específica

Usar este passo somente após investigação razoável. Não inventar uma causa para encerrar o processo. Registrar hipóteses testadas, evidências indisponíveis, limitações e medidas prudentes de controle.

### Categorias para aprofundamento

- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 10 — Problema ligado a Equip. / Instrum. de Utilidade?

**Classe de triagem:** Equipamentos e instrumentos de utilidade.

### Objetivo

Determinar se o fator causal está relacionado a **equipamentos e instrumentos de utilidade** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

identificação; função; configuração; condição; histórico; manutenção; calibração; alarmes; alterações e evidências físicas.

### Perguntas de apoio

- Qual função era requerida?
- Qual condição foi observada?
- Quando a condição surgiu?
- Como a condição influenciou o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [30 — Manutenção](30-Manutencao.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 11 — Problema ligado a outra classe de Equip. / Instrum.?

**Classe de triagem:** Outras classes de equipamentos e instrumentos.

### Objetivo

Determinar se o fator causal está relacionado a **outras classes de equipamentos e instrumentos** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

procedimentos, instruções, sequência real, riscos, preparação, recursos, observação da tarefa, desvios e interfaces.

### Perguntas de apoio

- Qual método era previsto?
- Qual método foi realmente utilizado?
- O método era correto, disponível e executável?
- A diferença contribuiu para o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [30 — Manutenção](30-Manutencao.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 12 — Problema ligado a Hardware?

**Classe de triagem:** Hardware.

### Objetivo

Determinar se o fator causal está relacionado a **hardware** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

identificação; função; configuração; condição; histórico; manutenção; calibração; alarmes; alterações e evidências físicas.

### Perguntas de apoio

- Qual função era requerida?
- Qual condição foi observada?
- Quando a condição surgiu?
- Como a condição influenciou o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [30 — Manutenção](30-Manutencao.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 13 — Problema ligado a matéria prima / produto?

**Classe de triagem:** Matéria-prima ou produto.

### Objetivo

Determinar se o fator causal está relacionado a **matéria-prima ou produto** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

item, lote, especificação, certificado, validade, inspeção, armazenamento, preservação, rastreabilidade, consumo e resultados.

### Perguntas de apoio

- Qual item foi efetivamente utilizado?
- O item atendia à especificação e estava liberado?
- Como foi armazenado e preservado?
- Existe mecanismo técnico ligando a condição do item ao evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 14 — Problema ligado a insumo de produção?

**Classe de triagem:** Insumo de produção.

### Objetivo

Determinar se o fator causal está relacionado a **insumo de produção** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

item, lote, especificação, certificado, validade, inspeção, armazenamento, preservação, rastreabilidade, consumo e resultados.

### Perguntas de apoio

- Qual item foi efetivamente utilizado?
- O item atendia à especificação e estava liberado?
- Como foi armazenado e preservado?
- Existe mecanismo técnico ligando a condição do item ao evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 15 — Problema ligado a material / padrão de referência?

**Classe de triagem:** Material ou padrão de referência.

### Objetivo

Determinar se o fator causal está relacionado a **material ou padrão de referência** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

item, lote, especificação, certificado, validade, inspeção, armazenamento, preservação, rastreabilidade, consumo e resultados.

### Perguntas de apoio

- Qual item foi efetivamente utilizado?
- O item atendia à especificação e estava liberado?
- Como foi armazenado e preservado?
- Existe mecanismo técnico ligando a condição do item ao evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [30 — Manutenção](30-Manutencao.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 16 — Problema ligado a pessoal CLT?

**Classe de triagem:** Pessoal CLT.

### Objetivo

Determinar se o fator causal está relacionado a **pessoal clt** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

função, tarefa, equipe, vínculo, competência, jornada, carga, procedimentos, recursos, planejamento, supervisão e comunicação.

### Perguntas de apoio

- Qual tarefa e decisão estavam envolvidas?
- Quais condições do sistema influenciaram a execução?
- Competência, recursos e supervisão eram adequados?
- Que barreiras deveriam prevenir ou detectar o desvio?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)
- [39 — Desempenho de Pessoal](39-Desempenho-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 17 — Problema ligado a pessoal PJ / RPA?

**Classe de triagem:** Pessoal PJ ou RPA.

### Objetivo

Determinar se o fator causal está relacionado a **pessoal pj ou rpa** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

função, tarefa, equipe, vínculo, competência, jornada, carga, procedimentos, recursos, planejamento, supervisão e comunicação.

### Perguntas de apoio

- Qual tarefa e decisão estavam envolvidas?
- Quais condições do sistema influenciaram a execução?
- Competência, recursos e supervisão eram adequados?
- Que barreiras deveriam prevenir ou detectar o desvio?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)
- [39 — Desempenho de Pessoal](39-Desempenho-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 18 — Problema ligado a Pessoal de Terceira Parte?

**Classe de triagem:** Pessoal de terceira parte.

### Objetivo

Determinar se o fator causal está relacionado a **pessoal de terceira parte** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

função, tarefa, equipe, vínculo, competência, jornada, carga, procedimentos, recursos, planejamento, supervisão e comunicação.

### Perguntas de apoio

- Qual tarefa e decisão estavam envolvidas?
- Quais condições do sistema influenciaram a execução?
- Competência, recursos e supervisão eram adequados?
- Que barreiras deveriam prevenir ou detectar o desvio?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)
- [39 — Desempenho de Pessoal](39-Desempenho-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 19 — Problema ligado a execução operacional?

**Classe de triagem:** Execução operacional.

### Objetivo

Determinar se o fator causal está relacionado a **execução operacional** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

função, tarefa, equipe, vínculo, competência, jornada, carga, procedimentos, recursos, planejamento, supervisão e comunicação.

### Perguntas de apoio

- Qual tarefa e decisão estavam envolvidas?
- Quais condições do sistema influenciaram a execução?
- Competência, recursos e supervisão eram adequados?
- Que barreiras deveriam prevenir ou detectar o desvio?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)
- [39 — Desempenho de Pessoal](39-Desempenho-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 20 — Problema ligado a supervisão operacional?

**Classe de triagem:** Supervisão operacional.

### Objetivo

Determinar se o fator causal está relacionado a **supervisão operacional** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

função, tarefa, equipe, vínculo, competência, jornada, carga, procedimentos, recursos, planejamento, supervisão e comunicação.

### Perguntas de apoio

- Qual tarefa e decisão estavam envolvidas?
- Quais condições do sistema influenciaram a execução?
- Competência, recursos e supervisão eram adequados?
- Que barreiras deveriam prevenir ou detectar o desvio?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)
- [39 — Desempenho de Pessoal](39-Desempenho-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 21 — Problema ligado a Software?

**Classe de triagem:** Software.

### Objetivo

Determinar se o fator causal está relacionado a **software** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

versão, requisitos, configuração, logs, acessos, validação, mudanças, falhas, integrações e recuperação.

### Perguntas de apoio

- Qual software e versão estavam em uso?
- Qual função deveria executar?
- Houve erro, configuração ou mudança relevante?
- Como isso influenciou o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 22 — Problema ligado a Fenômenos Naturais?

**Classe de triagem:** Fenômenos naturais.

### Objetivo

Determinar se o fator causal está relacionado a **fenômenos naturais** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

layout, instalações, utilidades, condições ambientais, acessos, eventos externos, controles de emergência, medições e registros.

### Perguntas de apoio

- Qual condição ambiental ou de infraestrutura estava presente?
- A condição era interna, natural ou externa?
- Quais controles e contingências eram esperados?
- A condição teve vínculo demonstrável com o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 23 — Problema ligado a atividade de suporte?

**Classe de triagem:** Atividade de suporte.

### Objetivo

Determinar se o fator causal está relacionado a **atividade de suporte** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

função, tarefa, equipe, vínculo, competência, jornada, carga, procedimentos, recursos, planejamento, supervisão e comunicação.

### Perguntas de apoio

- Qual tarefa e decisão estavam envolvidas?
- Quais condições do sistema influenciaram a execução?
- Competência, recursos e supervisão eram adequados?
- Que barreiras deveriam prevenir ou detectar o desvio?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)
- [39 — Desempenho de Pessoal](39-Desempenho-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 24 — Projeto e Desenv. de Produto, Equip., Mat. ou Serviço

**Classe de triagem:** Projeto e desenvolvimento.

### Objetivo

Determinar se o fator causal está relacionado a **projeto e desenvolvimento** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

entradas, saídas, requisitos, riscos, verificações, validações, mudanças, aprovações e registros.

### Perguntas de apoio

- O que foi projetado ou desenvolvido?
- Quais requisitos eram aplicáveis?
- Como foi verificado e validado?
- A deficiência de projeto contribuiu para o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 25 — Problema ligado a Infra / meio ambiente?

**Classe de triagem:** Infraestrutura ou meio ambiente.

### Objetivo

Determinar se o fator causal está relacionado a **infraestrutura ou meio ambiente** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

layout, instalações, utilidades, condições ambientais, acessos, eventos externos, controles de emergência, medições e registros.

### Perguntas de apoio

- Qual condição ambiental ou de infraestrutura estava presente?
- A condição era interna, natural ou externa?
- Quais controles e contingências eram esperados?
- A condição teve vínculo demonstrável com o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [29 — Projeto](29-Projeto.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 26 — Problema ligado a Evento Externo?

**Classe de triagem:** Evento externo.

### Objetivo

Determinar se o fator causal está relacionado a **evento externo** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

layout, instalações, utilidades, condições ambientais, acessos, eventos externos, controles de emergência, medições e registros.

### Perguntas de apoio

- Qual condição ambiental ou de infraestrutura estava presente?
- A condição era interna, natural ou externa?
- Quais controles e contingências eram esperados?
- A condição teve vínculo demonstrável com o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [32 — Fornecedores, Materiais e Serviços](32-Fornecedores-Materiais-e-Servicos.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 27 — Problema ligado a sabotagem / aspecto criminal?

**Classe de triagem:** Sabotagem ou aspecto criminal.

### Objetivo

Determinar se o fator causal está relacionado a **sabotagem ou aspecto criminal** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

layout, instalações, utilidades, condições ambientais, acessos, eventos externos, controles de emergência, medições e registros.

### Perguntas de apoio

- Qual condição ambiental ou de infraestrutura estava presente?
- A condição era interna, natural ou externa?
- Quais controles e contingências eram esperados?
- A condição teve vínculo demonstrável com o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Regra específica

Preservar evidências e encaminhar suspeitas pelos canais autorizados. Não atribuir intenção ou autoria sem apuração competente. A investigação de causa-raiz deve limitar-se aos fatos e às falhas de controle relacionadas ao evento.

### Categorias para aprofundamento

- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)
- [39 — Desempenho de Pessoal](39-Desempenho-de-Pessoal.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

## Passo 28 — Problema ligado a monitoramento?

**Classe de triagem:** Monitoramento.

### Objetivo

Determinar se o fator causal está relacionado a **monitoramento** e se exige aprofundamento nas categorias da LCC.

### Evidências iniciais a pesquisar

plano de controle, parâmetros, limites, instrumentos, frequência, registros, alarmes, tendências, análise crítica e ações.

### Perguntas de apoio

- O que deveria ser controlado ou monitorado?
- O método conseguia detectar o problema?
- O resultado foi analisado e comunicado?
- A falha do controle contribuiu para o evento?

### Decisão de triagem

```text
Resposta: Sim / Não / Indeterminado / Não aplicável
Justificativa:
Evidências utilizadas:
Evidências adicionais necessárias:
```

### Categorias para aprofundamento

- [30 — Manutenção](30-Manutencao.md)
- [31 — Informação Documentada](31-Informacao-Documentada.md)
- [33 — Perigos, Aspectos e Defeitos](33-Perigos-Aspectos-e-Defeitos.md)
- [34 — Protocolos Operacionais](34-Protocolos-Operacionais.md)
- [35 — Fatores de Interação Humano/Ambiente](35-Fatores-Interacao.md)
- [36 — Capacitação de Pessoal](36-Capacitacao-de-Pessoal.md)
- [37 — Responsabilidades, Planejamento e Supervisão do Serviço](37-Responsabilidades-Planejamento-Supervisao.md)
- [38 — Comunicação](38-Comunicacao.md)

### Saída esperada

```text
Fator causal:
Passo aplicado:
Resultado da triagem:
Categorias recomendadas:
Hipóteses iniciais:
Evidências adicionais:
```

---

# Matriz consolidada de roteamento

Ao concluir os passos aplicáveis, registrar:

```text
Fator causal | Passos positivos | Passos indeterminados | Categorias 29 a 39 | Justificativa | Evidências pendentes
```

## Regras de roteamento

- uma categoria pode ser acionada por vários passos;
- um passo pode direcionar para várias categorias;
- registrar somente categorias plausíveis para o fator analisado;
- não excluir categoria apenas porque outra parece mais provável;
- priorizar hipóteses por risco, relação temporal, mecanismo e qualidade das evidências;
- manter rastreabilidade entre fator causal, passo, categoria, código e teste.

# Saída final da etapa D

```text
FATORES CAUSAIS TRIADOS
1. [Fator]
   - Passos aplicáveis:
   - Resultado:
   - Evidências:

CATEGORIAS 29 A 39 RECOMENDADAS
- [Categoria e justificativa]

HIPÓTESES INICIAIS
- [Código ou tema]

EVIDÊNCIAS ADICIONAIS NECESSÁRIAS
- [Evidência, fonte e objetivo]

ITENS INDETERMINADOS
- [Passo e motivo]

PRÓXIMA AÇÃO
- Consultar as categorias recomendadas e elaborar planos de teste.
```

# Cuidados especiais

## Pessoas

Nos passos 3, 16, 17, 18, 19, 20 e 23, não encerrar a análise em “erro humano”. Pesquisar também condições da tarefa, ambiente, recursos, procedimentos, capacitação, planejamento, supervisão, comunicação e barreiras.

## Causa não determinada

O passo 9 é uma conclusão de limitação, não uma causa. Somente utilizar após documentar a investigação realizada e as lacunas que impedem determinação segura.

## Aspectos pessoais

Quando a triagem chegar à categoria 39 e a um item marcado com `*`, relatar somente **“Desempenho de Pessoal — Aspectos Pessoais”**, preservando privacidade e acesso autorizado.

## Sabotagem ou aspecto criminal

No passo 27, não inferir intenção, autoria ou crime. Preservar evidências e acionar os canais competentes conforme os processos aplicáveis.

# Relação com os demais documentos

- iniciar em [`00-ROTEIRO-OPERACIONAL.md`](00-ROTEIRO-OPERACIONAL.md);
- consultar critérios aprofundados em [`01-METODOLOGIA.md`](01-METODOLOGIA.md);
- após a triagem, abrir diretamente as categorias 29 a 39 recomendadas;
- registrar confirmação, refutação ou resultado inconclusivo conforme a metodologia.

# Controle e integridade

**Documento de origem:** Lista Compreensiva de Causas — FOG 222, revisão 00, de 24/10/2023.

**Nota de integridade:** as perguntas dos passos 1 a 28 foram preservadas conforme a fonte. Evidências sugeridas, perguntas de apoio, regras de decisão e roteamento para as categorias 29 a 39 são orientações complementares para operacionalizar a LCC.
