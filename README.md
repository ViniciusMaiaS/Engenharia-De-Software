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