Ação: Tenta autenticar o usuário com os dados inseridos (usuário e senha).

Processo:

Verifica se os campos foram preenchidos.

Consulta o banco de dados para ver se há um usuário correspondente com a senha.

Exibe uma mensagem de sucesso se o login for válido.

Exibe uma mensagem de erro se usuário ou senha estiverem errados.

Cadastro
Ação: Troca para a tela de cadastro de novo usuário.

 Deletar
Ação: Deleta o usuário atual do banco de dados.

Processo:

Verifica se os campos de login foram preenchidos.

Confirma com o usuário se ele realmente deseja deletar.

Checa se o usuário e senha existem no banco.

Se existir, deleta o usuário e mostra uma mensagem de confirmação.

Caso contrário, mostra erro.

 Alterar Senha
Ação: Permite ao usuário alterar a própria senha.

Processo:

Verifica se o login e a senha atual foram preenchidos.

Solicita a nova senha via JOptionPane.

Valida o usuário e atualiza a senha no banco de dados.

 Botões na Tela de Cadastro:
 Cadastrar
Ação: Cadastra um novo usuário no banco de dados.

Processo:

Verifica se os campos foram preenchidos.

Tenta inserir o novo usuário no banco de dados.

Se o usuário já existir (erro 1062), exibe mensagem de erro.

Se o cadastro for bem-sucedido, mostra mensagem de sucesso e volta para a tela de login.

 Voltar ao Login
Ação: Troca a interface de volta para a tela de login.

 Banco de Dados
Nome do banco: meu_banco

Tabela esperada: usuarios

Colunas usadas:

usuario (VARCHAR/UNIQUE)

senha (VARCHAR)
