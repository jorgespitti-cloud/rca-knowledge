# 00 — Roteiro Operacional da Investigação

## Finalidade

Este roteiro transforma a sequência inicial da **Lista Compreensiva de Causas (LCC)** em um fluxo operacional para agentes de inteligência artificial e investigadores humanos.

O roteiro deve ser executado antes da seleção das categorias de causa-raiz 29 a 39.

A sequência obrigatória é:

1. **Etapa A — Descrever o evento**;
2. **Etapa B — Pesquisar dados e evidências**;
3. **Etapa C — Organizar dados e evidências**;
4. **Etapa D — Iniciar a triagem a partir de cada fator causal**;
5. consultar as categorias 29 a 39 indicadas pela triagem;
6. pesquisar e testar hipóteses de causa;
7. continuar os “porquês” após confirmar uma causa.

> **Regra para o agente:** não saltar diretamente da descrição inicial para uma causa provável. Antes de sugerir causas, concluir as etapas A, B e C com as informações disponíveis e declarar as lacunas existentes.

---

# Visão geral do fluxo

```text
A — Descrever o evento
        ↓
B — Pesquisar dados e evidências
        ↓
C — Organizar dados e evidências
        ↓
D — Triar os fatores causais — passos 1 a 28
        ↓
Categorias 29 a 39
        ↓
Pesquisar e testar hipóteses
        ↓
Confirmar, refutar ou classificar como inconclusiva
        ↓
Continuar os porquês
```

---

# Etapa A — Descrever o evento

## Objetivo

Documentar o evento de forma objetiva, delimitada e verificável, sem antecipar causas.

A descrição deve permitir compreender:

- o que ocorreu;
- o que deveria ter ocorrido;
- quando e onde ocorreu;
- quem ou quais funções participaram;
- como o evento se desenvolveu;
- qual foi a extensão ou consequência conhecida;
- quais informações ainda estão ausentes.

## Aplicação do 5W2H

### Por quê?

Registrar o motivo conhecido para a existência da atividade, processo ou requisito. Não utilizar este campo para antecipar a causa-raiz.

### O quê?

Descrever o evento, desvio, falha, não conformidade, incidente ou resultado observado.

### Quando?

Registrar data, horário, duração, turno, etapa e sequência temporal conhecida.

### Onde?

Identificar local físico, processo, unidade, sistema, equipamento, lote, etapa ou ambiente envolvido.

### Quem?

Identificar funções, equipes e partes interessadas relevantes. Evitar exposição desnecessária de nomes pessoais.

### Como?

Descrever o modo de ocorrência e as condições observadas, sem inserir causas ainda não demonstradas.

### Quanto?

Informar quantidade, extensão, frequência, severidade, custo, impacto ou população afetada, quando conhecido.

## Informações mínimas

A etapa A deve registrar:

```text
Título do evento:
Data e horário:
Local, processo ou sistema:
Atividade em execução:
Condição esperada:
Condição encontrada:
Desvio observado:
Consequência conhecida:
Contenção inicial realizada:
Fontes iniciais:
Lacunas de informação:
```

## Modelo de descrição

```text
Em [data e horário], durante [atividade ou processo], em [local, sistema ou equipamento], foi observado [fato verificável], em comparação com [requisito ou condição esperada]. O evento resultou em [consequência conhecida]. Foram realizadas as contenções [ações]. Permanecem desconhecidos [lacunas].
```

## Perguntas de controle

Antes de encerrar a etapa A, verificar:

- A descrição contém fatos ou já presume uma causa?
- A condição esperada está identificada?
- O desvio entre esperado e realizado está claro?
- O evento está delimitado no tempo e no espaço?
- Consequências e contenções estão separadas das causas?
- Fatos, relatos e suposições estão identificados separadamente?
- As lacunas relevantes foram declaradas?

## Critério de conclusão da etapa A

A etapa A pode ser considerada concluída quando houver uma descrição suficiente para orientar a coleta de evidências, mesmo que ainda existam lacunas explicitamente registradas.

## Saída esperada

```text
DESCRIÇÃO OBJETIVA DO EVENTO
[Texto com 5W2H]

CONDIÇÃO ESPERADA
[Requisito ou resultado esperado]

CONDIÇÃO ENCONTRADA
[Fato observado]

CONSEQUÊNCIAS CONHECIDAS
[Consequências]

LACUNAS INICIAIS
[Informações ainda necessárias]
```

---

# Etapa B — Pesquisar dados e evidências

## Objetivo

Reunir evidências diretas e indiretas suficientes para reconstruir o evento, identificar fatores críticos e permitir o teste posterior das hipóteses.

## Regra de preservação

Antes de reparar, limpar, descartar, reiniciar, alterar configurações ou modificar o local do evento, avaliar a necessidade de preservar:

- fotografias e vídeos;
- peças, materiais, produtos e amostras;
- posição e condição de equipamentos e controles;
- dados de sistemas, alarmes e registros automáticos;
- documentos e versões utilizadas;
- mensagens, e-mails e metadados;
- condições ambientais;
- identificação de lotes;
- cronologia inicial;
- nomes das funções e fontes de informação.

A preservação deve respeitar segurança, integridade, privacidade e autoridade aplicáveis.

## Evidências diretas

Podem incluir:

- observação do local;
- fotografias e vídeos contemporâneos;
- peças, materiais e amostras;
- medições;
- alarmes e dados automáticos;
- registros eletrônicos contemporâneos;
- observação ou reprodução controlada da atividade, quando segura e autorizada.

## Evidências indiretas

Podem incluir:

- procedimentos, desenhos e especificações;
- registros de operação, manutenção e calibração;
- certificados e relatórios;
- análises de risco e gestão de mudanças;
- registros de treinamento, planejamento e supervisão;
- contratos, pedidos, inspeções e dados de fornecedores;
- comunicações, atas e livros de turno;
- histórico de eventos semelhantes;
- entrevistas com participantes, testemunhas e especialistas.

## Planejamento da coleta

Para cada informação necessária, registrar:

```text
Pergunta a responder:
Evidência necessária:
Fonte provável:
Responsável pela obtenção:
Prazo:
Cuidados de preservação ou privacidade:
Situação: disponível / pendente / indisponível
```

## Entrevistas

As entrevistas devem:

- buscar fatos e percepções sem sugerir respostas;
- começar por perguntas abertas;
- reconstruir a sequência na perspectiva da pessoa entrevistada;
- distinguir o que a pessoa viu, ouviu, fez, decidiu ou inferiu;
- evitar linguagem acusatória;
- confrontar divergências com outras evidências;
- preservar informações pessoais e sensíveis.

### Perguntas básicas de entrevista

- O que estava acontecendo antes do evento?
- Qual era a tarefa e o resultado esperado?
- Que informações e recursos estavam disponíveis?
- O que foi observado primeiro?
- Quais decisões e ações ocorreram em seguida?
- Houve mudança, interrupção, pressão, dúvida ou condição incomum?
- Que controles deveriam impedir ou detectar o problema?
- O que poderia ajudar a explicar a diferença entre o esperado e o ocorrido?

## Avaliação da evidência

Para cada evidência, avaliar:

- relevância;
- autenticidade;
- integridade;
- rastreabilidade;
- temporalidade;
- confiabilidade;
- independência;
- limitações.

## Registro mínimo

```text
ID da evidência:
Descrição:
Tipo: direta / documental / testemunhal / analítica
Fonte:
Data e horário:
Relação com o evento:
Fato apoiado ou contradito:
Limitações:
Local de armazenamento ou referência:
```

## Perguntas de controle

Antes de encerrar a etapa B, verificar:

- O cenário e os dados voláteis foram preservados?
- Foram coletadas evidências diretas e indiretas?
- As principais fontes foram consultadas?
- Há evidências independentes para fatos críticos?
- A cronologia pode ser reconstruída?
- Foram registradas evidências contrárias às primeiras explicações?
- As evidências indisponíveis e seus impactos foram declarados?

## Critério de conclusão da etapa B

A etapa B pode ser considerada concluída para iniciar a organização quando houver evidência suficiente para reconstruir provisoriamente o evento e identificar claramente as lacunas restantes.

A coleta pode continuar durante etapas posteriores quando novos testes exigirem informações adicionais.

## Saída esperada

```text
INVENTÁRIO DE EVIDÊNCIAS
- [ID, descrição e fonte]

ENTREVISTAS REALIZADAS
- [Função, data e temas]

EVIDÊNCIAS PENDENTES
- [Evidência, responsável e prazo]

EVIDÊNCIAS INDISPONÍVEIS
- [Evidência e impacto]

LIMITAÇÕES DA COLETA
- [Limitação]
```

---

# Etapa C — Organizar dados e evidências

## Objetivo

Organizar as informações coletadas para separar fatos, relatos, inferências e lacunas; reconstruir a cronologia; comparar condição esperada e realizada; e identificar fatores críticos relevantes.

## Classificação das informações

Cada informação deve ser classificada como:

### Fato confirmado

Informação sustentada por evidência confiável e rastreável.

### Relato

Informação fornecida por uma pessoa e ainda não confirmada de modo independente.

### Inferência

Interpretação lógica baseada nos fatos disponíveis, ainda sujeita a teste.

### Hipótese

Explicação proposta, específica e testável.

### Lacuna

Informação necessária, mas ainda indisponível ou impossível de obter.

## Construção da cronologia

Organizar os fatos em ordem temporal, incluindo:

- condições anteriores;
- decisões;
- comunicações;
- mudanças;
- preparação e início da atividade;
- sinais, alarmes e desvios;
- evento principal;
- respostas e contenções;
- descobertas posteriores.

### Modelo de cronologia

```text
Data/hora | Fato ou ação | Fonte/evidência | Classificação | Observação
```

## Comparação entre esperado e realizado

Para cada aspecto relevante, registrar:

```text
Requisito ou condição esperada:
Condição ou trabalho realizado:
Diferença observada:
Evidência da diferença:
Consequência possível:
Necessidade de teste:
```

## Identificação de fatores críticos

Fatores críticos são ações, condições, decisões, mudanças ou falhas de barreira que podem ter participado da sequência do evento.

Para cada fator crítico, perguntar:

- O fator estava presente no período relevante?
- O fator ocorreu antes ou durante o evento?
- O fator tem mecanismo plausível de influência?
- O fator aumentou probabilidade, severidade ou dificuldade de detecção?
- O evento ocorreria da mesma forma sem esse fator?
- Qual evidência sustenta ou contradiz essa relação?
- O fator deve seguir para a triagem da etapa D?

## Organização por famílias de fatores

Sem concluir causas, os fatores podem ser agrupados provisoriamente em:

- máquinas, equipamentos, instrumentos e hardware;
- matérias-primas, insumos, produtos e padrões;
- pessoas e organização do trabalho;
- métodos de trabalho;
- métodos de controle e monitoramento;
- meio ambiente e infraestrutura;
- software, eventos naturais ou externos;
- projeto e desenvolvimento.

## Mapa inicial de barreiras

Identificar as barreiras que deveriam:

- prevenir o evento;
- detectar a condição;
- mitigar a consequência;
- permitir recuperação.

### Modelo

```text
Barreira esperada:
Função:
Situação encontrada:
Evidência:
Possível fator crítico:
```

## Perguntas de controle

Antes de encerrar a etapa C, verificar:

- Os fatos estão separados de relatos e inferências?
- A cronologia está coerente com as evidências?
- Contradições estão registradas em vez de ocultadas?
- Condição esperada e condição realizada foram comparadas?
- Fatores críticos foram identificados sem ainda serem tratados como causas confirmadas?
- Barreiras relevantes foram mapeadas?
- As lacunas que impedem a triagem foram identificadas?

## Critério de conclusão da etapa C

A etapa C pode ser considerada concluída quando houver:

- cronologia provisória;
- fatos e lacunas classificados;
- comparação entre esperado e realizado;
- lista de fatores críticos;
- mapa inicial de barreiras;
- base suficiente para iniciar a etapa D.

## Saída esperada

```text
CRONOLOGIA
- [Data/hora — fato — evidência]

FATOS CONFIRMADOS
- [Fato]

RELATOS A CONFIRMAR
- [Relato]

INFERÊNCIAS E HIPÓTESES INICIAIS
- [Inferência ou hipótese]

CONTRADIÇÕES
- [Contradição e fontes]

LACUNAS
- [Lacuna e impacto]

FATORES CRÍTICOS PARA TRIAGEM
- [Fator e evidência]

BARREIRAS INICIAIS
- [Barreira e situação]
```

---

# Etapa D — Iniciar a triagem a partir de cada fator causal

## Objetivo

Utilizar cada fator crítico identificado na etapa C como ponto de partida para a triagem dos passos 1 a 28 da LCC.

A etapa D não confirma causas. A etapa D direciona a investigação para as categorias de causa-raiz 29 a 39 que devem ser consultadas.

## Documento de continuidade

Prosseguir para:

```text
02-TRIAGEM-DE-FATORES-CAUSAIS.md
```

## Regras para iniciar a triagem

- executar a triagem para cada fator crítico relevante;
- admitir mais de uma resposta positiva e mais de uma categoria aplicável;
- registrar a justificativa e as evidências para cada encaminhamento;
- não selecionar “pessoas” como fator sem avaliar tarefa, ambiente, recursos e organização;
- não descartar fatores apenas porque a evidência inicial é incompleta;
- declarar quando a categoria não puder ser determinada;
- manter hipóteses como abertas até a realização dos testes.

## Entrada necessária

```text
Fator crítico:
Descrição:
Evidências associadas:
Momento na cronologia:
Barreira relacionada:
Pergunta que precisa ser respondida:
```

## Saída esperada

```text
FATOR CRÍTICO TRIADO
[Fator]

PASSOS 1 A 28 APLICÁVEIS
- [Número e justificativa]

CATEGORIAS 29 A 39 RECOMENDADAS
- [Categoria e motivo]

HIPÓTESES INICIAIS
- [Código ou tema]

EVIDÊNCIAS ADICIONAIS NECESSÁRIAS
- [Evidência]
```

---

# Regras de passagem entre as etapas

## Da etapa A para a etapa B

A descrição do evento deve indicar quais evidências precisam ser preservadas e coletadas.

## Da etapa B para a etapa C

As evidências devem estar identificadas, rastreáveis e acompanhadas de suas limitações.

## Da etapa C para a etapa D

A cronologia, as diferenças entre esperado e realizado e os fatores críticos devem estar suficientemente organizados para permitir a triagem.

## Da etapa D para as categorias 29 a 39

Cada encaminhamento deve registrar:

- fator crítico de origem;
- passo de triagem aplicável;
- categoria recomendada;
- motivo do encaminhamento;
- evidências disponíveis;
- evidências adicionais necessárias.

---

# Conduta esperada do agente

O agente deve:

- conduzir uma etapa por vez;
- utilizar as informações fornecidas pelo investigador;
- fazer perguntas objetivas para preencher lacunas essenciais;
- apresentar uma síntese ao final de cada etapa;
- separar fatos, relatos, inferências e hipóteses;
- não inventar evidências;
- não confirmar causas antes do teste;
- informar claramente quando os dados forem insuficientes;
- registrar a trilha entre fator crítico, passo de triagem, categoria e hipótese.

O agente não deve:

- pular diretamente para uma causa provável;
- preencher lacunas com suposições não declaradas;
- omitir evidências contrárias;
- atribuir culpa ou intenção;
- solicitar dados pessoais ou sensíveis sem necessidade e autorização;
- tratar não conformidade documental como causa automática;
- encerrar a investigação em “erro humano”.

---

# Modelo consolidado de execução

```text
ETAPA A — DESCRIÇÃO DO EVENTO
[Descrição, esperado, encontrado, consequência e lacunas]

ETAPA B — DADOS E EVIDÊNCIAS
[Evidências disponíveis, pendentes, indisponíveis e limitações]

ETAPA C — ORGANIZAÇÃO
[Cronologia, fatos, relatos, inferências, contradições, lacunas e fatores críticos]

ETAPA D — TRIAGEM
[Passos 1 a 28 aplicáveis e categorias 29 a 39 recomendadas]

HIPÓTESES PARA PESQUISA E TESTE
[Código, descrição, evidências necessárias e prioridade]
```

---

# Controle e integridade

**Documento de origem:** Lista Compreensiva de Causas — FOG 222, revisão 00, de 24/10/2023.

**Relação com a base:** este roteiro operacional complementa o arquivo `01-METODOLOGIA.md` e direciona a continuidade para `02-TRIAGEM-DE-FATORES-CAUSAIS.md`.

**Nota de integridade:** as etapas A, B, C e D preservam a lógica original da LCC. Os modelos, critérios de conclusão, perguntas de controle e orientações ao agente são conteúdo complementar para operacionalizar a investigação.
