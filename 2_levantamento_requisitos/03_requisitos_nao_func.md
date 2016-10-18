## Requisitos não funcionais

Requisitos *não funcionais* descrevem limites para a solução, sendo também chamados de requisitos de qualidade. Podem ser classificados como requisitos de performance, requisitos de manutenabilidade, requisitos de segurança, requisitos de confiabilidade, requisitos de interoperabilidade e ainda muitos outros tipos de requisitos de software.

Para este projeto, os requisitos *não funcionais* descritos são:

### Usabilidade

### Performance

- A aplicação deve ser leve, não provocando atrasos - *legs* - na utilização.
- Todas as funções da aplicação devem estar disponíveis ao usuário quando a aplicação está rodando.
- Operações de análise e cálculo devem ser executadas sem causar impacto negativo na performance da aplicação. Estas operações devem rodar em processos separados.

### Confiabilidade

- A aplicação deve fornecer informações precisas sobre o estado do estoque ao usuário de forma contínua.
- A aplicação deve adicionar quaisquer receitas, ingredientes e fornecedores informados pelo usuário, fornecendos estimativas e status do estoque de forma relevante de acordo com o novo item.
- A aplicação só deve permitir a visualização e manipulação de dados por usuários devidamente credenciados.
- A aplicação deve fornecer atualizações em relação a processos abertos, e em caso de falhas/erros, deve fornecer informações relevantes sobre o problema.
- A aplicação não deve, em momento algum, adicionar, remover ou alterar informações no banco de dados em caso de falha durante um processo.

### Interoperabilidade

- A aplicação deve ser executada em servidores próprios ou servidores na *nuvem*, sem grandes diferenças de configuração.
- A aplicação deve ser adaptável, promovendo fácil instalação e utilização de módulos adicionais e/ou *plugins*.
- A aplicação deve ser acessada de qualquer máquina ou sistema operacional.
- A aplicação deve produzir os mesmos resultados independente do navegador utilizado, quando este está na lista dos navegadores suportados.

### Requisitos legais

- O usuário deve aceitar os Termos e Condições de Uso antes de utilizar a aplicação.
- A aplicação deve estar licenciada para a utilização do cliente.
