# Roteiro de Teste para Operações CRUD

Esse aqui é um guia criado por mim com auxílio do chat gpt de alguns pontos a serem lembrados sempre que for criar um crud:


## I. Testes de Criação (Create):

### Teste de Inserção Bem-sucedida:

Descrição: Teste se você pode criar um novo registro com sucesso.
Passos:
Acesse a página de criação.
Preencha todos os campos necessários com dados válidos.
Clique no botão "Salvar" ou equivalente.
Verifique se o registro é criado com sucesso e se os dados inseridos estão corretos.

### Teste de Validação:

Descrição: Teste como o sistema lida com dados inválidos.
Passos:
Acesse a página de criação.
Deixe campos obrigatórios em branco ou insira dados inválidos.
Tente salvar o registro.
Verifique se o sistema exibe mensagens de erro apropriadas e impede a criação do registro.


## II. Testes de Leitura (Read):

###Teste de Recuperação de Registros:

Descrição: Teste se você pode recuperar registros existentes com sucesso.
Passos:
Acesse a página de leitura.
Realize uma busca por registros existentes.
Verifique se os registros são exibidos corretamente.

###Teste de Busca/Filtro:

Descrição: Teste a capacidade de buscar registros com base em critérios específicos.
Passos:
Acesse a página de leitura.
Aplique filtros de busca com critérios específicos.
Verifique se os resultados correspondem aos critérios de busca.

## III. Testes de Atualização (Update):

### Teste de Atualização Bem-sucedida:

Descrição: Teste se você pode atualizar um registro existente com sucesso.
Passos:
Acesse a página de atualização.
Selecione um registro existente.
Atualize os campos necessários.
Clique no botão "Salvar" ou equivalente.
Verifique se o registro é atualizado corretamente.

### Teste de Validação:

Descrição: Teste como o sistema lida com atualizações inválidas.
Passos:
Acesse a página de atualização.
Selecione um registro existente.
Tente atualizar com dados inválidos.
Verifique se o sistema exibe mensagens de erro apropriadas e impede a atualização inválida.


## IV. Testes de Exclusão (Delete):

### Teste de Exclusão Bem-sucedida:

Descrição: Teste se você pode excluir um registro existente com sucesso.
Passos:
Acesse a página de exclusão.
Selecione um registro existente.
Confirme a exclusão.
Verifique se o registro é excluído corretamente.

### Teste de Exclusão de Registro Inexistente:

Descrição: Teste como o sistema lida com tentativas de exclusão de registros que não existem.
Passos:
Acesse a página de exclusão.
Tente excluir um registro que não existe.
Verifique se o sistema lida corretamente com a situação.


## V. Testes de Integração:

### Teste de Integração entre Operações CRUD:

Descrição: Teste como as operações CRUD funcionam juntas.
Passos:
Crie um registro.
Leia o registro.
Atualize o registro.
Exclua o registro.
Verifique se todas as operações funcionam corretamente em conjunto.

## VI. Testes de Desempenho:

### Teste de Carga:

Descrição: Avalie como o sistema se comporta sob carga.
Passos:
Crie, leia, atualize e exclua um grande número de registros em um curto período.
Meça o desempenho e verifique se está dentro dos limites aceitáveis.

### Teste de Desempenho:

Descrição: Meça o tempo que as operações CRUD levam para serem executadas.
Passos:
Cronometre o tempo necessário para realizar operações CRUD em registros típicos.
Verifique se as operações são executadas dentro dos limites de desempenho aceitáveis.
