# 03 — Modelos de Entregáveis da Análise

## 1. Finalidade

Este documento orienta a transformação de uma análise validada em três entregáveis consistentes:

1. **Relatório Técnico Completo**, para registro formal e rastreabilidade;
2. **DDS de Qualidade, HSE ou QHSE**, para comunicação e aprendizado das equipes;
3. **Apresentação Executiva em PowerPoint**, para a alta direção, com exatamente cinco slides.

> Nenhum entregável pode transformar hipótese preliminar ou inconclusiva em causa confirmada, omitir evidência contrária relevante ou inventar fatos, responsáveis, prazos, resultados ou aprovações.

---

## 2. Aplicação

Utilizar este documento somente após a validação das fases aplicáveis:

- descrição do evento;
- efeitos e consequências;
- contenção e mitigação;
- coleta e organização de evidências;
- triagem dos fatores causais;
- formulação e teste de hipóteses;
- aprofundamento pelos Porquês;
- identificação de causas imediatas, contribuintes e sistêmicas;
- elaboração e validação do plano de ação.

A geração dos entregáveis não substitui as revisões e aprovações formais da organização.

---

# 3. Regras comuns

## 3.1 Fonte única da informação

Os três entregáveis devem utilizar a mesma consolidação validada. Devem permanecer consistentes:

- código, título e identificação do evento;
- data, local, processo ou sistema;
- condição esperada, condição encontrada e desvio;
- extensão, efeitos e consequências;
- contenções executadas;
- evidências relevantes;
- hipóteses confirmadas, refutadas e inconclusivas;
- causas imediatas, contribuintes e sistêmicas;
- barreiras que falharam;
- ações, responsáveis, prazos e critérios de eficácia;
- lacunas, limitações e riscos remanescentes.

## 3.2 Uso interno da LCC

Os códigos e categorias da LCC são referências internas para pesquisa, triagem e teste. Não devem aparecer no Relatório Técnico, DDS ou PowerPoint, salvo solicitação expressa do usuário por uma versão técnica com rastreabilidade LCC.

Nos entregáveis comuns, utilizar descrições claras das hipóteses, causas e barreiras.

## 3.3 Identificadores estáveis

A rastreabilidade visível deve usar:

```text
E  = efeitos
C  = contenções
EV = evidências
H  = hipóteses
T  = trilhas dos Porquês
CA = causas confirmadas
AC = ações
EF = verificações de eficácia
```

Cadeia principal:

```text
E -> C -> EV -> H -> T -> CA -> AC -> EF
```

Os IDs não devem ser renumerados, reutilizados ou eliminados do histórico.

## 3.4 Estados das hipóteses

### Confirmada

A condição existia no período relevante, influenciou uma ação, decisão, processo ou barreira e possui vínculo causal demonstrável.

### Refutada

A condição não existia, estava controlada, não influenciou o evento ou é incompatível com as evidências.

### Inconclusiva

As evidências são insuficientes, conflitantes ou não permitem demonstrar ou afastar o vínculo causal.

## 3.5 Uso das hipóteses

- Hipótese confirmada pode fundamentar causa e ação definitiva.
- Hipótese refutada permanece no Relatório Técnico, mas não recebe ação corretiva.
- Hipótese inconclusiva deve indicar evidências faltantes e pode gerar investigação, monitoramento ou controle provisório.
- DDS e PowerPoint só mencionam hipóteses inconclusivas quando forem relevantes a riscos ou decisões pendentes.

## 3.6 Situação da análise

### Análise preliminar

```text
ANÁLISE PRELIMINAR
Hipóteses não testadas ou inconclusivas não devem ser tratadas como causas confirmadas. O conteúdo está sujeito à complementação de evidências e validação formal.
```

### Análise concluída

```text
ANÁLISE CONCLUÍDA
As conclusões são baseadas nas evidências disponíveis e permanecem sujeitas às aprovações formais da organização.
```

## 3.7 Privacidade e linguagem

Os entregáveis devem:

- priorizar funções, equipes e áreas em vez de nomes pessoais;
- omitir diagnóstico, medicamento, condição clínica, informação psicológica e problema pessoal;
- proteger informações de clientes, fornecedores e parceiros;
- evitar julgamento de caráter, culpa ou intenção;
- utilizar linguagem factual e proporcional às evidências;
- não divulgar conteúdo restrito a pessoas não autorizadas.

Para itens da categoria 39 marcados com `*`, utilizar somente:

```text
Desempenho de Pessoal — Aspectos Pessoais
```

## 3.8 Controle de versão

```text
Código do caso:
Título:
Versão:
Data de emissão:
Situação: Preliminar / Concluída
Elaborado por:
Revisado por:
Aprovado por:
Classificação da informação:
```

---

# 4. Entregável 1 — Relatório Técnico Completo

## 4.1 Finalidade

Registrar o processo de análise de forma completa, rastreável e tecnicamente defensável, incluindo evidências favoráveis e contrárias.

## 4.2 Formato

Gerar preferencialmente em Microsoft Word, com capa, sumário, títulos numerados, tabelas legíveis, controle de versão e paginação.

## 4.3 Estrutura obrigatória

### Capa

- código e título do caso;
- unidade, processo ou local;
- data do evento e do relatório;
- versão e situação;
- classificação da informação.

### 1. Resumo executivo

- o que ocorreu;
- extensão e impacto;
- resposta imediata;
- principais evidências;
- causas confirmadas;
- riscos e lacunas;
- principais ações e decisões.

### 2. Identificação e escopo

```text
Código do caso:
Título:
Data e horário:
Local, unidade ou processo:
Serviço, produto ou sistema:
Responsável pela análise:
Equipe participante:
Escopo incluído:
Escopo excluído:
Requisitos aplicáveis:
```

### 3. Descrição objetiva

Incluir condição esperada, condição encontrada, desvio, detecção, extensão, efeitos e lacunas. Não incluir causas nesta seção.

### 4. Efeitos, consequências e abrangência

```text
ID | Efeito | Consequência | Dimensão | Situação | Impacto | Abrangência conhecida | Abrangência a verificar
```

### 5. Contenção e mitigação

```text
ID | Efeito relacionado | Ação executada | Responsável | Prazo | Situação | Resultado | Verificação | Risco introduzido
```

Declarar que contenção não equivale necessariamente a ação corretiva.

### 6. Evidências e fontes

Separar evidências diretas, indiretas, relatos não confirmados, indisponibilidades, contradições e limitações.

```text
ID | Evidência | Tipo | Fonte | Data | Integridade/rastreabilidade | Hipótese apoiada ou contradita | Limitação
```

### 7. Cronologia

```text
Data/hora | Fato ou ação | Evidência | Classificação | Observação
```

### 8. Fatores causais e barreiras

```text
ID | Fator causal | Evidência associada | Posição na cronologia | Barreira esperada | Situação da barreira | Limitação
```

### 9. Registro Mestre de Hipóteses

```text
ID | Hipótese | Evidência favorável | Evidência contrária | Lacuna | Prioridade | Situação
```

### 10. Hipóteses e testes

Para cada hipótese, informar formulação testável, motivo, evidências favoráveis e contrárias, método, critérios de confirmação e refutação, limitações, resultado e justificativa.

### 11. Trilhas dos Porquês

```text
ID | Nível | Pergunta | Hipótese | Evidências favoráveis | Evidências contrárias | Resultado | Vínculo anterior
```

Não exigir exatamente cinco níveis.

### 12. Conclusão causal

Separar:

- causas imediatas;
- causas contribuintes;
- causas sistêmicas;
- condições sem influência;
- hipóteses inconclusivas;
- hipóteses refutadas relevantes.

### 13. Plano de ação

Criar ação definitiva somente para causa confirmada.

```text
ID | Causa relacionada | Causa tratada | Ação | Barreira fortalecida | Entregável | Indicador | Meta | Recursos | Prazo | Responsável | Abrangência | Gestão de mudança | Risco | Mitigação
```

### 14. Verificação de eficácia

```text
ID | Ação relacionada | Indicador | Linha de base | Meta | Método | Amostra/período | Data | Responsável | Critério de sucesso | Resposta se ineficaz
```

### 15. Matriz de rastreabilidade

```text
Efeito | Contenção | Evidência | Hipótese | Trilha | Causa confirmada | Ação | Verificação de eficácia
```

### 16. Lacunas, limitações e riscos remanescentes

Registrar informações não obtidas, hipóteses inconclusivas, riscos abertos, restrições, decisões pendentes e necessidade de análise adicional.

### 17. Aprovações

```text
Elaborador:
Revisor técnico:
Responsável pelo processo:
QHSE:
Aprovador:
Datas:
Ressalvas:
```

---

# 5. Entregável 2 — DDS de Qualidade, HSE ou QHSE

## 5.1 Finalidade

Comunicar o aprendizado às equipes em linguagem simples, objetiva e não punitiva, preservando confidencialidade.

## 5.2 Modalidades

- **DDS de Qualidade:** produto, serviço, processo, resultado, cliente, documentação ou conformidade técnica;
- **DDS de HSE:** saúde, segurança ou meio ambiente;
- **DDS de QHSE:** evento integrado ou aprendizado aplicável a Qualidade, Saúde, Segurança e Meio Ambiente.

> QHSE significa Qualidade, Saúde, Segurança e Meio Ambiente. Quando mais de uma dimensão estiver envolvida, preferir DDS de QHSE.

## 5.3 Seleção

Antes de gerar, apresentar e validar:

```text
Modalidade escolhida:
Justificativa:
Público recomendado:
Duração sugerida:
```

## 5.4 Estrutura

O DDS deve ter aproximadamente uma página e duração de 5 a 10 minutos.

### Título

Curto, objetivo e sem exposição indevida.

### O que aconteceu?

Descrição factual, sem nomes e sem hipóteses não confirmadas.

### Por que isso importa?

Impacto observado, risco potencial e relevância para a rotina.

### O que aprendemos?

De três a cinco aprendizados baseados em causas confirmadas e barreiras avaliadas.

### Sinais de atenção

Condições ou mudanças que exigem atenção, comunicação, escalonamento ou interrupção conforme procedimentos aplicáveis.

### Controles e comportamentos esperados

Não criar requisito novo nem substituir procedimento vigente.

### Perguntas para discussão

1. Esta situação poderia ocorrer em nossa atividade?
2. Qual barreira utilizamos e como sabemos que funciona?
3. O que deve ser comunicado e para quem?

### Mensagem-chave

Uma frase curta e memorável.

### Registro

```text
Data:
Local/equipe:
Facilitador:
Participantes:
Dúvidas ou sugestões:
Ações locais identificadas:
```

## 5.5 Restrições

O DDS não deve incluir nomes, diagnósticos, dados pessoais, informações protegidas de clientes, alegações disciplinares, códigos LCC, hipóteses refutadas ou hipótese inconclusiva apresentada como causa.

---

# 6. Entregável 3 — Apresentação Executiva em PowerPoint

## 6.1 Finalidade

Apresentar à alta direção uma síntese objetiva do evento, resposta, análise, causas, riscos, plano e decisões requeridas.

## 6.2 Regras visuais e editoriais

A apresentação deve:

- ser integralmente em português, inclusive títulos, tabelas, indicadores e notas;
- conter exatamente cinco slides;
- não utilizar fotografias, imagens geradas por IA, ilustrações, cliparts ou elementos figurativos;
- utilizar linguagem executiva e design corporativo minimalista;
- limitar cada slide a uma mensagem principal e, no máximo, cinco pontos;
- apresentar somente causas confirmadas como causas;
- mostrar hipóteses inconclusivas como questões abertas;
- não exibir códigos ou categorias LCC, salvo solicitação expressa;
- manter consistência com o Relatório Técnico.

## 6.3 Paleta

```text
Amarelo principal — Supernova/Cerello: #FFC700
Preto profundo/carvão: #000000 e cinzas muito escuros
Branco e neutros claros: #FFFFFF
Creme de apoio — Raffia: #E7CDAF
```

Aplicar `#FFC700` em títulos, destaques, indicadores, linhas e chamadas. Usar preto ou carvão em cabeçalhos e áreas de alto contraste, branco e neutros claros nos fundos principais e `#E7CDAF` apenas como apoio.

Usar somente tipografia, números, caixas, linhas do tempo, tabelas, divisores e indicadores simples. Não criar elementos decorativos figurativos.

## 6.4 Estrutura obrigatória

### Slide 1 — Evento, contexto e impacto

- descrição em uma frase;
- esperado versus encontrado;
- data, local e processo;
- impactos reais e potenciais;
- situação atual.

### Slide 2 — Extensão e resposta imediata

- abrangência conhecida;
- partes potencialmente afetadas;
- contenções executadas;
- eficácia da mitigação;
- riscos abertos.

### Slide 3 — Evidências e análise causal

- principais evidências;
- cronologia resumida;
- fatores causais;
- hipóteses confirmadas, refutadas e inconclusivas;
- limitações relevantes.

### Slide 4 — Causas e barreiras

- causa imediata;
- causas contribuintes;
- causas sistêmicas;
- barreiras que falharam;
- trilha resumida dos Porquês.

### Slide 5 — Plano, eficácia e decisões

- principais ações;
- responsáveis e prazos;
- abrangência e gestão de mudança;
- critérios de eficácia;
- decisões ou apoios requeridos.

## 6.5 Notas do apresentador

Incluir explicação complementar, fonte dos dados, limitações, perguntas esperadas e decisões requeridas. Todas as notas devem estar em português.

---

# 7. Matriz mestra de consistência

```text
Elemento | Relatório Word | DDS | PowerPoint | Consistente? | Observação
Descrição do evento
Extensão e impactos
Contenções
Evidências principais
Causas confirmadas
Hipóteses inconclusivas relevantes
Barreiras
Ações
Responsáveis e prazos
Critérios de eficácia
Riscos remanescentes
```

Resolver divergências com base na consolidação validada da análise.

---

# 8. Verificação antes da emissão

## 8.1 Relatório

- Os IDs foram preservados?
- Os códigos LCC estão ocultos, salvo solicitação?
- Evidências favoráveis e contrárias estão registradas?
- Cada causa possui vínculo demonstrável?
- Cada ação está vinculada a causa confirmada ou controle provisório identificado?
- A eficácia possui indicador, meta e prazo?
- Lacunas e limitações estão declaradas?

## 8.2 DDS

- A modalidade foi validada?
- O conteúdo é compreensível e não punitivo?
- O aprendizado decorre de fatos e causas confirmadas?
- Não há nomes, dados sensíveis ou códigos LCC?
- Existem três perguntas para discussão e uma mensagem-chave?

## 8.3 PowerPoint

- Está integralmente em português?
- Possui exatamente cinco slides?
- Está sem imagens e utiliza a paleta definida?
- Cada slide tem uma mensagem principal e até cinco pontos?
- Causas e hipóteses estão diferenciadas?
- Decisões requeridas estão explícitas?

---

# 9. Geração dos arquivos

Após validar a consolidação, oferecer:

```text
1. Gerar o Relatório Técnico Completo em Word;
2. Gerar o DDS de Qualidade, HSE ou QHSE em Word;
3. Gerar a Apresentação Executiva em PowerPoint;
4. Gerar todos os entregáveis.
```

Antes da geração, solicitar somente dados obrigatórios ainda ausentes. Se a geração direta não estiver disponível, produzir conteúdo completo e estruturado para Word e PowerPoint.

## Nomenclatura

```text
RCA_[codigo]_[Titulo-Curto]_Relatorio-Tecnico.docx
RCA_[codigo]_[Titulo-Curto]_DDS-[Qualidade-HSE-QHSE].docx
RCA_[codigo]_[Titulo-Curto]_Executivo-5-Slides.pptx
```

Nos nomes dos arquivos, substituir o ponto do código por hífen.

---

# 10. Consolidação obrigatória

Antes de criar arquivos, consolidar e validar:

```text
Código e título:
Situação: Preliminar / Concluída
Descrição:
Impactos:
Contenções:
Evidências principais:
Cronologia:
Registro Mestre:
Hipóteses confirmadas:
Hipóteses refutadas:
Hipóteses inconclusivas:
Causas imediatas:
Causas contribuintes:
Causas sistêmicas:
Barreiras que falharam:
Ações aprovadas:
Responsáveis e prazos:
Critérios de eficácia:
Riscos remanescentes:
Classificação da informação:
Aprovações necessárias:
```

---

# 11. Controle e integridade

**Documento de origem:** Base de Conhecimento da Lista Compreensiva de Causas — LCC.

**Uso:** orientação complementar para geração de entregáveis após análise estruturada e validada.

**Regra de alteração:** preservar rastreabilidade entre evento, evidência, hipótese, causa, ação e eficácia, além das regras de privacidade e aprovação.
