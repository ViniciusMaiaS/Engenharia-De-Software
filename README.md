# Engenharia-De-Software## 2. Justificativa da Escolha

### Tamanho e Complexidade

O aplicativo de delivery de comida caseira possui porte entre pequeno e médio, pois envolve o gerenciamento de clientes, estabelecimentos (Fornecedores de Comida), entregadores, pedidos, pagamentos e entregas. Essas funcionalidades precisam funcionar juntas, o que caba tornando o sistema um pouco complexo.

### Escopo Inicial e Equipe

Inicialmente o sitema atenderá até 300 usuários de uma determinada região, entre o que chamamos de cliente, estabelecimentos e entregadores. para ser desenvolvido e também mantido o sistema precisará de uma equipe de 3 pessoas formada por 1 Analista, 1 Desenvolvedor full stack e 1 Testador. 

### Problemas de Desenvolvimento Artesanal

Sem planejamento e processos definidos, o sistema poderia apresentar falhas em pedidos, inconsistências nos pagamentos, dificuldade de manutenção e atraso na entrega de novas implementações.

### Por que Programar Bem Não Seria Suficiente?

Programação mesmoq ue estrtuturada , sozinha e ela não garantiria o sistema. Também são necessários "requisitos bem definidos", "documentação", "testes", "versionamento" e "planejamento", isso tudo garantirá as funcioanlidades e ao aumentar o escopo aevolução.

### 3. **Aplicação dos Quatro Princípios**

O aplicativo pode ser dividido em módulos com responsabilidades separadas, facilitando o desenvolvimento e manutenção. Os principais módulos seriam:

- **Autenticação:** cadastro e login dos usuários.
- **Clientes:** perfil, endereço e histórico de pedidos.
- **Estabelecimentos:** cadastro dos fornecedores e gerenciamento do cardápio.
- **Pedidos:** criação, confirmação e acompanhamento.
- **Pagamentos:** registro e processamento.
- **Entregas:** controle dos entregadores e status das entregas.
- **Administração:** gerenciamento geral dos usuários, fornecedores e pedidos.

Essa divisão permite que cada módulo seja desenvolvido e alterado de forma organizada e independente, facilitando futuras melhorias no aplicativo.

Os atributos de qualidade mais críticos para o aplicativo são:
- **Funcionalidade:** garantir que o cliente consiga visualizar os cardápios de comidas caseiras disponíveis, realizar pedidos, efetuar pagamentos e acompanhar a entrega.
- **Confiabilidade:** evitar erros como pedidos duplicados, perda de informações, pagamentos incorretos, pedidos enviados incorretamente ao fornecedor, e outras inconsistências lógicas.
- **Usabilidade:** oferecer uma interface simples e fácil de usar para os clientes, cozinheiros, fornecedores e entregadores.
- **Eficiência:** garantir que cardápios, pedidos e informações sobre as entregas sejam atualizados em tempo real e preciso.
- **Manutenibilidade:** facilitar correções e futuras melhorias, como a adição de novos fornecedores, pratos e formas de pagamento.
- **Portabilidade:** permitir que o sistema possa ser utilizado em diferentes dispositivos.

Dessa forma, a divisão do sistema em módulos e a preocupação com a qualidade do software tornam o desenvolvimento mais organizado e seguro. Para um aplicativo de delivery de comida caseira, esses princípios são importantes para garantir o correto funcionamento dos pedidos, pagamentos e entregas, além de facilitar futuras melhorias e o crescimento do sistema.

Manutenibilidade e evolução:

O tipo de manutenção mais provável de acontecer com este sistema nos primeiros anos é a manutenção evolutiva. Como o aplicativo de delivery de comida caseira tem um escopo inicial planejado para até 300 usuários, à medida que a plataforma se estabilizar e o número de fornecedores e clientes crescer, o sistema precisará se adaptar para oferecer novas facilidades e acompanhar as demandas do mercado. Exemplo concreto: Adicionar um sistema de avaliação dos pedidos, aceitar novas formas de pagamento (como PIX e vale-refeição), incluir um mapa com GPS para os entregadores, adicionar uma opção de pedido aos favoritos e etc.

Boas práticas gerais: Para organizar o trabalho da equipe, aplicaremos as três práticas da seguinte forma:

- **Documentar decisões:** Registrar como funcionam as regras principais (ex: como é calculada a taxa de entrega) e as escolhas de tecnologia (ex: qual banco de dados usar).
- **Versionamento com Git:** Usar o GitHub para salvar o código com segurança. Cada pessoa fará o trabalho em uma branch, e usara mensagens claras do que foi feito.
- **Padronização de nomes e formatação:** Adotar regras fáceis para o código, como usar a primeira letra minúscula para variáveis, Usaremos ferramentas automáticas para que o visual do código fique sempre padronizado independentemente de quem escreveu.