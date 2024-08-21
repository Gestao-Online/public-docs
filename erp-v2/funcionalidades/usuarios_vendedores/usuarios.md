# 👤 Usuários

Aqui você tem a visão de todos os usuários cadastrados na plataforma, podendo fazer um novo cadastro, alterar e até excluir um usuário cadastrado.

{% hint style="danger" %}
**Atenção:** As informações aparecem conforme o que foi autorizado a ser exibido pelo administrador, por isso algumas informações podem não aparecer para você.
{% endhint %}

{% hint style="warning" %}
**Filtros:** Caso queira mais informações sobre como utilizar os filtros [**`clique aqui`**](/erp-v2/primeiro_acesso/filtros.md) para acessar a explicação sobre cada parte desta função.
{% endhint %}

![](/erp-v2/assets/funcionalidades/modulo_usuario.gif)

<br>

Nesta tela está um menu ao lado direito com as seguintes funções:

- <img src="/erp-v2/assets/icon_notificacao.png" alt="" data-size="line"> Enviar notificações para usuários;
- <img src="/erp-v2/assets/icon_exibir.png" alt="" data-size="line"> Mostrar/Esconder informações;
- <img src="/erp-v2/assets/icon_imprimir.png" alt="" data-size="line"> Imprimir página;
- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_filtro.png" alt="" data-size="line"> Filtro;
- <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> Adicionar usuário.

![](/erp-v2/assets/funcionalidades/menu_guia_usuarios.png)

<br>

{% hint style="warning" %}
**Mouse:** Caso queira informações sobre como utilizar as funções do botão direito do mouse [**`clique aqui`**](/erp-v2/primeiro_acesso/atalhos_internos#menu-botao-direito-do-mouse) para acessar a explicação.
{% endhint %}

## Adicionar novo usuário

No menu ao lado direito da tela, tem o botão <img src="/erp-v2/assets/icon_add.png" alt="" data-size="line"> adicionar novo usuário, confira abaixo o procedimento para fazer o cadastro corretamente:

![](/erp-v2/assets/funcionalidades/menu_guia_ususarios_menu_add_user.png)

<br>

Ao clicar neste botão, você será direcionado para esta página, para fazer o preenchimento dos dados do novo usuário:

![](/erp-v2/assets/funcionalidades/menu_guia_usuario_add_user.png)

<br>

Ao lado direito da tela, você pode ver a `barra de ferramentas` (menu na cor cinza, no canto superior direito da tela). Vejamos abaixo para entender melhor cada opção:

- <img src="/erp-v2/assets/icon_atualizar.png" alt="" data-size="line"> Atualizar página;
- <img src="/erp-v2/assets/icon_duplicar.png" alt="" data-size="line"> Duplicar Item;
- <img src="/erp-v2/assets/icon_salvar.png" alt="" data-size="line"> Salvar;
- <img src="/erp-v2/assets/icon_voltar.png" alt="" data-size="line"> Voltar;

![](/erp-v2/assets/funcionalidades/menu_guia_usuario_add_user_menu.png)

<br>

Olhando para a aba **`Geral`**, por padrão, quando você for criar uma conta é exigido o perfil e e-mail. Agora os outros campos para preenchimento podem deixar para o usuário quando confirmar a conta, listamos os campos abaixo:

- **Nome** (Nome completo do usuário, podendo preencher depois);
- **Nome de usuário** (É usado para login na plataforma, podendo ser um nome/código/CPF);
- **Alterar senha** (Para mais informações [clique aqui](/erp-v2/minhas_preferencias/alt_minha_senha.md));
- **Status** (Aqui você define o status do usuário, sendo ativado, desativado ou aguardando registro);
- **Perfil** (Item obrigatório, aqui define que tipo de autorização que terá na plataforma);
- **Unidade** (Nome do local/setor de trabalho);
- **E-mail** (Item obrigatório, a conta está vinculada exclusivamente ao e-mail, não podendo ser modificado depois);
- **Telefone**;
- **Documento** (Pode ser um RG/CPF/CNH, o usuário pode preencher depois);
- **CEP** (Após inserir o CEP os demais dados serão preenchidos automaticamente);

<br>

![](/erp-v2/assets/funcionalidades/menu_guia_usuario_add_user_itens.png)

<br>

Uma breve informação, de forma bem resumida sobre os tipos de Perfis (com as regras padrões):


- **Usuário:**
-> Parceiros/Clientes (todos da unidade/projeto em que trabalha)
-> Vendas (somente as criadas por ele)
-> Agendamento/Atividades (todas da unidade em que trabalha)
-> Dashboards/Relatórios (somente das próprias vendas)

- **Coordenador:**
-> Parceiros/Clientes (todos da unidade/projeto em que trabalha)
-> Vendas (todas da unidade em que trabalha)
-> Agendamento/Atividades (todas da unidade em que trabalha)
-> Pode cadastrar usuários na unidade que trabalha
-> Dashboards/Relatórios (somente da unidade que trabalha)

- **Gerente/Administrador:**
-> Parceiros/Clientes (Acesso total)
-> Vendas (Acesso total)
-> Agendamento/Atividades (Acesso total)
-> Dashboards/Relatórios (Acesso total)
-> Pode realizar alterações financeiro (Baixa/Estorno)
-> Cadastro de produtos
-> Cadastro de tabela de preço das unidades/indicadores.

- **Superadministrador:** (Mesmo acesso do administrador, mas com permissões de parâmetrizações)

{% hint style="info" %}
**Permissões por usuário:** 

As principais ações no sistema, permitem fazer liberações por usuário, combinado as permissões gerais nos perfis.

Alguns exemplos de permissões por usuário:
-> Estorno cartão de crédito 
-> Regras de comissão/custo 
-> Perfil de desconto

Essas configurações sāo feitas em cada tela/funçāo, atribuindo diretamente o usuário a aquela permissāo/regra. Para mais informações `🔒Permissões, restrições/exceções` [**`clique aqui`**](/erp-v2/primeiro_acesso/permissoes_restricoes_excecoes) 
{% endhint %}

Após finalizar o preenchimento, você clica em **`Salvar`** e o registro do usuário será salvo e enviado para o e-mail cadastrado, uma mensagem para finalizar o registro:

![](/erp-v2/assets/funcionalidades/menu_guia_usuarios_salvar.gif)


## Enviar notificaçāo interna para os usuários

Ao clicar no primeiro item do menu vamos para o envio de notificação aos usuários, o preenchimento é bem simples e intuitivo.

![](/erp-v2/assets/funcionalidades/menu_guia_usuarios_notificacao.png)

<br>

Você precisa definir primeiro nível de criticidade da notificação, das opções disponíveis têm:

- Mínimo;
- Baixo;
- Normal;
- Alto;
- Urgente.

![](/erp-v2/assets/funcionalidades/menu_guia_usuarios_notificacao_criticidade.png)

<br>

Após a definição do nível, seguimos para o perfil de usuário que irá receber esta notificação que você está gerando, são os tipos:

- Todos;
- Usuário;
- Coordenador;
- Gerente;
- Administrador;
- Super administrador.


![](/erp-v2/assets/funcionalidades/menu_guia_usuarios_notificacao_perfil.png)

<br>

### Enviando notificação

Após definido o tipo de usuário, agora vamos para a mensagem, deixamos um editor de texto com algumas funções para você poder escrever a sua notificação:

- <img src="/erp-v2/assets/funcionalidades/icon_tamanho_texto.png" alt="" data-size="line"> Escolha de tamanho do texto;
- <img src="/erp-v2/assets/funcionalidades/icon_negrito.png" alt="" data-size="line"> Negrito;
- <img src="/erp-v2/assets/funcionalidades/icon_italico.png" alt="" data-size="line"> Itálico;
- <img src="/erp-v2/assets/funcionalidades/icon_sublinhado.png" alt="" data-size="line"> Sublinhado
- <img src="/erp-v2/assets/funcionalidades/icon_hiperlink.png" alt="" data-size="line"> Hiperlink;
- <img src="/erp-v2/assets/funcionalidades/icon_lista_ordenada.png" alt="" data-size="line"> Lista ordenada;
- <img src="/erp-v2/assets/funcionalidades/icon_lista_nao_ordenada.png" alt="" data-size="line"> Lista não ordenada;
- <img src="/erp-v2/assets/funcionalidades/icon_limpar_formatacao.png" alt="" data-size="line"> Limpar formatação. 

Agora basta clicar em `Enviar notificaçāo`

![](/erp-v2/assets/funcionalidades/menu_guia_usuarios_notificacao_enviada.gif)

<br>
