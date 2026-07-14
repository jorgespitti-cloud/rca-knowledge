# 01 — Metodologia de Pesquisa e Teste de Causas

## 1. Finalidade

Esta metodologia orienta agentes de inteligência artificial e investigadores humanos na utilização da **Lista Compreensiva de Causas (LCC)** para:

1. compreender e delimitar o evento;
2. coletar e organizar dados e evidências;
3. pesquisar causas contribuintes plausíveis;
4. formular hipóteses de causa de maneira objetiva e testável;
5. confirmar, refutar ou classificar hipóteses como inconclusivas;
6. continuar os “porquês” após a confirmação de uma causa;
7. registrar uma trilha de investigação clara, rastreável e tecnicamente defensável.

A LCC deve ser usada como **taxonomia de hipóteses e roteiro de investigação**, e não como lista de conclusões automáticas.

---

## 2. Escopo de aplicação

Esta metodologia pode apoiar a investigação de:

- não conformidades de produtos, processos e serviços;
- incidentes e quase eventos de saúde e segurança;
- ocorrências e desvios ambientais;
- reclamações de clientes;
- falhas de equipamentos, instrumentos e sistemas;
- desvios de processo e resultados fora de especificação;
- falhas de fornecedores, materiais e serviços;
- recorrências e ineficácia de ações anteriores;
- outros problemas que exijam análise estruturada de causas.

A metodologia não substitui requisitos legais, normativos, contratuais ou corporativos aplicáveis, nem a validação por profissionais competentes e autorizados.

---

## 3. Arquitetura de consulta da base

A base foi organizada em dois níveis:

1. **Nível 1 — `INDEX.md`:** índice central e seleção das categorias aplicáveis;
2. **Nível 2 — arquivo da categoria:** causas, evidências, perguntas e critérios de teste.

O agente deve consultar o `INDEX.md`, selecionar uma ou mais categorias pertinentes e trabalhar no próprio arquivo da categoria, sem exigir um terceiro nível de navegação.

### Categorias disponíveis

- **29 — Projeto**;
- **30 — Manutenção**;
- **31 — Informação Documentada**;
- **32 — Fornecedores, Materiais e Serviços**;
- **33 — Perigos, Aspectos e Defeitos**;
- **34 — Protocolos Operacionais**;
- **35 — Fatores de Interação Humano/Ambiente**;
- **36 — Capacitação de Pessoal**;
- **37 — Responsabilidades, Planejamento e Supervisão do Serviço**;
- **38 — Comunicação**;
- **39 — Desempenho de Pessoal**.

---

## 4. Princípios obrigatórios

### 4.1 Basear conclusões em evidências

Uma hipótese não deve ser confirmada apenas porque:

- parece provável;
- é comum em eventos semelhantes;
- foi sugerida por uma pessoa experiente;
- não foi encontrada explicação alternativa;
- existe uma não conformidade documental;
- houve uma ação ou omissão humana.

A conclusão deve demonstrar a condição, sua presença no período relevante, o mecanismo de influência e o vínculo com o evento.

### 4.2 Pesquisar evidências favoráveis e desfavoráveis

Para cada hipótese, o agente deve procurar deliberadamente:

- evidências que sustentem a hipótese;
- evidências que contradigam a hipótese;
- explicações alternativas;
- limitações e incertezas da análise.

### 4.3 Não confundir correlação com causalidade

A presença simultânea de uma condição e de um evento não demonstra, por si só, que uma causou a outra. É necessário explicar e testar o mecanismo causal.

### 4.4 Não confundir ausência de registro com ausência de atividade

Quando um registro não for encontrado, distinguir:

- atividade não realizada;
- atividade realizada sem registro;
- registro perdido ou indisponível;
- registro incorreto ou incompleto;
- registro existente, mas sem análise crítica.

### 4.5 Não encerrar a análise em “erro humano”

Antes de concluir uma causa ligada à pessoa, investigar:

- projeto da tarefa e das interfaces;
- equipamentos, ferramentas e recursos;
- condições ambientais e carga de trabalho;
- procedimentos e informações disponíveis;
- treinamento, competência e autorização;
- responsabilidades, planejamento e supervisão;
- comunicação e passagem de serviço;
- barreiras de prevenção, detecção e recuperação.

### 4.6 Preservar a descrição original da LCC

Os códigos e as descrições originais da LCC devem permanecer identificáveis. Interpretações, perguntas, evidências e testes incluídos nesta base são orientações complementares.

### 4.7 Não fabricar dados

O agente não deve inventar documentos, medições, entrevistas, testemunhos, registros ou resultados. Quando faltarem informações, deve declarar a lacuna e recomendar como obtê-las.

---

## 5. Visão geral do processo

A investigação deve seguir oito etapas:

1. **Descrever o evento**;
2. **Preservar e coletar evidências**;
3. **Organizar os fatos e a cronologia**;
4. **Identificar fatores causais**;
5. **Pesquisar causas contribuintes na LCC**;
6. **Formular e testar hipóteses**;
7. **Continuar os porquês e avaliar causas sistêmicas**;
8. **Concluir, registrar e comunicar os resultados**.

---

# Fase A — Descrever o evento

## 6. Construção da descrição inicial

A descrição deve ser factual, objetiva e separada de interpretações causais.

Utilizar os elementos do 5W2H:

- **O quê:** o que ocorreu ou deixou de ocorrer;
- **Por quê:** motivo conhecido do contexto, sem antecipar a causa-raiz;
- **Quando:** data, horário, duração e sequência;
- **Onde:** local físico, processo, sistema, etapa ou equipamento;
- **Quem:** funções e participantes relevantes, evitando exposição desnecessária de nomes;
- **Como:** modo de ocorrência e condições observadas;
- **Quanto:** extensão, quantidade, severidade, frequência, custo ou impacto.

## 7. Regras para a descrição

A descrição inicial deve:

- declarar a condição esperada;
- declarar a condição encontrada;
- identificar o desvio entre esperado e observado;
- informar consequências conhecidas;
- separar fatos confirmados de relatos e suposições;
- evitar palavras causais sem evidência, como “porque”, “devido a” e “por falha de”;
- declarar lacunas relevantes.

### Modelo

```text
Em [data e horário], durante [atividade/processo], em [local], foi observado [fato verificável], em comparação com [requisito ou condição esperada]. O evento resultou em [consequência conhecida]. Até o momento, permanecem desconhecidos [lacunas relevantes].
```

---

# Fase B — Pesquisar dados e evidências

## 8. Preservação inicial

Antes de alterar, reparar, limpar, descartar ou reiniciar o cenário, avaliar a necessidade de preservar:

- fotografias e vídeos;
- condições do local;
- peças e materiais;
- amostras e lotes;
- configurações e dados de sistemas;
- alarmes e registros automáticos;
- documentos e versões utilizadas;
- comunicações e metadados;
- nomes das funções envolvidas;
- cronologia e condições ambientais.

A preservação deve respeitar segurança, privacidade, integridade, autoridade e requisitos aplicáveis.

## 9. Tipos de evidência

### Evidência direta

- observação do local ou da condição;
- fotografia ou vídeo contemporâneo;
- dado automático do equipamento ou sistema;
- peça, material ou amostra relacionada;
- medição realizada com método adequado.

### Evidência documental

- procedimentos, desenhos e especificações;
- registros de operação, manutenção e calibração;
- certificados e relatórios;
- históricos de revisão e trilhas de auditoria;
- registros de treinamento, planejamento e supervisão;
- e-mails, mensagens, atas e chamados.

### Evidência testemunhal

- entrevistas com participantes e testemunhas;
- relatos de especialistas;
- reconstruções do trabalho real.

Relatos devem ser confrontados, quando possível, com evidências independentes.

## 10. Avaliação da qualidade da evidência

Para cada evidência, avaliar:

- **relevância:** relação com a hipótese e o evento;
- **autenticidade:** origem e autoria demonstráveis;
- **integridade:** conteúdo completo e protegido contra alteração indevida;
- **rastreabilidade:** vínculo com pessoa, tarefa, ativo, lote, local e período;
- **temporalidade:** proximidade com o evento;
- **confiabilidade:** método de obtenção e possibilidade de erro;
- **independência:** existência de confirmação por outra fonte;
- **suficiência:** capacidade de sustentar ou refutar a hipótese.

## 11. Registro mínimo de evidência

Para cada evidência relevante, registrar:

```text
Identificação:
Descrição:
Fonte:
Data e horário:
Responsável pela coleta:
Relação com o evento:
Hipótese apoiada ou contradita:
Limitações:
Local de armazenamento ou referência:
```

---

# Fase C — Organizar dados e evidências

## 12. Cronologia

Construir uma linha do tempo contendo:

- condições anteriores;
- decisões e comunicações;
- mudanças;
- ações executadas;
- alarmes ou sinais;
- evento principal;
- respostas e contenções;
- descobertas posteriores.

Distinguir claramente:

- fato confirmado;
- relato ainda não confirmado;
- inferência;
- lacuna de informação.

## 13. Comparação entre esperado e realizado

Registrar, conforme aplicável:

```text
Requisito ou condição esperada:
Condição ou trabalho realizado:
Diferença observada:
Evidência da diferença:
Possível relação com o evento:
```

## 14. Fatores causais

Um fator causal é uma ação, condição, decisão, mudança ou falha de barreira que pode ter participado da sequência do evento.

Para cada fator causal, perguntar:

- Se o fator não existisse, o evento ainda ocorreria da mesma maneira?
- O fator alterou probabilidade, severidade, detecção ou capacidade de recuperação?
- Há evidência de que o fator estava presente no momento relevante?
- Qual categoria da LCC deve ser consultada?

---

# Fase D — Pesquisar causas contribuintes na LCC

## 15. Seleção de categorias

O agente deve selecionar uma ou mais categorias com base nos fatores causais, sem limitar prematuramente a investigação.

### Exemplo de encaminhamento

- requisitos, verificação ou validação → **29**;
- falha, manutenção ou calibração → **30**;
- registros e rastreabilidade → **31**;
- fornecedor, material ou armazenamento → **32**;
- riscos, mudanças, inspeções ou recorrência → **33**;
- procedimentos e instruções → **34**;
- ambiente, recursos, carga ou interface → **35**;
- treinamento, competência ou certificação → **36**;
- responsabilidades, planejamento ou supervisão → **37**;
- mensagens, canais, feedback ou timing → **38**;
- gestão de desempenho e aspectos pessoais autorizados → **39**.

## 16. Pesquisa de hipóteses

Para cada categoria selecionada:

1. identificar os códigos potencialmente aplicáveis;
2. registrar por que cada hipótese merece ser investigada;
3. listar evidências necessárias;
4. evitar confirmar a hipótese antes do teste;
5. priorizar as hipóteses por relevância, risco e disponibilidade de evidências.

### Modelo de hipótese candidata

```text
Código LCC:
Descrição original:
Fator causal relacionado:
Motivo para investigar:
Evidências necessárias:
Evidências já disponíveis:
Explicações alternativas:
Prioridade de teste:
```

---

# Fase E — Formular e testar hipóteses

## 17. Formulação da hipótese

Uma hipótese deve ser específica, verificável e causal.

### Estrutura recomendada

```text
A condição [X] estava presente em [período/local], influenciou [ação, decisão, barreira ou processo] por meio de [mecanismo] e contribuiu para [evento ou consequência].
```

### Evitar hipóteses vagas

Evitar:

```text
Falha de comunicação.
Falta de treinamento.
Erro humano.
Problema de procedimento.
Falha de supervisão.
```

Preferir:

```text
A alteração do limite operacional não foi comunicada ao turno noturno antes do início da atividade, fazendo com que a equipe utilizasse o valor anterior na configuração do equipamento.
```

## 18. Plano de teste

Para cada hipótese, definir antes da conclusão:

```text
Hipótese:
Condição que deve existir se a hipótese for verdadeira:
Evidências que sustentariam a hipótese:
Evidências que a contradiriam:
Método de verificação:
Critério de confirmação:
Critério de refutação:
Possível resultado inconclusivo:
Responsável e prazo:
```

## 19. Métodos de teste

Conforme a hipótese e os riscos, podem ser utilizados:

- inspeção física;
- análise documental;
- comparação de versões;
- rastreamento de lote ou item;
- reprodução controlada ou simulação autorizada;
- análise de dados e tendências;
- verificação funcional;
- comparação com equipamento, processo ou período equivalente;
- entrevistas estruturadas;
- análise de barreiras;
- análise de mudanças;
- revisão por especialista competente.

Nenhum teste deve criar risco indevido ou comprometer evidências.

## 20. Condição necessária, suficiente e contribuinte

Ao avaliar o papel da hipótese, distinguir:

- **condição necessária:** sem a condição, o evento não ocorreria daquela forma;
- **condição suficiente:** a condição, por si só, seria capaz de produzir o evento nas circunstâncias analisadas;
- **causa contribuinte:** aumentou a probabilidade, severidade ou dificuldade de detecção ou recuperação;
- **condição presente sem influência:** existia, mas não contribuiu para o evento.

Nem toda não conformidade encontrada é causa do evento.

## 21. Teste contrafactual

Perguntar:

> Se a condição investigada não existisse, mantendo-se as demais condições, o evento provavelmente teria ocorrido da mesma forma?

Interpretação:

- se **não**, a hipótese ganha força causal;
- se **sim**, a condição pode ser secundária ou não causal;
- se não houver informação suficiente, o resultado permanece inconclusivo.

O teste contrafactual deve ser sustentado por dados, conhecimento técnico ou comparação válida, e não apenas por opinião.

## 22. Análise de barreiras

Para cada hipótese, identificar:

- barreiras de prevenção;
- barreiras de detecção;
- barreiras de mitigação;
- barreiras de recuperação.

Para cada barreira, registrar:

```text
Barreira esperada:
Função da barreira:
Situação encontrada:
Motivo da falha ou ausência:
Evidência:
Relação com o evento:
```

---

# Fase F — Classificar o resultado

## 23. Hipótese confirmada

Classificar como **confirmada** quando houver evidência suficiente de que:

1. a condição existia no período relevante;
2. a condição afetou uma ação, decisão, processo ou barreira;
3. o mecanismo causal é tecnicamente plausível;
4. o vínculo com o evento está demonstrado;
5. evidências contrárias relevantes foram consideradas;
6. explicações alternativas não explicam melhor os fatos disponíveis.

## 24. Hipótese refutada

Classificar como **refutada** quando houver evidência suficiente de que:

- a condição não existia;
- a condição estava adequadamente controlada;
- o evento ocorreu por mecanismo incompatível;
- a condição não afetou a ação ou decisão relevante;
- outra evidência demonstrou que a hipótese não explica o evento.

## 25. Hipótese inconclusiva

Classificar como **inconclusiva** quando:

- as evidências forem insuficientes;
- houver conflito não resolvido entre fontes;
- o cenário não puder ser reconstruído;
- o método de teste não for confiável;
- o vínculo causal não puder ser estabelecido nem afastado.

O agente deve declarar:

- quais informações faltam;
- como poderiam ser obtidas;
- riscos de decidir sem essas informações;
- se a hipótese deve permanecer aberta.

## 26. Matriz de conclusão da hipótese

```text
Código LCC:
Hipótese:
Evidências favoráveis:
Evidências desfavoráveis:
Mecanismo causal:
Teste contrafactual:
Barreiras relacionadas:
Explicações alternativas:
Limitações:
Resultado: Confirmada / Refutada / Inconclusiva
Justificativa:
```

---

# Fase G — Continuar os porquês

## 27. Regra de continuidade

Quando uma causa for confirmada, continuar os “porquês” pelo menos mais duas vezes, quando aplicável, para buscar:

- condições antecedentes;
- decisões organizacionais;
- controles ausentes ou ineficazes;
- causas sistêmicas;
- condições que permitiram recorrência.

## 28. Formulação dos porquês

Cada “porquê” deve:

- partir da causa anteriormente demonstrada;
- produzir uma nova hipótese testável;
- ser sustentado por evidências;
- evitar saltos lógicos;
- terminar quando a organização puder agir sobre a condição dentro do escopo aplicável.

### Modelo de trilha

```text
Evento:
Por quê 1 — condição imediata:
Evidência:
Por quê 2 — condição contribuinte:
Evidência:
Por quê 3 — condição sistêmica:
Evidência:
Categoria e código LCC:
```

## 29. Critérios para interromper a sequência

A sequência pode ser encerrada quando:

- a causa sistêmica estiver demonstrada;
- houver capacidade de definir ação eficaz e verificável;
- novos porquês saírem do escopo ou da capacidade legítima de controle;
- as evidências não permitirem continuar, devendo a limitação ser registrada.

Não encerrar somente porque foi identificada uma ação ou omissão individual.

---

# Fase H — Concluir e comunicar

## 30. Estrutura da conclusão

A conclusão deve conter:

1. descrição objetiva do evento;
2. escopo e limitações da investigação;
3. cronologia dos fatos;
4. fatores causais identificados;
5. categorias e códigos LCC pesquisados;
6. hipóteses testadas;
7. evidências favoráveis e desfavoráveis;
8. hipóteses confirmadas, refutadas e inconclusivas;
9. mecanismo causal e análise de barreiras;
10. continuidade dos porquês;
11. causas contribuintes e sistêmicas confirmadas;
12. lacunas e incertezas remanescentes.

## 31. Linguagem da conclusão

Utilizar linguagem proporcional à força das evidências:

- **“As evidências demonstram...”** para conclusão confirmada;
- **“As evidências contradizem...”** para hipótese refutada;
- **“Não foi possível determinar...”** para resultado inconclusivo;
- **“Há indicação, mas faltam...”** quando a evidência é parcial.

Evitar:

- “certamente”, sem suporte;
- “obviamente”;
- julgamento de caráter;
- diagnóstico ou inferência pessoal;
- atribuição de culpa;
- expressão genérica sem mecanismo causal.

## 32. Regra especial para a categoria 39

Nos itens da categoria 39 marcados com `*`, utilizar no relato somente:

```text
Desempenho de Pessoal — Aspectos Pessoais
```

Não registrar diagnóstico, medicamento, condição clínica, informação psicológica ou problema pessoal. Questões ocupacionais devem ser encaminhadas aos processos e pessoas autorizados.

---

## 33. Modelo de resposta do agente — Pesquisa de causas contribuintes

```text
EVENTO ANALISADO
[Descrição objetiva]

FATOS CONFIRMADOS
- [Fato e evidência]

LACUNAS DE INFORMAÇÃO
- [Lacuna e forma de obtenção]

FATORES CAUSAIS
- [Fator causal]

CATEGORIAS LCC RECOMENDADAS
- [Categoria e justificativa]

HIPÓTESES PARA PESQUISA
1. [Código e descrição]
   - Motivo para investigar:
   - Evidências a buscar:
   - Perguntas:
   - Explicações alternativas:
   - Prioridade:

PRÓXIMOS PASSOS
- [Ação de coleta ou verificação]
```

## 34. Modelo de resposta do agente — Teste de causas

```text
HIPÓTESE
[Código LCC e formulação testável]

EVIDÊNCIAS FAVORÁVEIS
- [Evidência]

EVIDÊNCIAS DESFAVORÁVEIS
- [Evidência]

MECANISMO CAUSAL
[Como a condição poderia produzir ou contribuir para o evento]

TESTE REALIZADO
[Método, critério e resultado]

TESTE CONTRAFACTUAL
[O evento ocorreria da mesma forma sem a condição?]

BARREIRAS
- Prevenção:
- Detecção:
- Mitigação:
- Recuperação:

RESULTADO
Confirmada / Refutada / Inconclusiva

JUSTIFICATIVA
[Conclusão proporcional às evidências]

PRÓXIMOS PORQUÊS
- [Hipótese antecedente]
- [Hipótese sistêmica]

LACUNAS E LIMITAÇÕES
- [Lacuna]
```

---

## 35. Verificações contra vieses

Antes de concluir, o agente e o investigador devem verificar:

### Viés de confirmação

- Foram procuradas evidências que contradizem a hipótese?

### Viés retrospectivo

- A condição era identificável antes do evento ou parece óbvia apenas depois?

### Ancoragem

- A investigação ficou presa à primeira explicação sugerida?

### Disponibilidade

- Um caso recente ou conhecido está influenciando excessivamente a análise?

### Atribuição individual

- Condições do sistema foram investigadas antes de atribuir causa à pessoa?

### Viés de resultado

- A qualidade da decisão foi avaliada com base nas informações disponíveis no momento, e não apenas no resultado posterior?

---

## 36. Critérios mínimos de qualidade da investigação

Uma investigação é considerada adequadamente estruturada quando:

- o evento está descrito sem antecipação da causa;
- fatos, relatos, inferências e lacunas estão separados;
- evidências relevantes foram preservadas e avaliadas;
- mais de uma hipótese plausível foi considerada, quando aplicável;
- evidências contrárias foram pesquisadas;
- o mecanismo causal foi descrito;
- não conformidades sem vínculo foram separadas das causas;
- hipóteses foram classificadas com justificativa;
- os porquês avançaram além da ação individual;
- limitações e incertezas foram declaradas;
- a conclusão é rastreável às evidências.

---

## 37. Limites do agente de IA

O agente deve:

- apoiar organização, busca, comparação e formulação de perguntas;
- indicar evidências necessárias e lacunas;
- apresentar hipóteses como hipóteses até que sejam testadas;
- citar os códigos e categorias utilizados;
- declarar incertezas e limitações;
- solicitar validação humana para decisões técnicas e formais.

O agente não deve:

- inventar evidências;
- substituir julgamento técnico autorizado;
- concluir diagnóstico médico ou psicológico;
- atribuir culpa ou intenção;
- executar testes perigosos;
- aprovar formalmente causa-raiz ou ação corretiva;
- ocultar evidências contrárias.

---

## 38. Controle e integridade da metodologia

**Documento de origem:** Lista Compreensiva de Causas — FOG 222, revisão 00, de 24/10/2023.

**Uso:** orientação complementar para operacionalização da LCC por agentes de IA e investigadores humanos.

**Regra de alteração:** mudanças nesta metodologia devem preservar os códigos e significados originais da LCC e ser submetidas à revisão e aprovação definidas pela organização.
