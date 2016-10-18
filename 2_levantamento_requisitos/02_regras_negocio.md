## Regras de negócio

De acordo com a **Análise de Requisitos**, a **Regra de negócio** é o que define a forma de fazer o negócio, refletindo a política interna, o processo definido e/ou as regras básicas de conduta.  Ou seja, é um conjunto de instruções que os usuários já seguem e que o sistema a ser desenvolvido deve contemplar. Restrições, validações, condições e exceções do processo são exemplos clássicos de regras de negócio. Uma regra de negócio não necessariamente será refletida no sistema como uma funcionalidade, mas ela com certeza determinará o comportamento de uma ou mais funcionalidades do sistema.

As regras de negócio levantadas para o projeto são:

### Histórico de movimentação do estoque

A aplicação deve oferecer o histórico da movimentação a fins de análise. Para um bom planejamento de compra para o estoque, faz-se necessário ter acesso a dados passados.

### Prospecção de estado do estoque para gerenciamento proativo

A aplicação deve ser capaz de oferecer uma prospecção de como está o estoque e de como o estoque estará no futuro, fornecendo informações sobre níveis seguros para cada item do estoque.

### Atualização instantânea das quantidades do estoque

A aplicação deve atualizar suas informações assim que uma movimentação é efetuada, mantendo usuários informados em tempo real.

### Geração automática de lista de pedidos

Com base no conhecimento do estado de estoque, o aplicação deve gerar listas de pedidos automáticas, enviando-as para o gerente do estoque aprová-las e encaminhá-las para compra.

### Relatórios e métricas para avaliação de estoque

A aplicação deve fornecer relatórios e métricas com base no histórico e na prospeção de estado do estoque, possibilitando tomadas de decisões mais eficientes.

### Comunicação das ações e níveis de estoque aos usuários do sistema

Os usuários devem receber informações assim que ações ocorrem, mantendo todos os interessados informados.

### Gerenciamento de fornecedores

A aplicação deve fornecer funcionalidade para gerenciamento de fornecedores, com cadastro de seus contatos, localizações e pedidos já efetuados.

### Alimento relacionado a um fornecedor

Um alimento não pode ser cadastrado no sistema sem que o seu fornecedor também seja, evitando dados avulsos e informações sem relevância.

### Validade de alimentos

A aplicação deve fornecer informações antecipadas relacionadas as datas de validade dos itens do estoque.

### Gerenciamento de receitas

A aplicação deve fornecer funcionalidade para gerenciamento de receitas. A partir das receitas, os ingredientes podem ser deduzidos do estoque.
