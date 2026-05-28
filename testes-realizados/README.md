# Testes Realizados

## Descrição

Esta pasta contém testes realizados durante o desenvolvimento e validação das camadas do projeto. 

Os testes têm caráter exploratório, não científico ou estatístico. Servem para registrar usos práticos, comparar comportamentos entre modelos e identificar limitações recorrentes.

---

## Objetivos

Observar aderência às instruções, qualidade das fontes, consistência das respostas e limitações práticas de execução.

## Modelos testados

No processo, foram utilizados os seguintes modelos:

- Gemini
- Claude
- DeepSeek
- ChatGPT

Se encontram em arquivos **.txt** dentro de um arquivo **.rar** separados em páginas de acordo com a respectiva camada para melhor organização.

## Metodologia

Os testes foram conduzidos da seguinte maneira:

### Gemini:

- Sempre em aba anônima dada a praticidade. Isso possibilita o resultado de um modelo sem treinamento do usuário, se valendo apenas da capacidade disponibilizada pelo mesmo.

### Claude:

- Criada uma conta gratuita única e exclusivamente para testes;
- O modelo não passou por treinamento prévio de usuário, recebendo apenas prompts prontos;
- É de se esperar que, com o tempo, na conta utilizada, o modelo se adapte de alguma maneira;

### DeepSeek:

- Criada uma conta gratuita única e exclusivamente para testes;
- O modelo não passou por treinamento prévio de usuário, recebendo apenas prompts prontos;
- É de se esperar que, com o tempo, na conta utilizada, o modelo se adapte de alguma maneira;
- Para este modelo, foram utilizadas as funcionalidades **Rápido** e **Especialista**;

### ChatGPT:

- Para este, utilizei minha conta pessoal, a qual o modelo já é treinado se acordo com meu uso;
- Testes realizados dentro do plano **Plus**.
- Modelo utilizado foi e sempre será o mais recente. Os primeiros testes foram ainda dentro do **5.5 Instant**;

## Critérios Observados

- Aderência ao prompt;
- Uso de fontes;
- Tendência a extrapolar informações;
- Clareza da resposta;
- Respeito às limitações definidas.

## Considerações finais:

- Os testes não têm caráter científico ou estatístico. Servem como registro exploratório de uso, comparação prática e identificação de limitações recorrentes. As condições de teste intencionalmente variaram entre modelos, contas, planos e recursos disponíveis com o intuito de simular um cenário real, onde o recurso utilizado por cada pessoa pode variar.
- Apenas nomes de figuras públicas ocupando cargos em órgãos públicos foram utilizadas.
- Não houveram motivos particulares ou especiais para a escolha das figuras utilizadas nos testes, as escolhas foram baseadas no que julguei ser de melhor assimilação para o público em geral dada a ideia do projeto.
Por exemplo: a maioria do eleitorado brasileiro não saberia quem é o prefeito da minha cidade, mas provavelmente sabe quem é o presidente do país hoje;
- Embora possam haver exclusões de certas figuras nos testes pelo motivo citado acima, isto não limita a ideia, tampouco o prompt; Em um teste particular, foi possível obter informações acerca do prefeito atual da cidade a qual resido da mesma forma que informações sobre nosso atual presidente.

---
## Estrutura

- `camada-0/`: versões de prompts e resultados de testes relacionados à camada 0.
- `arquivos-originais/`: resultados brutos compactados preservados como referência.