## Cliente

O projeto surge da necessidade da Cozinha pedagógica do Centro de Gastronomia da Universidade de Joinville e Região. A Cozinha do Centro de Gastronomia é responsável pela realização de compras de alimentos, controle de estoque, análise e preparo de ingredientes para as receitas requisitadas.

### Situação atual

No dia 27 de outubro de 2015 foi realizada uma entrevista presencial com a Sr.ª Elisabete Vieira, doravante denominada *gestora* e responsável pelo gerenciamento da cozinha acadêmica e do estoque da cozinha. Nesta entrevista, de aproximadamente 1 hora de duração, foi perceptível a falta de informatização no processo de gerenciamento do estoque.

O processo é iniciado no momento em que os professores requisitam suas receitas. A gestora analisa cada receita e prepara a lista de ingredientes, classificando-as por disciplina (dos cursos). Com base na lista de ingredientes, o estoque é verificado e a compra é requisitada via uma solicitação SDCV, através do sistema OBC, a partir do qual o setor de compras da universidade realiza a cotação. A gestora é responsável por aprovar a cotação para que o setor de compras realize, de fato, a compra dos alimentos.

Porém, foi informado que de acordo com normativas da universidade, pedidos ao setor de compras devem ser realizados com 72 horas de antecedência, o que não é sempre possível. Em pedidos emergenciais é comum a gestora realizar as compras fazendo uso de um caixa de reserva da cozinha pedagógica, para que a compra seja processada posteriormente pelo setor de compras.

Além da gestora, apenas os estagiários sob sua direção – 3 pessoas no momento da entrevista supracitada – estão autorizadas a retirarem alimentos do estoque. Porém, o estoque não possui uma estrutura física própria, dificultando o controle de acesso aos produtos do estoque, e concominante a isto, ineficácia no controle do estado de estoque.

Todo o processo de catalogação de pedidos e movimentação de estoque é realizado utilizando-se de um caderno pessoal, no qual a gestora anota todas as alterações. A falta de informatização dificulta a análise e gestão dos alimentos e receitas, resultando em tempo perdido e  aumento de custo por controle ineficiente. Os fornecedores normalmente são cadastrados no sistema OBC, utilizado para pedido de compras com o setor responsável.

### Situação pretendida

Este projeto propõe o desenvolvimento de uma aplicação multi-plataforma para gestão do estoque da cozinha pedagógica do Centro de Gastronomia da Universidad de Joinville e Região.

A aplicação manterá registros de movimentação e quantidade de itens no estoque. Os itens do estoque poderão estar vinculados a receitas salvas na aplicação. Também é necessário o registro de fornecedores, com dados de localização, contatos e histórico de pedidos realizados.

A aplicação fornecerá uma prospecção do estado do estoque, gerando relatórios e informações para manutenção de um nível seguro de itens no estoque. A partir da prospecção, a aplicação poderá fornecer, previamente, listas de pedidos para aprovação dos gestores. Além disso, faz-se necessário que a aplicação realize e informe em tempo real a atualização dos níveis de estoque para cada produto.

A aplicação controlará as datas de validade para cada item, informando antecipadamente aos gestores os itens que poderão vencer antes da utilização.

Além de ser executada em plataforma web no computador, a aplicação pode ser acessada de *smartphones*, utilizando o próprio endereço *web*, ou o aplicativo *mobile*.

### Usuários

Os principais usuários da aplicação serão a equipe de gestão do estoque. Gestores do estoque aprovarão as ordens de compra, fornecerão informações de fornecedores, gerenciamento de receitas e definição de níveis de estoque. Muitas dessas informações, como fornecedores e níveis de estoque serão definidas apenas uma única vez.

Outros membros da equipe serão responsáveis por atualizar a quantidade de itens e movimentação do estoque.

Além dos membros da equipe de gerenciamento de estoque, os professores também poderão utilizar a aplicação, inserindo pedidos de receitas para a gestão aprovar.
