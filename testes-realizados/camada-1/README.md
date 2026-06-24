# Versões Anteriores — Camada 1

Esta pasta reúne versões anteriores do prompt operacional da camada 1.

O objetivo é preservar:
- histórico evolutivo;
- refinamentos metodológicos;
- alterações estruturais;
- mudanças de abordagem ao longo do desenvolvimento do projeto;
- testes de validação entre diferentes modelos;
- ajustes de controle de fontes, contexto e atribuição de responsabilidade.

## Evolução das versões

v1  
- estrutura inicial da camada 1;
- foco geral na explicação da função real do cargo;
- separação básica entre poderes, limites e dependências do cargo.

v1.2  
- reorganização estrutural do prompt;
- reforço da distinção entre cargo, pessoa e período;
- inclusão de validação do vínculo pessoa-cargo;
- maior preocupação com fontes compatíveis com o cargo analisado.

v1.2.1  
- refinamento das regras de fonte;
- testes com cargos de diferentes Poderes e estruturas;
- identificação de problemas no uso de fontes indiretas como complemento;
- início do ajuste contra atribuições não confirmadas.

v1.2.2  
- reforço da validação de titularidade, interinidade, substituição e exercício provisório;
- separação mais clara entre ocupar cargo titular e exercer função de forma interina;
- exigência de fonte oficial ou institucional para confirmar vínculo pessoa-cargo-período;
- maior controle contra uso indevido de fontes indiretas.

v1.2.3  
- consolidação metodológica da camada;
- remoção de fontes indiretas como base da resposta;
- priorização de fontes oficiais e institucionais diretamente ligadas ao cargo, órgão, Poder ou esfera analisada;
- reforço contra analogia, simetria ou comparação como base para afirmar competência formal;
- versão com melhor desempenho nos testes antes da inclusão do campo de contexto.

v2  
- versão final consolidada da camada 1;
- inclusão do campo “Contexto” como apoio opcional ao usuário;
- tratamento geral para cargos dependentes de órgão, esfera, localidade, gabinete, entidade, mandato ou período;
- manutenção da estrutura de validação pessoa-cargo-período;
- preservação do controle de fontes oficiais e institucionais;
- redução de redundâncias sem remover os critérios centrais da camada;
- fechamento da camada como versão publicável e defensável.


---
A versão oficial vigente encontra-se em:
- [Prompt da Camada 1](/camada-1/prompt-camada-1.md)

---
## Navegação
- [Testes realizados](../README.md)
- [Voltar ao Projeto](/README.md)