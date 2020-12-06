
# Aula - 01

## Descrição.

## Resumo.
Arquitetura orientada a serviço - SOA
  - paradigma de desenvolvimento.
  - Objetivo é criar módulos funcionais 
    - serviços com baixa acoplamentos.
  
Componentes
  - A ideia que é os serviços seja fracamente acoplados.
  - Podem continuar a funcionar mesmo com alterações na comunicação como:
    - Adição de novos parâmetros.
    - omissão de parâmetros.
    - mudança de ordem de parâmetros.

Granularidade
  - Ajuda a medir a complexidade de um modelo de componentes.
  - Grunlaridade fina:
    - Desce em nível de classes.
    - Muito detalhado.
  - Granularidade grossa:
    - Oculta o modelo de classe básico
    - Componentes executam mais de uma função.

Serviços
  - Executa unidade completa do trabalho:
    - Podem ser "statless"

Principios Serviços
  - Autonomia: Possuem controle sob a lógica que encapsulam.
  - Abstração: Escondem lógica do mundo externo.
  - Reusabilidade: Lógica dividida em serviços para promover reuso.
  - Ausente de estado: Serviço minimizam armazenamento sobre informações específicas de suas atividades.
  