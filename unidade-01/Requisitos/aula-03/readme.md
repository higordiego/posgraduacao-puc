# Aula - 03

## Descrição.

Uma das classificações de requisitos os divide em funcionais e não funcionais. Requisitos funcionais incluem ações realizadas pelo sistema que envolvem a interação com os diferentes usuários. Requisitos não funcionais incluem restrições que podem estar relacionadas a funcionalidades específicas ou ao sistema como um todo.

## Resumo.

Diveras classificações de requisitos de quanto a seu tipo existem:
  - Requisitos funcionais e requisitos não funcionais requisitos.
  - Requisitos de cliente e requisitos de sistema.


Requisitos funcionais.

  - Esspecificam ações que um sistema deve executar, sem levar consideração restrições físicas.
    Exemplos:
      - O sistema deve permitir ao Administrador gerenciar o cadastro de usuários.
      - O sistema deve permitir ao Gerente visualizar todos os empréstimos efetuados no mês, indicando o funcionário que disponibilizou o rempréstimo, o cliente que obteve o empréstimo e o valor emprestado.
  
**Requisitos funcionais por sua vez são deterministicos com ações de usuários e desejo literal do mesmo.**

Requisito não funcionais.

  - Descrevem restrições desejadas ou necessárias, atributos do sistema ou de seu ambiente.
  - Condições que o sistema deve atender.
  - Qualidades específicas que o sistema deve ter.
  - Especificidades que o ambiente deve cumprir.
  - São também chamados de restrições ou requisitos de qualidade.
  - Determinam a arquitetura do sistema.

**Requisitos não funcionais são requisitos que o sistema deve atender comportamentos de sistema como por exemplo escalabilidade ou desempenho. .**

Os requisitos não funcionais diversos tipos:
  1. Requisito não funcional global.

    - No requisito global quando ação especifica ou modulo causa impacto no sistema como todo.

  2. Requisito não funcional local.

    - No requisito local quando ação especifica ou modulo causa impacto em um pequeno escopo ou como o próprio nome diz local.

  3. Usabilidade

    - Estética, consistência da interface do usuário, ajuda on-line sensível ao contexto, wizards, documentação de usuário e material de treinamento.

  4. Confiabilidade

    - Frequência e severidade das falhas, possibilidade de recuperação, tempo médio entre falhas, previsibilidade, acurácia.

  5. Desempenho

    - Impõe condições ao requisitos funcionais: velocidade, eficiência, throughput, tempo de resposta, tempo de recuperação, faixa de recurso utilizados.

  6. Suporte

    - testabilidade, extensibilidade, adaptabilidade, manutenibilidade, compatibilidade, configurabilidade, instabilidade, internacionalização.
  
  7. Desenho

    - Define restrições ao desenho do sistema, como uso de padrões de desenho.

  8. Implementação

    - que define restrições á implementação do sistema, como linguagens de desenvolvimento, padrões de codificação, políticas de uso do banco de dados, limites de recursos e ambiente de desenvolvimento.

  9. Interface

    - Que especifica itens externos com os quais o sistema precisa interagir e restrições em formatos, sincronismo, protocolos ou outros fatores utilizados nessa interação.


Exemplos de requisitos não funcionais:

  1. O fechamento contábil do mês deverá ser realizado em no máximo 4 horas para um volume de até 40 milhões de registros.
  2. A base de dados do sistema deverá ser armazenada em Mysql.
  3. O sistema deverá suportar dois idiomas: português e espanhol.
  4. O sistema deve ser capaz de se recuperar de uma falha em até 1 hora.


Requisitos de clientes e requisitos de sistema.
  1. O detalhamento dos requisitos evoluir durante um projeto.
    - Origem no cliente e nos usuários.
    - Termina detalhado o suficiente para prosseguir o desenvolvimento do sistema.

Exemplo.

  1. Necessidade do cliente.

    - Construir um sistema para predição do movimento do mercado de ações da BOVESPA com taxa de acerto de 70%.

  2. Funcionalidades a serem cumpridas pelo o sistema.

    - Analisar séries históricas.
    - Treinar o sistema com dados históricos.
    - Gerar modelos matemáticos para conjunto de ações.
    - Compilar portfólios de ações.


Requisitos do Cliente.

  - Espressam os resultados desejados para superar os problemas reais.
  - Descrevem o problema enfrentado pelo o cliente ou usuário, materializado a partir de suas necessidades, espectativas, restrições e interface apontadas.
  - Descrevem as características desejáveis de uma solução.
  - Deslimitam o universo de soluções possíveis (domínio), ao invés de uma solução específica.
  - Também chamadas de requisitos de usuário.