# RCA Knowledge Base — Lista Compreensiva de Causas (LCC)

## 1. Finalidade

Esta base de conhecimento apoia agentes de inteligência artificial e investigadores humanos na análise de causa-raiz, com duas finalidades:

1. **Pesquisar causas contribuintes plausíveis**, a partir do evento, dos fatores causais e das evidências disponíveis.
2. **Testar hipóteses de causa**, buscando evidências que sustentem ou contradigam cada hipótese antes da conclusão.

A base utiliza como taxonomia principal a **Lista Compreensiva de Causas (LCC)**.

## 2. Regra de uso pelo agente

O agente deve seguir esta sequência:

1. Compreender e descrever o evento com base em informações verificáveis.
2. Identificar os fatores causais potencialmente relacionados ao evento.
3. Consultar o arquivo `INDEX.md` para localizar as categorias aplicáveis da LCC.
4. Pesquisar causas contribuintes sem presumir antecipadamente uma causa-raiz.
5. Formular hipóteses de causa de maneira objetiva e testável.
6. Para cada hipótese, buscar evidências favoráveis e desfavoráveis.
7. Classificar a hipótese como **confirmada**, **refutada** ou **inconclusiva**, conforme os critérios da base.
8. Quando uma causa for confirmada, continuar a investigação com pelo menos mais dois “porquês”, quando aplicável, para buscar condições antecedentes e causas sistêmicas.
9. Registrar a trilha de raciocínio, as fontes consultadas e as evidências utilizadas.

## 3. Princípios obrigatórios

- Não concluir uma causa apenas com base em opinião, percepção ou ausência de explicação alternativa.
- Não confundir correlação com relação causal.
- Não confundir ausência de registro com prova automática de que a atividade não ocorreu.
- Não selecionar “erro humano” como conclusão final sem investigar condições de trabalho, procedimentos, capacitação, planejamento, supervisão, comunicação e controles organizacionais relacionados.
- Considerar e registrar evidências que contradigam a hipótese.
- Verificar se a causa proposta tem vínculo lógico e demonstrável com o evento.
- Preferir evidências objetivas, rastreáveis e contemporâneas ao evento.
- Não alterar o significado dos códigos e descrições originais da LCC.
- Diferenciar conteúdo original da LCC de orientações complementares de investigação incluídas nesta base.

## 4. Tipos de evidência

O agente pode recomendar, conforme a hipótese investigada:

- documentos e procedimentos;
- registros operacionais e de controle;
- fotografias, vídeos e dados de sistemas;
- inspeções e observações de campo;
- entrevistas e relatos, devidamente confrontados com outras evidências;
- históricos de manutenção, calibração, treinamento, auditoria e mudança;
- especificações, requisitos, contratos e registros de fornecedores;
- indicadores, tendências e ocorrências anteriores semelhantes.

A relevância, autenticidade, integridade, temporalidade e rastreabilidade da evidência devem ser avaliadas.

## 5. Estados possíveis de uma hipótese

### Confirmada

Existem evidências suficientes de que a condição ocorreu, estava presente no momento relevante e contribuiu de forma demonstrável para o evento.

### Refutada

Existem evidências suficientes de que a condição não ocorreu, não estava presente no momento relevante ou não possui vínculo causal demonstrável com o evento.

### Inconclusiva

As evidências são insuficientes, conflitantes, indisponíveis ou não permitem estabelecer ou afastar o vínculo causal. O agente deve indicar quais informações adicionais são necessárias.

## 6. Estrutura da base

- `README.md`: finalidade, limites e regras gerais de uso.
- `INDEX.md`: índice central para acesso às categorias da LCC.
- `01-METODOLOGIA.md`: método detalhado de pesquisa e teste de causas.
- Arquivos `29` a `39`: categorias e hipóteses da LCC, com orientações de pesquisa e teste.

A navegação deve permanecer em, no máximo, dois níveis:

1. `INDEX.md`;
2. arquivo da categoria aplicável.

## 7. Limites de uso

Esta base é um instrumento de apoio à investigação. A base não substitui:

- competência técnica do time investigador;
- análise do contexto específico do evento;
- requisitos legais, normativos, contratuais ou corporativos aplicáveis;
- validação das evidências por pessoas autorizadas;
- aprovação formal da conclusão e das ações decorrentes.

O agente não deve fabricar fatos, registros, entrevistas, medições ou evidências ausentes. Quando faltarem dados, o agente deve declarar a lacuna e recomendar como tratá-la.

## 8. Resultado esperado

A aplicação desta base deve produzir uma análise rastreável contendo:

- descrição objetiva do evento;
- fatores causais considerados;
- causas contribuintes pesquisadas;
- hipóteses formuladas;
- evidências favoráveis e desfavoráveis;
- resultado de cada teste;
- causa ou causas confirmadas, quando demonstradas;
- continuidade dos “porquês”;
- lacunas e incertezas remanescentes.

---

**Documento-base:** Lista Compreensiva de Causas (LCC) — FOG 222, revisão 00, de 24/10/2023.

**Nota de integridade:** as descrições originais da LCC devem ser preservadas nos arquivos de categorias. As orientações de pesquisa, perguntas, testes e critérios são conteúdo complementar destinado a operacionalizar a consulta por agentes de IA e investigadores.
