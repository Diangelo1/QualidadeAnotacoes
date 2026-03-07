
1° Cenário: Criar Conta (Create)

Dado que estou na tela de criação de conta, E adiciono minhas informações de <email>, <nome>, <telefone> e <senha>, Quando clico no botão de <Criar Conta> então o sistema irá criar a conta e redirecionar a tela de login.

2° Cenário: Visualizar Conta (Read)

Dado que estou autenticado no sistema, e acesso a página de perfil, quando carregar a página ele exibe minhas informações de <email>, <nome> e <telefone>.

3° Cenário: Atualizar Conta (Update)

Dado que estou autenticado no sistema
E estou na página de edição de perfil
Quando altero meu <telefone>
E clico no botão "Salvar alterações"
Então o sistema deve atualizar minhas informações
E exibir uma mensagem de sucesso.

4° Cenário: Excluir Conta (Delete)

Dado que estou autenticado no sistema
E estou na página de configurações da conta
Quando clico no botão "Excluir conta"
E confirmo a exclusão
Então o sistema deve remover minha conta
E redirecionar para a página inicial.