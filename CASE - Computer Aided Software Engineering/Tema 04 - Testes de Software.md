# Definição
Refere-se a toda e qualquer atividade desempenhada para avaliar a qualidade do software identificando defeitos ou problemas.  
**Um teste de software consiste na verificação dinâmica do comportamento de um programa em um conjunto finito de casos de teste.**

# Bloco 1
## Etapas
- Planejamento: Elaboração de estratégia e plano de teste, baseando-se em requisitos
- Preparação: definição de recursos necessários para o ambiente de teste.
- Especificação: Elaboração / revisão de casos e roteiros de teste.
- Execução: Aplicação prática e registro dos resultados
- Entrega: documental, conclusão do processo de teste.

## Artefatos
- Casos
  - Situações que exercitem adequadamente todas as funcionalidades e requisitos
  - Elaborados para identificar defeitos na execução do software.
  
- Roteiro
  - Maneira estruturada de realizar testes manuais em softwares, definindo parâmetros e ações a serem realizadas

- Script
  - Aplicação do script
  - combina casos com procedimentos e dados gerados

- Plano de teste
  - Documento Resultante
  - Documento que contém uma abordagem sistemática para teste de software
  - Consiste em uma modelagem detalhada do fluxo de trabalho durante o processo.
  -  É como se fosse um mapa do ambiente de testes.  

## Verificação x Validação

Verificação: ações que determinam se o que foi desenvolvido está de acordo com as especificações 
Validação: Aceite

# Bloco 2
## Tipos de Teste
### Teste Alfa e Beta
#### Alfa
Realizado logo após o término do software e anterior à implantação  
Pelos desenvolvedores

#### Beta ("versão beta")
Depois do teste alfa, por um grupo de usuários. Feedback do sistema. Sem a participação do usuário.

### Testes de Requisitos 
Um dos mais importantes na Engenharia de  Requisitos
Validações nos aspectos de:
- Consistência
- Precisão
- Contextualização
- Cumprimento
- Análise 

### Teste de Caixa Preta
- Avaliação do comportamento externo de um componente, sem considerar o ambiente interno.
- Os dados de entrada são fornecidos, o teste é executado e o **resultado** obtido **é comparado a um outro previamente conhecido.**
- Não tem conexão com demais itens do backend (ex: banco)
- O ideal é que todas as entradas possíveis sejam testadas.

### Teste de caixa branca
- Técnica de teste que utiliza a perspectiva interna de um sistema para modelar os casos de teste.
- No teste de software, a perspectiva interna é constituída pelo código fonte e demais itens do backend.
- No teste de hardware, cada ponto da arquitetura de infraestrutura deve ser testado.